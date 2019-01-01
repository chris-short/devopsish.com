+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-03-05T07:07:00.961Z
description = ""
draft = false
slug = "013"
tags = ["devops", "cloud native", "open source", "kubernetes"]
title = "013: Week of 1488690000"
image = "/013/macbook-code-editor.jpg"
imagealt = "MacBook Running an IDE"

+++

I have been sick all week. I have pushed through it as much as possible but this was not a great week physically. However, there is plenty to discuss in the land of [**DevOps**](https://devopsish.com/).

{{< mc >}}

## Department of Data Defense

The Amazon S3 outage is the big story of the week. How many of you were impacted by it. I was to a minimal extent. Our products have been architected for failure pretty well. There was a little work to be done during the outage to work around one issue. Aside from that my time was spent monitoring things anticipating the catastrophe to expand (which it did to an extent). This did not cause any additional burden on my teams and I though. Why am I not mentioning [the reason behind the outage](https://aws.amazon.com/message/41926/)? Because it should not have been as devastating as it was. Folks, the cloud is still something you have to manage. Remember [error budgets from Google's Site Reliability Engineering](https://landing.google.com/sre/book/chapters/introduction.html) book? You have to anticipate outages and down time for just about everything in this world. Your code should not depend on one cloud provider's regional resource, ever. **Diversify your cloud**, folks!

## Department of Choice Concepts

Mattias Geniar announced that his [DNS Spy](https://dnsspy.io/?utm_source=devopsish.com) tool has entered public beta. DNS Spy is a nice and handy tool to monitor and alert on changes to your DNS records. This is nice if you ever think you might be targeted for DNS hijacking (which you probably will be).

[Black Duck Software announced its 2016 Open Source 'Rookies of the Year'](https://www.blackducksoftware.com/about/news-events/releases/black-duck-announces-2016-open-source-rookies-year). One notable mention on the list is [Ansible Container](https://www.ansible.com/ansible-container).

The US Department of Defense has spun up [Code.mil](https://github.com/deptofdefense/code.mil#welcome-to-codemil---an-experiment-in-open-source-at-the-department-of-defense). They are requesting feedback on their [proposed open source strategy](https://github.com/deptofdefense/code.mil/blob/master/Proposal/CONTRIBUTING.md). Please take a look at it and if you have expertise in this arena help them out.

Aaron Bieber shared a [unique method to use Tor to verify SSH fingerprints](https://deftly.net/posts/2017-02-27-ssh-fp-verification-using-tor.html). If you are worried about being subject to MitM attacks have a look.

## Department of Dafuq

Google stalled its TLS 1.3 rollout this week thanks to the [shoddy work of BlueCoat](https://bugs.chromium.org/p/chromium/issues/detail?id=694593) (I am biased; I loathe BlueCoat's products for legitimate reasons). When modern versions of Chrome connected through BlueCoat products to Google services the connection would just hang.

## Department of Happy Little Clouds

Since we are on the topic of AWS, [Craig McLuckie](https://medium.com/@cmcluck) published Heptio's [AWS Quickstart for Kubernetes](https://blog.heptio.com/aws-quickstart-for-kubernetes-26ccaf7e1c8f#.io92vwkvr). This is Heptio's CloudFormation template and written guide to aid folks getting Kubernetes up and running quickly.

I keep coming back to this time and time again lately. The Cloud Native Computing Foundation maintains an incredibly handy [Cloud Native Landscape](https://github.com/cncf/landscape). If you are ever wondering what tools are available to handle a certain task look here first (and share this with your CIO/CTO).

## Department of Next Year's Old Tech

[Apache Web Server is continuing to lose market share](https://news.netcraft.com/archives/2017/02/27/february-2017-web-server-survey.html) at a pretty steady clip. Microsoft has the largest market share and nginx is continuing to gain on Apache and is within striking distance of overtaking the Apache behemoth. Interestingly, I am considering writing my own web server in Go with no configuration files; compile and launch a single binary.

## DevOps'ish Tweet of the Week

{{< tweet 836662634543992832 >}}