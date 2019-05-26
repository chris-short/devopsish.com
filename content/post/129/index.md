+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-05-26T07:00:00Z
description = "Kubernetes Invades Barcelona, Summer Sanity Tips, Summer Survey, SuperGloo Makes Its Mark, Huawei Warm-up, Fake Agile, and More"
draft = false
slug = "129"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "container", "security", "linux", "infrastructure", "git", "GitHub", "survey", "summer", "huawei", "agile", "terraform", "Litmus", "AWS"]
title = "129: Kubernetes Invades Barcelona, Summer Sanity Tips, Summer Survey, SuperGloo Makes Its Mark, Huawei Warm-up, Fake Agile, and More"

+++

The end of May looms large on the horizon and a busy June is ahead for a lot of us. This is about that time of year I wish it were the holiday season. It's hot, people's patience wears down faster, and there is always something to do. Here are some tips for the days ahead:

1. Remember to pace yourself; you don't have to live a full life every day.
2. Remember to be kind; you have no idea if the person standing next to you in line at the airport is going on vacation or to a funeral. This is why my typical response when interacting with folks in a customer service capacity is, "Thank you very much!" So rare is appreciation for their work shown directly to them. A little kindness goes a long way and the good news is, everyone has within them the capacity to have infinite kindness.
3. But, don't be a doormat, please. Also, if you're sweaty af don't hug me; it's June you filthy carbon based life forms.

I'll be in Durham, NC 28-30 May and Raleigh 3-7 June. If you want to get together in the coming weeks, let me know. Stay safe out there and don't forget to drink water.

> [**DevOps'ish Summer 2019 Survey**](https://devopsi.sh/survey): Please take this year's survey. It is a handful of questions, will provide actionable feedback, and be greatly appreciated. The intent is to improve the overall experience and value this newsletter provides to its readers ([don't believe me?](https://devopsish.com/088/)). Thank you in advance, y'all!

## DevOps'ish Last Week's Top Five

1. [DevOps salaries: 10 statistics to see](https://enterprisersproject.com/article/2019/5/devops-jobs-salaries-10-statistics)
1. [Improve your Dockerfile, ~~best~~ practices](https://dev.to/azure/improve-your-dockerfile-best-practices-5ll)
1. [Saying goodbye to Microsoft](https://medium.com/@alicjaes/saying-goodbye-to-microsoft-bb5db8662656)
1. [Introducing Terraform Cloud Remote State Management](https://www.hashicorp.com/blog/introducing-terraform-cloud-remote-state-management)
1. [Comparison of Kubernetes Top Ingress Controllers](https://caylent.com/kubernetes-top-ingress-controllers/)

## People

[AnsibleFest 2019 Call for Proposals](https://ansiblefest2019.eventpoint.com/cfp/?utm_source=devopsish) — Are you adding value to your organization using Ansible? Perhaps you have automated your way out of a sticky situation before with Ansible? Have you scaled an organizations automation efforts with Ansible Tower? [Submit a proposal to AnsibleFest 2019!](https://ansiblefest2019.eventpoint.com/cfp/?utm_source=devopsish)

[Facebook Salaries and Levels](https://www.levels.fyi/salary/Facebook/) — Facebook pays well. But, how long is that going to last?

[The three Rs of remote work](https://dave.cheney.net/2019/05/19/the-three-rs-of-remote-work) — Little, Big, and Gothic Rs from The Dave Cheney

[Q&A: AWS 'container czarina' Abby Fuller weighs in on Kubernetes excitement](https://siliconangle.com/2019/05/21/qa-amazon-container-czarina-weighs-kubernetes-excitement-kubeconeu/) — Abby Fuller played defense for AWS community involvement. Rough. It's not always about flash and swag. Sometimes there are folks that have to get shit done.

[What Anxiety Does to Us at Work](https://hbr.org/2019/05/what-anxiety-does-to-us-at-work) — My week is summed up in this one HBR article.

[DevOps'ish Telegram](https://devopsi.sh/telegram) — Join the 300+ DevOps, Kubernetes, SRE, and other technology professionals discussing real-world problems, breaking technology events and outages, and the occasional Spotify playlist.

## Process

[**2019 State of Multicloud**](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) — A Report on the Underlying Dynamics Fueling Multicloud Strategies. [Download Today!](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) *SPONSORED*

[Understanding Fake Agile](https://www.forbes.com/sites/stevedenning/2019/05/23/understanding-fake-agile/#1b2af1d44bbe) — All the various forms in which Agile is implemented. Some just wrong, some work for some organizations, and others are indeed fake agile.

[Auth0 Closes $103M in Funding, Passes $1B Valuation](https://auth0.com/blog/auth0-closes-103m-in-funding-passes-1b-valuation/) — Congrats to the folks at Auth0! 👏🎉🍾🥂

[Amazon Has An Incredible New Way To Fight Walmart. It's Both Brilliant and Very Sad](https://www.inc.com/chris-matyszczyk/amazon-new-way-to-fight-walmart-its-both-brilliant-very-sad.html) — "Amazon is now moving into derelict malls... It's delicious in its strategic intentionality. It's the perfect way to ramp up Amazon's promise to make one-day delivery the norm."

[Linux Foundation Statement on Huawei Entity List Ruling](https://www.linuxfoundation.org/blog/2019/05/linux-foundation-statement-on-huawei-entity-list-ruling/) — Open source work has a special exclusion from Export Administration Regulation like the one being applied to Huawei. "Open source software, collaboration on open source code, attending telephonic or in person meetings, participating in training and providing membership or sponsorship funds are all activities which are not subject to the EAR and therefore should have no impact on our communities."

[RIP Hyper-Threading? ChromeOS axes key Intel CPU feature over data-leak flaws – Microsoft, Apple suggest snub](https://www.theregister.co.uk/2019/05/14/intel_hyper_threading_mitigations/) — I mentioned it earlier this week but, I'm legit thinking of switching to an ultra lightweight, 4 (actual) Core PC running Fedora because of the performance my 2018 MacBook Air has taken. There were shortcuts in keeping up with Moore's Law and our backs and wallets are going to pay the price for it. I'm open to suggestions for a new daily driver. But, it needs to comparable in weight to a MacBook Air (and not Huawei; more on that in next week's newsletter).

## Tools

[**How companies adopt and apply cloud native infrastructure--from O'Reilly**](https://www.oreilly.com/pub/cpc/224549) — Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud. *SPONSORED*

[A Practical kubernetes Operator using Ansible — an example](https://itnext.io/a-practical-kubernetes-operator-using-ansible-an-example-d3a9d3674d5b) — My friend and fellow Red Hatter, Jamie Duncan walks us through a variety of scenarios for using Ansible with Kubernetes Operators. Pretty awesome article.

[Providing chaos hooks to applications through Litmus Operator](https://medium.com/mayadata/litmus-chaos-operator-the-whys-hows-10a4519ad864) — "Litmus operator allows developers and DevOps architects introduce chaos into the applications and Kubernetes infrastructure in a declarative intent format, in other words — the Kubernetes way." Litmus is really cool, y'all. I also owe the folks at MayaData some hands on time with it (and a blog post). The donkey should come hold me hostage here in my office one day. It can help me too but, it has to stay in character.

[Hardening Prometheus and OpenEBS using Litmus](https://medium.com/mayadata/hardening-prometheus-and-openebs-using-litmus-143db2af59fb) — Yea, Litmus, y'all.

[Humio Unveils Scalability Benchmark Running 100 Terabytes A Day In Real-Time](https://finance.yahoo.com/news/humio-unveils-scalability-benchmark-running-070000942.html) — Humio's [Scalability Benchmark](https://info.humio.com/scalability-benchmark) boasts 100TB/Day of observability. Whatever that means. ¯\\\_(ツ)\_/¯

[What sucks about GitLab?](https://www.reddit.com/r/devops/comments/br4vui/what_sucks_about_gitlab/) — I'm sure there's something to learned here. Maybe we should stop assuming positive questions get the answers we want? 🤔🤔🤔

[The need for a standard, service mesh API](https://medium.com/solo-io/the-need-for-a-standard-service-mesh-api-d89be65f8fb3) — Ushering in the answer to, "Okay, I need a service mesh. Now which one?" It's great that this need was addressed so quickly.

[systemctl enable sysadmin: Welcome to Enable Sysadmin](https://www.redhat.com/sysadmin/welcome) — One of Red Hat's latest projects is geared directly towards sysadmins (and I may or may not have something to do with it).

[Cloudflare architecture and how BPF eats the world](https://blog.cloudflare.com/cloudflare-architecture-and-how-bpf-eats-the-world/) — "It seems, no matter the question - BPF is the answer."

[Part II: Why Is There No Docker in OpenShift 4 and RHEL 8?](http://crunchtools.com/why-no-docker/) — The business reasons alone are enough. Let alone the technical

[Announcing Terraform 0.12](https://www.hashicorp.com/blog/announcing-terraform-0-12) — I first heard about Terraform 0.12 around this time last year. It has been a lot of work. Congrats to the Terraform team!

[Using HashiCorp Sentinel to validate Terraform configuration/plan](https://atodorov.me/2019/05/23/using-hashicorp-sentinel-to-validate-terraform-configuration/plan/)

[Hardware bootstrapping with Ansible](https://opensource.com/article/19/5/hardware-bootstrapping-ansible) — DHCP, PXE, and TFTP oh my!

[Kubernetes Log Management: The Basics](https://www.bluematador.com/blog/kubernetes-log-management-the-basics) — "By the end of this post, you should have a good high level understanding of the essential concepts for logging with Kubernetes, and should be ready to begin implementing it for your cluster and logging use case."

[What is a fork, really, and how GitHub changed its meaning](https://drewdevault.com/2019/05/24/What-is-a-fork.html)

[5 Best Keyboards for 2019 (Cheap, Gaming, Mechanical)](https://www.wired.com/gallery/best-keyboards/) — YMMV

[workshops/README.ja.md at master · ansible/workshops](https://github.com/ansible/workshops/blob/master/exercises/ansible_f5/1.0-explore/README.ja.md) — Japanese translations to Ansible workshops are now available.

[instrumenta/conftest](https://github.com/instrumenta/conftest) — Write tests against structured configuration data using the Rego query language

[gardener/gardener](https://github.com/gardener/gardener) — Kubernetes API server extension and controller managing the full lifecycle of conformant Kubernetes clusters as a service on Alicloud, AWS, Azure, GCP, and OpenStack with minimal TCO.

[felipellrocha/pensieve](https://github.com/felipellrocha/pensieve) — Creates a development environment within a Kubernetes cluster by replacing one of your deployments with a docker container built for development, and gives you back a shell you can run any commands you'd like.

[alauda/kube-ovn](https://github.com/alauda/kube-ovn) — An OVN-based Kubernetes Network Fabric for Enterprises

## DevOps'ish Tweet of the Week

{{< tweet 1131584970194018304 >}}