+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-02-02T07:00:00Z
description = "Change at IBM and Red Hat, flaunt your Kubernetes knowledge, WireGuard, Tailscale, Azure, nmap, podman, and more"
draft = false
slug = "165"
tags = ["DevOps", "Kubernetes", "open source", "IBM", "Red Hat", "cloud", "cloud native", "Linux", "WireGuard", "Tailscale", "security", "scale", "engineer", "community", "nmap", "podman", "VPN", "Azure", "microservice", "Michigan", "Chinese", "coronavirus", "trends", "funding", "observability"]
title = "165: Change at IBM and Red Hat, flaunt your Kubernetes knowledge, WireGuard, Tailscale, Azure, nmap, podman, and more"

+++

A change at the helms of IBM and Red Hat are occurring in April [(IBM press release)](https://newsroom.ibm.com/2020-01-30-Arvind-Krishna-Elected-IBM-Chief-Executive-Officer). Ginni Rometty is retiring (after a short period as Executive Chairman). [Ginny is the only woman to have ever led IBM](https://www.washingtonpost.com/business/technology/ibm-ceos-over-the-century-first-and-only-woman-is-leaving/2020/01/30/643d0b86-43b6-11ea-99c7-1dfd4241a2fe_story.html) which is a feat all by itself. She had the unenviable job of leading IBM out of its funk too. [IBM had really good numbers this quarter](https://www.fool.com/investing/2020/01/29/ibm-is-big-blue-set-for-sustained-growth.aspx). Whether that continues remains to be seen but, it's noteworthy that it happened under Ginny's watch. It happened after she made her big move too; [one of the largest acquisitions ever](https://devopsish.com/ibm-red-hat-acquisition-index/). It's a little sad but we definitely knew it was going to happen at some point, [Jim Whitehurst is leaving Red Hat to take on the role of President of IBM](https://www.forbes.com/sites/jonobacon/2020/01/31/jim-whitehurst-becomes-president-of-ibm-why-he-gets-culture/#7a3611146394). It will be interesting to see what Jim can do in IBM's leadership. It will be interesting to see what happens in the Red Hat leadership too. It's going to be a fun, change filled year!

{{< tweet 1223255909373239299 >}}

## Events

[February 2020 Michigan Tech Events](https://cronicle.press/2020/01/27/february-2020-michigan-tech-events/) — If you're in Michigan this month, check out one of these awesome tech events while you're here. Also, the [Orchestructure](https://orchestructure.io/) meetup is the last Wednesday of the month and is always filled with Kubernetes nerds.

[SCALE 18x](https://www.socallinuxexpo.org)  
March 5-8, 2020  
SCaLE 18x – the 18th annual Southern California Linux Expo – will take place in March 5-8, 2020, at the Pasadena Convention Center. SCaLE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. SCaLE 18X expects to host 120 exhibitors this year, along with over 200 sessions, tutorials and special events. From kernels to containers, beginner installs to advanced security, HAMs to clouds, there is something for you at SCALE 18X.

[DevOpsDay LA](https://devopsdays.org/events/2020-los-angeles/)  
March 6, 2020  
DevOpsDay LA is a technical conference covering topics of software development, IT infrastructure operations, and the intersection between them.

[Kubernetes Contributor Summit Europe](https://events.linuxfoundation.org/kubernetes-contributor-summit-europe/) — Come learn some Kubernetes with me from some of the best people on earth to teach it. Also, get real work done in the community with folks right there in the room with you!

[A few days can make a lasting impact.](https://www.oreilly.com/pub/cpc/295841)  
I'm speaking at the O'Reilly Infrastructure & Ops Conference this year. But, did you know O'Reilly has a series of conferences geared towards every DevOps'ish reader? Did you know you can speak at these conferences too? Have a look and see what might interest you. *SPONSORED*

## People

[If You’ve Got It, Flaunt It — Kubernetes Experience, That Is](https://www.sdxcentral.com/articles/news/if-youve-got-it-flaunt-it-kubernetes-experience-that-is/2020/01/) — "There is no better time than the present for IT professionals with Kubernetes experience to flaunt what they’ve got. According to Indeed’s findings, the top tech roles of Kubernetes jobs included DevOps engineers, senior software engineers/ software engineers, software architects, cloud engineers, and full stack developers."

[Idit Levine Discussing Gloo, Service Mesh Interface, and Web Assembly Hub](https://www.infoq.com/podcasts/gloo-smi-webassembly/) — When Idit Levine speaks, it's wise to listen (or at least read). The work she has been doing will be things we're all embracing to some degree by the end of the year.

[I wrote Go code for 3 weeks and you won't believe what happened next](https://danlark.org/2020/01/31/i-wrote-go-code-for-3-weeks-and-you-wont-believe-what-happened-next/) — "Go is (almost) easy to learn", "Go is pretty performant", and "if you want to do something complex, Go won’t let you do this anyhow." 👀👀👀

[Life as a reporter trapped in Hubei, ground zero of the coronavirus outbreak](https://www.scmp.com/tech/apps-social/article/3048383/life-tech-reporter-trapped-hubei-ground-zero-coronavirus-outbreak) — "My parents, who had become accustomed recently to reading the news on their phones via Jinri Toutiao, a popular Chinese news aggregator app run by Beijing-based tech unicorn ByteDance, have gone back to watching TV amid a welter of fake news and rumours about the coronavirus circulating online." While others flooded game servers and app stores.

[Joining Tailscale](https://bradfitz.com/2020/01/30/joining-tailscale) — Brad Fitzpatrick has left Google to join Tailscale. I mentioned WireGuard on Twitter this week (and later in this newsletter) and was told about Tailscale by someone I regard highly for good software choices. I did a tiny bit of digging. I couldn't find out much about the company (the tech is WireGuard based). It's great that I could install Tailscale everywhere but, who is funding or how is it making money for a private company? That's the biggest concern I have about Tailscale. I suspect we'll find out soon enough.

[Keep Up with Technology Trends as a Tech Leader](https://codingsans.com/blog/keep-up-with-technology-trends) — This is a good list! I've already read half the books so ingesting everything else should be just a matter of organizing.

[How an SRE became an Application Security Engineer (and you can too)](https://breanneboland.com/blog/2020/01/27/how-an-sre-became-an-application-security-engineer-and-you-can-too/) — Breanne Boland is a super smart person. If you want to become a full-fledged security engineer, it's all laid out for you here.

[Azure DevOps Podcast: Emily Freeman on Modern DevOps](http://azuredevopspodcast.clear-measure.com/emily-freeman-on-modern-devops-episode-72) — My friends on podcasts make me happy.

## Process

[Observability Trends in 2020: The DevOps Pulse 2019 Results](https://logz.io/blog/devops-pulse-2019-announcement/) — The report highlights a few noteworthy things like the obvious, "Tool sprawl is a significant and widespread issue for software engineers" and the not so obvious "*As DevOps has become mainstream*, R&D teams are sharing the responsibility for observability across multiple roles" (emphasis mine). DevOps is mainstream now. 🎉🥳👏

[Jim Zemlin: The Linux Foundation Will Establish TARS Foundation, Focuses on Microservice Ecosystem](http://tarscloud.org/feeds/5268217533827955) — "Tencent's open source project TARS will set up a separate TARS foundation in 2020. This will be the first international open source foundation originated from a Chinese open source project and will also be the Linux fund. The only sub-foundation focusing on the ecology of microservice technology."

[Security at Cloud-native Speed (On-Demand)](https://security.stackrox.com/2020_01-Sec-at-C-N-Speed-Webinar_300-Registration-On-Demand.html?LSource=CS&Source=CS) — I mentioned during KubeCon San Diego that I was doing a Security at Cloud Native Speed booth talk for StackRox. They were cool enough to get me on a webinar with them to discuss it with a broader audience. My intent is to add hands-on examples for each lever in the toolkit and submit that talk to conferences. Please, tell me what you think!

[CacheOut](https://cacheoutattack.com/) — The next of what will be many speculative execution attacks.

[Is everything OK over there, Britain? Have you tried turning the UK off and on again? ISPs, financial orgs fall over in Freaky Friday of outages](https://www.theregister.co.uk/2020/01/31/uk_internet_outages/) — Brexit happened on Friday and for a while there it seemed like it really was gonna be a hard one as outage after outage occurred.

[Latest Jepsen Results against etcd 3.4.3](https://etcd.io/blog/jepsen-343-results/) — Jepsen highlighted some areas of improvement and strengths of the be~~loave~~loved `etcd`.

[How we retired Python 2 and improved developer happiness](https://engineering.linkedin.com/blog/2020/how-we-retired-python-2-and-improved-developer-happiness) — Some great knowledge being shared in this piece. Some very real lessons learned.

[CI/CD for Machine Learning](https://www.infoq.com/presentations/ci-cd-ml/) — "Sasha Rosenbaum shows how a CI/CD pipeline for Machine Learning can greatly improve both productivity and reliability"

[Hapless AWS engineer spilled passwords, keys, confidential internal training info, customer messages on public GitHub](https://www.theregister.co.uk/2020/01/23/aws_engineer_credentials_github/) — This is pretty bad. But, I did just give a vendor a guest account on one of my monitoring platforms. I don't think this is as uncommon as people think.

[(A few) Ops Lessons We All Learn The Hard Way](https://www.netmeister.org/blog/ops-lessons.html)

## Tools

[Basic network troubleshooting in Linux with `nmap`](https://www.redhat.com/sysadmin/nmap-troubleshooting) — `nmap` was the first open source project I ever contributed to (in 199-something). I have used it extensively across my career to make networks more secure. It is not a tool for evil like a lot of companies treat it. If your engineering teams aren't using nmap on the systems and services they're building, they are doing your organization a disservice. Teach yourself [nmap](https://nmap.org/).

[Enable basic podman support. by amwat · Pull Request #1302 · kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind/pull/1302) — If KinD could use podman instead of Docker, holy smokes that would be so awesome!

[Systemd-Homed Merged As A Fundamental Change To Linux Home Directories](https://www.phoronix.com/scan.php?page=news_item&px=Systemd-Homed-Merged) — systemd continues to take over everything.

[How to run Podman on Windows with WSL2](https://www.redhat.com/sysadmin/podman-windows-wsl2) — It's easier to run podman on Windows than it is Mac. 🤔🤔🤔

[Using Red Hat Universal Base Image with Azure Pipelines and Red Hat Quay.io](https://www.redhat.com/en/blog/using-red-hat-universal-base-image-azure-pipelines-and-red-hat-quayio) — I love the Universal Base Images and the rigor that goes into making those things solid. You should use UBI wherever it makes sense, including Azure (which is wild to be saying when I think back ten years ago).

[Make resilient Go net/http servers using timeouts, deadlines and context cancellation](https://ieftimov.com/post/make-resilient-golang-net-http-servers-using-timeouts-deadlines-context-cancellation/) — This is pretty good stuff. The basic [ssl-tester](https://github.com/chris-short/ssl-tester) I wrote doesn't use any of these concepts and is an absolutely unpredictable beast when hardware changes.

[WireGuard VPN Protocol Coming to a Linux Kernel Near You](https://thenewstack.io/wireguard-vpn-protocol-coming-to-a-linux-kernel-near-you/) — It looks like I'm going to be switching over to a WireGuard VPN solution very soon.

[Building a simple VPN with WireGuard with a Raspberry Pi as Server](https://snikt.net/blog/2020/01/29/building-a-simple-vpn-with-wireguard-with-a-raspberry-pi-as-server/) — This guide and a container or two are going to help me switch over to WireGuard

[Automated IDOR Discovery through Stateful Swagger Fuzzing](https://engineeringblog.yelp.com/2020/01/automated-idor-discovery-through-stateful-swagger-fuzzing.html) — "Today, we’re excited to announce that we’ll be open-sourcing `fuzz-lightyear`: a testing framework we’ve developed to identify Insecure Direct Object Reference (IDOR) vulnerabilities through stateful Swagger fuzzing, tailored to support an enterprise, microservice architecture."

[perlin-network/noise](https://github.com/perlin-network/noise) — A decentralized P2P networking stack written in Go.

[CERN ends trial of Facebook Workplace](https://home.cern/news/news/computing/cern-ends-trial-facebook-workplace) — CERN is switching to Mattermost.

[KubeOperator/webkubectl](https://github.com/KubeOperator/webkubectl) — Run kubectl command in Web Browser

[estesp/manifest-tool](https://github.com/estesp/manifest-tool) — Manifest tool for manifest list object creation/query

[Tekton in 2020 and beyond!](https://cd.foundation/blog/2020/01/28/tekton-in-2020-and-beyond/) — Tekton had a big 2019 and is showing mad love to the folks that made it all happen.

[Scheduled PostgreSQL Backups and Retention Policies with Kubernetes](https://info.crunchydata.com/blog/schedule-postgresql-backups-and-retention-with-kubernetes) — Jonathan Katz: When it comes to advising on running databases on Kubernetes, accept no substitutes.

[Operator SDK: Getting Started Guide](https://keithtenzer.com/2020/01/27/openshift-operator-sdk-getting-started-guide/) — This walkthrough is amazing. Operators are super powerful and the fact that a lot of the scaffolding is built out by the Operator SDK really makes it worth the time it takes to learn the concepts.

[Kronos-Android: Easy NTP](https://eng.lyft.com/kronos-android-easy-ntp-d44fd6ece9c5) — Lyft taught me that Android devices have an insane time drift across the diverse landscape of devices using it. They built their own solution, Easy NTP, to solve the problem around the time offset that would make for minutes of time differences between drivers and riders.

[ibuildthecloud/klum](https://github.com/ibuildthecloud/klum) — Kubernetes Lazy User Manager

## DevOps'ish Tweet of the Week

{{< tweet 1223049510798024704 >}}
