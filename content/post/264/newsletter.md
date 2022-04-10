+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-04-10T07:00:00Z
description = ["DevOps'ish 264"]
draft = false
slug = "264"
tags = ["Argo", "SLOs", "GitOps", "reliability", "service", "Kubernetes", "Raspberry Pi", "semiconductor coolant", "Flux", "engineering", "cloud native"]
title = "DevOps'ish 264"
+++

DevOps'ish is brought to you by your friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easier to understand and troubleshoot complex relationships within your distributed services. *Solve problems faster*. *Ship reliable and performant features*. *SPONSORED*

## Events

[**SLOConf - Service Level Objective Conference**](https://www.sloconf.com/)  
MAY 9-12, 2022  

Site Reliability Engineering is one of the hottest areas as companies look to build reliable systems and their online presence. As companies rush to adopt Site Reliability Engineering principles, Service Level Objectives (SLOs) are the most important place to begin. SLOs are the combination of cultural philosophies, practices, and tools.

The SRE community needs a place to gather and focus on SLOs in depth. This virtual conference will cover topics at all levels, from introduction to SLOs to the practical application of SLOs. This conference is a community event made and led by Site Reliability Engineers and influencers who care about reliability and becoming more customer centric by adopting, measuring and optimizing SLOs.

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish)  
MAY 17, 2022  
Designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)  
SEPTEMBER 19 – 21, 2022  
ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

![Fast cofounder and CEO Domm Holland. Picture via Fast](https://shortcdn.com/file/devopsish/Fast-cofounder-and-CEO-Domm-Holland.webp)  
[CEO of Failed Startup Fast Leaves Staff Hanging in Companywide Meeting](https://www.businessinsider.com/ceo-of-failed-startup-fast-leaves-staff-hanging-companywide-meeting-2022-4) ([archive.org](https://web.archive.org/web/20220408100743/https://www.businessinsider.com/ceo-of-failed-startup-fast-leaves-staff-hanging-companywide-meeting-2022-4))  
[Leaked Screenshots and Audio Reveal the Implosion Inside Fast](https://www.businessinsider.com/leaked-screenshots-audio-stripe-fast-layoffs-2022-3) ([archive.org](https://web.archive.org/web/20220409102738/https://www.businessinsider.com/leaked-screenshots-audio-stripe-fast-layoffs-2022-3))  
"CEO of Fast Domm Holland left employees hanging by a thread during an all-hands meeting that took place Tuesday, shortly after the company announced it would be closing its doors." Remember this face. Do yourself a favor and avoid this serial failure.

[Biden Invokes Defense Production Act to Boost Critical Mineral Supply](https://www.nytimes.com/2022/03/31/business/economy/biden-minerals-defense-production-act.html)  
We're going to have to get a lot better at extracting used lithium, nickel, cobalt, graphite, manganese and other critical minerals.

[Learning By Lurking](https://www.netmeister.org/blog/learning-by-lurking.html)  
This is pretty much how becoming a community member in Kubernetes works. Start showing up to meetings and eventually you'll know enough to actually do something. Before you know it, you'll be an official org member and off you go.

['We Interviewed a Coder. Someone Else Showed Up for the Job'](https://thenewstack.io/we-interviewed-a-coder-someone-else-showed-up-for-the-job/)  
This would be utterly terrifying.

[The Rise of the 9 p.m. Work Hour](https://www.theatlantic.com/newsletters/archive/2022/04/triple-peak-day-work-from-home/629457/)  
Burn it. Burn it with fire.

## Process

[3M's Semiconductor Coolant Plant Closed Indefinitely](http://www.businesskorea.co.kr/news/articleView.html?idxno=90116)  
"3M's semiconductor coolant plant in Belgium has been closed indefinitely under tightened local environmental regulations. The plant accounts for 80 percent of the global total semiconductor coolant output."

[Attacking rival, Google says Microsoft’s hold on government security is a problem](https://www.nbcnews.com/tech/security/attacking-rival-google-says-microsofts-hold-government-security-proble-rcna22159)  
On one hand, I have to admit I was shocked when I joined the Air Force and found wildly insecure networks all on the backs of Windows. On the other, this is corporate mudslinging at its finest.

[Lapsus$ and SolarWinds hackers both use the same old trick to bypass MFA](https://arstechnica.com/information-technology/2022/03/lapsus-and-solar-winds-hackers-both-use-the-same-old-trick-to-bypass-mfa/)
"Not all MFA is created equal, as script kiddies and elite hackers have shown recently."

[PHP bug allows attackers to bypass domain filters, stage DoS attacks against servers](https://portswigger.net/daily-swig/php-bug-allows-attackers-to-bypass-domain-filters-stage-dos-attacks-against-servers)  
"Filter bypass flaw is triggered only on very large user input, which puts restrictions on its exploitability"

[U.S. Says It Secretly Removed Malware Worldwide, Pre-empting Russian Cyberattacks](https://www.nytimes.com/2022/04/06/us/politics/us-russia-malware-cyberattacks.html)  
This is an actionable plan to counterattack potentially devastating attacks against all manner of infrastructure. Declassifying the fact you did within days of doing it is even wilder.

## Tools

[Kubernetes Removals and Deprecations In 1.24](https://kubernetes.io/blog/2022/04/07/upcoming-changes-in-kubernetes-1-24/)
I have written or said containerd so many time this year.

[Raspberry Pi OS Loses Default ‘Pi’ User for Security](https://www.tomshardware.com/news/raspberry-pi-default-username-removed)  
Knowing the username to most of the Raspberry Pis on earth felt very 1990s.

[Japanese Data Center Starts Eel Farming Side Hustle](https://www.tomshardware.com/news/japanese-data-center-starts-eel-farming-side-hustle)  
Talk about diversification.

[Service Mesh (Linkerd) | Raspberry Pi Kubernetes Cluster](https://picluster.ricsanfre.com/docs/service-mesh/)  
Yup! You can run a service mesh on your Raspberry Pi cluster. Not Istio though.

[Terraform: Up & Running, 3rd edition Early Release is now available!](https://blog.gruntwork.io/terraform-up-running-3rd-edition-early-release-is-now-available-4efd0eb2ce0a)  
Learn about 10 problems that have been fixed in Terraform since the 2nd edition

[flux-subsystem-argo/flamingo](https://github.com/flux-subsystem-argo/flamingo)  
"FSA (aka Flamingo) is Flux Subsystem for Argo. FSA's container image can be used as a drop-in replacement for the equivalent ArgoCD version to visualize, and manage Flux workloads, alongside ArgoCD." I need to take this for a spin.

[EmilHernvall/dnsguide](https://github.com/EmilHernvall/dnsguide)  
A guide to writing a DNS Server from scratch in Rust

[Amazon EKS now supports Kubernetes 1.22](https://aws.amazon.com/blogs/containers/amazon-eks-now-supports-kubernetes-1-22/)  
My first ever blog post at AWS.

## DevOps'ish Tweet of the Week

[![Thinking this today .... (Berkubernetus @fuzzychef on Twitter)](https://shortcdn.com/file/devopsish/264-devopsish-tweet-of-the-week.webp)](https://twitter.com/fuzzychef/status/1512137902477627423)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/264/notes/) to see what didn't make it to the newsletter but are still worth your time.

