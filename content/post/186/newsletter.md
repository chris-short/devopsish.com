+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2020"]
date = 2020-10-04T07:00:00Z
description = "Help save face, help for juniors, Hacktoberfest objection, cgroups, breaking busy culture, and more"
draft = false
slug = "186"
tags = ["Kubernetes", "culture", "DevOps", "dog", "open source", "build", "junior", "senior", "cloud", "observability", "cloud native", "security", "Google", "Red Hat", "cgroups", "computer", "sysadmins", "developer", "measure", "attacked", "Hacktoberfest", "serverless"]
title = "DevOps'ish 186"

+++

This is the hell that is America today: It took us a week to get a legitimate COVID-19 test for my daughter. Strep and flu tests were done at the same time; she tested positive for the flu. Hopefully, things are on the upswing there.

Just when that turned around for good, I went for a walk to take a break from the stressors of day to day life. Then out of nowhere, Sunny and I were attacked by an irresponsible neighbor's dog. Immediately taking down the attacking dog resulted in me skinning and bruising my left knee. Then the neighbors didn't want to take responsibility because we walked up the sidewalk. Can't I walk up the sidewalk now? I don't have time for stupid. I've never seen this dog before. I've lived in this neighborhood for three years. A neighbor that witnessed the whole thing confided in me that the same dog attacked his dog a while back and put it in the hospital.

Sunny luckily got off unscathed (defending her as a human shield was second nature). I got the cops involved, though, which is something I hate doing. But, the lack of responsibility taken and the fact this isn't a first forced my hand.

My mental health needs a break. I need an average week for once.

<iframe src="https://open.spotify.com/embed/album/4ljsev5vUnwB2BUFAMvwwy" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

## People

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[To Succeed in a Negotiation, Help Your Counterpart Save Face](https://hbr.org/2020/10/to-succeed-in-a-negotiation-help-your-counterpart-save-face)  
Sometimes you just need to give people what they need to look good.

[Computer science is not software engineering](https://swizec.com/blog/computer-science-is-not-software-engineering/)  
"We were computer scientists damn it! Going into industry is a waste of talent. We're here to advance the field!!"

[US govt wins right to snaffle Edward Snowden's $5m+ book royalties, speech fees – and all future related earnings](https://www.theregister.com/2020/10/02/us_govt_snowden_court_royalties_win/)  
And people wonder why the only thing I fear is the US government.

[U.S. expected to sue Google next week as DOJ seeks support from states](https://www.reuters.com/article/tech-antitrust-google-idUSKBN26L08E)  
"The U.S. Justice Department is expected to sue Alphabet’s Google as soon as next week, and is currently urging state attorneys general to sign onto the lawsuit, according to three sources familiar with the process." See previous statement.

[Need to know technologies for junior sysadmins](https://www.redhat.com/sysadmin/technologies-junior-sysadmins)  
"Sit down and have a conversation with some experienced sysadmins about technologies valuable to aspiring sysadmins."

[Junior To Senior Developer](https://www.ladybug.dev/episodes/junior-to-senior-developer)  
"What’s the difference between a junior and senior developer? While there’s no distinct measure from one title to the next, you can measure your progress in three areas: knowledge, coding, and communication. This week on the podcast we’re doing a deep dive into the progression from junior to senior dev."

[Netflix CEO Reed Hastings on high salaries: 'The best are easily 10x better than average'](https://www.cnbc.com/2020/09/08/netflix-ceo-reed-hastings-on-high-salaries-the-best-are-easily-10x-better-than-average.html)  
This article [brought out some feelings](https://twitter.com/bdimcheff/status/1310951594951876608) in folks.

## Process

Want to see your ad in DevOps'ish? Check out the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. *SPONSORED*

[HOTorNOT: The forgotten website that shaped the internet](https://mashable.com/feature/hotornot-history-20-year-anniversary/)  
"The forgotten joke website influenced YouTube, Twitter, Tinder, and so much more"

[Red Hat Code Sleuths Uncover Mysterious Bug in Registry Service](https://thenewstack.io/red-hat-code-sleuths-uncover-mysterious-bug-in-storage-service/)  
"After updating to OpenShift 4.3.19, Quay.io experienced intermittent service interruptions. The team quickly rolled back to 4.3.18, restoring service and steadying the waters, but everyone involved was now taking part in a murder mystery."

[DigitalOcean's Hacktoberfest is Hurting Open Source](https://blog.domenic.me/hacktoberfest/)  
"In reality, Hacktoberfest is a corporate-sponsored distributed denial of service attack against the open source maintainer community."

[How to Defeat Busy Culture](https://hbr.org/2020/09/how-to-defeat-busy-culture)  
"At home and at work, “busy” culture worsens the problems it promises to solve. It’s natural to assume that the busier we are, the bigger the impact we’ll be able to make — but in reality, studies have shown that busy culture destroys productivity and pulls us away from both our families and deeper relationships with our coworkers."

[Memristor Breakthrough: First Single Device To Act Like a Neuron](https://spectrum.ieee.org/nanoclast/semiconductors/devices/memristor-first-single-device-to-act-like-a-neuron)  
"Analog computing with neuron-like devices could efficiently solve problems traditional computers struggle with"

[VMware to Acquire SaltStack for Advanced Multicloud Automation](https://thenewstack.io/vmware-to-acquire-saltstack-for-advanced-multicloud-automation/)  
What's interesting is that Puppet is the only configuration management tool that hasn't been acquired yet. That should tell you something.

## Tools

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[Serverless Framework V2](https://www.serverless.com/blog/serverless-framework-v2)  
"We recently released our first (minimal) set of breaking changes in the Serverless Framework, in over 4 years, prompted by deprecating support for old Node.js versions. These breaking changes are included in the new v2 release."

[Wiki - RustStarterKit2020](https://wiki.alopex.li/RustStarterKit2020)  
"People were arguing about Rust’s std lib recently, so I went through the Cargo.toml of all the Rust projects I’ve written since 2015 and picked out the choice tools that get used over and over again. Up to date as of October 2020."

[kitty](https://sw.kovidgoyal.net/kitty/)  
The fast, featureful, GPU based terminal emulator

[A Linux sysadmin's introduction to cgroups](https://www.redhat.com/sysadmin/cgroups-part-one)
"Defining cgroups and how they help with resource management and performance tuning in this first article kicking off a four-part series covering cgroups and resource management."

[The Cloudcast: Learning Streaming from the Experts](https://www.thecloudcast.net/2020/09/learning-streaming-from-experts.html)  
"Chris Short ([@ChrisShort](https://twitter.com/ChrisShort), Technical Marketing Red Hat, CNCF Ambassador) talks about how to deliver compelling technical learning via streaming services, how to engage audiences and communities, and how to improve virtual events."

[RabbitMQ Monitoring on Kubernetes](https://piotrminkowski.com/2020/09/29/rabbitmq-monitoring-on-kubernetes/)  
"In this article, I will show you how to use Prometheus and Grafana to monitor the key metrics of RabbitMQ. Of course, we will build the applications that send and receive messages. We will use Kubernetes as a target platform for our system. In the last step, we are going to enable the tracing plugin. It helps us in collecting the list of incoming messages."

[Contributing to the Development Guide](https://www.kubernetes.dev/blog/2020/09/28/contributing-to-the-development-guide/)  
"A new contributor describes the experience of writing and submitting changes to the Kubernetes Development Guide."

[muesli/duf](https://github.com/muesli/duf)  
Disk Usage/Free Utility

[jetstack/version-checker](https://github.com/jetstack/version-checker)  
"Kubernetes utility for exposing image versions in use, compared to latest available upstream, as metrics."

## DevOps'ish Tweet of the Week

[![Can we have a break between clusterfucks](images/186-devopsish-tweet-of-the-week.png)](https://twitter.com/EffinBirds/status/1312527916060737536)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/186/notes/) to see what didn't make it to the newsletter.

{{< amazon >}}
