+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-03-15T07:00:00Z
description = "Rays of light that give us hope, A Minute on the Mic, new AMD & Intel vulns, Oxide Computer, good Operators, NTP in a Kubernetes cluster, and more"
draft = false
slug = "171"
tags = ["cloud", "DevOps", "Kubernetes", "open source", "good", "container", "cloud native", "crisis", "Intel", "AMD", "GKE", "AWS", "control plane", "Open Policy Agent", "developers", "coronavirus", "orchestration", "EKS", "SARS", "cluster", "Operator", "Azure", "Linux"]
title = "DevOps'ish 171"

+++

In dark times, there are typically rays of light that can be found to give us hope. I read an article last weekend that I thought would be worth mentioning here this week. [*Will the coronavirus crisis, like Sars, give birth to the next big thing in China tech?*](https://www.scmp.com/tech/big-tech/article/3073961/will-coronavirus-crisis-sars-give-birth-next-big-thing-china-tech) looks at how the Chinese e-commerce giants Alibaba and JD.com got their start during the SARS crisis of 2002-2003. The coronavirus caused markets to tank this week. But, US banks had plenty of liquidity from the Federal Reserve and capital on hand thanks to regulations passed after the 2008 financial crisis. A global outbreak of this nature will have a significant economic impact. But, there will be some good that comes from this current crisis. One possible example is that a few companies have halted stock buybacks. [Stopping stock buybacks might do some good for the economy](https://hbr.org/2020/01/why-stock-buybacks-are-dangerous-for-the-economy) as companies maintain capital that can be invested in things that will be more impactful during this trying time. [Use your time effectively like Isaac Newton](https://www.washingtonpost.com/history/2020/03/12/during-pandemic-isaac-newton-had-work-home-too-he-used-time-wisely/) did. You might not invent calculus or theories for gravity and motion but, the time you save from commuting might be able to be put to some good use. Keep your heads up.

Note: Starting this week, I'm stopping all e-mail click and open tracking. After 170 weeks of doing this, if I don't know what you want to read by now, I'm not doing a good job. This change will impact marketing efforts, but your privacy matters more to me. The only metric I have left to give to potential sponsors is subscribers. Do this newsletter a favor and help it grow. [Tell your whole team to subscribe today](https://devopsish.com/subscribe/).

## People

[A Good Word in the Storm? #hugops](https://blog.iirc.life/p/a-good-word-in-storm-hugops.html)  
"The infection curve will hit the inflection point. We will go back to 'conferencing' and I suspect that it will be all the harder to honor the 'no hugs, just verbal greetings' advisories when that happens."

[Humble Book Bundle: Land a Tech Job 2.0 by For Dummies (pay what you want and help charity)](https://www.humblebundle.com/books/tech-job-for-dummies-2-books)  
This bundle includes one of the best books on DevOps by Emily Freeman. I could probably use that SQL for Dummies book too (I'm so bad at syntax).

[The Diffblue Developer Survey](https://www.diffblue.com/Education/research_papers/2019-diffblue-developer-survey/?utm_source=newsletter&utm_medium=email&utm_campaign=DevOpsIsh)  
What's wrong with software speed, quality, and cost? Oxford-based AI company Diffblue surveyed 300 developers to find out what the people who actually work with code have to say about testing, their pain points, and what's holding back DevOps in their organizations. *SPONSORED*

[A Minute on the Mic](https://aminuteonthemic.com/)  
A new effort put together by [Laura Santamaria](https://nimbinatus.com/), A Minute on the Mic is a group of minute-long videos from experts answering questions related to relevant topics in tech. For example, eliminating toil and working from home were the first two topics. More videos are dropping next week!

['Leave the ladder down behind you rather than pull it up'](https://www.siliconrepublic.com/people/consensys-claire-fitzpatrick)  
"Claire Fitzpatrick of ConsenSys highlights some of the the rewarding and challenging parts of her career as a woman in tech."

{{< tweet 1236670741464178688 >}}

## Process

[AMD processors from 2011 to 2019 vulnerable to two new attacks](https://www.zdnet.com/article/amd-processors-from-2011-to-2019-vulnerable-to-two-new-attacks/)  
"Academics disclose new Collide+Probe and Load+Reload attacks on AMD CPUs."

[Intel CPUs vulnerable to new LVI attacks](https://www.zdnet.com/article/intel-cpus-vulnerable-to-new-lvi-attacks/)  
"Researchers say Intel processors will need another round of silicon chip re-designs to protect against new attack."

[Containers and Kubernetes: 3 transformational success stories](https://www.cio.com/article/3530277/containers-and-kubernetes-3-transformational-success-stories.html)  
"This powerful combo of workload portability and orchestration has become an invaluable business asset in multi-cloud and hybrid cloud environments."

[EKS vs. GKE vs. AKS — Comparing the top three cloud providers](https://www.stackrox.com/post/2020/02/eks-vs-gke-vs-aks/?utm_source=DevOps'ish&utm_medium=email&utm_campaign=sponsored)  
Not all managed Kubernetes services are created the same. They support different features and options for their cluster control planes and nodes, and they vary in how much management they really provide. To help cut through the fog, StackRox performed a hands-on, side-by-side comparison of the top three services (EKS, AKS, GKE) to help you understand the current state of these services and the trade-offs between them. *SPONSORED*

[Oxide Computer wants to build cloud hardware for everybody](https://www.protocol.com/oxide-computer-cloud-server)  
"Oxide Computer is a bold bet by three prominent engineers that some day, more and more companies will want cloudlike hardware under their own control."

[How Visa built its own container security solution](https://www.csoonline.com/article/3529974/how-visa-built-its-own-container-security-solution.html)  
"The homegrown solution takes advantage of the native capabilities that already exist on container orchestration platforms and is primarily built on top of open-source tools and libraries."

## Tools

[What makes a good Operator?](https://blog.openshift.com/what-makes-a-good-operator/)  
One Operator per managed application, one controller per custom resource definition, and do not hard-code namespaces or resources names are some pretty basic guidelines but, there are many other good bits folks should try to stick to (or at least be aware of the compromises you might be making).

[Managed Kubernetes Price Comparison (2020)](https://devopsdirective.com/posts/2020/03/managed-kubernetes-comparison/)  
"TL;DR: Azure and Digital Ocean don't charge for the compute resources used for the control plane, making AKS and DO the cheapest for running many, smaller clusters. For running fewer, larger clusters GKE is the most affordable option."

[Open Policy Agent's Mission to Secure the Cloud](https://thenewstack.io/open-policy-agents-mission-to-secure-the-cloud/)  
"OPA is an open-source tool that enables the enforcement of a wide range of policies across domains and all layers in the stack. This policy engine supplies users with greater control over their environment while eliminating the need to write a different policy language, API, or model for each product and service."

[USB Keystroke Injection Protection](https://opensource.googleblog.com/2020/03/usb-keystroke-injection-protection.html)  
"To make the life of an attacker harder, we propose a tool that measures the timing of incoming keystrokes and determines if it is an attack based on predefined heuristics (without a user being involved in the decision)."

[Free AWS, Azure, GCP, Kubernetes Architecture Diagram Tool](https://www.cloudskew.com/)  
Draw cloud architecture diagrams for free!

[NTP in a Kubernetes cluster](https://tech.goglides.com/2020/03/09/manage-ntp-using-kubernetes/)  
"I am going to follow this blog to create a build process for NTPD docker image and use that image to run NTPD in the Kubernetes cluster."

[7 tips to speed up your Linux command line navigation](https://www.redhat.com/sysadmin/cli-speedup)  
"The command line doesn't have to be tedious, it can be awesome with these shortcuts."

[Monitor Your Container Environment in One Place](https://www.datadoghq.com/dg/monitor/containers/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=DevOpsish-Newsletter04&utm_content=Containers)  
With Datadog's Live Container view, you can see every container's health, resource consumption, and running processes in real time. Datadog, a cloud-scale monitoring platform, allows you to easily monitor and manage your dynamic container fleet. Start today with a free 14-day trial. *SPONSORED*

[A 'No-BS' Checklist for Kubernetes](https://thenewstack.io/a-no-bs-checklist-for-kubernetes/)  
"To help you navigate the space and ask vendors the right questions, we created this no-BS Kubernetes checklist. All of the “must-haves” for a future-ready Kubernetes strategy are included in the list."

[similarweb/statusbay](https://github.com/similarweb/statusbay)  
Kubernetes deployment visibility like a pro

## DevOps'ish Tweet of the Week

{{< tweet 1237387483987374083 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/171/notes/) to see what didn't make it to the newsletter.
