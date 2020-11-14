+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-12-16T07:00:00Z
description = "Guinevere Saenger on Kubernetes 1.17 release, devs as a new soft target, need for a college degree, htop, CRDs, Istio, and more"
draft = false
slug = "158"
tags = ["Guinevere Saenger", "Kubernetes", "cloud", "cloud native", "DevOps", "Istio", "CRDs", "open source", "developers", "htop", "release", "college degree", "AWS", "Red Hat", "org TLD", "remote", "deliveryconf", "infrastructure", "Detroit", "DevSecOps", "Agile", "Google", "Seattle", "Ansible", "defense-in-depth"]
title = "158: Guinevere Saenger on Kubernetes 1.17 release, devs as a new soft target, need for a college degree, `htop`, CRDs, Istio, and more"

+++

The year 2019 is winding down. This is the time of year I reflect on the past 365 days. I feel a few themes that are predominant but, I’m looking forward "for the next thing" and it’s still [Kubernetes](https://kubernetes.io) and the cloud native ecosystem. This is why I think Kubernetes will become the standard cloud APIs that we all build on in the future. I look at [Linux](https://opensource.com/resources/linux) and how it has become table stakes these days. I look at [Ansible](https://ansible.com) and see that organizations are using either Ansible or a very similar tool. Seeing application deployment and infrastructure as code as more of the norm than the exception is great! Then there’s Kubernetes. The tool providing a consistent, repeatable, and extensible functionality to every cloud provider. While cloud providers’ lack of interoperability by design attempts to lock folks in ([there’s plenty here for everyone, AWS](https://www.crn.com.au/news/aws-forbids-partners-even-mentioning-multi-cloud-529598)), Kubernetes is there making hybrid solutions possible. I see organizations using it to provide the right blend of on-premises and cloud resource use. I see folks using it for data science to make sure their models run to completion. I see folks building mountains of [Raspberry Pi Kubernetes clusters](https://chrisshort.net/raspberry-pi-kubernetes-cluster/) to learn it. Kubernetes is becoming a standard API set folks are starting to expect to exist in data centers and clouds. When I look for what’s next in technology, I generally look for pain points. Kubernetes is solving some pain points and working on improving others with every release. Linux lowered the barrier to quality operating systems. Kubernetes is pushing infrastructure to be API driven. This is what we’ve wanted for ***years***. It’s not perfect but, the future is now.

[**Calling all DevOps Advocates**](http://bit.ly/DevOpsIsh)  
Does the idea of helping software professionals build and deploy modern cloud software faster and more collaboratively excite you? Pulumi is looking for a passionate Developer Advocate to build a community outreach program that will help devs and ops folks build innovative cloud software together using their open source infrastructure as code platform. [Join the team today](http://bit.ly/DevOpsIsh)!  *SPONSORED*

[**X-Team is Hiring Go developers with strong AWS skills (Remote)**](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)  
We are looking for passionate Go developers with strong AWS skills to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. We provide the funding needed to help you achieve your goals and grow as a remote developer. [Join X-Team](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)! *SPONSORED*

## Events

[DeliveryConf](https://www.deliveryconf.com/)  
Seattle, WA  
January 21-22, 2020  
DELIVERY|CONF 2020 is being held to give people a place to get deeper technical information about Continuous Integration (CI) and Continuous Delivery (CD). Our goal isn't to just tell you to "do the technical thing"; it is to show you real world examples of how others have done it. DELIVERY|CONF 2020 is a not-for-profit event being created by an all-volunteer team with many years of experience both in the technology and with creating conferences.

## People

[Malicious attackers are zeroing in on developers for their next big score](https://siliconangle.com/2019/12/10/malicious-attackers-zeroing-developers-next-big-score/) — This has always been a concern of mine. One of my projects early on after getting out of the Air Force was to conduct an educational wake-up call to my company. I setup [sptoolkit](https://github.com/chris-short/sptoolkit) on the old, old Red Hat OpenShift (the one with cartridges; way before I worked there). This gave me legitimately signed TLS keys on a Red Hat domain. From here I could host a very fake but functional login page for login boxes from Google, Box, Microsoft, and Yahoo. The email was carefully crafted to look suspicious as hell to those that were security-minded already. I made sure one last time everyone in my section was aware of the number of folks we were targeting and whom we weren’t for political reasons. After a final confirmation the op was a go. Upon launching the attack my phone rang, “Chris, did you see this email that just came out?” I said I was looking into it. Instead, I watched the numbers pile up as folks clicked bad links, took another step to log in, and were surprised to be followed by materials that would help them to prevent such attacks for succeeding in the future. No one in the administrative and HR roles in the org ended up getting phished. However, the entire dev team did. If the attack were real, we would have been dealing with compromised credentials to core business applications. Developers are a weak link in the defense-in-depth strategy because they’re humans like the rest of us. But, the implications are greater because of the trust given to engineers over business-critical systems. These people must be hyper-vigilant when it comes to their credential safety.

[Do I need a college degree to be a sysadmin?](https://www.redhat.com/sysadmin/college-degree) — No. I was a sysadmin and ran day-to-day operations for an internet service provider *while I was still in high school*. You don't need a degree in this. But, you definitely need to be really comfortable reading RFCs and figuring things out on your own.

[Former Oracle product manager says he was forced out for refusing to deceive customers. Now he's suing the biz](https://www.theregister.co.uk/2019/12/04/oracle_product_manager_lawsuit/) — "For a civil RICO claim to succeed, the plaintiff must show that the defendant committed one of the crimes covered by the statute, such as mail fraud or wire fraud."

[The Rise Of Open-Source Software (YouTube)](https://www.youtube.com/watch?v=SpeDK1TPbew) — "Open-source software powers nearly all the world’s major companies. This software is freely available, and is developed collaboratively, maintained by a broad network that includes everyone from unpaid volunteers to employees at competing tech companies. Here’s how giving away software for free has proven to be a viable business model."

[Maersk CISO Says NotPeyta Devastated Several Unnamed US firms](https://www.darkreading.com/threat-intelligence/maersk-ciso-says-notpeyta-devastated-several-unnamed-us-firms/a/d-id/1336558) — "At least two companies may have been dealt even more damage than the shipping giant, which lost nearly its entire global IT infrastructure."

[When You Work in a Male-Dominated Industry](https://hbr.org/podcast/2019/12/when-you-work-in-a-male-dominated-industry) — "Research shows that even well-meaning mentors direct female engineers into less technical, less valued roles. It’s no wonder so many women end up leaving the industry. We talk to a professor and two students at Olin College of Engineering about their experiences working among mostly men, what it means to “play nice,” and how male colleagues can help (listen!)."

[Google under investigation from NLRB](https://www.cnbc.com/2019/12/09/google-under-investigation-from-nlrb.html) — "The U.S. National Labor Relations Board has begun an official investigation into Google after the recent firing of four employees."

[High-tech job growth concentrated in just 5 cities, driving 'national inequality,' report finds](https://abcnews.go.com/Technology/high-tech-job-growth-concentrated-cities-driving-national/story?id=67596450) — Gravity matters. Detroit has a chance to become a Raleigh or even one of these cities. But, when you look at some of the challenges the high-tech hubs have and the ones Detroit is facing, there are many lessons Detroit will have to learn earlier in its transformation. This will likely lead to better outcomes for its citizens than those of San Francisco, Seattle, and Austin. That's my hope at least.

## Process

[FAQ for December 2019 TOC Nominations](https://www.cncf.io/blog/2019/12/13/faq-for-december-2019-toc-nominations/) — This process got really confusing. Thank you for this, Amye.

[Introduction to DevSecOps by John Willis](https://blog.openshift.com/introduction-to-devsecops-by-john-willis-red-hat-openshift-commons-briefing/) — "Why traditional DevOps has shifted and what this shift means. How DevSecOps can change the game for your team. How to get DevSecOps initiatives started within your organization."

[Number-crunchers set new record for cracking online encryption keys](https://www.newscientist.com/article/2226458-number-crunchers-set-new-record-for-cracking-online-encryption-keys/) — "A new record has been set for the largest encryption key ever cracked – but your secrets should be safe for now."

[We Need To Save .ORG From Arbitrary Censorship By Halting the Private Equity Buy-Out](https://www.eff.org/deeplinks/2019/12/we-need-save-org-arbitrary-censorship-halting-private-equity-buy-out) — "EFF has joined with over 250 respected nonprofits to oppose the sale of Public Interest Registry, the (currently) nonprofit entity that operates the .ORG domain, to Ethos Capital."

[Snyk's Gareth Rushgrove on How Visibility Is Driving Security](https://thenewstack.io/snyks-gareth-rushgrove-on-how-visibility-is-driving-security/) — I always enjoy reading things about my friends are doing. Snyk is up to some cool things.

[What Aircraft Crews Know About Managing High-Pressure Situations](https://hbr.org/2019/12/what-aircraft-crews-know-about-managing-high-pressure-situations) — "Debris from the exploded engine hit the left wing, destroying a number of electrical and hydraulic lines. Thereafter, several essential aircraft control systems failed. Over the next harrowing two hours, the pilots flew in a holding pattern..."

[Intel Unveils Cryogenic Chip To Speed Quantum Computing](https://spectrum.ieee.org/tech-talk/computing/hardware/intel-unveils-cryogenic-chips-to-speed-quantum-computing) — "Horse Ridge cryogenic control chip will let Intel increase the number of qubits"

[Agile project management: 4 lessons learned this year](https://enterprisersproject.com/article/2019/12/agile-project-management-4-lessons) — "Eighteen years after the publishing of the Agile Manifesto, how do its principles hold up? Pretty well.  But we’ve also learned some new lessons for agile teams"

[Red Hat Wins 2019 Ford IT Innovation Award](https://www.redhat.com/en/about/press-releases/red-hat-wins-2019-ford-it-innovation-award) — This is a significant award to me. Ford is the  automaker I've driven since 2003. Kubernetes is a project I've worked on since 2016. Red Hat is the company I've worked at for a year and a half. OpenShift is a product I've worked on since this summer. It's *really* cool to see all this in one place.

[9 of the biggest open source stories in 2019](https://www.techrepublic.com/article/9-of-the-biggest-open-source-stories-in-2019/)

## Tools

#### Kubernetes 1.17

* [**Kubernetes 1.17, with Guinevere Saenger**](https://kubernetespodcast.com/episode/083-kubernetes-1.17/)
* [Release v1.17.0 · kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/releases/tag/v1.17.0)
* [Kubernetes 1.17: Stability](https://kubernetes.io/blog/2019/12/09/kubernetes-1-17-release-announcement/)
* [Kubernetes 1.17 Feature: Kubernetes Volume Snapshot Moves to Beta](https://kubernetes.io/blog/2019/12/09/kubernetes-1-17-feature-cis-volume-snapshot-beta/)
* [Kubernetes 1.17 Feature: Kubernetes In-Tree to CSI Volume Migration Moves to Beta](https://kubernetes.io/blog/2019/12/09/kubernetes-1-17-feature-csi-migration-beta/)
* [Kubernetes 1.17: Volume Snapshots Beta and Scheduler changes for stability and extensibility](https://blog.openshift.com/kubernetes-1-17-volume-snapshots-beta-and-scheduler-changes-for-stability-and-extensibility/)
* [What’s New in Kubernetes 1.17: A Deeper Look at New Features](https://www.stackrox.com/post/2019/12/whats-new-in-kubernetes-1.17-a-deeper-look-at-new-features/)
* [Kubernetes 1.17 Features and Enhancements](https://blog.aquasec.com/new-in-kubernetes-1.17)

[SSH to remote hosts though a proxy or bastion with ProxyJump](https://www.redhat.com/sysadmin/ssh-proxy-bastion-proxyjump) — I love me some SSH ProxyJump.

[similarweb/finala](https://github.com/similarweb/finala) — A resource cloud scanner that analyzes and reports about wasteful and unused resources to cut unwanted expenses.

[CRD in Kubernetes: Powerful boost for an already powerful platform](http://techgenix.com/crd-in-kubernetes/) — Everyone can create APIs with CRDs, literally everyone. That's why CRDs exploded into the Kubernetes scene this year.

[Reducing Istio proxy resource consumption with outbound traffic restrictions](https://banzaicloud.com/blog/istio-sidecar/) — Istio is a beast. There are lighter-weight tools out there, like [Linkerd](https://linkerd.io/), that might better fit your needs. But, the industry has put a lot of weight behind Istio for large scale use cases. Naturally, folks want to learn Istio. Step one: it's a resource hog, be ready.

[Running Cassandra in Kubernetes: challenges and solutions](https://medium.com/flant-com/running-cassandra-in-kubernetes-challenges-and-solutions-9082045a7d93)

[Linux process management improved with `htop`](https://www.redhat.com/sysadmin/process-management-htop) — I keep running into people who haven't heard of `htop` somehow.

[kyma-project/rafter](https://github.com/kyma-project/rafter) — Kubernetes-native S3-like files/assets store based on CRDs and powered by MinIO

[Istio finds pair of critical vulnerabilities, issues trio of updates](https://devclass.com/2019/12/11/istio-finds-pair-of-critical-vulnerabilities-issues-trio-of-updates/) — Patch your meshes

[How to Export Kubernetes Events for Observability and Alerting](https://engineering.opsgenie.com/how-to-export-kubernetes-events-for-observability-and-alerting-a9b4a953363d) — "A hidden gem in Kubernetes might be holding a lot of information"

[How to test and validate DNSSEC using dig command line](https://www.cyberciti.biz/faq/unix-linux-test-and-validate-dnssec-using-dig-command-line/) — This is new enough technology that I haven't memorized this yet but, definitely run into more frequently.

## Tweet of the Week

{{< tweet 1203768589540454400 >}}
