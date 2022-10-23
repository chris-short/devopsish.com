+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2017"]
date = 2017-08-06T04:36:29.864Z
description = ""
draft = false
slug = "035"
tags = ["devops", "cloud native", "open source", "kubernetes", "detroit", "google", "password management", "microservices", "Site Reliability Engineering", "SRE", "Docker"]
title = "035: Google's Toxicity, Security, SRE, Kubernetes, and More!"
image ="https://shortcdn.com/devopsish/woodward-ave-downtown-detroit.jpg"
imagealt = "Woodward Avenue in Downtown Detroit"
aliases = [
    "devopsish-035-google-s-toxicity-security-sre-kubernetes-and-more-f4bfadd192c7"
]

+++

It's 67 degrees here in Michigan at the moment. How's the weather where you are? I'm not missing the humidity of the south at all. As I venture out into more of Detroit I'm continually pleased with the choice to move to the Mitten. America's high five has a lot going for it! [Metro Detroit Unemployment Rate Sees Largest Drop In U.S., Now Lower Than Boston, L.A. And New York](http://www.dailydetroit.com/2017/08/03/metro-detroit-unemployment-rate-sees-largest-drop-u-s-now-lower-boston-l-new-york/).

An additional thing that started here in Detroit this week is the [Detroit Go Meetup](https://detroitgolang.com/)! That's right! Detroit is home to quite a few Go developers. When I went to GopherCon I found out that Go developers didn't have a local community in Detroit. That changed this week. [Join us as we welcome Sam Boyer at our first Meetup on August 29th](https://www.meetup.com/DetroitGolang/events/242260260/)!

We are about a month away from [**DevOpsDay Raleigh**](https://www.devopsdays.org/events/2017-raleigh/welcome/). I'm WAY behind in updating the web site. But, why haven't you gotten your tickets yet?!? Do you not realize who is going to be speaking? [Ashley McNamara](https://twitter.com/ashleymcnamara), [Chris Collins](https://twitter.com/chrisindurham), [Nirmal Mehta](https://twitter.com/normalfaults), [ME](https://chrisshort.me), and many more! Oh and someone named [**John Willis](https://twitter.com/botchagalupe)** whom I hear is a big deal. The ticket is already super affordable but, there is a $5 discount code available with code **MEETUP5**. [Get your tickets today](https://www.eventbrite.com/e/devopsdays-raleigh-2017-tickets-34044332515?aff=es2) because is the next week or two we expect them to get scarce.

## People

[Exclusive: Here's The Full 10-Page Anti-Diversity Screed Circulating Internally at Google [Updated]](http://gizmodo.com/exclusive-heres-the-full-10-page-anti-diversity-screed-1797564320): This is fucking despicable. I'm not mad, I'm just utterly disappointed.

[Researcher Who Stopped WannaCry Ransomware Detained in US After Def Con](https://motherboard.vice.com/en_us/article/ywp8k5/researcher-who-stopped-wannacry-ransomware-detained-in-us-after-def-con): Hutchins was arrested for [allegedly creating the Kronos banking malware](https://motherboard.vice.com/en_us/article/pagn7v/malwaretech-wannacry-indictment-kronos-malware).

[This Is Why Your Best Developers Keep Quitting](https://www.fastcompany.com/40443084/this-is-why-your-best-developers-keep-quitting): It's one thing to hire a bunch of junior developers. It's another to retain the experienced people who'll mentor them.

[Do You Suffer From Decision Fatigue](http://www.nytimes.com/2011/08/21/magazine/do-you-suffer-from-decision-fatigue.html?referer=devopsish)? As you navigate a world of choices, revisit this 2011 magazine story on the paralyzing effects of decision fatigue.

[What does the manager of an open team do, anyway?](https://opensource.com/open-organization/17/8/what-open-leader-do) "What would you say you do here?" Sam Knuth's answer involves three principles for open leadership.

[Everyone is not Ops](https://medium.com/@cindysridharan/the-death-of-ops-is-greatly-exaggerated-ff3bd4a67f24): The pragmatic middle-ground

## Process

[A Rant on Usable Security by Jessie Frazelle](https://blog.jessfraz.com/post/a-rant-on-usable-security/): Security is hard but, it can be so much better.

[The SRE model](https://medium.com/@rakyll/the-sre-model-6e19376ef986): Cindy Sridharan's fantastic article on why everyone is not ops makes you rethink the relationship between your development and operations teams. In this article, I am trying to explain how Google approaches the problem and why it scales for our SRE team.

[Why We Broke Our Philosophical Vows to Bring You CircleCI 2.0](https://circleci.com/blog/why-we-broke-our-philosophical-vows-to-bring-you-circleci-2-0/): A couple weeks ago, we released CircleCI 2.0. This was a tremendous effort, involving every person at CircleCI by the time it reached General Availability. Exactly the kind of effort that we try to avoid as a CI/CD company.

[New Bill Seeks Basic IoT Security Standards](http://krebsonsecurity.com/2017/08/new-bill-seeks-basic-iot-security-standards/): Lawmakers in the U.S. Senate today introduced a bill that would set baseline security standards for the government's purchase and use of a broad range of Internet-connected devices, including computers, routers and security cameras.

[Symantec offloads its certs and web security biz to DigiCert](https://www.theregister.co.uk/2017/08/03/symantec_q1_2018/): Symantec sold its Website Security and related PKI solutions to DigiCert, effectively making its spat with Mozilla and Google someone else's problem.

## Tools

[exa](https://the.exa.website/): exa is a modern replacement for ls.

[amicontained](https://github.com/jessfraz/amicontained): Container introspection tool. Find out what container runtime is being used as well as features available.

[DShield Raspberry Pi Sensor](https://github.com/DShield-ISC/dshield): This is a set of scripts to setup a Raspberry Pi as a DShield Sensor.

[Use Docker to Search in 320 Million Pwned Passwords](https://stefanscherer.github.io/use-docker-to-search-in-320-million-pwned-passwords/)

[How Kubernetes certificate authorities work](https://jvns.ca/blog/2017/08/05/how-kubernetes-certificates-work/): Today, let's talk about Kubernetes private/public keys & certificate authorities!

[Kubernetes 1.7 with Tim Hockin](https://www.gcppodcast.com/post/episode-88-kubernetes-1-7-with-tim-hockin/): [Tim Hockin](https://twitter.com/thockin), one of the engineers that started the Kubernetes project, joins [Francesc](https://twitter.com/francesc) and [Mark](https://twitter.com/Neurotic) to talk about all of the cool stuff coming up with Kubernetes 1.7.

[Starting the Avalanche](https://medium.com/netflix-techblog/starting-the-avalanche-640e69b14a06): Application DDoS In Microservice Architectures

[Stratis Is Red Hat's Plan For Next-Gen Linux Storage Without Btrfs](https://phoronix.com/scan.php?page=news_item&px=Stratis-Red-Hat-Project)

[20 Linux commands every sysadmin should know](https://opensource.com/article/17/7/20-sysadmin-commands): curl, python -m json.tool / jq, ls, tail, cat, grep, ps, env, top, netstat, ip address, lsof, df, du, id, chmod, dig / nslookup, iptables, sestatus, and history.

[Cron Syntax Cheatsheet](https://healthchecks.io/docs/cron/): I often forget the order of minute, hours, days, ... I just forgot. This cheatsheet will help.

[Scout2](https://nccgroup.github.io/Scout2/): Security auditing tool for AWS environments

[crunchy](https://github.com/muesli/crunchy): Finds common flaws in passwords. Like cracklib, but written in Go.

[postmortem-templates](https://github.com/dastergon/postmortem-templates): A collection of postmortem templates

[Announcing two New Heptio Open Source Projects: Heptio Ark and Heptio Sonobuoy](https://blog.heptio.com/announcing-two-new-heptio-open-source-projects-heptio-ark-and-heptio-sonobuoy-7cef88a06f8)

[Vi & VIM Keyboard Covers for MacBook and iMac](https://www.editorskeys.com/products/vi-vim-keyboard-covers-for-macbook-imac)

[terraboard](https://github.com/camptocamp/terraboard): A web dashboard to inspect Terraform States

[ChAP: Chaos Automation Platform](https://medium.com/netflix-techblog/chap-chaos-automation-platform-53e6d528371f)

[fabio](https://github.com/fabiolb/fabio): A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by consul.

[learn-regex](https://github.com/zeeshanu/learn-regex): Learn RegEx The Easy Way

## DevOps'ish Tweet of the Week

[![DevOps'ish 035 Tweet of the Week](https://shortcdn.com/devopsish/035-devopsish-tweet-of-the-week.png)](https://twitter.com/bketelsen/status/892141526213591041)
