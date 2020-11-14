+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-04-21T07:00:00Z
description = "124: Kubernetes Tools, Google Anthos and Cloud Run, Fenrir for Serverless, Five Abstractions Make an Inception, Ports on Linux, and More"
draft = false
slug = "124"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "container", "security", "system", "Google", "Cloud Run", "Anthos", "linux", "abstractions", "inception"]
title = "124: Kubernetes Tools, Google Anthos and Cloud Run, Fenrir for Serverless, Five Abstractions Make an Inception, Ports on Linux, and More"

+++

I hope you had a wonderful week and are looking forward to the week ahead. I have been heads down working on Red Hat Summit work, upcoming releases, and trying to properly define DevOps this week. But, it has left me little time to really think about solving new problems. What do you do when you have complex problems to solve but only short bursts of time to work on them in? It's a balancing act for sure. Good luck this week in your endeavors!

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*

[**170+ live online training courses opened for March and April**](https://www.oreilly.com/pub/cpc/213941)  
Get hands-on training in machine learning, AWS, Kubernetes, Python, Java, and many other topics *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [How to Get Into SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre/)
1. [A beginner's guide to building DevOps pipelines with open source tools](https://opensource.com/article/19/4/devops-pipeline)
1. [Lessons from 300k+ Lines of Infrastructure Code](https://www.infoq.com/presentations/infrastructure-cookbook)
1. [Google's remote work employee survey](https://www.fastcompany.com/90329043/exclusive-google-asked-100000-employees-about-remote-work-this-is-what-they-learned)
1. [Hannah Montana Linux](http://hannahmontana.sourceforge.net/) 👀🤣🤣🤣

## People

[Want an awesome job, working in a great team, with a tremendous leader?](https://social.icims.com/viewjob/pt1553611085158445da) — If you're in Europe and want to work on the Ansible team with other fellow Red Hatters. This is the job for you (maybe)!

[Sonatype, Senior Technical Ambassador, DevOps Community](https://jobs.lever.co/sonatype/eb80a45e-dd73-4cc2-beae-58f2d4b937b2) — My friends at Sonatype are looking for an awesome DevOps person to talk about their great products and practices.

[The 5 communication problems that destroy company morale](https://qz.com/work/1587170/the-five-types-of-communication-problems-that-destroy-company-morale/) — "Missing Empathy" and "Communication that triggers anxiety" are two big ones for me personally. Come to folks with problems but show that you're interested in learning more about the context. Also, if you send four separate DMs, one after another triggering four separate notifications on Slack, you're part of the problem.

[The introvert's guide to Red Hat Summit](https://www.redhat.com/en/blog/introverts-guide-red-hat-summit) — If you're like me, going to Red Hat Summit but, have to ninja off to be a normal version of yourself for a little bit every once in a while, this guide is for you. Yes, I'll be at Red Hat Summit in Boston. Let me know if you'll be attending.

[What Happened When The DEA Demanded Passwords From LastPass](https://www.forbes.com/sites/thomasbrewster/2019/04/10/what-happened-when-the-dea-demanded-passwords-from-lastpass/#190345307ebe) — LastPass couldn't give the DEA the passwords because of their encryption implementation. But, there is always metadata and metadata can sometimes paint an even better picture than the data itself. An interesting tale of how you can do everything right and still screw your customers (or yourself, depending on the point of view).

[How much does a DevOps engineer make?](https://enterprisersproject.com/article/2019/4/devops-engineer-salary) — Putting debates around the term DevOps engineer aside, let's explore data points on salaries for this hot job title

[Alibaba founder Jack Ma says companies forcing staff to work overtime are ‘foolish'](https://www.scmp.com/news/china/society/article/3006127/alibaba-founder-jack-ma-says-companies-forcing-staff-work) — "He also calls enforced 996 schedule – working 9am to 9pm, six days a week – ‘inhumane' and ‘unsustainable'"

## Process

[**Accelerate: State of DevOps 2019 Survey**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5):  Nicole Forsgren, PhD is conducting the State of DevOps 2019 Survey. Your input is incredibly important. On several occasions, I have referenced [the 2018 report](https://cloudplatformonline.com/2018-state-of-devops.html) since its release for real-world work that impacts real numbers. Nicole's group also wrote, [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2), which I cannot recommend enough either.

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[Homeland Security warns of security flaws in enterprise VPN apps](https://techcrunch.com/2019/04/12/enterprise-security-flaws/) — A hole in OpenVPN means there's a hole in your backdoor, eek! Seriously, upgrade ASAP. I stepped back from OpenVPN a couple of years ago for a few reasons. If you need an alternative I'd recommend [WireGuard](https://www.wireguard.com/) (for personal use there is also [Outline](https://getoutline.org/)).

[Big Companies Thought Insurance Covered a Cyberattack. They May Be Wrong.](https://www.nytimes.com/2019/04/15/technology/cyberinsurance-notpetya-attack.html) — "Zurich Insurance said it would not be sending a reimbursement check. It cited a common, but rarely used, clause in insurance contracts: the 'war exclusion,' which protects insurers from being saddled with costs related to damage from war. Mondelez was deemed collateral damage in a cyberwar."

[The top two most popular Docker base images each have over 500 vulnerabilities](https://snyk.io/blog/the-top-two-most-popular-docker-base-images-each-have-over-500-vulnerabilities/) — "The last scan as of March 11, 2019 shows that the official Node.js image ships with 567 vulnerable system libraries. The remaining nine images ship with at least 31 publicly known vulnerabilities each." Remember, containers make it easy to ship software vulnerabilities too.

[How Monzo built a bank with open infrastructure](https://www.computerworlduk.com/open-source/how-monzo-built-bank-with-open-infrastructure-3695090/) — Miles Bryant, platform engineer at Monzo, shared some observations from the microservices-based challenger bank at the recent Open Infrastructure Day event in London.

[The Problem with SSH Agent Forwarding](https://defn.io/2019/04/12/ssh-forwarding/) — If you use SSH in an even remotely complicated way, please read this article. `ProxyJump` is your best friend in a lot of different situations.

[Sometimes Kanban is Better Than Scrum - Yes, I Said It](https://www.mountaingoatsoftware.com/blog/when-kanban-is-the-better-choice) — "In some situations, other approaches are called for. Usually, it will still be some variant of an agile approach. Most commonly that means Kanban."

## Tools

[Introducing Fenrir: How Coinbase is Scaling Serverless Applications](https://blog.coinbase.com/introducing-fenrir-how-coinbase-is-scaling-serverless-applications-9ba6e3a74761) — "Fenrir is our AWS SAM deployer; at its core is a reimplementation of the `sam deploy` command as an AWS Step Function, so it's a serverless serverless (serverless²) deployer." 🤯🤯🤯

[Linkerd 2.3 introduces Zero-Trust Networking for Kubernetes](https://hub.packtpub.com/linkerd-2-3-introduces-zero-trust-networking-for-kubernetes/) — "In this release, the mTLS is out of experimental to a fully supported feature. Along with several important security primitives, the important update in Linkerd 2.3 is that it turns authenticated, confidential communication between meshed services on by default."

[The Future of Serverless is... Functionless?](https://www.stackery.io/blog/future-of-serverless/) — "With [AWS] [AppSync](https://aws.amazon.com/appsync/), DynamoDB Tables, SQL Databases (via Aurora Serverless), Lambda Functions, and ElasticSearch domains have all been elevated as [first-class "Data Sources" for GraphQL resolvers](https://docs.aws.amazon.com/appsync/latest/devguide/tutorials.html)."

[Monitoring container vitality and availability with Podman](https://developers.redhat.com/blog/2019/04/18/monitoring-container-vitality-and-availability-with-podman/) — Healthchecks in Podman are now a thing.

[How Google Cloud Run Combines Serverless with Containers](https://thenewstack.io/how-google-cloud-run-combines-serverless-with-containers/) — Cloud Run is a Google-made layer on top of knative on top of Kubernetes on top of compute (which on GCP is probably a container in a container of containers). We might have finally hit enough abstractions to start measuring them by "inceptions" (five abstractions is one inception). Thoughts?

[CRI-O + Container Linux: How to Install](https://edenmal.moe/post/2018/CRI-O-Container-Linux-How-to-Install/) — This post is showing how you can install and run CRI-O for Kubernetes on Container Linux

[How do I check if a port is in use on Linux?](https://www.cyberciti.biz/faq/how-do-i-check-if-a-port-is-in-use-on-linux/) — The thing that shocked me the most about this article was the number of people that told me they had never heard of [`ss`](https://linux.die.net/man/8/ss) before. I've known about it since before RHEL 7 was released (2014). I discovered it in [this handy set of cheat sheets from Red Hat](https://access.redhat.com/articles/1189123) that shows you the difference in common commands between RHEL 5, 6, 7, and now RHEL 8. Full disclosure: I still use `sudo netstat -tupan` a lot more than I should (that command along with `perl -pie` solidifed my first position as a full-time Linux SysAdmin).

[Announcing Packer v.1.4.0](https://www.hashicorp.com/blog/announcing-packer-v-1-4-0) — Some interesting features for Packer users including a bevy of Windows features and some new provisioners (including Vagrant and InSpec).

[Kubernetes External Secrets](https://godaddy.github.io/2019/04/16/kubernetes-external-secrets/) — "This blog post describes a generalized approach and implementation for supporting secret management systems, like AWS Secrets Manager, in Kubernetes. We call this system Kubernetes External Secrets and we have [open sourced](https://github.com/godaddy/kubernetes-external-secrets) our initial implementation."

[Go is on a trajectory to become the next enterprise programming language](https://hackernoon.com/go-is-on-a-trajectory-to-become-the-next-enterprise-programming-language-3b75d70544e) — This article makes a lot of good cases for Go. It makes a case Go being a de facto Java replacement in enterprise applications.

[Everything You Want To Know About Anthos - Google's Hybrid And Multi-Cloud Platform](https://www.forbes.com/sites/janakirammsv/2019/04/14/everything-you-want-to-know-about-anthos-googles-hybrid-and-multi-cloud-platform/#30ed8c965b66) — Speaking of abstractions, there's now a thing call Google Anthos. One shocking thing I learned, "It's important to note that GKE On-prem runs as a virtual appliance on top of VMware vSphere 6.5." That's interesting for sure.

[The Fargate Illusion](https://leebriggs.co.uk/blog/2019/04/13/the-fargate-illusion.html) — AWS Fargate is a great idea but, maybe not such a great implementation. GCP has the one container per instance feature that makes it a little bit easier to "run my damn container."

[Is Helm used just for templating?](https://learnk8s.io/helm-templating-kubernetes-yaml/) — TL;DR: Helm is used for templating, sharing charts and managing releases. If you're looking just for templating, you should check out [kustomize](https://github.com/kubernetes-sigs/kustomize).

[Introducing kube-iptables-tailer: Better Networking Visibility in Kubernetes Clusters](https://kubernetes.io/blog/2019/04/19/introducing-kube-iptables-tailer/) — "We needed a mechanism to seamlessly deliver alerts about those iptables packet drops based on their network policies to help app owners quickly diagnose the corresponding issues."

[OpenSSH 8.0 released](https://lwn.net/Articles/786236/) — "OpenSSH 8.0 has been released with a bunch of new features and some bug fixes, including one for a security problem"

[chaosblade-io/chaosblade](https://github.com/chaosblade-io/chaosblade) - An easy to use and powerful chaos engineering experiment toolkit.（一款简单易用、功能强大的混沌实验注入工具）(from Alibaba)

[Alikhll/golang-developer-roadmap](https://github.com/Alikhll/golang-developer-roadmap) — Roadmap to becoming a Go developer in 2019

[jarun/ddgr](https://github.com/jarun/ddgr) — DuckDuckGo from the terminal

[nayafia/lemonade-stand](https://github.com/nayafia/lemonade-stand) — A handy guide to financial support for open source

## DevOps'ish Tweet of the Week

{{< tweet 1118816110571339778 >}}

Notes from this week's issue can be found [here](./notes/).
