---
author: Chris Short
date: '2026-11-22'
description: "Java4Shell puts an unauthenticated RCE in OpenJDK's Base64 decoder, Optimizely serves malware to visitors of 178 brands, kube-proxy's IPVS backend gets a removal date, and the FAA outage gets a root cause everyone is pointing fingers over."
slug: '336'
title: "DevOps'ish 336: Java4Shell hits OpenJDK, Optimizely ships malware for 178 brands, and more"
---

{{< subscribe >}}

[**Stop maintaining your own GitHub Actions runners**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-11-22) (Sponsor)

Running self-hosted runners on Kubernetes with ARC means someone owns the cluster, the autoscaling, and the upgrades. WarpBuild BYOC runs your runners on VMs in your own AWS, GCP, or Azure account and manages them for you. Try it with $50 in free credits using code START50.

[**KubeCon NA 2026: That's A Wrap**](https://www.cloudnativedeepdive.com/kubecon-na-2026-thats-a-wrap/) (4 minute read)

Michael Levan's recap says the KubeCon conversation moved from experimenting with AI to running it in production. The big themes were agentic infrastructure, sandboxing and isolation, and inference. He says Agent Substrate Day was full of engineers talking about what they'd actually built instead of vendor pitches, and hallway questions shifted from "what is AI" to "how do I implement it." If you missed Salt Lake City, this is a quick way to catch up.

[**Scheduling the removal of the kube-proxy IPVS backend**](https://kubernetes.io/blog/2026/11/16/ipvs-removal/) (7 minute read)

SIG Network deprecated kube-proxy's ipvs backend in 1.35 and now plans to remove it in 1.40. Dan Winship lays out the history. ipvs fixed real iptables scaling pain back in 2017, but the kernel IPVS API never matched Kubernetes Services well, the original authors moved on, and it leaned on iptables for anything past basic load balancing anyway. That last bit matters, because Red Hat plans to pull the iptables API out of RHEL, which takes ipvs down with it. On 1.36 or later with kernel 5.13+, switch to nftables. In kubeadm clusters that's changing `mode: ipvs` to `mode: nftables` in the kube-proxy ConfigMap and restarting the pods. Stuck on something older? The iptables backend is a lot better than it was in 2017. And if you picked ipvs for the fancy schedulers, the post explains why they never really worked in kube-proxy.

[**You will be busier by a lot: CNCF's Jorge Castro on maintaining open source with agents**](https://shiftmag.dev/you-will-be-busier-by-a-lot-cncfs-jorge-castro-on-maintaining-open-source-with-agents-13563/) (5 minute read)

Jorge Castro (CNCF developer relations, Universal Blue co-founder) says get your review process in place before you turn agents loose, because speed makes skipping review way too easy. Bluefin keeps human approval gates and lives with big review queues, and they added a triage role so non-coders can help label issues. He pegs Universal Blue's running costs at about $60 a month and figures local models could handle some review work for under $150 a month. His biggest worry is security, especially old enterprise software whose original authors are long gone. The headline is the honest part. Agents mostly move maintainer work into the review queue.

[**CVE-2026-114938 OpenJDK RCE (Java4Shell): Everything You Need to Know**](https://www.wiz.io/blog/cve-2026-114938-rce-java4shell-openjdk) (4 minute read)

CVE-2026-114938 is a memory corruption bug in OpenJDK's AVX-512 Base64 decoding code, scored 9.2 on CVSS v4, and Wiz says it's remotely exploitable without authentication. Feed it Base64 with an unexpected number of trailing `=` padding characters and you get an out-of-bounds heap write. It hits OpenJDK 17.0.6 and later on x86-64 CPUs with AVX-512 VBMI (Ice Lake and newer Xeons, Zen 4 and newer AMD), which drags in Corretto, Temurin, Zulu, Liberica, Microsoft's build, SapMachine, Red Hat's builds, and Oracle Java SE. ARM64 is fine. Patches landed November 17. If you can't patch yet, `-XX:-UseBASE64Intrinsics` turns off the vulnerable path at some performance cost. Somebody's about to spend a very long week rebuilding base images.

[**World's Largest Brands Infected With Malware Via Optimizely**](https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/) (20 minute read)

On November 16, someone injected malicious JavaScript into Optimizely Web customers' Project JavaScript, and it got served to visitors of 178 organizations, including Zoom, the BBC, and CNN. Scott Helme's writeup breaks down the payload: swapping crypto wallet addresses, skimming card details, stealing cookies and screenshots, and serving iOS exploit kits to iPhone and iPad users. The attacker walked off with about $7,040 in crypto, and the infected files were cleaned up by the 17th. Consider this your reminder to audit every third-party script tag on your site. Each one is somebody else's deploy pipeline running in your customers' browsers.

[**The Pulse: What can we learn from the Railway hack?**](https://newsletter.pragmaticengineer.com/p/the-pulse-what-can-we-learn-from-114) (2 minute read)

Gergely Orosz digs into Railway's postmortem of its recent hack, where the attacker likely used "abliterated" AI models with the safeguards stripped out. Most of the issue is behind the paywall. The rest covers native mobile and frontend jobs disappearing, how trust helps an AI-native engineering team work, and Carta selling a coding harness.

[**Secret scanning detects secrets in GitHub Actions workflow logs**](https://github.blog/changelog/2026-11-09-secret-scanning-detects-secrets-in-github-actions-workflow-logs/) (1 minute read)

Secret scanning now looks through GitHub Actions workflow logs. Hits show up in the repo's secret scanning alerts with a link back to the log. It's in public preview for GitHub Enterprise Cloud customers with Secret Protection or Advanced Security (GHE.com data residency included), and it's off by default, so an enterprise owner has to flip it on under Policies > Advanced Security. If you've ever `echo`ed an env var to debug a workflow, go turn this on.

[**Overwhelmed routers from 2001 grounded all US flights on Friday as FAA's decades-old server infrastructure buckled under network traffic**](https://www.tomshardware.com/networking/two-hpe-juniper-network-routers-grounded-all-the-us-flights-on-friday-faas-decades-old-copper-network-buckled-under-a-feature-hpe-says-worked-as-intended-creaking-air-traffic-communication-system-became-overloaded-by-very-high-rate-pinging) (5 minute read)

Last week's FAA ground stop had no root cause. Now it has one, sort of. Newly installed HPE Juniper routers at an FAA radio site in El Dorado, Arkansas, and a radar site in Amarillo, Texas, started hitting the network with what FAA technology chief Rebecca Guy called "a thousand connections over every four to five seconds." That's nothing for a modern network, but it swamped the FAA's aging copper one. HPE says its routers "did not fail," and the FAA turned the offending feature off on every Juniper router it has. Then Transportation Secretary Sean Duffy went on CNBC and blamed 2001-vintage Cisco gear he said went out of commission in 2006. New router floods the network, old gear falls over, everybody points at somebody else. Anyone who's sat through a postmortem knows this one.

[**Hundreds of fake accounts defended Jensen Huang and attacked lawmakers over chip exports.**](https://www.modelrepublic.org/articles/nvidia-koios-campaign-sockpuppet-accounts) (10 minute read)

A follow-up of sorts to last week's Jensen Huang news. Tyler Johnston found more than 400 apparent sockpuppet accounts that have posted thousands of times since November 2025, backing Nvidia's position on chip export controls, defending Huang during the spy scandal, and going after lawmakers and export control advocates. The coordination tells are there: batch account creation, scheduled posting, identical text, and lots of posts deleted after the fact. The trail leads to Koios, an Israeli firm tied to a pro-Qatar influence campaign that says it has shut down, and to a successor called IntellACT. Nvidia says it has no relationship with either and is trying to figure out who's behind the accounts. Nobody knows who paid for it yet.

[**Understanding the Linux Kernel: eBPF**](https://internals-for-interns.com/posts/linux-kernel-ebpf/) (13 minute read)

Jesús Espino wraps up his 12-part Linux kernel series with eBPF from the kernel's side, no eBPF code required. He walks a program from load to attach through the loader, verifier, and JIT compiler, and covers bytecode, maps, and hooks along the way. The running example is `sd_devices`, the program systemd loads to enforce device restrictions on services, so there's a decent chance it's already running on your machine.

[**CS Learn**](https://www.cs.cmu.edu/learn/) (2 minute read)

Carnegie Mellon's School of Computer Science is putting full classroom lectures from its faculty on YouTube for free, including 15-110 Principles of Computing and 11-768 AI Agents. Self-paced courseware and AI tutoring are listed as coming, and a few more courses premiere in January 2027. There are paid paths too, but the lectures cost nothing. Good for juniors, career changers, or anyone who skipped the theory and wants to backfill.

[**apple/container**](https://github.com/apple/container/blob/1.7.1/docs/cluster.md) - Apache License 2.0 - A tool for creating and running Linux containers using lightweight virtual machines on a Mac, written in Swift and optimized for Apple silicon. The 1.7.1 docs cover `container cluster`, which runs local Kubernetes clusters as lightweight VMs with worker nodes, CPU and memory sizing, and plain `kubectl` access. Read the security caveats before you reach for `--shared-image-store`.

{{< sponsor >}}
