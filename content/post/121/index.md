+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-03-31T07:00:00Z
description = "Kubernetes 1.14, Cloudy with a Chance of Complexity, Accelerate State of DevOps survey, and More"
draft = false
slug = "121"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "container", "security"]
title = "121: Kubernetes 1.14, Cloudy with a Chance of Complexity, Accelerate State of DevOps survey, and More"

+++

There is something to be said about simplicity. The amount of [yak shaving](https://www.hanselman.com/blog/YakShavingDefinedIllGetThatDoneAsSoonAsIShaveThisYak.aspx) needed these days is enormous. I've been on and off trying to get a container up and running in a cloud native manner. I've tried all of the major cloud providers and a few more. But, to a cloud, they all have inadequacies of one sort or another. If one has weird load balancing, the other has an absurdly expensive database service (compared to the competition). If one has a clean Kubernetes implementation, the other is missing a few features. This stuff isn't easy and if anyone thinks it is they've likely gotten ahold of a round peg they can force into a square hole more times than not. Keep your heads up out there.

> "Don't let yesterday use up too much of today." —Will Rogers

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*

**New Microsoft Azure Elastic Agent Plugin for GoCD**  
With GoCD's new Azure plugin, run your CI/CD pipelines on Azure virtual machines, and let GoCD scale up on-demand agents based on your need. Remove bottlenecks and reduce the cost of your agent infrastructure.

Learn more about GoCD: [www.gocd.org](https://www.gocd.org)  
Learn more about GoCD's Azure plugin: https://extensions-docs.gocd.org/azure/current/ *SPONSORED*

[**Audiobook: Lean Enterprise**](https://devopsi.sh/g8MpN7)  
How well does your organization respond to changing market conditions, customer needs, and emerging technologies? This practical guide presents Lean and Agile principles and patterns that enable you to move fast at scale—and demonstrates why and how to apply these methodologies throughout your organization, rather than in just one department or team. Through case studies, you'll learn how successful enterprises have rethought everything from governance and financial management to systems architecture and organizational culture in the pursuit of radically improved performance. *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [5 Ways to Boost Your Earning Potential in DevOps](https://www.thirdrepublic.com/blog/boost-earning-potential-devops)
1. [nomedium.dev](https://nomedium.dev)
1. [Defining a Distinguished Engineer](https://blog.jessfraz.com/post/defining-a-distinguished-engineer/)
1. [DevOps hiring and training: 16 top-rated skills](https://enterprisersproject.com/article/2019/3/devops-hiring-and-training-16-top-rated-skills)
1. [Elegantly activating a virtualenv in a Dockerfile](https://pythonspeed.com/articles/activate-virtualenv-dockerfile/)

## People

[‘Developers' lives matter' – Chinese software engineers use Github to protest against the country's 996 work schedule](https://www.scmp.com/tech/start-ups/article/3003691/developers-lives-matter-chinese-software-engineers-use-github) — As stated in the group's [GitHub repo](https://github.com/996icu/996.ICU), "The name 996.ICU refers to 'Work by "996", sick in ICU', an ironic saying among Chinese programmers, which means that by following the "996" work schedule, you are risking yourself getting into ICU (Intensive Care Unit)."

[Want an awesome job, working in a great team, with a tremendous leader?](https://social.icims.com/viewjob/pt1553611085158445da) — If you're in Europe and want to work on the Ansible team with other fellow Red Hatters. This is the job for you (maybe)!

[The Cloud Pod — Episode 16: This week in the cloud blob](https://www.thecloudpod.net/podcast/episode-16-this-week-in-the-cloud-blob/) — AWS Summit Season 2019 is officially underway. Justin, Peter and special guest Chris Short [@chrisshort](https://twitter.com/ChrisShort). Plus the famous lightning round.

[Report: U.S. workers hate ‘open' office spaces](https://www.prdaily.com/report-u-s-workers-hate-open-office-spaces/) — File this under, "Shit You Already Knew"

[5 Ways to Leave Your Work Stress at Work](https://hbr.org/2019/03/5-ways-to-leave-your-work-stress-at-work)

[On building a new engineering hub in Dublin](https://stripe.com/blog/dublin-eng-office) — Stripe shows you how they go about opening an office in a brand new region. It's pretty fascinating.

## Process

[Take the Accelerate State of DevOps survey today!](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5) — Can you spare some time to help the DORA research team know what it takes to make great software?

[Litmus: Journey of a storage e2e and chaos framework for Kubernetes](https://blog.openebs.io/litmus-journey-of-a-storage-e2e-and-chaos-framework-for-kubernetes-dc09a3904a24) — Litmus is so cool.

[[ANNOUNCE] Security release of Kubernetes kubectl - potential directory traversal - Releases 1.11.9, 1.12.7, 1.13.5, and 1.14.0 - CVE-2019-1002101 - Announcements](https://discuss.kubernetes.io/t/announce-security-release-of-kubernetes-kubectl-potential-directory-traversal-releases-1-11-9-1-12-7-1-13-5-and-1-14-0-cve-2019-1002101/5712) — Update kubectl if you haven't already.

[Over 100,000 GitHub repos have leaked API or cryptographic keys](https://www.zdnet.com/article/over-100000-github-repos-have-leaked-api-or-cryptographic-keys/) — We've all done it. But, there are tools to help now at least.

[A complete list of every product Google has ruthlessly killed](https://www.fastcompany.com/90322103/a-eulogy-for-every-product-google-has-ruthlessly-killed-145-and-counting) — It's hard to buy into a Google product these days.

[How do you encourage pragmatism in the face of shiny objects?](https://www.reddit.com/r/devops/comments/b4tesi/how_do_you_encourage_pragmatism_in_the_face_of/) — There's a balance here. But, if a new tool is solving an old problem consider a better use case.

## Tools

[Kubernetes 1.14: Production-level support for Windows Nodes, Kubectl Updates, Persistent Local Volumes GA](https://kubernetes.io/blog/2019/03/25/kubernetes-1-14-release-announcement/) — Kubernetes 1.14 consists of 31 enhancements: 10 moving to stable, 12 in beta, and 7 net new.

[Kubernetes v1.14: What you need to know](https://developers.redhat.com/blog/2019/03/25/kubernetes-v1-14-what-you-need-to-know/) — Persistent local storage, Windows nodes, kustomize, and more.

[Kubernetes Podcast from Google — Kubernetes 1.14, with Aaron Crickenberger](https://kubernetespodcast.com/episode/046-kubernetes-1.14/) — The Lead of sig-beard and the 1.14 release team lead joined the Kubernetes Podcast this week.

[Kubernetes-based Microservice Observability with Istio Service Mesh: Part 2](https://itnext.io/kubernetes-based-microservice-observability-with-istio-service-mesh-part-2-f25c4b474a65) — Prometheus, Grafana, Jaeger, and Kiali! Oh my!

[How to run PostgreSQL on Kubernetes](https://opensource.com/article/19/3/how-run-postgresql-kubernetes) — Create uniformly managed, cloud-native production deployments with the flexibility to deploy a personalized database-as-a-service.

[Endlessh](https://nullprogram.com/blog/2019/03/22/) — An SSH Tarpit

[Getting started with Vim: The basics](https://opensource.com/article/19/3/getting-started-vim) — `:q` to quit vim, y'all!

[Istio monitoring explained](https://blog.giantswarm.io/Istio-monitoring-explained/) — Fernando Ripoll explains Istio in a way I haven't seen before.

[Kubernetes has a problem called etcd](https://www.reddit.com/r/kubernetes/comments/b6g90j/kubernetes_has_a_problem_called_etcd/) — etcd is stable but, it's not exactly a simple answer to a not exactly simple problem.

[Install OpenShift in a container with Weave Footloose](https://blog.alexellis.io/openshift-in-a-footloose-container/) — "In this tutorial we will install OpenShift in a container using a new tool called [footloose](https://github.com/weaveworks/footloose) by Weaveworks."

[A Self-Hosted Global Load Balancer for OpenShift](https://blog.openshift.com/a-self-hosted-global-load-balancer-for-openshift/) — "While the technology is not yet ready for prime time, I hope that the described architecture will spark new ideas and foster new contributions so that these types of solutions can be used to improve how geographically distributed architectures can be built using OpenShift."

[Find the right AMI everytime: Make your AWS application work in any region](https://www.ansible.com/blog/find-the-right-ami-everytime-make-your-aws-application-work-in-any-region) — Working with three syllable thing (AMI) with three syllable tool (Ansible).

[Analysis of Open source Kubernetes Operators](https://medium.com/@cloudark/analysis-of-open-source-kubernetes-operators-f6be898f2340) — "In this post we present analysis of open source Kubernetes Operators available on GitHub."

[Ansible AWX 4.0.0](https://github.com/ansible/awx/releases/tag/4.0.0) — 48 commits in this release

[minikube 1.0.0](https://github.com/kubernetes/minikube/releases/tag/v1.0.0) — Going v1!!!

[lyft/cartography](https://github.com/lyft/cartography) — Cartography is a Python tool that consolidates infrastructure assets and the relationships between them in an intuitive graph view powered by a Neo4j database.

[vietnam-devs/coolstore-microservices](https://github.com/vietnam-devs/coolstore-microservices) — A Kubernetes-based polyglot microservices application with Istio service mesh

[weaveworks/flagger](https://github.com/weaveworks/flagger) — Istio and App Mesh progressive delivery Kubernetes operator

[ivx/kube-cleaner](https://github.com/ivx/kube-cleaner) — A utility to keep your kubectl config-file in check.

[jay-johnson/metalnetes](https://github.com/jay-johnson/metalnetes) — Create and manage multiple Kubernetes clusters using KVM on a bare metal Fedora 29 server

[fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI in Go based on Material Design

## DevOps'ish Tweet of the Week

{{< tweet 1112017864205185024 >}}
