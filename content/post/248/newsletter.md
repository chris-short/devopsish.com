+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-12-19
description = ["Log4j every day, the groping metaverse, e-waste, Deciding Between Argo CD and Flux, what happens when you upgrade to Kubernetes 1.24, and more"]
draft = false
slug = "248"
tags = ["log4j", "cloud", "Kubernetes", "open source", "GitOps", "DevOps", "developers", "server", "cloud native", "GRPC", "infrastructure", "vulnerability", "API"]
title = "DevOps'ish 248: Log4j every day, the groping metaverse, e-waste, Deciding Between Argo CD and Flux, what happens when you upgrade to Kubernetes 1.24, and more"

+++

For some of us, we need a break. Going at a break neck speed while stretched out mentally and physically is exhausting. I find myself needing a break from at least one of the things I do. Can't cut out my job; can't cut out the newsletter. I think until the new year, I'm going to take a break from open source contributions. Expect no open source work from me until 2022 (minus writing because I enjoy that).

[Log4j](/248/notes/#log4j) dominated the news this week. I was pulling nuggets in for KubeWeekly earlier this week and it literally felt like every other post was about Log4j. I have know lost count of how many CVEs there in Log4j. But, it's all impactful. Even if your in house systems aren't based around Java there is likely something in your enterprise that requires log4j and you need to make sure your vanquish this at multiple layers of the stack.

## People

[The metaverse has a groping problem already](https://www.technologyreview.com/2021/12/16/1042516/the-metaverse-has-a-groping-problem/)  
I really hope to avoid the metaverse.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Reducing e-waste: Could refurbished IT equipment be better than new?](https://www.wholegraindigital.com/blog/refurbished-it/)  
Greener IT means making use of what we have for longer periods of time. This is why I bought a used server for the house. This is also why I'd do it again if I needed one.

[Developer Avocados - Chris Short](https://avocados.dev/adventcado/2021/12/15/chris-short/)  
Developer Avocados did a profile on me (I genuinely do thank them). 

## Process

[A Log4J Vulnerability Has Set the Internet 'On Fire'](https://www.wired.com/story/log4j-flaw-hacking-internet/)  
Wired being ever so subtle. "The problem lies in Log4j, a ubiquitous, open source Apache logging framework that developers use to keep a record of activity within an application. Security responders are scrambling to patch the bug, which can be easily exploited to take control of vulnerable systems remotely. At the same time, hackers are actively scanning the internet for affected systems. Some have already developed tools that automatically attempt to exploit the bug, as well as worms that can spread independently from one vulnerable system to another under the right conditions." Find more [Log4j coverage in the notes](/248/notes/#log4j) for this issue. Also, check out [log4j memes](https://log4jmemes.com/).

[Pulumi: Infrastructure as Code](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)  
Developing on the cloud is complex. What if you could use your existing programming knowledge to build, deploy, and manage cloud infrastructure using your favorite languages and tools? Pulumi is a cloud engineering platform that lets you write infrastructure as code in any programming language and on any cloud platform. Get started for free at pulumi.com *SPONSORED*

[Minimum viable action – how to advance things that are stuck](https://www.eficode.com/blog/minimum-viable-action-how-to-advance-things-that-are-stuck)  
A process in which to get the hard stuff done.

[GitOps on Kubernetes: Deciding Between Argo CD and Flux](https://thenewstack.io/gitops-on-kubernetes-deciding-between-argo-cd-and-flux/)  
"Below are the results of exploring the differences between these two projects. Both have their uses, and both are quite well maintained and have active communities."

[Summary of the AWS Service Event in the Northern Virginia (US-EAST-1) Region](https://aws.amazon.com/message/12721/)  
Thundering herds gonna thunder.

## Tools

[Kubernetes isn't about containers](https://joshgav.github.io/2021/12/16/kubernetes-isnt-about-containers.html)  
It's about APIs.

In modern architecture, slow is the new down. Distributed tracing shows your deeply hidden problems so you can fix the right issue the first time. It's never been easier to get started. [Use Honeycomb and OpenTelemetry](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) to quickly find hidden slowness–for free. *SPONSORED*

[What happens when you upgrade to Kubernetes v1.24?](https://jimangel.io/post/dockershim-kubernetes-v1.24/)  
Jim Angel wonders what happens when you rip out dockershim when you need it.

[gRPC - Best Practices](https://kreya.app/blog/grpc-best-practices/)  
"Designing gRPC services is different from designing REST services, where the API contract (ex. OpenAPI) is often generated from the server implementation. With gRPC, it's the other way around. The API contract is first defined in protobuf, then the client and server stubs are generated from that API definition. In this section, we explain some of the best practices when designing gRPC APIs."

[LogMeIn to spin off password manager LastPass as a separate company](https://siliconangle.com/2021/12/14/logmein-spin-off-password-manager-lastpass-separate-company/)  
It didn't make sense [when LogMeIn bought LastPass](https://chrisshort.net/lastpass-sells-out-to-logmein/). It only makes sense they're spinning it out.

[aws/amazon-ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector)  
A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory

[ossf/wg-best-practices-os-developers](https://github.com/ossf/wg-best-practices-os-developers)
"The Best Practices for OSS Developers working group is dedicated to raising awareness and education of secure code best practices for open source developers."

[hjacobs/kube-ops-view](https://codeberg.org/hjacobs/kube-ops-view)  
"Kubernetes Operational View - read-only system dashboard for multiple K8s clusters"

[reddec/ingress-dashboard](https://github.com/reddec/ingress-dashboard)  
Kubernetes-native automatic dashboard for Ingress

[aws-samples/kubernetes-log4j-cve-2021-44228-node-agent](https://github.com/aws-samples/kubernetes-log4j-cve-2021-44228-node-agent)

[Cybereason/Logout4Shell](https://github.com/Cybereason/Logout4Shell)  
Use Log4Shell vulnerability to vaccinate a victim server against Log4Shell

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/248/notes.md) to see what didn't make it to the newsletter but are still worth your time.
