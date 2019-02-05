+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-04-09T11:11:01.056Z
description = ""
draft = false
slug = "018"
tags = ["devops", "cloud native", "open source", "kubernetes"]
title = "018: Week of 1491710400"
image = "/018/stormtrooper-lightbulb.jpg"
imagealt = "How many Stormtroopers does it take to screw in a light bulb?"
aliases = [
    "devopsish-weekly-018-week-of-1491710400-5677d6d9828b"
]

+++

I did so many different things this week! DevOps is really great and my role working between teams really brings me different challenges daily. Be it cultural or technical I am rarely doing the same thing hour-by-hour. Two things that did take a lot of my time this week were building new MySQL. database replicas (you know... state) and Mac server monitoring.

Surprisingly, I maintain a Mac server or two for package building for one of our products. There are literally no "out of the box" monitoring solutions for Mac OS X anymore. This is equally unsurprising and indicative of how a platform that is used by so many in DevOps is not used for production workloads. There is nothing wrong with this; it is just odd to me monitoring a Mac is such a cumbersome task (no it's not just FreeBSD).

In the world of [**DevOps**](https://devopsish.com/) otherwise, it has been a pretty busy week. Let's have a look!

## Department of Choice Concepts

[Naveen](https://medium.com/@snaveen) shared a great list of [tools that make working with Kubernetes easier](https://medium.com/google-cloud/tools-that-make-my-life-easier-to-work-with-kubernetes-fce3801086c0). This is a kind of must have list. For whatever reason, I cannot get tab completion working with kubectl. ¯\\\_(ツ)\_/¯

Speaking of [**Kubernetes](https://kubernetes.io/)**, I have been tinkering with it more and more (who isn't?). I really enjoy the tool and the concepts of k8s but, the documentation needs some serious help. I have volunteered to help the [sig-docs](https://kubernetes.slack.com/archives/C1J0BPD2M/p1491607569009282) team to clean this up. If you have some cycles please consider helping out, the team is VERY receptive and accepting. For the record, [Joe Beda pushed me to do something](https://twitter.com/jbeda/status/850377020538200064/photo/1).

[DevOps has gone mainstream. Is that a good thing?](https://medium.com/devops-journeys/devops-has-gone-mainstream-is-that-a-good-thing-1d698baaa12b)

## Department of Refreshment and Refurbishment

Here is something really off the wall, [iodine: IPv4 over DNS tunnel](http://code.kryo.se/iodine/). This is something I would have used in various military networks of yesteryear to prove security is not as good as they thought it was. Enforce ports AND protocols, folks.

Jenkins announced their long overdue improvement to their UI, [Blue Ocean, went 1.0](https://jenkins.io/blog/2017/04/05/welcome-to-blue-ocean/). I am excited to get this out there and start tinkering with it. I feel like the Jenkins UI is daunting to new users.

## Department of Data Defense

A [gnarly Xen vulnerability](https://xenbits.xen.org/xsa/advisory-212.html) was announced this week. Luckily this vulnerability only affects x86–64 guests. [Google's Project Zero has a detailed article detailing the vulnerability](https://googleprojectzero.blogspot.com/2017/04/pandavirtualization-exploiting-xen.html) if you are interested.

Security is an important aspect of every information worker's daily routine. To ignore this is to end up a headline in a newspaper regarding your breach. I think it might be past time for the DevOps community to be concerned about [container security](https://blog.acolyer.org/2017/04/03/a-study-of-security-vulnerabilities-on-docker-hub/).

## Department of Assemblage Obtainment

Obviously, VMware vCloud Air was a horrible idea. VMware Cloud on AWS put vCloud Air on the back burner in a big way. [The bastardized business unit is to be sold to OVH](http://www.vmware.com/company/news/releases/vmw-newsfeed.OVH-Announces-Intent-to-Acquire-VMware-vCloud-Air-Business.2153983.html).

## Department of Happy Little Clouds

Werner Vogels announced this week an [AWS region is coming to Stockholm, Sweden](http://www.allthingsdistributed.com/2017/04/aws-announces-eu-stockholm-region.html). "AWS EU (Stockholm) Region will have three Availability Zones and will be ready for customers to use in 2018."

## Department of Sane Workplaces

Don't read "[The Minimally-nice Open Source Software Maintainer](http://brson.github.io/2017/04/05/minimally-nice-maintainer)" as a Bible but it does merit a bookmark for when your open source works make you see red.

In a surprise to no one, [San Francisco has gotten so expensive, some tech companies can't convince employees to move there](http://www.cnbc.com/2017/04/06/san-francisco-cost-of-living-pricing-out-tech-companies-workers.html). It would take an absurd salary to get me to move to SF at this point.

## Department of Interior

I wrote some Go and wrote about it! [Golang to the rescue: Saving DevOps from TLS turmoil](https://opensource.com/article/17/4/testing-certificate-chains-34-line-go-program).

## DevOps'ish Tweet of the Week

Another tweet from Kelsey Hightower this week. I am particularly interested in seeing how this pans out:

{{< tweet 849617831268417538 >}}