+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-01-23T03:30:00Z
description = ["5G — It's all good, Measuring open source, Intel coming to Ohio, MoonBounce, GitOps in 2021, Google SRE hellscape, and more"]
draft = false
slug = "253"
tags = ["open source", "Intel", "5G", "MoonBounce", "security", "firmware", "environment", "Ohio", "Merck", "FAA", "malware", "Roblox", "SimCity", "Honeycomb", "upstream", "Solarwinds", "Linux", "GitOps"]
title = "DevOps'ish 253: 5G — It's all good, Measuring open source, Intel coming to Ohio, MoonBounce, GitOps in 2021, Google SRE hellscape, and more"

+++

DevOps'ish is brought to you by [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
"Stop Letting Complexity Slow You Down"  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

5G became an absolute shit show this week. But, at the end of it all, [Airline CEOs made a 180-degree turn and are now saying 5G isn’t a big problem for altimeters](https://arstechnica.com/tech-policy/2022/01/airline-ceos-make-u-turn-now-say-5g-isnt-a-big-problem-for-altimeters/). They are a few 100 megahertz apart. But, the summary might piss you off, "After stalling for almost two years, FAA cleared 78% of planes in the past week." I'm pretty sure the FAA has had a tumultuous past couple of years like many other employers. Productivity and staffing issues were probably significant limitations. You can't work in a lab if you can't go into the building. There's only so much simulating you can do before you need to make sure you're not going to kill a test pilot and need to touch the hardware in test conditions. Those skills are probably in high demand right now too. But, when you get the President's attention, you get what you need in government. That's how it works (I didn't say it was right; it's politics, and I've been there and done that).

Meanwhile, I saw three weirdly related headlines in a rather exciting succession this week:

* [Looking At The New "Critical" Security Firmware Update Hitting Systems - Delivers New Intel Microcode - Phoronix](https://www.phoronix.com/scan.php?page=article&item=jan-2022-firmware)
* [Chinese Hackers Spotted Using New UEFI Firmware Implant in Targeted Attacks](https://thehackernews.com/2022/01/chinese-hackers-spotted-using-new-uefi.html)
* [New MoonBounce UEFI bootkit can't be removed by replacing the hard drive - The Record by Recorded Future](https://therecord.media/new-moonbounce-uefi-bootkit-cant-be-removed-by-replacing-the-hard-drive/)

MoonBounce is what, I fear, is going to be the start of a wave of firmware vulnerabilities. I hope I'm wrong but, [we were warned about this years ago](https://youtu.be/oHK0lhBbJ3g). It's a ripe mark in an environment that has been neglected. The bottom line is security teams will continue to have their hands full as this attack vector matures.

## People

[Exclusive: Intel Reveals Plans for Massive Factory in Ohio](https://time.com/6140476/intel-building-factory-ohio/)  
[Mike DeWine'd and dined while Jon Husted hustled to get Intel to feel at home in Ohio](https://www.dispatch.com/in-depth/business/2022/01/21/how-mike-dewine-jon-husted-got-intel-come-ohio/9183683002/). This is a big win for the entire midwest which is ***RIPE*** for developments like Intel's.

[Army spouse uses Apple AirTag to track down shady moving truck driver](https://taskandpurpose.com/news/army-airtag-moving-company/)  
The interstate moving industry is a ruthless, lightly regulated network. We had to get a lawyer involved to get our stuff back from the mover's when we moved to Michigan. This is a brilliant idea.

[Inside Google’s Brewing Mental Health Crisis, Claims of Toxic Work Environment](https://www.bloomberg.com/news/features/2022-01-20/inside-google-s-brewing-mental-health-crisis-claims-of-toxic-work-environment)  
So much for [Google's Project Aristotle](https://rework.withgoogle.com/print/guides/5721312655835136/). Being an SRE at Google sounds like hell.

## Process

[Merck wins cyber-insurance lawsuit related to NotPetya attack](https://therecord.media/merck-wins-cyber-insurance-lawsuit-related-to-notpetya-attack/)  
"Having failed to change the policy language, Merck had every right to anticipate that the exclusion policy applied only to traditional forms of warfare." Yeah, malware running rampant is not an act of war. It's a design goal of the malware.

[Roblox Return to Service 10/28-10/31 2021](https://blog.roblox.com/2022/01/roblox-return-to-service-10-28-10-31-2021/)  
Roblox's HashiStack (Nomad, Consul and Vault) took a nap and Roblox had to tap Hashicorp to come in to help. The team did such a good job, "Roblox did not have a single significant production incident during the December surge."

[When SimCity got serious: the story of Maxis Business Simulations and SimRefinery](https://obscuritory.com/sim/when-simcity-got-serious/)  
I had no idea this was happening at the time. SimCity was a game changer in more than one market.

[Open source creates value, but how do you measure it?](https://github.blog/2022-01-20-open-source-creates-value-but-how-do-you-measure-it/)  
How do you measure it? What's the economic impact for your customers by you working upstream? What's the perception of your work upstream by your potential customers who already understand the benefit of open source? But, more importantly, do people want you working on their projects?

[SolarWinds Serv-U bug exploited in attacks in the wild](https://securityaffairs.co/wordpress/126933/security/solarwinds-serv-u-flaw.html)  
I really should've gone and worked on the Solarwinds core products when I was there. I'm not saying I'm some security expert or anything. But, I am really good at making sure my ass is covered. Oh and breaking things, I've broken a lot of stuff in my time.

## Tools

[Monitoring Linux Audit](https://engineering.teacherspayteachers.com/2022/01/17/monitoring-linux-audit.html)  
`auditd` in the house!

[SUSE announces CentOS-like Liberty Linux](https://www.theregister.com/2022/01/20/suse_liberty_linux/)  
"SUSE will build the software using its own [Open Build Service](https://openbuildservice.org/) tooling. All of the user-land of the new offering will be built from Red Hat's official Source RPMs (SRPMs), with the exception of the kernel. That comes from [SUSE's own](https://www.theregister.com/2018/06/25/suse_linux_enterprise_15/) SLE enterprise distribution, currently on version 15 SP3, but compiled using a Red Hat-compatible configuration."

[Free for developers](https://free-for.dev/)  
All the cool stuff you can get for FREE! Just not a [Google G Suite account anymore](https://thenextweb.com/news/google-gsuite-free-alternatives-analysis). I've considered getting off Google (I currently have two domain on Google accounts so this isn't a cheap venture). Also, paying money to feed information into an ad system isn't my idea of fair.

[Introducing vAPI – an open source lab environment to learn about API security](https://portswigger.net/daily-swig/introducing-vapi-an-open-source-lab-environment-to-learn-about-api-security)  
ATTACK!!!

[Dewan learns Kafka - architecture principles and recent changes](https://dewanahmed.com/dewan-learns-kafka-architecture-principles)  
My friend Dewan is diving into Kafka. A good read.

[4 Big GitOps Moments of 2021](https://www.weave.works/blog/2021-gitops-moments)  
The inception of [OpenGitOps](https://opengitops.dev/) and the establishment of [GitOps Principles](https://opengitops.dev/#principles) are big deals. Cool to be a tiny part of this.

[mattermost/focalboard](https://github.com/mattermost/focalboard)  
"Focalboard is an open source, self-hosted alternative to Trello, Notion, and Asana."

[khuedoan/homelab](https://github.com/khuedoan/homelab)  
I always find these solutions interesting. "My self-hosting infrastructure, fully automated from empty disk to operating services"

## DevOps'ish Tweet of the Week

[![Angie Jones (@techgirl1908 on Twitter) "If they ask, you ask for a range. Or answer with your salary expectations. *Option 1* Them: How much do you currently make? You: What's the salary range for this position? *Option 2* Them: How much do you currently make? You: I'm looking for something between $X - $Y"](https://shortcdn.com/devopsish/253-devopsish-tweet-of-the-week.webp)](https://twitter.com/techgirl1908/status/1483668538372075530)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/253/notes.md) to see what didn't make it to the newsletter but are still worth your time.
