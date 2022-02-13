+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-10-03T07:00:00Z
description = ["The week before KubeCon, special announcement this week, Slack DNS issues, HTTPS is everywhere, Competitive Compatibility, PostgreSQL 14, Kube-fledged, and more"]
draft = false
slug = "237"
tags = ["Kubernetes", "DevOps", "Cloud Native", "data", "cloud", "time", "DevOps", "news", "code", "container", "container images", "threst", "Rust", "Linux", "DNS", "Apple", "kube", "eBPF", "Linus Torvalds"]
title = "DevOps'ish 237: The week before KubeCon, special announcement this week, Slack DNS issues, HTTPS is everywhere, Competitive Compatibility, PostgreSQL 14, Kube-fledged, and more"

+++

It has been a stressful and challenging past few weeks. But, it's all worth it in the end. My KubeCon schedule is taking shape. I'll be in L.A. starting Saturday, so if you're around, feel free to ping me to chat or hang out. I mentioned on the CNCF Ambassador call last week something I've noticed recently. Thanks to the pandemic, my already sometimes tough to manage anxiety around large crowds in confined spaces is WAY worse. I'll be in a corner or room during keynotes. If you have anxiety around large crowds too, feel free to come watch keynotes with me from a safe space.

We're doing something a little different on [Red Hat Livestreaming](https://red.ht/livestreaming) next week. I'm going to sit in the hot seat for once and get interviewed by the esteemed [Stu Miniman](https://twitter.com/stu). There will be a special announcement during the stream, so be sure to check it out at [4 PM ET on October 6th](https://youtu.be/VLoeHoL0HdE?utm_source=newsletter&utm_medium=237&utm_campaign=devopsish).

## People

[In-person Zoom is the new norm for many workers returning to the office](https://www.washingtonpost.com/technology/2021/09/27/return-to-work-in-person-hybrid/)  
If you're in this position, I feel for you. I get it, some folks don't have homes conducive to working from. I'm lucky as all get out that I can have a basement finishing project in flight and still have space for an office I can close the door to. I also feel like there has to be a better way.

[Preventing Data Exfiltration with eBPF](https://goteleport.com/blog/preventing-data-exfiltration-with-ebpf/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish)  
Keep your data protected by developing security policies that target specific processes with eBPF. *SPONSORED*

[How we're silencing women in tech, one tweet at a time](https://www.techrepublic.com/article/how-were-silencing-women-in-tech-one-tweet-at-a-time/)  
"'When you are constantly getting these comments, you start to think, 'Okay. Maybe they are true,' she told me. 'You question yourself and you doubt yourself like, 'Maybe they're right. Maybe I'm not cut out for this.' So women like her are speaking less or not at all."

[Only 2.2% of VC $ went to female-founded startups in 2021...lowest in 5 years](https://twitter.com/jayleejanet/status/1443317135648854020)  
This is despicable. It proves you don't have to be smart to be an investor.

[Suspected Chinese state-linked threat actors infiltrated major Afghan telecom provider](https://therecord.media/suspected-chinese-state-linked-threat-actors-infiltrated-major-afghan-telecom-provider/)  
China's infiltrations are definitely an effort to maintain some type of surveillance on the terrorist threat along their border. This is par for the course for intelligence agencies the world over. I imagine the US and its allies are tapped in too.

[Linus Torvalds on Community, Rust and Linux's Longevity](https://thenewstack.io/linus-torvalds-on-community-rust-and-linuxs-longevity/)  
"It comes up when people talk about the possibility of writing some Linux kernel modules using Rust. “From a technical angle, does that make sense?” Torvalds asked. 'Who knows. That's not the point. The point is for a project to stay interesting — and to stay fun — you have to play with it.'"

[Trump pushing Microsoft to buy TikTok was 'strangest thing I've ever worked on,' says Satya Nadella](https://www.theverge.com/2021/9/27/22697565/microsoft-ceo-satya-nadella-tiktok-acquisition-drama-strangest-thing)  
Yeah, after reading this it is strange af.

## Process

[The Speed of Time](https://www.brendangregg.com/blog/2021-09-26/the-speed-of-time.html)  
"For Linux I've been recommending the faster tsc clocksource for years, altough I'm not a processor vendor so I can't make assurances about tsc issues of clock drift."

[Management platform for Infrastructure as Code Automation and Collaboration](https://app.env0.com/login?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and quality of life features. [Free Demo](https://app.env0.com/login?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Slack Outage due to DNS](https://status.slack.com/2021-09-30)  
If it were only 1% then why were so many affected? Got any DNS caching turned on? That'll screw you during an incident like this. Also, it's always DNS.

[WatchGuard Threat Lab Reports 91.5% of Malware Arrived over Encrypted Connections in Q2 2021](https://www.watchguard.com/wgrd-news/press-releases/watchguard-threat-lab-reports-915-malware-arrived-over-encrypted)  
This comes on the heels of [the news that EFF is discontinuing its HTTP Everywhere](https://www.eff.org/deeplinks/2021/09/https-actually-everywhere) tool. Because HTTPS really is everywhere, even malware.

[Competitive Compatibility: Let's Fix the Internet, Not the Tech Giants](https://cacm.acm.org/magazines/2021/10/255710-competitive-compatibility/fulltext)  
What does the venerable ANSI/SAE J56-compliant plug (the old cigarette lighter now universal charging port) have to do with a better solution than breaking up big tech? Find out inside.

[Trusted Cloud Principles](https://trustedcloudprinciples.com/principles/)  
In some ways, this is great. In others, this is legal cover.

## Tools

[PostgreSQL 14 Released!](https://www.postgresql.org/about/news/postgresql-14-released-2318/)  
"PostgreSQL 14 brings a variety of features that help developers and administrators deploy their data-backed applications. PostgreSQL continues to add innovations on complex data types, including more convenient access for JSON and support for noncontiguous ranges of data. This latest release adds to PostgreSQL's trend on improving high performance and distributed data workloads, with advances in connection concurrency, high-write workloads, query parallelism and logical replication."

Spend less time debugging and more time shipping new features. Quickly find discrepancies between how you think your code is supposed to work and how it really works in the real world. Stop using 3 separate pillars and unify your view of production. [Sign up for free Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[How We Made Bracket Pair Colorization 10,000x Faster In Visual Studio Code](https://code.visualstudio.com/blogs/2021/09/29/bracket-pair-colorization)  
"[W]e reimplemented the extension in the core of VS Code and brought this time down to less than a millisecond - in this particular example, that is more than 10,000 times faster. The feature can be enabled by adding the setting `"editor.bracketPairColorization.enabled": true`."

[Recent Siri Changes Remove Call, Email, and Voicemail Features Used by Low Vision and Blind Users](https://www.macrumors.com/2021/09/29/siri-changes-features-removed/)  
Accessibility used to matter to Apple.

[Kube-fledged: Cache Container Images in Kubernetes](https://itnext.io/kube-fledged-cache-container-images-in-kubernetes-7880a00bab91)  
"**kube-fledged** is a Kubernetes add-on or operator for creating and managing a cache of container images directly on the worker nodes of a Kubernetes cluster. It allows a user to define a list of images and onto which worker nodes those images should be cached (i.e. pulled)." Thus drastically reducing container start times.

[The Definitive Guide to Kubernetes in Production](https://www.weave.works/blog/the-definitive-guide-to-kubernetes-in-production)  
Definitive doesn't necessarily mean complete (it generally does though). But, this is a great start towards definitive for sure.

[Raspberry Pi 4 8GB Gets Sneaky Update](https://www.tomshardware.com/news/pi-4-gets-updated-soc)  
Jeff Geerling spots an interesting change in the Raspberry Pi 4 8 GB system-on-chip.

[Are SSDs Really More Reliable Than Hard Drives?](https://www.backblaze.com/blog/are-ssds-really-more-reliable-than-hard-drives/)  
Challenge your assumptions.

[inguardians/peirates](https://github.com/inguardians/peirates)  
Peirates - Kubernetes Penetration Testing tool

[containers/youki](https://github.com/containers/youki)  
A container runtime written in Rust

[juanfont/headscale](https://github.com/juanfont/headscale)  
An open source, self-hosted implementation of the Tailscale control server

[facebookincubator/below](https://github.com/facebookincubator/below)  
A time traveling resource monitor for modern Linux systems

## DevOps'ish Tweet of the Week

[![Alyssa Miller 👑 Duchess of Hackington (@AlyssaM_InfoSec) on Twitter: "OWASP Top 10:2024 A10: Meatbags, A9: Meat Popsicles, A8: Carbon and Water Based Oxygen Suckers, A7: Personage, A6: Intelligent Bipeds, A5: Mortals, A4: Hominids, A3: Homo sapiens, A2: People, A1: Humans"](https://shortcdn.com/file/devopsish/237-devopsish-tweet-of-the-week.png)](https://twitter.com/AlyssaM_InfoSec/status/1442566442755440644)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/237/notes/) to see what didn't make it to the newsletter but are still worth your time.
