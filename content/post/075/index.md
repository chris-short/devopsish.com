+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2018"]
date = 2018-05-13T07:00:00Z
description = ""
draft = false
slug = "075"
tags = ["devops", "cloud native", "open source", "kubernetes", "delivery", "microservices", "container", "security", "Ansible", "assholes", "containers", "Site Reliability Engineering", "SRE"]
title = "075: Assholes, SRE, Container and Kubernetes Security, Ansible for Windows, and More"
image ="https://shortcdn.com/file/devopsish/075-web.jpg"

+++

Assholes seemed to be the theme of the week. First, Rafael Avila de Espindola is [leaving the LLVM](https://lists.llvm.org/pipermail/llvm-dev/2018-May/122922.html) project because it adopted a code of conduct and its support of [Outreachy](https://www.outreachy.org/). Yes, Rafael is arguing that creating a framework to foster a more inclusive community and helping folks that have are at a significant disadvantage is against his "ethical views". Next, infamous bad actor, Richard Stallman, vehemently [opposed the removal of an abortion joke from glibc](https://lwn.net/SubscriberLink/753646/fdf5a92e1f87c69e/) source code. The basis for the opposition? "The fact that this is
not strictly and grimly technical is not a reason to remove this." Because a [GNU manual isn't meant to be a "safe space"](https://lwn.net/Articles/753654/) according to Stallman. Finally, Josh Pigford suggested that [changing jobs every 12-18 months was a red flag for hiring](https://twitter.com/shpigford/status/994583740943929346?s=12). When numerous people called bullshit, Josh continually doubled-down even after [someone pointed out Josh had ten jobs in a ten-year span](https://twitter.com/mordorinc/status/995190017394819072). Instead of apologizing or better explaining his statement Josh hid behind the fact the responses to his comments were overwhelming and decided to "[not look at Twitter for a few days](https://twitter.com/Shpigford/status/995008192429088769)" as a result. In my opinion, changing jobs every twelve to eighteen months shows you have a significant ability to learn and adapt. You will also have a significant experience advantage over someone who coasted somewhere for years because it was "comfortable". All of these assholes were nice enough to self-identify. Make sure you remember who they are should you ever cross paths with them. The moral of the story is, we all need to be excellent to each other and helpful to everyone. If you are somehow against that for some reason then maybe you're in the wrong line of existence.

[**5 considerations for continuous delivery of microservices**](https://www.gocd.org/2018/04/25/five-considerations-continuous-delivery-microservices/?utm_campaign=cd_microservices&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_microservices_blog&utm_term=)  
Continuous Delivery is an essential component of any software delivery practice, including microservices. This new blog series shares five considerations we recommend keeping in mind when designing a CD workflow on microservices architectures. *SPONSORED*

## Events

[**The Orchestructure Workshop**](https://www.meetup.com/orchestructure/events/250189685/)  
Date: 2018-05-19  
The Orchestructure Workshop will bring together southern Michiganders to provide hands-on experiences with the very technologies talked about at every meetup. The Workshop will take place over 4 hours with beginner and advanced content tracks including a lunch period break and group conversations at the end.

[**ChefConf 2018**](https://chefconf.chef.io/)  
Dates: 2018-05-22 through 2018-05-25  
Join an awesome community of #DevOps and automation professionals at [ChefConf](https://chefconf.chef.io/) in Chicago. I'll be presenting, *DevOps is Not a War*. Save 10% with discount code **Hugs4Chef**.

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

[**DevNation Federal**](https://devnationfederal.org/)  
Date: 2018-06-05  
Join us to learn about the revolutions happening in communities around containers, data, and application modernization. This is an opportunity for you to hear how visionary teams in the federal government are innovating with open source, and hear from leaders in the private sector doing the same.

[**Chaos Conf**](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[**LISA18**](https://www.usenix.org/conference/lisa18)  
Dates: 2018-10-29 through 2018-10-31  
Have something to say on the present & future of #ops? The LISA18 CFP closes May 24. [Submit your ideas](https://www.usenix.org/blog/usenix-lisa18-cfp-nashville)!

## People

[The ultimate DevOps hiring guide](https://opensource.com/article/18/4/ultimate-devops-hiring-guide): Trying to round up DevOps talent? We're a unique lot that requires some tweaks to your hiring practices.

[On a DevOps team? Learn the art of saying no](https://opensource.com/article/18/5/art-saying-no-devops): To focus on what you do best, sometimes you need to say no. Here's how to do so politely and respectfully.

[Fourth Circuit Rules That Suspicionless Forensic Searches of Electronic Devices at the Border Are Unconstitutional](https://www.eff.org/deeplinks/2018/05/fourth-circuit-rules-suspicionless-forensic-searches-electronic-devices-border-are): This is good news for US citizens. I'll be honest, I'm considering getting a Pixelbook for travel internationally because of intrusive customs policies. If they were cheaper I'd already have one.

[Programmers are having a huge debate over whether they should be required to behave respectfully to each other](http://www.businessinsider.com/programmers-debate-requirements-to-behave-respectfully-ccoc-2018-5): If you're a part of this debate please stop. We're humans, we should treat others how we want to be treated, period. We must make sure everyone is welcome regardless of [INSERT DEMOGRAPHIC HERE]. This is madness.

[Who Pays the Most and Least in Silicon Valley](https://www.wired.com/story/who-pays-the-most-and-least-in-silicon-valley): Facebook, Google, and Twitter are the top three. Amazon is dead last.

[The Subtle Sexism Of Your Open Plan Office](https://www.fastcodesign.com/90170941/the-subtle-sexism-of-your-open-plan-office): A remarkable new study documents the experiences of women in an open office designed by men.

## Process

[SRE vs. DevOps: competing standards or close friends?](https://cloudplatform.googleblog.com/2018/05/SRE-vs-DevOps-competing-standards-or-close-friends.html): There is a lot more in common with DevOps and SRE than most people think. In my opinion, SRE is the codification of acceptable risk, performance, and contribution of work towards metrics. Both require organizational buy-in. One statement I think applies across the board is, "Encourage moving quickly by reducing costs of failure." You can't accelerate software deployments without this thinking. I have been saying this for a very long time. SRE and DevOps are both ultimately trying to do the same thing; make software development and delivery be enjoyable.

[The Ultimate Guide to Kubernetes Security](https://neuvector.com/container-security/kubernetes-security-guide/): A full spectrum look at securing your Kubernetes environments.

[Exploring container security: Isolation at different layers of the Kubernetes stack](https://cloudplatform.googleblog.com/2018/05/Exploring-container-security-Isolation-at-different-layers-of-the-Kubernetes-stack.html): A discussion of the Kubernetes that will help you maintain a more secure environment.

[The Women in Tech Show: Container Security with Maya Kaczorowski](https://thewomenintechshow.com/2018/05/07/container-security-with-maya-kaczorowski/)

[IBM bans all removable storage, for all staff, everywhere](https://www.theregister.co.uk/2018/05/10/ibm_bans_all_removable_storage_for_all_staff_everywhere/): "Risk of 'financial and reputational damage' is too high, says CISO"

[Microsoft Windows, Apple macOS, Linux, BSD: All hit by same 'serious' security flaw](https://www.zdnet.com/article/microsoft-windows-apple-macos-linux-bsd-all-hit-by-same-serious-security-flaw/): OS and hypervisor makers patch flaw that attackers could use to crash systems or read data from memory.

[Kubernetes stands at an important inflection point](https://techcrunch.com/2018/05/06/kubernetes-stands-at-an-important-inflection-point/): "Much like a startup that realizes it actually achieved the product-market fit it had hypothesized, the Kubernetes  community has to figure out how to take this to the next level — and that reality presents some serious challenges and enormous opportunities."

[Mapping Maturity: create context specific maturity models with Wardley Maps informed by Cynefin](https://medium.com/@chrisvmcd/mapping-maturity-create-context-specific-maturity-models-with-wardley-maps-informed-by-cynefin-37ffcd1d315)

[Kubernetes best practices: Resource requests and limits](https://cloudplatform.googleblog.com/2018/05/Kubernetes-best-practices-Resource-requests-and-limits.html)

[JEDI mind tricks: Brakes slammed on Pentagon's multibillion cloud deal](https://www.theregister.co.uk/2018/05/08/house_slams_the_brakes_on_pentagons_big_cloud_deal/): This may not be the vendor you're looking for – explain yourself to get your funding

[Defining SLOs for services with dependencies - CRE life lessons](https://cloudplatform.googleblog.com/2018/05/Defining-SLOs-for-services-with-dependencies-CRE-life-lessons.html): "Discussion on how to define and manage SLOs for services with dependencies, each of which may (or may not!) have their own SLOs."

[Tesla's Factory in a Fishbowl](https://www.wsj.com/articles/teslas-factory-in-a-fishbowl-1525716237): All eyes are on the electric-car maker's production process, which is akin to that of a software company

## Tools

[Ten Things I Hate About You: Manage Windows like Linux with Ansible](https://www.ansible.com/blog/ten-things-i-hate-about-you-manage-windows-like-linux-with-ansible)

[A new API for mounting filesystems](https://lwn.net/Articles/753473/) (Subscription Required): fsmount() has entered the game.

[You may not need websockets](https://sipsandbits.com/2018/05/10/you-may-not-need-websockets/): Hark! Whatever do you mean?

[Announcing Microsoft's own Content Delivery Network](https://azure.microsoft.com/en-us/blog/announcing-microsoft-s-own-cdn-network/): "enabling Azure customers to use and deliver content from Microsoft's own global CDN network."

[Bitnami Launches Kubeapps 1.0 to Advance Kubernetes Application Services](http://www.prweb.com/releases/2018/05/prweb15452909.htm)

[Is K8s Too Complicated?](http://jmoiron.net/blog/is-k8s-too-complicated/): [Above the line and below the line matter](https://www.oreilly.com/ideas/above-the-line-below-the-line) a lot when it comes to container orchestration. The systems we work on everyday are already complicated. We understand the older complications and how to handle them somewhat gracefully. Kubernetes is a new layer.

[AWS Command line: S3 content from stdin or to stdout](https://loige.co/aws-command-line-s3-content-from-stdin-or-to-stdout/): "This article presents a quick tip that will help you deal with the content of files in S3 through the AWS command line in a much faster and simpler way."

[awslabs/aws-sam-cli](https://github.com/awslabs/aws-sam-cli): AWS SAM CLI 🐿 is a CLI tool for local development and testing of Serverless applications

[guardicore/monkey](https://github.com/guardicore/monkey): Infection Monkey - An automated pentest tool

[solo-io/envoy-operator](https://github.com/solo-io/envoy-operator): Envoy Operator creates/configures/manages Envoy clusters atop Kubernetes

## Jobs

[**SJ Technologies**](http://sjtechcorp.com/) is looking to bring someone on board to work in our DevOps and Digital Transformation practice. If you want to help some big-time companies eager to implement change [*let me know*](mailto:chris.short@sjtechcorp.com). Plus, you get to work for great team of folks including [Karen Lawton](https://twitter.com/sjtech_karen?lang=en), [John Willis](https://twitter.com/botchagalupe/), [Barbara Bouldin](https://twitter.com/bbouldin711), and [ME](https://chrisshort.net/).

[DZone](http://careers.dzone.com/apply/DBWe0hiNCN/Site-Reliability-Engineer) is looking for a Site Reliability Engineer in Cary, NC. Based off my experiences with DZone, this is a cool place to work. To quote a decision maker at DZone, "We need strong cloud, automation, security [experience]." Check them out.

## DevOps'ish Tweet of the Week

{{< tweet 994190137016967168 >}}
