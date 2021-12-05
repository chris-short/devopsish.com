+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2016"]
date = "2016-12-25T00:00:00Z"
description = ""
draft = false
slug = "003"
tags = ["devops", "cloud native", "open source", "containers"]
title = "003: Week of 1482642000"
image = "/003/wrapping-paper.jpg"
imagealt = "Merry Christmas and Happy DevOps! 🎅 🎄 🤶"
aliases = [
    "003-week-of-1482642000-885ce5d0fee1"
]
+++

Merry Christmas and Happy [**DevOps**](https://devopsish.com/)! 🎅 🎄 🤶

Quick hitter this week as the family watches Elf.

## Department of Refreshment and Refurbishment

[Python 3.6 was released](https://www.python.org/downloads/release/python-360/)! The [full changelog is available](https://docs.python.org/3.6/whatsnew/changelog.html#python-3-6-0) for your review.

Ruby 2.4.0 was released! The [full changelog is also available](https://github.com/ruby/ruby/blob/v2_4_0/NEWS).

[GitLab 8.15 was released](https://about.gitlab.com/2016/12/22/gitlab-8-15-released/)! I am not a huge fan of GitLab's UI but the Auto Deploy feature looks intriguing.

[OpenJDK on Windows? Yep! Thanks, Redhat](https://developers.redhat.com/blog/2016/06/27/openjdk-now-available-for-windows/).

[Dominick Krachtus](http://ttlequals0.com/) released a nice script to quickly spin up an OpenVPN instance in AWS called [autovpn](https://github.com/ttlequals0/autovpn)

[Tony Narlock](http://www.git-pull.com/) has made his upcoming book, [The Tao of tmux,](https://leanpub.com/the-tao-of-tmux) available to read for free.

## Department of Choice Concepts

[David Gilbertson](https://hackernoon.com/@david.gilbertson?source=post_header_lockup) shares some performance tips during his experience, "[making the fastest site in the world](https://hackernoon.com/10-things-i-learned-making-the-fastest-site-in-the-world-18a0e1cdf4a7#.xyp27gsp2)"

[Julia Evans](http://jvns.ca/) has written a fantastic piece on [container networking](http://jvns.ca/blog/2016/12/22/container-networking/) that I would highly recommend taking a look at.

## Department of Next Year's Old Tech

[ClusterHQ shut its doors](https://clusterhq.com/2016/12/22/clusterf-ed/). Their software is still [open source](https://github.com/ClusterHQ/).

## DevOps'ish One-Liner of the Week

Should you be in a position and need to figure out what systems are holding a high number of connections to a system login and try this out:

    netstat -n | awk '{print $5}' | egrep -o '[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}' | sort | uniq -c | sort -n
