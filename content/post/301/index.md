---
author: Chris Short
categories:
- Weekly
- Newsletter
- '2026'
date: '2026-03-22'
draft: false
slug: '301'
title: "DevOps'ish 301: Super Micro Arrests, FT PO'd AWS, Show Me the Tokens, and more"
---

It was a big week. NVIDIA’s GTC conference dominated the headlines, with Jensen Huang making the case that your engineers should be spending nearly as much on AI tokens as they earn in salary. Whether that’s visionary or just a really good way to sell more GPUs, remains to be seen. Meanwhile, the U.S. government moved against chip smugglers, charging Super Micro employees with funneling Nvidia silicon to China, in what feels like the opening act of a much longer enforcement saga.

Ingress NGINX is dead, y’all. No more patches, no more fixes. If you’re still running it in production, this is your official wake-up call. The Gateway API migration path is real now, and there’s solid coverage in this edition to help you get there.

Kenneth Reitz’s essay on open source burnout is worth your full attention. It’s honest in a way that’s rare in this industry. Also, a good reminder that the people behind the tools we all depend on are, in fact, people. Read it, and maybe go thank a maintainer today.

If you’re at KubeCon in Amsterdam this week, stay safe and have fun.

[**QEMU microvm vs. Cloud Hypervisor: Choosing Your VMM**](https://depot.dev/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=301)  
Building a CI platform? Choosing between QEMU and Cloud Hypervisor means weighing legacy flexibility against a modern, Rust-based design. Depot's engineers break down the differences in API support, GPU passthrough, and hotplugging to help you make the right call. _SPONSORED_

## Events

[Cloud Native Days Romania](https://cloudnativedays.ro/)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania’s community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[Running Agents on Kubernetes with Agent Sandbox](https://kubernetes.io/blog/2026/03/20/running-agents-on-kubernetes-with-agent-sandbox/) - Agent Sandbox, a new Kubernetes project under SIG Apps, introduces a declarative API for running isolated, stateful AI agents with strong execution boundaries, lifecycle management, and stable networking identities.

[Securing Production Debugging in Kubernetes](https://kubernetes.io/blog/2026/03/18/securing-production-debugging-in-kubernetes/) - Recommendations for securing Kubernetes debugging workflows using RBAC least privilege, short-lived identity-bound credentials, and SSH-style secure shell gateways that enforce temporary access with full audit logging.

[The Invisible Rewrite: Modernizing the Kubernetes Image Promoter](https://kubernetes.io/blog/2026/03/17/image-promoter-rewrite/) - The `kpromo` tool underwent a nine-phase rewrite that cut 20% of the codebase, fixed rate limiter performance bugs, and rebuilt the architecture as a clean pipeline engine — all without disrupting production.

[Stairway to GitOps: Scaling Flux at Morgan Stanley](https://fluxcd.io/blog/2026/03/stairway-to-gitops-morgan-stanley/) - Morgan Stanley shares their five-year journey deploying GitOps with Flux across 500+ clusters, covering security hardening, performance tuning, and observability at enterprise scale.

[Super Micro shares tank 33% after employees charged with smuggling Nvidia chips to China](https://www.cnbc.com/2026/03/19/us-tech-execs-smuggled-nvidia-chips-to-china-prosecutors-say.html) - Federal prosecutors charged Super Micro employees with illegally exporting top-tier Nvidia AI chips to China as the U.S. government intensifies its crackdown on semiconductor export control violations.

[OpenAI preps for IPO by end of year, tells employees ChatGPT must be 'productivity tool'](https://www.cnbc.com/2026/03/17/openai-preps-for-ipo-in-2026-says-chatgpt-must-be-productivity-tool.html) - OpenAI hired former DocuSign CFO Cynthia Gaylor to lead investor relations as it gears up for a potential 2026 IPO, with internal messaging refocusing employees on ChatGPT's commercial productivity value.

[AI Tokens and Productivity](https://archive.is/20260320124538/https://www.wsj.com/tech/ai/ai-tokens-productivity-d35c6bd8) - Business leaders are reassessing AI's productivity-boosting promise as Jensen Huang's GTC proposal to compensate engineers with token budgets worth half their salary reframes compute access as a form of human capital.

[The Great AI Silicon Shortage](https://newsletter.semianalysis.com/p/the-great-ai-silicon-shortage) - Critical bottlenecks in TSMC's N3 wafer capacity and HBM memory are constraining the AI infrastructure buildout despite massive hyperscaler capital investment, and the shortage isn't easing anytime soon.

[Addressing GitHub's recent availability issues](https://github.blog/news-insights/company-news/addressing-githubs-recent-availability-issues-2/) - GitHub's CTO acknowledges recent outages driven by rapid growth and architectural limitations, outlining near-term fixes and a longer-term migration to Azure infrastructure.

[2 Ways to Correct the Financial Times at AWS (So Far)](https://www.lastweekinaws.com/blog/2-ways-to-correct-the-financial-times-at-aws-so-far/) - Amazon published two defensive blog posts in three weeks to dispute FT reporting on AI-related production incidents, raising questions about whether protecting AI's reputation matters more than accountability.

[Open Source Gave Me Everything Until I Had Nothing Left to Give](https://kennethreitz.org/essays/2026-03-18-open_source_gave_me_everything_until_i_had_nothing_left_to_give) - Kenneth Reitz reflects on how years of maintaining the Requests library provided identity and recognition but came at the cost of undiagnosed bipolar disorder and a burnout that nearly destroyed him.

[NGINX: What Happened and Where Should Companies Turn Next](https://www.thestack.technology/ingress-nginx-retires-what-next-gateway-api/) - Ingress NGINX, deployed in half of all cloud native environments, is officially retired as of March 2026 with no further security patches, leaving teams to evaluate Gateway API and other successors.

[My custom agent used 87% fewer tokens when I gave it Skills for its MCP tools](https://seroter.com/2026/03/16/my-custom-agent-used-87-fewer-tokens-when-i-gave-it-skills-for-its-mcp-tools/) - Comparing six agent configurations for a Google Cloud billing analysis task, giving an MCP-equipped agent pre-defined skills slashed token consumption by 87% compared to MCPs alone.

[How Can Governments Pay Open Source Maintainers?](https://shkspr.mobi/blog/2026/03/how-can-governments-pay-open-source-maintainers/) - Practical barriers prevent governments from paying open source maintainers at scale, and the author lays out concrete strategies for project creators to make themselves easier to fund by large organizations.

[How Kernel Anti-Cheats Work: A Deep Dive into Modern Game Protection](https://s4dbrd.github.io/posts/how-kernel-anti-cheats-work/) - A technical breakdown of how modern kernel-level anti-cheat systems use Windows privilege rings, memory scanning, and behavioral analysis in an ongoing arms race with cheat developers.

[Bypassing deep packet inspection with socat and HTTPS tunnels](https://blog.bofh.it/debian/id_472) - A practical walkthrough for tunneling SSH traffic inside HTTPS connections using socat to evade firewall restrictions and set up an unrestricted SOCKS proxy.

[NVIDIA/NemoClaw](https://github.com/NVIDIA/NemoClaw) - Apache-2.0 - Run OpenClaw more securely inside NVIDIA OpenShell with managed inference.

[NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell) - Apache-2.0 - Safe, private runtime for autonomous AI agents.

[langgenius/dify](https://github.com/langgenius/dify) - Apache-2.0 with additional conditions - Production-ready platform for agentic workflow development.

[mattrobinsonsre/terrapod](https://github.com/mattrobinsonsre/terrapod) - GPL-3.0 - Open-source Terraform Enterprise replacement.

[zerobootdev/zeroboot](https://github.com/zerobootdev/zeroboot) - Apache-2.0 - Sub-millisecond VM sandboxes for AI agents via copy-on-write forking.

[open-webui/open-terminal](https://github.com/open-webui/open-terminal) - MIT - A computer you can curl.

[cartography-cncf/cartography](https://github.com/cartography-cncf/cartography) - Apache-2.0 - Python tool that consolidates infrastructure assets and their relationships in an intuitive graph view powered by Neo4j.

[jlandersen/k8s-unix-system](https://github.com/jlandersen/k8s-unix-system) - Jurassic Park Unix System style Kubernetes resource viewer.

[robida/human.json](https://codeberg.org/robida/human.json) - AGPL-3.0 - A lightweight protocol for humans to assert authorship of their website content and vouch for the humanity of others via a web-of-trust JSON system.

{{< subscribe >}}
