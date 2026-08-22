---
author: Chris Short
date: '2026-08-23'
description: "Go 1.27 finally ships generic methods and encoding/json/v2, GitHub's CTO puts numbers behind a 7 hour 47 minute outage, a peer-reviewed look at 443,000 Backblaze drives says the vendor rankings you have been quoting were never like-for-like, and engineering leaders keep walking out the door."
draft: false
slug: '323'
title: "DevOps'ish 323: Go 1.27 lands generic methods, GitHub shows its work after the August 17 outage, and more"
---

{{< subscribe >}}

[**Go 1.27 is released**](https://go.dev/blog/go1.27) (5 minute read)

Shipped 19 August 2026, and the language changes are the headline. Methods can now take type parameters, which closes a gap people have been filing issues about since generics landed in 1.18. Struct literals can initialize fields in nested and embedded structs directly, and type inference now works in composite literals, type conversions, and channel sends. The standard library additions matter just as much: `encoding/json/v2` is here with `encoding/json` rebuilt on top of it, `encoding/json/jsontext` handles low-level streaming, `crypto/mldsa` brings FIPS 204 post-quantum signatures into `crypto/x509` and `crypto/tls`, and there is finally a `uuid` package so you can delete a dependency. Size-specialized allocation cuts the cost of small-object allocation by up to 30%. The `goroutineleak` profile in `runtime/pprof` is generally available now, which is the sort of thing you do not need until the night you very badly need it.

[**The August 17 outage, and the work ahead**](https://github.blog/news-insights/company-news/the-august-17-outage-and-the-work-ahead/) (4 minute read)

GitHub CTO Vlad Fedorov on a 7-hour, 47-minute outage that took down github.com, authentication, Actions, the APIs, pull requests, issues, and Copilot. A critical infrastructure component in the Central US data center failed to scale under record traffic; capacity pressure cascaded, and authentication started failing. Copilot recovered last because a client-side retry loop pushed more traffic into a system that was trying to come back. Credit where it is due: this post has actual numbers instead of vibes. Over 3 million CPU cores and 120 petabytes of high-speed storage added, Azure going from 12% of platform load in May to 58% now and carrying half of all Git operations, with monthly commits up from 1.4 billion in April to 2.9 billion in August, and Actions runs at 115.4 million. This was also the second significant August incident after the Actions failure on the 6th.

[**How Kubernetes probes work**](https://ngrok.com/blog/probes) (18 minute read)

Four thousand words on startup, readiness, and liveness probes, and worth every one of them. The defaults get spelled out plainly: failureThreshold of 3, successThreshold of 1, a 30-second termination grace period, CrashLoopBackOff starting at 10 seconds and doubling to a 5-minute ceiling. The reason to send this to your team, though, is the bug the author found and reproduced on k3s, minikube, and kind: liveness probes firing before the startup probe has succeeded, introduced in v1.35.0. That is the exact failure mode that makes a slow-starting service restart forever while everyone stares at the dashboard.

[**Headed for the Exit: the Great Engineering Leader Career Break**](https://newsletter.pragmaticengineer.com/p/the-great-engineering-leader-career-break) (14 minute read)

Gergely Orosz talked to roughly 20 CTOs, VPs of Engineering, and Heads of Engineering, and six in ten said they are leaving or thinking hard about it. The reasons are less about AI than about what AI gave people cover to demand: unrealistic transformation timelines, 20% to 50% cost cuts, and low-quality code shipped to production with nobody holding the bag. The equity math is brutal and specific, with one CTO holding 2% at a company that raised $110M on a 2x preference, meaning a $210M exit before the stock is worth anything. Add flattened org charts, wider reporting ratios, and teams of one or two engineers per project, and there are simply fewer chairs. Paywalled partway through, and still worth the read for the part you can see.

[**Fifteen Tics**](https://randsinrepose.com/archives/fifteen-tics/) (5 minute read)

Michael Lopp catalogs fifteen of his own behavioral quirks, from interruption sensitivity to rage at small broken things to lying awake over an unresolved problem, and pairs each with what he does to keep it from landing on other people. The framing is the useful part. A manager readme works better as honest self-reflection than as a list of rules for everyone else to follow. "Good leaders don't lead by mandate; they lead by example. You see, with your eyeballs, how your leaders act, and you decide, with your brain, does this work for me?"

[**Docker Desktop Gets a Hypervisor of its Own**](https://cloudnativenow.com/features/docker-desktop-gets-a-hypervisor-of-its-own/) (3 minute read)

Docker VMM is a unified virtualization layer, in beta with Docker Desktop v4.86 on Windows and macOS, with Linux general availability targeted for October 2026. It replaces the pile Docker has been standing on: libkrun on Apple, Hyper-V and WSL on Windows, KVM and QEMU on Linux. The pitch is faster startup and recovery, smoother I/O, and better memory behavior when containers sit idle, and the tech got its first real workout in Docker Sandboxes for AI agents. Owning the hypervisor means one code path to fix instead of three to work around.

[**Peer-reviewed study of 443,000 Backblaze hard drives ranks HGST most reliable and Toshiba the least**](https://www.tomshardware.com/pc-components/hdds/peer-reviewed-study-of-443000-backblaze-drivers-ranks-hgst-most-reliable-and-toshiba-least) (4 minute read)

Christoph Siemroth at Essex and Yeomyung Park at Sungkyunkwan ran Backblaze's public data through IEEE Transactions on Cloud Computing: 443,156 enterprise drives, more than 1.66 million drive-years from 2013 through Q2 2025, controlling for age, capacity, form factor, and temperature. Normalized against Seagate at 100%, HGST comes in around 41% and WD around 52%, with Toshiba at 107%. The methodological point is the real story. Backblaze's own quarterly reports compare whatever drives happen to be in the fleet, which stacks old drives against young ones, and everyone has been quoting those numbers for a decade. Two other findings to file away: every additional degree Celsius of average drive temperature raises failure rates by 2.1%, and Toshiba's failure rate more than quadruples past 60 months in a way nobody else's does. The catch on the winner is that WD bought HGST in 2012 and eventually retired the brand.

[**We rebuilt the Linux microVM stack on Apple Silicon**](https://encore.dev/blog/firecracker-apple-silicon) (13 minute read)

Encore has run every build in Firecracker microVMs since mid 2022, which works fine until you want it on a laptop, because Firecracker needs `/dev/kvm` and macOS doesn't have one. So they wrote crackling, one microVM API with a Firecracker backend on Linux and Apple's Virtualization.framework on macOS. The guest agent talks over AF_VSOCK with an eight-byte header framing protocol, kernel decompression handles the EFI zboot gzip format, and the root filesystem gets built as newc format cpio archives in pure Rust. The honest limitation is worth knowing before you plan around it: Apple will not let third parties snapshot a VM, since that needs the `com.apple.private.virtualization` entitlement, and the validator lies and says it is supported.

[**Broadcom seeks more than $60 billion in latest AI debt deal, Bloomberg News reports**](https://www.reuters.com/technology/broadcom-seeks-more-than-60-billion-latest-ai-debt-deal-bloomberg-news-reports-2026-08-20/) (2 minute read)

Reuters, relaying Bloomberg: Broadcom is in talks with lenders to raise more than $60 billion for an AI chip financing deal benefiting Anthropic and others, structured through a special purpose vehicle, with Blackstone and Apollo in discussions to join. It builds on the June partnership among the three, where Broadcom backstopped most of the debt so the senior tranches could get investment-grade ratings and cheaper money. That earlier deal raised $35 billion for 1 gigawatt of compute; the stated ambition is more than 20 gigawatts by 2028. Talks are ongoing, terms may change, and everyone declined to comment. Keep an eye on this shape of deal, because a lot of leverage rides on hyperscaler CAPEX staying where it is.

[**Intel may refresh Raptor Lake for a third time as high DDR5 prices push buyers toward older hardware**](https://www.techspot.com/news/113495-intel-may-refresh-raptor-lake-third-time-ddr5.html) (3 minute read)

AI data center demand has driven DDR5 prices high enough that a 2022 CPU looks like a reasonable purchase again. Intel VP Robert Hallock says the company intends to keep Raptor Lake around and stabilize supply of 10nm parts on LGA 1700, and rumor puts a third refresh, "Raptor Lake Next," in the first half of 2027. At least two motherboard vendors are ramping production of aging LGA 1700 boards. The appeal is that Raptor Lake takes DDR4 or DDR5, so you can upgrade without rebuying memory at current prices. AMD re-released the Ryzen 7 5800X3D, and Nvidia brought back the 12GB RTX 3060, both also from 2022. The memory market is now bending the consumer parts market around it.

[**tonedefdev/opendepot**](https://github.com/tonedefdev/opendepot) - Apache-2.0 - A Kubernetes native OpenTofu/Terraform registry. Implements both the Module Registry Protocol and the Provider Registry Protocol as CRDs and controllers, deploys via Helm, and gates access with GitHub App auth, tokens, and Kubernetes RBAC. Works with any OpenTofu version and Terraform v1.2 and later.

[**kepano/defuddle**](https://github.com/kepano/defuddle) - MIT - Get the main content of any page as Markdown. More forgiving than Readability, removes fewer uncertain elements, uses mobile styling as a signal for what is junk, and returns standardized footnotes, math, and code blocks along with schema.org metadata. Ships as a browser core bundle, a full bundle with math and Markdown conversion, a Node bundle for JSDOM, linkedom, or happy-dom, and a CLI.

[**bikeshaving/termdom**](https://github.com/bikeshaving/termdom) - MIT - Build terminal apps with HTML, CSS and DOM. Renders real DOM nodes to the terminal on Node, Bun, and Deno with no native components, including cascading stylesheets mapped to ANSI colors, the box model, flexbox, table layout, CJK and emoji width handling, MutationObserver and ResizeObserver, form controls, scrolling, text selection, and web components with shadow DOM.

{{< sponsor >}}
