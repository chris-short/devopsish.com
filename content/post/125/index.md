+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-04-28T07:00:00Z
description = "125"
draft = false
slug = "125"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "container", "security", "system", "Docker Hub breach", "docker", "docker hub", "compromise"]
title = "125: Docker Hub Breach, "
image = "/125/docker-hub-breach.png"
imagealt = "Docker Hub breach impacting at least 190,000 accounts"

+++

> **NOTE**: Please read my [Disclaimer](https://devopsish.com/terms/) before breaking out the tar and feathers.

What a series of unfortunate events for [**Docker**](http://petty.company) in 2019. In what appeared to be a massive talent flush due to what looks like a potential earnings miss, the Great Docker Culling of 2019 happened. Docker appears to have laid off the vast majority of its well-known talent. [Andrea Luzzardi](https://twitter.com/aluzzard), [Sam Alba](https://www.linkedin.com/in/samalba/), and [Gareth Rushgrove](https://twitter.com/garethr) are among a slew of recent [Docker layoffs](https://devopsish.com/117/) discussed in this newsletter earlier this year. According to one source teams were, "killed," and Docker, "missed their number, and by a lot."

Fast forward to Friday night on the US east coast (like we weren't going to notice?!?). Many people (myself included) [received an e-mail from Docker](https://devopsish.com/125/docker-hub-breach-email.pdf) about a **Docker Hub breach** impacting at least 190,000 accounts. According to the e-mail, "Data includes usernames and hashed passwords... as well as Github and Bitbucket tokens for Docker autobuilds." Audit any Docker Hub tokens right now. Docker also, "revoked GitHub tokens and access keys. This means your autobuilds will fail." Nothing like a page on a weekend because Docker broke your builds. Check your [Docker Hub Linked Accounts](https://cloud.docker.com/settings) and re-link them. You'll then likely have to do a weird do-si-do in the Build config of one of your image pages to get everything working as is.

This Docker Hub breach is a **significant breach** if the tokens of Alpine, busybox, node, or any database images were compromised. These compromised builds could have easily permeated into the wild with little to no knowledge. From my point of view, the only way to be sure you're not affected is to somehow verify with the image provider their account has been cleaned up (as [directed by Docker](https://success.docker.com/article/docker-hub-user-notification), (note the URL, *success*) and redeploy your all containers. Why? Because some upstream likely used Docker Hub even if you didn't. In other words, "Nuke the entire site from orbit. It's the only way to be sure."

*What a Docker freaking mess we're in*. At the risk of being extra petty, I can't help but mention I started using [Quay](https://quay.io/) when I joined Red Hat and I'm pretty happy with it. It's a container registry, not an Alexander Wang piece. Quay is not perfect but, I'm not expecting a whole lot here. It looks like I'll be moving more images off Docker Hub in the future.

[**Hit send on your last tech job application**](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email1)  
One application, many tech opportunities. Indeed Prime makes job hunting quick and easy. Save time and let us do the heavy lifting for you by matching you with top tech companies. [Join for free today](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email1)! *SPONSORED*

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*

{{< sponsor-blurb >}}

## DevOps'ish Top Five from Last Week

1. [How much does a DevOps engineer make?](https://enterprisersproject.com/article/2019/4/devops-engineer-salary)
1. [What Happened When The DEA Demanded Passwords From LastPass](https://www.forbes.com/sites/thomasbrewster/2019/04/10/what-happened-when-the-dea-demanded-passwords-from-lastpass/#e337d747ebeb)
1. [The Problem with SSH Agent Forwarding](https://defn.io/2019/04/12/ssh-forwarding/)
1. [The 5 communication problems that destroy company morale](https://qz.com/work/1587170/the-five-types-of-communication-problems-that-destroy-company-morale/)
1. [Alikhll/golang-developer-roadmap: Roadmap to becoming a Go developer in 2019](https://github.com/Alikhll/golang-developer-roadmap)

## People

[Kubernetes jobs hunt: How to land that role](https://enterprisersproject.com/article/2019/4/kubernetes-jobs-hunt-how-land-role) — Trying to get a job working with Kubernetes? Consider these five tips.

[DevOps'ish Telegram](https://devopsi.sh/telegram) — Join the over 230+ DevOps, Kubernetes, and SRE professionals discussing real world problems and solutions to modern day issues.

## Process

[**Accelerate: State of DevOps 2019 Survey**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5):  Nicole Forsgren, PhD is conducting the State of DevOps 2019 Survey. Your input is incredibly important. On several occasions, I have referenced [the 2018 report](https://cloudplatformonline.com/2018-state-of-devops.html) since its release for real-world work that impacts real numbers. Nicole's group also wrote, [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2), which I cannot recommend enough either.

PROCESS

## Tools

[Packets-per-second limits in EC2](https://stressgrid.com/blog/pps_limits_in_ec2/) — "[W]e determined that each EC2 instance type has a packet-per-second budget. Surprisingly, this budget goes toward the total of incoming and outgoing packets. Even more surprisingly, the same budget gets split between multiple network interfaces, with some additional performance penalty."

[All That You Need to Know About Microsoft's New Programming Language: Bosque](https://dev.to/0xrumple/all-what-you-need-to-know-about-microsoft-s-new-programming-language-bosque-38c0) — "The Bosque programming language is a Microsoft Research project that is investigating language designs for writing code that is simple, obvious, and easy to reason about for both humans and machines."

[cdr/sshcode](https://github.com/cdr/sshcode) — Run VS Code on any server over SSH

[operator-framework/community-operators](https://github.com/operator-framework/community-operators) — The canonical source for Kubernetes Operators that appear on OperatorHub.io, OpenShift Container Platform, and [OKD](https://www.okd.io/)

## DevOps'ish Tweet of the Week

{{< tweet 1118816110571339778 >}}