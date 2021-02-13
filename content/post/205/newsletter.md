+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-02-14T07:00:00Z
description = ""
draft = false
slug = "205"
tags = []
title = "DevOps'ish 205:"

+++

First off, Happy Valentine's Day. I hope you're enjoying it as best you can.

This week I learned that an organization in the healthcare industry is working on a large project involving Kubernetes [Pod Security Policies](https://kubernetes.io/docs/concepts/policy/pod-security-policy/) as a mainstay in their project. In case you haven't heard, Pod Security Policies (PSPs) will begin the [Kubernetes deprecation process](https://kubernetes.io/docs/reference/using-api/deprecation-policy/) in the 1.21 release. Kubernetes 1.21 releases on or about Thursday, April 8th, 2021. With PSPs being completely phased out by the 1.25 release (sometime in mid'ish 2022). When 1.21 is released, you'll see a message similar to the following when touching PSPs, "The PodSecurityPolicy API is deprecated in 1.21, and will no longer be served starting in 1.25." The [Kubernetes Contributor Marketing Team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) is working on an official blog post, but it is taking longer than I'd prefer given the amount of PSP utilization that's out there.

I'm writing this here because I have worked in large banks, healthcare systems, and government agencies where changes like this could take quite some time to plan, test, verify, and implement. But, what is replacing PSPs? Well, that's to be determined, which is equally terrifying to some. But, this is where folks have to have faith in the process. Sometimes we have to plan deprecation of something to force the community to respond to fill the gap.

Right now, from my seat, a viable replacement is [Open Policy Agent's Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/). Open Policy Agent (OPA) has recently moved to a [graduated CNCF Project](https://www.cncf.io/announcements/2021/02/04/cloud-native-computing-foundation-announces-open-policy-agent-graduation/). OPA is ready for production implementation. At this time, again, in my opinion, [OPA](https://www.openpolicyagent.org/) will be the de facto replacement for PSPs in the future. But, I will admit, the future is hard to predict at this level. There very well be many more viable alternatives in six to twelve months.

Other projects and products can help manage and enforce what pod requirements are for Kubernetes clusters. I will not be touching on those because, to be honest, [there are a lot of potential solutions](https://landscape.cncf.io/card-mode?category=security-compliance&grouping=category) in the CNCF Landscape. One of those alternatives has rubbed me wrong during the writing process of the PSP deprecation blog post. It's not their place to force us to provide a complete picture of the ecosystem in a singular blog post. We're trying to stay scoped to inform the masses of a deprecation. In the wake of the [dockershim deprecation](https://devopsish.com/195/), this is already hard enough. The Upstream Marketing team has a [charter](https://github.com/kubernetes/community/blob/master/communication/marketing-team/CHARTER.md). We wrote the [Ethos/Vision part of the subproject's charter](https://github.com/kubernetes/community/blob/master/communication/marketing-team/CHARTER.md#ethosvision) to prevent such behavior. State your case, don't try to force others to state it on your behalf.

Regardless, Kubernetes Pod Security Policies are going away and folks need to prepare for that. Start assessing what is using PSPs in your environment, what requirements it's implementing, and find a solution that can replicate that functionality.

## People

{{< tweet 1360276547018625028 >}}

[Ephemeral Environments as a Service 🤯](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102)  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team’s ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. Your developers will never have to fight over staging environments again. [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102). *SPONSORED*

PEOPLE

## Process

PROCESS

[10 Docker Security Best Practices](https://snyk.io/blog/10-docker-image-security-best-practices/)  
The top 10 most popular images have more than 30 known vulnerabilities. Learn best practices for choosing a secure base image and fixing container vulnerabilities. Check out the blog: <https://snyk.io/blog/10-docker-image-security-best-practices/>

PROCESS

## Tools

TOOLS

**LaunchDarkly** is a feature management platform that empowers all teams to safely deliver and control software through feature flags. By separating code deployments from feature releases, LaunchDarkly enables you to deploy faster, reduce risk, and iterate continuously. Microsoft, IBM, Atlassian, and 1500+ organizations use LaunchDarkly to build, operate, and learn from their software. [Learn more](https://launchdarkly.com/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) and start your free trial today! *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

TWEET

[![reminder - 'i like to make money' is a good enough reason to want to be paid fairly. — jill wohlner (@JillWohlner) February 3, 2021](/images/205-devopsish-tweet-of-the-week.png)](https://twitter.com/JillWohlner/status/1357082152094040064)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/205/notes/) to see what didn't make it to the newsletter.
