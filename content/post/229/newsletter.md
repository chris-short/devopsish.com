+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-08-08T07:00:00Z
description = [""]
draft = false
slug = "229"
tags = []
title = "DevOps'ish 229: Kubernetes 1.22, KubeCon schedule announced, "

+++

Kubernetes 1.22 shipped this week. I suggest you at a minimum read the [release blog post](https://kubernetes.io/blog/2021/08/04/kubernetes-1-22-release-announcement/) or take a gander at the [CHANGELOG](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.22.md) and definitely read the [No, really, you MUST read this before you upgrade](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.22.md#no-really-you-must-read-this-before-you-upgrade). Some of the bigger changes:

* Audit log files are created with mode 0600 (owner read-only)
* Rootless mode containers moving to alpha: In my opinion, if you use Podman, you're used to this. If you're not, you should be using rootless containers intentionally for security reasons (more on that later).
* Cgroupsv2 moving to alpha
* Pod Security Policy replacement (aka Pod Security Admission Controller): Yes, [PSPs are deprecated](https://devopsish.com/205/) and being replaced. [There are a lot of reasons why](https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/).
* LoadBalancer moving to beta
* Enable seccomp by default
* and a whole bunch more

KubeCon NA 2021 acceptances went out this week and [the schedule is live](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/program/schedule/). I'm excited to say I'm teaming up with [Kaslin Fields](https://twitter.com/kaslinfields), [Bart Farrell](https://twitter.com/birthmarkbart), [Matthew Broberg](https://twitter.com/mbbroberg), and [Kunal Kushwaha](https://twitter.com/kunalstwt) for [a panel talk](https://kccncna2021.sched.com/event/lV3S) about what we've been doing in the [Kubernetes Upstream Marketing Team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) (which includes the [@K8sContributors](https://twitter.com/K8sContributors/) Twitter handle and so much more).

A note about KubeCon: I want everyone that might be speaking at a Day 0 event or trying to get to KubeCon to know that if anyone needs financial support, please apply for a scholarship, either diversity or needs-based here: <https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/>

## People

PEOPLE

[A Non-Tech Explanation of Containers and Kubernetes](https://www.linode.com/content/declarative-cloud-infrastructure-management-terraform-linode/?utm_source=tldr&utm_medium=newsletter_sponsorship&utm_campaign=newsletter_sponsorship-tldr-terraform&utm_content=ebook-terraform&utm_term=)  
100 Million Downloads and Over 5,000 Ecosystem Add-Ons later, Hashicorp has released the 1.0 version of Terraform.  This eBook and audiobook will help you understand the underlying concepts of this infrastructure as a code tool and how it can be a significant resource when your cloud infrastructure hits critical mass. *SPONSORED*

PEOPLE

## Process

PROCESS

[Collaboration and Automation for Infrastructure as Code](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dymanic RBAC and quality of life features. Free Demo. *SPONSORED*

PROCESS

## Tools

TOOLS

[Search your code. ALL of it, everywhere.](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text)  
Imagine if you could search all your code across every repo, every language, every code host. You can with [Sourcegraph universal code search](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). Quickly navigate code with contextual hover tooltips that show definitions, references, and usage examples. Construct complex queries and filter code in ways that IDEs and code hosts can't. Find and fix code fast, without losing your flow. Sourcegraph universal code search is a dev's superpower. [Get it now](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

I know AWS has a UX team. I don't know if AWS listens to their UX team though.

[![C:\hristina (@divinetechygirl) on Twitter: "Does AWS make AWS confusing on purpose or ¯\_(ツ)_/¯¯¯? Like you shouldn't have to study for a cert just to figure out how to do things in the UI 🤦🏽‍♀️ Please note: I do not need help and figured out how to do what I needed to do but it was definitely not straight forward."](/images/229-devopsish-tweet-of-the-week.png)](https://twitter.com/divinetechygirl/status/1422954646918864905)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/229/notes/) to see what didn't make it to the newsletter but are still worth your time.
