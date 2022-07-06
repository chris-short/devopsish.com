+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2018"]
date = 2018-05-06T07:00:00Z
description = ""
draft = false
slug = "074"
tags = ["devops", "cloud native", "open source", "kubernetes", "kubecon", "docker", "aws", "cloud", "lambda", "containers", "Site Reliability Engineering", "SRE"]
title = "074: Kubernetes' Big Week in Europe, Three-day no meetings, High-speed networking, and More"
image ="https://shortcdn.com/file/devopsish/air-show.jpg"
imagealt = "Air show"

+++

My week started out great! Spring had finally sprung here in Michigan. But, with that came something I'm allergic to. Then that turned into a sinus infection. That has now expanded into a horrible cough. I have already had one doctor's visit. But, it was a VA doc since I already had an appointment there. It might be time to see a real doctor.

[**Free Webinar: Continuous Delivery with Docker, Kubernetes, and GoCD**](https://info.thoughtworks.com/Continuous-Delivery-Docker-Kubernetes-webinar)  
Docker and Kubernetes provide the platform for organizations to get software to market quickly. In this webinar, you will get a practical guide in designing a Docker-based CD pipeline on Kubernetes with GoCD. *SPONSORED*

## Events

[**ChefConf 2018**](https://chefconf.chef.io/)  
Dates: 2018-05-22 through 2018-05-25  
Join an awesome community of #DevOps and automation professionals at [ChefConf](https://chefconf.chef.io/) in Chicago. I'll be presenting, *DevOps is Not a War*. Save 10% with discount code **Hugs4Chef**.

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

[**DevNation Federal**](https://devnationfederal.org/)  
Date: 2018-06-05  
Join us to learn about the revolutions happening in communities around s, data, and application modernization. This is an opportunity for you to hear how visionary teams in federal government are innovating with open source, and hear from leaders in the private sector doing the same.

[**Chaos Conf**](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[**LISA18**](https://www.usenix.org/conference/lisa18)  
Dates: 2018-10-29 through 2018-10-31  
Have something to say on the present & future of #ops? The LISA18 CFP closes May 24. [Submit your ideas](https://www.usenix.org/blog/usenix-lisa18-cfp-nashville)!

## People

[The ultimate DevOps hiring guide](https://opensource.com/article/18/4/ultimate-devops-hiring-guide): Trying to round up DevOps talent? We're a unique lot that requires some tweaks to your hiring practices.

[What makes a great SRE?](https://opensource.com/article/18/5/what-makes-great-sre) Site reliability engineers play a pivotal role in most organizations. Here are some of the top skills and qualifications to look for.

[‘Forget the Facebook leak': China is mining data directly from workers' brains on an industrial scale](http://www.scmp.com/news/china/society/article/2143899/forget-facebook-leak-china-mining-data-directly-workers-brains): Government-backed surveillance projects are deploying brain-reading technology to detect changes in emotional states in employees on the production line, the military and at the helm of high-speed trains

## Process

[Three-day no-meeting schedule for engineers](https://medium.com/@Pinterest_Engineering/three-day-no-meeting-schedule-for-engineers-fca9f857a567): We did something a lot like this at McClathy Interactive. We had all our cross departmental meetings on Monday and Friday. Every day, your organizational unit had a standup/scrum spanning all projects (no longer than 15 minutes, first thing in the morning). Every time I walk into a new workcenter I espouse the benefits of this model. A huge thanks to Ted Boggs and Steve Coile for letting me work in this model. It was glorious!

[The GDPR Checklist](https://gdprchecklist.io/): "This list is far from a legal exhaustive document, it merely tries to help you overcome the struggle." Which is a lot more than I could ever hope to do.

[Kubernetes: The State of Stateful Apps](https://www.cockroachlabs.com/blog/kubernetes-state-of-stateful-apps/): StatefulSets and DaemonSets are here to help. But, keep in mind, your database doesn't *have* to be in a Kubernetes cluster.

[GitHub says bug exposed some plaintext passwords](https://www.zdnet.com/article/github-says-bug-exposed-account-passwords/): I'd really like for 1Password to rotate my highly complex passwords for critical sites routinely. Things like Twitter, GitLab, GitHub, and Google are critical services I cannot afford to have compromised. I have two-factor authentication obviously but, there has to be more I can do, right? No? Okay fine.

[Netlify's Approach to the CDN, Microservices, and Breaking Down Your Monolith](https://thenewstack.io/netlifys-approach-to-the-cdn-microservices-and-breaking-down-your-monolith/)

[Lessons from Building Static Analysis Tools at Google](https://cacm.acm.org/magazines/2018/4/226371-lessons-from-building-static-analysis-tools-at-google/fulltext): "Here, we describe how we have applied the lessons from Google's previous experience with FindBugs Java analysis, as well as from the academic literature, to build a successful static analysis infrastructure used daily by most software engineers at Google."

## Tools

[Kubernetes in Europe: The most significant news from Kubecon this week](https://www.geekwire.com/2018/kubernetes-europe-significant-news-kubecon-week/): A decent round up from KubeCon in case you want to bounce this newsletter off a third-party source.

[How Does Kubernetes Networking Actually Work?](http://blog.wercker.com/how-does-kubernetes-work)

[Introducing the Kubernetes Podcast from Google](https://cloudplatform.googleblog.com/2018/05/introducing-kubernetes-podcast-from-google.html)

[Kubernetes And The Open Service Broker Make Multi-Cloud A Reality](https://www.forbes.com/sites/janakirammsv/2018/04/29/kubernetes-and-the-open-service-broker-make-multi-cloud-a-reality/#66e29d231295)

[Datadog provides visibility into Kubernetes apps with new container map](https://techcrunch.com/2018/05/03/datadog-now-offers-visibility-into-kubernetes-applications-via-container-map/)

[Introducing the Confluent Operator: Apache Kafka® on Kubernetes Made Simple](https://www.confluent.io/blog/introducing-the-confluent-operator-apache-kafka-on-kubernetes/): "In the next month, we'll release a reference architecture along with a set of deployment templates and Confluent Platform docker images. You can use these to deploy Apache Kafka and Confluent Platform on Kubernetes."

[Announcing Rancher 2.0 GA](https://rancher.com/blog/2018/2018-05-01-rancher-ga-announcement-sheng-liang/): "Today we reach an important milestone. Rancher 2.0, a release we worked on in the past year, has achieved GA and is ready for production deployment."

[Bitnami Launches Kubeapps 1.0 to Advance Kubernetes Application Services](http://www.prweb.com/releases/2018/05/prweb15452909.htm): Production Ready Kubernetes Application Console integrates Open Service Broker, Kubeless serverless functions and JFrog Kubernetes Registry

[Building a Media Transcoder with Exodus, FFmpeg, and AWS Lambda](https://intoli.com/blog/transcoding-on-aws-lambda/): Running ffmpeg on AWS Lambda for 1.9% the cost of AWS Elastic Transcoder

[Announcing Stackdriver Kubernetes Monitoring: Comprehensive Kubernetes observability from the start](https://cloudplatform.googleblog.com/2018/05/Announcing-Stackdriver-Kubernetes-Monitoring-Comprehensive-Kubernetes-observability-from-the-start.html)

[AWS announces support for serverless containers on Kubernetes](https://www.computing.co.uk/ctg/news/3031378/aws-announces-support-for-serverless-containers-on-kubernetes): Cloud giant weighs in to support Virtual Kubelet project originally kicked off by Microsoft

[5 Kubernetes Monitoring to-dos](https://thenewstack.io/5-kubernetes-monitoring-to-dos/)

[High Speed Networking: Open Sourcing our Kernel Bypass Work](https://www.bbc.co.uk/rd/blog/2018-04-high-speed-networking-open-source-kernel-bypass)

[Rook's Framework for Cloud-Native Storage Orchestration](https://blog.rook.io/rooks-framework-for-cloud-native-storage-orchestration-c66278014df7): Now Supporting CockroachDB and Minio

[openebs/litmus](https://github.com/openebs/litmus): Decisive e2e tests for qualifying Kubernetes storage options by running many stateful workloads in a variety of Kubernetes environments. Release the chaos monkey.

[kontena/pharos-cluster](https://github.com/kontena/pharos-cluster): The simple, solid, certified Kubernetes distribution that just works.

[joyent/triton-kubernetes](https://github.com/joyent/triton-kubernetes): "Triton Kubernetes is a multi-cloud Kubernetes solution. It has a global cluster manager (control plane) which can run on any cloud - Public, Private or Bare Metal and manages Kubernetes environments."

[curltainer](https://github.com/chris-short/dockerfiles/tree/master/curltainer): I'm tinkering with ways to build, extend, and standardize common functions like autopublishing this newsletter or triggering builds of Docker containers. Ultimately, what I'd like is to have one container for all functions and one Kubernetes artifact for that function. Things like running curls at webhooks should be feasible. I'd love to see more projects like this.

[github/gh-ost](https://github.com/github/gh-ost): GitHub's Online Schema Migrations for MySQL

[nearmap/cvmanager](https://github.com/nearmap/cvmanager): "Container Version Manager (cvmanager) is a continuous integration (CI) and continous delivery (CD) tool designed for Kubernetes cluster/services."

[gruntwork-io/terratest](https://github.com/gruntwork-io/terratest): Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.

[![XKCD: Containers](https://shortcdn.com/file/devopsish/containers.png)](https://xkcd.com/1988/)

## Jobs

[**SJ Technologies**](http://sjtechcorp.com/) is looking to bring someone on board to work in our DevOps and Digital Transformation practice. If you want to help some big-time companies eager to implement change [*let me know*](mailto:chris.short@sjtechcorp.com). Plus, you get to work for great team of folks including [Karen Lawton](https://twitter.com/sjtech_karen?lang=en), [John Willis](https://twitter.com/botchagalupe/), [Barbara Bouldin](https://twitter.com/bbouldin711), and [ME](https://chrisshort.me/).

[DZone](http://careers.dzone.com/apply/DBWe0hiNCN/Site-Reliability-Engineer) is looking for a Site Reliability Engineer in Cary, NC. Based off my experiences with DZone, this is a cool place to work. To quote a decision maker at DZone, "We need strong cloud, automation, security [experience]." Check them out.

## DevOps'ish Tweet of the Week

{{< tweet 992054069148770304 >}}
