---
author: Chris Short
date: '2026-07-05'
description: "ClickHouse is winning the observability wars, Vint Cerf retires from Google with a warning for the AI age, Podman 6.0 breaks things on purpose, the BIS eyes the AI bubble, and Kepler gets a rewrite."
draft: false
slug: '316'
title: "DevOps'ish 316: ClickHouse Eats Observability, the Father of the Internet Bows Out, Podman Breaks Things, and More"
---

[**Designing IaC Interfaces That Work for Humans, AI Agents, and Whatever Comes Next**](https://events.iacconf.com/designing-iac-interfaces-july-2026-spotlight/?refid=DevOpsish&utm_campaign=46400040-FY26%20-%20Virtual%20Event%20-%20IaCConf%20Designing%20IaC%20Interfaces%20July%202026&utm_source=DevOpsish&utm_medium=email&utm_content=Email%20placement%20-%20WV%20-%20IaCConf%20Spotlight%20July%202026%20-%20variation%20A) (SPONSOR)

AI agents are changing who, or what, uses your Terraform modules. Join Jinger Meilani, Senior DevOps Engineer at MNTN, to learn how to design reusable, self-service IaC interfaces that reduce misuse and work for humans, AI agents, and whatever comes next.

[**Kepler, re-architected: Improved power accuracy and a community call to action!**](https://www.cncf.io/blog/2026/06/30/kepler-re-architected-improved-power-accuracy-and-a-community-call-to-action/) (8 minute read)

The CNCF's Kubernetes power-monitoring project got a full rewrite. The new architecture drops eBPF, sheds a pile of required privileges, and adds dynamic hardware discovery so the energy numbers actually mean something across mixed fleets. The team is also asking for help validating accuracy, so if you care about sustainability metrics, consider this your invitation.

[**Akrites: The Latest Attempt to Protect Open-Source From AI Attacks Has Arrived**](https://devops.com/akrites-the-latest-attempt-to-protect-open-source-from-ai-attacks-has-arrived/) (7 minute read)

The Linux Foundation stood up Akrites, a single coordination point for finding and fixing open source vulnerabilities before attackers get there first. Jim Zemlin's framing is bleak and accurate: the mean time to exploit is now measured in negative days. Whether another initiative moves the needle or just adds a logo to the pile is the open question.

[**Clickhouse is winning the Observability Wars**](https://matduggan.com/clickhouse-is-winning-the-observability-wars/) (12 minute read)

The argument here is architectural, not tribal. ClickHouse holds its shape as data volume grows, while Elasticsearch, the LGTM stack, and Datadog all hit a wall that forces a fundamental redesign at scale. If you are staring down an observability bill or a re-platforming decision, this one earns its length.

[**WSL container is now available for public preview**](https://devblogs.microsoft.com/commandline/wsl-container-is-now-available-for-public-preview/) (5 minute read)

Microsoft shipped a public preview of native Linux containers on Windows through WSL, complete with a new wslc.exe CLI, an API for programmatic access, virtiofs for roughly 2x faster file access, and Defender plus Intune hooks for the enterprise crowd. Docker Desktop finally has some company on Windows.

[**Podman 6.0 Lands with Breaking Changes, AMD GPUs Support**](https://linuxiac.com/podman-6-0-lands-with-breaking-changes-amd-gpus-support/) (5 minute read)

A major release that is not shy about breaking things. CNI and cgroups v1 are gone, AMD GPU support is in, and there are new machine features to go with the cleanup. Read the breaking changes list before you upgrade anything you actually care about.

[**Want AI Agents That Don't Spill Secrets? Don't Give Them Secrets**](https://auth0.com/blog/want-ai-agents-that-don-t-spill-secrets-don-t-give-them-secrets/) (10 minute read)

The thesis is refreshingly blunt: if you do not want your agent leaking a credential, do not hand it the credential. The piece walks through how secrets sneak into tool schemas and skill prompts, then shows how to keep auth in the deterministic application layer rather than the probabilistic model. Good architecture hygiene for anyone wiring up agents.

[**How the AI bubble could pop and take down the global economy, according to the BIS**](https://www.theregister.com/ai-and-ml/2026/06/29/how-the-ai-bubble-could-pop-and-take-down-the-global-economy-according-to-the-bis/5263793) (6 minute read)

The Bank for International Settlements put the current AI capex spree, north of a trillion dollars in 2026, next to historical bubbles and did not love the resemblance. Their point is not that the tech is fake; it is that capital keeps arriving faster than returns can justify. Sober reading in a hype-soaked week.

[**OpenAI proposes 5% stake to Trump administration to ease Washington pressure**](https://www.cnbc.com/2026/07/02/openai-proposes-us-government-own-5percent-stake-to-address-political-blowback.html) (3 minute read)

OpenAI reportedly floated giving the US government a 5% stake to defuse political heat, after Trump mused in June that Washington possessing a stake in the AI giants would be "a beautiful thing." File this under things that would have sounded absurd a couple of years ago.

[**Vint Cerf, a Father of the Internet, Retires From Google**](https://www.technology.org/2026/07/02/vint-cerf-retires-from-google/) (4 minute read)

One of the actual fathers of the internet is stepping down from Google after 20 years as chief internet evangelist. Cerf co-designed TCP/IP with Bob Kahn in the 1970s, and on his way out he left a warning for the agentic AI crowd: English is too ambiguous for agents to coordinate on, and formal standards are coming whether the vibe-coders like it or not.

[**Qwen 3.6 27B is the sweet spot for local development**](https://quesma.com/blog/qwen-36-is-awesome/) (8 minute read)

Piotr Migdal makes the case that Qwen 3.6 27B is the first local model that actually holds up as general intelligence, backed with benchmarks, llama.cpp setup notes, and roughly 32 tokens per second on an M5 MacBook. If you have been waiting for local inference to stop feeling like a compromise, start here.

[**All you need is PostgreSQL**](https://ebellani.github.io/blog/2026/all-you-need-is-postgresql/) (35 minute read)

A very long, code-heavy walkthrough of building a production-grade financial transaction system on nothing but PostgreSQL 18. It takes the "just use Postgres" meme seriously and actually shows the auditing, write throughput, and query work to back it up. Block out real time for this one.

[**Red Hat ARM Engineer Abandons ARM64 Linux Personal Desktop, Goes Back To AMD Ryzen System**](https://www.phoronix.com/news/Red-Hat-ARM-Engineer-Back-Ryzen) (3 minute read)

Red Hat senior software engineer Marcin Juszkiewicz, of the company's ARM team, spent nearly a year daily-driving an AArch64 Linux desktop and has gone back to an AMD Ryzen box. It is an honest field report on where ARM on the desktop still falls short, from someone with no reason to sugarcoat it.

[**Examining circuit boards from the Space Shuttle's I/O Processor**](https://www.righto.com/2026/06/space-shuttle-io-processor-boards.html) (20 minute read)

Ken Shirriff cracks open two circuit boards from the Space Shuttle's I/O Processor, a separate programmable computer more complex than the main CPU that ran 25 virtual processors on a single physical core. Peak weekend nerd-out material, and a reminder that we solved a form of hardware multithreading a very long time ago.

[**chris-short/respect-the-oracle**](https://github.com/chris-short/respect-the-oracle) - MIT License

A portable agent skill that stops AI coding agents from overfitting or gaming tests they don't own.

[**PlummersSoftwareLLC/TinyRetroPad**](https://github.com/PlummersSoftwareLLC/TinyRetroPad) - Apache License 2.0

A working, Notepad-style Windows text editor in roughly 2.5 KB, forked from Dave's Tiny Editor and built with MASM and Crinkler.

{{< subscribe >}}
