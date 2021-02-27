+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-08-16T07:00:00Z
description = "DevOps'ish 179"
draft = false
slug = "179"
tags = ["DevOps", "security", "cloud native", "Kubernetes", "io TLD", "GitOps", "Docker", "namespace", "Linux", "UPS", "performance", "DevSecOps", "AWS", "scale", "CI/CD", "operations", "community", "development", "open source", "hierarchical namespace", "1Password", "Microsoft", "service mesh", "kustomize"]
title = "DevOps'ish 179"

+++

Welcome!

This week I move a bunch of web sites [off the .io](https://twitter.com/ChrisShort/status/1292971206480723968) top-level domain. [Kubernetes News](https://kubenews.net/) is one such site. Why should you move off your .io domains. Well, newly minted AWS Developer Advocated, [Justin Garrison beat me to it](https://twitter.com/rothgar/status/1292971873169367040?s=20) ([buy his book](https://amzn.to/3g2ohQU)). But regardless, there's enough reason and evidence out there, that we as an industry should no longer condone the use and of a top level domain for the abuse of a people. Here is a list of the articles referenced in the discussion:

* [No to .io, yes to .xyz!](https://yarmo.eu/post/no-io-yes-xyz)
* [How the IO Top Level Domain is mired with outages and injustice](https://www.thewebmaster.com/hosting/2016/feb/27/io-tld-top-level-domain/)
* [The dark side of .io: How the U.K. is making web domain profits from a shady Cold War land deal](https://gigaom.com/2014/06/30/the-dark-side-of-io-how-the-u-k-is-making-web-domain-profits-from-a-shady-cold-war-land-deal/)

It's time for change. It's time for consciousness. It's time for our consciences to get the better of us.

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_179).

## People

[Security Jobs With a Future -- And Ones on the Way Out](https://www.darkreading.com/edge/theedge/security-jobs-with-a-future----and-ones-on-the-way-out/b/d-id/1338652)  
SOC Analyst, Security Engineer, Hardware Engineer, Data Center Security Manager are all out. DevSecOps Security Engineer (redundant, I know) or (better) DevSecOps Engineer is the new hotness.

[The Workforce Is About to Change Dramatically](https://www.theatlantic.com/ideas/archive/2020/08/just-small-shift-remote-work-could-change-everything/614980/)  
The reduction in business travel (which is charged and a premium and systems are gamed) will hurt tourism across the board (folks aren't earning miles and points to use for family trips anymore; let alone are they risking their families' lives right now). Free agency is going to start. You'll start seeing your folks taking on side jobs to earn a little more cash. American politics might even change as big, high dollar real estate is vacated for more space in well connected but less densely populated areas. One theory of mine is that the change between the 2020 and 2030 US Census will be dramatically different.

[Some thoughts on #CloudNative and humility...](https://mobile.twitter.com/fintanr/status/1290666168286683137)  
"But when you dismiss the current reality for people within these orgs as being in purgatory it just comes across as dismissive. Have some empathy. Everyone wants an easier job, no one wants to be described as inferior for a situation that is generally beyond their control."

## Process

[Misconfigured cloud storage services are commonplace in 93% of deployments](https://www.helpnetsecurity.com/2020/08/06/misconfigured-cloud-storage-services/)  
"Cloud breaches will likely increase in velocity and scale, and highlights steps that can be taken to mitigate them, according to Accurics."

[Backup and DR in the Age of GitOps](https://containerjournal.com/topics/container-security/backup-and-dr-in-the-age-of-gitops/)  
"Interoperability with GitOps, IaC, and CI/CD systems is a must as organizations increasingly are deploying these systems to improve IT operations and enhance business success. Even with these powerful primitives available, the need for backup and disaster recovery is as important as ever, and deploying a backup solution will be critical for safety and scale. However, it is imperative that such a backup system be truly cloud-native that can integrate into GitOps and CI/CD workflows. Legacy VM-based systems will simply not work in the new cloud-native world we live in today!"

[China is now blocking all encrypted HTTPS traffic that uses TLS 1.3 and ESNI](https://www.zdnet.com/article/china-is-now-blocking-all-encrypted-https-traffic-using-tls-1-3-and-esni/)  
The fact we've caught up to and potentially surpassed Chinese mass surveillance capabilities is a great and scary thing.

[US voting hardware maker's shock discovery: Security improves when you actually work with the community](https://www.theregister.com/2020/08/06/black_hat_ess_bugs/)  
More minds are better than fewer ones. More diverse perspective is better than limited perspective. I see a trend here...

## Tools

[Webinar | Empower DevOps and Security Teams with Kubernetes-native Security](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh)  
Startups and enterprises alike are embracing containerization and Kubernetes, but security struggles to move at the pace of DevOps, bogged down by tools and processes not suited for cloud-native technology. [Register for this webinar](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh) where cloud-native security experts from AWS, Informatica, and StackRox will discuss how to apply Kubernetes-native security and controls to protect containers and Kubernetes without slowing down application development and rollout. *Date: Sep 03, 2020 | 10 AM PDT* *SPONSORED*

[Docker shocker: Cash-strapped container crew threatens to delete 4.5 petabytes of unloved images](https://www.theregister.com/2020/08/14/docker_container_retention_policy/)  
You're still using Docker?!?!?! Have you not learned by now they do not give a flying fuck about users nor people? It's been like this since their inception. And the writing was on the wall before I wrote [Docker, Inc is Dead](https://chrisshort.net/docker-inc-is-dead/).

[Introducing Hierarchical Namespaces](https://kubernetes.io/blog/2020/08/14/introducing-hierarchical-namespaces/)  
"In its simplest form, a hierarchical namespace is a regular Kubernetes namespace that contains a small custom resource that identifies a single, optional, parent namespace. This establishes the concept of ownership across namespaces, not just within them."

[1Password for Linux development preview](https://discussions.agilebits.com/discussion/114964/1password-for-linux-development-preview)  
I have not kicked the tires on this yet but, I legit can't wait for everyone to be able to enjoy 1Password. I left LastPass long ago and am so glad I did.

[That UPS you bought for your home server may not be as useful as you think](https://fitzcarraldoblog.wordpress.com/2020/08/09/that-ups-you-bought-for-your-home-server-may-not-be-as-useful-as-you-think/)  
I learned a lot about UPSes in this blog post. Interestingly enough, my go to UPS these days is a top notch, feature rich one. One is powering my desk and two others are powering [the server I just acquired](https://twitter.com/ChrisShort/status/1294216468901568512?s=20). I highly recommend the [CyberPower CP1500AVRLCD Intelligent LCD UPS System, 1500VA/900W, 12 Outlets, AVR, Mini-Tower](https://amzn.to/30XcJu7).

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[Service Mesh with Michelle Noorali and Delyan Raychev](https://www.arresteddevops.com/service-mesh/)  
Oh hai, Microsoft! Oh look another service mesh! Oprah's out here with service meshes now.

[Recap: measuring linux performance - how to avoid typical mistakes](https://ma.ttias.be/recap-measuring-linux-performance-avoid-typical-mistakes/)  
"In the last two weeks, Peter Zaitsev published a 4-part series on measuring Linux performance on this blog." Peter is the CEO of Percona, a friend, and hands down, bar none the smartest database person in most any room. He knows every aspect of performance, how to measure it, and how it impacts operations. Teaming up with Mattias Geniar... Brilliant!

[swade1987/gitops-with-kustomize: An example repo structure for GitOps with Kustomize](https://github.com/swade1987/gitops-with-kustomize)  
A solid start. A few more folks contributing and this is gold.

## DevOps'ish Tweet of the Week

{{< tweet 1294374245791825922 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/179/notes/) to see what didn't make it to the newsletter.

