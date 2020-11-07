+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-09-06T07:00:00Z
description = "1x engineers, Future of Ops Jobs, DevOps for non-IT biz leaders, Kubernetes, Litmus, and more"
draft = false
slug = "182"
tags = ["Kubernetes", "DevOps", "Cloud", "cloud native", "security", "Business", "Engineers", "open source", "Engineering", "cluster", "AWS"]
title = "DevOps'ish 182"

+++

Welcome!

Your environment makes up so much of who you are in real life. I often wonder if your work environment reflects how your infrastructure will look. If you’re okay with satisfying that 80% use case, does your infra look like AWS with hundreds of services some of which are quite stable and others not so much? Or if you the perfect be the enemy of the good and be like a lot of companies and spend a lot of time spinning their wheels waiting for the right thing to happen. I’ve seen countless examples of this.

But, what about when your environment is resilient, scalable, and cloud-enabled. What about when psychological safety is achieved AND the idea of cost per minute to the business during an outage is established? We see so many examples of bad ways and maybe a few good ways of building. I would love to see more use cases around the things that are possible when the business value is known down to the individual and the organization is a high-performer. Highlighting more of the good, I hope, would engrain “the why” behind the need for change way more than features and individual capabilities.

Or... Is it what we all know deep down inside? It’s a little bit of a shit show *somewhere*.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_182). Learn more about their new open source project [Terrscan](https://www.accurics.com/blog/products/terrascan-opa-policy-as-code/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_182) which has recently been refactored Open Policy Agent.

## People

[1x Engineer](https://1x.engineer/)  
1x engineers are the best engineers. [10x Engineers aren't real](http://10x.engineer/).

[OpenSSL Is Looking for a Full Time Administrator and Manager](https://www.openssl.org/blog/blog/2020/09/05/OpenSSL.ProjectAdminRole/)  
I hope they intend to pay accordingly.

[The Future of Ops Jobs](https://acloudguru.com/blog/engineering/the-future-of-ops-jobs)  
"Infrastructure, ops, devops, systems engineering, sysadmin, infraops, SRE, platform engineering. As long as I’ve been doing computers, these terms have been effectively synonymous. If I wanted to tell someone what my job was, I could throw out any one of them and expect to be understood."

[Managing Remotely: 6 Ways to Support Engineers](https://devops.com/managing-remotely-6-ways-to-support-engineers/)  
A quick hitter on some useful management tools given the current situation.

[Nintendo Plans Upgraded Switch Console and Major Games for 2021](https://www.bloomberg.com/news/articles/2020-08-25/nintendo-plans-upgraded-switch-console-and-major-games-for-2021)  
You know I was thinking of getting a Nintendo Switch, then I saw this.

## Process

[RIP: NetApp Advanced Technology Group shuffles off this mortal coil](https://www.theregister.com/2020/08/28/rip_netapp_advanced_technology_group/)  
"The 'ideas factory' falls victim to latest round of corporate penny-pinching"

[Webinar | Empower DevOps and Security Teams with Kubernetes-native Security](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh)  
Startups and enterprises alike are embracing containerization and Kubernetes, but security struggles to move at the pace of DevOps, bogged down by tools and processes not suited for cloud-native technology. [Register for this webinar](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh) where cloud-native security experts from AWS, Informatica, and StackRox will discuss how to apply Kubernetes-native security and controls to protect containers and Kubernetes without slowing down application development and rollout. *Date: Sep 03, 2020 | 10 AM PDT* *SPONSORED*

[Is cloud security too easy to screw up?](https://acloudguru.com/blog/engineering/is-cloud-security-too-easy-to-screw-up)  
Forrest Brazeal sits down with Troy Hunt.

[Quick Guide to DevOps for the Non-IT Business Leader](https://itrevolution.com/quick-guide-to-devops-for-the-non-it-business-leader/)  
"Adapted from War and Peace and IT: Business Leadership, Technology, and Success in the Digital Age by Mark Schwartz."

## Tools

[Using sysctls in a Kubernetes Cluster](https://kubernetes.io/docs/tasks/administer-cluster/sysctl-cluster/)  
This document describes how to configure and use kernel parameters within a Kubernetes cluster using the sysctl interface.

[7 versatile Vim commands that are easy to memorize](https://initialcommit.com/blog/7-versatile-vim-commands)  
I wouldn't say these are "easy" to memorize because I suck at memorization but, this is a good reference. And I'm really good and finding my bookmarks.

[Crunchy HA PostgreSQL keeps critical applications running](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week3&utm_campaign=CrunchyHA)  
Take the hassle out of building HA PostgreSQL environments with one-click setup. Combine with Ansible Tower clustering to keep data secure accessible for your critical components. Learn more or [get started today](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week3&utm_campaign=CrunchyHA)! *SPONSORED*

[A Sysadmin’s Guide to Markdown Language](https://adamtheautomator.com/a-sysadmins-guide-to-markdown-language/)  
I love Markdown. It's what I use to write all my web sites content these days. It's a feature set *just* complete enough to say, "If I need more than this I might need to rethink things." Although, I wouldn't say any of my web sites are pretty though.

[The Kubernetes Handbook](https://www.freecodecamp.org/news/the-kubernetes-handbook/)  
Yet another Kubernetes Handbook. YMMV.

[How a Kubernetes Pod Gets an IP Address](https://ronaknathani.com/blog/2020/08/how-a-kubernetes-pod-gets-an-ip-address/)  
"I wanted to write this post to share what I have learned about various networking components and how they are stitched together in a Kubernetes cluster for every pod to receive an IP address."

[5 Linux network troubleshooting commands](https://www.redhat.com/sysadmin/five-network-commands)  
"Linux provides many command-line tools to help sysadmins manage, configure, and troubleshoot network settings." Minus nslookup this is a helpful list.

[Public Sector on Air: SPARTA OCP 4.5 Air-Gapped AWS Gov Cloud](https://www.twitch.tv/videos/727360211?filter=archives&sort=time)  
"Sparta was created to solve the problem of delivering the Red Hat OpenShift Kubernetes Platform, along with an extensible middleware and application portfolio, within restricted deployment environments (e.g. behind an air gap)."

[Understanding DNS-anatomy of a BIND zone file](https://arstechnica.com/gadgets/2020/08/understanding-dns-anatomy-of-a-bind-zone-file/)  
"Need a clear, thorough guide to understanding how DNS records work? We got you."

[litmuschaos/litmus](https://github.com/litmuschaos/litmus)  
Litmus helps Kubernetes SREs and developers practice chaos engineering in a Kubernetes native way

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week from @annamv10](/images/182-devopsish-tweet-of-the-week.png)](https://twitter.com/annamv10/status/1298032639396294657)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/182/notes/) to see what didn't make it to the newsletter.

{{< amazon >}}
