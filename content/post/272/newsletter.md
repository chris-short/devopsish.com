+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-06-19T07:00:00Z
description = ["Conway's Law and GitOps, Arctic undersea cable, revoking job offers is the new layoff, Symbiote, and more"]
draft = false
slug = "272"
tags = ["open source", "GitOps", "system", "Argo", "Conway's Law", "processes", "events", "security", "management", "Julia Ferraoili", "Linux", "Raspberry Pi", "communication", "Kubernetes", "community", "organization", "git", "Coinbase", "eBPF", "multimeter", "kernel", "compose", "debug", "ArgoCon"]
title = "DevOps'ish 272: Conway's Law and GitOps, Arctic undersea cable, revoking job offers is the new layoff, Symbiote, and more"
+++

I'll be at Open Source Summit this week in Austin. If you see me, stop me and say hello.

Conway's Law and GitOps are two things that go hand in hand. I'd like that not to be the case, but in building and working with an upcoming demo of multi-cluster GitOps, I'm worried GitOps might not reach an escape velocity over Conway's Law.

[Conway's Law](https://en.wikipedia.org/wiki/Conway%27s_law) states, "Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure." This might seem natural but think about the different ways we communicate now. E-mail, text messages, phone calls, Slack, Discord, Twitter, etc. are all communication tools that serve various purposes. But, in GitOps, whether you design around a good developer experience (using git as the only interface) or design around a minimalistic amount of tooling (one secret management solution), that tooling has to fit within Conway's Law usually.

For example, if you want to use an existing tool with GitOps, that's entirely possible. But, that tool, let's say a key management system (KMS), has rules of its use, and automating them will need you to build a system that can interface well with the team that runs that system. If you're lucky, you can run your Vault in your namespace and minimize handoffs. This is the only way to escape Conway's Law in GitOps. Decoupling the entire system from the rest of the org. Bring everything you need as a team to the platform, and running it all yourself will minimize the communication lanes, but I doubt it will reduce your system's footprint.

Sure. You can then dictate what communications need to occur to make system changes. But, this will create a lot of overlap, and at some point, someone in compliance or finance or both will say, "Everyone is running their own Vaults with different policies and availability metrics. We could run Vault Enterprise and have all our regulatory needs met and HA." Now you have to communicate outside your team. That will lead to you building a system that looks like the communication structure of your organization. This isn't bad. It's something you need to be aware of.

This is when Conway's Law and GitOps intersect. The moment you start to make optimizations to the system at scale. Secrets management is a crucial yet still engineering-intensive part of GitOps. Who manages the key management system? Who creates an "inception secret" that opens the door to seed all the other secrets? What processes create a management cluster? All these answers will come back to Conway's Law. It's like fate or Darth Vader telling Luke Skywalker, "Let's rule the Galaxy together as Father and Son!" This is something that isn't pleasant, but we have to accept it.

There are specific components you need to make a GitOps workflow. These foundational steps should be on a trail map of their own for GitOps. CNCF, Weaveworks, or Amazon could make it. That would be the top half of the page. The bottom half of the page lies this intro about the intersection of GitOps and Conway's Law.

This might be the last piece I write on GitOps for a little bit. I'm making a move internally and won't be directly focused on Kubernetes. Being in that community (or, more accurately, being in CNCF's chaotic orbit) has taken a significant toll on me lately. I will still be in the container ecosystem, and you'll see me around. But, at the end of the month, my journey on the EKS team will change to a new one I'm very excited about.

## Observability Leader Honeycomb Releases O’Reilly Book on Observability

Honeycomb helps you sift through billions of events to see your application’s hidden problems so you can quickly debug before users notice. Get your FREE copy of our [new O’Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors’ Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts

## Events

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

## People

[Sustain Episode 124: Julia Ferraioli on Open Source Stories, and Responsible Recognition for Open Source Contributions](https://podcast.sustainoss.org/124)  
Sustain  
"We have joining us as our guest, Julia Ferraioli, who’s an open source human, co-founded Open Source Stories, and has been part of the Sustain community for a while. Our conversations today take us through learning about Julia’s background, what Open Source Stories is, and how she quantifies a black swan open source. We also learn about two camps of people who work on open source that Julia encountered, a detailed explanation of what “matters” means, and what Julia does when she works on standardizing open source information. Go ahead and download this episode now to hear more!"

[A Warming Arctic Emerges as a Route for Subsea Cables](https://www.wsj.com/articles/a-warming-arctic-emerges-as-a-route-for-subsea-cables-11655323903)  
Isabelle Bousquette, Wall Street Journal  
"Northern countries are racing to build undersea communications cables through the waters of the Arctic, as shrinking ice coverage opens the region to new business opportunities and heightens geopolitical rivalries between Russia and the West." The cable's route takes it from Japan, to the Aluetian Islands, to the northern part of Alaska, through northern Canada, around Greenland then terminates in Ireland and Norway.

[Russia is taking over Ukraine’s Internet](https://arstechnica.com/tech-policy/2022/06/russia-is-taking-over-ukraines-internet/)  
Matt Burgess, WIRED  
"Multiple Ukrainian ISPs are now forced to switch their services to Russian providers and expose their customers to the country’s vast surveillance and censorship network, according to senior Ukrainian officials and technical analysis viewed by WIRED."

[Canadian internet outage attributed to beaver](https://therecord.media/canadian-internet-outage-beaver/)  
Andrea Peterson, The Record by Recorded Future  
"BC Hydro official Bob Gammer told [CTV](https://bc.ctvnews.ca/single-beaver-caused-mass-internet-cell-service-outages-in-northern-b-c-1.5944697) an aspen tree knocked out a Telus fiber optic cable strung along power lines, but the fallen tree had the telltale gnaw marks of Canada’s once-endangered largest rodent. "

[SpaceX Said to Fire Employees Involved in Letter Rebuking Elon Musk](https://www.nytimes.com/2022/06/17/technology/spacex-employees-fired-musk-letter.html)  
, The New York Times
"SpaceX, the private rocket company, on Thursday fired employees who helped write and distribute [an open letter](https://www.nytimes.com/2022/06/16/technology/spacex-employees-musk-tweets.html) criticizing the behavior of its chief executive, Elon Musk, said three employees with knowledge of the situation."

## Process

[A message from Coinbase CEO and Cofounder, Brian Armstrong](https://blog.coinbase.com/a-message-from-coinbase-ceo-and-cofounder-brian-armstrong-578d76eedb12)  
Brian Armstrong, CEO of Coinbase  
"Today I am making the difficult decision to reduce the size of our team by about 18%, to ensure we stay healthy during this economic downturn. I want to walk you through why I am making this decision below, but first I want to start by taking accountability for how we got here. I am the CEO, and the buck stops with me."

[Stitch Fix shares sink after company announces layoffs, offers weak guidance](https://www.cnbc.com/2022/06/09/stitch-fix-is-laying-off-15percent-of-its-salaried-employees-internal-memo-says.html)  
Lauren Thomas, CNBC  
"Stitch Fix is laying off 15% of its salaried workers, or about 330 people. The company also issued weak revenue guidance as it contends with weaker consumer demand. Shares of the company fell Thursday to $7.78. A year ago, the stock was trading above $68."

[Revoking job offers is an increasingly common cost-cutting strategy](https://www.axios.com/2022/06/09/revoking-job-offers-is-an-increasingly-common-cost-cutting-strategy)  
Emily Peck, Axios  
"Tech companies are hitting the brakes on record levels of hiring over the past two years. It's happening so fast that instead of the usual mix of layoffs and slower backfills, employers like [Coinbase](https://blog.coinbase.com/update-on-hiring-plans-bcedfa634989), [Redfin](https://www.linkedin.com/feed/update/urn:li:activity:6933122396723826688/?commentUrn=urn%3Ali%3Acomment%3A%28activity%3A6933122396723826688%2C6933191061397782528%29), [Twitter](https://www.linkedin.com/posts/muyang-wang-b61181ba_unofficial-twitter-affected-new-grads-input-activity-6937465477581479936-9Qv0?utm_source=linkedin_share&utm_medium=member_desktop_web) and some startups are rescinding lucrative job offers — a practice last seen widely during the financial crisis."

[Credentials for thousands of open source projects free for the taking—again!](https://arstechnica.com/information-technology/2022/06/credentials-for-thousands-of-open-source-projects-free-for-the-taking-again/)  
Dan Goodin, Ars Technica  
How is Travis CI still around?

[Symbiote: A New, Nearly-Impossible-to-Detect Linux Threat](https://blogs.blackberry.com/en/2022/06/symbiote-a-new-nearly-impossible-to-detect-linux-threat)  
Dr. Joakim Kennedy, The BlackBerry Research & Intelligence Team  
"What makes Symbiote different from other Linux malware that we usually come across, is that it needs to infect other running processes to inflict damage on infected machines. Instead of being a standalone executable file that is run to infect a machine, it is a shared object (SO) library that is loaded into all running processes using LD_PRELOAD (T1574.006), and parasitically infects the machine. Once it has infected all the running processes, it provides the threat actor with rootkit functionality, the ability to harvest credentials, and remote access capability."

## Tools

[Tetragon – Kubernetes eBPF-based Security](https://blog.sectool.co/ebpf-based-security)  
SECTOOL  
Tetragon detects and is able to react to security-significant events, such as, process execution events, system call activity, and I/O activity including network & file access.

[Validate Your YAML (with CUE)](https://earthly.dev/blog/yaml-validate-and-lint-cue-lang/)  
Adam Gordon Bell, Earthly Blog  
"Cuelang can be used to specify a schema for a plain YAML file. You can put your types in a separate file and run `cue vet types.cue plain.yml` and start benefiting from static types right away."

[Introducing Furiko, an open-source, Kubernetes-native job platform](https://furiko.io/blog/introducing-furiko/)  
Irvin Lim and Shen Tao  
"Furiko is able to schedule jobs to be run on a periodic or once-off basis, supports a wide variety of use cases, and is able to scale to millions of executions per day."

[If OpenSSL were a GUI](https://smallstep.com/blog/if-openssl-were-a-gui/)  
Carl Tashian, smallstep  
It'd be ugly af.

[How To Use a Multimeter to Measure Voltage, Current and More](https://www.tomshardware.com/how-to/use-a-multimeter-in-electronic-circuits)  
Jo Hinchliffe, Tom's Hardware  
"But no matter what level of maker you may be, we all need a Digital Multimeter. A multimeter enables us to make accurate measurements of both current and voltage, can help us test and debug circuits by checking continuity and can help us identify component values."

[eBPF, sidecars, and the future of the service mesh](https://buoyant.io/2022/06/07/ebpf-sidecars-and-the-future-of-the-service-mesh/)  
William Morgan, Buoyant  
"The eBPF service mesh still requires proxies"

[s-matyukevich/raspberry-pi-os: Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)  
Sergey Matyukevich  
"This repository contains a step-by-step guide that teaches how to create a simple operating system (OS) kernel from scratch. I call this OS Raspberry Pi OS or just RPi OS. The RPi OS source code is largely based on Linux kernel, but the OS has very limited functionality and supports only Raspberry PI 3."

[saraford/three-git-tips](https://github.com/saraford/three-git-tips)  
Sara Ford  

1. How to demystifying git commands using the best visualization tool ever
2. Why there is no "git undo"
3. Find when a bug first started occurring in a repo without ever looking at code

[F1bonacc1/process-compose](https://github.com/F1bonacc1/process-compose)  
Process Compose is like docker-compose, but for orchestrating a suite of processes, not containers

[prowler-cloud/prowler](https://github.com/prowler-cloud/prowler)  
Prowler is an Open Source security tool to perform AWS security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness. It contains more than 240 controls covering CIS, PCI-DSS, ISO27001, GDPR, HIPAA, FFIEC, SOC2, AWS FTR, ENS and custom security frameworks.

[borisdayma/dalle-mini](https://github.com/borisdayma/dalle-mini)  
DALL·E Mini - Generate images from a text prompt

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
