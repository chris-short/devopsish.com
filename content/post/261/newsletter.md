+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-03-20T07:00:00Z
description = ["Secrets with GitOps, cr8escape, B1txor20, npm sabotage (again), updated Kubernetes Hardening Guide, ArgoCD and Starboard, scripting with Go, and more"]
draft = false
slug = "261"
tags = ["GitOps", "secrets", "ArgoCD", "Kubernetes", "git", "service", "hardening", "cluster", "Honeycomb", "cloud", "scripting", "math", "CDN"]
title = "DevOps'ish 261: Secrets with GitOps, cr8escape, B1txor20, npm sabotage (again), updated Kubernetes Hardening Guide, ArgoCD and Starboard, scripting with Go, and more"
+++

This week I wanted to spur discussion around some GitOps hurdles folks are facing. As a co-chair, it's not only my job to make sure we're discussing how folks are handling things. We should be providing some guidance on how to implement those [**GitOps Principles**](https://opengitops.dev/#principles) in a practical manner. The discussions themselves are around ["Management" Clusters](https://github.com/open-gitops/project/discussions/95), [Progressively Delivery](https://github.com/open-gitops/project/discussions/93), and [Handling Secrets with GitOps](https://github.com/open-gitops/project/discussions/96).

That last one is sticking out in my mind quite a bit: GitOps Secrets Management. I'll preface this by saying this is my opinion. It's is not the opinion of the CNCF GitOps Working Group or OpenGitOps. Universally, it's a bad idea to check secrets into `git`. Whether they're encrypted or not that shouldn't really matter. They're still secrets and, in my opinion, encrypted or not, secrets shouldn't live in `git`. A shared password safe is better than `git`. Even better an external secret store so you could utilize the [Kubernetes Secrets Store CSI Driver](https://secrets-store-csi-driver.sigs.k8s.io/). To me, it comes down to a few important things.

1. Unix philosophy: I think secrets management tooling is probably better at managing secrets than a distributed version control system. Just saying.
1. You need active secrets management in production: That means regular rekeying, monitoring of existing keys, and the auditing and logging such a service provides. This could run in cluster but, chances are you're using a Secrets Store CSI Driver compatible service somewhere in your enterprise.
1. Quantum computing (or time): eventually, that blob of encrypted text is going to fall flat on its face against quantum computing or a skilled adversary. Adversarial governments already posses the power to decrypt many things if they dedicate the resources to it. There's no reason to expose what is essentially a very important database to the general public because, like with all things, given enough time and energy, whatever protection you did have, will fall.
1. I'll say it again, *there's no reason to expose what is essentially a very important database to the general public*.

GitOps says everyone in the `git` pool. But, just like some folks still think the best way to run a database is on bare metal, with no abstractions on compute (latency matters). In my opinion, the best way to store your secrets is some place off cluster in a secret management service or on cluster in a secret manager that's highly available. Either way, it should never be publicly accessible.

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## Events

Calling all front-line DevOps and SRE practitioners: Join [**IR Conf**](https://www.irconf.io/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on April 1 (no joke), a free, half-day virtual conference for industry experts and new voices in incident response. Incident responders will come together to swap horror stories about the biggest outages, discuss best practices, and gain a better understanding of how the best are dealing with incidents. Register to:

* Discover trends and tooling in resiliency and incidence response
* Gain guidance on how to structure your teams, tooling, and processes
* Learn better practices from incident response experts
* Connect with a community of incident responders who care about this, learn from each other

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on 2022-05-17 is designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)  
SEPTEMBER 19 – 21, 2022  
ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[To Keep Students in STEM fields, Let's Weed Out the Weed-Out Math Classes](https://www.scientificamerican.com/article/to-keep-students-in-stem-fields-lets-weed-out-the-weed-out-math-classes/)
I would love public math and math teachers to get a complete overhaul. The system is intentionally exclusionary and overly elitist, in my opinion. I could have loved math if it wasn't for a bad teacher.

[Goldman Sachs’ CEO demanded all employees return full-time to the office. Only half showed up](https://finance.yahoo.com/news/goldman-sachs-ceo-demanded-employees-210608499.html)  
Not sure what folks expected. There are two sides to this coin. People don't mind or rather enjoy the office and people that have been working from home and don't see a better way to manage their competing responsibilities.

[Intel announces another megafab as chipmaker expands EU footprint](https://arstechnica.com/tech-policy/2022/03/intel-announces-another-megafab-as-chipmaker-expands-eu-footprint/)  
The chip crisis is going to last until all these new fabs are spun up. Then there might actually be more supply than we need but, demand is increasing year after year after year so we'll see.

[Facebook’s Parent Company Will Make Employees Do Their Own Laundry](https://www.nytimes.com/2022/03/11/technology/facebook-meta-perks.html)  
On a trip to the Google campus YEARS ago one of the single most jaw dropping perks I saw was full-blown laundry service. More time to focus on your work, I guess. But, yeah, not doing laundry would be pretty great. I'll never get such a perk working from home.

[Russia faces IT crisis with just two months of data storage left](https://www.bleepingcomputer.com/news/technology/russia-faces-it-crisis-with-just-two-months-of-data-storage-left/amp/)  
Never thought of this. But, yeah, there's not a lot of hard drive manufacturing in Russia is there.

## Process

[Court affirms it's false advertising to claim software is Open Source when it’s not](https://opensource.org/blog/court-affirms-its-false-advertising-to-claim-software-is-open-source-when-its-not)  
"The court held that it was improper for the defendants to remove the Commons Clause, and therefore the defendants’ claims in advertising that its ONgDB software was open source was false advertising."

[Why you should avoid Sealed Secrets in your GitOps deployment](https://dnastacio.medium.com/why-you-should-avoid-sealed-secrets-in-your-gitops-deployment-e50131d360dd)  
A take on sealed secrets that coincides with this week's introduction.

[cr8escape: New Vulnerability in CRI-O Container Engine (CVE-2022-0811)](https://www.crowdstrike.com/blog/cr8escape-new-vulnerability-discovered-in-cri-o-container-engine-cve-2022-0811/)  
"When invoked, an attacker could escape from a Kubernetes container and gain root access to the host and be able to move anywhere in the cluster"

[Sabotage: Code added to popular NPM package wiped files in Russia and Belarus](https://arstechnica.com/information-technology/2022/03/sabotage-code-added-to-popular-npm-package-wiped-files-in-russia-and-belarus/)
Dear Software Supply Chain tooling, please don't indicate where are operations run.

[etcd Integrates Continuous Fuzzing](https://etcd.io/blog/2022/etcd-integrates-continuous-fuzzing/)  
A more secure etcd for a more secure Kubernetes.

[Why SSO Sucks and the future of SSO](https://goteleport.com/blog/why-sso-sucks/)  
"There are a few problems that mean that this isn’t a reality. The tl;dr is that because each app controls the login process, and different apps have different architectures, having a standardized flow that works across all apps is very challenging."

[New Threat: B1txor20, A Linux Backdoor Using DNS Tunnel](https://blog.netlab.360.com/b1txor20-use-of-dns-tunneling_en/)  
Strap in. We're going for a ride. "B1txor20 is a Backdoor for the Linux platform, which uses DNS Tunnel technology to build C2 communication channels. In addition to the traditional backdoor functions, B1txor20 also has functions such as opening Socket5 proxy and remotely downloading and installing Rootkit."

## Tools

[NSA & CISA Kubernetes Hardening Guide Version 1.1](https://www.armosec.io/blog/nsa-cisa-kubernetes-hardening-guide/)  
NSA and CISA updated the Kuberentes Hardening Guide this week. ARMO takes a look at it. Here's the [PDF](https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/0/CTR_Kubernetes_Hardening_Guidance_1.1_20220315.PDF) if you're interested.

[Scripting with Go](https://bitfieldconsulting.com/golang/scripting)  
Why scripting in Go could be a better solution than all those shell scripts.

[Kubernetes and containerization trends (according to the reports of 2021)](https://blog.flant.com/kubernetes-and-containers-market-trends-2021/)  
An aggregate of a bunch of Kubernetes reports last year. This is some interesting data but, be careful with averages of averages.

[e-Cloud: Large-scale CDN using KubeEdge](https://www.cncf.io/blog/2022/03/18/e-cloud-large-scale-cdn-using-kubeedge/)  
"This article describes how e-Cloud uses KubeEdge to manage CDN edge nodes, automatically deploy and upgrade CDN edge services, and implement edge service disaster recovery (DR) when it migrates its CDN services to the cloud."

[Kubernetes Security through GitOps Best Practices: ArgoCD and Starboard](https://www.youtube.com/watch?v=YvMY8to9aHI)  
"In this tutorial, I show you how to integrate Starboard into your GitOps workflow to continuously check our workloads for vulnerabilities." Here is the [corresponding blog post](https://anaisurl.com/gitops-argocd-starboard/).

[Using Argo CD with vclusters](https://blog.argoproj.io/using-argo-cd-with-vclusters-5df53d1c51ce)  
vclusters are essentially Kubernetes in Kubernetes. "Developing and testing external cluster deployment scenarios can be challenging because of needing to set up multiple clusters. Luckily, there is a tool which helps simplify creating clusters that works great with Argo CD."

[Honeycomb Terraform Provider Now Officially Supported by Honeycomb](https://www.honeycomb.io/blog/hny-terraform-provider-now-officially-supported/)  
That's a good idea.

[SSH and Git, meet 1Password 🥰](https://blog.1password.com/1password-ssh-agent/)  
A 1Password ssh-agent? Okay, I'll play!

[Nvidia Unveils Big Accelerator Memory: Solid-State Storage for GPUs](https://www.tomshardware.com/news/nvidia-unveils-big-accelerator-memory-solid-state-storage-for-gpus)  
This thing looks wild. "Nvidia and IBM propose a new GPU-SSD interoperability framework."

## DevOps'ish Tweet of the Week

[![CyclingTips (@cyclingtips on Twitter) "This is everything 😍"](https://shortcdn.com/file/devopsish/261-devopsish-tweet-of-the-week.webp)](https://twitter.com/cyclingtips/status/1503446251148230656)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/261/notes/) to see what didn't make it to the newsletter but are still worth your time.
