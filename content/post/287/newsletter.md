+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-10-02T07:00:00Z
description = ["DevOps'ish 287 is dedicate to a wonderful community member we lost this week, Cody Crudgington"]
draft = false
slug = "287"
tags = ["open source", "Kubernetes", "Cody Crudgington", "podcast", "Twitter", "code", "contributor", "Cloud Native", "community", "Iran", "Signal", "Istio", "KubeCon", "developers", "CIA", "Girls Who Code", "Linux", "news", "GitHub", "GitOps"]
title = "DevOps'ish 287: Cody Crudgington, Help Iranians connect, bill to protect open source, VMware ESXi popped, Baffling Maze of Kubernetes, Girls Who Code Founder Speaks Out, and more"
image ="https://shortcdn.com/devopsish/cody-speaking.webp"
imagealt = "Cody Crudgington speaking at the Kubernetes Contributor Summit in San Diego"
imagecap = "Cody Crudgington speaking at the Kubernetes Contributor Summit in San Diego"
+++

With a heavy heart, I bring you the news of [Cody Crudgington's passing](https://twitter.com/AlexB138/status/1574590750288920599) in his home. The [Kubernetes Contributor Comms Team](https://github.com/kubernetes/community/blob/master/communication/marketing-team/README.md) sprang into action on behalf of Kubernetes Steering (who are all overworked already) this week to get coordinated around who to open up communication lanes with and generally being as open with the community as possible while respecting the wishes of Cody's family.

As I wrote on the [CNCF Memorial for Cody](https://github.com/cncf/memorials/blob/main/cody-crudgington.md), he and I had some unique similarities. He was willing to drop whatever he was doing to help folks in need. Cody was loved in the Kubernetes community for his positivity and optimism. The [K8sContributor thread on Wednesday](https://twitter.com/K8sContributors/status/1574809587785601024) is filled with an outpouring of love and admiration. He truly will be missed.

Follow [K8sContributors on Twitter](https://twitter.com/K8sContributors) or the [k-dev mailing list](https://groups.google.com/a/kubernetes.io/g/dev) for any additional details.

We will be doing a memorial at KubeCon for Cody. I will put those event details in this newsletter once I have them. I've reached out to those coordinating to let them know I'm here to help (especially since I'm local).

I know in these times we all want to do something to help. For the moment, check out the links mentioned here and stand by for further information as it becomes available.

Remember, any news that **I** add to my info sharing "Firehose" will land in the [/r/devopsish](https://www.reddit.com/r/devopsish/) subreddit almost immediately, then [Twitter](https://twitter.com/ChrisShort) and [LinkedIn](https://www.linkedin.com/in/thechrisshort/) eventually.

### The DevOps'ish Podcast

[The DevOps'ish Podcast: 2022-10-03](https://twitter.com/i/spaces/1ypJddDEyXQJW) is recorded in front of a live audience. Join us this week on Monday, October 3rd, 10 AM ET/14:00 UTC ([iCal](https://devopsi.sh/iCal) and [Google Calendar](https://devopsi.sh/GCal)).

Join the Twitter Space to participate and ask questions. Bring some friends along too! Follow me on [Twitter](https://twitter.com/ChrisShort) to get notified about upcoming Twitter Spaces. Subscribe to the [DevOps'ish Podcast](https://anchor.fm/devopsish) via your podcasting software of choice so you can listen on Mondays on your lunch break or ride home.

Learn more about [The DevOps'ish Podcast](https://devopsish.com/podcast/) and listen to [last week's episode](https://anchor.fm/devopsish/episodes/The-DevOpsish-Podcast-2022-09-26-e1od700).

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**Kubernetes Contributor Summit North American 2022**](https://www.kubernetes.dev/events/2022/kcsna/)

October 24, 2022 at [KubeCon](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)

The Summit will have a healthy mix of content tailored to active contributors. To conclude the summit, we'll end with [Contributor Social](https://www.kubernetes.dev/events/2022/kcsna/social) with games and refreshments.

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

[**FOSDEM 2023**](https://fosdem.org/2023/)

FEBRUARY 4 - 5, 2023

FOSDEM is a free event for software developers to meet, share ideas and collaborate.

Every year, thousands of developers of free and open source software from all over the world gather at the event in Brussels.

## People

[Help people in Iran reconnect to Signal – a request to our community](https://signal.org/blog/run-a-proxy/)  
Meredith Whittaker, Signal  
"Signal is currently blocked in Iran. To help people in the country access Signal, we are republishing and revising a post that we originally posted in February, 2021 during a very similar situation in Iran."

[Girls Who Code Founder Speaks Out After Learning a School District Had Banned Her Books](https://www.businessinsider.com/girls-who-code-founder-speaks-out-banning-books-schools-2022-9)  
Bethany Biron, Business Insider  
"Girls Who Code founder Reshma Saujani is speaking out after learning that her company's book series had been banned from a Pennsylvania school district... 'This is about controlling women and it starts with controlling our girls and what info they have access to,' Saujani told Insider." This is a form of repression these days. I mean think about all the girls that'd be independent if they knew how to code. Can't have that now. [WTF?!?](https://pen.org/about-us/)

[NSA Employee Leaked Classified Cyber Intel, Charged with Espionage](https://www.nextgov.com/technology-news/2022/09/nsa-employee-leaked-classified-cyber-intel-charged-espionage/377846/)  
Alexandra Kelley, Nextgov  
"Former NSA InfoSec Designer Jareh Sebastian Dalke was arrested by the FBI in Denver, Colorado on Wednesday as part of a sting operation." Sounds like he was at the same facility I was stationed at from [2005-2007](https://chrisshort.net/curriculum-vitae/#cyber-transport-systems--communications-computer-systems-controller--us-air-force--nov-1999-to-dec-2010).

[Statement on the fatal flaws found in a defunct CIA covert communications system](https://citizenlab.ca/2022/09/statement-on-the-fatal-flaws-found-in-a-defunct-cia-covert-communications-system/)  
The Citizen Lab  
"In 2018, Jenna McLaughlin and Zach Dorfman of [Yahoo News reported](https://news.yahoo.com/cias-communications-suffered-catastrophic-compromise-started-iran-090018710.html/) that a system used by the CIA to covertly communicate with its assets around the world had been compromised by Iran and China around 2011. The compromise reportedly led to the death of “more than two dozen sources” in China in 2011 and 2012, and also reportedly led Iran to execute some CIA assets and imprison others."

[Senators introduce a bill to protect open-source software](https://www.washingtonpost.com/politics/2022/09/22/senators-introduce-bill-protect-open-source-software/)  
Analysis by Tim Starks with research by Aaron Schaffer, The Washington Post  
"The Peters/Portman legislation would direct the Cybersecurity and Infrastructure Security Agency to develop a way to evaluate and reduce risk in systems that rely on open-source software. Later, CISA would study how that framework could apply to critical infrastructure."

## Process

[Mystery Hackers Are ‘Hyperjacking’ Targets for Insidious Spying](https://www.wired.com/story/hyperjacking-vmware-mandiant/)  
Andy Greenberg, WIRED  
"For decades, security researchers warned about techniques for hijacking virtualization software. Now one group has put them into practice." And no one is saying who it is but, VMware ESXi has been popped. You're going to want to read this.

[Numerous orgs hacked after installing weaponized open source apps](https://arstechnica.com/information-technology/2022/09/north-korean-threat-actors-are-weaponizing-all-kinds-of-open-source-apps/)  
Dan Goodin, Ars Technica  
Please make sure you download your software from reputable sources.

[Pentagon bug bounty program turns up nearly 350 vulnerabilities](https://therecord.media/pentagon-bug-bounty-program-turns-up-nearly-350-vulnerabilities/)  
Martin Matishak, The Record by Recorded Future  
"Competitors submitted 648 reports, within the scope of the DoD’s vulnerability disclosure program (VDP), to bug bounty platform HackerOne and the department agencies overseeing the pilot program between July 4 and July 11. Of those, 349 were deemed 'actionable' — paying out $75,000 in total bounties and another $35,000 in bonuses and awards."

[US candidate defeats Russian rival to head UN tech agency](https://therecord.media/us-candidate-defeats-russian-rival-to-head-un-tech-agency/)  
Alexander Martin, The Record by Recorded Future  
"Amid the backdrop of the war in Ukraine, and a battle for the future of the internet, the American contender to lead the United Nations telecommunications agency has defeated their Russian rival by a surprising landslide vote." It was not expected to go this way.

[Fedora Linux Disabling Mesa's H.264 / H.265 / VC1 VA-API Support Over Legal Concerns](https://www.phoronix.com/news/Fedora-Disable-Bad-VA-API)  
Michael Larabel, Phoronix  
"For Fedora Linux users currently making use of Mesa's VA-API support with the open-source AMD graphics driver or similar and using it to speed-up H.264, H.265, or VC1 decoding, you may soon be out of luck and will have to fall-back to either using CPU-based decoding or be relying on an unofficial/third-party Mesa build."

## Tools

[Container Conundrum: DevOpsDays Chicago 2022 Open Space Notes](https://chrisshort.net/container-conundrum-devopsdays-chicago-2022-open-space-notes/)  
Chris Short, ChrisShort.net  
"My notes from a DevOpsDay Chicago 2022 Open Space suggestion: 'Container Conundrum: Pain points around containers'"

[Ask Command — AI-powered Developer Assistant](https://askcommand.com/)  
Tony Dinh 🎯  
"A tiny app to remind you about those commands you always forget. Powered by AI." Too cool NOT to share. Like GitHub Copilot but at your command as opposed to constantly consuming your code. You do have to pay for credits (which is a more than fair way to pay for Open AI's GPT-3 license, yes, Open AI actually ain't open source).

[How Kubefirst Builds Kubernetes Platforms in 8 Steps](https://kubefirst.io/blog/how-kubefirst-builds-kubernetes-platforms-in-8-steps)  
John Dietz, KubeFirst  
"An Open Source Approach to Self Hosting a GitOps Platform"

[The Baffling Maze of Kubernetes](https://www.lastweekinaws.com/blog/The-Baffling-Maze-of-Kubernetes/)  
Corey Quinn, Last Week in AWS Blog  
"As a new user of Kubernetes, I'm already confronted with what feels like too many choices and too little authoritative direction about the 'right' way to get set up. I can therefore..."

[Building an eBPF-Based Profiler](https://www.containiq.com/post/building-an-ebpf-based-profiler)  
Matt Lenhard, ContainIQ  
"In this blog post, we recap the process and methodology we used to build our eBPF-based profiler. We include techniques and examples for both compiled and interpreted languages."

[A distributed SQLite benchmark: How mvSQLite scales](https://univalence.me/posts/mvsqlite-bench-20220930)  
Heyang Zhou  
"mvSQLite is the open-source, SQLite-compatible distributed database built on FoundationDB. In this post we benchmark mvSQLite with go-ycsb to see what its performance is like, and how a single database scales when we add more machines to the cluster."

[Istio is an official CNCF project - what does it mean for you?](https://www.solo.io/blog/istio-is-an-official-cncf-project-what-does-it-mean-for-you/)  
Lin Sun, Solo.io  
"As a founding Istio TOC and Steering member, I am extremely excited about moving Istio under CNCF’s governance and I believe this is another game changer for the Istio project in addition to the ambient mesh announcement a few weeks ago."

[Timestone: Netflix’s High-Throughput, Low-Latency Priority Queueing System with Built-in Support for Non-Parallelizable Workloads](https://netflixtechblog.com/timestone-netflixs-high-throughput-low-latency-priority-queueing-system-with-built-in-support-1abf249ba95f)  
Kostas Christidis, Netflix Technology Blog  
"Timestone is a high-throughput, low-latency priority queueing system we built in-house to support the needs of our media encoding platform, [Cosmos](https://netflixtechblog.com/the-netflix-cosmos-platform-35c14d9351ad)."

[Test for modern Internet Standards like IPv6, DNSSEC, HTTPS, DMARC, STARTTLS and DANE.](https://internet.nl/)  
internet.nl  
Cool testing tool I stumbled upon.

[soxoj/maigret](https://github.com/soxoj/maigret)  
🕵️‍♂️ Collect a dossier on a person by username from thousands of sites

[kairos-io/kairos](https://github.com/kairos-io/kairos)  
The immutable Linux meta-distribution for edge Kubernetes.

[allero-io/allero](https://github.com/allero-io/allero)  
By scanning CI/CD misconfigurations, Allero helps reduce production issues, harden your security posture and shift-left CI/CD from DevOps to developers.

[jhuangtw/xg2xg](https://github.com/jhuangtw/xg2xg)  
by ex-googlers, for ex-googlers - a lookup table of similar tech & services

[kubernetes-csi/external-health-monitor](https://github.com/kubernetes-csi/external-health-monitor)  
This repo contains sidecar controller and agent for volume health monitoring.

## DevOps'ish Post of the Week

[![BenTheElder on Twitter: "PSA: The @kubernetesio container image host http://k8s.gcr.io is *actually* getting redirected to the community controlled http://registry.k8s.io starting with a small portion of traffic on October 3rd. If you notice any issues, *please* ping me, @thockin or @ameukam.")](https://shortcdn.com/devopsish/287-devopsish-post-of-the-week.webp)](https://twitter.com/BenTheElder/status/1575898507235323904)

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/287/notes.md?utm_source=devopsish)
