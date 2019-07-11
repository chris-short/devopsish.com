+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-02-24T06:00:00Z
description = "Open Source Licenses, Kubernetes Interview Prep, .dev Grossness, Hashicorp in Wired, Ansible for Kubernetes, Knative, and More"
draft = false
slug = "116"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "ansible", "container", "security", "automation", "knative", "cicd", "learning", "openshift", "istio", "docker layoffs", "docker", "layoffs", "licenses"]
title = "116: Open Source Licenses, Kubernetes Interview Prep, .dev Grossness, Hashicorp in Wired, Ansible for Kubernetes, Knative, and More"

+++

Last week's attempt at full automation failed and pointed out a shortcoming or two. ~~I hope that's all ironed out (time will tell).~~ It also highlights the need to think of always starting from a clean slate. My theory is, a cached version of the newsletter was stored on MailChimp. When I enabled the automation for web site to e-mail, MailChimp observed 115 as new and shipped it. Hopefully, you get this while I'm sleeping and everything works wonderfully. Ha!

I was in Raleigh and Durham this week for several meetings and collaborative efforts. A HUGE thank you to everyone that attended the Triangle DevOps Meetup on Wednesday. Y'all showed up in crappy weather before the most anticipated [shoe blowouts](https://devopsish.com/116/zion-nike-shoe-fail.gif) of the year. Seriously though, thank you. I met some [great people from far away lands](https://twitter.com/cotufa82/status/1098580247853838336) and the discussion afterward was delightful.

This week I'm holding down the fort outside Detroit. I plan on attending the [Orchestructure meetup](https://www.meetup.com/orchestructure/events/259159699/) and you should come too! The week after that the family and I are on vacation in Fort Lauderdale, Florida. If you're there and want to grab a Mai Thai, let me know.

> "Be weird, be transparent, be authentic, be yourself." —Ron Tite

[**Use Lead Time Metric to Improve Your CI/CD Process**](https://www.gocd.org/2019/01/14/cd-metrics-deployment-lead-time/)  
Check out GoCD's latest blog in CD Metrics series. It talks about what lead time means in CD context and guides you on how to identify bottlenecks and improve your CI/CD process. *SPONSORED*

[**Works on Arm**](https://www.worksonarm.com/blog)  
Works on Arm (WOA) is how I keep up with most of my Arm news. The editor is a local friend that works at a very heavy consumer of Arm processors, [Packet](https://www.packet.com/) who is a sponsor of WOA. Check it out, give it a subscribe, and trust me, you won't be disappointed. *SPONSORED*

{{< sponsor-blurb >}}

## DevOps'ish Top Five from Last Week

1. [Former engineer Liz Fong-Jones has ‘grave concerns' about Google](https://www.businessinsider.com/liz-fong-jones-google-concerns-2019-2)
2. [You Guys](https://www.xaprb.com/blog/you-guys/)
3. [Stop Disabling SELinux](https://stopdisablingselinux.com/)
4. [Automation - Just do it!](https://www.dowen.me.uk/Automation-Just-do-it!/)
5. [What's the future of Linux distributions?](https://funnelfiasco.com/blog/2019/02/14/whats-the-future-of-linux-distributions/)

## People

[Docker Layoffs?](https://www.linkedin.com/feed/update/urn:li:activity:6504718037906710528/) — According to one source, during a Zoom meeting this week, Docker told staff it was making a 10% reduction in force. Surprisingly, despite getting news from an independent intelligence chain, I could not obtain confirmation. I've sent along almost everything I know to a journalist I trust. We'll see what happens. But, if you're affected by this but, under NDA and need a new job, I can confidentially help you find a new job. **People matter more than tech or corporations.**

[Hiring #TravisAlums](https://hiringtravisalums.glitch.me/) — As mentioned in [DevOps'ish 112](https://devopsish.com/112/), in a sort of out of nowhere move, [Idera acquired Travis CI](https://blog.travis-ci.com/2019-01-23-travis-ci-joins-idera-inc). This week, Idera canned some great CI/CD talent that is in very high demand. Help them out if you're hiring. Also, should we, as a community, be moving projects off Travis CI in protest? GitLab CI is excellent but, GitHub contributions matter (GitHub Actions isn't ready for prime time, IMHO).

[The curse of the Twitter reply guy](https://mashable.com/article/twitter-reply-guys/#T.cVGlvFWZqx) — Alright, **dudes**, read this, please.

[poteto/hiring-without-whiteboards](https://github.com/poteto/hiring-without-whiteboards) — ⭐️ Companies that don't have a broken hiring process

[Mentoring Someone with Imposter Syndrome](https://hbr.org/2019/02/mentoring-someone-with-imposter-syndrome) — (HBR; possible paywall) The advice in this article is fantastic. Please read this even if you don't manage or mentor anyone.

[20 hottest tech skills that will get you hired](https://www.cnbc.com/2019/02/12/current-trends-in-the-tech-industry-are-fueling-new-types-of-skills.html) — Some highlights: Kubernetes, OAuth, Vue.js framework, and many more in our sphere. If you're looking to pick up something new to further your career, this isn't a bad list.

[Technical Recruiting Is Broken](https://leerob.io/blog/technical-recruiting-is-broken) — It is SO incredibly broken.

[Kubernetes job interview questions: How to prepare](https://enterprisersproject.com/article/2019/2/kubernetes-job-interview-questions-how-prepare) — "Demand for Kubernetes skills is growing. Whether you're a hiring manager or a job candidate, these 20 questions will help set you up for success."

## Process

[dirtysock.info](https://dirtysock.info/) — "Collecting new information about Dirty Sock as it comes to light." Also selling pretty dope swag.

[Making Learning a Part of Everyday Work](https://hbr.org/2019/02/making-learning-a-part-of-everyday-work) — Building learning into your job is as much your job as it is your company's. Here are some excellent tips on embracing and sharing learning.

[Why limiting work-in-progress works.](https://lethain.com/limiting-wip/) — "A new project can only be started when an existing project is finished, creating a feedback loop preventing us from overwhelming ourselves with unfinished tasks."

[The battle between real open source vs. faux open source heats up](https://www.zdnet.com/article/the-battle-between-real-open-source-vs-faux-open-source-heats-up/) — Clear lines are being drawn in the sand. "[P]ushing FUD about open-source licenses and software will only harm Redis and anyone else trying to build a business around open source."

[CVE-2019-8912](https://nvd.nist.gov/vuln/detail/CVE-2019-8912) — "In the Linux kernel through 4.20.11, af_alg_release() in crypto/af_alg.c neglects to set a NULL value for a certain structure member, which leads to a use-after-free in sockfs_setattr." Here's Red Hat's notice (Red Hat is my employer; read the [disclaimer](https://devopsish.com/disclaimer/)).

[GitLab might move to a single Rails codebase](https://about.gitlab.com/2019/02/21/merging-ce-and-ee-codebases/) — GitLab is attempting to put both open and licensed code in the same repository. That's very ambitious, but the efficiency gains could be huge.

[Fancy a .dev domain? They were $12,500 a pop from Google. Now, $1,000. Soon, $17.50. And you may want one](https://www.theregister.co.uk/2019/02/21/google_launches_dev/) — I'm a little disgusted by this whole .dev TLD. I really, really don't want to be forced to buy domain names or e-ink notebooks to be hip, cool, and in. My current DevRel pet peeve is having to follow someone on Twitter because if they don't follow you, it somehow reflects poorly on you. Really? This is a thing now? Come on...

[The CI/CD market consolidation](https://about.gitlab.com/2019/02/21/ci-cd-market-consolidation/) — "The DevOps industry is consolidating. GitLab is here to stay."

[This Company Takes the Grunt Work Out of Using the Cloud](https://www.wired.com/story/this-company-takes-grunt-work-using-the-cloud/) — "Much of Terraform's success stems from HashiCorp's focus on developers' experience. HashiCorp releases open source versions of its products that anyone can use without charge."

[Password managers may leave your online crown jewels 'exposed in RAM' to malware – but hey, they're still better than the alternative](https://www.theregister.co.uk/2019/02/20/password_managers_security_bugs/) — The headline kinda says it all. But, this is the best we have between security and convenience so let's either improve it or replace it.

[How to Break Down Work into Tasks That Can Be Automated](https://hbr.org/2019/02/how-to-break-down-work-into-tasks-that-can-be-automated) — Jumpstart your *Automation Imagination™️*.

[7 Common Content Marketing Mistakes Developers Make and How to Avoid Them](https://www.stephaniemorillo.co/single-post/2019/02/17/7-Common-Content-Marketing-Mistakes-Developers-Make-and-How-to-Avoid-Them) — Here's one I've seen a lot lately; developers making messaging guides when they have marketers on their team to build precisely that.

[Alooma signs an agreement to join the Google Cloud family](https://www.alooma.com/blog/alooma-plans-to-join-google-cloud) — Google Cloud has consumed Alooma.

## Tools

[Ansible for Kubernetes - a book by Jeff Geerling](https://www.ansibleforkubernetes.com/) — I absolutely cannot wait to get my hands on this Ansible for Kubernetes book. Jeff, if you need some help, let me know.

[Running Kubernetes without nodes](http://jpetazzo.github.io/2019/02/13/running-kubernetes-without-nodes-with-kiyot/) by Jérôme Petazzoni — "Capacity planning with Kubernetes is a non-trivial challenge. How many nodes should we deploy? What should be their size? When should we add or remove nodes to accommodate variations in load? One solution is to not deploy nodes, and provision resources on-demand instead."

[Go, the Programming Language of the Cloud](https://thenewstack.io/go-the-programming-language-of-the-cloud/) — Container runtimes, Kubernetes, CoreDNS, Prometheus, and numerous other cloud native software projects are written in Go. You'll do yourself justice by getting familiar with it.

[Kubernetes Storage Performance Comparison](https://medium.com/vescloud/kubernetes-storage-performance-comparison-9e993cb27271) — "The greatest dilemma is to select right storage technology for your cluster. There is not a simple answer or single test, which would tell you what is the best technology on market. Actually it very much depends on the type of workload you want to run."

[Rook (Ceph) Deployment on OpenShift 4](https://medium.com/@karansingh010/rook-ceph-deployment-on-openshift-4-2b34dfb6a442) — "Before installing anything we need infrastructure, for this, we are going to use AWS EC2 instances & EBS volumes for Ceph. One of the cool features of OpenShift 4 is you don't need to worry about provisioning infrastructure resources. Let's see how."

[An illustrated guide to Kubernetes Networking [Part 1]](https://morioh.com/p/ecb38c8342ba/an-illustrated-guide-to-kubernetes-networking) — There's easy to consume diagrams and some animation. Good to have handy.

[Use Istio traffic mirroring for quicker debugging](https://itnext.io/use-istio-traffic-mirroring-for-quicker-debugging-a341d95d63f8) — When debugging network issues, give me pcaps or give me death. One buggered packet can tell you so much about where a problem might be. Istio's Mirror service will allow folks to set up a copy of an application and mirror real traffic to it. Even better, Istio makes sure the copied instance doesn't respond to requests. This is neat and could have saved me so much time in the past.

[Gloo, by Solo.io, is the first alternative to Istio on Knative](https://medium.com/solo-io/gloo-by-solo-io-is-the-first-alternative-to-istio-on-knative-324753586f3a) — "Istio's main role in Knative is to serve as an ingress technology. Gloo now joins Istio as an integrated and supported Ingress for Knative." People are hyped about this company and the people in it.

[OpenShift 4 Architecture Overview](https://podctl.com/openshift-4-architecture-overview/) — "Brian talks with Clayton Coleman and Derek Carr, Technical Leads of Red Hat OpenShift, about the upcoming architectural changes in version 4."

[Build and deploy a serverless service to Knative](https://developers.redhat.com/coderland/serverless/) — "The Knative serverless environment lets you deploy code to Kubernetes, but no resources are consumed unless your code needs to do something. With Knative, you create a service by packaging your code as a Docker image and handing it to the system. Your code only runs when it needs to, with Knative starting and stopping instances automatically."

[Extending Vector with eBPF to inspect host and container performance](https://medium.com/netflix-techblog/extending-vector-with-ebpf-to-inspect-host-and-container-performance-5da3af4c584b) — "Today [Netflix is] excited to announce latency heatmaps and improved container support for our on-host monitoring solution — Vector — to the broader community."

[firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) — Secure and fast microVMs for serverless computing.

[Marp](https://yhatt.github.io/marp/) — Markdown Presentation Writer (MIT Licensed)

## DevOps'ish Tweet of the Week

When my biological mother left my father in the late 1980s, she joined a [cult](https://chrisshort.net/foundation-for-purposeful-living/). Of course, she dragged my brother and me along. One thing this [cult](https://chrisshort.net/foundation-for-purposeful-living/the-cult-that-is-human-service-alliance-and-the-center-for-purposeful-living/) did, which could be viewed as an abomination, introduce me to is Buddhism (and Islam, Judaism, Hinduism, Christianity, and worshiping a "guru") against my will. However, there are some pretty good life lessons in Buddhism. I'm finding them more and more pertinent as time goes on. Thus this week's DevOps'ish Tweet of the Week.

{{< tweet 1098892705873022976 >}}
