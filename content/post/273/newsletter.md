+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-06-26T07:00:00Z
description = [""]
draft = false
slug = "273"
tags = []
title = "DevOps'ish 273: "
+++

This week I was in Austin, Texas (where it was hotter than the hinges of hell) at Open Source Summit. I staffed the AWS booth, attended a few talks, met with friends I hadn't seen in long, and became generally reinvigorated about open source. It's my last event on the Amazon EKS team. I'm moving inside the Containers organization at AWS to work on a new and different project.

AWS was a leading sponsor. I had great conversations with folks. Undergrads, customers, partners, and others had questions about Kubernetes, EKS, or GitOps. I gave a booth demo on Multi-Cluster GitOps, a solution we intend to open source soon.

I was impressed by quite a few sponsors there. [Camunda](https://camunda.com), [Coder](https://coder.com) (thanks for the Caddy config), [KubeCost](https://www.kubecost.com/), [Solo](https://www.solo.io/), and [Capital One](https://www.capitalone.com/tech/) all had great presences at the conference. But two newer companies melted my brain with how excellent their products were: **Fermyon** and **Clockwork**.

[Fermyon](https://www.fermyon.com) ventured out to start a company for all you WebAssembly fans (closet fan, still need to learn it). Fermyon is making a batteries included WebAssembly platform. I feel Fermyon will soon make its way into the mainstream WebAssembly developers' workflows. My friend Michelle Dhanani and others from Microsoft are there, so I'm certain they'll be doing some fantastic things. Be sure to checkout their `spin` repo in the [Tools](#tools) section.

[Clockwork](https://www.clockwork.io/) is another company that caught my eye. Their premise is that their time service is highly available AND highly accurate. Using this in your Kubernetes cluster will provide very precise time stamps. If you've ever noticed an event in your cluster before the resource was created, you need a better timing solution, and Clockwork is here to provide it. They are so accurate and highly available that they compare themselves to Google Spanner's TrueTime system, which helps that database solution overcome the CAP Theorem. They demonstrated microsecond accuracy even when they lose significant resources and time stays accurate to the microsecond.

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

[fermyon/spin](https://github.com/fermyon/spin)  
"Spin is an open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly"


### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
