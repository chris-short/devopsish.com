+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-05-30
description = ["Fretting over free tier, Amazon's creepy network, NOBELIUM, Half-Double Rowhammers on sale, Istio vs. Linkerd, cost of cloud, and more"]
draft = false
slug = "220"
tags = ["cloud", "DevOps", "attack", "open sources", "government", "compose", "privacy", "observability", "cloud native", "lithium", "Docker", "Honeycomb", "free tier", "time", "system", "providers", "code", "Kubernetes", "Podman", "cloud spend", "NOBELIUM", "AWS", "infrastructure", "postgresql", "hack", "investigation", "Amazon", "Russia", "breached", "unpatched", "Fortinet", "benchmarking", "Linkerd", "Istio", "IBM", "Argo", "HAProxy", "metrics", "Rust", "developers", "GitOps", "API"]
title = "DevOps'ish 220: Fretting over free tier, Amazon's creepy network, NOBELIUM, Half-Double Rowhammers on sale, Istio vs. Linkerd, cost of cloud, and more"

+++

I'm in surgery recovery mode. I will be for a while it looks like. Nerves are weird. Do me a favor; if you're reading this, [take the 2021 DORA State of DevOps survey](https://cloud.google.com/blog/products/devops-sre/take-2021-state-devops-survey-shape-future-devops).

## People

[Growing Concerns among Developers about the AWS Free Tier](https://www.infoq.com/news/2021/05/aws-billing-limits/)  
It feels like if you think you're keeping yourself in the free tier you're an API call or bug in the system away from a massive panic attack.

Are you looking to learn more about observability practices? Join Honeycomb for [o11ycon+hnycon](https://o11ycon-hnycon.io/devopsish/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=devopsish&utm_adgroup) June 9-10! This is the observability event of the year, where people come together to explore cutting-edge observability practices, new tech like OpenTelemetry, and more. Register for this free virtual conference to connect with peers and learn from top Honeycomb customers and observability experts–including speakers from HelloFresh, Slack, CircleCI & Netflix!

Observe, debug, and improve with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Amazon devices will soon automatically share your Internet with neighbors](https://arstechnica.com/gadgets/2021/05/amazon-devices-will-soon-automatically-share-your-internet-with-neighbors/)  
This is a security nightmare laying in shadows. Disable this setting now (directions in article)!

[Emily Wilder's Firing at The A.P. Reminds Us of What We Didn't Expect](https://www.nytimes.com/2021/05/29/technology/emily-wilder-firing-ap.html)  
This is a disturbing problem running rampant across society. Like, I don't even want a Facebook account anymore. I love Twitter but I'm legitimately thinking about deleting everything from my 20s-mid-30s. If this is how things are going to be, it's not worth it to keep a history around.

[Long working hours lead to a rise in premature deaths, WHO says](https://www.seattletimes.com/explore/careers/long-working-hours-lead-to-a-rise-in-premature-deaths-who-says/)  
Next time your coworkers are working long hours, remind them that they're killing themselves.

## Process

[New sophisticated email-based attack from NOBELIUM](https://www.microsoft.com/security/blog/2021/05/27/new-sophisticated-email-based-attack-from-nobelium/)  
"NOBELIUM has historically targeted government organizations, non-government organizations (NGOs), think tanks, military, IT service providers, health technology and research, and telecommunications providers. With this latest attack, NOBELIUM attempted to target approximately 3,000 individual accounts across more than 150 organizations, employing an established pattern of using unique infrastructure and tooling for each target, increasing their ability to remain undetected for a longer period of time."

[Securing Your PostgreSQL Database](https://goteleport.com/blog/securing-postgres-postgresql/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish)  
A comprehensive overview of the best practices for securing access to PostgreSQL databases. *SPONSORED*

[As Chips Shrink, Rowhammer Attacks Get Harder to Stop](https://www.wired.com/story/rowhammer-half-double-attack-bit-flips/)  
"A full fix for the 'Half-Double' technique will require rethinking how memory semiconductors are designed."

[Have I been Pwned goes open source](https://www.zdnet.com/article/have-i-been-pwned-goes-open-source/)  
"Want to find out if someone's stolen your user IDs and passwords? Then you can use "Have I Been Pwned," and now the code behind it is being open sourced."

[Belgium government discovers old 2019 hack during Hafnium investigation](https://therecord.media/belgium-government-discovers-old-2019-hack-during-hafnium-investigation/)  
This is how I picture the phone call going. "Hey Boss, how are you?" "Oh I'm good. So you know how we've been cleaning up after that Exchange breach. Well... We found another one." "What's that?" "No... It's not new. It's umm... from 2019." "Okay, I'll pack my things and be gone in an hour."

[A dynamic stability design strategy for lithium metal solid state batteries](https://www.nature.com/articles/s41586-021-03486-3)  
"Here we describe a solid-state battery design with a hierarchy of interface stabilities (to lithium metal responses), to achieve an ultrahigh current density with no lithium dendrite penetration. Our multilayer design has the structure of a less-stable electrolyte sandwiched between more-stable solid electrolytes, which prevents any lithium dendrite growth through well localized decompositions in the less stable electrolyte layer." Better, safer batteries coming soon.

[Russia Appears to Carry Out Hack Through System Used by U.S. Aid Agency](https://www.nytimes.com/2021/05/28/us/politics/russia-hack-usaid.html)  
"Senior Democrats said the latest attack, ahead of President Biden's meeting with his Russian counterpart, demanded a stronger response." I feel pretty confident that US operations are in an on-going state of infect and wait across Russia.

[FBI says an APT breached a US municipal government via an unpatched Fortinet VPN](https://therecord.media/fbi-says-an-apt-breached-a-us-municipal-government-via-an-unpatched-fortinet-vpn/)  
"The Federal Bureau of Investigation said today that foreign hackers had breached the network of a local US municipal government after exploiting vulnerabilities in an unpatched Fortinet networking appliance."

[TeamTNT Targets Kubernetes, Nearly 50,000 IPs Compromised in Worm-like Attack](https://www.trendmicro.com/en_us/research/21/e/teamtnt-targets-kubernetes--nearly-50-000-ips-compromised.html)  
Why are your clusters exposed to the internet? Come on folks...

## Tools

[Benchmarking Linkerd and Istio](https://linkerd.io/2021/05/27/linkerd-vs-istio-benchmarks/)  
Linkerd really kicks the llamas ass.

[Gain Control of Your Code with Feature Management](https://learn.launchdarkly.com/demo/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
Testing in production?  It's scary until it's not. Get total control of your code like Square, Hulu, Atlassian, Toyota, Intuit & IBM have  to ship fast without breaking things.  Book a demo today and learn how your team can reap the rewards of CI/CD without the risk.
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Podman v3 and docker-compose](https://www.youtube.com/watch?v=Eahh-ZxiU4U)  
"For reals this time, let's experiment with docker-compose using a podman backend. Since we didn't actually get to this back in episode 30 let's get back into Docker Compose support in the latest Podman release. We'll see if we can launch our Cool Store using the Compose-like features. We'll also experiment with exporting the compose pods and try to run them in OpenShift."

[The Cost of Cloud, a Trillion Dollar Paradox](https://a16z.com/2021/05/27/cost-of-cloud-paradox-market-cap-cloud-lifecycle-scale-growth-repatriation-optimization/)  
"When you consider the sheer magnitude of cloud spend as a percentage of the total cost of revenue (COR), 50% savings from cloud repatriation is particularly meaningful. Based on benchmarking public software companies (those that disclose their committed cloud infrastructure spend), we found that contractually committed spend averaged 50% of COR."

[Using Kubernetes to rethink your system architecture and ease technical debt](https://stackoverflow.blog/2021/05/19/rethinking-system-architecture-can-kubernetes-help-to-solve-rewrite-anxiety/)  
"This is a story about trying to rethink complex systems: the challenges you face when you try to rebuild them, the burdens you face as they grow, and how inaction itself can cause it's own problems. When you're weighing the risk and reward of replacing architecture, it can take several attempts to find a solution that works for you."

[USB-C levels up and powers up to deliver 240W in upgraded power delivery spec](https://www.theregister.com/2021/05/27/usb_pd_240w_upgrade/)  
Will USB-C replace everything someday? Maybe. It just might.

[Introducing Argo Rollouts v1.0. Progressive Delivery done right!](https://blog.argoproj.io/introducing-argo-rollouts-v1-0-803e87f76ef7)  
"Future releases will support many more ingress controllers and metric providers, as well as leveraging even more advanced traffic shaping techniques such as header-based routing, or shadow trafficking."

[Visualize HAProxy Metrics with InfluxDB](https://www.haproxy.com/blog/visualize-haproxy-metrics-with-influxdb/)  
"In this article, we'll walk through all of the steps necessary to get your HAProxy metrics displayed in InfluxDB."

[A Guide to the Zsh Completion With Examples](https://thevaluable.dev/zsh-completion-guide-examples/)  
"Zsh has two completion systems, the old compctl and the more recent compsys. We only look at compsys in this article."

[Curated list of awesome lists](https://project-awesome.org/)

[TaKO8Ki/awesome-alternatives-in-rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust)  
A curated list of replacements for existing software written in Rust

[pluja/awesome-privacy](https://github.com/pluja/awesome-privacy)  
"Awesome Privacy - A curated list of services and alternatives that respect your privacy because PRIVACY MATTERS."

[nccgroup/PMapper](https://github.com/nccgroup/PMapper)  
"A tool for quickly evaluating IAM permissions in AWS."

[nocodb/nocodb](https://github.com/nocodb/nocodb)  
"🔥 🔥 The Open Source Airtable alternative"

## DevOps'ish Tweet of the Week

[![@holly_cummins on Twitter: "Maybe ... it depends how generous your definition of 'picture of' is :)"](https://shortcdn.com/devopsish/220-devopsish-tweet-of-the-week.png)](https://twitter.com/holly_cummins/status/1397951970502119431)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/220/notes.md) to see what didn't make it to the newsletter but are still worth your time.
