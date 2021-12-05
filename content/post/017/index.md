+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-04-02T12:24:58.717Z
description = ""
draft = false
slug = "017"
tags = ["devops", "cloud native", "open source", "kubernetes", "linux", "github", "google", "containers", "Docker"]
title = "017: Week of 1491105600"
image = "/017/Unicorn-Farting-Rainbow-DevOps.gif"
imagealt = "This Glorious GIF is Courtesy of Josh Atwell from his talk at this week's Triangle DevOps Meetup"
aliases = [
    "devopsish-weekly-017-week-of-1491105600-9b15368745fb"
]

+++

I started a new on-call rotation this week and it has really sucked. The team whose rotation I was added on to is mature in a few areas but monitoring and alerting seems to be lacking a little. They acknowledge that and my coming on to the rotation is partially to identify areas of improvement. The rotation I was on a couple weeks ago for a different team resulted in no pages all week and my bringing the team donuts.

This week's rotation has resulted in a page every night (and two shorter maintenance events). The team that got donuts is very weak in some areas that this week's team is not. But the donut team focused on monitoring and alerting as well as not waking people up and it shows.

Part of my job is to bring consistency to these teams that are separated 3,676 miles apart. Sharing expertise, processes, and procedures is part of the gig. The deficiencies in tooling have been identified. The need for personnel has been fulfilled. Now it's time to bring on the processes and results.

The good news is I organized and lead my first [Triangle DevOps](https://tridevops.com) meetup on Wednesday night. It was a blast! [Josh Atwell](https://twitter.com/Josh_Atwell) did a superb job speaking (the GIF is glorious), [The Select Group](http://www.selectgroup.com/) fed us well, and [Transloc](http://transloc.com/) was a fantastic host. Thanks to everyone for a successful first rodeo!

## Department of Choice Concepts

I think it's save to say Jessie Frazzle broke the Internet with her exquisite comparison of [containers vs. Zones vs. Jails vs. VMs](https://blog.jessfraz.com/post/containers-zones-jails-vms/). Also, dudes need to stop telling Jess how containers work.

Julia Evans put together a wonderful article on [Bash scripting quirks and safety tips](http://jvns.ca/blog/2017/03/26/bash-quirks/).

freeCodeCamp has put together a list of the [10 most mentioned GitHub repos for new developers](https://medium.freecodecamp.com/the-10-github-repos-people-mention-the-most-in-freecodecamps-main-chat-room-189750600fa4). My personal favorite is the [free-programming-books](https://github.com/vhf/free-programming-books) repo.

Get Into DevOps put together a very useful piece on [tidying up after the rather messy Docker](https://getintodevops.com/blog/keeping-the-whale-happy-how-to-clean-up-after-docker).

[Meet Alpine Linux, Docker's Distribution of Choice for Containers](https://thenewstack.io/alpine-linux-heart-docker/)

[Curl is written in C and here is why](https://daniel.haxx.se/blog/2017/03/27/curl-is-c/).

Upheaval in the Linux Kernel world! [A cadre of kernel developers are going to Make Linux Great Again](https://lkml.org/lkml/2017/3/31/641). 😉😉😉

## Department of Data Defense

Congress made VPNs all the rage this week when they [repealed broadband privacy protections](http://www.dslreports.com/shownews/The-GOP-Just-Killed-Consumer-Broadband-Privacy-Protections-139244). The amount of FUD out there regarding VPNs is really high. When my wife is reading about [VPNs on Buzzfeed](https://www.buzzfeed.com/nicolenguyen/how-to-keep-your-browsing-history-actually-private) we have reached a story's critical mass. Remember, a VPN will only change your jurisdiction, not what you are actually surfing. At some point in your packets' journey, your traffic is still trackable and traceable. You can reduce the risk but you cannot completely eliminate it. I recommend using an ad blocker like [Ghostery](https://www.ghostery.com/), use a VPN you are actually invested in (read the terms and pay for it), and generating a ton of bogus traffic might be a good idea too. [NYU has launched TrackMeNot to generate noise and obfuscation](https://cs.nyu.edu/trackmenot/).

[IIS 6 has a gnarly zero day that Microsoft has stated it will not patch](http://www.pcworld.com/article/3186748/security/millions-of-websites-affected-by-unpatched-flaw-in-microsoft-iis-6-web-server.html).

[EL5 (RHEL and CentOS) is officially end of life](https://access.redhat.com/support/policy/updates/errata). You should have purged it from your infrastructure already.

## Department of Discussion

[KubeCon Europe](http://events.linuxfoundation.org/events/cloudnativecon-and-kubecon-europe) wrapped up this past week. There were quite a few nuggets of great information from the event. [The New Stack had fantastic coverage of KubeCon Europe](https://www.thenewstack.io/tag/KubeCon-Europe-2017). Part of this coverage included a great piece on [Kelsey Hightower's talk on Kubernetes Federation](https://thenewstack.io/kubernetes-federation-post-configuration-management-universe/).

## Department of Happy Little Clouds

[Dell EMC has joined the Cloud Native Computing Foundation](https://blog.codedellemc.com/2017/03/29/cloud-native-computing-foundation-announces-dell-technologies-platinum-member/).

[Microsoft is shutting down CodePlex and recommending people use GitHub](https://blogs.msdn.microsoft.com/bharry/2017/03/31/shutting-down-codeplex/).

## Department of Sane Workplaces

[Lara Hogan has put together a list of 1-on-1 questions](http://larahogan.me/blog/first-one-on-one-questions/) that I feel would have helped me stay at some company's longer if my manager had known the answers to these questions.

## Department of Assemblage Obtainment

[Cloudera has filed for an IPO on the NYSE](https://venturebeat.com/2017/03/31/cloudera-files-to-raise-200-million-in-ipo/) (CLDR). They are trying to raise $200 million.

## Not DevOps But Still Cool

[Google announced](https://opensource.googleblog.com/2017/03/a-new-home-for-google-open-source.html?m=1) their new home for open source, [Google Open Source](https://opensource.google.com/). Google has opened a treasure trove of documentation to help companies advance their open source initiatives. [The Changelog episode with Will Norris](https://changelog.com/podcast/245) announcing Google Open Source is a great listen.

## DevOps'ish Tweet of the Week

{{< tweet 848200675674607616 >}}
