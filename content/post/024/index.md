+++

author = "Chris Short"
categories = ["Newsletter"]
date = 2017-05-21T14:01:01.401Z
description = ""
draft = false
slug = "024"
tags = ["devops", "cloud native", "open source", "kubernetes", "ansible", "hashicorp"]
title = "024: Week of 1495339200"
image = "/024/Mohnfeld-by-Olli-Henze.jpg"
imagealt = "Mohnfeld by Olli Henze"
imagecap = "[Mohnfeld](https://www.flickr.com/photos/gruenewiese/14160612230) by Olli Henze"
aliases = [
    "devopsish-024-week-of-1495339200-fdfa5f34806"
]

+++

Ever have one of those weeks where you feel like more of a consultant than a full-time employee? That was my week. I do not mind it at all. But, sometimes it's nice to not be bombarded with questions all week long. Also, I hate building VPNs.

In other news, I received a request to make the newsletter more responsive and readable. If you are reading this in a mail client then you should be benefitting from the hour or so I put into the new template. Reply to let me know what you think.

{{< upscribe >}}

## Department of Choice Concepts

[Ben Sima shared the first three things he installs on any new server.](https://bsima.me/clog/server-tools.html) I'm surprised he doesn't have this in Ansible for easy deployment.

[Being agile and working smart are not the same thing](https://techbeacon.com/being-agile-working-smart-are-not-same-thing) (TechBeacon)

Matt Micene reminds us all that DevOps isn't some apparition that appeared out of nowhere. [DevOps is the course correction to a culture that is a byproduct of Taylorism and Sloanianism](https://opensource.com/open-organization/17/5/what-is-the-point-of-DevOps).

[Mike Simmons shares his monster list of Docker tips](https://dev.to/mikesimons/mikes-monster-list-of-docker-tips). There are definitely some container nuggets in here.

[Anthony Shaw weighs the strengths and weaknesses of Ansible vs. Salt vs. StackStorm](https://medium.com/@anthonypjshaw/ansible-v-s-salt-saltstack-v-s-stackstorm-3d8f57149368). Ansible fairs very well showing that it is standing the test of time.

[Heap shared a solid article on Postgres performance tuning](http://heap.engineering/basic-performance-analysis-saved-us-millions/) (despite the click-bait title).

[Kubernetes put out a piece on monitoring](http://blog.kubernetes.io/2017/05/kubernetes-monitoring-guide.html) and how k8s shifts the mindset required to effectively monitor your infrastructure.

## Department of Happy Clouds

[Cloud Spanner](https://cloud.google.com/spanner/), the world's first horizontally-scalable and strongly-consistent relational database service, is now generally available for your mission-critical OLTP applications. This is great news for folks needing five-nines of availability, strong consistency, and low latency.

## Department of Refreshment and Refurbishment

[Vagrant 1.9.5 is out](https://www.hashicorp.com/blog/vagrant-1-9-5/)! This release features Docker Compose support among other things.

Ever want a completely open source software forge? [Apache Allura](http://allura.apache.org/) offers a git repo, wiki, and ticketing system with 2FA.

[HTTP/2 coming to EL7 (finally)](https://ma.ttias.be/centos-7-4-ship-tls-1-2-alpn/): OpenSSL has been rebased in RHEL 7 to OpenSSL 1.0.2k. This will allow for Application-Layer Protocol Negotiation (ALPN) which is necessary for HTTP/2.

[Stack Overflow has a new iOS and Android app](https://stackoverflow.blog/2017/05/16/stack-overflow-official-app-launches-ios-android/). I'm not sure how useful this will be to me; Google has always been my conduit to Stack Overflow. But, if you slap it on your phone and use it more power to you.

[Introducing Badger: A fast key-value store written natively in Go](https://open.dgraph.io/post/badger/) (Dgraph)

[Kubernetes 1.6.4 is out](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG.md/#v164) as the k8s squad pushes towards 1.7.

## Department of Data Defense

[Unmanaged SSH keys are truly awful](http://www.csoonline.com/article/3196974/data-protection/unmanaged-orphaned-ssh-keys-remain-a-serious-enterprise-risks.html). How are you going to handle employees coming and going (sometimes abruptly) without central management of SSH credentials? It's surprisingly a bigger problem than you'd think.

What happens where you get hacked? [A developer at Panic shared their experience when, through a random series of events, got pwned](https://panic.com/blog/stolen-source-code/). It is an insightful postmortem of personal accountability.

[The need for urgent collective action to keep people safe online: Lessons from last week's cyberattack](https://blogs.microsoft.com/on-the-issues/2017/05/14/need-urgent-collective-action-keep-people-safe-online-lessons-last-weeks-cyberattack/#sm.0000llg81y90hdbs115975pt98jep) (Microsoft)

## Department of Assemblage Obtainment

My employer, [SolarWinds](http://www.solarwinds.com/), has acquired [Scout](https://scoutapp.com/). Scout was in the server monitoring and APM space. [This acquisition](http://www.solarwinds.com/company/press-releases/solarwinds-acquires-scouts-saas-based-server-monitoring-technology-and-launches-it-as-solarwinds-pingdom-server-monitor) dovetails nicely into both the traditional SolarWinds monitoring space and its cloud business.

## Not DevOps But Still Cool

[Kelsey Hightower shared how he goes about learning new things](https://twitter.com/kelseyhightower/status/864857551942307840). Reading RFCs is truly insightful.

[Joe Nelson broke down what the quintessential Linux workstation would look like today](https://begriffs.com/posts/2017-05-17-linux-workstation-guide.html#core). Asus is still the manufacturer of choice for the motherboard.

The University of Washington has a new class, [Calling Bullshit in the Age of Big Data](http://callingbullshit.org/syllabus.html). If I were anywhere near Seattle I would be in this class.