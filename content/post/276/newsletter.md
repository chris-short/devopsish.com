+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-07-17
description = ["Packed with projects, Chrome OS Flex, DevOpsDays Seattle, Screaming in the Cloud, 'critical' projects maintained by volunteers, OSS Insight, and more"]
draft = false
slug = "276"
tags = []
title = "DevOps'ish 276: Packed with projects, Chrome OS Flex, DevOpsDays Seattle, Screaming in the Cloud, 'critical' projects maintained by volunteers, OSS Insight, and more"
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

[What Can the Tech Community Do to Protect Its Trans Members?](https://thenewstack.io/what-can-the-tech-community-do-to-protect-its-trans-members/)  
Heather Joslyn, The New Stack  
"[Aeva] Black, whose keynote alerted the conference attendees about how the rights of transgender individuals are under attack around the United States, and the role tech can play, currently works in Microsoft Azure's Office of the Chief Technology Officer and holds seats on the boards of the Open Source Initiative and on the OpenSSF's Technical Advisory Council."

[Kubernetes and OpenGitOps with Chris Short](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/kubernetes-and-opengitops-with-chris-short/)  
Last Week in AWS Podcast  
"It's how much does your team want to manage? That's the customer obsession part of AWS coming through when it comes to containers is because there's so many different ways to run those workloads, but there's so many different ways to make sure that your team is right-sized, based off the services you're using."

["Critical" projects and volunteer maintainers](https://lwn.net/SubscriberLink/900953/44823d451920e233/)  
Jake Edge, LWN  
"As Luis Villa noted last year, FOSS maintainers are being asked to do more and more things; often they are being asked to do so without any compensation, though perhaps "doors opening" counts to a limited extent. As more critical projects are identified, it is likely we will see more conflicts of this nature. What happens when a maintainer does not want to follow the recommendations of OpenSSF (or some other similar effort) on changes? Forks are generally seen as a hostile move, but one suspects that may ultimately happen for projects that find themselves at odds with sponsoring organizations. That is a rather different world than the one FOSS grew up in."

[A Bored Chinese Housewife Spent Years Falsifying Russian History on Wikipedia](https://www.vice.com/en/article/pkgbwm/chinese-woman-fake-russian-history-wikipedia)  
Rachel Cheung, Vice  
"What's mom doing on the computer?"  
"Contributing nearly 300 articles on Russian history that are all ficticious."  
"Oh... Well I guess that's more exciting than crocheting, huh?"

[Publishing your work increases your luck](https://github.com/readme/guides/publishing-your-work)  
Aaron Francis, GitHub  
When your project gets picked up by a major vendor and contributions start coming in. When your blog post takes off. When your newsletter has a great week. You have to be your own best agent to total strangers on the internet.

## Process

[Retbleed: Arbitrary Speculative Code Execution with Return Instructions](https://comsec.ethz.ch/research/microarch/retbleed/)  
Computer Security Group  
Maybe speculative execution is a big mistake. It's gotta be hard to defend these days. The hits just keep coming. If someone has seen a light at the end of the tunnel, please pass that along. I could write a blog post on corporate responsibility and ethics in our modern world on this topic alone.

[First Cyber Safety Review Board report finds Log4j has become an 'endemic vulnerability'](https://therecord.media/first-cyber-safety-review-board-report-finds-log4j-has-become-an-endemic-vulnerability/)  
The Record by Recorded Future  
Log4j is in a close second to speculative execution on being a critical flaw worldwide, over and over again. This goes to the fact that a lot of this is built and maintained by volunteers that SHOULD be compensated for their globally acknowledge as wildly popular works. Software is The Renaissance's art. We should insure it similarly.

[$9.99/Month](https://basicappleguy.com/basicappleblog/999month)  
Basic Apple Guy  
I need to do this myself. My problem is I'll buy a year of something for the savings then end up replacing it with something better a few months later. We should all take stock of our subs in this subscription economy. Your sources of truths are varied and numerous here. Good luck!

[Lessons in Frugality: Why Pay for Linktree?](https://chrisshort.net/lessons-in-frugality-why-pay-for-linktree/)  
Chris Short, chrisshort.net  
Speaking of things I buy for a year and replace in a few months with something else... Following the "own your platform" mantra, I've rolled out <chrisshort.me> as a replacement for Linktree. Believe me, you can do this and you can usually do it for free.

[AWS is quietly getting better at open source](https://www.techrepublic.com/article/aws-getting-better-at-open-source/)  
Matt Asay, TechRepublic  
There are a group of us pushing very hard towards helping open source helps our customers. We've embodied that in our work by doing work upstream as well as downstream. It is working. Please see my [disclaimer](https://devopsish.com/terms/#disclaimer).

[What Is Delaware's Court of Chancery and Its Role in Elon Musk's Twitter Deal?](https://www.nytimes.com/article/musk-twitter-delaware-court-chancery.html?referringSource=devopsish)  
Kalley Huang, The New York Times  
"Twitter has sued Mr. Musk to force a sale of the company, and the case will be determined by a 230-year-old court in Delaware." This was a fascinating read.

## Tools

[Kubernetes Gateway API Graduates to Beta](https://kubernetes.io/blog/2022/07/13/gateway-api-graduates-to-beta/)  
Shane Utt (Kong), Rob Scott (Google), Nick Young (VMware), Jeff Apple (HashiCorp), Kubernetes  
"Gateway API is a collection of resources centered around Gateway resources (which represent the underlying network gateways / proxy servers) to enable robust Kubernetes service networking through expressive, extensible and role-oriented interfaces that are implemented by many vendors and have broad industry support."

[Twitter now lets all users 'unmention' themselves in tweets](https://techcrunch.com/2022/07/11/twitter-now-lets-all-users-unmention-tweets/)  
Aisha Malik, TechCrunch  
Finally! I can duck out of conversations after they've gone from good to horse kicking. Also, I immediately texted [VM Brasseur](https://www.vmbrasseur.com/) when I heard the news.

[OSS Insight](https://ossinsight.io/analyze/chris-short)  
"OSS Insight, short for open source software insights, is a powerful insight tool that can help you analyze in depth any single GitHub repository, compare any two repositories using the same metrics, and provide comprehensive, valuable, and trending open source insights." Now this shows how active someone is in open source on GitHub in a whole new way.

[Samsung QVO vs. EVO: SSD differences explained](https://www.digitaltrends.com/computing/samsung-qvo-vs-evo-guide/)  
Monica J. White, Digital Trends  
I was confused based off pricing from different sites which Samsung drive had the better performance. I share this with you for when you go to upgrade your NAS/lab/etc.

[weaveworks/vscode-gitops-tools](https://github.com/weaveworks/vscode-gitops-tools)  
"GitOps Visual Studio Code Extension" I'm kinda surprised they aren't available on code-server but I guess that is part of the sacrifice I made. Friends from [Coder](https://coder.com/) feel free to educate me here.

[pulumi/registry](https://github.com/pulumi/registry)  
"The global index of everything you can do with Pulumi"

[LyonSyonII/hunt-rs](https://github.com/LyonSyonII/hunt-rs)  
"Simplified Find command made with Rust." You had me at Simplified Find.

[containerd/stargz-snapshotter](https://github.com/containerd/stargz-snapshotter)  
"Fast container image distribution plugin with lazy pulling"

[innobead/kubefire](https://github.com/innobead/kubefire)  
"KubeFire 🔥, creates and manages Kubernetes Clusters using Firecracker microVMs" Remember kids, fire and Kubernetes mix well.

[servian/aws-auto-cleanup](https://github.com/servian/aws-auto-cleanup)  
"Programmatically delete AWS resources based on an allowlist and time to live (TTL) settings"

[codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)  
"Master programming by recreating your favorite technologies from scratch."

[codesenberg/bombardier](https://github.com/codesenberg/bombardier)  
"Fast cross-platform HTTP benchmarking tool written in Go"

## DevOps'ish Post of the Week

[![Lily Ray 😏 on Twitter: "My jaw actually dropped. @wilreynolds showed 3 examples of black doctors/nurses where Google's Vision AI rated the image as 70%+ "Street Fashion" despite them literally wearing scrubs When he painted the nurses white, it switched to "Formal wear" Truly unbelievable #mozcon https://t.co/hgM3gA9uvO" / Twitter)](https://shortcdn.com/devopsish/275-devopsish-post-of-the-week.webp)](https://twitter.com/lilyraynyc/status/1547361484144984065?s=12&t=Uxd6qd18SoDoQq1c473hkA)

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
