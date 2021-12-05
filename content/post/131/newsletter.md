+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2019"]
date = 2019-06-09T07:00:00Z
description = "DevOps Tools, Kubernetes ≠ Rocket Science, IBM Layoffs, Open Source Licenses Aren't Broken, Small Kubernetes Clusters, and More"
draft = false
slug = "131"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "IBM layoffs", "licenses", "Linus Torvalds"]
title = "131: DevOps tools, Kubernetes ≠ rocket science, IBM layoffs, Open Source licenses aren't broken, small Kubernetes clusters, and more"
image = "/images/kubernetes-what-if-i-told-you.jpg"
imagealt = "What if I told you... You don't have to be a Kubernetes expert to use it."

+++

This week's image was something I whipped up when talking to a friend. When I explained that running Kubernetes on a Raspberry Pi cluster or Digital Ocean didn't mean they had to be an expert at running Kubernetes, it tilted their world off axis a little. I blew away a cluster and rebuilt it from a handful of files in less than thirty minutes a couple of weeks ago. This should be a rare occurrence (and there should be backups). But, if there isn't time to troubleshoot (and you maintain proper configuration management), burn it down and start over if you make a mistake. It points to the practice Rob Hirschfeld discovered of [keeping Kubernetes clusters small](https://thenewstack.io/the-optimal-kubernetes-cluster-size-lets-look-at-the-data/) to reduce blast radius and snowflakes.

[**2019 State of Multicloud**](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE)  
A Report on the Underlying Dynamics Fueling Multicloud Strategies. [Download Today!](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) *SPONSORED*

[**DevOps'ish Summer 2019 Survey**](https://devopsi.sh/survey)  
Please take this year's survey. It is a handful of questions, will provide actionable feedback, and be greatly appreciated. The intent is to improve the overall experience and increase the value this newsletter provides to its readers. [Take the survey today!](https://devopsi.sh/survey)

[**How companies adopt and apply cloud native infrastructure--from O'Reilly**](https://www.oreilly.com/pub/cpc/224549)  
Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud. *SPONSORED*

## DevOps'ish Last Week's Top Five

1. [Kubernetes jobs: 11 salary stats to see](https://enterprisersproject.com/article/2019/5/kubernetes-jobs-11-salary-statistics)
1. [The Definitive Guide To Prometheus in 2019](http://devconnected.com/the-definitive-guide-to-prometheus-in-2019/)
1. [Top DevOps Skills Developers and Managers Need for Success](https://www.cloudbees.com/blog/top-devops-skills-developers-and-managers-need-success)
1. [A Gentle Introduction to DevOps](http://ravikirans.com/gentle-introduction-to-devops/)
1. [Command-line tools for Kubernetes: kubectl, stern, kubectx, kubens](https://developers.redhat.com/blog/2019/05/27/command-line-tools-for-kubernetes-kubectl-stern-kubectx-kubens/)

## People

[IBM layoffs affect more than 1,000 employees](https://www.cnbc.com/2019/06/06/ibm-layoffs-affect-more-than-1000-employees.html) — It was interesting to learn this week some folks at Red Hat received retention bonuses while others did not. This is a reminder of why the IBM acquisition of Red Hat makes people concerned.

[Experience from Six Months of Remote Work](https://www.justingarrison.com/blog/2019-05-29-six-months-remote/) — "While I've had lots of experience working in open source and tons of experience with communicating asynchronously doing full time work remotely is different. I wanted to share some things I've learned so far."

[The guy who made a tool to track women in porn videos is sorry](https://www.technologyreview.com/s/613607/facial-recognition-porn-database-privacy-gdpr-data-collection-policy/) — What could possibly go wrong?!? ¯\\\_(ツ)\_/¯

[New Evidence Suggests Satoshi Nakamoto Is Paul Solotshi, The Creator of Encryption Software E4M and TrueCrypt](https://www.investinblockchain.com/new-evidence-suggests-satoshi-nakamoto-is-paul-solotshi-the-creator-of-encryption-software-e4m-and-truecrypt/) — Everyboy knowns that [Chloe Condon](https://twitter.com/ChloeCondon) created Bitcoin (and probably blockchain).

[How I came back from burnout by learning to lean on my team - CircleCI](https://circleci.com/blog/how-i-came-back-from-burnout-by-learning-to-lean-on-my-team/)

## Process

[The problem with Amazon and Open Source isn't Amazon](https://anonymoushash.vmbrasseur.com/2019/06/07/the-problem-with-amazon-and-open-source-isnt-amazon/) — Jen Wike Huger and I played a part in starting this shit storm. But, in general, there is nothing wrong with open source licenses. There are a lot of things wrong with trying to build an entire business on 100% open source software with little to no value add. Yet, I do believe a reemergence of shareware could occur in a big way. Something along the lines of this software is for personal use only. Contact us for a license is happening already. I see a potential future where a competitor to OSI might form around these form of open source. Enough lawyers are poking at this and Linux Foundation is standing up new foundations every time Linus Torvalds blinks. There is too much smoke here for something not to be on fire.

[Why We're Relicensing CockroachDB](https://www.cockroachlabs.com/blog/oss-relicensing-cockroachdb/) — This is the only license I think is being honest while legal about commercial usage. But, make a better business.

[Google Cloud Networking Incident #19009](https://status.cloud.google.com/incident/cloud-networking/19009) — Network configuration change resulting in degraded service preventing connections to network devices to rollback changes is like the worst nightmare I think we've all been in at least once. The distinction in traffic Google can then manage and prioritize is fascinating.

[What is DevOps](https://devopsish.com/what-is-devops/) — "DevOps is the professional practice of frequent, continued, and iterative improvements through measurable changes, the goal of which is to become a high-velocity organization thus improving business outcomes."

[Empowering Users through Site Reliability Engineering](http://jasonhand.com/blog/empowering_users_through_site_reliability_engineering/) — "How does the service we are building change the way they perceive themselves? Does it make them better at something?"

[Sustainable Operations in Complex Systems with Production Excellence](https://www.infoq.com/articles/production-excellence-sustainable-operations-complex-systems/) — "Cultural and process changes, rather than changes in tooling alone, are necessary for teams to sustainably manage services... Services run more smoothly when quantitative risk analysis allows teams to prioritize fixes."

[This week's dead Google product is Google Trips, may it rest in peace](https://arstechnica.com/gadgets/2019/06/this-weeks-dead-google-product-is-google-trips-may-it-rest-in-peace/) — Hard to break this image Google has when products keep getting knocked off left and right.

[The Linux Foundation Fires All Staff and Editors at Linux.com. Future Uncertain.](http://techrights.org/2019/06/05/linux-com-future-uncertain/) — This is not positive.

[Rapid Kubernetes Growth Creates Some Pain](https://containerjournal.com/2019/06/04/rapid-kubernetes-growth-creates-some-pain/) — "A survey of 500 attendees at the recent KubeCon + CloudNativeCon 2019 Europe conference finds that nearly half the respondents (47%) are now running an instance of Kubernetes in a production environment."

## Tools

[Bash coprocess](https://medium.com/@copyconstruct/bash-coprocess-2092a93ad912) — "Bash versions 4.0 and above offer another way to start asynchronous processes in a subshell. This is done with the help of the `coproc` keyword."

[CNCF Tools Overview: Are You Cloud-Native?](https://epsagon.com/blog/cncf-tools-overview-are-you-cloud-native/)

[Why I no longer use Terraform for Templating Kubernetes](https://medium.com/@stobiewankenobi/why-i-no-longer-use-terraform-for-templating-kubernetes-9aef37741447) — Helm is the apparent solution but Helm leaves a lot to be desired.

[Service Mesh Interface with Lachlan Evenson](https://softwareengineeringdaily.com/2019/06/06/service-mesh-interface-with-lachlan-evenson/) — "Whichever container deployment system you choose, your application and its multiple servers need a way to route traffic, measure telemetry, and configure security policy. A service mesh abstraction can help serve these use cases."

[Generate new repositories with repository templates](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) — "[R]epository templates to make boilerplate code management and distribution a first-class citizen on GitHub."

[Why Red Hat is investing in CRI-O and Podman](https://www.redhat.com/en/blog/why-red-hat-investing-cri-o-and-podman)

[12 Common Tools for Your DevOps Team](https://www.tripwire.com/state-of-security/devops/common-tools-for-your-devops-team/) — Ansible is mentioned with venerable brands and projects.

[Why does macOS Catalina use Zsh instead of Bash? Licensing](https://thenextweb.com/dd/2019/06/04/why-does-macos-catalina-use-zsh-instead-of-bash-licensing/) — Why the sudden change? In a word: licensing.

[Kubernetes basics: Learn how to drive first](https://opensource.com/article/19/6/kubernetes-basics) — "Quit focusing on new projects and get focused on getting your Kubernetes dump truck commercial driver's license."

[59 Linux Networking commands and scripts](https://haydenjames.io/linux-networking-commands-scripts/)

[bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go

[majkinetor/au](https://github.com/majkinetor/au) — Chocolatey Automatic Package Updater Module

[CoolerVoid/HiddenWall](https://github.com/CoolerVoid/HiddenWall) — Tool to generate a Linux kernel module for custom rules with Netfilter hooking. (block ports, Hidden mode, rootkit functions etc)

## DevOps'ish Tweet of the Week

There is a tie for the DevOps'ish Tweet of the Week.

{{< tweet 1136709168323104768 >}}

{{< tweet 1136194197814272001 >}}

Notes from this week's issue can be found [here](./notes/).
