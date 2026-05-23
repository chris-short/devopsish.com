---
author: Chris Short
date: '2026-05-24'
description: "TeamPCP backdoored a VS Code extension to breach GitHub's internal repos and compromise 540+ npm packages in the same week. While you're digesting that, two Linux LPEs went public with working PoCs, NGINX has an 18-year-old RCE, and CISA left 844 MB of credentials on a public GitHub repo. Meta is logging your mouse movements. Google deleted a pension fund's cloud. Microsoft shipped Linux. Normal week."
draft: false
slug: '310'
title: "DevOps'ish 310: The Breaches Are Coming From Inside the Extension Store"
---

[GitHub Confirms Internal Breach via Poisoned VS Code Extension](https://x.com/github/status/2056949169701720157) - Official statement from GitHub confirming TeamPCP's breach of approximately 3,800 internal repositories via the backdoored Nx Console VS Code extension; the malicious version was pulled in 18 minutes, credentials rotated, and no customer data appears to have been affected.

[NGINX Rift: Achieving NGINX Remote Code Execution via an 18-Year-Old Vulnerability](https://depthfirst.com/research/nginx-rift-achieving-nginx-rce-via-an-18-year-old-vulnerability) - A critical heap buffer overflow in NGINX dating back to 2008 can be exploited via the `rewrite` and `set` directives to achieve remote code execution -- yes, 18 years.

[Fragnesia Made Public As Latest Linux Local Privilege Escalation Vulnerability](https://www.phoronix.com/news/Linux-Fragnesia) - Hot on the heels of Dirty Frag, Fragnesia is now public as a similar LPE in Linux's ESP/XFRM code with a logic bug allowing arbitrary byte writes into the kernel page cache -- proof-of-concept code already out there.

[AI Just Found Another Linux Zero-Day and Security Researchers Are Freaking Out](https://linuxstans.com/ai-just-found-another-linux-zero-day-and-security-researchers-are-freaking-out/) - CVE-2026-46333, a privilege escalation flaw in the Linux kernel's ptrace subsystem, is stoking greater concern about AI tools compressing the timeline from discovery to exploitation.

[TeamPCP Compromises NPM Maintainer with Over 540 Packages](https://opensourcemalware.com/blog/teampcp-compromises-npm-maintainer-with-over-540-packages) - The same group behind the GitHub breach gained access to an NPM maintainer account, potentially backdooring over 540 JavaScript packages in a cascading supply chain play.

[How We Got a CISA GitHub Leak Taken Down in Under a Day](https://blog.gitguardian.com/how-we-got-a-cisa-github-leak-taken-down-in-26-hours/) - GitGuardian found a public GitHub repo containing 844 MB of CISA credentials and sensitive infrastructure data; coordinated disclosure got it offline in 26 hours.

[Critical PostgreSQL Vulnerabilities Enable Code Execution and SQL Injection](https://cybersecuritynews.com/postgresql-code-execution-vulnerabilities/) - PostgreSQL pushed emergency patches for 11 vulnerabilities across versions 14-18, including arbitrary code execution via the refint module and SQL injection via logical replication.

[Meta Reassigns 7,000 Workers to AI Teams Before Mass Layoffs](https://www.nytimes.com/2026/05/19/technology/meta-layoffs-ai.html?unlocked_article_code=1.j1A.3nhQ.n7SNMgU9zm87&smid=url-share) - Meta moved workers into four new AI-native organizations with flatter management structures the same day it sent 4 a.m. layoff emails to everyone else.

[Meta US Employees Organize Protest Against Mouse-Tracking Tech](https://www.reuters.com/sustainability/society-equity/meta-us-employees-organize-protest-against-mouse-tracking-tech-2026-05-12/) - Workers distributed flyers at US offices pushing back on Meta's Model Capability Initiative, which captures mouse movements, keystrokes, and screenshots to train AI agents -- CTO Bosworth confirmed there is no opt-out.

[Google Cloud Deletes Australian Trading Fund's Infrastructure](https://blog.pragmaticengineer.com/google-cloud-deletes-australian-trading-funds-infra/) - Google Cloud accidentally deleted a major Australian retirement fund's subscription and all associated data across replicated regions, causing a two-week outage and a scramble to recover from external backups.

[Google Accused of Pushing 'Free for Life' G Suite Users Onto Paid Plans](https://www.theregister.com/applications/2026/05/19/google-accused-of-pushing-free-for-life-g-suite-users-onto-paid-plans/5242567) - Long-time G Suite Legacy users are getting notices that their accounts have been flagged as commercial use and must pay for Google Workspace or face suspension.

[On Google Declaring War on the Web](https://tante.cc/2026/05/20/on-google-declaring-war-on-the-web/) - Google's I/O keynote pushed Search further toward AI-processed answers, doubling down on AI Overviews to reduce click-throughs to the open web and pushing the rest of us off a cliff.

[Anthropic Reinstates OpenClaw and Third-Party Agent Usage on Claude Subscriptions, With a Catch](https://venturebeat.com/technology/anthropic-reinstates-openclaw-and-third-party-agent-usage-on-claude-subscriptions-with-a-catch) - Anthropic re-enabled OpenClaw and third-party agent integration on Claude subscriptions after earlier restrictions, but new usage conditions apply.

[The Best Argument I've Heard for Why AI Won't Take Your Job](https://www.platformer.news/ai-job-loss-box-ceo-aaron-levie/) - Box CEO Aaron Levie's case that AI multiplies productivity rather than replacing workers; the interviewer does a decent job of poking holes in it.

[Git Is Unprepared for the AI Coding Tsunami](https://www.theregister.com/devops/2026/05/15/git-is-unprepared-for-the-ai-coding-tsunami/5241480) - AI-generated pull requests are hammering Git and GitHub's infrastructure, and the ecosystem is only starting to reckon with what agentic development does to version control at scale.

[Gemini 3.5 Flash Might Be Fast Enough for Gen AI to Make Sense](https://arstechnica.com/google/2026/05/google-announces-agent-optimized-gemini-3-5-flash-and-a-do-anything-model-called-omni/) - Google positions the agent-optimized Gemini 3.5 Flash as the key to making AI workflows economically viable, with speed gains that may shift the math on agentic deployments.

[Ukraine Says Russia Is Deploying AI-Powered Malware on the Battlefield](https://therecord.media/ukraine-says-russia-using-ai-malware-on-battlefield) - Ukrainian officials report Russia has embedded AI directly into malware for realtime command generation, creating an asymmetric advantage in cyber operations that defenders are struggling to match.

[Microsoft Surprises with Its First Server Linux Distribution: Azure Linux 4.0](https://www.zdnet.com/article/microsoft-releases-its-first-server-linux-distribution-azure-linux-4-0/) - Announced at Open Source Summit North America, Azure Linux 4.0 is a Fedora-based, general-purpose cloud distribution backed by Microsoft's full supply chain, with WSL support for local dev parity -- yes, Microsoft is shipping Linux now.

[Announcing etcd 3.7.0-beta.0](https://kubernetes.io/blog/2026/05/20/etcd-370-beta/) - SIG-etcd's first beta of v3.7.0 brings the new RangeStream capability for large result sets, drops legacy v2store, and marks etcd v3.4 end-of-life.

[Grafana on X - GrafanaCON 2026 Announcements](https://x.com/grafana/status/2055827123236171827) - Grafana Labs unveiled Grafana 13 with AI-powered features, Grafana Assistant for self-managed users, new AI observability tooling, and the Grafana Marketplace at GrafanaCON 2026.

[Automating Confidential Containers (CoCo) Infrastructure with Kyverno](https://www.cncf.io/blog/2026/05/19/automating-confidential-containers-coco-infrastructure-with-kyverno/) - How platform teams can use Kyverno to automatically inject and validate Confidential Containers configuration, simplifying zero-trust security deployment without making every dev learn the full CoCo stack.

[pgBackRest Will Continue](https://lwn.net/Articles/1073470/) - Multiple sponsors came forward to fund pgBackRest development after maintainer David Steele initially archived the project for lack of financial support -- a small but real win for open source sustainability.

[Kubernetes In Anger](https://samof76.space/kubernetes-in-anger.html) - A comprehensive operational guide for diagnosing and fixing production EKS failures fast, covering failure domain identification, platform-specific failure modes, and incident response runbooks.

[You Can Get Some of Your Nudes Removed From the Internet Under a New Law](https://www.wired.com/story/how-to-remove-nudes-take-it-down-act/) - Starting May 19, US tech platforms have to comply with the Take It Down Act; here's how more than a dozen major platforms are handling nonconsensual image takedown demands.

[I Was Laid Off by Atlassian](https://www.youtube.com/watch?v=55pTFVoclvE) - Personal account of the layoff experience at Atlassian -- worth a watch as the human texture behind the wider tech restructuring playing out everywhere right now.

[Why I'm Leaving GitHub for Forgejo](https://jorijn.com/en/blog/leaving-github-for-forgejo/) - A developer explains migrating to self-hosted Forgejo over concerns about Microsoft ownership, data training, and US jurisdictional risk, following a similar move by the Dutch government.

[Swamp Beyond Infrastructure](https://webframp.com/posts/swamp-beyond-infrastructure/) - The argument that [Swamp](https://swamp.club/) is fundamentally a typed data platform for AI agents -- not just an infrastructure tool -- enabling use cases from content generation to governance.

[spegel-org/spegel](https://github.com/spegel-org/spegel) - MIT - Stateless cluster local OCI registry mirror.

[ardanlabs/kronk](https://github.com/ardanlabs/kronk) - Apache 2.0 - Go-based engine for hardware-accelerated local inference using llama.cpp and whisper.cpp, with a high-level API and model server baked in.

[googlecloudplatform/kubectl-ai](https://github.com/googlecloudplatform/kubectl-ai) - Apache 2.0 - AI-powered Kubernetes assistant.

[kubetail-org/kubetail](https://github.com/kubetail-org/kubetail) - Apache 2.0 - Real-time logging dashboard for Kubernetes; runs in a terminal or browser, works from desktop to cluster to Docker.

[raiyanyahya/how-to-train-your-gpt](https://github.com/raiyanyahya/how-to-train-your-gpt) - MIT - Build a modern LLM from scratch, including every line commented and explained clearly.

[0xdeadbeefnetwork/ssh-keysign-pwn](https://github.com/0xdeadbeefnetwork/ssh-keysign-pwn) - No license - PoC exploit for stealing SSH host private keys and /etc/shadow via the ptrace_may_access mm-NULL bypass and pidfd_getfd on pre-31e62c2ebbfd kernels.

{{< subscribe >}}
