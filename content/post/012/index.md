+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-02-26T07:07:00.636Z
description = ""
draft = false
slug = "012"
tags = ["devops", "cloud native", "open source", "google", "lambda", "Linus Torvalds"]
title = "012: Week of 1488085200"
image = "/012/blast-door.jpg"
imagealt = "Blast Door"
aliases = [
    "devopsish-weekly-012-week-of-1488085200-4d30ffd92b69"
]

+++

This week has been highlighted by multiple security events

What an incredibly busy week news wise. No matter where you are in your [**DevOps**](https://devopsish.com/) journey it's very likely one of the major events this week affected you. I am in the process of fighting off a sinus infection too so this week was a lot to handle.

## Department of Sane Workplaces

Unless you live under a rock I am almost certain you have heard about the [insanity Susan J. Fowler went through during her time at Uber](https://www.susanjfowler.com/blog/2017/2/19/reflecting-on-one-very-strange-year-at-uber). This shit is #NotOkay, folks, period. If you proposition your coworkers, you are in the wrong. If you harass your coworkers, you are in the wrong. If you cover up sexual misconduct, workplace violence, or any other human resource issue in your organization, **YOU ARE IN THE WRONG**. [I have said this a lot in the past year](https://chrisshort.net/what-the-military-taught-me-about-devops/), I did not spend 11 years in the military so ignorant jerks can harass people. You can read the [incredibly well written piece by Mike Isaac](https://www.nytimes.com/2017/02/22/technology/uber-workplace-culture.html) for an impartial point of view.

## Department of Choice Concepts

[Dana P'Simer](https://github.com/danapsimer) released a pretty nifty tool to [utilize Go with AWS Lambda](https://github.com/danapsimer/aws-api-to-lambda-shim).

## Department of Data Defense

[GitLab released all of their runbooks for public consumption](https://gitlab.com/gitlab-com/runbooks). If you need to create documentation this is a good place to start.

[Google's Project Zero discovered](https://bugs.chromium.org/p/project-zero/issues/detail?id=1139) a [memory leak in a CloudFlare parser](https://blog.cloudflare.com/incident-report-on-memory-leak-caused-by-cloudflare-parser-bug/). This was a pretty gnarly leak. This summary from [Mattias Geniar](https://ma.ttias.be/cloudbleed-cloudflare-reverse-proxies-dumping-uninitialized-memory/) is spot on, "any site behind Cloudflare *might* have leaked info from other sites hosted behind Cloudflare. Even if your HTML was perfectly balanced and strict, your site might've become the victim of another site with imbalanced HTML tags that leaked *your* data."

[Google found a SHA1 collision](https://security.googleblog.com/2017/02/announcing-first-sha1-collision.html) so the already limping hash function is now, for all intents and purposes, dead. Unless you are [Linus Torvalds](https://public-inbox.org/git/CA+55aFxJGDpJXqpcoPnwvzcn_fB-zaggj=w7P2At-TOt4buOqw@mail.gmail.com/) who said, "I doubt the sky is falling for git as a source control management tool. Do we want to migrate to another hash? Yes. Is it 'game over' for SHA1 like people want to say? Probably not."

[Netflix open sourced Stethoscope](http://techblog.netflix.com/2017/02/introducing-netflix-stethoscope.html) this week. "Stethoscope is a web application that collects information for a given user's devices and gives them clear and specific recommendations for securing their systems."

[EFF is reporting that over half of the web's traffic is now encrypted](https://techcrunch.com/2017/02/22/eff-half-the-web-is-now-encrypted/).

## Department of Next Year's Old Tech

[Ansible turned five years old this week!](https://www.ansible.com/blog/happy-birthday-ansible)

## DevOps'ish One-Liner of the Week

I end up sending a lot of work through AWS SQS. This little one liner is handy for blasting more than one message into SQS:

    while read N ; do echo $N ; aws send --region=us-east-1 /ACCT/QUEUE --message "$N" ; done < MESSAGES.txt
