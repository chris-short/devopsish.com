+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-10-24T07:00:00Z
description = ["You're probably underpaid, Karanbir Singh Steps Down, Honeycomb's cool $50 million, and more"]
draft = false
slug = "240"
tags = ["cloud", "Cloud Native", "DevOps", "Linux", "kernel", "KubeCon", "open source", "security", "SSH", "Kubernetes", "Honeycomb", "GitOps"]
title = "DevOps'ish 240: You're probably underpaid, Karanbir Singh Steps Down, Honeycomb's cool $50 million, and more"

+++

KubeCon hangover is real. I grossly overestimated how much I'd be able to do in four days, of course. I spent my little break between jobs trying to sleep in most days. Spend extra time with Max (daddy pick-ups from school are a real thing now). But, any time I went to do something technical or constructive, it took a lot longer than I thought it would. I did a lot of little niceties to [various websites](https://chrisshort.net/projects/), pre-employment stuff, write the $newjob blog post, and generally did not think about complex things. I wanted to tinker with a list of little projects, but I opted to read maybe or play Madden instead. It wasn't bad, but to say I've recovered from KubeCon is a gross overestimation. I'm going to shut myself in and lay on heating packs all day tomorrow, more than likely. Two bad ankles, a bone spur in the neck, and a bad shoulder all snarling at you doesn't make for a good time.

## People

[Report: 47% of U.S. employees say they are underpaid](https://venturebeat.com/2021/10/20/report-47-of-u-s-employees-say-they-are-underpaid/)  
The educational challenges stiffing people's growth.

Teleport allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments. [Learn more](https://goteleport.com/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish). *SPONSORED*

[Mark Zuckerberg to Be Added to Facebook Privacy Suit](https://www.nytimes.com/2021/10/20/technology/mark-zuckerberg-facebook-lawsuit.html)  
"Mark Zuckerberg, the chief executive of Facebook, had an active role in decisions that are under scrutiny, the District of Columbia's attorney general said." How's that [name change](https://www.theverge.com/2021/10/19/22735612/facebook-change-company-name-metaverse) going?

[CentOS Project Chair Karanbir Singh Steps Down](https://www.phoronix.com/scan.php?page=news_item&px=Singh-CentOS-Steps-Down)  
CentOS Stream has a wide blast radius it would seem.

[Cloud Native Computing Foundation Announces 2021 Community Awards Winners](https://www.cncf.io/announcements/2021/10/15/cloud-native-computing-foundation-announces-2021-community-awards-winners/)  
I'm incredibly proud of Anaïs Urlichs, Nikhita Raghunath, Tim Bannister, Emily Fox, Aeva Black, Tasha Drew, Carlos Panato, and Carolyn Van Slyck.

## Process

[How a simple Linux kernel memory corruption bug can lead to complete system compromise](https://googleprojectzero.blogspot.com/2021/10/how-simple-linux-kernel-memory.html)  
"This blog post describes a straightforward Linux kernel locking bug and how I exploited it against Debian Buster's 4.19.0-13-amd64 kernel. Based on that, it explores options for security mitigations that could prevent or hinder exploitation of issues similar to this one."

[Collaboration and Automation for Infrastructure as Code](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and quality of life features. [Free Demo](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[How Honeycomb Is Using $50M in New Funding to Bring Observability to All](https://www.honeycomb.io/blog/series-c-funding-bringing-observability-to-all/)  
"We're using this investment to support the growth of our customers and community, ensure the benefits of observability can be realized by all engineering teams, and expand the ways we can better serve you."

[Incident Review and Postmortem Best Practices](https://newsletter.pragmaticengineer.com/p/incident-review-best-practices)  
A survey of how companies deal with incidents today, and a peek into the best practices of the future. NOTE: I'm not too fond of the premise of best practices. They're practices that work well today. But, in a year could be table stakes.

[Navigating ATOs](https://18f.gsa.gov/2021/10/19/navigating-atos/)  
My government friends will appreciate this.

## Tools

[The Only Bash Scripting Cheat Sheet That You Will Ever Need](https://dev.to/bobbyiliev/the-only-bash-scripting-cheat-sheet-that-you-will-ever-need-55c7)  
A bold statement.

In modern architecture, slow is the new down. Distributed tracing shows your deeply hidden problems so you can fix the right issue the first time. It's never been easier to get started. [Use Honeycomb and OpenTelemetry](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) to quickly find hidden slowness–for free. *SPONSORED*

[What's in a hostname?](https://www.netmeister.org/blog/hostnames.html)  
A lot more than you probably realize.

[New HTTP standards for caching on the modern web](https://httptoolkit.tech/blog/status-targeted-caching-headers/)  
Remember when we ran Varnish servers at scale? I'm sure they're still out there but, I haven't had to think much about caching since switching to a static site using various services to put together a website

[Brave Removes Google as its Default Search Engine](https://www.thurrott.com/cloud/web-browsers/258380/brave-removes-google-as-its-default-search-engine)  
The 90s advice, "never use the default search engine" is now back in style.

[Iterating on how we do NFS at Wikimedia Cloud Services](https://techblog.wikimedia.org/2021/10/19/iterating-on-how-we-do-nfs-at-wikimedia-cloud-services/)  
The way anyone manages a massive amount of data is always interesting to me.

[SuDump: Exploiting suid binaries through the kernel](https://alephsecurity.com/2021/10/20/sudump/)  
"In this research we dug deeper into how core dump handling happens inside the Linux kernel. We explored several different mechanisms which are all individually valid, but combined together can create dangerous unwanted behavior."

[maxgoedjen/secretive](https://github.com/maxgoedjen/secretive)  
Store SSH keys in the Secure Enclave

[IntelLabs/control-flag](https://github.com/IntelLabs/control-flag)  
A system to flag anomalous source code expressions by learning typical expressions from training data

[ossf/scorecard](https://github.com/ossf/scorecard)  
Security Scorecards - Security health metrics for Open Source

[ddosify/ddosify](https://github.com/ddosify/ddosify)  
High-performance load testing tool, written in Golang.

[Netflix/flamescope](https://github.com/Netflix/flamescope)  
FlameScope is a visualization tool for exploring different time ranges as Flame Graphs.

[l0phtcrack](https://gitlab.com/l0phtcrack)  
Now open source.

## DevOps'ish Tweet of the Week

[![julia ferraioli @juliaferraioli on Twitter) "Mastodon founder Eugen Rochko told The Post on Thursday that Trump's site may violate Mastodon's licensing rules, which require developers to share any modifications and link to the original source code." *laughs in open source*](https://shortcdn.com/file/devopsish/240-devopsish-tweet-of-the-week.png)](https://twitter.com/juliaferraioli/status/1451381022013079553)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/240/notes/) to see what didn't make it to the newsletter but are still worth your time.
