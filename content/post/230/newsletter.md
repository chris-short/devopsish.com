+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-08-15T07:00:00Z
description = ["Complex Systems == No Single Root Cause, WFHers juggling two jobs, Service Reliability Math, eBPF Foundation, Dashboards, Tools from Black Hat and more"]
draft = false
slug = "230"
tags = ["systems", "cloud", "single root cause", "Kubernetes", "DevOps", "lightning", "datacenter", "security", "Steam", "cooling", "reset", "power", "containers", "cloud native", "Apple", "code", "Linux", "Red Hat", "ARM", "open source", "John Allspaw", "work from home", "incidents", "AWS", "eBPF Foundation", "dashboards", "nano", "GitOps"]
title = "DevOps'ish 230: Complex Systems == No Single Root Cause, WFHers juggling two jobs, Service Reliability Math, eBPF Foundation, Dashboards, Tools from Black Hat and more"

+++

Another week another bout of bad weather. Systems here in our home have gotten a bit more robust since our multi-day total blackout. I took a meeting this week in a house with no power. The meeting was short, but it demonstrated that if everything goes to hell in a handbasket, my systems are redundant enough to enable me to pass whatever batons when needed. But, lately, it’s felt like a lot.

You can feel the cost of communication when a cacophony of UPSes suddenly fills the house. Luckily power was restored before we went to bed that night. But, what came later was something of a surprise. In 36 hours, [Michigan received almost a quarter of its annual total of lightning stikes](https://www.mlive.com/whitecaps/2021/08/you-wont-believe-how-many-lightning-strikes-occurred-over-michigan-on-wednesday-and-thursday.html) (a lot of them cloud to ground). While this didn’t seem to affect services we consume, I can only imagine the hell it played out for multiple fire responders of all stripes.

One of the worse incidents I was part of was a lightning strike that hit a datacenter’s generator transfer switch. It kicked off a chaotic series of events that caused HVAC systems to go offline. The storm that night was hellacious too. A datacenter can generate enough heat to make network switches act up is a miserable series of events. There was no single root cause. Multiple systems failed or malfunctioned in unplanned or thought of ways. The fact we weren’t up and running once temperatures started to cool down unlocked a new mystery that ultimately led us to restart our core switches because the heat had thrown the ASICs out of whack. But, there was never a single root cause. You could say the lightning strike was the root cause. But, that hit systems outside the datacenter and related to power. Our systems went down because core switching had overheated. Cooling units inside the datacenter reset but didn’t start using refrigerant until they were reset again in a particular order (the cooling system was never supposed to respond the way it did). There’s never a single root cause for a large-scale outage (John Allspaw argues the point further below).

But, there was never a single root cause. You could say the lightning strike was the root cause. But, that hit systems outside the datacenter and related to power. Our systems went down because core switching had overheated. Cooling units inside the datacenter reset but didn’t actually start using refrigerant until they were reset again in a certain order (the cooling system was never supposed to respond the way it did). There’s never a single root cause for a large scale outage (John Allspaw argues the point further below).

Large-scale systems (and some not-so-large ones) are too complex for us to understand completely. We make assumptions past a certain threshold of knowledge. We have to start being more diligent about our assumptions and developing a better understanding of how our systems perform. We need to apply those lessons to reduce wasteful spending, protect our systems, and improve the quality of our services.

## People

[These People Who Work From Home Have a Secret: They Have Two Jobs](https://www.wsj.com/articles/these-people-who-work-from-home-have-a-secret-they-have-two-jobs-11628866529?mod=djemalertNEWS)  
Whoa! I can barely keep the one job... Wait... This is newsletter is technically a second job. DAMMIT!!! But, this is sneakier than I could imagine.

[A Non-Tech Explanation of Containers and Kubernetes](https://www.linode.com/content/non-tech-explanation-of-containers-and-kubernetes/?utm_source=devopsish&utm_medium=newsletter_sponsorship&utm_campaign=newsletter_sponsorship-devopsish-kubernetes&utm_content=&utm_term=)  
Through this simple analogy by 451 Research, get a better understanding of virtualization, containers, and Kubernetes. Learn the differences between these big topics and the role of each in a multicloud future. *SPONSORED*

[Exhaustive study puts China's infamous Great Firewall under the microscope](https://portswigger.net/daily-swig/exhaustive-study-puts-chinas-infamous-great-firewall-under-the-microscope)  
The Great Firewall hasn't been probed like this before. Brilliant work.

[Chinese cyber spies targeted Israel posing as Iranian hackers](https://therecord.media/chinese-cyber-spies-targeted-israel-posing-as-iranian-hackers/)  
This is the stuff that haunts me at night. I have nightmares like this.

[These Common Phrases Are Actually Ableist, So Quit Using Them](https://lifehacker.com/these-common-phrases-are-actually-ableist-so-quit-usin-1847473756)  
I have to deal with a lot of these phrases and ableism in multiple facets of my day-to-day life. If Lifehacker is raining on your parade, you might be in the wrong. The worst is, "But, you look fine." Like that changes the internal injuries of someone.

[Apple keeps shutting down employee-run surveys on pay equity — and labor lawyers say it's illegal](https://www.theverge.com/2021/8/9/22609687/apple-pay-equity-employee-surveys-protected-activity)  
Apple is trying to keep its employees from taking surveys on pay equity. But it's illegal. What makes it worse is that Apple is thumping its chest that it doesn't have a pay inequity problem. They shouldn't with a $2.46 trillion dollar market cap and only ~147,000 employees.

## Process

[xkcd: Every Data Table](https://xkcd.com/2502/)  
\* 2020  
† 2021  
🤣🤣🤣

[Management platform for Infrastructure as Code Automation and Collaboration](https://app.env0.com/login?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dymanic RBAC and quality of life features. [Free Demo](https://app.env0.com/login?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Root cause of failure, root cause of success](https://surfingcomplexity.blog/2021/08/13/root-cause-of-failure-root-cause-of-success/)  
"That's the point of the thought exercise. 🙂 Finding a single 'root cause' of a failure is the same as finding a single 'root cause' of a success — subject to all pitfalls in doing so. 🙂 — John Allspaw"

[How to audit and secure an AWS account](https://acloudguru.com/blog/engineering/how-to-audit-and-secure-an-aws-account)  
"But where do you start when it comes to securing your AWS account?" Here. You can start here.

[Firewalls and middleboxes can be weaponized for gigantic DDoS attacks](https://therecord.media/firewalls-and-middleboxes-can-be-weaponized-for-gigantic-ddos-attacks/)  
"Academics discover novel DDoS attack vector abusing the TCP protocol... The new DDoS technique can be used to launch attacks with amplification factors in the realm of 1000x and more." Well this is bad.

[Service Reliability Math that Every Engineer Should Know](https://matt-rickard.com/service-reliability-math-that-every-engineer-should-know/)  
"For a service to be up 99.99999% of the time, it can only be down at most 3 seconds every year. Unfortunately, achieving that milestone is a herculean task, even for the most experienced site reliability engineering teams."

[Facebook, Google, Isovalent, Microsoft and Netflix Launch eBPF Foundation as Part of the Linux Foundation](https://www.linuxfoundation.org/press-release/facebook-google-isovalent-microsoft-and-netflix-launch-ebpf-foundation-as-part-of-the-linux-foundation/)  
Lightning strikes.

[Notes on the Perfidy of Dashboards](https://charity.wtf/2021/08/09/notes-on-the-perfidy-of-dashboards/)  
Some very salient points about dashboards. Dashboards need to be dynamic, provide context, and be able to show useful, actionable information. "We need more vendors to think about building for queryability, explorability, and the ability to follow a trail of breadcrumbs. Modern systems are going to demand more and more of this approach."

## Tools

[Go, Rust "net" library affected by critical IP address validation vulnerability](https://www.bleepingcomputer.com/news/security/go-rust-net-library-affected-by-critical-ip-address-validation-vulnerability/)  
"[A]pplications relying on net could be vulnerable to indeterminate Server-Side Request Forgery (SSRF) and Remote File Inclusion (RFI) vulnerabilities."

[Manage incidents directly from Slack](https://consuming-macrospore.herokuapp.com/b?y=49q24eh2c4r3ce1gcoo3echi65h62opj74rjcdpic9ij6e3571im4dpocch2o8ji48t24q3keho76ehf5tp6urrkdhsisqbf5svnat3dbtpmutbicdijqrj5etpmopbkehin49j1dlo3mtbkdlfmqpb4d5qmqfb4clr6us3jd5pmg8g=) 🧑‍🚒
Rootly helps automate the tedious manual work like creating incident channels, searching for runbooks, documenting the postmortem timeline, and more. Teams sized 20 to 2000 manage hundreds of incidents daily and save thousands of engineering hours a year within Rootly. Get started in <5min or book a demo to learn more and get Starbucks ☕ on us! *SPONSORED*

[Security tools showcased at Black Hat USA 2021](https://therecord.media/security-tools-showcased-at-black-hat-usa-2021/)  
This list is amazing. It includes [Kubestriker](https://github.com/vchinnipilli/kubestriker), [Kubesploit](https://github.com/cyberark/kubesploit), and many other great tools showcased at Black Hat this year.


[This is why Valve is switching from Debian to Arch for Steam Deck's Linux OS](https://www.pcgamer.com/this-is-why-valve-is-switching-from-debian-to-arch-for-steam-decks-linux-os/)  
It always fascinates me when a project, like Steam Deck, chooses a Linux distro. Choosing Arch allows for Steam to make more iterative updates quickly. Including kernel changes. Which would be a pain to do on Debian without some kind of forking. The thing that gets me is that I fully intend to own a Steam Deck. I also plan to use it as a desktop computer as well. I wonder how consumers will use this device and how Steam will handle supporting it.

[A RedMonk Conversation: Arm64 for the Best Price/Performance on AWS: Why You Should Take The Graviton Challenge](https://redmonk.com/jgovernor/2021/08/09/a-redmonk-conversation-arm64-for-the-best-price-performance-on-aws-why-you-should-take-the-graviton-challenge/)  
Everyone knows I'm a big ARM fan. ARM dominating the mobile phone market is just the beginning. Cheaper but performant, compute that allows for savings to get passed on to the buyer is hard to pass up. If you're smart, you'll commit to being able to run new services on ARM very soon. Then figure out how to get the rest of your codebase ported over the next two years should be a top priority. You'll be light years ahead when some amazing chips start shipping. Note: This has to go better than your switch to IPv6.

[A Container Security Checklist](https://gotopia.tech/articles/container-security-checklist)  
"Published by O'Reilly, Liz Rice's Container Security book provides a security checklist covering the need-to-know when deciding how to protect deployments running on containers. Liz gave us an outline of the checklist in her GOTOpia Europe 2020 presentation and took a deep dive into the specifics of certain likely vulnerabilities that you need to prevent."

[GNU nano is my editor of choice](https://ariadne.space/2021/08/13/gnu-nano-is-my-editor-of-choice/)  
And there is absolutely nothing wrong with loving `nano`. I'm using VScode and the now builtin `vim` bindings. There is a [nano keybindings plugin](https://marketplace.visualstudio.com/items?itemName=rkevin.nano-keybindings) too.

[Bobbycar - A demonstration of Red Hat Open Hybrid Cloud, the platform for your IoT solutions](https://www.youtube.com/watch?v=_AbADA9G9O4)  
This is a really cool demo.

[kubernetes-csi/csi-lib-utils)](https://github.com/kubernetes-csi/csi-lib-utils)  
Common code for Kubernetes CSI sidecar containers (e.g. `external-attacher`, `external-provisioner`, etc.

[bytecodealliance/lucet](https://github.com/bytecodealliance/lucet)  
Lucet, the Sandboxing WebAssembly Compiler.

[andy-5/wslgit](https://github.com/andy-5/wslgit)  
Use Git installed in Bash on Windows/Windows Subsystem for Linux (WSL) from Windows and Visual Studio Code (VSCode)

[Call-for-Code-for-Racial-Justice/Five-Fifths-Voter](https://github.com/Call-for-Code-for-Racial-Justice/Five-Fifths-Voter)  
"Five Fifths Voter is a web application tool designed to enable and empower Black people and others to exercise their right to vote by ensuring their voice is heard"

## DevOps'ish Tweet of the Week

[![Jaana Dogan ヤナ ドガン (@rakyll) on Twitter: "A picture is worth a thousand words. An architectural diagram is worth ten meetings."](https://shortcdn.com/file/devopsish/230-devopsish-tweet-of-the-week.png)](https://twitter.com/rakyll/status/1425249619450023936)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/230/notes/) to see what didn't make it to the newsletter but are still worth your time.
