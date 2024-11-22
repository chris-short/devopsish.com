+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-08-08
description = ["Kubernetes 1.22, KubeCon schedule announced, security fails abound, Zoom's paltry fine, finally death to 996, NSA Kubernetes Hardening Guidance, and much more"]
draft = false
slug = "229"
tags = ["Kubernetes", "code", "DevOps", "KubeCon", "tech", "news", "cloud native", "containers", "Amazon", "DNS", "security", "infrastructure", "policy", "engineering", "reliability", "time", "time", "HTTP2", "Windows", "servers", "Terraform", "pod", "controller", "release", "GitHub", "SRE", "rootless containers", "privacy", "996", "GitOps", "Solarwinds", "Intel", "Tekton", "ArgoCD", "Sourcegraph", "docker-compose", "Kompose", "Google", "Apple", "backdoor", "Microsoft", "open source", "hard drive", "GPS", "Git", "developers", "AWS", "UX", "VirtualBox", "macOS", "Linux"]
title = "DevOps'ish 229: Kubernetes 1.22, KubeCon schedule announced, security fails abound, Zoom's paltry fine, finally death to 996, NSA Kubernetes Hardening Guidance, and much more"

+++

Kubernetes 1.22 shipped this week. I suggest you, at a minimum, read the [release blog post](https://kubernetes.io/blog/2021/08/04/kubernetes-1-22-release-announcement/) or take a gander at the [CHANGELOG](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.22.md) and definitely read the [No, really, you MUST read this before you upgrade](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.22.md#no-really-you-must-read-this-before-you-upgrade). Some of the bigger changes:

* Audit log files are created with mode 0600 (owner read-only)
* Rootless mode containers moving to alpha: In my opinion, if you use Podman, you're used to this. If you're not, you should be using rootless containers intentionally for security reasons (more on that later).
* Cgroupsv2 moving to alpha
* Pod Security Policy replacement (aka Pod Security Admission Controller): Yes, [PSPs are deprecated](https://devopsish.com/205/) and being replaced. [There are a lot of reasons why](https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/).
* LoadBalancer moving to beta
* Enable seccomp by default
* and a whole bunch more

KubeCon NA 2021 acceptances went out this week and [the schedule is live](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/program/schedule/). I'm excited to say I'm teaming up with [Kaslin Fields](https://twitter.com/kaslinfields), [Bart Farrell](https://twitter.com/birthmarkbart), [Matthew Broberg](https://twitter.com/mbbroberg), and [Kunal Kushwaha](https://twitter.com/kunalstwt) for [a panel talk](https://kccncna2021.sched.com/event/lV3S) about what we've been doing in the [Kubernetes Upstream Marketing Team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) (which includes the [@K8sContributors](https://twitter.com/K8sContributors/) Twitter handle and so much more).

A note about KubeCon: I want everyone that might be speaking at a Day 0 event or trying to get to KubeCon to know that if anyone needs financial support, please apply for a scholarship, either diversity or needs-based here: <https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/attend/scholarships/>

## People

[Apple's Plan to "Think Different" About Encryption Opens a Backdoor to Your Private Life](https://www.eff.org/deeplinks/2021/08/apples-plan-think-different-about-encryption-opens-backdoor-your-private-life)  
Now we enter life with one of the top phone makers having a backdoor into the private lives of its consumers. I can't wait until pictures of Max in the bathtub somehow leading to a search warrant. I have a feeling this isn't going to go well at all for any of us.

[A Non-Tech Explanation of Containers and Kubernetes](https://www.linode.com/content/declarative-cloud-infrastructure-management-terraform-linode/?utm_source=tldr&utm_medium=newsletter_sponsorship&utm_campaign=newsletter_sponsorship-tldr-terraform&utm_content=ebook-terraform&utm_term=)  
100 Million Downloads and Over 5,000 Ecosystem Add-Ons later, Hashicorp has released the 1.0 version of Terraform.  This eBook and audiobook will help you understand the underlying concepts of this infrastructure as a code tool and how it can be a significant resource when your cloud infrastructure hits critical mass. *SPONSORED*

[Study reveals racial bias on GitHub](https://www.protocol.com/policy/github-race-bias-study)  
This should surprise no one. The IEEE breaks it down in a report titled, "On the Relationship Between the Developer's Perceptible Race and Ethnicity and the Evaluation of Contributions in OSS" [[PDF](https://arxiv.org/pdf/2104.06143.pdf)]

[Amazon now employs almost 1 million people in the U.S. — or 1 in every 169 workers](https://www.nbcnews.com/business/business-news/amazon-now-employs-almost-1-million-people-u-s-or-n1275539)  
This should be a big red flag for regulators to pick at.

[DevOps, SRE, and Platform Engineering](https://iximiuz.com/en/posts/devops-sre-and-platform-engineering/)  
Ivan Velichko breaks down what he sees as the differences between Development, DevOps, Site Reliability Engineering (SRE), and Platform Engineering.

[How to Talk About Your Mental Health with Your Employer](https://hbr.org/2021/07/how-to-talk-about-your-mental-health-with-your-employer)
Very, very carefully. I usually bring it up within a month of getting a new boss. Oh... I guess I need to have [this conversation](https://chrisshort.net/the-importance-of-psychological-safety/) again soon.

[Zoom will pay $85 million to settle lawsuit over privacy and 'zoombombing'](https://www.engadget.com/zoom-privacy-lawsuit-settlement-205427084.html)  
Zoom's market cap at time of writing is $112.989 *billion* (source [CNBC](https://www.cnbc.com/quotes/ZM)).

[We're in hottest job market for tech workers since dot-com era](https://www.bostonherald.com/2021/07/18/were-in-hottest-job-market-for-tech-workers-since-dot-com-era/)  
If you're not interviewing right now, you could be missing out.

[Playbook to Bust Bureaucracy](https://itrevolution.com/playbook-to-bust-bureaucracy/)  
This is a delightfully rebellious read.

[Why Chinese Big Tech no longer dares say '996'](https://www.protocol.com/china/china-996-overtime-era-ended)  
Long overdue. "Over the past two months, at least four Chinese tech giants have announced plans to cancel mandatory overtime; some of the changes are companywide, and others are specific to business units. ByteDance, Kuaishou and Meituan's group-buying platform announced the end of a policy called 'Big/Small Week,' where a six-day workweek is followed by a more moderate schedule. In early June, a game studio owned by Tencent rolled out a policy that mandated employees punch out at 6 p.m. every Wednesday and take the weekends off."

## Process

[HTTP/2: The Sequel is Always Worse](https://portswigger.net/research/http2)  
All the bad things (so far) about HTTP/2.

[Collaboration and Automation for Infrastructure as Code](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dymanic RBAC and quality of life features. Free Demo. *SPONSORED*

[NSA, CISA release Kubernetes Hardening Guidance](https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/)  
This is a big deal. The NSA guides are top-notch reference material. What’s one of the first pieces of guidance? Using non-root containers. There are good example YAMLs in the appendix as well. [PDF](https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/1/CTR_KUBERNETES%20HARDENING%20GUIDANCE.PDF)

[SolarWinds urges US judge to toss out crap infosec sueball: We got pwned by actual Russia, give us a break](https://www.theregister.com/2021/08/04/solarwinds_lawsuit_shareholders_motion_dismiss/)  
Solarwinds is saying that they're, "the victim of the most sophisticated cyberattack in history" and shouldn't be held liable for loss in marker value by its shareholders. It's a reasonable argument, but this is a pretty big precedent to set too.

[The summer Intel fell behind](https://www.theverge.com/22597713/intel-7nm-delay-summer-2020-apple-arm-switch-roadmap-gelsinger-ceo?scrolla=5eb6d68b7fedc32c19ef33b4)  
If you're a regular reader of this newsletter you knew that Intel's reckoning was coming. Well this year it finally happened. What comes next could make or break the chip maker.

## Tools

[Kubernetes CI/CD with Tekton and ArgoCD](https://piotrminkowski.com/2021/08/05/kubernetes-ci-cd-with-tekton-and-argocd/)  
Build and deploy with Tekton and ArgoCD with this incredibly detailed article.

[Search your code. ALL of it, everywhere.](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text)  
Imagine if you could search all your code across every repo, every language, every code host. You can with [Sourcegraph universal code search](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). Quickly navigate code with contextual hover tooltips that show definitions, references, and usage examples. Construct complex queries and filter code in ways that IDEs and code hosts can't. Find and fix code fast, without losing your flow. Sourcegraph universal code search is a dev's superpower. [Get it now](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). *SPONSORED*

[Docker Compose to Kubernetes: Step-by-Step Migration](https://loft.sh/blog/docker-compose-to-kubernetes-step-by-step-migration/)  
I always forget how useful [Kompose](https://kompose.io/) is at the beginning of a new project. "Kompose is a conversion tool for Docker Compose to container orchestrators such as Kubernetes (or OpenShift)."

[Amazon and Google patch major bug in their DNS-as-a-Service platforms](https://therecord.media/amazon-and-google-patch-major-bug-in-their-dns-as-a-service-platforms/)  
It's not all DNS's fault. "What the Wiz team discovered was that several managed DNS providers did not blacklist their own DNS servers inside their backends." Which means, you could easily hijack Amazon and Google's DNS servers to do basically anything you wanted to an unknowing victim or adversary. I reported on this last week but, this sheds a little more light on the subject.

[Microsoft halts Windows 365 trials after running out of servers](https://www.bleepingcomputer.com/news/microsoft/microsoft-halts-windows-365-trials-after-running-out-of-servers/)  
I'm not sure what this says about Windows, but I'm sure it isn't good.

[Hard Drive Reliability: A Look at HDD and SDD Failure Rates](https://www.backblaze.com/blog/backblaze-drive-stats-for-q2-2021/)  
Hard drive reliability is at a new peak. This report is fascinating.

[Deployment Strategies In Kubernetes](https://auth0.com/blog/deployment-strategies-in-kubernetes/)  
"Learn what are the different deployment strategies available in Kubernetes and how to use them."

[Postgres.app – the easiest way to get started with PostgreSQL on the Mac](https://postgresapp.com/)  
Neat!

[A GPSD time warp](https://lwn.net/SubscriberLink/865044/c7d4680c55526374/)  
If you're like me and have been a GPS consumer since before consumers got highly accurate GPS data, you probably understand how bad of a problem this is.

[New in Git: switch and restore](https://www.banterly.net/2021/07/31/new-in-git-switch-and-restore/)  
`git switch` is my new best friend.

[openshift/service-ca-operator](https://github.com/openshift/service-ca-operator)  
Controller to mint and manage serving certificates for Kubernetes services

[myspaghetti/macos-virtualbox](https://github.com/myspaghetti/macos-virtualbox)  
Push-button installer of macOS Catalina, Mojave, and High Sierra guests in Virtualbox for Windows, Linux, and macOS

[Tib3rius/AutoRecon](https://github.com/Tib3rius/AutoRecon)  
AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services.

[mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy)  
An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.

## DevOps'ish Tweet of the Week

I know AWS has a UX team. I don't know if AWS listens to their UX team though.

[![C:\hristina (@divinetechygirl) on Twitter: "Does AWS make AWS confusing on purpose or ¯\_(ツ)_/¯¯¯? Like you shouldn't have to study for a cert just to figure out how to do things in the UI 🤦🏽‍♀️ Please note: I do not need help and figured out how to do what I needed to do but it was definitely not straight forward."](https://shortcdn.com/devopsish/229-devopsish-tweet-of-the-week.png)](https://twitter.com/divinetechygirl/status/1422954646918864905)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/229/notes.md) to see what didn't make it to the newsletter but are still worth your time.
