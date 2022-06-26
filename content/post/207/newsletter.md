+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-02-28T07:00:00Z
description = "Solarwinds, 4 hour a week Kubernetes maintainer, mischievous Mailchimp, secrets management, Digital Ocean IPO, Sysdig, BOOP, Flux, and More"
draft = false
slug = "207"
tags = ["Kubernetes", "cloud", "time", "DevOps", "Cloud Native", "software", "open source", "secrets management", "development", "CNCF", "DNS", "LaunchDarkly", "git", "Mailchimp", "Raindrop.io", "EmailOctopus", "Digital Ocean", "Google", "JUST", "vulnerabilities", "Citi", "Microsoft", "IBM", "Sysdig", "kernel", "eBPF", "boop", "Flux", "GitOps", "security", "automation", "hybrid cloud", "developer"]
title = "DevOps'ish 207: Solarwinds, 4 hour a week Kubernetes maintainer, mischievous Mailchimp, secrets management, Digital Ocean IPO, Sysdig, BOOP, Flux, and More"

+++

DevOps'ish is in a state of spring cleaning. First, I've found a tool that I like more than Pocket to bookmark and save pages in [Raindrop.io](https://raindrop.io/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish). All the Recommended Reads automation is now pulling from Raindrop.io. Then three Zapier rules ferry everything off to the appropriate places. I made that transition midweek.

Next is the newsletter service itself. I've been unhappy with the current provider ever since doing the never-easy switch from Mailchimp (how forward-thinking that was) to the current provider. I've had more tickets opened than newsletters sent; enough was enough. Last week, I discovered [**EmailOctopus**](https://emailoctopus.com/?urli=n6msM). I have been researching it in my spare time. Yesterday was a day off for me, so I started the switch to making DevOps'ish a Google Workplace domain and use EmailOctopus to send newsletters. It takes a lot more work than it should to get and send an email than it used to, but it'll be worth it.

The [DevOps'ish Solarwinds supply chain compromise Index](https://devopsish.com/solarwinds-supply-chain-compromise/) has many updates this week. Including the former Solarwinds CEO blaming an intern for the mistake and a congressional hearing on the matter.

## People

[Give Black Employees Time to Rest and Recover](https://hbr.org/2021/02/give-black-employees-time-to-rest-and-recover)  
"Black employees have been navigating both the disproportionate effects of Covid-19 and systemic racism over the past year. Prioritizing recovery and resilience, both from an organizational and personal perspective, is vital. To do this, focus on four key areas: getting rest, learning to say “no,” making space for collective healing and care, and positively affirming Black identity."

[Never wait for a staging environment again](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=title&utm_campaign=20210228) 🛑  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team's ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. You'll never have to wait around for staging environments again. 🚀 [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=20210228) 🚀

[How I became a Kubernetes maintainer in 4 hours a week](https://opensource.com/article/21/2/kubernetes-maintainer)  
"If you have a small amount of time, you can make a big difference in open source." I see Matt doing it every week. I need to get my poop in a group.

[How to Avoid the Most Dangerous Word in Software Development](https://pawelurbanek.com/dangerous-word-slack)  
"J-U-S-T. Those four characters can be significantly detrimental to a software development process. In this blog post, I'll describe how the 'just keyword' can affect team's communication and how to avoid misusing it on Slack."

[Mailchimp employees have complained about inequality for years — is anyone listening?](https://www.theverge.com/22300931/mailchimp-company-culture-discrimination-unequal-pay?scrolla=5eb6d68b7fedc32c19ef33b4)  
And the [CEO admitted they have "work to do."](https://www.businessinsider.com/mailchimp-ceo-ben-chestnut-email-pay-equity-discrimination-kelly-ellis-2021-2) That might be an understatement.

[#hugops hope to spread empathy in tech](https://www.protocol.com/enterprise/oral-history-hugops)  
"When something breaks on the internet, the people who know how to fix it just want to give their colleagues a hug — even if they're a rival."

## Process

[CNCF Provides Insights into Secrets Management Tools with Latest End User Technology Radar](https://www.cncf.io/announcements/2021/02/23/cncf-provides-insights-into-secrets-management-tools-with-latest-end-user-technology-radar/)  
An interesting assessment. What are you using for secrets management in your environment?

["Fix Kubernetes vulnerabilities with a pull request"](https://snyk.io/lp/kubernetes/)  
Kubernetes misconfiguration is the #1 cloud vulnerability. Find and fix K8s misconfigurations and vulnerabilities with a pull request. Get started with Snyk for free.

[Follow the CAPEX: Digital Ocean](https://www.platformonomics.com/2021/02/follow-the-capex-digital-ocean/)  
Digital Ocean is going public. DO is a great cloud for many use cases. I do one thing running in DO for personal use. I bet other folks do too.

[Please do not put IP addresses into DNS MX records](https://blog.hboeck.de/archives/904-Please-do-not-put-IP-addresses-into-DNS-MX-records.html)  
Don't violate RFC 1035... Just don't.

[Some quick thoughts on Citi's $900M OOPSie](https://surfingcomplexity.blog/2021/02/19/some-quick-thoughts-on-citis-900m-oopsie/)  
"Citi accidentally transferred $900 million dollars to various hedge funds. Citi then asked the funds to reverse the mistaken transfer, and while some of the funds did, others said, 'no, it's ours, and we're keeping it,' and Citi took them to court, and lost." This story is wild. It's [a checkbox away from a disaster](https://www.bloomberg.com/opinion/articles/2021-02-17/citi-can-t-have-its-900-million-back) waiting to happen; which makes me wonder how it hasn't happened before.

[Everything is broken, and it's okay](https://increment.com/reliability/failure-is-okay/)  
"Accepting that imperfect things still work is fundamental to preventing failures from becoming catastrophes."

## Tools

[Breaking down and fixing Kubernetes](https://itnext.io/breaking-down-and-fixing-kubernetes-4df2f22f87c3)  
"The Kubernetes architecture allows you to easily survive various kinds of failures and always stay afloat. Today we will break the cluster, delete certificates, rejoin nodes on live, and doing all this fancy stuff without possible downtime for already running services."

**LaunchDarkly** is a feature management platform that empowers all teams to safely deliver and control software through feature flags. By separating code deployments from feature releases, LaunchDarkly enables you to deploy faster, reduce risk, and iterate continuously. Microsoft, IBM, Atlassian, and 1500+ organizations use LaunchDarkly to build, operate, and learn from their software. [Learn more](https://launchdarkly.com/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) and start your free trial today!

[Sysdig contributes Falco's kernel module, eBPF probe, and libraries to the CNCF](https://sysdig.com/blog/sysdig-contributes-falco-kernel-ebpf-cncf/)  
"I'm excited to announce the contribution of the Sysdig kernel module, eBPF probe, and libraries to the Cloud Native Computing Foundation."

[Kubernetes Gives Us That for FREE](https://youtu.be/ZQrLinUOp3c)  
It doesn't.

[Boop](https://boop.okat.best/)  
Brian Ketelsen mentioned Boop this week. It's going to save me a ton of time. Thanks, Brian.

[🚨🚨 That's a lot of YAML 🚨🚨](https://noyaml.com/)  
> Made with 💖 by <https://twitter.com/geoffreyhuntley> after one too many CustomResourceDefinitions

[How We Minimized the Overhead of Kubernetes in Our Job System](https://www.datadoghq.com/blog/engineering/moving-a-jobsystem-to-kubernetes/)  
"If you're running a lot of machines, you probably know that Kubernetes can offer significant management and scalability benefits. But these benefits aren't free..."

[Free Windows 10 development virtual machines for HyperV, Parallels, VirtualBox, and VMWare](https://www.hanselman.com/blog/free-windows-10-development-virtual-machines-for-hyperv-parallels-virtualbox-and-vmware)  
These are super useful to be aware of.

[Four causes for ‘Zoom fatigue’ and their solutions](https://news.stanford.edu/2021/02/23/four-causes-zoom-fatigue-solutions/)  
Meeting software has become a tool in everyone's toolbox. Whether they wanted it or not. Some good tips in this one.

[A little tool to make DNS queries](https://jvns.ca/blog/2021/02/24/a-little-tool-to-make-dns-queries/)  
Everyone loves a good DNS tool.

[Flux v2 is getting closer](https://www.weave.works/blog/flux-2-is-getting-closer)  
I hope to hear more news about this GitOps tool.

[ComplianceAsCode/content](https://github.com/ComplianceAsCode/content)  
Security automation content in SCAP, OSCAL, Bash, Ansible, and other formats

[git-learning-game/oh-my-git](https://github.com/git-learning-game/oh-my-git)  
An interactive Git learning game!

[DidierRLopes/GamestonkTerminal](https://github.com/DidierRLopes/GamestonkTerminal)  
The next best thing after Bloomberg Terminal

## DevOps'ish Tweet of the Week

[![amye on Twitter: "Ok, so everyone is just a little weird this week, right? Yes. This is because there is such a thing as 'ambiguous loss', and we are all coming up on the year anniversaries of 'how the world turned upside down'. So. That is why everything is weird."](https://shortcdn.com/file/devopsish/207-devopsish-tweet-of-the-week.png)](https://twitter.com/amye/status/1364685306646028288)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/207/notes/) to see what didn't make it to the newsletter but are still worth your time.
