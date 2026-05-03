---
author: Chris Short
date: '2026-05-03'
description: "Critical Linux kernel privilege escalation, GitHub's bad week of reliability and RCE, Meta ditching Llama, AI writing half of Google's code, and Linux on PS5."
draft: false
slug: '307'
title: "DevOps'ish 307: Copy Fail, GitHub's bad week, Linux on PS5, and more"
---

I spoke at [DevOpsDays Raleigh](https://devopsdays.org/events/2026-raleigh/welcome/) this past week. It's always good to visit Raleigh; I consider it a second home (sorry I didn't meet with more friends). The event was incredibly well done. The event staff and volunteers did a fantastic job on all facets of eventing. I took meetings in an [old control room](https://www.instagram.com/p/DX2lzfvEf2t/?img_index=1) for the event space which was a true blast from the past. My notes doc included two interesting stats.

Stat #1: 56% of women leave tech before the age of 35 - This is just sad especially when you consider women comprise a mere 28% of tech in general. This needs to change. It starts with using the privilege of the majority to help out the minority. Those of us in the majority have a duty to advocate for people not in the room.

Stat #2: Google expects 50% of all new code to be written by AI as soon as next year. This accelerates in the following years too. That's wild to think about. We'll be managing agents and subagents soon enough it seems to do not just coding but things like my slides from my talk, [Open Source Survival Guide: 10 rules to keep you sane in the open source world], this week(https://docs.google.com/presentation/d/1xqHKpihDnmOjwiheyf37feark1R9ti56rAGtxk5HkBQ/). I used Claude to restyle the deck from when I gave the talk at All Things Open. Claude did a surprisingly good job at matching the color palette of <shortconsulting.io>.

[Run Specialized Agents for Every Part of Your Workflow](https://mistr.al/vibe-devopsish-nl)  
Mistral Vibe lets you build dedicated agents for targeted tasks like deploy scripts, PR reviews, and test generation, and invoke them on demand. Subagents run independently, return results asynchronously, and inherit full project context without supervision. [Start with Mistral Vibe today](https://mistr.al/vibe-devopsish-nl)! *SPONSORED*

[How is infrastructure keeping pace with AI in 2026?](https://www.iacconf.com/iacconf-2026?refid=devopsish&utm_source=devopsish&utm_medium=paid_newsletter&utm_campaign=fy26%20-%20ww%20-%20virtual%20event%20-%20iacconf%20-%20may%202026&utm_content=newsletter)  
Managing IaC or leading platform engineering? IaCConf is the "can't miss" event featuring 20 top IaC leaders across 13 sessions. Join 5,000+ practitioners to share what's actually working and swap hard-won lessons. Register now! *SPONSORED*

[Cloud Native Days Romania](https://cloudnativedays.ro/?utm_source=devopsish&utm_medium=email&utm_campaign=307)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania's community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[Kubernetes v1.36: In-Place Vertical Scaling for Pod-Level Resources Graduates to Beta](https://kubernetes.io/blog/2026/04/30/kubernetes-v1-36-inplace-pod-level-resources-beta/) - In-place vertical scaling of pod-level resource budgets is now beta in Kubernetes v1.36, letting you adjust aggregate CPU and memory allocations for running pods without requiring container restarts in most cases.

[Kubernetes v1.36: Mutable Pod Resources for Suspended Jobs (beta)](https://kubernetes.io/blog/2026/04/27/kubernetes-v1-36-mutable-pod-resources-for-suspended-jobs/) - Also graduating to beta in v1.36, the ability to modify container resource requests and limits on suspended Jobs before they start or resume, giving queue controllers and admins real flexibility over CPU, memory, GPU, and extended resources.

[Ghostty Is Leaving GitHub](https://mitchellh.com/writing/ghostty-leaving-github) - Mitchell Hashimoto announces the Ghostty terminal project is departing GitHub due to persistent service reliability issues that have become a genuine blocker to productive development.

[GitHub is sinking](https://dbushell.com/2026/04/29/github-is-sinking/) - Post-acquisition degradation in GitHub's reliability and quality has the author arguing it's time to seriously evaluate alternative Git hosting platforms.

[GitHub RCE Vulnerability: CVE-2026-3854 Breakdown](https://www.wiz.io/blog/github-rce-vulnerability-cve-2026-3854) - Wiz details a critical remote code execution flaw in GitHub's internal git infrastructure that lets authenticated users run arbitrary commands via a single git push exploiting field injection vulnerabilities.

[GitHub Actions is the weakest link](https://nesbitt.io/2026/04/28/github-actions-is-the-weakest-link.html) - A well-argued breakdown of how GitHub Actions' default design choices like mutable action references, `pull_request_target` triggers, and overly permissive token defaults have made it the primary attack vector in recent open source supply chain compromises.

[Copy Fail: 732 Bytes to Root on Every Major Linux Distribution](https://xint.io/blog/copy-fail-linux-distributions) - CVE-2026-31431 is a critical Linux kernel privilege escalation through a logic flaw in the authencesn crypto template that lets unprivileged users write arbitrary data into page cache, affecting all major distributions.

[Trivy, KICS, and the shape of supply chain attacks so far in 2026](https://www.docker.com/blog/trivy-kics-and-the-shape-of-supply-chain-attacks-so-far-in-2026/) - Docker breaks down the supply chain compromise of the Checkmarx KICS container image repository, where stolen publisher credentials were used to push malicious images to Docker Hub, and outlines the broader credential-theft pattern driving attacks this year.

[Meta abandons open-source Llama for proprietary Muse Spark](https://thenewstack.io/meta-abandons-llama-spark/) - This didn't last long. Meta is discontinuing Llama in favor of a proprietary model called Muse Spark, a significant reversal of the company's previous open source AI posture.

[AI's New Training Data: Your Old Work Slacks And Emails](https://www.forbes.com/sites/annatong/2026/04/16/ais-new-training-data-your-old-work-slacks-and-emails/) - Defunct startups are liquidating their Slack archives, Jira tickets, and email threads as "operational exhaust" that AI labs now treat as premium training data. A new platform called Asset Hub is making it a marketplace.

[White House opposes Anthropic's plan to expand Mythos access to 70 companies, citing compute and security concerns](https://thenextweb.com/news/white-house-opposes-anthropic-mythos-expansion) - The Trump administration has blocked Anthropic's bid to broaden access to its cybersecurity AI model Mythos, citing security risks and insufficient compute infrastructure. It's not lost on me that Anthropic was criticized for not opening up Mythos to more organizations in the beginning and now they're being told not to.

[Where the goblins came from](https://openai.com/index/where-the-goblins-came-from/) - OpenAI explains how a reward signal tied to the "Nerdy" personality option during RLHF caused ChatGPT to develop a 3,881% spike in goblin references; a useful case study in how learned behaviors escape their training scope.

[Underwhelming or underrated? DeepSeek V4 shows 'impressive' gains](https://www.scmp.com/tech/tech-trends/article/3351419/underwhelming-or-underrated-deepseek-v4-shows-impressive-gains) - DeepSeek's V4 Pro shows technical improvements over its predecessor but still trails Moonshot AI's Kimi K2.6 and American closed-source models in head-to-head comparisons.

[Pull Request For Linux To Remove Old Network Drivers, ISDN Subsystem Due To AI/LLM Noise](https://www.phoronix.com/news/Linux-7.1-PR-Remove-Old-Net) - Linux networking maintainers are removing the ISDN subsystem, AX.25, amateur radio, and several legacy Ethernet drivers in 7.1, citing the surge of AI/LLM-generated bug reports against long-orphaned code as a key motivation.

[Warp is now open-source](https://www.warp.dev/blog/warp-is-now-open-source) - Warp has released its terminal client under an AGPL license, leaning into agent-first development workflows managed through its Oz platform for community contributions.

[Zed is 1.0](https://zed.dev/blog/zed-1-0) - The Rust-built, AI-native code editor hits 1.0 and declares it has reached "a tipping point where most developers can quickly feel at home," with collaborative features and performance as its continued north stars.

[How I Use Claude Code](https://boristane.com/blog/how-i-use-claude-code/) - Boris Tane's disciplined four-phase workflow for AI-assisted development is worth a read: the core rule is "never let Claude write code until you've reviewed and approved a written plan."

[I Left Port 22 Open on the Internet for 54 Days. Here's Who Showed Up](https://arman-bd.hashnode.dev/i-left-port-22-open-on-the-internet-for-54-days-here-s-who-showed-up) - Out of 7,556 attacking IPs logged against an intentionally exposed SSH honeypot, only 0.4% ever opened an interactive shell. The rest were pure automation, fingerprinting, and moving on.

[The Unwritten Laws of Software Engineering](https://newsletter.manager.dev/p/the-unwritten-laws-of-software-engineering) - Seven hard-learned lessons covering deployment safety, backup reliability, logging practices, data migrations, dependency management, code review discipline, and why "temporary" is forever.

[Rural America is resisting the surge in data center construction](https://arstechnica.com/ai/2026/04/rural-america-is-resisting-the-surge-in-data-center-construction/) - Many rural communities are viscerally opposed to AI infrastructure buildout in their backyards, and that resistance is becoming an increasingly organized policy and zoning fight.

[Building a PCI-DSS Compliant GKE Framework for Financial Institutions: Data Protection, Governance & Audit Logging](https://blog.devops.dev/building-a-pci-dss-compliant-gke-framework-for-financial-institutions-data-protection-governance-0deaa1b72893) - Part four of Mohamed Rasvi's series covers tokenization, customer-managed encryption keys (CMEK), DLP scanning, and the audit trail a PCI QSA actually wants to see.

[Terraform Audit Guide: Monitoring, Logging & Compliance](https://spacelift.io/blog/terraform-audit) - A systematic walkthrough of reviewing Terraform infrastructure code and operations to ensure compliance with organizational governance and security standards.

[Notepad++ finally lands on macOS as a real native app](https://nerds.xyz/2026/04/notepad-plus-plus-mac/) - A native macOS build of the long-running Windows text editor Notepad++ has arrived, [built with Apple frameworks](https://notepad-plus-plus-mac.org/) rather than compatibility shims. I remember when I was forced to use Windows systems and had to use Notepad++. I can't say I'm ditching VScode for it though now that it's on macOS.

[Installing vLLM on macOS: A Step-by-Step Guide](https://medium.com/@rohitkhatana/installing-vllm-on-macos-a-step-by-step-guide-bbbf673461af) - Working around CUDA dependencies to get the vLLM inference engine running on macOS, with practical fixes for Python import issues along the way.

[trycua/cua](https://github.com/trycua/cua) - MIT License - Open-source infrastructure for Computer-Use Agents: sandboxes, SDKs, and benchmarks to train and evaluate AI agents that can control full desktops (macOS, Linux, Windows).

[skyhook-io/radar](https://github.com/skyhook-io/radar) - Apache License 2.0 - Modern Kubernetes visibility with topology views, event timelines, service traffic inspection, resource browsing, and Helm management.

[ps5-linux/ps5-linux-loader](https://github.com/ps5-linux/ps5-linux-loader) - GNU General Public License v3.0 - Linux payload implementing the HV exploit and a custom bootloader for the PS5.

{{< subscribe >}}
