+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-07-04
description = ["Changing roles, drunk worker nearly creates privacy disaster, more layoffs, Kubernetes scanning with Trivy, OpenSSL 3.0.4 vuln, my ultimate dev environment, IE tombstone, and more"]
draft = false
slug = "274"
tags = ["Kubernetes", "open source", "development environment", "OpenSSL", "Independence Day", "community", "code", "AWS", "Trivy", "cluster", "code-server", "Caddy", "Tailscale", "Hugo", "MacBook", "GitOps", "dockershim", "upstream", "cloud native"]
title = "DevOps'ish 274: Changing roles, drunk worker nearly creates privacy disaster, more layoffs, Kubernetes scanning with Trivy, OpenSSL 3.0.4 vuln, my ultimate dev environment, IE tombstone, and more"
+++

## Independence Day

Happy Independence Day to my friends and family in the United States. I have a lot of mixed feelings on this day. But, we should note that independence is hard-won. The United States declared its independence in 1776. But, it took eight years of war and bringing in two British enemies (Spain and France) in the process. What has followed is one of the best examples of enemies turned BFFs in our world today (it did take time, though). There's much to be gleaned here about creating allies out of opponents. It is often necessary when going through any transformation. Your detractors, once convinced, can become your biggest allies. If this piqued your interest, check out my talk, [DevOps is Not War](https://chrisshort.net/video/devops-not-war-chefconf-2018/).

## I Made Some Shinies

I've been busy the past few weeks. I often have or create side projects on which I want to spend time while traveling. You might remember [I was at Open Source Summit](https://devopsish.com/273) last month. During the week of Open Source Summit, my side project was to build out [my ultimate development environment: code-server, Caddy, Tailscale, and Hugo](https://devopsi.sh/env). It was super helpful to be able to ping the fine folks in the [Coder](https://coder.com/) booth when I had questions walking in or out of the venue that day. I call it "[W]onderful, like unicorns and rainbows, y'all. 🦄🌈🦄🌈🦄🌈" It is where newsletters, blog posts,  [landing pages](https://chrisshort.me/) (I need to write a blog post on that), and all the YAMLs are being created these days (public repos only for obvious reasons).

## Changing Roles at AWS

This week has had its ups and downs. [More downs than ups](https://twitter.com/ChrisShort/status/1542547822888849410), to be honest. But, I tried like hell to crank out all the work that needed to be updated to start a new role come Tuesday. Let me make this abundantly clear now. There's nothing wrong with the EKS Developer Advocate team. It's truly an amazingly talented group. Also, I'm staying at AWS (yes, I like it here, and they've done right by me and my family, big time).

### Amazon EKS Developer Advocate

In 249 days, we've churned out a `multi-cluster-gitops` project I highlighted at Open Source Summit in the AWS booth. We've also built a successful newsletter that, in 22 issues, has ~1500 subscribers without a dime of Marketing support. We worked in the upstream Kubernetes project to get through ALL the `dockershim` work with the community leads guiding our hands. A role in which I ensured there were always too many people named Chris in the group. The `dockershim` work alone could've been all I did for 249 days; it felt like some weeks, at least. But working upstream with my colleagues brings me so much joy. We're agile and can chip in where the work is complex and intertwined.

### Community work

I'm not stopping all my contributions to cloud native and Kubernetes altogether, oh no. I intend to use the trust I've built within the Kubernetes community to help make it a more diverse and welcoming place. You'll find me in #github-management more as that's a function that's more my speed (especially after deep diving into it late in the afternoon on Friday). No leadership capacity there; merely chipping in to help bring more folks into the project. I'll also remain an advisor to the [Contributor Comms](https://github.com/kubernetes/community/tree/master/communication/marketing-team) team (a role I'm finally settling into, I hope; Kaslin is the real judge there). I did step down effective 1 July 2022 as [GitOps WG](https://github.com/cncf/tag-app-delivery/tree/main/gitops-wg) co-chair (that was a tough but necessary decision).

You'll be seeing me around in my new role too. I'm heading over to work on a new project that I'm VERY excited about. I had the idea for such a thing last year but ultimately shelved it because I was too busy to support such a project at the time. Now it's going to be my job to make this idea very much into a reality. To briefly quote the job description, "[Y]ou will focus primarily on open source projects, integrations, and related workflows. Developer experience, CI/CD, and end-to-end container image lifecycle are all in scope."

## Free Copy of Honeycomb's O'Reilly Book: Observability Engineering

Looking to make the switch from monitoring to observability? Download your free copy of Honeycomb's [O'Reilly book: Observability Engineering](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) to help you get started. Debrief the chapters with the authors themselves during our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112).

## Events

**Editor's note:** Is your event open to a wider group than your town/city? Let me know!

[**HugoConf**](https://hugoconf.io/?source=devopsish)

JULY 8-9, 2022

The free, online conference for everything Hugo

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Drunk worker loses USB stick containing details of every resident of his city](https://www.bitdefender.com/blog/hotforsecurity/drunk-worker-loses-usb-stick-containing-details-of-every-resident-of-his-city/)  
Graham Cluley, Bitdefender  
If you read one article this week, this one *has* is it. "At a press conference, the authorities reported that the flash drive had been encrypted — reducing the chances of the data leaking into the wrong hands.  Nonetheless, the city's mayor and other officials bowed in apology to residents."

[Celebrating Pride Month is great, but LGBTQ+ representation in high-tech leadership matters more](https://www.geektime.com/celebrating-pride-month-is-great-but-lgbtq-representation-in-high-tech-leadership-matters-more/)  
Toby Stein, Datagen  
"We accept as a fact that people work better in an environment of openness, respect, and mutual understanding. But, for many LGBTQ+ people, as well as members of other marginalized or underrepresented groups, this message can run up against learned habits of being less queer-presenting or keeping sexual orientation a private matter."

[Tesla lays off nearly 200 Autopilot workers, shutters San Mateo office](https://techcrunch.com/2022/06/28/tesla-layoffs-autopilot-workers-san-mateo/)  
Rebecca Bellan, TechCrunch  
"Tesla has gutted the data annotation team working on Autopilot, laying off nearly 200 employees and shutting down the San Mateo, California office where they worked"

[Substack Is Laying Off 14% of Its Staff](https://www.nytimes.com/2022/06/29/business/media/substack-layoffs.html)  
Benjamin Mullin, The New York Times  
"The newsletter start-up discussed raising funding last year but abandoned the plan after the market for venture investments cooled."

[Sources: Unity Laying Off Hundreds Of Staffers](https://kotaku.com/sources-unity-laying-off-hundreds-of-staffers-1849125482)  
Ari Notis, Kotaku  
"Management at the company behind the free game development engine has been a 'shit show' recently, sources say"

## Process

[What have we learned from scanning over 10K Kubernetes Clusters?](https://www.armosec.io/blog/what-we-learned-from-scanning-over-10k-kubernetes-clusters/)  
Jonathan Kaftzan, Armo  
A lot of good lessons in this post.

[Kubernetes security scanning with Trivy CLI and Trivy Operator](https://youtu.be/bgYrhQ6rTXA)  
Anais Urlichs  
"In this video, we are going to look at Kubernetes cluster scanning. Specifically, we are going to use first the Trivy CLI and then the Trivy Operator to scan our cluster for security issues including vulnerabilities and misconfiguration."

[ZuoRAT Hijacks SOHO Routers to Silently Stalk Networks](https://blog.lumen.com/zuorat-hijacks-soho-routers-to-silently-stalk-networks/)  
Black Lotus Labs, Lumen
"ZuoRAT is a MIPS file compiled for SOHO routers that can enumerate a host and internal LAN, capture packets being transmitted over the infected device and perform person-in-the-middle attacks (DNS and HTTPS hijacking based on predefined rules)."

[OpenSSL to Release Security Patch for Remote Memory Corruption Vulnerability](https://thehackernews.com/2022/06/openssh-to-release-security-patch-for.html)  
Ravie Lakshmanan, The Hacker News  
"The latest version of the OpenSSL library has been discovered as susceptible to a remote memory-corruption vulnerability on select systems. The issue has been identified in OpenSSL [version 3.0.4](https://github.com/openssl/openssl/releases/tag/openssl-3.0.4), which was released on June 21, 2022, and impacts x64 systems with the [AVX-512](https://en.wikipedia.org/wiki/AVX-512) instruction set. OpenSSL 1.1.1 as well as OpenSSL forks BoringSSL and LibreSSL are not affected."

[Exposed Kubernetes clusters](https://blog.cyble.com/2022/06/27/exposed-kubernetes-clusters/)  
Bill Toulas, Cyble  
"Organizations At Risk Of Data Breaches Via Misconfigured Kubernetes"

## Tools

[code-server, Caddy, Tailscale, and Hugo = My ultimate dev environment](https://chrisshort.net/code-server-caddy-tailscale-and-hugo-my-ultimate-dev-environment/)  
Chris Short  
"I think I've discovered my development environment equivalent to nirvana: code-server, Caddy, Tailscale, and Hugo"

[Fast Feedback Loop for Kubernetes Product Development in a Production Environment](https://doordash.engineering/2022/06/23/fast-feedback-loop-for-kubernetes-product-development-in-a-production-environment/)  
Santosh Banda & Misa Gohara, Doordash  
Doordash Engineering seems to like [Signadot](https://docs.signadot.com/docs/overview/): A Kubernetes based platform that scales testing for engineering teams building Microservices based applications.

[Remote Development at Slack](https://slack.engineering/remote-development-at-slack/)  
Sylvestor George, Slack Engineering  
"In this article, “remote development environments” refer to AWS EC2 instances where engineers make code changes and can see a running Slack application with those changes."

[Best Linux Commands For Advanced Hardware and System Info](https://nixsanctuary.com/best-linux-hardware-system-info-commands/)  
Paul, Nix Sanctuary  
A good page to bookmark for whenever you to poke around the hardware you're working on.

[ripgrep-all Command in Linux: One grep to Rule Them All](https://itsfoss.com/ripgrep-all/)  
Pratham Patel, It's FOSS  
"[rga](https://github.com/phiresky/ripgrep-all), called ripgrep-all, is an excellent tool that allows you to search almost all files for a text pattern. While the OG grep command is limited to plaintext files, rga can search for text in a wide range of file types such as PDF, e-Books, Word documents, zip, tar, and even embedded subtitles."

[Rufus lets you install Windows 11 22H2 without a Microsoft account](https://liliputing.com/2022/06/rufus-lets-you-install-windows-11-22h2-without-a-microsoft-account.html)  
Brad Linder, Liliputing  
"Windows 11 22H2, which is set to roll out later this year, removes the option to set up a device using just a local account (that’s not tied to a Microsoft account)... But the developers of an open source tool for creating bootable USB flash drives already has a workaround."

[Internet Explorer is shutting down after 27 years, and someone in South Korea built a real tombstone for it!](https://twitter.com/DataChaz/status/1537337984604848128)  
Charly Wargnier  
"He was a good tool to download other browsers."

[Apple’s entry-level MacBook Pro M2 has slower SSD speeds than its M1 counterpart](https://www.theverge.com/2022/6/27/23184515/apple-macbook-pro-m2-slow-ssd-speeds)  
Tom Warren, The Verge  
"If SSD speeds are an issue for you on the base 13-inch MacBook Pro, you’ll need to stump up an extra $200 for the faster 512GB model. But if you’re willing to do that, you might want to wait and see what’s inside the new MacBook Air."

[elesiuta/picosnitch](https://github.com/elesiuta/picosnitch)  
Monitor network traffic per executable using BPF

[ray-project/ray](https://github.com/ray-project/ray)  
An open source framework that provides a simple, universal API for building distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library.

[containers/bubblewrap](https://github.com/containers/bubblewrap)  
Unprivileged sandboxing tool

## DevOps'ish Post of the Week

[![@marinavance on Twitter)](https://shortcdn.com/devopsish/274-devopsish-post-of-the-week-001.webp)](https://twitter.com/marinavance/status/1541835993115856896)

[![@marinavance on Twitter)](https://shortcdn.com/devopsish/274-devopsish-post-of-the-week-002.webp)](https://twitter.com/AlexJonesax/status/1543678834100297730)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
