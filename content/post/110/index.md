+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-01-13T07:00:00Z
description = "Weaveworks Flagger, DevOps Leaving Ops Behind, AWS 🖕 OSS, Kubernetes Galore, and More"
draft = false
slug = "110"
tags = ["kubernetes", "docker", "devops", "open source", "cloud", "tech", "software", "github", "cloud native", "ansible", "aws", "linux"]
title = "110: Weaveworks Flagger, DevOps Leaving Ops Behind, AWS 🖕 OSS, Kubernetes Galore, and More"

+++

This week I ran an unscientific Twitter poll asking, "Has DevOps left Ops behind?" It was a question that came up during a discussion with one of my  co-workers.

{{< tweet 1082767409595977729 >}}

There will be more discussion and thought around this for sure. But, it appears the software industry has gotten ahead of the skillsets of the majority of folks in it. Think about it though. We went from containers going mainstream via Docker in 2014 to Kubernetes going mainstream in 2017. Now it's 2019 and we're talking about Istio, serverless, and eBPF. If it seems like the pace of change is accelerating, it's because it is.

In Thomas L. Friedman's [*Thank You For Being Late: An Optimist's Guide to Thriving in the Age of Accelerations*](https://amzn.to/2SSD4mr) a graph is drawn by Google X's Eric "Astro" Teller like this one here.

![Technology is outpacing human adaptability](/110/Thank_You_graph_04a.9_fmt.jpg)

Friedman goes on to explain that the roles of education and government today should be to figure out how to lift the line of human adaptability to be able to keep pace with technology.

{{< youtube GyZHySRUKXI >}}

This sounds familiar... It's no surprise that we in tech have been trying to do exactly this for years in tech with things like DevOps and SRE (and many things before that). I think the fact we've created "things" (DevOps, SRE, Agile, Lean, etc.) to help us adapt to change faster shows a clear sign the technology is outpacing human capacity to adapt to it. So what do we do about it? Looks like that's the big question here.

[**O'Reilly Software Architecture Conference NY 25% off**](http://www.oreilly.com/pub/cpc/187994)  
Save 25% on your Gold, Silver, or Bronze pass to the O’Reilly Software Architecture Conference in New York next month. Register using the code **PCDEVOPSISH**. Explore complex software architecture topics, learn best practices from industry experts, and exchange ideas and insights with your peers. [Register Now](http://www.oreilly.com/pub/cpc/187994) *SPONSORED*

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

{{< sponsor-blurb >}}

## Last Week's Top Five

1. [18 people in tech every programmer and software engineer needs to follow in 2019](https://hub.packtpub.com/18-people-in-tech-every-programmer-and-software-engineer-needs-to-follow-in-2019/)
2. [DevOps engineer interviews: Ask these questions](https://enterprisersproject.com/article/2018/12/hiring-devops-engineer-ask-these-questions)
3. [Hashicorp at Home](https://www.mockingbirdconsulting.co.uk/blog/2019-01-05-hashicorp-at-home/)
4. [On leaving Chef](https://www.juliandunn.net/2019/01/04/on-leaving-chef/)
5. [7 CI/CD tools for sysadmins](https://opensource.com/article/18/12/cicd-tools-sysadmins)

I'm going to add this new top five from the previous newsletter. Hit reply and tell me what you think.

## People

[2018 and what’s to come in 2019](https://kimmcmahon.me/2018-and-whats-to-come-in-2019/) — My dear friend, **Kim McMahon**, wrote a great recap of her 2018, which started with the {code} team shuttering and being unemployed to becoming Senior Director of Digital Strategy at Cloud Foundry Foundation (CFF). A great read because it crosses over so many facets of the tech industry.

[Kolton Andrus, Gremlin Inc on On-Call Nightmares Podcast](https://www.podomatic.com/podcasts/oncallnightmares/episodes/2019-01-10T07_28_49-08_00) — Kolton is the CEO of chaos engineering firm Gremlin, Inc.

{{< adsense-inarticle >}}

[Jenn's Guide to Thriving in Tech](https://dev.to/geekgalgroks/jenns-guide-to-thriving-in-tech-4k91) — A well-rounded list of things to do to be successful in tech. One thing I need to work on is time boxing research.

[Mainframe brains-slurper sues IBM for 'age discrim', calls Ginny and biz 'morally bankrupt'](https://www.theregister.co.uk/2019/01/07/ibm_age_discrimination_lawsuit/) — This is disturbing to me because I think we all knew it was happening. But, no one could really do anything about it at the time.

[I'm a Red Hat Certified Specialist: Ansible Automation](https://chrisshort.net/im-a-red-hat-certified-specialist-ansible-automation/) — I did a thing because I felt I had something to prove.

## Process

[oss-security - System Down: A systemd-journald exploit](https://www.openwall.com/lists/oss-security/2019/01/09/3) — Patch all the 🍑

[Production Guideline](https://medium.com/@rakyll/production-guideline-9d5d10c8f1e) — JBD gives us an absolutely fantastic list of things to go through before making it to production.

[IBM Began Buying Red Hat 20 Years Ago](https://www.linuxjournal.com/content/ibm-began-buying-red-hat-20-years-ago)

{{< adsense-inarticle >}}

[Cloud Native Apps Need to be Managed in a Completely New Way](https://thenewstack.io/cloud-native-apps-need-to-be-managed-in-a-completely-new-way/) — Always be shifting left.

[AWS gives open source the middle finger](https://techcrunch.com/2019/01/09/aws-gives-open-source-the-middle-finger/) — Boy did AWS ever show all the license zealots out there how quickly their war was gonna last.

[China Is Shooting Itself in the Foot Over Huawei](https://foreignpolicy.com/2019/01/07/china-is-shooting-itself-in-the-foot-over-huawei/) — I get it, Huawei is important to China. But, it's getting to a point where folks are going to think twice regardless.

[What is DevSecOps?](https://opensource.com/article/19/1/what-devsecops) — A nice, lightweight eBook on DevSecOps from opensource.com.

## Tools

[Weaveworks Flagger](https://flagger.app/) — "Flagger is a Kubernetes operator that automates the promotion of canary deployments using Istio routing for traffic shifting and Prometheus metrics for canary analysis." [Flagger Slide Deck](https://www.slideshare.net/weaveworks/flagger-istio-progressive-delivery-operator)

[Why Is Storage On Kubernetes So Hard?](https://softwareengineeringdaily.com/2019/01/11/why-is-storage-on-kubernetes-is-so-hard/) — Storage is not trivial. Storage on Kubernetes is harder.

[How Tilt updates Kubernetes in Seconds, not Minutes](https://medium.com/windmill-engineering/how-tilt-updates-kubernetes-in-seconds-not-minutes-28ddffe2d79f) — Tilt is kinda in the same vein as Skaffold. It's a high-speed Kubernetes deployment/development tool. It introduces something they've dubbed a Synclet (a sidecar) that enables easy reuse of existing pods in Kubernetes as opposed to tearing the pod down, rebuilding it, and relaunching the containers in it. Pretty cool looking (I have not kicked the tires on it).

[5 open source tools to upgrade your next Kubernetes project](https://jaxenter.com/5-kubernetes-open-source-tools-154333.html) — Tilt, Rook, Rancher, and Fission (I'd say [OpenFaaS](https://www.openfaas.com/))

[Kubernetes Authorization via Open Policy Agent](https://itnext.io/kubernetes-authorization-via-open-policy-agent-a9455d9d5ceb) — RBAC isn't the only auth tool in the Kubernetes world. "This blog post explains how to implement advanced authorization policies via Open Policy Agent (OPA) by leveraging the Webhook authorization module."

[Adventures with a home Kubernetes cluster](https://blog.marshallbrekka.com/post/2019-01-05/home-kubernetes-cluster/) — There's more than one way to run Kubernetes, on ARM, in your house.

[Scaling Jupyter notebooks with Kubernetes and Tensorflow](https://learnk8s.io/blog/scaling-machine-learning-with-kubeflow-tensorflow)

{{< adsense-inarticle >}}

[How to set up a Let's Encrypt SSL Cert for Azure Web App with Linux in 5 steps](https://jessicadeen.com/how-to-manually-setup-a-lets-encrypt-ssl-cert-for-azure-web-app-with-linux/) — "Have you ever wondered how you take a free Let's Encrypt Certificate and use it with an Azure Web App (Linux)? This post is for you!"

[Google Adds DNS-over-TLS Support to Its Public DNS Service](https://www.bleepingcomputer.com/news/google/google-adds-dns-over-tls-support-to-its-public-dns-service/) — This will come in handy.

[Picking communication tools for your community](https://funnelfiasco.com/blog/2019/01/07/picking-communication-tools-for-your-community/) — I talked way too much about community tools this week. Sadly, no one tool is going to work for everyone, ever. But, there is a tool that meets the needs of most folks. This is why Jenkins is still a thing. ¯\\\_(ツ)\_/¯

[New year, new GitHub: Announcing unlimited free private repos and unified Enterprise offering](https://blog.github.com/2019-01-07-new-year-new-github/) — Free private repos with up to three contributors. That's great but, GitHub Actions is what I'm really hoping will get better.

[GitHub now offers free private repos for up to three collaborators – here are our thoughts](https://about.gitlab.com/2019/01/07/github-offering-free-private-repos-for-up-to-three-collaborators/) — Here's what GitLab thinks of GitHub giving folks free private repos.

[8 Productivity Tips for GitHub](https://dev.to/_darrenburns/8-productivity-tips-for-github-44kn) — I'm starting to get better about GitHub notifications, workflows, etc. I have a confession to make, I didn't know what version control software was until 2011 and then it was svn. I was anti git until a few years ago. I know how to use git but, GitHub requires its own set of tools to manage.

[Git Explorer](https://gitexplorer.com/) — Find the right commands you need without digging through the web.

{{< adsense-inarticle >}}

[A YubiKey for iOS Will Soon Free Your iPhone From Passwords](https://www.wired.com/story/yubikey-lightning-ios-authentication-passwords/) — iOS will need some work to make this happen. But, I literally can't wait to be done with passwords.

[Update Elastic Stack with Ansible Playbooks](https://www.toptal.com/ansible/update-elastic-stack-ansible-playbooks)

[Bash-5.0 release available](http://lists.gnu.org/archive/html/bug-bash/2019-01/msg00063.html) — Some new bits for bash.

[How to Monitor a Website's Uptime for $0.75/month on Amazon](https://danielmiessler.com/blog/how-to-monitor-a-website-for-0-75-month-on-amazon/) — Since [Pingdom is pulling the plug on their free monitoring](https://www.reddit.com/r/devops/comments/adjhmd/pingdom_discontinues_their_free_plan/), here's a reasonably priced AWS Route53 alternative. There's also [UptimeRobot](https://uptimerobot.com/) which has a great free plan and reasonably priced entry tier.

[Introduction to eBPF in Red Hat Enterprise Linux 7](https://www.redhat.com/en/blog/introduction-ebpf-red-hat-enterprise-linux-7) — eBPF, y'all.

[What's New in Ansible Tower 3.4](https://www.ansible.com/blog/whats-new-in-ansible-tower-3.4) — "We're most excited about workflows enhancements, job slices, and some other nifty features." Here's [an interview with one of my all time fav PMs, Bill Nottingham](https://devops.com/red-hat-adds-support-for-nested-workflows-to-ansible-automation-framework/), about this release.

{{< adsense-inarticle >}}

[Courier: Dropbox migration to gRPC](https://blogs.dropbox.com/tech/2019/01/courier-dropbox-migration-to-grpc/)

[mkcert: valid HTTPS certificates for localhost](https://blog.filippo.io/mkcert-valid-https-certificates-for-localhost/)

[Metasploit Framework 5.0 Released](https://blog.rapid7.com/2019/01/10/metasploit-framework-5-0-released/) — I love me some Metasploit.

[1.9.0 — Homebrew](https://brew.sh/2019/01/09/homebrew-1.9.0/) — "Homebrew 1.9.0 has beta support for Linux and Windows 10" YES!!! One step closer to having one Ansible Playbook for all my boxes!!!

## DevOps'ish Tweet of the Week

{{< tweet 1083415010913775617 >}}