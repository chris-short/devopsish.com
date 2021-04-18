+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-04-17T07:00:00Z
description = ["Kubernetes mentioned 26 times, Burnout, VMware spun off, Google's FloC, Kanban, chip shortage, shell operator and more"]
draft = false
slug = "214"
tags = ["Kubernetes", "burner", "DevOps", "open source", "cloud", "cloud native", "cluster", "ingress", "burnout", "Amazon", "CNCF", "tech", "pay", "edge", "Chrome", "OpenShift", "distributed tracing", "Argo", "emissary", "Operators", "developers", "compassion", "VMware", "IBM", "security", "FLoC", "Google", "APIs", "Kanban", "Intel", "TSMC", "chip shortage"]
title = "DevOps'ish 214: Kubernetes mentioned 26 times, Burnout, VMware spun off, Google's FloC, Kanban, chip shortage, shell operator and more"

+++

We've had [another rough week](https://twitter.com/ChrisShort/status/1381365508470145027) in the Short household. The adults, at least, are exhausted. [Max is fully energized](https://twitter.com/ChrisShort/status/1382694680350064643). Sunny is getting [nursed back to health](https://twitter.com/ChrisShort/status/1381590349408243718).

I always try to provide some value in the intro but, I have to say, I almost skipped this week due to everything. Some valuable nuggets live on a few other sites I run. New and old subscribers alike can get some benefit from these:

* [DevOps README.md](https://devopsreadme.xyz/): What books 📚 to read to learn more about DevOps.
* [DevOps Newsletters](https://devopsnewsletters.com/) intends to be a one stop shop for the best DevOps content from around the world.
* [Kubernetes README](https://kubernetesreadme.com/): What books 📚 to read to learn more about Kubernetes.
* [Kubernetes News](https://kubenews.net/) intends to be a resource to help keep up with the wide ranging and rapidly evolving world of Kubernetes.

I'm speaking as part of a group talk about non-code contributions, specifically the work we've been doing on the Kubernetes Upstream Marketing Team. Please [add it to your KubeConEU schedule](https://kccnceu2021.sched.com/event/iE6I/how-you-can-tell-your-kubernetes-contributor-story-with-these-tips-matt-broberg-chris-short-red-hat-kaslin-fields-google-peeyush-gupta-digitalocean).

## People

[Tech whistleblowers like Timnit Gebru can't just move on](https://www.protocol.com/big-tech-whistleblowers)  
"People have often reported on whistleblowing matter-of-factly as though we did it and moved on with our lives." But that couldn't be further from the truth.

Learnk8s is running 2 and 4 days Kubernetes courses on the 20th of May. If you want to understand the inner workings of Kubernetes & how to apply it in practice then this course is for you. The course is beginner-friendly and hands-on. [Register now](https://learnk8s.io/online-advanced-may-2021) *SPONSORED*

[Leaked Documents Show How Amazon Rates Employees in Annual Reviews](https://www.businessinsider.com/amazon-employees-annual-reviews-rating-2021-4)  
"The rating also sets the total compensation target for each employee. Amazon employees are each put in a pay band with a range for their total compensation, made up of base pay and stock options. One internal document said those placed in the top-performing group could reach 100% of their pay target, while those on the HV1 grade got zero upside." And that's not the worst of it.

[Why you need a platform team for Kubernetes](https://polarsquad.com/blog/why-you-need-a-platform-team-for-kubernetes)  
"Setting up a Kubernetes cluster can be deceptively simple, as there are plenty of installers to create a basic cluster in minutes. However, that’s only the start of the actual work. Kubernetes moves fast; when it’s a critical part of your infrastructure, there’s a host of things you need to look out for to maintain a healthy cluster. More often than not, it’s wise to have a dedicated team to run Kubernetes."

[Valuable Resources for Black Women Coders in Tech](https://peopleofcolorintech.com/front/valuable-resources-for-black-women-coders-in-tech/)  
"Today we’ve put together a list of communities, podcasts, and blogs, that provide a space for Black women software developers to feel seen and heard, as well as supported throughout their journey."

[Your Burnout Is Unique. Your Recovery Will Be, Too.](https://hbr.org/2021/04/your-burnout-is-unique-your-recovery-will-be-too)  
"While it’s up to employers to provide a working environment that prevents burnout as much as possible, new research suggests that addressing burnout once you’re suffering from it is a little more complicated. There are steps that organizations can (and should) take to support their employees, but the most effective measures to counteract burnout are generally driven by the individual. Specifically, employees should start by identifying the source or sources of their burnout, and should then take action by focusing on self-care, acts of kindness towards others, or some combination of the two. Most importantly, the authors stress that compassion — whether towards yourself or your colleagues — is a muscle that can be trained, and that developing and practicing compassion is the key to combatting burnout."

## Process

[Dell Technologies Announces Planned VMware Spin-Off](https://investors.delltechnologies.com/news-releases/news-release-details/dell-technologies-announces-planned-vmware-spin)  
No one saw this coming... I mean no one. This barely made a blip on the radar this week despite being good news for VMware.

[Learn what LaunchDarkly can do for your organization.](https://learn.launchdarkly.com/demo?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)
LaunchDarkly enables companies like Square, Hulu, Atlassian, Toyota, Intuit, IBM, and others gain a competitive edge with better feature management.  
Move fast without breaking things and learn how your team can reap the rewards of CI/CD without the risk.  
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Security researcher drops Chrome and Edge exploit on Twitter](https://therecord.media/security-researcher-drops-chrome-and-edge-zero-day-on-twitter/)  
"While details about the exact nature of the bug were never publicly disclosed, Agarwal told The Record he spotted the patches for this bug by looking at the source code commits to the V8 JavaScript engine, a component of the Chromium open-source browser project, which allowed him to recreate the Pwn2Own exploit, which he uploaded earlier today on GitHub, and shared on Twitter." People like this are why we can't have nice things.

[Firefox, Edge, Safari, and other browsers won’t use Google’s new FLoC ad tech](https://www.theverge.com/2021/4/16/22387492/google-floc-ad-tech-privacy-browsers-brave-vivaldi-edge-mozilla-chrome-safari)
Get yourself [up to speed on FLoC](https://brave.com/why-brave-disables-floc/). It's a bad news new feature that Google is replacing third party cookies. If you HAVE to use Chrome there is help in the form of the [DuckDuckGo Chrome extension](https://spreadprivacy.com/block-floc-with-duckduckgo/) and a site run by the EFF, [Am I FLoCed?](https://amifloced.org/)

[APIs Aren’t Just for Tech Companies](https://hbr.org/2021/04/apis-arent-just-for-tech-companies)  
Pretty wild when Harvard Business Review is writing about APIs.

[The Problem With Agile Scrum (and Why We Use Kanban Instead)](https://www.cloudzero.com/blog/why-cloudzero-uses-kanban)  
Kanban runs everything around me.

[Intel, Nvidia, TSMC execs agree: Chip shortage could last into 2023](https://arstechnica.com/gadgets/2021/04/intel-nvidia-tsmc-execs-agree-chip-shortage-could-last-into-2023/)  
We're all going to feel this chip shortage at some point, I'd imagine. It's already [affecting folks here in Detroit](https://www.fox2detroit.com/news/more-computer-chip-shortages-cause-auto-plants-to-shut-down).

## Tools

[Introducing kube-burner, A tool to Burn Down Kubernetes and OpenShift](https://www.openshift.com/blog/introducing-kube-burner-a-tool-to-burn-down-kubernetes-and-openshift)  
"Kube-burner is a tool designed to stress different OpenShift components basically by coordinating the creation and deletion of k8s resources... Kube-burner is a static compiled binary written in Golang, and makes an extensive usage of the client-go library to interact with the API." Put the screws to your clusters with greater ease.

Distributed Tracing shows the relationships between microservices in a distributed system—but unfortunately, it has a bad reputation as being difficult to instrument, implement, and decipher. With Honeycomb Beelines, having the tracing you deserve is easier than you think. Learn how with our "[Distributed Tracing for Microservices Guide](https://www.honeycomb.io/distributed-tracing-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=guide-distributed-tracing-devopsish&utm_adgroup)."

Guess less and know more with [Honeycomb](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Kubernetes is moving to three releases a year](https://groups.google.com/g/kubernetes-dev/c/IxnWeVRIadM/m/Mqkp6j1TAAAJ?pli=1)  
"The current plan, outlined by the KEP, is to continue the *3* Release Per Cadence that we adopted in an ad hoc manner in 2020. Kubernetes 1.22 and Kubernetes 1.23 will each be approximately 15 weeks, with the following tentative release dates:

Kubernetes 1.22: August 2nd (tentative)  
Kubernetes 1.23: December 14th (tentative)"  
I'm all for this intentional slow down to allow for the Release teams to just have a chance to get their standing.

[Argo Workflows 3.0, a detailed look at what’s new from the Argo Team](https://www.youtube.com/watch?v=ttWR5OVSwmM)  
Henrik Blixt and Alex Collins show off some new Argo workflows features.

[emissary-ingress (formerly Ambassador) is now a CNCF incubating project](https://www.cncf.io/blog/2021/04/13/emissary-ingress-formerly-ambassador-is-now-a-cncf-incubating-project/)  
"The CNCF Technical Oversight Committee (TOC) has voted to accept emissary-ingress as a CNCF incubating project. Emissary-ingress, formerly known as Ambassador, is an open source ingress controller and API Gateway for Kubernetes. It is built on Envoy Proxy and supports a wide range of use cases for ingress, including load balancing, authentication, and observability."

[Verify OCI Container Image Signatures in Kubernetes](https://blog.sigstore.dev/verify-oci-container-image-signatures-in-kubernetes-33663a9ec7d8)  
"With Connaisseur adding experimental support for Cosign, you can now verify OCI container image signatures in Kubernetes. Here is how."

[Ask an OpenShift Admin Office Hour - Day 2 Operations, Part 1](https://www.openshift.com/blog/ask-an-openshift-admin-office-hour-day-2-operations-part-1)  
My teammate Andrew Sullivan and I talked about all the bits that are considered day 2 operations after your cluster is up and running. Well at least part of them. [Tune in this week for part 2](https://youtu.be/2XLPbZE9UAU).

[Enforcing Policy as Code using OPA and Gatekeeper in Kubernetes](https://elastisys.com/enforcing-policy-as-code-using-opa-and-gatekeeper-in-kubernetes/)  
"Enforcing organizational policies on a Kubernetes cluster allows you to be in control of the resources being deployed. For example, you can prevent deploying non-vetted pods to the production environment or disable usage of default passwords for databases. Doing so stops you from worrying about quarterly security reviews and a ton of issues in your backlog."

[Postgres is Out of Disk and How to Recover: The Dos and Don'ts](https://blog.crunchydata.com/blog/postgres-is-out-of-disk-and-how-to-recover-the-dos-and-donts)  
"Welp ...... sometimes ~~'stuff'~~ shit happens  ...... and you find yourself having a really bad day."

[Apache Mesos Narrowly Avoids a Move to the Attic (for Now)](https://thenewstack.io/apache-mesos-narrowly-avoids-a-move-to-the-attic-for-now/)  
Sounds like they're trying to restart the project with pretty much everyone converting over to Kubernetes.

[shell-operator v1.0.0: the long-awaited release of our tool to create Kubernetes operators](https://blog.flant.com/shell-operator-v1-release-for-kubernetes-operators/)  
Operators based on shell. Madness but totally awesome.

[extrawurst/gitui](https://github.com/extrawurst/gitui)  
Blazing 💥 fast terminal-ui for git written in rust 🦀

[rothgar/awesome-tuis](https://github.com/rothgar/awesome-tuis)  
List of projects that provide terminal user interfaces

[harlanc/xiu](https://github.com/harlanc/xiu)  
A rtmp live server

[calendso/calendso](https://github.com/calendso/calendso)  
The open-source Calendly alternative.

[kdash-rs/kdash](https://github.com/kdash-rs/kdash)  
A simple and fast dashboard for Kubernetes

## DevOps'ish Tweet of the Week

[![@eanakashima on Twitter: We went through the whole "no more heroes" arc for ops/engineers in the early days of DevOps. Some days it feels like we need to figure out the variant of that for managers & leaders."](/images/214-devopsish-tweet-of-the-week.png)](https://twitter.com/eanakashima/status/1382065119400583169)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/214/notes/) to see what didn't make it to the newsletter but are still worth your time.
