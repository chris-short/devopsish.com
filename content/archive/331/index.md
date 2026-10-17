---
author: Chris Short
date: '2026-10-18'
description: "Linus hacks the kernel with Claude Code, hackers cook French supermarket fridges, Docker Hub fixes a token handoff bug, and Kubernetes Steering Election"
draft: false
slug: '331'
title: "DevOps'ish 331: Linus codes with Claude, hackers cook French fridges, Docker Hub's token mixup, and more"
---

{{< subscribe >}}

[**One CI runner platform for every OS and architecture**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-10-18) (SPONSOR)

Run Linux x64, Linux ARM64, macOS, and Windows jobs from one place, on one bill. Build ARM64 images natively without QEMU emulation, and test on every platform you ship. WarpBuild runners are twice as fast at half the cost of GitHub-hosted runners. Try it with $50 in free credits using code START50.

[**Announcing the 2026 Steering Committee Election Results**](https://www.kubernetes.dev/blog/2026/10/16/steering-committee-results-2026/) (1 minute read)

Three of the seven Kubernetes Steering Committee seats were up this year. Michael McCune (Red Hat), Janet Kuo (Google), and Priyanka Saggu (SUSE) were elected to two-year terms that start now. They join Kat Cosgrove, Paco Xu, Rita Zhang, and Maciej Szulik. Congrats to all of them, and thanks to everyone who ran and voted. Steering meetings are open on the first Wednesday of every month at 8 am PT if you want to see how the sausage gets governed.

[**Linus Torvalds Working On A Hefty Linux Kernel Improvement With Claude Code**](https://www.phoronix.com/news/Linus-Torvalds-Claude-Code) (2 minute read)

A new branch showed up in torvalds/linux.git called *noref-filemap-read-with-llm*. It reads from the page cache without taking folio references, which fixes contention when lots of threads do small reads of the same file. Linus is upfront about it: Claude Code produced the code, test programs, review, and first draft of the cover letter "under my direction," and he ran the measurements on his own machine. The benchmark gains are big. Whether it lands in the 7.4 merge window is the next thing to watch.

[**Rolling Release Distros Superior To LTS Distros In The Patch-Heavy GenAI Era?**](https://www.phoronix.com/news/Rolling-Releases-GenAI-Era) (2 minute read)

At Linux Plumbers in Prague, Qualcomm's Khem Raj asked whether LTS distributions still make sense when AI coding agents keep cranking up the patch flow. His case for rolling releases: less backporting, less drift from upstream, faster security fixes. Certification and qualification are the obvious counterarguments, and Phoronix says so. Having lived on both sides of a backport queue, I don't think enterprises are dumping LTS anytime soon, but somebody will have to pay for all that backporting.

[**AI-Found Linux Kernel Flaw Gives Local Users Root, and Can Break a Guest Out to the Host**](https://thehackernews.com/2026/10/ai-found-linux-kernel-flaw-gives-local.html) (4 minute read)

Vghost (CVE-2026-74580) is a stale cache bug in the kernel's vhost subsystem that gives a local user deterministic kernel read/write and root. No heap grooming, no racing. It took two reasonable changes to create it, one in 2017 (4.11) and one in 2020 (5.9), and it sat there for about nine years. Tencent Zhuque Lab reproduced it on Ubuntu 26.04, RHEL 9.8, Amazon Linux 2023, Azure Linux 3.0, and Oracle Linux 10.2. On four of those, */dev/vhost-net* was world-readable at 0666. In one virtual IOMMU setup, an untrusted guest can also write into the host's QEMU process. Kernels from 4.11 to 7.2-rc4 are affected; the fix is commit de845981da67, and you should check your device node permissions.

[**Docker Hub Security Advisory: CVE-2026-105445**](https://www.docker.com/blog/docker-hub-security-advisory-cve-2026-105445/) (5 minute read)

Starting August 26, 2024, converting a Docker Hub personal account into an organization handed that account's personal access tokens to whoever was named the new owner. Nobody rotated the secrets, and nobody asked the owner. So an attacker could make an account, mint a PAT, convert it, name you as owner, and keep a token that now acted as you at the registry. Push, pull, delete. Docker shipped a fix four hours after the report and deactivated every transferred PAT on October 8. They say the 304,000 pushes made with transferred tokens all went to the converted org or the new owner's own repos, and they found no tampering. It's a good write-up. Review your PATs anyway, and switch automation to organization access tokens.

[**Canonical Hit by Second DDoS Attack in 2026, Public Websites Disrupted**](https://securityaffairs.com/200832/security/canonical-hit-by-second-ddos-attack-in-2026.html) (2 minute read)

ubuntu.com, canonical.com, the Ubuntu blog, the developer portal, and the security advisory pages were intermittent for more than four hours. The Ubuntu Security API and Livepatch took hits too. Nobody has claimed it, and it's the second time this year.

[**Fridges in French supermarkets hit by cyber attack**](https://www.bbc.com/news/articles/crq5nzxv9q4yo) (3 minute read)

Someone accessed Danfoss's remote refrigeration management software and told supermarket fridges and freezers to heat up and stay hot. Intermarché says its units hit 50C for six hours overnight. Roughly 400 stores across Intermarché, Netto, Coopérative U, Carrefour, Monoprix, and E.Leclerc were affected, with millions of Euros in food thrown out. Danfoss says the affected units were older models whose security software couldn't be updated. Your patch backlog is a food safety problem now.

[**AI is less regulated than milk, Microsoft president says**](https://www.bbc.com/news/articles/c6rmy7zmvx3lo) (3 minute read)

Brad Smith told the BBC's Big Boss Interview podcast that your washing machine and your milk carton face more safety rules than AI does. He wants kill switches, mandatory incident reports, a legal duty to tell victims when an AI agent goes rogue, and independent evaluators signing off before release. He also thinks the UK should lead, thanks to its AI Security Institute. That puts him at odds with his own president, who wants the industry to regulate itself. The milk line is going to stick.

[**Redis by proxy: Percona targets the last major hurdle to Valkey adoption**](https://thenewstack.io/valkey-proxy-redis-percona/) (4 minute read)

Lots of apps were written assuming a single Redis instance, and moving them to a Valkey Cluster means teaching them about nodes and routing. Commercial Redis and cloud services hide that behind a proxy. Self-hosted Valkey hasn't had a good open source one. Percona's Kyle Davis says Envoy doesn't fully understand the protocol. Valkey-proxy is Percona's answer, built in-house, headed for the Valkey project, and set to go public this month. If you run your own on-prem cache tier, this is the one to watch.

[**Topgolf saved over $11.3 million after leaving VMware**](https://arstechnica.com/information-technology/2026/10/topgolf-saved-over-11-3-million-after-leaving-vmware/) (5 minute read)

Broadcom's pricing would have raised Topgolf's VMware costs 400%. So a shop that sat on VMware customer councils moved 12,000 VMs to VergeIO's VergeOS and says it has cut over $11.3 million in infrastructure costs. Twenty venues are still on VxRail and should be off VMware by mid-December. VergeIO's CMO says most of its roughly 70 new customers a quarter come from VMware. That's a vendor talking, sure, but the Broadcom exodus stories keep coming.

[**Why WebMCP matters**](https://blog.yoav.ws/posts/why_webmcp_matters/) (7 minute read)

Yoav Weiss shipped Shopify's storefront WebMCP tools and explains why he bothered. WebMCP lets a site register JavaScript tools with schemas so an agent calls them directly instead of looking at screenshots and fumbling through the DOM. He argues co-browsing, where the user can grab the wheel back at any time, is the only agent model where the web stays the web. Shopify's Checkout team measured 2.7x faster, 58% cheaper, and 60/60 successes versus 56/60 with browser automation. The open questions he lists, like who gets to register tools and how to protect users from malicious ones, are the part I'd read twice.

[**38 things we've learned about building AI products**](https://newsletter.posthog.com/p/38-things-weve-learned-about-building) (7 minute read)

PostHog has built ten AI products in four years; here's the list. My favorite stat: five times as many people use their MCP server daily as PostHog AI, therefore maybe build for AI before you build AI. Their install wizard does two hours of work in about eight minutes, and people who use it convert to paid 5x more often. They also suggest watching for customers rebuilding your product with AI, and writing down how an AI-native competitor beats you, then funding that version yourself. Practical and refreshingly free of hype.

[**oxynote/oxynote**](https://github.com/oxynote/oxynote) - Apache-2.0 - An open source technical wiki connected to the systems it describes.

[**portworx/kubevirt-benchmark**](https://github.com/portworx/kubevirt-benchmark) - Apache-2.0 - A vendor-neutral performance testing toolkit for KubeVirt virtual machines on OpenShift or any Kubernetes distribution running KubeVirt.

{{< sponsor >}}
