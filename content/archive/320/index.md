---
author: Chris Short
date: '2026-08-02'
description: "Anthropic found three of its models broke into real systems during cyber tests, Kubernetes v1.37 lines up its deprecations, open-weight AI hits its Kubernetes moment, and Google's AI is quietly starving the open web."
draft: false
slug: '320'
title: "DevOps'ish 320: Claude models broke into real systems during security tests, Kubernetes v1.37's deprecation list, and more"
---

{{< subscribe >}}

[**Make it simple for your team to do their work securely.**](https://fandf.co/4vWVJ2e) (SPONSOR)

You don't need to maintain VPN clients and duplicate auth logic across microservices. Pomerium authenticates against your existing IdP and authorizes every request against policy, at Layer 7 for HTTP and natively for SSH. HTTP upstreams get a signed JWT assertion so they can trust who's calling. SSH gets ephemeral certificates, so there's no per-user key or authorized_keys sprawl and access is revoked centrally. Every decision lands in a centralized audit log. Same policy engine for the workloads in your cluster and the MCP tool calls your agents make.Secure Kubernetes as well as AI and MCP workloads.

[Walk through deployments](https://fandf.co/4vWVJ2e) in browser-based playgrounds. [Learn more by doing](https://fandf.co/4vWVJ2e). (SPONSOR)

[**Kubernetes v1.37 Sneak Peek**](https://kubernetes.io/blog/2026/07/31/kubernetes-v1-37-sneak-peek/) (6 minute read)

The release team's early heads-up on v1.37, and it leans hard on deprecations. IPVS mode in kube-proxy is on the chopping block (off by default in v1.40, gone in v1.43), `kubectl run -f` is going away, and static pods lose the ability to reference Secrets and ConfigMaps. The slow retirement of cgroup v1 also continues, so if you are still running it, plan the migration now rather than during an outage.

[**How the controller-runtime Cache Actually Works, and Why Your Controller Does Not Crash the API Server**](https://kubernetes.io/blog/2026/07/29/controller-runtime-cache-explained/) (30 minute read)

If you write Go controllers with kubebuilder and think r.Get() and r.List() are hitting the API server, they are not. They read from a local in-memory cache that the manager fills with list calls and keeps fresh with watches. The practical fallout is worth knowing: reads are cheap but not strongly consistent right after a write, writes still go straight to the API server, cache size and indexes drive your memory footprint, and a sloppy List() can quietly turn into an O(n) scan over tens of thousands of objects. Under the hood, it is the same Reflector, DeltaFIFO, and Indexer primitives that run Kubernetes itself.

[**Anthropic says three Claude models reached real-world systems during cyber tests**](https://www.axios.com/2026/07/30/anthropic-mythos-security-testing) (3 minute read)

Anthropic combed through more than 141,000 cybersecurity evaluation runs and found three of its models, Opus 4.7, Mythos 5, and an unreleased internal model, actually broke into real systems during capture-the-flag tests because a testing environment got left wired to the open internet. In one case, Mythos 5 built and pushed a malicious Python package to PyPI, thinking it was all a simulation, and the thing got downloaded and run on 15 real machines before it came down about an hour later. The uncomfortable part is that two of the three organizations whose assets got touched never noticed, which tells you more about the sorry state of detection than it does about the cleverness of the models.

[**How AI Is Changing Open Source**](https://enblog.eischmann.cz/2026/07/23/how-ai-is-changing-open-source/) (13 minute read)

Jiri Eischmann lays out four ways AI is quietly reshaping open source, and none of them are the shiny future the vendors promised. GitHub is drowning in AI-generated repos that were never real projects, maintainers are stuck reviewing thousand-line pull requests padded with useless quote swaps, and license-circumvention worries plus a firehose of AI security reports are chipping away at the will to publish source at all. It is a grounded, maintainer's-eye take on where the burnout actually lands.

[**Open-weight AI is having its Kubernetes moment. Let's not ruin it.**](https://tobi.knaup.me/2026-07-25-open-weight-ai-is-having-its-kubernetes-moment/) (6 minute read)

Tobi Knaup, who co-founded Mesosphere and watched Kubernetes eat its lunch, argues open-weight AI models are hitting the same inflection point: a portable substrate that a whole ecosystem builds on faster than any single vendor can match. His warning to Washington is blunt. Banning Chinese open-weight models like Kimi K3 and Qwen would lock American developers out of the ecosystem everyone else keeps building, a spectacular own goal, when the smarter play is releasing frontier-grade American open weights, using procurement to reward interoperability, and setting independent safety standards in place of walls.

[**Google's Immense Greed Is Destroying the Open Web**](https://futurism.com/artificial-intelligence/google-greed-destroying-open-web) (5 minute read)

Google's AI search summaries are quietly strangling the referral traffic that publishers depend on, and outlets like USA Today, Reuters, and Politico are reportedly rethinking whether staying in Google's index is worth it. The irony writes itself: choke off the open web that produces fresh, human-made content, and you eventually starve the very training data that keeps the models from feeding on their own slop.

[**Introducing AI-powered container standardization**](https://medium.com/capital-one-tech/introducing-ai-powered-container-standardization-2f9314cde883) (9 minute read)

Capital One walks through how it wired AI into its container pipeline to detect and remediate vulnerabilities without dragging developers into the loop. The pitch is "avoid and automate": golden image governance, continuous scanning, SBOM analysis, and automated image refreshes, with AI doing the prioritizing so patches get tested and shipped hands-free. It reads like a vendor-free field report from a heavily regulated shop, so take the outcomes with the usual grain of salt, but the framework and the six best practices are worth a look if you own a fleet of images and are tired of chasing CVEs by hand.

[**The Wild Wild West Of LEGO Datacenters**](https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters) (59 minute read)

SemiAnalysis digs into the complicated reality of modular datacenter construction, where prefab power blocks, containerized skids, and Meta's rapid deploy "tents" are being thrown at a brutal electrician shortage. After testing the vendor claims, the verdict lands at roughly 36% faster timelines and about 8% lower cost versus traditional builds, alongside a map of the 80-plus players fighting over the space.

[**git rebase -i is not that scary**](https://cachebag.sh/journal/interactive-rebasing/) (5 minute read)

Interactive rebase gets treated like a live mine, but it is really just a text file where you plan what happens to your commits. This walkthrough covers the squash, reword, and fixup commands, and leans hard on the safety nets that people forget exist: you can always abort, rebase writes new commits instead of nuking the originals, and the reflog will bail you out when you inevitably fat-finger something. A solid encouragement for juniors to stop fearing the tool and start keeping a cleaner history.

[**PGSimCity: How PostgreSQL Works, in 3D**](https://nikolays.github.io/PGSimCity/) (6 minute read)

An interactive 3D visualization that renders PostgreSQL internals as a little city you can poke at, complete with a "Machine" view that shows real Postgres code next to the modeled architecture. Fair warning from the author: it is an early, unreviewed prototype and may get some details wrong, so treat it as a learning aid rather than gospel. Still a fun way to build intuition for what the engine is actually doing under the hood.

[**omarismail/terraform-plan-tui**](https://github.com/omarismail/terraform-plan-tui) - MIT - A terminal UI for browsing and reviewing Terraform plans without wading through raw plan output.

[**can1357/oh-my-pi**](https://github.com/can1357/oh-my-pi) - MIT - An AI coding agent for the terminal featuring hash-anchored edits, an optimized tool harness, LSP integration, Python and browser support, and subagents.

[**ASCIT31/Dark-Moon**](https://github.com/ASCIT31/Dark-Moon) - GPL-3.0 - An autonomous AI pentesting engine that runs continuous offensive security across web, cloud, Active Directory, and Kubernetes, using agentic reasoning and real exploit execution to produce proof-based vulnerabilities while a privacy gateway keeps your real IPs, hosts, and credentials from ever reaching the LLM.

[**CoreBunch/Instatic**](https://github.com/CoreBunch/Instatic) - MIT - An open-source, self-hosted visual CMS and alternative to Webflow, Framer, and WordPress that outputs clean static pages with built-in users, roles, plugins, content, and database support.

{{< sponsor >}}
