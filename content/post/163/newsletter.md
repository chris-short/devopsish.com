+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-01-19T07:00:00Z
description = "Mozilla and DigitalOcean Layoffs, NSA discloses Windows vuln, Kubernetes Bug Bounty Program, PrivateBin, and more"
draft = false
slug = "163"
tags = ["Kubernetes", "cloud native", "DevOps", "NSA", "Mozilla", "DigitalOcean", "bug bounty", "developers", "Microsoft", "Windows", "AWS", "layoffs", "chaos engineering", "Ansible", "governance", "infosec", "security", "pair programming", "postmortems", "Y2K"]
title = "163: Mozilla and DigitalOcean Layoffs, NSA discloses Windows vuln, Kubernetes Bug Bounty Program, PrivateBin, and more"

+++

Got a jam-packed newsletter this week, complete with relevant stories from The Washington Post and New York Times. It's an exciting time to be alive. I remember when something had to be earth-shattering to make these papers. Nowadays, it seems commonplace to read about low level, tech news (like the .org registry issues), and high stakes tech news all the same (like the NSA disclosing a Windows vuln). But, what these two stories this week highlight is the importance of governance. In one case, there is seemingly poor governance. In the other case, there is potentially the saving of billions of dollars of economic impact. Hopefully, we can somehow save the .org registry in the same way the NSA helped Microsoft this week.

## Events

[DeliveryConf](https://www.deliveryconf.com/)  
Seattle, WA  
January 21-22, 2020  
DELIVERY|CONF 2020 is being held to give people a place to get deeper technical information about Continuous Integration (CI) and Continuous Delivery (CD). Our goal isn't to just tell you to "do the technical thing"; it is to show you real world examples of how others have done it. DELIVERY|CONF 2020 is a not-for-profit event being created by an all-volunteer team with many years of experience both in the technology and with creating conferences. Use discount code *DEVOPSISH_10* for 10% admission.

[Hacking With The Homies Developers Conference Ticket](https://www.eventbrite.com/e/hacking-with-the-homies-developers-conference-tickets-83203845943)  
Detroit, MI  
Feb 29, 2020  
This is the first Software Developer Conference with a 100% focus on Black and Brown software developers. All sessions will be led by developers and will contain an actual code walk-thru. All presenters have a 3 slide limit and everything else has to be code. We have a Happy Hour after the conference where you can network and mingle with other developers. The profits from the conference will go to funding Detroit Black Tech initiatives and events.

[SCALE 18x](https://www.socallinuxexpo.org)  
March 5-8, 2020  
SCaLE 18x – the 18th annual Southern California Linux Expo – will take place in March 5-8, 2020, at the Pasadena Convention Center. SCaLE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. SCaLE 18X expects to host 120 exhibitors this year, along with over 200 sessions, tutorials and special events. From kernels to containers, beginner installs to advanced security, HAMs to clouds, there is something for you at SCALE 18X.

[DevOpsDay LA](https://devopsdays.org/events/2020-los-angeles/)  
March 6, 2020  
DevOpsDay LA is a technical conference covering topics of software development, IT infrastructure operations, and the intersection between them.

## People

[Mozilla lays off 70 as it waits for new products to generate revenue](https://techcrunch.com/2020/01/15/mozilla-lays-off-70-as-it-waits-for-subscription-products-to-generate-revenue/) — "In an internal memo, Mozilla chairwoman and interim CEO Mitchell Baker specifically mentions the slow rollout of the organization’s new revenue-generating products as the reason for why it needed to take this action. The overall number may still be higher, though, as Mozilla is still looking into how this decision will affect workers in the U.K. and France."

[DigitalOcean is laying off staff, sources say 30-50 affected](https://techcrunch.com/2020/01/17/digitalocean-layoffs/) — "After appointing a new CEO and CFO last summer, cloud infrastructure provider DigitalOcean is embarking on a wider reorganisation: the startup has announced a round of layoffs, with potentially between 30 and 50 people affected."

[Internet Nonprofit Leaders Fight Deal to Sell Control of .org Domain](https://www.nytimes.com/reuters/2020/01/10/technology/09reuters-internet-domain-sale.html) — Not too often industry news like this hits the newsstands.

[On mid-career challenges by Ryn Daniels](https://www.ryn.works/blog/on-mid-career-challenges) — An interesting take on the impact the current tech job market has on an individual's career trajectory is rather problematic.

## Process

[NSA found a dangerous Microsoft software flaw and alerted the firm — rather than weaponizing it](https://www.washingtonpost.com/national-security/nsa-found-a-dangerous-microsoft-software-flaw-and-alerted-the-firm--rather-than-weaponize-it/2020/01/14/f024c926-3679-11ea-bb7b-265f4554af6d_story.html) — The global instability this could have caused if it hadn't gone patched is mind-boggling. Also, our industry on newsstands again this week.

[Introducing the Kubernetes Bug Bounty Program](https://www.cncf.io/blog/2020/01/14/introducing-the-kubernetes-bug-bounty-program/) — I am so happy that the Kubernetes bug bounty program has come to fruition.

[Getting Serious About Open Source Security](https://cd.foundation/blog/2020/01/15/getting-serious-about-open-source-security/) — "A not so serious look at a very serious problem." Also, shout out for reposting this from Medium. I was legit concerned about readers hitting the [spontaneous Medium paywall](https://nomedium.dev) but, no worries now.

[NSW fires: Wollemi pines saved by secret RFS firefighting mission](https://www.smh.com.au/environment/conservation/incredible-secret-firefighting-mission-saves-famous-dinosaur-trees-20200115-p53rom.html) — Never underestimate the power of determined humans on clandestine missions... Even when it's to save a species of trees.

[State of the Auth: 2FA Use and Awareness Surge](https://duo.com/blog/2fa-use-and-awareness-surge) — "The survey revealed that 53% of respondents have used 2FA, representing a 25% jump in just two years. Meanwhile, 77% of survey respondents said they’ve heard of 2FA, which is up from 44% in 2017’s survey, a 33% swing."

[On Pair Programming](https://martinfowler.com/articles/on-pair-programming.html) — "One reason for its varying acceptance is that its benefits are not immediately obvious, it pays off more in the medium- and long-term. And it's also not as simple as "two people working at a single computer", so many dismiss it quickly when it feels uncomfortable. However, in our experience, pair programming is vital for collaborative teamwork and high quality software."

[5 Example Postmortems & Best Practices you can Start Using Today](https://www.blameless.com/5-best-practices-nailing-postmortems/) — "Postmortems are like snowflakes; no two will ever look the same. There isn’t a definitive template for success that will work in every situation, but there are some practices and procedures when writing postmortems that can help."

[20 Years Since Y2K: left-pad, Heartbleed, and DevOps](https://www.transposit.com/blog/2020.01.15-left-pad-heartbleed-and-devops/) — "An exploration of incidents that changed how we operate since Y2K"

[Microsoft just ended support for the dominant PC OS in China](https://www.abacusnews.com/china-tech-city/microsoft-just-ended-support-dominant-pc-os-china/article/3045984) — Windows 7 support is officially (unofficially) over.

[Huawei restructures to focus on cloud computing, AI](https://technode.com/2020/01/14/huawei-makes-changes-to-organizational-structure-highlighting-cloud-computing-ai/) — "Huawei announced last week changes to its organizational structure and management team, creating a fourth business group for its cloud computing and artificial intelligence (AI) divisions in a sign that the telecommunications giant is priming to ramp up its efforts in this sector."

## Tools

[Backblazed](https://daniel.haxx.se/blog/2020/01/14/backblazed/) — It's really cool when a company whose product you pay for supports an open source project you love.

[Kubernetes on MIPS](https://kubernetes.io/blog/2020/01/15/kubernetes-on-mips/) — Rejoice MIPS systems! You can run pods, replica sets, ingresses, and more too.

[Tesla Is Making Use Of The Open Source Coreboot Within Their Electric Vehicles](https://www.phoronix.com/scan.php?page=news_item&px=Tesla-Uses-Coreboot) — After hearing Jessie Frazelle's talk on our system's underlying firmware code, I'm more convinced that coreboot is an essential open source project.

[netblue30/firejail](https://github.com/netblue30/firejail) — Linux namespaces and seccomp-bpf sandbox

[PrivateBin/PrivateBin](https://github.com/PrivateBin/PrivateBin) — A minimalist, open source online pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256 bits AES.

[KubeVault v0.3.0 - Tools for running HashiCorp Vault on Kubernetes](https://blog.byte.builders/post/kubevault-v0.3.0/) — "This is a major rewrite of the project that captures the concepts present in Vault in a Kubernetes native way." Indeed it is.

[Chaos Mesh - Your Chaos Engineering Solution for System Resiliency on Kubernetes](https://pingcap.com/blog/chaos-mesh-your-chaos-engineering-solution-for-system-resiliency-on-kubernetes/) — "Chaos Mesh is a versatile Chaos Engineering platform that features all-around fault injection methods for complex systems on Kubernetes, covering faults in Pod, network, file system, and even the kernel."

[New API coming for Podman](https://podman.io/releases/2020/01/17/podman-new-api.html) — Sounds like some good changes are in store for Podman.

[jnoller/kubernaughty](https://github.com/jnoller/kubernaughty) — IO, resource contention notes, docs and tools

[MariaDB Goes Cloud Native with AWS S3 API, and Introduces 'Smart' Transactions](https://thenewstack.io/mariadb-goes-cloud-native-with-aws-s3-api-and-introduces-smart-transactions/) — MariaDB isn't playing games. Cloud native or bust.

[Setup and Deploy Vitess on Kubernetes (Minikube) for MySQL - Part II of III](https://www.percona.com/blog/2020/01/14/setup-and-deploy-vitess-on-kubernetes-minikube-for-mysql-part-ii-of-iii/) — A great blog series on setting up Vitess which answers the question, "How do you run MySQL on Kubernetes?"

[0x4447/0x4447_product_s3_email](https://github.com/0x4447/0x4447_product_s3_email) — 📫 A serverless email server on AWS using S3 and SES

[How Useful Is Ansible in a Cloud-Native Kubernetes Environment?](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment) — Jeff Geerling's take on where Ansible fits in the cloud native ecosystem of tools. What are you using Ansible for in your environments?

## DevOps'ish Tweet of the Week

{{< tweet 1217682156710846464 >}}
