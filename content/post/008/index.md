+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2017"]
date = 2017-01-29T08:02:00.453Z
description = ""
draft = false
slug = "008"
tags = ["devops", "cloud native", "open source", "observability", "linux", "Docker"]
title = "DevOps'ish 008: Week of 1485666000"
image ="https://shortcdn.com/devopsish/gopherize-yourself-fools.png"
imagealt = "Gopherize Yourself, Fool"
aliases = [
    "devopsish-weekly-008-week-of-1485666000-c7e6d9a9790a"
]

+++

Oh look! There's a 666 in the epoch this week... Great! But, as one of my co-workers and I always say, we're going to "will it" to be a good week in [**DevOps**](https://devopsish.com/) . It usually works out too.

## Department of Choice Concepts

[Nitin Agarwal breaks down the Docker filesystem](https://medium.com/@nagarwal/docker-containers-filesystem-demystified-b6ed8112a04a#.y03d2gbvf) (AUFS). It is a rather simplistic presentation. If you know someone struggling with the concepts it's definitely worth a read.

[Brendan Gregg](https://twitter.com/brendangregg) built out a very simple page containing ALL his works on [Linux Performance](http://www.brendangregg.com/linuxperf.html). I do not think you could bookmark this page enough.

![[Linux Performance](http://www.brendangregg.com/linuxperf.html) by [Brendan Gregg](https://twitter.com/brendangregg)](https://shortcdn.com/devopsish/linux-observability-tools.png)  *[Linux Performance](http://www.brendangregg.com/linuxperf.html) by [Brendan Gregg](https://twitter.com/brendangregg)*

## Department of Data Defense

There is some pretty insane stuff happening in Russia. Some pretty [senior cybersecurity folks are being held by a military tribunal](https://www.buzzfeed.com/sheerafrenkel/theres-something-very-weird-happening-inside-russias-cyberse?utm_term=.mjeldYBvYv#.soZRp8Yg8g). Keep an eye on this one.

## Department of Refreshment and Refurbishment

[DZone](https://dzone.com/) recently released their [Guide to DevOps: Continuous Delivery and Automation](https://dzone.com/guides/devops-continuous-delivery-and-automation). Lots of cool concepts and stories for you to ponder over.

## Department of Happy Little Clouds

Did you hear that [SoftLayer was handing over the reigns to BlueMix](http://blog.softlayer.com/2016/softlayer-ibm-bluemix-integration)? Me neither (sorry, not sorry). [The transition appears to be going over like a fart in church](http://www.theregister.co.uk/2017/01/26/ibm_softlayer_having_meltdown/). Big Blue where are you?

AWS went full on IPv6 this week (kinda). [AWS has rolled out IPv6 to a large swath of services](https://aws.amazon.com/blogs/aws/aws-ipv6-update-global-support-spanning-15-regions-multiple-aws-services/). It is remarkable to me that IPv6 is not embraced in the US even now.

## Department of Interior

We found two annoying bugs this week during our daily DevOps'ing. One bug involved [an issue with the notoriously awful GitLab UI](https://chrisshort.net/gitlab-annoyance-private-to-public-repos/). GitLab has told me they are trying to fix this issue. The other bug was around [AWS's text formatting](https://chrisshort.net/find-ec2-instances-that-are-missing-tags/). Depending on which region you are querying the formatting can be wildly different.

## Not DevOps But Still Cool

[Gopher Academy is launching training courses](http://finance.yahoo.com/news/gopher-academy-launches-training-programs-134500474.html). I will be attending the [Introduction to Buffalo — Web Development in Go](https://www.bigmarker.com/gopheracademy/Introduction-to-Buffalo-Web-Development-in-Go) on January 31, 2017. Take a look at what is coming up.

## DevOps'ish One-Liner of the Week

If you are looking to show AWS instances that do not have a particular tag (specified by key); you can execute this command to find them:

    aws ec2 describe-instances --query "Reservations[].Instances[].{ID: InstanceId, Tag: Tags[].Key}" --output text | grep -v Name
