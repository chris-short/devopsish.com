+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-03-10T07:00:00Z
description = "Kubernetes, People, Say AMI, Ghidra, Terraform, Git, OperatorHub, and More"
draft = false
slug = "118"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "ansible", "container", "security", "Ghidra", "Terraform", "docker", "azure", "operator", "Docker Inc", "Linus Torvalds", "GitOps"]
title = "118: Kubernetes, People, Say AMI, Ghidra, Terraform, Git, OperatorHub, and More"

+++

Life is more significant than tech. We all recognize this fact but, seldom do we internalize it and own it. This newsletter attempts to imitate life. Injecting needed doses of humanity and thought provocation into your inbox every week. People, Process, and Tools involves all facets of each. They're in that order for a reason. I can load your inbox up every week with endless lists of tools. They aren't going to fix your broken processes though. The people implementing those processes need to have their minds open to new ideas and methods.

People implementing processes they have real ownership in using tooling they find real value in using will go further towards improving outcomes than implementing any new piece of technology ever will. My long-held opinion that technology should improve life is only a part of the equation. Technology by itself gives people a way to improve something. People do the actual improving. The care, education, and growth of the people in your charge are dependent upon you. Treat this great responsibility with the attention it deserves and you will go very far in life.

> "Don't let the behavior of others destroy your inner peace." —Dalai Lama

**New Microsoft Azure Elastic Agent Plugin for GoCD**  
With GoCD's new Azure plugin, run your CI/CD pipelines on Azure virtual machines, and let GoCD scale up on-demand agents based on your need. Remove bottlenecks and reduce the cost of your agent infrastructure.

Learn more about GoCD: [www.gocd.org](https://www.gocd.org)  
Learn more about GoCD's Azure plugin: https://extensions-docs.gocd.org/azure/current/ *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [xkcd: Modern OSI Model](https://xkcd.com/2105/)
2. [Killing Kubernetes](https://blog.freetrade.io/killing-kubernetes-7f8b61c701aa)
3. [Common Assumptions to Avoid When Starting with Kubernetes](https://blog.flux7.com/common-assumptions-to-avoid-when-starting-with-kubernetes)
4. [How I passed the CKA (Certified Kubernetes Administrator) Exam](https://medium.com/@krystiannowaczyk/how-i-passed-the-cka-certified-kubernetes-administrator-exam-f94b11566528)
5. [Linus Torvalds pulls pin, tosses in grenade: x86 won, forget about Arm in server CPUs, says Linux kernel supremo](https://www.theregister.co.uk/2019/02/23/linus_torvalds_arm_x86_servers/)

## People

[AMI has three syllables](https://ami-has-3-syllables.online/) — "Say 'ahh-mee' again. Say 'ahh-mee' again, I dare you, I double dare you motherfucker, say what one more Goddamn time!" —Jules Winnfield, Pulp Fiction

[New adventures at Slack!](https://www.linkedin.com/pulse/new-adventures-slack-nora-jones/) — Best of luck, Nora!

[Portland startup Stackery sticks by CEO despite ex-spouse's allegation of verbal abuse, threats](https://www.oregonlive.com/silicon-forest/2019/03/portland-startup-stackery-sticks-by-ceo-despite-ex-spouses-verbal-abuse-allegation.html) — I know nothing of this situation but, I'm really glad I'm not married to someone in the industry. I feel like that'd be really hard.

[Camille Fournier on Scaling, Structure, and Growing as an Engineering Manager](https://blog.gitprime.com/camille-fournier-on-scaling-structure-and-growing-as-an-engineering-manager/)

[Companies Need to Pay More Attention to Everyday Unethical Behavior](https://hbr.org/2019/03/companies-need-to-pay-more-attention-to-everyday-unethical-behavior) — "The standard you walk past is the standard you accept."

[The saddest thing I've ever heard on an airplane](https://theoatmeal.com/comics/airplane_heard)

## Process

[Goodbye Docker and Thanks for all the Fish](https://technodrone.blogspot.com/2019/02/goodbye-docker-and-thanks-for-all-fish.html) — Someone else that thinks [**Docker is Dead**](https://chrisshort.net/docker-inc-is-dead/). I wonder if Docker is going to bad mouth the author like they've bad mouthed me.

[You Don't Need All That Complex/Expensive/Distracting Infrastructure](https://blog.usejournal.com/you-dont-need-all-that-complex-expensive-distracting-infrastructure-a70dbe0dbccb) — "So, finally getting that next Unicorn idea down into code? You don't need all of that infrastructure you have planned out."

[IBM hunkers down for no-deal Brexit, warns of disruption to supply chain, data transfers](https://www.theregister.co.uk/2019/03/01/ibm_brexit_plan/) — Brexit is about to get very real for a lot of folks. The fifth largest economy is about to make a move that will have ramifications for a very long time.

[Google Chrome Zero-Day Vulnerability CVE-2019-5786 actively exploited in the wildSecurity Affairs](https://securityaffairs.co/wordpress/82058/hacking/chrome-zero-day-cve-2019-5786.html) — This is gnarly and I'm surprised isn't happening more frequently.

[Considerations on OpenShift PKIs and Certificates](https://blog.openshift.com/considerations-on-openshift-pkis-and-certificates/) — Encryption and PKI is hard. I need to come up with a [Drawing](https://chrisshort.net/drawings/) of some sort to help with this. Developers have told me they know nothing of encryption and that terrifies me.

[NSA's Ghidra Reverse Engineering Framework Stirs Up Malware Researchers](https://www.bleepingcomputer.com/news/security/nsas-ghidra-reverse-engineering-framework-stirs-up-malware-researchers/) — It's interesting the NSA would release this.

[The Thunderclap vulnerabilities](https://lwn.net/SubscriberLink/782381/be9bbbaff9133198/) — "At its core, Thunderclap exploits the ability of devices with direct memory access (DMA) capability to read system memory, including memory that is not at all related to the supposed function of the device."

[How to ace the Certified Kubernetes Administrator Exam in 7 days](https://medium.com/@writetomiglani/how-to-ace-the-certified-kubernetes-administrator-exam-in-7-days-e4603ac40746)

[Why I, A Serverless Developer, Don't Care About Your Containers](https://medium.com/adobetech/why-i-a-serverless-developer-dont-care-about-your-containers-40c08d36aee4) — Groan... Why I don't care about what you care about and other life lessons (but y'all clicked it a lot).

[Hardening Git for GitOps](https://www.weave.works/blog/whitepaper-hardening-git-for-gitops)

## Tools

[Terraform Command: 0.12upgrade](https://www.terraform.io/docs/commands/0.12upgrade.html) — "The terraform 0.12upgrade command applies several automatic upgrade rules to help prepare a module that was written for Terraform v0.11 to be used with Terraform v0.12."

[Ansible and Terraform: Better Together](https://www.hashicorp.com/resources/ansible-terraform-better-together) — Presenters from Red Hat and HashiCorp showcase workflows that integrate the best parts of Ansible and the HashiCorp stack for configuration and provisioning.

[How to measure every API call in your Go app (in fewer than 30 lines of code)](https://blog.sensu.io/how-to-measure-every-api-call-in-your-go-app) — You can only improve what you measure.

[Murder On The Kubernetes Express: The Life And Death Of A Docker Container](https://itnext.io/murder-on-the-kubernetes-express-the-life-and-death-of-a-docker-container-d7aec13f8188) — "It's a brutal existence but one that is extremely beneficial to you and me as developers."

[Do RHEL Containers Inherit Security Compliance from the Host?](https://medium.com/shawndwells/do-rhel-containers-inherit-security-compliance-from-the-host-b3f11161d34b) — "*tl;dr:* There are 363 configuration settings applicable to RHEL 7-based container hosts. 93 controls are not inherited and applicable to RHEL as a container image. 85 of the 93 controls are resolvable through automation. The remainder requires manual review." Holy shit.

[The Wireshark Foundation released Wireshark 3.0.0](https://securityaffairs.co/wordpress/81893/breaking-news/wireshark-3-0-0.html) — A long time in the making.

[Julia's cheat sheet for curl](https://daniel.haxx.se/blog/2019/03/05/julias-cheat-sheet-for-curl/) — I appreciate when developers appreciate the works of their users.

[Linux 5.0](https://lore.kernel.org/lkml/CAHk-=wjuG6HiGbD7DCGfvDvhr_1WZUR-eYF2qWGbYyn9k6unvg@mail.gmail.com/T/#u) — AMD FreeSync support, Btrfs file-system restores support for swap files, and, Retpoline overhead reduction work are some of the things in the new kernel.

[A surprisingly arcane little Unix shell pipeline example](https://utcc.utoronto.ca/~cks/space/blog/unix/ShellPipelineIndeterminate) — `(echo red; echo green 1>&2) | echo blue`

[5 ~~Best~~ Serverless Security Platform for Your Applications](https://geekflare.com/serverless-application-security/) — I corrected the title.

[Building a Control Plane for Envoy](https://medium.com/solo-io/building-a-control-plane-for-envoy-7524ceb09876) — "In this series of blogs, we will share our experience of building Gloo, a multi-purpose control plane for the Envoy proxy. The first blog in the series will focus on Envoy design, and the technical architecture decisions we needed to make while building the first layer of the control plane."

[Getting started with Git and GitHub: the complete beginner's guide](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6) — Git and GitHub basics for the curious and completely confused (plus the easiest way to contribute to your first open source project ever!)

[How rootless Buildah works: Building containers in unprivileged environments](https://opensource.com/article/19/3/tips-tricks-rootless-buildah)

[Load Balancing and Reverse Proxying for Kubernetes Services](https://medium.com/@chamilad/load-balancing-and-reverse-proxying-for-kubernetes-services-f03dd0efe80) — Different load balancing and reverse proxying strategies to use in Production K8s Deployments to expose services to outside traffic

[Red Hat, AWS, Google, Microsoft Launch Kubernetes Operator Registry](https://www.datacenterknowledge.com/open-source/aws-google-microsoft-red-hats-new-registry-act-clearing-house-kubernetes-operators) — "Operators make life easier for Kubernetes users, but they're so popular that finding good ones is not easy. Operatorhub.io is an attempt to fix that."

[CoreDNS-1.4.0 Release](https://coredns.io/2019/03/03/coredns-1.4.0-release/) — My favorite DNS server's first release since CoreDNS became a graduated CNCF project.

[aiven/pghoard](https://github.com/aiven/pghoard) — PostgreSQL backup and restore service

[Microsoft/frontend-bootcamp](https://github.com/Microsoft/frontend-bootcamp) — Frontend Workshop from HTML/CSS/JS to TypeScript/React/Redux

[derailed/k9s](https://github.com/derailed/k9s) — Kubernetes CLI To Manage Your Clusters In Style! (I love this tool)

## DevOps'ish Tweet of the Week

{{< tweet 1103746792850669568 >}}

Notes from this week's issue can be found [here](./notes/).
