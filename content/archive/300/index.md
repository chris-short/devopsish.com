---
author: Chris Short
date: '2026-03-15'
draft: false
slug: '300'
title: "DevOps'ish 300: High blast radii, another SUSE Sale, and more"
---

I'm starting to get the feeling people need to reframe their thinking about AI and jobs. I know Amazon started to shrink the moment they had to start paying Nvidia and TSMC for chips for AI workloads. The AI frenzy has bled into every facet of tech at this point. The chip buying frenzy has also invaded every nook and cranny of tech company budgets. You're either spending on tokens or chips. The larger tech employers are doing both. Just the past few weeks Amazon has had another round of layoffs, Block cut 40% of its staff, and [others have laid off significant numbers of employees](https://www.networkworld.com/article/4143749/tech-layoffs-surpass-45000-in-early-2026.html). Meanwhile, Anthropic says their impact on the job market [isn't as dramatic as it seems](https://shortcdn.com/devopsish/Anthropic-Labor-market-impacts-of-AI-A-new-measure-and-early-evidence.pdf). Both cannot be true at the same time. Folks are truly missing the big story right in front of them: building AI tooling is causing layoffs to offset dramatic increases in CAPEX spending. The chips cost dramatically more to procure and operate.

**Editor's note**: I need feedback to help improve newsletter quality and to provide potential sponsors with data they require. Starting this issue, I'm gathering metrics on newsletter opens and clicks.

[**Secure Access to Cloud Services from Your Cluster with a Security Token Service**](https://www.tremolo.io/post/secure-access-to-cloud-services-from-your-cluster-with-a-security-token-service?utm_source=devopsish&utm_medium=newsletter&utm_campaign=299)  
Securely connect your Kubernetes workloads to cloud services without long-lived credentials using a Security Token Service pattern. This post shows how OpenUnison validates ServiceAccount identity and issues short-lived, service-specific tokens to reduce credential exposure and improve authorization posture. _SPONSORED_

## Events

[Cloud Native Days Romania](https://cloudnativedays.ro/)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania’s community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[Announcing the AI Gateway Working Group](https://kubernetes.io/blog/2026/03/09/announcing-ai-gateway-wg/) - The Kubernetes community launches a new working group focused on developing standards and best practices for networking infrastructure supporting AI workloads, including token-based rate limiting and AI-specific routing patterns

[In Wake of Outage, Amazon Calls Upon Senior Engineers to Address Issues Created by 'Gen-AI Assisted Changes'](https://www.tomshardware.com/tech-industry/artificial-intelligence/amazon-calls-engineers-to-address-issues-caused-by-use-of-ai-tools-report-claims-company-says-recent-incidents-had-high-blast-radius-and-were-allegedly-related-to-gen-ai-assisted-changes) - Amazon convenes senior engineers to address service disruptions caused by AI-generated code changes, with reports indicating recent incidents had "high blast radius"

[Pwn Request: Scanning GitHub for the Vulnerability That Took Down Trivy](https://www.plerion.com/blog/pwn-request-scanning-github-for-the-vulnerability-that-took-down-trivy) - Misconfigured GitHub Actions workflows using `pull_request_target` enabled a widespread vulnerability affecting 48 repositories, including major cloud and security tools

[AWS Introduces Nested Virtualization on EC2 Instances](https://www.infoq.com/news/2026/03/aws-ec2-nested-virtualization/) - AWS now enables running virtual machines within EC2 instances using KVM or Hyper-V, a long-requested feature addressing use cases like mobile emulation and hardware simulation

[NanoClaw and Docker Team Up to Isolate AI Agents Inside MicroVM Sandboxes](https://thenewstack.io/nanoclaw-docker-sandboxes-ai-agents/) - NanoClaw partners with Docker to run AI agents inside isolated MicroVMs, offering a security-focused, open-source alternative to OpenClaw

[MariaDB Backs Down on Galera Removal After Community Outcry](https://www.theregister.com/2026/03/09/mariadb_galera/) - MariaDB Corporation reversed its decision to remove Galera clustering technology from the open source MariaDB Community Server after significant community pushback

[A New Chapter for Bluesky](https://bsky.social/about/blog/03-09-2026-a-new-chapter-for-bluesky) - Jay Graber transitions from CEO to Chief Innovation Officer, with Toni Schneider taking over as interim CEO to lead scaling efforts. Will enshitifcation set in?

[EQT Eyes Potential $6 Billion Sale of Linux Pioneer SUSE](https://www.reuters.com/business/eqt-eyes-potential-6-billion-sale-linux-pioneer-suse-sources-say-2026-03-09/) - Private equity firm EQT explores selling SUSE in a deal that could value the enterprise Linux distribution company at up to $6 billion

[OpenAI and Google Workers File Amicus Brief in Support of Anthropic Against the US Government](https://www.wired.com/story/openai-deepmind-employees-file-amicus-brief-anthropic-dod-lawsuit/) - Google DeepMind chief scientist Jeff Dean is among the AI researchers and engineers rushing to Anthropic's defense against the US government

[Nvidia Is Planning to Launch an Open-Source AI Agent Platform](https://www.wired.com/story/nvidia-planning-ai-agent-platform-launch-open-source/) - Ahead of its annual developer conference, Nvidia is readying a new approach to software that embraces AI agents

[Oracle Is Building Yesterday's Data Centers with Tomorrow's Debt](https://www.cnbc.com/2026/03/09/oracle-is-building-yesterdays-data-centers-with-tomorrows-debt.html) - The OpenAI deal fallout exposes the fundamental danger of being the most leveraged player in a market where the chip cycle moves faster than the concrete dries

[Engineering Speed at Scale — Architectural Lessons from Sub-100-ms APIs](https://www.infoq.com/articles/engineering-speed-scale/) - How to design and maintain APIs with sub-100-millisecond response times using latency budgets, strategic caching, async patterns, and circuit breakers

[WordPress Debuts a Private Workspace That Runs in Your Browser](https://techcrunch.com/2026/03/11/wordpress-debuts-a-private-workspace-that-runs-in-your-browser-via-a-new-service-my-wordpress-net/) - WordPress launches a browser-based service enabling users to create private websites without requiring hosting or account registration. I'm curious what folks are going to do with this.

[Kali & LLM: Completely Local with Ollama & 5ire](https://www.kali.org/blog/kali-llm-ollama-5ire/) - A guide to setting up a fully local, offline AI assistant on Kali Linux by combining Ollama's language models with the 5ire interface and MCP server tools

[China Issues New Safety Rules for OpenClaw](https://www.scmp.com/tech/article/3346269/china-issues-new-safety-rules-openclaw-here-are-dos-and-donts?utm_source=rss_feed) - China's tech regulator releases guidelines outlining six recommended practices and six prohibitions for safely using the popular AI agent tool, OpenClaw

[Blocking HTTP/1.1 - Some Results](https://sheep.horse/2026/3/blocking_http1.1_-_some_results.html) - Observations from experimenting with blocking HTTP/1.1 requests. The web isn't as modern as you might think.

[The Memory Stock Cycle of Boom-Bust-Repeat Is Over, Executives Say](https://www.cnbc.com/2026/03/11/memory-stocks-ai-chips-demand.html) - Sustained AI chip demand is breaking the traditional boom-bust cycle of memory stocks

[Apple's Smart Home Display Is Apparently Delayed, and Siri's Late AI Rebirth Is to Blame](https://www.digitaltrends.com/home/apples-smart-home-display-is-apparently-delayed-and-siris-late-ai-rebirth-is-to-blame/) - Apple's smart home display has been pushed to the latter half of 2026 due to AI-related delays for the next-gen Siri assistant. How many more things won't happen this year as Apple gets around to finally making the next iteration of Siri?

[Rising Memory and CPU Prices Could Push Mainstream Notebook Prices Up by Nearly 40%](https://www.trendforce.com/presscenter/news/20260310-12959.html) - Component cost increases from memory and CPU price hikes could force mainstream notebook retail prices up approximately 40% in 2026. Ugh... Where's the best place to buy used Macs these days?

[Sweep the Strait](https://sweepthestrait.com/) - A Minesweeper game where the playable field is roughly the shape of the Strait of Hormuz

[karpathy/autoresearch](https://github.com/karpathy/autoresearch) - MIT - AI agents autonomously conduct ML research by modifying code, training models for 5-minute intervals, and iterating based on performance metrics

[gianlucam76/k8s-cleaner](https://github.com/gianlucam76/k8s-cleaner) - Apache 2.0 - A Kubernetes controller that identifies unused or unhealthy resources, with scheduling, label filtering, Lua-based selection criteria, and multi-platform notifications

{{< subscribe >}}
