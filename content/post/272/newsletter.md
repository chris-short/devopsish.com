+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-06-19T07:00:00Z
description = [""]
draft = false
slug = "272"
tags = []
title = "DevOps'ish 272"
+++

I'll be at Open Source Summit this week in Austin. If you see me, stop me and say hello.

Conway's Law and GitOps are two things that go hand in hand. I'd like that not to be the case, but in building and working with an upcoming demo of multi-cluster GitOps, I'm worried GitOps might not reach an escape velocity over Conway's Law.

[Conway's Law](https://en.wikipedia.org/wiki/Conway%27s_law) states, "Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure." This might seem natural but think about the different ways we communicate now. E-mail, text messages, phone calls, Slack, Discord, Twitter, etc. are all communication tools that serve various purposes. But, in GitOps, whether you design around a good developer experience (using git as the only interface) or design around a minimalistic amount of tooling (one secret management solution), that tooling has to fit within Conway's Law usually.

For example, if you want to use an existing tool with GitOps, that's entirely possible. But, that tool, let's say a key management system (KMS), has rules of its use, and automating them will need you to build a system that can interface well with the team that runs that system. If you're lucky, you can run your Vault in your namespace and minimize handoffs. This is the only way to escape Conway's Law in GitOps. Decoupling the entire system from the rest of the org. Bring everything you need as a team to the platform, and running it all yourself will minimize the communication lanes, but I doubt it will reduce your system's footprint.

Sure. You can then dictate what communications need to occur to make system changes. But, this will create a lot of overlap, and at some point, someone in compliance or finance or both will say, "Everyone is running their own Vaults with different policies and availability metrics. We could run Vault Enterprise and have all our regulatory needs met and HA." Now you have to communicate outside your team. That will lead to you building a system that looks like the communication structure of your organization. This isn't bad. It's something you need to be aware of.

This is when Conway's Law and GitOps intersect. The moment you start to make optimizations to the system at scale. Secrets management is a crucial yet still engineering-intensive part of GitOps. Who manages the key management system? Who creates an "inception secret" that opens the door to seed all the other secrets? What processes create a management cluster? All these answers will come back to Conway's Law. It's like fate or Darth Vader telling Luke Skywalker, "Let's rule the Galaxy together as Father and Son!" This is something that isn't pleasant, but we have to accept it.

There are specific components you need to make a GitOps workflow. These foundational steps should be on a trail map of their own for GitOps. CNCF, Weaveworks, or Amazon could make it. That would be the top half of the page. The bottom half of the page lies this intro about the intersection of GitOps and Conway's Law.

This might be the last piece I write on GitOps for a little bit. I'm making a move internally and won't be directly focused on Kubernetes. Being in that community (or, more accurately, being in CNCF's chaotic orbit) has taken a significant toll on me lately. I will still be in the container ecosystem, and you'll see me around. But, at the end of the month, my journey on the EKS team will change to a new one I'm very excited about.

## Observability Leader Honeycomb Releases O’Reilly Book on Observability

Honeycomb helps you sift through billions of events to see your application’s hidden problems so you can quickly debug before users notice. Get your FREE copy of our [new O’Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors’ Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts

## Events

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

## People

PEOPLE

## Process

PROCESS

## Tools

TOOLS

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
