+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-05-22T07:00:00Z
description = ["KubeCon EU 2022, GitOpsCon EU 2022, China locks down Gitee, 380K publicly accessible K8s API Servers, Observability Engineering (free eBook), and more"]
draft = false
slug = "268"
tags = ["Kubernetes", "KubeCon", "KubeCon EU 2022", "Argo", "GitOps", "GitOpsCon", "GitOpsCon EU 2022", "CNCF", "COVID", "COVID-19", "open source", "Gitee", "China", "Kubernetes API server", "open API servers", "API server", "security", "observability", "EU", "career", "keynote", "friends", "Van Jones", "mask mandate", "environment", "videos", "monitoring", "Microsoft", "community", "Flux", "Detroit", "Observability Engineering"]
title = "DevOps'ish 268: KubeCon EU 2022, GitOpsCon EU 2022, China locks down Gitee, 380K publicly accessible K8s API Servers, Observability Engineering (free eBook), and more"
+++

This past week was KubeCon EU 2022. I attended only part of it (more on that later). The Kubernetes Contributor Summit looked like it went off okay. I will admit I showed up quite late due to jet lag. But, I was able to sit down with Kaslin and schedule the rest of the tweets for KubeCon EU 2022 as part of our duties for the [Kubernetes Contributor Comms](https://github.com/kubernetes/community/tree/master/communication/marketing-team) team (please follow [K8sContributors on Twitter](https://twitter.com/k8scontributors)). I was also able to say hello to many friends I had not seen in ages. Including my good friend, Vincent Batts. He seemed to want me to know that there is a reason to celebrate (and often is in certain cultures) when someone is taken from us so soon.

The day prior, I had quietly cried myself to sleep on the plane after scrolling past a movie titled "Lucy," much like Kendrick Lamar, [I grieve different](https://music.apple.com/us/album/united-in-grief/1623854804?i=1623854815). It reminded me of my studies of Buddhism and Hinduism I learned in the cult my mother was in (surprise; I [grew up in a cult for quite a few years](https://chrisshort.net/foundation-for-purposeful-living/)). I was at peace, I thought, but Vincent drove that point home.

GitOpsCon was nothing short of a fantastic event ([videos available here](https://www.youtube.com/playlist?list=PLj6h78yzYM2PTHsP7RhbRYBT_TDJz5x3M)). I helped organize it, so I'm biased, but problems got solved quickly if we had them. We did an outstanding job, from last-minute changes due to travel issues to moving folks between two tracks on two different floors. I ran track 2 of GitOpsCon, so I was in the Joaquín Rodrigo Room most of the day on Tuesday. The room was jam-packed and full of people for most of the talks. We had people sitting along the walls and standing out into the hallway at one point. I mentioned two things to CNCF staff about the event:

1. The A/V team was terrific. Rolling with the punches, finding videos sent in by speakers, and managing slight course corrections in our schedule as the day went on.
2. We're going to need more room for GitOpsCon at [KubeCon NA 2022 here in Detroit](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/).

Things went downhill after Tuesday. Let me preface this by saying I'm at a higher risk of catching COVID than the average attendee (disabilities suck). I ended up coming home from KubeCon three days earlier than planned. Combined with travel, the time change, hosting GitOpsCon, and the discipline and rigor needed to maintain my promise to my family, "I'm coming home in a week." I got shoved beyond my limits. I was under a lot of stress managing all that already. Then word came out [that 5 to 11-year-olds should get a COVID vaccine booster](https://www.cdc.gov/vaccines/covid-19/planning/children.html) (this increased Max's risk, in my mind). When friends started catching COVID, the riskier situation was staying in Spain and attending KubeCon than flying home.

What you're about to read could end up in me being sanctioned by the CNCF. But, I would rather you all know _my truth_ than get in line like a good little Ambassador. There was a time when I could write freely about the CNCF and they'd take my views into consideration as feedback. I'm not sure that's still the case.

I intentionally did not go to the keynotes on Wednesday to conserve resources and to help mitigate some of the perceived risks knowing I could watch/listen online while getting ready for the day. One keynote, in particular, felt more like [tone policing](https://en.wikipedia.org/wiki/Tone_policing) than actually helping the community. I am pretty frustrated with the CNCF's lack of ownership of the problem they created after their masking flip-flop _past_ their self-imposed 11th hour (that fact is one they've routinely brushed off every time I've mentioned it). But, intention or not, it sent a message and set a precedent of bending the rules and getting away with it (which I know was not the intention, but that's the environment we're in these days, sadly).

Knowing what I know (which is way more than the average attendee or even most CNCF staff), the Van Jones keynote felt like a dressing down of the community for reacting to CNCF's self-inflicted problems. Some folks responded in a despicable way (death and rape threats will NEVER be okay). Others responded with the intent of forcing change (myself included). I'm glad we did it too. I do not doubt the person CNCF is now trying to turn into a pariah ended up likely saving lives in Valencia. I'm not sure if the CNCF thoroughly thought through the Van Jones keynote and how it would be perceived. Regardless, the optics looked terrible and made Mr. Jones' remarks seem not how they were intended, especially for those with the full context (which appears to be VERY few).

Using a person I served under President Obama with, Van Jones, to talk about something that Mr. Jones didn't have a complete picture of felt VERY self-serving. This is a shared belief amongst several current and former CNCF Ambassadors, not only me. By the way, Van Jones' going virtual rate is $50-60K. That money could have been spent in much better ways, in my opinion, like more signage around the **massive** venue, a bigger second room for GitOpsCon, or towards any project's security audit, for example.

Regardless, this one keynote ratcheted up my anxiety levels even more. Why is this impacting me so hard? Well, I care deeply about a lot of things. The Kubernetes community might be one of the things I care about most. I see massive fissures forming, and that's troubling. But, I have some hope for the future, thanks to the TOC being receptive [to this idea](https://lists.cncf.io/g/cncf-toc/message/6983). But, the moment COVID cases started popping up at KubeCon, given the lightly enforced mask mandate, the conference became an event that forced me to reconsider my participation.

KubeCon had tripped pain and risk management thresholds by Wednesday afternoon, causing anxiety issues to surface. Wednesday afternoon, I no longer felt like myself and was nearing what could have been a dangerous panic attack (given new health issues after KubeCon L.A.). The stress of sitting in my room mentally preparing myself for the next day became an exercise in futility. I asked my boss if coming home on Friday was an option. Then I thought to myself, "You're going to push yourself even harder to get through another day?" I only had one thing I **had** to do after the two Day 0s. Thank you to my friend and teammate, [Justin Garrison](https://twitter.com/rothgar), for picking up my 30 minutes of booth duty on Thursday.

As I was flying home on Thursday, I finally had time to process things. A lot of things went wrong. My packing checklist was not thorough enough. I didn't have enough redundancies and mental checkpoints in place. I am out of practice traveling, and COVID is still a significant risk factor in any travel situation. [The pandemic is not over](https://khn.org/morning-breakout/its-not-over-fauci-clarifies-that-pandemic-is-in-transition-but-not-done/). I felt more comfortable in L.A. than in Spain because there was a firm mask mandate throughout the event. It was without question. If the mask mandate had been followed through (with no flip-flop), this could have been a different KubeCon for me. But, be it the location, the flip-flop, or apathy, masking mandates were not adequately enforced (even on the showcase floor). The risk was so significant, in my mind, that I wore my mask all the way home until I tested negative for COVID in an empty house (Julie and Max were at baseball). The refrain playing in my mind was whether or not this would be a super spreader event. That stopped when I got on the airplane in Amsterdam and knew very little stood in my way of getting home. Anxiety is an odd beast.

I will use this opportunity to turn my postmortem into a talk I'll submit to KubeCon NA 2022 here in Detroit (assuming I'm not banned for sharing my opinion). There were some things I could have done much better, and there were a lot of lessons learned along the way. One lesson I learned at KubeCon NA 2019 in San Diego was to take Wednesday off from the conference to rest and recuperate. I completely forgot that idea this KubeCon. Obviously, I need to write things down. Keep your eyes peeled to [ChrisShort.net](https://chrisshort.net/) for that postmortem in the coming days.

## Free Copy of Honeycomb's O'Reilly Book: Observability Engineering

Looking to make the switch from monitoring to observability? Download your free copy of Honeycomb's [*O'Reilly book: Observability Engineering*](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) to help you get started. Debrief the chapters with the authors themselves during our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112).

## Events

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Gitee, China's answer to GitHub, to review all code by temporarily closing open-source projects to the public](https://www.scmp.com/tech/big-tech/article/3178323/gitee-chinas-answer-github-review-all-code-temporarily-closing-open)  
Coco Feng, South China Morning Post  
"China's largest open-source code platform will temporarily close public repositories to review their contents before opening them up again. The policy change, for which no reason was given, comes as Beijing tightens its grip on internet content." Truly disturbing for open source, in general.

[Satya Nadella details Microsoft plan for 'significant additional investment' in employee compensation](https://www.geekwire.com/2022/satya-nadella-details-microsoft-plan-for-significant-additional-investment-in-employee-compensation/)  
Todd Bishop, GeekWire  
"The move, detailed by Microsoft CEO Satya Nadella in an email to employees Monday morning, represents an attempt to keep its compensation competitive in a tough market for tech talent, and a broader environment of inflation." I hope my friends at Microsoft get **PAID**.

[You are responsible for your career. No one else is. – ](https://letterstoanewdeveloper.com/2022/05/16/you-are-responsible-for-your-career-no-one-else-is/)  
Rowell Belen, Letters To A New Developer  
"The organization doesn’t empower you. You empower yourself. The organization doesn’t invest in you. You invest in yourself. The organization doesn’t foster your career growth. You foster your own career growth. The organization has its priorities, and they most likely don’t revolve around you or your career. That’s not a bad thing. It just is what it is." A few times in my career I took my eye off the ball. I could have gotten to where I'm at faster had I focused on working where I wanted to work as opposed to finding out the hard way the places I didn't want to work.

[My journey back to Fedora Workstation](https://rubenerd.com/my-journey-back-to-fedora-workstation/)  
Ruben Schade  
"After distro hopping more times than I care to admit, I tried Fedora again after a few friends and people I trust reported positive experiences with Workstation and the immutable Silverblue. It just worked again, save for some Nvidia adventures which I don't fault Linux distro maintainers for. I even did an update from 35 to 36, and I haven't had a system upgrade outside the BSD ecosystem go so smoothly."

[Apple Delays and Modifies Its Return to Office Plans](https://www.nytimes.com/2022/05/17/technology/apple-delays-return-to-office.html)  
Tripp Mickle, The New York Times  
"The news was welcomed by an employee group worried about growing coronavirus rates." I bet!!!

## Process

[Over 380 000 open Kubernetes API servers](https://www.shadowserver.org/news/over-380-000-open-kubernetes-api-servers/)  
The Shadowserver Foundation  
"We find over 380,000 Kubernetes API daily that allow for some form of access, out of over 450,000 that we are able to identify. Data on these is shared daily in our [Accessible Kubernetes API Server Report](https://www.shadowserver.org/what-we-do/network-reporting/accessible-kubernetes-api-server-report/)." This is really, really bad y'all. "[The Kubernetes API server](https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/) validates and configures data for the api objects which include pods, services, replicationcontrollers, and others." You should be scanning your IP blocks for things like this. Your API server SHOULD NOT be publicly accessible. If you have a legitimate, non-infosec reason for doing so, I'm all ears and promise complete anonymity.

[GitOpsCon EU 2022 YouTube Playlist](https://youtube.com/playlist?list=PLj6h78yzYM2PTHsP7RhbRYBT_TDJz5x3M)  
[GitOpsCon EU 2022 Speakers and Organizers](https://gitopsconeu22.sched.com/)  
All 27 GitOpsCon EU 2022 videos are ready for your immediate consumption. Here's how to [get involved in the OpenGitOps project](https://opengitops.dev/get-involved/) to help us form patterns and practices that work for various industries and environments.

[Lucas Käldström and Chris Short Talk Kubernetes, Physics, and more](https://youtu.be/0rOvC8IhIEk)  
[Lucas Käldström](https://twitter.com/kubernetesonarm) and [Chris Short](https://twitter.com/ChrisShort)  
Lucas Käldström has a brilliant thesis out titled, "Encoding human-like operational knowledge using declarative Kubernetes operator patterns." We sat down to talk about how, "Kubernetes operators form a novel programming model, allowing a shift from humans managing servers to servers managing servers, analogously to the Industrial Revolution."

[MITRE Creates Framework for Supply Chain Security](https://www.darkreading.com/application-security/mitre-creates-framework-for-supply-chain-security)  
Kelly Jackson Higgins, Dark Reading  
"MITRE's so-called System of Trust (SoT) prototype framework is, in essence, a standard methodology for evaluating suppliers, supplies, and service providers. It can be used not just by cybersecurity teams but across an organization for assessing a supplier or product."

[Apple patches dozens of security flaws with iOS 15.5, over 50 fixes for macOS 12.4](https://9to5mac.com/2022/05/16/apple-patches-27-security-flaws-ios-15-5/)  
Michael Potuck, 9to5Mac  
I never like having to update devices on the road. But, this made me do it anyway.

## Tools

[Tetragon - eBPF-based Security Observability & Runtime Enforcement](https://isovalent.com/blog/post/2022-05-16-tetragon)  
[Isovalent](https://isovalent.com/)  
"Tetragon is a powerful eBPF-based security observability and runtime enforcement platform that has been part of Isovalent Cilium Enterprise for several years. Today, [we are open sourcing major parts as project Tetragon](https://github.com/cilium/tetragon) and open it up for collaboration with the entire community."

[Demystifying the Kubernetes Iceberg: Part 1](https://asankov.dev/blog/2022/05/15/demystifying-the-kubernetes-iceberg-part-1/)  
Anton Sankov  
"**NOTE**: Even though I have been working with Kubernetes for almost three years at the time of this writing, I still don’t consider myself a Kubernetes expert. In fact, I was also not familiar with some of the more advanced concepts here, so I had to do some learning myself. And this is one of the reasons for writing this series of articles. So that we can learn and grow together, both my readers and me." That's an important thing to point out. I don't consider myself a Kubernetes expert either. While I'm probably more versed in it than I know (that's true because I learned so making all those bespoke configs for the dockershim removal docs team). Kubernetes is for distributed systems. Remember [above the line, below the line](https://shortcdn.com/file/devopsish/3380774.3380777.pdf). Like most things, you need to know the basics to build on additional concepts that get introduced further down the line. If you understand TCP/IP or HTTP, for example, there's a whole host of things you are now knowledgeable of that you don't realize at first.

[Flux from End-to-End](https://fluxcd.io/docs/flux-e2e/)  
Flux  
"We describe the flow of data through Flux, from End to End." A GitOps must read.

[Linux To Introduce The Ability To Set The Hostname Before Userspace Starts](https://www.phoronix.com/scan.php?page=news_item&px=Linux-Kernel-Hostname-Set)  
Michael Larabel, Phoronix  
"So now finally in 2022 there is a kernel parameter working its way upstream with `"hostname="` should you want to ensure the hostname is set before user-space is started." FINALLY!

[The Best Kubernetes Monitoring Tools](https://speedscale.com/2022/02/28/the-best-kubernetes-monitoring-tools/)
Jay Clark, Speedscale  
A very high level overview of monitoring tools available for Kubernetes.

[DB Browser for SQLite](https://sqlitebrowser.org/)  
The first thing I do when I get access to a database is look how it's organized. You can do this on the CLI or with some connection parameters a GUI. There's no wrong answer for viewing data. Use a tool that works best for you.

[wfxr/forgit](https://github.com/wfxr/forgit)  
A utility tool powered by fzf for using git interactively.

[anchore/grype](https://github.com/anchore/grype)  
A vulnerability scanner for container images and filesystems

## DevOps'ish Post of the Week

[![http://operationdvoretskyi.org #KubeConEU (Chris Lentricchia 🤙, @IAmCippino on Twitter)](https://shortcdn.com/file/devopsish/268-devopsish-tweet-of-the-week-2x.webp)](https://twitter.com/IAmCippino/status/1526827726635732994)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
