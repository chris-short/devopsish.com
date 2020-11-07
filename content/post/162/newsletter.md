+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-01-12T07:00:00Z
description = "kubectl tree, SHA-1, Pulse Secure VPN vulnerability, data gravity, Falco, eBPF, Bash-my-AWS, and more"
draft = false
slug = "162"
tags = ["data gravity", "AWS", "SHA-1", "DevOps", "developers", "eBPF", "VPN", "Pulse Secure", "vulnerability", "Kubenetes", "Falco", "Amazon", "bash", "kubectl", "cloud native", "open source", "OpenShift"]
title = "162: kubectl tree, SHA-1, Pulse Secure VPN vulnerability, data gravity, Falco, eBPF, Bash-my-AWS, and more"

+++

It felt like security dominated the news this week. A Pulse Secure VPN vulnerability is getting exploited. SHA-1 is effectively busted now. Firefox exploits need patching too. Meanwhile, Kubernetes news abounds with new talks, tools, and tips. Enjoy some other awesome deep dives, stories, and posts from across the industry too. Have a great week!

## Events

[DeliveryConf](https://www.deliveryconf.com/)  
Seattle, WA  
January 21-22, 2020  
DELIVERY|CONF 2020 is being held to give people a place to get deeper technical information about Continuous Integration (CI) and Continuous Delivery (CD). Our goal isn't to just tell you to "do the technical thing"; it is to show you real world examples of how others have done it. DELIVERY|CONF 2020 is a not-for-profit event being created by an all-volunteer team with many years of experience both in the technology and with creating conferences. Use discount code DEVOPSISH_10 for 10% admission.

[Hacking With The Homies Developers Conference Ticket](https://www.eventbrite.com/e/hacking-with-the-homies-developers-conference-tickets-83203845943)  
Detroit, MI  
Feb 29, 2020  
This is the first Software Developer Conference with a 100% focus on Black and Brown software developers. All sessions will be led by developers and will contain an actual code walk-thru. All presenters have a 3 slide limit and everything else has to be code. We have a Happy Hour after the conference where you can network and mingle with other developers. The profits from the conference will go to funding Detroit Black Tech initiatives and events.

## People

[Company shuts down because of ransomware, leaves 300 without jobs just before holidays](https://www.zdnet.com/article/company-shuts-down-because-of-ransomware-leaves-300-without-jobs-just-before-holidays/) — This is nightmare fuel. I couldn't imagine being a leader in a business that has been debilitated by ransomware to the point of deciding to shut down operations.

[OpenShift and Kubernetes, with Clayton Coleman](https://kubernetespodcast.com/episode/085-openshift-and-kubernetes/) — "Hosts Adam Glick and Craig Box return for 2020 with the story of OpenShift"

[Why I love Kubernetes Failure Stories and You Should Too by Henning Jacobs](https://youtu.be/E0GBU8Q-VFY) — "In this talk, I will walk you through our horror stories of operating 100+ clusters and share the insights we gained from incidents, failures, user reports and general observations."

[DoD Enterprise DevSecOps Initiative (Software Factory)](https://devopsish.com/pdf/DoD-Enterprise-DevSecOps-Initiative-Keynote-v1.7.pdf) — Nicolas Chaillan's presentation on how the US Air Force is fielding cutting edge technologies in its operations. This is a laundry list of good tips and practices on cloud native and DevOps.

[4 lessons for sysadmins from The Unicorn Project](https://www.redhat.com/sysadmin/unicorn-project) — This piece by Jason Hibbets is a sysadmin's guide to getting things done well.

[What It Takes to Give a Great Presentation](https://hbr.org/2020/01/what-it-takes-to-give-a-great-presentation) — I read this piece and immediately sent it to my daughter who starts up classes here soon. Such a great piece on what makes for good public speaking.

## Process

[Travelex being held to ransom by hackers](https://www.bbc.com/news/business-51017852) — This is a pretty bad hack and has tied up a ton of money. It's likely due to a [Pulse Secure VPN vulnerability](https://www.darkreading.com/attacks-breaches/widely-known-flaw-in-pulse-secure-vpn-being-used-in-ransomware-attacks/d/d-id/1336729) that was patched in April 2019.

[SHA-1 is a Shambles](https://sha-mbles.github.io/) — SHA-1's demise is upon us it appears. "We have computed the very first chosen-prefix collision for SHA-1." There shouldn't be a lot of SHA-1 left, although PGP/GnuPG was the target of the experiment. But, someone pointed out this week that some DNSSEC implementations use SHA-1. Keep your eyes peeled and update when you can.

[AWS Cost Optimization 101](https://cloudonaut.io/aws-cost-optimization-101/) — "The beginning of the year is the perfect time to clean up and optimize. This also applies to your AWS bill. [Andreas Wittig] composed practical tips on how to cut costs with small effort."

[6 requirements of cloud-native software by Daniel Oh](https://opensource.com/article/20/1/cloud-native-software) — A checklist for developing and implementing cloud-native (container-first) software.

[How to Use Sonatype OSS Index to Identify Security Vulnerabilities](https://blog.sonatype.com/how-to-use-sonatype-oss-index-to-identify-security-vulnerabilities) — "OSS Index is a free service that Sonatype provides for developers to check if any library has known, disclosed vulnerabilities."

[The soap opera continues. HP again tells Xerox: Show us more money!](https://www.theregister.co.uk/2020/01/09/the_soap_opera_continues_hp_again_tells_xerox_to_show_me_more_money/) — This is a legit popcorn eating saga of business craziness.

[An economic model for Data Gravity](http://blog.thestateofme.com/2020/01/03/an-economic-model-for-data-gravity/) — "We can model data gravity by looking at the respective storage and network costs for different scenarios where workload and associated data might be placed in one or more clouds. As network egress charges are relatively high, this makes the effect of data gravity substantial – pushing workloads and their data to be co-resident on the same cloud." Does this go far enough? I think it's hard not to look at databases when looking at data gravity. I started thinking about all the possible combinations and I got lightheaded.

## Tools

[TOC Votes to Move Falco into CNCF Incubator](https://www.cncf.io/blog/2020/01/08/toc-votes-to-move-falco-into-cncf-incubator/) — Congrats to the Falco folks!

[kubectl tree](https://ahmet.im/blog/kubectl-tree/) — Visualize Kubernetes object ownership

[Stop everything. Update Firefox now](https://www.grahamcluley.com/stop-everything-update-firefox-now/) — Serious vuln being exploited in the wild. Update immediately.

[OpenShift Authentication Integration with ArgoCD](https://blog.openshift.com/openshift-authentication-integration-with-argocd/) — Deep dive into using Openshift authentication with ArgoCD.

[Writing GitHub Actions in Go](https://www.sethvargo.com/writing-github-actions-in-go/) — " This post explores how to write and publish GitHub Actions written in Go, but the principles are largely applicable to any language since the deliverable is a Docker container."

[Intelligent DNS based load balancing at Dropbox](https://blogs.dropbox.com/tech/2020/01/intelligent-dns-based-load-balancing-at-dropbox/) — Deep dive into Dropbox's rather intense DNS load balancing which wouldn't be complete without maps of undersea cables. But, this post does highlight the need to understand the geography of the internet and the way traffic moves around the planet.

[A Deep Dive into eBPF: The Technology that Powers Tracee](https://blog.aquasec.com/intro-ebpf-tracing-containers) — eBPF is gonna have a big 2020 it would appear.

[Bash-my-AWS](https://bash-my-aws.org/) — "Bash-my-AWS is a simple but extremely powerful set of CLI commands for managing resources on Amazon Web Services."

[Urgent & Important – Rotate Your Amazon RDS, Aurora, and Amazon DocumentDB (with MongoDB compatibility) Certificates](https://aws.amazon.com/blogs/aws/urgent-important-rotate-your-amazon-rds-aurora-and-documentdb-certificates/) — "The SSL/TLS certificates for RDS, Aurora, and Amazon DocumentDB expire and are replaced every five years as part of our standard maintenance and security discipline."

[rakyll/govalidate](https://github.com/rakyll/govalidate) — Validates your Go installation and dependencies

## DevOps'ish Tweet of the Week

{{< tweet 1213607102595424258 >}}
