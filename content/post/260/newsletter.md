+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-03-13T07:00:00Z
description = ["Organizational skills a key to productivity, don't spy on employees, Elementary OS implosion, Dirty Pipe, big ole amplification attacks, GitOps galore, lavished by Linkerd, and more"]
draft = false
slug = "260"
tags = ["GitOps", "ArgoCD", "Kubernetes", "DevOps", "security", "security incident", "attack", "cloud", "Cloud Native", "Linkerd", "practitioners", "cybersecurity", "vulnerability", "community", "collaboration", "avoid pitfalls", "Flux", "infrastructure", "DDoS", "developers", "CNCF", "OpenGitOps", "Elementary OS", "Honeycomb"]
title = "DevOps'ish 260: Organizational skills a key to productivity, don't spy on employees, Elementary OS implosion, Dirty Pipe, big ole amplification attacks, GitOps galore, lavished by Linkerd, and more"
+++

We are very fortunate. I remind myself of that every day. Our household's collective efforts have put us where we are today (being some random dude from a town called Hickory; this is far further than I'd ever imagined). I have been posting pictures from my new office that we custom built in our basement. I'm very fortunate to have a room, with a solid door and some soundproofing, to work from in these times. The only thing to bother me are the things I let into my day.

It was funny, the other day, when I got a knock on the door and two of my nephews rolled in with Max and Julie. "Wow, Uncle Chris! I didn't realize you were down here!" "Oh wow, Uncle Chris! I love your office!" Even the kids think it's cool. Like I said, very fortunate.

This weekend, I [live tweeted cleaning out two bins FULL of cables](https://twitter.com/ChrisShort/status/1502649910415474688?utm_campaign=devopsish&utm_source=newsletter&utm_medium=text). Lots of old memories brought up. All normal and some great memories. Now, I'm in a space that is just for *me*. Julie has a space just for herself as well. Both getting improved upon a little bit more every day.

I’m iterating on a consistent theme, “Optimize storage space (create as much as possible and use it as best as possible), recycle, right-size, or dispose. Do not keep anything unless you think you might need it based off what’s *in this house*.” It is an wonderful feeling to be organized. It is how I maintain a usually high level of productivity. I will admit, when my workspace is chaotic, I’m chaotic. Optimizing every thing to your desired state of balance requires not overthinking things. What’s the dead simplest way to achieve X? Will you appreciate seeing this every day? Will this function as you desired?

Some pictures still need to be hung. But, I’ve been operational down here for a couple weeks now. I can say I’ve fulfilled a long time dream of working from home, in an office that has been custom built to optimize my productivity and comfort. Flexible yet reliable. It’s a balance of the best of both worlds in what is now my third and hopefully last office in this house.

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## Events

Calling all front-line DevOps and SRE practitioners: Join [**IR Conf**](https://www.irconf.io/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on April 1 (no joke), a free, half-day virtual conference for industry experts and new voices in incident response. Incident responders will come together to swap horror stories about the biggest outages, discuss best practices, and gain a better understanding of how the best are dealing with incidents. Register to:

* Discover trends and tooling in resiliency and incidence response
* Gain guidance on how to structure your teams, tooling, and processes
* Learn better practices from incident response experts
* Connect with a community of incident responders who care about this, learn from each other

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/?utm_source=newsletter&utm_medium=258&utm_campaign=devopsish) on 2022-05-17 is designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)  
SEPTEMBER 19 – 21, 2022  
ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[Amazon announces 20-for-1 stock split, $10 billion buyback](https://www.cnbc.com/2022/03/09/amazon-announces-20-for-1-stock-split-10-billion-buyback.html)  
I don't think this helps or hurts me as a new employee. But, a lot of my coworkers are about to get happier.

[Flux for Helm Users](https://youtu.be/r_vKf5l1D1M)  
Use Helm? Want to use Flux? Here you go!

[U.S. Senate Passes Cybersecurity Bill to Strengthen Critical Infrastructure Security](https://thehackernews.com/2022/03/us-senate-passes-cybersecurity-bill-to.html)  
"The U.S. Senate unanimously passed the 'Strengthening American Cybersecurity Act'... The new bipartisan legislation, among other things, stipulates entities that experience a cyber incident to report the attacks within 72 hours to the U.S. Cybersecurity and Infrastructure Security Agency (CISA), in addition to alerting the agency about ransomware payments within 24 hours." This is going to make a big impact once signed into law. We're going to see a ***huge*** uptick in reported compromises too I suspect.

[Spy on Your Employees, Make The Great Resignation Worse](https://news.crunchbase.com/news/great-resignation-worse-employee-retention/)  
Don't spy on your employees. Just don't.

## Process

[Linux has been bitten by its most high-severity vulnerability in years](https://arstechnica.com/information-technology/2022/03/linux-has-been-bitten-by-its-most-high-severity-vulnerability-in-years/)  
Dirty Pipe needs a theme song at this point.

[Multiple Security Flaws Discovered in Popular Software Package Managers](https://thehackernews.com/2022/03/multiple-security-flaws-discovered-in.html)  
"But the newly discovered issues in various package managers highlight that they could be weaponized by attackers to trick victims into executing malicious code."

[Privilege Escalation Vulnerability CVE-2022-0492 and its impact on Kubernetes](https://www.armosec.io/blog/privilege-escalation-vulnerability-cve-2022-0492-kubernetes/)  
"Until you upgraded the base kernel image to the fixed version or applied a specific temporary patch, your node is vulnerable."

[Leaked stolen Nvidia key can code-sign Windows malware](https://www.theregister.com/2022/03/05/nvidia_stolen_certificate/)

[CVE-2022-26143: TP240PhoneHome Reflection/Amplification DDoS Attack Vector](https://www.akamai.com/blog/security/phone-home-ddos-attack-vector)  
This is bad. A "potential amplification ratio of 4,294,967,296:1" combined with, "This particular attack vector differs from most UDP reflection/amplification attack methodologies in that the exposed system test facility can be abused to launch a sustained DDoS attack of up to 14 hours in duration by means of a single spoofed attack initiation packet." This is a bad time waiting to happen to literally anyone. All because of 2,600 poorly configured devices. The numbers in this report are eye-watering.

[Google to Acquire Mandiant](https://www.mandiant.com/company/press-release/mgc)  
Interesting move by Google. One would think they'd have enough security folks on staff to manage customer needs but, here's another way to make sure of that.

## Tools

[The future of Kubernetes – and why developers should look beyond Kubernetes in 2022](https://www.cncf.io/blog/2022/03/04/the-future-of-kubernetes-and-why-developers-should-look-beyond-kubernetes-in-2022/)  
"As summarized above, the majority of the traditional Kubernetes resources may have better alternatives for developers. Using alternatives will improve how we develop and operate cloud-native applications in the years to come. After all, Kubernetes is a platform for building platforms. It’s not the end-game!"

[Kubernetes at Scale without GitOps Is a Bad Idea](https://thenewstack.io/kubernetes-at-scale-without-gitops-is-a-bad-idea/)  
"In this article, we describe the issues and challenges that enterprises face when deploying Kubernetes clusters at scale. We also describe how GitOps processes and tools can allow organizations to gain proper control of these highly distributed environments while improving security and compliance best practices."

[A deep dive to Canary Deployments with Flagger, NGINX and Linkerd on Kubernetes](https://devopsian.net/posts/kubernetes-canary-deployments/)  
A cloud native good time that I'm here for.

[Is Linkerd Winning the Service Mesh Race?](https://thenewstack.io/is-linkerd-winning-the-service-mesh-race/)  
"Independent of the CNCF survey, analyst firm Enterprise Management Associates (EMA) noted a 'strong momentum of the Linkerd platform,' Torsten Volk, an analyst at EMA, said. 'Its growing user base is raving about its simplicity and its targeted addition of more enterprise-grade features.'"

[Announcing automated multi-cluster failover for Kubernetes](https://linkerd.io/2022/03/09/announcing-automated-multi-cluster-failover-for-kubernetes/)  
"This feature gives Linkerd the ability to automatically redirect all traffic from a failing or inaccessible service to one or more replicas of that service—including replicas on other clusters."

[Apple Announces M1 Ultra: Combining Two M1 Maxes For Workstation Performance](https://www.anandtech.com/show/17306/apple-announces-m1-ultra-combining-two-m1-maxes-for-even-more-performance)  
This is a deep dive into how the M1 Ultra Arm processor formed from two M1 Max's. "M1 Max has a very high speed interface along one of its edges." This is a novel approach.

[6 CNCF Projects for CI/CD](https://containerjournal.com/features/6-cncf-projects-for-ci-cd/)  
[OpenGitOps](https://opengitops.dev/) is shouted out here. Please join our [fortnightly meetings](https://tockify.com/cncf.public.events/detail/401/1647453600000) if you'd like to help contribute to what GitOps is and isn't. Note: I'm a co-chair of the OpenGitOps project.

[Scripting with Go](https://bitfieldconsulting.com/golang/scripting)  
"I'm not saying shell scripting is obsolete. I still use a lot of shell scripts myself. There is a large problem domain where shell is absolutely the right answer. But small programs tend to grow into large ones, and when that happens, it's nice to be able to use the facilities of a language that was designed for programming at scale."

[elementary OS is imploding](https://lunduke.substack.com/p/elementary-os-is-imploding)  
Oh this is really sad because elementary OS is what I default to for new to Linux users. Clearly the company has a lot of issues. But, I hope the community can keep this distro going. 🤞🤞🤞

[estafette/estafette-vulnerability-scanner](https://github.com/estafette/estafette-vulnerability-scanner)  
"An application that regularly scans all containers in a Kubernetes cluster for vulnerabilities"

## DevOps'ish Tweet of the Week

{{< tweet user="todaywasawesome" id="1501955445094699024">}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/260/notes.md) to see what didn't make it to the newsletter but are still worth your time.
