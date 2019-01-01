+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-11-25T07:00:00Z
description = "DevOps for All, Requirements, Discord Acquisition Coming, Kubernetes Myths, Service Meshes, and More"
draft = false
slug = "103"
tags = ["weekly", "devops", "newsletter", "cloud native", "cloud", "open source", "kubernetes", "automation", "red hat", "ansible", "security", "serverless"]
title = "103: DevOps for All, Requirements, Discord Acquisition Coming, Kubernetes Myths, Service Meshes, and More"

+++

This week was Thanksgiving in the US. It was a holiday and I unplugged to a certain extent. I played games on my phone instead of working on various things and reading research. I took a little bit of a mental break the second half of this week (and I hope you did too if you could). This week, while most of the tech world is Las Vegas, I'll be the designated survivor in an undisclosed location (aka Westford, Massachusetts). re:Invent is too big for me and too soft of a target for my frayed whatever you want to call it (nerves, anxiety, etc.). Have a great week!

[**Spin up a Continuous Delivery server in less than 5 minutes**](https://www.gocd.org/test-drive-gocd/)  
Trying out new continuous delivery tools can take some time, so the team at GoCD created a quick start option for new users to spin up a GoCD server in under 5 minutes. [Try now](https://www.gocd.org/test-drive-gocd/). *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*

[**AWS re:Invent 2018 is THIS WEEK**](https://lastweekinaws.com/)  
Amazon isn't cool enough to sponsor this newsletter yet. For that reason, I don't cover AWS much unless I feel like it's amazing news. If you want great AWS coverage and snark subscribe to [Last Week in AWS](https://lastweekinaws.com/). *SPONSORED*

{{< sponsor-blurb >}}

{{< mc >}}

## People

['Tis the Season of Family Tech Support](https://chrisshort.net/tis-the-season-of-family-tech-support/) — I put in some work this weekend.

[Daniel Stenberg is leaving Mozilla after five years](https://daniel.haxx.se/blog/2018/11/18/im-leaving-mozilla/) — And where Daniel lands is still up in the air.

[I hate manager READMEs](https://medium.com/@skamille/i-hate-manager-readmes-20a0dd9a70d0) — Camille Fournier "got feisty on twitter today and wrote up some tweets on manager READMEs, a recent hot trend in management. Let’s break them down..."

[People: Google doesn’t get ‘enterprise’ and should have people who’re more enterprise focused. GOOG: Look, we just hired an enterprise focused person. People: OMG! Why did just hire an enterprise person?](https://www.softwaredefinedtalk.com/156)

[Head of R&D Jia Li Leaves Google Cloud AI](https://syncedreview.com/2018/11/15/head-of-rd-jia-li-leaves-google-cloud-ai/) — "Head of R&D of Google Cloud AI Jia Li has left her position with the company... Chinese media is reporting that Li will start her own AI company with the aim of bringing machine learning solutions to the healthcare industry." That's two big losses for Google lately.

[Want to work at Amazon? Former ‘Bar Raiser’ launches startup to prepare candidates for tech giant’s grueling interview process](https://www.geekwire.com/2018/want-work-amazon-former-bar-raiser-launches-startup-prepare-candidates-tech-giants-grueling-interview-process/) — If you're into that kind of thing (working for Amazon)

[My hiring experience as a submarine sonar operator in the Norwegian Navy](https://www.brautaset.org/articles/2018/submarine-sonar-hiring.html) — There are some "requirements" that are anything but required.
{{< adsense-inarticle >}}

## Process

[DevOps is for everyone](https://opensource.com/article/18/11/how-non-engineer-got-devops) — A non-engineer explains why you don't need to be a developer or an operations person to fall for DevOps.

[SRE: Performance Analysis: Tuning Methodology Using a Simple HTTP Webserver In Go](https://medium.com/dm03514-tech-blog/sre-performance-analysis-tuning-methodology-using-a-simple-http-webserver-in-go-d475460f27ca) — SRE principles for performance profiling and tuning

[How to write scintillating technical blog posts](https://medium.com/@lperkins/how-to-write-scintillating-technical-blog-posts-90f65dc5c089) — Adhere to just a few simple principles and your content may just have a fighting chance

[As We May Kube*](https://itnext.io/as-we-may-kube-293b30c0a365) — Michael Hausenblas talks about developer experience with Kubernetes, "This article reviews where we stand in Kubernetes-land concerning developing apps and where we may be heading."

[A Serverless and Go Journey](https://medium.com/capital-one-tech/a-serverless-and-go-journey-credit-offers-api-74ef1f9fde7f) — Evolution of the Capital One Credit Offers API

[10 IT predictions for the next 5 years: IDC](https://enterprisersproject.com/article/2018/11/10-it-predictions-next-5-years-idc) — Long story short; API driven infrastructure becomes the norm, AI/ML will make magic happen, "skills development and retention will become differentiating strategies", and failing gracefully.

[Who could buy Discord? Acquirers have been giving the gaming startup a long look.](https://www.recode.net/2018/11/21/18103919/discord-acquisition-gaming-microsoft-amazon-facebook-tencent-activision) — Discord has hired Qatalyst Partners, the boutique investment bank known for selling tech companies.

[What DevOps Teams Should Track on Black Friday/Cyber Monday](http://www.eweek.com/enterprise-apps/what-devops-teams-should-track-on-black-friday-cyber-monday) — It's all about know what to look for. This is a great start.

[On the Future of Cloud Computing](https://thenewstack.io/on-the-future-of-cloud-computing/) — Simon Wardley thinks the world will become serverless.

[Operations: The Last Mile Problem for Digital Transformation and DevOps](https://www.rundeck.com/blog/operations-the-last-mile-problem-for-digital-transformation-and-devops) by Damon Edwards
{{< adsense-inarticle >}}

## Tools

[Sorry, Linux. Kubernetes is now the OS that matters](https://www.infoworld.com/article/3322120/kubernetes/sorry-linux-kubernetes-is-now-the-os-that-matters.html) — "Linux is just plumbing. The real OS—the real value—is with Kubernetes" ***record scratch*** The whole lot of it is bubble gum and duct tape masquerading as plumbing.

[The biggest bullsh!t that I ever heard: Sorry Linux, Kubernetes is now the OS that matters](https://www.reddit.com/r/devops/comments/9yuadv/the_biggest_bullsht_that_i_ever_heard_sorry_linux/) — r/devops take on the aforementioned article.

[Kubernetes in production vs. Kubernetes in development: 4 myths](https://enterprisersproject.com/article/2018/11/kubernetes-production-4-myths-debunked) — IT teams tinkering with containers and Kubernetes can discover a steep learning curve when their local changes deploy to production. Here's what to know ahead of time.

[Kubernetes Ingress Controllers and Certificates: The Walkthrough](https://jessicadeen.com/kubernetes-ingress-controllers-and-certificates-the-walkthrough/) — Jessica Deen's video walkthrough of Ingresses and Helm Charts

[Introducing SuperGloo: The Service Mesh Orchestration Platform](https://medium.com/solo-io/https-medium-com-solo-io-supergloo-ff2aae1fb96f) — This is a thing now. I think that says something about service meshes (they might be kind of a big deal).

[The Inner Workings of Istio](https://freecontent.manning.com/mental-model-graphic-istio-in-action/) — From Istio in Action by Christian Posta

[Running Gitea on Kubernetes](https://medium.com/@jmarhee/running-gitea-on-kubernetes-d1ca5bcf0a4e) — How much do you trust your Kubernetes cluster?

[7 command-line tools for writers](https://opensource.com/article/18/11/command-line-tools-writers) — Put away your word processor and start writing from the command line using these open source tools.

[Schedule One-Time Commands with the UNIX at Tool](https://www.linuxjournal.com/content/schedule-one-time-commands-unix-tool) — Oh at how I miss thee.

[mitchellh/golicense](https://github.com/mitchellh/golicense) — Scan and analyze OSS dependencies and licenses from compiled Go binaries

[Using Ark and Restic to provide DR for IBM Kubernetes Service](https://medium.com/@mlrborowski/using-ark-and-restic-to-provide-dr-for-ibm-kubernetes-service-cae53cfe532) — Restore your application configurations AND your persistent storage.

## DevOps'ish Tweet of the Week

{{< tweet 1064899991968219136 >}}