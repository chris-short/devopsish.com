+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-01-07T07:01:02.584Z
description = ""
draft = false
slug = "057"
tags = ["devops", "cloud native", "open source", "kubernetes", "intel", "linux", "spectre"]
title = "057: The Spectre of Meltdown, 20 Years of Open Source, Docker Deathwatch, Kubernetes..."
image = "/057/patty-melt-by-dale-cruse.jpg"
imagealt = "It's a Patty Melt. Get it?"
imagecap = "[patty melt](https://www.flickr.com/photos/dalecruse/28295053371) by Dale Cruse"
aliases = [
    "devopsish-057-the-spectre-of-meltdown-20-years-of-open-source-docker-deathwatch-kubernetes-5e516fb90d00"
]

+++

Is anything going on in the InfoSec arena this week? I couldn't tell. If you have been under a rock this week I have some news for you. There are two vulnerabilities in CPU designs that essentially put everything we thought we knew about computer security on its head. [Meltdown and Spectre](https://meltdownattack.com/) are vulnerabilities affecting virtually all modern CPUs. I don't think I could ever visualize a complete picture of all the vulnerable systems that are impacted. But, to put it in perspective, my first Windows PC was a used Dell something or other with a 486 DX2 66 MHz CPU I got back in 1995. If I still had it, I would not need to patch it. But, if you have a 120 MHz Intel Pentium CPU based system laying around, it's impacted.

The blast radius of these vulnerabilities is massive. Considering that, I am making a new section of the newsletter this week dedicated to Meltdown and Spectre. The reason for this is twofold: 1) There's so much information in this space it could be a newsletter edition all by itself. 2) You might have some fatigue from these vulnerabilities. I don't want you to skip over other awesome things in the newsletter. Scroll down past Tools for the Meltdown and Spectre section. Stay vigilant, keep your eyes open for patches, and rest assured [**Linus is PISSED**](http://www.businessinsider.com/linus-torvalds-linux-inventor-is-furious-at-intel-2018-1).

Two personal notes:

1. I ran my first Kubernetes Community meeting this week (and it was awesome)! Kubernetes 1.10 is coming Wednesday, March 21st.
2. I have some job news coming very soon so stay tuned to [chrisshort.net](https://chrisshort.net/).

[**GoCD — Open Source Continuous Delivery Server**](https://devopsish.us14.list-manage.com/track/click?u=631fcd11ad2a643d08035c221&id=5a1471dfb5&e=7cc492dc98)  
GoCD is a continuous delivery tool supporting modern infrastructure with elastic on-demand agents and cloud deployments. With GoCD, you can easily model, orchestrate and visualize complex workflows from end to end. [It's open source, free to use and download](https://devopsish.us14.list-manage.com/track/click?u=631fcd11ad2a643d08035c221&id=3133731028&e=7cc492dc98). *SPONSORED*


## People

[Vincent Batts: An Open Source Career from KDE to OCI](https://thenewstack.io/vincent-batts-kde-oci/): Vincent is a friend, and an absolutely wonderful person. It's awesome to see him get the recognition he deserves.

[20 years of the Open Source Initiative (OSI)](http://www.computerweekly.com/blog/Open-Source-Insider/20-years-of-Open-Source-Initiative-OSI): The 'open source' label itself was created at a strategy session held by members of the group that we now call the Open Source Initiative (OSI) on February 3rd, 1998 in Palo Alto, California USA.

[What Would Really Happen If Russia Attacked Undersea Internet Cables](https://www.wired.com/story/russia-undersea-internet-cables/)

[How and why we teach non-engineers to use GitHub at Thread](https://thread.engineering/teaching-non-engineers-how-to-contribute-code-2e85411ab464)

[Taking the Certified Kubernetes Administrator Exam](https://medium.com/@KevinHoffman/taking-the-certified-kubernetes-administrator-exam-eeab17d65476)

[Top 21 conferences for DevOps and sysadmins in 2018](https://www.hpe.com/us/en/insights/articles/2018/01/top-21-conferences-for-devops-and-sysadmins-in-2018.html)

[What I learned in 2017 Writing Go](https://www.commandercoriander.net/blog/2017/12/31/writing-go/)

["Oh My God, This Is So F — -ed Up": Inside Silicon Valley's Secretive, Orgiastic Dark Side](https://www.vanityfair.com/news/2018/01/brotopia-silicon-valley-secretive-orgiastic-inner-sanctum)

[2017 SRE & DevOps Influencers](https://robhirschfeld.com/2018/01/01/2017-sre-devops-influencers/)

## Process

[Docker, Inc isn't Dead](https://blog.iron.io/docker-inc-isnt-dead/): Dylan Stamat of iron.io responded to my [**Docker Inc is Dead**](https://chrisshort.net/docker-inc-is-dead/) story. I'm not quite sure Dylan's response is outright disproving anything I wrote (it might actually reinforce it) but, it's interesting to see opposing opinions.

[The evolution of Fastly's Open Source and Nonprofit Program: supporting an ethical and open internet](https://www.fastly.com/blog/evolution-fastlys-open-source-and-nonprofit-program-supporting-an-ethical-and-open-internet/)

[The Limitations of Chaos Engineering](https://medium.com/production-ready/the-limitations-of-chaos-engineering-2a74816c0df3): It's evident that Chaos Engineering has become a technology trend, with more and more companies adopting it.

[Creative ways to encourage the integration of DevOps processes](http://www.theserverside.com/feature/Creative-ways-to-encourage-the-integration-of-DevOps-processes)

[Selecting a Cloud Provider](https://codeascraft.com/2018/01/04/selecting-a-cloud-provider/) by Etsy

[The future of DevOps is mastery of multi-cloud environments](https://opensource.com/article/18/1/future-devops)

[It's 2018 and your Docker containers need to be secure](https://blog.cloudpassage.com/2018/01/02/2018-docker-containers-need-secure/)

## Tools

[The DevOps Glossary](https://caylent.com/devops-glossary/): Whether you're new to the world of DevOps or a seasoned guru looking to brush up on pesky terminology, look no further. This glossary covers some of the core definitions you and your team need to know.

[Staging endpoint for ACME v2](https://community.letsencrypt.org/t/staging-endpoint-for-acme-v2/49605): The Let's Encrypt wildcard certs are coming.

[7 systems engineering and operations trends to watch in 2018](https://www.oreilly.com/ideas/7-systems-engineering-and-operations-trends-to-watch-in-2018?cmp=tw-webops-confpro-info-vlca18_2018_trends)

[9 New Programming Languages To Learn In 2018](https://www.rankred.com/new-programming-languages-to-learn/)

[Top 5: Best of 2017, the future of DevOps, and more](https://opensource.com/article/18/1/top-5-january-5)

[Get Started with Spinnaker on Kubernetes](https://thenewstack.io/getting-started-spinnaker-kubernetes/): A walkthrough on how to run Spinnaker on Minikube.

[A Brief History of sed](https://blog.sourcerer.io/a-brief-history-of-sed-6eaf00302ed): Their story is interesting, not least because it can't be told without mentioning many acknowledged giants of computer science. It's especially interesting when you interpret it in the context of all the other emerging parts of the nascent UNIX ecosystem that were also in motion at the time.

[Kubernetes, OpenShift build hybrid cloud outside Silicon Valley](https://siliconangle.com/blog/2018/01/02/kubernetes-openshift-build-hybrid-cloud-outside-silicon-valley-kubecon/)

[These Kubernetes developments make the platform ripe to explode in 2018](https://www.techrepublic.com/article/these-kubernetes-developments-make-the-platform-ripe-to-explode-in-2018/)

[kubernetes-incubator/kube-arbitrator](https://github.com/kubernetes-incubator/kube-arbitrator): kube-arbitrator provides policy based resource sharing for a Kubernetes cluster.

[samoshkin/docker-letsencrypt-certgen](https://github.com/samoshkin/docker-letsencrypt-certgen): Docker image allowing to generate, renew, revoke RSA and/or ECDSA SSL certificates from LetsEncrypt CA using certbot and acme.sh clients in automated fashion.

[khenidak/dysk](https://github.com/khenidak/dysk): Dysk mounts Azure disks as Linux block devices directly on VMs without dependency on the host. Dysks can be used within Azure VMs or on-prem machines.

[alexellis/mine-with-docker](https://github.com/alexellis/mine-with-docker): This repository contains Docker images that lets you get from zero to mining in around 5 minutes on any Linux host anywhere.

## Meltdown and Spectre

[Intel's CEO reportedly sold shares after the company already knew about massive security flaws](https://www.cnbc.com/2018/01/04/intel-ceo-reportedly-sold-shares-after-the-company-already-knew-about-massive-security-flaws.html)

[Nearly Every Computer Made Since 1995 Is Dangerously Flawed. Here's What You Need to Know.](http://nymag.com/selectall/2018/01/intel-chip-security-flaw-meltdown-spectre-what-to-know-explainer.html) ([I tech reviewed this article](https://twitter.com/JakeSwearingen/status/949003894000181248) before it was published)

["Meltdown" and "Spectre": Every modern processor has unfixable security flaws](https://arstechnica.com/gadgets/2018/01/meltdown-and-spectre-every-modern-processor-has-unfixable-security-flaws/)

[Apple Says All Macs, iPhones and iPads Exposed to Chip Security Flaws](https://www.bloomberg.com/news/articles/2018-01-05/apple-says-all-macs-iphones-ipads-exposed-to-chip-flaw)

[An Update on AMD Processor Security](https://www.amd.com/en/corporate/speculative-execution)

[Arm Processor Security Update](https://developer.arm.com/support/security-update)

[Processor Speculative Execution Research Disclosure](https://aws.amazon.com/security/security-bulletins/AWS-2018-013/) via AWS

[A collection of Meltdown/Spectre postings](https://lwn.net/Articles/742999/) via LWN.net

[Addressing Meltdown and Spectre in the kernel](https://lwn.net/SubscriberLink/743265/df1eea5a556de4d4/) via LWN.net

[Guide to Meltdown / Spectre CPU Vulnerabilities](http://help.packet.net/technical/infrastructure/guide-to-meltdown-spectre-cpu-vulnerabilities) via Packet

[Why Raspberry Pi isn't vulnerable to Spectre or Meltdown](https://www.raspberrypi.org/blog/why-raspberry-pi-isnt-vulnerable-to-spectre-or-meltdown/): "Both vulnerabilities exploit performance features (caching and speculative execution) common to many modern processors to leak data via a so-called side-channel attack. Happily, the Raspberry Pi isn't susceptible to these vulnerabilities, because of the particular ARM cores that we use."

[How a researcher hacked his own computer and found 'worst' chip flaw](http://www.reuters.com/article/us-cyber-intel-researcher/how-a-researcher-hacked-his-own-computer-and-found-worst-chip-flaw-idUSKBN1ET1ZR)

[Intel Issues Updates to Protect Systems from Security Exploits](https://newsroom.intel.com/news-releases/intel-issues-updates-protect-systems-security-exploits/)

[Mitigations landing for new class of timing attack](https://blog.mozilla.org/security/2018/01/03/mitigations-landing-new-class-timing-attack/) via Mozilla

[Initial Benchmarks Of The Performance Impact Resulting From Linux's x86 Security Changes](https://www.phoronix.com/scan.php?page=article&item=linux-415-x86pti&num=1)

[Intel facing multiple class action suits over chip security flaw](https://www.theverge.com/2018/1/5/16853732/intel-meltdown-spectre-cpu-vulnerability-class-action-suits): As you can imagine, Linus is not the only one pissed about Meltdown and Spectre.

[Why Intel x86 must die: Our cloud-centric future depends on open source chips](http://www.zdnet.com/article/why-intel-x86-must-die-our-cloud-centric-future-depends-on-open-source-chips-meltdown/)

[Speculative Execution Exploit Performance Impacts — Describing the performance impacts to security patches for CVE-2017–5754 CVE-2017–5753 and CVE-2017–5715](https://access.redhat.com/articles/3307751)

dig +short txt istheinternetonfire.com

## DevOps'ish Tweet of the Week

> Fun new game this week: Figure out if your Chrome CPU usage is so high because of a JavaScript cryptominer delivered through a compromised ad, or if someone is dumping your kernel memory with JavaScript delivered through a compromised ad.

— SwiftOnSecurity (@SwiftOnSecurity) [January 4, 2018](https://twitter.com/SwiftOnSecurity/status/948750329646075905?ref_src=twsrc%5Etfw)
