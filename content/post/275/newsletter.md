+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-07-10T07:00:00Z
description = ["Snakebit, You Belong Here, lots more layoffs, MI5 and FBI heads issue joint statement, 10 Awesome Kubernetes Projects for Beginners, and more"]
draft = false
slug = "275"
tags = ["open source", "cloud", "server", "git", "software", "Apple", "Kubernetes", "infrastructure", "service", "platform", "build", "code", "cloud native", "development", "Detroit", "Linux", "developer", " caching	"]
title = "DevOps'ish 275: Snakebit, You Belong Here, lots more layoffs, MI5 and FBI heads issue joint statement, 10 Awesome Kubernetes Projects for Beginners, and more"
+++

Have you ever felt like you're [snakebit][1]? When whatever you do in a particular discipline, nothing goes as planned.

I have a Dell R820 packed to the gills with 500 GB Samsung SSDs (I'll update to [1 TB drives][2] once they're under $100) in my lab. 1.3 terabytes of RAID10 at your service. If you've followed me since my Red Hat days, you've seen me wrangle with Kubernetes local storage on this box. I've destroyed this server live on air, on purpose, more than I want to admit.

After joining AWS, I didn't need an OpenShift cluster and completely wiped the server. It sat there completely off for weeks at a time. The entire month of June, it sat off. I didn't use the server for much after October, aside from the random tasks that were I/O heavy.

I'm focused on inner loop development in my new role at AWS. The pipeline to prod experience from there, while not necessarily in scope, that interface, that handoff, that experience, has to be solid. Also, the job will vary day-to-day as I'm the first Developer Advocate on this team. One day I might be building software from source one day. Next, I could be looking at a CI pipeline. Another day, I'll be creating and spinning up many containers at once. There's also this cool new thing for [bare metal called EKS Anywhere][3] (I had my feedback put into the product). It's open source, too; I don't need a license as long as I'm not calling support for it.

I'm spending time now, early in the job, while I'm reading and researching, doing technical work to balance my days and lay the foundation to emulate the developer experience. Whatever it may be—I'm building out the platform now so that I can feel the same pains. I build empathy this way. I build muscle memory this way. I usually pick up a good habit or two in the process.

I want to have all the flexibility our customers have at my fingertips as they do. Whether deploying from laptop to test on-prem or in the cloud, I want my use cases covered.

The problem I'm having is the kind of Murphy's Law that makes you want to hang it up for the weekend and give up until Monday. While that might have been a better option at 6 AM, I took the path of figuring things out. The difficulties of computers not bending to my will would have festered in my head all weekend if I'd not done something.

I woke up Saturday morning, looked over everything, realized what I was doing wrong, and proceeded to set things right in one place while something else would break. I realized I was trying to do too many things at once. One system at a time. One step at a time. The server came up. I moved my [code-server][4] over to it, so I could do a wipe and load on my brand new NUC, which decided it wanted to add in on the fun (along with Julie's laptop; Apple friends, call me).

The worst part is that these systems aren't connected in any way. I'm the only consistency here. Yes, I push systems to their limits. But, I'm not superstitious until life gives me a reason to be. I remember rough patches at literally all my jobs. Where things didn't fall my way, it's not so much what you do to get over the hump. The act of getting over it is hard but worth it. Once you're through it, you can go back and write that blog post you originally wanted to finish this weekend, but silicon had different plans for you.

[1]: https://www.merriam-webster.com/dictionary/snakebit
[2]: https://amzn.to/3RmeHfJ
[3]: https://aws.amazon.com/blogs/containers/getting-started-with-eks-anywhere-on-bare-metal/
[4]: https://devopsi.sh/env

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

## Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

## People

[You Belong Here](https://jpetazzo.github.io/2022/06/30/you-belong-here/)  
Jérôme Petazzoni  
"To all my LGBT+ friends, peers, and fellow members of the Kubernetes and Cloud Native communities: you do belong here. No matter what others think or say; privately or publicly; you played (and are still playing) a major role in the success of this community."

[Start-Up Funding Falls the Most It Has Since 2019](https://www.nytimes.com/2022/07/07/technology/tech-start-up-funding.html)  
Erin Griffith, The New York Times  
"The drop was another fallout of rising inflation and widespread economic uncertainty, and a retreat after years of a funding boom."

[Highflying Cyber Firms Cut Staff After Raising Hundreds of Millions of Dollars](https://www.wsj.com/articles/highflying-cyber-firms-cut-staff-after-raising-hundreds-of-millions-of-dollars-11657099801)  
David Uberti, WSJ  
"Security startups hunker down and stockpile cash as they prepare for a bear market."

[Sources: Unity Laying Off Hundreds Of Staffers [Update]](https://kotaku.com/sources-unity-laying-off-hundreds-of-staffers-1849125482)  
Ari Notis, Kotaku  
"Unity, the company behind the popular game development engine of the same name, has recently laid off hundreds of staffers"

[Man set up fake ISP to scam low-income people seeking gov't discounts, FCC says](https://arstechnica.com/tech-policy/2022/07/man-set-up-fake-isp-to-scam-low-income-people-seeking-govt-discounts-fcc-says/)  
Jon Brodkin, Ars Technica  
"[Kyle] Traxler created an entity called Cleo Communications that sought authorization to be a provider in the FCC's Emergency Broadband Benefit (EBB) program, which provided $50 monthly discounts on Internet service and discounts for devices."

[Meet the first graduating class of Apple's developer academy in Detroit](https://www.clickondetroit.com/news/local/2022/06/30/meet-the-first-graduating-class-of-apples-developer-academy-in-detroit/)  
Click On Detroit, Evrod Cassimy
"'This is the first time Apple is doing this in North America. To be a part of the first graduating class is really is a great accomplishment,' graduate Aaron Preston said." That's right, Apple did it in Detroit first.

[Systemd Creator Lands At Microsoft](https://www.phoronix.com/scan.php?page=news_item&px=Systemd-Creator-Microsoft)  
Michael Larabel, Phoronix  
"Yesterday's surprise was that [Lennart Poettering quietly had left Red Hat](https://www.phoronix.com/scan.php?page=news_item&px=Lennart-Poettering-Out-Red-Hat) following a decade and a half there leading PulseAudio among other projects and ultimately going on to start systemd that has fundamentally reshaped modern Linux distributions. It turns out he had joined Microsoft and continuing his work on systemd."

## Process

[The Social Model of Open Source](https://thenewstack.io/the-social-model-of-open-source/)  
Emily Omier, The New Stack  
"The social model of open source, Ferraioli says, is about understanding the different use cases for open source, as well as providing a framework for determining what appropriate success metrics could be depending on what the project's motivations are."

[OrBit: New Undetected Linux Threat Uses Unique Hijack of Execution Flow](https://www.intezer.com/blog/incident-response/orbit-new-undetected-linux-threat/)  
Nicole Fishbein, Intezer  
"Unlike other threats that hijack shared libraries by modifying the environment variable LD_PRELOAD, this malware uses 2 different ways to load the malicious library."

[China: MI5 and FBI heads warn of 'immense' threat](https://www.bbc.com/news/world-asia-china-62064506)  
Gordon Corera, BBC News  
"The heads of UK and US security services have made an unprecedented joint appearance to warn of the threat from China."

[Why Lockdown mode from Apple is one of the coolest security ideas ever](https://arstechnica.com/information-technology/2022/07/introducing-lockdown-from-apple-the-coolest-defense-youll-probably-never-use/)  
Dan Goodin, Ars Technica  
"Apple intros 'extreme' optional protection against the scourge of mercenary spyware."

[IDC expects cloud spending to surpass noncloud infrastructure for first time this year](https://siliconangle.com/2022/07/04/idc-expects-cloud-infrastructure-spending-surpass-non-cloud-first-time-year/)  
Mike Wheatley, SiliconANGLE  
"In its latest Worldwide Quarterly Enterprise Infrastructure Tracker: Buyer and Cloud Deployment, IDC said such spending rose 17.2% in the first quarter from a year ago, to $18.3 billion."

## Tools

[10 Awesome Kubernetes Projects for Beginners](https://www.containiq.com/post/kubernetes-projects-for-beginners)  
Vyom Srivastava, ContainIQ  
This went wild on social media this week. I can see why.

[The trouble with symbolic links](https://lwn.net/SubscriberLink/899303/3affe7bdef85706c/)  
Jonathan Corbet, LWN.net  
A fascinating discussion about symlinks, scheduling, and energy consumption.

[Is it time to look past Git?](https://dev.to/yonkeltron/is-it-time-to-look-past-git-ah4)  
Jonathan E. Magen, DEV Community
I can't fault any of these reasons for yearning for something better, easier, and friendlier than git. Hell, I down right don't like git but literally started using it because I couldn't keep up with changes in the git-mercurial plugin. Yes, I think [Mercurial](https://www.mercurial-scm.org/) is better than git. I'm sad it didn't take off.

[The Latin of Software Code Is Thriving](https://www.nytimes.com/2022/07/06/technology/cobol-jobs.html)  
Shira Ovide, The New York Times  
"Latin is dead, but old computer programming languages like COBOL live on."

[Infrastructure Self-Service with Crossplane](https://www.innoq.com/en/articles/2022/07/infrastructure-self-service-with-crossplane/)  
Sascha Selzer, INNOQ  
"Introducing container technology and Kubernetes to the development and deployment process allows developers to independently manage deployments of their services without needing to interact with the platform team. This is true for applications but not necessarily for external resources like databases which are probably still in the hands of the platform team because the access management and tooling differs. Crossplane could fill this gap towards a full self-service capability."

[Private Web based IDE](https://blog.shalman.org/private-web-based-ide/)  
Nahum Shalman
A riff on [my dev environment](https://devopsi.sh/env) using fewer components, complete with code.

[Cubernetes](https://www.justingarrison.com/blog/2022-07-06-cubernetes/)  
Justin Garrison  
It's so pretty.

[How We Built a Cross-Region Caching Library](https://www.wix.engineering/post/how-we-built-a-cross-region-caching-library)  
Wix Engineering  
"Because of Wix's massive growth over a short period of time, several different developers created different caching solutions to help them reduce the number of HTTP requests and fancy DB queries. But these libraries didn't cover all the needed features and were more of a "halfway" solution. On top of that, different groups used different libraries so it became unhealthy for the organization to keep going like this - we needed an internal caching solution as part of our server infrastructure. "

[h3xduck/TripleCross](https://github.com/h3xduck/TripleCross)  
A Linux eBPF rootkit with a backdoor, C2, library injection, execution hijacking, persistence and stealth capabilities

[pocketbase/pocketbase](https://github.com/pocketbase/pocketbase)  
Open Source realtime backend in 1 file

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.
