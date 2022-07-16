+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-07-17T07:00:00Z
description = []
draft = false
slug = "276"
tags = []
title = "DevOps'ish 276: "
+++

### A note about Detroit

I have heard through the grapevine many folks hating on Detroit as the city of choice for KubeCon NA 2022. Let me shove that theory into the refuse bin for you. [Time just named Detroit one of the World's 50 greatest places of 2022][1]. That's right, [Detroit][2] is dope af, and I can't wait for you to experience it at KubeCon NA.

### Ukraine

My friends, I've checked in on almost every Ukrainian I know during the past two weeks. To a person, they pleaded, "Please let everyone know that there is still a war in Ukraine." A donation or a link from your socials to [Operation Dvoretskyi][3] (named after my friend [Ihor Dvoretskyi][4]) means the world to many of my Ukrainian friends. Ukrainians need our continued support.

With the world so focused on the outcomes of Russian sanctions, food shortages, inflation, higher fuel costs, etc. We must remember why we all are enduring this. It's bigger than all of us. It's for the world. It's for Europeans. It's for Ukrainians. These are all messages from my friends that I share with you at their behest. This is how they've asked me to help.

### Last Week

Remember how [last week][5], I said I felt like I was [snakebit][6]. This week was the exact opposite story. I've been kicking systems' asses and taking names. Work has been great; lots of kicking tires hard and head-scratching, which I enjoy. If you have or know of a complex, open sourced Dockerfile, I'd love to take a look at it and poke at it. I'll go spelunking into [Jess Frazelle's dockerfiles otherwise][7].

I installed [Chrome OS Flex][8] on a 10-year-old, out-of-support Apple MacBook Air breathing new life into old hardware (more on that in a second). Our "new" Plex box is now using the SSD-based RAID 10 array in my lab's server over NFS. Max is grateful for the performance and reliability improvement. I briefly explained the setup to him, and he responded, "That's cool!" My [code-server environment][9] had a hiccup. I migrated it to the lab server, which is way more redundant and stable than the box I named bugs (Looney Tunes naming standards are legit).

I'm using nothing but open source solutions to manage my VMs and storage (with some guidance from my old Red Hat teammates; forever grateful to all of you). I have to say; I'm glad I went this route. Moving KVM/libvirt boxes from system to system on a local network is pretty easy, and the level of complexity is low.

Even though I'm not fond of Chrome these days, I find that with proper [DNS filtering][10], [Privacy Badger][11], and [DuckDuckGo's browser extension][12] and [search engine][13], I'm sidestepping as much as possible from Google's data slurping ecosystem. But, like [Kevin Mitnick][14] once said (paraphrasing), "If I have physical access, it's only a matter of time." Well, I gave Google physical access, so there's that.

[Chrome OS Flex][8] is the Chrome OS I wanted when I beta tested the Cr-48 way back in the day. A lightweight OS optimized to run on damn near anything. I've got the Linux dev environment up and running, too. I get a decent Linux CLI experience. But, the one (for me, major) drawback is that while the Linux dev environment can have Tailscale running on it, it's inside its happy little sandbox. But, right now, Chrome OS Flex can't install Android apps yet. I'll wait for that to develop more as that is the current default way of installing Tailscale on a ChromeOS machine. Then it has a real shot at being a laptop I could use daily.

### The week ahead

I'm in Seattle this week. On Monday, I'll finally walk into an Amazon building as an employee for the first time. I am also attending [DevOpsDays Seattle][16]. Funny story there. I joined the Kubernetes Contributor Comms meeting this week. In the pre-recording banter, [Kaslin Fields][17] mentioned she was organizing DevOpsDays Seattle. I was like, "Hey, I'm in Seattle next week..." A quick DM convo with my boss, and before the meeting was over; I had the green light to attend. On Thursday, I'm at an internal AWS event. Then I'm flying home on Friday.

I look forward to going to a DevOpsDays again. I need to start submitting CFPs again for in-person events. But, getting my feet wet in the new world is an excellent first step. Let me know if you're in Seattle and want to link up for coffee that isn't Starbucks or a meal.

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

## Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**DevOpsDays Seattle**][16]

DevOpsDays is coming back to Seattle for 2 days in person! Speakers include my friends Kat Cosgrove, Aaron Aldrich, and Laura Santamaria as well as many other awesome folks. As I mentioned in the intro, I'll be in attendance so grab a ticket and join me.

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

## People

PEOPLE

## Process

PROCESS

## Tools

TOOLS

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

[1]: https://time.com/collection/worlds-greatest-places-2022/?source=devopsish
[2]: https://time.com/collection/worlds-greatest-places-2022/6194455/detroit/?source=devopsish
[3]: https://www.operationdvoretskyi.org/?source=devopsish
[4]: https://twitter.com/idvoretskyi/status/1497840240748281856?source=devopsish
[5]: https://devopsish.com/275/
[6]: https://www.merriam-webster.com/dictionary/snakebit?source=devopsish
[7]: https://github.com/jessfraz/dockerfiles?source=devopsish
[8]: https://chromeenterprise.google/os/chromeosflex/?source=devopsish
[9]: https://chrisshort.net/code-server-caddy-tailscale-and-hugo-my-ultimate-dev-environment/?source=devopsish
[10]: https://nextdns.io/?from=atf4r8uh
[11]: https://privacybadger.org/?source=devopsish
[12]: https://duckduckgo.com/app?source=devopsish
[13]: https://duckduckgo.com/?source=devopsish
[14]: https://en.wikipedia.org/wiki/Kevin_Mitnick?source=devopsish
[16]: https://devopsdays.org/events/2022-seattle/welcome/?source=devopsish
[17]: https://kaslin.rocks/?source=
