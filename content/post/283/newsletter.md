+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-09-04
description = ["Cloudflare's demise, Fog Data Science, Privileged Ports Must Die, OpenTelemetry, COSI, and more"]
draft = false
slug = "283"
tags = ["Kubernetes", "cloud native", "USB 4", "Detroit", "Developers", "DevOps", "SRE", "software", "security", "OpenTelemetry", "object storage"]
title = "DevOps'ish 283: Cloudflare's demise, Fog Data Science, Privileged Ports Must Die, OpenTelemetry, COSI, and more"
+++

It's a holiday weekend here in the US. We spent Saturday afternoon soaking in some of the best Detroit has to offer: Eastern Market, the Detroit Jazz festival, river walk, Renaissance Center, Hart Plaza, Woodward Ave, and Campus Martius. It was cool that most of downtown was blocked off so we could walk more freely than usual. Downtown was alive thanks to the Jazz festival. I can't wait for folks to see this magnificent city during KubeCon.

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

[Kiwi Farms: Anti-trans stalkers chasing Keffals around the world](https://www.nbcnews.com/tech/internet/cloudflare-kiwi-farms-keffals-anti-trans-rcna44834)  
Ben Collins and Kat Tenbarge, NBC News
"A trans streamer and a Republican congresswoman were targeted at their homes in the last month. Experts warn this is just the beginning." This situation has gotten so bad I've just finished moving everything OFF Cloudflare for good.

[Quiet Quitting Is About Bad Bosses, Not Bad Employees](https://hbr.org/2022/08/quiet-quitting-is-about-bad-bosses-not-bad-employees)  
Jack Zenger and Joseph Folkman, Harvard Business Review  
The headline says it all. "Our data indicates that quiet quitting is usually less about an employee’s willingness to work harder and more creatively, and more about a manager’s ability to build a relationship with their employees where they are not counting the minutes until quitting time."

[Inside Fog Data Science, the Secretive Company Selling Mass Surveillance to Local Police](https://www.eff.org/deeplinks/2022/08/inside-fog-data-science-secretive-company-selling-mass-surveillance-local-police)  
Bennett Cyphers, Electronic Frontier Foundation  
"The company, Fog Data Science, has claimed in marketing materials that it has 'billions' of data points about 'over 250 million' devices and that its data can be used to learn about where its subjects work, live, and associate." It's never the "big, bad" companies. It's always some obscure one that no one hears of until you read about it here.

[Opinion: deleting online accounts should not be hard](https://www.ghacks.net/2022/09/01/opinion-deleting-online-accounts-should-not-be-hard/)  
Martin Brinkmann, gHacks Tech News  
"There is no standard procedure that users may follow; some sites may not even offer a quick delete option for user accounts. It may be necessary to contact support or even send them a Fax to get an account deleted. Even sites that make it less difficult may require some digging in the account settings or support pages to find out how the account can be deleted."

## Process

[Dear Linux, Privileged Ports Must Die](https://ar.al/2022/08/30/dear-linux-privileged-ports-must-die/)  
Aral Balkan  
"As it was in Unix in the 1980s, so it is now, that any process that wants to bind to a port less than 1024 must have elevated privileges. These ports are known as “privileged ports.” While this was a security feature in the days of dumb terminals, in the age of the World Wide Web, it is a security vulnerability."

[What is USB4? Differences from Thunderbolt 4, older USB versions explained](https://arstechnica.com/gadgets/2022/09/breaking-down-how-usb4-goes-where-no-usb-standard-has-gone-before/)  
Scharon Harding, Ars Technica  
"USB4 is compatible with USB 2.0 and 3.2 and can support Thunderbolt 3 and 4. Remember that you'll get the lowest data transfer rate available. For example, if you plug a USB4 40Gbps cable into a USB 3.2 Gen 1 port on your laptop, expect the cable to work at 5Gbps."

[Devops vs SRE](https://www.justingarrison.com/blog/2202-08-30-devops-vs-sre/)  
Justin Garrison, Liz Fong-Jones, and Emily Freeman  
"My first observation was that devops—in its intended form—required an org chart that was decentralized. SRE took an exact opposite approach and centralized the responsibility of reliability in a role. Sometimes SRE roles work on product teams, but they often report to a central SRE org and not the team manager."

## Tools

[K8s IRL](https://www.youtube.com/watch?v=aB0zE-gzgkY)  
Justin Garrison, AWS

[Argo CRDs and Kustomize: The Problem of Patching Lists](https://blog.argoproj.io/argo-crds-and-kustomize-the-problem-of-patching-lists-5cfc43da288c)  
Zach Aller, Argo Project  
"As an end user of any Argo Project or a Kubernetes custom resource and also a user of Kustomize, I want to be able to use strategic merge patches (SMPs) for environment variables or any array type field within the resource definition."

[End-to-end tracing with OpenTelemetry](https://blog.frankel.ch/end-to-end-tracing-opentelemetry/)  
Nicolas Fränkel  
Stem to stern OpenTelemetry education

[Introducing COSI: Object Storage Management using Kubernetes APIs](https://kubernetes.io/blog/2022/09/02/cosi-kubernetes-object-storage-management/)  
Sidhartha Mani, Minio, Inc  
"File and block storage are treated as first class citizens in the Kubernetes ecosystem via [Container Storage Interface](https://kubernetes.io/blog/2019/01/15/container-storage-interface-ga/) (CSI). Workloads using CSI volumes enjoy the benefits of portability across vendors and across Kubernetes clusters without the need to change application manifests. An equivalent standard does not exist for Object storage... COSI aims to standardize consumption of object storage."

[Creating a kubernetes cluster with kubeadm on Ubuntu 22.04 LTS](https://balaskas.gr/blog/2022/08/31/creating-a-kubernetes-cluster-with-kubeadm-on-ubuntu-2204-lts/)  
Evaggelos Balaskas  
This is really thorough.

[21 Basic Yet Essential Linux Networking Commands](https://itsfoss.com/basic-linux-networking-commands/)  
Sagar Sharma, It's FOSS  
"This compilation includes CLI utilities that will help you with troubleshooting network issues, monitoring packets, connected devices, and much more."

[Ramilito/kubediff](https://github.com/Ramilito/kubediff)  
⭐️ 20  
Source VS Deployed

[airwallex/k8s-pod-restart-info-collector](https://github.com/airwallex/k8s-pod-restart-info-collector)  
⭐️ 43  
Automated troubleshooting of Kubernetes Pods issues. Collect K8s pod restart reasons, logs, and events automatically.

[ktock/buildg](https://github.com/ktock/buildg)  
⭐️ 345  
Interactive debugger for Dockerfile, with support for IDEs (VS Code, Emacs, Neovim, etc.)

[natesales/q](https://github.com/natesales/q)  
⭐️ 832  
A tiny command line DNS client with support for UDP, TCP, DoT, DoH, DoQ and ODoH.

## DevOps'ish Post of the Week

[![Julia Ferraioli on Twitter: "Trying to understand the background behind the push against @Cloudflare? This thread from Ben has you covered. #CloudflareProtectsTerrorists #DropCloudflare")](https://shortcdn.com/devopsish/283-devopsish-post-of-the-week.webp)](https://twitter.com/juliaferraioli/status/1565826386690199553?utm_source=devopsish)

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/283/notes.md?utm_source=devopsish)
