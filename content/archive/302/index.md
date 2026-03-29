---
author: Chris Short
date: '2026-03-29'
description: "The TeamPCP supply chain attack expands to Trivy's Docker images, Google's Sashiko brings AI code review to the Linux kernel, and more in this week's DevOps'ish"
draft: false
slug: '302'
title: "DevOps'ish 302: Trivy Supply Chain Attack, AI Reviews the Linux Kernel, and More"
---

Supply chain security had a rough week. The TeamPCP campaign didn’t just hit Trivy once — it kept going, expanding to compromised Docker images for versions 0.69.4 through 0.69.6, then spreading to LiteLLM and Telnyx. There’s solid coverage across multiple sources in this edition; if you run Trivy in CI/CD, this week is required reading. No exceptions.

On the AI governance side, the DOD’s attempt to block Anthropic from federal contracts hit a courtroom wall. A federal judge deemed it to look more like retaliation than policy. Anthropic, meanwhile, is pushing back against separate claims that it could remotely sabotage its own models during a national security event. The gap between what AI companies can actually do and what people think they can do remains impressively wide.

Sashiko is worth your full attention. Google engineers built an agentic AI code-review system for the Linux kernel, found 53% of bugs that human reviewers missed, and then handed the project to the Linux Foundation. That’s the right governance move and a genuinely compelling result. More of that, please.

[The era of the "black box" CI runner is over](https://fandf.co/4bPRygB)  
Your CI is slow and it’s not the runner’s fault. It’s the 45-second cold starts, the sequential  steps, and the log files you’re scrolling through at 11pm. Depot CI is a new CI engine that runs your existing GitHub Actions workflows. Jobs start in 2-3 seconds. Steps run in parallel. You can SSH into a failing job instead of guessing from logs. One command to migrate, $0.0001/sec to run. Same YAML, same actions, no rewrite. *SPONSORED*

## Events

[Cloud Native Days Romania](https://cloudnativedays.ro/)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania’s community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[Trivy Supply Chain Attack Expands to Compromised Docker Images](https://socket.dev/blog/trivy-docker-images-compromised) - Docker images for Trivy versions 0.69.4, 0.69.5, and 0.69.6 were found to contain malware and published to Docker Hub without corresponding GitHub releases, expanding the scope of the TeamPCP infostealer campaign targeting Aqua Security’s toolchain.

[Guidance for Detecting, Investigating, and Defending Against the Trivy Supply Chain Compromise](https://www.microsoft.com/en-us/security/blog/2026/03/24/detecting-investigating-defending-against-trivy-supply-chain-compromise/) - Microsoft’s security team analyzes how threat actors compromised the trusted Trivy vulnerability scanner distribution to inject credential-stealing malware into CI/CD pipelines globally, and provides defensive recommendations.

[The TeamPCP Supply Chain Attack Evolves](https://www.reversinglabs.com/blog/teampcp-supply-chain-attack-spreads) - A malicious campaign targeting security tools has expanded from Trivy and Checkmarx to compromise LiteLLM and Telnyx packages, stealing cloud credentials and secrets through a cascading supply chain attack.

[How to Know If the Trivy Supply Chain Attack Hit You](https://pulse.latio.tech/p/how-to-know-if-the-trivy-supply-chain) - A security analysis of the March 2026 Trivy malware compromise explaining detection issues, remediation procedures, and prevention strategies for organizations that may be vulnerable.

[Google Engineers Launch “Sashiko” for Agentic AI Code Review of the Linux Kernel](https://www.phoronix.com/news/Sashiko-Linux-AI-Code-Review) - An agentic AI code review system for the Linux kernel, funded by Google and transferred to the Linux Foundation, found 53% of bugs in an unfiltered set of upstream issues that human reviewers missed. Check it out at <https://sashiko.dev/>

[Anthropic Denies It Could Sabotage AI Tools During War](https://www.wired.com/story/anthropic-denies-sabotage-ai-tools-war-claude/) - The Department of Defense alleges Anthropic could manipulate its models in the middle of armed conflict; company executives argue that’s technically impossible and are pushing back publicly. This level of control over a product as widely used as Claude would be next to impossible to manage, let alone detect in real time if a single response violates a moral imperative.

[Migrating a 1TB PostgreSQL from AWS to Azure with pgcopydb](https://underthehood.meltwater.com/blog/2026/03/19/migrating-a-1tb-postgresql-from-aws-to-azure-with-pgcopydb/) - Meltwater engineers describe their experience using the open-source tool pgcopydb to transfer a large PostgreSQL database between cloud providers, covering migration strategies, Kubernetes execution, and lessons learned from common pitfalls.

[Memory Crisis: The Latest DRAM Chips from Micron, Samsung, SK Hynix](https://www.cnbc.com/2026/03/20/memory-crisis-latest-dram-chips-micron-samsung-sk-hynix.html) - Parts of the market are asking whether peak tightness in DRAM margins has arrived, as the chip shortage shows no signs of easing and AI infrastructure demand continues to pressure supply with no relief until 2030\.

[OpenAI Shutters Its Sora Short-Form Video App as Company Reels in Costs](https://www.cnbc.com/2026/03/24/openai-shutters-short-form-video-app-sora-as-company-reels-in-costs.html) - OpenAI is closing the standalone Sora short-form video app that went viral after its launch six months ago, while the company tries to rein in costs ahead of its planned IPO. Do Meta Ray-Bans next, please (we learned nothing from Google Glass)\!

[The Rise of the Ray-Ban Meta Creep](https://www.wired.com/story/the-rise-of-the-ray-ban-meta-creep/) - Between pickup artists and juvenile pranksters, Ray-Ban Meta smart glasses are becoming associated with pests of all kinds, raising fresh questions about wearable surveillance in public spaces.

[CanisterWorm](https://www.endorlabs.com/learn/canisterworm) - A campaign of malicious npm packages uses installation scripts to steal developer credentials and automatically inject malware into victims’ own packages, creating a self-propagating worm across the open source ecosystem.

[cq: Stack Overflow for Agents](https://blog.mozilla.ai/cq-stack-overflow-for-agents/) - [Mozilla.ai](http://Mozilla.ai) introduces cq, a shared knowledge platform that enables AI agents to query past learnings and contribute discoveries, helping prevent redundant problem-solving across isolated agent systems.

[Data Centers Embrace 800V Power Shift](https://spectrum.ieee.org/data-center-dc) - An exploration of whether switching data centers from lower-voltage to 800V DC power systems could meaningfully improve energy efficiency while supporting the growing demands of AI infrastructure.

[Arm Is Now Making Its Own Chips](https://www.wired.com/story/chip-design-firm-arm-is-making-its-own-ai-cpu/) - The chip design firm says Meta, OpenAI, Cerebras, and Cloudflare are among the first customers of its new artificial intelligence hardware, denoting a significant shift from licensing to direct silicon.

[Framework CEO Tears Down the MacBook Neo](https://www.youtube.com/watch?v=uvYt1GgcsUI) - Framework’s CEO does a live teardown comparing their latest laptop to Apple’s MacBook Neo, making the case for right-to-repair and modular design in an era of increasingly sealed hardware.

[AI ‘Aha’ Team Meetings](https://larahogan.me/blog/ai-aha-team-meetings/) - Lara Hogan proposes regular team meetings where engineers share small learning moments and discoveries about using AI tools, fostering vicarious learning and psychological safety around this quickly evolving technology.

[Eliminating the ‘Rego Tax’: How AI Orchestrators Automate Kubernetes Compliance](https://next.redhat.com/2026/03/20/eliminating-the-rego-tax-how-ai-orchestrators-automate-kubernetes-compliance/) - AI orchestrators streamline Kubernetes compliance by automatically generating OPA Gatekeeper policies from live cluster data via the Model Context Protocol, decreasing the manual burden of writing Rego.

[Introducing function-kro: YAML+CEL Composition Meets Crossplane](https://blog.crossplane.io/function-kro-yaml-cel/) - A new Crossplane composition function brings the YAML+CEL authoring model of kro into Crossplane’s pipeline architecture, permitting users to define Kubernetes resources with simplified syntax and dependency management.

[Ubuntu’s Snap Affected by Local Privilege Escalation Vulnerability](https://www.phoronix.com/news/Ubuntu-Snapd-High-Vulnerability) - A high-severity local privilege escalation vulnerability has been disclosed in Ubuntu’s snapd daemon, affecting systems running Snap-packaged applications across Ubuntu releases.

[North Carolina Tech Worker Found Guilty of Insider Attack Netting $2.5M Ransom](https://cyberscoop.com/cameron-curry-insider-attack-washington-tech-company/) - A 27-year-old contractor was convicted of extorting his former employer by stealing corporate payroll data and threatening to expose pay inequity unless the company paid him $2.5 million.

[Open Source Is Critical Infrastructure, Not Just a Development Model](https://allthingsopen.org/articles/open-source-critical-infrastructure-openinfra-alignment) - Open source has evolved from a development approach into essential global infrastructure, with organizations valuing its importance for digital sovereignty, economic value, and coordinated collaboration across industries and governments.

[When Did Every AWS Service Launch?](https://medium.com/@brookejamieson/when-did-every-aws-service-launch-c4a414288b72) - From a friend of the newsletter, Brooke Jamieson, a comprehensive chronological compilation of AWS service launch dates from SQS in 2004 through 2026, with links to original announcements for each service.

[Migrating Etsy’s Database Sharding to Vitess](https://www.etsy.com/codeascraft/migrating-etsyas-database-sharding-to-vitess) - Etsy’s engineering team shares how they migrated their database sharding layer to Vitess, covering planning, execution challenges, and operational trade-offs involved in migrating a large-scale e-commerce database infrastructure.

[Markdown Ate the World](https://matduggan.com/markdown-ate-the-world/) - A look at how Markdown became the dominant writing format by offering simplicity and universal compatibility, eventually displacing complex proprietary formats that plagued users with corruption and version chaos.

[The Tmux Intro I Wish I Had Gotten](https://www.simplethread.com/the-tmux-intro-i-wish-i-had-gotten/) - A practical guide to configuring tmux from scratch using ergonomic key bindings and custom key tables instead of the confusing default bindings most people give up on early.

[Small Programming Tricks Matter](https://will-keleher.com/posts/small-programming-tricks-matter/) - Engineering productivity is noticeably enhanced by accumulating practical knowledge nuggets — useful command-line tricks, database techniques, and language features — that don’t require extensive prerequisite understanding to apply.

[metalbear-co/mirrord](https://github.com/metalbear-co/mirrord) - MIT - Connect your local process and your cloud environment to run local code in cloud conditions without deploying.

[hectorvent/floci](https://github.com/hectorvent/floci) - MIT - Light, fluffy, and always free AWS local emulator for development and testing.

[czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) - MIT - An MCP server for Claude Desktop, Claude Code, Windsurf, and Cursor to build n8n workflows on your behalf.

[pyodide/pyodide](https://github.com/pyodide/pyodide) - MPL-2.0 - Python distribution for the browser and Node.js based on WebAssembly.

[bramcohen/manyana](https://github.com/bramcohen/manyana) - Public Domain - A version control system built on CRDTs where merges never fail and always converge to the same result.

[jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) - MIT - A Claude Code plugin that shows what’s happening in real time: context usage, active tools, running agents, and todo progress.

[wasmerio/edgejs](https://github.com/wasmerio/edgejs) - MIT - A secure JavaScript runtime designed for edge computing and AI workloads.

{{< subscribe >}}
