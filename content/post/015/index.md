+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-03-19T09:02:00.782Z
description = ""
draft = false
slug = "015"
tags = ["devops", "cloud native", "open source", "intel", "github", "google", "containers", "licenses", "Docker"]
title = "015: Week of 1489896000"
image ="https://shortcdn.com/file/devopsish/womens-track-and-field.jpg"
imagealt = "Why Doesn't DevOps Consider Front End Performance More Often?"
aliases = [
    "devopsish-weekly-015-week-of-1489896000-fc5adb2ccf34"
]

+++

I have recently taken over as a co-organizer of [**Triangle DevOps**](https://www.meetup.com/Triangle-DevOps/). In a meeting with the other primary co-organizer we talked a little about performance. [**DevOps**](https://devopsish.com/) considers network, code, system, and other aspects of performance. Yet, we rarely, if ever, consider what we can do to help the most critical part of our products; the front end.

The customer cares the most about the interface they use for the products we facilitate. If we do not consider caching, CDNs, and asset utilization at some point in our journey are we doing DevOps justice? I would argue it's not the job of development or design to consider global optimizations such as this. Don't get me wrong, it would be awesome if someone else cared but so often it is not even a thought. This is a part of what DevOps is all about! Optimization, reduce costs, and gain efficiencies. *DevOps is everything and everything is DevOps.*

## Department of Choice Concepts

Speaking of front end performance, [Google just announced Guetzli](https://research.googleblog.com/2017/03/announcing-guetzli-new-open-source-jpeg.html). It can create high quality JPEG images with file sizes 35% smaller.

I am obsessed with time. Timekeeping, time synchronization, relativity; just the thought of time as a unit of measurement fascinates me. LazyStone shares some interesting thoughts around [managing time for your users](https://lazystone.github.io/programming/time/2017/03/13/time-matters.html).

[Stop spending engineering effort solving problems you don't have!](https://hackernoon.com/stop-spending-engineering-effort-solving-problems-you-dont-have-8d18584f4d2a#.hgj1iv4cb) Here's a pragmatic approach for teams trying to iterate rapidly with few resources.

We in DevOps have a genetic tendency to over-engineer solutions. The sign of a good fashion designer is their ability to edit themselves. The same applies to DevOps Engineers. [Avoid complex infrastructure when building simple things](https://hackernoon.com/after-i-just-do-all-this-itll-be-so-simple-de73c5f799e2#.f1g8kyqay).

[So you want to be a wizard](https://jvns.ca/blog/so-you-want-to-be-a-wizard/).

## Department of Dafuq

If [**lkml.wtf](https://lkml.wtf/)** is consistently updated by Jess Frazelle it will be a sad yet hilarious weekly highlight of how fucked up Linux kernel development is.

## Department of Discussion

[**RevolutionConf**](https://revolutionconf.com/) is coming back to Virginia Beach, June 1–2, 2017. It's a 2 day, 5 track, polyglot technology conference just feet from the beach. In addition to talks, [**RevConf**](https://twitter.com/revconf/) 2017 will also include four 3-hour workshops in our workshop track on AWS, Azure, Docker, and the new features of ECMAScript 6. Wave 1 ($199) tickets will be over on March 31st (if they do not sell out before). Diversity scholarships are available and will be awarded on a rolling basis: [tinyurl.com/zwnvoxn](http://tinyurl.com/zwnvoxn)

RevolutionConf Note: For those who want to plan a mini-vacation, there's a limited-time rate of $119 for oceanfront hotel rooms at the Wyndham.

[Videos from all the Google Cloud Next 2017](https://www.youtube.com/playlist?list=PLIivdWyY5sqI8RuUibiH8sMb1ExIw0lAR) sessions were up insanely quick. Job well done Google.

## Department of Refreshment and Refurbishment

[A formal spec for GitHub Flavored Markdown](https://githubengineering.com/a-formal-spec-for-github-markdown/) (thank all things holy).

You have heard of Docker containers. Hopefully, you have heard of rkt containers. If you haven't heard anything about Intel's Clear Container educate yourself because [Intel is adding legitimacy to the Clear Container spec](http://www.theregister.co.uk/2017/03/14/clear_containers_docker_kubernetes/).

[GitHub is elevating the importance of licenses on its platform](https://github.com/blog/2335-open-source-license-descriptions-and-metadata).

## Department of Sane Workplaces

[The Top 10 Thought Leaders in DevOps](https://sweetcode.io/top-10-thought-leaders-devops/) has only **one** woman on the list. This feels wrong to even mention in DevOps'ish. But, I think it's important to point out. Also, [Nicole Forsgren](http://nicolefv.com/) is both brilliant AND inspirational. But, we [need more women in DevOps](/014/).

Harvard Business Review just slapped some sense into every dude on the planet. "... [Far more troubling, lots of men are bystanders, silent and impotent in the face of a toxic workplace](https://hbr.org/2017/03/too-many-men-are-silent-bystanders-to-sexual-harassment)."

## Department of Assemblage Obtainment

Citrix has an office here in Raleigh and they employ quite a few people there. My understanding is that it's not a great place to work. With [a sale of Citrix pending](https://www.bloomberg.com/news/articles/2017-03-13/citrix-is-working-with-goldman-sachs-on-potential-sale-process) there will likely be some DevOps talent available soon.

[GitLab is acquiring Gitter and intends to open-source the code.](http://venturebeat.com/2017/03/15/gitlab-acquires-software-chat-startup-gitter-will-open-source-the-code/)

## Not DevOps But Still Cool

[The Raspberry Pi is the third best-selling general purpose computer of all time](https://www.raspberrypi.org/magpi/raspberry-pi-sales/).

## DevOps'ish One-Liner of the Week

Ever want to just grab the dates from a PagerDuty ICS file? Well I needed to this week:

    grep DATE-TIME On\ Call\ Schedule\ for\ Solarwinds\ Alerts\ \(Level2\).ics | cut -d: -f2 | sort | cut -dT -f1
