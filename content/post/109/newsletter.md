+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2019-01-06T07:00:00Z
description = "Get Caught Up, Kubernetes in High Demand, Two Monorepos Walk into a Bar, Hashicorp at Home, and More"
draft = false
slug = "109"
tags = ["devops", "kubernetes", "open source", "cloud", "newsletter", "cloud native", "security", "gocd", "software", "engineering", "aws", "golang", "linux", "openebs", "monorepos", "container", "infosec"]
title = "109: Get Caught Up, Kubernetes in High Demand, Two Monorepos Walk into a Bar, Hashicorp at Home, and More"

+++

What a weird week. It started on Wednesday first of all. It felt like half of everyone was still on vacation. It was quiet but, it was busy. There was a lot of great content this week too surprisingly. The time at the end of one year, the beginning of another is awesome. So many folks are taking time to write down their thoughts on everything from note taking during programming to monorepos to Kubernetes to infosec. It feels kinda magical out in the world of tech right now. Hopefully, we can turn this positive energy into something awesome this year.

In case you have been in a cave, here are the top stories you might have missed the past two weeks:

1. [DevOps engineer interviews: Ask these questions](https://enterprisersproject.com/article/2018/12/hiring-devops-engineer-ask-these-questions)
2. [7 CI/CD tools for sysadmins](https://opensource.com/article/18/12/cicd-tools-sysadmins)
3. [Highest Paying Tech Companies of 2018 by Levels.fyi](https://www.levels.fyi/2018/) — Note: I think this list is utter rubbish. Give it a look and you'll see why.
4. [How to become an AWS expert](https://aws.amazon.com/blogs/aws/how-to-become-an-aws-expert/)
5. [The truth about impostor syndrome](https://dev.to/kelly/the-truth-about-impostor-syndrome-165h)
6. [2018 Learnings, 2019 Expectations](https://chrisshort.net/2018-learnings-2019-expectations/)
7. [10 books for your DevOps reading wishlist](https://opensource.com/article/18/12/devops-wishlist)
8. [Moving on From Red Hat by Christian Posta](http://blog.christianposta.com/moving-on-from-red-hat/)
9. [The biggest technology failures of 2018](https://www.technologyreview.com/s/612646/the-biggest-technology-failures-of-2018/)
10. [YAML Has Won](https://medium.com/@robmuh/yaml-has-won-ba5dae37e740)

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*

[**Real World DevOps**](https://www.realworlddevops.com/)  
The Real World DevOps Podcast talks about the messy, behind-the-scenes realities of running systems. We'll be talking with practitioners from across the industry, both from traditional enterprises to modern cloud-native startups. *SPONSORED*


## People

[18 people in tech every programmer and software engineer needs to follow in 2019](https://hub.packtpub.com/18-people-in-tech-every-programmer-and-software-engineer-needs-to-follow-in-2019/) — I'm honored (and flattered) to be on this list of wonderfully brilliant minds.

[How Millennials Became The Burnout Generation](https://www.buzzfeednews.com/article/annehelenpetersen/millennials-burnout-generation-debt-work) — I'm stretched pretty thin on literally everything.

[Kubernetes Dominates in IT Job Searches](https://www.sdxcentral.com/articles/news/kubernetes-dominates-in-it-job-searches/2019/01/) — #1 skill is [Kubernetes](https://kubernetes.io), #4 is [golang](https://golang.org/), #5 is [Ansible](https://www.ansible.com/)

[One year in San Francisco as a Software Engineer](https://evertpot.com/a-look-back-at-sf/) — Yikes...

[On leaving Chef](https://www.juliandunn.net/2019/01/04/on-leaving-chef/) — Jeez... What's going on at Chef. I'm not sure who I even know over there anymore.

[Why It Is Difficult to Hire for DevOps?](https://thenewstack.io/why-it-is-difficult-to-hire-for-devops/) — DevOps is hard and hiring for it is even harder. But, orgs can help themselves here too.

## Process

A pair of Kubernetes security issues this week. #shoutout to the Kubernetes Product Security Team:

1. [Security Impact of Kubernetes API server external IP address proxying](https://discuss.kubernetes.io/t/security-impact-of-kubernetes-api-server-external-ip-address-proxying/4072) — "It was reported to us by Michael Schubert of Kinvolk that the Kubernetes API server can be used as a HTTP proxy to not only cluster internal but also external target IP addresses."
2. [Security release of dashboard v1.10.1 - CVE-2018-18264](https://discuss.kubernetes.io/t/security-release-of-dashboard-v1-10-1-cve-2018-18264/4069) — "A security issue was discovered in kubernetes dashboard versions v1.10.0 or older... The TLS secrets for a Kubernetes Dashboard can be obtained by visiting https://[DASHBOARD_HOST]/api/v1/secret/kube-system/kubernetes-dashboard-certs."

[How our kubernetes journey saved us $1 million dollars](https://hackernoon.com/how-our-kubernetes-journey-saved-us-1-million-dollars-cede771f1f2b)

[Open Source Business Models Considered Harmful](https://medium.com/@johnmark/open-source-business-models-considered-harmful-2e697256b1e3) — If your value is the software you open sourced, don't be surprised when you can't make money on it. Provide value, open source what you can, and work from there.

[How To Shutter Your Startup: Best Practices for Corporate Dissolution](https://www.techstars.com/content/accelerators/shutter-startup-best-practices-corporate-dissolution/) — Don't screw up the end. Deprecate gracefully.

[When you code, write down everything](https://swizec.com/blog/write-down-everything/swizec/8851) — When I was doing Ops and InfoSec work daily I wrote down everything. My notes were absurd and I was highly organized. It allowed me to drop complex project work and go put out the latest security incident and pick right back up where I left off.

[Effective Mental Models for Code and Systems](https://medium.com/@copyconstruct/effective-mental-models-for-code-and-systems-7c55918f1b3e)

[On Thinking About Infrastructure as Code](https://blog.scottlowe.org/2018/12/31/on-thinking-about-infrastructure-as-code/)

[Three Acquisitions In 2018 To Impact 2019's Tech Landscape](https://www.forbes.com/sites/cognitiveworld/2018/12/30/three-acquisitions-in-2018-to-impact-2019s-tech-landscape/#49ab698d353e) — Cloud, AI, and IoT are all getting touched.

[Monorepos: Please don't!](https://medium.com/@mattklein123/monorepos-please-dont-e9a279be011b) — Don't hurt 'em, Matt.

[Monorepo: please do!](https://medium.com/@adamhjk/monorepo-please-do-3657e08a4b70) — You tell 'em, Jacob.

[Security trends to pay attention to in 2019 and beyond](https://cloud.google.com/blog/products/identity-security/security-trends-to-pay-attention-to-in-2019-and-beyond) — Very insightful. If you have any thoughts that aren't covered here please share them.

[lorin/resilience-engineering](https://github.com/lorin/resilience-engineering) — Resilience Engineering Notes

## Tools

[Linux Technology for the New Year: eBPF](https://thenewstack.io/linux-technology-for-the-new-year-ebpf/) — Some are saying 2019 is the year of eBPF.

[NSA Releasing the GHIDRA Reverse Engineering Tool at RSAConference](https://www.bleepingcomputer.com/news/security/nsa-releasing-the-ghidra-reverse-engineering-tool-at-rsaconference/) — "GHIDRA is a reverse engineering framework that is available for Windows, macOS, and Linux that the NSA is unveiling at the conference."

[io_submit: The epoll alternative you've never heard about](https://blog.cloudflare.com/io_submit-the-epoll-alternative-youve-never-heard-about/)

[The State of Kubernetes 2019](https://blog.giantswarm.io/the-state-of-kubernetes-2019/) — I respect the folks over at Giant Swarm (a lot) and you should too.

[Kubernetes In a Nutshell](https://enqueuezero.com/kubernetes-in-a-nutshell.html) — I love the format of this. It's almost like you could make index cards if you want to with it. When I update my [Getting Started with Kubernetes](https://chrisshort.net/kubernetes-getting-started/) article, this is definitely going in it.

[Kicking the Tires on OpenEBS for Cluster Storage](https://vadosware.io/post/kicking-the-tires-on-openebs-for-cluster-storage/) — If you have thought about trying out OpenEBS give this a once over. I should point out, the [OpenEBS](https://www.openebs.io/) folks are great.

[5 things you didn't know about Istio](https://opensource.com/article/18/12/you-didnt-know-about-istio) — Learn how Istio helps address microservices challenges, in this talk from All Things Open 2018.

[Hashicorp at Home](https://www.mockingbirdconsulting.co.uk/blog/2019-01-05-hashicorp-at-home/) — Applying the Hashicorp stack in your home; pretty cool idea.

[Database migrations in Golang](https://lanre.wtf/blog/2019/01/02/database-migration-golang/) — Moving your state with Go 101

[windmilleng/tilt](https://github.com/windmilleng/tilt) — Local Kubernetes development with no stress

[dbcli/litecli](https://github.com/dbcli/litecli) — CLI for SQLite Databases with auto-completion and syntax highlighting

[project-koku/koku](https://github.com/project-koku/koku) — An open source solution for cost management of cloud and hybrid cloud environments

[Ne0nd0g/merlin](https://github.com/Ne0nd0g/merlin) — Merlin is a cross-platform post-exploitation HTTP/2 Command & Control server and agent written in golang.

[Best Linux Distro 2019, for desktop](https://haydenjames.io/best-linux-distro/)

## DevOps'ish Tweet of the Week

{{< tweet 1081418769849700352 >}}

Notes from this week's issue can be found [here](./notes/).
