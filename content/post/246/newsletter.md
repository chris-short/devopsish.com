+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-12-05T07:00:00Z
description = ["A little terrorism, The Case of the Recursive Resolvers, Knative asks to join CNCF, Karpenter, and move"]
draft = false
slug = "246"
tags = ["cloud", "Cloud Native", "AWS", "DevOps", "open source", "GitOps", "infrastructure", "code", "Kubernetes", "impostor syndrome", "Microsoft", "Honeycomb", "social model", "CKAD"]
title = "DevOps'ish 246: A little terrorism, The Case of the Recursive Resolvers, Knative asks to join CNCF, Karpenter, and more"

+++

AWS re:Invent was this week. I put a whole section in the notes this week for y'all all about [AWS re:Invent](/246/notes/). There were a lot of cool announcements this week. There was a scenario where I was going to be there. But, family was getting COVID-19 vaccines the Sunday before, I had doctor's appointments, and it wasn't meant to be. Thank the Maker I didn't end up going. This week has been a nightmare, wrapped in worry, with a big dose of impostor syndrome on top, and I caught a cold too.

First, there were multiple family crises. At one point in time my sole focus was on two of my nephews because we needed to watch them at one point with an extra dose of sunshine. Really glad I was here to help and support. Then [part of a terror plot unfolded](https://www.wxyz.com/news/oxford-school-shooting/prosecutor-details-disturbing-warning-signs-and-events-that-led-up-to-the-oxford-high-school-shooting) in our front yards. This story is really sad, bad, and preventable. A lot of people failed in their responsibilities and people are dead as a result. It's a truly horrible situation. Max was home from school for two days this week. Again, glad I was here to help and support. I think everyone in the know was definitely pegged out on the stress meter. Normally, I turn to work to help distract me from stress but, I'm still forming my path. That's when the impostor syndrome set in (because that's a totally normal reaction). Thankfully, [this video helped with the impostor syndrome](https://www.youtube.com/watch?v=Bz8F9YT4axA). I got the ship righted by Friday. But, wow... This week has been something else.

## People

[CKAD - free materials](https://www.reddit.com/r/kubernetes/comments/r4q1ec/ckad_free_materials/)  
This is a pretty great list if you're interested in passing the CKAD.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Microsoft shareholders back protest vote over sexual harassment claims](https://arstechnica.com/tech-policy/2021/11/microsoft-shareholders-back-protest-vote-over-sexual-harassment-claims/)  
I was wondering when someone was going to say something about how maybe something might be off about how Microsoft handled sexual harassment when Bill Gates was at the helm. Yes, this should definitely be investigated.

[5 Signs It's Time to Quit Your Job](https://cate.blog/2021/11/29/5-signs-its-time-to-quit-your-job/)  
"6. Bonus: You're reading this." Well there's that.

[Document Detail - Property of the People](https://propertyofthepeople.org/document-detail/?doc-id=21114562)  
Use Signal.

[Ex-Googler Timnit Gebru Starts Her Own AI Research Center](https://www.wired.com/story/ex-googler-timnit-gebru-starts-ai-research-center/)  
"The researcher, who says Google fired her a year ago, wants to ask questions about responsible use of artificial intelligence."

## Process

[The Case of the Recursive Resolvers](https://slack.engineering/what-happened-during-slacks-dnssec-rollout/)  
Absolutely fascinating deep dive into a production rollout that had fits and starts. Then when it was finally go time, things went poorly. This is a must read.

Join us for [Honeycomb Developer Week](https://www.honeycomb.io/developer-week-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish) on Dec 13–15! With free hands-on training and snackable sessions, you'll learn leading edge observability practices in just a few hours. Learn how to debug why exactly your apps are slow for only some users. Learn to spot patterns, anomalies, and trends with distributed tracing. Tame alert noise and focus on what matters with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[First Update on the Vizio lawsuit](https://sfconservancy.org/blog/2021/nov/30/vizio-update-0/)  
Vizio is being shady af and violating open source licenses.

[Hackers Are Spamming Businesses' Receipt Printers With ‘Antiwork' Manifestos](https://www.vice.com/en/article/qjbb9d/hackers-are-spamming-businesses-receipt-printers-with-antiwork-manifestos)  
Hide yo kids, firewall your networked devices.

[Square changes corporate name to Block](https://www.cnbc.com/2021/12/01/square-changes-corporate-name-to-block-.html)  
Okay...

[A vision for a social model of open source](https://leaddev.com/agile-other-ways-working/vision-social-model-open-source)  
"Technical model versus social model of open source" a very interesting read from Julia Ferraioli.

## Tools

[Knative Has Applied to Become a CNCF Incubating Project](https://knative.dev/blog/steering/knative-cncf-donation/)  
This was quite the course correction. I had to flat out ask [Chris Dibona what brought about this change](https://twitter.com/cdibona/status/1465754668450025473). I got an answer. I'm not sure I'm buying it just yet. Time will tell. If Knative wants in, I welcome them with open arms. I wish they would have made that decision without the WTF moment that drove good people away from the project.

[Pulumi: Infrastructure as Code](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)  
Developing on the cloud is complex. What if you could use your existing programming knowledge to build, deploy, and manage cloud infrastructure using your favorite languages and tools? Pulumi is a cloud engineering platform that lets you write infrastructure as code in any programming language and on any cloud platform. Get started for free at pulumi.com *SPONSORED*

[Scaling Kafka at Honeycomb](https://www.honeycomb.io/blog/scaling-kafka-observability-pipelines/)  
"In this post, we’ll review the history of how we got here, why we’re so picky about Kafka software and hardware, and how we qualified and adopted the new AWS Graviton2-based storage instances. Lastly, at the end of this post, we’ll discuss the decrease in price per megabyte of throughput after the cumulative optimizations we’ve made in the past two years. Let’s dive in."

[Karpenter vs Kubernetes Cluster Autoscaler](https://www.youtube.com/watch?v=3QsVRHVdOnM)  
AWS made [Karpenter](https://karpenter.sh/) generally available this week. Something wasn't quite clicking until I watched this video from Justin Garrison. Now it all makes sense and I'll be putting this in one of my work clusters soon enough.

[A Hang In The Linux Kernel Can Happen If Trying To Read A Broken Floppy Then Ejecting It](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.17-Floppy)  
I don't want to know how this was discovered. I want to know how was this discovered.

[Find Answers to AWS Questions | AWS re:Post](https://repost.aws/questions)  
Got a question about an AWS service? There's a place for that.

[App Store Awards honor the best apps and games of 2021](https://www.apple.com/newsroom/2021/12/app-store-awards-honor-the-best-apps-and-games-of-2021/)  
I always appreciate these awards. I always find something new to try.

[MacBook Air M1: the best laptop?](https://michael.stapelberg.ch/posts/2021-11-28-macbook-air-m1/)  
I've always liked the MacBook Air. I feel like the M1 is finally the power boost the form factor needed. Michael provides an honest assessment here.

[waydabber/BetterDummy](https://github.com/waydabber/BetterDummy)  
Software Dummy Display Adapter for Apple Silicon/Intel Macs to Have Custom HiDPI Resolutions. Note: I have this problem... Not sure I want to unpack that monitor again.

## DevOps'ish Tweet of the Week

[![Kerri Miller (with 3 Rs) (@kerrizor) on Twitter) "A junior engineer has learned things. An intermediate engineer has built things. A senior engineer has seen things. Horrible things. A staff engineer ph'nglui mglw'nafh Cthulhu R'lyeh wgah'nagl fhtagn"](/images/246-devopsish-tweet-of-the-week.webp)](https://twitter.com/kerrizor/status/1465694154508300292)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/246/notes/) to see what didn't make it to the newsletter but are still worth your time.
