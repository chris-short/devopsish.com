+++

author = "Chris Short"
categories = ["Newsletter"]
date = 2018-05-27T07:00:00Z
description = ""
draft = false
slug = "077"
tags = ["devops", "cloud native", "open source", "kubernetes", "go", "golang", "ChefConf", "security", "gdpr", "vgo", "community", "dep", "containers", "veteran"]
title = "077: ChefConf 2018, GDPR, Go CoC 🙌, Go vgo 😞, Kubernetes, Laptop Giveaway, Security, and More"
image = "/077/chicago-river-chefconf-2018.jpg"
imagealt = "Chicago River from Michigan Ave Bridge after ChefConf"
imagecap = "Chicago River from Michigan Ave Bridge after ChefConf"

+++

I have a lot to talk about this week. I'm putting sections in the introduction for ease of reading (feel free to skip parts you're not mildly interested in). Also, thank you to this week's sponsors; [**Replicated**](https://www.replicated.com/) and [**GoCD**](https://www.gocd.org/2018/05/08/continuous-delivery-microservices-test-strategy/)!

### ChefConf 2018

The highlight of my week was being able to meet 1,400 new friends at [ChefConf](http://chefconf.chef.io/) 2018 in Chicago. If you are ever wondering how to run an amazing event, look no further than the good folks at Chef. From a speaker's perspective, I have never felt more prepared for a talk. The event itself was meticulously planned and executed. I presented my talk, *DevOps is Not War* to a standing room only audience. Thanks to the fantastic guidance from the conference's speaking coach, [Anna Boynton](http://messageglue.com/), I was able to take a forty minute talk and land it perfectly inside the twenty-minute time slot I had. The event morphed my bias of Chef from a niche tool to a formidable accompaniment of software to ease automation tasks. The messages from the keynotes were like those I've delivered to many audiences before, "You're not an X company, you're a technology company." I highly recommend adding ChefConf 2019 to your schedules as soon as it is announced.

### GDPR Fatigue

I won't ~~bore~~ annoy you with more GDPR news. But, I do have one ask from readers: What do you want to know about the data gathered by this newsletter and accompanying web site? I think GDPR is important but, I have not changed much to implement it (and I'm not really sure if I need to either). With that being said, I present to you the [👎 GDPR Hall of Shame](https://gdprhallofshame.com/).

### Go Code of Conduct and vgo

There were two announcements this week from the [Go](https://golang.org/) community that merit attention: one is good, the other is disconcerting. First, Go has adopted a new [Code of Conduct](https://golang.org/conduct) (based on Google's new [Code of Conduct template](https://opensource.google.com/docs/releasing/template/CODE_OF_CONDUCT/)) Go's new Code of Conduct now applies to community members working in non-Go community spaces. This change is a good thing. You shouldn't be able to prey on people in a community outside of that community's space and expect to have your standing in the community protected. This allows for open secrets to be acted upon (and I feel transparency is good).

Sadly, this good news was offset by something that I'm deeply concerned about in the Go community. You may recall at GopherCon 2017, [Sam Boyer gave a keynote](https://youtu.be/5LtMb090AZI) stating that [**dep**](https://github.com/golang/dep) was the "official experiment" for Go package management. According to [Matt Farina](https://codeengineered.com/blog/2018/golang-godep-to-vgo/) at the very same GopherCon, "Russ Cox, the current lead of the Go team, came to the table. He made a comment that he could do better if he went off on his own and built something. That something was later announced as vgo." This indicates that dep literally had no chance at being the official anything for Go. Russ Cox announced on 2018-04-25 that the [vgo proposal has been accepted](https://github.com/golang/go/issues/24301#issuecomment-384349642). Sam Boyer is a friend. I know he has spent countless hours working on dep as well as analyzing vgo. Sam has several articles in progress analyzing vgo; [An Analysis of Vgo](https://sdboyer.io/vgo/intro/) and [Failure Modes](https://sdboyer.io/vgo/failure-modes/) have already been published.

My concern as a somewhat outsider looking in, as well as others I've talked to in the Go community, is not in the solution itself but how the communication has been handled. Why announce dep as even a remote possibility as the one way forward at GopherCon 2017? Why was Russ the proposer, writer, and approver of something that clearly needed more debate? I understand Go is a Google project but, this seems rather dictatorial. It's not a good look for Go's core maintainers (to say the least). My worry is that this could hurt a young and growing community. I would hate to see that. I ❤️ Go!

### Memorial Day and Veterans Day: Know the Difference

It is Memorial Day weekend here in the US. One thing we veterans get mildly irritated about is when citizens don't recognize the difference between Memorial Day and Veterans Day. Remember this: **we remember the fallen on Memorial Day. We thank veterans on Veterans Day**.

[**Replicated: The modern way to ship and manage enterprise software**](https://www.replicated.com/)  
Replicated gives SaaS and software vendors a cloud-native platform for easily and securely deploying their applications inside customers’ data centers or VPC environments. Replicated provides tooling for automatic updates, license management, support, audit logs, LDAP integration and more. [Sign up for a free trial](https://vendor.replicated.com/) and get started now. *SPONSORED*

[**Test Strategy for Microservices**](https://www.gocd.org/2018/05/08/continuous-delivery-microservices-test-strategy/)  
Testing microservices systems is significantly more nuanced and complex than testing a traditional monolithic application. Is traditional testing pyramids still relevant? How to verify overall system behavior? Check out our new post: Test Strategy for Microservices. *SPONSORED*

## Events

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

[**DevNation Federal**](https://devnationfederal.org/)  
Date: 2018-06-05  
Join us to learn about the revolutions happening in communities around containers, data, and application modernization. This is an opportunity for you to hear how visionary teams in the federal government are innovating with open source, and hear from leaders in the private sector doing the same.

[**Chaos Conf**](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

> If you’d like me to speak at your conference, Meetup, office, party, etc. please send me a DM on Twitter ([@ChrisShort](https://twitter.com/ChrisShort)) or [e-mail](mailto:chris@chrisshort.net). Thanks!

<p><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-8972983586873269"
     data-ad-slot="9019534115"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></p>

## People

[opensource.com is giving away a System76 laptop](https://opensource.com/article/18/5/system76-oryx-pro-laptop-giveaway): Enter for a chance to win a brand new laptop from System76. Not just any laptop either; it's a first generation Oryx Pro!

[Would you wear this muzzle around the office for private calling?](https://www.cnet.com/news/would-you-wear-this-muzzle-around-the-office-for-private-calling/): You've got to be kidding me! When are we going to build walls again?

[IBM's Watson Health wing left looking poorly after 'massive' layoffs](https://www.theregister.co.uk/2018/05/25/ibms_watson_layoffs/): Up to 70% of staff shown the door this week, insiders claim

[15 books for kids who (you want to) love Linux and open source](https://opensource.com/article/18/5/books-kids-linux-open-source): Plus, three books for babies.

['Elitist den of hate': Silicon Valley pastor decries hypocrisy of area's rich liberals](https://www.theguardian.com/technology/2018/may/22/silicon-valley-pastor-gregory-stevens-wealth-liberals): Gregory Stevens resigns after tweets about Palo Alto, slamming tech industry greed and empty social justice promises

<p><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-8972983586873269"
     data-ad-slot="9019534115"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></p>

## Process

[Observability+](https://medium.com/observability): A fantastic site about all things observability from the brilliant JBD.

[Why do Kubernetes clusters in AWS cost more than they should?](https://medium.com/@dyachuk/why-do-kubernetes-clusters-in-aws-cost-more-than-they-should-fa510c1964c6): Like all things AWS you have to actively manage your cloud spend. Dmytro Dyachuk shows us how.

[Writing Technical Articles](https://chrisshort.net/writing-technical-articles/): People struggle with writing. Here's my attempt at getting you started. "Pick three points, add an introduction and conclusion and you have the beginnings of a great article."

[Has Kubernetes Already Become Too Unnecessarily Complex for Enterprise IT?](https://thenewstack.io/has-kubernetes-already-become-too-unnecessarily-complex-for-enterprise-it/): Is Enterprise IT stupid? No. There's the answer to that question.

[Making Kubernetes work for the average engineer—via PaaS](https://www.infoworld.com/article/3273104/containers/making-kubernetes-work-for-the-average-engineer-via-paas.html): Despite being the hottest thing since, well, Docker, Kubernetes remains a dark art for most mainstream enterprises

[Will Kubernetes Collapse Under the Weight of Its Complexity?](https://www.influxdata.com/blog/will-kubernetes-collapse-under-the-weight-of-its-complexity/): Is it? I'm pretty sure Kelsey Hightower said it was boring in Austin last year.

[Navigating the container security ecosystem](https://opensource.com/article/18/5/navigating-container-security-ecosystem): As container adoption increases, security automation will become a critical element of every organization's workflow.

[Five Words that Get In The Way of DevSecOps](https://www.scmagazine.com/five-words-that-get-in-the-way-of-devsecops/article/761870/): "Vulnerability, risk, policy, compliance and governance are words that get lost in translation between development, security and operations and cause confusion."

[Improve Security with Automated Image Scanning Through CI/CD](https://thenewstack.io/improve-security-with-automated-image-scanning-through-ci-cd/): "Using cloud-native security tools that hook right into Jenkins or your favorite CI/CD tool, enterprise security teams can set policies for developers who are building container images."

[The DevOps Security Checklist](https://www.sqreen.io/checklists/devops-security-checklist.html): This security checklist aims to give DevOps professionals a list of DevOps security best practices they can follow to implement DevSecOps.

[CNCF To Host Telepresence in the Sandbox](https://www.cncf.io/blog/2018/05/22/telepresence-in-the-sandbox/): "Telepresence is an open source tool — licensed under the Apache 2.0 License — that lets developers run a single service locally, while connecting that service to a remote Kubernetes cluster."

[Kubernetes best practices: terminating with grace](https://cloudplatform.googleblog.com/2018/05/Kubernetes-best-practices-terminating-with-grace.html): "When it comes to distributed systems, handling failure is key."

[Your Success with Enterprise Kubernetes Isn’t About Kubernetes](https://medium.com/google-cloud/your-success-with-enterprise-kubernetes-isnt-about-kubernetes-1c2b18dedc9): Running like Google is more than Kubernetes products or a nice UI.

<p><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-8972983586873269"
     data-ad-slot="9019534115"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></p>

## Tools

A healthy debate happening on my LinkedIn page (of all places) about why containers matter (and VMs still do too): ["I still don't see the point of containers and Kubernetes when you can just have a good old VM. Why should I have multiple containers for each process I need when I can just run them all on the VM?"](https://www.linkedin.com/feed/update/urn:li:activity:6406136826708451328/?commentUrn=urn:li:comment:(activity:6406136826708451328,6406138601528193024))

[Accessing Kubernetes Services Without Ingress, NodePort, or LoadBalancer](https://medium.com/@kyralak/accessing-kubernetes-services-without-ingress-nodeport-or-loadbalancer-de6061b42d72): ECMP can make Kubernetes services accessible without Ingress, NodePort, or LoadBalancer service types.

[Kubernetes won – so now what?](http://redmonk.com/jgovernor/2018/05/25/kubernetes-won-so-now-what/): Iterative improvements, that's what!

[Open Sourcing Zuul 2](https://medium.com/netflix-techblog/open-sourcing-zuul-2-82ea476cb2b3): Netflix open sourced Zuul 2, their "cloud gateway"

[All aboard the gRPC train](http://lpan.io/migrating-to-grpc/): A Datadog intern migrated a legacy, homegrown RPC to gRPC.

[ianmiell/autotrace](https://github.com/ianmiell/autotrace): Runs a process, and gives you the output along with other telemetry on the process, all in one terminal window.

[Building a Microservices Application in Go Following the CQRS Pattern](https://outcrawl.com/go-microservices-cqrs-docker/): This article walks through the development of a simplistic social network application where anyone can post anonymous messages.

[Announcement: Scope community](https://groups.google.com/forum/#!topic/scope-community/wLlOV_0Lt7Q): Weaveworks has decided to promote and foster [Scope](https://github.com/weaveworks/scope) as a community project.

[Go2 status](https://github.com/golang/go/wiki/Go2): This page tracks the status of "Go 2". Go 2 is in a very early, planning phase.

[atlassian/escalator](https://github.com/atlassian/escalator): Escalator is a batch or job optimized horizontal autoscaler for Kubernetes

[Playing battleships over BGP](https://blog.benjojo.co.uk/post/bgp-battleships): "Two communities were produced that would allow me run a game of battleships over BGP"

[Open Sourcing Coinbase’s Secure Deployment Pipeline](https://engineering.coinbase.com/open-sourcing-coinbases-secure-deployment-pipeline-ae6c78e25517): Odin takes a description of a project release and then safely and securely launches it into AWS using auto-scaling groups.

[facebookincubator/katran](https://github.com/facebookincubator/katran): A high performance layer 4 load balancer

[avantoss/vault-infra](https://github.com/avantoss/vault-infra): Terraform to create Vault infrastructure

[The Kata Containers project launches version 1.0 of its lightweight VMs for containers](https://techcrunch.com/2018/05/22/the-kata-containers-project-hits-1-0/)

[State of Cloud Native CI/CD Tools for Kubernetes](https://engineering.opsgenie.com/cloud-native-continuous-integration-and-delivery-tools-for-kubernetes-e6ea34d308c): A smorgasbord of cloud native tooling!

[A Docker Image in Less Than 1000 Bytes](https://zwischenzugs.com/2018/05/22/a-docker-image-in-less-than-1000-bytes/)

[kubernetes/kubernetes-template-project](https://github.com/kubernetes/kubernetes-template-project): A template for starting new projects on the github.com/kubernetes organization

[How OpenFaaS came to rescue us!](https://medium.com/iconscout/how-openfaas-came-to-rescue-us-ec129518cd46): An overview on our experience with serverless computing and speeding up Iconscout

[Automatically Generating InSpec Controls from Terraform](https://blog.chef.io/2018/05/23/automatically-generating-inspec-controls-from-terraform/)

[鯨魚水上飄的修煉 Day 4：Raspberry Pi上的Kubernetes](https://medium.com/mr-efacani-teatime/%E9%AF%A8%E9%AD%9A%E6%B0%B4%E4%B8%8A%E9%A3%84%E7%9A%84%E4%BF%AE%E7%85%89-day-4-raspberry-pi%E4%B8%8A%E7%9A%84kubernetes-b9f60cbc5517): 兩個月學習Docker & Kubernetes 的心得分享

[CalVer](http://calver.org/): CalVer is a software versioning convention that is based on your project's release calendar, instead of arbitrary numbers.

<p><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-8972983586873269"
     data-ad-slot="9019534115"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></p>

## Tweet of the Week

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">To journalist and analyst doing interviews at tech confs: don&#39;t change the conversation to from technical to D&amp;I _just_ because the interviewee is woman, minority, or PoC.</p>&mdash; Vincent Batts (@vbatts) <a href="https://twitter.com/vbatts/status/999644575659581441?ref_src=twsrc%5Etfw">May 24, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
