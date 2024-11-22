+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2018"]
date = 2018-09-09
description ="Kubernetes, Musk, Dorsey, Go, Blame, Serverless, and More"
draft = false
slug = "092"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "automation", "ansible", "infrastructure", "Elon Musk", "Jack Dorsey", "serverless"]
title = "092: Kubernetes, Musk, Dorsey, Go, Blame, Serverless, and More"

+++

Elon Musk is a weird dude. Amidst [the SEC probing into his tweet](https://www.nytimes.com/2018/08/15/business/tesla-musk-sec-subpoena-goldman.html) about taking Tesla private, ol' Elon decides to [smoke a blunt on a podcast with Joe Rogan](https://money.cnn.com/2018/09/07/technology/elon-musk-joe-rogan/index.html) (the memes are amazing by the way). Not the smartest move. The only thing dumber that happened this week was [Alex Jones at the US Capitol](https://www.wired.com/story/jack-dorsey-alex-jones-photo/) accosting Jack Dorsey. Did you know [Dorsey fasts every day](https://www.businessinsider.com/twitter-ceo-jack-dorsey-heart-rate-spiked-hearings-congress-2018-9)? Alex Jones is so dumb, he pisses off hangry people. What a maroon. The one person that said [keep Alex Jones](https://www.fastcompany.com/90215581/twitters-jack-dorsey-defends-decision-to-keep-alex-jones) on the platform doesn't eat during the day and Jones pisses him off. [The moron got banned that day](https://www.washingtonpost.com/technology/2018/09/06/twitter-has-permanently-banned-alex-jones-infowars/?noredirect=on&utm_term=.ebdc392abea3). What a weird week.

In other news, two incredibly close and amazing friends of ours (both were in Julie and I's wedding) will be participating in the Leukemia and Lymphoma Society's Light the Night 2018. They have done this year after year regardless of what was going on in their worlds. To quote our friend Kim, "This year will be extra special because we have a new nextdoor neighbor, Maya (3rd grade), who is a leukemia survivor and she will be joining our team and walking with us! 2 survivors on 1 team! Both Sara and Maya's family speak at length about how amazing LLS was to them during their treatments and how LLS continues to be a beacon of hope for so many."

They turn it into a healthy competition pitting wife (Kim) against husband (Chris). As I'm writing this, Chris is getting shellacked in the donation department. If you are able, please contribute. I will be matching confirmed contributions made by DevOps'ish readers (up to $200). Please forward your receipts to me by 2018-09-24.

To Donate to Kim: [https://pages.lightthenight.org/nc/Triangle18/KHaught](https://pages.lightthenight.org/nc/Triangle18/KHaught)  
To Donate to Chris: [https://pages.lightthenight.org/nc/Triangle18/CHaught](https://pages.lightthenight.org/nc/Triangle18/CHaught)

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

[**Correlate request traces, metrics, and logs**](https://www.datadoghq.com/ts/tshirt-landingpage/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterTshirt)  
Seamlessly navigate between logs, metrics, and request traces for a clear view of all your systems. Visualize and alert on metrics in real-time with anomaly and outlier detection. [Try Datadog's full-stack monitoring for free](https://www.datadoghq.com/ts/tshirt-landingpage/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterTshirt) *SPONSORED*

[**Office Hours: Developing on Kubernetes**](http://bit.ly/2Nso0wq)  
Learn how to develop and push your apps to Kubernetes in our Office Hours every Thursday 10am PT — This week's topic: Progressive Delivery (A/B testing, Blue/Green, Canary) - Part 1. [Register here](http://bit.ly/2Nso0wq) *SPONSORED*


## People

[Air Force is looking into Elon Musk's pot smoking: Source](https://www.cnbc.com/2018/09/07/air-force-is-looking-into-elon-musks-pot-smoking-source.html) and [Air Force says it's not investigating Elon Musk for smoking pot](http://thehill.com/policy/defense/405688-air-force-says-its-not-investigating-elon-musk-for-smoking-pot): At this point, I don't think the Air Force can do much but, who knows.

[The Military Secret to Falling Asleep in Two Minutes](https://www.independent.co.uk/life-style/fall-asleep-two-minutes-how-to-military-secret-trick-a8520991.html): Apparently there's another way aside from abject exhaustion.

[Stop treating tech jerks like gods](https://nypost.com/2018/09/01/stop-treating-tech-jerks-like-gods/): Seriously, we need to stop doing this. Especially [assclowns that think people shouldn't be offended by the term slave](http://antirez.com/news/122). Come on!

[How to teach yourself hard things](https://jvns.ca/blog/2018/09/01/learning-skills-you-can-practice/) by Julia Evans

[GopherCon 2018 - Writing Accessible Go](https://about.sourcegraph.com/go/gophecon-2018-writing-accessible-go/): Julia spoke to the importance of writing code that was accessible to all developers. She shared the story of her disability and how it affects her ability to read and write code. She provided examples of how her vision is affected and the difficulties of the existing tooling she uses. Finally she provided suggestions to help make code more readable for everyone.

[The #1 Office Perk? Natural Light](https://hbr.org/2018/09/the-1-office-perk-natural-light): Definitely, 100%, can confirm. I am so thankful for an office with light and windows.

[Tech's ultimate success: Software developers are now more valuable to companies than money](https://www.cnbc.com/2018/09/06/companies-worry-more-about-access-to-software-developers-than-capital.html): 💰💵💰💵💰💵💰

[Jeff Bezos' First Major Political Donation Is $10 Million to Elect Veterans](https://www.nytimes.com/2018/09/05/technology/jeff-bezos-amazon-political-donation-veterans.html)

[5 DevOps Trends CISOs Must Watch](https://securityboulevard.com/2018/09/5-devops-trends-cisos-must-watch/): "Make no mistake, DevOps trends are catching fire in the enterprise these days and for good reason. A new report out by DevOps Research & Assessment (DORA) shows that the highest performing DevOps organizations are crushing their software delivery metrics."

[4 dying IT jobs](https://enterprisersproject.com/article/2018/9/4-dying-it-jobs): R.I.P. project managers and sysadmins? IT recruiters say these roles are vanishing due to factors including AI and DevOps

## Process

[How We Massively Reduced Our AWS Lambda Bill With Go](https://runbook.cloud/blog/posts/how-we-massively-reduced-our-aws-lambda-bill-with-go/): "Serverless functions should almost always be a single thread, single task"

[Top 5 lessons learned working at startups](https://medium.com/@copyconstruct/top-5-lessons-learned-working-at-startups-828ba1d13aa4): "Always, always, ALWAYS choose to work with good people"

[Microservices in a Post-Kubernetes Era](https://www.infoq.com/articles/microservices-post-kubernetes): "Modern developers must be fluent in a programming language to implement the business functionality, and equally fluent in cloud native technologies to address the non-functional infrastructure level requirements."

[HubSpot outage KOs Red Hat Ansible site and other hapless marketers Right in the middle of Inbound 2018 conference, no less](https://www.theregister.co.uk/2018/09/06/hubspot_outage_inbound_2018_conference/): Yes, ansible.com uses HubSpot. Yes, HubSpot went down. Yes, it was (and still kinda is) a pain in the ass.

[Docs Like Code](https://www.docslikecode.com/): Let's treat docs like code

[What is Kubernetes? Optimise your hosting costs and efficiency](https://learnk8s.io/blog/what-is-kubernetes): A bold statement.

[NIST Releases Draft on BGP Security](https://www.darkreading.com/perimeter/nist-releases-draft-on-bgp-security/d/d-id/1332740): Oh thank, NIST. Twenty years later.

[DevOps: The consequences of blame](https://opensource.com/article/18/9/consequences-blame-your-devops-team): To build a successful DevOps environment, you must eliminate blame. Here's why—and how to do it.

[Public IP Addresses of Tor Sites Exposed via SSL Certificates](https://www.bleepingcomputer.com/news/security/public-ip-addresses-of-tor-sites-exposed-via-ssl-certificates/): Whoops

[Updated: Microsoft Azure's southern U.S. data center goes down for hours, impacting Office365 and Active Directory customers](https://www.geekwire.com/2018/microsoft-azures-southern-u-s-data-center-goes-hours-impacting-office365-active-directory-customers/)

[The Hidden Benefit of Giving Back to Open Source Software](https://hbswk.hbs.edu/item/the-hidden-benefit-of-giving-back-to-open-source-software): Firms that allow their software programmers to "give back" to the open source community on company time gain benefits—even though competitors might benefit too, says Frank Nagle.

## Tools

[mhausenblas/stateful-kubernetes](https://github.com/mhausenblas/stateful-kubernetes): This is a list of resources for all thingz stateful apps and tooling in and for Kubernetes.

[AWS releases EKS Platform Version 2; adds support for Horizontal Pod Auto Scaling and Kubernetes Metrics Server](http://wwpi.com/2018/09/02/aws-releases-eks-platform-version-2-adds-support-for-horizontal-pod-auto-scaling-and-kubernetes-metrics-server/)

[walkthrough: buildah on knative](https://gist.github.com/vbatts/ab78083700872ca854e46cccc9f18fd5): When in doubt, be yourself. Unless you can be Vincent Batts, then always be Vincent Batts.

[Monitoring Vault on Kubernetes using Cloud Native technologies](https://banzaicloud.com/blog/monitoring-vault-grafana/)

[Fabulous Text Only Websites, 2018 Edition](http://rickcarlino.com/2018/07/11/fabulous-text-only-websites-2018-edition-html.html): No images, no styling. Just text.

[Jenkins: Shifting Gears](https://jenkins.io/blog/2018/08/31/shifting-gears/index.html): Jenkins usually makes me mad. It's always slow. Apparently, the company has become self aware.

[40 million tables in MySQL 8.0 with ZFS](https://www.percona.com/blog/2018/09/03/40-million-tables-in-mysql-8-0-with-zfs/): Alexander Rubin is an incredibly smart person.

[Turn your vim editor into a productivity powerhouse](https://opensource.com/article/18/9/vi-editor-productivity-powerhouse): These 20+ useful commands will enhance your experience using the vim editor.

[Learning about Go internals at GopherCon](https://lwn.net/Articles/764131/)

[Taints and tolerations, pod and node affinities demystified](https://banzaicloud.com/blog/k8s-taints-tolerations-affinities/): "Kubernetes provides building blocks to deal with various special scenarios with regards to deploying and running application components/services."

[Porting Our Software to ARM64](https://blog.cloudflare.com/porting-our-software-to-arm64/): ARM is the future.

[Distributed Tracing Infrastructure with Jaeger on Kubernetes](https://medium.com/@masroor.hasan/tracing-infrastructure-with-jaeger-on-kubernetes-6800132a677): One cannot overstate the importance of monitoring infrastructure as an integral component of distributed systems (or, any system for that matter).

[Recommended etcd minimum versions: 3.1.11+, 3.2.10+, 3.3.0+](https://discuss.kubernetes.io/t/recommended-etcd-minimum-versions-3-1-11-3-2-10-3-3-0/2637): If you run etcd in production, please read!

[Introducing cstar: The Spotify Cassandra orchestration tool, now open source](https://labs.spotify.com/2018/09/04/introducing-cstar-the-spotify-cassandra-orchestration-tool-now-open-source/): Spotify's Cassandra orchestration tool

[Kubernetes with Cilium and Containerd using Kubeadm](https://blog.scottlowe.org/2018/09/06/kubernetes-cilium-containerd-using-kubeadm/): "Now, if that isn't a title jam-packed with buzzwords, I don't know what is!" (author's words, not mine).

[Introducing stateless microservices for OpenFaaS](https://www.openfaas.com/blog/stateless-microservices/): Alex walks us through the latest addition to OpenFaaS - full support for stateless microservices giving an example of a guestbook written in Ruby with Sinatra

## DevOps'ish Tweet of the Week

{{< tweet 1037832137905524737 >}}
