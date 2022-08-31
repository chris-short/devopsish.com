+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-05-16T07:00:00Z
description = ["What is DevOps eBook, Linux on the Desktop, racist AI, Darkside goes dark, systemd 💪, AWS free tier, lots of tools, and more"]
draft = false
slug = "218"
tags = ["DevOps", "cloud", "Cloud Native", "Kubernetes", "GitOps", "systemd", "security", "What is DevOps", "KubeCon", "OpenShift.TV", "Lambda School", "GitOps Con", "Linux on the Desktop", "security", "scale", "SSH", "open source", "Microsoft", "Red Hat", "Apple", "Google", "observability", "Windows eBPF", "Rust", "OpenShift", "CNCF", "Linus Torvalds", "AWS", "BGP", "kubectl", "AI"]
title = "DevOps'ish 218: What is DevOps eBook, Linux on the Desktop, racist AI, Darkside goes dark, systemd 💪, AWS free tier, lots of tools, and more"

+++

Finally, an average week, expect weeks are anything but “normal” these days. This past week marked the [first birthday of OpenShift.TV](https://www.openshift.com/blog/its-been-a-full-year-since-we-launched-openshift-tv) (which is for all intents and purposes) what I’ve been working on the past year. 540 hours of content that [has been archived](https://www.youtube.com/user/rhopenshift) to help folks tackle all kinds of issues with Kubernetes, OpenShift, and a host of other open source projects. I bet we’ve touched on [etcd’s thirst for low latency](https://www.ibm.com/cloud/blog/using-fio-to-tell-whether-your-storage-is-fast-enough-for-etcd), having to remind people to [use DHCP for IPI installations](https://www.twitch.tv/videos/729330449), and have come up with as many "stage" names; it might total up to about 540 times too. It’s been worth it. The value it brings to others is beyond what we were hoping for.

But, this week was the week of, "What are you going to do when things go back to being in person?" I’m not sure what that looks like. It could mean I bring a portable studio with me everywhere I go or something that stays a mostly at-home job with trips to cover events occasionally. I don’t know what anything will look like in two weeks from now, let alone six months from now. I know that we launched a live streaming effort a year ago, and [I went through six mic arms in the process](https://chrisshort.net/desk-setup-january-2021/).

I’m going to enjoy this moment before we have to change it all up. We stood it all up in three weeks and iterated on it as we went. Embracing the DevOps principles I’ve learned from my work in the past has probably been the greatest joy in running it all. It’ll be the same routine when things start going back to what becomes whatever the new normal becomes. We’ll start where we think it’s going to go and land on what it becomes. That is the beauty of this industry; change is constant.

Speaking of change, the [**What is DevOps**](https://devopsish.com/what-is-devops/) page now features a free eBook for you to download. Grab a copy of What is DevOps; send it to your executive team if you think you’re not heading in the right direction. You can blame me; please blame me for maybe nudging folks towards hopefully positive change. The [**ePub**](https://shortcdn.com/devopsish/What_is_DevOps_eBook.epub?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_218) and [**PDF**](https://shortcdn.com/devopsish/What_is_DevOps_eBook.pdf?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_218) editions are available NOW!

Note: All [KubeCon EU 2021 talks are available on YouTube](https://youtube.com/playlist?list=PLj6h78yzYM2MqBm19mRz9SYLsw4kfQBrC&utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_218)

## People

[Three students sue coding bootcamp Lambda School alleging false advertising and financial shenanigans](https://techcrunch.com/2021/05/13/lambda-school-lawsuits/)  
This is really ugly. These schools playing fast and loose with people's lives have something coming.

[Teleport](https://goteleport.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_218) allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments. I heard it was pretty cool and they reached out to be sponsors but, I don't have any ad copy this week to share, so hopefully, this works? I doubt it will. They'll probably be like, "Oh, we want an extra week." and I'll all be like, "No. Because I already have given you two." and they're going to be like, "Okay, awesome." Then I'll be like, "It might not be right now... Logistics... Physics... Space... Time..." Go check out [Teleport](https://goteleport.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_218). *SPONSORED*

[Microsoft Releases Azure Static Web Pages into General Availability](https://www.infoq.com/news/2021/05/azure-static-web-apps-ga/)  
Might this be where I land after Netlify?

[97 Things Every Cloud Engineer Should Know](https://www.redhat.com/en/engage/things-every-cloud-s-202103201521)  
Red Hat is offering this book for "free" now. It's a good book and I wrote part of it, so if you haven't gotten it yet, now you can.

[Shopify Employees Say Noose Emoji Found in Slack; CEO Silenced Debate](https://www.businessinsider.com/shopify-employees-noose-emoji-slack-ceo-tobi-lutke-silenced-debate-2021-5)  
This doesn't surprise me anymore. It's only affirming what I already know.

[GitOpsCon EU 2021 - First time for everything](https://www.weave.works/blog/gitopscon-eu-2021-first-time-for-everything)  
"Organized by the CNCF GitOps Working Group and sponsored by us and our friends at Red Hat, the event showcased an amazing panel of GitOps evangelists and practitioners who covered a range of topics for those still contemplating GitOps adoption to experienced GitOps practitioners who manage enterprise scale implementations."

[How to learn and stay up to date with DevOps and Cloud Native technologies](https://itnext.io/how-to-learn-and-stay-up-to-date-with-devops-and-cloud-native-technologies-44526658a4fb)  
"It is important to relay on proven information sources and find the ones that resonate with you the most. Here is a very abbreviated list of resources that I tend to come back to over and over to hone my practical skills."

[Linus Torvalds on why desktop Linux sucks](https://www.youtube.com/watch?v=Pzl1B7nB9Kc)  
Holy shit, I agree with Linus Torvalds. Wow! Like, not the delivery but on principle.

[Image classification algorithms at Apple, Google still push racist tropes](https://algorithmwatch.org/en/apple-google-computer-vision-racist/)  
"Automated systems from Apple and Google label characters with dark skins 'Animals'."

## Process

[Darkside ransomware gang says it lost control of its servers & money a day after Biden threat](https://therecord.media/darkside-ransomware-gang-says-it-lost-control-of-its-servers-money-a-day-after-biden-threat/)  
It could be a ruse but, it is way more likely the full weight and force of the US intelligence apparatus has been applied to regain loses and identify all involved. But, it's even more likely this event becomes a kinetic one given the impact and independent operations. Also, stop hoarding if you're impacted by this.

[Guide to Effective Feature Management [O'Reilly]](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)
Testing in production sounds scary, right? What if you could safely ship features faster?
Adopt feature management practices to accelerate release cycles and deploy every 6 hours, instead of every 6 weeks. [Check out the new book](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) from O'Reilly and LaunchDarkly CTO & Cofounder John Kodumal. *SPONSORED*

[Systemd Service Strengthening](https://www.linuxjournal.com/content/systemd-service-strengthening)  
"[W]e are going to explain how to improve the security of a systemd service. But first, we need to step back for a moment.  With the latest releases systemd has implemented some interesting features relating to security, especially sandboxing. In this article we are going to show step-by-step how to strengthen services using specific directives, and how to check them with the provided systemd suite."

[Ford will start rolling out major over-the-air software updates to its vehicles this year](https://www.theverge.com/2021/5/13/22432770/ford-ota-software-update-amazon-alexa?scrolla=5eb6d68b7fedc32c19ef33b4)  
"The automaker says it’s prepared to rapidly increase the number of vehicles capable of receiving software updates, with the goal of producing 33 million vehicles with the capability by 2028." That's a huge scale. The future really is here.

[Security keys are now supported for SSH Git operations](https://github.blog/2021-05-10-security-keys-supported-ssh-git-operations/)  
`ssh-keygen -t ecdsa-sk -C <email address>`  
`Generating public/private ecdsa-sk key pair.`  
`You may need to touch your authenticator to authorize key generation.`

## Tools

[Please fix the AWS Free Tier before somebody gets hurt](https://cloudirregular.substack.com/p/please-fix-the-aws-free-tier-before)  
It's easier and cheaper for AWS to issue a refund than to deliver cost data in real time. That's why you can have [a $2700 bill before you know anything happened](https://chrisshort.net/the-aws-bill-heard-around-the-world/).

Take a deep dive into observability at [o11ycon+hnycon](https://o11ycon-hnycon.io/devopsish/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=devopsish&utm_adgroup), a two-day virtual conference on the future of shipping software. Happening June 9-10, this highly interactive event connects you and your peers to explore cutting-edge capabilities and unique outcomes that define observability. You’ll also hear from top Honeycomb customers and observability experts– including Corey Quinn, Chief Cloud Economist of The Duckbill Group, and Nora Jones, CEO of Jeli!

Guess less and know more with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Kubernetes: Apprentice Cookbook](https://dev.to/aveuiller/kubernetes-apprentice-cookbook-4j6h)  
"The aim of this article is to explain the most used concepts of Kubernetes relying on basic system administration concepts, then use some of these to deploy a simple web server and showcase the interactions between the different resources."

[Running BGP in large-scale data centers](https://engineering.fb.com/2021/05/13/data-center-engineering/bgp/)  
"We devised this routing design for our data centers to build our network quickly and provide high availability for our services, while keeping the design itself scalable. We know failures happen in any large-scale system — hence, our routing design aims to minimize the impact of any potential failures." Which is exactly what BGP is great at.

[Making eBPF work on Windows](https://cloudblogs.microsoft.com/opensource/2021/05/10/making-ebpf-work-on-windows/)  
"We are announcing this now while the project is still relatively early in development because our goal is to work in collaboration with the robust eBPF community to make sure that eBPF works great on Windows, and everywhere else."

[Learn Rust - Rust Programming Language](https://www.rust-lang.org/learn)  
The official Rust learning resource.

[1Password/vault-plugin-secrets-onepassword](https://github.com/1Password/vault-plugin-secrets-onepassword)  
Hashicorp Vault plugin that allows for the retrieval, creation, and deletion of items stored in a 1Password vault accessed by use of the 1Password Connect.

[nodeshift/nodeshift](https://github.com/nodeshift/nodeshift)  
CLI application for OpenShift Node.js deployment 🚀

[AkihiroSuda/lima](https://github.com/AkihiroSuda/lima)  
Lima: Linux-on-Mac ("macOS subsystem for Linux", "containerd for Mac"

[predatorray/kubectl-tmux-exec](https://github.com/predatorray/kubectl-tmux-exec)  
A kubectl plugin to control multiple pods simultaneously using Tmux

[jonnylangefeld/kubectl-mc](https://github.com/jonnylangefeld/kubectl-mc)  
Run kubectl commands against multiple clusters at once

[ossrs/srs](https://github.com/ossrs/srs)  
SRS is a simple, high efficiency and realtime video server, supports RTMP/WebRTC/HLS/HTTP-FLV/SRT/GB28181.

## DevOps'ish Tweet of the Week

[![@nicolefv on Twitter: Why do we listen to people who have notably scammed people out of billions of dollars and ::checks notes:: whose entire business model relies on people returning to an office? My dude your passive aggressive hot take is bad](https://shortcdn.com/devopsish/218-devopsish-tweet-of-the-week.png)](https://twitter.com/nicolefv/status/1392851719797673992)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/218/notes/) to see what didn't make it to the newsletter but are still worth your time.
