---
author: Chris Short
date: '2026-06-07'
description: "Red Hat npm packages compromised, EU tech sovereignty, rsync outrage, measuring OSS funding impact, Florida sues OpenAI, the token race nobody won, and more."
draft: false
slug: '312'
title: "DevOps'ish 312: Nobody won the token race, rsync outrage, dev goes scorched earth on vibe coders, and more"
---

[Most teams quarantine flaky tests. We fix them.](https://www.mendral.com/?utm_source=devopsish)  
A flake fails, someone hits retry, it passes, you merge. The bug doesn't go away. Mendral runs in your CI, reproduces the flake in a sandbox, finds the actual race or timing bug, and opens the fix PR. No quarantines, no skip annotations, no ignore list growing month over month. *SPONSORED*

[Eliminating Kubernetes Image Signature Replication](https://www.kubernetes.dev/blog/2026/06/05/image-signature-routing/) - The Kubernetes project tore out a resource-intensive signature replication pipeline and replaced it with a simple routing approach that points all signature requests to a single canonical region. Less infra, same trust chain.

[From Kubernetes Dashboard to Headlamp: Understanding the Transition](https://kubernetes.io/blog/2026/06/01/dashboard-to-headlamp/) - The Kubernetes Dashboard is archived. Headlamp is the successor, and this post maps familiar workflows to the new tool while walking through multi-cluster visibility, application-centric views, and the plugin extension model.

[Multiple Red Hat Cloud Services npm Packages Compromised to Deploy Credential-Stealing Malware](https://cybersecuritynews.com/red-hat-cloud-services-npm-packages/) - Attackers compromised the CI/CD pipeline behind the @redhat-cloud-services `npm` namespace and poisoned over 30 packages with malware that runs automatically on `npm install`. It hoovers up GitHub tokens, cloud credentials, Kubernetes tokens, SSH keys, and more -- then disguises its exfil traffic as calls to `api.anthropic.com` to blend into org logs. If you run anything from that scope, audit your environments now.

[Fed up with vibe coders, dev sneaks data-nuking prompt injection into their code](https://arstechnica.com/security/2026/05/fed-up-with-vibe-coders-dev-sneaks-data-nuking-prompt-injection-into-their-code/) - A developer embedded a hidden instruction in jqwik v1.10.0 that told AI coding agents to delete test code and output directories, concealing it with ANSI escapes so human reviewers would not see it. Claude Code flagged it without following it. The frustration with vibe coding is legitimate; shipping malware into an open source library is not.

[Microsoft says it will not pursue security researchers after zero-day backlash](https://therecord.media/microsoft-says-it-will-not-pursue-security-researchers-disclosure) - Microsoft walked back language in a blog post that security researchers read as a threat. The company clarified that it has no intention of pursuing researchers for publishing their findings, dropped the phrase "responsible disclosure," and returned to using "Coordinated Vulnerability Disclosure." The researcher behind the original disclosure is still planning to drop a new Secure Boot bypass in June.

[Florida sues OpenAI and CEO Sam Altman, saying they put profit over safety](https://www.nbcnews.com/tech/tech-news/florida-sues-openai-sam-altman-saying-put-profit-safety-rcna347602) - Florida AG James Uthmeier filed an 83-page complaint accusing OpenAI of knowingly releasing ChatGPT while concealing risks, including providing self-harm instructions to minors and coaching criminal behavior. The suit seeks to hold Altman personally liable. First state to go this route; not going to be the last.

[The European Union Takes On Tech Sovereignty](https://www.nytimes.com/2026/06/03/technology/european-union-tech-sovereignty.html?unlocked_article_code=1.nlA.Fser.IpTad_xw2JqD&smid=nytcore-ios-share) - The European Commission's Tech Sovereignty Package landed June 3: a revised Chips Act, the Cloud and AI Development Act, and a strategic roadmap covering AI and energy digitalization. The short version is that the EU wants to stop depending on American and Chinese infrastructure for anything it considers critical. The U.S. Cloud Act makes it structurally difficult for American companies to reach the highest sovereignty tiers.

[G7 Agrees On Shared Language Around Open Source AI, Open Weights AI](https://www.phoronix.com/news/G7-On-Open-Source-AI) - G7 Digital and Technology Ministers agreed on a shared vocabulary for AI openness -- distinguishing Open Source AI with Open Data, Open Source AI, Open Weights AI, and Weights Available AI. The OSI served as a knowledge partner for three months during the process. Establishing common language before the regulatory frameworks calcify is the right order of operations.

[SpaceX is worth less than half its IPO target price, Morningstar says](https://www.cnbc.com/2026/06/03/morningstar-spacex-ipo-target-price-nasdaq.html) - Morningstar pegs SpaceX's fair value at $780 billion against the company's $1.75 trillion IPO target. They're not saying it will crash at open -- a tiny float, universal underwriter support, and a new Nasdaq-100 fast-track rule will likely prop it up short term. They are saying patient investors will have better entry points after lock-ups expire.

[Nobody Won the Token Race](https://techtrenches.dev/p/nobody-won-the-token-race) - A sharp take on how optimizing AI deployments for token throughput rather than business outcomes created perverse incentives, inflated costs, and delivered underwhelming productivity gains. The token race was the wrong race to run.

[Percona celebrates 20th birthday with new foundation -- and a goat cake](https://thenewstack.io/percona-20-oursql-foundation-rebrand/) - Percona turned 20 and used the occasion to launch the OurSQL Foundation, a vendor-neutral 501(c)(6) backed by Percona, PlanetScale, PingCAP, and Alibaba Cloud to support the MySQL ecosystem. The explicit goal is to present a unified front to Oracle and keep MySQL's open source future viable. The goat cake was also apparently a thing.

[rsync and outrage](https://medium.com/@tridge60/rsync-and-outrage-d9849599e5a0) - Andrew Tridgell, creator of rsync, wrote a candid post defending his use of AI tools to rewrite rsync's test suite and handle a surge of vulnerability reports. The backlash from some was to break out the tar and feathers. This is a nuanced read from someone who has earned the right to make their own engineering calls.

[How GitHub plans to win developers back](https://thenewstack.io/github-wants-developers-back/) - GitHub is actively working to recover developer loyalty and market share in a competitive tools ecosystem. The question is whether the platform fixes are enough or whether the trust erosion runs deeper than features.

[How OSPOs can Measure the Impact of OSS Funding](https://fastwonderblog.com/2026/06/02/how-ospos-can-measure-the-impact-of-oss-funding/) - A practical framework for OSPOs to evaluate and demonstrate the effectiveness of their open source funding, built from academic research. If your OSPO has to justify its budget, this is useful ammunition.

[Framework Laptop 13 Pro Deep Dive - LPCAMM2](https://frame.work/blog/framework-laptop-13-pro-deep-dive-lpcamm2) - Framework goes deep on the benefits of LPCAMM2; lower voltage, better power efficiency, and user-upgradeability restored after years of the industry soldering everything down. Rare to see a hardware company explain its decisions this thoroughly.

[Nvidia unveils RTX Spark Superchip at Computex 2026](https://www.tomshardware.com/laptops/nvidia-unveils-rtx-spark-superchip-at-computex-2026-new-platform-promises-to-turn-windows-into-an-agentic-ai-os-with-arm-cpu-blackwell-gpu-and-128gb-unified-memory) - Nvidia announced the RTX Spark, a Windows on Arm platform combining an Arm CPU, Blackwell GPU, and 128GB unified memory aimed at running AI agents as a first-class computing interface. Over 30 laptops and 10 desktops are expected this fall.

[How Integers and Floats Work](https://wizardzines.com/zines/integers-floats/) - Julia Evans' latest zine covers why computers do math in surprising ways, including binary representation and floating-point quirks. If you have ever been burned by a floating-point comparison in a monitoring threshold, this is the explainer.

[What Are SPIFFE and SPIRE? Workload Identity Explained](https://www.youtube.com/watch?v=cCHXRzoThsM) - A clear introduction to SPIFFE and SPIRE for anyone who needs to explain workload identity to a team or just get their own mental model straight.

[IaCConf 2026 Keynote: AI Speaks Terraform Like a Tourist](https://www.youtube.com/watch?v=MCepvlS9j30&list=PLocaoeyiLZlU_w5e_uxzWqWVlJPpAY_Hg&index=3) - IaCConf 2026 keynote from friend of the newsletter, Corey Quinn, on AI and Terraform.

[harehare/mq](https://github.com/harehare/mq) - MIT License - A jq-like Markdown query language for command-line processing.

[chopratejas/headroom](https://github.com/chopratejas/headroom) - Apache License 2.0 - Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, and MCP server.

{{< subscribe >}}
