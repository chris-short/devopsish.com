+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-11-03T07:00:00Z
description = "UNIX: A History and a Memoir, systemd ~, JEDI, Jaeger, Fitbit, DKIM, Ansible Operators, Quarkus, Img, Podman, Contour, and More"
draft = false
slug = "152"
tags = ["DevOps", "Kubernetes", "cloud", "Unix", "open source", "container", "Contour", "Img", "Ansible Operators", "Cloud Native", "Quarkus", "Jaeger", "podman", "DKIM", "CNCF", "Fitbit", "systemd", "JEDI", "platform", "AWS", "culture"]
title = "152: UNIX: A History and a Memoir, systemd ~, JEDI, Jaeger, Fitbit, DKIM, Ansible Operators, Quarkus, Img, Podman, Contour, and More"

+++

I actually crossed things off my list this week. The little wins should be celebrated along with the big ones. There is something very therapeutic about erasing a line on a whiteboard or checking a box. That's not celebration enough though. Make sure if you are doing complicated work that you take a moment to celebrate when it all comes together. There's absolutely nothing wrong with feeling good about yourself. Morale is a huge part of this work. I learned this early on back in my  military days and it has served me very well in the DevOps world.

## Events

[All Day DevOps, Live Online](https://www.alldaydevops.com/)  
November 6, 2019 (24 hours)  
From your desktop, laptop, or mobile device  
[Free Registration](https://www.alldaydevops.com/register)

On November 6th, we will be supporting the live online All Day DevOps conference. This is a 24 hour event with 5 simultaneous tracks, delivering 125+ sessions in 38 time zones. Session tracks include Cloud Native Infra and Monitoring, DevSecOps and Automated Security, CI/CD, Site Reliability Engineering, and Cultural Transformation.

[**KubeCon + CloudNativeCon North America 2019**](https://cshort.co/kcna19)  
The Cloud Native Computing Foundation's flagship conference gathers adopters and technologists from leading open source and cloud native communities in San Diego, California from November 18-21, 2019. Join Kubernetes, Prometheus, Envoy, CoreDNS, containerd, Fluentd, OpenTracing, gRPC, CNI, Jaeger, Notary, TUF, Vitess, NATS, Linkerd, Helm, Rook, Harbor, etcd, Open Policy Agent, CRI-O, and TiKV as the community gathers for four days to further the education and advancement of cloud native computing. Use code *KCNACSN10* at checkout for a 10% discount on KubeCon Corporate Registration.

## People

{{< tweet 1189948923777032193 >}}

[GitHub tries, in vain, to quell employee anger over ICE contract](https://www.latimes.com/business/technology/story/2019-10-31/github-ice-contract-defense) — To say things aren't going smoothly at GitHub would appear to be an understatement. DevOps'ish reader, Twitter friend, and now former GitHub staff engineer, Sophie Haskins, resigned on Monday, "the company did not cancel its contract with ICE and 'shows no indication of canceling the contract,' which she wrote was 'morally unacceptable.'" That's another huge loss for GitHub.

[UNIX: A History and a Memoir by Brian W Kernighan](https://amzn.to/2NsxEgF) — "The fascinating story of how Unix began and how it took over the world. Brian Kernighan was a member of the original group of Unix developers, the creator of several fundamental Unix programs, and the co-author of classic books like 'The C Programming Language' and 'The Unix Programming Environment.'"

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[Introducing your friends to automation (and overcoming their fear)](https://www.redhat.com/sysadmin/introducing-automation) — "The term 'automation' makes people nervous for a variety of reasons. Here are some ways to help your friends get over those fears and embrace automation."

[mxssl/sre-interview-prep-guide](https://github.com/mxssl/sre-interview-prep-guide) — Site Reliability Engineer Interview Preparation Guide

[How to ‘unlearn' your habitual behaviours and step closer to success](https://www.siliconrepublic.com/advice/unlearning-success-barry-oreilly) — "Business adviser, entrepreneur and author Barry O'Reilly discusses the importance of ‘unlearning' for a successful career."

[Ann Arbor-Detroit Tech Events, November 2019](https://cronicle.press/2019/10/31/ann-arbor-detroit-tech-events-november-2019/) — The tech scene is really flourishing in Michigan right now. We have great beer up here too.

## Process

[The JEDI Contract: What really happened?](https://www.cloudmanagementinsider.com/the-jedi-contract-what-really-happened/) — America's cloud train wreck.

[GitLab Had Begun Planning To Track Its Users But Quickly Changed Course](https://www.phoronix.com/scan.php?page=news_item&px=GitLab-Telemetry-Yes-No) — "After announcing planned changes to their terms of service, following customer outrage they quickly stepped down on those plans." This went out and got turned around so fast. I'm not sure what GitLab was thinking here.

[Linux Foundation Introduces a Telemetry Policy for All Projects](https://thenewstack.io/linux-foundation-introduces-a-telemetry-policy-for-all-projects/) — Inevitable in the wake of the GitLab pullback.

[Jaeger seventh project to graduate CNCF](https://devclass.com/2019/10/31/jaeger-seventh-project-to-graduate-cncf/) — What is CNCF Graduation mean? From [DevOps'ish 066](https://devopsish.com/066/), "[CNCF Graduation] is meant to be a stamp from the Technical Oversight Committee and the CNCF of what is a sustainable, production ready and mature open source project (i.e., you can bet your business on it)."

[Google forks out $2.1bn for Fitbit – and promises not to exploit all that delicious health data to sling ads (honest)](https://www.theregister.co.uk/2019/11/01/google_buys_fitbit/) — Fitbit owners get a to wonder if their product is the next thing [Google kills](https://killedbygoogle.com/). But, after the Google and Nest "thing" I suspect there will be a Pixel wearable soon.

[Founders' note: IOpipe joins New Relic!](https://read.iopipe.com/founders-note-iopipe-joins-new-relic-c15eeda47151) — Congrats to the folks at IOpipe!

[Ansible Operators October 2019 Update](https://blog.openshift.com/ansible-operators-october-2019-update/) — What happened in the Ansible Operator space last month. Also, my first blog post on the OpenShift blog!

[Pentagon awaits possible Amazon challenge over cloud deal](https://apnews.com/a3d7a26c6f0642089dfc3f43b60a60e1) — That's inevitable.

[Why Platform9 Migrated Its Managed Kubernetes Service to Packet from AWS](https://thenewstack.io/why-platform9-migrated-its-managed-kubernetes-service-to-packet-from-aws/) — "'There's a zillion levers you can pull to optimize costs, we were spending so much of our time trying to manage and optimize costs.' Platform9 reached a point where investing additional money was inevitable: either in a way to control AWS costs or in moving to another solution that would lead to lower costs."

[16M passwords from Fortune 500 companies found on the dark web](https://siliconangle.com/2019/10/30/16m-passwords-fortune-500-companies-found-dark-web/) — That's a lot of passwords. But since it's from Fortune 500s it's probably a lot of `123456`, `admin`, and `password` type passwords which means this dump is [skewing the numbers even more](https://en.wikipedia.org/wiki/List_of_the_most_common_passwords).

[Phippy and Zee Go To The Mountains](https://phippygoestothemountains.github.io/) — I missed this when it was released. Wee lil Zee and good ole Phippy take on Prometheus in this adventure.

[3 quick ways to reduce your attack surface on Linux](https://www.redhat.com/sysadmin/reduce-attack-surface) — The basics are beyond important.

## Tools

[DevOps: Tools Can Lead The Culture Change](https://redmonk.com/rstephens/2019/10/25/devops-tools-can-lead-the-culture-change/) — "It's an industry truism that DevOps is about culture change rather than products, but tools can very much lead a culture change and we shouldn't underestimate their role."

[DKIM demystified](https://www.20i.com/blog/dkim-demystified/) — If you deliver mail from a domain, it should have DKIM configured.

[Istio: Up and Running: Using a Service Mesh to Connect, Secure, Control, and Observe](https://amzn.to/2PGCQAk) — "In this book, Lee Calcote and Zack Butcher explain why your services need a service mesh and demonstrate step-by-step how Istio fits into the life cycle of a distributed application. You’ll learn about the tools and APIs for enabling and managing many of the features found in Istio."

[Sysdig 2019 Container Usage Report: New Kubernetes and security insights](https://sysdig.com/blog/sysdig-2019-container-usage-report/) — "One of the surprising insights this year is the 2X increase in the number of containers that live for less than five minutes." Hot damn!

[Why you don't have to be afraid of Kubernetes](https://opensource.com/article/19/10/kubernetes-complex-business-problem) — "It's just a shitload of YAML and some APIs." —Chris Short

[When Quarkus Meets Knative Serverless Workloads](https://vmblog.com/archive/2019/10/29/when-quarkus-meets-knative-serverless-workloads.aspx#.XbiN1JNKiuN) — My buddy Daniel Oh explains the massive productivity gains Java devs can gain when using Quarkus.

[Why you should use `python -m pip`](https://snarky.ca/why-you-should-use-python-m-pip/) — "Fellow core developer and Canadian, Mariatta, asked on Twitter about python -m pip and who told her about that idiom along with asking for a reference explaining it."

[Inspecting Docker Containers with Visual Studio Code](https://code.visualstudio.com/blogs/2019/10/31/inspecting-containers) — "[Y]ou can attach Visual Studio Code to your container so that you can use the full power of VS Code, including debugging, to inspect the container, figure out what is going wrong, and fix it."

[Configuring container networking with Podman](https://www.redhat.com/sysadmin/container-networking-podman) — "Confused about how to network rootless and rootfull pods with Podman? Read on."

[Building Container Images with Img](https://blog.giantswarm.io/building-container-images-with-img/) — "Essentially, Img is a wrapper around another open source build-related technology called BuildKit, which is embedded within Img as a library."

[The current adoption status of cgroup v2 in containers](https://medium.com/nttlabs/cgroup-v2-596d035be4d7) — "While the adoption of cgroup v2 is an inevitable step toward 2020s, most container implementations including Docker/Moby and Kubernetes still don't support cgroup v2."

[ClusterAPI — A Guide on How to Get Started](https://medium.com/condenastengineering/clusterapi-a-guide-on-how-to-get-started-ff9a81262945) — "However, tectonic-installer is no longer under active development and its features are to be converged with Red Hat OpenShift Container Platform. Considering the circumstances, the cloud platforms team at Condé Nast is in the process of investigating and trialling diverse mechanisms for cluster provisioning, including ClusterAPI."

[Contour Announcing Contour 1.0: A Proxy for Your Multi-Tenant Future](https://projectcontour.io/announcing-contour-1.0/) — "From Ingress to IngressRoute to HTTPProxy" congrats to the folks working on the Contour project for hitting 1.0.

[Enabling OpenTracing with the NGINX Ingress Controller for Kubernetes](https://www.nginx.com/blog/opentracing-with-nginx-ingress-controller-for-kubernetes/)

[Pack Your Bags – Systemd Is Taking You To A New Home](https://hackaday.com/2019/10/16/pack-your-bags-systemd-is-taking-you-to-a-new-home/) — "Home directories are so unspectacular in their nature, it wouldn't usually cross anyone's mind to even consider to change anything about them. And then there's Lennart Poettering."

[ghostinthewires/Azure-Readiness-Checklist](https://github.com/ghostinthewires/Azure-Readiness-Checklist) — This checklist is your guide to the best practices for deploying secure, scalable, and highly available infrastructure in Azure. Before you go live, go through each item, and make sure you haven't missed anything important!

[Furduhlutur/yar](https://github.com/Furduhlutur/yar) — Yar is a tool for plunderin' organizations, users and/or repositories.

[gshipley/wild-west-kubernetes](https://github.com/gshipley/wild-west-kubernetes) — A wild west game to kill pods on kubernetes

[jlesquembre/kubeprompt](https://github.com/jlesquembre/kubeprompt) — Kubernetes prompt

## Tweet of the Week

![Jill Jubs on Twitter](/images/152-tweet-of-the-week.png)
