---
author: Chris Short
date: '2026-02-08'
draft: false
slug: '296'
title: "DevOps'ish 296: OpenClaw flaws, Notepad++ hit, and Ingress NGINX CVEs"
---

Last week, the world was fawning over ~~Clawdbot~~ ~~Moltbot~~ OpenClaw. This week was an episode of Deadliest Catch where the boats all filled their hulls at the first stop. What they caught were a bunch of [backdoors](https://www.straiker.ai/blog/how-the-clawdbot-moltbot-ai-assistant-becomes-a-backdoor-for-system-takeover), [API keys](https://www.theregister.com/2026/01/27/clawdbot_moltbot_security_concerns/), and only King Triton 🧜‍♂️ knows [what else](https://www.wiz.io/blog/exposed-moltbook-database-reveals-millions-of-api-keys) will emerge from the murky depths.

Another piece of software had an even crazier week. [Notepad++ shared they were the target of nation-state hackers](https://notepad-plus-plus.org/news/hijacked-incident-info-update/), "The incident began in June 2025. Multiple independent security researchers have assessed that the threat actor is likely a Chinese state-sponsored group, which would explain the highly selective targeting observed during the campaign."

[Multiple CVEs in Ingress NGINX](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue%20state%3Aclosed%20CVE%20Ingress%20NGINX%20closed%3A%3E%40today-1w) were disclosed. You are going to have to touch those sooner rather than later. Reminder: Ingress NGINX retirement is next month (and there won't be security updates).

**Editor's Note**: Huge thanks to Tremolo Security for sponsoring! Also, we'll be on vacation next week, so there won't be a newsletter the week of February 16th.

[Short Lived Tokens With Vault Without The Static ServiceAccount](https://www.tremolo.io/post/short-lived-tokens-with-vault-without-the-static-serviceaccount?utm_source=devopsish&utm_medium=newsletter&utm_campaign=296)  
Learn how Tremolo Security’s OpenUnison enables issuing short-lived Vault tokens without static Kubernetes ServiceAccounts, delivering identity-driven, ephemeral credentials with reduced blast radius. This post walks through using OpenUnison and OIDC with Vault to simplify rotation and strengthen workload security in modern Kubernetes environments. _SPONSORED_

[The Tech Elites in the Epstein Files](https://www.wired.com/story/epstein-files-tech-elites-gates-thiel-musk/) - The DOJ released over 3 million Epstein-related documents revealing the extent of Big Tech figures' connections to Jeffrey Epstein. This was also the most popular link I shared this week.

[Anthropic's New Cowork Plugins Prompt Sell-Off in Software Shares](https://www.siliconrepublic.com/business/anthropics-new-cowork-plug-ins-prompt-sell-off-in-software-shares) - Anthropic's latest Cowork plugins are triggering significant market sell-offs in software and professional services stocks as investors worry about AI automation replacing existing solutions. The plugins are in their infancy; imagine what happens if they get really good someday. I think nations will have to rethink their economies in our lifetimes, especially the United States.

["You Had One Job": Why Twenty Years of DevOps Has Failed to Do It](https://www.honeycomb.io/blog/you-had-one-job-why-twenty-years-of-devops-has-failed-to-do-it) - DevOps' core mission of establishing feedback loops connecting developers with production has largely failed because existing tools got in the way. AI may finally be able to help address this but the proof is in the pudding.

[OpenTelemetry Collector vs Agent: How to Choose the Right Telemetry Approach](https://www.cncf.io/blog/2026/02/02/opentelemetry-collector-vs-agent-how-to-choose-the-right-telemetry-approach/) - A guide comparing OpenTelemetry Collectors with agents, helping teams decide which telemetry architecture fits their observability needs

[Introducing Node Readiness Controller](https://kubernetes.io/blog/2026/02/03/introducing-node-readiness-controller/) - A new Kubernetes project enabling declarative management of node taints based on custom health signals, ensuring workloads only schedule on nodes meeting infrastructure-specific readiness requirements

[New Conversion from cgroup v1 CPU Shares to v2 CPU Weight](https://kubernetes.io/blog/2026/01/30/new-cgroup-v1-to-v2-cpu-conversion-formula/) - An improved quadratic conversion formula for mapping cgroup v1 CPU shares to cgroup v2 CPU weight, addressing CPU priority allocation issues for Kubernetes workloads

[Unconventional PostgreSQL Optimizations](https://hakibenita.com/postgresql-unconventional-optimizations) - Creative optimization techniques for PostgreSQL queries beyond standard approaches, including constraint-based pruning, function-based indexing, and hash indexes for uniqueness on large values

[Exploring Solutions to Tackle Low-Quality Contributions on GitHub](https://github.com/orgs/community/discussions/185387) - GitHub is investigating tools and policies to help maintainers manage spam and low-quality pull requests, particularly those generated by AI. If you have ideas, I'm sure they'd like to hear them.

[FBI Stymied by Apple's Lockdown Mode After Seizing Journalist's iPhone](https://arstechnica.com/tech-policy/2026/02/fbi-stymied-by-apples-lockdown-mode-after-seizing-journalists-iphone/) - Apple's Lockdown Mode successfully blocked the FBI from accessing a journalist's iPhone, which is pretty badass.

[Claude Code: Connect to a Local Model When Your Quota Runs Out](https://boxc.net/blog/2026/claude-code-connecting-to-local-models-when-your-quota-runs-out/) - How to switch from Anthropic's Claude to locally-hosted models when you hit API usage quota limits using tools like LM Studio or llama.cpp

[The TV Industry Finally Concedes That the Future May Not Be in 8K](https://arstechnica.com/gadgets/2026/01/lg-joins-the-rest-of-the-world-accepts-that-people-dont-want-8k-tvs/) - Stop trying to make ~~fetch~~ 8K happen. The graph says it all.

[Nvidia's Plan to Invest up to $100 Billion in OpenAI Has Stalled, WSJ Reports](https://www.reuters.com/business/nvidias-plan-invest-up-100-billion-openai-has-stalled-wsj-reports-2026-01-31/) - Nvidia's planned $100 billion OpenAI investment has stalled after internal doubts surfaced, with CEO Jensen Huang privately questioning OpenAI's business strategy

[When Capex Beats Headcount: What Amazon's Layoffs Actually Mean](https://techtrenches.dev/p/when-capex-beats-headcount-what-amazons) - Amazon's 30,000 layoffs represent a strategic shift prioritizing AI infrastructure spending over engineering talent, despite leadership messaging about "reducing bureaucracy"

[ramonvermeulen/whosthere](https://github.com/ramonvermeulen/whosthere) - A Go-based LAN discovery TUI tool performing unprivileged, concurrent scans using mDNS and SSDP to identify connected devices. Apache-2.0 License

[metaspartan/mactop](https://github.com/metaspartan/mactop) - A terminal-based monitoring tool for Apple Silicon Macs displaying real-time CPU, GPU, memory, power, and temperature metrics. MIT License

[DrSkyle/CloudSlash](https://github.com/DrSkyle/CloudSlash) - An autonomous AWS infrastructure optimization platform that finds waste via dependency graph analysis and enables safe remediation with Terraform state restoration. AGPL-3.0 License

[sqldef/sqldef](https://github.com/sqldef/sqldef) - Idempotent schema management for MySQL, PostgreSQL, SQLite3, and SQL Server using plain SQL DDLs to automatically generate and apply migrations. MIT License

[steipete/RepoBar](https://github.com/steipete/RepoBar) - A macOS menu bar app for glanceable GitHub repo status, including CI, releases, traffic, and activity without opening a browser. MIT License

{{< subscribe >}}
