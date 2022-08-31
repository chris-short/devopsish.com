+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-05-09T07:00:00Z
description = ["KubeCon EU 2021, COSI confusion, Kohl's GitOps tool, Colonial Pipelines attack, dev platforms, Docker dead in water, GitOps Con 2021, PodTopologySpread, and more"]
draft = false
slug = "217"
tags = ["Kubernetes", "KubeCon", "cloud", "Cloud Native", "open source", "DevOps", "GitOps", "COSI", "pods", "interface", "availability", "observability", "systems", "control", "VPC", "community", "platform", "Pulumi", "Talos Systems", "pipeline", "container", "Docker", "Kohl's", "object storage", "Argo", "Twitch", "Red Hat", "learning organization", "ransomware", "IBM", "AWS", "Amazon", "CNCF", "cluster", "Honeycomb", "StackRox", "Accurics"]
title = "DevOps'ish 217: KubeCon EU 2021, COSI confusion, Kohl's GitOps tool, Colonial Pipelines attack, dev platforms, Docker dead in water, GitOps Con 2021, PodTopologySpread, and more"

+++

It was indeed KubeCon EU this week. What my family is told is one of my Super Bowl events (KubeCons and Red Hat Summit are in that class). It was indeed an extraordinary virtual event. That’s right; you read that right. KubeCon EU 2021 was a great virtual event. No one besides Deserted Island DevOps and CNCF has unlocked successful models of making a virtual event enjoyable.

As a speaker, I did not test anything until thirty minutes before the talk on Friday morning. After 530+ hours of live streaming, if I couldn’t figure it out in thirty minutes, it was beyond fixing. I found the tooling I needed after logging in, and we were off to the virtual races. Incorporating Slack as a primary communication medium made a ton of sense. Having great content running on Twitch and a dedicated virtual track made for an excellent experience outside of the virtual event platform. I was impressed.

There was one embarrassing announcement from a KubeCon vendor/sponsor, though. Talos Systems announced COSI, the Common Operating System Interface. But… Um… There’s already a COSI in Kubernetes; [Container Object Storage Interface](https://github.com/kubernetes/enhancements/tree/master/keps/sig-storage/1979-object-storage-support) (also mentioned in [DevOps'ish 215](https://devopsish.com/215/)). Oops! I know naming things is hard but, this is a gross error. No one was aware of the Kubernetes projects. I mean it was in this newsletter two weeks ago. A [DuckDuckGo search for Kubernetes COSI](https://duckduckgo.com/?q=Kubernetes+COSI) returns numerous Container Object Storage Interface results and one new entry for Talos Systems Common Operating System Interface. I would like to see this fixed to reduce any confusion in an already crowded [landscape](https://l.cncf.io/). Container Object Storage Interface should keep its name. It’s closer to the core Kubernetes project and was the first to go public if you will. **Talos Systems**, you’ve got to do the right thing here and rename your product.

Note: All KubeCon EU 2021 talks will be available on YouTube on May 14th.

## People

[Learn essential Kubernetes commands with a new cheat sheet](https://opensource.com/article/21/5/kubernetes-cheat-sheet)  
"Start exploring kubectl, containers, pods, and more, then download our free cheat sheet so you always have the key commands at your fingertips."

**Learnk8s** is running 2 and 4 days Kubernetes courses on the 20th of May. If you want to understand the inner workings of Kubernetes & how to apply it in practice then this course is for you. The course is beginner-friendly and hands-on. [Register now!](https://learnk8s.io/online-advanced-may-2021) *SPONSORED*

[GitOps Con 2021](https://www.youtube.com/playlist?list=PLXOML2VBdIo7xEp8Bo9kFB-d6tTlHK5Fk)  
Hosting the inaugural GitOps Con was an absolute blast. Being in charge of the playlist meant all videos were live almost as soon as the event was over.

[The Next Step after DevOps and GitOps Is Cloud Engineering, Pulumi Says](https://thenewstack.io/the-next-step-after-devops-and-gitops-is-cloud-engineering-pulumi-says/)  
Pulumi is making big waves. But, I feel like Pulumi is also addressing a fraction of who they could be. This is an interesting prediction. We'll all be makers of clouds.

[xkcd: Vaccinated](https://xkcd.com/2460/)  
Making friends was already hard enough. I have noticed I've become distant from almost all my friends. It's weird to talk to people, not knowing if or when you'll ever see them again.

[Continuous Learning as a Tool for Adaptation](https://www.infoq.com/articles/series-enhancing-resilience-5/)  
"Developing a learning organization is a competitive advantage, and leaders who study, encourage, and understand what it means to develop this kind of organization are well-positioned to achieve stronger collaboration and team dynamics under pressure."

## Process

[Cyberattack Forces a Shutdown of a Top U.S. Pipeline](https://www.nytimes.com/2021/05/08/us/cyberattack-colonial-pipeline.html)  
"The operator, Colonial Pipeline, said it had halted systems for its 5,500 miles of pipeline after being hit by a ransomware attack." I've driven along this pipelines path numerous times in my life east and west on I-40 in North Carolina. The fact it had to halt operations of nearly half the US east coast's fuel supplies is an insanely high cost to pay for a ransomware attack. I've got a bad feeling the US is going to start using these elite special forces units coming home from overseas in other ways soon. If the US goes kinetic to defend cyberspace, we're talking really uncharted territory.

[Cloud Native Security Day, Capture The Flag](https://www.youtube.com/watch?v=bFyYaECAPpo)  
This was one of the highlights of my KubeCon experience (originally on Twitch with audience and participant engagement). I learned, I suggested, I learned a little more. This was very cool.

[Gain Control of Your Code with Feature Management](https://learn.launchdarkly.com/demo/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
Testing in production?  It's scary until it's not. Get total control of your code like Square, Hulu, Atlassian, Toyota, Intuit & IBM have  to ship fast without breaking things.  Book a demo today and learn how your team can reap the rewards of CI/CD without the risk.
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Is Docker Dead in the Water?](https://www.simplethread.com/is-docker-dead-in-the-water/)  
Some of us [have thought this since 2017](https://chrisshort.net/docker-inc-is-dead/). In general, it seems the author hasn't followed Docker the company as closely as the technology. But, it is a worthwhile read.

[Amazon VPC Announces Pricing Change for VPC Peering](https://aws.amazon.com/about-aws/whats-new/2021/05/amazon-vpc-announces-pricing-change-for-vpc-peering/)  
Like, this was overdue. "Starting May 1st 2021, all data transfer over a VPC Peering connection that stays within an Availability Zone (AZ) is now free. All data transfer over a VPC Peering connection that crosses Availability Zones will continue to be charged at the standard in-region data transfer rates. You can use the Availability Zone-ID to uniquely and consistently identify an Availability Zone across different AWS accounts."

[Why positioning matters for open source software](https://www.emilyomier.com/blog/why-positioning-matters-for-open-source-software)  
"Positioning is important whether you are trying to build a community of people who pay you money or trying to build a community of people who will pay you with their time (ie contribute to your open source project)."

## Tools

[Introducing PodTopologySpread](https://kubernetes.io/blog/2020/05/introducing-podtopologyspread/)  
"Managing Pods distribution across a cluster is hard. The well-known Kubernetes features for Pod affinity and anti-affinity, allow some control of Pod placement in different topologies. However, these features only resolve part of Pods distribution use cases: either place unlimited Pods to a single topology, or disallow two Pods to co-locate in the same topology. In between these two extreme cases, there is a common need to distribute the Pods evenly across the topologies, so as to achieve better cluster utilization and high availability of applications."

Are you looking to learn more about observability practices? Join us for [o11ycon+hnycon](https://o11ycon-hnycon.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword&utm_content=devopsish&utm_adgroup) June 9-10! This is the observability event of the year, where people come together to explore cutting-edge observability practices, new tech like OpenTelemetry, and more. Register for this free virtual conference to connect with peers and learn from top Honeycomb customers and observability experts.

Guess less and know more with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Welcome to StackRox.io and the StackRox community](https://www.stackrox.io/blog/welcome-to-stackrox-io-and-the-stackrox-community/)  
StackRox going open source is going to be amazing. Be on the ground floor and get involved now.

[Using CoreDNS Effectively with Kubernetes](https://www.infracloud.io/blogs/using-coredns-effectively-kubernetes/)  
Please read this if you manage DNS for anything.

[Iter8](https://iter8.tools/)  
AI-driven Kubernetes experimentation platform: Iter8 makes it easy to optimize business metrics and validate SLOs when you release new versions of Kubernetes apps/ML models.

[Cloud Native Computing Foundation Grants Spotify the Top End User Award](https://www.cncf.io/announcements/2021/05/05/cloud-native-computing-foundation-grants-spotify-the-top-end-user-award/)  
Meanwhile, Corey Quinn was [shitting all over it](https://www.lastweekinaws.com/blog/developer-portals-are-an-anti-pattern/).

[Open Policy Agent: The Top 5 Kubernetes Admission Control Policies](https://blog.styra.com/blog/open-policy-agent-the-top-5-kubernetes-admission-control-policies)  
"Note: Each of the sample policies below can be implemented via Open Policy Agent (OPA), the de facto policy engine for cloud native (open source)." That's a mighty high horse you're on.

[Accurics Announces Argo Integration for Open Source Terrascan](https://www.devopsdigest.com/accurics-announces-argo-integration-for-open-source-terrascan)  
Dropping Terrascan right into Argo will make for more secure pipelines. Make it happen folks, Accurics is legit.

[PlayStation invests in Discord and plans integration with PSN in 2022](https://venturebeat.com/2021/05/03/playstation-invests-in-discord-and-plans-integrating-with-psn-in-2022/)  
Shit just got real awkward for teams using Discord.

[My Favorite One Liners](https://muhammadraza.me/2021/Oneliners/)  
This is inspiring me to create my own list.

[Eunomia](https://operatorhub.io/operator/eunomia)  
Kohl's GitOps platform

[pixie-labs/pixie](https://github.com/pixie-labs/pixie)  
Instant Kubernetes-Native Application Observability

[utkuozdemir/pv-migrate](https://github.com/utkuozdemir/pv-migrate)  
Persistent volume migration plugin for Kubernetes


## DevOps'ish Tweet of the Week

[![@birthmarkbart on Twitter: After seeing the panel with @mbbroberg @kaslinfields @_inductor_ and @Dixie3Flatline's panel in @kubecon about non-code contributors in the #k8s community, I wanted to share this as a huge thank you to the #k8s marketing folks who welcomed me from day one! Thx @CloudNativeFdn!](https://shortcdn.com/devopsish/217-devopsish-tweet-of-the-week.png)](https://twitter.com/birthmarkbart/status/1389960932395294725)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/217/notes/) to see what didn't make it to the newsletter but are still worth your time.
