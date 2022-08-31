+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2018"]
date = 2018-05-20T07:00:00Z
description = ""
draft = false
slug = "076"
tags = ["devops", "cloud native", "open source", "kubernetes", "security", "microservices", "Site Reliability Engineering", "SRE", "Docker"]
title = "076: Hiring in DevOps, Security, Kubernetes, and More"
image ="https://shortcdn.com/devopsish/076-web.jpg"

+++

This has been a whirlwind week. On Sunday, we celebrated Mother's Day. It was a good day where I tried very hard to give Julie the day off from the rigors of Max management. I had to bail a little  before Max's bedtime though to head to Cleveland for an [SJ Technologies](http://sjtechcorp.com/) client visit. It was a great visit but it was, in military lingo, a turn and burn. I was back in Michigan by Monday night. I was working on a couple of tickets this week before heading off to [ChefConf](https://chefconf.chef.io/). One issue revealed a lovely [little bug in Kubernetes](https://access.redhat.com/solutions/3391931) (login required). I was attempting to mount a ConfigMap as a file in the root directory of a container and it was not working no matter what. It was awful and the workaround was thankfully easy enough due to the fact it was a web app and [Caddy](https://caddyserver.com/) was available. I created an HTTP redirect and I was off and running. I submitted some additional bug reports where appropriate and was off to the next thing. Tripping over bugs is annoying. But, there's a great Kubernetes community right here in Michigan: [Orchestructure](https://www.meetup.com/orchestructure/). Thanks to y'all for helping me out this week.

[**5 considerations for continuous delivery of microservices**](https://www.gocd.org/2018/04/25/five-considerations-continuous-delivery-microservices/?utm_campaign=cd_microservices&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_microservices_blog&utm_term=)  
Continuous Delivery is an essential component of any software delivery practice, including microservices. This new blog series shares five considerations we recommend keeping in mind when designing a CD workflow on microservices architectures. *SPONSORED*

## Events

[**ChefConf 2018**](https://chefconf.chef.io/)  
Dates: 2018-05-22 through 2018-05-25  
Join an awesome community of #DevOps and automation professionals at [ChefConf](https://chefconf.chef.io/) in Chicago. I'll be presenting, *DevOps is Not a War*. Save 10% with discount code **Hugs4Chef**.

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

[**DevNation Federal**](https://devnationfederal.org/)  
Date: 2018-06-05  
Join us to learn about the revolutions happening in communities around containers, data, and application modernization. This is an opportunity for you to hear how visionary teams in the federal government are innovating with open source, and hear from leaders in the private sector doing the same.

[**Chaos Conf**](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[**LISA18**](https://www.usenix.org/conference/lisa18)  
Dates: 2018-10-29 through 2018-10-31  
Have something to say on the present & future of #ops? The LISA18 CFP closes May 24. [Submit your ideas](https://www.usenix.org/blog/usenix-lisa18-cfp-nashville)!

## People

[The ultimate DevOps hiring guide](https://opensource.com/article/18/4/ultimate-devops-hiring-guide): Trying to round up DevOps talent? We're a unique lot that requires some tweaks to your hiring practices.

[DevOps hiring strategies to attract top talent](https://opensource.com/article/18/5/devops-hiring-strategies-attract-top-talent): Top DevOps recruiter Ken Middleton offers insight on how to attract and hire the best candidates.

[#127 SRE vs Devops with Liz Fong-Jones and Seth Vargo](https://www.gcppodcast.com/post/episode-127-sre-vs-devops-with-liz-fong-jones-and-seth-vargo/): "Liz Fong-Jones and Seth Vargo battle it out on which is better: SRE or Devops (hint - everyone wins!)."

[Goodbye, Google (an open micro-letter)](https://medium.com/@sadams.codes/goodbye-google-b249cd513102): This made me very sad. I miss Sarah's energy in our community.

[DevOps Culture through the Prism of Maslow's Hierarchy of Needs](https://devops.com/devops-culture-through-the-prism-of-maslows-hierarchy-of-needs/)

[27 things I learned about hiring in tech from looking for a new engineering management role](http://wunder.schoenaberselten.com/2018/05/12/27-things-i-learned-about-hiring-in-tech-from-looking-for-a-new-engineering-management-role/)

## Process

[Not So Pretty: What You Need to Know About E-Fail and the PGP Flaw](https://www.eff.org/deeplinks/2018/05/not-so-pretty-what-you-need-know-about-e-fail-and-pgp-flaw-0): "Don't panic! But you should stop using PGP for encrypted email and switch to a different secure communications method for now."

[The DevOps Security Checklist](https://www.sqreen.io/checklists/devops-security-checklist.html): "This security checklist aims to give DevOps professionals a list of DevOps security best practices they can follow to implement DevSecOps."

[This Week on The New Stack: Is a Kubernetes Backlash Afoot?](https://thenewstack.io/this-week-on-the-new-stack-kubernetes-needs-developers/)

[Red Hat and CoreOS put Kubernetes on autopilot](https://siliconangle.com/blog/2018/05/18/red-hat-and-coreos-put-kubernetes-on-autopilot-rhsummit/)

[How to start a Go project in 2018](https://boyter.org/posts/how-to-start-go-project-2018/): "Getting started with a Go project in 2018 is frankly a little more painful then getting anything else started IMHO."

[Rackspace Launches Comprehensive Kubernetes-as-a-Service Solution with Fully Managed Operations](https://globenewswire.com/news-release/2018/05/16/1507403/0/en/Rackspace-Launches-Comprehensive-Kubernetes-as-a-Service-Solution-with-Fully-Managed-Operations.html)

[Tech giants offer startups free patents in bid to foil lawsuits](http://www.dailyherald.com/business/20180519/tech-giants-offer-startups-free-patents-in-bid-to-foil-lawsuits): "Red Hat Inc. and Lenovo Group Ltd. are giving away free patents to any start-up that joins a group of more than 200 companies devoted to keeping its members and their patents out of court."

[Kubernetes Chaos Engineering: Lessons Learned](https://learnk8s.io/blog/kubernetes-chaos-engineering-lessons-learned)

[North Carolina, Apple negotiating deal on Triangle campus](https://www.wral.com/north-carolina-apple-negotiating-deal-on-triangle-campus-second-site-in-cary/17558985/): "Apple is close to announcing a deal that would bring as many as 10,000 jobs to North Carolina, including a major investment in the Research Triangle Park, according to multiple sources with knowledge of the deal."

## Tools

[Edge computing and the importance of open infrastructure](https://opensource.com/article/18/5/edge-computing): The "edge" is diverse, dispersed, often independently owned and operated, and comes with a set of constraints not addressed in the average data center.

[Making Kubernetes work for the average engineer—via PaaS](https://www.infoworld.com/article/3273104/containers/making-kubernetes-work-for-the-average-engineer-via-paas.html): Despite being the hottest thing since, well, Docker, Kubernetes remains a dark art for most mainstream enterprises

[Citrix snuffs Xen and NetScaler brands](https://www.theregister.co.uk/2018/05/14/citrix_rebranding/): Arise, 'Citrix Hypervisor' and 'Citrix SD-WAN'

[How HTTPS Works: Why Do We Need HTTPS?](https://howhttps.works/why-do-we-need-https/)

[Julia Evans](https://jvns.ca/) made another fantastic zine: [Bite size linux!](https://gumroad.com/l/bite-size-linux)

[The headers we don't want](https://www.fastly.com/blog/headers-we-dont-want) by Fastly

[Windows Package Management with Ansible](https://www.ansible.com/blog/windows-package-management)

[Introducing Git protocol version 2](https://opensource.googleblog.com/2018/05/introducing-git-protocol-version-2.html): "This update removes one of the most inefficient parts of the Git protocol and fixes an extensibility bottleneck, unblocking the path to more wire protocol improvements in the future."

[google/nomulus](https://github.com/google/nomulus): Top-level domain name registry service on Google App Engine

[Mayeu/awesome-open-source-organizations](https://github.com/Mayeu/awesome-open-source-organizations): A list of organizations that have open sourced everything they do

[gocolly/colly](https://github.com/gocolly/colly/releases/tag/v1.0.0): Congrats to Colly on going 1.0!

[goreleaser/nfpm](https://github.com/goreleaser/nfpm): NFPM is Not FPM - a simple deb and rpm packager written in Go

## Jobs

[**SJ Technologies**](http://sjtechcorp.com/) is looking to bring someone on board to work in our DevOps and Digital Transformation practice. If you want to help some big-time companies eager to implement change [*let me know*](mailto:chris.short@sjtechcorp.com). Plus, you get to work for great team of folks including [Karen Lawton](https://twitter.com/sjtech_karen?lang=en), [John Willis](https://twitter.com/botchagalupe/), [Barbara Bouldin](https://twitter.com/bbouldin711), and [ME](https://chrisshort.me/).

[DZone](http://careers.dzone.com/apply/DBWe0hiNCN/Site-Reliability-Engineer) is looking for a Site Reliability Engineer in Cary, NC. Based off my experiences with DZone, this is a cool place to work. To quote a decision maker at DZone, "We need strong cloud, automation, security [experience]." Check them out.

## DevOps'ish Tweet of the Week

> Her palms are sweaty, knees weak, arms are heavy
> There's errors on her console already, kubernetes
> 
> — bletchley punk (@alicegoldfuss) [May 18, 2018](https://twitter.com/alicegoldfuss/status/997268087429713922?utm_source=devopsish&utm_medium=newsletter&utm_campaign=076)
