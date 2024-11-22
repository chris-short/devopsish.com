+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-06-26
description = ["Open Source Summit, Tiger Global, KubeCon's Lack of Diversity, Interim CNCF Code of Conduct Committee, ugit, GitBOM, Fermyon, Clockwork, and more"]
draft = false
slug = "273"
tags = ["Argo", "Kubernetes cluster", "Kubernetes", "cluster", "open source", "CNCF", "SSH", "Fermyon", "artifact", "Clowckwork", "AWS", "cloud", "community", "Tailscale", "WebAssembly", "system", "observability"]
title = "DevOps'ish 273: Open Source Summit, Tiger Global, KubeCon's Lack of Diversity, Interim CNCF Code of Conduct Committee, ugit, GitBOM, Fermyon, Clockwork, and more"
+++

This week I was in Austin, Texas (where it was hotter than the hinges of hell) at Open Source Summit. I staffed the AWS booth, attended a few talks, met with friends I hadn't seen in long, and became generally reinvigorated about open source. It's my last event on the Amazon EKS team. I'm moving inside the Containers organization at AWS to work on a new and different project.

AWS was a leading sponsor. I had great conversations with folks. Undergrads, customers, partners, and others had questions about Kubernetes, EKS, or GitOps. I gave a booth demo on Multi-Cluster GitOps, a solution we intend to open source soon.

I was impressed by quite a few sponsors there. [Camunda](https://camunda.com), [Coder](https://coder.com) (thanks for the Caddy config), [KubeCost](https://www.kubecost.com/), [Solo](https://www.solo.io/), and [Capital One](https://www.capitalone.com/tech/) all had great presences at the conference. But two newer companies melted my brain with how excellent their products were: **Fermyon** and **Clockwork**.

[Fermyon](https://www.fermyon.com) ventured out to start a company for all you WebAssembly fans (closet fan, still need to learn it). Fermyon is making a batteries included WebAssembly platform. I feel Fermyon will soon make its way into the mainstream WebAssembly developers' workflows. My friend Michelle Dhanani and others from Microsoft are there, so I'm certain they'll be doing some fantastic things. Be sure to checkout their `spin` repo in the [Tools](#tools) section.

[Clockwork](https://www.clockwork.io/) is another company that caught my eye. Their premise is that their time service is highly available AND highly accurate. Using this in your Kubernetes cluster will provide very precise time stamps. If you've ever noticed an event in your cluster before the resource was created, you need a better timing solution, and Clockwork is here to provide it. They are so accurate and highly available that they compare themselves to Google Spanner's TrueTime system, which helps that database solution overcome the CAP Theorem. They demonstrated microsecond accuracy even when they lose significant resources and time stays accurate to the microsecond.

## Observability Leader Honeycomb Releases O’Reilly Book on Observability

Honeycomb helps you sift through billions of events to see your application’s hidden problems so you can quickly debug before users notice. Get your FREE copy of our [new O’Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors’ Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts

## Events

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Tiger Global: 'Poster Child' of the Tech Meltdown](https://nymag.com/intelligencer/2022/06/tiger-global-poster-child-of-the-tech-meltdown.html)  
Michelle Celarier, Intelligencer  
"The guy who started as a shy analyst would put up impressive gains for years, then suffer mind-boggling losses: $25 billion (and counting) as of June, a record figure even in the lofty world of hedge funds." What goes up, must come down.

[DocuSign CEO Dan Springer steps down](https://www.cnbc.com/2022/06/21/docusign-ceo-dan-springer-steps-down.html)  
Jessica Bursztynsky, CNBC  
"DocuSign CEO Dan Springer is stepping down in his role after the e-signature software maker lost more than 60% of its value year to date."

[KubeCon + CloudNativeCon Europe 2022 Transparency Report](https://www.cncf.io/reports/kubecon-cloudnativecon-europe-2022/)  
CNCF Staff  
As I mentioned [on Twitter](https://twitter.com/ChrisShort/status/1540391736970821642), I am very disappointed in our diversity stats. CNCF senior leadership needs to look inwardly and realize this isn't what we want as a community.

[Stack Overflow Developer Survey 2022](https://survey.stackoverflow.co/2022/)  
Stack Overflow Staff  
It's as if Steve Ballmer is walking out on a stage, sweaty af, yelling, "Containers, containers, containers."

[Tips for passing the Certified Kubernetes Administrator (CKA) Exam](https://www.thecloudonmymind.com/Tips-for-passing-the-Certified-Kubernetes-Administrator-CKA-Exam/)  
The Cloud On My Mind
"I was extremely nervous before writing the CKA exam, but with the right strategy this exam can be less stressful to take and you too can enjoy the sweet certificate and badge provided by the Linux Foundation when you pass 😄"

## Process

[CNCF's Interim CNCF Code of Conduct Committee has launched](https://www.cncf.io/blog/2022/06/23/cncfs-interim-cncf-code-of-conduct-committee-has-launched/)  
CNCF Staff  
The community took control of the CNCF Code of Conduct process. I have the faintest of hopes for the right things to be done. But, from the looks of things, I might not be a KubeCon Detroit if cards fall a certain way.

[Hired Releases Annual State of Wage Inequality in Tech Data Report 2022](https://hired.com/blog/highlights/hired-releases-annual-state-wage-inequality-tech-data-report-2022/)  
Hired Staff  
"The gender and race wage gap is narrowing, but access to opportunity and discrepancies in salaries persist for underrepresented tech talent." We have to do better as an industry.

[New NTLM Relay Attack Lets Attackers Take Control Over Windows Domain](https://thehackernews.com/2022/06/new-ntlm-relay-attack-lets-attackers.html)  
Ravie Lakshmanan, The Hacker News  
"Spooler service disabled, RPC filters installed to prevent PetitPotam and File Server VSS Agent Service not installed but you still want to relay [Domain Controller authentication to [Active Directory Certificate Services]? Don't worry MS-DFSNM have (sic) your back," security researcher Filip Dragovic said in a tweet." When are we ridding the world of NTLM?

## Tools

[Undo your last git mistake with ugit](https://bhupesh.me/undo-your-last-git-mistake-with-ugit/)  
Bhupesh Varshney  
"It’s just a simple shell script with guided programmatic steps to undo your last git command, powered by FZF built for people who live and work with terminals every day."

[Deploying a HA Kubernetes cluster on Raspberry Pi using Kubeadm](https://sayakm.me/deploying-a-ha-kubernetes-cluster-on-raspberry-pi-using-kubeadm/)  
Sayak Mukhopadhyay  
"I hadn't had the opportunity to set up a cluster by myself. But, I always wanted to setup a bare metal cluster one day." Bare Metal Kubernetes is the future for a lot of folks.

[SpaceX Starlink Internet Experience & Performance (US Midwest, Mid 2022) Review](https://www.phoronix.com/scan.php?page=article&item=spacex-starlink&num=1)  
Michael Larabel, Phoronix  
If these are the speeds over Chicago, I do not feel bad at all about not rushing out to get on the Starlink bandwagon.

[Introducing Tailscale SSH](https://tailscale.com/blog/tailscale-ssh/)  
Brad Fitzpatrick, Maisem Ali, Maya Kaczorowski and Ross Zurowski, Tailscale  
"Tailscale SSH allows you to establish SSH connections between devices in your Tailscale network, as authorized by your access controls, without managing SSH keys, and authenticates your SSH connection using WireGuard®."

[Using Vim as Your MySQL Shell Editor](https://trstringer.com/vim-mysqlsh/)  
Thomas Stringer  
I thought this was a pretty nifty vim use case.

[![If your GitHub workflows use the Ubuntu image, interact with AWS, and started breaking today, it is likely due to the fact that the AWS CLI has been updated to v2.7.9, which includes breaking changes. @hasheddan on Twitter)](https://shortcdn.com/devopsish/hasheddan-github-actions.webp)](https://twitter.com/hasheddan/status/1540016556184305672)

[GitBOM](https://gitbom.dev/)  
"GitBOM is a minimalistic scheme for build tools to:

1. Build a compact Artifact Dependency Graph (ADG), tracking every source code file incorporated into each built artifact.
1. Embed a unique, content-addressable reference for that Artifact Dependency Graph (ADG), the GitBOM identifier, into the artifact at build time."

[ondat/discoblocks](https://github.com/ondat/discoblocks)  
"Open Source declarative disk configuration system for Kubernetes" We need more projects like this to help simplify storage for cluster admins.

[fermyon/spin](https://github.com/fermyon/spin)  
"Spin is an open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly"

[nyph-infosec/daggerboard](https://github.com/nyph-infosec/daggerboard)  
"DaggerBoard is a vulnerability scanning tool that ingests Software Bill of Material (SBOM) files (CycloneDX,SPDX) and outputs results in a human-readable format. This tool evaluates software dependencies outlined within the SBOM file for package vulnerabilities."

## DevOps'ish Post of the Week

Friday was a "where were you when" kind of day.

[![@YourAnonNews on Twitter)](https://shortcdn.com/devopsish/273-devopsish-post-of-the-week.webp)](https://twitter.com/YourAnonNews/status/1540526828603015169)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
