+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-03-22
description = "Kubernetes 1.18 is coming, curl gets JSON, istiod, install OKD4 on GCP, Tailscale, and more"
draft = false
slug = "172"
tags = ["DevOps", "Kubernetes", "cloud", "encryption", "security", "services", "open source", "systems", "clusters", "production", "performance", "Azure", "Datadog", "cloud native", "developers", "Tailscale", "WireGuard", "Istio", "curl", "Amazon"]
title = "DevOps'ish 172"

+++

There is [a line in Saving Private Ryan about griping](https://www.dailymotion.com/video/x4h4db5). There's a chain of command in the military and leadership voices its concerns up the chain, never down it. This week, I've been reaching up my chain of command in government to make sure that the people that are supposed to be leading right now are. I would encourage you to do the same. Some good news this week is that after announcing an initiative to harness a global computer network to contribute work towards pharmaceutical drugs to combat COVID-19, [Folding@Home has seen a 1200% increase in computers actively contributing to the project](https://cointelegraph.com/news/foldinghome-surpasses-400-000-users-amid-crypto-contribution). I set up four systems to run Folding@Home this week as part of this effort. But, on Friday, I had to back down to three due to fan noise. I would also encourage you to donate any spare CPU and GPU cycles you have to the project. Together we can beat COVID-19.

## People

[Join SIG Scalability and Learn Kubernetes the Hard Way](https://kubernetes.io/blog/2020/03/19/join-sig-scalability/)  
"Contributing to SIG Scalability is a great way to learn Kubernetes in all its depth and breadth, and the team would love to have you join as a contributor. I took a look at the value of learning the hard way and interviewed the current SIG chairs to give you an idea of what contribution feels like."

[The world's fastest supercomputer identified chemicals that could stop coronavirus from spreading, a crucial step toward a treatment](https://www.cnn.com/2020/03/19/us/fastest-supercomputer-coronavirus-scn-trnd/index.html)  
"Summit, IBM's supercomputer equipped with the 'brain of AI,' ran thousands of simulations to analyze which drug compounds might effectively stop the virus from infecting host cells."

[Do Your D&I Efforts Include People with Disabilities?](https://hbr.org/2020/03/do-your-di-efforts-include-people-with-disabilities)  
"Although 90% of companies claim to prioritize diversity, only 4% consider disability in those initiatives"

[The Diffblue Developer Survey](https://www.diffblue.com/Education/research_papers/2019-diffblue-developer-survey/?utm_source=newsletter&utm_medium=email&utm_campaign=DevOpsIsh)  
What's wrong with software speed, quality, and cost? Oxford-based AI company Diffblue surveyed 300 developers to find out what the people who actually work with code have to say about testing, their pain points, and what's holding back DevOps in their organizations. *SPONSORED*

[D2iQ Leadership Update](https://d2iq.com/blog/d2iq-leadership-update)  
"Tobi Knaup, co-founder and current CTO, will share the helm with William Freiberg, current President and COO, as Co-CEO's for D2iQ."

[Not All Diverse Hiring Is Created Equal](https://peopleofcolorintech.com/articles/not-all-diverse-hiring-is-created-equal/)  
"As with anyone who exists in a space of privilege, I have a responsibility to use my privilege to benefit others. But given that I am also a diverse individual, how can I do this successfully? Here are three things I've done, and will continue to do, with my unique position as a palatable diverse person in tech."

## Process

[Bringing encryption restrictions in through the back door](https://lwn.net/SubscriberLink/815137/fb7bca4bc7bf5f0b/)  
"EARN IT for short, is an attempt to force online service providers (e.g. Facebook, Google, etc.) to follow a set of 'best practices' determined by a commission, to combat the scourge of CSAM; the composition of that commission makes it clear that end-to-end encryption will not be one of those practices, but companies that do not follow the best practices will lose liability protection for their users' actions. It is, in brief, an attempt to force providers to either abandon true end-to-end encryption or face ruinous lawsuits—all without 'seeming' to be about encryption at all."

[A Minute on the Mic: DevOps Meaning](https://aminuteonthemic.com/episodes/episode4/)  
"Here's the 4th episode of A Minute on the Mic! Our question this round is 'What does DevOps mean to you?'"

[How Tailscale works](https://tailscale.com/blog/how-tailscale-works/)  
I installed Tailscale this week on several systems. It's a dead-simple WireGuard VPN implementation. I am a little wary of it, but it is handy to have 'direct' access to systems from anywhere. If installing WireGuard on everything were this easy, I'd have done it already.

[Checklist for building production-ready Kubernetes clusters](https://devopsi.sh/production-ready-c00e9)  
Like any aspiring Kubernaut, you've been building Kube clusters in a dev/test environment for months. But now it's time to flip the switch and move your baby into production so the masses can reach your services. How do you know you've set things up correctly and it's safe to launch into prod? Check out StackRox's checklist to help you prepare your containers and Kube clusters for production traffic. *SPONSORED*

[How to create a Kubernetes security policy](https://www.techrepublic.com/article/how-to-create-a-kubernetes-security-policy/)  
"If you're looking to take your Kubernetes security to the next level, you'll want to start working with pod security policies. Here's a quick introduction to this feature."

[NetApp cans Kubernetes and Cloud Volumes services on HCI. But what is waiting in the wings?](https://blocksandfiles.com/2020/03/20/netapp-nks-and-cloud-volumes-on-hci/)  
NetApp promises something cool that provides more value. Uh huh...

## Tools

[What's new in Kubernetes 1.18?](https://sysdig.com/blog/whats-new-kubernetes-1-18/)  
More features than you can shake a stick at! OIDC discovery, more support for Windows nodes, HPA tuning knobs, node topology manager and IPv6 going beta, Ingress v1.0, and more.

[curl write-out JSON](https://daniel.haxx.se/blog/2020/03/17/curl-write-out-json/)  
You can now get `curl` output in JSON!

[Introducing istiod: simplifying the control plane](https://istio.io/blog/2020/istiod/)  
"Consolidating Istio components into `istiod` simplifies mesh operability, while retaining Istio's powerful functionality"

[Fixing the Kubernetes clusterfuck](https://fosdem.org/2020/schedule/event/kubernetes/)  
Understanding security from the kernel up by Kris Nova

[NASA to launch 247 petabytes of data into AWS – but forgot about eye-watering cloudy egress costs before lift-off](https://www.theregister.co.uk/2020/03/19/nasa_cloud_data_migration_mess/)  
"NASA needs 215 more petabytes of storage by the year 2025, and expects Amazon Web Services to provide the bulk of that capacity. However, the space agency didn't realize this would cost it plenty in cloud egress charges. As in, it will have to pay as scientists download its data."

[How To Install OKD4 on GCP (YouTube)](https://youtu.be/2UwQD0diUxk)

[How Container Networking Affects Database Performance](https://www.percona.com/blog/2020/03/18/how-container-networking-affects-database-performance/)  
Running databases in Kubernetes will result in a performance hit. How much of a hit depends a lot on your CNI of choice.

[Start Monitoring Azure DevOps Pipelines With Datadog](https://www.datadoghq.com/dg/monitor/azure-devops-monitoring/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=DevOpsish-Newsletter05&utm_content=AzureDevOps)  
Track Azure DevOps builds, releases, and code events with Datadog to understand how deployments impact app performance. Start monitoring quickly with auto-discovery for Azure services, so you can focus on improving the speed and agility of DevOps initiatives. Try Datadog today with a free 14-day trial. *SPONSORED*

[GitHub for mobile is now available](https://github.blog/2020-03-17-github-for-mobile-is-now-available/)  
At least there's a decent experience around all the discussions I used to have to go back to a computer for after work... Wait...

[mbbroberg/awesome-zoom-backgrounds](https://github.com/mbbroberg/awesome-zoom-backgrounds)  
A community repo for humors

[rudoi/cruster-api](https://github.com/rudoi/cruster-api)  
Order Domino's with Kubernetes

## DevOps'ish Tweet of the Week

{{< tweet 1239714843352903680 >}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/172/notes.md) to see what didn't make it to the newsletter.
