+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2019"]
date = 2019-07-14T07:00:00Z
description = "It is done, unicorn languages, Weave Ignite, you can't handle the CORS, and more"
draft = false
slug = "136"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "security", "DevOps news", "Kubernetes news", "Red Hat", "code", "Microsoft Teams", "infrastructure", "VSCode", "GitOps"]
title = "136: It is done, unicorn languages, Weave Ignite, you can't handle the CORS, and more"

+++

[Q&A: IBM's Landmark Acquisition of Red Hat](https://www.ibm.com/blogs/think/2019/07/ibm-red-hat/). It is done. Aside from extra meetings from too many Red Hat folks, I have seen zero change. I'd like to talk more about the whole acquisition process from my point of view since it was announced, at some point. Overall, from my perspective, the process was smooth. I commend Red Hat and IBM leadership for keeping the chaos to a minimum. Here's to next week and hopefully fewer meetings!

[**10 Kubernetes distributions leading the container revolution**](https://www.oreilly.com/pub/cpc/238261)  
Kubernetes and containers are changing how applications are built, deployed, and managed. Check out the distros leading the charge. *SPONSORED*

## DevOps'ish Last Week's Top Five

1. [Why I quit a $500K job at Amazon to work for myself](https://danielvassallo.com/only-intrinsic-motivation-lasts/)
1. [Fuck Off As A Service (FOAAS)](https://foaas.com/)
1. [Get your work recognized: write a brag document](https://jvns.ca/blog/brag-documents/)
1. [How to use GitLab and Ansible to create infrastructure as code](https://about.gitlab.com/2019/07/01/using-ansible-and-gitlab-as-infrastructure-for-code/)
1. [DevOps for doubters: How to deal with 9 kinds of people who push back](https://enterprisersproject.com/article/2019/7/devops-for-doubters-9-tips)

## People

[DevOps for introverted people](https://opensource.com/article/19/7/devops-introverted-people) — "We asked the Opensource.com DevOps team to talk about their experience as DevOps introverts and to give DevOps extroverts some advice. Here are their answers." Dan Barker, Catherine Louis, Abhishek Tamrakar, Elizabeth Joseph, and I were all quoted in this piece. It turned out *really* good.

[Here are the most popular programming languages used by the world's largest unicorn startups](https://www.geekwire.com/2019/popular-programming-languages-used-worlds-largest-unicorn-startups/) — If you're looking to pick up a new language, maybe start with this list.

[The case for making the transition from sysadmin to DevOps engineer](https://opensource.com/article/19/7/devops-vs-sysadmin) — "There's a learning curve, but there's no time like the present to get started."

[Five Things Developers Can Use to Go On-Call (And Not Hate Their Life)](https://channel9.msdn.com/Shows/5-Things/Five-Things-Developers-Can-Use-to-Go-On-Call-And-Not-Hate-Their-Life)

[Emotional exhaustion](https://en.wikipedia.org/wiki/Emotional_exhaustion) — It's a real thing.

[Opioid rules reassessed amid outcry from patients needing painkillers](https://www.usatoday.com/story/news/health/2019/07/12/opioid-rules-reassessed-amid-outcry-patients-needing-painkillers/1705026001/) — Too often when a few people get together and think they're doing the right thing, they're harming another group of people. The changes to opioid laws of late have definitely increased the difficulty level on life for me and undoubtedly countless others. Make high impact decisions in public, please.

## Process

[No Slacking: Microsoft Teams Announces 13M DAUs, Mattermost Raises At Rapid Clip](https://news.crunchbase.com/news/no-slacking-microsoft-teams-announces-13m-daus-mattermost-raises-at-rapid-clip/) — Microsoft Teams is so great that numerous teams at Microsoft flat out don't use it. The edict from on high mentioned a few weeks ago to force folks out Microsoft products? Apparently, it had no teeth. Sadly there will be no getting away from Teams if you're an Office 365 company it appears (hard to beat free). Mattermost CEO, Ian Tien, [tweeted in relation to this story](https://twitter.com/iantien/status/1150031555256913920), "Messaging Collaboration is a $30B market—as big as email and web conferencing—with 3 key segments: First mover (Slack), incumbent (Microsoft Teams), and open source (Mattermost). Open source offers trust, flexibility and innovation like no other. Let's see what happens next :)"

[Canonical Ltd source code repositories have been compromised](https://news.ycombinator.com/item?id=20369902) — "We can confirm that on 2019-07-06 there was a Canonical owned account on GitHub whose credentials were compromised and used to create repositories and issues among other activities. Canonical has removed the compromised account from the Canonical organisation in GitHub and is still investigating the extent of the breach, but there is no indication at this point that any source code or PII was affected."

[Seriously, stop using RSA](https://blog.trailofbits.com/2019/07/08/fuck-rsa/) — Originally titled, "Fuck RSA", this article pulls no punches. "RSA is an intrinsically fragile cryptosystem containing countless foot-guns which the average software engineer cannot be expected to avoid."

[Crypto-Mining Malware Outsmarting Image Scanners](https://blog.aquasec.com/crypto-mining-malware-container-security) — It's interesting to see everyone's fears about sharing Vagrant images come to fruition with containers. You don't need the whole OS to compromise a line of code (or infrastructure as code).

[Elastic CEO says Amazon Web Services isn't slowing down its business](https://www.businessinsider.com/elastic-shay-banon-amazon-web-services-elasticsearch-2019-7) — I'm a little worried about Elastic but, it doesn't seem the folks there are. To be honest, I'm worried about any company that has to monkey around with open source licensing to protect their business model, Elastic or otherwise.

[Details of the Cloudflare outage on July 2, 2019](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/) — I've moved almost all of my web sites off Cloudflare's CDN (hello new regions of the world!) but, their DNS lookup times are top-notch. This was a mess due to a configuration change. Guess what? Everyone tests in Prod.

[Blue Matador Closes $3.1 Million in Seed Funding to Transform Cloud Infrastructure Monitoring](https://finance.yahoo.com/news/blue-matador-closes-3-1-150000613.html) — Congrats to my friends over at Blue Matador!

[A Very Cold Take on IBM, Red Hat and Their Hybrid Cloud Hyperbole](http://www.platformonomics.com/2019/07/a-very-cold-take-on-ibm-red-hat-and-their-hybrid-cloud-hyperbole/) — Maybe a somewhat hyperbolic take on hybrid cloud hyperbole.

## Tools

[Fire Up Your VMs with Weave Ignite](https://www.weave.works/blog/fire-up-your-vms-with-weave-ignite) — "Weave Ignite is an open source VM with a container UX and built-in GitOps management. [It] combines AWS Firecracker MicroVMs with Docker / OCI images to unify containers and VMs. [It] Works in a GitOps fashion and can manage VMs declaratively and automatically like Kubernetes and Terraform."

[Developers don't understand CORS](https://fosterelli.co/developers-dont-understand-cors) — CORS is something I'm *guaranteed* to RTFM before even thinking about touching anything remotely close to cross origin related. The security implications are too high.

[Kubernetes productivity tips and tricks](https://www.padok.fr/en/blog/kubernetes-productivity-tips) — "Here's are Kubernetes tips and tricks to code and deploy faster."

[9 Steps to Awesome with Kubernetes](https://learning.oreilly.com/live-training/courses/9-steps-to-awesome-with-kubernetes/0636920283713/) — Live Training from fellow Red Hatter, Burr Sutter. "For Developers, learn nine simple and practical steps that will take you from Kubernetes novice to cloud native application architect."

[Dissecting the HAProxy Kubernetes Ingress Controller](https://www.haproxy.com/blog/dissecting-the-haproxy-kubernetes-ingress-controller/)

[Terraform: Up & Running, 2nd edition Early Release is now available!](https://blog.gruntwork.io/terraform-up-running-2nd-edition-early-release-is-now-available-b104fc29783f?gi=95020ed22d5) — I know a lot of folks have been waiting very patiently for this.

[A ~~simple~~ example of git bisect command](https://www.pixelstech.net/article/1562942424-A-simple-example-of-git-bisect-command) — I don't think any solution to a problem as complex doing anything in git history should be called "simple" but, maybe that's just me.

[There's more than one way to write an IP address](https://ma.ttias.be/theres-more-than-one-way-to-write-an-ip-address/) — All the fun ways to type an IP on the Linux CLI.

[The Illustrated TLS Connection: Every Byte Explained](https://tls.ulfheim.net/)

[Ramblings from Jessie: Linux Observability with BPF](https://blog.jessfraz.com/post/linux-observability-with-bpf/) — Jessie Frazelle wrote the foreword to an upcoming book on BPF.

[Announcing AWS Toolkit for Visual Studio Code](https://aws.amazon.com/blogs/developer/announcing-aws-toolkit-for-visual-studio-code/) — AWS Serverless Application Model (AWS SAM) focused extension for VSCode

[EKSphemeral](https://eksphemeral.info/) — "Meet EKSphemeral, the simple manager for ephemeral EKS clusters, allowing you to launch EKS clusters that auto-tear down after some time, and you can also prolong their lifetime if you want to continue to use them."

[Announcing Docsy: A Website Theme for Technical Documentation](https://opensource.googleblog.com/2019/07/announcing-docsy-website-theme-for.html)

[crashloopbackoff.dev](https://crashloopbackoff.dev) — How to describe CrashLoopBackOff in a way people understand (maybe ImagePullBackOff more accurately though).

[knadh/listmonk](https://github.com/knadh/listmonk) — High performance, self-hosted newsletter and mailing list manager with a modern dashboard (as the maintainer of a newsletter, I'm VERY interested in this project)

[stakater/Reloader](https://github.com/stakater/Reloader) — A Kubernetes controller to watch changes in ConfigMap and Secrets and then restart pods for Deployment, StatefulSet, DaemonSet and DeploymentConfig – [✩Star] if you're using it!

[hjacobs/kube-ops-view](https://github.com/hjacobs/kube-ops-view) — Kubernetes Operational View - read-only system dashboard for multiple K8s clusters

[dropbox/goebpf](https://github.com/dropbox/goebpf) — Library to work with eBPF programs from Go

[edgelevel/lastpass-operator](https://github.com/edgelevel/lastpass-operator) — A Kubernetes Operator to manage secrets stored in LastPass password manager

[paypal/hera](https://github.com/paypal/hera) — Hera multiplexes connections for MySQL and Oracle databases. It supports sharding the databases for horizontal scaling.

[chris-short/DevOps-README.md](https://github.com/chris-short/DevOps-README.md) — What to Read to Learn More About DevOps

[poseidon/typhoon](https://github.com/poseidon/typhoon) — Minimal and free Kubernetes distribution

Notes from this week's issue can be found [here](./notes/).
