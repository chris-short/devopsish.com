+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-08-29T07:00:00Z
description = ["DevOps'ish 232: seccomp's day in the Kubernetes sun, Linux at 30, burn out, Chevy Bolt bot blunder, lifelong learning, GitOps, and more"]
draft = false
slug = "232"
tags = ["Kubernetes", "cloud", "cloud native", "security", "DevOps", "GitOps", "open source", "Red Hat", "RBAC", "seccomp", "Google", "workflows", "community", "cluster", "sigstore", "operator", "admission controllers", "Intel", "secure", "Teleport", "production", "software", "developers", "GitOpsCon", "KubeCon", "mortgage", "financial", "algorithm", "stack", "equipment", "infrastructure", "code", "automate", "Terraform", "robot", "Chevy Bolt", "Linux", "systems", "traffic", "errors", "tool", "supply", "release", "environments", "eBPF"]
title = "DevOps'ish 232: seccomp's day in the Kubernetes sun, Linux at 30, burn out, Chevy Bolt bot blunder, lifelong learning, GitOps, and more"

+++

A trying week capped off by trigger point injections. Long story short, I've been trying to get a family out of Afghanistan for the past two weeks to no avail. I won't bore you with info or divulge identifying details. But, the possibility for their safe passage to the US has pretty much gone to 0. It's hard telling a 16-year-old kid that you've exhausted all your resources. You can only offer tidbits of info. HUGE shoutout to the team behind [Ehtesab](https://ehtesab.af/) for enabling me to get SOME intel from folks on the ground. The situation itself is a failure.

A failure on multiple levels. But, it's a stark reminder that you have to experiment and sometimes try all the ways possible to get a solution into production. Can you deploy this feature as a feature flag, or do you need a canary or blue/green deployment? At what layer are you going to manage THAT? Your global load balancer? Maybe inside your application stack on a `keepalived`  instance? Perhaps it's better to handle this in your Kubernetes cluster by managing replica sets or ingresses. Once you get past that decision, there are many more along the way. Then it's "go time." Your solution is ready to handle some production traffic.

You start seeing increased errors, so you roll back. This release isn't a failure, though. Maybe it's a bug somewhere else in the system. Maybe your environments aren't as consistent as you thought. Perhaps you're lacking a critical piece of information that somehow didn't make it to you (a recent change in the system like admission controllers being enabled in prod). This is why having a team that you can actively collaborate with is vital. You can do this in person or via Slack/Teams/etc. Regardless your peers might have seen behaviors like this before, and they know the answer. Better yet, the team rallies around the error and figures out your ingress isn't configured quite right (or you forgot a crucial new config). Remember the concept of [above the line and below the line](https://queue.acm.org/detail.cfm?id=3380777). You might have an excellent understanding of the abstractions but, maybe not that 20% use case people bump into.

The point is, test, validate, get peer reviews, and use your people network (internal or external) to the best of your ability. People are your greatest asset, no matter what part of the stack you're working on. People hold knowledge and capabilities. Never stop growing those networks. They will pay off at some point. Yes, soft skills matter more than your coding, configuration, and tests A LOT.

## People

[Burning out and quitting](https://mayakaczorowski.com/blogs/burnout)  
A friend who thought I needed to read this sent it to me. Maya Kaczorowski makes burnout more clear for me. Jury is still out on whether or not I'm burned out or tired of my injuries affecting work performance.

[Easy steps on how to secure your Kubernetes cluster by installing Teleport, an open-source, identity-aware access proxy.](https://youtu.be/2diX_UAmJ1c?utm_source=devopsish&utm_campaign=232)  
Teleport allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments. Learn more at [https://goteleport.com/docs/](https://goteleport.com/docs/?utm_source=devopsish&utm_campaign=232) *SPONSORED*

[A Third Of Stitch Fix’s Workers Have Quit En Masse](https://www.buzzfeednews.com/article/carolineodonovan/stitch-fix-employees-quitting)  
This seems like a calculated decision by at least one of the parties involved. The cause and effect is clear. If you take away flexibility, you're going to be losing talent.

[Programmers Don’t Understand Hash Functions](https://soatok.blog/2021/08/24/programmers-dont-understand-hash-functions/)  
"I don’t blame software developers for their lack of understanding on anything I’m going to discuss. The term “hash function” can accurately represent any of the following [five] disparate topics in computer science..."

[It’s Time for Police to Stop Using ShotSpotter](https://www.eff.org/deeplinks/2021/07/its-time-police-stop-using-shotspotter)  
Bad AI leads to really bad outcomes.

[GitOpsCon Schedule](https://events.linuxfoundation.org/gitopscon-north-america/program/schedule/)  
GitOpsCon is a KubeCon day zero event and the schedule of speakers is certified dope.

[The secret bias hidden in mortgage-approval algorithms](https://apnews.com/article/lifestyle-technology-business-race-and-ethnicity-mortgages-2d3d40d5751f933a88c1e17063657586)  
"An investigation by The Markup has found that lenders in 2019 were more likely to deny home loans to people of color than to white people with similar financial characteristics — even when we controlled for newly available financial factors that the mortgage industry has in the past said would explain racial disparities in lending."

## Process

[Google Cloud Status](https://status.cloud.google.com/incidents/8DhiwfKvD987f5tJrj1G)  
Google had an unusual reason for downtime in australia-southeast2. "The issue was transient voltage at the feeder to the network equipment, causing the equipment to reboot. In order to mitigate the issue, traffic within the australia-southeast2 region was redirected temporarily."

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
Code, No Manual Processes. Automate Terraform tasks, reduce errors and drifts, improve security and auditability of your infrastructure. env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. *SPONSORED*

[Misaligned factory robot may have sparked Chevy Bolt battery fires](https://arstechnica.com/cars/2021/08/misaligned-factory-robot-may-have-sparked-chevy-bolt-battery-fires/)  
Read about how one robot at LG Chem has drastic impact downstream. Only the future will tell if the Chevy Bolt can get past this Pinto-esque moment.

[30 years of Linux: OS was successful because of how it was licensed, says Red Hat](https://www.theregister.com/2021/08/25/30_years_of_linux_red_hat/)  
"On the 30th anniversary of the announcement of Linux by Linus Torvalds, Red Hat has said that it all worked out because of the way the OS was licensed."

[‘Lifelong learning will be normalised and seen as essential’](https://www.siliconrepublic.com/careers/lifelong-learning-future-of-work-2)  
I've been saying this for a long time. But, resting on your laurels is only going to hurt yourself these days.

[SIG Docs needs your help!](https://groups.google.com/g/kubernetes-dev/c/zA3q5MaIzp0/m/crVoQ__JAAAJ)
"TL;DR: SIG Docs needs help from you (or your company) to continue providing quality docs. Are you interested in helping contribute, or taking on a leadership role, in the open source community? Reach out to us on slack or reply here!"

[After Razer, SteelSeries Software Also Hit by Zero-Day Vulnerability, SteelSeries Responds (Update)](https://www.tomshardware.com/news/steelseries-admin-vulnerability)  
This might be the quickest way to break into Windows systems these days.


## Tools

[Conditionally setting your gitconfig](https://utf9k.net/blog/conditional-gitconfig/)  
I did not realize you could do conditions in gitconfigs. This is kind of a game changer.

[Manage incidents directly from Slack 🧑‍🚒](https://consuming-macrospore.herokuapp.com/b?y=49q24eh2c4r3ce1gcoo3echi65h62opj74rjcdpic9ij6e3571im4dpocch2o8ji48t24q3keho76ehf5tp6urrkdhsisqbf5svnat3dbtpmutbicdijqrj5etpmopbkehin49j1dlo3mtbkdlfmqpb4d5qmqfb4clr6us3jd5pmg8g=?utm_source=devopsish&utm_campaign=232)  
Rootly helps automate the tedious manual work like creating incident channels, searching for runbooks, documenting the postmortem timeline, and more. Teams sized 20 to 2000 manage hundreds of incidents daily and save thousands of engineering hours a year within Rootly. Get started in <5min or book a demo to learn more and get Starbucks ☕ on us! *SPONSORED*

[GitOps Guide to the Galaxy (Ep 21): RBAC Revisited](https://www.youtube.com/watch?v=pI9UqMwgElM)  
"Failure is not an option! We revisit the subject of  Role-based access control (RBAC) with three, yes count them THREE, different patterns. We will be taking a look at SSO, Authentication, and Git workflows approach to RBAC. So join us to learn more about the dynamic duo of GitOps and RBAC. If you missed the previous episode about RBAC, watch it here: https://youtu.be/XsiPPjnKFGw"

[A New Tool Wants to Save Open Source From Supply Chain Attacks](https://www.wired.com/story/sigstore-open-source-supply-chain-code-signing/)  
If you didn't read this article or want to get up to speed on [Sigstore](https://www.sigstore.dev/), join us on Tuesday at 10 AM ET/1400 UTC as we sit down with the one and only, Luke Hinds, creator of Sigstore. Check out the [Red Hat Livestreaming calendar](https://red.ht/streamcal) for details.

[A Checklist of Cloud Security Orienteering](https://gist.github.com/ramimac/823e52befba373d71bc936d1742768f4)  
"How to orienteer in a cloud environment, dig in to identify the risks that matter, and put together actionable plans that address short, medium, and long term goals."

[Enable seccomp for all workloads with a new v1.22 alpha feature](https://kubernetes.io/blog/2021/08/25/seccomp-default/)  
"Kubernetes v1.22.0 introduces a new kubelet feature gate SeccompDefault, which has been added in alpha state as every other new feature. This means that it is disabled by default and can be enabled manually for every single Kubernetes node."

[Managing Kubernetes seccomp profiles with security profiles operator](https://medium.com/@LachlanEvenson/managing-kubernetes-seccomp-profiles-with-security-profiles-operator-c768cff58b0)  
"In my last [blog](https://medium.com/@LachlanEvenson/how-to-enable-kubernetes-container-runtimedefault-seccomp-profile-for-all-workloads-6795624fcbcc), we learned about setting the RuntimeDefault flag in Kubernetes which configures all Pods to use a specific seccomp profile. While this is a great addition to improve your Kubernetes security posture, the runtime default seccomp profile might expose more syscalls than your application needs. In addition, the creation and management of seccomp profiles is cumbersome and error prone for cluster administrators. This is problem space is what the security profile operator sets out to solve. In this blog we’ll cover the features of the [security profile operator](https://github.com/kubernetes-sigs/security-profiles-operator) and how to use it."

[metacontroller/metacontroller](https://github.com/metacontroller/metacontroller)  
"Writing kubernetes controllers can be simple"

[cloud-native-toolkit/multi-tenancy-gitops](https://github.com/cloud-native-toolkit/multi-tenancy-gitops)
"This repository shows the reference architecture for gitops directory structure"

[sigstore/community](https://github.com/sigstore/community)  
"General sigstore community repo"

[nailgun](https://leshow.github.io/post/nailgun/)  
DNS benchmarking tool

## DevOps'ish Tweet of the Week

[![Jaana Dogan ヤナ ドガン (@rakyll) on Twitter: "Hard skills are hard, soft skills are harder."](https://shortcdn.com/file/devopsish/232-devopsish-tweet-of-the-week.png)](https://twitter.com/rakyll/status/1430696443044532228)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/232/notes/) to see what didn't make it to the newsletter but are still worth your time.
