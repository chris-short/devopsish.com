+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-12-03T07:01:00.952Z
description = ""
draft = false
slug = "052"
tags = ["devops", "cloud native", "open source", "kubernetes", "observability", "infrastructure", "docker", "moby", "containers"]
title = "052: 1 Year 🎉, CNI Book Giveaway, AWS re:Invent, Kubernetes, and More!"
image = "/052/sharks-circling.jpg"
imagealt = "The sharks are circling"
imagecap = "[Flight of the Hammerheads](http://digitalblasphemy.com/preview.shtml?i=hammerheads2k62) by Digital Blasphemy"
aliases = [
    "devopsish-052-1-year-cni-book-giveaway-aws-re-invent-kubernetes-and-more-4404bb5f7362"
]

+++

This is the 52nd issue of [**DevOps'ish**](https://devopsish.com/)! While the official one-year anniversary is next week, there are 52 weeks in a year and now is as good a time as any to celebrate. In keeping with DevOps best practices, I shared some lessons learned in, [Notes on Running a Newsletter: A Year of DevOps'ish](https://chrisshort.net/notes-on-running-a-newsletter-a-year-of-devopsish/).

To celebrate the DevOps'ish first anniversary, Kris Nova has graciously offered to sponsor a giveaway of her and Justin Garrison's new book, [*Cloud Native Infrastructure*](http://shop.oreilly.com/product/0636920075837.do). If you want to be entered to win, please complete the [DevOps'ish Diversity Form](https://goo.gl/forms/aVCS0AVwIyLouV1p2) for consideration. Winners will be announced in next week's newsletter!

Looking back the five most popular issues of DevOps'ish have been:

1. [DevOps'ish 035: Google's Toxicity, Security, SRE, Kubernetes, and More!](/035/)
2. [DevOps'ish 045: Sick Days, Kubernetes, Kaspersky, Go, AWS, and More!](/045/)
3. [DevOps'ish 040: Solaris, Observability, Shift Left, Ansible, and More](/040/)
4. [DevOps'ish 037: Google, Debian, MongoDB, Kubernetes, and More!](/037/)
5. [DevOps'ish Weekly — 014: Week of 1489294800](/014/)

Thanks for making the first year of running this newsletter so awesome. I hope the next year will be even more amazing!

In personal news, thanks to the generosity of the Cloud Native Computing Foundation, I will be attending [KubeCon + CloudNativeCon North America 2017](http://events.linuxfoundation.org/events/kubecon-and-cloudnativecon-north-america)! If you're in Austin Dec 5th through 9th, be sure to send me a note or stop me for some new and improved DevOps'ish stickers.

[**Continuous Delivery: GoCD VS Spinnaker**](https://www.gocd.org/2017/07/10/gocd-vs-spinnaker/?utm_campaign=gocd_vs_spinnaker&utm_medium=email&utm_source=devopsish_newsletter&utm_content=gocd_vs_spinnaker&utm_term=)  
GoCD or Spinnaker? This post is an overview of GoCD and Spinnaker, why they are different from each other and which problems you should use them to solve. [Check it out](https://www.gocd.org/2017/07/10/gocd-vs-spinnaker/?utm_campaign=gocd_vs_spinnaker&utm_medium=email&utm_source=devopsish_newsletter&utm_content=gocd_vs_spinnaker&utm_term=). *SPONSORED*

{{< sponsor-blurb >}}

## People

[Linux Journal Ceases Publication](http://www.linuxjournal.com/content/linux-journal-ceases-publication): "The simple fact is that we've run out of money, and options along with it."

[So you want to be a wizard](https://jvns.ca/blog/2017/12/01/new-zine--so-you-want-to-be-a-wizard/) by Julia Evans

[On becoming Ryn](https://ryn.works/2017/12/01/on-becoming-ryn/): "Hi. My name is Ryn, and I'm nonbinary." The welcoming of Ryn to the world was fantastic to see this week.

[DevOps and Socks Episode 3 — Hammock Chilling](https://youtu.be/VDo8VoPLgOU): Ria and Jess chill on a Hammock in Austin before KubeCon.

[My First Few Months as a Junior Engineer](https://medium.com/@erinkayfox/my-first-few-months-as-a-junior-engineer-c0155691007) by Erin Fox: "We should all compare ourselves, to our past selves to really see how far we've come and how much we've learned."

["Don't expect your data scientist to be a full-stack developer."](https://twitter.com/i/moments/937075112343371777)

[Former Intel data center boss Diane Bryant joins Google Cloud as new COO](https://www.cnbc.com/2017/11/30/former-intel-data-center-boss-diane-bryant-joins-google-cloud-as-new-coo.html)

[What Etsy's former CTO is bringing to his new startup](https://technical.ly/brooklyn/2017/11/29/john-allspaw-etsy-former-cto-adaptive-capacity-labs/): John Allspaw talks about Adaptive Capacity Labs and what he learned from the Great Etsy Shakeup of 2017.

[David Karp is leaving Tumblr by the end of the year](https://techcrunch.com/2017/11/27/david-karp-is-leaving-tumblr-by-the-end-of-the-year/?ncid=rss)
{{< carbon_ads >}}

## Process

[May the next Etsy learn its lessons](https://m.signalvnoise.com/may-the-next-etsy-learn-its-lessons-af9928218114) by DHH

[5 best practices for getting started with DevOps](https://opensource.com/article/17/11/5-keys-get-started-devops): Are you ready to implement DevOps, but don't know where to begin? Try these five best practices.

[a short example of why dimensions are suuuuuper valuable](https://medium.com/@mhat/a-short-example-of-why-dimensions-are-suuuuuper-valuable-67e880055eb0) by Matt Knopp

[The Why, How, and What of Metrics and Observability](https://blog.digitalocean.com/observability-and-metrics/)

[The State of Open Source Security](https://snyk.io/stateofossecurity/?imm_mid=0f89e2&cmp=em-webops-na-na-newsltr_security_20171128)

[Fighting hidden threats with DevOps security best practices](http://www.theserverside.com/tip/Fighting-hidden-threats-with-DevOps-security-best-practices): "Find out what experts had to say about using DevOps security principles to weave threat resistance into the fabric of the development process."

[Executives overestimate DevOps maturity](http://www.zdnet.com/article/executives-overestimate-devops-maturity/): "We break down why understanding the current maturity of DevOps leads to successful implementation."

[Capital One: DevOps at Its Core](https://www.informationweek.com/devops/capital-one-devops-at-its-core/d/d-id/1330515)

DORA released [*Cloud Infrastructure in the Federal Government: Modern Practices for Effective Risk Management](https://devops-research.com/assets/federal-cloud-infrastructure.pdf) *(PDF)

[DevSecOps in Government: You Deploy It, You Own It](https://www.linkedin.com/pulse/devsecops-government-you-deploy-own-derek-e-weeks/)

[Dear CIOs: Stop beating yourselves up for being behind on transformation](https://enterprisersproject.com/article/2017/11/dear-cios-stop-beating-yourselves-being-behind-transformation): Let's break down three misconceptions about digital transformation for CIOs racing to make progress
{{< carbon_ads >}}

## Tools

[Say Hello to AWS Fargate & Amazon Elastic Container Service for Kubernetes (EKS)](https://medium.com/containers-on-aws/say-hello-to-amazon-fargate-and-amazon-elastic-container-service-for-kubernetes-66707dd14976) by tiffany jernigan: "No more needing to provision, configure, or manage any clusters or instances!"

[Introducing AWS Fargate — Run Containers without Managing Infrastructure](https://aws.amazon.com/blogs/aws/aws-fargate/)

[Keeping Time With Amazon Time Sync Service](https://aws.amazon.com/blogs/aws/keeping-time-with-amazon-time-sync-service/)

[Amazon MQ — Managed Message Broker Service for ActiveMQ](https://aws.amazon.com/blogs/aws/amazon-mq-managed-message-broker-service-for-activemq/)

[Welcoming AWS to the Kubernetes ecosystem, and introducing a new open source project for Kubernetes authentication](https://blog.heptio.com/welcoming-aws-to-the-kubernetes-ecosystem-and-introducing-a-new-open-source-project-for-kubernetes-200a6085ca6c) by Craig McLuckie

[Kubernetes: Getting Started](https://chrisshort.net/kubernetes-getting-started/) by [Chris Short](https://chrisshort.net/): How do you get started with "an open-source system for automating deployment, scaling, and management of containerized applications"?

[Containers and the Battle for the Iron Throne](https://blog.thecodeteam.com/2017/11/30/containers-battle-iron-throne/) by Josh Bernstein: "Instead, Docker launched Moby and confused everyone with the company's business vision."

[Cutting cluster management fees on Google Kubernetes Engine](https://cloudplatform.googleblog.com/2017/11/Cutting-Cluster-Management-Fees-on-Google-Kubernetes-Engine.html)

[How Netflix Tunes EC2 Instances for Performance](https://www.slideshare.net/brendangregg/how-netflix-tunes-ec2-instances-for-performance)

SysAdvent [Day 1 — Comfortably Numb — or — "How Corporate Analgesia is Actively Harming You"](https://sysadvent.blogspot.com/2017/12/day-1-comfortably-numb-or-corporate.html) by H. "Waldo" Grunenwald and Adam Compton

SysAdvent [Day 2 — Shifting Left Securely With inSpec](https://sysadvent.blogspot.com/2017/12/day-2-shifting-left-securely-with-inspec.html) by Matt Stratton and Rich Cassara

[Automating Go development with Make](https://blog.gopheracademy.com/advent-2017/make/) by Kevin Burke

[Alpine 3.7.0 released](https://alpinelinux.org/posts/Alpine-3.7.0-released.html)

[Ansible 2.4.2 released](https://github.com/ansible/ansible/blob/stable-2.4/CHANGELOG.md#242-dancing-days---2017-11-29)

[PHP 7.2.0 Released](http://php.net/archive/2017.php#id2017-11-30-1)

[Announcing the OpenFaaS Function Store](https://blog.alexellis.io/announcing-function-store/)

[michelleN/helm-secure-tiller](https://github.com/michelleN/helm-secure-tiller): This Helm plugin allows you to add an RBAC profile to a Tiller in a Kubernetes namespace.

[tenta-browser/tenta-dns](https://github.com/tenta-browser/tenta-dns): Recursive and authoritative DNS server in go, including DNSSEC and DNS-over-TLS

[Golang's Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/): "In this blog post, we'll look at Go's garbage collector. We'll see how it works (the tricolor algorithm), why it works (achieving such short GC pauses), and most importantly, whether it works (benchmarking these GC pauses, and comparing them with other languages)."

[CNCF Community Infrastructure Lab](https://www.cncf.io/community/infrastructure-lab/): (CIL) provides free access to state-of-the-art computing resources for open source developers working to advance cloud native computing.

## DevOps'ish Tweet of the Week

{{< tweet 935890590377697281 >}}