+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-08-29T07:00:00Z
description = []
draft = false
slug = "232"
tags = []
title = "DevOps'ish 232: "

+++

This was a trying week capped off by trigger point injections. Long story short, I've been trying to get a family out of Afghanistan for the past two weeks to no avail. I won't bore you with info or divulge identifying details. But, the possibility for their safe passage to the US has pretty much gone to 0. It's hard telling a 16 year old kid that you've exhausted all your resources. You can only offer tidbits of info. HUGE shoutout to the team behind [Ehtesab](https://ehtesab.af/) for enabling me to get SOME intel from folks on the ground. The situation itself is a failure.

This is a failure on multiple levels. But, it's a stark reminder that you have to experiment and sometimes try all the ways possible to get a solution into production. Can you deploy this feature as a feature flag or do you need to do a canary or blue/green deployment?  At what layer are you going to manage THAT? Your global load balancer? Maybe inside your application stack on a `keepalived` instance? Maybe it's better to handle this in your Kubernetes cluster by managing replica sets and ingresses. Once you get past that decision there are many more along the way. Then it's go time. Your solution is ready to handle some production traffic.

You start seeing increased errors so you rollback. This isn't a failed release though, maybe it's a bug somewhere else in the system. Maybe your environments aren't as consistent as you thought. Maybe you're lacking a critical piece of information that somehow didn't make it to you (a recent change in the system like admission controllers being enabled for prod). This is why having a team that you can actively collaborate with is vital. You can do this in person or via Slack/Teams/etc. Regardless your peers might have seen behaviors like this before and they know the answer. Better yet, the team rallies around the error and figures out your ingress isn't configured quite right (or you forgot a crucial new config). Remember the concept of [above the line and below the line](https://queue.acm.org/detail.cfm?id=3380777). You might have a fantastic understanding of the abstrations but, maybe not that 20% use case people bump into.

The point is, test, validate, get peer reviews, and use your people network (internal or external) to the best of your ability. People are your greatest asset no matter what part of the stack you're working under. People hold knowledge and capabilities. Never stop growing those networks. They will pay off at some point. Yes, soft skills matter more than your coding, configuration, and tests A LOT.

## People

PEOPLE

[Easy steps on how to secure your Kubernetes cluster by installing Teleport, an open-source, identity-aware access proxy.](https://youtu.be/2diX_UAmJ1c?utm_source=devopsish&utm_campaign=232)  
Teleport allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments. Learn more at [https://goteleport.com/docs/](https://goteleport.com/docs/?utm_source=devopsish&utm_campaign=232) *SPONSORED*

PEOPLE

## Process

PROCESS

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
Code, No Manual Processes. Automate Terraform tasks, reduce errors and drifts, improve security and auditability of your infrastructure. env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. *SPONSORED*

PROCESS

## Tools

TOOLS

[Manage incidents directly from Slack 🧑‍🚒](https://consuming-macrospore.herokuapp.com/b?y=49q24eh2c4r3ce1gcoo3echi65h62opj74rjcdpic9ij6e3571im4dpocch2o8ji48t24q3keho76ehf5tp6urrkdhsisqbf5svnat3dbtpmutbicdijqrj5etpmopbkehin49j1dlo3mtbkdlfmqpb4d5qmqfb4clr6us3jd5pmg8g=?utm_source=devopsish&utm_campaign=232)  
Rootly helps automate the tedious manual work like creating incident channels, searching for runbooks, documenting the postmortem timeline, and more. Teams sized 20 to 2000 manage hundreds of incidents daily and save thousands of engineering hours a year within Rootly. Get started in <5min or book a demo to learn more and get Starbucks ☕ on us! *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

[![Jaana Dogan ヤナ ドガン (@rakyll) on Twitter: "Hard skills are hard, soft skills are harder."](/images/232-devopsish-tweet-of-the-week.png)](https://twitter.com/rakyll/status/1430696443044532228)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/232/notes/) to see what didn't make it to the newsletter but are still worth your time.
