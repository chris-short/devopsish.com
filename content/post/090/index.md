+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-08-26T07:00:00Z
description ="DevOps, GitOps, Commons Clause Clusterfuck, NotPetya, Kubernetes, Prometheus, and more!"
draft = false
slug = "090"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "automation", "ansible", "red hat", "windows", "linux", "rss", "pipelines", "cicd", "NotPetya", "licenses"]
title = "090: DevOps, GitOps, Commons Clause Clusterfuck, NotPetya, Kubernetes, Prometheus, and more!"

+++

The past few weeks have resulted in iterative improvements to my office workspace. After visiting a few Red Hat offices, it dawned on me that my office wasn't what it should be. The improvements have helped me mentally in numerous ways. They've also allowed me to think more broadly about a number of things. Some odd little nuggets related to DevOps'ish popped out too (sausage making follows):

1. Automation: This newsletter relies more on automation for content curation than you might realize. Recently, I've realized I'd like to run that automation more reliably with more granular controls. A switch from IFTTT to Zapier took place after I couldn't determine why Corey Quinn's [Last Week in AWS](https://lastweekinaws.com/) was breaking my automation. Corey's site was making a malformed URL. IFTTT gives little in the way of logging or event details compared to Zapier. So one evening this week I migrated everything.

2. The Return of the RSS Feed: A lot of my reading had moved away from RSS feeds after the death of Google Reader. But, the dust *finally* settled in that world I have embraced RSS again in a big way. Cleaning out IFTTT showed me how much my reliance on it to parse RSS and send me e-mails had become. All of those RSS feeds moved into my [inoreader](https://www.inoreader.com/). Then it dawned on me, "This is hypocritical." I originally turned off the DevOps'ish RSS feed to get more people to subscribe to the e-mail newsletter. That 'gamble' paid off. There are now over 2,000 subscribers to DevOps'ish weekly e-mails. Not having an RSS might have helped reach that number a little faster. But, it's not open and focuses more on the business side of things and less on the user experience. Time for that to change.

3. Return of the Facebook: The blue F took a huge one to the chin in the face of Cambridge Analytica. Have they learned their lesson? Probably not. But, not having the Facebook page for DevOps'ish seemed silly. I re-enabled the Facebook page and invite you to [Like it if you're into Facebook](https://www.facebook.com/devopsish/).

[**Webinar: "Want to successfully adopt DevOps? Change Everything."**](https://info.thoughtworks.com/Adopting-DevOps-Webinar.html)  
Moving your organization to a DevOps culture isn't as simple as buying a tool. It requires changes to many parts of your process. In this webinar, Ken Mugrage will walk you through four changes you can make in your organization to help you "Do the DevOps". *SPONSORED*

[**What's Kubernetes Doing? Datadog Knows, So You Can Too!**](https://www.datadoghq.com/monitor-kubernetes/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterKubernetes)  
Get real-time metrics from Docker and Kubernetes with Datadog. Visualize the performance of your entire container infrastructure at a glance and investigate issues quickly. [Start your free Datadog trial today](https://www.datadoghq.com/monitor-kubernetes/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterKubernetes) *SPONSORED*

{{< sponsor-blurb >}}

## People

[Artificial Intelligence Still Isn't All That Smart](https://www.bloomberg.com/view/articles/2018-08-16/smart-machines-won-t-be-ready-to-do-complex-jobs-anytime-soon): Some routine jobs might be at risk someday, but work requiring judgment seems safe.

[Today's CIOs, by the numbers: 9 telling stats](https://enterprisersproject.com/article/2018/8/today-s-cios-numbers-9-telling-stats): How is the CIO role evolving? Are CIOs truly shaping digital strategy? Deloitte's 2018 global CIO survey offers instructive data

[Verizon throttled fire department's "unlimited" data during Calif. wildfire](https://arstechnica.com/tech-policy/2018/08/verizon-throttled-fire-departments-unlimited-data-during-calif-wildfire/): Fire department had to pay twice as much to lift throttling during wildfire response.

[Amazon's India chief takes stand against work email after 6pm](https://www.scmp.com/tech/article/2160426/amazons-india-chief-takes-stand-against-work-email-after-6pm): While the demands of technology on workers has become a topic of debate around the world, work-life balance is severely off kilter in Bangalore, India's third-largest city, where a significant portion of the one million workers employed in the outsourcing business cater to global customers and often work late into the night

[Case Study: Can You Fix a Toxic Culture Without Firing People?](https://hbr.org/2018/08/case-study-can-you-fix-a-toxic-culture-without-firing-people)

[A Brief History of DevOps, Part I: Waterfall](https://circleci.com/blog/a-brief-history-of-devops-part-i-waterfall/): "When software development was still young, engineers modeled their work on the hardware world."


## Process

[Redis modules and the Commons Clause](https://lwn.net/SubscriberLink/763179/d7a76bd0885f162f/): Redis threw a flashbang in the room, closed the door, and walked away. A fumbled announcement of a "Commons Clause" license being added to Redis Labs products, a clarification/walk back, and a whirlwind of [navel](https://anonymoushash.vmbrasseur.com/2018/08/21/redis-labs-and-the-questionable-business-decision/) [gazing](https://medium.com/@michaeldehaan/why-open-source-needs-new-licenses-d2d9d819a10) from the open source software world. In my professional opinion, this is a clusterfuck.

[Vulnerability Affects All OpenSSH Versions Released in the Past Two Decades](https://www.bleepingcomputer.com/news/security/vulnerability-affects-all-openssh-versions-released-in-the-past-two-decades/)

[How to explain DevOps, agile, and automation like a golfer](https://enterprisersproject.com/article/2018/8/how-explain-devops-agile-and-automation-golfer): What do mulligans and agile development have in common? Quite a bit. Let's bring some tech concepts down to golf terms

[The Untold Story of NotPetya, the Most Devastating Cyberattack in History](https://www.wired.com/story/notpetya-cyberattack-ukraine-russia-code-crashed-the-world)

[A Practical Guide to Testing in DevOps](https://leanpub.com/testingindevops) by [Katrina Clokie](https://twitter.com/katrina_tester): A Practical Guide to Testing in DevOps offers direction and advice to anyone involved in testing in a DevOps environment.

[DevOps lessons learned: What I wish I knew sooner](https://enterprisersproject.com/article/2018/8/devops-lessons-learned-what-i-wish-i-knew-sooner): Eight DevOps veterans share the one thing they wish they'd learned earlier in their careers. Apply their wisdom to your work

[New "Turning Tables" Technique Bypasses All Windows Kernel Mitigations](https://www.bleepingcomputer.com/news/security/new-turning-tables-technique-bypasses-all-windows-kernel-mitigations/): "[S]ince the concept of page tables is also used by Apple and the Linux project, macOS and Linux are, in theory, also vulnerable to this technique, albeit the researchers have not verified such attacks, as of yet."

[Y Combinator, a startup program that's harder to get into than Harvard, accepts all 15,000 applicants into Startup School after a major screwup](https://www.businessinsider.com/y-combinator-accepted-15000-startups-into-startup-school-2018-8): Whoops 🤭

[Slack just raised a whopping $427 million to become a $7.1 billion company](https://www.businessinsider.com/slack-funding-valuation-microsoft-teams-2018-8): Getting the money while it can. The industry is having Slack fatigue.

[What Is GitOps Really?](https://www.weave.works/blog/what-is-gitops-really): How is this different from traditional infrastructure as code and continuous delivery Do I have to use Kubernetes?

[Download Docker CE without logging in #6910](https://github.com/docker/docker.github.io/issues/6910): To get [petty.company](http://petty.company/)'s Docker for Windows and Mac you now need a login. I hope they don't try that with their repos.

[Don't Do This in Production](https://stephenmann.io/post/dont-do-this-in-production/): "The code from these blog posts had spread through the codebase like a disease, scattering issues here and there without any rhyme or reason."

[This is not your father's Microsoft](https://www.cnet.com/news/this-is-not-your-fathers-microsoft/): CEO Satya Nadella knew the culture at the world's largest software maker needed a fix. Employees and investors are sold. Now he's got to convince the rest of us.

[The Benefits You Need to Know about Infrastructure as Code](https://blog.kylegalbraith.com/2018/08/21/the-benefits-you-need-to-know-about-infrastructure-as-code/): "It is a swiss army knife for both developers and system administrators."

[Idempotence. What is it and why should I care?](http://cloudingmine.com/idempotence-what-is-it-and-why-should-i-care/)

[How Cloudflare protects customers from cache poisoning](https://blog.cloudflare.com/cache-poisoning-protection/): Not a typical problem to have. But, this is a pretty cool way of handling it.

[How to Correctly Handle DB Schemas During Kubernetes Rollouts](https://www.weave.works/blog/how-to-correctly-handle-db-schemas-during-kubernetes-rollouts): "So you have decided to migrate to Kubernetes, but you are unsure how to safely roll out your microservice's replicas, while also coordinating changes to the schema of the underlying database?"

[Someone Is Waging a Secret War to Undermine the Pentagon's Huge Cloud Contract](https://www.defenseone.com/technology/2018/08/someone-waging-secret-war-undermine-pentagons-huge-cloud-contract/150685/)

[Pentagon Amends JEDI Contract, Moves Forward Despite Protest](https://www.nextgov.com/it-modernization/2018/08/pentagon-amends-jedi-contract-moves-forward-despite-protest/150808/)


## Tools

["Prometheus changed how the cloud-native world thinks of data ingestion scale and how it labels monitoring & other data"](https://jaxenter.com/prometheus-cncf-interview-hartmann-148526.html)

[Make a Kubernetes Operator in 15 minutes with Helm](https://blog.openshift.com/make-a-kubernetes-operator-in-15-minutes-with-helm/): "An Operator is a method of packaging, deploying and managing a Kubernetes application."

[What CI/CD tools and pipelines are people using?](https://discuss.kubernetes.io/t/what-ci-cd-tools-and-pipelines-are-people-using/2180): "Kubernetes users, what are you all using for CI/CD pipelines today?"

[Red Hat Enterprise Linux 7.6 beta is out now](https://www.zdnet.com/article/red-hat-enterprise-linux-7-6-beta-is-out-now/): The latest version of Red Hat Enterprise Linux takes a big step forward into the cloud.

[Recap of Container Talks at DevConf US](http://crunchtools.com/containers-recap-devconf/)

[Cilium 1.2: DNS Security Policies, EKS Support, ClusterMesh, kube-router integration](https://cilium.io/blog/2018/08/21/cilium-12/): One of the most exciting features is the introduction of security policies based on DNS names to secure access to external services outside of the cluster.

[Lessons Learned: Switching from CircleCI to Google Cloud Build](https://medium.com/@hexsprite/what-i-learned-switching-from-circleci-to-google-cloud-build-b4405de2be38)

[Cloud Product Accidentally Exposes Users' TLS Certificate Private Keys](https://www.bleepingcomputer.com/news/security/cloud-product-accidentally-exposes-users-tls-certificate-private-keys/): The Traefik dashboard API exposed TLS cert private keys; [CVE-2018-15598](https://nvd.nist.gov/vuln/detail/CVE-2018-15598)

[What is a Makefile and how does it work?](https://opensource.com/article/18/8/what-how-makefile): Run and compile your programs more efficiently with this handy automation tool.

[Sending Keybase Chats Using Vim](https://www.codesections.com/blog/sending-keybase-chats-with-vim)

[Introduction to writing pipelines-as-code and implementing DevOps with Jenkins 2](https://opensource.com/article/18/8/devops-jenkins-2): Learn how to create pipelines as code in Jenkins 2.

[kube-hunter](https://kube-hunter.aquasec.com/): "kube-hunter is an open-source tool that hunts for security issues in your Kubernetes clusters. It's designed to increase awareness and visibility of the security controls in Kubernetes environments." 💯

[Introducing Red Hat infrastructure migration solution](https://www.redhat.com/en/blog/introducing-red-hat-infrastructure-migration-solution): An enterprise-grade remedy designed for proprietary virtualization silo ills

[Introducing ebpf_exporter](https://blog.cloudflare.com/introducing-ebpf_exporter/): Prometheus exporter for custom eBPF metrics

[How to Compile Percona Server for MySQL 5.7 in Raspberry Pi 3](https://www.percona.com/blog/2018/08/22/how-to-compile-percona-server-for-mysql-5-7-in-raspberry-pi-3/)

[Windows 95 Is Now Available as an App for Windows, macOS and Linux](https://www.bleepingcomputer.com/news/microsoft/windows-95-is-now-available-as-an-app-for-windows-macos-and-linux/): This pleases me.

[What Stable Kernel Should I Use?](http://kroah.com/log/blog/2018/08/24/what-stable-kernel-should-i-use/): I like [Jamie Duncan](https://twitter.com/jamieeduncan/status/1033420624264347648)'s take here, "The one that's lets you sleep at night."

[Getting Started With Consul & Vault in Kubernetes](https://kruschecompany.com/blog/post/hashicorp-in-kubernetes): "The implementation of Consul or Vault in Kubernetes, or Kubernetes itself is not an easy task."

[defionscode/stig-cli](https://github.com/defionscode/stig-cli): A CLI for perusing DISA STIG content Mac, Linux, and Windows Compatible

[buzzfeed/sso](https://github.com/buzzfeed/sso): sso, the way Buzzfeed secures services

[coredns/auto](https://coredns.io/plugins/auto/): auto enables serving zone data from an RFC 1035-style master file, which is automatically picked up from disk.

## DevOps'ish Tweet of the Week

{{< tweet 1032714604542132224 >}}
