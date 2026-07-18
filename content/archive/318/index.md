---
author: Chris Short
date: '2026-07-19'
description: "Linus tells the AI objectors they can fork the kernel, SK Hynix warns 2027 brings the worst memory shortage yet, John Deere finally bows to right-to-repair, Anubis gets picked apart, and Kimi K3 makes the case for open models."
draft: false
slug: '318'
title: "DevOps'ish 318: Linus Makes Peace With AI, the Worst Memory Shortage Yet, Deere Bows to Repair, and More"
---

[**When your Kubernetes fleet can't drift, upgrades stop being a gamble.**](https://www.siderolabs.com/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=omni-upgrades) (SPONSOR)

Kubernetes upgrades have a way of sliding to next quarter, because one drifted node is enough to derail a routine upgrade. Talos Linux is immutable, so every node runs from the same image and can't drift apart. Talos Omni upgrades the OS and Kubernetes together, one cluster at a time across the fleet, so the upgrade you dreaded turns into a non-event.

93% of teams have already hit an AI-caused infrastructure incident, but only 30% have a policy. Spacelift surveyed 406 leaders on who's actually ready for AI.

[Download the report](https://spacelift.io/infrastructure-automation-survey-2026?utm_campaign=48496167-FY26%20-%20WW%20-%20Strategic%20-%20infrastructure%20Automation%20Report%202026&utm_source=DevOpsish&utm_medium=email&utm_content=DevOpsish%20-%20Infrastructure%20automation%20survey) to see what the most advanced teams do differently, and [watch the event](https://platformengineering.org/events/the-ai-readiness-gap-where-infrastructure-teams-are-getting-ai-wrong-2026-07-16?utm_source=spacelift-external) where we unpacked the data. (SPONSOR)

[**Building a Custom Metrics Exporter for Kubernetes**](https://kubernetes.io/blog/2026/07/14/custom-metrics-exporter-kubernetes/) (8 minute read)

A hands-on tutorial for writing your own Prometheus exporter in Go, packaging it as a container, and wiring it into a cluster so you can autoscale on real signals like queue depth instead of just CPU and memory. Counters, gauges, histograms, naming conventions, and HorizontalPodAutoscaler integration, all in one walkthrough.

[**Linus Torvalds Puts His Foot Down on AI in the Kernel**](https://lore.kernel.org/all/CAHk-%3Dwi4zC%2BZe8e%2Bp3tMv8TtG_80KzsZ1syL9anBtmEh5Z40vg@mail.gmail.com/) (2 minute read)

In a July 2026 LKML reply, Linus Torvalds says Linux is not an anti-AI project, calls AI a clearly useful tool, and tells the objectors they can fork the kernel or walk away. Decisions stay on technical merit, not fear of new tooling.

[**Who does Anubis actually stop?**](https://fzakaria.com/2026/07/09/who-does-anubis-actually-stop) (4 minute read)

A pointed critique of Anubis, the proof-of-work HTTP proxy, arguing it barely slows sophisticated scrapers and AI crawlers while taxing the time and energy of ordinary human visitors. The author ships a tool to bypass the challenge and does the math on all that wasted human effort.

[**Shipyard: How We Built Slack's Next-Generation EC2 Platform**](https://slack.engineering/shipyard-how-we-built-slacks-next-generation-ec2-platform/) (14 minute read)

Slack's engineering team walks through Shipyard, the platform they built to manage EC2 compute at scale, and the architecture and design calls behind it. Worth a read if you run a lot of instances and want someone else's scar tissue.

[**ClickHouse on Docker Hardened Images**](https://clickhouse.com/blog/docker-hardened-images) (8 minute read)

ClickHouse now ships as a Docker Hardened Image: a minimal, security-hardened build that carries only what the database needs and passes enterprise vulnerability scans, with no change to how ClickHouse actually behaves.

[**Karpenter + Cluster API**](https://a-cup-of.coffee/blog/karpenter-capi-ovh/) (17 minute read)

One engineer's journey autoscaling an OVH cluster deployed via Cluster API, using Karpenter and its cluster-api provider with MKS as the management cluster. Long, detailed, and honest about the rough edges.

[**Rotating Postgres Credentials Without Dropping a Single Connection**](https://the-practical-developer.online/posts/rotating-postgres-credentials-without-downtime/) (9 minute read)

A walkthrough of zero-downtime Postgres credential rotation in Node.js, swapping connection pools instead of bouncing services so no live connection gets dropped. The kind of unglamorous reliability work that saves you at 2 a.m.

[**SK Hynix CEO Sees Worst-Ever Memory Supply Shortage in 2027**](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) (2 minute read)

SK Hynix CEO Kwak Noh-jung tells Reuters the memory industry is headed for its worst-ever supply shortage in 2027, with AI demand set to outpace production beyond 2030. If your capacity planning assumes cheap RAM forever, it's past time to adjust.

[**John Deere Owners Get the Right to Repair Their Own Equipment Under a New FTC Settlement**](https://apnews.com/article/john-deere-right-to-repair-agriculture-equipment-cb7514ffedb95c130a976af661f2bc02) (1 minute read)

The US FTC and several state attorneys general reached a right-to-repair settlement with Deere & Co., forcing the farm equipment giant to let farmers and independent shops fix their own machines after years of withheld repair software. A win worth noting.

[**You Paid [Thom Holwerda], a Long-Time Linux User, to Use Windows 11 Exclusively for a Month: Here's How It Went**](https://www.osnews.com/story/145459/you-paid-me-a-long-time-linux-user-to-use-windows-11-exclusively-for-a-month-heres-how-it-went/) (22 minute read)

OSNews editor Thom Holwerda takes reader money to run Windows 11 as his only OS for a month and documents the driver pain, inconsistent UI, forced online accounts, telemetry, and ads before going back to Linux. Exactly as fun as it sounds. Reminds me that I'm fortunate to not have to touch Windows often.

[**Kimi K3: Open Frontier Intelligence**](https://www.kimi.com/blog/kimi-k3) (18 minute read)

Is China surpassing the US and EU with improving open models? Moonshot AI introduces Kimi K3, an open frontier model. Kimi K3 falls short of the top proprietary models, Claude Fable 5 and GPT 5.6 Sol, in overall capability and user experience, but still delivers frontier-level results across Kimi's evaluation suite and beats other tested open and closed models on most benchmarks. On certain tasks like GPU kernel optimization, it holds up competitively against Fable 5 while clearly surpassing Opus 4.8, GPT 5.6 Sol, and GPT 5.5.

[**The Great Digital Fatigue: How Digital Burnout Is Changing Social Media Use**](https://blog.incogni.com/digital-fatigue-and-burnout/) (9 minute read)

As someone who helps manage social media accounts for a large open source project, I found this interesting. A 2026 Incogni survey finds that digital burnout is changing how people use social media: posting less, guarding who sees their content, and pulling back amid political division and mental health concerns. Feels about right.

[**vshulcz/deja-vu**](https://github.com/vshulcz/deja-vu/) - MIT - Memory layer for coding agents: search, MCP recall, auto-context, secret redaction, stats, and share/sync over the session logs that Claude Code, Codex, opencode, Cursor, Gemini CLI, aider, Antigravity, Grok Build, and Qwen Code already write. One zero-dependency binary.

[**JustVugg/colibri**](https://github.com/JustVugg/colibri) - Apache-2.0 - Run GLM-5.2 (744B MoE) on a 25GB-RAM consumer machine. Pure C, zero dependencies, experts streamed from disk. A tiny engine for an immense model.

[**clawkwork/clawk**](https://github.com/clawkwork/clawk) - Apache-2.0 - Give coding agents a disposable Linux VM, not your laptop.

[**perber/leafwiki**](https://github.com/perber/leafwiki) - MIT - A self-hosted wiki that ships as a single Go binary using SQLite and Markdown on disk, with no external database required.

{{< subscribe >}}
