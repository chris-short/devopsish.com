---
author: Chris Short
date: '2026-11-08'
description: "A trojaned Claude Code extension lands on Cursor's marketplace under Anthropic's real ID, a 9.8 Linux TCP use-after-free gets a Claude-written root exploit, OpenAI builds Pando to keep Git up with Codex agents, and AWS says committed capacity is mostly sold through 2027."
draft: true
slug: '334'
title: "DevOps'ish 334: Claude Code gets trojaned on Cursor, a 9.8 Linux TCP bug, OpenAI rebuilds Git, and more"
---

{{< subscribe >}}

[**More AI commits. Less ARC to babysit.**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-11-08) (Sponsor)

Scaling Actions Runner Controller to keep up with AI commit volumes means more nodes to scale, images to patch, and upgrades to plan. WarpBuild runs your GitHub Actions jobs on managed runners, twice as fast at half the cost, in our cloud or yours. Try it with $50 in free credits using code START50.

[**Official Claude Code Extension on Cursor Marketplace Trojanized with Persistent SSH Backdoor**](https://thehackernews.com/2026/10/official-claude-code-vs-code-extension.html) (6 minute read)

Someone published a tampered build of Anthropic's Claude Code extension to Cursor's marketplace under the real *anthropic.claude-code* ID. It wasn't a lookalike. It was the real ID with a 66-line loader stuck on the front. The loader adds an attacker SSH key labeled "svc-telemetry," tries to turn on SSH and open a reverse tunnel, installs persistence (scheduled task, crontab, or LaunchAgent), and beacons host details plus the names of credential-looking environment variables. Versions 2.1.312 and 2.1.313 were live for about 11 hours on October 29 and reached at most 5,000 users. Open VSX, the Microsoft marketplace, and npm were not affected. If you auto-update extensions in Cursor, check *~/.ssh/authorized_keys* now. Uninstalling the extension doesn't clean up what it wrote outside its own directory. Nobody has explained yet how the attacker got publish access under Anthropic's name, and that's the part I'd most like answered.

[**Linux Kernel TCP Flaw With 9.8 CVSS Score Affects Ubuntu, Red Hat and Other Distributions**](https://thehackernews.com/2026/10/linux-kernel-tcp-flaw-with-98-cvss.html) (7 minute read)

CVE-2026-98432 is a use-after-free race in the IPv4 TCP handshake code, and it's been there since Linux 4.4. Anthropic says Claude wrote an exploit that gets unauthenticated root on servers with a multipath TCP listener: 48 minutes to leak a kernel address, then 5 more to get a shell. Go 1.24 and later turn on MPTCP for listening sockets by default, which makes that detail matter more than it sounds. Scores range from 5.9 to 9.8 depending on who you ask. Debian, Oracle, SUSE, and Amazon Linux have shipped fixed kernels for at least some releases. Ubuntu and RHEL hadn't as of October 30, and Red Hat says there's no mitigation it's comfortable recommending. The distro table in this piece is the useful part.

[**PHP2Shell: how to confirm your PHP server is actually patched**](https://www.pixelstech.net/article/1793494754-php2shell%3a-how-to-confirm-your-php-server-is-actually-patched) (7 minute read)

This is the practical follow-up to the last two weeks of PHP2Shell chaos. *php -v* can lie to you in both directions. A patched Ubuntu 24.04 box still reports 8.3.6 because of backports, and an updated host can keep serving from old FPM workers that never restarted. The fix is a small throwaway script you load through the web SAPI to see what's actually answering requests. There's also a good explanation of why *ini_set()* is the wrong place for the mitigations, plus a warning I hadn't seen elsewhere: after you patch, *memory_limit* becomes a soft limit, and crossing the new hard limit kills the process with exit 137 and nothing in *error_log*. That will look exactly like the OOM killer at 2 a.m.

[**Scaling Git at OpenAI**](https://openai.com/index/scaling-git-at-openai/) (22 minute read)

OpenAI built Pando, a Git-compatible backend that now runs its whole monorepo, because Codex agents push far more often than humans ever did. The main trick is dropping repository-wide consistency for causal consistency, so pushes to unrelated branches don't wait on each other. Reads come from cached packfiles served through Git's packfile-uri mechanism. They report median push latency down nearly 80%, close to a petabyte of Git data served per day, and 57 TB in a single hour with over 99% coming from local disk cache. It's written in Rust, it took 10 weeks, and improvements are going upstream rather than into a fork. It's internal only for now, with no release plans. Hacker News folks noted the post skips pushes per second and concurrency numbers, which is fair.

[**AWS Capacity Largely Sold out through 2027, with On-Demand Headroom Reserved**](https://www.infoq.com/news/2026/11/aws-capacity-sold-out/) (2 minute read)

Andy Jassy told a16z that AWS's big committed capacity is mostly spoken for through 2027, with a good chunk of 2028 gone too, while some headroom is held back for On-Demand, EC2, and Bedrock. David Linthicum pushed back, saying sold-out reserved blocks are not the same thing as "you can't launch an instance." The Reddit thread was less reassuring: people are hitting plain EC2 capacity errors, mostly in CI but sometimes in production Kubernetes clusters. One commenter called reserving capacity out of fear "an anti-cloud pattern." They're not wrong, and I expect plenty of teams to do it anyway.

[**Shopify Overexposed Scans GKE Ingresses and Cloud Run for Exposure**](https://www.infoq.com/news/2026/11/shopify-kubernetes-ingresses/) (3 minute read)

Shopify's first try at finding unauthenticated public endpoints read Ingress configs out of the infra repo, and it missed things. Admission controllers rewrote settings, and other tools created Ingresses the repo never saw. Their summary: "the repository shows intent; the cluster shows what is enforced." Version two pulls from GCP Cloud Asset Inventory and sends each candidate a single anonymous request, which cut inconclusive Ingress verdicts by about 80%. Evidence that isn't clear stays "inconclusive" instead of quietly becoming "protected," and they hardened the scanner against SSRF since it hits arbitrary hostnames. It's a nice design writeup if you're building something similar.

[**The 'Pain in the Ass' Math That Could Save Vibe Coding From Itself**](https://www.wired.com/story/software-verification-is-the-hot-new-answer-to-the-ai-safety-crisis/) (6 minute read)

Formal verification has been the thing everyone agrees is great and almost nobody pays for. Now startups like &Truth ($70 million raised), Harmonic, and Truidic are betting AI can write the specs and proofs cheaply enough to change that. One Stanford result did in under half a day, for under $500, what took three experts five months. The skeptics get real airtime too. Antithesis's Will Wilson calls verification "a trap" for math nerds and says his company has found bugs in code customers had already formally verified. Proofcraft worries about "unjustified trust" in AI-written specs. I'm somewhere in between. A proof is only as good as what you told it to prove.

[**Interesting systemd features you may not know about**](https://martinalderson.com/posts/interesting-systemd-features/) (4 minute read)

Martin Alderson found a new use for systemd: babysitting throwaway code written by agents. *systemd-run --user --scope -p MemoryMax=4G -p CPUQuota=200%* caps a leaky script before it takes your box down. *RuntimeMaxSec* keeps an agent from running all night, and *systemd-inhibit* stops the laptop from sleeping mid-run. He also covers timers with *Persistent* and *RandomizedDelaySec*, plus path units that fire when a folder gets a new file. None of this is new to anyone who's lived in unit files, but it suggests the plumbing you need is probably already installed.

[**Fast and slow ways to improve your reputation**](https://www.seangoedecke.com/how-to-get-assigned-interesting-work/) (6 minute read)

You need a reputation to get the important projects, and you need the important projects to get a reputation. Sean Goedecke explains why your manager keeps handing the good stuff to the same senior engineer: that's the safe bet for the manager's own reputation, and manager tenure is short enough that the long-term cost lands on somebody else. The slow fix is shipping small things reliably and making sure people notice. The faster, riskier ones are building a relationship with your skip-level, making side bets, or impressing your fellow engineers on a healthy team. He also points out that complaining about fairness in 1:1s doesn't work. Cynical, maybe, but accurate.

[**InditexTech/kumoss**](https://github.com/InditexTech/kumoss) - Apache-2.0 - Kumoss turns natural-language requests into compliant, plan-validated Terraform/OpenTofu pull requests, with drift correction, policy gates, and human review. Multicloud, bring-your-own LLM.

[**ivov/lisette**](https://github.com/ivov/lisette) - MIT - A little language inspired by Rust that compiles to Go

{{< sponsor >}}
