+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-10-17T07:00:00Z
description = ["KubeCon, tzdata, weak SSH keys revoked, Linux kernel CPU Namespace proposal, multicloud, and more"]
draft = false
slug = "239"
tags = ["time", "CPU", "cloud", "data", "DevOps", "code", "Cloud Native", "open source", "software", "security", "infrastructure", "namespace", "Linux", "TLS", "AWS", "Red Hat", "community", "SSH", "KubeCon", "Kubernetes", "GitOps"]
title = "DevOps'ish 239: KubeCon, tzdata, weak SSH keys revoked, Linux kernel CPU Namespace proposal, multicloud, and more"

+++

KubeCon + CloudNativeCon North America 2021 in Downtown Los Angeles was fantastic. I got to see friends I hadn't seen in a long time and some people I met for the first time. "I didn't realize you were so tall" was a common statement from people I was meeting for the first time. It was very cool to meet folks in the community and Red Hat for the first time. It was also interesting to see new companies entering the cloud native ecosystem. I spent more than one time looking up companies or products I'd not heard of before. It was also interesting NOT to see Google Cloud or VMware there. Those companies opted not to get a booth based on their company COVID-19 policies.

It was a little weird being in such a large venue with only a few thousand people. The L.A. Convention Center made for some long walks. I ended up crushing my Apple Health rings every day. Except for maybe the last day on site. One thing I noted after day two was that I was very dehydrated. You can't drink while wearing a mask. It got to the point where I drank a liter to two liters before the conference. Retreat outside and drink as much water as possible. I was then drinking a ton of water at the end of the day.

I was pleased with how my shoulder performed overall too. I used more lidocaine than usual while staying ahead of the pain curve. It worked until the last day. Then a little after 5 PM PT, the spasms started and didn't stop until I was in bed. It was the kind of "arm ripping off" pain that wasn't going away. I never really adjusted to being on the west coast either. After not traveling for so long and no travel on the immediate horizon, my body was not motivated enough to jump over to west coast time. Which made for long days, but I hit the ground running on Saturday.

Overall, it was a great conference. I wish everyone had equal access. Also, I can't wait to show y'all Detroit next year.

## People

[The Largely Untold Story Of How One Guy In California Keeps The World's Computers Running On The Right Time Zone. (Well, Sort Of)](https://onezero.medium.com/the-largely-untold-story-of-how-one-guy-in-california-keeps-the-worlds-computers-on-the-right-time-a97a5493bf73)  
"Down the rabbit hole: my brief odyssey into the esoteric world of the tight-knit time zone data maintenance community who quietly keep the world's computers from avoiding DST-related-meltdowns"

Make incredibly fast fault localization your second nature. Find the right issue the first time. Quickly optimize your code. Build reliable services. Create happier teams and customers. Production incidents? No sweat! [Sign up for free Honeycomb](https://honeycomb.quip.com/76D4AHU5mYvF/Devopsish-ad-copy-Guide-Product-Signup). *SPONSORED*

[2021 Last Week in AWS Charity T-Shirt](https://store.lastweekinaws.com/collections/2021-charity-shirt)  
"The world might be melting, but just think happy thoughts. It works for the AWS status page! Now you can wear the comfort of the world’s most reliable static website everywhere you go."

[US has already lost AI fight to China, says ex-Pentagon software chief](https://www.ft.com/content/f939db9a-40af-4bd1-b67d-10492535f8e0)  
He's right.

[Researchers show Facebook's ad tools can target a single user](https://techcrunch.com/2021/10/15/researchers-show-facebooks-ad-tools-can-target-a-single-user/)  
"The research raises fresh questions about potentially harmful uses of Facebook's ad targeting tools, and — more broadly — questions about the legality of the tech giant's personal data processing empire given that the information it collects on people can be used to uniquely identify individuals, picking them out of the crowd of others on its platform even purely based on their interests." Delete Facebook, Instagram, WhatsApp, Oculus, and any other Facebook owned entity.

[Was Our Universe Created in a Laboratory?](https://www.scientificamerican.com/article/was-our-universe-created-in-a-laboratory/)  
"Developing quantum-gravity technologies may elevate us to a 'class A'”' civilization, capable of creating a baby universe" The idea of somehow generating a universe being a technology that is harnessed by humankind is a wild concept.

## Process

[Azure, GitHub, GitLab, BitBucket mass-revoke SSH keys following bug report](https://therecord.media/azure-github-gitlab-bitbucket-mass-revoke-ssh-keys-following-bug-report/)  
"Microsoft, GitHub, GitLab, and BitBucket—four of today's largest code hosting portals—have initiated mass revocations of SSH keys on Monday after the discovery of a vulnerability in a popular Git software client named GitKraken."

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
Code, No Manual Processes. Automate Terraform tasks, reduce errors and drifts, improve security and auditability of your infrastructure. env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. *SPONSORED*

[IBM Proposing A CPU Namespace For The Linux Kernel - Phoronix](https://www.phoronix.com/scan.php?page=news_item&px=Linux-CPU-Namespace)  
"The CPU namespace isolates CPU information by virtualizing logical CPU IDs and creating a scrambled virtual CPU map of the same. It latches onto the task_struct and is the cpu translations designed to be in a flat hierarchy this means that every virtual namespace CPU maps to a physical CPU at the creation of the namespace. The advantage of a flat hierarchy is that translations are O(1) and children do not need to traverse up the tree to retrieve a translation."

[How Rust developers are making the web safer](https://github.com/readme/featured/rust-programming)  
"'Memory safety isn’t just a technical issue, it’s a social issue as well,' Internet Security Research Group Executive Director Joshua Aas. 'Memory safety issues don’t just produce buggy software. They can crash services that people rely on to make a living or find employment. Security flaws can rob us of our privacy. Software can and should be built in better ways.'"

[NSA warns of ALPACA TLS attack, use of wildcard TLS certificates](https://therecord.media/nsa-warns-of-alpaca-tls-attack-use-of-wildcard-tls-certificates/)  
"The National Security Agency has issued a technical advisory this week warning organizations against the use of wildcard TLS certificates and the new ALPACA TLS attack."

## Tools

[Linux Patches Rewrite The Retpoline Rewrite Code - Possible Performance Benefit](https://www.phoronix.com/scan.php?page=news_item&px=Linux-Retpoline-Rewrite-Rewrite)  
"The Linux kernel has supported Retpolines for over three years now as part of their Spectre Variant Two mitigations while now a patch series is proposed that rewrites Retpoline's rewrite logic."

[Preventing Data Exfiltration with eBPF](https://goteleport.com/blog/preventing-data-exfiltration-with-ebpf/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish)  
Keep your data protected by developing security policies that target specific processes with eBPF. *SPONSORED*

[Learn TypeScript in 5 minutes](https://swizec.com/blog/learn-typescript-in-5-minutes/)  
"TypeScript is a language extension that adds static typing to JavaScript. It reached a breaking point sometime in 2020 and is fast becoming the default way to write JavaScript." I loathe JavaScript and I'm picking up some TypeScript here and there.

[Multicloud failover is almost always a terrible idea](https://cloudpundit.com/2021/10/14/multicloud-failover-is-almost-always-a-terrible-idea/)  
"Regulators, risk managers, and plenty of IT management largely think of AWS, Azure, etc. as monolithic entities, where 'the cloud' can just break for them, and then kaboom, everything is dead everywhere worldwide. They imagine one gargantuan amorphous data center, subject to all the problems that can afflict single data centers, or single systems. But that's not how it works, that's not the most effective way to address risk, and testing the 'resilience of the provider' (as a generic whole) is both impossible and meaningless."

[Which Version of JDK Should I Use?](https://whichjdk.com/)  
"The [OpenJDK](https://openjdk.java.net/) is the open source reference implementation of the Java SE Specification, but it is only the source code. Binary distributions are provided by different vendors for a number of supported platforms. These distributions differ in licenses, commercial support, supported platforms, and update frequency."

[kuberlogic/kuberlogic](https://github.com/kuberlogic/kuberlogic)  
Kuberlogic is an open-source product that deploys and manages software on top of the Kubernetes cluster and turns infrastructure into a managed PaaS.

[parca-dev/parca](https://github.com/parca-dev/parca)  
Continuous profiling for analysis of CPU, memory usage over time, and down to the line number. Saving infrastructure cost, improving performance, and increasing reliability.

[DiscoRiver/massh](https://github.com/DiscoRiver/massh)  
Go package for running Linux distributed shell commands via SSH.

[romkatv/zsh-bench](https://github.com/romkatv/zsh-bench)  
Benchmark for interactive zsh

## DevOps'ish Tweet of the Week

[![Laura is at #KubeCon NA (@nimbinatus) on Twitter: "We had a great time at the @K8sContributors SIG Meet and Greet at #kubecon2021! I bring you the folks that made it happen, on their way to the event itself, in epic video form (and I may have had too much fun making this video)."](https://shortcdn.com/devopsish/239-devopsish-tweet-of-the-week.png)](https://twitter.com/nimbinatus/status/1448666894815297536)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/239/notes.md) to see what didn't make it to the newsletter but are still worth your time.
