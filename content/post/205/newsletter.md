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

I'm writing this here because I have worked in large banks, healthcare systems, and government agencies where changes like this could take quite some time to plan, test, verify, and implement. But, what is replacing PSPs? Well, that's to be determined, which is equally terrifying to some. But, this is the process in Kubernetes. Sometimes we have to plan deprecation of something, which forces the community to respond to fill the gap.

Right now, from my seat, a viable replacement is [Open Policy Agent's Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/). Open Policy Agent (OPA) has recently moved to a [graduated CNCF Project](https://www.cncf.io/announcements/2021/02/04/cloud-native-computing-foundation-announces-open-policy-agent-graduation/). OPA is ready for production implementation. At this time, in my opinion, OPA will be the de facto replacement for PSPs in the future. But, I will admit, the future is hard to predict at this level. There very well be many viable alternatives in six to twelve months.

Other projects and products can help you manage and enforce what pod requirements are for your clusters. I will not be touching on those because, to be honest, there are a lot of them. One of those alternatives has pissed me off during the writing process of the deprecation blog post. Trying to wiggle their way into every nook and cranny of the discussion isn't helpful. It's not their place to force us to provide a complete picture of the ecosystem in a singular blog post, trying to stay scoped to inform the masses of a deprecation. In the wake of the [dockershim deprecation](https://devopsish.com/195/), this is already hard enough. The Upstream Marketing team is not expressly their marketing team (I wrote the [Ethos/Vision part of the subproject's charter](https://github.com/kubernetes/community/blob/master/communication/marketing-team/CHARTER.md#ethosvision) to prevent such behavior). Get out of the way, let us maintain our scope, and please don't spread any FUD. State your case, don't try to force others to state it on your behalf.

I will say that my employer, Red Hat, has solutions for this problem ready now. If you're an OpenShift customer, you'll be okay. I'd hope that's the case for the other vendors, but there are too many for me to assess myself. Reach out to your vendor if you're using one. Vanilla K8s users should begin researching.

Regardless, Pod Security Policies are going away and you need to prepare for that. Start assessing what is using PSPs in your environment, what requirements it's implementing, and find a solution that can replicate that functionality.

## People

PEOPLE

[Ephemeral Environments as a Service](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102)  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team’s ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. Your developers will never have to fight over staging environments again. [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102). *SPONSORED*

PEOPLE

## Process

PROCESS

AD

PROCESS

## Tools

TOOLS

[Effective Feature Management](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
What if your team could safely ship software features faster? Gain a competitive advantage with Effective Feature Management: Releasing and Operating Software in the Age of Continuous Delivery by O'Reilly, written by LaunchDarkly CTO & Co-founder John Kodumal. So you can deploy when you want, release when you’re ready and enable valuable product innovation. Download your [free copy](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) today! *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

TWEET

[![reminder - 'i like to make money' is a good enough reason to want to be paid fairly. — jill wohlner (@JillWohlner) February 3, 2021](/images/205-devopsish-tweet-of-the-week.png)](https://twitter.com/JillWohlner/status/1357082152094040064)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/205/notes/) to see what didn't make it to the newsletter.
