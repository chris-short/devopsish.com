+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2019"]
date = 2019-09-01T07:00:00Z
description = ""
draft = false
slug = "143"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "DevOps news", "Kubernetes news", "tanzu", "cluster", "javascript", "pacific"]
title = "143: Fresh caught Pacific Tanzu, Cluster API, good God Google, JavaScript library ads, and more"

+++

## DevOps'ish Last Week's Top Five

1. [Git Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html)
1. [WeWTF](https://www.profgalloway.com/wewtf)
1. [Learn Kubernetes during your Coffee Break - Kubernetes Camp](https://k8s.camp/)
1. [It's not always true, but sometimes it is true.](https://www.reddit.com/r/kubernetes/comments/ctn93i/its_not_always_true_but_sometimes_it_is_true/)
1. [walmartlabs/kubeman](https://github.com/walmartlabs/kubeman)

[See the top ten →](https://devopsish.com/143/notes/)

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[See more Events →](https://devopsish.com/143/events/)

## People

[Nikki McDonald](https://www.linkedin.com/in/nikkimc/) is looking for a full-time content director or conference producer/manager role. It would need to be remote or based in Ann Arbor, Michigan. Nikki is also open to freelance editing/writing work or contract jobs.

[Cisco lays off 'whole teams' at RTP campus, confirms employee](https://www.wraltechwire.com/2019/08/23/cisco-lays-off-whole-teams-at-rtp-campus-confirms-employee/) — Cisco will continue to lay off and hire en masse to make its numbers work as long as workers keep coming back to Cisco.

[Female-free speaker list causes PHP show to collapse when diversity-oriented devs jump ship](https://www.theregister.co.uk/2019/08/27/php_europe_cancelled/) — Women make up half the population. If you can't manage to get one woman to speak at a conference it should be shut down.

[My Time at Google and After](https://medium.com/@jennifer.blakely/my-time-at-google-and-after-b0af688ec3ab) — "In October of 2008, still living together, David [Drummond] and I attended a dinner in Palo Alto with other Google employees, many from the legal department. During dinner, our babysitter called to say our son was sick so I went home and David said he would be right behind me. Several hours later that same evening, I received a call from Chris Chin, the Associate General Counsel and a friend, who told me that David had taken two other women who worked for him in the legal department to San Francisco. I didn't understand. Our son was very sick and I panicked so I called him several times but he didn't answer his phone. Finally, I sent him a text message asking him when we could expect him home. He responded, 'Don't expect me back. I'm never coming back.' And he didn't."

[Techies are coming together to program a geekier nation](https://timesofindia.indiatimes.com/business/india-business/techies-are-coming-together-to-program-a-geekier-nation/articleshow/70816677.cms) — Fellow CNCF Ambassador, Neependra Khare, was interviewed by Times of India.

## Process

[Document Like a Scientist](https://noti.st/karissapeth/g3vUiw) — "Learn how scientists document their work and are able to pick up new experimental protocols quickly. Apply the concepts of scientific protocols to your documentation to make them more useful to yourself and your users."

[DevOps terms: 10 essential concepts, explained](https://enterprisersproject.com/article/2019/8/devops-terms-10-essential-concepts) — "Here's a primer on 10 key terms you need to know – whether you are new to DevOps or you want to bring a colleague up to speed quickly. We also contrast commonly confused DevOps terms"

[How to Grade DevOps Teams with Nicole Forsgren, PhD](https://www.screaminginthecloud.com/episodes/how-to-grade-devops-teams-with-nicole-forsgren-phd) — "Join Corey and Nicole as they discuss what it's like to put together said reports, why people are so passionate about their DevOps team's unique approach, the four metrics you can use to grade DevOps teams, how to scale DevOps teams, and more."

[Don't get locked up into avoiding lock-in](https://martinfowler.com/articles/oss-lockin.html) — "[L]ock-in isn't a simple true-or-false matter: avoiding being locked into one aspect often locks you into another. Also, popular notions, such as open source automagically eliminating lock-in, turn out to be not entirely true. Time to have a closer look at lock-in, so you don't get locked up into avoiding it!"

## Tools

[Project Pacific - Technical Overview](https://blogs.vmware.com/vsphere/2019/08/project-pacific-technical-overview.html) — "Project Pacific is a re-architecture of vSphere with Kubernetes as its control plane." VMware is moving the management of workloads forward by pushing its entire platform to run on top of Kubernetes. This is a paradigm shift for the industry. This is essentially the beginning of the end for traditional virtual machines. Will VMs be a mainframe-like technology? No. People have been bitten way too many times for leaving their VMs alone for years and then trying to change literally anything.

[Introducing VMware Tanzu Mission Control to Bring Order to Cluster Chaos](https://blogs.vmware.com/cloudnative/2019/08/26/vmware-tanzu-mission-control/) — Tanzu brings, "A SaaS based control plane will securely integrate with a Kubernetes cluster through an agent and supports a wide array of operations on the cluster. That includes lifecycle management (deploy, upgrade, scale, delete) of cloud-based clusters via Cluster API." Single pane of glass matters and unfortunately the community maintained Kubernetes dashboard falls short in a lot of ways.

[Popular JavaScript library starts showing ads in its terminal](https://www.zdnet.com/article/popular-javascript-library-starts-showing-ads-in-its-terminal/) — In a rather comical and wholly unsafe turn of events, a JavaScript library... is now inserting ads in its terminal. [standard](https://www.npmjs.com/package/standard) package devs thought it'd be a great idea (it's probably fine). [npm has changed its policies](https://www.npmjs.com/policies/open-source-terms#commercial-content) as a result. But, it is continuing the debate of how to fund open source development.

[Mutual Auto-Unseal Two Vault clusters in Kubernetes](https://itnext.io/mutual-auto-unseal-two-vault-clusters-in-kubernetes-465516da98f8) — Use one Vault to auto-unseal another automatically.

[Dell announces new Linux XPS 13 developer edition 7390 laptop](https://www.cyberciti.biz/linux-news/dell-announces-new-linux-xps-13-developer-edition-7390-laptop/) — If Apple keeps screwing around with under performing devices, this could be my next laptop.

[Someone Forked GIMP into Glimpse Because Gimp is an Offensive Word](https://itsfoss.com/gimp-fork-glimpse/) — Pulp Fiction came out in 1994. GNU Image Manipulation Program (GIMP) was first released in 1996. I first used it in '98, before I was hurt. I only thought of the Pulp Fiction reference back then. Gimp was a derogatory term long before 1994 and it never should've been named GIMP to begin with. I had to explain what Windows NT was to someone the other day. Before meeting me in 2010, my spouse had never seen Pulp Fiction. A rename is long overdue.

[Bootstrapping a Kubernetes Cluster on AWS with Cluster API](https://blog.scottlowe.org/2019/08/27/bootstrapping-a-kubernetes-cluster-on-aws-with-clusterapi/) — Do you want to build a cluster?

[curl exercises by Julia Evans](https://jvns.ca/blog/2019/08/27/curl-exercises/)

[sysdiglabs/kubectl-dig](https://github.com/sysdiglabs/kubectl-dig) — Deep kubernetes visibility from the kubectl

[tensorflow/text](https://github.com/tensorflow/text) — Making text a first-class citizen in TensorFlow

[fcsonline/drill](https://github.com/fcsonline/drill) — Drill is a HTTP load testing application written in Rust inspired by Ansible syntax

## DevOps'ish Tweet of the Week

Please do the open source community a favor and read the whole thread.

{{< tweet 1166100939792474112 >}}

Notes from this week's issue can be found [here](https://devopsish.com/143/notes/).
