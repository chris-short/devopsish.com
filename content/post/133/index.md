+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-06-23T07:00:00Z
description = ""
draft = false
slug = "133"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "weekly newsletter"]
title = "133:"

+++

INTRO

[**2019 State of Multicloud**](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE)  
A Report on the Underlying Dynamics Fueling Multicloud Strategies. [Download Today!](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) *SPONSORED*

[[Webinar] Every commit should have an issue ticket number](https://try.datree.io/trace-commits-to-tickets)  
Referencing an issue ticket in each commit is a development best practice. It improves code reviews, creates audit trails, and keeps you compliant. Learn how to implement this scalably with CircleCI + Datree.io. *SPONSORED*

## DevOps'ish Last Week's Top Five

1. 
1. 
1. 
1. 
1. 

## People

[The worst morale boosting gesture I’ve experienced](https://shkspr.mobi/blog/2019/06/the-worst-morale-boosting-gesture-ive-experienced/) — This might be the single dumbest morale booster I've ever heard (and I've seen some really bad ones).

[When Your Job Is Your Identity, Professional Failure Hurts More](https://hbr.org/2019/06/how-we-confuse-our-roles-with-our-self) — "...when you take professional kicks personally you compromise your own ability to recover and see the bigger picture..." Perhaps you are the one doing the kicking and your organization is reacting accordingly.

[DevOps’ish Telegram](https://t.me/devopsish) — Join the 300+ DevOps, Kubernetes, SRE, and other technology professionals discussing real-world problems, breaking technology events and outages, and the occasional Spotify playlist.

## Process

[TCP SACK PANIC](https://access.redhat.com/security/vulnerabilities/tcpsack) — Originally discovered by [Netflix](https://github.com/Netflix/security-bulletins/blob/master/advisories/third-party/2019-001.md), these TCP selective acknowledgment vulnerabilities impact Linux and FreeBSD kernels. "Multiple TCP-based remote denial of service vulnerabilities" (four CVEs in total) basically creating a new pings of death. Woohoo! Y'all exhausted from these mega vulns yet? [LWN](https://lwn.net/SubscriberLink/791409/d00105536e597c1c/) has a great overvieew.

[DevOps'ish Summer 2019 Survey](https://devopsi.sh/survey) is coming to a close. It's *vital* feedback that I will use to pivot, fork, or modify the newsletter, if needed. Therefore it's important that everyone [**takes the survey today**](https://devopsi.sh/survey)!

[Forget monoliths vs. microservices. Cognitive load is what matters](https://techbeacon.com/app-dev-testing/forget-monoliths-vs-microservices-cognitive-load-what-matters) — "Excessive cognitive load works against effective team ownership and supportability of software. Here's why, and how to approach the problem." FINALLY! 🤯🤯🤯

[3 Strategies for implementing a microservices architecture](https://about.gitlab.com/2019/06/17/strategies-microservices-architecture/) — Three ways to attack that weighty monolith.

[Explaining CVE-2019-10164 + PostgreSQL Security ~~Best~~ Practices](https://info.crunchydata.com/blog/explaining-cve-2019-10164-with-postgresql-security-best-practices) — I love how security issues in the PostgreSQL community are solved emphatically by upgrading to the latest version. I know that's not as cut and dry as it sounds but, think about that recommendation for MySQL or Oracle 😱🙀😱🙀

[Understanding Public Key Infrastructure and X.509 Certificates](https://www.linuxjournal.com/content/understanding-public-key-infrastructure-and-x509-certificates) — PKI basics are vital for almost everyone reading this. This will get you some CLI time with openssl.

[IBM to win unconditional EU okay for $34 billion Red Hat deal](https://www.reuters.com/article/us-red-hat-m-a-ibm-eu/ibm-to-win-unconditional-eu-okay-for-34-billion-red-hat-deal-sources-idUSKCN1TK28K) — Coupled with reports that [this is the last quarter Red Hat will be reporting earnings](https://www.theregister.co.uk/2019/06/21/red_hat_last_results_before_ibm_acquisition/), it would appear the end of an independent Red Hat is here. I'm optimistic for what the future brings! Note: both of these articles have been added to the [DevOps’ish IBM Red Hat Acquisition Index
](https://devopsish.com/ibm-red-hat-acquisition-index/).

[VMware Eyeing Containers](https://seekingalpha.com/article/4270923-vmware-eyeing-containers) — A Wall Street take on the goings on of VMware which is starting to look like a great destination if the future of Kubernetes is something you want to work on.

[Cisco and IBM Cloud Announce Hybrid Cloud Partnership](https://blogs.cisco.com/datacenter/cisco-and-ibm-cloud-announce-hybrid-cloud-partnership) — Enterprise vendors; holding hands and skipping through the hybrid clouds together.

[What is DevOps](https://devopsish.com/what-is-devops/) — "DevOps is the professional practice of frequent, continued, and iterative improvements through measurable changes, the goal of which is to become a high-velocity organization thus improving business outcomes."

## Tools

[Future of CRDs: Structural Schemas](https://kubernetes.io/blog/2019/06/20/crd-structural-schema/) — "The core of a structural schema is an OpenAPI v3 schema made out of `properties`, `items`, `additionalProperties`, `type`, `nullable`, `title`, and `descriptions`. In addition, all types must be non-empty, and in each sub-schema only one of `properties`, `additionalProperties` or `items` may be used."

[The future of how Ansible content is handled](https://youtu.be/CGjDarrqBjg) — Collections are coming and the Ansible team needs your feedback. Kick the tires and let us know!

[Kubernetes 1.15: Extensibility and Continuous Improvement](https://kubernetes.io/blog/2019/06/19/kubernetes-1-15-release-announcement/) — "25 enhancements: 2 moving to stable, 13 in beta, and 10 in alpha"

[All You Need to Know About Red Hat Universal Base Image](http://crunchtools.com/all-you-need-to-know-about-red-hat-universal-base-image/) — If my social media is any indication, there appears to be significant interest in Universal Base Image (UBI). I'm biased (Red Hat employee; see [disclaimer](https://devopsish.com/disclaimer/)) but, I think it's pretty slick. I made a very lean and secure [container for Alibaba Cloud's ossutil](https://quay.io/repository/chrisshort/ossutil) to use in CI in no time. The trick is using [microdnf](https://access.redhat.com/solutions/3144031) (free login required).

[Follow logs from multiple K8s Pods in a Deployment, ReplicaSet, etc.](https://www.jeffgeerling.com/blog/2019/follow-logs-multiple-k8s-pods-deployment-replicaset-etc)

[Automating Highly Available Kubernetes and external ETCD cluster setup with terraform and kubeadm on AWS](https://ifritltd.com/2019/06/16/automating-highly-available-kubernetes-cluster-and-external-etcd-setup-with-terraform-and-kubeadm-on-aws/) — "[A] set of terraform and bash scripts which should be sufficient enough for you to literally just run terraform plan/apply to get your HA etcd and k8s cluster up and running without any hassle..." Bold statement.

[Faster Docker builds with pipenv, poetry, or pip-tools](https://pythonspeed.com/articles/pipenv-docker/) — If you're building python containers, these are some great suggestions.

[New C5 instance sizes and bare metal instances](https://aws.amazon.com/blogs/aws/now-available-new-c5-instance-sizes-and-bare-metal-instances/) — More compute for the compute gods.

[Introducing time.cloudflare.com](https://blog.cloudflare.com/secure-time/) — I'm a huge NTP nerd. The fact Cloudflare is offering this service is good. Quality time sources on the internet are drying up. The fact they took the extra step to provide a secure NTP service is good too. But, I would still use the [NTP Pool Project](https://www.ntppool.org/).

[bashfulrobot/bashfulrobot-ansible](https://github.com/bashfulrobot/bashfulrobot-ansible) — Ansible Repo that utilizes an ansible-pull command to configure my workstations

[containerenv/containerenv](https://github.com/containerenv/containerenv) — shippable linux user environments

## DevOps'ish Tweet of the Week

{{< tweet 1140779753286201344 >}}
