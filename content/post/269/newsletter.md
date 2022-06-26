+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-05-29T07:00:00Z
description = ["On Vacation, Layoff and Freezes, Unlimited PTO, Broadcom offers to buy VMware, and much more"]
draft = false
slug = "269"
tags = ["Argo", "security", "containerd", "Detroit", "cloud", "layoffs", "hiring", "Google", "open source", "cloud native", "code", "runc", "CRI", "HCL", "Kubernetes", "tech news", "VMware"]
title = "DevOps'ish 269: On Vacation, Layoffs and Freezes, Unlimited PTO, Broadcom offers to buy VMware, and much more"
+++

On a much-needed vacation this weekend. Enjoying Traverse City's finer local haunts. Amazingly, this city is in the same state that Detroit is. Speaking of, I can't wait until KubeCon NA 2022 in Detroit. As we get closer to an event, I'll be sharing some more local news and info (like the Aloft will be under construction during KubeCon NA). I know there's a large contingent of Michiganders that read this newsletter. What's one fantastic thing folks in downtown Detroit can't miss (hit reply, yes, I filter out-of-office messages in 40+ languages)?

I'll start with Campus Martius Park. You'll be shocked by this excellent little happening spot in the city's heart.

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

## Events

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Tech company layoffs and hiring freezes in 2022](https://www.protocol.com/workplace/tech-company-layoffs-2022)  
Nat Rubio-Licht and Michelle Ma, Protocol  
"High-flying startups with record valuations, huge hiring goals and ambitious expansion plans are now announcing hiring slowdowns, freezes and in some cases widespread layoffs. It’s the dot-com bust all over again — this time, without the cute sock puppet and in the midst of a global pandemic we just can’t seem to shake."

[Software Engineering Insights From 10 Years At Google](https://web.archive.org/web/20220519020040/https://addyosmani.com/blog/software-eng-10-years/) (Web Archive link)  
Addy Osmani, Google  
This is an incredible font of knowledge. I do understand the whys behind its disappearance from the web though.

[How GDPR Is Failing](https://www.wired.com/story/gdpr-2022/)  
Matt Burgess, Wired  
Having just spent a week in Europe, I appreciate that I have the explicit option to turn things off. Now, whether you have to do that with one or 101 clicks is the question. It really isn't serving as the great hurdle folks thought it would be and in most cases just gets in the way.

[The science of interviewing developers](https://stackoverflow.blog/2022/05/23/the-science-of-interviewing-developers/)  
Isaac Lyman, Stack Overflow Blog  
"All those CEOs on LinkedIn claiming they can find the right candidate in a five-minute conversation? Wrong. Science shows us how we can do better." I once had the CEO of an entire company tell me that Meyers-Briggs is how they hire people and built the company. Clearly, calling it the poppycock it was meant I didn't get the job. Then [Meyers-Briggs was debunked](https://www.vox.com/2014/7/15/5881947/myers-briggs-personality-test-meaningless).

[Oracle’s Larry Ellison joined Nov. 2020 call about contesting Trump’s loss](https://www.washingtonpost.com/politics/2022/05/20/larry-ellison-oracle-trump-election-challenges/)  
Isaac Stanley-Becker and Shawn Boburg, The Washington Post  
"Larry Ellison, the billionaire co-founder and chairman of the software company Oracle and the biggest backer of Elon Musk’s attempted Twitter takeover, participated in a call shortly after the 2020 election that focused on strategies for contesting the legitimacy of the vote, according to court documents and a participant."

[The smoke and mirrors of unlimited paid time off](https://www.bbc.com/worklife/article/20220520-the-smoke-and-mirrors-of-unlimited-paid-time-off)  
Bryan Lufkin, BBC Worklife
"Workers will likely only take a decent amount of holiday if firms create an environment that encourages them to do so. In some firms with UPTO, workers end up taking less holiday – not more – because of peer pressure and perceived expectations around ‘acceptable’ amounts of holiday."

## Process

"[Broadcom announces plans to acquire VMware for around $61B in cash and stock, paying $142.50 per share, and will assume VMware's $8B in net debt](https://www.reuters.com/markets/us/chipmaker-broadcom-buy-vmware-61-bln-deal-2022-05-26/)” —Techmeme  
Chavi Mehta and Krystal Hu, Reuters  
As I said [on Twitter](https://twitter.com/ChrisShort/status/1529793277515505664) this week, "In an economy turning south, buying companies with debt is a bold move." This happened to McClatchy news right before 2008 and they never recovered. I do hope for better circumstances here though. I've also heard there will be layoffs at VMware to which I say, go to [amazon.jobs](https://amazon.jobs/) and let me know if there's a role that interests you (you can reply to this email). I have Developer Advocate and Tech Writer slots open on my team.

[Cloud Native Security Whitepaper (v2)](https://github.com/cncf/tag-security/blob/main/security-whitepaper/v2/CNCF_cloud-native-security-whitepaper-May2022-v2.pdf)  
CNCF TAG Security  
While the large majority of the original paper stands the test of time, this refreshed version demystifies security assurance and compliance by walking through specific use-cases of ransomware incident handling and how to secure financial institutions under EU regulations.

[Google has been DDoSing SourceHut for over a year](https://drewdevault.com/2022/05/25/Google-has-been-DDoSing-sourcehut.html)  
Drew DeVault  
"I took a look at the HTTP logs on git.sr.ht. Of the past 100,000 HTTP requests received by git.sr.ht (representing about 2½ hours of logs), 4,774 have been requested by GoModuleProxy — 5% of all traffic. And their requests are not cheap: every one is a complete git clone. They come in bursts, so every few minutes we get a big spike from Go, along with a constant murmur of Go traffic."

[Cyber Insurers Raise Rates Amid a Surge in Costly Hacks](https://www.wsj.com/articles/cyber-insurers-raise-rates-amid-a-surge-in-costly-hacks-11652866200?mod=djemalertNEWS)  
James Rundle and David Uberti, WSJ  
"Direct-written premiums collected by the largest U.S. insurance carriers in 2021 swelled by 92% year-over-year, according to information submitted to the National Association of Insurance Commissioners, an industry watchdog, and compiled by ratings firms."

[Zero-Click Zoom Bug Allows Code Execution Just by Sending a Message](https://www.darkreading.com/application-security/zero-click-zoom-bug-allows-remote-code-execution-by-sending-a-message)  
Tara Seals, Dark Reading  
"Google has disclosed a nasty set of six bugs affecting Zoom chat that can be chained together for MitM and RCE attacks, no user interaction required."

## Tools

[The differences between Docker, containerd, CRI-O and runc](https://www.tutorialworks.com/difference-docker-containerd-runc-crio-oci/?_hsmi=213803458)  
Tom Donohue, Tutorial Works  
Missed the boat on why `containerd` became a thing, but otherwise a good run down. In a nutshell, `runc` is an OCI-compliant reference implementation. CRI-O and `containerd` consume `runc` to implement their OCI-compliant runtime. There are a bunch of others the might be useful to you but most things use `containerd`, Red Hat uses CRI-O, which is fine, and the rest are very use case specific.

[Announcing the HCL Extension for Visual Studio Code 0.1](https://www.hashicorp.com/blog/announcing-the-hcl-extension-for-visual-studio-code-0-1)  
Radek Simko, James Pogran, Simon Davis, Hashicorp  
"HashiCorp adopts the community-created HCL Extension for Visual Studio Code and adds HCL 2.0 support."

[Kubernetes 1.24: Maximum Unavailable Replicas for StatefulSet](https://kubernetes.io/blog/2022/05/27/maxunavailable-for-statefulset/)  
Mayank Kumar (Salesforce), Kubernetes  
"Kubernetes 1.24 includes a new alpha feature to help. Before you can use the new feature you must enable the MaxUnavailableStatefulSet feature flag. Once you enable that, you can specify a new field called maxUnavailable, part of the spec for a StatefulSet."

[A Kernel Hacker Meets Fuchsia OS](https://a13xp0p0v.github.io/2022/05/24/pwn-fuchsia.html)  
Alexander Popov  
"As a Linux kernel hacker, I decided to take a look at Fuchsia OS and assess it from the attacker's point of view. This article describes my experiments."

[Don't Buy a Yeti](https://dontbuyayeti.com/)  
James McKinven, PodPanda
Great advice. I don't care who wrote it. And yes, I recommend those mics in that order. You dod't need to go overboard for the [Shure SM7B](https://amzn.to/3PQWKFq) anymore. The [Shure MV7](https://amzn.to/3z4PW0M) is more than adequate. Biggest thing is it needs to be close to your face.

[opensourcestories/opensourcestories.org](https://github.com/opensourcestories/opensourcestories.org)  
Do me a favor and star this repo. Some friends run it and they're trying to get to 100 stars so they can access GitHub Sponsors. Thank you.

[chen-keinan/kube-beacon](https://github.com/chen-keinan/kube-beacon)  
Open Source runtime scanner for k8s cluster and perform security audit checks based on CIS Kubernetes Benchmark specification

[codepo8/prompter](https://github.com/codepo8/prompter/)  
A quick script to turn a text into a prompter on screen for video recordings

[CaledoniaProject/awesome-opensource-security](https://github.com/CaledoniaProject/awesome-opensource-security)  
A list of interesting open-source tools

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
