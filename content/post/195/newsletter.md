+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-12-06T07:00:00Z
description = "Google's firing of Timnit Gebru, Slack acquired by Salesforce, Kubernetes dockershim Deprecation, "
draft = false
slug = "195"
tags = []
title = "DevOps'ish 195"

+++

There are a few themes to this week's news worth discussing here in the introduction of the newsletter to give folks a clearer picture on each topic. We'll tackle them in the same People, Process, and Tools format DevOps'ish uses (which are the three core components of DevOps, in order of importance). Surprisingly, I have to explain the tools portion of the news the most because it involves one of the most toxic companies in the world, **Docker**.

I'd like to take this moment to remind folks about this site's [disclaimer](https://devopsish.com/terms#disclaimer).

## Google's firing of Timnit Gebru

Google continues to display bad behavior towards people who highlight what it's doing wrong potentially to the detriment of the entire planet. Google fired Timnit Gebru for an email (which isn't unheard of), but it's the fact she found flaws in large language models, which are a big part Google's operating model, that could actually hurt people. The concern is around the staggering impact on the environment building these models takes a significant amount of compute costing somewhere between $942,973-$3,201,722 and dumping 626,155 pounds (284,019 kilograms) of carbon into the environment. There's also a [Standing with Dr. Timnit Gebru](https://googlewalkout.medium.com/standing-with-dr-timnit-gebru-isupporttimnit-believeblackwomen-6dadc300d382) page, that I've signed and I'd encourage you to do so as well (if it safe for you to do so without risk of retaliation).

The most comprehensive coverage of Timnit Gebru's firing is from MIT Technology Review's, [*We read the paper that forced Timnit Gebru out of Google. Here’s what it says.*](https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/)

The actual email Timnit Gebru sent that got her fired is available via [Platformer News](https://www.platformer.news/p/the-withering-email-that-got-an-ethical).

## Slack acquired by Salesforce

All your SaaS are belong to Salesforce. At least that's their goal it looks like. The world was thinking this could be bigger than the IBM-Red Hat acquisition. It almost did, [clocking in $27.7 Billion](https://www.nytimes.com/2020/12/01/technology/salesforce-slack-deal.html). But, why did Slack want to be acquired? According to [The Verge](https://www.theverge.com/22150313/how-microsoft-crushed-slack-salesforce-acquisition), Slack grew to 12 million users while since 2016, Microsoft Teams grew to 115 million thanks to its inclusion, for free, in Office365. The acquisition will position Slack to better compete with Microsoft Teams but, this is a fine example of Microsoft's monopoly building skills of the 1990s in full effect.

## dockergate (again) 🤦‍♂️🤦‍♂️🤦‍♂️

From the [Kubernetes 1.20 changelog](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.20.md):

> ### Deprecation
> > Docker support in the kubelet is now deprecated and will be removed in a future release. The kubelet uses a module called "dockershim" which implements CRI support for Docker and it has seen maintenance issues in the Kubernetes community. We encourage you to evaluate moving to a container runtime that is a full-fledged implementation of CRI (v1alpha1 or v1 compliant) as they become available. ([#94624](https://github.com/kubernetes/kubernetes/pull/94624), [@dims](https://github.com/dims)) [SIG Node]

Mirantis and Docker don't have their eye on Kubernetes. I think we can infer that from this week's debacle. That became apparent this week when [Ian Coldwater noted the dockershim deprecation](https://twitter.com/iancoldwater/status/1334161889476157442) was coming in Kubernetes 1.20. In early October, a [Kubernetes Enhancement Proposal (KEP) was created to remove dockershim from kubelet](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/1985-remove-dockershim) (because either a shim turns into something maintainable or it goes away).

For most people, [this shouldn't be a huge deal](https://kubernetes.io/blog/2020/12/02/dont-panic-kubernetes-and-docker/). But, the entire team of people it took, led by Kat Cosgrove to explain how the technologies folks were using actually work deserve a huge thank you. They all took on the monumental task of informing run of the mill Docker users that what they are working on is [legacy tooling](https://twitter.com/mlbiam/status/1335238217168203776) at best.

This usually isn't a big deal but Docker has built a toxic community full of people who think they know better. I knew this from [my 2017 article where I declared Docker dead](https://chrisshort.net/docker-inc-is-dead/). Ian and Kat sadly experienced this first hand. Ian actually raised an alarm in the CNCF Ambassadors channel that they could use some help. This is where I screwed up. Sitting on the Kubernetes Upstream Marketing team, I should have alerted our crew immediately. But, in all fairness, this shouldn't have been necessary.

[We all make assumptions about how things work. It's a proven fact (I strongly encourage you to read more on this topic from Dr. Richard I. Cook).](https://queue.acm.org/detail.cfm?id=3380777) When someone shows us differences in our assumptions, we should assume that we're in for a learning experience. Never should we mount up for a fight, which is what a lot of Docker users did. That and being creepy or derogatory toward the people trying to explain the aforementioned KEP. On a medium not designed to have deep, technical conversations.

Item nine on the [Cloud Native Trail Map](https://raw.githubusercontent.com/cncf/trailmap/master/CNCF_TrailMap_latest.pdf) are Container Registry and Runtime. You can run any [OCI compliant](https://opencontainers.org/) container runtime in Kubernetes thanks to the [Container Runtime Interface (CRI) in Kubernetes](https://kubernetes.io/blog/2016/12/container-runtime-interface-cri-in-kubernetes/). The CNCF landscape is rather [specific about what container runtimes work with Kubernetes](https://landscape.cncf.io/category=container-runtime&format=card-mode&grouping=category). Containerd, donated to CNCF by Docker years ago is sorta the default as it's the only graduated runtime out there. Docker was hard to work with back in their heyday (still is apparently) so Red Hat created CRI-O, a lightweight alternative to Docker, which like containerd is based on [runc](https://github.com/opencontainers/runc) from OCI. But, all these runtimes offer something that the other doesn't. CRI-O was an answer to Docker's bloated implementations (Docker is more than one thing and they have a huge naming problem). Containerd is the OCI compliant runtime that Docker officially switched over to a while back. But, you could still run [docker-engine runtimes](http://petty.company/products/container-runtime) in Kubernetes.

But, dockershim is on its way out of the kubelet. What should you do? Investigate what runtimes are in use in your environment and make the switch to an OCI compliant runtime. Trust but verify, folks.

Allow me to elaborate on the "Mirantis and Docker don't have their eye on Kubernetes" point. The deprecation of dockershim has been a long time in the making. The KEP which is an enormous amount of information to assemble which has many artifacts as a part of it, was published on 2020-10-06. A full two months ago. That's when Mirantis and Docker should've done something. But, no, it took this massive Twitter shit storm, an [FAQ](https://kubernetes.io/blog/2020/12/02/dockershim-faq/), and a [blog post](https://kubernetes.io/blog/2020/12/02/dont-panic-kubernetes-and-docker/) from the Kubernetes team before Mirantis ([the legacy company in Marc Boorshtein's example](https://twitter.com/mlbiam/status/1335238217168203776)) did anything to address this issue.

Mirantis did so in [a blog post stating they'd continue support for dockershim](https://www.mirantis.com/blog/mirantis-to-take-over-support-of-kubernetes-dockershim-2/) and details on how to keep it as a runtime in Kubernetes would be coming. Who knows if Mirantis even looked at the code and all the reasons for its deprecation before they made this promise. But, they did it anyway because their business appears to be helping legacy workloads trod on. Regardless, [plans remain unchanged to remove support for dockershim from kubelet](https://twitter.com/dims/status/1335262856187695105). CRI is still moving towards production readiness in Kubernetes and docker-engine is still incompatible with CRI.

**I've mentioned this before, but getting off Docker should be a strategic imperative in your organization.** To quote fellow CNCF Ambassador, [Kat Cosgrove](https://twitter.com/Dixie3Flatline/), who took on the nearly impossible task of explaining this change to folks, "Docker is no more than a user experience at this point." *Note: Do not harass Kat or you'll be biting off way more than you can chew.*

Alternative tools have come a long way since the advent of Docker. Consider those before continuing to march forward with what is all but legacy software. You'll be better for it. Remember, something can die in tech without a replacement. Its not always competition or time that ends a business or technology.

Still curious what this all means in more technical terms, checkout fellow CNCF Ambassador, Gianluca Arbezzano's blog: [Kubenetes v1.20 the docker deprecation dilemma in practice](https://gianarb.it/blog/kubernetes-1-20-dockershim-in-practice).

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=195)

## People

[How a Vibrating Smartwatch Could Be Used to Stop Nightmares](https://www.wired.com/story/how-a-vibrating-smartwatch-could-be-used-to-stop-nightmares/)  
Those of us with PTSD that haunts us at night now have a reason for hope of a medication-free relief to the struggles we face thanks to [NightWare](https://night-ware.com/). I've already sent a message to my docs at the VA to see if I can get my hands on this. Let me know if you attempt to get a prescription for NightWare. I'd like to hear about who is on board with this and who isn't.

Want to see your ad in DevOps'ish? Check out the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. *SPONSORED*

[KubeCon + CloudNativeCon North America 2020 - Virtual](https://www.youtube.com/playlist?list=PLj6h78yzYM2Pn8RxfLh2qrXBDftr6Qjut)  
CNCF has shared all the videos from KubeCon + CloudNativeCon North America 2020 - Virtual.

## Process

[GitOps: It’s the cloud-native way](https://sdtimes.com/softwaredev/gitops-its-the-cloud-native-way/)  
I said this in 2018, "GitOps is also being declared as the 'next big thing for DevOps' because of their strong connection. According to Weaveworks’ [Cornelia] Davis, while DevOps doesn’t have a concrete set of practices, GitOps does provide a concrete way of doing DevOps."

[Download today: container security ebook - going beyond image scanning](https://security.stackrox.com/container-security-going-beyond-image-scanning.html?Source=DevOpsish&LSource=DevOpsish)  
Vulnerability scanning is often the first step to securing containers and Kubernetes, but it’s insufficient by itself. [Download this eBook](https://security.stackrox.com/container-security-going-beyond-image-scanning.html?Source=DevOpsish&LSource=DevOpsish), from StackRox, to learn about the security checks, controls, and best practices DevOps should consider to secure container images and CI build pipeline, Kubernetes deployments, running workloads, and the underlying Kubernetes infrastructure. *SPONSORED*

PROCESS

## Tools

[Introducing another free CA as an alternative to Let's Encrypt](https://scotthelme.co.uk/introducing-another-free-ca-as-an-alternative-to-lets-encrypt/)  
ZeroSSL is offering free certs via ACME. Here's a list of additional [ACME servers](https://docs.https.dev/list-of-acme-servers).

🎺  Looking to up your hands-on skills at KubeCon? We are premiering our [OpenTelemetry Starter Kit at the Honeycomb booth](https://info.honeycomb.io/honeycomb-and-kubecon). Instrument a sample app or your own production data. There are prize-drawings for completed steps, but the real prize is launching with OTel and getting valuable insights right away.

[Git stash doesn’t have to be scary](https://jemma.dev/blog/git-stash)  
"Stashes are more easily understood as a basic last in, first out stack."

[Weaveworks Brings GitOps to Amazon EKS Distro](https://www.weave.works/blog/on-prem-kubernetes-gitops-eks-distro)  
"This is especially for those customers who need more than just a ‘day zero’ installer for one or two clusters."


## DevOps'ish Tweet of the Week

[![DevOps'ish 195 Tweet of the Week](/images/195-devopsish-tweet-of-the-week.png)](https://twitter.com/Dixie3Flatline/status/1333549755952087040)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/195/notes/) to see what didn't make it to the newsletter.
