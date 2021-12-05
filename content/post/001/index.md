+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2016"]
date = 2016-12-11T00:00:00Z
description = ""
draft = false
slug = "001"
tags = ["devops", "cloud native", "open source", "aws", "amazon", "docker", "nodejs"]
title = "001: Week of 1481432400"
aliases = [
    "001-week-of-1481432400-696c2c8043f1"
]

+++

Welcome to this week's edition of DevOps'ish where we cover Dev, Ops, and all the ish in between.

## Department of Choice Concepts

I love the idea of [dumping XML and JSON for HTML 5](https://blog.gladwell.me/html-microservices.html). Despite having to block people trying to pick fights on Twitter, this idea has been pretty well received. I would love to see the frustrations of JSON cast aside for something less syntactically challenging and more human readable.

## Department of Happy Little Clouds

[Ryan Scott Brown might have beat Amazon to the punch](https://twitter.com/ryan_sb/status/806884324805115906) but [AWS has launched a region in Canada](https://aws.amazon.com/blogs/aws/now-open-aws-canada-central-region/)! 🇨🇦 🇨🇦 🇨🇦
The general consensus is if a company that is doing business in Canada they are likely going to be diving head first into this AWS region. [Canadian privacy laws](http://www.servercloudcanada.com/2015/09/canadian-privacy-laws-canadian-cloud-primer-canadian-businesses/) make sure a lot of Canadian PII does not leave the county.

Speaking of Amazon and privacy... [A developer interviewing at Amazon had a rather unusual experience](http://shivankaul.com/blog/2016/12/07/clean-your-desk-yet-another-amazon-interview-experience.html) taking a proctored test. He ended up terminating the interview early and then as the proctor was unable to clean things up on the dev's machine the dev terminated the termination. "The normalization of privacy violation has never felt more real."

There is another example where [the dev being interviewed rejected out right to a proctored test](https://rajk.me/amazon-interview-experience/) over privacy concerns. Instead, the dev offered to do a face-to-face. Amazon has yet to respond.

## Department of Dafuq

LinkedIn found an issue with longer garbage collection times from their Java app running in cgroups. "[We found that Java applications can have more and longer application pauses when using CFS (Completely Fair Scheduler) in conjunction with CFS Bandwidth Control quotas.](https://engineering.linkedin.com/blog/2016/11/application-pauses-when-running-jvm-inside-linux-control-groups)"

[Alice Goldfuss](https://twitter.com/alicegoldfuss) sparked off a fire storm that she likely was not given enough credit for starting with the wonderfully written [SysAdvent](http://sysadvent.blogspot.com/) piece titled, "[Day 6 — No More On-Call Martyrs](http://sysadvent.blogspot.com/2016/12/day-6-no-more-on-call-martyrs.html)." Reading [some](https://lobste.rs/s/djmmbg/no_more_on_call_martyrs) [of](https://twitter.com/alicegoldfuss/status/806328359768690688) [the](https://twitter.com/alicegoldfuss/status/806329196683415561) [discussion](http://naildrivin5.com/blog/2016/12/07/on-call.html) with [Andy Williams' "It's The Most Wonderful Time Of The Year"](https://www.youtube.com/watch?v=gFtb3EtjEic) playing is kinda comical (in a sick sort of way). 🎄🎅🎄🎅

## Department of Continuous Continuum

[Travis CI announced a new cron feature](https://blog.travis-ci.com/2016-12-06-the-crons-are-here)! Test your stuff all day!

[Node.js v7 has updated V8 to 5.4](https://nodejs.org/en/blog/community/update-v8-5.4/) and Node.js is trying to make itself [VM-neutral](https://nodejs.org/en/blog/weekly-updates/weekly-update.2016-12-02/) (which is great news).

## Department of Sane Workplaces

I wrote an article for DZone discussing [**empathy** that is so desperately needed in DevOps](https://dzone.com/articles/empathy-the-emerging-art-in-devops-1).

[Don Denoncourt](http://twitter.com/denoncourt) over at [Corgibytes](http://corgibytes.com/) has an interesting piece on what to do about a problem we all have... [Getting older](http://corgibytes.com/blog/2016/12/06/getting-old-er-in-tech/). Oh and Corgibytes has the best logo.

## Department of Assemblage Obtainment

[Infinit was acquired by Docker](https://blog.docker.com/2016/12/docker-acquires-infinit/) giving Docker the potential for distributed storage in their product offerings (which is long overdue, in my opinion). More on [Infinit from Crunchbase](https://www.crunchbase.com/organization/infinit).

## Department of Next Year's Old Tech

I have had a few discussions this week about how configuration management platforms like Ansible, Puppet, Chef, etc. are going to start fading into the background as containers and Kubernetes gain popularity. What do you think?

## Not DevOps But Still Cool

Anil Dash and Fog Creek launched a new product called [Gomix](https://gomix.com/community/). Show it off to your relatives during the holidays and spark some intrigue in coding if you can.

Red Hat gave Duke University a $180,000 gift that will, "[assist students who have project ideas that use open-source software to advance humanitarian issues](https://today.duke.edu/2016/11/red-hat-gift-spurs-open-source-ideas-duke)." Two seniors are building a specialized prosthetic arm for a cake decorator using open source software.

## DevOps'ish One-Liner of the Week

I needed to figure out how big some Amazon S3 buckets were this week and found there was not an obvious way but at least [serverfault](http://serverfault.com/questions/84815/how-can-i-get-the-size-of-an-amazon-s3-bucket) netted this beauty:

    aws s3api list-objects --bucket BUCKET_NAME --output json --query "[sum(Contents[].Size), length(Contents[])]" | awk 'NR!=2 {print $0;next} NR==2 {print $0/1024/1024/1024" GB"}'
