+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2020"]
date = 2020-12-27T07:00:00Z
description = "Solarwinds supply chain compromise worsens (bonus DLL deep dive), Apple outages, shady GoDaddy, GitOps improves security, ARM, diffs, streams, and more"
draft = false
slug = "198"
tags = ["DevOps", "security", "cloud", "cloud native", "Apple", "Linux", "systems", "Solarwinds", "supply chain", "compromise", "Microsoft", "COVID-19", "Intel", "theory", "DLL", "threat", "GitOps", "Kubernetes", "ARM", "trace", "syscalls", "gopher", "namespaces", "diffs", "streams"]
title = "DevOps'ish 198"

+++

Remember last week how I said things would be punchier? Well, I updated the [DevOps'ish Solarwinds supply chain compromise Index](https://devopsish.com/solarwinds-supply-chain-compromise/). By the way, Microsoft says it was, "used by a different threat actor."

I wrote the parts of the newsletter below, which are probably helpful. ¯\\\_(ツ)\_/¯

The past few days have been incredibly challenging mentally and physically. I'm not sure if I would do it all the same way again. Sadly, I think I'm going to have to sideline myself a little more next year. The good news is, I get to try again next year. For that, I am truly thankful. The holidays, especially religious-based ones, are challenging for me. I have a challenging relationship with religion in general. That's for a different blog though. For those celebrating holidays the past few weeks and the weeks ahead, I wish you all the best.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=198)

## People

[Reverse Engineering the source code of the BioNTech/Pfizer SARS-CoV-2 Vaccine](https://berthub.eu/articles/posts/reverse-engineering-source-code-of-the-biontech-pfizer-vaccine/)  
"In this post, we’ll be taking a character-by-character look at the source code of the BioNTech/Pfizer SARS-CoV-2 mRNA vaccine." Damn. That's awesome.

[Our Digital Lives Drive a Brick-and-Mortar Boom in Data Centers](https://www.nytimes.com/2020/12/22/business/data-storage-centers-coronavirus.html)  
"Developers and investors see more opportunities in commercial real estate as businesses and consumers gobble up more data."

[The Secret History of the First Microprocessor, the F-14, and Me](https://www.wired.com/story/secret-history-of-the-first-microprocessor-f-14/)  
There was the Intel 4004, then there was this monster. This is a great story that I'm glad has come to light.

[GoDaddy Employees Were Told They Were Getting a Holiday Bonus. It Was Actually a Phishing Test.](https://coppercourier.com/story/godaddy-employees-holiday-bonus-secruity-test/)  
I haven't used GoDaddy in a LONG time. You shouldn't either.

[How Claude Shannon’s Information Theory Invented the Future](https://www.quantamagazine.org/how-claude-shannons-information-theory-invented-the-future-20201222/)  
"The heart of his theory is a simple but very general model of communication: A transmitter encodes information into a signal, which is corrupted by noise and then decoded by the receiver. Despite its simplicity, Shannon’s model incorporates two key insights: isolating the information and noise sources from the communication system to be designed, and modeling both of these sources probabilistically." I've touched this work with my own hands. Pushing signals to and fro, multiplexing them, sending them over the air only to be disassembled on the other side.

## Process

[Analyzing Solorigate, the compromised DLL file that started a sophisticated cyberattack, and how Microsoft Defender helps protect customers](https://www.microsoft.com/security/blog/2020/12/18/analyzing-solorigate-the-compromised-dll-file-that-started-a-sophisticated-cyberattack-and-how-microsoft-defender-helps-protect/)  
Take a deep dive into the DLL toppling security apparatus across the globe. Also, it was “used by a different threat actor.” Oh good… Multiple agencies knew about it and exploited it. Sit back and grab your popcorn and keep an eye on [the index](https://devopsish.com/solarwinds-supply-chain-compromise/).

[How GitOps Improves the Security of Your Development Pipelines](https://www.weave.works/blog/how-gitops-improves-security-development-pipelines)  
“GitOps is usually discussed in terms of boosting developer velocity. But another benefit – one that doesn’t always get as much attention – concerns its potential to improve security.” To go fast, you have to go safely and securely. Otherwise, you’re introducing risk. You’re human. Let a computer and the knowledge of as many viable sources as possible do the safety and security for you. But that in the GitOps toolchain and maybe, you won’t end up like Solarwinds (aka on the front page of news sources the world over).

[Apple Setup Issues: Apple Watch Verification Failed, HomePod Stuck on Configuring](https://www.macrumors.com/2020/12/25/apple-verification-failed-stuck-configuring/)  
How's that switch from Mesos to Kubernetes coming? Oh... Distributed systems are hard.

[Executable PNGs](https://djharper.dev/post/2020/12/26/executable-pngs/)  
Imagine this concept with a tight bit of Go or Rust logic. Large PNGs would be odd but not easily detected as suspicious without some actual compute looking into it.

[Linux Hardening Guide](https://madaidans-insecurities.github.io/guides/linux-hardening.html)  
I would have killed for this web site in the early 2000s. Many arguments and old ways could've been avoided.

## Tools

[Active-Active PostgreSQL Federation on Kubernetes](https://info.crunchydata.com/blog/active-active-postgres-federation-on-kubernetes)  
This is kinda a dream come true if you build this right (the article doesn't mention the physics involved: latency, for example). But, it does cover HA in all locations with a single operator so that's dope.

**We need your voice!**

In partnership with the team at ClearPath Strategies, [Honeycomb.io](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish) is collecting insights for changes in software development and operation practices across our industry. How do you see the world and what your team is doing?

[Take the survey](https://clearpathstrategies.sjc1.qualtrics.com/jfe/form/SV_cMAECZ6jv5wmjrL?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=software-production-excellence-survey-clearpath-devopsish&utm_adgroup=) for a chance to win $500 from Apple, HelloFresh, or Fender. *SPONSORED*

[How an obscure British PC maker invented ARM and changed the world](https://arstechnica.com/features/2020/12/how-an-obscure-british-pc-maker-invented-arm-and-changed-the-world/)  
2021 is going to be an ARM filled year, to say the least.

[How to Trace Linux System Calls in Production with Minimal Impact on Performance](https://pingcap.com/blog/how-to-trace-linux-system-calls-in-production-with-minimal-impact-on-performance)  
"This blog post introduces perf and traceloop, two commonly used command-line tools, to help you trace system calls in a production environment." Because running strace in prod is a last resort.

[GopherCon 2020: Angelica Hill - Anyone Can Be A Gopher!](https://www.youtube.com/watch?v=WNBzMtIaXwE&feature=share)  
I'm not a coder by trade but I am a Gopher (language not protocol). It's one of the most welcoming communities out there.

[Evolving Container Security With Linux User Namespaces](https://netflixtechblog.com/evolving-container-security-with-linux-user-namespaces-afbe3308c082)  
In this post, we describe how Titus agents leverage user namespaces to improve the overall security of the Titus agent fleet.

[2020 Time Zone Database (tzdata) changes](https://developers.redhat.com/blog/2020/12/25/2020-time-zone-database-tzdata-changes/)  
I'm fascinated by the concept of time. How it is truly a mangled thing by humans to fit our will and wreak havoc in our systems.

[CrowdStrike/CRT](https://github.com/CrowdStrike/CRT)  
"This tool queries the following configurations in the Azure AD/O365 tenant which can shed light on hard to find permissions and configuration settings in order to assist organizations in securing these environments."

[so-fancy/diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)  
Good-lookin' diffs. Actually… nah… The best-lookin' diffs.

[owncast/owncast](https://github.com/owncast/owncast)  
"Take control over your live stream video by running it yourself. Streaming + chat out of the box."

[stolk/freqtop](https://github.com/stolk/freqtop)  
Monitor for the CPU Frequency Scaling under Linux.

## DevOps'ish Tweet of the Week

[![DevOps'ish 198 Tweet of the Week](["https://shortcdn.com/file/devopsish/198-devopsish-tweet-of-the-week.png)](https://twitter.com/askvirginia/status/1340431843422855172)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/198/notes/) to see what didn't make it to the newsletter.
