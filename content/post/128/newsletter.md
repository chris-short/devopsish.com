+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2019"]
date = 2019-05-19T07:00:00Z
description = "128: MDS, Mined Minds, Red Hat & IBM, Kubernetes Operating Systems, ReactiveOps Polaris, ~~Best~~ Practices, and More"
draft = false
slug = "128"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "container", "security", "linux", "infrastructure", "git", "GitHub", "MDS", "Mined Minds", "best practice", "practices", "vuln", "vulnerabilities", "open source contributor"]
title = "128: MDS, Mined Minds, Red Hat & IBM, Kubernetes Operating Systems, ReactiveOps Polaris, ~~Best~~ Practices, and More"

+++

No. Contrary to what everyone I've talked to this week thinks, I'm not going to KubeCon Barcelona. I don't think I was really planning on it at the beginning of the year. I believe it was added to my schedule right before my Shingles diagnosis. Let me tell you, Shingles is bullshit. I've been battling a flare-up of the nerve pain today and it's gnarly af. I was going to discuss the use of the term "best practice" this week but, I need to go get some rest. Instead, lend me your thoughts. [The Tweet of the Week this week](https://twitter.com/Kate_Catlin/status/1128403226678587393) provides the thinking behind modifying or eliminating the use of the phrase "best practices". [I asked for clarification from the greater community this week](https://twitter.com/ChrisShort/status/1129342806307278848) and the conversation was insightful. Check it all out and let me know what you think (Twitter, email, Telegram, etc.)!

Thank you to everyone that helped pushed the newsletter to over 3,000 subscribers!

## DevOps'ish Last Week's Top Five

1. [10 Mistakes You Should Avoid During Your One on One Meetings](https://www.fellow.app/blog/2019/10-mistakes-you-should-avoid-during-one-on-one-meetings/)
1. [Do These 5 Emotionally Intelligent Things Within 5 Minutes Of Meeting](https://www.fastcompany.com/40441365/do-these-5-emotionally-intelligent-things-within-5-minutes-of-meeting-someone)
1. [DevOps is Dead with James Turnbull](https://www.realworlddevops.com/episodes/devops-is-dead-with-james-turnbull)
1. [How to Stop Worrying About What Other People Think of You](https://hbr.org/2019/05/how-to-stop-worrying-about-what-other-people-think-of-you)
1. [Oops, We Forgot to Build a Managed Kubernetes Service!](https://www.packet.com/blog/oops-we-forgot-to-build-a-managed-kubernetes-service/)

## People

[**Your career needs more than a search bar.**](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email4) — Get matched with tech opportunities from leading companies, rising enterprises, and startups. Cut time, effort and stress with a 5-minute application to reach 1000s of companies—connecting you directly to tech roles that fit your profile. [Join for free today](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email4)! *SPONSORED*

[AnsibleFest 2019 Call for Proposals](https://ansiblefest2019.eventpoint.com/cfp/?utm_source=devopsish) — Are you adding value to your organization using Ansible? Perhaps you have automated your way out of a sticky situation before with Ansible? Have you scaled an organizations automation efforts with Ansible Tower? [Submit a proposal to AnsibleFest 2019!](https://ansiblefest2019.eventpoint.com/cfp/?utm_source=devopsish)

[Taking a systems-focused approach to diversity and inclusion](https://opensource.com/open-organization/19/5/inclusivity-solution-innovation) — Let's be real: Diversity and inclusion is a business issue. If the problem is a struggle to innovate, then the solution is greater diversity and inclusion.

[The Price of the Hallway Track](https://hynek.me/articles/hallway-track/) — The hallway track is when I make actual connections with people. The talks I go to are because I want to engage with the speaker on the topic or the discussion in general. But, if you go to conferences and ignore all talks, you're doing the speakers a very real disservice.

[They Were Promised Coding Jobs in Appalachia. Now They Say It Was a Fraud.](https://www.nytimes.com/2019/05/12/us/mined-minds-west-virginia-coding.html) — "Mined Minds came into West Virginia espousing a certain dogma, fostered in the world of start-ups and TED Talks. Students found an erratic operation." "Out of the 10 or so people who made it to the final weeks of Ms. Frame's [Mined Minds] class in Beckley, only one formally graduated. He is now delivering takeout."

[Saying goodbye to Microsoft](https://medium.com/@alicjaes/saying-goodbye-to-microsoft-bb5db8662656) — "What I gained, lost & learned while working for Microsoft."

[Facebook has struggled to recruit since Cambridge Analytica scandal](https://www.cnbc.com/2019/05/16/facebook-has-struggled-to-recruit-since-cambridge-analytica-scandal.html) — Today's workforce is more inundated with  information than ever. It's also a workforce that isn't here to punch a clock. We want to make an actual impact and fully utilize our skills to do it. Facebook's bad behavior leading to recruiting problems should surprise absolutely no one.

[The struggles of an open source maintainer](http://antirez.com/news/129) — "That said, I was able to work for many years doing things I really loved, that gave me friends, recognition, money, so I don't want to say it was a bad deal. Yet I totally understand people struggling a lot to stay afloat once their projects start to be popular. This blog post is dedicated to them."

[DevOps salaries: 10 statistics to see](https://enterprisersproject.com/article/2019/5/devops-jobs-salaries-10-statistics) — Are DevOps salaries leveling off? How much does experience and certification matter? Check out the data, job seekers and hiring managers.

[What Is It Like To Manage a 65,000-Person Slack Channel?](https://www.cronicle.press/2019/05/16/what-is-it-like-to-manage-a-65000-person-slack-channel/) — My buddy, Jeff Sica sat down with Cronicle Press to talk about what it's like managing the massive Kubernetes Slack.

## Process

[**2019 State of Multicloud**](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) — A Report on the Underlying Dynamics Fueling Multicloud Strategies. [Download Today!](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) *SPONSORED*

[cpu.fail](https://cpu.fail) — Microarchitectural Data Sampling (MDS) and a group of vulnerabilities individually known as ZombieLoad, RIDL, and Fallout have been disclosed publicly. [Every processor Intel made since 2011](https://www.tomsguide.com/us/zombieload-attack-intel-what-to-do,news-30082.html) is impacted by these vulnerabilities. In my opinion, Arm is the future now. I wouldn't be surprised if organizations accelerated plans investing in Arm or switching architectures to Arm. Arm is by no means flawless but, Intel is not going to easily overcome this. Why? [Google Cloud is advising GKE customers](https://support.google.com/faqs/answer/9330250) they, "must disable hyper-threading." Truly mitigating these vulnerabilities means you will have half the CPUs you thought you did. Fellow Red Hatter Jon Masters has [an extended MDS explanation video](https://youtu.be/Xn-wY6Ir1hw) and [MDS blog post](https://www.redhat.com/en/blog/understanding-mds-vulnerability-what-it-why-it-works-and-how-mitigate-it) explaining more.

{{< youtube Oeb-O4yKK2c >}}

[A 'smoking good' deal? Red Hat could prove a $34 billion bargain for IBM](https://siliconangle.com/2019/05/13/smoking-good-deal-10-trillion-impact-red-hat-34-billion-bargain-rhsummit-guestoftheweek/) — "Red Hat stands as an open-source success story, validated when IBM Corp. announced last October plans to acquire the firm for $34 billion. And, when asked if IBM's decision will prove a good deal for everyone involved, Red Hat's chief executive officer had no doubts."

[Where IBM and Red Hat go from here](https://www.zdnet.com/article/where-ibm-and-red-hat-go-from-here/) — "Sometime in the next few months, IBM's acquisition of Red Hat will go through. Here's what will happen to Red Hat afterwards." 

The previous two links have been added to the [DevOps'ish IBM Red Hat Acquisition Index](https://devopsish.com/ibm-red-hat-acquisition-index/).

[CVE-2019-11815](https://access.redhat.com/security/cve/cve-2019-11815) — After the MDS vulns, what's a kernel vuln amongst friends?

[A Cisco Router Bug Has Massive Global Implications](https://www.wired.com/story/cisco-router-bug-secure-boot-trust-anchor/) — "According to its security bulletin, all fixes are still months away from release, and there are currently no workarounds. When the patches do arrive, Cisco says, they will 'require an on-premise reprogramming,' meaning the fixes can't be pushed remotely, because they are so fundamental."

Remember the ransom attacks that hit Git repos (see [DevOps'ish 126](https://devopsish.com/126/))? [Atlassian Bitbucket, GitHub, and GitLab](https://github.blog/2019-05-14-git-ransom-campaign-incident-report/) released, "a joint blog post in a coordinated effort to help educate and inform users of the three platforms on secure ~~best~~ practices relating to the recent Git ransomware incident."

[VMware to acquire Bitnami](https://blog.bitnami.com/2019/05/vmware-to-acquire-bitnami.html) — What VMware is doing in the Kubernetes space is starting to look intriguing.

## Tools

[Kubernetes and the future of cloud native: We chat with Kelsey Hightower](https://about.gitlab.com/2019/05/13/kubernetes-chat-with-kelsey-hightower/) — "GitLab CEO Sid Sijbrandij sat down with Kelsey Hightower to talk about a variety of topics like cloud native, Kubernetes, infrastructure challenges, understanding new technology, and much more. One topic that came up again and again was fundamentals."

[**How companies adopt and apply cloud native infrastructure--from O'Reilly**](https://www.oreilly.com/pub/cpc/224549) — Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud. *SPONSORED*

[Kubernetes, The Open and Scalable Approach to ML Pipelines](https://towardsdatascience.com/kubernetes-the-open-and-scalable-approach-to-ml-pipelines-1e972a965f0d) — Before I left Bankrate, we were trying to get our data scientists to embrace containers and a CI/CD pipeline (we built a rudimentary one for their high CPU and I/O needs). This article helps data nerds embrace a pipeline much like that of software engineering and DevOps teams.

[Improve your Dockerfile, ~~best~~ practices](https://dev.to/azure/improve-your-dockerfile-best-practices-5ll)

[KubeOne: A New Lifecycle Management Tool for HA Kubernetes Clusters](https://www.loodse.com/blog/2019-05-13-kubeone/) — "KubeOne takes care of installing, configuring, upgrading and maintaining Highly-Available (HA) Kubernetes clusters. It works out-of-the-box on any cloud provider, as well as in on-prem and bare-metal environments."

[Kubernetes Operating Systems](https://kubedex.com/kubernetes-operating-systems/) — "Well take a look at some of the features of Container Linux (formerly CoreOS), RancherOS, Talos, k3os and LinuxKit and discuss if there is any benefit to using these versus installing Kubernetes on a standard Linux distribution."

[Build a quick CI system using Red Hat Ansible Tower with GitHub Actions](https://www.ansible.com/blog/build-a-quick-ci-system-using-red-hat-ansible-tower-with-github-actions) — My co-worker, [Sean Cavanaugh](https://www.ansible.com/blog/author/sean-cavanaugh), got access to GitHub Actions a little early and found immediate use for it.

[Comparison of Kubernetes Top Ingress Controllers](https://caylent.com/kubernetes-top-ingress-controllers/) — "Choosing the right ingress controller becomes important when you start considering traffic and load coming to your Kubernetes cluster."

[It's Time To Pay Attention To Intel's Clear Linux OS Project](https://www.forbes.com/sites/jasonevangelho/2019/05/13/its-time-to-pay-attention-to-intels-clear-linux-os-project/#425c335e5c49) — I would but my CPU is half the processor it used to be. Too soon?

[Cluster API to the Rescue: An Easier Way to Manage Your Kubernetes Clusters](https://containerjournal.com/2019/05/13/cluster-api-to-the-rescue-an-easier-way-to-manage-your-kubernetes-clusters/)

[Introducing Terraform Cloud Remote State Management](https://www.hashicorp.com/blog/introducing-terraform-cloud-remote-state-management) — Finally, a viable solution to Terraform state files that doesn't involve me burning incense and making ritualistic sacrifices trying not to get an [S3 Bucket Negligence Award](https://www.lastweekinaws.com/?utm_source=devopsish&utm_medium=email&utm_campaign=128).

[Red Hat Enterprise Linux 8 developer cheat sheet](https://developers.redhat.com/blog/2019/05/07/red-hat-enterprise-linux-8-developer-cheat-sheet/)

[containership/konstellate](https://github.com/containership/konstellate) — Free and Open Source GUI to Visualize Kubernetes Applications

[Aracki/gobernetes](https://github.com/Aracki/gobernetes) — Collection of miscellaneous Kubernetes resources

[reactiveops/polaris](https://github.com/reactiveops/polaris) — Validation of best practices in your Kubernetes clusters

[kontena/akrobateo](https://github.com/kontena/akrobateo) — Akrobateo is a simple Kubernetes operator to expose in-cluster LoadBalancer services as node hostPorts using DaemonSets

[muesli/service-tools](https://github.com/muesli/service-tools) — A growing collection of convenient little tools to work with systemd services

[nunomaduro/phpinsights](https://github.com/nunomaduro/phpinsights) — 💡Instant PHP quality checks from your console

## DevOps'ish Tweet of the Week

{{< tweet 1128403226678587393 >}}

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com).
