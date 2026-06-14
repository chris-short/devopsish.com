---
author: Chris Short
date: '2026-06-14'
description: "Fable 5 died by export control, 1,500 AUR packages were hijacked, and AI invented case law until a judge fired everyone."
draft: false
slug: '313'
title: "DevOps'ish 313: Export Controlled, AUR Torched, Lawyers Disqualified, and more"
---

The Claude Fable launch turned into a complete debacle this week and is a cautionary tale of the times we're in. It's also one of the most botched product releases we've witnessed in quite some time. On Tuesday, June 9th, [Claude Fable 5 and Mythos 5 were released](https://www.wired.com/story/anthropic-releases-claude-fable-5-mythos-5/) to every paying customer for a limited time, before it was slated to move to API billing on June 22nd. Anthropic implemented several safeguards (classifiers) to route sensitive topics such as cybersecurity, chemistry, and biology queries to older models. There were additional checks in place that hindered AI researchers and safety folks from doing their work by invisibly doing the same thing. [Anthropic walked back the invisible safety checks](https://www.wired.com/story/anthropic-responds-to-backlash-on-claudes-secret-sabotage-on-ai-research/), saying, "We made the wrong trade-off and we apologize for not getting the balance right." On Thursday, [Microsoft restricted employees](https://www.theverge.com/report/947575/microsoft-claude-fable-5-restricted-internally) from using the latest Claude models due to a 30-day retention policy that Anthropic implemented as yet another safety feature. I have no doubt numerous other organizations would do the same.

Then, on Friday, [the US government weighed in](https://www.anthropic.com/news/fable-mythos-access). According to Anthropic, citing national security concerns, the US government placed export controls on Fable 5 and Mythos 5. The US government was very specific in stating that Anthropic needed to restrict access not only to foreign nations but also to foreign nationals inside the US, including Anthropic's own employees. "The net effect of this order is that we must abruptly disable Fable 5 and Mythos 5 for **all** our customers to ensure compliance," Anthropic said (emphasis theirs). This is quite the release gone wrong. This week's activities really highlight the need for regulatory processes and more coordination between the frontier labs and the US government. But this whole ordeal plays into Anthropic's fear-based marketing strategy, which is unfortunate because fear-mongering is the last thing the world needs from a product like Claude. What an absolute mess.

[Your CI got slower this month. Nobody fixed it.](https://www.mendral.com/?utm_source=devopsish)  
One dep, one job, one cache miss at a time. Pipelines bloat. Nobody owns fixing it because nobody has the time. Mendral profiles your CI, finds the slow steps, and opens PRs that cut real minutes. Better caching, parallel jobs, killing redundant installs and reduces your CI costs. The work a senior engineer would do, if they had a spare week. *SPONSORED*

[Arch Linux's AUR Sees More Than 400 Packages Compromised With Malware](https://www.phoronix.com/news/Arch-Linux-AUR-400-Compromised) - What started as 400 compromised AUR packages turned into over 1,500 by the end of the day. Attackers hijacked orphaned packages and modified PKGBUILDs to add npm as a dependency and run credential-stealing payloads. This is not the official Arch repos; if you are pulling from the AUR in CI/CD pipelines, audit now. The Arch team is working to reset affected content, but they are still encouraging everyone to review PKGBUILD and install script changes when updating.

[The Blight Reaches Microsoft: 73 Repos Disabled in 105 Seconds](https://opensourcemalware.com/blog/miasma-reaches-azure) - The Miasma worm, a variant of the Mini Shai-Hulud campaign from TeamPCP, hit 73 Microsoft GitHub repos across Azure, Azure-Samples, Microsoft, and MicrosoftDocs, including `azure-functions-host` and the entire Durable Task family. GitHub's automated enforcement swept them in 105 seconds. The attack targets developers who open repos in Claude Code, Gemini CLI, Cursor, or VS Code, harvesting cloud credentials and self-replicating into any writable repo. This is the second known Microsoft breach in weeks from the same malware family. If you use `Azure/functions-action` in your pipelines, pay attention.

[NanoClaw and JFrog launch 'immune system' to block AI agents from downloading malicious code](https://venturebeat.com/security/nanoclaw-and-jfrog-launch-immune-system-to-block-ai-agents-from-downloading-malicious-code) - NanoClaw agents now route package, CLI tool, and MCP server requests through JFrog registries, which block malicious downloads and loop back to the agent with a corrected path to safe alternatives. You cannot patch an agent's curiosity, so controlling what it touches is the right architecture for the agentic supply chain problem.

[Claude Opus / Fable / Shitpost](https://artificialconfidence.com/p/claude-opus-fable-shitpost) - Corey Quinn takes Anthropic's Fable 5 pricing model apart: premium rates charged when the safety classifier routes you to a fallback model, mandatory data retention requirements, and a limited availability window that makes it temporary by design. Worth reading if you are budget-planning around Claude in production.

[xAI is looking more like a datacentre REIT than a frontier lab](https://martinalderson.com/posts/xais-new-rental-business/) - A sharp observation that xAI's compute deals with Anthropic and Google look less like a frontier AI lab building toward AGI and more like a profitable data center operator with a compelling narrative. When your competitive moat is rack space, sustaining the frontier story becomes harder.

[A court just held Google responsible for AI Overviews errors](https://www.androidauthority.com/ai-overviews-errors-3676591/) - A German court ruled Google bears accountability for inaccurate AI-generated news summaries. Google's response was a measured non-commitment. This is one of the first cases to hold AI-generated search results accountable, and it will not be the last.

[Judge Learns Lawyers on Both Sides of Case Used AI, Cancels Trial, Kicks Everyone Off the Case](https://www.404media.co/judge-learns-lawyers-on-both-sides-of-case-used-ai-cancels-trial-kicks-everyone-off-the-case/) - A federal judge in Mississippi discovered both sides' attorneys used AI to draft briefs that cited fabricated cases, then canceled the trial and disqualified all four lawyers. If you are using AI to write legal arguments, verifying the citations is not optional.

[GitLab cuts 14% of staff as it scales its platform to serve AI workloads](https://techcrunch.com/2026/06/03/gitlab-cuts-14-of-staff-as-it-scales-its-platform-to-serve-ai-workloads/) - GitLab laid off roughly 350 people while restructuring to handle the infrastructure needs of AI agent workloads. The industry pattern is consistent: headcount goes down, compute spend goes up. Whether the bet pays off depends on whether AI workloads actually land on GitLab's platform.

[Meta Facebook, Instagram, and Messenger went down for four hours](https://www.businessinsider.com/meta-facebook-instagram-messenger-outage-issues-2026-6) - Meta's platforms went dark on June 12, hitting Facebook Ads Manager, Meta Business Suite, Messenger, and Instagram. WhatsApp was not affected. Root cause per the company: "technical issue." Their long-standing policy of not explaining outages in any useful detail remains intact.

[Everything Apple Announced at WWDC 2026](https://www.wired.com/story/everything-apple-announced-at-wwdc-2026/) - iOS 27, macOS Golden Gate, a rebuilt Siri rebranded as Siri AI, Liquid Glass opacity controls, child accounts, iCloud shared albums at full resolution on Android and Windows, and a lot of bug fixes described as improvements. The (1.0.0 release of the apple/container)[https://github.com/apple/container/releases/tag/1.0.0] the next day suggests the platform is serious about developer tooling on Apple Silicon.

[Build 2026: Furthering Windows as the trusted platform for development](https://blogs.windows.com/windowsdeveloper/2026/06/02/build-2026-furthering-windows-as-the-trusted-platform-for-development/) - Microsoft announced local AI dev tools, secure agent execution containers, and the Surface RTX Spark Dev Box at Build 2026. The Spark pairs an Arm CPU, Blackwell GPU, and 128GB unified memory, which is a serious local inference workstation if you are running agents on-prem. But one of the most exciting things is Coreutils for Windows. The older I get the more Linux-like Windows becomes.

[Seattle City Council passes emergency data center moratorium and policy framework](https://council.seattle.gov/2026/06/09/city-council-passes-emergency-data-center-moratorium-and-policy-framework/) - Seattle passed emergency legislation to freeze new data center construction while the city studies environmental, infrastructure, and economic impacts. Unanimous vote. When a tech hub city calls a timeout on data centers, that is a signal worth tracking.

[To study how chips really work, MIT researchers built their own operating system](https://news.mit.edu/2026/to-study-how-chips-really-work-mit-researchers-built-their-own-operating-system-0610) - MIT built Fractal, a custom OS kernel for studying processor behavior meticulously, and used it to find previously unidentified vulnerabilities in Apple's M1, including the first Phantom speculative attack evidence on Apple Silicon. The right tool for the job sometimes means building the tool yourself.

[NVIDIA Engineer Devises Patch To Significantly Reduce GCC Bootstrap Time](https://www.phoronix.com/news/NVIDIA-Reduce-GCC-Bootstrap) - An NVIDIA engineer posted patches that cut GCC native bootstrap configure time by 43% and overall bootstrap wall time by 15% with no change to generated output. If you regularly build GCC from source, this is a concrete quality-of-life improvement.

[GGUF vs MLX: A Decision Guide, Not Another Benchmark](https://muhammadraza.me/2026/gguf-vs-mlx-decision-guide/) - A five-question framework for choosing between GGUF and MLX model formats, focused on portability needs, workload characteristics, and training requirements rather than raw benchmark numbers. Practical and honest about tradeoffs.

[Monitor LLM routing with the Kubernetes Inference Extension](https://www.datadoghq.com/blog/llm-routing-kubernetes-inference-extension/) - Datadog walks through how the Kubernetes Gateway API's Inference Extension routes LLM requests based on backend serving states and how to validate routing effectiveness with Datadog. Good reference material if you are building LLM inference infrastructure on Kubernetes.

[How LLMs Actually Work](https://www.0xkato.xyz/how-llms-actually-work/) - A clear explanation of transformer architecture covering tokenization, embeddings, attention mechanisms, and next-token prediction. Useful for sharing with colleagues who are building on these systems without a solid mental model of what is actually happening.

[Life is too short for a slow terminal](https://mijndertstuij.nl/posts/life-is-too-short-for-a-slow-terminal/) - A hands-on breakdown of achieving a 30ms zsh startup without frameworks, including why plugin managers add overhead you never needed, and how to get completions, syntax highlighting, autosuggestions, fzf, and direnv running lean.

[VibeOS - Fully Hallucinated Operating System](https://www.youtube.com/watch?v=z3pV6FHvcgM) - Exactly what it sounds like. Also, I'm not even mad. I'm impressed.

[apple/container](https://github.com/apple/container/releases/tag/1.0.0) - Apache License 2.0 - A tool for creating and running Linux containers using lightweight virtual machines on a Mac, written in Swift and optimized for Apple Silicon. 1.0 ships with a new `container machine` feature for long-lived Linux environments and a TOML configuration system replacing UserDefaults-backed properties.

[microsoft/pg_durable](https://github.com/microsoft/pg_durable) - PostgreSQL License - PostgreSQL in-database durable execution.

[losfair/zeroserve](https://github.com/losfair/zeroserve) - MIT License - Zero-config, fast `io_uring`-based HTTPS server.

[Andyyyy64/whichllm](https://github.com/Andyyyy64/whichllm) - MIT License - Find the local LLM that actually runs and performs best on your hardware, ranked by real, recency-aware benchmarks rather than parameter count. One command to run it. I still like `llmfit` more.

[oxidecomputer/mitos](https://github.com/oxidecomputer/mitos) - No license found - ASCII art generator for brand assets. I think [it did a pretty good job](https://devopsish.com/313/devopsish-ascii-art.txt).

{{< subscribe >}}
