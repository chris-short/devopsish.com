+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2018"]
date = 2018-07-01T07:00:00Z
description = "Picking Winning Tech, Blue is Bad, Kubernetes, GCP Problems, VKE, Ansible, and More"
draft = false
slug = "082"
tags = ["devops", "cloud native", "open source", "kubernetes", "ansible", "microservices", "google", "github", "microsoft", "cloud"]
title = "082: Picking Winning Tech, Blue is Bad, Kubernetes, GCP Problems, VKE, Ansible, and More"
image = "/082/IMG_4318.jpg"
imagealt = "Petosky State Park overlooking Lake Michigan"
imagecap = "Petosky State Park overlooking Lake Michigan"

+++

Twelve hours after this newsletter was published last week, I was on a plane back to my old stomping grounds in Raleigh, North Carolina. [I started at Red Hat this week on the Ansible team as Principal Product Marketing Manager](https://chrisshort.net/joining-ansible-team-at-red-hat/). After the first week, I feel like this is the best career move I've ever made. It's also a move that I've wanted to make for a long time. But, the delay has been well worth it. I look forward to working with teams internal and external to Red Hat to make Ansible an even better product than it already is.

As an aside, the family and I escaped the near triple-digit (Fahrenheit) temperatures of the Greater Detroit Metro for way "up north" Michigan. The image this week is of my son Max playing on the beach of Lake Michigan in [Petosky State Park](https://www.michigan.org/property/petoskey-state-park). Get out and enjoy the world around you when you have some time. Also, if you're disabled in any way be sure to take care of yourself.

[**Blog Series: Continuous Delivery of Microservices - Parts 1 - 4**](https://www.gocd.org/tags/cd-for-microservices.html?utm_campaign=cd_microservices&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=serries_1_4&utm_term=)  
This blog series from Sheroy Marker cover the principles of CD of microservices. Get a practical guide on designing CD workflows for microservices, testing strategies, trunk based development, feature toggles and environment plans. *SPONSORED*

[**Ballerina: Cloud-Native Programming Language**](http://ballerina.io/)  
Ballerina makes it easy to write microservices that integrate APIs. TechWorld placed it as #1 in their "Top programming languages you should try". Ballerina supports modern protocols and data formats, has built-in constructs for event and stream processing, resiliency, parallel execution, and can deploy directly onto Docker and Kubernetes. *SPONSORED*

[**The all-new Tower Git client for macOS & Windows has launched**](https://www.git-tower.com/?utm_source=devopsish%20newsletter&utm_medium=newsletter&utm_campaign=tower%20x%20launch&utm_content=june%202018)  
The new version adds an extensive set of new features: from Pull Requests to Interactive Rebase, Tower gives you access to Git's powerful feature set right from your desktop. [Save 20% for a limited time only](https://www.git-tower.com/?utm_source=devopsish%20newsletter&utm_medium=newsletter&utm_campaign=tower%20x%20launch&utm_content=june%202018)!  *SPONSORED*

## Events

[Kubernetes Workshop, Getting Minikube Up On Your Computer](https://www.meetup.com/Detroit-Kubernetes-Docker-all-things-Cloud-Native/events/251658852/)  
Date: 2018-07-12  
Time: 5:00 PM to 8:00 PM ET
We want everyone to have a local Kubernetes instance to experiment with, this will be a practical workshop, bring your laptop.

[Ballerinacon](https://con.ballerina.io/)  
Date: 2018-07-18  
Full day event in San Francisco and also streamed globally. Get intense training on the best practices of microservice development, resiliency, integration, Docker and Kubernetes deployment, Service Meshes, serverless, test-driven microservice development, lifecycle management, observability, and security.  
**DevOps'ish readers can attend FREE!** Use coupon code **BalCon-Devopsish** when buying the ticket.

[DevOpsDays Boston 2018](https://www.devopsdays.org/events/2018-boston/welcome/)  
Date: 2018-09-24 through 2018-09-25  

[Chaos Conf](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[AnsibleFest 2018](https://www.ansible.com/ansiblefest)  
Date: 2018-10-02 through 2018-10-03  
AnsibleFest is the annual user conference for the Ansible community and Red Hat Ansible Automation users. For the first time, we've expanded to two-days, jam-packed with content covering all aspects of IT automation, whether you're just getting started or already an advanced automation professional.

[All Day DevOps](http://www.alldaydevops.com/), Live Online  
Date: 2018-10-17 (24 hours)  
Where: From your desktop, laptop, or mobile device  
[**Free** Registration](https://www.alldaydevops.com/all-day-devops-2018-register)

## People

[3 Military Behaviors That Don't Work In The Civilian Workplace](https://taskandpurpose.com/3-military-behaviors-that-dont-work-in-the-civilian-workplace/): Number 3 took me a while to learn.

[Tintri terminates 200 staff, cash set to run dry in a couple of days](https://www.theregister.co.uk/2018/06/28/tintri_terminates_200_employees/): Array maker survived a whole year after IPO

[Q&A: Julia Grace, Slack's Head of Infrastructure Engineering](https://thenewstack.io/qa-julia-grace-slacks-head-of-infrastructure-engineering/): Slack was down this week...

[Leveling up: why developers need to be able to identify technologies with staying power (and how to do it)](https://medium.com/netlify/leveling-up-why-developers-need-to-be-able-to-identify-technologies-with-staying-power-and-how-to-9aa74878fc08): "...it's important to build up a solid instinct for separating the technologies and products worth spending time on from the ones that will fade into obscurity after their 15 minutes of fame is over..."

[Network Reliability Engineering: What's In a Name?](https://forums.juniper.net/t5/Enterprise-Cloud-and/Network-Reliability-Engineering-What-s-In-a-Name/ba-p/329764): "an NRE is someone that implements the core principles of DevOps, in a network engineering context"

[Forget about Clean Code, let's embrace Compassionate Code](http://johannesbrodwall.com/2018/06/24/forget-about-clean-code-lets-embrace-compassionate-code/): "I sometimes train teams in TDD, incremental design, refactoring and pair programming. I almost always have to spend a lot of time helping the team bridge their disagreements in a more constructive way. And often the ones who have read Clean Code are the most susceptible to this sort of conflicts."

[Why tech's favorite color is making us all miserable](https://www.fastcodesign.com/90177573/how-blue-became-techs-favorite-color-and-why-it-shouldnt-be): The cold blue light of modern touchscreens may be aesthetically pleasing, but it poses health problems. Designers and technologists should take cues from military history and embrace the orange.

[Open source jobs report: 3 hot skill areas now](https://enterprisersproject.com/article/2018/6/open-source-jobs-report-3-hot-skill-areas-now) "How hard is it to recruit cloud, containers, and DevOps gurus? Just 19 percent of open source pros say they haven't fielded a recruiter call during the past six months"

[13 must-read books to take your DevOps skills to the next level](https://opensource.com/article/18/6/13-books-devops-practitioners): This reading list includes some uncommon books to fine tune your DevOps practice.

[10 IT salary negotiation do's and don'ts](https://enterprisersproject.com/article/2018/6/10-it-salary-negotiation-dos-and-donts): Get the salary you deserve for that new job. Follow this advice on how to prepare – and how to avoid mistakes

## Process

[Kubernetes 1.11: In-Cluster Load Balancing and CoreDNS Plugin Graduate to General Availability](https://kubernetes.io/blog/2018/06/27/kubernetes-1.11-release-announcement/)

[Microsoft Buys GitHub: Three Weeks Later](https://www.linuxjournal.com/content/microsoft-buys-github-three-weeks-later): "Open source is big business now. Really big. Trying to frame it as the 'little guy' just doesn't work when you are the establishment."

[Why you should not use Google Cloud](https://medium.com/@serverpunch/why-you-should-not-use-google-cloud-75ea2aec00de): There's a lot going on here. But, for the record, Google Cloud Platform is my cloud provider of choice. However, as I told Tariq Islam, "[I'm sure this is similar to every story. The truth lies somewhere between both sides.](https://twitter.com/ChrisShort/status/1013245607723569152)" But, [Tariq did point out some great fallacies](https://twitter.com/chumboslice/status/1013260046476677120) in the debate.

[Good housekeeping for error budgets - part two - CRE life lessons](https://cloudplatform.googleblog.com/2018/06/cre-life-lessons-good-housekeeping-for-error-budgets.html): "An error budget is a crucial concept when you're taking a principled approach to service reliability."

[Puppet raises $42M to fuel its software development technology for the cloud, hopes to be cash-flow positive in a year](https://www.geekwire.com/2018/puppet-raises-42-million-mostly-existing-investors-hopes-cash-flow-positive-year/)

[Friday's Massive Comcast Outage Shows How Fragile the Internet Is](https://www.wired.com/story/friday-comcast-outage-cut-fiber): Cut fiber in North Carolina and New York led to a widespread outage for Comcast customers.

[Jack Dorsey just blew up Twitter's org structure to prepare it for the next decade](https://www.cnbc.com/2018/06/28/twitter-is-restructuring-as-its-product-executive-steps-down.html): "The change organizes Twitter into functional groups, such as engineering, instead of around individual products"

[Security for Kubernetes](https://thenewstack.io/security-for-kubernetes/): Let's talk with Liz Rice about Kubernetes security.

[Google Cloud CEO wanted to buy GitHub, hopes Microsoft really keeps it neutral; Azure CTO vows not to mess with it](https://www.geekwire.com/2018/google-cloud-ceo-wanted-buy-github-hopes-microsoft-really-keeps-neutral-azure-cto-vows-not-mess/)

[Repository Attacks Continue with Backdoored Docker Images](https://thenewstack.io/repository-attacks-continue-with-backdoored-docker-images/): When you outsource your core infrastructure don't be surprised by what you get.

[Gentoo Github Organization hacked](https://archives.gentoo.org/gentoo-announce/message/dc23d48d2258e1ed91599a8091167002)

[Stop Scheduling Conference Calls and Finally Commit to Videoconferencing](https://hbr.org/2018/06/stop-scheduling-conference-calls-and-finally-commit-to-videoconferencing): There is an enormous benefit to seeing who you're talking to.

## Tools

[GitHub Developers are Giving Microsoft a Chance](https://www.wired.com/story/github-developers-are-giving-microsoft-a-chance/): While I think there's no reason to panic about the Microsoft acquisition of GitHub one mantra holds true: diversify your portfolio.

[We're moving from Azure to Google Cloud Platform](https://about.gitlab.com/2018/06/25/moving-to-gcp/): GitLab.com is migrating to Google Cloud Platform – here's what this means for you now and in the future.

[Introducing VMware Kubernetes Engine™ (VKE)](https://blogs.vmware.com/cloudnative/2018/06/26/introducing-vmware-kubernetes-engine-vke/): Now you can unnecessarily involve VMWare in even more things.

[Terraform becomes a programming language](https://ilya-sher.org/2018/06/30/terraform-becomes-a-programming-language/): A quick-hitting article about Terraform's recent changes (and a knock against Puppet and Ansible)

[Bare Metal K8s Clustering at Chick-fil-A Scale](https://medium.com/@cfatechblog/bare-metal-k8s-clustering-at-chick-fil-a-scale-7b0607bd3541): Chik-fil-A is doing some interesting things around the open source space lately.

[Ansible 2.6](https://releases.ansible.com/ansible/) is available now

[Why You Should Care about a Service Mesh](https://thenewstack.io/why-you-should-care-about-a-service-mesh/): "Service meshes offer the centralized control plane that enterprises require, while still enabling the free-wheeling stylings of agile, cloud-based application development."

[3 ways to copy files in Go](https://opensource.com/article/18/6/copying-files-go): In the third article in this series about the Go programming language, learn the three most popular ways to copy a file.

[It's Time You Learned About Quantum Computing](https://www.wired.com/story/time-you-learned-about-quantum-computing/): When you figure it all out let me know.

[Running integration tests in Kubernetes](https://opensource.com/article/18/6/running-integration-tests-kubernetes): Verify how your application behaves with your full solution stack by using multiple containers to provide a whole test environment.

[Automating Helm Charts with Ansible](https://blog.openshift.com/automating-helm-charts-with-ansible/)

[HashiCorp Consul 1.2: Service Mesh](https://www.hashicorp.com/blog/consul-1-2-service-mesh): "This release supports a major new feature called Connect that automatically turns any existing Consul cluster into a service mesh solution."

[Why Kubernetes is The New Application Server](https://developers.redhat.com/blog/2018/06/28/why-kubernetes-is-the-new-application-server/): "In this new containerized world, application servers are mutating into becoming more like frameworks."

## Jobs

[DevOps Engineer at TiVo in Durham, NC](http://jobs.jobvite.com/careers/tivo/job/o1PA7fwh?__jvst=Employee%20Referral&__jvsd=srq0nhw0&__jvsc=Twitter&bid=ndUrYFwG)  
As a DevOps Engineer, you'll be part of a small operations team responsible for engineering and maintaining the production infrastructure for Tivo's Advanced Search and Recommendations platform in the cloud and on-premises.

[Developer Advocate at Kickbox (REMOTE, US Only)](https://kickbox.workable.com/j/3A32893ACE)  
The core of developer relations is community and empathy. We're looking for someone that can connect with people, build relationships and actively support the learning and success of others.

[Product Marketer at Kickbox (REMOTE, US Only)](https://kickbox.workable.com/j/C4E099F227)  
The core of product marketing is rooted in product promotion. It's a combination of product development and branding and plays a critical role in bringing new tech products to market. We're looking for someone to enthusiastically collect data, create developer personas and develop a marketing funnel.

**NOTE:** If you're a subscriber and looking for talent, please let me know. For the time being, I'm happy to feature job postings from subscribers for free.

## DevOps'ish Tweet of the Week

{{< tweet 1012011199897141249 >}}
