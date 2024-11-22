+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-11-28
description = ["Please do not attempt to simplify this code, Rust Mod Team, feedback, attackers don't bother brute-forcing long passwords, GitOps, kube-scheduler-simulator, and more"]
draft = false
slug = "245"
tags = ["code", "Kubernetes", "Space Shuttle", "open source", "simplify", "team", "GitOps", "Cloud", "DevOps", "scheduler", "simulator", "free", "Cloud Native", "Rust", "kube", "brute forcing", "infrastructure", "sigstore", "Amazon", "persistent volumes", "NASA", "process", "Linux", "gp3", "automation", "practices", "clever", "Microsoft", "Honeycomb", "quantum", "persistent volume controller", "Riverbed", "NVIDIA", "Apple", "Pulumi", "developers", "Fedora", "AWS", "CNCF", "Red Hat"]
title = "DevOps'ish 245: Please do not attempt to simplify this code, Rust Mod Team, feedback, attackers don't bother brute-forcing long passwords, GitOps, kube-scheduler-simulator, and more"

+++

["PLEASE DO NOT ATTEMPT TO SIMPLIFY THIS CODE. KEEP THE SPACE SHUTTLE FLYING."](https://github.com/kubernetes/kubernetes/blob/5a81905f772c28dc4c8f5d2cb2e5bfc48c422f41/pkg/controller/volume/persistentvolume/pv_controller.go): This almost 2000 lines of code that make up the [persistent volume controller](https://kubernetes.io/docs/concepts/storage/persistent-volumes/) was one of the most popular social media posts this week:

{{< highlight go "linenos=table,hl_lines=3-4,linenostart=58" >}}
 
// ==================================================================
// PLEASE DO NOT ATTEMPT TO SIMPLIFY THIS CODE.
// KEEP THE SPACE SHUTTLE FLYING.
// ==================================================================
//
// This controller is intentionally written in a very verbose style. You will
// notice:
//
// 1. Every 'if' statement has a matching 'else' (exception: simple error
//    checks for a client API call)
// 2. Things that may seem obvious are commented explicitly
//
// We call this style 'space shuttle style'. Space shuttle style is meant to
// ensure that every branch and condition is considered and accounted for -
// the same way code is written at NASA for applications like the space
// shuttle.
//
{{< / highlight >}}

Two things struck me about this comment:

1. The two times NASA was arrogant or, at the time, clever and thought it knew better (Space Shuttles Challenger and Columbia), those crews didn't come home alive. The pressure of a human or a team or an administration (NASA) not succeeding at their best guess outweighed the lives of those people on those spacecraft (sorry, grew up in Florida, might have been close to the shuttle program later in life, I have strong opinions). This Space Shuttle philosophy embarked in the code here also falls in line with the ye ole developers mantra, "[Clear is better than clever](https://dave.cheney.net/2019/07/09/clear-is-better-than-clever?utm_source=newsletter&utm_medium=237&utm_campaign=devopsish&utm_term=hi+dave&utm_content=love+chris)."
1. I happened to know some folks involved in contributing this code. So I asked questions.

In the early days of Kubernetes, persistent volumes (the Achilles heel of a container orchestrator being state and all) weren't considered reliable. This made widespread adoption of Kubernetes (state being the lifeblood of businesses worldwide and all) was pretty dependent on this feature workings.

In 2016, some Kubernetes contributors were locked in a room. Eventually, they all agreed. They needed to be sure that every use case was covered. No matter what, even if it was a no-op, EVERY USE CASE had to be covered. Naturally, PRs came in from people that wanted to help. People tried to simplify the code. But, there was something about the approach taken, the process behind the code, that needed to be codified. So it was written, "PLEASE DO NOT ATTEMPT TO SIMPLIFY THIS CODE. KEEP THE SPACE SHUTTLE FLYING."

## People

[Rust Mod Team Resigns in Protest of ‘Unaccountable’ Core Team](https://thenewstack.io/rust-mod-team-resigns-in-protest-of-unaccountable-core-team/)  
Core teams only accountable to themselves isn't good. It's an abuse petri dish. I have to be honest I didn't do much more digging after reading this article. If you have a perspective on this that shows a pattern of abuse please feel free to reach out.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Don't soften feedback](https://larahogan.me/blog/dont-soften-feedback/)  
"Managers: it’s your responsibility to clearly (and kindly) articulate what’s expected of your teammates in their roles, and what the gaps are. If you avoid being direct—even if it sucks to do so, on top of everything else happening in the world!—you’re setting them up for failure." You really are. I had to get shaken pretty hard at the beginning of the pandemic.

[Ably best-practices to optimize on-call shift rotations](https://ably.com/blog/best-practices-for-on-call-processes)  
"In the rest of this post, I outline how we manage on-call shifts at Ably, including what we've built and how we've optimized processes to benefit the team, and our customers." It's a good list.

[Web scale open source with Kubernetes - All Things Open 2021 (full talk)](https://www.youtube.com/watch?v=eym93NluVxc)  
Justin does an amazing job at virtual talks. "A video about Kubernetes and open source. The first video part of the Kubernetes Cinematic Universe (KCU)."

[How COVID-19 mRNA Vaccines Work - Vaccine Makers Project on Vimeo](https://vimeo.com/579667076)  
I found this video highly informative. Reading it on paper, it is harder to think out the process of having the body take in mRNA. This makes the immune system's custodial chain of that Nobel Prize winning technology pretty clear.

## Process

[Attackers don't bother brute-forcing long passwords, Microsoft engineer says](https://therecord.media/attackers-dont-bother-brute-forcing-long-passwords-microsoft-engineer-says/)  
Another reason why you shouldn't set your password policy to something shorter than a quantum safe number of characters. Sidenote: I can't believe dealing with quantum safe security is something I'm going to deal with in my life time. Didn't see that one coming but, looks like it will be.

Join us for [Honeycomb Developer Week](https://www.honeycomb.io/developer-week-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish) on Dec 13–15! With free hands-on training and snackable sessions, you’ll learn leading-edge observability practices in just a few hours. Find out how to debug why exactly your apps are slow for only some users. Learn to spot patterns, anomalies, and trends with distributed tracing. Tame alert noise and focus on what matters with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Busting 5 Sigstore Myths](https://chainguard.dev/posts/2021-11-19-sigstore-myths)

1. Short-lived certificates mean you need to re-sign your software artifacts constantly
1. Sigstore doesn’t support revocation
1. Sigstore is only for signing and verifying containers!
1. The transparency log means you can’t verify signatures offline
1. Sigstore is only for open source software

[Notes on GitOps potential role in compliance](https://redmonk.com/jgovernor/2021/11/19/notes-on-gitops-potential-role-in-compliance/)  
"But Git is helping us move forward as an industry, as a common underlying platform, not just in the Kubernetes world, but in pretty much every community and platform in software."

[Nvidia acquisition of Arm now under scrutiny by FTC](https://arstechnica.com/tech-policy/2021/11/nvidia-acquisition-of-arm-now-under-scrutiny-by-ftc/)  
If the UK and US are having cold feet, the EU will slam the door shut on this one. NVIDIA might have to go a different way. I wouldn't doubt for a second if there wasn't a supply shortage this deal would've sailed through.

[Riverbed Tech files for Chapter 11 bankruptcy protection](https://www.theregister.com/2021/11/18/riverbed_technologies_chapter11/)  
Riverbed. Ghastly things. Single points of failure were the only times I encountered these. It sucks for the employees, yes, but, y'all went a long time with WAN accelerators. There wasn't a lot of investment in other tech that could make a business profitable.

[Free Apple support](https://daniel.haxx.se/blog/2021/11/18/free-apple-support/)  
How not to open source.

## Tools

[kubernetes-sigs/kube-scheduler-simulator](https://github.com/kubernetes-sigs/kube-scheduler-simulator)  
A web-based simulator for the Kubernetes scheduler (Note: THIS IS COOL)

[Pulumi: Infrastructure as Code](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)
With Pulumi you can build, deploy and manage infrastructure on any cloud using familiar languages and tools. Provision infrastructure using Python, Go, JavaScript, TypeScript, and C#. Get started for free at [pulumi.com](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac) *SPONSORED*

[Amazon Linux 2022 Released - Based On Fedora With Changes](https://www.phoronix.com/scan.php?page=news_item&px=Amazon-Linux-2022-Preview)  
FWIW, I've run a Fedora Server for a long time now. It's actually acting as a hypervisor host too. No issues. It's kinda nice actually. To me, success here is AWS written fixes get applied upstream in a collaborative and open manner.

[Neat! It even includes the CNCF landscape. /r/kubernetes](https://www.reddit.com/r/kubernetes/comments/qzzu7k/neat_it_even_includes_the_cncf_landscape/)  
This made me laugh a little too hard.

[Migrating Amazon EKS clusters from gp2 to gp3 EBS volumes](https://aws.amazon.com/blogs/containers/migrating-amazon-eks-clusters-from-gp2-to-gp3-ebs-volumes/)  
Want your EKS cluster to take advantage of those fancy gp3 volumes? Here's how.

[amazonlinux/amazon-linux-2022](https://github.com/amazonlinux/amazon-linux-2022)  
Amazon Linux 2022

[cheat/cheat](https://github.com/cheat/cheat)  
"cheat allows you to create and view interactive cheatsheets on the command-line. It was designed to help remind *nix system administrators of options for commands that they use frequently, but not frequently enough to remember." Psst... It has `cheat xargs`.

[podtato-head/podtato-head](https://github.com/podtato-head/podtato-head)  
Demo App for TAG App Delivery (very cool, check it out GitOps nerds)

## DevOps'ish Tweet of the Week

If CSAIL does it like this, I'm putting in too much effort.

[![MIT CSAIL (@MIT_CSAIL) on Twitter) "How to regex. (comic v/@garabatokid)"](https://shortcdn.com/devopsish/245-devopsish-tweet-of-the-week.png)](https://twitter.com/MIT_CSAIL/status/1463587220841910272)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/245/notes.md) to see what didn't make it to the newsletter but are still worth your time.
