+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-09-05T07:00:00Z
description = ["Luke Hinds of Sigstore, three REALLY bad breaches/bugs, Docker's increasing desperation, Kubernetes mTLS, update your Operators, BGP & filesystem benchmarks, and more"]
draft = false
slug = "233"
tags = ["Kubernetes", "cloud native", "Luke Hinds", "Docker", "DevOps", "Operators", "BGP", "filesystem", "benchmarks", "mTLS", "security", "Sigstore", "systems", "infrastructure", "abstraction", "Terraform", "Ansible", "code", "CNCF", "GitOps", "IoT", "database", "nginx", "failure", "trust but verify"]
title = "DevOps'ish 233: Luke Hinds of Sigstore, three REALLY bad breaches/bugs, Docker's increasing desperation, Kubernetes mTLS, update your Operators, BGP & filesystem benchmarks, and more"

+++

I spent most of the week in a deteriorated state. Getting over the 12 injections last Friday took much longer than expected. It still amazes me how much work I can do with a disability, medications that slow me down, and a lack of sleep (Max started Kindergarten this week).

In a way, this is a lot like our systems, overtaxed by the increasing number of people using them. Ready to both be upgraded by an admin and taken down by a deluge of traffic at the same time (or worse, the opposite). Running along in a less than optimal state is pretty optimal for a lot of workloads. Sure, specific workloads will need certain kinds of hardware, and the software varies in those spaces. But, most of us are still using an abstraction of an abstraction of an abstraction (of an abstraction).

Like a top starting to lose its grip on centrifugal force, our systems run fine until they don't. Now, more than ever, we need to know how the systems are performing. What caused the slowdown? What sent the system sliding off the table into oblivion? Will it be able to be spinning like a top again soon? What do you do to pick it back up and having it moving like the top in Inception? All these questions are answered by the same question: How do we know if we're doing the right thing?

If you're doing the right things, the system will bounce back resiliently, knowing that maybe that AZ is having a bad day, the direct connect *isn't* the fastest route anymore due to an upstream provider mistake, or the system is in a state its never experienced before. If you're doing the right things, downtime is minimal. Services impacted are few. Dollars lost are low. This reminds me, if you don't know how much your organization is losing by any given system outage, you might not be doing the right thing.

But, how the team moves forward is a series of steps that eventually lead to the right thing to do to fix the system. If you're ever stuck troubleshooting, ask yourself, "How do we do what's right here?" Reset the situation in your mind. Find the point of failure by starting from the closest thing to the failure and eliminating what's working from the list. Verify they're working. Trust but verify. You can get to the right thing by process of elimination sometimes too.

## People

[What it’s like to be an older worker in tech](https://www.protocol.com/workplace/ageism-tech-workers)  
"[M]anagement should be careful about sanctioned post-work 'fun,' since a lot of it isn't very inclusive. 'There might be single moms who can't stay after work, or somebody with a disability who can't do whatever the fun physical game is.'"

[Declarative Cloud Infrastructure Management with Terraform](https://www.linode.com/content/declarative-cloud-infrastructure-management-terraform-linode/?utm_source=devopsish&utm_medium=newsletter_sponsorship&utm_campaign=newsletter_sponsorship-tldr-terraform&utm_content=ebook-terraform&utm_term=)  
100 Million Downloads and Over 5,000 Ecosystem Add-Ons later, Hashicorp has released the 1.0 version of Terraform. This eBook and audiobook will help you understand the underlying concepts of this infrastructure as a code tool and how it can be a significant resource when your cloud infrastructure hits critical mass. *SPONSORED*

[Reducing sugar in packaged foods can prevent disease in millions](https://www.massgeneral.org/news/press-release/Reducing-sugar-in-packaged-foods-can-prevent-disease-in-millions)  
Let's talk about REAL scale with REAL human impacts.

[KBE Insider (Ep 3): Luke Hinds](https://youtu.be/qV42CG4VM7Y)  
"We talk to Luke Hinds, Security Lead for Office of CTO, Red Hat, about his work on the Kubernetes Security Response Team (CNCF), Sigstore, and the Kubernetes Hackerone Bug Bounty program. Sigstore was the topic of a recent Wired story. Luke is involved in many other projects and hobbies. KBE Insider, hosted by CNCF Ambassador Chris Short and Developer Langdon White, lets you reach people deeply involved with Kubernetes, hear what they have to say, and interact with Kubernetes experts from across the globe."

[Chinese developers protested insanely long work hours. Now the nation's courts agree](https://www.theregister.com/2021/08/30/can_china_wean_itself_off/)  
"'996' culture and its assumption of six twelve hour days - without overtime - labelled abusive and illegal"

[It is time to say Goodbye!](https://www.linkedin.com/pulse/time-say-goodbye-nicolas-m-chaillan/)  
This is why I said, "When the government is done with me, I'm done with government work."

## Process

[Why are hyperlinks blue?](https://blog.mozilla.org/en/internet-culture/deep-dives/why-are-hyperlinks-blue/)  
"April 12, 1993 – Mosaic Version 0.13" The standard you create today could outlive you.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
Code, No Manual Processes. Automate Terraform tasks, reduce errors and drifts, improve security and auditability of your infrastructure. env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. *SPONSORED*

["Worst cloud vulnerability you can imagine" discovered in Microsoft Azure](https://arstechnica.com/information-technology/2021/08/worst-cloud-vulnerability-you-can-imagine-discovered-in-microsoft-azure/)  
"Access to a Cosmos DB instance's primary key is 'game over.' It allows full read, write, and delete permissions to the entire database belonging to that key. Wiz's Chief Technology Officer Ami Luttwak describes this as 'the worst cloud vulnerability you can imagine,' adding, 'This is the central database of Azure, and we were able to get access to any customer database that we wanted.'"

[T-Mobile hacker explains how he breached carrier's security](https://www.axios.com/t-mobile-hacker-john-binns-b23f8cdc-4c9e-45bf-adca-c16047108ffc.html)  
"'I was panicking because I had access to something big,'”' he wrote in Telegram messages to the Journal. 'Their security is awful.'" Good lord. It's T-Mobile's third breach in two years.

[Billions of devices impacted by new BrakTooth Bluetooth vulnerabilities](https://therecord.media/billions-of-devices-impacted-by-new-braktooth-bluetooth-vulnerabilities/)  
"[R]esearch found that the same Bluetooth firmware was most likely used inside more than 1,400 chipsets, used as the base for a wide assortment of devices, such as laptops, smartphones, industrial equipment, and many types of smart “Internet of Things” devices."

## Tools

[Docker Desktop no longer free for large companies: New 'Business' subscription is here](https://www.theregister.com/2021/08/31/docker_desktop_no_longer_free/)  
The blow hole sounds of desperation.

['Migrating from Docker to Podman' by Marcus Noble](https://marcusnoble.co.uk/2021-09-01-migrating-from-docker-to-podman/)
"Docker has recently announced that Docker Desktop will soon require a subscription and, based on the size of your company, may require a paid subscription. (It remains free for personal use)."

[Manage incidents directly from Slack 🧑‍🚒](https://consuming-macrospore.herokuapp.com/b?y=49q24eh2c4r3ce1gcoo3echi65h62opj74rjcdpic9ij6e3571im4dpocch2o8ji48t24q3keho76ehf5tp6urrkdhsisqbf5svnat3dbtpmutbicdijqrj5etpmopbkehin49j1dlo3mtbkdlfmqpb4d5qmqfb4clr6us3jd5pmg8g=?utm_source=devopsish&utm_campaign=233&utm_medium=newsletter)  
Rootly helps automate the tedious manual work like creating incident channels, searching for runbooks, documenting the postmortem timeline, and more. Teams sized 20 to 2000 manage hundreds of incidents daily and save thousands of engineering hours a year within Rootly. Get started in <5min or book a demo to learn more and get Starbucks ☕ on us! *SPONSORED*

[API deprecation in Kubernetes 1.22 that will impact your operators](https://connect.redhat.com/blog/api-deprecation-kubernetes-122-will-impact-your-operators)  
"The CRD update is expected to be the change that will affect most [community and] partners [operators]. The good news is that it’s really easy to make this update because the stable API is almost identical to the one you’re already using – it just requires a small code update."

[A Kubernetes engineer's guide to mTLS](https://buoyant.io/mtls-guide/)  
"Mutual authentication for fun and profit"

[Linux 5.14 SSD Benchmarks With Btrfs vs. EXT4 vs. F2FS vs. XFS](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.14-File-Systems)  
Which filesystem should you use for your needs?

[Five Ansible Techniques I Wish I’d Known Earlier](https://zwischenzugs.com/2021/08/27/five-ansible-techniques-i-wish-id-known-earlier/)  
"If you’ve ever spent ages waiting for an Ansible playbook to get through a bunch of tasks so yours can be tested, then this article is for you."

[Linux/BSD command line wizardry: Learn to think in sed, awk, and grep](https://arstechnica.com/gadgets/2021/08/linux-bsd-command-line-101-using-awk-sed-and-grep-in-the-terminal/)  
"'Do people really write these long, convoluted commands?' In a word: yes." I've got some real doozies in my notes. Trust me `sort | uniq -c | sort -n` is handy too.

[Comparing Open Source BGP stacks with internet routes](https://elegantnetwork.github.io/posts/comparing-open-source-bgp-internet-routes/)  
I love this comparison. BGP is so handy so knowing which implementation to use is a big deal.

[Release NGINX Ingress Controller - v1.0.0 · kubernetes/ingress-nginx](https://github.com/kubernetes/ingress-nginx/releases/tag/controller-v1.0.0)  
"Ingress NGINX v1.0.0 is HERE! With support for Kubernetes v1.22 and dropping support for v1beta1!"

[run-x/awesome-kubernetes](https://github.com/run-x/awesome-kubernetes)  
"A curated list for awesome kubernetes projects, tools and resources."

[uutils/coreutils](https://github.com/uutils/coreutils)  
"Cross-platform Rust rewrite of the GNU coreutils"

[borjatur/kubernetes-using-ansible-vagrant](https://github.com/borjatur/kubernetes-using-ansible-vagrant)  
"Kubernetes Setup Using Ansible and Vagrant"

[tiny-http/tiny-http](https://github.com/tiny-http/tiny-http)  
Low level HTTP server library in Rust

## DevOps'ish Tweet of the Week

[![Corey Quinn (@QuinnyPig) on Twitter: "So @docker has a new monetization strategy that's definitely innovative. "Docker Desktop requires you pay them if you're at a large company," which they define as over $10 million in revenue or 250 employees."](https://shortcdn.com/devopsish/233-devopsish-tweet-of-the-week.png)](https://twitter.com/QuinnyPig/status/1432720164169076755)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/233/notes.md) to see what didn't make it to the newsletter but are still worth your time.
