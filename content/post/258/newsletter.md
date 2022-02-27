+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-02-27T07:00:00Z
description = [""]
draft = false
slug = "258"
tags = []
title = "DevOps'ish 258: "

+++

Rough week here on the home front. Rough week in other places too. Reach out if you're struggling.

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## People

[Employees Are Sick of Being Asked to Make Moral Compromises](https://hbr.org/2022/02/employees-are-sick-of-being-asked-to-make-moral-compromises)  
"Moral injury is experienced as a trauma response to witnessing or participating in workplace behaviors that contradict one's moral beliefs in high-stakes situations and that have the potential of harming others physically, psychologically, socially, or economically, and it could prompt people to leave a company." This is an interesting take. Perfect example (potentially extreme) of this is [me](https://chrisshort.net/curriculum-vitae/#cyber-transport-systems--communications-computer-systems-controller--us-air-force--nov-1999-to-dec-2010) and [Snowden](https://en.wikipedia.org/wiki/Edward_Snowden). It bothered me for years. After years of therapy I can finally live with it all.

[Chris Lattner Formally Steps Down From Swift's Core Team](https://www.phoronix.com/scan.php?page=news_item&px=Lattner-Leaves-Swift-Core-Team)  
"Chris Lattner's current day focus is serving as co-founder and CEO of Modular AI with seeking to overhaul the AI/ML infrastructure world."

[We Shouldn't Have To Hide Our Disability: Is The Tech Industry Doing Enough To Support Disabled People Of Color?](https://peopleofcolorintech.com/break-into-tech/we-shouldnt-have-to-hide-our-disability-is-the-tech-industry-doing-enough-to-support-disabled-people-of-color/)  
"People with disabilities with an advanced degree earn $21,000 less annually than people without disabilities, though they have the same education levels." On top of so much more. Being disabled doesn't pay.

[Five Years Ago, I Set Out To Prove A VC Firm Could Invest With A Diversity Thesis. Here's Where We Are Today.](https://news.crunchbase.com/news/diverse-founders-report-harlem-capital-black-latino-founders/)  
"Then my firm, Harlem Capital Partners, started raising for Fund I in 2018 and LPs kept asking, 'But are there enough Black and Latino founders to have a diversity thesis?'"

[Agile Doesn't Work Without Psychological Safety](https://hbr.org/2022/02/agile-doesnt-work-without-psychological-safety)  
"Here are five practical ways to increase psychological safety to foster a collaborative, successful agile team."

## Process

[Intel Ramps Up Linux Investment By Acquiring Linutronix](https://www.phoronix.com/scan.php?page=news_item&px=Intel-Acquires-Linutronix)
"This is a great move by Intel for furthering their contributions to the Linux / open-source world."

[How secure is your Grafana instance? What you need to know](https://grafana.com/blog/2022/02/22/how-secure-is-your-grafana-instance-what-you-need-to-know/)  
"Grafana is a web service. In its simplest form, a web service does something for you. You request information from the service, and the service responds with the information you asked for by querying the backend (i.e., a database or another web service). We all know that data, in general, is precious and needs to be protected; thus, both the database as well as the service need to have some kind of security. But what does “security” actually mean?"

[US microchip powerhouse Nvidia hit by cyber attack](https://www.telegraph.co.uk/business/2022/02/25/us-microchip-powerhouse-nvidia-hit-cyber-attack/)
And it appears [Nvidia hacked them back](https://hothardware.com/news/lapsus-claims-nvidia-hacked-back-after-its-attack)!  
What a time to be alive.

[Oh, Snap! Security Holes Found in Linux Packaging System](https://thenewstack.io/oh-snap-security-holes-found-in-linux-packaging-system/)  
"Despite the funny name, these security holes are serious. In the worst-case scenario, this 7.8 Common Vulnerability Scoring System (CVSS) rated security hole can be used to obtain full root privileges on default Ubuntu installations."

[Snyk has acquired Fugue, entering into the cloud security market](https://www.itopstimes.com/itsec/snyk-has-acquired-fugue-entering-into-the-cloud-security-market/)  
"Additionally, a new Snyk solution will unite and extend its Infrastructure as Code and Fugue's cloud security capabilities that were designed for DevSecOps teams."

[OpenSea Investigating ‘Exploit Rumors' as Users Complain of Missing NFTs](https://www.coindesk.com/business/2022/02/20/opensea-investigating-exploit-rumors-as-users-complain-of-missing-nfts/)  
"Emails purporting to be from the NFT marketplace about a planned smart contract migration may have been a phishing attack."

## Tools

[Free Cybersecurity Services and Tools](https://www.cisa.gov/free-cybersecurity-services-and-tools)  
As we all have a heightened sense of vigilance, here's some help if you need it.

[The US Copyright Office says an AI can't copyright its art](https://www.theverge.com/2022/2/21/22944335/us-copyright-office-reject-ai-generated-art-recent-entrance-to-paradise?scrolla=5eb6d68b7fedc32c19ef33b4)  
I had to think for a long time whether to put this in [People](#people) or [Tools](#tools). Ultimately, a tool was used to create a work. That work wasn't made by a human and the Copyright Office cited the non-human factor in their ruling.

[Running Windows workloads on a private EKS cluster](https://aws.amazon.com/blogs/containers/running-windows-workloads-on-a-private-eks-cluster/)  
"Blog post provides a step by step guide from enabling Windows support in an EKS cluster to allowing Windows worker nodes to utilize cluster internal networking to creating a Windows node group."

[Deprecation of the MinIO gateway](https://blog.min.io/deprecation-of-the-minio-gateway/)  
"We introduced the gateway feature early on to help make the S3 API ubiquitous... The goal has been achieved. S3 API is the de facto standard for storage and has made object storage the storage class of the cloud and of Kubernetes."

[A almost perfect rsync over ssh backup script](https://blog.zazu.berlin/software/a-almost-perfect-rsync-over-ssh-backup-script.html)  
`rsync` can be akin to magic at times.

[Kubernetes for dummies: Life of a Pod](https://itnext.io/kubernetes-for-dummies-life-of-a-pod-fc8158e27aa)  
A pod is a pod, of course, of course, and no one can talk to a pod of course that is, of course, unless the pod is in the famous Kubernetes!

[How to route UDP traffic into Kubernetes](https://aws.amazon.com/blogs/containers/how-to-route-udp-traffic-into-kubernetes/)  
"Demonstrates how to configure and deploy an ADOT Collector to collect system metrics for workloads on an EKS Fargate cluster and sending them to CloudWatch"

[Retain on Delete](https://www.pulumi.com/blog/retainondelete/)  
"We've seen a number of user questions over the years about keeping resources after Pulumi deployments, or sharing resources between deployments. All of these worked down to needing a new resource option to tell the Pulumi engine to not actually delete a resource when replacing or removing it from the stack."

[Avoiding the Top 10 NGINX Configuration Mistakes](https://www.nginx.com/blog/avoiding-top-10-nginx-configuration-mistakes/)  
"In this blog we look at 10 of the most common errors, explaining what's wrong and how to fix it."

[Getting Started wtih GitOps and Flux](https://www.youtube.com/watch?v=NwAgATWoEcM)  
Flux CNCF webinar about Flux

[orioledb/orioledb: OrioleDB](https://github.com/orioledb/orioledb)  
"Building a modern cloud-native storage engine (... and solving some PostgreSQL wicked problems)"

[jodevsa/wireguard-operator](https://github.com/jodevsa/wireguard-operator)  
"A wireguard operator created to easily provision a VPN in a k8s cluster"

## DevOps'ish Tweet of the Week

[![Kelsey Hightower (@kelseyhightower on Twitter) "Let's say the bitcoin dream comes true, and we all get the 'freedom to transact', does racism, oppression, and the abuse of power disappear, or does it simply use bitcoin to fund it?"](https://shortcdn.com/file/devopsish/258-devopsish-tweet-of-the-week.webp)](https://twitter.com/kelseyhightower/status/1495809055088345088)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/258/notes/) to see what didn't make it to the newsletter but are still worth your time.
