+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-10-11T07:00:00Z
description = "Kubernetes on spy planes, @K8sContributors, Unfck the internet, Demystifying GitOps, Cilium, and more"
draft = false
slug = "187"
tags = ["Kubernetes", "cloud", "cloud native", "DevOps", "internet", "IBM", "Red Hat", "GttOps", "infrastructure", "data", "security", "Wordpress", "hybrid cloud", "Mozilla", "observability", "runtime", "storage", "kernel", "GitHub", "Google", "Accurics", "Cilium", "GitOps"]
title = "DevOps'ish 187"

+++

Normally, I don't like to highlight military uses of Kubernetes (people have feelings about that; I do too, for that matter). But, this week, something rather significant happened out in Utah: [U-2 Federal Lab achieves flight with Kubernetes](https://www.hill.af.mil/News/Article-Display/Article/2375297/u-2-federal-lab-achieves-flight-with-kubernetes/). "The U-2 Federal Laboratory successfully leveraged Kubernetes during a local training sortie on a U-2 Dragon Lady assigned to the 9th Reconnaissance Wing at Beale Air Force Base, Sept. 22. This represents the first time Kubernetes has flown on an operational major weapon system in the Department of Defense."

Yes, OpenShift and Kubernetes are in use in ground systems across the US Department of Defense. But, I've not heard of Kubernetes running on actual airframes until this week. The fact the team on the U-2 did this is quite stunning. Remember, U-2s were critical intelligence gathering sources on overflight missions during the [Cuban Missile Crisis](https://en.wikipedia.org/wiki/Cuban_Missile_Crisis) ***in 1962***.

The U-2 program is a very old and sensitive program to the US government. As high and overarching as my clearances were, I never got close to the U-2 program (compartmentalization works). [The U-2](https://en.wikipedia.org/wiki/Lockheed_U-2) is a critical [C4ISR platform](https://www.northropgrumman.com/c4isr/) used in humanitarian and war fighting missions the globe over. The fact the U-2 program is leaning forward with containers and cloud native thinking makes me ask the same question I asked folks about [DevOps and the US nuclear weapons program](https://youtu.be/eKOGQKHOBNg?t=655). "If they can do it, why can't you?"

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

## People

Want to see your ad in DevOps'ish? Check out the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. Give the [DevOps'ish Sponsorship Prospectus](https://devopsi.sh/prospectus) a look if you need some help convincing others in your organization. *SPONSORED*

[K8sContributors Twitter Account](https://twitter.com/K8sContributors)  
Powered by Kubernetes SIG-Contributor-Experience; this is the Twitter account maintained by the [Kubernetes Upstream Marketing Team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) (which you join by showing up to the meetings on Fridays). And yes, we've made the process to send a tweet conform to community governance (using GitHub approvals, etc.). It's a great system that's only going to get better with time thanks to the efforts of those on the Kubernetes Upstream Marketing Team. Follow [K8sContributors](https://twitter.com/K8sContributors) and stay informed!

[Microsoft is letting more employees work from home permanently](https://www.theverge.com/2020/10/9/21508964/microsoft-remote-work-from-home-covid-19-coronavirus)  
I've been working from home non-stop for two years and had several jobs that allowed for it prior to that. Your home office is something you have to invest in making a space you enjoy and appreciate. I need to do a lot of work and flip things on my desk at some point so I can get more natural lighting in my field of view. It's just the next thing on the list. After that, there will be something small I can do to improve things. You don't get a dope setup overnight unless you win the lottery.

[Building Better Communication for Kubernetes Contributors with Marketing - Matthew Broberg, Red Hat, Kaslin Fields, Google & Rajula Vineet Reddy, CERN](https://kccncna20.sched.com/event/ekHJ/building-better-communication-for-kubernetes-contributors-with-marketing-matthew-broberg-red-hat-kaslin-fields-google-rajula-vineet-reddy-cern)  
The KubeCon + CloudNativeCon 2020 schedule has been posted. I would encourage everyone to attend this talk as everyone in the community will likely want to have something written about or given some more exposure at some point in their Kubernetes contributor journey.

[Fixing our broken internet](https://lwn.net/Articles/833625/)  
"In unusually stark terms, Mozilla is trying to rally the troops to take back the internet from the forces of evil—or at least "misinformation, corruption and greed"—that have overtaken it. In a September 30 blog post, the organization behind the Firefox web browser warned that "the internet needs our love". While there is lots to celebrate about the internet, it is increasingly under threat from various types of bad actors, so Mozilla is starting a campaign to try to push back against those threats." Mozilla in trying to [Unfck the internet](https://www.mozilla.org/en-US/firefox/unfck/).

[6 must-read books for aspiring Cloud Architects](https://www.redhat.com/architect/books-cloud-architects)  
"Cloud architecture is a different paradigm. Here are some recommended reads to help you be ready for the new landscape."

## Process

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[GitOps Happy Hour: Demystifying GitOps](https://youtu.be/UvwcVNv61Mo)  
"Join Christian Hernandez, GitOps Extraordinaire, for a journey through how to achieve GitOps in any number of ways. The occasional Red Hatters and special guest will join us too."

[IBM to spin off new company, will focus on $1 trillion cloud 'opportunity'](https://www.wraltechwire.com/2020/10/08/ibm-to-spin-off-new-company-will-focus-on-1-trillion-cloud-opportunity/)  
"'Now is the right time to create two market-leading companies focused on what they do best,' said IBM Chief Executive Arvind Krishna in a statement. 'IBM will focus on its open hybrid cloud platform and AI [artificial intelligence] capabilities. NewCo will have greater agility to design, run and modernize the infrastructure of the world’s most important organizations.'" When I boss called me and asked if I'd heard the news that morning I said no. After he told me, I asked if there was an email announcement? He said, "Dude, it's IBM. Check the internet." To my credit, I was in the process of making coffee. But, that's a very valid point. If Red Hat did this, no one would care. IBM does it and it's a sea change.

[Twilio Set To Acquire Cloud Customer Data Startup Segment For $3.2 Billion](https://www.forbes.com/sites/alexkonrad/2020/10/09/twilio-to-acquire-cloud-startup-segment-for-3-billion/#51d4e38c2020)  
Twilio makes big waves. It also points to the need to have an analytics engine as part of any good platform of services.

[Apple's T2 custom secure boot chip is not only insecure, it cannot be fixed without replacing the silicon](https://www.theregister.com/2020/10/08/apple_t2_security_chip/)  
Throw all those chips out.

[Using a WordPress flaw to leverage zerologon vulnerability and attack companies’ Domain ControllersSecurity Affairs](https://securityaffairs.co/wordpress/109175/hacking/zerologon-dc-hack.html)  
If I had to run WordPress in my infrastructure. It'd be on its own isolated network with no attachment to anything in my production environment. At that point, I might as well pay WordPress to worry about WordPress for me.

[Stop the EARN IT Bill Before It Breaks Encryption](https://act.eff.org/action/stop-the-earn-it-bill-before-it-breaks-encryption-a7904e20-2083-4d5e-88ae-44ee5fef7a5d)  
50% of this newsletter's audience needs to pick up the phone and call their Congresscritters to kill this bill.

## Tools

Two wonderful comics from [Julia Evans](https://twitter.com/@b0rk) this week I'd like to highlight:

* [bash errors](https://wizardzines.com/comics/bash-errors/)
* [bash quotes](https://wizardzines.com/comics/bash-quotes/)

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[Managing cgroups with systemd](https://www.redhat.com/sysadmin/cgroups-part-four)  
"Find out how much easier cgroup management is with systemd in this four-part series finale covering cgroups and resource management."

[Measuring the Memory Overhead of a Postgres Connection](https://blog.anarazel.de/2020/10/07/measuring-the-memory-overhead-of-a-postgres-connection/)  
Everything comes at a cost.

[Continuous Availability and Active-Active Bucket Replication](https://blog.min.io/active-active-replication/)  
"One of the key requirements driving enterprises towards cloud-native object storage platforms is the ability to consume storage in a multi-data center setup. Multiple data centers provide resilient, highly available storage clusters, capable of withstanding the complete failure of one or more of those data centers. Multi-data center support brings private and hybrid cloud infrastructure closer to how the public cloud providers architect their services to achieve high levels of resilience."

[How Alibaba Cloud uses Cilium for High-Performance Cloud-Native Networking](https://cilium.io/blog/2020/10/09/cilium-in-alibaba-cloud/)  
Cilium is making a big push of late to highlight the platforms they support. I would expect to see them on openshift.tv at some point in the near future.

[Memory Safe ‘curl’ for a More Secure Internet](https://www.abetterinternet.org/post/memory-safe-curl/)  
"ISRG is funding Daniel to work on adding support for Hyper as an HTTP back-end for curl. Hyper is a fast and safe HTTP implementation written in Rust."

[Accurics Enables Self-healing Infrastructure with GitHub App](https://www.accurics.com/blog/devops/accurics-for-github/)  
"It provides a library of more than 500 policies aligned with compliance standards such as the CIS benchmark. New commits and pull requests are automatically scanned for policy violations, and when security risks are found they are added to the PR and/or repo as issues. To help your team quickly eliminate them, you can even trigger new PRs with automatically-generated code to fix the issues." Slick.

[How eBPF Turns Linux into a Programmable Kernel](https://thenewstack.io/how-ebpf-turns-linux-into-a-programmable-kernel/)  
We've always been kernel engineers to a certain extent. Tweak a setting here, tune a setting there. But, eBPF thrusts us all deep into kernel guts. Be ready.

[NVIDIA Unveils $59 USD Raspberry Pi Competitor With Jetson Nano 2GB](https://www.phoronix.com/scan.php?page=article&item=nvidia-jetson-2gb&num=1)  
I bought one. I'll let y'all know what I think about it. I'm probably going to try to use it as part of a Kubernetes cluster.

[dheera/magicimport.py](https://github.com/dheera/magicimport.py)  
"The idea of magicimport.py is to allow an arbitrary piece of Python code to fetch its own dependencies and versions at runtime and "just run", no questions asked, without fuss. Behind the hood it uses virtualenv to create a virtual environment and install its dependencies there without messing with your system Python packages."

[storax/kubedoom](https://github.com/storax/kubedoom)  
Kill Kubernetes pods by playing Id's DOOM!

[exelban/stats](https://github.com/exelban/stats)  
macOS system monitor in your menu bar (I've started using this on my main Mac laptop and it's rather handy).

[nb](https://xwmx.github.io/nb/)  
CLI plain-text note-taking, bookmarking, and archiving.

[TimeToogo/tunshell](https://github.com/TimeToogo/tunshell)  
Remote shell into ephemeral environments 🐚 🦀

## DevOps'ish Tweet of the Week

[!["Japanese textbooks: cute, 'programming is fun!' vibe. American textbooks: eldritch horrors, chronicles of riddick cosplay."](https://shortcdn.com/devopsish/187-devopsish-tweet-of-the-week.png)](https://twitter.com/gl4cierblue/status/1313994061745975297)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/187/notes.md) to see what didn't make it to the newsletter.

