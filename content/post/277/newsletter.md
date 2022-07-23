+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-07-24T07:00:00Z
description = [""]
draft = false
slug = "277"
tags = []
title = "DevOps'ish 277: "
+++

**A note about notes**: I will no longer publish the weekly notes file on the website. They are still [made available on GitHub][1] as they have been for the past 170 issues. If you're curious about the why: spam emails that came as a result. Yeah, funny how that works.

### The Past Week

I'm writing this week's newsletter intro from a Delta 737-900ER high above the western United States. I'm flying back from Seattle, where I had a great week (minus the fatigue and pain; I need to finish physical therapy). On Monday, I got to meet my new team face-to-face. The team is diverse in cultures, experiences, and skill sets. Share opinions on open source, the CNCF, and the Kubernetes ecosystem, as well as answer even the most basic of questions around governance. This is refreshing because I have the chance to help mentor and help people grow, in addition to my day job. I'm fortunate to be working with this wonderful group of folks.

One thing that stood out to me the most as I wandered around Seattle this week. The city's diversity has improved since my visits in 2012 and 2018. I'm looking forward to making more future trips to this beautiful city (fog or not). I know Max would love to tag along, too (he was impressed by the seagull population, pigeons, unique architecture, and construction). Yes, I have a unique photo album for Max when I travel.

### DevOpsDays Seattle

I attended DevOpsDays Seattle this week too. It was great to be back at DevOpsDays in person again. Seeing so many of my friends after so long ended up breathing new life into what I'm doing. My friend Kat Cosgrove gave a great talk about the history of configuration management. There have been a lot of tools to help with this along the way. The big ones; Make, cfengine, Puppet, Ansible (and many more); I've touched them all. I know I'm old because my body tells me that, but I'm experienced because I changed jobs enough to avoid getting too stuck on one tool. This was my first grand realization. I got fortunate that I had the opportunity to learn Puppet when it was new and complicated. To learn Ansible back in the late 1.x days. These experiences gave me foresight into what to look for in the following tooling setups. This led me to Kubernetes and what I'm doing today.

I met a few new people at DevOpsDays and people I've followed on Twitter forever but haven't met in person and had open and honest discussions. I got to see my Marine friends Ken Mugrage and Trip Longworth (for what might have been the longest, hardest hug I've had all year; I needed it). I saw Laura Santamaria of Kubernetes Community fame, former Red Hatter, and fellow Detroiter Rain Leander.

#### OCI Compliant Registries

Kat Morgan and I discussed why OCI-compliant repos should be able to host any OCI-compliant file, not only Dockerfiles. This could reduce complexity and tool sprawl, but I see application owners managing their repositories with simple backup and restore processes. Then I see enterprises coming in on top and doing their backups, scanning, and so forth. We must move beyond the Docker Registry v2 spec and into more universal places to push and pull images, charts, object configs, and other YAML bits. A sole source of truth is more manageable and easier to harden than 18 sources of truth. One OCI registry spec to rule all objects. That means a limitation needs to be brought to light, or conversations somewhere need to happen. I've only started looking into the issue recently, but I'm curious why it hasn't happened after talking to Kat Morgan. It feels like the right thing to do for developers and ops folks alike (not saying you'd all use the same registry. But, consistent tooling that's familiar to all teams is easier to make compliant.

#### Lightning Bolt of Logic

One lightning bolt from the realm of logic and reason came from Aaron Aldrich. "We won't run our systems past 80% load, but we refuse to let humans run at anything less than 100%." This is a remarkable fact of life. The talk was so inspiring I submitted a similar talk about my mental health struggles to [Deserted Island DevOps][2]. Lord knows the past year alone is enough to undo someone, let alone see them thrive. It took a lot of hard work and courage to get here.

### AWS Heros

We also had a few internal AWS events happening this week. I wanted to go to one on Thursday. But while walking there, I got diverted to an AWS Heros meeting. My boss was ill (and has a strong desire not to get others sick). I quickly get through the "fog of confusion" and into "roll with the punches" mode. The change in direction is always the hardest; once you've pivoted, you're off and running.

It's always great to get insights from our customers. [Even better to meet people you've helped along the way][3]. I always learn a lot talking to customers. But, many of the pain points I heard are still around organizational cultural problems. I spoke to one AWS Hero that defined the quintessential DevOps nightmare situation. With DevOps being over a decade old, you'd think we wouldn't be in this position anymore, yet here we are. This is why evolution is critical. There's a lot of something-something-Ops out there, but if you have Kubernetes in your stack, [GitOps][4] is for you.

I did hear murmurs like, "Do we have to run Kubernetes?" The answer is no. But, what are you trying to do? What might you be losing out on, or worse, hand jamming into production? People are fallible. Wouldn't systems scanning an audit log and taking actions as programmed when events trigger be a good default practice? There's some complexities to getting that done at scale. Once you're of a certain size, yes, Kubernetes makes sense. But, if you find a better abstraction point for your organization, do it. You also might have the engineering talent of Netflix and build your own thing if you want. But I got news for Netflix folks. All the bespoke open source projects they've created for internal use look like a lot of technical debt when your company is up against rough times and a competitive market environment. The layoffs and downturn will have you wishing you didn't build everything yourself once you've been whittled to a certain point. I mention Netflix because they seem to be the new Google. Netflix is doing it all on its own and [telling people their biggest competitor is sleep][5] (so by having a Netflix account, you are buying into the fact that you want less sleep). Why the hell would you ever tell a public audience that? That level of hubris led to Docker's ultimate demise.

[1]: https://github.com/chris-short/devopsish.com/tree/main/content/post
[2]: https://desertedislanddevops.com/
[3]: https://twitter.com/margaretvaltie/status/1550186266167152640
[4]: https://opengitops.dev/
[5]: https://twitter.com/chrisshort/status/1549850632395206656

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we’re expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We’re excited to welcome you back to our Deserted Island this September 14th and 15th!

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

## DevOps'ish Post of the Week

[![Lily Ray 😏 on Twitter: "My jaw actually dropped. @wilreynolds showed 3 examples of black doctors/nurses where Google's Vision AI rated the image as 70%+ "Street Fashion" despite them literally wearing scrubs When he painted the nurses white, it switched to "Formal wear" Truly unbelievable #mozcon https://t.co/hgM3gA9uvO" / Twitter)](https://shortcdn.com/file/devopsish/275-devopsish-post-of-the-week.webp)](https://twitter.com/lilyraynyc/status/1547361484144984065?s=12&t=Uxd6qd18SoDoQq1c473hkA)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/277/notes.md)