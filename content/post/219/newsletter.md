+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-05-22T07:00:00Z
description = ["Mobile First Development, Bill Gates, your Wi-Fi are belong to us, irksome IRC, Argo with Okta, kubectl debug, and more"]
draft = false
slug = "219"
tags = ["DevOps", "mobile", "iPad Pro", "Okta", "Argo", "kubectl debug", "development", "open source", "Wi-Fi", "IRC", "Linux", "Kubernetes", "Bill Gates", "OpenShift", "cloud native", "server", "cluster", "CodeReady Workspaces", "irksome", "Microsoft", "observability", "GitOps", "GitHub", "VScode", "Red Hat", "Developers", "runc", "LGBTQ+", "Tailscale"]
title = "DevOps'ish 219: Mobile First Development, Bill Gates, your Wi-Fi are belong to us, irksome IRC, Argo with Okta, kubectl debug, and more"

+++

[Mobile first development](https://twitter.com/ChrisShort/status/1396150939631955972). A simple idea in principle, but the options, while numerous, all suck in some particular way. Yes, I'm a sucker and bought a new iPad Pro. I think that the time is right to make this purchase now, both for family and productivity. With a 5G modem, the device has somewhat unbounded future potential. But, the hardware is hamstrung by iPadOS.

Last night, I was sitting at my desk using the new Magic Keyboard (there's a mousepad). This is an ultra-level netbook with a demon inside it. It is indeed fast. Playing larger maps on Civ6 is enjoyable. The rapid responsiveness of the device is a lot like my Red Hat-issued 16" MacBook Pro (which usually sits on [my desk I wrote about in January](https://chrisshort.net/desk-setup-january-2021/), I do need to provide an updated version soon). This thing could easily handle a lot of my day-to-day work right now. I could, in theory, do my daily job on this iPad Pro. Slack, email, browser, RDP client, and most other software I use to produce and host [OpenShift.TV](https://openshift.tv/) has iPad-friendly versions. When KubeCon NA comes ([the CFP closes today](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/program/cfp/)), I'll have some hard choices to make. I have to decide between bringing an 11" iPad Pro and a mic or a buffet of A/V gear in a Pelican case.

Oddly, things got weird when I thought about writing the newsletter. I found myself [with a few routes](https://twitter.com/ChrisShort/status/1396090916054736897) I could take, but none of them were trivial:

1. MOSH/SSH/TMUX/code-server was one route. I could run that on my OpenShift cluster.
1. I have an OpenShift cluster (fresh too because I blew it up accidentally Saturday morning). I could install a VPN (Wireguard; Tailscale feels too good to be true). Then, install [CodeReady Workspaces](https://developers.redhat.com/products/codeready-workspaces/overview/). There are also [free sandboxes of OpenShift with CodeReady Workspaces](https://red.ht/dev-sandbox).
1. Then two decent options are browser-based and are, at the very least, mobile developer friendly. The first is [GitHub Codespaces](https://github.com/features/codespaces). Next is [github1s](https://www.stefanjudis.com/notes/github1s-open-any-github-repository-in-vs-code-in-your-browser/). Both have some UX bugs to solve that I imagine existing in any VSCode web instance. The new Magic Keyboard for the iPad Pro, the scrolling gesture fails to scroll. You have to scroll with your finger (not a deal-breaker). The two-figure motion to scroll does nothing. Also, the left-most scroll bar is unclickable as well. Which I feel like is a bizarre bug, I see the scroll bar, but it's not clickable. I [filed a bug with GitHub Codespaces as a result](https://github.com/github/feedback/discussions/4010).

But, I feel like "mobile first development" will become a thing very soon. We're close right now, and it very well might already be here for a lot of folks. I'm thinking about handing this to someone out of college, and they're up and running (which the paid product, CodeReady Workspaces, definitely does nail this use case). But that's not usually an option for everyone. The first to make a genuinely mobile development experience will bring in a lot of users. If Apple brings or allows a VSCode-like system to work on iPadOS natively, that would be amazing. But, what I think is more likely to happen is that the M-series iPad Pros get an option that's a lot more like macOS. The bloody thing has 16 GB of RAM! It's a beastly little thing.

## People

[Bill Gates Left Microsoft Board Amid Probe Into Prior Relationship With Staffer](https://www.wsj.com/articles/microsoft-directors-decided-bill-gates-needed-to-leave-board-due-to-prior-relationship-with-staffer-11621205803)  
Oh... What do you know? A rich white guy that had an association with Epstein is a scum bag. Huh... Never saw that coming.

[Cloudflare stops offering to block LGBTQ webpages](https://www.theregister.com/2021/05/21/cloudflare_lgbtq_filtering/)  
I guess you used to be able to "block the gay away." It's appalling that this filter existed for so long.

Take a deep dive into observability at [o11ycon+hnycon](https://o11ycon-hnycon.io/devopsish/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=devopsish&utm_adgroup), a two-day virtual conference on the future of shipping software. Happening June 9-10, this highly interactive event connects you and your peers to explore cutting-edge capabilities and unique outcomes that define observability. You’ll also hear from top Honeycomb customers and observability experts– including Corey Quinn, Chief Cloud Economist of The Duckbill Group, and Nora Jones, CEO of Jeli!

Guess less and know more with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Clarity is an underrated skill](https://tomgamon.com/posts/clarity/)  
"I think clarity of communication is one of the most underrated skills as a developer."

[Linux and open-source communities rise to Biden's cybersecurity challenge](https://www.zdnet.com/google-amp/article/linux-and-open-source-communities-rise-to-bidens-cybersecurity-challenge/)  
"Massive ransomware attacks to the left of us, supply chain attacks to the right of us, but the Linux Foundation is answering the president's call for greater software security."

[To Make Real Progress on D&I, Move Past Vanity Metrics](https://hbr.org/2021/05/to-make-real-progress-on-di-move-past-vanity-metrics)  
"Work with HR and legal to ensure that you’re capturing the right data and allowing people to opt-in appropriately. Use the data you’ve collected to build a single source of truth that is based on facts. Honest, accessible metrics around your diversity progress and remaining gaps are critical to ensuring the work is measurable, targeted, and impactful."

[Coping when the pain gets overwhelming](https://www.youtube.com/watch?v=GNixn3gBmEA)  
"You're at work, going about your day, and wham! pain hits and you're in the middle of a meeting or conversation with your colleagues. Chris and Julia talk about different ways we cope (with the obligatory tangents)."

## Process

[Vulnerabilities in billions of Wi-Fi devices let hackers bypass firewalls](https://arstechnica.com/gadgets/2021/05/farewell-to-firewalls-wi-fi-bugs-open-network-devices-to-remote-hacks/)  
FragAttacks let hackers inject malicious code or commands into encrypted Wi-Fi traffic."

[It took 'over 80 different developers' to review and fix 'mess' made by students who sneaked bad code into Linux](https://www.theregister.com/2021/05/21/linux_5_13_patches/)  
"The majority here is the fallout of the umn.edu re-review of all prior submissions. That resulted in a bunch of reverts along with the 'correct' changes made, such that there is no regression of any of the potential fixes that were made by those individuals. I would like to thank the over 80 different developers who helped with the review and fixes for this mess."

[Guide to Effective Feature Management [O'Reilly]](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)
Testing in production sounds scary, right? What if you could safely ship features faster?
Adopt feature management practices to accelerate release cycles and deploy every 6 hours, instead of every 6 weeks. [Check out the new book](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) from O'Reilly and LaunchDarkly CTO & Cofounder John Kodumal. *SPONSORED*

[CentOS IRC channels moving to irc.libera.chat](https://blog.centos.org/2021/05/centos-irc-channels-moving-to-irc-libera-chat/)  
This whole [freenode thing](https://www.theregister.com/2021/05/19/freenode_staff_resigns/) has been a headache. It's likely going to be the end of IRC for me.

[Symlink-Exchange attack - runc - (CVE-2021-30465)](https://access.redhat.com/security/vulnerabilities/RHSB-2021-004)  
runc is the Open Container Initiative-compliant foundation of a lot of [container runtimes](https://kubernetes.io/docs/setup/production-environment/container-runtimes/), including containerd and cri-o.

## Tools

[The Full Story of the Stunning RSA Hack Can Finally Be Told](https://www.wired.com/story/the-full-story-of-the-stunning-rsa-hack-can-finally-be-told/)  
Once they're inside the wire, it's only a matter of time before they get the crown jewels. The exfiltration process on this one is the thing of novels.

[How to Set Up an SSH Jump Server](https://goteleport.com/blog/ssh-jump-server/https://goteleport.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish). In this blog post we explain how to set up an SSH jump server using two open source projects. *SPONSORED*

[OpenShift sizing and subscription guide for enterprise Kubernetes](https://www.redhat.com/en/resources/openshift-subscription-sizing-guide-detail)  
Always a topic of conversation on air.

[ArgoCD: Okta integration, and user groups](https://itnext.io/argocd-okta-integration-and-user-groups-d6886633e71b)  
I know a lot of shops use Okta. Get that jiving with Argo.

[Welcoming Linux to the 1Password Family](https://blog.1password.com/welcoming-linux-to-the-1password-family/)  
It works so well too. I ditched LastPass for 1Password long ago and it has been an excellent choice. It keeps getting better.

[The Easiest Way to Debug Kubernetes Workloads](https://martinheinz.dev/blog/49)  
`kubectl debug` is quite powerful, indeed.

[Frontier Supercomputer to Get World's Fastest Storage: 75 TB/s, 15 Billion IOPS, 700 PetaBytes](https://www.tomshardware.com/news/olcf-describes-frontier-storage-sub-system)  
Just read the article and fathom what they could do with that.

[Scan your entire website for accessibility issues with a few simple clicks](https://developer.ibm.com/blogs/accessibility-checker-update/)  
We all can do better when it comes to a11y. This tool helps with that.

[HTTPX](https://www.python-httpx.org/)  
"A next-generation HTTP client for Python."

[loft-sh/vcluster](https://github.com/loft-sh/vcluster)  
"vcluster - Create fully functional virtual Kubernetes clusters - Each vcluster runs inside a namespace of the underlying k8s cluster. It's cheaper than creating separate full-blown clusters and it offers better multi-tenancy and isolation than regular namespaces."

[chris-marsh/pureline](https://github.com/chris-marsh/pureline)  
A Pure Bash Powerline PS1 Command Prompt

---

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/219/notes/) to see what didn't make it to the newsletter but are still worth your time.
