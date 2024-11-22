+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-08-28
description = ["Senselessness, sleeplessness leads to selfishness, Twilio Breach, patch your GitLab, OpenLens, High Table Stakes of Modern Blogs, and more"]
draft = false
slug = "282"
tags = ["Kubernetes", "open source", "cloud", "security", "cloud native", "developer", "behavior", "vulnerability", "Linux", "kernel", "AWS", "KubeCost", "OpenLens", "GitLab", "suicide", "AdGuard", "DNS", "DevOps", "community", "advocacy", "Michigan"]
title = "DevOps'ish 282: Senselessness, sleeplessness leads to selfishness, Twilio Breach, patch your GitLab, OpenLens, High Table Stakes of Modern Blogs, and more"
+++

Another week, another senseless loss. This week marked the third suicide to take place in my family/extended family in my lifetime. To a degree, I understand if you're suffering. But, suicide is a long term solution to generally short term problems. If you or someone you know is considering harming yourself, please reach out. The psychological damage you will inflict on others is far worse than going to a therapist yourself. At the very least, please reach out to one of the numbers listed on the [American Psychological Association Crisis hotlines and resources](https://www.apa.org/topics/crisis-hotlines) page. I'm literally in therapy going through a suicide that was very close to me that I never got to put the loose ends around, from 15 years ago. Don't do this to people you care about, it's not fair.

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

[Erik Prince wants to sell you a "secure" smartphone that's too good to be true](https://www.technologyreview.com/2022/08/19/1058243/erik-prince-wants-to-sell-you-a-secure-smartphone-thats-too-good-to-be-true/)  
Patrick Howell O'Neill, MIT Technology Review  
"MIT Technology Review obtained Prince's investor presentation for the 'RedPill Phone,' which promises more than it could possibly deliver."

[What if I vanished?](https://daniel.haxx.se/blog/2022/08/24/what-if-i-vanished/)  
Daniel Stenberg, curl  
The creator of curl talks succession plans. The best time to make and test one of these plans is while you're still alive.

[Sleepless nights make people more selfish and asocial](https://www.theguardian.com/lifeandstyle/2022/aug/23/sleepless-nights-make-people-more-selfish-and-asocial-study)  
Sascha Pare, The Guardian  
"Losing even one hour of rest reduces ‘innate desire of humans to help one another', US research finds"

[People with disagreeable personalities (selfish, combative, and manipulative) do not have an advantage in pursuing power at work](https://pubmed.ncbi.nlm.nih.gov/32868412/)  
Cameron Anderson, Daron L Sharps, Christopher J Soto, Oliver P John, PubMed  
"A close examination of behavior patterns in the workplace found that disagreeable individuals engaged in two distinct patterns of behavior that offset each other's effects on power attainment: They engaged in more dominant-aggressive behavior, which positively predicted attaining higher power, but also engaged in less communal and generous behavior, which predicted attaining less power. These two effects, when combined, appeared to cancel each other out and led to a null correlation between disagreeableness and power."

[Wanted: 7,000 construction workers for Intel chip plants](https://apnews.com/article/intel-ohio-construction-workers-f5b7b4a083eb3142870a9654f43b438b)  
Andrew Welsh-Huggins, AP News  
"Ohio's largest-ever economic development project comes with a big employment challenge: how to find 7,000 construction workers in an already booming building environment when there's also a national shortage of people working in the trades."

## Process

[Why the Twilio Breach Cuts So Deep](https://www.wired.com/story/twilio-breach-phishing-supply-chain-attacks/)  
Lily Hay Newman, WIRED  
"The phishing attack on the SMS giant exposes the dangers of B2B companies to the entire tech ecosystem."

[Update now! GitLab issues critical security release for RCE vulnerability](https://www.malwarebytes.com/blog/news/2022/08/update-now-gitlab-issues-critical-security-release-for-rce-vulnerability)  
Pieter Arntz, Malwarebytes Labs  
"GitLab has released versions 15.3.1, 15.2.3, 15.1.5 for GitLab Community Edition (CE) and Enterprise Edition (EE). These versions contain important security fixes, and it's recommended that all GitLab installations be upgraded to one of these versions immediately."

[SolarWinds Hackers Using New Post-Exploitation Backdoor 'MagicWeb'](https://www.hackread.com/solarwinds-hackers-exploit-backdoor-magicweb/)  
Deeba Ahmed, HackRead  
"Microsoft has warned that the new post-compromise backdoor MagicWeb lets hackers 'authenticate as anyone.'"

[Vulnerability in Linux containers – investigation and mitigation](https://www.benthamsgaze.org/2022/08/22/vulnerability-in-linux-containers-investigation-and-mitigation/)  
Steven J. Murdoch  
"The good news is that the vulnerability affects a feature of Linux access control permissions that is not widely used – negative group permissions."

["As Nasty as Dirty Pipe" — 8 Year Old Linux Kernel Vulnerability Uncovered](https://thehackernews.com/2022/08/as-nasty-as-dirty-pipe-8-year-old-linux.html)  
Ravie Lakshmanan, The Hacker News  
"'DirtyCred is a kernel exploitation concept that swaps unprivileged kernel credentials with privileged ones to escalate privilege," researchers Zhenpeng Lin, Yuhang Wu, and Xinyu Xing noted. 'Instead of overwriting any critical data fields on kernel heap, DirtyCred abuses the heap memory reuse mechanism to get privileged.'"

## Tools

[Kubernetes v1.25: Pod Security Admission Controller in Stable](https://kubernetes.io/blog/2022/08/25/pod-security-admission-stable/)  
Tim Allclair (Google), Sam Stoelinga (Google), Kubernetes  
Kubernetes 1.25 came out this week and along with it the replacement for PSPs; Pod Security Admission Controllers. Here's the [CHANGELOG](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.25.md#v1250).

[Why your website should be under 14kB in size](https://endtimes.dev/why-your-website-should-be-under-14kb-in-size/)  
Nathaniel  
TCP's slow start creates this weird phenomenom, "What is surprising is that a 14kB page can load much faster than a 15kB page — maybe 612ms faster — while the difference between a 15kB and a 16kB page is trivial."

[AWS and Kubecost collaborate to deliver cost monitoring for EKS customers](https://aws.amazon.com/blogs/containers/aws-and-kubecost-collaborate-to-deliver-cost-monitoring-for-eks-customers/)  
Mike Stefaniak and Vipin Mohan, AWS  
"Amazon EKS customers can deploy an EKS optimized bundle of Kubecost for cluster cost visibility. This is available free of charge, and customers can get Kubecost support from AWS as part of their existing AWS support agreements. Kubecost enables users to view costs broken down by Kubernetes resources including pods, nodes, namespaces, labels, and more."

[AdGuard DNS v2.0 goes open source](https://adguard.com/en/blog/adguard-dns-2-0-goes-open-source.html)  
Andrey Meshkov, AdGuard DNS  
Released under an AGPL license, AdGuard DNS is going open source, again.

[Is it time to migrate from Lens to OpenLens to manage your Kubernetes clusters?](https://blog.devgenius.io/is-it-time-to-migrate-from-lens-to-openlens-75496e5758d8)  
Armin Nikdel, Dev Genius  
"tl;dr; OpenLens is same as Lens IDE without proprietary components and its free of charge based on MIT license. However currently there is no signed binary available for OpenLens. This article discusses crowdfunding regarding code signature for the community, and it shows how to compile OpenLens ourselves for macOS, Linux, and Windows."

[Heroku announces plans to eliminate free plans, blaming 'fraud and abuse'](https://techcrunch.com/2022/08/25/heroku-announces-plans-to-eliminate-free-plans-blaming-fraud-and-abuse/)  
Kyle Wiggers, TechCrunch  
I'm super curious if anyone reading this is still using Heroku. "Starting November 28, the Salesforce-owned cloud platform as a service will stop providing free product plans and shut down free data services and soon (on October 26) will begin deleting inactive accounts and associated storage for accounts that have been inactive for over a year."

[The Surprisingly High Table Stakes of Modern Blogs](https://www.swyx.io/the-surprisingly-high-table-stakes-of-modern-blogs/)  
Modern day blogs are hard work. Really hard work.

[Turning SQLite into a distributed database](https://univalence.me/posts/mvsqlite)  
Heyang Zhou  
"mvSQLite is the open-source, SQLite-compatible distributed database. We decoupled SQLite's storage layer onto FoundationDB to offer massive yet 'bottomless' scalability, point-in-time reads, and the strictest level of consistency."

[zinclabs/zinc: ZincSearch](https://github.com/zinclabs/zinc)  
⭐️ 11.4K
A lightweight alternative to elasticsearch that requires minimal resources, written in Go.

[runsidekick/sidekick](https://github.com/runsidekick/sidekick)  
⭐️ 692  
Free and open-source live application debugger. Like chrome dev tools but for your backend

[k8spacket/k8spacket](https://github.com/k8spacket/k8spacket)  
⭐️ 173  
Packets traffic visualization for kubernetes

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/282/notes.md?utm_source=devopsish)
