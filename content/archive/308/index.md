---
author: Chris Short
date: '2026-05-10'
description: "CopyFail is being actively exploited, Antrea's Jenkins got owned via a malicious PR, NVIDIA chips have a Rowhammer problem that bypasses IOMMU, pgBackRest lost its sole maintainer, and Meta is being sued for torrenting 267TB of pirated books to train Llama. Kubernetes v1.36 shipped a lot too."
draft: false
slug: '308'
title: "Actively Exploited, Actively Litigated, Actively Dead"
---

[Build Real-Time Voice Agents with 90ms Latency](https://mistr.al/audio-devopsish-nl)  
Voxtral TTS streams natively, handles arbitrarily long generations, and slots into any STT + LLM stack. Clone any voice in 9 languages from a 3-second sample—no fine-tuning required. Pair with Voxtral Transcribe for end-to-end speech-to-speech. [Get started with Voxtral TTS](https://mistr.al/audio-devopsish-nl)! *SPONSORED*

[IaCConf 2026: AI, IaC, and platform engineering](https://www.iacconf.com/iacconf-2026?refid=devopsish&utm_source=devopsish&utm_medium=email&utm_campaign=fy26%20-%20ww%20-%20virtual%20event%20-%20iacconf%20-%20may%202026&utm_content=newsletter)  
It’s 2026. Platform engineering is shifting. Your users aren’t just developers anymore. They’re AI agents. Plan for it. Join IaCConf 2026 to hear from the people building this sh*ft on May 14th at 11 am ET. *SPONSORED*

[Cloud Native Days Romania](https://cloudnativedays.ro/?utm_source=devopsish&utm_medium=email&utm_campaign=308)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania's community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[CNCF Project Antrea Compromised in Daring GitHub Attack](https://opensourcemalware.com/blog/antrea-compromise2) - The Antrea open-source Kubernetes project was attacked via its Jenkins integration on May 2 by an unknown threat actor who opened a malicious pull request, claimed root on the Jenkins controller, and taunted maintainers. All thanks to the Trivy vulnerability.

[Kubernetes v1.36: Moving Volume Group Snapshots to GA](https://kubernetes.io/blog/2026/05/08/kubernetes-v1-36-volume-group-snapshot-ga/) - Volume group snapshots reach General Availability in Kubernetes v1.36, enabling crash-consistent snapshots of multiple volumes at the same time through CSI drivers.

[Kubernetes v1.36: Pod-Level Resource Managers (Alpha)](https://kubernetes.io/blog/2026/05/01/kubernetes-v1-36-feature-pod-level-resource-managers-alpha/) - Alpha in v1.36, pod-level resource managers enable hybrid allocation models that give performance-critical containers NUMA-aligned dedicated resources while letting sidecars share what's left.

[Kubernetes v1.36: Admission Policies That Can't Be Deleted](https://kubernetes.io/blog/2026/05/04/kubernetes-v1-36-manifest-based-admission-control/) - Manifest-based admission control lands as alpha in v1.36, loading webhooks and CEL-based policies from disk at API server startup so they exist from cluster bootstrap and can't be deleted by a bad actor or runbook gone sideways.

[Kubernetes v1.36: Declarative Validation Graduates to GA](https://kubernetes.io/blog/2026/05/05/kubernetes-v1-36-declarative-validation-ga/) - Declarative validation for Kubernetes native types is now GA in v1.36, swapping thousands of lines of handwritten validation code for a unified marker-tag framework that's actually maintainable.

[Mark Zuckerberg 'Personally Authorized and Actively Encouraged' Meta's Massive Copyright Infringement to Train AI Systems, Publishers and Scott Turow Allege in Lawsuit](https://variety.com/2026/digital/news/meta-ai-mark-zuckerberg-copyright-infringement-lawsuit-publishers-scott-turow-1236738383/) - Five major publishers and author Scott Turow have filed a class action alleging Meta torrented over 267 terabytes of pirated material to train Llama, with Zuckerberg personally directing the strategy after the company walked away from a $200M licensing deal. This is being called "the most flagrant copyright breach in history," which is saying something.

['CopyFail' Attackers Start Cashing in on Linux Flaw](https://www.theregister.com/security/2026/05/05/copyfail-attackers-start-cashing-in-on-linux-flaw/5226930) - Active exploitation of CVE-2026-31431 has begun following the release of a working proof-of-concept, with attackers now turning the Linux kernel privilege escalation into actual attacks.

[Rowhammer Attack Against NVIDIA Chips](https://www.schneier.com/blog/archives/2026/05/rowhammer-attack-against-nvidia-chips.html) - Two independent research teams revealed rowhammer attacks against NVIDIA GPUs that can yield complete system control through bit flips in GDDR memory, with a third variant shown to work even with IOMMU protections enabled.

[pgBackRest is dead. Now what?](https://mydbanotebook.org/posts/pgbackrest-is-dead.-now-what/) - David Steele, the sole maintainer of pgBackRest, has discontinued the project after his sponsoring company was sold, leaving a major PostgreSQL backup tool without a future and the community scrambling for alternatives.

[Terraform is dead](https://grahamgilbert.com/blog/2026/04/20/terraform-is-dead/) - The argument here is that AI has made Terraform's DSL unnecessary by letting you describe infrastructure through diagrams and natural language. A provocative take, and not entirely wrong even if the obituary is premature.

[A New Chapter for Mirantis](https://www.mirantis.com/blog/a-new-chapter-for-mirantis/) - CEO Alex Freedland announces Mirantis's acquisition by IREN and positions the company to make k0rdent AI the open standard for enterprise AI infrastructure across heterogeneous hardware and cloud environments.

[Introducing deepsec: The Security Harness for Finding Vulnerabilities in Your Codebase](https://vercel.com/blog/introducing-deepsec-find-and-fix-vulnerabilities-in-your-code-base) - Vercel's open-source deepsec tool uses AI coding agents to identify security vulnerabilities in large codebases, combining static analysis with multi-step investigation and validation workflows.

[OCP Multipath Reliable Connection (MRC) 1.0 Specification](https://www.opencompute.org/documents/ocp-mrc-1-0-pdf) - The Open Compute Project publishes the MRC 1.0 spec, an open networking protocol that extends InfiniBand Reliable Connection semantics to spread traffic over multiple paths simultaneously for AI supercomputer fabrics. MRC is already deployed across OpenAI's GB200 clusters and co-developed by AMD, Broadcom, Intel, Microsoft, and NVIDIA.

[Your Container Is Not a Sandbox: The State of MicroVM Isolation in 2026](https://emirb.github.io/blog/microvm-2026/) - A clear-eyed assessment of how Rust-based microVM monitors provide genuine hardware-isolated security boundaries, and why containers, which share a kernel, still fall short for untrusted workload execution despite years of hardening.

[Podman Rootless Containers and the Copy Fail Exploit](https://garrido.io/notes/podman-rootless-containers-copy-fail/) - Gabriel Garrido confirms CVE-2026-31431 is exploitable inside rootless Podman containers to get a container root shell, then walks through the defense-in-depth measures (read-only images, capability drops, firewalling) that limit the blast radius.

[How AWS Trainium Actually Works (2026)](https://medium.com/@brookejamieson/how-aws-trainium-actually-works-2026-deb4142dae11) - A solid explainer from friend of the newsletter, Brooke Jamieson, on the three hardware design decisions behind Trainium: specialized compute cores with dedicated engines, on-chip memory close to processors, and separate communication hardware for inter-chip coordination.

[C8s: A Confidential Kubernetes Architecture](https://arxiv.org/abs/2604.26974) - A research paper introducing a confidential computing framework for Kubernetes that uses hardware Trusted Execution Environments to provide cryptographically rooted confidentiality, integrity, and verifiability for sensitive workloads.

[Hands Off My Trademark! Notepad++ Dev Threatens Legal Action Against macOS Port](https://www.theregister.com/software/2026/05/04/macos-port-of-notepad-called-out-for-trademark-violation/5224076) - Notepad++ creator Don Ho is going after an independent macOS port for misappropriating his trademark, logo, and domain naming, arguing the project misleadingly presents itself as official despite buried disclaimers. This release got me. Passing it along to y'all was a mistake, and I apologize for that.

[4 Behaviors That Make You Look Junior (No Matter Your Title)](https://alifeengineered.substack.com/p/4-behaviors-that-make-you-look-junior) - Visible irritation with processes, allowing emotions to cloud your work, defensive reactions to feedback, and defaulting to pessimism will undermine your reputation regardless of what your badge says.

[The "Negative Split" Software Engineering Effect](https://newsletter.manager.dev/p/the-negative-split-software-engineering-effect) - Drawing from marathon strategy, the argument is that engineering teams should deliberately start slower to build better foundations. The teams that rush early tend to pay for it in technical debt that compounds worse than a slow start ever did.

[Formatting an Entire 25 Million Line Codebase Overnight: The rubyfmt Story](https://stripe.dev/blog/formatting-an-entire-25-million-line-codebase-overnight-the-rubyfmt-story) - How Stripe's Developer Productivity team deployed `rubyfmt`, a Rust-based code formatter, across their entire Ruby codebase at scale.An engineering story worth reading for the operational details alone.

[What is Distributed Tracing? A Practical Guide](https://encore.dev/blog/tracing-guide) - Encore's guide covers the fundamentals of distributed tracing: how to see every operation in a request, how long each took, and where the time went; useful for anyone still treating `console.log` as observability.

[How to Secure Workloads, Containers, and Kubernetes the Right Way](https://webflow.sysdig.com/blog/how-to-secure-workloads-containers-and-kubernetes-the-right-way) - Sysdig lays out a three-pillar approach: vulnerability management based on actual runtime risk, real-time threat detection and response, and continuous compliance monitoring rather than point-in-time snapshots.

[1jehuang/jcode](https://github.com/1jehuang/jcode) - MIT License - Coding Agent Harness

[modem-dev/hunk](https://github.com/modem-dev/hunk) - MIT License - Review-first terminal diff viewer for agentic coders

[niri-wm/niri](https://github.com/niri-wm/niri) - GPL-3.0 License - A scrollable-tiling Wayland compositor

[intel/auto-round](https://github.com/intel/auto-round) - Apache-2.0 License - A state-of-the-art quantization algorithm for high-accuracy low-bit LLM inference, optimized for CPU/XPU/CUDA with full compatibility with vLLM, SGLang, and Transformers

[withastro/flue](https://github.com/withastro/flue) - Apache-2.0 License - The sandbox agent framework

{{< subscribe >}}
