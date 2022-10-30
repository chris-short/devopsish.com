+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-12-20T07:00:00Z
description = "Solarwinds Orion compromise, State of Women in Tech Report 2020, 737 MAX Assumptions, Google postmortem, Discord, CKS, CKAD, WebAssembly, and more"
draft = false
slug = "197"
tags = ["Kubernetes", "cloud", "Solarwinds", "compromise", "hack", "DevOps", "Women in Tech", "Google", "ARM", "Linux", "WiFi", "Docker", "Git", "cloud native", "Red Hat", "Apple", "security", "runtime", "Boeing", "CKS", "container", "supply chain", "harassment", "GitHub", "OKRs", "FAA", "Discord", "open source", "air gapped", "cluster", "Cloud Native Computing Foundation", "CNCF", "CLI", "AltaVista", "search engine", "Solarwinds Orion", "OpenShift", "GitHub Actions", "OpenShift", "GitOps", "Windows", "SSH", "remote", "scientists", "observability", "Operator"]
title = "DevOps'ish 197"

+++

This being a holiday break my intros will probably be a little bit shorter than normal. "More punchy" as my first boss at Red Hat would say. Let's start with the thing with an ever-increasing blast radius: **Solarwinds**.

## Solarwinds Supply Chain Compromise

For the record, Reuters has been all over this coverage wise. I can't do them justice. This story has been evolving so rapidly that by the time I hit send, my coverage will be incomplete. Everything from Russian hackers to insider trading to putting a global sinkhole in place for the command and control (C2) domain.

This is a truly terrifying compromise at a company [I genuinely enjoyed working for in the past](https://chrisshort.net/resume/). No, I never touched the Orion product while I worked there. Perhaps I should have. But, over the years, I've been in contact with more places than I can count that use Solarwinds Orion. It really is everywhere that has a big enough footprint to justify it. Governments included. This might turn out to be bigger than the OPM hack when the dust settles. I decided to build an [Index](https://devopsish.com/categories/Indexes) page to provide continuing coverage of the [**Solarwinds supply chain compromise**](https://devopsish.com/solarwinds-supply-chain-compromise/). When in doubt, go to this page for vetted info.

There's already a lot of coverage and it will continue to grow. Here's where you the reader can help round out the coverage. Feel free to add missing links yourself (and help me enjoy my downtime a little more); [pull requests welcome](https://github.com/chris-short/devopsish.com/) or you can e-mail or [DM me on Twitter](https://twitter.com/ChrisShort).

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=devopsish&utm_campaign=197)

## People

[Use OKRs to Set Goals for Teams, Not Individuals](https://hbr.org/2020/12/use-okrs-to-set-goals-for-teams-not-individuals)  
This drove me a little batty at one employer. Now I at least no why. "Setting individual OKRs generally leads to goals that are either not true indications of meaningful progress or that are easily gameable. Instead, individual contributors should be assessed based on the extent to which their work contributes to team goals that add real value to the company and its customers."

[State of Women in Tech Report 2020](https://womenwhotech.com/data-and-resources/state-women-tech-and-startups)  
Women Who Tech's annual report shows that half of women founders have been harassed in the past twelve months; 41% of that harassment was sexual harassment. "Nearly 50% of women founders were told they would raise more money if they were a man." Additionally, "Women in tech aren't reporting the harassment they experience to senior leadership at the same rate as they have previously." WOMEN DESERVE BETTER! Forward this to a scumbag you know. Tell them you expect better. The only way we stop this vile and insane behavior is by having people that look like the scumbags standing up against them. They're bullies and criminals, they should be treated and dealt with as such. I'm tired of this shit and I'm pulling cards in 2021, believe that.

[Device and data access when personal safety is at risk](https://manuals.info.apple.com/MANUALS/1000/MA1976/en_US/device-and-data-access-when-personal-safety-is-at-risk.pdf)  
Apple's 20-page guide to protecting yourself. "If you're concerned that someone is accessing information you did not share from your Apple device, this guide will also help you identify risks, and walk you through the steps to help make the technology you rely on as private and secure as you want it to be."

[China-Based Executive at U.S. Telecommunications Company Charged with Disrupting Video Meetings Commemorating Tiananmen Square Massacre](https://www.justice.gov/opa/pr/china-based-executive-us-telecommunications-company-charged-disrupting-video-meetings)  
This is super shady behavior. Xinjiang Jin no longer works at Zoom now.

[Why Capable People Are Reluctant to Lead](https://hbr.org/2020/12/why-capable-people-are-reluctant-to-lead)  
I don't want to lead folks right now for a variety of reasons. Mainly because the last time I managed people I was brought in to help transform an org, which to leadership, meant to be an ax. I don't roll like that. It's on the list of things I need to tackle through therapy, to be honest. As a matter of fact, that job likely led to an acceleration of a decline in my mental health. Leadership is brutal in some orgs.

[Retail Sales Fell More Than Expected as Spending Slowed](https://www.nytimes.com/2020/12/16/business/us-retail-sales-november.html)  
I foresee a tougher economy ahead. A lot tougher as our change in behavior due to COVID-19 changes a number of spending habit changes across the world. The US administration could do something about it to help, but I do not think what is being kicked around in Congress is going to help anything long term.

## Process

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[nixcraft's NET4 India Debacle](https://threadreaderapp.com/thread/1340258493056499712.html)  
NET4 India sounds like an awful registrar. Now they're out of business with their director in prison for fraud. Hundreds of thousands of domains now remain in limbo. The good news is, [Nixi permits Net4India domain name customers to shift to other registrars](https://www.business-standard.com/article/current-affairs/nixi-permits-net4india-domain-name-customers-to-shift-to-other-registrars-120092901612_1.html)

[Boeing 'inappropriately coached' pilots in 737 MAX testing: U.S. Senate report](https://www.reuters.com/article/us-boeing-737-max-idUSKBN28S314)  
"The committee concluded Federal Aviation Administration (FAA) and Boeing officials 'had established a pre-determined outcome to reaffirm a long-held human factor assumption related to pilot reaction time ... It appears, in this instance, FAA and Boeing were attempting to cover up important information that may have contributed to the 737 MAX tragedies.'" My God...

[Google Cloud Status Dashboard](https://status.cloud.google.com/incident/zall/20013)  
"On Monday 14 December, 2020, for a duration of 47 minutes, customer-facing Google services that required Google OAuth access were unavailable. Cloud Service accounts used by GCP workloads were not impacted and continued to function. We apologize to our customers whose services or businesses were impacted during this incident, and we are taking immediate steps to improve the platform's performance and availability." A fascinating read into how Google accidentally broke things.

[Update: Discord confirms raising $100M at a valuation of $7B](https://techcrunch.com/2020/12/17/filing-discord-is-raising-up-to-140m-at-a-valuation-of-up-to-7b/)  
Discord is the new Slack.

[[2012.06884] AIR-FI: Generating Covert Wi-Fi Signals from Air-Gapped Computers](https://arxiv.org/abs/2012.06884)  
Oh, this is good and terrifying. Researchers have figured out a way to turn the memory bus into a Wi-Fi transmitter. “Our evaluation shows that data can be exfiltrated from air-gapped computers to nearby Wi-Fi receivers located a distance of several meters away.”

[CKS Certification Study Guide: Cluster Setup in Kubernetes](https://www.stackrox.com/post/2020/12/cks-certification-study-guide-cluster-setup-in-kubernetes/)  
"As we dive into studying for the Certified Kubernetes Security Specialist (CKS) program, make sure to understand the test and its structure. A full blog details the Cloud Native Computing Foundation’s (CNCF) announcement about the CKS and its exam structure."

## Tools

[Kubernetes is Removing Docker Support, Kubernetes is Not Removing Docker Support](https://www.openshift.com/blog/kubernetes-is-removing-docker-support-kubernetes-is-not-removing-docker-support)  
Fellow Red Hatter, Scott McCarty, covers why Docker is so damn confusing to folks in detail and how to manage things going forward. Josh Berkus sums it up well in [this tweet](https://twitter.com/fuzzychef/status/1339734481373024256), "The fact that the term 'docker' refers to a CLI, a server, a container runtime, a container building tool, and an online container host has never not been confusing."

**We need your voice!**

In partnership with the team at ClearPath Strategies, [Honeycomb.io](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish) is collecting insights for changes in software development and operation practices across our industry. How do you see the world and what your team is doing? 

[Take the survey](https://clearpathstrategies.sjc1.qualtrics.com/jfe/form/SV_cMAECZ6jv5wmjrL?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=software-production-excellence-survey-clearpath-devopsish&utm_adgroup=) for a chance to win $500 from Apple, HelloFresh, or Fender. *SPONSORED*

[An Alternate AltaVista Search Engine History Lesson For Internet Nerds](https://tedium.co/2020/12/15/altavista-history-digital-dot-com-domain-name)  
"How AltaVista, our first good search engine, fell into the digital abyss"

[How Shopify Uses WebAssembly Outside of the Browser](https://shopify.engineering/shopify-webassembly)  
"We wrap Lucet within a Rust web service which manages the I/O and storage of modules, which we call the Wasm Engine."

[Commits are snapshots, not diffs](https://github.blog/2020-12-17-commits-are-snapshots-not-diffs/)  
"I believe that Git becomes understandable if we peel back the curtain and look at how Git stores your repository data. After we investigate this model, we'll explore how this new perspective helps us understand commands like `git cherry-pick` and `git rebase`."

[Go on ARM and Beyond](https://blog.golang.org/ports)  
ARM is the future. You can run [Kubernetes on Raspberry Pis](https://chrisshort.net/raspberry-pi-kubernetes-cluster/) thanks largely to Go's early embrace of non-x86 architectures. "In the past year, several major vendors have made announcements of new ARM64 hardware for servers, laptops and developer machines. Go was well-positioned for this. For years now, Go has been powering Docker, Kubernetes, and the rest of the Go ecosystem on ARM64 Linux servers, as well as mobile apps on ARM64 Android and iOS devices."

[Deploying to OpenShift using GitHub Actions](https://www.openshift.com/blog/deploying-to-openshift-using-github-actions)  
"The OpenShift starter workflow uses the Red Hat GitHub Actions to help you get an application up and running by providing a workflow that automatically builds and deploys your application." This is a viable starting point on your GitOps journey. Perhaps this route will be easier to embrace at first than ArgoCD and Flux. I'm going to be kicking the tires on some of these soon enough. Stay tuned to [OpenShift.tv](https://openshift.tv) in 2021 for a GitOps Happy Hour on this topic.

[A Windows Guy in a Linux World: VS Code and Remote SSH](https://adamtheautomator.com/vs-code-remote-ssh/)  
"Welcome to the final installment of A Windows Guy in a Linux World blog post series where you'll learn to use VS Code to connect to a remote SSH host. If you have been following along with the series, by now you should already have all of the tools and knowledge to start remotely managing your Linux machines (including editing files)."

[Effective Linux & Bash for Data Scientists](https://dagshub.com/blog/effective-linux-bash-data-scientists/)  
"In November 2020, DAGsHub gave a series of guest lectures to the excellent Y-DATA course for aspiring data scientists, which we would now like to share with whoever finds it useful, in blog form!"

[martinvonz/jj](https://github.com/martinvonz/jj)  
Jujube (an experimental VCS)

[external-secrets/kubernetes-external-secrets](https://github.com/external-secrets/kubernetes-external-secrets)  
Integrate external secret management systems with Kubernetes

[timescale/tobs](https://github.com/timescale/tobs)  
The Observability Stack for Kubernetes. Easy install of a full observability stack into a k8s cluster with a CLI tool or Helm charts.

[upptime/upptime](https://github.com/upptime/upptime)  
Uptime monitor and status page powered by GitHub

[k8spin/k8spin-operator](https://github.com/k8spin/k8spin-operator)  
K8Spin multi-tenant operator

## DevOps'ish Tweet of the Week

[![DevOps'ish 197 Tweet of the Week](https://shortcdn.com/devopsish/197-devopsish-tweet-of-the-week.png)](https://twitter.com/bryanl/status/1339951522092900352)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/197/notes.md) to see what didn't make it to the newsletter.
