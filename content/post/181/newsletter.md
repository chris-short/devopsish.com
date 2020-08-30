+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2020"]
date = 2020-08-30T07:00:00Z
description = ""
draft = false
slug = "181"
tags = []
title = "DevOps'ish 181"

+++

Welcome!

It would appear the clock has run out for all the Heptio folks to get their payouts from the VMware acquisition. A few Kubernetes contributors are jumping ship from VMware. Four in a little over a week is nothing short of a sign, though. These aren't the kinds of folks who like to hang out in big corporate orgs and feel like cogs in the machine. They want to feel like they're making an impact and see the value in their work. They, like Deming, appreciate and take pride in their work. There is nothing at all wrong with this. I 100% understand, given that Red Hat is the biggest organization I've ever been a part of outside the Air Force. I can understand the appeal of the late-stage startup life too. But, there is comfort in working for a 25-year-old organization inside a much larger organization that probably won't muck with us too much given the current global situation. VMware completely sucked all the Heptio out of Heptio the second they started renaming and rebranding Heptio projects to VMware products. I have to hand it to Red Hat. Realizing that the CoreOS name meant something and keeping some of its projects active and incorporating the CoreOS name into products shows that at the very least, Red Hat appreciated CoreOS's work. I don't know if the same can be said for VMware of Heptio. Perception is often reality in these instances.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_181). Learn more about their new [open source project Terrscan](https://www.accurics.com/blog/products/terrascan-opa-policy-as-code/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_181).

## People

[DevOps engineer: IT's most in-demand title for the future](https://enterprisersproject.com/article/2020/8/devops-engineer-in-demand-it-title)  
"Have concerns about using the term 'DevOps' in job titles in the years to come? Get over it. Spend your time using the DevOps engineer title to help achieve important outcomes"

[Facebook algorithm found to 'actively promote' Holocaust denial](https://www.theguardian.com/world/2020/aug/16/facebook-algorithm-found-to-actively-promote-holocaust-denial#Echobox=1597587921)  
Utterly fucking disgusting. What else is Facebook fucking up besides elections and the truth about the Holocaust. Just turn it off.

[Camille Fournier on Effectively Managing Internal Platform Teams](https://www.infoq.com/news/2020/08/fournier-internal-platform/)  
"Camille Fournier, managing director, head of platform engineering at Two Sigma, recently shared her learnings from managing internal platform engineering teams. Two of the key challenges she shared are the smaller size of the customer base and the challenge in understanding how your customers will use your product. She also stressed the importance of ensuring invested development work is aligned to the best interests of the product and the end user."

[The Fall of Civilizations and Software](https://listed.to/@castrojo/17593/the-fall-of-civilizations-and-software)  
"One thing I've been trying to pay attention to is how historical subjects can be applied to modern open source communities. For example a year ago if you would have asked me what caused the Bronze Age collapse I'd have defaulted to 'Easy, it was the sea people. Easter Island? Everyone knows they just chopped all their own trees down right?'"

[Michigan reaches over $500M settlement in Flint water crisis suits](https://www.detroitnews.com/story/news/michigan/flint-water-crisis/2020/08/19/michigan-reaches-settlement-flint-water-crisis-suits/5612711002/)  
In case you didn't hear. No one will go to jail for poisoning children, decimating a community, and making people's homes unlivable. I hope the lawyers take as little as possible. Folks have had to rip *all* of their plumbing *to the street* just to get the toxins within tolerance. "If money is how government expresses sorrow for its crimes - this is a big apology."

[Every Decision Is A Risk. Every Risk Is A Decision.](https://fivethirtyeight.com/features/every-decision-is-a-risk-every-risk-is-a-decision/)  
When I worked ops jobs and higher risk positions, I used to tell my family, "Every time I hit ENTER, I'm making a decision. I'm taking a logical risk that what I'm about to do isn't going to blow things up." I'm glad I don't live like that anymore.

## Process

[Relying on plain-text email is a 'barrier to entry' for kernel development, says Linux Foundation board member](https://www.theregister.com/2020/08/25/linux_kernel_email/)  
Sarah is of course 100% in the right here. Forcing folks to use archaic tools to follow archaic processes will ultimately lead to only the archaic contributing. Get with times. You're already using Git for kernel development; there's about a dozen git servers out there with concepts like the Pull Request that solve this probably for the LKML, But, they'd rather bitch and moan and spend more energy on conspiracy theories and not being more welcoming.

[Exploring Certificates](https://dev.to/singhshemona/certificates-395n)  
"Certificates are one of those terms that are redefined for you once you embark on the journey of learning web development. It was certainly discussed in college within my computer science curriculum, but if you hadn't taken a network security class I'd imagine certificates may have come up within an exploration into encryption, networks or privacy of some sort. For those not in tech, your relationship to them might arise only when a reference to certificates appears in puzzling ways, like the following screen I'm sure many of us are somewhat familiar with:"

[Webinar | Empower DevOps and Security Teams with Kubernetes-native Security](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh)  
Startups and enterprises alike are embracing containerization and Kubernetes, but security struggles to move at the pace of DevOps, bogged down by tools and processes not suited for cloud-native technology. [Register for this webinar](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh) where cloud-native security experts from AWS, Informatica, and StackRox will discuss how to apply Kubernetes-native security and controls to protect containers and Kubernetes without slowing down application development and rollout. *Date: Sep 03, 2020 | 10 AM PDT* *SPONSORED*

[New P2P botnet infects SSH servers all over the world | Ars Technica](https://arstechnica.com/information-technology/2020/08/new-p2p-botnet-infects-ssh-servers-all-over-the-world/)  
This is nothing short of terrifying.

[Trump backs Oracle as potential TikTok buyer](https://www.theregister.com/2020/08/19/trump_backs_oracle_as_tiktok/)  
I have no idea WTF is going to happen with TikTok. But, Microsoft and WalMart of all people want in on the action too? Weird. The whole situation is weird and is probably going to get ruled illegal at some point anyway.

[Is Your Organization Ready for Permanent WFH?](https://hbr.org/2020/08/is-your-organization-ready-for-permanent-wfh)  
It's happening. Folks are subletting, Amazon is taking over former big box stores in malls for distribution centers, and things are generally going to move to working from home for the foreseeable future. I've been grounded until July 2021.

## Tools

[ArgoCD and Tekton: Match made in Kubernetes heaven](https://www.twitch.tv/videos/716089280)  

[GitOps Toolkit Roadmap](https://toolkit.fluxcd.io/roadmap/)  
I'm very interested in WeaveWorks and what they're doing. I think they have a great approach to GitOps.

[The Runaway Problem of Kubernetes Operators and Dependency Lifecycles](https://thenewstack.io/the-runaway-problem-of-kubernetes-operators-and-dependency-lifecycles/)  
Operators: A good problem to have.

[Do I Need Kubernetes?](https://mbird.biz/writing/do-i-need-kubernetes.html)  
Well do ya... Punk?

[Why are Creative Commons ”Non Commercial” licenses not Open Source and a big problem for hardware & product design - Mifactori](https://mifactori.de/non-commercial-is-not-open-source/)  
Licensing your projects matter. This is something I had not thought of about specific Creative Commons licenses. Don't worry! DevOps'ish doesn't use eight of these licenses.

[KubeCon EU: Accurics, Snyk Release Tools to Secure Infrastructure-as-Code Deployments](https://thenewstack.io/kubecon-eu-accurics-snyk-release-tools-to-secure-infrastructure-as-code-deployments/)  
"Cloud native security providers Accurics and Snyk have each released new tools that promise to help organizations secure infrastructure-as-Code (IaC) deployments."  
*[**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_181) is a sponsor of DevOps'ish*

[Run cloud-native Postgres on Kubernetes](https://www.crunchydata.com/developers/download-postgres/containers/postgres-operator?utm_source=DevOpsish&utm_medium=Week2&utm_campaign=CrunchyOperator)  
Make your Postgres deployments elastic, HA, and secure with open source Crunchy PostgreSQL for Kuberenetes. Its PostgreSQL Operator provides a simple interface to provision, secure and scale database clusters in your K8S environments. Download now or reach out to the team at Crunchy Data to get started. *SPONSORED*

[Why Kubernetes Operators Will Unleash Your Developers by Reducing Complexity](https://thenewstack.io/why-kubernetes-operators-will-unleash-your-developers-by-reducing-complexity/)  
"Operators are a big part of helping us reach this automated, on-demand, container-based future. Operators are operational procedures and best practices that are codified into software. They make automated day two operations possible on Kubernetes, and model the complexities of today’s distributed systems."

[GitOps gains momentum among Kubernetes deployment tools](https://searchitoperations.techtarget.com/news/252487865/GitOps-gains-momentum-among-Kubernetes-deployment-tools)  
"The growing popularity of Kubernetes GitOps tools reflects increasing cloud-native maturity and complexity among enterprise shops such as American Express."

[NTP's Fate Hinges On 'Father Time'](https://www.informationweek.com/it-life/ntps-fate-hinges-on-father-time/d/d-id/1319432)  
"The Network Time Protocol provides a foundation to modern computing. So why does NTP's support hinge so much on the shaky finances of one 59-year-old developer?"

[SQLite 3.33 Released With PostgreSQL-Inspired UPDATE FROM, Database Files Up To 281 TB](https://www.phoronix.com/scan.php?page=news_item&px=SQLite-3.33-Released)  
If you have at 100+ TB SQLite database, can I please interview you on a live stream or for a blog post or something. I want to know how and why?

[What I've learned about scaling OSPF in Datacenters](https://elegantnetwork.github.io/posts/What-Ive-learned-about-OSPF/)  
A little something for my network engineering buddies out there. You know I still got love for y'all. I used to be a heavy user of OSPF.

## DevOps'ish Tweet of the Week

{{< tweet 1296741182018486272 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/181/notes/) to see what didn't make it to the newsletter.

{{< amazon >}}
