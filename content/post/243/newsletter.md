+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-11-14T07:00:00Z
description = ["Bellwethers, changes at Red Hat, Kubernetes 2021 Steering Committee Election Results, Monstrosity Email, Bitbucket's move to AWS is complete, and more"]
draft = false
slug = "243"
tags = ["cloud", "free", "service", "DevOps", "bellwethers", "Kubernetes", "news", "dockershim", "infrastructure", "email", "infrastructure", "code", "cloud native", "open source", "Red Hat", "programming", "kustomize", "automation", "Terraform", "Kustomize Cheat Sheet", "GitOps"]
title = "DevOps'ish 243: Bellwethers, changes at Red Hat, Kubernetes 2021 Steering Committee Election Results, Monstrosity Email, Bitbucket's move to AWS is complete, and more"

+++

[bellwether](https://www.dictionary.com/browse/bellwether) — noun — a person or thing that shows the existence or direction of a trend; index.

I want to introduce a metric I use to evaluate potential employers. I have bellwethers. People that I respect and whose work interests me. I use them to gauge my potential for success at a company. I keep a mental list of folks and where they're working. In some cases, when I start to evaluate a specific employer, I check how long they've been there and often ask folks who have been there a long time how to succeed.
These bellwethers have to be people you can call or chat with when you have questions. Often they're folks that you have established relationships. Even better, have a bunch of bellwethers; this way, if you end up with multiple opportunities, you know folks at each potential employer, you can have a chat. These can be local, national, or international. But, two keys, you have to know them and have a lot of them.

If your bellwethers are starting to gather in one place, you know something is up and should investigate. If you know your bellwethers are leaving a specific company, you know organizations you should approach with caution. If all of a sudden your bellwethers are all in flux, that's a clear indicator you should start putting feelers out there. But, if you suddenly begin considering opportunities, you can quickly short circuit your search by reaching out to your bellwethers. It's not always what you know. More often than not, it's who your know.

💡 Set your email autoresponder to “Due to supply chain issues, this email may go unnoticed for quite some time. Extreme shortages will make for delayed replies sometimes in excess of 14 days.”

## People

[Hey Guys](https://heyguys.cc/)  
"'Hey guys' is a common salutation, but it's not gender neutral. People who aren't men can feel excluded when addressed as “guys,” even if that is not the intent."

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Red Hat to hire fewer senior engineers after budget frozen](https://www.theregister.com/2021/11/05/red_hat_jobs/)  
Dodged that bullet. "'All current reqs and future backfills will be down-leveled by one level by default (e.g., Senior Software Engineer to Software Engineer),' the memo explained." Red Hat might be top heavy, I'll give the C-suite that. But, they're also one of the lower paying employers in tech too. In essence, this was a preventable event, the low pay necessitated the inflation of titles, which has now led to a perceived top heaviness. Regardless, I feel more confident about the timing behind my recent employment decisions.

[Judge buys Rittenhouse lawyer's inane argument that Apple's pinch-to-zoom manipulates footage](https://www.theverge.com/2021/11/10/22775580/kyle-rittenhouse-trial-judge-apple-ai-pinch-to-zoom-footage-manipulation-claim)  
"Judge Schroeder argued that it was the prosecution — not the defense — that had the burden of proving that Apple doesn't use artificial intelligence to manipulate footage, demanding that they provide an expert to testify, and didn't allow the prosecution to adjourn to find that expert before bringing Rittenhouse up for cross-examination." Last I checked... This is a bald face lie and this judge is forcing the prosecution to prove an apparition created without actual evidence by the defense. Holy smokes.

[Announcing the 2021 Steering Committee Election Results](https://kubernetes.io/blog/2021/11/08/steering-committee-results-2021/)  
Congrats to Christoph Blecker, Stephen Augustus, Paris Pittman, and Tim Pepper.

[These parents built a school app. Then the city called the cops](https://arstechnica.com/information-technology/2021/11/these-parents-built-a-school-app-then-the-city-called-the-cops/)  
Punishing people who show up government programs/officials is an all too common theme in our field.

## Process

[Three rules of bug fixing for better OSS security](https://github.blog/2021-11-09-three-rules-bug-fixing-better-oss-security/)  
Building the regression test first is an important takeaway from this one.

Distributed tracing helps you debug complex service relationships. But trace data is only one piece of the puzzle. See how Honeycomb's integrated approach to tracing puts the pieces together for you. Get the [power of Honeycomb for free](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[AT&T Alien Labs finds new Golang malware (BotenaGo) targeting millions of routers and IoT devices with more than 30 exploits](https://cybersecurity.att.com/blogs/labs-research/att-alien-labs-finds-new-golang-malwarebotenago-targeting-millions-of-routers-and-iot-devices-with-more-than-30-exploits)  
"AT&T Alien Labs™ has found new malware written in the open source programming language Golang. Deployed with more than 30 exploits, it has the potential of targeting millions of routers and IoT devices." A deep dive into a new Mirai looking but, different functioning malware that's taking advantage of Go. It'll be rewritten in Rust by next week's edition.

[The Monstrosity Email Has Become](https://ploum.net/the-monstrosity-email-has-become/)  
Email is **hard**. Run a public facing mail server with multiple users and you'll quickly feel like you're on the wrong end of the value chain. DKIM, SPF, DMARC, BIMI, MX, proving to the mail provider you actually own the domain, and a host of other foot guns will find you wondering where you went wrong starting a newsletter some nights. Oh wait... That's my story. "Your mail inbox is becoming a battlefield where everyone with a small authority fight for your attention, trying to fill your mental space even if you don't open the mail."

[Report for vulnerabilities in Oh My Zsh (2021-11-12)](https://github.com/ohmyzsh/ohmyzsh/issues/10414)  
`omz update` post haste

## Tools

[How Kubernetes Validates Custom Resources](https://danielmangum.com/posts/how-kubernetes-validates-custom-resources/)  
![Image by Daniel Mangum — 'This post is about one part of one handler in one API server in the Kubernetes API server chain.'](https://shortcdn.com/devopsish/k8s-resource-validation.webp)

[Pulumi: Infrastructure as Code](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)
Developing on the cloud is complex. What if you could use your existing programming knowledge to build, deploy, and manage cloud infrastructure using your favorite languages and tools? Pulumi is a cloud engineering platform that lets you write infrastructure as code in any programming language and on any cloud platform. Get started for free at [pulumi.com](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac) *SPONSORED*

[The Service Mesh: What Every Engineer Needs to Know about the World's Most Over-Hyped Technology](https://buoyant.io/service-mesh-manifesto/)  
"The architecture of the service mesh has a couple big implications. For one, since the proxy featureset is designed for service-to-service calls, the service mesh really only makes sense if your application is built as services. You could use it with a monolith, but it would be a whole lot of machinery to run a single proxy, and the featureset wouldn't be a great fit." A good read.

[Dockershim removal is coming. Are you ready?](https://kubernetes.io/blog/2021/11/12/are-you-ready-for-dockershim-removal/)  
"Last year we announced that Dockershim is being deprecated: [Dockershim Deprecation FAQ](https://kubernetes.io/blog/2020/12/02/dockershim-faq/). Our current plan is to remove dockershim from the Kubernetes codebase soon. We are looking for feedback from you whether you are ready for dockershim removal and to ensure that you are ready when the time comes. **Please fill out this survey**: <https://forms.gle/svCJmhvTv78jGdSx8>."

[Kubernetes Kustomize Cheat Sheet](https://scribe.rip/@olegsucharevich/kubernetes-kustomize-cheat-sheet-8e2d31b74d8f)  
"kustomize is a command-line tool supporting template-free, structured customization of declarative configuration targeted to k8s-style objects. Targeted to k8s means that kustomize has some understanding of API resources, k8s concepts like names, labels, namespaces, etc., and the semantics of resource patching. kustomize is an implementation of DAM."

[Two NPM Packages With 22 Million Weekly Downloads Found Backdoored](https://thehackernews.com/2021/11/two-npm-packages-with-22-million-weekly.html)  
`coa` and `rc` "were found to be compromised with malicious code by gaining unauthorized access to the respective developer's accounts."

[Bitbucket Cloud has landed in AWS](https://bitbucket.org/blog/bitbucket-cloud-has-landed-in-aws)  
The story of a massive cloud migration that went right.

[Free Developer Stuff](https://freestuff.dev/)  
"List of free service for developer to use. Some services are free forever or have a free tier at least for 1 year"

[chubin/awesome-console-services)](https://github.com/chubin/awesome-console-services)  
A curated list of awesome console services (reachable via HTTP, HTTPS and other network protocols

[im2nguyen/rover](https://github.com/im2nguyen/rover)  
"Interactive Terraform visualization. State and configuration explorer."

## DevOps'ish Tweet of the Week

[![Liz Fong-Jones (方禮真) (@lizthegrey) on Twitter) "Dear event organizers, until rapid test+antiviral is a thing, your event is not accessible to immunocompromised unless you have: (1) mandatory mask/vaxx/rapid test for entry, (2) physical distancing in seating _and_ lines/pickup, (3) distancing preference wristbands for mingling"](https://shortcdn.com/devopsish/243-devopsish-tweet-of-the-week.webp)](https://twitter.com/lizthegrey/status/1458491938319974403)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/243/notes.md) to see what didn't make it to the newsletter but are still worth your time.
