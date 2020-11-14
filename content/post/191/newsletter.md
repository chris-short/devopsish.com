+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-11-08T07:00:00Z
description = "On Dan Kohn's Passing, NAT slipstreaming, Raspberry Pi 400, Python overtakes Java, container registries, Raspberry Pi 400, and more"
draft = false
slug = "191"
tags = ["Dan Kohn", "CNCF", "Cloud Native Computing Foundation", "community", "Kubernetes", "Linux", "DevOps", "monitoring", "Docker", "open source", "service", "Travis CI", "security", "family", "GitHub", "Java", "Python", "Raspberry Pi 400", "technology", "kernel", "KubeCon", "CKS", "distributed", "microservices", "tracing", "NAT slipstreaming", "Ant Group IPO"]
title = "DevOps'ish 191"

+++

*As written for [my website](https://chrisshort.net/on-the-passing-of-dan-kohn/), a version of which is also [here](https://github.com/cncf/memorials/blob/master/dan-kohn.md).*

I woke Sunday morning to some very sad news. We've had a tragic loss in the cloud native community. [Last weekend we lost Dan Kohn](https://twitter.com/DrOceanJulie/status/1322957062444326919). Dan Kohn is the former Executive Director of Cloud Native Computing Foundation and was leading up COVID-19 response for the Linux Foundation. He passed away after [losing his battle with stage four colon cancer](https://www.dankohn.com/health). Dan's passing happened far too soon. I knew Dan was battling something, but we hadn't been in the same place for quite some time. It's not one of those things you necessarily want to initiate a conversation about either. I did not know of Dan's blog about it until he was gone. I would encourage all of us to look at our physical ailments as we age (perhaps more rapidly because of 2020) to take care of ourselves.

To Dan's family and his kids, we are here. I'm very sorry for your loss. Our condolences go out to you on behalf of the cloud native community. We are very sorry, and we're here to let you know that we will be there as you need us. Please do not hesitate to reach out, reach out to me if you need anything at all.

Dan and I didn't always see eye to eye on things. That was probably a healthy thing for the community and maybe not so much our relationship. But, Dan Kohn (along with CNCF) saved my career in 2017. I was coming out of a role I left due to several reasons. The day before Thanksgiving, the company I was starting with the coming Monday rescinded their offer after a fairly long courtship. Jobless, as the sole breadwinner in your household, is never where you want to be. I knew I needed to be at KubeCon the following week to job hunt and network. After naively asking on Twitter how I could somehow procure a ticket. Dan DM'd me for details, made sure I had what I needed once I got to Austin, and covered the hotel so I could actively job hunt and network without the guilt of leaving the family behind. That trip [lead to me becoming a CNCF Ambassador](https://chrisshort.net/chris-short-named-cloud-native-ambassador/) (thank you goes to Jorge Castro for telling me to apply).

Dan stuck up for Ambassadors too, even in the face of enormous pressure. We are humans; we aren't robots. If we shared opinions about [Docker](https://chrisshort.net/docker-inc-is-dead/), yes, we might get a phone call one day from the head of CNCF while we're both at airports (I was at Logan, he was at Kennedy and we were both outside getting into cabs, if memory serves) asking to put a disclaimer at the top. But, CNCF members have fundamental human rights; Dan was never going to censor an ambassador. That let me know I was in the right place. I needed to put even more effort into this community. To give back for helping my family and me in our time of need. We don't forget things like Dan getting me into KubeCon Austin 2017 or telling Docker people can share their opinions.

Dan was one of the folks out there trying to take the skills and talents they had to try to make the world a better place. Agree or disagree on anything, sure. But, I respect the hell out of someone like Dan. His impact has been made. Dan Kohn's legacy is a sea change in the technology landscape like the world hadn't seen since the introduction of the Linux kernel. Dan will truly be missed.

Other articles on Dan's passing:

* [A Tribute to Dan Kohn - CD Foundation](https://cd.foundation/blog/2020/11/03/a-tribute-to-dan-kohn/)
* [CNCF Statement on the Passing of Dan Kohn | Cloud Native Computing Foundation](https://www.cncf.io/blog/2020/11/02/cncf-statement-on-the-passing-of-dan-kohn/)
* [Mourning Dan Kohn [LWN.net]](https://lwn.net/Articles/835839/rss)
* [An Open Source Leader Is Gone, a Remembrance of Dan Kohn - The New Stack](https://thenewstack.io/an-open-source-leader-is-gone-a-remembrance-of-dan-kohn/)

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

## People

[The world needs women who code](https://www.redhat.com/sysadmin/women-who-code)  
"How can we motivate more women to get into the technology field?"

[Yes, Virtual Presenting Is Weird](https://hbr.org/2020/11/yes-virtual-presenting-is-weird)  
Yeah, it's a little weird but, after almost 300 hours of live streaming, I can tell you that getting comfortable with the camera is key. Make that lens the audience you're talking to from up on stage. And yes, sitting is totally fine, as is standing. Whatever you do, be you, don't try to be someone you aren't. Authenticity goes a long way digitally.

[The Tech Antitrust Problem No One Is Talking About](https://www.wired.com/story/tech-antitrust-problem-no-one-talking/)
"Americans pay more for broadband internet service and have fewer choices than consumers in other countries." This is reinforced by corruption. We need competent leadership to fix this problem.

[A Simple Tactic That Could Help Reduce Bias in AI](https://hbr.org/2020/11/a-simple-tactic-that-could-help-reduce-bias-in-ai)
"It’s easier to program bias out of a machine than out of a mind."

[The ultimate curated resources for Certified Kubernetes Security Specialist "CKS"](https://dev.to/walidshaari/the-ultimate-curated-resources-for-certified-kubernetes-security-specialist-cks-410l)  
Educate yourself! Kubernetes genius Walid Shaari breaks down how to get CKS certified.

## Process

People might say traces can be used anywhere, but let’s face it: you absolutely need them when you’re dealing with distributed systems and microservices. You probably don’t have them yet because instrumenting your apps to collect them will get you super table-flippy. (╯°□°)╯︵ ┻━┻

Until now.

Download [Distributed Tracing: A Guide to Microservices & More](https://info.honeycomb.io/distributed-tracing-with-honeycomb-lp-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=distributed-tracing-guide-for-microservices-and-more-honeycomb-lp-devopsish) and get the tracing you deserve the easy peasy way. Guess less & know more with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Samy Kamkar - NAT Slipstreaming](https://samy.pl/slipstream/)  
Great... "[NAT Slipstreaming](https://github.com/samyk/slipstream) allows an attacker to remotely access any TCP/UDP service bound to a victim machine, bypassing the victim's NAT/firewall (arbitrary firewall pinhole control), just by the victim visiting a website."

[Ant Group to refund $2.8 trillion in Shanghai IPO bids](https://technode.com/2020/11/06/ant-group-to-refund-2-8-trillion-in-shanghai-ipo-bids/)  
"Jack Ma told a crowd of Chinese regulators and financiers that China suffers from overbearing regulation." And the CCP got **pissed**.

[Linux Looks To Change The Default For Some Of Its Spectre Mitigations](https://www.phoronix.com/scan.php?page=news_item&px=Linux-Spectre-SECCOMP-Default)  
"Andrea Arcangeli of Red Hat has laid out a proposal to avoid the SECCOMP default and instead turn the default behavior to that of opting in by the prctl interface. This change would lead to the same affect as booting any current Linux kernel release with the options of 'spec_store_bypass_disable=prctl spectre_v2_user=prctl.'"

[Neustar Agrees to Buy Verisign's Public DNS Service](https://www.darkreading.com/perimeter/neustar-agrees-to-buy-verisigns-public-dns-service/d/d-id/1339359)  
Whew! I was a little worried this was going to be bungled but, "The address space for Verisign Public DNS will be incorporated into Neustar's UltraDNS Public service following the acquisition." I feel like that's about as good as we can ask for here.

[RIAA Takedowns Backfire as Pirated MP3s Now Surface on GitHub](https://torrentfreak.com/riaa-takedowns-backfire-as-pirated-mp3s-now-surface-on-github-201104/)  
🤣🤣🤣 I love this. But, I have a daily need for youtube-dl, downloading backups of live streams. I will happily distribute the source myself if it comes to it.

[D2iQ Takes the Next Step Forward](https://d2iq.com/blog/d2iq-takes-the-next-step-forward)  
Kubernetes slays another orchestrator.

## Tools

[Oh Dear, uptime monitoring like no other](https://ohdear.app/)  
With Oh Dear, you get uptime monitoring, SSL certificate alerts, performance monitoring and we'll crawl your entire site, reporting 404's, server errors and more. With our unlimited status pages and cron job monitoring, Oh Dear is all the monitoring you'll ever need. Sign up with code DEVOPSISH and get a 30% discount on your first 3 months. *SPONSORED*

[Git & GitHub](https://www.ladybug.dev/episodes/git-and-github)  
"Git is both simple and complex. You can usually get through your workday by memorizing a few commands, but under the hood there’s so much more to it. Today we will dive deep into Git with a special guest, Monica Powell. Let’s dive in!"

[Python overtakes Java to become the second-most popular programming language](https://www.techrepublic.com/article/python-overtakes-java-to-become-the-second-most-popular-programming-language/)  
"For the first time in the history of TIOBE's index, Java has slipped out of the top two, leaving Python to occupy the spot behind reigning champion, C." This is pretty significant given the massive install base Java has.

[VMware Tools Is Now a Separate Product](https://blogs.vmware.com/vsphere/2020/11/vmware-tools-is-now-its-own-product.html)  
This will impact many a vSphere admin and user.

[Advice for customers dealing with Docker Hub rate limits, and a Coming Soon announcement](https://aws.amazon.com/blogs/containers/advice-for-customers-dealing-with-docker-hub-rate-limits-and-a-coming-soon-announcement/)  
"Within weeks, AWS will deliver a new public container registry that will allow developers to share and deploy container images publicly. This new registry will allow developers to store, manage, share, and deploy container images for anyone to discover and download." Getting off Docker Hub should be a strategic priority if you haven't yet.

[Travis CI's new pricing plan threw a wrench in my open source works](https://www.jeffgeerling.com/blog/2020/travis-cis-new-pricing-plan-threw-wrench-my-open-source-works)  
Travis CI's pricing changes have impacted quite a few folks. I can't think of a person with more Travis CI projects churning away than Jeff Geerling. Here's the impact its had on his day-to-day operations. I would say getting off Travis CI is probably a good idea too.

[Running Percona Kubernetes Operator for Percona XtraDB Cluster with Kata Containers](https://www.percona.com/blog/2020/11/04/running-percona-kubernetes-operator-for-percona-xtradb-cluster-with-kata-containers/)  
"Running databases in containers is an ongoing trend and keeping data safe is always the top priority for a business. Kata containers provide security isolation through mature and extensively tested qemu virtualization with little-to-none changes to the existing environment."

[metal3-io/baremetal-operator](https://github.com/metal3-io/baremetal-operator)  
Bare metal host provisioning integration for Kubernetes

[Using WireGuard to Extend OpenShift Networks](https://www.openshift.com/blog/using-wireguard-to-extend-openshift-networks)  
"How can we enable hardware from any lab to be added to our clusters on different networks? What we have done in these instances is use WireGuard as an overlay network to bridge the private lab networks via the public network."

[Announcing Vitess 8](https://vitess.io/blog/2020-10-27-announcing-vitess-8/)  
"In this release, we have continued to make important improvements to the Vitess project with over 200 PRs in several areas. Some of the major bug fixes and changes in behaviors are documented in the Release Notes. Please read them carefully and report any issues via GitHub. We would like to highlight the following themes for this release."

[Benchmarking The Raspberry Pi 400 - A Raspberry Pi Keyboard Computer](https://www.phoronix.com/scan.php?page=article&item=raspberry-pi-keyboard&num=1)  
Nifty looking and affordable the Raspberry Pi 400 looks super cool. But, I've got too many low powered computers already.

[SiFive unveils plan for Linux PCs with RISC-V processors](https://venturebeat.com/2020/10/29/sifive-unveils-plan-for-linux-pcs-based-on-risc-v-processors/)  
Speaking of new tiny PCs...

[rbtnn/vim-mario](https://github.com/rbtnn/vim-mario)  
Mario on Vim

[BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep)  
ripgrep recursively searches directories for a regex pattern while respecting your gitignore

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week from @JoeBiden](/images/191-devopsish-tweet-of-the-week.png)](https://twitter.com/JoeBiden/status/1325118992785223682)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/191/notes/) to see what didn't make it to the newsletter.
