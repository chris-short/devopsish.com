+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-02-20T07:00:00Z
description = [""]
draft = false
slug = "257"
tags = []
title = "DevOps'ish 257: "

+++

I spent a lot of time working on the [dockershim removal](https://k8s.io/dockershim) documentation effort. These docs are vitally important and often require some technical hands to get things figured out. First, many people have to be very specific and finite in their relation with Docker and Kubernetes. Yes, it's cringe-worthy how often you say anything potentially harmful about Docker, and people think, "the entire container ecosystem will collapse without the existence of this one company." It shows how the learning paths to Kubernetes must be improved upon. Yes, you might need Docker Engine to get containers running on your Mac or Windows laptop. But, all the container bits are containerd (or CRI-O) now when you get into production. containerd is a graduated CNCF project (and is the default CRI in Kubernetes), and CRI-O is an incubating project. If you notice, Docker, Docker Engine, and anything else with the word docker are on the [CNCF projects](https://www.cncf.io/projects/) page. The internet shock and awe factor is real. It takes people with some battle hardening around the Docker topic to write some of these docs.

Second, the work is technologically hard. For example, `DefaultAddCapabilities` are a [docker specific concept](https://docs.petty.company/engine/reference/run/#runtime-privilege-and-linux-capabilities) exposed via Kubernetes. What happens to `DefaultAddCapabilities` when the dockershim is gone in 1.24. Keep in mind [Kubernetes Pod Security Policies](https://kubernetes.io/docs/concepts/policy/pod-security-policy/) aren't removed until 1.25. Do we remove these from all the docs? What happens to PSPs if those capabilities are just gone? What then? I've never done such fulfilling docs work in my life.

Third, I've had to test oddball use cases. Use Fedora and CRI-O with Kubernetes and update the docs around that. That use case generated questions about long strings in outputs, which the Docs team didn't have a style standard for necessarily. Getting the test environment up was an interesting enough challenge. But, what made it more interesting was having to create that environment twice because I deleted it when I started the PR (wait until your PRs merge before blowing away test environments). I've learned things I never knew about Kubernetes because I'm working on this project. We could use more help. Look for the dockershim named items in the CNCF Slack and CNCF Calendar.

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## People

PEOPLE

## Process

PROCESS

## Tools

TOOLS

## DevOps'ish Tweet of the Week

[![Jason H. Moore, PhD (@moorejh on Twitter) "#sciencetwitter"](https://shortcdn.com/file/devopsish/257-devopsish-tweet-of-the-week.webp)](https://twitter.com/moorejh/status/1491495889809993728)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/257/notes/) to see what didn't make it to the newsletter but are still worth your time.
