+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-07-31
description = ["Intro to eBPF, Lawfare looks at open source, Sextortion Victim Hacks Back, UEFI rootkit, UOR Framework, Intel's dividend amid CHIPS Act, and more"]
draft = false
slug = "278"
tags = ["eBPF", "open source", "kernel", "Argo", "Linux", "security", "Kubernetes", "network", "cloud native", "observability", "Detroit", "developer", "devopsdays", "cloud", "system", "falco", "Windows", "engineering", "software", "cilium", "DevOps", "KubeCon", "code", "UEFI", "containers", "Intel"]
title = "DevOps'ish 278: Intro to eBPF, Lawfare looks at open source, Sextortion Victim Hacks Back, UEFI rootkit, UOR Framework, Intel's dividend amid CHIPS Act, and more"
+++

**ICYMI on Notes**: In [DevOps'ish 277](https://devopsish.com/277/) I stated I will no longer publish the weekly notes file on the website. They are still [made available on GitHub][1] as they have been for the past 170 issues. If you're curious about the why: spam emails that came as a result. Yeah, funny how that works.

I occasionally ask for writing prompts from folks on Twitter. Sometimes asking on social media works well. Other times it's giving someone a good URL. But this week, the people have spoken. They want to learn more about **eBPF**.

![eBPF](https://shortcdn.com/devopsish/ebpf-logo.webp)

### What is eBPF?

> eBPF (which is no longer an acronym for anything) is a revolutionary technology with origins in the Linux kernel that can run sandboxed programs in a privileged context such as the operating system kernel. It is used to safely and efficiently extend the capabilities of the kernel without requiring to change kernel source code or load kernel modules.

### How does eBPF work?

> eBPF programs are event-driven and are run when the kernel or an application passes a certain hook point. Pre-defined hooks include system calls, function entry/exit, kernel tracepoints, network events, and several others.

There are two sites you should bookmark regarding eBPF right off the bat:

- [https://ebpf.foundation/][1] (Linux Foundation site)
- [https://ebpf.io][2] (Run by Daniel Borkmann)

At the time of writing, these two sites look strikingly similar, but different folks run them. For "reasons," the .foundation site decided to start as a fork of the .io site. Yes, I know a few SEOs reading this spit their morning drink of choice just now. Calm thyself. Your device is probably waterproof ¯\\\_(ツ)\_/¯. I told them that was a terrible idea. I expect to have a chat this week. 😇😇😇

If you're unfamiliar with [Isovalent][3], the folks who make an enterprise-ready [Cilium][4] product (Cilium the Container Network Interface (CNI)), it's where my peeps [Liz Rice][5] and [Duffie Cooley][6] work. If you recall, I sat down with them [earlier this year to chat about what they're up to pre-KubeCon EU 2022][7]. The tag line on Isovalent's site is "eBPF-based networking, security, and observability." You can do a lot of hard work with eBPF.

If you're like me and have been in the guts of the kernel before adding and removing modules to optimize the system or make unique hardware work, you know this can often be very disruptive or damaging. eBPF enables you to muck with the kernel in new and exciting ways without running a single modprobe command or even rebooting. They are generally safer than kernel modules as well.

You write eBPF programs that trigger on different events in the Linux kernel or prevent them from happening altogether. As a result, eBPF is VERY powerful because it's so ingrained where all the magic happens (the Linux kernel). eBPF lets you write custom code in the kernel. Since the activity occurs in the kernel, it often makes eBPF programs fast and efficient. The programs you write, for example, could intercept network access before even hitting the network stack or provide detailed execution information on calls being made by what programs for observability.

Here's where a lot of folks learning paths diverge. Some folks will want to read all the things. The good news is that the [BPF and XDP Reference Guide][8] and [HOWTO interact with the BPF subsystem][9] are _fantastic_ deep dives. Others would love to see some implementations. If you want to pick and choose, check out the [awesome-ebpf][10] repo. Want to see some implementations? First, I recommend watching [A Beginner's Guide to eBPF Programming with Go by Liz Rice at GOTO 2021][11]. What kind of programs are out there taking advantage of eBPF? Quite a few, actually:

- [pixie][12]: Instant Kubernetes-Native Application Observability (aka FM: F'ing Magic)
- [boopkit][13]: Linux eBPF backdoor over TCP. Spawn reverse shells, RCE, on prior privileged access. Less Honkin, More Tonkin.
- [Calico][14]: an open source networking and network security solution for containers, virtual machines, and native host-based workloads (their [eBPF page has pretty pictures][15])
- [kubectl trace][16]: kubectl plugin that allows you to schedule the execution of bpftrace programs in your Kubernetes cluster
- [bpftrace][17]: High-level tracing language for Linux systems
- [Falco][18]: Falco eBPF probe is a viable option in environments where kernel modules are not trusted or are not allowed but eBPF programs are
- [SysmonForLinux][19]: Sysmon For Linux is a port of the Windows Sysmon tool, with the driver replaced by eBPF programs
- [tracee][20]: Linux Runtime Security and Forensics using eBPF
- [ebpf-for-windows][21]: eBPF implementation that runs on top of Windows
- [Katran][22]: Facebook-created network load balancer

### Chris! Is it all worth it?

Yes! eBPF is good stuff. I am waiting for a project to bust out one of the above projects to dive into performance issues. "Any sufficiently advanced technology is indistinguishable from magic" applies here. But, eBPF is a rubber mallet, and you can't fix EVERYTHING with it. You can cover a lot of sins with eBPF. You can FIND damn near with it, and that's as good a start as anyone can give you.

[1]: https://ebpf.foundation/
[2]: https://ebpf.io
[3]: https://isovalent.com/
[4]: https://cilium.io/
[5]: https://twitter.com/lizrice
[6]: https://twitter.com/mauilion
[7]: https://chrisshort.net/video/aws-container-days-eu-2022-day-3/#cilium-on-eks-anywhere--liz-rice-chief-open-source-officer-isovalent---duffie-cooley-field-cto-isovalent
[8]: https://docs.cilium.io/en/latest/bpf/
[9]: https://www.kernel.org/doc/html/latest/bpf/bpf_devel_QA.html
[10]: https://github.com/zoidbergwill/awesome-ebpf
[11]: https://youtu.be/uBqRv8bDroc
[12]: https://github.com/pixie-io/pixie
[13]: https://github.com/kris-nova/boopkit
[14]: https://projectcalico.docs.tigera.io/about/about-calico
[15]: https://projectcalico.docs.tigera.io/about/about-ebpf
[16]: https://github.com/iovisor/kubectl-trace
[17]: https://bpftrace.org/
[18]: https://falco.org/blog/choosing-a-driver/#ebpf-probe
[19]: https://github.com/Sysinternals/SysmonForLinux
[20]: https://github.com/aquasecurity/tracee
[21]: https://github.com/microsoft/ebpf-for-windows
[22]: https://engineering.fb.com/2018/05/22/open-source/open-sourcing-katran-a-scalable-network-load-balancer/

## Free Copy of Honeycomb's O'Reilly Book: Observability Engineering
Looking to make the switch from monitoring to observability? [Download your free copy of Honeycomb's O'Reilly book: Observability Engineering](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) to help you get started. Debrief the chapters with the authors themselves during our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112).

### Jobs

Now Hiring: [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003)  
[Camunda](https://camunda.com/) is the leader in process orchestration software. Our software helps orchestrate complex business processes that span people, systems, and devices. With Camunda, business users collaborate with developers to model and automate end-to-end processes using BPMN-powered flowcharts that run with the speed, scale, and resiliency required to compete in today's digital-first world.

As the [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003), you'll be the direct people manager for a team of 4 Developer Advocates, responsible for career growth, performance evaluations, setting of priorities, and overall strategic guidance. You'll also be responsible for strategic planning for the Developer Advocacy function, including quarterly OKRs and annual goals as well as documentation of team responsibilities, goals, and success metrics.

*Note: The hiring manager is on a hard earned vacation.*

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**DevOpsDays Detroit**](https://devopsdays.org/events/2022-detroit/welcome/)

AUGUST 25 - 26, 2022

DevOpsDays Detroit is thinking about cancelling if registrations don't pick up. Let's not let our local DevOpsDays go down in flames. I'll take selfies with you if you want. Show up, it'll be awesome! Come see Detroit before KubeCon shows up. They're offering folks $50 off. Register by Aug 3rd (Wednesday) when the organizers will make a decision, please: <https://www.eventbrite.com/e/336097074397/?discount=WELCOMEBACK>

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we're expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We're excited to welcome you back to our Deserted Island this September 14th and 15th!

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?utm_source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing.

## People

[With U.S. ~on brink of~ in recession, Twitch streamers tighten their belts](https://www.washingtonpost.com/video-games/2022/07/27/twitch-streamers-recession-inflation-brand-deals-tiktok/)  
Nathan Grayson, The Washington Post  
"'Lots of creators have felt the shift as income has decreased noticeably,' said Miguel Lozada, a senior partnerships manager at Elgato who also creates gaming-related content on YouTube, TikTok and Twitch."

[AMD and Nvidia leaks show we are drunk on power, and the hangover is going to be brutal](https://www.techradar.com/news/amd-and-nvidia-leaks-show-we-are-drunk-on-power-and-the-hangover-is-going-to-be-brutal)  
John Loeffler, TechRadar  
"The planet may burn but at least the end will be ray-traced at 8K"

[The Default Tech Settings You Should Turn Off Right Away](https://www.nytimes.com/2022/07/27/technology/personaltech/default-settings-turn-off.html)  
Brian X. Chen, The New York Times  
"These controls, which are buried inside products from Apple, Google, Meta and others, make us share more data than we need to."

[Sextortion Victim Turns the Tables on Her Hacker](https://www.bloomberg.com/news/articles/2022-07-26/sextortion-victim-turns-the-tables-on-her-hacker)  
Jeff Stone, Bloomberg  
Hack back. Defend forward. Whatever you want to call it, works at all levels. "Unhappy with the way her case was being handled, a college student took matters into her own hands."

[jorgef/engineeringladders](https://github.com/jorgef/engineeringladders)  
⭐️ 4.2K  
A framework for Engineering Managers

## Process

[Intel Cuts Fab Buildout by $4B To Pay Billions In Dividends](https://semianalysis.substack.com/p/intel-cuts-fab-buildout-by-4b-to)  
Dylan Patel, SemiAnalysis  
Color me pissed. You get a MASSIVE taxpayer bailout and turn around and give that money to stock holders?!? "First Net Loss In Over 30 Years, Cutting Fab Buildouts, But 'Committed To Growing The Dividend'"

[CosmicStrand: the discovery of a sophisticated UEFI firmware rootkit](https://securelist.com/cosmicstrand-uefi-firmware-rootkit/106973/)  
, Securelist  
"We present a UEFI firmware rootkit that we called CosmicStrand and attribute to an unknown Chinese-speaking threat actor." 😬😬😬😬😬

[Open-Source Security: How Digital Infrastructure Is Built on a House of Cards](https://www.lawfareblog.com/open-source-security-how-digital-infrastructure-built-house-cards)  
Chinmayi Sharma, Lawfare  
Yo! If Lawfare writes about open source software, you better read it.

[F.T.C. Chair Lina Khan Upends Antitrust Standards by Suing Meta](https://www.nytimes.com/2022/07/28/technology/ftc-lina-khan-meta.html)  
Cecilia Kang, The New York Times  
"Lina Khan may set off a shift in how Washington regulates competition by filing cases in tech areas before they mature. She faces an uphill climb."

[Intel To Wind Down Optane Memory Business - 3D XPoint Storage Tech Reaches Its End](https://www.anandtech.com/show/17515/intel-to-wind-down-optane-memory-business)  
Ryan Smith, Anandtech  
I never understood the appeal. Why waste all that bandwidth, all those PCIe lanes on so little storage? But, the best comment, "I also will miss optane's depature."

[Upgrading probably the world's oldest running Linux install](https://www.theregister.com/2022/07/25/ancient_linux_install_upgraded/)  
Liam Proven, The Register  
"If you use PuTTY, there's a good chance you've visited Chiark"

## Tools

[What is eBPF, anyway, and why should Kubernetes admins care?](https://www.groundcover.com/blog/what-is-ebpf)  
Aviv Zohari, groundcover  
Speak of the devil! "But we can tell you why eBPF has become such a big deal for revolutionizing Kubernetes observability, among other tasks. Let's look at the history of eBPF, how it works, which problems it solves and why you – yes, you – should start taking advantage of it."

[Aya: your tRusty eBPF companion](https://deepfence.io/aya-your-trusty-ebpf-companion/)  
Michal Rostecki and Thomas Legris, Deepfence  
"Aya is a library that makes it possible to write eBPF programs fully in Rust and is focused on providing an experience that is as friendly as possible for developers. In this post we are going to explain what eBPF is, why Aya started, and what's unique about it."

[The UOR Framework](https://next.redhat.com/2022/07/13/the-uor-framework/)  
Alex Flom and Andrew Block, Red Hat  
As someone who thinks OCI could be a storage spec for more than just Dockerfiles and charts. I'm going to scratch at this as folks at Kong are also interested.

[It's BBQ Season! How Pit Bosses Use InfluxDB to Avoid the Stall](https://www.influxdata.com/blog/bbq-how-pit-bosses-use-influxdb/)  
Bria Jones, InfluxData  
"Some call it art, some call it science. Those who include InfluxDB in their culinary toolkit will call it science and I will share with you how these pitmaster scientists perfect their BBQ with time series data."

[GNOME To Warn Users If Secure Boot Disabled, Preparing Other Firmware Security Help](https://www.phoronix.com/news/GNOME-Secure-Boot-Warning)  
Michael Larabel, Phoronix  
"GNOME and Red Hat developers are working on integrating firmware security tips and recommendations into the desktop for warning users about platform/firmware security issues like if UEFI Secure Boot is disabled and other possible avenues their system could be exploited."

[Kubernetes Network Policies: An Actionable Guide & Tutorial](https://www.containiq.com/post/kubernetes-network-policies)  
Kasper Siig, ContainIQ  
"In this guide, you'll learn about Kubernetes Network Policies, including what they do, why they're needed, and how to configure and work with them effectively."

[Global shortage of fiber-optic cable threatens digital growth](https://arstechnica.com/information-technology/2022/07/global-shortage-of-fiber-optic-cable-threatens-digital-growth/)  
Anna Gross, Ars Technica  
Droughts everywhere. "Rising prices of components cast shadow over 5G rollout and development of data centers."

[keyval-dev/odigos](https://github.com/keyval-dev/odigos)  
43 ⭐️  
Get traces, metrics and logs in minutes. No code changes needed

[mgoltzsche/khelm](https://github.com/mgoltzsche/khelm)  
58 ⭐️  
A Helm chart templating CLI, kustomize plugin and containerized kustomize/kpt KRM function

[sieve-project/sieve](https://github.com/sieve-project/sieve)  
109 ⭐️  
Automatic Reliability Testing for Kubernetes Controllers

## DevOps'ish Post of the Week

[![Sarah Drasner on Twitter: "I bet the things in your apps that don't work well have direct correspondence to people/teams not collaborating well. Stop separating team health from technical expertise/efficiency.")](https://shortcdn.com/devopsish/278-devopsish-post-of-the-week.webp)](https://twitter.com/sarah_edo/status/1551318133029236736/?utm_source=devopsish)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/278/notes.md)