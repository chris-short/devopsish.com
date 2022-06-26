+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2018"]
date = 2018-04-01T07:00:00Z
description = ""
draft = false
slug = "069"
tags = ["devops", "cloud native", "open source", "kubernetes", "docker", "infosec", "Ansible", "lambda", "containers", "Docker Inc", "Site Reliability Engineering", "SRE"]
title = "069: Kubernetes 1.10, Docker Deathwatch, Breaches, goo.gl Gone, Ansible, and More"
image ="https://shortcdn.com/file/devopsish/easter-2018.jpg"
imagealt = "Happy Easter"
imagecap = ""

+++

What a big week for tech news! On Monday, the first Kubernetes release of 2018  dropped like the world's hottest mixtape; [Kubernetes 1.10](https://kubernetes.io/blog/2018/03/26/kubernetes-1.10-stabilizing-storage-security-networking/) is out! On Wednesday, we saw what I believe to be the next step in Docker's death; Solomon Hykes is out! More on that below. We also witnessed yet [another big-time company get hit by WannaCry](https://www.seattletimes.com/business/boeing-aerospace/boeing-hit-by-wannacry-virus-fears-it-could-cripple-some-jet-production/); Boeing. Boeing is the latest victim of poor IT practices as it found itself fighting the fast-spreading virus. Kudos to Boeing for getting it mitigated quickly but, this should never have happened given how old WannaCry is. Then on Thursday, 150 million of us found ourselves as a victim of yet another breach when [MyFitnessPal announced its systems had been compromised](https://www.buzzfeed.com/skbaer/myfitnesspal-under-armour-data-stolen?utm_term=.gbbPDpvGR#.bnkebagxZ). The MyFitnessPal breach compromised only superficial login data and passwords. No health or government issued data was stolen. Not to be outdone, Drupal core had a ["Highly critical" RCE vulnerability](https://www.drupal.org/sa-core-2018-002). To top things off there appears to be a "skip containers, go serverless" drum beat building (more on that below).

[**Announcement: Continuous Delivery on Kubernetes with GoCD**](https://www.gocd.org/2018/03/21/continuous-delivery-gocd-kubernetes/)  
GoCD now integrates natively with Kubernetes! GoCD's pipeline capability along with Kubernetes' highly programmable platform provide you the premiere Continuous Delivery tool on modern infrastructure. *SPONSORED*

**Get early access to the all-new Tower Git client for Mac and Windows**  
The best Git client for your Mac and PC now supports pull requests, interactive rebase and many powerful new features. [Read more](https://www.git-tower.com/blog/tower-public-beta-2018-whats-new?utm_source=devopsish%20newsletter&utm_medium=newsletter&utm_campaign=tower%20public%20beta&utm_content=april%202018) about the upcoming release and [sign up here](https://www.git-tower.com/public-beta-2018?utm_source=devopsish%20newsletter&utm_medium=newsletter&utm_campaign=tower%20public%20beta&utm_content=april%202018) to get early access. *SPONSORED*

**[Visualize AWS VPC data flow logs, in near real-time, on an interactive and immersive visual platform](https://beta.totalcloud.io/)**  
Tighten the VPC's security and improve its performance with complete visibility. *SPONSORED*

## Events

[**Open Source 101 Columbia**](http://opensource101.com/columbia/)  
Date: 2018-04-17  
Sadly I won't be able to participate in Open Source 101 Columbia but if it's half as good as the one held in Raleigh it's a can't miss event. [Open Source 101](http://opensource101.com/columbia/) is such a fantastic and inexpensive event (if you need assistance with a ticket let me know).

[**Event-Based Architectures in Go**](https://www.meetup.com/DetroitGolang/events/249236487/)  
Date: 2018-04-27  
We'll talk about design considerations, effective uses for event-based systems, the state of the Go ecosystem, and work through some examples that leverage Apache Kafka.

[**ChefConf 2018**](https://chefconf.chef.io/)  
Dates: 2018-05-22 through 2018-05-25  
Join an awesome community of #DevOps and automation professionals at [ChefConf](https://chefconf.chef.io/) in Chicago. I'll be presenting a brand spanking new talk, *DevOps is Not a War*. Save 10% with discount code 'Hugs4Chef'.

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

## People

[What a Docker shocker; founder, CTO Solomon Hykes takes a hike](https://www.theregister.co.uk/2018/03/28/docker_shocker_solomon_hykes_take_a_hike/): Solomon Hykes officially announced he was leaving Docker after presumably being [sidelined in November](https://thenewstack.io/solomon-hykes-changes-roles-docker/).  [Cluster and application management services in Docker Cloud are shutting down on May 21](https://docs.petty.company/docker-hub/) and [Docker Security Scanning](https://docs.petty.company/develop/scan-images/) is shuttering on March 31st. Something is definitely happening at Docker. I still think [Docker is Dead](https://chrisshort.net/docker-inc-is-dead/). It smells like Docker is cleaning out the crufty or unprofitable services to make themselves riper for acquisition.

[Google Isn't Listening, So Its Employees Are Suing](https://gizmodo.com/google-isnt-listening-so-its-employees-are-suing-1823611720): "Google is the target of several high-profile lawsuits from former employees, all alleging discrimination."

[Creating a strong 'office' culture for remote workers](https://slackhq.com/creating-a-strong-office-culture-for-remote-workers-77caad08306d): How the dispersed team at Student Loan Hero prioritizes communication and connection

[Through the looking glass: Security and the SRE](https://opensource.com/article/18/3/through-looking-glass-security-sre): It's time to take a more proactive approach to system security. Here's how chaos engineering can play a key role.

## Process

[GitLab's Journey to Cloud Native: Breaking the monolith and scaling for tomorrow](https://docs.google.com/presentation/d/1fsgvSuGpn-MnMqKaTOoiRvUvdJFHd3VpoAAfBoMtFYg/mobilepresent?slide=id.g2823c3f9ca_0_9) (SLIDESHOW)

[CNCF Survey: China is Going Native with Cloud](https://www.cncf.io/blog/2018/03/26/cncf-survey-china/)

[Serverless is eating the stack and people are freaking out — as they should be](https://read.acloud.guru/serverless-is-eating-the-stack-and-people-are-freaking-out-and-they-should-be-431a9e0db482): "AWS Lambda has stamped a big DEPRECATED on containers." Meanwhile, I went looking for a place to run containers as a service this week (and I only found AWS Fargate).

[Skip containers and do serverless computing instead](https://www.infoworld.com/article/3265457/containers/why-serverless-is-the-better-option-than-containers.html): Container technologies like Docker are very powerful, but require talent you can't get. Serverless computing provides the same benefits—with talent you can actually get

[As predicted, more branch prediction processor attacks are discovered](https://arstechnica.com/gadgets/2018/03/its-not-just-spectre-researchers-reveal-more-branch-prediction-attacks/): New attack focuses on a different part of the branch prediction system.

[Exploring container security: An overview](https://cloudplatform.googleblog.com/2018/03/exploring-container-security-an-overview.html)

[Waiting time, load factor, and queueing theory – why you need to cut your systems a bit of slack](https://erikbern.com/2018/03/27/waiting-time-load-factor-and-queueing-theory.html)

[All AWS Services GDPR ready](https://aws.amazon.com/blogs/security/all-aws-services-gdpr-ready/): AWS services comply with the General Data Protection Regulation (GDPR)

[GoDaddy signs multiyear deal with Amazon Web Services for 'vast majority' of its computing infrastructure](https://www.geekwire.com/2018/godaddy-signs-multiyear-deal-amazon-web-services-vast-majority-computing-infrastructure/): GoDaddy's new tagline should be: "GoDaddy: AWS run poorly so you don't have to!"

## Tools

[Kubernetes 1.10: Stabilizing Storage, Security, and Networking](https://kubernetes.io/blog/2018/03/26/kubernetes-1.10-stabilizing-storage-security-networking/): This was a monumental effort by the entire Kubernetes community. A huge thanks to the [1.10 Release Team](https://github.com/kubernetes/sig-release/blob/master/releases/release-1.10/release_team.md) for their hard work.

[CNCF Cloud Native Trail Map](https://github.com/cncf/landscape/#trail-map): The Cloud Native Landscape has a growing number of options. This Cloud Native Trail Map is a recommended process for leveraging open source, cloud native technologies. At each step, you can choose a vendor supported offering or do it yourself, and everything after step #3 is optional based on your circumstances.

["Cloud Native Infrastructure", a Free O'Reilly eBook, thanks to Heptio!](https://blog.heptio.com/i-still-remember-the-first-time-i-logged-into-a-production-server-over-ssh-and-telling-myself-i-53ab1d1e7f46): Get Justin Harrison's and Kris Nova's awesome book for free. Thank you, Heptio!

[Google is shutting down its goo.gl URL shortening service](https://www.engadget.com/2018/03/30/google-shutting-down-goo-gl-url-shortening-service/): The company wants you to use the more app-centric Firebase Dynamic Links

[Draft vs Gitkube vs Helm vs Ksonnet vs Metaparticle vs Skaffold](https://blog.hasura.io/draft-vs-gitkube-vs-helm-vs-ksonnet-vs-metaparticle-vs-skaffold-f5aa9561f948): A comparison of tools that help developers build and deploy their apps on Kubernetes

[skaffold 0.3.0 was released this week](https://github.com/GoogleCloudPlatform/skaffold/releases/tag/v0.3.0) just in time for this week's [TGI Kubernetes](https://www.youtube.com/watch?v=McwwWhCXMxc&t=0s&list=PLvmPtYZtoXOENHJiAQc6HmV2jmuexKfrJ&index=30).

[Studying the Kubernetes Ingress system](https://www.joyfulbikeshedding.com/blog/2018-03-26-studying-the-kubernetes-ingress-system.html)

[tammybutow/chaos_engineering_bootcamp](https://github.com/tammybutow/chaos_engineering_bootcamp): Tammy Butow's Chaos Engineering Bootcamp is available on GitHub.

[Ansible 2.5 was announced this week](https://www.ansible.com/blog/ansible-2.5-traveling-space-and-time)

[Manage your workstation with Ansible: Automating configuration](https://opensource.com/article/18/3/manage-your-workstation-configuration-ansible-part-2): Learn how to make Ansible automatically apply configuration changes to a fleet of laptops and desktops.

[How to create an open source stack using EFK](https://opensource.com/article/18/3/efk-creating-open-source-stack): This tutorial shows you how to use Elasticsearch, Fluentd, and Kibana to build an open source stack that helps you manage complex data systems.

[Bring your own Linux to Windows with new open source tool](https://arstechnica.com/gadgets/2018/03/microsofts-new-open-source-tool-lets-you-bring-your-own-linux-distro-to-windows/): If an off-the-shelf Linux distribution doesn't float your boat, why not build your own?

[Serverless in the cloud: AWS vs. Google Cloud vs. Microsoft Azure](https://www.infoworld.com/article/3265750/paas/serverless-in-the-cloud-aws-vs-google-cloud-vs-microsoft-azure.html): With AWS Lambda, Google Cloud Functions, and Microsoft Azure Functions, a little bit of business logic can go a very long way

[Caddy 0.10.12 Released with ACMEv2 and Wildcard Certificates](https://caddyserver.com/blog/caddy-0_10_12-released)

[Rancher's Project Longhorn Now Available on Kubernetes](http://rancher.com/project-longhorn-now-available-kubernetes/)

[kelseyhightower/confd](https://github.com/kelseyhightower/confd)

[cloud66/copper](https://github.com/cloud66/copper): Copper is a configuration validator for Kubernetes by Cloud 66

[grpc/grpc-go](https://github.com/grpc/grpc-go): The Go language implementation of gRPC. HTTP/2 based RPC

[gokrazy](https://gokrazy.org/): gokrazy is a pure-Go userland for your Raspberry Pi 3 appliances

[Microsoft rolls out the first availability zones within Azure regions to boost customer reliability](https://www.geekwire.com/2018/microsoft-rolls-first-availability-zones-within-azure-regions-boost-customer-reliability/): How is this JUST now happening?!? How is Azure the #2 cloud provider?!?

## DevOps'ish Tweet of the Week

{{< tweet 978732224324427777 >}}
