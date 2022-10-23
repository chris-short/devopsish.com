+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-05-08T07:00:00Z
description = ["We did some good in the world, Kubernetes 1.24, Netflix downward slide, critical F5 vuln, RFC 9116, Kubernetes Goat, Pulumi YAML, and more"]
draft = false
slug = "266"
tags = ["Kubernetes", "Argo", "YAML", "Pulumi", "Pulumi YAML", "DevOps'ish", "team", "SLOs", "Amazon EKS", "Elastic Kubernetes Service", "Netflix", "GitOps", "AWS", "environment", "Site Reliability Engineer", "SRE", "Kubernetes Goat", "practices", "vulnerability", "security", "enhancements", "cloud", "DevOps", "asshole test", "dockershim", "pod", "progressive delivery", "cloud native", "Lucy"]
title = "DevOps'ish 266: We did some good in the world, Kubernetes 1.24, Netflix downward slide, critical F5 vuln, RFC 9116, Kubernetes Goat, Pulumi YAML, and more"
+++

Thank you to everyone that donated to my sister's [Walk for Wishes](https://secure2.wish.org/site/TR/;jsessionid=00000000.app202a?px=7065476&pg=personal&fr_id=4096&NONCE_TOKEN=CAB8CE6B5E882373D563373C7D9D2285) for Make-A-Wish® Michigan this week. We kinda crushed it for Lucy. Here's how the tally adds up as of 7 PM Saturday:

[![2022 Walk For Wishes - Michigan(Make-A-Wish® Michigan)](https://shortcdn.com/devopsish/Make-a-Wish-Michigan-Walk-for-Wishes-2022.webp)](https://secure2.wish.org/site/TR?fr_id=4096&pg=entry)

First, we helped push the event over its goal ($366K raised, $360K goal; pat yourselves on the back, that's huge). Second, our "We Love Lucy" team raised the **third** highest amount of money ($16.5K) for the event. Third, your donations made my sister the **#4 individual fundraiser**. Fourth, the "We Love Lucy" team raised so much that we eclipsed all but the two major event sponsors as far as company's participating.

**None of this would've been possible without you, the reader.** DevOps'ish alone donated $1,000 to spur others to donate and donate you did. I'm so thankful.

It felt really good to get that hug yesterday morning. She sends a very special thank you to every single one of you who donated this week. My personal thanks as well. You didn't have to make an impact on our family, but you did. For that, I am forever grateful.

There is hope for you yet, Internet... Maybe.

**Side Note**: I joined Mastodon in earnest this week. Follow me here: <https://mastodon.technology/@ChrisShort>.  
I'm finding it quite nice. I enjoy it as a non-distracting interface to Twitter with the [Mastodon Twitter Crossposter](https://crossposter.masto.donte.com.br/).

Also, [Kubernetes News](https://kubenews.net) is out there to help you discover more Kubernetes newsletters. Submit a PR if I'm missing a one, please.

## DevOps'ish is brought to you by...

DevOps'ish is brought to you by your friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).

***"Stop Letting Complexity Slow You Down"***

[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easier to understand and troubleshoot complex relationships within your distributed services. *Solve problems faster*. *Ship reliable and performant features*. *SPONSORED*

## Events

[**SLOConf - Service Level Objective Conference**](https://www.sloconf.com/)

MAY 9-12, 2022

Site Reliability Engineering is one of the hottest areas as companies look to build reliable systems and their online presence. As companies rush to adopt Site Reliability Engineering principles, Service Level Objectives (SLOs) are the most important place to begin. SLOs are the combination of cultural philosophies, practices, and tools.

The SRE community needs a place to gather and focus on SLOs in depth. This virtual conference will cover topics at all levels, from introduction to SLOs to the practical application of SLOs. This conference is a community event made and led by Site Reliability Engineers and influencers who care about reliability and becoming more customer centric by adopting, measuring and optimizing SLOs.

[**AWS Containers Days**](https://awscontainerdayseurope.splashthat.com/)  

MAY 10TH-13TH, AND 17TH  
8:00AM-10:00AM PT | 17:00-19:00 CEST

Join us (me on Thursday) for AWS Containers Days @ KubeCon + CloudNativeCon Europe 2022! In the days leading up to Kubecon + CloudNativeCon we'll be spending the week talking about how you can deploy, manage, and scale containerized applications using Kubernetes on AWS. These sessions, led by our AWS Kubernetes team and guest speakers, will contain technical deep dives, product demos, and best practices.

In the closing keynote on May 17th, Nate Taber, Principal Product Manager, AWS will share the Amazon EKS Vision and Roadmap and throughout the session you will hear directly from our customers.

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/)

MAY 17, 2022

Designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**DevOpsDays Ukraine: DevOps in Crisis**](https://devopsdays.com.ua/)

May 17-18th, 2022, Virtual

DevOpsDays Ukraine is a part of the global DevOpsDays family.  
This May we are running a virtual charity event to discuss DevOps during crisis, incident, and business continuity management and collect donations to support Ukrainians.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Preparing to Tell Your Boss “I Quit”](https://hbr.org/2022/05/preparing-to-tell-your-boss-i-quit)  
Nihar Chhaya and Dorie Clark, Harvard Business Review  
The worst part of dealing with leaving Red Hat was explaining to folks that I was burned out and that's why I was leaving. Then the counter offer process was like, just don't, don't bother. Well, why? Maybe if I read this sooner, I could have handled this a little better.

[IBM's asshole test](https://johnpublic.mataroa.blog/blog/the-asshole-test/)  
johnpublic  
"At the end of the day the group is split into two rooms, my room is given the good news and I go on to join the grad scheme. Six months later I am shadowing a colleague who is running the 'group test'. I asked him if he'd ever seen a group complete the test? 'Oh, it's not about that, this is an asshole test. You see who turns into an asshole under pressure and they don't make it to the next round'."

[Netflix cuts marketing staff after losing subscribers](https://www.latimes.com/entertainment-arts/business/story/2022-04-28/netflix-cuts-marketing-staff-after-losing-subscribers)  
Wendy Lee, Los Angeles Times

Three issues at hand here:

1. Continuously constant growth is impossible
1. Competition in the streaming market is VERY new, multi-pronged, and almost overwhelming (especially to consumers)
1. All that custom-built software we admire Netflix for has an enormous cost associated with it in engineers and operations. [Brendan Gregg](https://www.brendangregg.com/blog/2022-05-02/brendan-at-intel.html), one of Netflix's best known engineers, is long gone, for example.

This perfect storm of events has brought us to where we are today. The future of Netflix depends upon its ability to compete. Until recently, they've been the top or sometimes ONLY dogs in the mass media streaming market. Adjusting from market leader to in the mix of a bevy of services households subscribe to is going to be hard. It's almost shameful Netflix didn't see this coming and do more to adjust sooner (maybe they did but, I didn't see it).

[Salesforce expands Silenced No More Act protections in U.S.](https://www.protocol.com/bulletins/salesforce-silenced-no-more-act)  
Issie Lapowsky, Protocol  
"Salesforce is extending Silenced No More Act protections to all U.S. employees, following shareholder pressure."

[All of the bases in DNA and RNA have now been found in meteorites](https://www.sciencenews.org/article/all-of-the-bases-in-dna-and-rna-have-now-been-found-in-meteorites)  
Liz Kruesi, Science News  
"The discovery adds to evidence that suggests life's precursors came from space." You truly are star dust.

## Process

[CISA urges F5 users to address 'critical' vulnerability in BIG-IP software](https://therecord.media/f5-big-ip-alert-cisa/)  
Jonathan Greig, The Record by Recorded Future  
"The company also [released an advisory](https://support.f5.com/csp/article/K55879220) about the bug, CVE-2022-1388, which could allow an attacker with access through the BIG-IP system's management port to execute arbitrary system commands, create or delete files, or disable services. The vulnerability — which F5 said it discovered internally — has a CVSS score of 9.8 out of 10, ranking it as 'critical.'"

[RFC 9116: A File Format to Aid in Security Vulnerability Disclosure](https://www.rfc-editor.org/rfc/rfc9116)  
E. Foudil and Y. Shafranovich, Nightwatch Cybersecurity  
Internet Engineering Task Force (IETF)  
"When security vulnerabilities are discovered by researchers, proper reporting channels are often lacking. As a result, vulnerabilities may be left unreported. This document defines a machine-parsable format ("security.txt") to help organizations describe their vulnerability disclosure practices to make it easier for researchers to report vulnerabilities."

[Botnet that hid for 18 months boasted some of the coolest tradecraft ever](https://arstechnica.com/information-technology/2022/05/how-hackers-used-smarts-and-a-novel-iot-botnet-to-plunder-email-for-months/)  
Dan Goodin, Ars Technica  
"The group, which security firm Mandiant is calling UNC3524, has spent the past 18 months burrowing into victims' networks with unusual stealth. In cases where the group is ejected, it wastes no time reinfecting the victim environment and picking up where things left off. There are many keys to its stealth."

[US Court Orders Every ISP in the United States to Block Illegal Streaming Sites](https://torrentfreak.com/us-court-orders-every-isp-in-the-united-states-to-block-illegal-streaming-sites-220502/)  
Andy Maxwell, TorrentFreak  
"More than a decade after U.S. lawmakers scuttled the controversial SOPA legislation that would've required ISPs to block pirate sites, a US court has demonstrated that the ability to block sites has been available all along. Injunctions issued in response to lawsuits against three pirate streaming services require every ISP in the United States to prevent subscribers from accessing them."

[1Password for SSH Changed The Way I Work](https://blog.1password.com/1password-ssh-changed-how-i-work/)  
K.J. Valencik, 1Password  
This is a potentially a game changer in the way folks work. I need to dive a little deeper into getting this working but, I suspect 1Password is also working to make this even easier than it is today.

[Competition Intensifying in SSD Market](http://www.businesskorea.co.kr/news/articleView.html?idxno=91760)  
Michael Herh, Business Korea  
In a market of high chip prices, we could see the cost of NAND production plummet which would bring some welcome relief in a market full of damn near maxed out pricing of products.

## Tools

### Kubernetes 1.24

[Dockershim deprecated with Kubernetes 1.24](https://www.theregister.com/2022/05/04/kubernetes_docker_cncf/)  
Tobias Mann, The Register  
I've done so much `dockershim` removal work I'm ready to throw a party now that it's gone. Like, this was an enormous amount of work for Kubernetes docs folks. We ended up creating a team of extremely dedicated technical writers and Kubernetes experts so that we could make sure every use case in the docs was either still good or revamped entirely. Congrats to the release team for getting this release out the door in what was one of the harder releases I've seen to date (due to multiple reasons, some beyond the projects' control completely).

[Kubernetes 1.24: Stargazer](https://kubernetes.io/blog/2022/05/03/kubernetes-1-24-release-announcement/)  
[Kubernetes 1.24 Release Team](https://github.com/kubernetes/sig-release/blob/master/releases/release-1.24/release-team.md)  
This release consists of 46 enhancements: fourteen enhancements have graduated to stable, fifteen enhancements are moving to beta, and thirteen enhancements are entering alpha. Also, two features have been deprecated, and two features have been removed.

This release saw two major changes:

1. Dockershim Removal
1. Beta APIs are off by Default

[Kubernetes 1.24: Volume Expansion Now A Stable Feature](https://kubernetes.io/blog/2022/05/05/volume-expansion-ga/)  
Hemant Kumar, Red Hat  
This feature allows Kubernetes users to simply edit their `PersistentVolumeClaim` objects and specify new size in PVC Spec and Kubernetes will automatically expand the volume using storage backend and also expand the underlying file system in-use by the Pod without requiring any downtime at all if possible.

[Storage Capacity Tracking reaches GA in Kubernetes 1.24](https://kubernetes.io/blog/2022/05/06/storage-capacity-ga/)  
Patrick Ohly, Intel  
"As explained in more detail in the [previous blog post about this feature](https://kubernetes.io/blog/2021/04/14/local-storage-features-go-beta/), storage capacity tracking allows a CSI driver to publish information about remaining capacity. The kube-scheduler then uses that information to pick suitable nodes for a Pod when that Pod has volumes that still need to be provisioned."

### EKS users

If you're using EKS and you're not subscribed to [EKS News](https://eks.news), you're truly missing out. It's designed to keep Amazon EKS customers up to date with EKS and the Kubernetes ecosystem: [**Subscribe today**](https://eks.news/#subscribe)

[Kubernetes Goat](https://madhuakula.com/kubernetes-goat/)  
Madhu Akula  
"Kubernetes Goat is a "Vulnerable by Design" cluster environment to learn and practice Kubernetes security using an interactive hands-on playground 🚀"

[Contributor Cheatsheet](https://www.kubernetes.dev/docs/contributor-cheatsheet/#squashing-commits)  
Kubernetes Contributors  
This cheat sheet isn't new but the [Kubernetes Contributors site](https://www.kubernetes.dev/) (maintained by SIG-Contributor Experience) is full of helpful nuggets of info like this.

[Continuous Load Testing](https://slack.engineering/continuous-load-testing/)  
Shreya Ramesh and Melissa Khuat, Slack  
"We've shared our journey of [building load testing tools](https://slack.engineering/load-testing-with-koi-pond/) at Slack as our usage has scaled. Once we had a solid set of load testing tools (most notably, Koi Pond), we focused on our next goal: building a culture of performance at Slack. Rather than approach performance reactively, we wanted it to be ingrained in the development process and easy to consider."

[Progressive Delivery with Argo Rollouts : Blue-Green Deployment](https://www.infracloud.io/blogs/progressive-delivery-argo-rollouts-blue-green-deployment/)  
Ninad Desai, Infracloud  
"In this post, we discussed what progressive delivery is all about and its characteristics. We also learned about ArgoRollouts custom controller and how it can help to achieve the blue-green deployment, which is ultimately a form of progressive delivery."

[Don't Write Your Own Kubernetes YAML Generator](https://matduggan.com/tips-for-making-kubernetes-yaml-less-annoying/)  
Mathew Duggan  
Matthew points out the many ways YOU don't have to write all that YAML yourself that already exist.

[Pulumi YAML: A Simple Declarative Interface for Pulumi](https://www.pulumi.com/blog/pulumi-yaml/)  
Luke Hoban, Pulumi  
"Our goal though has always been to offer the broadest range of programming language options to empower every cloud builder so that they could benefit from the best of Pulumi's Infrastructure as Code platform. Today, we are excited to launch [Pulumi YAML](https://www.pulumi.com/docs/intro/languages/yaml/), a simple YAML-based interface to the entirety of the Pulumi Infrastructure as Code platform."

[Introducing arcticDB: A database for Observability](https://www.polarsignals.com/blog/posts/2022/05/04/introducing-arcticdb/)  
Frederic Branczyk, Polar Signals  
"Continuous profiling needed a columnar database, so we built it."

[Breakthrough Discovery of the One-Way Superconductor – Thought To Be Impossible](https://scitechdaily.com/breakthrough-discovery-of-the-one-way-superconductor-thought-to-be-impossible/)  
Mazhar Ali, Delft University of Technology  
"The fact that Ali's group was able to make superconducting one-directional – which is required for computing – is remarkable: it's like inventing a special type of ice that has zero friction one way but insurmountable friction the other."

[Adaptive-Sync Certification Could Kill FreeSync, G-Sync Branding](https://www.tomshardware.com/news/vesa-adaptive-sync-certification)  
Brandon Hill, Tom's Hardware  
"We may see G-Sync and FreeSync branding completely supplanted by Adaptive-Sync Display and MediaSync Display logos." All hail non-proprietary standards.

[anderseknert/awesome-opa](https://github.com/anderseknert/awesome-opa)  
A curated list of OPA related tools, frameworks and articles

[NimbleArchitect/kubectl-ice](https://github.com/NimbleArchitect/kubectl-ice)  
view running kubernetes information about multi-container pods and sidecars

[kris-nova/boopkit](https://github.com/kris-nova/boopkit)  
Linux eBPF backdoor over TCP. Spawn reverse shells, RCE, on prior privileged access. Less Honkin, More Tonkin.

[sustainable-computing-io/kepler](https://github.com/sustainable-computing-io/kepler)  
Kepler (Kubernetes-based Efficient Power Level Exporter) uses eBPF to probe energy related system stats and exports as Prometheus metrics

## DevOps'ish Social Media of the Week

Tweets, toots, reddit posts, etc. will now fill this section.  I want to open it to all social media platforms. If you see something, send it my way, please.

[![Yo... This GitOps to Modern Practices Map from @williamcaban is amazing! #GitOps #IaC #DevOps (Chris Short @ChrisShort on Twitter)](https://shortcdn.com/devopsish/266-devopsish-tweet-of-the-week.webp)](https://twitter.com/ChrisShort/status/1522666771588788226)

The original graphic is spot on and available [here](https://shortcdn.com/devopsish/gitops-to-moden-practices.png): ![GitOps to Modern Practices](https://shortcdn.com/devopsish/gitops-to-moden-practices.png)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/266/notes.md) to see what didn't make it to the newsletter but are still worth your time.

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
