+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-07-24T07:00:00Z
description = ["DevOpsDays Seattle, Google freezes hiring; spf13 out, The Path to GitOps, MinIO calls foul on Nutanix, Ephemeral Containers, K8s Gateway API, and more"]
draft = false
slug = "277"
tags = ["people", "Kubernetes", "open source", "DevOpsDays", "DevOpsDays Seattle", "security", "infosec", "DevOps", "software", "Kat Cosgrove", "IoT", "Netflix", "Google", "images", "developer", "OCI", "scaling", "AWS", "systems", "Steve Francia", "GitOps", "scale", "hiring", "compliant", "developers", "container", "containers", "customers", "processes"]
title = "DevOps'ish 277: DevOpsDays Seattle, Google freezes hiring; spf13 out, The Path to GitOps, MinIO calls foul on Nutanix, Ephemeral Containers, K8s Gateway API, and more"
+++

**A note about notes**: I will no longer publish the weekly notes file on the website. They are still [made available on GitHub][1] as they have been for the past 170 issues. If you're curious about the why: spam emails that came as a result. Yeah, funny how that works.

### The Past Week

I'm writing this week's newsletter intro from a Delta 737-900ER high above the western United States. I'm flying back from Seattle, where I had a great week (minus the fatigue and pain; I need to finish physical therapy). On Monday, I got to meet my new team face-to-face. The team is diverse in cultures, experiences, and skill sets. Share opinions on open source, the CNCF, and the Kubernetes ecosystem, as well as answer even the most basic of questions around governance. This is refreshing because I have the chance to help mentor and help people grow, in addition to my day job. I'm fortunate to be working with this wonderful group of folks.

One thing that stood out to me the most as I wandered around Seattle this week. The city's diversity has improved since my visits in 2012 and 2018. I'm looking forward to making more future trips to this beautiful city (fog or not). I know Max would love to tag along, too (he was impressed by the seagull population, pigeons, unique architecture, and construction). Yes, I have a unique photo album for Max when I travel.

### DevOpsDays Seattle

I attended [DevOpsDays Seattle](https://devopsdays.org/events/2022-seattle/welcome/) this week too. It was exciting to be back at DevOpsDays in person again. Seeing so many of my friends after so long ended up breathing new life into what I'm doing. My friend Kat Cosgrove gave a great talk about the history of configuration management (which was Kat's first keynote; she nailed it). There have been a lot of tools to help with this along the way. The big ones; Make, cfengine, Puppet, Ansible (and many more); I've touched them all. I know I'm old because my body tells me that, but I'm experienced because I changed jobs enough to avoid getting too stuck on one tool. This was my first grand realization. I got fortunate that I had the opportunity to learn Puppet when it was new and complicated. To learn Ansible back in the late 1.x days. These experiences gave me foresight into what to look for in the following tooling setups. This led me to Kubernetes and what I'm doing today.

I met a few new people at DevOpsDays and people I've followed on Twitter forever but haven't met in person and had open and honest discussions. I got to see my Marine friends Ken Mugrage and Trip Longworth (for what might have been the longest, hardest hug I've had all year; I needed it). I saw Laura Santamaria of Kubernetes Community fame, former Red Hatter, and fellow Detroiter Rain Leander.

See the [live tweets of the event here](https://twitter.com/search?q=from%3AChrisShort%20%23DevOpsDays&src=typeahead_click&f=live).

#### OCI Compliant Registries

Kat Morgan and I discussed why OCI-compliant repos should be able to host any OCI-compliant file, not only Dockerfiles. This could reduce complexity and tool sprawl, but I see application owners managing their repositories with simple backup and restore processes. Then I see enterprises coming in on top and doing their backups, scanning, and so forth. We must move beyond the Docker Registry v2 spec and into more universal places to push and pull images, charts, object configs, and other YAML bits. A sole source of truth is more manageable and easier to harden than 18 sources of truth. One OCI registry spec to rule all objects. That means a limitation needs to be brought to light, or conversations somewhere need to happen. I've only started looking into the issue recently, but I'm curious why it hasn't happened after talking to Kat Morgan. It feels like the right thing to do for developers and ops folks alike (not saying you'd all use the same registry. But, consistent tooling that's familiar to all teams is easier to make compliant.

#### Lightning Bolt of Logic

One lightning bolt from the realm of logic and reason came from Aaron Aldrich. "We won't run our systems past 80% load, but we refuse to let humans run at anything less than 100%." This is a remarkable fact of life. The talk was so inspiring I submitted a similar talk about my mental health struggles to [Deserted Island DevOps][2]. Lord knows the past year alone is enough to undo someone, let alone see them thrive. It took a lot of hard work and courage to get here.

### AWS Heros

We also had a few internal AWS events happening this week. I wanted to go to one on Thursday. But while walking there, I got diverted to an AWS Heros meeting. My boss was ill (and has a strong desire not to get others sick). I quickly get through the "fog of confusion" and into "roll with the punches" mode. The change in direction is always the hardest; once you've pivoted, you're off and running.

It's always great to get insights from our customers. [Even better to meet people you've helped along the way][3]. I always learn a lot talking to customers. But, many of the pain points I heard are still around organizational cultural problems. I spoke to one AWS Hero that defined the quintessential DevOps nightmare situation. With DevOps being over a decade old, you'd think we wouldn't be in this position anymore, yet here we are. This is why evolution is critical. There's a lot of something-something-Ops out there, but if you have Kubernetes in your stack, [GitOps][4] is for you.

I did hear murmurs like, "Do we have to run Kubernetes?" The answer is no. But, what are you trying to do? What might you be losing out on, or worse, hand jamming into production? People are fallible. Wouldn't systems scanning an audit log and taking actions as programmed when events trigger be a good default practice? There's some complexities to getting that done at scale. Once you're of a certain size, yes, Kubernetes makes sense. But, if you find a better abstraction point for your organization, do it. You also might have the engineering talent of Netflix and build your own thing if you want. But I got news for Netflix folks. All the bespoke open source projects they've created for internal use look like a lot of technical debt when your company is up against rough times and a competitive market environment. The layoffs and downturn will have you wishing you didn't build everything yourself once you've been whittled to a certain point. I mention Netflix because they seem to be the new Google. Netflix is doing it all on its own and [telling people their biggest competitor is sleep][5] (so by having a Netflix account, you are buying into the fact that you want less sleep). Why the hell would you ever tell a public audience that? That level of hubris led to Docker's ultimate demise.

[1]: https://github.com/chris-short/devopsish.com/tree/main/content/post
[2]: https://desertedislanddevops.com/
[3]: https://twitter.com/margaretvaltie/status/1550186266167152640
[4]: https://opengitops.dev/
[5]: https://twitter.com/chrisshort/status/1549850632395206656

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Jobs

Now Hiring: [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003)  
[Camunda](https://camunda.com/) is the leader in process orchestration software. Our software helps orchestrate complex business processes that span people, systems, and devices. With Camunda, business users collaborate with developers to model and automate end-to-end processes using BPMN-powered flowcharts that run with the speed, scale, and resiliency required to compete in today's digital-first world.

As the [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003), you'll be the direct people manager for a team of 4 Developer Advocates, responsible for career growth, performance evaluations, setting of priorities, and overall strategic guidance. You'll also be responsible for strategic planning for the Developer Advocacy function, including quarterly OKRs and annual goals as well as documentation of team responsibilities, goals, and success metrics.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**SCALE 19x**](http://www.socallinuxexpo.org/?utm_source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we're expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We're excited to welcome you back to our Deserted Island this September 14th and 15th!

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?utm_source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

## People

[Google to slow hiring, Pichai calls for 'consolidating where investments overlap' [U: Pause]](https://9to5google.com/2022/07/20/google-hiring-slow-down/)  
Abner Li, 9 to 5 Google  
Temporary freezes are an interesting slow down model. On the one hand you're not hiring for two weeks which simply pushes the costs a couple weeks down the road. It's like saying you need another two weeks to get your books *just* right.

[Spf13 google](https://spf13.com/p/spf13-google/)  
Steve Francia (spf13)  
After six years directly on the Go team at Google, Steve Francia is changing jobs. No one is immune from the Great Resignation.

[Ondat cuts headcount amid market pressures](https://blocksandfiles.com/2022/07/18/ondat-layoffs/)  
Chris Mellor, Blocks and Files  
"Kubernetes storage startup [Ondat](https://www.ondat.io/) has gone through a layoff exercise as market conditions make business life much harder."

[E-Commerce Startup Fabric Pulled Employee Stock-Buyback Program](https://www.businessinsider.com/e-commerce-startup-fabric-pulled-employee-stock-buyback-program-2022-7)  
Kylie Robison, Business Insider  
"Any employee who had been there for 12 months or more would be eligible, the email explained. Ten days later, the tender offer was abruptly scuttled before it even began."

[CoffeeOps](http://www.coffeeops.org/)  
I heard about this group at DevOpsDays Seattle. If anyone wants to start a Midwest one, let me know.

## Process

[The Path to GitOps](https://developers.redhat.com/e-books/path-gitops)  
Christian Hernandez, Codefresh  
In his final Red Hat act, Christian Hernandez has released an ebook titled, "The Path to GitOps" I was fortunate enough to be asked to write the foreword for this book. So two ex-Red Hatters wrote this one. If you don't have a Red Hat Developers login, and trust me, [here's the PDF](https://shortcdn.com/devopsish/Path-to-GitOps-Red-Hat-Developer-e-book.pdf).

[Nutanix Objects Violates MinIO's Open Source License](https://blog.min.io/nutanix-objects-violates-minios-open-source-license/)  
Garima Kapoor, MinIO  
"If you are a customer of Nutanix Objects, there may be legal and security risks you should be aware of as a consequence of these license violations. You may not be on the latest version of the MinIO Object Storage Software, and you may not be receiving adequate IP licenses from Nutanix." It would appear that Nutanixbadger don't give a fuck ([here's their response](https://www.nutanix.com/blog/open-source-statement)).

[Apple Releases Security Patches for all Devices Fixing Dozens of New Vulnerabilities](https://thehackernews.com/2022/07/apple-releases-security-patches-for-all.html)  
Ravie Lakshmanan, The Hacker News  
Sorry, I have to stay home and update my Apple devices is 2022's lowest rejection line ever.

[Digital security giant Entrust breached by ransomware gang](https://www.bleepingcomputer.com/news/security/digital-security-giant-entrust-breached-by-ransomware-gang/)  
Lawrence Abrams, Bleeping Computer  
"Approximately two weeks ago, a source told BleepingComputer that Entrust was breached on June 18th and that the hackers stole corporate data during the cyberattack. However, it wasn't until yesterday that the breach was publicly confirmed when security researcher Dominic Alvieri [tweeted a screenshot](https://twitter.com/AlvieriD/status/1550119202287013891) of a security notice sent to Entrust's customers on July 6th."

[TeamViewer installs suspicious font only useful for web fingerprinting](https://www.ctrl.blog/entry/teamviewer-font-privacy.html)  
Daniel Aleksandersen, Ctrl blog  
tl;dr After some digging someone did find a very thin but, legit use case. After all the hullabaloo, TeamViewer is going to remove the font in a future release.

[6 Tips to Overcome Scaling Challenges Like Design Decisions, Tech Debt, and Developer Satisfaction](https://alphalist.com/blog/6-tips-to-overcome-scaling-challenges-like-design-decisions-tech-debt-and-developer-satisfaction)  
Rachel Potvin, VP Engineering at GitHub, alphalist Podcast  
"What worked when your company was founded will no longer work now that you are scaling and hiring at a rapid pace. How will people communicate? How will tech debt be tackled? The choices one engineer makes affect many more people so now it's time for you to strategize on how your increased workforce works together.  Rachel tackled many scaling challenges when the team she led grew threefold - to 500 people! This is what she shared on the alphalist CTO podcast on how she had to adapt as the team grew."

## Tools

[How Kubernetes Broke Git](https://matt-rickard.com/how-kubernetes-broke-git/)  
Matt Rickard  
"How did Kubernetes push git to its limit? Some stories from my time (2016-2019) working on Kubernetes."

[K8s Gateway API is here - what's in it for you?](https://www.groundcover.com/blog/k8s-gateway-api)  
Noam Levy, groundcover  
"Enabling Kubernetes users to build expertise in universal apis instead of becoming vendor-specific experts will help build more mature products, focus on creating value and apply our skills more easily and in different environments."

[Getting Started With Ephemeral Containers](https://metalbear.co/blog/getting-started-with-ephemeral-containers/)  
Mehul Arora , MetalBear 🐻  
"Ephemeral containers let us run a container with a specific image in the context of an already running container in a Pod. This comes in handy when debugging/troubleshooting distroless images or images that lack certain utilities, where `kubectl exec` won't be helpful." After seeing how this worked in practice at DevOpsDays Seattle, my containers doing work on Kubernetes are about to lose some layers.

[Using vcluster with Gloo Mesh for fast k8s Dev Environments](https://loft.sh/blog/development-environments-with-vcluster-a/)  
Antonio Berben, Loft  
Here's how you can test your prod environment more locally.

[1 Billion Flux Downloads Show GitOps Gaining Ground](https://containerjournal.com/features/1-billion-flux-downloads-show-gitops-gaining-ground/)  
Mike Vizard, Container Journal  
"Weaveworks today says container images of its open source Flux version control software have now been downloaded more than one billion times. Flux is at the core of Weaveworks' GitOps platform. In addition, the company claims that its enterprise customer base doubled in the first half of 2022, which led to a corresponding increase in revenue for the same period."

[Cilium 1.12 - Ingress, Multi-Cluster, Service Mesh, External Workloads, and much more](https://isovalent.com/blog/post/cilium-release-112/)  
Isovalent  
A lot of extra bits being launched in this release.

[Scaling Kubernetes with Karpenter: Advanced Scheduling with Pod Affinity and Volume Topology Awareness](https://aws.amazon.com/blogs/containers/scaling-kubernetes-with-karpenter-advanced-scheduling-with-pod-affinity-and-volume-topology-awareness/)  
Lukonde Mwila, Principal Technical Evangelist, SUSE, AWS Containers Blog  
"A hands-on approach to scaling Kubernetes with [Karpenter](https://karpenter.sh/) specifically for supporting advanced scheduling techniques with inter-pod affinity and volume topology awareness." Karpenter implements what autoscalers should do, look the the spec file and figure out the best compute to put it on.

[mgoltzsche/khelm](https://github.com/mgoltzsche/khelm)  
⭐️ 57  
A Helm chart templating CLI, kustomize plugin and containerized kustomize/kpt KRM function

[opcr-io/policy](https://github.com/opcr-io/policy)  
⭐️ 84  
CLI for building OPA policies into OCI images

[Exein-io/pulsar](https://github.com/Exein-io/pulsar)  
⭐️ 89  
A highly modular and blazing fast runtime security framework for the IoT, powered by eBPF.

[SpatiumPortae/portal](https://github.com/SpatiumPortae/portal)  
⭐️ 166  
Portal is a quick and easy command-line file transfer utility from any computer to another 🖥️ 🌌 💻

[OpenSLO/OpenSLO](https://github.com/OpenSLO/OpenSLO)  
⭐️ 837  
Open specification for defining and expressing service level objectives (SLO)

[carbon-language/carbon-lang](https://github.com/carbon-language/carbon-lang)  
⭐️ 14.4K  
"An experimental successor to C++" Carbon Language's main repository: documents, design, implementation, and related tools. (NOTE: Carbon Language is experimental; see README)

[AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)  
⭐️ 24.6K  
AppFlowy is an open-source alternative to Notion. You are in charge of your data and customizations. Built with Flutter and Rust.

## DevOps'ish Post of the Week

[![u/Ordinary-March on r/kubernetes: "Is the Universe a giant Kubernetes cluster where galaxies are namespaces, stars are pods, planets sidecar containers and gravity a well designed service mesh!" / Reddit)](https://shortcdn.com/devopsish/277-devopsish-post-of-the-week.webp)](https://www.reddit.com/r/kubernetes/comments/w2h7bz/is_the_universe_a_giant_kubernetes_cluster_where/?utm_source=devopsish)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/277/notes.md)