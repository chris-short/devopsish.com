+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-06-18T13:01:53.529Z
description = ""
draft = false
slug = "028"
tags = ["devops", "cloud native", "open source", "kubernetes", "database", "infrastructure", "detroit", "microservices", "Y2K"]
title = "028: Week of 1497758400"
image = "/028/detroit-pride.jpg"
imagealt = "GM RenCen Gay Pride"
aliases = [
    "devopsish-028-week-of-1497758400-e82b184e967a"
]

+++

Happy Father's Day to all the Dads out there. May your day be everything you want it to be and then some. This is my first weekend living in the Detroit Metro area so I will be quietly getting my bearings (and hopefully a car wash). I spent twelve hours in the car on Thursday and listened to more podcasts than I ever thought possible. On Tuesday, June 20th I will be attending the [DevOps Detroit Meetup at Grand Circus](https://www.meetup.com/DevOps-Detroit/events/239887659/). If you are near Detroit come check it out! It was a busy week in the world of DevOps and looks to be an even busier one this coming week.

[**Full Stack Fest 2017: Problems of today, wonders from the future.**](https://2017.fullstackfest.com)  
Barcelona, 4–8 Sept. 2017  
Are you a curious mind? [Full Stack Fest](https://2017.fullstackfest.com) is a week-long conference based in the amazing city of Barcelona that peeks into the web of tomorrow. Serverless, Blockchain, WebVR, Distributed Web, Progressive Web Apps... Come and see! Early bird tickets available with a 10% discount using the code DEVOPSISH. *SPONSORED*

## Department of Choice Concepts

My friend, [Jennifer Peters](https://jenniferannpeters.com/), pointed this Stack Overflow piece out to me: [Developers Who Use Spaces Make More Money Than Those Who Use Tabs](https://stackoverflow.blog/2017/06/15/developers-use-spaces-make-money-use-tabs/). I use tab to insert four spaces 💥

Heap Analytics shares their [Terraform Gotchas And How We Work Around Them](https://heap.engineering/terraform-gotchas/).

Paul Burt shares how to [Get Started with Go](https://opensource.com/article/17/6/getting-started-go?sc_cid=70160000001273HAAQ). There is now an all Go alternative Go Playground called [The Go Play Space](https://goplay.space/); kick the tires on that when you have a moment.

[Deploy an App into Kubernetes in less than 24 Minutes](https://devcentral.f5.com/articles/deploy-an-app-into-kubernetes-in-less-than-24-minutes-26764)

Parsec goes into detail about their [ELK stack running in Kubernetes](https://blog.parsec.tv/adventures-in-high-availability-logging-elk-on-kubernetes-5f38768e1740).

SQLite made the bold claim that their relational database is [35% faster than the filesystem](https://www.sqlite.org/fasterthanfs.html). "This article disproves the common assumption that a relational database must be slower than direct filesystem I/O."

[5 ways to cheat the software change curve with DevOps](https://techbeacon.com/5-ways-cheat-software-change-curve-devops):

1. Automate Deploys
2. Infrastructure as Code
3. Immutable Infrastructure
4. Microservices
5. [QA in Production](https://martinfowler.com/articles/qa-in-production.html)

[Joel Bastos walks use through the methodology to build phoenix servers](https://blog.kintoandar.com/2017/06/Baking-delicious-cloud-instances.html).

[Git remote branches and Git's missing terminology](http://blog.plover.com/prog/git-remote-branches.html)

[Julia Evans](https://jvns.ca/) is the [Richard Feynman](http://kottke.org/17/06/if-you-cant-explain-something-in-simple-terms-you-dont-understand-it) of our generation. Anything Julia writes is a must read, [especially her recent post on ACID databases](https://jvns.ca/blog/2017/06/11/log-structured-storage/).

## Department of Discussion

[Changelog dedicated an entire episode to discuss the GitHub Open Source Survey](https://changelog.com/podcast/252). We're hurting for diversity in the OSS, period.

Working remote can be difficult if the organization isn't excellent at communicating and collaborating (those are two different things). [Developer Tea discusses working remotely as a junior developer](https://developertea.simplecast.fm/episodes/70457-listener-question-joel-asks-about-remote-work-as-a-junior-developer) as well as other useful job seeking pointers.

[Alanna Brown Director of Technical Product Marketing at Puppet and Nicole Forsgren, PhD, CEO at DORA, discussed the State of DevOps Report 2017](https://soundcloud.com/infoq-engineering-culture/alanna-brown-and-nicole-forsgren-on-the-state-of-devops-report-2017).

[GoTime talked to Ramya Rao about VS Code](https://changelog.com/gotime/49). I think VS Code might be becoming my editor of choice (if I could get the time to configure it the way I want it).

[John Willis discusses the human factor of DevOps](https://jaxenter.com/john-willis-human-factor-devops-131054.html). Building that safety culture is so important. DevOps doesn't have human errors, it has systems failures.

## Department of Dafuq

Trump did something right this week; [Trump Orders Government to Stop Work on Y2K Bug, 17 Years Later](https://www.bloomberg.com/politics/articles/2017-06-15/trump-orders-government-to-stop-work-on-y2k-bug-17-years-later). While most probably overlooked the Y2K compliance bits, it highlights an issue in government: at what point does common sense get codified?

According to some great work by Mark Callaghan, [MySQL 5.7 likely created a performance issue in the codebase](https://smalldatum.blogspot.com/2017/06/sysbench-for-mysql-50-51-55-56-57-and-8.html).

## Department of Refreshment and Refurbishment

The first beta of [Go 1.9](https://tip.golang.org/doc/go1.9) was released this week.

[Daisy: a private blockchain where blocks are SQLite databases](https://github.com/ivoras/daisy).

## Department of Assemblage Obtainment

[Microsoft Joins Hot Open Source PaaS Project Cloud Foundry](http://www.datacenterknowledge.com/archives/2017/06/13/microsoft-joins-hot-open-source-paas-project-cloud-foundry/). Microsoft has really done a 180 of late. I would seriously consider working for them now which is something I would never have ten years ago.

Slack raising another HUGE round (Series G, I believe). The company is trying to grab $500 million with a $5 billion post-funding valuation. Why is this significant to the DevOps world? [This funding round piqued the interest of Amazon](https://www.bloomberg.com/news/articles/2017-06-15/messaging-startup-slack-said-to-draw-interest-from-amazon-com). Any suitor would obviously like to buy Slack pre-round if it could as it will be at a discounted valuation. For the sake of DevOps alone, Slack needs to remain independent.

[Speaking of Amazon, they are buying Whole Foods](http://www.cnbc.com/2017/06/16/amazon-buying-whole-foods-is-a-no-brainer-slam-dunk.html). Whole Foods just happens to be [a Microsoft Azure customer](http://www.cnbc.com/2017/06/16/amazons-acquisition-of-whole-foods-brings-in-a-microsoft-cloud-client.html).

## Department of Sane Workplaces

I love this post from Katherine Daniels about [accidentally upgrading Apache in production](https://beero.ps/2017/06/17/on-failure-and-resilience/). Great explanation of how a team with great culture works.

[Lara Hogan shares a treasure trove of ally resources with us](https://github.com/larahogan/ally-resources). "Just a handful of things that were helpful to me, or that I developed with other allies, while working at Etsy."

## DevOps'ish Tweet of the Week

{{< tweet 873527496939102212 >}}
