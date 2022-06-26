+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-11-22T07:00:00Z
description = "KubeCon, need to improve all virtual events, inclusive leaders, GitOps WG, DKIM, cloud native acquisitions, youtube-dl is back, big problems with Big Sur, and more"
draft = false
slug = "193"
tags = ["virtual events", "complexity", "cloud", "security", "cloud native", "open source", "DevOps", "Apple", "community", "time", "platform", "IBM", "Kubernetes", "attend", "reason", "KubeCon", "IoT", "CNCF", "awk", "conference", "news", "GitHub", "Microsoft", "developers", "employers", "teach", "workloads", "leaders", "internet", "Twitter", "fleets", "friction", "postgresql", "Big Sur", "Fedora", "ARM", "Crunchy Data", "WSL", "attendees", "hallway track", "Red Hat", "culture", "cloud native ecosystem", "Intrado", "inclusive behavior", "GitOps", "Amazon", "container", "eBook", "hybrid cloud", "Operators", "Linux", "network", "IPO", "Xi Jinping", "Jack Ma", "Instana", "Google", "youtube-dl", "YouTube", "EFF", "OpenTelemetry", "observability", "YAML", "Mac", "GNU", "FrontPage", "Windows", "Zoom", "Slack", "Rambly", "Ian Coldwater", "Cloud Native Security White Paper"]
title = "DevOps'ish 193"

+++

Saturday morning, I awoke at 5 AM to pain and an awful headache. I know this headache well; it was a headache from looking at a computer screen too much (after 25 years in the industry, I rarely get these). It was the headache of sitting down before 8:30 AM on Friday, the next time you look up it's almost 2 PM, and you've crossed one thing off your list. Friday was the last day of KubeCon. I thought I was actually going to be able to participate, but life had different plans. Saturday morning, I realized that the idea of an in real life (IRL) event being "lift and shift" into a virtual platform is something I no longer want to signup to attend. A simple statement like, "[KubeCon was my last virtual event. We need a better way.](https://twitter.com/ChrisShort/status/1330121850362470400)" was needed. Please note, I'm still going to speak at any event I'm invited to (and can manage with schedule and everything). But, I'm no longer going to be part of a vast statistic of folks that don't show after registering to attend an event. This is by no means a knock on KubeCon. They had a lot of things that made a conference good.

But, I don't know how Intrado survives after that fecal performance. They must have some iron clad contracts and good lawyers because I expect way more than two 8s of uptime from a video platform. CNCF should be getting a healthy refund on whatever they paid. The errors that occurred on the platform did the content an incredible injustice. Instead of watching and learning, audiences were checking internet connections and asking folks if they lost the talk too. The one keynote I did get to see most of was marred by multiple periods of no output, but the video still jumped ahead as if nothing was wrong. I already know CNCF is never using Intrado again. I hope I never have to see that platform again. But, even then, there are many decent event platforms, but none of them are great for industry events. They all have some form of user friction that limits or sometimes blocks progress with the conference experience.

We need to give virtual events more thought. No one in their right mind will go to a physical event until late next year at the absolute earliest. Even that is somewhere between a wild ass and educated guess. We cannot take the same thing we'd do if we were all together, merely record it, and share it at a specific time. This leaves a gaping hole in people's psyche as we're removing the social aspect of sitting in a room full of like-minded peers. Someone is discussing a topic that folks in the room have varying degrees of understanding of the subject. Lift and shift virtual events are psychologically harmful and are actually more work than an in-person event. Often, the content has to be recorded weeks in advance for some reason.

Also, employers just flat out don't respect virtual events. Suppose I were in Boston like we were supposed to be. My team would never have reached out to me unless something was broken or going wrong. When you're traveling, you have a legitimate reason to focus on the thing your company is spending thousands of dollars (potentially) for you to attend. Event maintainers must realize by now that the low attendance rates are a systemic problem with virtual events themselves. We've reduced the sign up and logistics friction by an order of magnitude. But, people have to weigh how they use their time; if you're not providing attendees clear value with a low level of friction, there will be high attrition rates. The right way to approach this is to show the attendees AND the employers what the value add is. Employers must weigh the benefit their employees will get against their time away from the office, just like always. Employers need to respect that the organization's folks are at a conference this week to learn and grow.

We need to toss out the idea of taking an IRL event and making it virtual. That kind of lift and shift doesn't work. The numbers show that. The industry lauds events when 25% of people that register actually attend. That's not a problem??? No one is thinking about how to fix that? Cloud migrations have taught us that lift, shift, and optimize is a viable transition between on-premises and cloud environments. This goes back to my argument that there's a lot that DevOps can teach marketing and marketing can teach DevOps a lot too. What's the fix here? Let's look at our constraints first:

1. Time is valuable, scarce, and people might not be able to dedicate three to five days at a virtual conference. As a matter of fact, it appears that virtual events only add to folks' (especially speakers) workloads and do nothing to reduce it.
2. Some orgs are fighting for their existence right now. I've already mentioned having to show the org leaders and attendees alike the value in attending whatever event you're putting together.
3. People aren't able to gather together physically. For KubeCon, Kubernetes community members stepped up and created an effective hallway track with Zoom, Slack, and [Rambly](https://rambly.app/). That worked! We should look at this example and see what else we can do to improve on it. Fast iterations are key (that thing didn't work on day 1, try something different on day 2).
4. **Time Zones**: You're never going to solve this problem, but you can organize your schedule to optimize for good content being available at peak times for major regions.

In my opinion, less is more here. Suppose you did one hour a day with a talk and hallway track. That is way more effective than four days of asking for the impossible. Yes, that's 261 hours of content to figure out but, you've got all year to do it. Note: I've personally produced more than 300 hours of live streamed content since May inside ONE business unit at Red Hat. This is more than possible; [I'm doing it](https://openshift.tv). I look at live streaming numbers and metrics all the time as part of my day job these days. I can definitively tell you that content matters most ([Content is King (2003)](https://chrisshort.net/content-is-king/) still), audio is second, and video is third.

I also know that you have to keep things very easy for presenters that are varying degrees of nervous to chomping at the bit. I know I did not submit a talk to either of this year's KubeCons because of the platform in use and the stress that it puts on speakers. Event organizers need to see themselves as complexity managers. Moving complexity to sit with the event owners is vital. It should never be dictated by the platform that's in use.

We need to take the virtual event and flip it on its head. Shake what's good out and experiment with literally everything else along the way (including during events). But, there are other things we should focus on too. Like events having REAL breaks in them. The actual accessibility of them. Accessibility in web design and in the Americans with Disabilities Act (which should be considered the bare minimum) sense. I can't sit, stand, walk, run, or anything for that matter for more than about an hour without having to move or adjust or something. I have a standing desk for a reason. That same desk is on wheels for a reason too. I have to put a lot of thought about breaks, moving around to keep me sane, healthy, and such throughout my normal day to day life. If an event takes that away from me, it's not going to end well. I'd encourage you to [read the whole thread](https://twitter.com/ChrisShort/status/1330121850362470400) and follow on commentary so that you can see some of the ideas and comments from folks. It's a worthwhile adventure.

{{< tweet 1330131626421067776 >}}
That's a step in the right direction, POP!

{{< tweet 1330135904200126465 >}}
A very good question, Kevin.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/)

## People

Want to see your ad in DevOps'ish? Check out the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. *SPONSORED*

[Cloud Native Computing Foundation Announces 2020 Community Awards Winners](https://www.cncf.io/announcements/2020/11/20/cloud-native-computing-foundation-announces-2020-community-awards-winners/)  
Huge congrats to Ian Coldwater, your contributions to our community have been more than code. You've significantly contributed to the culture of the Kubernetes community. We are very lucky to have you. I don't want to spoil all the announcements so I won't list everyone. But, know that I greatly appreciate your contributions to the cloud native ecosystem.

[What Inclusive Leaders Sound Like](https://hbr.org/2020/11/what-inclusive-leaders-sounds-like)  
"Leaders across virtually every industry are pledging to be more inclusive; but if their actions and behaviors don’t support those values, the progress stops there. In their recent study, the authors applied a combination of computational linguistics, vocal mapping, and facial micro-expression analysis to determine what truly makes a leader inclusive in the eyes of an audience. Here they provide three behaviors that can be learned, practiced, and mastered."

[IBM Apologizes For Firing Computer Pioneer For Being Transgender...52 Years Later](https://www.forbes.com/sites/jeremyalicandri/2020/11/18/ibm-apologizes-for-firing-computer-pioneer/?sh=303da50f67d5)  
A long overdue apology to Lynn Conway.

[Twitter users say fleets are ripe for harassment](https://www.engadget.com/twitter-fleets-harassment-013757824.html)  
I'm a Twitter beta tester and fleets have not come to that side of the Twitter app spectrum. This leads me to believe, given its ripeness for abuse, that fleets are an experiment that was not thought out well.

[Firing Christopher Krebs Crosses a Line](https://www.wired.com/story/trump-fires-christopher-krebs-cisa/)  
The US is about to enter a hell status that will be hard to undo. This makes the already unsteady security footing the US had even more fragile.

[Apple lobbies against Uighur forced labor bill](https://www.washingtonpost.com/technology/2020/11/20/apple-uighur/)  
Okay, subscribers at Apple, time to start doing something about this.

[Announcing the GitOps Working Group](https://www.weave.works/blog/announcing-gitops-working-group)  
"Today Amazon, Codefresh, GitHub, Microsoft, and Weaveworks are announcing the creation of the GitOps Working Group. This will be an open CNCF community project created inside the CNCF fluxcd GitHub organization as the initial venue for collaboration and open governance."

## Process

[Download today: container security ebook - going beyond image scanning](https://security.stackrox.com/container-security-going-beyond-image-scanning.html?Source=DevOpsish&LSource=DevOpsish)  
Vulnerability scanning is often the first step to securing containers and Kubernetes, but it’s insufficient by itself. [Download this eBook](https://security.stackrox.com/container-security-going-beyond-image-scanning.html?Source=DevOpsish&LSource=DevOpsish), from StackRox, to learn about the security checks, controls, and best practices DevOps should consider to secure container images and CI build pipeline, Kubernetes deployments, running workloads, and the underlying Kubernetes infrastructure. *SPONSORED*

[Announcing the Cloud Native Security White Paper](https://www.cncf.io/blog/2020/11/18/announcing-the-cloud-native-security-white-paper/)  
“Cloud native security is a multi-objective and multi-constrained problem space spanning many areas of expertise and practice. Developers, operators, and security teams must collaborate to continue to move the field and industry forward. As with any technical innovation, it is the people, their passion, and the journey that genuinely make the community and cloud native security possible, and a solid understanding of the concepts provides a basis for this,” said Emily Fox of SIG Security. Big shoutout to SIG Security for this. Thank you, Emily, and other contributors for helping us step up our security postures.

[Open Invention Network Linux patent protection group turns 15](https://www.zdnet.com/article/open-invention-network-linux-patent-protection-group-turns-15/)  
OIN is a critical entity in our industry. "For fifteen years, the Open Invention Network has been protecting Linux and open-source software developers and companies from open-source's enemies and patent trolls. And, they're not about to stop anytime soon."

[Jack Ma vs. the Party: Inside the collapse of the world's biggest IPO](https://asia.nikkei.com/Spotlight/The-Big-Story/Jack-Ma-vs.-the-Party-Inside-the-collapse-of-the-world-s-biggest-IPO)  
Things not do before your mega IPO: Piss off the regulators. Namely your country's Communist leader. But, how much harm did Xi Jinping do to the future of China's economy by drawing this line in the sand?

[IBM to Acquire Instana as Company Continues to Advance its Hybrid Cloud and AI Strategy](https://newsroom.ibm.com/2020-11-18-IBM-to-Acquire-Instana-as-Company-Continues-to-Advance-its-Hybrid-Cloud-and-AI-Strategy)  
First thought is, "Oh cool!" But, then I realized there's a lot of IBM partners in the monitoring space that might be worried now. I'm not sure what the future will hold but, I'd think IBM would continue to maintain those partnerships to give its clients more choice and thus happiness. Also, that thinking vibes with the new IBM culture. Regardless, I am going to start tinkering with Instana a little.

[Ok Google: please publish your DKIM secret keys](https://blog.cryptographyengineering.com/2020/11/16/ok-google-please-publish-your-dkim-secret-keys/)  
"This new non-repudiation feature was not part of DKIM’s design goals. The designers didn’t intend it, nobody discussed whether it was a good idea, and it seems to have largely taken them by surprise. Worse, this surprise feature has some serious implications: it makes us all more vulnerable to extortion and blackmail."

[Cisco Buys Another Kubernetes Startup Banzai Cloud](https://www.sdxcentral.com/articles/news/cisco-buys-another-kubernetes-startup-banzai-cloud/2020/11/)  
At some point, the cloud native ecosystem will start to consolidate around the best ideas and solutions, it looks like that some sort of consolidation might be happening.

[Introducing “How to Fix the Internet,” a New Podcast from EFF](https://www.eff.org/deeplinks/2020/11/introducing-how-fix-internet-new-podcast-eff)  
"Hosted by EFF’s Executive Director Cindy Cohn and our Director of Strategy Danny O’Brien, How to Fix the Internet digs into the gritty technical details and the case law surrounding these digital rights topics, while charting a course toward how we can better defend the rights of users." Note: I contribute to the EFF.

## Tools

🎺  Looking to up your hands-on skills at KubeCon? We are premiering our [OpenTelemetry Starter Kit at the Honeycomb booth](https://info.honeycomb.io/honeycomb-and-kubecon). Instrument a sample app or your own production data. There are prize-drawings for completed steps, but the real prize is launching with OTel and getting valuable insights right away.

OpenTelemetry + observability = path to production excellence. Get the observability you deserve from [Honeycomb.io](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Managing 2.5 Million Lines of YAML](https://www.awsgeek.com/KubeCon-Virtual-2020/Managing-2-5-Million-Lines-of-YAML/)  
For all you YAML wranglers out there.

[GitHub Reinstates Youtube-DL and Puts $1M in Takedown Defense Fund](https://torrentfreak.com/github-reinstates-youtube-dl-and-puts-1m-in-takedown-defense-fund-201116/)  
GitHub rights a wrong. "GitHub has reinstated the youtube-dl repository after it concluded that the code doesn't violate the DMCA's anti-circumvention provisions. The company believes that developers should have the freedom to tinker, whether the RIAA likes it or not, and has placed $1 million into a takedown defense fund."

[Apple apps on Big Sur bypass firewalls and VPNs - this is terrible](https://thenextweb.com/plugged/2020/11/16/apple-apps-on-big-sur-bypass-firewalls-vpns-analysis-macos/)  
"What Wardle found is that the Mac App Store on the latest macOS bypasses any firewall. For all intents and purposes, its traffic is invisible to firewalls. What’s happening is that Apple apps on Big Sur are beginning to operate outside the user’s control. Which is terrible news." This is a big problem and I've completely frozen any and all Bir Sur upgrades in the Short household.

[PostgreSQL Benchmarks: Apple ARM M1 MacBook Pro 2020](https://info.crunchydata.com/blog/postgresql-benchmarks-apple-arm-m1-macbook-pro-2020)  
I love Crunchy and their desire to make PostgreSQL the best it can be. "This week Apple started delivering Macs using their own Apple Silicon chips, starting with a Mac SOC named the M1. M1 uses the ARM instruction set and claims some amazing acceleration for media workloads. I wanted to know how it would do running PostgreSQL, an app that's been running on various ARM systems for years. The results are great!"

[Intel’s New NUC Laptop Kit: Whitebook Tiger Lake For All](https://www.anandtech.com/show/16262/intels-new-nuc-laptop-kit-whitebook-tiger-lake-for-all)  
As solid as my 8th Gen NUCs are, I cannot wait for laptops under this umbrella. But, to be honest, my next compute purchase could be a very expensive desktop.

[The state of the AWK](https://lwn.net/Articles/820829/)  
"The recent release of GNU Awk 5.1 seems like a good reason to survey the AWK landscape, see what GNU Awk has been up to, and look at where AWK is being used these days."

[FrontPage: The Good, The Bad, and The Ugly](https://invisibleup.com//articles/33/)  
No bull. FrontPage Express, which came on the same CD-ROM as Internet Explorer 4, taught me how to build web sites. That coupled with knowing how to build a PC and being a Windows SysAdmin got me a job. FrontPage's impact is unmistakable. But then things went all Microsoft in the '90s cattywampus.

[Achieving 100Gbps intrusion prevention on a single server](https://blog.acolyer.org/2020/11/16/pigasus/)  
Introducing Pigasus...

[Using Fedora 33 with Microsoft's WSL2](https://fedoramagazine.org/wsl-fedora-33/)  
There is a very sticky indemnification requirement Microsoft imposes on WSL distros that Fedora can likely never meet. This guide is super helpful and will teach you some things about WSL along the way to having Fedora on your Windows box.

[How to Clean JSON Data at the Command Line](https://www.ezzeddinabdullah.com/posts/how-to-clean-json-data-at-the-command-line)  
A deep dive into using `jq` for all the things

[charmbracelet/glow](https://github.com/charmbracelet/glow)  
Render markdown on the CLI, with pizzazz! 💅🏻

[naggie/dsnet](https://github.com/naggie/dsnet)  
Simple command to manage a centralised wireguard VPN. Think wg-quick but quicker.

[koct9i/ioping](https://github.com/koct9i/ioping)  
simple disk I/0 latency measuring tool

[TwinProduction/gatus](https://github.com/TwinProduction/gatus)
Gatus - Automated service health dashboard

## DevOps'ish Tweet of the Week

[![DevOps'ish 193 Tweet of the Week](https://shortcdn.com/file/devopsish/193-devopsish-tweet-of-the-week.jpg)](https://twitter.com/dims/status/1329400522890219520)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/193/notes/) to see what didn't make it to the newsletter.
