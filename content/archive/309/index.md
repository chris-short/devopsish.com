---
author: Chris Short
date: '2026-05-17'
description: "Linux kernel page cache exploits keep coming. Plus: Kubernetes v1.36, Meta AI morale in freefall, GitLab restructures for the agentic era, and AWS overheats in Virginia -- again."
draft: false
slug: '309'
title: "DevOps'ish 309: Dirty Pages All the Way Down, The Cloud Is Hot, and more"
---

The Linux kernel vulnerabilities are coming in hot and heavy. I don't think I've ever updated a kernel due to security issues this frequently before. I fear CopyFail, Dirty Frag, and Fragnesia are the tip of a much bigger iceberg below the surface. There will be more, and they could come very quickly as more flaws in the kernel's page cache logic are discovered, as more and more eyeballs focus on this exploit vector. As always, build safety into your systems and processes to make upgrades and reboots as painless as possible. Stay safe out there.

[**How to migrate your paging tool without breaking your team**](https://fandf.co/4f3OFvX)  
Most teams treat a paging tool migration as a like-for-like swap. Mistake. Paging is ~10% of incident management. The other 90% (triage, comms, postmortems) is where teams actually break. *SPONSORED*

[Fleet-Scale Kubernetes: An Operating Model for Homogeneous Clusters with Decoupled Capacity](https://lucy.sh/fleet-scale-kubernetes) - The case for managing fleets of many small, homogeneous Kubernetes clusters with decoupled capacity provisioning through a standardized autoscaler contract, rather than trying to scale individual clusters or unify across specialized cluster types.

[ingress-nginx to Envoy Gateway Migration on CNCF Internal Services Cluster](https://www.cncf.io/blog/2026/04/13/ingress-nginx-to-envoy-gateway-migration-on-cncf-internal-services-cluster/) - CNCF migrated its own Kubernetes cluster from the retiring ingress-nginx to Envoy Gateway, documenting the shared gateway architecture, cross-namespace access, and cloud load balancer integration details. A useful reference as the rest of the ecosystem works through the same migration.

[Kubernetes v1.36: PSI Metrics for Kubernetes Graduates to GA](https://kubernetes.io/blog/2026/05/12/kubernetes-v1-36-psi-metrics-ga/) - Pressure Stall Information metrics for monitoring resource contention at node, pod, and container levels are now stable in v1.36, with performance testing confirming low overhead even under high-density workloads.

[Kubernetes v1.36: Advancing Workload-Aware Scheduling](https://kubernetes.io/blog/2026/05/13/kubernetes-v1-36-advancing-workload-aware-scheduling/) - v1.36 separates the static Workload API from the runtime PodGroup API, adds topology-aware scheduling and workload-aware preemption, and integrates with Dynamic Resource Allocation for smarter batch and AI/ML workload scheduling.

[Kubernetes v1.36: Deprecation and Removal of Service ExternalIPs](https://kubernetes.io/blog/2026/05/14/kubernetes-v1-36-deprecation-and-removal-of-service-externalips/) - The `.spec.externalIPs` field is formally deprecated in v1.36 due to CVE-2020-8554 and multi-tenant cluster exploit risks; migrate to MetalLB, manually-managed LoadBalancer Services, or similar before the field disappears in a future release.

[How We Replaced Ingress-NGINX at Stack Overflow](https://stackoverflow.blog/2026/05/06/how-we-replaced-nginx-ingress-at-stack-overflow/) - Stack Overflow evaluated three Gateway API implementations and landed on Istio, citing increased stability and performance testing results. A timely read given the wider ingress-nginx sunset currently playing out across the ecosystem.

[Meta's Embrace of AI Is Making Its Employees Miserable](https://www.nytimes.com/2026/05/08/technology/meta-ai-employees-miserable.html?unlockedarticlecode=1.hVA.6Egz.ZImQVn3XS8um&smid=nytcore-ios-share) - Meta is tracking everything its employees type and click under the Model Capability Initiative to train its AI, while simultaneously cutting 10% of staff and tying performance reviews to AI tool adoption. Historic-low morale, people actively angling to get laid off for severance. This is the preview of what every large tech employer is going to try.

[GitLab Is Cutting Jobs for the Agentic Era. It Does Not Yet Know How Many.](https://thenextweb.com/news/gitlab-layoffs-agentic-era-devops-ai) - GitLab is flattening management, cutting 30% of country operations, and reorganizing into autonomous teams to invest in AI agents, with the actual headcount reduction to be disclosed in June earnings. The vibes in DevOps land are not great right now.

[AWS Data Center Outage Hits Trading on FanDuel, Coinbase -- Recovery to Take Hours](https://www.cnbc.com/2026/05/08/aws-outage-data-center-fanduel-coinbase.html) - Overheating at a Northern Virginia data center took down AWS long enough to disrupt FanDuel and Coinbase. The cloud is still a single-region failure problem when you don't build for it.

[All Those AI Notetakers? They're Making Lawyers Very Nervous.](https://www.nytimes.com/2026/05/09/business/dealbook/ai-notetakers-legal-risk.html?unlocked_article_code=1.hlA.-4F3.tqCql3xo3NwI&smid=nytcore-ios-share) - Every offhand comment in a recorded meeting is now potentially discoverable, AI bots may void attorney-client privilege, and a federal judge already ruled that Claude transcripts weren't protected by privilege. The lawyers are right to be nervous, and so should the rest of us.

[NHS to Close-Source Hundreds of GitHub Repos Over AI, Security Concerns](https://www.theregister.com/software/2026/05/05/nhs-to-close-source-github-repos-over-ai-security-concerns/5224392) - The UK National Health Service is making its public GitHub repos private over concerns that AI models could exploit exposed source code. Security researchers are skeptical it actually moves the needle on risk. As one follower pointed out, if you are dependent on one of these codebases git clone is an effective ally.

[Mythos Finds a Curl Vulnerability](https://daniel.haxx.se/blog/2026/05/11/mythos-finds-a-curl-vulnerability/) - Anthropic's Mythos model found exactly one confirmed security vulnerability in curl's 178,000 lines of code, which Daniel Stenberg notes may suggest the hyped model's security analysis capabilities are more modest than advertised.

[GTIG AI Threat Tracker: Adversaries Leverage AI for Vulnerability Exploitation, Augmented Operations, and Initial Access](https://cloud.google.com/blog/topics/threat-intelligence/ai-vulnerability-exploitation-initial-access) - Google's Threat Intelligence Group documents adversaries using AI for zero-day exploit development, autonomous malware orchestration, defense evasion, and supply chain attacks against AI systems themselves.

[CUDA Proves Nvidia Is a Software Company](https://www.wired.com/story/cuda-proves-nvidia-is-a-software-company/) - The moat around Nvidia isn't the chips -- it's the decade-deep CUDA software ecosystem that everything in AI training and inference has been written against. The hardware is the delivery mechanism.

[Why MistralAI Grows Faster Than OpenAI/Anthropic](https://productify.substack.com/p/why-mistralai-grows-faster-than-openaianthropic) - Mistral achieved 20x revenue growth by positioning as a sovereign, capable alternative for European enterprises and governments that want independence from US AI platforms rather than competing on raw scale.

[Motherboard Sales 'Collapse' by More Than 25% as Chipmakers Strangle Enthusiast PC Market to Build More AI Chips](https://www.tomshardware.com/pc-components/motherboards/motherboard-sales-collapse-by-more-than-25-percent-as-chipmakers-strangle-enthusiast-pc-market-to-build-more-ai-chips-asus-projected-to-sell-5-million-fewer-boards-in-2025-gigabyte-msi-and-asrock-also-expected-to-see-reduced-sales-numbers) - Asus is projected to sell 5 million fewer boards in 2025 as chipmakers redirect production toward AI chips, squeezing Gigabyte, MSI, and ASRock too. The AI buildout is eating the enthusiast PC market alive. I'm coming to grips with the idea that my next computer (which I'll need sooner rather than later) will be the most expensive machine I've ever bought.

[10 Trillion Downloads Are Crushing Open-Source Repositories -- Here's What They're Doing About It](https://www.zdnet.com/article/open-source-repositories-are-being-overwhelmed-but-there-is-an-answer/) - Companies are hammering Maven Central, PyPI, RubyGems, and friends like CDNs -- 82% of demand from 1% of IPs -- and the Linux Foundation is pulling together a Sustaining Package Registries Working Group to figure out funding, governance, and shared security before something important falls over.

[How NASA Built Artemis II's Fault-Tolerant Computer](https://cacm.acm.org/news/how-nasa-built-artemis-iis-fault-tolerant-computer/) - Eight CPUs across four fail-silent, self-checking Flight Control Modules run the Orion capsule in lockstep -- lose three FCMs in 22 seconds and the fourth still holds. The dissimilar backup flight software on completely different hardware is a nice touch.

[Tech Is Turning Increasingly to Religion in a Quest to Create Ethical AI](https://apnews.com/article/ai-artificial-intelligence-ethics-religion-roundtable-053a44133c64703f83fd50c9ee6124ea) - Tech companies are increasingly bringing faith leaders into AI ethics conversations, which is a fascinating signal that the secular frameworks haven't been convincing enough on their own.

[Localmaxxing](https://tomtunguz.com/localmaxxing/) - Roughly half of daily AI tasks run fine on a local 35B model with 2x faster inference than cloud frontier models -- you lose some reasoning ceiling, but the latency and offline capability trade is real.

[Running Local Models on an M4 with 24GB Memory](https://jola.dev/posts/running-local-models-on-m4) - A practical walkthrough of running a Qwen model locally on a MacBook Pro M4, covering configuration and the honest tradeoff between local convenience and cloud-model capability.

[In a Quest to Becoming AI-Independent: A Guide to Local LLM Inference Hardware](https://adlrocha.substack.com/p/adlrocha-in-a-quest-to-becoming-ai) - The argument that cloud AI services are engineered to create dependency, paired with a practical hardware breakdown for running local LLM inference without feeding the subscription machine.

[Useful Memories Become Faulty When Continuously Updated by LLMs](https://dylanzsz.github.io/faulty-memory/) - Automatically distilling agent memories into rewritten text lessons degrades performance over time because the consolidation introduces errors instead of accumulating knowledge -- episodic-only memory outperforms abstraction-based approaches.

[Refactoring HCL Organization-Wide with OpenRewrite](https://oczadly.io/posts/2026-04-23-refactoring-hcl-organization-wide-with-openrewrite/) - Using OpenRewrite's lossless semantic trees and Gradle to run deterministic, structure-aware infrastructure-as-code migrations across an org, producing clean reviewable PRs instead of the usual regex-and-pray approach.

[V4bel/dirtyfrag](https://github.com/V4bel/dirtyfrag/blob/master/README.md) - No License - Universal Linux LPE chaining CVE-2026-43284 (xfrm-ESP page-cache write) and CVE-2026-43500 (RxRPC page-cache write) to obtain root on major Linux distributions. Deterministic logic bug, no race condition required. Both CVEs are now patched in mainline.

[sjjian/openhare](https://github.com/sjjian/openhare) - Apache-2.0 License - AI-powered desktop SQL client, cross-platform, built with Flutter.

[alebeck/boring](https://github.com/alebeck/boring) - Other License - The `boring` SSH tunnel manager.

{{< subscribe >}}
