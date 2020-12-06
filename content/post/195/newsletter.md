+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-12-06T07:00:00Z
description = ""
draft = false
slug = "195"
tags = []
title = "DevOps'ish 195"

+++

There are a few themes to this week's news worthy discussing here in the introduction of the newsletter

## Google's firing of Timnit Gebru

Google continues to display bad behavior towards people who highlight what it's doing wrong potentially to the detriment of the entire planet. Google fired Timnit Gebru for an email (which isn't unheard of), but it's the fact she found flaws in Google's operating model that could actually hurt people. 

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

**I've mentioned this before, but getting off Docker should be a strategic imperative in your organization.** To quote Kat Cosgrove, "Docker is no more than a user experience at this point." Alternative tools have come a long way since the advent of Docker. Consider those before continuing to march forward with legacy software. You'll be better for it. Remember, something can die in tech without a replacement. Its not always competition that ends a business or technology.

## Slack acquired by Salesforce

All your SaaS are belong to Salesforce. At least that's their goal it looks like.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=195)

## People

PEOPLE

Want to see your ad in DevOps'ish? Check out the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. *SPONSORED*

## Process

PROCESS

## Tools

TOOLS

## DevOps'ish Tweet of the Week

[![DevOps'ish 195 Tweet of the Week](/images/195-devopsish-tweet-of-the-week.png)](https://twitter.com/Dixie3Flatline/status/1333549755952087040)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/195/notes/) to see what didn't make it to the newsletter.
