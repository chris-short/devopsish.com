+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2018"]
date = 2018-12-10
description = "Two Years 🎂, #KubeKhan, CVE-2018-1002105, State of k8s, vim, and More!"
draft = false
slug = "105"
tags = ["weekly", "devops", "newsletter", "cloud native", "cloud", "open source", "kubernetes", "automation", "Red Hat", "ansible", "security", "serverless", "Site Reliability Engineering", "SRE", "GitOps"]
title = "105: Two Years 🎂, #KubeKhan, CVE-2018-1002105, State of k8s, vim, and More!"

+++

DevOps'ish turns two this week. Started on 2016-12-11 as a Medium publication, with an epoch for a subject line, only 632 characters, and no images to be found. A lot has changed but, a lot has stayed the same too. There's no image again but, it's not on Medium anymore. There's a ton of news but, it's still sourced by me. There's more people reading and giving feedback but, I'm still grateful for every one of you. I'll be at KubeCon (and [#KubeKhan](https://twitter.com/search?q=%23KubeKhan)) Sunday through Wednesday morning, Raleigh on Thursday, and Durham on Friday. The number to beat for hotel stays this week is three. Have fun, patch your Kubernetes clusters, and stay safe out there!

Here's to another year of [**DevOps'ish**](https://devopsish.com/)! This newsletter was written from 35,000 feet above the United States.

[**Blog series: Actionable Continuous Delivery metrics**](https://www.gocd.org/tags/cd-analytics.html)  
In this new blog series we will go through important concepts and use examples to address common issues like low deployment frequency, slow lead time, high change to fail percentage, high MTTR. *SPONSORED*

[**Working with Irregular Time Series**](https://www.influxdata.com/blog/working-with-irregular-time-series/?utm_campaign=devopsish&utm_medium=partner&utm_source=email&utm_content=&utm_term=)  
One of the benefits of InfluxDB is the ability to store raw events, which might come in at varying intervals, as an irregular time series. Learn how you can convert irregular time series to a regular on the fly by calculating an aggregate of individual values for arbitrary windows of time. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*


## People

[U.S. Yield Curve Just Inverted. That's Huge.](https://www.bloomberg.com/opinion/articles/2018-12-03/u-s-yield-curve-just-inverted-that-s-huge) — This is a big deal. 2019 will bring an economic recession (not 2008 level but, within striking distance). Make sure you're at a place in life that can weather it.

[Linux.org domain hacked, plastered with trolling, filth and anti-transgender vandalism](https://www.theregister.co.uk/2018/12/07/linuxorg_hacked/) — Compromised through the registrar. If you hacked linux.org or have anti-LGBTQIA+ please take a long walk off a short pier.

[Ada Lovelace  —  The first programmer](https://medium.com/a-computer-of-ones-own/ada-lovelace-the-first-programmer-954c32228481) — I can't do Ada a damn bit of justice. We are so lucky this mind ever existed.

[Barbara Liskov — Inventor of Abstract Data Types](https://medium.com/a-computer-of-ones-own/barbara-liskov-inventor-of-abstract-data-types-9f8908fdcf86) — It's important to understand the  people who make today's technology possible.

[Arrest of Top Huawei Executive Could Roil Trade Talks with China](https://foreignpolicy.com/2018/12/07/arrest-of-top-huawei-executive-could-roil-trade-talks-with-china/) — Shit got real between the West and China this week.

[Police: 22-Year-Old Found Dead Inside Google's NYC Office](https://newyork.cbslocal.com/2018/12/08/22-year-old-found-dead-google/) — This is very odd for a 22-year-old. I did a little digging into the person's social media and literally found nothing outside of the norm. Seemed like an okay character.

[Neil DeGrasse Tyson Accused Of Sexual Misconduct By Four Women](https://www.buzzfeednews.com/article/azeenghorayshi/neil-degrasse-tyson-sexual-allegations-four-women) — Neil DeGrasse Tyson, Dirtbag Supreme.

[On Linus' Return to Kernel Development](https://www.linuxjournal.com/content/linus-returns-kernel-development-0) — "So, nothing was said about the code of conduct, and nothing about how he used his time away from kernel development. He just focused on catching up on merges and discussing possible changes to his workflow."

[Helping Remote Workers Avoid Loneliness and Burnout](https://hbr.org/2018/11/helping-remote-workers-avoid-loneliness-and-burnout)

[This is why women leave jobs in tech](https://www.fastcompany.com/90274067/this-is-why-women-leave-jobs-in-tech)

[The "Woke" Men Who Still Want Housewives by Jessica Valenti](https://medium.com/s/jessica-valenti/the-woke-men-who-still-want-housewives-debb2ad46aa0) — Check yourself before you wreck yourself.

[Lightning Talk on How To Jump Start a Career in Open Source (video)](http://www.schabell.org/2018/12/all-things-open-2018-lightning-talk-video.html)
{{< youtube LQ2BYca8u48 >}}

## Process

[The Results are in ... The State of K8s 2018](https://blog.heptio.com/the-results-are-in-the-state-of-k8s-2018-d25e54819416) — Heptio dives into the state of Kubernetes

[Support Driven Engineering (SDE)](http://willgallego.com/2018/12/09/support-driven-engineering-sde/) — While it might be ripe for abuse, being helpful and supportive is a good default position.

[Already learned DevOps? Great, now it's time for GitOps What's GitOps and how does it work?](https://thenextweb.com/contributors/2018/12/08/all-you-need-to-know-about-gitops/) — GitOps is what I want in everything DevOps and SRE.

[Dr. Richard Cook and John Allspaw's Seeking SRE Chapter](http://www.adaptivecapacitylabs.com/blog/2018/12/06/chapter-in-seeking-sre-sre-cognitive-work/) — When Dr. Cook speaks you should listen. I still need to dive into this book.

[The Untold Secrets of Operational Wi-Fi Calling Services:
Vulnerabilities, Attacks, and Countermeasures (PDF)](https://arxiv.org/pdf/1811.11274.pdf)

[Linux Foundation Continues to See Increasing Commitments to Open Source With Twenty-Three New Members](https://www.linuxfoundation.org/press-release/2018/11/linux-foundation-continues-to-see-increasing-commitments-to-open-source-with-twenty-three-new-members-in-october/) — The more the merrier!

[The Borg Is attacking Earth: Will anyone get fired for hiring Big Purple?](https://medium.com/@johndavidmarx/the-borg-is-attacking-earth-will-anyone-get-fired-for-hiring-big-purple-b791f2eb63a7) — Red Hat handled CVE-2018-1002105 very well.

[The Case For Breaking Up IBM](https://seekingalpha.com/article/4226183-case-breaking-ibm) — And poof! Just like that. [IBM selling Lotus Notes/Domino business to HCL for $1.8B](https://techcrunch.com/2018/12/07/ibm-selling-lotus-notes-domino-business-to-hcl-for-1-8b/) (these two stories were published within twenty-four hours of each other).

[A Collection of Well-Known Software Failures](http://www.cse.psu.edu/~gxt29/bug/softwarebug.html)

[Dell Systems Hacked to Steal Customer Information](https://www.bleepingcomputer.com/news/security/dell-systems-hacked-to-steal-customer-information/)

## Tools

[Kubernetes security flaw (CVE-2018-1002105)](https://elastisys.com/2018/12/04/kubernetes-critical-security-flaw-cve-2018-1002105/): Big, gnarly, but, fixable bug in Kubernetes and Kubernetes-based distributions.

[Kubernetes being hijacked worldwide](https://blog.binaryedge.io/2018/12/06/kubernetes-being-hijacked-worldwide/) — Yea... It's bad, folks.

[First impressions with the new kubeadm](https://elastisys.com/2018/12/05/first-impressions-with-the-new-kubeadm/)

[How Firecracker Is Going to Set Modern Infrastructure on Fire](https://thenewstack.io/how-firecracker-is-going-to-set-modern-infrastructure-on-fire/) — TBD but maybe.

[Optimizing Kubernetes resource allocation in production](https://opensource.com/article/18/12/optimizing-kubernetes-resource-allocation-production) — Testing resource limits and loads adds predictability and resiliency to your systems.

[Ed Vielmetti](https://twitter.com/worksonarm) clued me into the fact ARM support is coming to [Firefox](https://www.bleepingcomputer.com/news/software/mozilla-announces-a-native-arm64-version-of-firefox/) and [Chrome](https://www.neowin.net/news/microsoft-and-google-are-working-together-to-bring-chrome-to-windows-on-arm). This is *great* since **ARM is the future of compute**.

[The State of the Octoverse: communicating with emoji on GitHub](https://blog.github.com/2018-12-07-octoverse-emoji-on-github/) — "Yes. I use emojis in git commit messages. Oh your terminal doesn't support it? Sorry. Get one that does." —Me

[Setting Up Pod Security Policies](https://joshrosso.com/posts/setting-up-psps) — "Kubernetes, by default, allows anything capable of creating a Pod to run a fairly privileged container that can compromise a system. Pod Security Policies protect clusters from privileged pods by ensuring the requester is authorized to create a pod as configured."

[Managing containerized system services with Podman](https://developers.redhat.com/blog/2018/11/29/managing-containerized-system-services-with-podman/)

[Vimways ~ From .vimrc to .vim](https://vimways.org/2018/from-vimrc-to-vim/) — I like vim but I gave up on trying to make it something it isn't a long time ago. I do make heavy use of the vim plugin in Visual Studio Code though.

[The Rise of Microsoft Visual Studio Code](https://triplebyte.com/blog/editor-report-the-rise-of-visual-studio-code) — Speaking of Visual Studio Code...

[The Containerization of Machine Learning: TensorFlow, Kubernetes and Kubeflow](https://medium.com/datadriveninvestor/the-containerization-of-machine-learning-tensorflow-kubernetes-and-kubeflow-93bcdfb01ad5) — Kubernetes ❤️ Machine Learning

[AWS Outposts sets fire under on-prem competitors' seats](https://siliconangle.com/2018/11/30/aws-outpost-sets-fire-under-on-prem-competitors-seats-reinvent/) — You have my attention AWS.

[O'Reilly Kubernetes Security ebook](https://info.aquasec.com/kubernetes-security)

[90 days of AWS EKS in Production](https://kubedex.com/90-days-of-aws-eks-in-production/)

[The Future of OpenJDK at Red Hat](https://www.infoq.com/news/2018/11/red-hat-openjdk-gc-Nov18) — I welcome Java's open first future.

## DevOps'ish Tweet of the Week

Two tweets of the week for the second birthday of DevOps'ish. One because it's amazing how just getting together to say hi and chat can turn into something amazing when you open it to all. Another because, life is hard and then your job gets automated in the Short household 🎄.

{{< tweet 1070707964011368448 >}}

{{< tweet 1069798669245931520 >}}
