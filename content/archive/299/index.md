---
author: Chris Short
categories:
- Weekly
- Newsletter
- '2026'
date: '2026-03-08'
draft: false
slug: '299'
title: "DevOps'ish 299: Anthropic vs. US Gov, 'How not to IAM' by LexisNexis, and more"
---

A lot is going on in the world of tech today. I have to say, of all the boneheaded moves the US government has made in the past couple of weeks, [turning away Anthropic](https://www.anthropic.com/news/where-stand-department-war), one of the most popular AI companies, because of two very simple asks is not smart. The government's ask is too broad (anything legal; the definition of legal can change), and Anthropic's ask is quite narrow (don't use our AI to kill people unchecked or spy on US citizens domestically). The US already spies on everything we do as citizens indirectly (metadata can be as powerful as the actual data at a sufficient scale). I suspect this is the sticking point for the US government.

Like it or not, the world is in a race to integrate and improve AI across all of society. Telling Anthropic that they can't play in the government space is not going to accelerate anything; quite the opposite. Meanwhile, the rest of the world is using US AI company tooling to speed their delivery of new AI capabilities. Some would argue that China is winning right now, specifically with Qwen ([which also had a weird week](https://simonwillison.net/2026/Mar/4/qwen/)).

The beef between Anthropic and the US government does nothing to advance the US position in the AI race. Meanwhile, [OpenAI has admitted](https://www.cnbc.com/2026/03/03/openai-sam-altman-pentagon-deal-amended-surveillance-limits.html) that their moves during all this looked slimy (because they were). During all this, Anthropic Claude app installs are up on the App Store (they're still at #1 as of Friday). Meanwhile, [OpenAI ChatGPT uninstalls are up](https://techcrunch.com/2026/03/02/chatgpt-uninstalls-surged-by-295-after-dod-deal/) too. Oh, and [negotiations between Anthropic and the US government are ongoing](https://www.cnbc.com/2026/03/05/anthropic-pentagon-ai-deal-department-of-defense-openai-.html) so I suspect this will be a non-issue soon. This whole thing looks like a moral win for Anthropic but whether or not that matters in the long run is anyone's guess.

[**Secure Access to Cloud Services from Your Cluster with a Security Token Service**](https://www.tremolo.io/post/secure-access-to-cloud-services-from-your-cluster-with-a-security-token-service?utm_source=devopsish&utm_medium=newsletter&utm_campaign=299)  
Securely connect your Kubernetes workloads to cloud services without long-lived credentials using a Security Token Service pattern. This post shows how OpenUnison validates ServiceAccount identity and issues short-lived, service-specific tokens to reduce credential exposure and improve authorization posture. _SPONSORED_

**Events**

[Cloud Native Days Romania](https://cloudnativedays.ro/)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania’s community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage. Take advantage of early bird pricing now!

[Leaders at the Departments of State, Treasury and Health and Human Services directed their employees to abandon Anthropic's language-trained chatbot platform Claude](https://www.reuters.com/business/us-treasury-ending-all-use-anthropic-products-says-bessent-2026-03-02/) - Three U.S. cabinet agencies moved to cease use of Anthropic's AI products after the Trump administration and Anthropic failed to agree on limits to military use of Claude — specifically around autonomous weapons targeting and domestic surveillance of Americans. The Pentagon dropped Anthropic first; State, Treasury, HHS, FHFA, Fannie Mae, and Freddie Mac followed on Monday. State is switching its internal StateChat tool to GPT-4.1 from OpenAI, which conveniently announced its own DoD classified network deal on Friday.

[Attackers Now Need Just 29 Minutes to Own a Network](https://www.darkreading.com/cyber-risk/attackers-now-need-just-29-minutes-to-own-a-network) - CrowdStrike's 2026 Global Threat Report reveals the average attacker breakout time has dropped to just 29 minutes (down from 62 minutes a few years ago), with 82% of detections being malware-free and AI-assisted attacks surging 89% year over year.

[LexisNexis Confirms Data Breach as Hackers Leak Stolen Files](https://www.bleepingcomputer.com/news/security/lexisnexis-confirms-data-breach-as-hackers-leak-stolen-files/) - American data analytics company LexisNexis Legal & Professional has confirmed that hackers breached its servers and accessed customer and business information, with the stolen files subsequently leaked publicly.

[Seedworm: Iranian APT on Networks of U.S. Bank, Airport, Software Company](https://www.security.com/threat-intelligence/iran-cyber-threat-activity-us) - The Iranian APT group Seedworm has been conducting cyber operations against multiple U.S. organizations since February 2026, deploying previously unknown backdoors and attempting data exfiltration in the wake of military escalations in the Middle East.

[Mount Mayhem at Netflix: Scaling Containers on Modern CPUs](https://netflixtechblog.com/mount-mayhem-at-netflix-scaling-containers-on-modern-cpus-f3b09b68beac) - Netflix engineers detail how they diagnosed and resolved container scaling issues on modern CPUs, sharing lessons learned from a deep dive into Linux mount namespaces and kernel behavior at scale.

[How We Reduced the Size of Our Agent Go Binaries by Up to 77%](https://www.datadoghq.com/blog/engineering/agent-go-binaries/) - Datadog engineers achieved massive binary size reductions through systematic dependency removal, enabling linker optimizations, and eliminating unnecessary imports — bringing their Agent artifacts from 1.22 GiB back to levels not seen in five years while maintaining full functionality.

[How I Dropped Our Production Database and Now Pay 10% More for AWS](https://alexeyondata.substack.com/p/how-i-dropped-our-production-database) - A cautionary tale about using an AI agent to run Terraform commands that accidentally destroyed a production database and all its automated backups, requiring AWS Business Support intervention to restore the data at significant ongoing cost.

[Alibaba's Small, Open Source Qwen3.5-9B Beats OpenAI's gpt-oss-120B and Can Run on Standard Laptops](https://venturebeat.com/technology/alibabas-small-open-source-qwen3-5-9b-beats-openais-gpt-oss-120b-and-can-run) - Alibaba's Qwen3.5-9B outperforms OpenAI's 120B open-source model on key benchmarks including graduate-level reasoning and multilingual knowledge, runs on an 8 GB GPU with 4-bit quantization, and is available under an Apache 2.0 license.

[FCC Lets Charter Buy Cox, Says No Reason to Worry About Higher Internet Prices](https://arstechnica.com/tech-policy/2026/03/fcc-lets-charter-buy-cox-says-no-reason-to-worry-about-higher-internet-prices/) - The FCC approved Charter's acquisition of Cox, making Charter the largest ISP in the US, rejecting concerns about price increases on the grounds that the two companies don't directly compete in most markets. Which is a reason, I guess? ¯\\\_(ツ)_/¯

[2025 State of Rust Survey Results](https://blog.rust-lang.org/2026/03/02/2025-State-Of-Rust-Survey-results/) - The Rust Survey Team shares findings from 7,156 responses to the 10th annual survey, revealing stable and growing industry adoption, top desired features like generic const expressions, and results that closely mirror last year's — a sign of a maturing ecosystem.

[The Generative AI Policy Landscape in Open Source](https://redmonk.com/kholterhoff/2026/02/26/generative-ai-policy-landscape-in-open-source/) - An analysis of generative AI policies across 70 open source organizations maps how the community is responding to AI-generated contributions, examining stances ranging from permissive to restrictive and key concerns around code quality, copyright, and ethics.

[Multi-AZ by Default, Local by Design: Cutting Cross-Zone Traffic with Cilium](https://isovalent.com/blog/post/multi-az-by-default-local-by-design-cutting-cross-zone-traffic-with-cilium/) - A practical guide to using Cilium's topology-aware routing features to keep traffic local within availability zones in multi-AZ Kubernetes clusters, reducing cross-zone data transfer costs without sacrificing resilience.

[ing-switch: Migrate from Ingress NGINX to Traefik or Gateway API in Minutes, Not Days](https://blog.kubesimplify.com/ing-switch-migrate-from-ingress-nginx-to-traefik-or-gateway-api-in-minutes-not-days) - With Ingress NGINX being deprecated in March 2026, `ing-switch` is an open-source CLI + visual UI that scans your cluster, maps 50+ NGINX annotations, generates ready-to-apply migration manifests, and walks you through a zero-downtime cutover to Traefik or Gateway API.

[OpenClaw, but in containers: Meet NanoClaw](https://www.theregister.com/2026/03/01/nanoclaw_container_openclaw/) - A smaller, security-conscious take on the viral AI agent platform. I deployed this very quickly and have been tinkering with it. I'm impressed so far.

[How to Deploy OpenClaw on Kubernetes](https://openclaw.rocks/blog/deploy-openclaw-kubernetes) - A comprehensive guide for deploying OpenClaw AI agents securely on Kubernetes using a dedicated operator, covering setup, security features, auto-updates, browser automation, and local inference configurations.

[IP66](https://ip66.dev/) - A free, daily-updated MMDB-compatible IP geolocation database providing ASN, country, and continent data with no license key required.

[dlvhdr/diffnav](https://github.com/dlvhdr/diffnav) - A git diff pager based on delta but with a file tree navigator, à la GitHub. License: MIT

[googleworkspace/cli](https://github.com/googleworkspace/cli) - Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more, dynamically built from the Google Discovery Service with AI agent skills included. License: Apache 2.0

{{< subscribe >}}
