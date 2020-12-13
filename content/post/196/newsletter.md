+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-12-13T07:00:00Z
description = ""
draft = false
slug = "196"
tags = []
title = "DevOps'ish 196"

+++

Some people understand that the advancement of technology is marching at an ever quickening pace. We're talking exponential advancement every year. Five years ago, [Kubernetes](https://kubernetes.io/) was brand new. Now it's democratizing computing across clouds. Docker, the company behind some glue technology that made containers the new norm in software, has [died twice now](https://www.tariqislam.com/posts/kubernetes-docker-dep/). The size and shape of infrastructure has changed so much the past two years, it's hard to remember ten years ago when [Vagrant](https://www.vagrantup.com/) was brand new.

I've been thinking about my typical end of year blog post this week quite a bit. Trying to accurately predict what next year will bring is difficult. When an organization offers to support something for ten years, it seems increasingly daunting to fathom what the technology landscape will look like.

When I found out (the same time you did) about [CentOS Stream](https://blog.centos.org/2020/12/future-is-centos-stream/), I appreciated it ([FAQ](https://centos.org/distro-faq/)). It feels like DevOps has touched the enterprise operating system I was using when I first started learning DevOps. But, then I realized, like most decent digital transformations, change is often met with some resistance. The best people in DevOps are the ones that can [help people see the future a little clearer](https://youtu.be/MDu6wL1DWY4). Some people lean into DevOps; some people resist it. This is human nature.

There's nothing I'm going to say or do that's going to change anything. But, I hope you can seek out understanding like [Kristian Köhntopp](https://blog.koehntopp.info/2020/12/09/embracing-the-stream.html) did. It might not be the popular thing, but it helps when you realize the [sea change that has occurred underneath us all](https://www.cncf.io/).

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=196)

## People

[Sen. Klobuchar asks HHS about health-tracker privacy protections](https://www.washingtonpost.com/technology/2020/12/11/amazon-halo-klobuchar-privacy/)  
"The $65 wearable contains an always-on microphone and asks users to strip down for 3D body scans"

[Kubernetes Contributor Awards 2020](https://www.youtube.com/watch?v=XCRkzgMTaJU&feature=youtu.be)  
"Kubernetes SIG Co-Chairs and Tech Leads would like for you to attend this special event where we honor and dedicate the hard work that the community has been working on. These peer awards are a tradition at the Kubernetes Contributor Summits so we are bringing them virtual, please join us to thank and support all the people who have worked hard to help us this year."

[U.S. Schools Are Buying Cellebrite Phone-Hacking Tech](https://gizmodo.com/u-s-schools-are-buying-phone-hacking-tech-that-the-fbi-1845862393)  
File this under, "This should be illegal." It's also why I give money to the [EFF](https://eff.org).

[Oracle is moving its headquarters from Silicon Valley to Austin, Texas](https://www.cnbc.com/2020/12/11/oracle-is-moving-its-headquarters-from-silicon-valley-to-austin-texas.html)  
Sorry, Austin.

[National Weather Service faces internet bandwidth shortage, proposes access limits](https://www.washingtonpost.com/weather/2020/12/09/nws-data-limits-internet-bandwidth/)  
"The Weather Service’s proposed remedy is to limit users to 60 connections per minute on a large number of its websites that provide weather observations, forecasts, warnings, computer model data, air quality information, aviation weather support and ocean conditions." The impacts could be pretty severe.


## Process

[FireEye hack: foreign government attackers steal ‘Red Team’ tools from US cybersecurity firm](https://www.scmp.com/news/world/united-states-canada/article/3113137/fireeye-hack-foreign-government-attackers-steal-red)  
"Attack carried out by ‘nation with top-tier offensive capabilities’. Hackers stole tools used to probe defences of FireEye customers."

[Kubernetes security: preventing man in the middle with policy as code](https://www.accurics.com/blog/security/kubernetes-security-man-in-the-middle-cve-2020-8554/)  
Use Terrascan to defend thyself.

[It's Just a Monitoring Change](https://sbg.technology/2020/12/09/its-just-a-monitoring-change/)  
"The more database-intensive query (getting all payment records for the previous week) took nearly as long as the interval to return results, and very soon was taking longer than the interval. Even though the Prometheus scrape was timing out after 10 seconds, the query was still running to completion on the database. After around 15 minutes we were in a situation where the database was overloaded by this query running multiple times, so much so that other services which use this database (such as login) were unable to interact with it."

[Kubernetes security project faces reckoning over beta status](https://searchitoperations.techtarget.com/news/252493492/Kubernetes-security-project-faces-reckoning-over-beta-status)  
"Kubernetes Pod Security Policies could be marked for deprecation as soon as the next Kubernetes release, in the wake of new limits on the beta phase for components of the platform."

[How Long Can a Company Thrive Doing Just One Thing?](https://hbr.org/2020/12/how-long-can-a-company-thrive-doing-just-one-thing)  
"The deal, however, epitomizes a question facing so-called best-of-breed companies such as Slack, Zoom, and Dropbox: how secure is their edge over companies such as Microsoft, which offer integrated software bundles that directly compete."

[The FTC is suing Facebook to unwind its acquisitions of Instagram and WhatsApp](https://www.theverge.com/2020/12/9/22158483/facebook-antitrust-lawsuit-anti-competition-behavior-attorneys-general)  
You don't derail elections and not get sanctioned somehow.

[Leading Cloud and Telecom providers Invest 36M in Series C to Accelerate GitOps](https://www.weave.works/blog/announcing-weaveworks-36m-series-c/)  
Congrats to my friends at WeaveWorks!

## Tools

[Kubernetes 1.20: The Raddest Release](https://kubernetes.io/blog/2020/12/08/kubernetes-1-20-release-announcement/)  
"We’re pleased to announce the release of Kubernetes 1.20, our third and final release of 2020! This release consists of 42 enhancements: 11 enhancements have graduated to stable, 15 enhancements are moving to beta, and 16 enhancements are entering alpha."

### CentOS News

* [CentOS Stream: Building an innovative future for enterprise Linux](https://www.redhat.com/en/blog/centos-stream-building-innovative-future-enterprise-linux)
* [Thoughts on CentOS Stream](https://jperrin.org/blog/thoughts-on-stream/)
* [CentOSStreamConfusion](https://utcc.utoronto.ca/~cks/space/blog/linux/CentOSStreamConfusion)
* [Before You Get Mad About The CentOS Stream Change, Think About...](http://crunchtools.com/before-you-get-mad-about-the-centos-stream-change-think-about/)

[Jeli.io announces $4M seed to build incident analysis platform](https://techcrunch.com/2020/12/07/jeli-io-announces-4m-seed-to-build-incident-analysis-platform/)  
This company is going places. Some really brilliant minds there.

[Linkerd service mesh's steady updates outlast Istio's flash](https://searchitoperations.techtarget.com/news/252493353/Linkerd-service-meshs-steady-updates-outlast-Istios-flash)  
"As service mesh adoption goes mainstream, early adopters of Linkerd say it allowed them to start small and grow in scale and sophistication as needed."

[5 useful DevOps newsletters that will blow your mind 🤯](https://daily.dev/posts/5-useful-devops-newsletters-that-will-blow-your-mind)  
Thank you!

[Micro frontend](https://explodingtopics.com/topic/micro-frontend)  
"User-facing part of a program coded in small, manageable chunks. This allows teams to work separately on self-contained sections." Expect to hear a lot about this in the near future.

[Cloudflare and Apple design a new privacy-friendly internet protocol](https://techcrunch.com/2020/12/08/cloudflare-and-apple-design-a-new-privacy-friendly-internet-protocol/)  
Oblivious DNS-over-HTTPS... Huh.

[Renovate your GitOps](https://mjpitz.com/blog/2020/12/03/renovate-your-gitops/)  
"Together, these technologies reduce the burden of running software yourself. It can free up time for your developers, allowing them to focus on valuable work for your company. With proper testing, you can configure Renovate to automatically merge changes if they pass your checks."

[Netflix/consoleme](https://github.com/Netflix/consoleme)  
"ConsoleMe consolidates the management of multiple AWS accounts into a single interface. It allows your end-users and administrators to get credentials for your different accounts, and allows your users/administrators to manage or request cloud permissions."

## DevOps'ish Tweet of the Week

[![DevOps'ish 196 Tweet of the Week](/images/196-devopsish-tweet-of-the-week.png)](https://twitter.com/adamhjk/status/1336892243131518978)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/196/notes/) to see what didn't make it to the newsletter.
