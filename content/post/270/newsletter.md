+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-06-05T07:00:00Z
description = ["KubeCon CFPs, DevOps survey, Kubernetes Annual Report, Sandberg steps aside, Lacework asks 20% of staff to step out, other layoffs, gitnoter, and more"]
draft = false
slug = "270"
tags = ["KubeCon", "Detroit", "talk", "Kubernetes", "Argo", "company", "project", "KubeCon", "cloud", "CFPs", "community", "service", "process", "build", "software", "CNCF", "Facebook", "Sandberg", "CNCF landscape", "VMware", "Kubernetes iceberg", "DevOps", "Meta", "open source", "Google", "Contributor Comms", "Microsoft", "Windows", "Netflix", "automation"]
title = "DevOps'ish 270: KubeCon CFPs, DevOps survey, Kubernetes Annual Report, Sandberg steps aside, Lacework asks 20% of staff to step out, other layoffs, gitnoter, and more"
+++

I had a good but busy week. Two big things happened on Friday:

1. Max finished Kindergarten (super proud)
1. I reviewed more KubeCon CFPs for more people submitting them than I have in a LONG time

Three straight hours of non-stop CFP reviewing. Don't take this as a brag. I tend to put incoming requests for help over my work when so many folks ask for reviews of their CFP. That's okay. I appreciate being able to share knowledge and help wherever I can whenever the time is right. I might have been happier building out a GitOps environment for demoing during booth duty at [Open Source Summit](https://events.linuxfoundation.org/open-source-summit-north-america/?source=devopsish) (yes, I'm making an exception for Austin, TX). I will find out which was more fun next week.

It's always interesting to me working with first-time submitters. You're not putting together a business proposal. You're trying to get on stage at a conference with a talk acceptance rate in the low to mid teens. Remember that the conference CFP reviewers have a FAR more demanding job than I do. I try to improve the proposals I see (I don't rewrite them to get accepted magically).

The track chairs have to review scores and build their track to make it the best possible (reviewers sometimes have to defend their scores). It's a laborious and time-consuming process. If your talk isn't selected, you're in the vast majority. Please don't complain and especially don't be rude. That's a surefire way to make sure your talks are never accepted. Trust me. I'll be looking for negative comments toward KubeCon volunteers. Please don't do it. Your *career* will appreciate it.

There is a balance between being overly descriptive and not being descriptive enough in a talk proposal. A wall of text in front of someone who wants to review over 100 CFPs will get glossed over at best. There is a lot of pressure to get as many CFPs reviewed as humanly possible. The review process is cumbersome too. As someone proposing a talk, you'll have a better chance if you can [Hemingway](http://www.hemingwayapp.com/?source=devopsish) yourself into a tighter, cleaner CFP. I always love it when folks push back on my feedback too.

I told one person never to assume the reviewer knows that the project your talk is about is on the CNCF Landscape. There are 1,097 projects on the [CNCF Landscape](https://landscape.cncf.io/?source=devopsish). No one knows them all by heart, and adding more work to a reviewer's plate will reduce your chances of selection. Ultimately, it's really on the submitter if the talk is good enough. There's not much I can do other than positioning your proposal in a better light. If it's a turd of a talk or a glut of submissions about a particular project, your talk has an even higher chance of not being selected. If your talk isn't selected, look at the abstract of the talks on the schedule. Notice anything different? There's a wealth of knowledge lingering in past KubeCon schedules.

Let's do some math. [Observability](https://landscape.cncf.io/card-mode?category=observability-and-analysis&grouping=category?source=devopsish) has 129 projects in the CNCF Landscape. If you're up against 20 submissions about the same tool doing close to the same thing, your chances are now 1 in 20 of being selected. If you're keeping score at home, that is a 5% chance vs. an average of under 15%. That means your proposed talk has to be the best one. This happens more often than you think. You'll have to prove that your talk is the best on stage in [Detroit](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?source=devopsish).

Speaking of Detroit, I had a conversation on Friday (I had a hectic week, and Friday was insanely busy). Someone asked for tips and hints about improving Detroit's image, so folks aren't complaining about going to Detroit for KubeCon. Y'all, Detroit is dope. Does it have major metropolitan area problems? Yes. Like the 26 cities in the US larger than Detroit, we have crime.

But, we also have [the best pizza in the US](https://www.buddyspizza.com/?source=devopsish) and one of the [best
food scenes](https://visitdetroit.com/inside-the-d/detroit-restaurants-guide/?source=devopsish) in the Midwest (probably only surpassed by Chicago). More importantly, my home is here. I could live anywhere, globally, and I chose Detroit over my original home state, North Carolina. Speaking of North Carolina, some of the best barbecue I've ever had is in the Detroit Metro Area.

I got some news if you think we don't know much about automation up here. Folks in Detroit build the robots that make people's cars in the US. We have one of the first [autonomous corridors](https://www.wxyz.com/money/auto-news/new-autonomous-vehicle-corridor-planned-between-detroit-and-ann-arbor?source=devopsish) in the US connecting two cities where public/private research teams can test their new tech (like [in-road charging](https://www.cbsnews.com/news/electreon-detroit-wireless-electric-vehicle-charging/?source=devopsish)). We have an entire section of Michigan (I live in it) called [Automation Alley](https://www.automationalley.com/?source=devopsish).

If you're worried about Detroit, please talk to me. I will make you look forward to the visit, I promise. Downtown Detroit is one of my favorite places on earth. [Say nice things about Detroit](https://www.shinola.com/our-stories/say-nice-things-about-detroit-story-emily-t-gail/).

{{< youtube -lLjEQx0H4I >}}

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### [Take the 2022 Accelerate State of DevOps Survey](https://cloud.google.com/blog/products/devops-sre/take-the-2022-state-of-devops-survey?source=devopsish)

Each year the [DevOps Research and Assessment (DORA)](https://www.devops-research.com/research.html#reports?source=devopsish) team seek input from technical practitioners in every industry to help all of us understand the practices and capabilities the drive software delivery and operations performance. The research and subsequent reporting are anonymous, academically-rigorous, and platform-agnostic. The research investigates technical, process, measurement, and cultural capabilities. Anyone responsible for prioritizing, building, deploying, or operating software services is encouraged to participate in the survey. [Take the survey to help improve your organization!](https://google.qualtrics.com/jfe/form/SV_2aXfK0Zw75lvCl0?source=devopsish)

### [Kubernetes Annual Report 2021](https://www.cncf.io/reports/kubernetes-annual-report-2021/)

> This report documents both quantitative measures of community health (project milestones and snapshot) as well as qualitative measures of the community as reported by community leaders and contributors to the project.
> 
> Authors: The Kubernetes Steering Committee
> Editor: Tim Bannister, @sftim, SIG Docs Tech Lead

## Events

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**SCALE 19x**](http://www.socallinuxexpo.org/?source=devopsish)

JULY 28-31, 2022

SCALE is the largest community-run open-source and free software conference in North America. It is held annually in the greater Los Angeles area. This summer it returns to an in person show at the LAX Hilton.

## People

[Facebook parent Meta COO Sheryl Sandberg is stepping down](https://www.cnbc.com/2022/06/01/facebook-coo-sheryl-sandberg-says-she-is-stepping-down.html?source=devopsish)  
Jessica Bursztynsky and Matt Rosoff, CNBC  
"Sheryl Sandberg is stepping down from her role as Chief Operating Officer at Meta, the company formerly known as Facebook. Sandberg joined Facebook in early 2008 as the No. 2 to Facebook CEO and co-founder Mark Zuckerberg. Javier Olivan, the company's chief growth officer, will take over as COO this fall. Sandberg will continue to serve on Meta's board of directors." [According to the WSJ](https://www.wsj.com/articles/why-sheryl-sandberg-quit-facebook-meta-11654215712?source=devopsish) there might have been a cause behind her stepping down, "One of the world's most powerful executives became increasingly burned out and disconnected from the mega-business she was instrumental in building. That dovetailed with a company investigation into her activities." Regardless, it's probably not going to be one person filling her shoes.

[Cloud security firm Lacework lays ​off 20% of staff](https://www.protocol.com/enterprise/lacework-layoffs-cloud-security-startup)  
Kyle Alspach, Protocol  
There is an economic theme to this week's newsletter. The tech bubble see bursting at the moment is the one of the tech companies that aren't really tech companies. That's not to say they don't have technologist on staff that provide a strategic advantage, nothing could be further from that, Lacework seems to be the exception to the rule making it possible for anyone that hadn't quite gotten their brand market fit or key partnerships solidified fair game for who's next in tech? Here's hoping our collective career choices pay off.

[Tension Inside Google Over a Fired AI Researcher’s Conduct](https://www.wired.com/story/google-brain-ai-researcher-fired-tension/)  
Tom Simonite, WIRED  
"The episode adds to a series of recent internal conflicts at Google that suggest the freewheeling, engineer-centric culture it celebrated as a startup has left the company unprepared for some challenges of being a multinational with more than 100,000 staff."

[Record Labels Want to Know if Piracy Trial Jurors are Hip-Hop Fans](https://torrentfreak.com/record-labels-want-to-know-if-piracy-trial-jurors-are-hip-hop-fans-220531/)  
Ernesto Van der Sar, TorrentFreak  
*Literal record scratch* "I'm sorry what did you just ask me you racist 🤬 🤬🤬🤬 🤬? And yes! [I do support the EFF](https://chrisshort.net/causes#electronic-frontier-foundation), because of 🤬🤬 like this!"

[Ableism And Disability Discrimination in New Surveillance Technologies (PDF)](https://shortcdn.com/file/devopsish/2022_05_23_CDT_Ableism_and_Disability_Discrimination_in_New_Surveillance_Technologies_report_final_r.pdf)  
Center for Democracy & Technology  
Something weird happened when I bookmarked this so I'm sharing the PDF from my own CDN. "How new surveillance technologies in education, policing, health care, and the workplace disproportionately harm disabled people"

[A Quick Intro to Contributor Comms (anyone can contribute)](https://www.youtube.com/watch?v=MCcaAkZWqY4)  
Kaslin Fields and Chris Short, Kubernetes Contributor Comms Team  
"Kaslin Fields and Chris Short sit down to talk about getting started on the Contributor Comms team. We have a unique objective of highlighting the excellent work being done by folks every day in the Kubernetes community. Even better, while coders are more than welcome, we need folks with other skills like writing, social media, video production, automation, and more to contribute."

## Process

[Code execution 0-day in Windows has been under active exploit for 7 weeks](https://arstechnica.com/information-technology/2022/05/code-execution-0day-in-windows-has-been-under-active-exploit-for-7-weeks/)  
Dan Goodin, Ars Technica  
"A critical code execution zero-day in all supported versions of Windows has been under active exploit for seven weeks, giving attackers a reliable means for installing malware without triggering Windows Defender and a roster of other endpoint protection products." That's bad.

[Google has been DDoSing SourceHut for over a year](https://drewdevault.com/2022/05/25/Google-has-been-DDoSing-sourcehut.html)
Drew DeVault  
"Just now, I took a look at the HTTP logs on git.sr.ht. Of the past 100,000 HTTP requests received by git.sr.ht (representing about 2½ hours of logs), 4,774 have been requested by GoModuleProxy — 5% of all traffic. And their requests are not cheap: every one is a complete git clone. They come in bursts, so every few minutes we get a big spike from Go, along with a constant murmur of Go traffic."

[DuckDuckGo's Search Deal Stops Browser From Blocking Microsoft Trackers](https://www.searchenginejournal.com/duckduckgo-microsoft-trackers/452006/)  
Matt G. Southern, Search Engine Journal  
This is the clearest explanation of the whole, "DuckDuckGo giving Microsoft cookies out on their search result pages" (which are, at least in part, pulled from Microsoft). It's a contractual obligation essentially. If you don't want large companies to see your search engine usage, well, there's tools out there to make you harder to track, but if they want you, you're doomed. They can listen through your cell phone (while it's off) to everything going on around you from a satellite tens of thousands of miles in the sky. Meanwhile, back in society, DuckDuckGo is still your best choice balance of bloat and privacy.

[Tech company layoffs and hiring freezes in 2022](https://www.protocol.com/workplace/tech-company-layoffs-2022)  
Nat Rubio Licht and Michelle Ma, Protocol  
"Last week, Y Combinator sent an email to its portfolio founders warning them to '[plan for the worst](https://techcrunch.com/2022/05/19/yc-advises-founders-to-plan-for-the-worst/).'" The thing is, Meta feeling a crunch is society responding to what they've been doing. That's been possible since day one. Salesforce has a wide swath of products covering many sectors (oh and Slack too). They'll for sure have course corrections as the market and demand for products ebb and flow. Netflix spent a ton of money up front to build a service to meet the demands of the biggest streaming service in the country. Then doubled down on the engineering teams. Then Netflix couldn't keep magically adding millions of subscribers quarter after quarter after quarter. The streaming market is over saturated and the folks winning right now seem to be everyone but Netflix. But, continual growth is impossible. The other companies in the article *barely* pass as tech companies. Klarna and PayPal are banks before tech companies. Robinhood is a trading company whose interface happens to be an amazing computer in your hand usually. Carvana is a car company. What I'm trying to say is, I don't think this is end times. I feel this is a course correction. Where investors and founders learn a hard lesson about calling something that isn't actually a tech company a tech company.

[Freeing up of hundreds of millions of IPv4 addresses mooted](https://www.itnews.com.au/news/freeing-up-of-hundreds-of-millions-of-ipv4-addresses-mooted-580689)  
Juha Saarinen, iTnews  
FINALLY! All these wasted IP blocks are just out there. Yes, it sucks if you're using them but this will free up 419 million IPv4 addresses! The greater good matters. IP blocks are already selling at a premium.

[Broadcom plans 'rapid subscription transition' for VMware](https://www.theregister.com/2022/05/27/broadcom_vmware_subscriptions/?source=devopsish)  
Simon Sharwood, The Register  
"Broadcom has signaled its $61 billion acquisition of VMware will involve a 'rapid transition from perpetual licenses to subscriptions.'... 'Whether it's perpetual or subscription, frankly, it's the same,' Tan added. "We are, in a sense, restructuring the contracts from perpetual to subscription." VMware may also experience slower growth in the short term due to the licensing shift." And there you have it, "The move to subscription-based licensing will apparently happen over the course of the next few years." Is this how Broadcom ensures growth in VMware? A licensing change? I hope not. I hope I hear about the positive parts of the article paying off. We'll all wait to hear and see.

[Experts uncovered over 3.6M accessible MySQL servers worldwideSecurity Affairs](https://securityaffairs.co/wordpress/131851/security/3-6-million-mysql-servers-accessible-online.html)  
Pierluigi Paganini, Security Affairs  
"Researchers from Shadow Server scanned the internet for publicly accessible MySQL server instances on port 3306/TCP and uncovered 3.6M installs worldwide responding to their queries." I'm again, not surprised at all.

## Tools

[It's Time to Bring Back the AIM Away Message](https://www.wired.com/story/bring-back-the-aim-away-message/)
Lauren Goode, WIRED  
I do agree with the author, in principle, I should be able to write a sentence or two if I need to convey multiple status updates. "These are not guardrails. These are squishy orange cones that we all plow through, like 15-year-olds in driver's ed. Even the names of these features—Focus, Schedule Send—are phrases born of a work-obsessed culture. Bring back the ennui, the poetry, the pink fonts, the tildes and asterisks."

[The differences between Docker, containerd, CRI-O and runc](https://www.tutorialworks.com/difference-docker-containerd-runc-crio-oci/)  
Tom Donohue, Tutorial Works  
This was very popular this week. The article gives you the context you need to start thinking about what's under the hood of your local Kubernetes cluster.

[Demystifying the Kubernetes Iceberg: Part 3](https://asankov.dev/blog/2022/05/29/demystifying-the-kubernetes-iceberg-part-3/)  
Anton Sankov  
In case you missed parts [one](https://asankov.dev/blog/2022/05/15/demystifying-the-kubernetes-iceberg-part-1/) and [two](https://asankov.dev/blog/2022/05/22/demystifying-the-kubernetes-iceberg-part-2/). Flant's iceberg was essentially the CNCF Landscape on an iceberg. There were TONS of overlapping projects in there that maybe at one point or another you decide on. For CNI, [Cilium](https://cilium.io/) seems to be the front runner. You knowing that took a big chunk of that iceberg out. [Linkerd](https://linkerd.io/) is lighter weight than [Istio](https://istio.io/) which could give you a better bang for your buck (so make sure you test at test at least whatever feels best for you). Also, your cloud vendor probably has a managed service mesh you could use too. If you can compile your code to run on arm64/aarch64, you're really going to see some serious improvements. Go with what works for your teams that have to work on the clusters every day. Not necessarily the cheapest thing over the next four years.

[XMODEM in 2022](https://www.mattkeeter.com/blog/2022-05-31-xmodem/)  
Matt Keeter  
"How did I find myself writing a new implementation of a 45-year old protocol?"

[How to Store an SSH Key on a Yubikey](https://xeiaso.net/blog/yubikey-ssh-key-storage)  
Xe  
"Using a password to encrypt the private key is a viable option, but the UX for that is hot garbage. It's allegedly the future, so surely we MUST have some way to make this all better, right?" There is; since [OpenSSH 8.2](https://www.openssh.com/releasenotes.html#8.2). I haven't done it yet because my workflow hasn't been terrible. But, that'd be way more secure.

[Kubernetes RBAC: Implementation and Best Practices](https://www.containiq.com/post/kubernetes-rbac)  
James Walker, Contain IQ  
"Role-based access control lets you use organizational user roles to restrict access to resources. In this guide, you’ll learn how to apply this in Kubernetes and best practices for doing so." Back to basics, bookmark quality link, y'all.

[git-noter/gitnoter](https://github.com/git-noter/gitnoter)  
An open source, markdown-based, self-hosted note taking webapp

[atsign-foundation/sshnoports](https://github.com/atsign-foundation/sshnoports)  
"ssh no ports provides ssh to a remote Linux device with out that device having any ports open" Shit sounds crazy but, yeah, we're in crazy so it makes sense.

[dragonflydb/dragonfly](https://github.com/dragonflydb/dragonfly)  
A modern replacement for Redis and Memcached

## DevOps'ish Post of the Week

[![I would have thought you already had at least 10,000! For what it's worth you doing the no-tracking, privacy-friendly thing is a big selling point for me tbh Kai (@KaiPMDH) on Twitter)](https://shortcdn.com/file/devopsish/270-devopsish-post-of-the-week.webp)](https://twitter.com/KaiPMDH/status/1531269812596391938)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.

### There's another newsletter these days

If you're not aware, I'm also writing a newsletter for work. [EKS News](https://eks.news/?source=devopish) is a newsletter curated by the Amazon Elastic Kubernetes Service (Amazon EKS) Developer Advocates. It aims to bring the latest and greatest on all things AWS Elastic Kubernetes Service, Kubernetes, and Cloud Native. Keeping up with what's happening so you can stay on top of this evolving space. [Subscribe today](https://eks.news/?source=devopish)!
