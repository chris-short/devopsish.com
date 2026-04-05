---
author: Chris Short
date: '2026-04-05'
description: ""
draft: false
slug: '303'
title: "DevOps'ish 303: Claude Code's Source, Iran's Tech Hit List, Microsoft's rough times, and More"
---

Happy Easter! This week, I needed a term to describe the Easter Bunny as sneaky, and I came up with "Resurrection Rabbit." Max thought it was funny in Elmer Fudd parlance, "Rascally Resurrection Rabbit."

One of the news items this week was the revelation that, thanks to a faulty build step, Anthropic leaked at least some of Claude Code's source code. I was fortunate enough to obtain a copy to give it a cursory look. But others are already discussing what they are learning from the source code now that it's out in the wild. I found the included pieces interesting, as well as an article about the `.claude` directory.

The Islamic Revolutionary Guard Corps (IRGC) [issued a threat to 18 US-based tech companies](https://www.wired.com/story/iran-threatens-to-start-attacking-major-us-tech-firms-on-april-1/) that they would be deemed military targets. One had already been attacked, as we've already seen with AWS. But, this threat also included a date and time: 1 April, 8 PM (Iran Standard Time). It appears the AWS region in Bahrain, me-south-1, was targeted again and [AWS is scrambling to recover capacity](https://www.tomshardware.com/tech-industry/iranian-missile-blitz-takes-down-aws-data-centers-in-bahrain-and-dubai-amazon-declares-hard-down-status-for-multiple-zones). There's some dispute over whether an Oracle facility was attacked in the UAE. I have many concerns about this war, one of which is whether these tech companies can continue to sustain the costs of being drawn into this conflict because of their work with the US government. The long-term effects of this conflict remain to be seen.

More layoffs were announced this week at [Meta](https://siliconangle.com/2026/03/25/meta-laying-off-hundreds-staff-across-multiple-divisions/) and [Oracle](https://www.cnbc.com/2026/03/31/oracle-layoffs-ai-spending.html). A friendly reminder, I'm looking for a new role. If you're hiring, [let's talk](https://chrisshort.net/contact/)! I'm also available for projects and go to market activities as well through my consulting firm, [Chris Short Consulting](https://shortconsulting.io/#get-in-touch).

Enjoy this week's newsletter!

[What we need from CI for agentic engineering](https://fandf.co/4sQrjhm)  
CI was designed for humans who context-switch while waiting. Agents don't. They're just blocked. Depot CEO Kyle Galbraith on how they re-imagined CI Depot CI to close the loop: run against local patches, rerun a single job, SSH into the runner to check reality. Per-second billing, no minimums. *SPONSORED*

## Events

[Cloud Native Days Romania](https://cloudnativedays.ro/)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania's community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[DevOpsDays Raleigh](https://tickets.devopsdays.org/devopsdays-raleigh/2026/)  
DevOpsDays Raleigh is one of the region's premier community-driven tech conferences, bringing together engineers, DevOps leaders, and IT professionals for two days of real-world insights, practitioner-led talks, and interactive open spaces. And this year is special as it's the 10th anniversary! This conference is focused on DevOps, cloud, automation, and modern software delivery.  It offers a unique mix of learning, networking, and collaboration with peers tackling similar challenges across industries. Join me in Raleigh **April 30th & May 1st**!

## This Week

[OSPO Notes: Open Source Governance — Who Decides, and How](https://chrisshort.net/ospo-notes-open-source-governance-who-decides-and-how/) - Open source governance answers one question: who decides, and how? A plain-language guide to every major governance model — and why mature projects layer several at once.

[Kubernetes v1.36 Sneak Peek](https://kubernetes.io/blog/2026/03/30/kubernetes-v1-36-sneak-peek/) - A preview of what's landing at the end of April 2026, packed with enhancements, removals, and deprecations across the release cycle — worth reading before the release notes drop.

[Claude Code's Source Code Appears to Have Leaked: Here's What We Know](https://venturebeat.com/technology/claude-codes-source-code-appears-to-have-leaked-heres-what-we-know) - Anthropic accidentally shipped 512,000 lines of TypeScript source code via a misconfigured source map file in the Claude Code npm package, exposing remote telemetry, killswitches, 44 feature flags, and an unreleased autonomous agent mode called KAIROS.

[Here's What That Claude Code Source Leak Reveals About Anthropic's Plans](https://arstechnica.com/ai/2026/04/heres-what-that-claude-code-source-leak-reveals-about-anthropics-plans/) - A persistent background agent, a stealth "Undercover" mode instructing Claude not to mention AI involvement in open source commits, and a virtual assistant codenamed Buddy are among the unreleased features exposed in the accidental npm source map leak.

[Reading Leaked Claude Code Source Code](https://lr0.org/blog/p/claude-code-source/) - A technical walkthrough of the exposed TypeScript codebase, covering a full Vim keybinding state machine, a machine-learning safety classifier in a file called `yoloClassifier.ts`, and hex-encoded companion species names tied to internal model codenames.

[Critical Claude Code Vulnerability: Deny Rules Silently Bypassed Because Security Checks Cost Too Many Tokens](https://adversa.ai/claude-code-security-bypass-deny-rules-disabled/) - Adversa AI's red team found that Claude Code's deny rules stop working silently after 50 subcommands because the security check is disabled to save tokens. I'd bet there are more of these gotchas out there.

[California Governor Newsom Signs First-of-Its-Kind Executive Order on AI](https://www.nytimes.com/2026/03/30/technology/california-ai-executive-order.html?unlocked_article_code=1.XVA.FBAr.cdhCvSbwLFtS&smid=nytcore-ios-share) - Newsom signed an executive order requiring AI vendors with state contracts to document bias and privacy safeguards, letting California set its own oversight standards independent of the US federal government's AI policy.

[Microsoft Closes Worst Quarter on Wall Street Since 2008 on AI Concerns](https://www.cnbc.com/2026/03/31/microsofts-stock-closes-worst-quarter-since-2008-financial-crisis.html) - Investors reset Microsoft's earnings multiple to its lowest since late 2022, with the company losing nearly a quarter of its value this year as AI spending concerns continue to mount.

[Linux Kernel Czar Says AI Bug Reports Aren't Slowing Down or Going Away](https://www.theregister.com/2026/03/26/greg_kroahhartman_ai_kernel/) - Greg Kroah-Hartman can't explain the inflection point in AI-generated kernel bug reports, but says the trend isn't reversing.

[Quantum Technology Firms Race to Market as the Industry Sees an 'Inflection Point'](https://www.cnbc.com/2026/03/30/quantum-computing-firms-go-public-breakthroughs-commercialization.html) - Quantum technology firms are braving turbulent markets to publicly list this year as the nascent industry looks toward commercialization and moves past proof-of-concept.

[Supply Chain Attack on Axios Introduces Malicious npm Dependency](https://socket.dev/blog/axios-npm-package-compromised) - A supply chain attack on Axios introduced a malicious dependency via npm (again). Socket is reporting a fairly [wide blast radius](https://socket.dev/blog/hidden-blast-radius-of-the-axios-compromise).

[These Raspberry Pi Price Hikes Are No Joke](https://www.theverge.com/gadgets/905189/raspberry-pi-price-increases-pi-4-3gb) - The Pi 5 16GB now costs double its original launch price, with increases hitting the Pi 4 3GB model as well — bad news for anyone building compute on a budget. I recommend buying used gear at this point.

[Sony Temporarily Suspends Memory Card Sales Due to Shortages](https://www.theverge.com/tech/902828/sony-sd-cfexpress-memory-card-shortage) - Sony Japan stopped accepting SD and CFexpress card orders from dealers and consumers amid a broader memory card supply crunch with no near-term resolution in sight.

[We Built an Org-Wide AI Agent in 4 Days. Here's What Broke in the Weeks After.](https://daily.dev/blog/we-built-an-org-wide-ai-agent-in-4-days-heres-what-broke-in-the-weeks-after) - A 29,000-line org AI agent built with Codex in four days; credential leaks, silent event-loop deaths, and cascading failures dominated the weeks after launch — the honest post-mortem most teams won't write.

[SQLite Features You Didn't Know It Had](https://slicker.me/sqlite/features.htm) - Modern SQLite includes JSON support, FTS5 full-text search, window functions, strict tables, WAL mode, and generated columns — it has grown well beyond a simple embedded database and deserves a second look.

[Kubernetes RBAC Roles and Permissions Guide](https://daily.dev/blog/kubernetes-rbac-roles-permissions-guide) - A clear guide to Kubernetes RBAC covering Roles, ClusterRoles, bindings, best practices, auditing, and troubleshooting for least-privilege access in production clusters.

[Shell Tricks That Actually Make Life Easier (And Save Your Sanity)](https://blog.hofstede.it/shell-tricks-that-actually-make-life-easier-and-save-your-sanity/) - A practical collection of shell shortcuts grouped by portability — what works everywhere versus Bash/Zsh-specific tricks — focused on the ones that save real time in daily terminal work.

[Google Now Lets Users in the US Change Your Gmail Address. Here's How.](https://www.wired.com/story/how-to-change-your-gmail-address/) - Google has finally added the ability to change your Gmail address without losing your account history or managing a messy transition period.

[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) - MIT - Fully autonomous AI agents system capable of performing complex penetration testing tasks.

[rderaison/bromure](https://github.com/rderaison/bromure) - MIT - Secure, ephemeral browsing in a disposable VM (macOS only).

{{< subscribe >}}
