---
author: Chris Short
date: '2026-11-01'
description: "PHP finds another session bug two days after the PHP2Shell patches, Broccoli2Shell turns a Brotli decoder bug into RCE for Node.js, Envoy, and Istio, two unauthenticated KSMBD flaws land on public lists with no kernel fix, and KubeVirt looks ahead to its next decade."
draft: false
slug: '333'
title: "DevOps'ish 333: Broccoli2Shell, more PHP pain, KSMBD on blast, and KubeVirt's next decade"
---

{{< subscribe >}}

[**Keep your CI in the US or the EU**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-11-01) (Sponsor)

Choose where your GitHub Actions jobs run. WarpBuild runs in US and EU regions, or inside your own AWS, GCP, or Azure account with BYOC. Your code and build artifacts stay where your compliance team needs them. Twice as fast at half the cost. Try it with $50 in free credits using code START50.

[**The next 10 years of KubeVirt**](https://thenewstack.io/next-ten-years-kubevirt/) (6 minute read)

Vladik Romanovsky walks through where the CNCF incubating project goes after ten years of running VMs on Kubernetes. GPUs can already be claimed through Dynamic Resource Allocation (beta in v1.9), and that model is spreading to host devices, SR-IOV NICs, and CPUs. Also on deck: confidential VMs, the VM as a sandbox, newer Nvidia hardware, and pluggable virtualization backends. The enhancement queue went from a handful of items in v1.6 to more than a hundred by v1.10, and the community is working toward graduation. The design rule I like most: when Kubernetes grows a native way to do something, delete the KubeVirt-only path.

[**Is this the new cyber normal?**](https://drew.silcock.dev/blog/is-this-the-new-cyber-normal/) (23 minute read)

Drew Silcock tries to make sense of a week where PHP2Shell and a pile of other critical bugs dropped one after another. His read: LLMs are very good at turning a vague patch diff into a working exploit, so the moment a fix is announced is about the last moment you can assume nobody has an exploit. One of the PHP2Shell bugs had even turned up in a 2024 audit and got shelved because nobody could figure out how to exploit it. He then works through the options (close source everything, out-AI the attackers, or fix how disclosure works) with honest pros and cons and a healthy suspicion of the money involved. Long, but worth it if you're the one getting paged.

[**PHP Warns of Another Unpatched RCE Risk Two Days After Emergency PHP2Shell Patches**](https://thehackernews.com/2026/10/urgent-php-warns-of-another-unpatched.html) (2 minute read)

PHP published an informational advisory for CVE-2026-115560 on October 23, two days after the emergency PHP2Shell releases. The exposure is narrow: an app has to switch session.serialize_handler to php at runtime with ini_set() before session_start(), with session upload progress still on. PHP isn't shipping an emergency fix; it wants you to set session.upload_progress.enabled=0 until the next routine release. If you already flipped that for CVE-2026-109619, you're done. Meanwhile, PHP2Shell probing went from tens of thousands of attempts to millions within a day, though nobody has confirmed code execution yet.

[**PHP2Shell: buy time with a WAF, then patch the servers**](https://traefik.io/blog/php2shell-buy-time-with-a-waf-then-patch-the-servers) (17 minute read)

Traefik's pitch is a virtual patch at the edge while you chase down every PHP worker in the fleet. They built a rule set for the Traefik Hub WAF, tested it against a real PHP 8.3 app, and report it blocked every published attack shape, evasions included, for about 7% of throughput and p95 latency going from 55 to 60 ms. Yes, it's a vendor post, but the config is in there and the exposure-window argument holds for any WAF. They're also clear that it's a stopgap. Upgrade to 8.2.35, 8.3.36, 8.4.27, or 8.5.12 (or your distro's backport) and restart everything.

[**Broccoli2shell: Everything You Need To Know About The Critical Brotli Decoder Vulnerability**](https://www.wiz.io/blog/cve-2026-111497-brotli-rce-node-js) (4 minute read)

CVE-2026-111497 is an out-of-bounds write in the upstream Brotli C decoder, so it isn't only a Node.js problem. Bun, Envoy, Istio, Python's brotli and brotlicffi, and Go's andybalholm/brotli all need patches. Anything that decompresses attacker-controlled Brotli data is in scope, including HTTP clients that do it automatically without your code ever mentioning Brotli. Wiz says 91% of cloud environments have vulnerable resources. Check the version table and get moving, especially on your service mesh.

[**Two CVSS 9.0 Linux KSMBD RCE Flaws Disclosed on Public Mailing Lists Before Kernel Fixes**](https://thehackernews.com/2026/10/two-cvss-90-linux-ksmbd-rce-flaws.html) (5 minute read)

Trend Micro's ZDI reported two remote code execution bugs in KSMBD, the in-kernel SMB server. One needs SMB Direct and RDMA. The other needs no authentication at all, just port 445. Neither had a fix in mainline or linux-next at publication time, and there are no CVEs yet. The reports came from an AI scanner and went to public lists without patches, following the kernel's new "AI-found bugs are already public" guidance, and Greg Kroah-Hartman was not happy about it. Run `lsmod | grep ksmbd`; if it's loaded and you don't need it, unload it.

[**Why Kubernetes autoscalers keep fighting each other (and why the solution must be autonomous)**](https://thenewstack.io/why-kubernetes-autoscalers-fight/) (5 minute read)

HPA says 11 replicas, VPA says shrink the requests, KEDA says 24 replicas, and Karpenter just bought two more nodes. Nikhil Kurup lays out how these controllers step on each other because they all mutate the same fields with no shared view. The HPA vs. VPA "denominator collapse" is the one to understand: VPA lowers requests, utilization percentage jumps, HPA scales out, and around it goes. The author works at Sedai, which sells autonomous rightsizing, so take the conclusion with salt. The diagnosis is still solid.

[**Exploring Apple's On-Device Model: Core Advanced**](https://www.airealist.ai/p/exploring-apple-on-device-model) (39 minute read)

Apple hasn't published a model card for its 20-billion-parameter on-device model, so this author built one from the outside on a Mac. The model sits in a ~5 GB file in flash and pulls in a few experts per prompt. Two seconds after a long request it held 2.0 GiB of memory, versus about 15 GiB for a comparable open model. It also used about a third of the energy on the same math problems. The catch: it finished last of four on math, and you can't pin or tune it. The process breakdown, separate safety models, and the bit about Google's part being the tokenizer are what make this worth the time.

[**Comcast loses more customers, claims other ISPs' cheap prices are "irrational"**](https://arstechnica.com/tech-policy/2026/10/comcast-loses-more-customers-claims-other-isps-cheap-prices-are-irrational/) (5 minute read)

Comcast lost 144,000 residential broadband customers in Q3, up from 91,000 a year ago, to fixed wireless and fiber. Its CFO calls $30 to $40 fiber plans "irrational" because fiber costs $1,500+ per home to build. The fix is a $1 billion+ restructuring charge, job cuts, and more AI agents in customer service. As someone who's dealt with Comcast customer service, I'm not sure the bots can make it worse. Competition is apparently only rational when Comcast doesn't have any.

[**kubev2v/forklift**](https://github.com/kubev2v/forklift) - Apache-2.0 - Toolkit for migrating VMs from VMware, OVA, EC2, HyperV, oVirt and OpenStack to KubeVirt

[**superplanehq/superplane**](https://github.com/superplanehq/superplane) - Apache-2.0 (the /ee directory is under a separate Enterprise Edition license) - Open source factory for one-shot engineering

{{< sponsor >}}
