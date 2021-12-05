+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-06-27T07:00:00Z
description = ["Take your time off, Bryan Liles on a mission, John McAfee dead, Dell SupportAssist assisting the wrong people, AWS DNS hijack, Istio 1.10, Intel to make RISC-V chips, and more"]
draft = false
slug = "224"
tags = ["cloud", "DevOps", "cloud native", "Linux", "open source", "Kubernetes", "DNS", "release", "Microsoft", "Istio", "localhost", "Google", "John McAfee", "experimentation", "platform", "development", "Red Hat", "production", "kernel", "AWS", "VPN", "observability", "sidecar", "fzf", "Intel", "RISC-V", "SiFive", "GitOps"]
title = "DevOps'ish 224: Take your time off, Bryan Liles on a mission, John McAfee dead, Dell SupportAssist assisting the wrong people, AWS DNS hijack, Istio 1.10, Intel to make RISC-V chips, and more"

+++

Let me be someone to remind you to take some time off (if you can). As a family, we had many lessons learned from not being in our daily routines, setting, or location. This whole month has been a lot of optimizations in our household. All these learned from being outside our sixteen-month grooves. For example, I confirmed I needed glasses after a persistent headache went away then came back when I went back to work.

Time off is healthy. Do it (again, if you can or as soon as you're able). Go to another part of your state/country and do something different. You've earned it. You made it through some of the earth's darker days. Tell your people Chris Short said so. A few friends have come through Michigan lately. I invite you to fall through if you're able to safely. A surprising concentration of Kubernetes contributors lives here. We all seem to have a desire to show off this wonderland of ours. Case in point, I'll see you soon, [Pop](https://twitter.com/danpopnyc/status/1407834916000239618).

OpenShift.TV has a shiny new web page. Yes, the calendar is busted, I know. But, the [proper calendar is here](https://red.ht/streamcal) and is the source of truth for the channel. This is why we talk about the calendar [in our docs](https://github.com/cloud-platforms-streaming/streaming-docs) so much. In general, I have a feeling things are about to take off. A friend who started at Red Hat at the same time as me reminded me that "you've proven you're good enough to everyone but you." Until these kids are through college and hopefully set up well for the future with good heads on their shoulders, I'm always going to be competing against a younger but brighter version of myself. This is what drives me. So, I'm curious, what drives you?

## People

[The Science of Why Swearing Reduces Pain](https://www.wired.com/story/the-science-of-why-swearing-physically-reduces-pain/)  
If anyone wonders why I swear so much...

Easy steps on how to secure your Kubernetes cluster by installing [Teleport](https://www.youtube.com/watch?v=2diX_UAmJ1c), an open-source, identity-aware access proxy. *SPONSORED*

[Sole Black VMware principal engineer aims to diversify tech](https://searchsoftwarequality.techtarget.com/opinion/Sole-Black-VMware-principal-engineer-aims-to-diversify-tech)  
"VMware's only Black principal engineer talks about his rise in the cloud-native world, how to bring in a new generation of minorities and the future of technology."

[Twitter hired a team of tech critics to build ethical AI](https://www.protocol.com/workplace/twitter-ethical-ai-meta)  
Hopefully they're fairing better than Google.

[John McAfee dead of apparent suicide in Spanish jail after extradition order](https://www.cnbc.com/2021/06/23/john-mcafee-found-dead-after-spanish-court-oks-extradition-for-tax-crimes-.html)  John McAfee has been busy doing a lot of dirt lately and took his life after being cleared for extradition back to the United States.

[In Argentina, cheap government-issued netbooks sparked a musical renaissance](https://restofworld.org/2021/argentina-netbooks-music/)  
Never underestimate the power of technology in the hands of youth.

[How YouTube's rules are used to silence human rights activists](https://www.technologyreview.com/2021/06/24/1027048/youtube-xinjiang-censorship-human-rights-atajurt/)  
The system is built to protect the oppressor.

[The Linux Foundation Appoints Industry Veteran as Chief Marketing Officer](https://www.linuxfoundation.org/press-release/the-linux-foundation-appoints-industry-veteran-as-chief-marketing-officer/)  
Congrats to Derek Weeks!

[OpenGitOps - The Vendor-Neutral GitOps Project](https://www.weave.works/blog/opengitops-the-vendor-neutral-gitops-project)  
Congrats to Christian Hernandez!

## Process

[Preliminary Assessment: Unidentified Aerial Phenomena](https://www.dni.gov/files/ODNI/documents/assessments/Prelimary-Assessment-UAP-20210625.pdf)  
It's interesting to see a government grapple with inconsistencies in policies, procedures, reporting, stigmas, and not having the right tooling in place to make for consistent reporting. Sounds like a story or two I've told before. I intentionally buried the lede here: **ALIENS**!

[LaunchDarkly Named a Leader in Feature Management and Experimentation](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)
Discover why in its first Wave report dedicated to Feature Management And Experimentation, Forrester rates LaunchDarkly's platform a Leader among vendor features that enable development teams to reduce software release headaches and enable true testing in production. [Download today](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)! *SPONSORED*

[Dell SupportAssist bugs put over 30 million PCs at risk](https://www.bleepingcomputer.com/news/security/dell-supportassist-bugs-put-over-30-million-pcs-at-risk/)  
Holy smokes this is a big blast radius.

[A Review of the Linux Kernel's Release Signing and Key Management Policies](https://ostif.org/a-review-of-the-linux-kernels-release-signing-and-key-management-policies/)  
There are definitely some improvements our Linux kernel devs could make to their security practices.

[A terrible, horrible, no-good, very bad day at Slack](https://leaddev.com/technical-direction-strategy/terrible-horrible-no-good-very-bad-day-slack)  
When your massive infrastructure and HAproxy servers handles configuration changes like the ocean your incidents when come in waves.

[New DNS Name Server Hijack Attack Exposes Businesses, Government Agencies](https://www.darkreading.com/vulnerabilities---threats/new-dns-name-server-hijack-attack-exposes-businesses-government-agencies/d/d-id/1341377)  
"Researchers found a 'novel' class of DNS vulnerabilities in AWS Route53 and other DNS-as-a-service offerings that leak sensitive information on corporate and government customers, with one simple registration step." This will make your skin crawl a little.

[North Korean hackers breach South Korea's atomic research agency through VPN bug](https://therecord.media/north-korean-hackers-breach-south-koreas-atomic-research-agency-through-vpn-bug/)  
"Thirteen different IPs were seen abusing the vulnerability and accessing the organization's internal network." Can I recommend we prioritize VPN updates, upgrades, and 2FA.

## Tools

[Last Week in Azure](https://lastweekinazure.com/)  
Microsoft snark incoming.

In their upcoming O'Reilly book, [Honeycomb's](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) Charity Majors, Liz Fong-Jones, and George Miranda explain what constitutes good observability and show you how to make improvements from what you're doing today. They also provide practical do's and don'ts for migrating from legacy tooling, such as metrics monitoring and log management. Check out [a preview of their book](https://info.honeycomb.io/observability-engineering-oreilly-book-preview-0?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish&utm_adgroup), which includes introductory chapters focused on how observability differs from traditional approaches to managing software in production. *SPONSORED*.

[Istio 1.10: Q&A with Release Manager Sam Naser](https://www.infoq.com/news/2021/06/istio-1-10/)  
"On older versions of Istio the sidecar would intercept pod traffic and forward it to the user application on localhost. Users had to make sure their apps were listening on localhost for things to work. **Starting with 1.10, the sidecar will redirect traffic to eth0**. This change makes Istio work out of the box with popular stateful applications like Zookeeper or Elasticsearch, but to that end, user applications that are bound exclusively to localhost will have to be modified. We added a command to catch this automatically and make the migration easier." (emphasis mine)

[Microsoft left Linux users in the cold for almost an entire day](https://www.windowscentral.com/microsoft-left-linux-users-cold-almost-entire-day)  
I mean, we're kinda used to this.

[PipeWire Under The Hood](https://venam.nixers.net/blog/unix/2021/06/23/pipewire-under-the-hood.html)  
The post-pulseaudio era is here.

[Semgrep](https://parsiya.net/blog/2021-06-22-semgrep-the-surgical-static-analysis-tool/)  
"The Surgical Static Analysis Tool"

[4 Useful fzf Tricks for Your Terminal](https://pragmaticpineapple.com/four-useful-fzf-tricks-for-your-terminal/)  
fzf seems fun.

[Intel to Create RISC-V Development Platform with SiFive P550 Cores on 7nm in 2022](https://www.anandtech.com/show/16780/intel-to-create-riscv-development-platform-with-sifive-p550-cores-on-7nm-in-2022)  
If you can't beat 'em, join 'em.

[netlify-labs/netlify-plugin-lighthouse](https://github.com/netlify-labs/netlify-plugin-lighthouse)  
"Netlify Plugin to run Lighthouse on each build"

[Call-for-Code-for-Racial-Justice/Open-Sentencing](https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing)  
"To help public defenders better serve their clients, Open Sentencing shows racial bias in data such as demographics providing insights for each case"

## DevOps'ish Tweet of the Week

{{<tweet 1408528711830454293>}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/224/notes/) to see what didn't make it to the newsletter but are still worth your time.
