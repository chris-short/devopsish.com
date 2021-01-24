+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-01-24T07:00:00Z
description = "AWS/Elastic drama, "
draft = false
slug = "202"
tags = []
title = "DevOps'ish 202: AWS/Elastic drama, "

+++

Unpopular opinion alert...

Call me old fashioned, but I thought two of the top tenets of open source were candor and goodwill. I thought it was good practice to contribute to a project before baking it into a product. This was often the case for open source friendly vendors. But, it feels like AWS came along and never got that memo. I feel like AWS has done a lot more taking and productizing (aka making AWS a trillion-dollar, with a T, business) than contributing back to open source.

They keep shooting themselves in the foot as they take more and more projects into their bevy of services. A couple of weeks ago, I saw a tweet of a dev finding their code in the codebase of an AWS project without any credit being given, among other license violations. Someone at AWS said they'd look into it. But, consumption without credit incidents keeps happening (this wasn't the first such incident I'd observed). There's a culture problem, it seems. Then AWS hires a journalist to cover its open source work. I feel like that doesn't help its case at all either. It acknowledges awareness of a problem. Pay for play is a negative thing in the radio business. It's duplicitous at best in the tech industry.

I get it. AWS and others think [forking Elastic's code](https://aws.amazon.com/blogs/opensource/stepping-up-for-a-truly-open-source-elasticsearch/) was inevitable and acceptable. Maybe? On a different timeline, with candor and goodwill sprinkled on it, this is never an issue because AWS would be submitting heaping helpings of PRs that Elastic would gladly accept. It gives them the same capabilities in their product that a hyperscale cloud provider has. AWS wouldn't care because they rake in billions upon billions in profits every year. Sure they are technically assisting a competing product but, how many people using a non-AWS Elastic are also using higher-level AWS services? I imagine that's a tiny overlap in a Venn diagram. AWS and Elastic cater to *slightly* different personas. AWS was the most prominent cloud six years ago and had enough market share and growth to stay that way. Instead of helping an open source project, they consumed it to make money. This gave birth to the [bullshit SSPL license](https://opensource.org/node/1099), and the rest is history. Major takeaway: open source isn't a business model.

No one is right here, and customers pretty much get hosed on the software and services' price anyway. [Elastic makes its versions](https://www.elastic.co/blog/licensing-change) of ElasticSearch, LogStash, and Kibana. AWS makes a fork of the previously Apache-licensed code. Who wins here? Elastic and AWS. Developers don't win because they potentially have to make up for deficiencies in one version or the other. I feel like this fork and SSPL drama could very well have been preventable. But, what do I know? I've just been around open source for most of my life. It all feels gross.

**Note**: I’m looking for an intern this summer to help with [OpenShift.tv](https://OpenShift.tv?utm_source=newsletter&utm_medium=devopsish&utm_campaign=202) (live streaming). If you know anyone that may be interested, please ask them to apply. If they have questions, feel free to send them my way ([Twitter DMs](https://twitter.com/ChrisShort), [Telegram](https://t.me/ChrisShort)). Please [apply ASAP](https://us-redhat.icims.com/jobs/83032/openshift.tv-associate-producer-internship/job?utm_source=newsletter&utm_medium=devopsish&utm_campaign=202) as I’m already reviewing resumes this weekend.

## People

PEOPLE

## Process

PROCESS

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

PROCESS

## Tools

TOOLS

## DevOps'ish Tweet of the Week

{{< tweet 1352394137018847233 >}}

[![Just remember, at heart: this is two giant companies fighting to put their hand in your pocket. That one of them (AWS) is *also* fighting for open source is a side effect. I'm glad they're doing it. But their motivations aren't exactly pure either. Nobody's a hero here.](/images/202-devopsish-tweet-of-the-week.png)](https://twitter.com/adamhjk/status/1352394137018847233)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/202/notes/) to see what didn't make it to the newsletter.
