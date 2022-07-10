+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-07-10T07:00:00Z
description = [""]
draft = false
slug = "275"
tags = []
title = "DevOps'ish 275: "
+++

Have you ever felt like you're [snakebit][1]? When whatever you do in a particular discipline, nothing goes as planned.

I have a Dell R820 packed to the gills with 500 GB Samsung SSDs (I'll update to [1 TB drives][2] once they're under $100) in my lab. 1.3 terabytes of RAID10 at your service. If you've followed me since my Red Hat days, you've seen me wrangle with Kubernetes local storage on this box. I've destroyed this server live on air, on purpose, more than I want to admit.

After joining AWS, I didn't need an OpenShift cluster and completely wiped the server. It sat there completely off for weeks at a time. The entire month of June, it sat off. I didn't use the server for much after October, aside from the random tasks that were I/O heavy.

I'm focused on inner loop development in my new role at AWS. The pipeline to prod experience from there, while not necessarily in scope, that interface, that handoff, that experience, has to be solid. Also, the job will vary day-to-day as I'm the first Developer Advocate on this team. One day I might be building software from source one day. Next, I could be looking at a CI pipeline. Another day, I'll be creating and spinning up many containers at once. There's also this cool new thing for [bare metal called EKS Anywhere][3] (I had my feedback put into the product). It's open source, too; I don't need a license as long as I'm not calling support for it.

I'm spending time now, early in the job, while I'm reading and researching, doing technical work to balance my days and lay the foundation to emulate the developer experience. Whatever it may be—I'm building out the platform now so that I can feel the same pains. I build empathy this way. I build muscle memory this way. I usually pick up a good habit or two in the process.

I want to have all the flexibility our customers have at my fingertips as they do. Whether deploying from laptop to test on-prem or in the cloud, I want my use cases covered.

The problem I'm having is the kind of Murphy's Law that makes you want to hang it up for the weekend and give up until Monday. While that might have been a better option at 6 AM, I took the path of figuring things out. The difficulties of computers not bending to my will would have festered in my head all weekend if I'd not done something.

I woke up Saturday morning, looked over everything, realized what I was doing wrong, and proceeded to set things right in one place while something else would break. I realized I was trying to do too many things at once. One system at a time. One step at a time. The server came up. I moved my [code-server][4] over to it, so I could do a wipe and load on my brand new NUC, which decided it wanted to add in on the fun (along with Julie's laptop; Apple friends, call me).

The worst part is that these systems aren't connected in any way. I'm the only consistency here. Yes, I push systems to their limits. But, I'm not superstitious until life gives me a reason to be. I remember rough patches at literally all my jobs. Where things didn't fall my way, it's not so much what you do to get over the hump. The act of getting over it is hard but worth it. Once you're through it, you can go back and write that blog post you originally wanted to finish this weekend, but silicon had different plans for you.

[1]: https://www.merriam-webster.com/dictionary/snakebit
[2]: https://amzn.to/3RmeHfJ
[3]: https://aws.amazon.com/blogs/containers/getting-started-with-eks-anywhere-on-bare-metal/
[4]: https://devopsi.sh/env

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

## Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

PEOPLE

## Process

PROCESS

## Tools

TOOLS

## DevOps'ish Post of the Week

[![@marinavance on Twitter)](https://shortcdn.com/file/devopsish/275-devopsish-post-of-the-week-001.webp)](https://twitter.com/marinavance/status/1541835993115856896)

[![@marinavance on Twitter)](https://shortcdn.com/file/devopsish/275-devopsish-post-of-the-week-002.webp)](https://twitter.com/AlexJonesax/status/1543678834100297730)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.
