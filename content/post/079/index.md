+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-06-09T07:00:00Z
description = ""
draft = false
slug = "079"
tags = ["devops", "cloud native", "open source", "kubernetes", "github", "microsoft", "ansible", "amazon", "eks", "google"]
title = "079: Microsoft 💒 GitHub, Kubernetes, Ansible, Amazon EKS, Uber's D and More"
image = "/079/dc-skyline-from-dca.jpg"
imagealt = "Washington DC skyline as seen from Reagan National Airport (DCA)"
imagecap = "Washington DC skyline as seen from Reagan National Airport (DCA)"

+++

*Trying something different this week and sending out the newsletter on Saturday. Hit Reply and Let me know what you think.*

The big news this week is Microsoft's acquisition of GitHub. Jim Zemlin, Executive Director at The Linux Foundation, provides [a very positive and principled take on the GitHub acquisition](https://www.linuxfoundation.org/blog/microsoft-buys-github-the-linux-foundations-reaction/). I have been a believer in Microsoft's commitment to open source ever since [they reached out to me](https://twitter.com/ChrisShort/status/691756978679500800) to discuss how they can improve their image in the open source community. Microsoft is apologizing for the Ballmer years profusely with actions (not just words). But, I wonder if Microsoft is buying open source "cool points" too fast? The initial reaction to the acquisition from folks that didn't work at either company was generally negative. When [I discussed how far Microsoft has come](https://chrisshort.net/microsoft-has-come-a-long-way/) back in April, the reaction was also negative. The comments harkened back to an old Microsoft adage, ["Embrace, extend, and extinguish."](https://lobste.rs/s/ldts2j/microsoft_has_come_long_way#c_aa0zyy) I understand peoples' distrust. However, it has been three years since [Microsoft took the keynote stage at All Things Open 2015](https://twitter.com/ChrisShort/status/656457689053138944) to talk about how much they love Linux. They are doing everything right so far. It's time to start taking Microsoft's word (we're not at war). They are going to be good stewards of the open source communities they manage.

[**Two Key Practices for your CI process**](https://www.gocd.org/2018/05/30/ci-microservices-feature-toggles-trunk-based-development/)  
Trunk-based development and feature toggles are the two key practices which go a long way in implementing a robust CI process. In our new post of the CD of Microservices blog series, we'll focus on how to implement these two.  *SPONSORED*

{{< mc >}}

## Events

[Chaos Conf](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[AnsibleFest 2018](https://www.ansible.com/ansiblefest)  
Date: 2018-10-02 through 2018-10-03  
AnsibleFest is the annual user conference for the Ansible community and Red Hat Ansible Automation users. For the first time, we've expanded to two-days, jam-packed with content covering all aspects of IT automation, whether you're just getting started or already an advanced automation professional.

## People

[👋 Hello, GitHub](https://natfriedman.github.io/hello/): GitHub's new CEO, Nat Friedman, colors the path forward for GitHub. Give it a read if you hated this week's introduction.

[Nearly half of Bay Area residents say they want to leave](https://www.mercurynews.com/2018/06/03/nearly-half-of-bay-area-residents-say-they-want-to-leave/): Despite the Bay Area's natural beauty and booming job market, nearly half of its residents now want to get out, citing a creeping disillusionment with the high cost of housing.

[Uber CEO Dara Khosrowshahi insists that leaders say they have 'the D' in meetings — and bewildered employees aren't sure if he gets the other meaning](http://www.businessinsider.com/uber-ceo-dara-khosrowshahi-have-the-d-memo-2018-6): I literally can't even with Uber anymore. Talk about not having a clue (but they do have "the D"). Good lawd!

[Remote only](https://www.remoteonly.org/): A manifesto for remote only organizations. Also, good argument material for that boss that forces you to make that soul-sucking drive into the office every day.

[8 roles on a cross-functional DevOps team](https://opensource.com/article/18/6/roles-squad-model): Defining roles in the first step to implementing a squad model approach to DevOps. Here's an example of how to do it.

[The human scalability of "DevOps"](https://medium.com/@mattklein123/the-human-scalability-of-devops-e36c37d3db6a): "I've come to the conclusion that while DevOps can work extremely well for small engineering organizations, the practice can lead to considerable human/organizational scaling issues without careful thought and management."

[How not to kill your DevOps team](https://enterprisersproject.com/article/2018/6/how-not-kill-your-devops-team): Gloss over certain needs and warning signs and your DevOps initiative might just burn your team out. Follow these do's and don'ts to keep making healthy progress.

[Community Pulse — Imposter Syndrome (Episode 24)](http://communitypulse.io/24-imposter-syndrome/): "PJ, Jason, and Mary joined up with [Kelsey Hightower](https://twitter.com/kelseyhightower) from Google Cloud Platform to chat about imposter syndrome: What is imposter syndrome? Is it a thing? How can we overcome imposter syndrome in ourselves? How can we prevent imposter syndrome in others?"

[The Women in Tech Show: Chaos Engineering with Tammy Bütow](https://thewomenintechshow.com/2018/06/05/chaos-engineering-with-tammy-butow/)

[L8ist Sh9y Podcast: Chris Short on SRE, DevSecOps, Pipelines, Immutability, and Kubernetes](https://soundcloud.com/user-410091210/chris-short-on-sre-devsecops-pipelines-immutability-and-kubernetes)

[Live-Tweeting at Conferences](https://www.linkedin.com/pulse/live-tweeting-conferences-kim-mcmahon/) by [Kim McMahon](https://kimmcmahon.me/): I'm trying to get better at this. But, I think I'll leave the event tweeting to the pros.

{{< adsense-inarticle >}}

## Process

[GitHub Is Microsoft's $7.5 Billion Undo Button](https://www.bloomberg.com/news/articles/2018-06-06/github-is-microsoft-s-7-5-billion-undo-button): "Steve Ballmer spent years hating on open source software. Satya Nadella recognized that the service has become indispensable to programmers."

[Congratulations GitHub on the acquisition by Microsoft](https://about.gitlab.com/2018/06/03/microsoft-acquires-github/): "The acquisition of GitHub by Microsoft is validation of the growing influence of software developers in the world." GitLab is a class act organization.

[AI at Google: our principles](https://www.blog.google/topics/ai/ai-principles/)

[State of IPv6 Deployment 2018](https://www.internetsociety.org/resources/2018/state-of-ipv6-deployment-2018/): Kinda sad that the adoption rate is still so low. But, if IPv6 weren't as complex it'd be a lot higher.

[Fault Tolerance Is Not High Availability](https://dzone.com/articles/fault-tolerance-is-not-high-availability): These terms are not interchangeable. Learn the ins and outs of fault tolerance to highlight the differences between the two concepts.

[DevNationFederal 2018: DevOps is Not War](https://chrisshort.net/devnationfederal-2018-devops-is-not-war/): Red Hat invited me to speak at DevNationFederal. The organizers requested I present my DevOps is Not War talk to technologists in the Washington DC area.

[Squarespace: Gaining Productivity and Resilience with Kubernetes](https://kubernetes.io/case-studies/squarespace/): "Since Squarespace moved to Kubernetes, in conjunction with modernizing its networking stack, deployment time has been reduced by almost 85%." WOW!

[Can DevOps Really Shift Everything 'To The Left'?](https://www.forbes.com/sites/jasonbloomberg/2018/06/08/can-devops-really-shift-everything-to-the-left/#68b870cbc83a)
{{< adsense-inarticle >}}

## Tools

[The Best CI/CD Tool for Kubernetes Doesn't Exist](https://thenewstack.io/the-best-ci-cd-tool-for-kubernetes-doesnt-exist/): "'The hardest thing about running on Kubernetes is gluing all the pieces together. You need to think more holistically about your systems and get a deep understanding of what you're working with,' said [Chris Short](https://twitter.com/ChrisShort), a DevOps consultant and CNCF ambassador."

[Getting started with Buildah](https://opensource.com/article/18/6/getting-started-buildah): Buildah offers a flexible, scriptable way to create lean, efficient container images using your favorite tools.

[Lessons from Building Observability Tools at Netflix](https://medium.com/netflix-techblog/lessons-from-building-observability-tools-at-netflix-7cfafed6ab17): "It is critical to understand your users and deliver views tailored to a user's profile."

[Iterative Terraform Development with Skaffold and Kubernetes](https://hackernoon.com/iterative-terraform-development-with-skaffold-and-kubernetes-42cb6d60f7dc): "What if we could use Kubernetes tools for Terraform?"

[Kubernetes Deep Dive and Use Cases](https://thenewstack.io/kubernetes-deep-dive-and-use-cases/)

[A friendly alternative to the find tool in Linux](https://opensource.com/article/18/6/friendly-alternative-find): The fd command offers a simple, intuitive way to search your Linux filesystem.

[Amazon EKS – Now Generally Available](https://aws.amazon.com/blogs/aws/amazon-eks-now-generally-available/): I'm still waiting for Digital Ocean's Kubernetes product offering.

[Post-quantum Cryptography VPN](https://www.microsoft.com/en-us/research/project/post-quantum-crypto-vpn/): "This project takes a fork of the OpenVPN software and combines it with post-quantum cryptography."

[Get deeper insights with Honeycomb Tracing](https://www.honeycomb.io/blog/2018/06/get-deeper-insights-with-honeycomb-tracing/)

[A New Approach to DevOps with Spinnaker on Kubernetes](https://thenewstack.io/a-new-approach-to-devops-with-spinnaker-on-kubernetes/): "Companies must define the rollout process for the candidate it's running and manage it in a manner that recognizes the validity of the manifest for Kubernetes."

[VSTS and GitHub](https://blogs.msdn.microsoft.com/devops/2018/06/04/vsts-github/)

[How to deploy geographically distributed services on Kubernetes Engine with kubemci](https://cloudplatform.googleblog.com/2018/06/How-to-deploy-geographically-distributed-services-on-Kubernetes-Engine-with-kubemci.html)

[Heptio Kubernetes Subscription](https://blog.heptio.com/hey-aws-welcome-eks-to-the-kubernetes-community-949a2ef3a239): "HKS packages products and projects that help you run Kubernetes in AWS EKS, EC2 or on premises. For example, stand up clusters using Heptio Validated Designs for AWS."

[weaveworks/eksctl](https://github.com/weaveworks/eksctl): CLI for Amazon EKS

[Simple deployment to Amazon EKS](https://about.gitlab.com/2018/06/06/eks-gitlab-integration/): Amazon EKS is now GA! We've partnered with AWS to make sure GitLab support is available out of the gate.

[How to install a Kubernetes cluster on CentOS 7](https://www.techrepublic.com/article/how-to-install-a-kubernetes-cluster-on-centos-7/): Jack Wallen walks you through the process of installing a Kubernetes cluster on the enterprise-friendly CentOS 7 server platform.

[Etsy — Deploying to Google Kubernetes Engine](https://codeascraft.com/2018/06/05/deploying-to-google-kubernetes-engine/): "Our strategy specifically for deploying to a pair of Kubernetes clusters: one running in the Google Kubernetes Engine (GKE) and the other on-premises in our data center."

[aws_eks_cluster](https://docs.ansible.com/ansible/devel/modules/aws_eks_cluster_module.html): Manage Elastic Kubernetes Service Clusters with **Ansible**

[Baltimore Go June Meeting — Go to the Rescue: Saving DevOps from TLS Turmoil](https://chrisshort.net/baltimore-go-june-meeting---go-to-the-rescue-saving-devops-from-tls-turmoil/)

[Is OpenShift a Fork of Kubernetes? Short Answer – No. Longer Answer – Here's a Ton of Technical Reasons.](http://crunchtools.com/is-openshift-a-fork-of-kubernetes-short-answer-no-longer-answer-heres-a-ton-of-technical-reasons/)

[Go Language CookBook With Examples](https://ednsquare.com/publisher/view/Go-Language-CookBook-With-Examples------xOhLZaZVGG): An insightful guide to learning the Go programming language

[Dynamic Ingress in Kubernetes](https://kubernetes.io/blog/2018/06/07/dynamic-ingress-in-kubernetes/)

[Use Satellite 6 as an Inventory Source in Ansible Tower](https://www.ansible.com/blog/use-satellite-6-as-an-inventory-source-in-ansible-tower)

## Jobs

[DevOps Engineer at TiVo in Durham, NC](http://jobs.jobvite.com/careers/tivo/job/o1PA7fwh?__jvst=Employee%20Referral&__jvsd=srq0nhw0&__jvsc=Twitter&bid=ndUrYFwG)  
As a DevOps Engineer, you'll be part of a small operations team responsible for engineering and maintaining the production infrastructure for Tivo's Advanced Search and Recommendations platform in the cloud and on-premises.

## DevOps'ish Tweet of the Week

{{< tweet 1003643593729294337 >}}