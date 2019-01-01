+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-01-22T09:07:00.307Z
description = ""
draft = false
slug = "007"
tags = ["devops", "cloud native", "open source", "infrastructure", "linux", "google", "microservices", "ntp", "containers"]
title = "DevOps'ish 007: Week of 1485061200"
image = "/007/woc-in-tech.jpg"
imagealt = "Photo Courtesy WOCinTech Chat"
imagecap = "Photo by [#WOCinTech Chat](http://www.wocintechchat.com/)"
aliases = [
    "devopsish-weekly-007-week-of-1485061200-4f3c2ca3481d"
]

+++

What a busy week in the land of [DevOps](https://devopsish.com/)! It seems like everyone has shaken off the holidays and snow days. So without further adieu let's get to it!

## Department of Choice Concepts

Breanne Boland has a great piece on [lessons learned during her first year as a software engineer](http://breanneboland.com/blog/2017/01/11/11-lessons-first-year-software-engineering/). "Timing is everything" as always but her point on curiosity is spot on.

The Cloudcast had a fantastic episode titled, "[Balancing Monolithic Apps and Microservices](http://www.thecloudcast.net/2017/01/the-cloudcast-286-balancing-monolithic.html)". I had a lightbulb click on for one of the products I support while listening to this episode. Everyone has legacy infrastructure. This episode discusses a strategy to deal with the older parts of your applications.

Grant Shipley shared [how to get a full blown OpenShift cluster up and running in thirty minutes](https://blog.openshift.com/openshift-developers-set-full-cluster-30-minutes/). OpenShift is looking more and more appealing.

Jessie Frazelle hacked the bejesus out of CoreOS' Container Linux. [She put graphics drivers in CoreOS, y'all](https://blog.jessfraz.com/post/ultimate-linux-on-the-desktop/)... Graphics drivers! Jess is a glutton for punishment and I admire the hell out of her for it.

Eric Raymond is making the next version of NTP, aptly named NTPsec. He recently made [a comparison of Rust vs. Go for the NTPsec project](https://blog.ntpsec.org/2017/01/18/rust-vs-go.html) that is a good assessment of both languages.

{{< mc >}}

## Department of Dafuq

Remember [last week](/006/), when I linked to a piece from Red Hat about [SELinux stopping a Docker bug dead in its tracks](http://rhelblog.redhat.com/2017/01/13/selinux-mitigates-container-vulnerability/)? [Docker is not too happy about that](http://thenewstack.io/docker-calls-out-red-hat/) for some reason.

[Bruh... Please](https://psiloveyou.xyz/help-me-im-on-tinder-i-don-t-want-to-see-your-code-711de4986ab8#.plk8m2y9b). No one on Tinder wants to look at your code.

## Department of Data Defense

[Google shared their infrastructure security design](https://cloud.google.com/security/security-design/) with the world. They go through a lot of effort to secure the data that makes them dominate. Google's security measures are deep, "We also design custom chips, including a hardware security chip that is currently being deployed on both servers and peripherals. These chips allow us to securely identify and authenticate legitimate Google devices at the hardware level."

## Department of Refreshment and Refurbishment

[Cumulus Networks is releasing its own hardware](http://www.theregister.co.uk/2017/01/19/cumulus_networks_writes_its_name_on_a_white_box/). Cumulus is an open networking operating system and their teams make heavy use of Ansible. It is great to see them branding their own hardware.

## Department of Sane Workplaces

yossorion shared their thoughts on [what they wish they knew before they joined a unicorn](https://gist.github.com/yossorion/4965df74fd6da6cdc280ec57e83a202d). Thinking about taking equity as compensation? I would recommend reading this.

Jérôme Petazzoni penned a fantastic piece on sexism in our industry. [This shit is not okay](http://jpetazzo.github.io/2017/01/15/yes-all-men/) and our industry HAS to fix this right the fuck now (RTFN).

## One-Liner of the Week

The one true way to grep IP addresses:

`egrep -o '[0–9]{1,3}\.[0–9]{1,3}\.[0–9]{1,3}\.[0–9]{1,3}'`