+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-09-25T07:00:00Z
description = ["Torvalds' M2 MacBook Air, LastPass had guests over for four days, Last Floppy-Disk Seller, Backstage, Graceful Shutdown with Lifecycle preStop Hook and more"]
draft = false
slug = "286"
tags = ["Kubernetes", "Linux", "Twitter", "podcast", "cloud", "cloud native", "security", "DevOps", "developers", "open source", "GitOps", "container", "OCI", "systems", "virtual", "engineers", "Detroit", "Argo", "Flux", "Linus Torvalds"]
title = "DevOps'ish 286: Torvalds' M2 MacBook Air, LastPass had guests over for four days, Last Floppy-Disk Seller, Backstage, Graceful Shutdown with Lifecycle preStop Hook and more"
+++

The bivalent booster is kicking me hard today. I got it around noon and my joints were hurting by 3 PM. My neck and both shoulders are sore and tight. Compounding existing injuries. I also just watched my Florida Gators lose to Tennessee. I'm gonna take the a break from writing an intro this week.

### Join the DevOps'ish Twitter Space on Monday

[This week in DevOps'ish](https://twitter.com/i/spaces/1lPKqBNQvrQGb), Monday, September 26th, 11 AM ET/1500 UTC

Follow me on [Twitter](https://twitter.com/ChrisShort) to get notified about upcoming Twitter Spaces. Subscribe to the [DevOps'ish Podcast](https://anchor.fm/devopsish) via your podcasting software of choice so you can listen on Mondays on your lunch break or ride home. Join the Twitter Space to participate and ask questions. Bring some friends along too!

The format for the podcast will be to go over the inputs into the DevOps'ish newsletter. That way it won't be a complete rehash of the newsletter itself but, instead a fun journey through the unique stories that people most enjoyed the previous week.

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

[**Kubernetes Contributor Summit North American 2022**](https://www.kubernetes.dev/events/2022/kcsna/cfp/)

Day 0 KubeCon

Submissions should be applicable for members of one of the Kubernetes orgs, especially if you’re making a change this cycle that affects multiple SIGs or have a topic that would be useful for the entire group

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

## People

[Linus Torvalds talks Rust on Linux, his work schedule and life with his M2 MacBook Air](https://www.zdnet.com/article/linus-torvalds-talks-rust-on-linux-his-work-schedule-and-life-with-his-m2-macbook-air/)  
Steven Vaughan-Nichols, ZDNET  
"At the 2022 Linux Plumbers Conference, Torvalds and I have a chance to sit down and talk again about life, Linux and scuba diving."

[IT’s Stressful. Ask DevOps. Stress in the IT Sector [2022 Survey]](https://spacelift.io/blog/are-it-jobs-stressful)  
Gosia Hytry, Spacelift  
This survey might be flawed because I find this hard to believe, "Women working in the IT sector experience much less stress than those in non-IT jobs (35% vs. 53%)." But, also, "DevOps engineers are more frequently stressed than the IT average. Over 40% of them admit to being stressed “often” or “very often” compared to 34% of the IT average."

[4-Day Workweek Brings No Loss of Productivity, Companies in Experiment Say](https://www.nytimes.com/2022/09/22/business/four-day-work-week-uk.html)  
Jenny Gross, The New York Times  
"More than 70 companies in Britain are undergoing a six-month experiment in which their employees get a paid day off each week. So far, most companies say it’s going well."

## Process

[LastPass says hackers had internal access for four days](https://www.bleepingcomputer.com/news/security/lastpass-says-hackers-had-internal-access-for-four-days/)  
Sergiu Gatlan, BleepingComputer
"LastPass says the attacker behind the August security breach had internal access to the company's systems for four days until they were detected and evicted." FOUR DAYS? And YOU didn't KNOW? Nothing looked off? No tooling was able to raise an alert??? HOW?

[Update Firefox and Thunderbird now! Mozilla patches several high risk vulnerabilities](https://www.malwarebytes.com/blog/news/2022/09/update-firefox-and-thunderbird-now-mozilla-patches-several-high-risk-vulnerabilities)  
Pieter Arntz, Malwarebytes  
Gnarly CVEs to vanquish and your earliest convenience.

[Does the GitOps Emperor Have No Clothes?](https://thenewstack.io/does-the-gitops-emperor-have-no-clothes/)  
Mike Long, CEO at Kosli, via The New Stack  
Folks, stop being religious about things. You can use Jenkins and Argo. It's okay. Trying to go all in on ONE tool leaves little room for those edge cases.

[The Deep Roots of Nigeria’s Cybersecurity Problem](https://www.wired.com/story/nigeria-cybersecurity-issues/)  
Olatunji Olaigbe, WIRED  
"Despite having one of the strongest data-protection policies in Africa, the country’s enforcement and disclosure practices remain dangerously broken."

[What We Discovered Analyzing the Top 100 Public Container Images](https://www.slim.ai/blog/container-report-2021.html)  
Ayse Kaya, Slim.AI  
Bloated containers are bad, complexity hinders understanding, and security issues are the three main issues seen in this report.

[Last Floppy-Disk Seller Says Airlines Still Order the Old Tech](https://www.businessinsider.com/last-floppy-disk-seller-airlines-still-order-storage-2022-9)  
Travis Clark, Business Insider  
The airline industry is giving the last floppy manufacturer busy for the next four years then it's probably game over.

## Tools

[I spent two years trying to do what Backstage does for free](https://stackoverflow.blog/2022/09/19/i-spent-two-years-trying-to-do-what-backstage-does-for-free/)  
Ryan Donovan, Stack Overflow Blog  
"Absent a time machine, telling others how to avoid my mistakes is the best I can do."

[Kubernetes Just Has to Get Easier for Developers](https://thenewstack.io/kubernetes-just-has-to-get-easier-for-developers/)  
B. Cameron Gain, The New Stack  
"A new group of tools and platforms is emerging to make K8s easier for developers to do their development work with little or no knowledge of Kubernetes."

[Chainguard releases Wolfi, a Linux 'undistribution'](https://www.zdnet.com/article/chainguard-releases-wolfi-a-linux-undistribution/)  
Steven Vaughan-Nichols, ZDNET  
"Chainguard takes a ~~new~~ approach to building a container Linux with all the security you'd need already baked in."

[Lima VM - Linux Virtual Machines On macOS](https://earthly.dev/blog/lima/)  
Adam Gordon Bell, Earthly Blog  
Lima is a CNCF project now. It's a great project that enables folks to mimic whatever environment they need.

[Git Revert: Rolling Back in GitOps and Kubernetes](https://komodor.com/learn/git-revert-rolling-back-in-gitops-and-kubernetes/)  
Daniel Slavin, Komodor  
"When using GitOps to manage your Kubernetes development, Git revert is a way to roll back while retaining complete version history in source control for all team members."

[Kubernetes Guide: Graceful Shutdown with Lifecycle preStop Hook](https://www.datree.io/resources/kubernetes-guide-graceful-shutdown-with-lifecycle-prestop-hook)  
Datree.io  
I forgot who I was talking to about it but, there's a cleaner way to see if a pod's connections are finished before being destroyed.

[Managing Kyverno Policies as OCI Artifacts with OCIRepository Sources](https://fluxcd.io/blog/2022/08/manage-kyverno-policies-as-ocirepositories/)  
developer-guy, Flux  
"One of them is OCI Repositories feature that allows us to store and distribute a wide variety of sources such as Kubernetes manifests, Kustomize overlays, and Terraform modules as OCI (Open Container Initiative) artifacts."

[siderolabs/kres](https://github.com/siderolabs/kres)  
Tool to automate build instructions generation

## DevOps'ish Post of the Week

This should **never, ever** be okay. Putin is a monster.

[![максим.еріставі on Twitter: "my family was just forced to vote at gunpoint in russian cosplay of a 'referendum' in southern ukraine: they come to your house, you have to openly tick the box for being annexed by russia (or for staying with ukraine if you feel suicidal), all while armed gunmen watch you")](https://shortcdn.com/devopsish/286-devopsish-post-of-the-week.webp)](https://twitter.com/maksymeristavi/status/1573356436091969536?utm_source=devopsish)

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/286/notes.md?utm_source=devopsish)
