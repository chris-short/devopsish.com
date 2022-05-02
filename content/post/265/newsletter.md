+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-05-01T07:00:00Z
description = ["DevOps'ish 265"]
draft = false
slug = "265"
tags = ["Argo", "Kubernetes", "GitOps", "CNCF", "cloud", "reliability", "data", "security", "open source", "AWS", "Honeycomb", "Cancer"]
title = "DevOps'ish 265"
+++

Hey, y'all! What I miss???

This is the only sentence that will feature Elon Musk this week. Promise. He's had enough coverage lately and I hope you've had your fill. Also, I won't be discussing any CNCF shenanigans until after KubeCon EU 2022. I'd like for there to be a resolution prior, but I doubt there will be at this point.

I'm back on the horse after my 4 month old niece's passing (I hope you can understand the brief hiatus). Thank you to everyone who reached out. Thank you to my incredibly team at AWS. Also, special thanks to our sponsor [Honeycomb](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) for allowing me the time to process this loss.

It's tragic; beyond what few can imagine. But, Lucy was strong. She gave hospitals and labs across the country a ton of data on a very rare form of cancer. I'm almost proud to say that my niece might have improved testing nationwide and globally. Whenever the hospital in Detroit did a lab, they sent samples to other labs across the country. This is modus operandi. You never know and sure as hell don't want to make a mistake.

Guess what? The labs here in Detroit were usually spot on. A lab in Seattle, *never* detected her cancer, ever.

Think about that for a second. The tremendous impact her short life has made on testing for this form of cancer alone... While it fixes nothing, there's a chance (maybe) a kid in her theoretical lifetime could beat this given some of these advances in testing. That helps me, a little, and I hope it helps others a lot more.

**On to the newsletter!**

DevOps'ish is brought to you by your friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).

***"Stop Letting Complexity Slow You Down"***

[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easier to understand and troubleshoot complex relationships within your distributed services. *Solve problems faster*. *Ship reliable and performant features*. *SPONSORED*

## Events

[**SLOConf - Service Level Objective Conference**](https://www.sloconf.com/)

MAY 9-12, 2022


Site Reliability Engineering is one of the hottest areas as companies look to build reliable systems and their online presence. As companies rush to adopt Site Reliability Engineering principles, Service Level Objectives (SLOs) are the most important place to begin. SLOs are the combination of cultural philosophies, practices, and tools.

The SRE community needs a place to gather and focus on SLOs in depth. This virtual conference will cover topics at all levels, from introduction to SLOs to the practical application of SLOs. This conference is a community event made and led by Site Reliability Engineers and influencers who care about reliability and becoming more customer centric by adopting, measuring and optimizing SLOs.

[AWS Container Days @ KubeCon Europe 2022](https://awscontainerdayseurope.splashthat.com/)

May 10th-13th, and 17th

8:00am-10:00am PT | 17:00-19:00 CEST

Event to be streamed at <https://www.twitch.tv/aws>, register for calendar invites

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish)

MAY 17, 2022

Designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[I'm a security engineer and I still almost got scammed](https://robertheaton.com/almost-scammed/)

Robert Heaton

This cat almost got got. These attacks are getting way more sophisticated. But, basically, never take a phone call directly from your bank. You call them at a known good number.

[US Army could 'waste' up to $22b on Microsoft HoloLens](https://www.theregister.com/2022/04/26/army_microsoft_headset/)

Katyanna Quach, The Register

Well... That's disconcerting. "Will soldiers actually use these goggles? Asking for a watchdog"

[A Nigerian engineer who helped build Fast’s product speaks out](https://www.businessofbusiness.com/articles/nigeria-engineer-defunct-startup-fast/)

Chidinma Divine Iwu, The Business of Business

"Early product development at once promising one-click payments startup Fast was done by engineers in Nigeria. One of them told us what working for the company was like."

[‘Bossware is coming for almost every worker’: the software you might not realize is watching you](https://www.theguardian.com/technology/2022/apr/27/remote-work-software-home-surveillance-computer-monitoring-pandemic?CMP=fb_a-technology_b-gdntech)

Zoë Corbyn, The Guardian

I'm just glad their creepy graphic doesn't follow my mouse around the screen.

## Process

[Log4j Attack Surface Remains Massive](https://www.darkreading.com/threat-intelligence/l0g4j-attack-surface-remains-huge)

Jai Vijayan, Dark Reading

"Four months after the Log4Shell vulnerability was disclosed, most affected open source components remain unpatched, and companies continue to use vulnerable versions of the logging tool."

[The first open-source Kubernetes security platform just scored $30 million](https://www.geektime.com/armo-kubescape-raises-30m-series-a/)

Geektime

ARMO, the Israeli startup that created the Kubernetes open-source security project Kubescape, just closed a Series A investment round

[Fedora not deprecating legacy BIOS - yet](https://lwn.net/Articles/892826/)

corbet, LWN.net

There was some talk of going over to UEFI by default but not yet. That's going to be an interesting upgrade.

[Cloudflare blocks 15M rps HTTPS DDoS attack](https://blog.cloudflare.com/15m-rps-ddos-attack/)

Omer Yoachimik and Julien Desgats, Cloudflare

"While this isn’t the largest application-layer attack we’ve seen, it is the largest we’ve seen over HTTPS." Eek!

[Google Cloud to submit Istio service mesh project to CNCF](https://www.protocol.com/enterprise/google-cloud-istio-cncf)

Donna Goodison, Protocol

The most lightly covered CNCF news this week. "Istio is the last major component of the Kubernetes ecosystem to sit outside of the CNCF. At one point, Google seemed unsure whether it would cede control of the service-mesh project, but things have changed."

## Tools

[Migrate Kubernetes cluster autoscaler to Karpenter (Video)](https://www.youtube.com/watch?v=sXYNmnzbEFA)

Justin Garrison, AWS

Justin did a really good job with this. "We will migrate a Amazon EKS Kubernetes cluster using the cluster autoscaler to Karpenter for node autoscaling."

[Service Mesh Comparison](https://servicemesh.es/)

Anja Kammer, Christine Koppelt, Jörg Müller, Hanna Prinz, Christopher Schmidt, and Eberhard Wolff, INNOQ

This is a handy chart when considering implementing service meshes.

[Securing Kubernetes with Open Policy Agent](https://asankov.dev/blog/2022/04/21/securing-kubernetes-with-open-policy-agent/)

Anton Sankov

"Build-in Kubernetes security is not enough for most organizations to enforce granular rules and policies to the workloads running in their clusters. That is why projects like OPA and Gatekeeper exist to help you achieve a higher level of Kubernetes security"

[Tailscale Authentication for NGINX](https://tailscale.com/blog/tailscale-auth-nginx/)

Xe Iaso, Tailscale

Nifty!!! This could come in real handy.

[GPU-Powered RAID Blasts to 110 GBps, 19 Million IOPS](https://www.tomshardware.com/news/gpu-powered-raid-110-gbps-19-million-iops)

Zhiye Liu, Tom's Hardware

A bunch of these and you'll blow every storage budget on the planet but it'll be faster than anything out there.

[Broadband internet: Copper telephone wire could be almost as fast as fibre](https://www.newscientist.com/article/2317040-ordinary-copper-telephone-wire-could-carry-gigabit-broadband-speeds/)

Matthew Sparkes, New Scientist

"Many homes in the UK rely on repurposed phone lines for internet access, leading to slow download speeds, but there may be a solution"

[Introducing zq: an Easier (and Faster) Alternative to jq](https://www.brimdata.io/blog/introducing-zq/)

Brim Data

"Zed operators are like jq filters but they can be stateful. To make this work, we simply borrowed the aggregate function concept from the 50 year-old SQL model, though unlike SQL, [Zed aggregate functions](https://zed.brimdata.io/docs/language/aggregates/) can [stream their results incrementally](https://zed.brimdata.io/docs/language/overview/#610-aggregate-function-calls)."

[etcd/v3.5-data-inconsistency](https://github.com/etcd-io/etcd/blob/main/Documentation/postmortems/v3.5-data-inconsistency.md)

Marek Siarkowicz, etcd

The postmortem for the etcd 3.5.[1-2] data inconsistency issue. Lovely title, I know.

[dimensionhq/fleet](https://github.com/dimensionhq/fleet)

🚀 The blazing fast build tool for Rust.

[NetBook-ai/spawner](https://github.com/NetBook-ai/spawner)

Mulit-Cloud infrastructure orchestrator for kubernetes first development.

[AlexsJones/prop-rep](https://github.com/AlexsJones/prop-rep)

Find out which organisations are best represented in a repository

[kris-nova/boopkit](https://github.com/kris-nova/boopkit)

Linux eBPF backdoor over TCP. Spawn reverse shells, RCE, on prior privileged access. Less Honkin, More Tonkin.

[Cerchie/git-cherry-pick-tutorial](https://github.com/Cerchie/git-cherry-pick-tutorial)

"I wrote this tutorial to help you learn how to use git-cherry-pick 🍒"

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/265/notes/) to see what didn't make it to the newsletter but are still worth your time.
