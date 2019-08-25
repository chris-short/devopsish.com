+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-02-17T16:15:00Z
description = "CVE-2019-5736 runc vuln, You Can Fit So Much Kubernetes in this Newsletter, Liz Fong-Jones, MongoDB's Demise, GPS epoch, DIY DBaaS, and More!"
draft = false
slug = "115"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "ansible", "container", "security", "runc", "CVE-2019-5736", "vulnerability", "liz fong-jones", "GPS", "DBaaS"]
title = "115: CVE-2019-5736 runc vuln, You Can Fit So Much Kubernetes in this Newsletter, Liz Fong-Jones, MongoDB's Demise, GPS epoch, DIY DBaaS, and More!"

+++

Last week, I enabled a workflow to automate more of the DevOps'ish process. One thing I did not test as a part of this workflow was link tracking. To be honest, I did not think it would matter. That assumption bit me hard. Within minutes, reports from readers came in saying Gmail was flagging the links in the e-mail as suspicious.

As it turns out, disabling the link tracking also bypassed a bug in Mailchimp's platform. When the automation kicked off with link tracking enabled it triggered the bug in the Mailchimp platform. My apologies for ever making you question the validity of the e-mails for this newsletter. The lesson I've re-learned here is never to trust your assumptions. Trust but verify all features.

Mailchimp is working on the bug and gave me a very viable workaround. E-mail is hard, y'all. I've managed email delivery at a few companies now. If you think it's easy, try doing it en masse, at scale. It's a constant game of give and take that you win and lose at often. Mailchimp is a real delight to work with and I appreciate their support.

I'm hopeful this week will be different. If you see any issues, please let me know. Thanks for reading!

> "Care about what other people think and you will always be their prisoner." —Lao Tzu

[**Use Lead Time Metric to Improve Your CI/CD Process**](https://www.gocd.org/2019/01/14/cd-metrics-deployment-lead-time/)  
Check out GoCD's latest blog in CD Metrics series. It talks about what lead time means in CD context and guides you on how to identify bottlenecks and improve your CI/CD process. *SPONSORED*

[**Triangle DevOps presents DevOps is Not War with Chris Short of Red Hat**](https://www.meetup.com/triangle-devops/events/257189603/)  
Over the past 500 years, there have been 16 cases of a rising power threatening to displace a ruling power. 75% of those cases resulted in war. Although your organizational transformation probably won't lead to war, it could be contentious. History can help prevent conflict when driving change. This talk will analyze human tendencies, historical data, and provide real-world examples of how to avoid friction during your DevOps journey. *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [7 Habits Of Highly Effective CI/CD Pipelines](https://medium.com/uptime-99/7-habits-of-highly-effective-ci-cd-pipelines-45006e2cb550)
2. [12 ways to get smarter about Kubernetes](https://enterprisersproject.com/article/2019/2/kubernetes-12-ways-get-smarter)
3. [20 VS Code Extensions You'll Actually Use](https://dev.to/vip3rousmango/vs-code-extensions-youll-actually-use-46gp)
4. [We Don't Do That Here](http://www.thagomizer.com/blog/2017/09/29/we-don-t-do-that-here.html)
5. [High prevalence of poor mental health among tech (specifically Ops) employees?](https://www.reddit.com/r/devops/comments/aoi38i/high_prevalence_of_poor_mental_health_among_tech/)

## People

[Former engineer Liz Fong-Jones has ‘grave concerns' about Google](https://www.businessinsider.com/liz-fong-jones-google-concerns-2019-2) — I have a helluva lot of respect for Liz Fong-Jones. Standing up for what you believe in and walking the talk at great personal risk is heroic. We truly don't deserve her.

[The Secret History of Women in Coding](https://www.nytimes.com/2019/02/13/magazine/women-coding-computer-programming.html) — Computer programming once had much better gender balance than it does today. What went wrong?

[You Guys](https://www.xaprb.com/blog/you-guys/)

[U-M Flint professor lodges Title IX complaint against WSU](https://www.thesouthend.wayne.edu/article_69c55fe6-2ee9-11e9-8d0a-ab3bc286938e.html) — "[Mark Perry, an economics professor at U-M Flint, submitted a Title IX complaint against WSU because the university hosted a summer workshop for Black Girls CODE... Perry says WSU was acting as a venue sponsor for Black Girls CODE from July 30, 2018 to Aug. 10, 2018. Because the Black Girls CODE program only allowed girls ages 13 to 17 to participate, it was discriminatory to boys and therefore a breach of Title IX." [Mark Perry](https://www.umflint.edu/som/mark-perry)'s pettiness knows no bounds.

[Joe Beda on Kubernetes & the CNCF](https://www.infoq.com/podcasts/joe-beda-kubernetes-cncf) — "Kubernetes was always viewed by the creators as something to be build on. It was never really viewed as the end goal."

[Venture capital is still very much a boys' club](https://www.axios.com/venture-capital-women-tech-diversity-29c3f2f0-2d1e-4ec5-b542-7878ab149d45.html) — "Only 9.65% of decision-makers at U.S. venture capital firms are women. The breakdown was 105 female decision-makers out of an industry total of 1,088."

[A record 7 million Americans are 3 months behind on their car payments, a red flag for the economy](https://www.washingtonpost.com/business/2019/02/12/record-million-americans-are-months-behind-their-car-payments-red-flag-economy/?utm_term=.b57565c0ae9c) — A horrifying economic indicator.

[Salary Negotiation Tips from White Men in Tech: Part 1 – Career Advice for Women in Security](https://keirstenbrager.tech/salarytips-part1/)

## Process

[CVE-2019-5736: runc container breakout (all versions)](https://seclists.org/oss-sec/2019/q1/119) — Another nasty vulnerability impacting virtually the entire container ecosystem. This vulnerability was interesting in the sense that it was clearly embargoed but, not every Kubernetes vendor got their systems patched by the deadline. As the day wore on, it became apparent IBM and Microsoft had missed the boat on patching this vulnerability. Open source security is a difficult world. Be open and collaborative but, be secretive and limit communications regarding vulnerabilities. Things break, communications systems break, and all we can do is try to improve things for next time. Other runc vulnerability articles from this week:

* [runc - Malicious container escape - CVE-2019-5736](https://access.redhat.com/security/vulnerabilities/runcescape) (Red Hat)
* [Runc and CVE-2019-5736 - Kubernetes](https://kubernetes.io/blog/2019/02/11/runc-and-cve-2019-5736/) (Kubernetes.io)
* [RunC Vulnerability Gives Attackers Root Access on Docker, Kubernetes Hosts](https://www.bleepingcomputer.com/news/security/runc-vulnerability-gives-attackers-root-access-on-docker-kubernetes-hosts/) (Bleeping Computer)
* [Mitigating High Severity RunC Vulnerability (CVE-2019-5736)](https://blog.aquasec.com/runc-vulnerability-cve-2019-5736) (Aqua Security)

[Detecting exploits of CVE-2019-5736: runc container breakout](https://sysdig.com/blog/cve-2019-5736-runc-container-breakout/) — Sysdig has put together a guide for detecting the runc exploit.

[Stop Disabling SELinux](https://stopdisablingselinux.com/) — "Every time you run setenforce 0, you make [Dan Walsh](https://twitter.com/rhatdan) weep."

[Diversity Is Vital to Advance Security](https://www.darkreading.com/careers-and-people/diversity-is-vital-to-advance-security/a/d-id/1333818) — "Diversity isn't just different appearances or labels. It's beyond that. It's about diversity of thought, the differences in our problem-solving processes and perspectives — and it is a critical component of true innovation." I absolutely could not agree more.

[Commit to your lock-in](https://veekaybee.github.io/2019/02/10/lockin/) — Embracing that little bit of lock-in can enable a lot more engineering time to other things. Data gravity is a thing; embrace it and move forward as it suits your needs.

[Automation - Just do it!](https://www.dowen.me.uk/Automation-Just-do-it!/) — Listed as a benefit, "Personal development, over time you will gain confidence and be able to contribute some valuable automation"

[GNU Health Federation Information System moves from MongoDB to PostgreSQL](https://savannah.gnu.org/forum/forum.php?forum_id=9366) — MongoDB's demise is in progress. Their stance against open source is not something the industry can embrace.

[Red Hat Satellite to standardize on PostgreSQL backend](https://www.redhat.com/en/blog/red-hat-satellite-standardize-postgresql-backend)

[USN-3887-1: snapd vulnerability](https://usn.ubuntu.com/3887-1/) — Eeek! "Chris Moberly discovered that snapd versions 2.28 through 2.37 incorrectly validated and parsed the remote socket address when performing access controls on its UNIX socket. A local attacker could use this to access privileged socket APIs and obtain administrator privileges."

[The CNCF 2018 annual report](https://lwn.net/Articles/779381/)

[Fun fact: GPS uses 10 bits to store the week. That means it runs out... oh heck – April 6, 2019](https://www.theregister.co.uk/2019/02/12/current_gps_epoch_ends/) — If you're running older GPS gear it might be time to replace it.

[What's the future of Linux distributions?](https://funnelfiasco.com/blog/2019/02/14/whats-the-future-of-linux-distributions/) — I have so many thoughts here. SO MANY...

[Ansible Community Update — February 2019](https://www.ansible.com/blog/ansible-community-update-february-2019) — Lots of good stuff in the works in the Ansible community.

## Tools

[Running your own DBaaS based on your preferred DBs, Kubernetes operators and containerized storage](https://blog.openebs.io/running-your-own-dbaas-based-on-your-preferred-dbs-kubernetes-operators-and-containerized-storage-3cc36ba115b8) — "This blog was intended to outline some of the things to think about when running your own DBaaS. Overall I recommend doing so — however I also suggest you think long and hard about operations automation and, of course, underlying data resilience." —Evan Powell, CEO of MayaData (Editor's Note: Such a good piece)

[chris-short/DevOps-README.md](https://github.com/chris-short/DevOps-README.md) — The DevOps README.md needs a refresh. It's a work in progress for me but pull requests are VERY welcomed.

[The Rise of Bare-Metal Kubernetes Servers](https://containerjournal.com/2019/02/11/the-rise-of-bare-metal-kubernetes-servers/) — If you recall, I said in my annual update that, "[Kubernetes Will Start to Replace The Hypervisor](https://chrisshort.net/2018-learnings-2019-expectations/)". It's already happening.

[Kubernetes Policies – PodCTL](https://podctl.com/kubernetes-policies/) — Brian and new co-host John Osborne (@OpenShiftFed) discuss policies in and around Kubernetes.

[Running Static Pods in Kubernetes](https://medium.com/devopslinks/running-static-pods-in-kubernetes-f6d1587c31f1) — Static pods are configured to be start at Kubelet daemon or whenever Kubelet daemon reloads itself. All Master components run as Static pod and configured to be run at start/reload of Kubelet daemon.

[Kubernetes Podcast from Google](https://kubernetespodcast.com/episode/039-minikube/) — Interview with author and maintainer of minikube, Dan Lorenc

[What's the right amount of swap space for a modern Linux system?](https://opensource.com/article/19/2/swap-space-poll) — Complete the survey and voice your opinion on how much swap space to allocate.

[Building Small Containers (Kubernetes Best Practices)](https://medium.com/@priyank_33569/building-small-containers-kubernetes-best-practices-9d275e414058) — "The first step in deploying to Kubernetes is putting your app inside a container. let's explore how you can create a small and secure container images"

[The 10 Kubernetes Commandments](https://www.infoq.com/presentations/10-kubernetes) — "Bryan Liles and Carlos Amedee explore topics from booting Kubernetes clusters to running complex workloads as a list of 10 items."

[How to explain Kubernetes Operators in plain English](https://enterprisersproject.com/article/2019/2/kubernetes-operators-plain-english) — What are Kubernetes Operators, and why are they so valuable to organizations working with containers? Here's a primer for IT leaders – and anyone needing to demystify the concept.

[Setting up a Kubernetes cluster with Kubespray](https://medium.com/@leonardo.bueno/setting-up-a-kubernetes-cluster-with-kubespray-1bf4ce8ccd73) — [Kubespray](https://github.com/kubernetes-sigs/kubespray) has been mentioned in DevOps'ish before ([088](https://devopsish.com/088/), [094](https://devopsish.com/094/)). It's a composable way to install Kubernetes on damn near anything x86 based using Ansible. It's good stuff.

[Inspector Murphy, The Kubernetes quality enforcer](https://medium.com/@MysticSdet/inspector-murphy-the-kubernetes-quality-enforcer-d930fc7bbaa2)

[Single Sign-On for Kubernetes: An Introduction](https://www.tigera.io/blog/single-sign-on-for-kubernetes-an-introduction/) — "One of the great things about Kubernetes is that it completely separates authentication and authorization. Authentication (Authn) meaning the act of identifying who the user is and authorization (Authz) meaning the act of working out if they're allowed to perform some action."

[Kubernetes as an API standard](https://www.cloudatomiclab.com/rustyk8s/) — Justin Cormack is on to something here.

[Pimp my Kubernetes Shell](https://itnext.io/pimp-my-kubernetes-shell-f144710232a0) — Making a more usable Kubernetes shell is within reach.

[Cluster-level Logging in Kubernetes with Fluentd](https://supergiant.io/blog/cluster-level-logging-in-kubernetes-with-fluentd/)

[How to build a Serverless Single Page App](https://www.openfaas.com/blog/serverless-single-page-app/) — OpenFaaS is good stuff.

[How does rootless Podman work?](https://opensource.com/article/19/2/how-does-rootless-podman-work)

[Fathom: An Open Source Google Analytics Alternative](https://dev.to/jacobherrington/fathom-an-open-source-google-analytics-alternative-1g7g) — As of this issue, I'm starting a long process of moving away from embedding Google products into this web property. Google AdSense has been removed. Google Analytics is next and [Fathom](https://github.com/usefathom/fathom) will likely be my replacement. Google Fonts is going to be the hard one.

[Networking tool comics!](https://jvns.ca/blog/2019/02/10/a-few-networking-tool-comics/) — Admit it; you might not be great at networking. This should help.

[Managing EC2 servers at scale: Ansible and RunCommand](https://advancedweb.hu/2019/02/12/ansible/) — Ansible vs SSM RunCommand: which one to use to manage a fleet of servers

[bincyber/vigilant](https://github.com/bincyber/vigilant) — A security controller for Kubernetes

[shawnxlw/infra-dev-env](https://github.com/shawnxlw/infra-dev-env) — A docker image that contains the necessary tools for doing Infrastructure Development

[A handy flowchart for when to use blockchain](https://imgur.com/gallery/Tp6U61d)

## DevOps'ish Tweet of the Week

{{< tweet 1095273479887310848 >}}

Notes from this week's issue can be found [here](./notes/).
