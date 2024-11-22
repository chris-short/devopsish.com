+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-04-03
description = ["TSMC says demand slowing, yet another BGP mishap, Pulumiverse, Spring4Shell, etcd corruption issue, kaar, kubectl-detector-for-docker-socket, and more"]
draft = false
slug = "263"
tags = ["Kubernetes", "etcd data corruption issue", "SLOs", "GitOps", "etcd", "Detector for Docker Socket", "supply chain", "attacks", "hackers", "MFA", "reliability", "BGP", "Linux", "kaar", "kubectl", "community", "pulumiverse", "TSMC", "cluster", "cloud", "process", "backups", "Amazon"]
title = "DevOps'ish 263: TSMC says demand slowing, yet another BGP mishap, Pulumiverse, Spring4Shell, etcd data corruption issue, kaar, kubectl-detector-for-docker-socket, and more"
+++

This week's newsletter features some potentially good news about the chip supply chain, a BGP mishap involving Twitter, and a tale of foreign bribes at Microsoft according to a whistleblower. Also, How Go Mitigates Supply Chain Attacks, Lapsus$ and SolarWinds hackers both use the same old trick to bypass MFA, and a bunch of attacks and zero days. Rounding out the newsletter the Tools section brings us a new Detector for Docker Socket for Kubernetes from Justin Garrison, Kris Nóva's new shiny `kaar` ("tar for Kubernetes" Nóva called it), and the ultimate question of the year so far; Is Your Cluster Ready for v1.24?

DevOps'ish is brought to you by your friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easier to understand and troubleshoot complex relationships within your distributed services. *Solve problems faster*. *Ship reliable and performant features*. *SPONSORED*

## Events

[**SLOConf - Service Level Objective Conference**](https://www.sloconf.com/)  
MAY 9-12, 2022  

Site Reliability Engineering is one of the hottest areas as companies look to build reliable systems and their online presence. As companies rush to adopt Site Reliability Engineering principles, Service Level Objectives (SLOs) are the most important place to begin. SLOs are the combination of cultural philosophies, practices, and tools.

The SRE community needs a place to gather and focus on SLOs in depth. This virtual conference will cover topics at all levels, from introduction to SLOs to the practical application of SLOs. This conference is a community event made and led by Site Reliability Engineers and influencers who care about reliability and becoming more customer centric by adopting, measuring and optimizing SLOs.

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish)  
MAY 17, 2022  
Designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)  
SEPTEMBER 19 – 21, 2022  
ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[U.S. and European Leaders Reach Deal on Trans-Atlantic Data Privacy](https://www.nytimes.com/2022/03/25/business/us-europe-data-privacy.html)  
"American and European Union leaders said on Friday that they had reached an 'agreement in principle' to assure that it is legal to transfer personal data across the Atlantic, after a previous pact was struck down when a court found it did not do enough to shield Europeans from American surveillance programs." Finally a step towards a solution to this problem.

[TSMC says demand for smartphones, PCs starting to slow](https://asia.nikkei.com/Spotlight/Supply-Chain/TSMC-says-demand-for-smartphones-PCs-starting-to-slow)  
Good news for stretched supply chains. "Consumer electronics demand is showing signs of slowing amid geopolitical uncertainties and COVID-related lockdowns in China, the chairman of Taiwan Semiconductor Manufacturing Co. said on Wednesday." There I saved you a click.

[Four Russian Government Employees Charged in Two Historical Hacking Campaigns Targeting Critical Infrastructure Worldwide](https://www.justice.gov/opa/pr/four-russian-government-employees-charged-two-historical-hacking-campaigns-targeting-critical)
The US Justice Department with these press releases and their headlines lately. It's like 💥 😵! It's like a comic book in a title. Game over.

[Apple and Meta shared data with hackers pretending to be law enforcement officials](https://www.theverge.com/2022/3/30/23003600/apple-meta-shared-data-hackers-pretending-law-enforcement-officials?scrolla=5eb6d68b7fedc32c19ef33b4)  
Well that's really bad. And you best believe I could pull this off too.

[Some Twitter traffic briefly funneled through Russian ISP, thanks to BGP mishap](https://arstechnica.com/information-technology/2022/03/absence-of-malice-russian-isps-hijacking-of-twitter-ips-appears-to-be-a-goof/)  
The internet still runs on Border Gateway Protocol all these years later.

[Microsoft is tied to hundreds of millions of dollars in foreign bribes, whistleblower alleges](https://www.theverge.com/2022/3/25/22995144/microsoft-foreign-corrupt-practices-bribery-whistleblower-contracting)  
This is a very serious infraction in the United States. If a case becomes of this, I can't imagine what the fine would be.

## Process

[How Go Mitigates Supply Chain Attacks](https://go.dev/blog/supply-chain)  
"Despite any process or technical measure, every dependency is unavoidably a trust relationship. However, the Go tooling and design help mitigate risk at various stages."

[Apple emergency update fixes zero-days used to hack iPhones, Macs](https://www.bleepingcomputer.com/news/security/apple-emergency-update-fixes-zero-days-used-to-hack-iphones-macs/)  
Them: "Apple is aware of a report that this issue may have been actively exploited."
Me: Oh shit...
Moral of the story: Patch your kit!

[Lapsus$ and SolarWinds hackers both use the same old trick to bypass MFA](https://arstechnica.com/information-technology/2022/03/lapsus-and-solar-winds-hackers-both-use-the-same-old-trick-to-bypass-mfa/)  
Not all MFA are the best MFAs. I have [FIDO2 compliant](https://fidoalliance.org/fido2/) keys for all my important accounts. You should too. If you don't, I'd recommend trying to work with your IT department to get a FIDO2 compliant MFA system prioritized. I don't think [all these companies](https://fidoalliance.org/members/) are wrong.

[Spring confirms ‘Spring4Shell’ zero-day, releases patched update](https://therecord.media/spring-confirms-spring4shell-zero-day-releases-patched-update/)  
[CVE-2022-22965](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-22965) was leaked ahead of CVE publication making it a zero-day. Apparently, that means your CVE can get a "cool" name these days. Anyways... Patch your stuff.

[Muhstik Botnet Targeting Redis Servers Using Recently Disclosed Vulnerability](https://thehackernews.com/2022/03/muhstik-botnet-targeting-redis-servers.html)  
There are so many botnets and CVEs being targeted by them this year. The biggest thing is your systems shouldn't be directly internet accessible. You've got to continuously scan your systems for open holes.

[Hackers Increasingly Using 'Browser-in-the-Browser' Technique in Ukraine Related Attacks](https://thehackernews.com/2022/03/hackers-increasingly-using-browser-in.html)  
One of those instances where teaching sand to do math might be regrettable.

## Tools

[Is Your Cluster Ready for v1.24?](https://kubernetes.io/blog/2022/03/31/ready-for-dockershim-removal/)  
"Way back in December of 2020, Kubernetes announced the deprecation of Dockershim." It was a digital tornado of FUD and misunderstanding. But, the community has steeled itself and has gotten out in front of every major deprecation since. This article from Kat Cosgrove can help you get out of front of the Kubernetes 1.24 release.

[Kubernetes Release Cadence Survey 2022](https://www.surveymonkey.com/r/k8s-cadence-2022)  
"WHO SHOULD FILL OUT THIS SURVEY: Kubernetes project contributors. Users of Kubernetes. Staff of companies that use, resell, and/or host Kubernetes."

[Release v3.5.2 · etcd-io/etcd](https://github.com/etcd-io/etcd/releases/tag/v3.5.2)  
"This release is no longer recommended for production. Please use v3.4 minor until v3.5.3 is released. Read more in <https://github.com/etcd-io/etcd/tree/main/CHANGELOG>." The problem being a [data corruption issue](https://github.com/etcd-io/etcd/tree/main/CHANGELOG#v35-data-corruption-issue), "Running etcd v3.5.2, v3.5.1 and v3.5.0 under high load can cause a data corruption issue. If etcd process is killed, occasionally some committed transactions are not reflected on all the members." What's kinda not haha funny but bad funny is that I'm kicking the tires on Kubespray this weekend and it's hanging on the etcd step. I think it's a networking issue though.

[S3 Is Not a Backup](https://www.lastweekinaws.com/blog/s3-is-not-a-backup/)  
My friend Corey Quinn wrote something salient about a thing he knows a lot about. My cloud-based backups are the last in a chain of backups that I've put in place. I care about data like my music library from 1992-2000. All the photos I've ever taken and family and friends have shared with us. You know, hard drives that could be snatched up on the way out for a fire. In the worst case scenario, I can rest assured the layers of backups I have work. I highly recommend restore testing scenarios. Use your imagination and get creative. Eliminate every layer and see where there are holes in your strategies.

[Talos: Linux Designed For Kubernetes](https://youtu.be/iEFb2Zg4xUg)  
Viktor Farcic kicks the tires on Talos Linux. "Talos Linux is Linux designed for Kubernetes – secure, immutable, and minimal."

[Amazon EBS CSI driver is now generally available in Amazon EKS add-ons](https://aws.amazon.com/blogs/containers/amazon-ebs-csi-driver-is-now-generally-available-in-amazon-eks-add-ons/)  
EBS for your CSI as an Amazon EKS add-ons.

[Introducing the Pulumiverse](https://www.pulumi.com/blog/2022-03-30-introducing-pulumiverse/)  
Finally! A 'verse I can at the very least appreciate.

[Introducing Caddy-SSH](https://www.caffeinatedwonders.com/2022/03/28/new-ssh-server/)  
You have my attention!

[Charm](https://charm.sh/)  
I found this and showed it off to a fellow GitOps co-chair this week and we both agreed, this is pretty dang cool.

[aws-containers/kubectl-detector-for-docker-socket](https://github.com/aws-containers/kubectl-detector-for-docker-socket)  
"A Kubectl plugin that can detect if any of your workloads or manifest files are mounting the docker.sock volume." To go along with the 1.24 release. Because you shouldn't turn on that cluster-wide policy preventing it until you know you're not actually using it. Trust but verify before you take down prod and sometimes verifying a couple ways doesn't hurt.

[kris-nova/kaar](https://github.com/kris-nova/kaar)  
"Kubernetes Application Archive: Bundle up a Kubernetes application 📦 into a single static OCI compliant archive."

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/263/notes.md) to see what didn't make it to the newsletter but are still worth your time.
