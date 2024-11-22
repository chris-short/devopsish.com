+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-03-27
description = ["Docker whales, Okta and Lapsus$ galore, Apple Outage, Kubernetes storage, using mtr, Kubernetes events in Slack, and more"]
draft = false
slug = "262"
tags = ["Kubernetes", "Argo", "Okta", "Apple", "SLOs", "Lapsus$", "GitOps", "mtr", "reliability", "incident", "Microsoft", "Russia", "Pulumi", "DevOps", "engineering", "Docker"]
title = "DevOps'ish 262: Docker whales, Okta and Lapsus$ galore, Apple Outage, Kubernetes storage, using mtr, Kubernetes events in Slack, and more"
+++

[![ChrisShort (@ChrisShort on Twitter) "Going through some of Max’s stuff today... (picture of Docker whale stuffed toys) Should I tell them???"](https://shortcdn.com/devopsish/262-Intro.webp)](https://twitter.com/ChrisShort/status/1507816647217790982)

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## Events

Calling all front-line DevOps and SRE practitioners: Join [**IR Conf**](https://www.irconf.io/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on April 1 (no joke), a free, half-day virtual conference for industry experts and new voices in incident response. Incident responders will come together to swap horror stories about the biggest outages, discuss best practices, and gain a better understanding of how the best are dealing with incidents. Register to:

* Discover trends and tooling in resiliency and incidence response
* Gain guidance on how to structure your teams, tooling, and processes
* Learn better practices from incident response experts
* Connect with a community of incident responders who care about this, learn from each other

[**SLOConf - Service Level Objective Conference**](https://www.sloconf.com/)  
MAY 9-12, 2022  

Site Reliability Engineering is one of the hottest areas as companies look to build reliable systems and their online presence. As companies rush to adopt Site Reliability Engineering principles, Service Level Objectives (SLOs) are the most important place to begin. SLOs are the combination of cultural philosophies, practices, and tools.

The SRE community needs a place to gather and focus on SLOs in depth. This virtual conference will cover topics at all levels, from introduction to SLOs to the practical application of SLOs. This conference is a community event made and led by Site Reliability Engineers and influencers who care about reliability and becoming more customer centric by adopting, measuring and optimizing SLOs.

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on 2022-05-17 is designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)  
SEPTEMBER 19 – 21, 2022  
ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Toronto's Tech Industry Is Quietly Booming](https://www.nytimes.com/2022/03/21/technology/toronto-tech-boom.html)  
"For all the excitement around places like Austin and Miami, the biggest tech expansion has been in Canada’s largest city."

[Ex-Apple Worker Accused Of Defrauding Tech Giant Out Of Millions](https://sanfrancisco.cbslocal.com/2022/03/18/ex-apple-worker-accused-defrauding-tech-giant/)  
As this case unravels we'll learn more but, it seems like this was something Apple detected then when they were sure handed it over to prosecutors. Now, the prosecutors are certain enough that they'll win that they've brought the charges in the first place.

[Microsoft is tied to hundreds of millions of dollars in foreign bribes, whistleblower alleges](https://www.theverge.com/2022/3/25/22995144/microsoft-foreign-corrupt-practices-bribery-whistleblower-contracting)  
If true, this activity is VERY illegal in the United States. It's a high bar to clear for prosecutors (of course) but, it's important to do business free of corruption or misgivings. I get it, some cultures expect certain things. But, the US legal system believes that deals outside of businesses doing business shouldn't be part of business deals.

[Meet the Secretive US Company Building an ‘Unbreakable' Internet Inside Russia](https://www.vice.com/en/article/z3n5e9/russian-internet-lantern)  
A tool to bypass Russian government internet censorship might be foiled by Russia completely disconnecting itself from the internet and maintaining its own "sovereign internet". Well actually, Russia, that's really not an internet; it's an intranet. But seriously, the White House and other governments are telling their citizens to get ready for cyber attacks from Russia.

[Open Letter to Okta](https://www.linkedin.com/pulse/open-letter-okta-amit-yoran/)  
"Like many of you, the first question I asked myself after learning of the Okta breach was, 'Are we exposed?' That's an incredibly simple, but crucial question — one that Okta customers should have had the chance to ask themselves two months ago when the company first discovered the compromise." Okta will be a recurring theme this week.

## Process

[What the NSA and CISA Left Out of Their Kubernetes Hardening Guide](https://www.tremolosecurity.com/post/what-the-nsa-and-cisa-left-out-of-their-kubernetes-hardening-guide)  
[The NSA's Kubernetes Hardening Guide] doesn't provide much depth on authentication and authorization in Kubernetes or guidance on how to implement it. This post will fill in that gap.

[Okta revises original statement, says 366 customers affected by Lapsus$ breach](https://therecord.media/okta-revises-original-statement-says-hundreds-of-customers-affected-by-lapsus-breach/)  
I don't know how Okta regains people's trust if they're going to hold out for months from affected customers that they've been compromised somehow.

[It's official, Lapsus$ gang compromised a Microsoft employee's account](https://securityaffairs.co/wordpress/129391/hacking/lapsus-gang-compromised-microsoft-employees-account.html)  
Same group that got Okta, got Microsoft.

[Lapsus$ Cyberattacks Traced to Teenager in England](https://www.bloomberg.com/news/articles/2022-03-23/teen-suspected-by-cyber-researchers-of-being-lapsus-mastermind)  
And [arrests have been made.](https://www.bloomberg.com/news/articles/2022-03-24/u-k-police-arrest-seven-young-people-in-connection-with-hacking)

[Massive outage brought down most Apple services, including iCloud and iMessage](https://arstechnica.com/gadgets/2022/03/massive-outage-brought-down-most-apple-services-like-icloud-and-imessage/)  
Even as a pretty heavy Apple user, I did not seem to be adversely impacted but, I know a ton of people reported issues.

## Tools

[Streaming Kubernetes Events in Slack](https://aws.amazon.com/blogs/containers/streaming-kubernetes-events-in-slack/)  
"By default, Kubernetes events expire after 60 minutes. To retain events for a longer period of time, you’ll need a tool like k8s-event-logger that forwards events to another service for retention. BotKube works in a similar fashion. BotKube watches Kubernetes events and forwards them to Slack, Microsoft Teams, and MatterMost."

[How to properly interpret a traceroute or mtr](https://phil.lavin.me.uk/2022/03/how-to-properly-interpret-a-traceroute-or-mtr/)  
`mtr` is such a wonderful tool. It can really help you during some gnarly things.

[Apple's M1 Ultra Benchmarked: 2.6X Slower Than AMD's Threadripper Pro 5995WX](https://www.tomshardware.com/news/apple-m1-ultra-benchmarked-in-passmark)  
Yeah... I didn't think Apple could pull off the fastest chip in the world type sayings.

[Kubernetes PVC Guide: Tutorials & Troubleshooting Tips](https://komodor.com/learn/kubernetes-pvc-guide-basic-tutorial-and-troubleshooting-tips/)  
Full lifecycle of PVCs from creation to troubleshooting.

[How we manage GitHub at Pulumi with Pulumi](https://www.pulumi.com/blog/managing-github-with-pulumi/)  
GitHub management with Pulumi sounds like it'd be fun enough to try.

## DevOps'ish Tweet of the Week

[![やすなり工業 (@ysnr_ysd on Twitter) "I can't..."](https://shortcdn.com/devopsish/262-devopsish-tweet-of-the-week.webp)](https://twitter.com/ysnr_ysd/status/1505006506957176837)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/262/notes.md) to see what didn't make it to the newsletter but are still worth your time.
