+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-07-09T06:01:00.961Z
description = ""
draft = false
slug = "031"
tags = ["devops", "cloud native", "open source", "kubernetes", "interview", "mental health", "hiring", "gophercon"]
title = "031: Let's Encrypt, Go, Kubernetes, zinc, Mental Health, Interviewing"
image = "/031/cheeseman-park.jpg"
imagealt = "Cheesman Park in Denver, Colorado (I went ghost hunting here once)"
aliases = [
    "devopsish-031-let-s-encrypt-go-kubernetes-zinc-mental-health-interviewing-400a4f11fdf7"
]

+++

This week was nuts. We dealt with a service degradation due to issues between our CDN and data center edge network. On a long, holiday weekend it's the last thing you want to deal with. There were eighteen action items to come out of the post mortem (which was long enough to merit an executive summary). This was one of the weirder issues I have ever seen as it involved three different companies and a few bad hops in a network path. [I quoted Baruch Sadogursky two weeks ago](/029/), "Pain is instructional." It definitely is! Meanwhile, my company, Bankrate, was [getting acquired by Red Ventures](http://www.thedrum.com/news/2017/07/04/red-ventures-digs-deep-bankrate-website-124bn-personal-finance-drive) for $1.24 billion.

Hopefully, the week ahead will be calmer. Doubtful given I'll be in Atlanta on Monday, Denver on Tuesday, back in North Carolina on Sunday, and then back to Michigan later the following. Next week's edition of DevOps'ish Weekly will be written right after the conclusion of [GopherCon 2017](https://gophercon.com/)! I'm attending GopherCon for the first time ever and am so thankful to have the opportunity to do so. If you're there ask me for a DevOps'ish sticker.

[**Full Stack Fest 2017: Problems of today, wonders from the future.**](https://2017.fullstackfest.com)  
Barcelona, 4–8 Sept. 2017  
Are you a curious mind? [Full Stack Fest](https://2017.fullstackfest.com) is a week-long conference based in the amazing city of Barcelona that peeks into the web of tomorrow. Serverless, Blockchain, WebVR, Distributed Web, Progressive Web Apps... Come and see! Early bird tickets available with a 10% discount using the code DEVOPSISH. *SPONSORED*

## Department of Choice Concepts

[Let's Encrypt Wildcard Certificates Coming January 2018](https://letsencrypt.org//2017/07/06/wildcard-certificates-coming-jan-2018.html): "Wildcard certificates will be offered free of charge via our upcoming ACME v2 API endpoint. We will initially only support base domain validation via DNS for wildcard certificates, but may explore additional validation options over time."

[HTTPS for free in Go, with little help of Let's Encrypt](https://blog.kowalczyk.info/article/Jl3G/https-for-free-in-go.html): Here's how to start HTTPS web server that uses free SSL certificates from Let's Encrypt.

[zinc](https://github.com/PressLabs/zinc): Route 53 zone manager. Policy Records on the Cheap.

[sops](https://github.com/mozilla/sops): sops is an editor of encrypted files that supports YAML, JSON and BINARY formats and encrypts with AWS KMS and PGP (by Mozilla).

[goreleaser](https://github.com/goreleaser/goreleaser): GoReleaser builds Go binaries for several platforms, creates a GitHub release and then pushes a Homebrew formula to a repository. All that wrapped in your favorite CI.

[Ultimate Guide: Self-Hosted Alternatives to Cloud Apps](http://blog.ssdnodes.com/blog/ultimate-guide-self-hosted-alternatives-to-cloud-apps)

[Kubernetes Playground](http://labs.play-with-k8s.com/): This is so cool! Stand up a Kubernetes cluster with dashboard and everything in seconds to tinker with for up to four hours at a time.

[Using a GPG key for SSH Authentication](http://ryanlue.com/posts/2017-06-29-gpg-for-ssh-auth): PGP keys and SSH keys are different. It took me longer than I care to admit to understand this, given that the first StackExchange thread I found on the subject made it pretty clear that it's not trivial to use one where you're supposed to use the other.

[How a 20-year old kernel feature helped USDS improve VA's network](https://medium.com/the-u-s-digital-service/how-a-20-year-old-kernel-feature-helped-usds-improve-vas-network-33109cbcb2e6): "this bug is fascinating because we started debugging Ruby on Rails from AWS and found the root cause in the NSOC Cisco Routers thanks to an ancient feature in the Linux kernel."

[kube-shell](https://github.com/cloudnativelabs/kube-shell): Kubernetes shell - An integrated shell for working with the Kubernetes CLI

[kubeval](https://github.com/garethr/kubeval): Validate your Kubernetes configuration files, supports multiple Kubernetes versions

[Open Sourcing Iris and Oncall](https://engineering.linkedin.com/blog/2017/06/open-sourcing-iris-and-oncall): Iris, named after the Greek goddess of messages, is our open-sourced solution for incident escalation and reliable messaging, and has provided LinkedIn with fast, automated escalations for almost two years now.

[OpenBSD Will Get Unique Kernels on Each Reboot](https://www.bleepingcomputer.com/news/security/openbsd-will-get-unique-kernels-on-each-reboot-do-you-hear-that-linux-windows/): A new feature added in test snapshots for OpenBSD releases will create a unique kernel every time an OpenBSD user reboots or upgrades his computer.

[Netflix Platform Engineering — we're just getting started](https://medium.com/netflix-techblog/neflix-platform-engineering-were-just-getting-started-267f65c4d1a7): As Netflix continues to evolve and grow, so do our engineering challenges. The nature of such challenges changes over time — from "greenfield" projects, to "scaling" activities, to "operationalizing" endeavors — all at great scale and break-neck speed.

## Department of Dafuq

[RIP, Systems Administrator, Welcome DevOps](https://www.informationweek.com/devops/rip-systems-administrator-welcome-devops/a/d-id/1329208): While the traditional sys admin role may fade away, those who are willing to change can take an exciting journey with cloud and DevOps.

[Two Commits That Wrecked the User Experience of Git](https://redfin.engineering/two-commits-that-wrecked-the-user-experience-of-git-f0075b77eab1): Git didn't have to be so obnoxious, but these two commits set a terrible, unfixable precedent

[7 Specific Suggestions to Sabotage DevOps Simply](http://squad-twelve.com/2017/07/03/7-specific-suggestions-to-sabotage-devops-simply/): Have you ever felt like people were conspiring to make DevOps fail? They probably had good intentions but they just made DevOps more difficult than it should be. What if it was actually intentional? The resistance gets organized...

## Department of Assemblage Obtainment

[SoundCloud Cuts 40% of Staff in Push for Profitability](https://www.bloomberg.com/news/articles/2017-07-06/soundcloud-cuts-40-percent-of-staff-in-bid-to-remain-independent): Music service will close offices in San Francisco, London

[Microsoft plans thousands of job cuts in a sales staff overhaul to fuel cloud growth](http://www.cnbc.com/2017/07/06/microsoft-will-layoff-thousands-of-employees.html): Microsoft's layoffs will mostly affect sales, and thousands of jobs will be cut. Most of the changes will affect employees outside of the U.S.

## Department of Sane Workplaces

[Depression is not a sign of weakness](https://medium.com/@ashleymcnamara/depression-is-not-a-sign-of-weakness-478d55ba66f9): "What you don't see is how terribly afraid I am of my own code, what if it's bad? What if they laugh at me? What if they see how much I actually don't know? Will I ever know enough?"

[It's 2017 and Mental Health is still an issue in the workplace](https://medium.com/@OlarkLiveChat/its-2017-and-mental-health-is-still-an-issue-in-the-workplace-61efbef092f): "We are in a knowledge economy. Our jobs require us to execute at peak mental performance. When an athlete is injured they sit on the bench and recover. Let's get rid of the idea that somehow the brain is different."

[Finding, and Landing, the Right Job for You](https://devops.com/finding-landing-right-job/): Finding the right job is really hard. Take a look at [my LinkedIn profile](https://www.linkedin.com/in/christopherbshort/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BxgmsXBp6RqOuzgj8Wke%2B7Q%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-identity_welcome_message) and you'll see evidence of this fact. Finding the right balance of challenge and culture is very hard. These tips on navigating job hunting from [Conor Delanbanque](https://twitter.com/ConorDevOps) are a good start.

[How to Interview Engineers](http://blog.triplebyte.com/how-to-interview-engineers): On the other side of job seeking is hiring. As a hiring manager, I am finding it very challenging to get people to open up during that initial phone call. I want details but not rambling, I want low ego but please tell me what you're proud of. This how to is good and I especially think asking every candidate the same questions is very important.

## DevOps'ish Tweet of the Week

[![031 Tweet of the Week](/031/031-tweet-of-the-week.png)](https://twitter.com/chrisshort/status/882960128445747202)
