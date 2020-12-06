+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2017"]
date = 2017-02-19T12:31:08.541Z
description = ""
draft = false
slug = "011"
tags = ["devops", "cloud native", "open source", "database", "linux", "google", "CAP Theorem", "Linus Torvalds", "Docker"]
title = "011: Week of 1487480400"
image = "/011/alexander-graham-bell-birthplace.jpg"
imagealt = "Alexander Graham Bell Birthplace, Edinburgh, Scotland, United Kingdom"
aliases = [
    "devopsish-weekly-011-week-of-1487480400-952ca358aec1"
]

+++

Alexander Graham Bell Birthplace, Edinburgh, Scotland, United Kingdom

My apologies for the delay in this week's DevOps'ish newsletter. When I opened the ole MacBook last night to hammer it out it dawned on me how exhausted I was. Instead of this newsletter I spent time with family and went to bed early. Sorry, not sorry. It was an eventful week in the world of [**DevOps**](https://devopsish.com/) though.

## Department of Choice Concepts

[Google Spanner](https://cloud.google.com/spanner/) was introduced as, "The first horizontally scalable, globally consistent, relational database service." After some initial reading on [Wired about Spanner](https://www.wired.com/2017/02/spanner-google-database-harnessed-time-now-open-everyone/) my interest has piqued. There is a white paper in regards to [CAP Theorem and Spanner](https://cloud.google.com/spanner/docs/whitepapers/SpannerAndCap.pdf) that is like reading a sci-fi novel in which laws of physics are bent to humanity's will. But the true gem in Spanner is [Google's handling of time](http://static.googleusercontent.com/media/research.google.com/en/us/archive/spanner-osdi2012.pdf) (dubbed TrueTime) to create consistency.

Software licensing is becoming an incredibly important factor in DevOps. You might have cobbled together some tools and some code to solve a problem but can your employer legally use it? [Tom Callaway is the person behind making Fedora legally legit](https://lwn.net/SubscriberLink/714524/0c495ef932cd49a8/). The story about his work in the Fedora teams is a must read.

## Department of Data Defense

[OpenSSL 1.1.0 received an update this week to mitigate CVE-2017–3733](https://www.openssl.org/news/vulnerabilities.html#2017-3733). Not a show stopper for most people. Has the Heartbleed stress finally gone its course surrounding OpenSSL updates?

[Instapaper published their recent outage postmortem this week](https://medium.com/making-instapaper/instapaper-outage-cause-recovery-3c32a7e9cc5f#.tz9u7z33m). It reminded me of an ever present problem in DevOps; **who owns state**? As much as we want to abstract state further away from development, we have to maintain state in a very hands on way or we're doomed. Instapaper offloaded their state to Amazon RDS. An unknown and undocumented (by Amazon) 2TB limit in ext3 doomed the Instapaper RDS instance.

I am a sucker for a good cheatsheet or command reference. [Bobbin Zachariah created a good Docker cheatsheet](http://linoxide.com/linux-how-to/docker-commands-cheat-sheet/) (albeit aesthetically awful) that is worth keeping around.

## Department of Discussion

[Linus Torvalds, creator of the Linux kernel, made some headlines this week](https://www.theregister.co.uk/2017/02/15/think_different_shut_up_and_work_harder_says_linus_torvalds/) at Open Source Leadership Summit. But, the real story is not Linus' gruff attitude it's the fact that he acknowledged that process (not code) is the real problem in large projects.

## Department of Next Year's Old Tech

[Anne Currie reminds us that strictly Operations jobs are an outmoded profession](https://medium.com/@anne_e_currie/kubernetes-the-destroyer-of-worlds-4615dec3027b#.jv62ksuu8). Automation will eventually eliminate tier 2 type positions and those folks will need to either become DevOps thinking people or change professions entirely. Technology is evolving around us, what are you doing to keep up?

## Not DevOps But Still Cool

[Brian Krebs had some news on folks that have messed with him personally.](https://krebsonsecurity.com/2017/02/men-who-sent-swat-team-heroin-to-my-home-sentenced/) Justice is being served and some of the attackers are apologetic to Krebs.

## DevOps'ish One-Liner of the Week

This week's one-liner is pretty simple but one that I actually used this week. We needed to run [pt-query-digest](https://www.percona.com/software/database-tools/percona-toolkit) against a week's worth of MySQL slow query logs. The problem was the logs were rotated daily and I needed a single file for input.

    ls -1rt /var/lib/mysqllogs/*-slow-log-* | tail -n 7 | while read N ; do cat $N >> /tmp/slow-query.log ; done
