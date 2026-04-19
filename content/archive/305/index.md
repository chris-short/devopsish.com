---
author: Chris Short
date: '2026-04-19'
description: "AI is eating all the compute, Rust is finally stable in Linux 7.0, your smart glasses are a civil liberties problem, and Agile is
  on its deathbed. The usual week in tech."
draft: false
slug: '305'
title: "DevOps'ish 305: Rust ships, Agile dies, nobody has enough GPUs, and more"
---

[Ship Code Faster with a Terminal-Native AI Agent](https://console.mistral.ai/codestral/cli?utm_source=newsletter&utm_medium=email&utm_campaign=vibe&utm_content=devopsish)  
Mistral Vibe is a terminal-native coding agent that works directly inside your codebase—reading your file structure, executing shell commands, patching files, and managing multi-step tasks through natural language. The CLI is open source under Apache 2.0, so you can self-host, inspect, and extend it on your own infrastructure. [Try Mistral Vibe today](https://console.mistral.ai/codestral/cli?utm_source=newsletter&utm_medium=email&utm_campaign=vibe&utm_content=devopsish). *SPONSORED*

[Don't Miss IaCConf 2026: Keeping Pace](https://www.iacconf.com/iacconf-2026?utm_source=devopsish&utm_medium=email&utm_campaign=305)  
The Community-Driven IaC Conference is back — and it's free to attend! Infrastructure as Code is evolving fast. Are you keeping pace? Join us on Thursday, May 14, 2026 at 11AM EDT for a full day of real-world stories, live demos, and panel discussions featuring some of the sharpest minds in DevOps and Platform Engineering — all from the comfort of your own desk. *SPONSORED*

[Cloud Native Days Romania](https://cloudnativedays.ro/?utm_source=devopsish&utm_medium=email&utm_campaign=305)  
Two days of cloud native talks, hands-on workshops, and strong community momentum - **18–19 May** at the Radisson Blu, Bucharest. Join developers, platform engineers, DevOps practitioners, engineering leaders, and cloud enthusiasts for the 3rd edition of Romania's community-driven Cloud Native Days, bringing practical Kubernetes use cases and modern cloud native systems to the stage.

[DevOpsDays Raleigh](https://tickets.devopsdays.org/devopsdays-raleigh/2026/?utm_source=devopsish&utm_medium=email&utm_campaign=305)  
DevOpsDays Raleigh is one of the region's premier community-driven tech conferences, bringing together engineers, DevOps leaders, and IT professionals for two days of real-world insights, practitioner-led talks, and interactive open spaces. And this year is special as it's the 10th anniversary! This conference is focused on DevOps, cloud, automation, and modern software delivery.  It offers a unique mix of learning, networking, and collaboration with peers tackling similar challenges across industries. Join me in Raleigh **April 30th & May 1st**!

[The AI industry is running out of compute, with outages, rationing, and rising GPU prices](https://the-decoder.com/the-ai-industry-is-running-out-of-compute-with-outages-rationing-and-rising-gpu-prices/) - Explosive demand for AI agents is overwhelming computing infrastructure, causing service outages at major providers, product cancellations, and GPU prices to surge nearly 50% as supply struggles to keep pace.

[Meta Is Warned That Facial Recognition Glasses Will Arm Sexual Predators](https://www.wired.com/story/meta-ray-ban-oakley-smart-glasses-no-face-recognition-civil-society/) - More than 70 organizations, including the ACLU, EPIC, and Fight for the Future, say the AI smart glasses feature would endanger abuse victims, immigrants, and LGBTQ+ people.

[iPhone forensics expose Signal messages after app removal in U.S. case](https://securityaffairs.com/190740/security/iphone-forensics-expose-signal-messages-after-app-removal-in-u-s-case.html) - An FBI case in Texas reveals that Signal messages can be recovered from iPhones through system notification databases even after the app is deleted, exposing a gap between privacy expectations and how operating systems actually preserve data.

[Digital sovereignty isn't just a buzzword - it's the future](https://www.theregister.com/2026/04/13/digital_sovereignty/) - European governments and businesses are increasingly moving away from US technology providers toward open source and domestically-controlled infrastructure to reduce their dependence on American companies and executive orders.

[You can use Linux 7.0 on these 7 distros today - here's what to expect](https://www.zdnet.com/article/try-new-linux-7-0-kernel-on-these-distributions/) - Linux 7.0 lands with Rust finally stable in the kernel, a revamped scheduler with lazy preemption for hybrid CPUs, and Linus Torvalds acknowledging AI tooling is now part of the normal development cycle.

[Thoughts on the Bluesky public incident write-up](https://surfingcomplexity.blog/2026/04/12/thoughts-on-the-bluesky-public-incident-write-up/) - Lorin Hochstein analyzes Bluesky's April 2026 outage, explaining how ephemeral port exhaustion and TIME_WAIT states caused a cascading failure when connecting to memcached, and how using multiple loopback addresses provided relief.

[Can Michigan Become the U.S. Drone Capital?](https://www.nytimes.com/2026/04/14/business/michigan-drone-capital.html?unlockedarticlecode=1.bFA.3Aze.xDFGsIAEsq9W&smid=nytcore-ios-share) - Michigan is spending millions to lure drone manufacturers into its auto supplier ecosystem, betting that federal restrictions on DJI and ballooning defense budgets create a once-in-a-generation opportunity to build a domestic drone industry from scratch.

[Finding zombies in our systems: A real-world story of CPU bottlenecks](https://medium.com/pinterest-engineering/finding-zombies-in-our-systems-a-real-world-story-of-cpu-bottlenecks-ea4722e552eb) - Pinterest engineers trace Ray-based ML training crashes back to zombie memory cgroups accumulating from a malfunctioning ECS agent, which starved CPUs and triggered AWS ENA network driver resets.

[Programming used to be free](https://purplesyringa.moe/blog/programming-used-to-be-free/) - The rise of expensive, proprietary LLMs threatens to make programming inaccessible to those without institutional resources, reversing decades of progress in broadening access to software development through free and open source tools.

[TIOBE Index for April 2026](https://www.tiobe.com/tiobe-index/) - Python holds the top spot, C and C++ trail behind, and Rust's rapid rise shows signs of slowing after peaking at #13 earlier this year and dropping to #16.

[How do AI agents use S3 Files to persist memory and share state? (2026)](https://medium.com/@brookejamieson/how-do-ai-agents-use-s3-files-to-persist-memory-and-share-state-2026-69d6b4a3a4da) - Amazon's S3 Files service lets AI agents mount S3 buckets as shared file systems for persisting state across Lambda, ECS, and EC2 without rolling your own coordination layer.

[Why aren't we uv yet?](https://aleyan.com/blog/2026-why-arent-we-uv-yet/) - Despite near-universal developer admiration, uv has only hit 30% adoption in new Python repos -- largely because LLMs trained on older data keep defaulting to pip and requirements.txt in their suggestions.

[Saying Goodbye to Agile](https://lewiscampbell.tech/blog/260414.html) - Software's "Agile moment" has been and gone, and it's time to reckon with what spec-driven development looks like in the wake of its decline.

[Claude Code Cheat Sheet](https://cc.storyfox.cz/) - A handy reference guide documenting Claude Code's keyboard shortcuts, slash commands, configuration options, and workflow features for anyone living in the CLI.

[Internet Protocol Version 8 (IPv8) - IETF Draft](https://datatracker.ietf.org/doc/draft-thain-ipv8/00/) - An IETF Internet-Draft proposing a new managed network protocol that integrates address management, authentication, DNS resolution, and security into a unified system while maintaining full IPv4 backward compatibility via a 64-bit addressing scheme.

[camilleroux/tech-digest](https://github.com/camilleroux/tech-digest) - MIT - Claude Code skill: daily tech digest from Hacker News, Lobste.rs and more. Zero dependencies, score-based filtering.

[multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) - No license - A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

{{< subscribe >}}
