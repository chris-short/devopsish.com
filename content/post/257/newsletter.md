+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-02-20T07:00:00Z
description = ["Kubernetes dockershim removal work, shades of DevOps, signal jamming is still illegal (in most places), CKA tips, PostgreSQL horrors, Kubernetes on a PS4, and more"]
draft = false
slug = "257"
tags = ["Kubernetes", "Docker", "time", "SSH", "security", "containerd", "CRI", "DevOps", "CNCF", "git", "Honeycomb", "Plaid", "dockershim", "CKA", "PostgreSQL", "Zabbix", "vulnerability"]
title = "DevOps'ish 257: Kubernetes dockershim removal work, shades of DevOps, signal jamming is still illegal (in most places), CKA tips, PostgreSQL horrors, Kubernetes on a PS4, and more"

+++

I spent a lot of time working on the [dockershim removal](https://k8s.io/dockershim) documentation effort. These docs are vitally important to our community. These updates often require some technical hands to get things figured out. First, many people have to be very specific and finite in their language with Docker and Kubernetes. Yes, it's cringe-worthy how often you say anything potentially harmful about Docker, and people think, "the entire container ecosystem will collapse without the existence of this one company." It shows how the learning paths to Kubernetes must be improved upon. Yes, you might need Docker Engine to get containers running on your Mac or Windows laptop. But, all the CRI implementations are containerd (or CRI-O) now when you get into production. containerd is a graduated CNCF project (and is the default CRI in Kubernetes), and CRI-O is an incubating project. If you notice, Docker, Docker Engine, and anything else with the word docker are on the [CNCF projects](https://www.cncf.io/projects/) page. The internet shock and awe factory is real. It takes people with some battle hardening around the Docker topic to write some of these docs.

Second, the work is technologically hard. For example, `DefaultAddCapabilities` are a [docker specific concept](https://docs.petty.company/engine/reference/run/#runtime-privilege-and-linux-capabilities) exposed via Kubernetes. What happens to `DefaultAddCapabilities` when the dockershim is gone in 1.24. Keep in mind [Kubernetes Pod Security Policies](https://kubernetes.io/docs/concepts/policy/pod-security-policy/) aren't removed until 1.25. Do we remove these from all the docs? What happens to PSPs if those capabilities are just gone? What then? I've never done such fulfilling docs work in my life.

Third, I've volunteered to test oddball use cases I was comfortable with. Use Fedora and CRI-O with Kubernetes and update the docs around that! That use case generated questions about long strings in outputs, which the Docs team didn't have a style standard for yet. Getting the test environment up was an interesting enough challenge. But, what made it more interesting was having to create that environment twice because I deleted it when I started the PR (wait until your PRs merge before blowing away test environments). I've learned things I never knew about Kubernetes because I'm working on this project. We could use more help. Look for the dockershim named items in the CNCF Slack and CNCF Calendar.

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## People

[A Hacker Group Has Been Framing People for Crimes They Didn't Commit](https://gizmodo.com/a-hacker-group-has-been-framing-people-for-crimes-they-1848522497)  
"A recent study shows the tactics and techniques of a cybercrime group that is known for planting incriminating evidence on the devices of activists in India."

[Shades of DevOps - Related Job titles](https://www.jedi.be/blog/2022/02/11/shades-of-devops-roles/)  
Patrick Debois posts, I usually mention it. This chart makes for an interesting pay scale justification. I've been a SysAdmin, DevOps Engineer and Manager, I did web ops right before DevOps caught fire. Today I talk to a lot of Platform Engineer, Cloud Ops teams, and there are still network engineers out here.

[Dad takes down town's internet by mistake to get his kids offline](https://www.bleepingcomputer.com/news/technology/dad-takes-down-towns-internet-by-mistake-to-get-his-kids-offline/)  
This poor dad. Just trying to make sure his kids get some sleep. Hey, the jammer you bought, might be a little stronger than you realized.

[Building for the 99% Developers](https://future.a16z.com/software-development-building-for-99-developers/)  
We know that we're all just trying to make the best of the tooling we have. Sometimes it's not the Silicon Valley's latest trinket or widget. Most of the time it's Java money printing machine that we make sacrifices for so we can tinker with the latest thing and become good enough to one day pay our bills using it eventually.

[How Tumblr taught young women to code](https://mashable.com/article/tumblr-girl-learn-code)  
"Young women were lured to Tumblr by fandom and fashion. Now they've turned coding into a career."

## Process

[Passed my CKA exam first time - here are my tips!](https://www.reddit.com/r/kubernetes/comments/ssk065/passed_my_cka_exam_first_time_here_are_my_tips/)  
*u/WillSewell* shares how they pass their CKA on reddit. Join [r/devopsish](https://www.reddit.com/r/devopsish/) while you're over there.

[A Hairy PostgreSQL Incident](https://ardentperf.com/2022/02/10/a-hairy-postgresql-incident/)  
I don't think I've ever read this much about PostgreSQL in one sitting. I mean seriously, you usually don't have to do much with Postgres out of the box.

[Plaid is an evil nightmare product from Security Hell](https://drewdevault.com/2022/02/19/Plaid-is-an-evil-nightmare-product.html)  
Yes, Plaid is pretty bad. As a matter of fact, I can't use it at all. All of my accounts are locked down with security features that aren't supported by Plaid. I want to believe people people favor security over convenience when it comes to their banking credentials. Don't crush my small, impossible dreams. Let me just keep this one.

[Critical vulnerabilities in Zabbix Web Frontend allow authentication bypass, code execution on servers](https://portswigger.net/daily-swig/critical-vulnerabilities-in-zabbix-web-frontend-allow-authentication-bypass-code-execution-on-servers)  
"Two vulnerabilities in open source monitoring platform Zabbix could allow an attacker to bypass authentication and execute arbitrary code on a targeted server." Also, could I interest you in the newsletter's sponsor [Honeycomb](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup)?

[New Chrome 0-Day Bug Under Active Attack – Update Your Browser ASAP!](https://thehackernews.com/2022/02/new-chrome-0-day-bug-under-active.html)  
Seriously, update your browsers folks. You make me cringe every time you share your screens.

## Tools

[1Password for SSH & Git (Beta)](https://developer.1password.com/docs/ssh/)  
"Introducing 1Password for SSH & Git (Beta), the single source of truth for all your SSH keys. With 1Password, you can, 1. Generate and import your SSH keys. 2. Autofill public keys in your browser for Git and other cloud platforms. 3. Use the 1Password SSH Agent to authenticate all your Git and SSH workflows." I'm here for this.

[Free Cybersecurity Services and Tools](https://www.cisa.gov/free-cybersecurity-services-and-tools)  
A grab bag of tools to meet your various security needs.

[Automatic SBOMs with ko](https://blog.chainguard.dev/auto-sboms-with-ko/)  
"Bobby Flay here with the coolest shit in SBOMs."

[101 AWS Lambda tutorial for Go developers](https://blog.mantil.com/101-aws-lambda-tutorial-for-go-developers-api-gateway-part-2-7008d2b64a4e)  
"Add API Gateway to your AWS Lambda function in Go via Terraform"

[SendGrid appending a tracking pixel even when disabled](https://cappe.github.io/blog/sendgrid-appending-a-tracking-pixel.html)  
I kinda figured companies need to measure their deliverability rates, in near real time too, so they know when an IP address is burnt by a bad actor. The fact they could measure EVERYTHING though and not a subset of messages is the problem.

[Kubernetes on a PS4](https://zhekunhu.xyz/ps4-kubernetes.html)  
Just read it. It makes no sense to do this... Or does it???

[Toshiba's 20TB HDDs Are Ready For Primetime](https://www.tomshardware.com/news/toshiba-20tb-drive-validated)  
I like to remind people in 1994 I paid $300 for a 1.6 GB hard drive one summer. I thought that was a ton of space at the time.

[How To Expose Multiple Applications on Amazon EKS Using a Single Application Load Balancer](https://aws.amazon.com/blogs/containers/how-to-expose-multiple-applications-on-amazon-eks-using-a-single-application-load-balancer/)  
"AWS Load Balancer Controller is a controller that helps manage Elastic Load Balancers for Kubernetes clusters. For this scenario, we are using the Ingress kind to automatically provision an ALB and configure the routing rules needed for this ALB to be defined via Kubernetes manifests."

## DevOps'ish Tweet of the Week

[![Nicole Holliday (@mixedlinguist on Twitter) "I am once again begging companies with computer scientists to actually hire social scientists instead of reading a summary of their ideas and then sloppily applying them to massive million-dollar applications. A lot of y'all have never studied humans and it shows!"](https://shortcdn.com/file/devopsish/257-devopsish-tweet-of-the-week.webp)](https://twitter.com/mixedlinguist/status/1493213892620832776)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/257/notes/) to see what didn't make it to the newsletter but are still worth your time.
