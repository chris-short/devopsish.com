+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]

date = 2022-01-16T03:00:00Z
description = ["5G update, pink slips for the unvaccinated, Apache stifled by out of date software still in use, Canon's eWaste, Security Obstructionism (SecObs) Market, tracing traffic in Kubernetes, and more"]
draft = false
slug = "252"
tags = ["security", "Kubernetes", "5G", "data", "practices", "time", "Lastpass", "platform", "obstructionism", "SecObs", "market", "API", "C-band", "cluster", "unvaccinated", "Google", "Apache", "Canon", "ink", "Honeycomb", "diagnosis", "remediation", "workloads", "AWS", "GitOps", "Flux"]
title = "DevOps'ish 252: 5G update, pink slips for the unvaccinated, Apache stifled by out of date software still in use, Canon's eWaste, Security Obstructionism (SecObs) Market, tracing traffic in Kubernetes, and more"

+++

DevOps'ish is brought to you by [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
"Stop Letting Complexity Slow You Down"  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

[Last week](https://devopsish.com/251), I reported the back and forth with Verizon's and AT&T's 5G efforts on the old C-band spectrum. This frequency band is also used to tell airplanes where the ground is as they're on final approaches and landings, and [the FAA has been frantically working](https://www.bloomberg.com/news/articles/2022-01-14/u-s-faa-issues-first-aircraft-specific-limits-due-to-5g-signals) to prevent a delay in the 5G rollouts of two of the US's largest carriers.

Meanwhile, I'll be getting introduced to [this new service on January 19th as Verizon](https://www.pcmag.com/opinions/verizon-5g-is-changing-january-19-what-you-need-to-know) flips on their 5G network based on this frequency band on January 19th. This could also mean a shift in the works in terms of how I consume the internet. Right now, it's a Comcast Business link. I would prefer not to be a Comcast customer. Home 5G, [Project Kuiper](https://www.aboutamazon.com/news/innovation-at-amazon/amazon-marks-breakthrough-in-project-kuiper-development), and ~~Starlink~~ [Cat bed based internet](https://www.smithsonianmag.com/smart-news/outdoor-cats-are-using-500-starlink-satellite-dishes-as-self-heating-beds-180979401/) are all looking like viable alternatives. Meanwhile, we learn that [5G could be used as a sensor itself](https://acris.aalto.fi/ws/portalfiles/portal/20768974/sigg_et_al_VT_conf.pdf).

## People

[you feel like shit](https://youfeellikeshit.com/)  
A site that helps you figure out why.

[no hello](https://nohello.net/)  
"Imagine calling someone on the phone, going hello! then putting them on hold... 🤦‍♀️"

[Nike, Columbia Sportswear plan to start firing unvaccinated employees](https://www.oregonlive.com/business/2022/01/nike-columbia-sportswear-plan-to-start-firing-unvaccinated-employees.html)  
Not just for [healthcare providers anymore](https://www.cbsnews.com/news/mayo-clinic-fires-700-unvaccinated-employees/), companies have no time for COVID-19 shenanigans and are exposed to massive risk by having the unvaccinated in their midst. I can't wait until this happens in the tech sector en masse. Take all the trash out in one fell swoop. All it takes is insurance companies saying they'll charge employers a penalty if they don't have an acceptable vaccination mandate. This is going to be fun.

[Toxic Culture Is Driving the Great Resignation](https://sloanreview.mit.edu/article/toxic-culture-is-driving-the-great-resignation/)  
Good. But, mobility alone won't fix the problem. It'll sure make the bad actors better known though. Like, I know better than to work for any of the Quicken Loans family of businesses. They're generally toxic cesspools and I've kinda called them out on it. I'm on their naughty list now.

[LastPass is holding people's data hostage and it is an absolute disgrace that needs to stop](https://www.reddit.com/r/software/comments/s053t3/lastpass_is_holding_peoples_data_hostage_and_it/)  
A LastPass employee actually reached out to me about my shallow take on the subject of LastPass. Little did they know [I've loathed LastPass for a long time](https://chrisshort.net/lastpass-sells-out-to-logmein/) now (2015). I don't know why I'm still surprised by actions like this.

[French Navy ATL2 MPA: Someone Just Lasered the Wrong Aircraft](https://www.navalnews.com/naval-news/2022/01/french-navy-atl2-mpa-someone-just-lasered-the-wrong-aircraft/)  
You're a fucking idiot if you point a laser at a surveillance aircraft. They can detect energy changes like being lazzed for targeting, you know, by lasers.

[Google Had Secret Project to ‘Convince’ Employees ‘That Unions Suck’](https://www.vice.com/en/article/v7d7j9/google-had-secret-project-to-convince-employees-that-unions-suck)  
Of course it did. The fact Google did this systemically is no surprise.

## Process

[The Security Obstructionism (SecObs) Market](https://swagitda.com/blog/posts/the-security-obstructionism-secobs-market/)  
"In security, obstructionism foments the dreaded Department of No, the begrudged gatekeeper, and the truculent Security Theatre1. Hence, I am introducing the term Security Obstructionism (SecObs)2, a category of tools, policies, and practices whose outcome is to impede or prevent progress for security’s (speculative) sake. I suspect the TAM (total addressable market) for SecObs is enormous and perhaps provides a more coherent understanding of security stacks than traditional market categories."

[5 Dashboard Design Best Practices](https://www.influxdata.com/blog/5-dashboard-design-best-practices/)  
A bad dashboard might be worse than bad data or no data at all.

[Apache Software Foundation warns its patching efforts are being undercut by use of end-of-life software](https://portswigger.net/daily-swig/apache-software-foundation-warns-its-patching-efforts-are-being-undercut-by-use-of-end-of-life-software)
"Despite the resource constraints inherent in a volunteer-staffed organization, Mark Cox said the ASF continues to achieve “a consistent process for how reported security issues are handled” among more than 350 diverse, independent Apache projects, and reserves the right to archive projects that fall short."

[10 real-world stories of how we’ve compromised CI/CD pipelines](https://research.nccgroup.com/2022/01/13/10-real-world-stories-of-how-weve-compromised-ci-cd-pipelines/)  
Installing Jenkins and a few of its multitude of plugins is akin to installing Wordpress to manage your code deployment process.

[Canon can’t get enough toner chips, so it’s telling customers how to defeat its DRM](https://arstechnica.com/tech-policy/2022/01/chip-shortage-has-canon-telling-customers-how-to-skirt-its-printer-toner-drm/)  
Why does ink need a chip? I mean seriously, think about that for a second. The printer consumes ink and applies it to paper. You can do this without a chip. This shows how bad recycling programs are for these printer cartridges. Even worse, imagine how many perfectly good chips are sitting in landfills right now that could be used for literally anything else.

## Tools

[Working with Kubernetes API - Resources, Kinds, and Objects](https://iximiuz.com/en/posts/kubernetes-api-structure-and-terminology/)  
"The Kubernetes API is a bit more advanced than just a bunch of HTTP endpoints thrown together. Therefore, it's vital to understand the Kubernetes API structure and be fluent in the terminology before trying to access it from code."

[Auto-Diagnosis and Remediation in Netflix Data Platform](https://netflixtechblog.com/auto-diagnosis-and-remediation-in-netflix-data-platform-5bcc52d853d1)  
"We have been working on an auto-diagnosis and remediation system called Pensive in the data platform to address these concerns. With the goal of troubleshooting failing and slow workloads and remediating them without human intervention wherever possible. As our platform continues to grow and different scenarios and issues can disrupt the workloads, Pensive has to be proactive in detecting broad problems at the platform level in real-time and diagnosing the impact across the workloads." 🤯🤯🤯

[Tracing the path of network traffic in Kubernetes](https://learnk8s.io/kubernetes-network-packets)  
"TL;DR: In this article, you will learn how packets flow inside and outside a Kubernetes cluster. Starting from the initial web request and down to the container hosting the application."

[Top 10 security best practices for securing backups in AWS](https://aws.amazon.com/blogs/security/top-10-security-best-practices-for-securing-backups-in-aws/)  
"I showed you the top ten security best practices and controls to protect your backup data in AWS. I encourage you to use these best practices to design and implement a backup and recovery strategy and architecture with multiple layers of controls that scales and achieves your business needs."

[Detect crashes in your Kubernetes cluster using kwatch and Slack](https://kwatch.dev/blog/detect-crashes-in-your-cluster-using-kwatch-and-slack)  
"In this tutorial, I will help you setup and deploy kwatch on your Kubernetes cluster. Plus, integrate with Slack to get notified on a channel when there is a crash in your apps."

[GitOps model for provisioning and bootstrapping Amazon EKS clusters using Crossplane and Flux](https://aws.amazon.com/blogs/containers/gitops-model-for-provisioning-and-bootstrapping-amazon-eks-clusters-using-crossplane-and-flux/)  
"In this blog post (Part 2), I will present the details of implementing the same use case using Flux for GitOps-based deployment."

[Pull Request Generator - ApplicationSet Controller](https://argocd-applicationset.readthedocs.io/en/stable/Generators-Pull-Request/#pull-request-generator)  
I'm curious what y'all think about this. Anyone using this in production?

[Shogan/kube-chaos](https://github.com/Shogan/kube-chaos)  
"A chaos engineering style game where you seek out and destroy Kubernetes pods, twinstick shmup style."

[v4d1/SpoofThatMail](https://github.com/v4d1/SpoofThatMail)  
Bash script to check if a domain or list of domains can be spoofed based in DMARC records

## DevOps'ish Tweet of the Week

[![Ian Coldwater 📦💥 (@IanColdwater on Twitter) "It's frankly miraculous that the Internet works at all"](https://shortcdn.com/file/devopsish/252-devopsish-tweet-of-the-week.webp)](https://twitter.com/IanColdwater/status/1480595046449700864)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/252/notes/) to see what didn't make it to the newsletter but are still worth your time.
