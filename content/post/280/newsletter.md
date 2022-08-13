+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-08-14T07:00:00Z
description = ["GitBOM, Nutanix layoffs, Winter Soldier, cloud platform teams, EKS Multi-cluster GitOps, and more"]
draft = false
slug = "280"
tags = ["dependencies", "SBOM", "cloud", "Kubernetes", "software", "cloud native", "GitBOM", "developer", "open source", "secrets", "minimum standard", "AWS", "security", "accessibility", "Detroit", "DevOps", "code", "platform", "Nutanix", "GitOps", "Amazon", "EKS"]
title = "DevOps'ish 280: GitBOM, Nutanix layoffs, Winter Soldier, cloud platform teams, EKS Multi-cluster GitOps, and more"
+++

I spent the week in Seattle. I'm writing this in SeaTac waiting for my flight back to Detroit because we're going to a friend's birthday party tomorrow night. Work is good, but I had a meeting this week to start working on a blog post for a new project I'm contributing to; [GitBOM](https://gitbom.dev/?utm_source=devopsish).

GitBOM hopes to more clearly and cleanly identify dependencies in code bases without human intervention. GitBOM aims to complement SBOMs, not replace them. GitBOM creates "consistently construct verifiable [Artifact Dependency Graph (ADG)s](https://gitbom.dev/glossary/artifact_dependency_graph?utm_source=devopsish) across languages, environments, and packaging formats, with zero developer effort, involvement, or awareness to enable automatic, verifiable [artifact](https://gitbom.dev/glossary/artifact) resolution across today's diverse software supply chains."

Why is this important? Why am I getting involved? Because the government standard [is far too low to be useful](https://twitter.com/ChrisShort/status/1557169874484334592?utm_source=devopsish) and SBOMs are starting to look like the cookie consent boxes that GDPR brought us. One thing I'm exceptional at is going from an order from the US government to the actual documentation implementing how the order should be followed. As I sat there listening to [Aeva Black](https://aeva.online/) talk about how compute intensive (and expensive) it is to generate an SBOM of any significant depth. I wanted to know how the [Cyber Security Executive Order](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/?utm_source=devopsish) had been implemented.

I searched for which government agency would set the standards in the EO: US Department of Commerce. More specifically, the US National Telecommunications and Information Administration. That's when I found [The Minimum Elements For a Software Bill of Materials (SBOM)](https://www.ntia.doc.gov/files/ntia/publications/sbom_minimum_elements_report.pdf?utm_source=devopsish). The document states explicitly with regards to depth, "An SBOM should contain all primary (top level) components, with all their transitive
dependencies listed. *At a minimum, all top-level dependencies must be listed with enough detail to seek out the transitive dependencies recursively*." Emphasis mine because that sentence is the most important.

"At a minimum, all top-level dependencies must be listed with enough detail to seek out the transitive dependencies recursively," means a *depth of one* and giving the person needing to find dependencies in their environment enough info *to seek out* those deeper dependencies *on their own*.

THAT is not in the spirit of the Executive Order.

THAT is not in the spirit of the Executive Order. THAT will not help us find Log4j in our dependencies unless we put it there. GitBOM hopes to answer that without burning tens of thousands of dollars trying to find all the dependencies in your environment. This is important to me because I don't want anyone to get hacked because a random device had a transitive dependency their SBOM didn't tell them about due to lax regulatory standards. [Like I said](https://twitter.com/aevavoom/status/1557173213490081792?utm_source=devopsish) at the table with Aeva, "If your supplier is meeting the NTIA's minimum standard for SBOMs, you need to be prepared for maximal effort."

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Jobs

Now Hiring: [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003?utm_source=devopsish)  
[Camunda](https://camunda.com/) is the leader in process orchestration software. Our software helps orchestrate complex business processes that span people, systems, and devices. With Camunda, business users collaborate with developers to model and automate end-to-end processes using BPMN-powered flowcharts that run with the speed, scale, and resiliency required to compete in today's digital-first world.

As the [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003?utm_source=devopsish), you'll be the direct people manager for a team of 4 Developer Advocates, responsible for career growth, performance evaluations, setting of priorities, and overall strategic guidance. You'll also be responsible for strategic planning for the Developer Advocacy function, including quarterly OKRs and annual goals as well as documentation of team responsibilities, goals, and success metrics.

*Note: The hiring manager is on a hard earned vacation.*

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/?utm_source=devopsish)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we're expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We're excited to welcome you back to our Deserted Island this September 14th and 15th!

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?utm_source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

## People

[What ultra-successful people who practice DevRel know and do](https://www.youtube.com/watch?v=3O-hbh1FbpI)  
Wesley Faulkner and Chris Short, AWS  
Join Wesley Faulkner, Sr, Community Manager at AWS and Chris Short, Sr. Developer Advocate for a discussion about getting decision makers to buy-in in the #DevRel space. Watch live on ** 16 August at 11 AM ET / 15:00 UTC**. Also streaming to [Twitch](https://twitch.com/thechrisshort) and [LinkedIn](https://www.linkedin.com/video/event/urn:li:ugcPost:6963548758777200640/).

[Nutanix to layoff 270 employees](https://blocksandfiles.com/2022/08/10/nutanix-layoffs/)  
Chris Mellor, Blocks and Files  
"A Nutanix 8-K SEC filing reveals it's planning to chop 270 employees, 4 percent of its workforce."

[Hackers Behind Twilio Breach Also Targeted Cloudflare Employees](https://thehackernews.com/2022/08/hackers-behind-twilio-breach-also_10.html)  
Ravie Lakshmanan, The Hacker News  
"The wave of over 100 smishing messages commenced less than 40 minutes after the rogue domain was registered via Porkbun, the company noted, adding the phishing page was designed to relay the credentials entered by unsuspecting users to the attacker via Telegram in real-time."

[How to pick a starter project that'll make someone quit](https://amir.rachum.com/blog/2022/08/07/starter-project/)  
Amir Rachum  
Cheeky but a lot of stories I've heard before.

## Process

[Tech, Cyber Companies Launch Security Standard to Monitor Hacking Attempts](https://www.wsj.com/articles/tech-cyber-companies-launch-security-standard-to-monitor-hacking-attempts-11660123802)  
Kim S. Nash, WSJ  
"A group of 18 tech and cyber companies said Wednesday they are building a common data standard for sharing cybersecurity information. They aim to fix a problem for corporate security chiefs who say that cyber products often don't integrate, making it hard to fully assess hacking threats."

[Over 100K Cars Cut From North American Production This Week Due to Chip Shortage](https://www.cnet.com/roadshow/news/north-american-production-chip-shortage/)  
Steven Ewing, CNET  
"Industry experts expect more than 3.8 million vehicles to be cut by the end of the year."

## Tools

[GitOps: A Simple Approach to using AWS Secrets Manager with Kubernetes](https://opssorry.substack.com/p/gitops-a-simple-approach-to-using)  
Marco Lau, Ops Sorry  
"AWS Secrets Manager and Config Provider for Secret Store CSI Driver" provides an effective secrets management solution.

[Amazon EKS now supports Kubernetes 1.23](https://aws.amazon.com/blogs/containers/amazon-eks-now-supports-kubernetes-1-23/)  
Sai Vennam and Chris Short, AWS Containers  
The last blog post I helped with on the EKS team. There are important changes for workloads with Amazon EBS volumes and the inevitable `dockershim` removal is in the 1.24 release so make sure you're ready for that. As well as many new features.

[Winter Soldier: Scale down your Infrastructure in the easiest possible way](https://devtron.ai/blog/winter-soldier-scale-down-your-infrastructure-in-the-easiest-possible-way/)  
Anugrah Chaturvedi, devtron  
"In this post, we'll focus on how to remove or scale down the orphaned (unused resources)" by making use of a tool called, "[Winter Soldier](https://github.com/devtron-labs/winter-soldier)"

[Cloud Platform Teams Are Everywhere — Here's Why](https://www.hashicorp.com/blog/cloud-platform-teams-are-everywhere-heres-why)  
Jared Ruckle, Hashicorp  
"In HashiCorp's new State of Cloud Strategy survey, 86% of respondents said they rely on cloud platform teams — for a wide variety of very good reasons."

[Manage Secrets on Kubernetes with ArgoCD and Vault](https://piotrminkowski.com/2022/08/08/manage-secrets-on-kubernetes-with-argocd-and-vault/)  
Piotr Minkowski  
"In this article, you will learn how to integrate ArgoCD with HashiCorp Vault to manage secrets on Kubernetes."

[Why we have containers](https://jessitron.com/2022/08/07/why-we-have-containers/)  
Jessitron  
"or, How a young program grew a little bit closer to software."

[All the Ways to Check If a Port is Open in Linux](https://adamtheautomator.com/check-if-a-port-is-open-in-linux/)  
Nicholas Xuan Nguyen, ATA Learning  
"In this article, you will learn several ways to check if a port is open in Linux so you may choose which ones work best for you. Ready? Read on!"

[Scaling Kubernetes to Thousands of CRDs](https://blog.upbound.io/scaling-kubernetes-to-thousands-of-crds/)  
Nic Cope, Upbound  
"Over the past few months Crossplane has pushed the boundaries of Kubernetes with the number of Custom Resources it supports. In this post we'll explore the limitations Upbound engineers have discovered and how we've helped to overcome them."

[aws-samples/eks-multi-cluster-gitops](https://github.com/aws-samples/eks-multi-cluster-gitops)  
⭐️ 56  
This is the multi-cluster EKS GitOps code I showed off at Open Source Summit.

[ine-labs/AWSGoat](https://github.com/ine-labs/AWSGoat)  
⭐️ 342  
A Damn Vulnerable AWS Infrastructure

## DevOps'ish Post of the Week

[![Karli Drew on Twitter: "Please understand: advances towards "back to normal" largely involve the reversal of accessibility measures. Telehealth appointments? Accessibility. Remote work? Accessibility. Widespread delivery and curbside pickup options? Accessibility. "Normal" isn't good enough.")](https://shortcdn.com/file/devopsish/280-devopsish-post-of-the-week.webp)](https://twitter.com/christianh814/status/1555641036713578498?utm_source=devopsish)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/280/notes.md?utm_source=devopsish)
