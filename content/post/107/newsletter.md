+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-12-23T12:45:00Z
description = "KubeCon Recap, Larry Ellison, China Hacking, Kubernetes Security, and More"
draft = false
slug = "107"
tags = ["weekly", "devops", "newsletter", "cloud native", "cloud", "open source", "kubernetes", "automation", "red hat", "ansible", "security", "serverless", "container", "UEFI", "China", "Site Reliability Engineering", "SRE"]
title = "107: KubeCon Recap, Larry Ellison, China Hacking, Kubernetes Security, and More"
+++

As mentioned [last week](https://devopsish.com/106/), I was able to finish [my KubeCon + CloudNativeCon NA 2018 recap](https://chrisshort.net/kubecon-cloudnativecon-na-2018/) this week. It's not an exhaustive list of things I did but, it covers the big ones. One point of emphasis for me was to assess the physical toil I managed along the way. It's important to note that life doesn't stop because you're at a conference. [Videos from the Kubernetes Contributor Summit are now available](https://discuss.kubernetes.io/t/videos-from-the-kubernetes-contributor-summit-are-now-available/3907) too.

I'm on PTO this week. I thought about DevOps'ish taking its first week off ever. But, I don't think that's necessary so here's to over two years of uninterrupted [DevOps'ish](https://devopsish.com/)!

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*


## People

[The Mom Project, a job site for moms returning to work, nabs $8M from Initialized and more](https://techcrunch.com/2018/12/17/the-mom-project-a-job-site-for-moms-returning-to-work-nabs-8m-from-initialized-and-more/)

[Google's Secret China Project "Effectively Ended" After Fight](https://theintercept.com/2018/12/17/google-china-censored-search-engine-2/) — Well... That's done.

[Oracle's Ellison: No way a 'normal' person would move to AWS](https://www.zdnet.com/article/oracles-ellison-no-way-a-normal-person-would-move-to-aws/) — Because Larry Ellison knows so much about "normal" people.

[How to become an AWS expert](https://aws.amazon.com/blogs/aws/how-to-become-an-aws-expert/) — Because being an AWS expert will serve you far better than being an Oracle expert.

[Gladys West, the 'hidden figure' of GPS, inducted into Air Force hall of fame](https://thehill.com/blogs/blog-briefing-room/news/422353-dr-gladys-west-the-hidden-figure-of-gps-inducted-into-air-force)

[Lawmakers push to create a three-digit suicide hotline number](https://techcrunch.com/2018/12/17/lawmakers-push-to-create-three-digit-suicide-phone-line/) — Nice to see this happening.

[Moving on From Red Hat](http://blog.christianposta.com/moving-on-from-red-hat/) — Christian Posta is leaving Red Hat 😕

[Burnout, stress lead more companies to try a four-day work week](https://www.reuters.com/article/us-world-work-fourdayweek-idUSKBN1OG0GY) — That's not going to help me I don't think (see Tweet of the Week from [last week](https://devopsish.com/106/)).

## Process

[We need Sustainable Free and Open Source Communities](https://medium.com/sustainable-free-and-open-source-communities/we-need-sustainable-free-and-open-source-communities-edf92723d619)

[Reuters Exclusive: China hacked HPE, IBM and then attacked clients](https://www.reuters.com/article/us-china-cyber-hpe-ibm-exclusive-idUSKCN1OJ2OY) — "Hackers working on behalf of China's Ministry of State Security breached the networks of Hewlett Packard Enterprise Co and IBM, then used the access to hack into their clients' computers, according to five sources familiar with the attacks."

[How China's Elite APT10 Hackers Stole the World's Secrets](https://www.wired.com/story/doj-indictment-chinese-hackers-apt10/) — "The MSP hacks don't just show China's hacking sophistication; they demonstrate its ruthless efficiency and determination."

[Here's What VMware Paid for Kubernetes Startup Heptio](https://www.lightreading.com/enterprise-cloud/infrastructure-and-platform/heres-what-vmware-paid-for-kubernetes-startup-heptio/d/d-id/748317) — You too can have your own Heptio for $550 million.

[As cloud-native matures, CNCF sees mainstream adoption of open source](https://siliconangle.com/2018/12/21/cncf-sees-mainstream-adoption-of-open-source-as-cloud-native-matures-guestoftheweek/) — "CNCF, cloud-native and Kubernetes all have matured a lot in the last three years," Chris Aniszczyk said. "The wider ecosystem is going to continue to grow."

[SQLite bug impacts thousands of apps, including all Chromium-based browsers](https://www.zdnet.com/article/sqlite-bug-impacts-thousands-of-apps-including-all-chromium-based-browsers/) — That sqlite database you used with that one script to do that thing in production that one time and is now part of your standard process... Yea... Patch that.

[DevOps Research and Assessment Joins Google Cloud](https://devops-research.com/2018/12/dora-joins-google-cloud/) — I'm happy but, I have mixed feelings. I love the fact Nicole, Jez, and Gene exited to such a great place for their work to flourish. But, one of the first things I tried to do at Red Hat was convincing the team to sponsor the DORA report. That wasn't in the cards this year and I'm not sure Red Hat will ever get the chance again.

[How Rancher Discovered the Kubernetes Vulnerability](https://thenewstack.io/how-rancher-discovered-the-kubernetes-vulnerability/) — "We identified it. It was kind of kept quiet until the fixed that were pushed out, and then everyone had the ability to patch really quickly last week."

[Applying Best Practice Security Controls to a Kubernetes Cluster](https://blog.giantswarm.io/applying-best-practice-security-controls-to-a-kubernetes-cluster/) — "In this article, we're going to address the application of best-practice security controls, using some of the cluster's inherent security mechanisms." Puja is always keeping it real.

[Clueless on Kubernetes? You're not alone, says Heptio](https://devclass.com/2018/12/19/clueless-on-kubernetes-youre-not-alone-says-heptio/) — "The pain of adoption is being felt most acutely early on according to a Heptio 2018 State of Kubernetes survey, which found 41 per cent of respondents require most help with architecture design."

[Celebrating 20 Years of OpenSSL](https://www.openssl.org/blog/blog/2018/12/20/20years/) — "The 20th year looks to be an exciting one, with a major change to the version number scheme, the switch to the Apache License 2.0, and a new FIPS validation project just for starters. And although all the versions of SSL are now deprecated, it's not likely we'll rebrand back to OpenTLS any time soon."

[The business case for serverless](https://techcrunch.com/2018/12/15/the-business-case-for-serverless/) — "[Serverless] is the best way to achieve maximum development velocity over time."

[Stop Calling Everything Serverless!](https://www.jeremydaly.com/stop-calling-everything-serverless/) — The definition of serverless is fuzzier than the definition of DevOps. There's a lot of ways to interpret "serverless". Jeremy tackles the varying meanings and comes to a nicely packaged conclusion.

[The Cyclical Theory of Open Source](https://redmonk.com/sogrady/2018/12/21/cycles-oss/)

[The Three Principles of Excellent API Design](https://nordicapis.com/the-three-principles-of-excellent-api-design/) — Purpose, Usability, and Constraints

[How to Properly Engage with AWS Enterprise Support](https://lastweekinaws.com/blog/how-to-properly-engage-with-aws-enterprise-support.html) — I made fun of Oracle for writing a similar article but, it was very much a HOWTO where this is a gentle reminder of what Enterprise support gets you with AWS. In general, AWS Enterprise Support is absolutely phenomenal.

## Tools

[Understanding Golang TLS mutual authentication DoS - CVE-2018-16875](https://apisecurity.io/mutual-tls-authentication-vulnerability-in-go-cve-2018-16875/) — "The crypto/x509 package of Go before 1.10.6 and 1.11.x before 1.11.3 does not limit the amount of work performed for each chain verification, which might allow attackers to craft pathological inputs leading to a CPU denial of service. Go TLS servers accepting client certificates and TLS clients are affected." Your software supply chain is VERY important.

[7 CI/CD tools for sysadmins](https://opensource.com/article/18/12/cicd-tools-sysadmins) — An easy guide to the top open source continuous integration, continuous delivery, and continuous deployment tools.

[Bye bye Mongo, Hello Postgres](https://www.theguardian.com/info/2018/nov/30/bye-bye-mongo-hello-postgres) — Guardian's path from Mongo to Postgres.

[Getting started with Prometheus](https://opensource.com/article/18/12/introduction-prometheus) — Learn to install and write queries for the Prometheus monitoring and alerting system.

[Re-Imagining Virtualization with Kubernetes and KubeVirt](https://blog.openshift.com/re-imagining-virtualization-with-kubernetes-and-kubevirt/) — The march to Kubernetes on bare metal continues.

[SSH on Windows Server 2019 (including how to sudo)](https://raymii.org/s/tutorials/SSH_on_Windows_Server_2019.html) — "How to elevate permissions via SSH on Windows, sudo but way more complicated. This guide is also applicable on Windows 10, build 1809 and up."

[SRE Challenges: Taming the Tool Sprawl](https://www.rundeck.com/blog/sre-challenges-taming-the-tool-sprawl) — Embrace heterogeneity, for the win

[15 Useful Helm Charts Tools](https://caylent.com/15-useful-helm-charts-tools/) — "Devs have found Helm Charts extremely useful, so they've begun developing tools, add-ons, and plugins for specific functions to enhance it further."

[DNS over TLS: Encrypting DNS end-to-end](https://code.fb.com/security/dns-over-tls/) — I've gone to using a CoreDNS based DNS server in the house to push all DNS requests outbound over TLS (or HTTPS). Improving your privacy starts at home (uninstalling the Facebook app is a good start).

[Four Tools That Support Your DevSecOps Process](https://www.tigera.io/blog/four-tools-that-support-your-devsecops-process/) — Some solid suggestions from Daniel Oh.

[Project Mu](https://microsoft.github.io/mu/) — "Mu is built around the idea that shipping and maintaining a **UEFI** product is an ongoing collaboration between numerous partners."

[Ansible Tips and Tricks: Dealing with Unreliable Connections and Services](https://www.ansible.com/blog/ansible-tips-and-tricks-dealing-with-unreliable-connections-and-services) — The world isn't fully connected yet. Here are some tricks to help with that.

[aws-quickstart/quickstart-awx](https://github.com/aws-quickstart/quickstart-awx) — Want to get AWX running on AWS? Here's a quick way to get up and running.

[mholt/certmagic](https://github.com/mholt/certmagic) — Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal

[amir20/dozzle](https://github.com/amir20/dozzle) — Realtime docker logs through the browser

[Terraform CLI Cheat Sheet](https://dzone.com/articles/terraform-cli-cheat-sheet)

[A New Font, Sans Forgetica, Helps You Remember What You Read](https://www.wired.com/story/new-font-sans-forgetica-for-learning/) — "Australia's RMIT University recently introduced a new typeface, Sans Forgetica, that uses clever tricks to lodge information in your brain." Got an onboarding doc?

[Minikube v0.32.0 released!](https://discuss.kubernetes.io/t/minikube-v0-32-0-released/3969)

[VirtualBox 6.0 Released](https://www.virtualbox.org/wiki/Changelog-6.0#v0) — Some pretty big features added to Virtualbox.

[HAProxy 1.9 Has Arrived](https://www.haproxy.com/blog/haproxy-1-9-has-arrived/) — A lot of improvements and future proofing in this release.

[10 books for your DevOps reading wishlist](https://opensource.com/article/18/12/devops-wishlist) — This list of books will help fine-tune your DevOps practice.

[Linux ip Command Examples](https://www.cyberciti.biz/faq/linux-ip-command-examples-usage-syntax/) — I've never used `ip link set dev {DEVICE} {up|down}` before. It's been a long time since I've bounced an interface on a Linux server come to think about it.

## DevOps'ish Tweet of the Week

{{< tweet 1076532900806311936 >}}

Notes from this week's issue can be found [here](./notes/).
