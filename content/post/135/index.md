+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-07-07T07:00:00Z
description = ""
draft = false
slug = "135"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "weekly newsletter", "security", "podcast", "burnout", "on-call"]
title = "135: DevOps'ish Deep Cuts podcast, burnout, on-call, Cloudflare fustercluck, multicloud mess, cherry-picks and more"

+++

I was on PTO this week. I was working on a number side project issues I've been trying to resolve for quite some time. This includes soft launching a podcast! [**Deep Cuts**](https://devopsish.com/deep-cuts-134/) is a podcast that looks at the news behind the news. Things that were significant but didn’t make the newsletter for one reason or another. Prepare to embrace People, Process, and Tools in your ear holes.

I say soft launch because it's important to me to take things iteratively. [Anchor](https://anchor.fm/devopsish) is the platform for the moment. They're working the difficult task of getting the podcast listed in all the major directories. Iterative improvements will be the name of the game. Feedback on anything I do is always appreciated.

[**How companies adopt and apply cloud native infrastructure--from O'Reilly**](https://www.oreilly.com/pub/cpc/224549)  
Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud. *SPONSORED*

## DevOps'ish Last Week's Top Five

1. [How I use Slack—alone—to get more done](https://char.gd/blog/2019/how-i-use-slack-alone-to-get-more-done)
1. [After 4 years with nginx, we switched to Caddy - Here is why](https://engineering.hashnode.com/after-4-years-with-nginx-we-switched-to-caddy-here-is-why-cjxbv8eb2001ke8s1yl7ndroz)
1. [I spend too much time in Zoom...](https://medium.com/@joebeda/i-spend-too-much-time-in-zoom-5eedcea5cc90)
1. [A deep dive into Linux namespaces](http://ifeanyi.co/posts/linux-namespaces-part-1/)
1. [How SRE teams are organized, and how to get started](https://cloud.google.com/blog/products/devops-sre/how-sre-teams-are-organized-and-how-to-get-started)

## People

[DevOps for doubters: How to deal with 9 kinds of people who push back](https://enterprisersproject.com/article/2019/7/devops-for-doubters-9-tips) — This article is stuffed with quotes about dealing with all sorts of personalities practioners have experienced. I was one of many quoted in the article.

[Why I quit a $500K job at Amazon to work for myself](https://danielvassallo.com/only-intrinsic-motivation-lasts/) — "La st week I left my cushy job at Amazon after 8 years. Despite getting rewarded repeatedly with promotions, compensation, recognition, and praise, I wasn’t motivated enough to do another year."

[When Passion Leads to Burnout](https://hbr.org/2019/07/when-passion-leads-to-burnout) — "When we equate work we love with 'not really working,' it propagates a belief that if we love it so much, we should do more of it — all of the time, actually."

[Intro to containers, Kubernetes, and Red Hat OpenShift (DO180)](https://www.redhat.com/en/services/training/do180-introduction-containers-kubernetes-red-hat-openshift) — "Introduction to Containers, Kubernetes, and Red Hat OpenShift (DO180) helps you build core knowledge in managing containers through hands-on experience with containers, Kubernetes, and the Red Hat® OpenShift® Container Platform."

[The 2019 Web Developer Roadmap - A Visual Guide to Becoming a Front End, Back End, or DevOps Developer](https://www.freecodecamp.org/news/2019-web-developer-roadmap/)

[An Inconvenient Truth of the Cloud Native World](https://www.tfir.io/2019/07/05/cloud-native-trends-security-risk-dirk-hohndel-cncf-kubecon/) — "No matter how you slice it, “a better understanding of the code that you’re running is always an advantage," says Dirk Hohndel, Vice President and Chief Open Source Officer at VMware.

[Get your work recognized: write a brag document](https://jvns.ca/blog/brag-documents/) — This is really great advice from Julia Evans.

[DevOps'ish Telegram](https://t.me/devopsish) — Join the 300+ DevOps, Kubernetes, SRE, and other technology professionals discussing real-world problems, breaking technology events and outages, and the occasional Spotify playlist.

## Process

[If you have to ask... OpenEBS 1.0](https://medium.com/mayadata/if-you-have-to-ask-openebs-1-0-dd4a1663c8a9) — Evan Powell shares, "an entrepreneur’s perspective on what achieving OpenEBS 1.0 means." This is a big deal for any project. MayaData has done some really great work. Evan and the MayaData team have a lot to be proud of.

[Microsoft is teasing Windows 1.0 — yes, from 1985 — for a mystery Stranger Things tie-in](https://www.theverge.com/tldr/2019/7/5/20683448/microsoft-windows-1-0-stranger-things-season-3-upside-down-july-8) — This should be interesting for us old timers. To be clear, I don't think I got into Windows until the 3.x days, so I'm not that old (haters).

[Making On-Call Not Suck](https://dev.to/molly_struve/making-on-call-not-suck-490) — Molly Struve shares what a long time between on-call rotations do to your team's incident response skills. The team essentially made microservices of their on-call to improve the process and ownership. A very interesting read.

[Distributed Tracing — we’ve been doing it wrong by Cindy Sridharan](https://medium.com/@copyconstruct/distributed-tracing-weve-been-doing-it-wrong-39fc92a857df) — "[E]ven if hypothetically all of these problems were to be solved, there’s a good likelihood that nothing much has significantly changed as far as the end user experience is concerned."

[How To Prepare For The Coming Recession](https://go.forrester.com/blogs/how-to-prepare-for-the-coming-recession/) — If you've read this newsletter long enough you know a recession is not a matter of if, but when. It could be another dot com bubble too and that literally scares the shit out of me.

[This major internet routing blunder took A WEEK to fix. Why so long? It was IPv6 – and no one really noticed](https://www.theregister.co.uk/2019/07/02/ipv6_routing_error/) — "BGP and DNS are the bubble gum and duct tape of the internet." An IPv6 discussion around this article on Twitter led to me blocking people. Good lawd, y'all.

[Cloudflare Worldwide Outage Caused by Bad Software Deployment](https://www.bleepingcomputer.com/news/technology/cloudflare-worldwide-outage-caused-by-bad-software-deployment/) — "The teams at @verizon and @noction should be incredibly embarrassed at their failings this morning which impacted @Cloudflare and other large chunks of the Internet. It’s absurd BGP is so fragile. It’s more absurd Verizon would blindly accept routes without basic filters." —Matthew Prince, CEO, Cloudflare from [a tweet on June 24th](https://twitter.com/eastdakota/status/1143182575680143361). On July 2nd, "Cloudflare experienced a worldwide outage today for about 30 minutes, with network performance issues that brought down a multitude of websites and web services all around the world, and triggered "502 Bad Gateway" errors." All due to some bad regex causing a massive CPU spike. [Life comes at you fast](https://blog.cloudflare.com/cloudflare-outage/).

[Brazil revocation of IBM-Red Hat deal approval likely to delay closing, attorney says](https://www.wraltechwire.com/2019/06/28/brazil-revocation-of-ibm-red-hat-deal-approval-likely-to-delay-closing-attorney-says/) — Be careful what you wish for. When [I asked Brazil to stall the Red Hat acquistion](https://twitter.com/ChrisShort/status/1145793603182239744) for me so my PTO didn't get interrupted this week, I was 100% not serious. But, thanks? [¯\\\_(ツ)\_/¯](https://chrisshort.net/shrug/)

## Tools

[How to use GitLab and Ansible to create infrastructure as code](https://about.gitlab.com/2019/07/01/using-ansible-and-gitlab-as-infrastructure-for-code/) — Explore the power of GitLab CI and Ansible playbooks in infrastructure as code.

[Kube Forwarder](https://kube-forwarder.pixelpoint.io/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=135) — Easy to use Kubernetes port forwarding manager. This will help lower the barrier to entry to Kubernetes for some folks.

[The Infrastructure Mess Causing Countless Internet Outages](https://www.wired.com/story/bgp-route-leak-internet-outage/) — "Originally conceived in 1989 (on two napkins), the version of BGP used today remains largely unchanged since 1994." Can confirm. I did a LOT of fun stuff at Langley AFB with BGP back in 2000. It taught me that with great power comes great responsibility in all kinds of new ways.

[Running Kubernetes on Ephemeral Infrastructure](https://ctovision.com/running-kubernetes-on-ephemeral-infrastructure/) — "'Running Kubernetes on Ephemeral Infrastructure', talks about what happens when you run large kubernetes clusters for mission critical enterprise apps and you destroy every node every 48 hours." It's from the folks at Palantir Technologies so take that into account.

[Fedora mulls its "python" version](https://lwn.net/Articles/792718/) — What should `python` really mean?

[To run or not to run a database on Kubernetes: What to consider](https://cloud.google.com/blog/products/databases/to-run-or-not-to-run-a-database-on-kubernetes-what-to-consider) — A primer on database considerations with Kubernetes. "Stateless is easy. Stateful is hard." —Old Cloud Proverb

[Absence of certain features in IRC considered a feature](https://drewdevault.com/2019/07/01/Absence-of-features-in-IRC.html) — I know Electron is bad but, y'all. Don't get me wrong, I use still IRC. However, if it weren't for an always-on service with a mobile app, I would not be as likely to use IRC. There's a balance here somewhere but, my 66 Slack accounts ain't it. Pure IRC isn't it either.

[Fuck Off As A Service (FOAAS)](https://foaas.com/) — "FOAAS (Fuck Off As A Service) provides a modern, RESTful, scalable solution to the common problem of telling people to fuck off."

[Apple is reportedly giving up on its controversial MacBook keyboard](https://www.theverge.com/2019/7/4/20682079/apple-butterfly-switch-scissor-switch-2019-macbook-air-2020-macbook-pro) — Why do Apple feature failures always take so long to come to their logical conclusion? This is good for all Mac users. Let's face it though, old CPUs and GPUs at premium pricing isn't a good look for Apple. The faulty keyboards are the cherry on top for a ton of folks.

[Why multicloud management is a mess](https://www.techrepublic.com/article/why-multicloud-management-is-a-mess/) — My take: Because it's not in the cloud providers' interest to make multicloud easy. Matt Asay's take, "Roughly 80% of all enterprises are steering toward multicloud; the other 20% are kidding themselves." Again, you have to build a platform on top of the clouds to make them agnostic. Hence Kubernetes' popularity. This goes back to what I said in last week's newsletter, "Folks have to pick a cloud or build a platform across them."

[Monitoring Stock Prices with Prometheus and Molescrape](https://eliteinformatiker.de/2019/07/03/monitoring-stock-prices-with-prometheus-and-molescrape)

[jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker) — The lazier way to manage everything Docker

[darshanime/notes](https://github.com/darshanime/notes) — detailed notes on computer science topics, in one page

[community/cherry-picks.md](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-release/cherry-picks.md) — "This document explains how cherry-picks are managed on release branches within the kubernetes/kubernetes repository. A common use case for this task is backporting PRs from master to release branches."

[goadapp/goad](https://github.com/goadapp/goad) — Goad is an AWS Lambda powered, highly distributed, load testing tool

## DevOps'ish Tweet of the Week

{{< tweet 1145787863235223552 >}}
