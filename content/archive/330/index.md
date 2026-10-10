---
author: Chris Short
date: '2026-10-11'
description: "Kubernetes stops starting the kubelet on cgroup v1 nodes by default while node swap on NVMe triples sandbox density, James Ross watches Sindre Sorhus and Hono shut the door on outside pull requests and calls open source as we know it dead, Simon Willison wants hard budget caps on everything before an agent runs up your bill overnight, and Apple puts more friction in front of Full Disk Access because of AI agents."
draft: false
slug: '330'
title: "DevOps'ish 330: cgroup v1 gets the boot, open source closes its doors, cap your cloud bill, and more"
---

{{< subscribe >}}

[**The Shift to cgroup v2 in Kubernetes: What You Need to Know**](https://kubernetes.io/blog/2026/10/06/kubernetes-cgroups-v2-shift/) (10 minute read)

Starting with v1.35, *failCgroupV1* defaults to true, so the kubelet won't start on a cgroup v1 node unless you set the override. kubeadm now fails preflight on it instead of warning. This FAQ is for anyone who hasn't moved yet. It covers what v2 buys you: Memory QoS with tiered *memory.min*/*memory.low* protection (still alpha in v1.36), whole-container OOM kills, PSI metrics on by default, and in-place Pod-level resizing. There's also a requirements list: kernel 5.8 or later, containerd 1.4+ or CRI-O 1.20+, and matching cgroup drivers on the kubelet and runtime. Find those old nodes before your next upgrade does.

[**Scaling Kubernetes Workloads with Node Swap**](https://kubernetes.io/blog/2026/10/05/scaling-kubernetes-workloads-with-node-swap/) (6 minute read)

This one only works because of cgroup v2's separate swap accounting. Node swap went GA in v1.34, and these benchmarks back it with NVMe Local SSDs on GKE. A Linux kernel build ran with half the memory limit (300 MB instead of 600 MB) and actually finished faster, 374s versus 433s. gVisor headless Chrome pods doubled from 80 to 160 per node, and gVisor Python sandboxes tripled from 80 to 240. Then the honest part: squeezing the kernel build to 200 MB pushed the active working set into swap and made it over 40% slower. Swap is insurance for idle and bursty memory. It's not more RAM. The setup is a few lines of KubeletConfiguration with *LimitedSwap* and Burstable QoS on your pods.

[**Meet the A2A CLI: discover, message, and manage agents from your terminal**](https://a2a-protocol.org/latest/blog/2026/10/01/introducing-a2a-cli/) (5 minute read)

A2A now has an official command-line client, built on the CLI from the A2A Go SDK and speaking A2A Protocol v1.0. Fetch agent cards, send messages, stream task updates, and drop it into CI with JSON output and predictable exit codes. The fun bit is *a2a server --exec*, which turns any program that reads stdin and writes stdout into an A2A agent. A throwaway Python script becomes a discoverable agent in about four commands. They say *--echo* and *--exec* are for demos and testing, not production, and I'd take them at their word. Apache-2.0.

[**Open Source as We Know It Is Dead**](https://jross.me/open-source-as-we-know-it-is-dead/) (9 minute read)

James Ross got his first PRs merged by strangers in 2014, including a 300-line unsolicited "global tidy up" that nobody would touch today. This year the doors started closing. curl ended its bug bounty, Ladybird stopped taking public PRs, Jazzband shut down, Sindre Sorhus disabled external PRs on all his repos, and then Hono did too. He doesn't blame maintainers one bit, and he admits he uses AI every day. His point: AI made contributing cheap and made maintaining more expensive, and the volunteer who has to say no eats the cost. He doesn't have a fix. I don't either. Read it if you were ever the stranger who got let in.

[**the senior engineer death spiral**](https://sunilpai.dev/posts/the-senior-engineer-death-spiral/) (4 minute read)

Sunil Pai describes a failure mode he's lived through more than once. New senior role, imposter syndrome, an overly ambitious project, weeks of "it's going well" standup updates with nothing to show. Then lost sleep, burnout, maybe a PIP. His fix is counterintuitive: drop a level for a while. Fix bugs, take the grunt work off someone else's plate, write things up, and rebuild momentum and trust. "You are in the reputation-building business, and software is actually downstream of that." Send this to the new hire who's gone quiet.

[**We're going to need default hard budget caps on pretty much everything**](https://simonwillison.net/2026/Oct/3/default-hard-budget-caps/) (2 minute read)

Simon Willison wants hard budget caps on pay-per-use services by default, with removal as the opt-in. A warning email at midnight does nothing when your agent-built side project spends a few thousand dollars while you sleep. AWS launched spend limits on September 16 that pause a project when it hits the cap, though only for a limited set of customers so far. Google Cloud shipped Spend Caps in July. He'd also like coding agents to steer newer builders toward providers that have caps. Most people would take errors over a surprise $10,000 bill. Having done this myself, so would I.

[**Apple says it's tightening macOS 'Full Disk Access' controls due to new risks from AI agents**](https://techcrunch.com/2026/10/02/apple-says-its-tightening-macos-full-disk-access-controls-due-to-new-risks-from-ai-agents/) (2 minute read)

Days after an Inc. columnist reported that Meta's Muse app on Mac knew the contents of his private messages (Meta disputes it), Apple said it's adding controls around Full Disk Access. Apple's words: some developers use it "in ways that could put users at risk," and more capable AI agents make that worse. Going forward, granting it will take "very explicit user action." TechCrunch corrected its original framing, so to be clear, this is about informed consent, not a new limit. RemoveMacAI, down in the repos, fits nicely with this one.

[**Heroku Is Dead (And It Taught Us Everything We Know)**](https://www.youtube.com/watch?v=3CLrqv6ZtW8) (21 minute watch)

Viktor Farcic tells Heroku's story as a bedtime story. Three founders in 2007, *git push* deploys, buildpacks, the Twelve-Factor App, a $200 million Salesforce acquisition, years of enterprise compliance features directed at the wrong customer, and a rebuild that came eleven years too late. The ideas won anyway. Buildpacks became a CNCF project, and the twelve factors live in your Dockerfile. His jab at platform teams two years into rebuilding what Heroku already shipped is going to land with some of you.

[**Raspberry Pi Desktop now available for PC and Mac**](https://www.raspberrypi.com/news/raspberry-pi-desktop-now-available-for-pc-and-mac/) (5 minute read)

After years stuck on Bullseye, Raspberry Pi Desktop for PC and Mac is back on 64-bit Debian Trixie. Flash the live image to a USB stick, boot with persistence, and install it with Calamares if you like it. You get the new Control Center and dock, plus a Raspberry Pi Connect client so you can screen share or open a remote terminal into the PC like any other Pi. Apple Silicon is out since Debian's support there is still experimental. Good news for the old laptop in your closet.

[**Two U.S. Site-Blocking Bills Compete Over VPN Rules and ISP Liability**](https://torrentfreak.com/two-u-s-site-blocking-bills-compete-over-vpn-rules-and-isp-liability/) (10 minute read)

For the first time since SOPA, Congress has pirate site-blocking bills on the table. Two of them. Rep. Darrell Issa's ACPA would let courts order ISPs, DNS resolvers, as well as VPNs with 100,000+ U.S. users to block foreign sites, uses a looser "only limited" commercial purpose test, and gives providers a damages shield. The bipartisan DEFEND IP Act reaches ISPs down to 50,000 subscribers, but only covers public DNS resolvers with over $100 million in revenue, and it excludes VPN-only services and encrypted-only DNS like DoH. If you run network infrastructure, TorrentFreak's side-by-side table is the fastest way to see what each one asks of you.

[**A Practical Guide To Naming Things**](https://www.smashingmagazine.com/2026/10/how-name-things/) (6 minute read)

Naming is hard, so here's a pile of help. Classnames for themed word lists, a repository of 30,355 color names, Intuit's design token taxonomy case study, Iain Bean's Component Gallery with 50+ UI components and the other names they go by, and Erin Gannon on naming features people can actually find. Written for designers, but useful for anyone who's stared at a variable name for ten minutes.

[**Devpack for Rust: Zero to Rust in seconds**](https://ubuntu.com//blog/devpack-for-rust-support) (2 minute read)

Canonical's Devpack for Rust is a snap (*sudo snap install devpack-for-rust --classic*) that installs Rustup, an IDE, and your pick of Rust command-line tools from a tree menu. The author's most used picks are ripgrep, fd, and just. Handy for getting someone new to Rust set up fast. It's open source on GitHub, and they're asking for suggestions on tools to add.

[**storytold/photocraft**](https://github.com/storytold/photocraft) - MIT or Apache-2.0 - An open source, clean-room reimplementation of Adobe Photoshop in pure Rust. Layers, masks, adjustment layers, layer styles, type, vectors, brushes, and real PSD files, with a GPU compositor on wgpu for macOS, Windows, Linux, FreeBSD, and the web. It's early alpha, the repo was created September 30, and it's already past 40,000 stars.

[**eolix/photosuite**](https://github.com/eolix/photosuite) - MIT or Apache-2.0 - A desktop image editor built on PhotoCraft's engine that's aiming for 1:1 PSD/PSB round trips with classic Photoshop, effects and smart objects included. Still a work in progress, but there are installers for macOS, Windows, and just about every Linux package format.

[**omlahore/RemoveMacAI**](https://github.com/omlahore/RemoveMacAI) - MIT - Debloat macOS. Turn off Apple Intelligence and delete its models, stop the analytics and ads, quiet the pop-ups, and switch off other apps' background updaters. It's a native app and a CLI, it shows you every change before it happens, and every change can be undone. Built on 4evy's pared. The app isn't notarized and the install path is curl piped to bash, so read *install.sh* first.

[**openclaw/openclaw-enterprise**](https://github.com/openclaw/openclaw-enterprise) - MIT - "Think of it as Kubernetes for agents." OpenClaw Enterprise is an open source, vendor neutral control plane for deploying and managing agents, with a Go and TypeScript codebase. Run it locally on k3d or install it on a cluster you already operate. Deploying your first agent needs an OpenAI API key. Created August 29 and sitting around 400 stars.

{{< sponsor >}}
