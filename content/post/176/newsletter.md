+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-04-19T07:00:00Z
description = "Upcoming hiatus, phishing, DevSecOps, Mars rover driving from home, Vision Fund, BGP, Kubernetes Operators, OpenTelemetry, and more!"
draft = false
slug = "176"
tags = ["cloud", "Kubernetes", "DevOps", "AWS", "GitHub", "cloud native", "security", "Linux", "IDE", "eBPF", "Vision Fund", "BGP", "Operators", "container", "Microsoft", "privelege escalation", "phishing", "Verizon", "BlueJeans", "Red Hat", "EKS", "GKE", "AKS", "OpenTelemetry", "Lambda", "VSCode"]
title = "DevOps'ish 176"

+++

Next week's DevOps'ish (177) will be the last DevOps'ish for a while. I'm going to be putting DevOps'ish on a COVID-19 hiatus. A large part of making this newsletter is reading the news every day. Even with very heavy-handed filtering, the amount of data I read about the ongoing pandemic is far higher than one should be consuming. I'm pausing DevOps'ish because the news is hard to read these days. I'll still be around. I've got something I'm pretty excited about in the works. Stay tuned on [Twitter](https://twitter.com/ChrisShort) and [chrishort.net](https://chrisshort.net) for more info on that.

## People

[Sawfish phishing campaign targets GitHub users](https://github.blog/2020-04-14-sawfish-phishing-campaign-targets-github-users/)  
"Over the last week, GitHub has received reports related to a phishing campaign targeting our customers. We're publishing this blog to increase awareness of this ongoing threat."

[DevOps Chats: DevSecOps and OpenShift, with Red Hat](https://devops.com/devops-chats-devsecops-and-openshift-with-red-hat/)  
When Kirsten Newcomer speaks, I listen. "We're seeing that shift left a lot, but then there's all these other range of things that you should be doing and can be doing to build security into the platform. And so, when we saw pod security policies in Kubernetes, for example, that's a way that the Kube admin can take advantage of the Linux features that enable container isolation at the Kubernetes layer and enforce things like ensure that a container doesn't run with unnecessary privileges."

[Stop Making Students Use Eclipse](https://nora.codes/post/stop-making-students-use-eclipse/)  
"When students don't understand what a file is, or haven't ever edited text in anything but Microsoft Word and don't realize they can edit code outside of an IDE, they will not be able to do the crucial work of self-directed learning that is a hallmark of all computer science success."

[How Working Parents Can Support One Another](https://hbr.org/2020/04/how-working-parents-can-support-one-another)  
I know there are thousands of working parents juggling kids right now. Yes, Max is around most of the day, but we're fortunate in that we're a single-income household. If you're working with folks that are tagging out of meetings and directly into parenting so their partner can do their meeting, please give them the advantage of every ounce of flexibility you have.

[NASA's Curiosity Keeps Rolling As Team Operates Rover From Home](https://www.nasa.gov/feature/jpl/nasas-curiosity-keeps-rolling-as-team-operates-rover-from-home)  
If these folks can control a rover on another fucking planet while working from home, what's your organization's excuse? I've talked to four different doctors the past couple weeks and every, single one of them thinks we might have changed medicine forever at this point.

[Is It Even Possible to Focus on Anything Right Now?](https://hbr.org/2020/04/is-it-even-possible-to-focus-on-anything-right-now)  
It's not. Stop acting like we're all okay.

## Process

[Zero Day Initiative - CVE-2020-8835: Linux Kernel Privilege Escalation via Improper eBPF Program Verification](https://www.thezdi.com/blog/2020/4/8/cve-2020-8835-linux-kernel-privilege-escalation-via-improper-ebpf-program-verification)  
"This blog explains the technical details of an exploit using the Linux eBPF feature to achieve local privilege escalation. Due to the nature of the bug(s), which are rather subtle misbehaviors of a safety-critical feature called the “verifier”, some explanations about the inner workings of eBPF need to be provided first."

[SoftBank expects $24 billion in losses from Vision Fund, WeWork and OneWeb investments](https://techcrunch.com/2020/04/13/softbank-expects-24-billion-in-losses-from-vision-fund-wework-and-oneweb-investments/)  
Now we all have to figure out what definition of vision is the correct one for Vision Fund.

[Online Workshop: Practical Steps to Reduce Your AWS Bill](https://devopsi.sh/practical-steps-4640e)  
Learn about practical steps you can take now to reduce your AWS bill. In this workshop, you'll learn common causes of cloud waste, how to get cost visibility with proper tagging and account segmentation, and how to analyze your cost in the context of your business. Looking to get immediate visibility into your costs? Check out the only engineering-first cloud cost management tool and start a free trial at [www.cloudzero.com](https://www.cloudzero.com/). *SPONSORED*

[Is BGP Safe Yet? No. But we are tracking it carefully](https://blog.cloudflare.com/is-bgp-safe-yet-rpki-routing-security-initiative/)  
BGP will take a significant amount of work to become safe. The fact that as a 19-year old I could redirect a whole country's network traffic on accident to a router I controlled (and things like that are still happening today) shows just how far we have to go with BGP.

[Verizon will buy video conferencing company BlueJeans](https://www.cnbc.com/2020/04/16/verizon-will-buy-video-conferencing-company-blue-jeans.html)  
I wonder if I should start taking my BlueJeans meetings over my Verizon connection.

['Remote hands' flub takes out much of Cloudflare](https://www.itnews.com.au/news/remote-hands-flub-takes-out-much-of-cloudflare-546752)  
"During planned maintenance remote hands decommissioned some equipment that they shouldn't have." This has happened to me before.

## Tools

[Crafting Kubernetes Operators](https://developers.redhat.com/blog/2020/04/15/crafting-kubernetes-operators/)  
"In this talk, you'll learn about crafting Kubernetes Operators from Josh Wood and Burr Sutter."

[Git Releases Security Update With Newline Character Creating Possible Credential Leak](https://www.phoronix.com/scan.php?page=news_item&px=Git-Newline-Leak-Vulnerability)  
"A member of Google's Project Zero team discovered that a specially crafted URL could trick the Git client into sending credential information for an alternative host to an attacker's host."

[EKS vs. GKE vs. AKS - Comparing the top three cloud providers](https://devopsi.sh/gke-aks-e3ad2)  
Not all managed Kubernetes services are created the same. They support different features and options for their cluster control planes and nodes, and they vary in how much management they really provide. To help cut through the fog, StackRox performed a hands-on, side-by-side comparison of the top three services (EKS, AKS, GKE) to help you understand their current state and trade-offs - updated April 2020 *SPONSORED*

[OpenTelemetry Steps up to Manage the Mayhem of Microservices](https://thenewstack.io/opentelemetry-steps-up-to-manage-the-mayhem-of-microservices/)  
"Work continues to make OpenTelemetry the standard set of vendor-neutral specifications and associated tools for capturing cloud native operational data."

[The Good Parts of AWS](https://gumroad.com/l/aws-good-parts)  
I bought this book to read after I finish The Unicorn Project (finally).

[Fedora Silverblue is an amazing immutable desktop](https://blog.christophersmart.com/2020/04/11/fedora-silverblue-is-an-amazing-immutable-desktop/)  
Layers aren't just for containers.

[Online Debug for AWS Lambda on your IDE!](https://devopsi.sh/aws-lambda-97890)  
Thundra allows you to natively debug your serverless applications on the cloud with their own permissions. Thundra's online-debugger sets up a secure bridge between your AWS Lambda environment and your IDE. VSCode and IntelliJ IDEA are natively supported with plugins. For other IDEs, we provide a portable client to foster the integration with any IDEs. Start debugging Node.js, Python and Java functions for free today! *SPONSORED*

[alexellis/awesome-baremetal](https://github.com/alexellis/awesome-baremetal)  
"Bare-metal is awesome. Let's share our favourite tools."

[raphamorim/lucario](https://github.com/raphamorim/lucario)  
"The best flat theme for Vim, Atom, Sublime Text, Jetbrains Editors, Terminal.app, iTerm, Xcode and XTerm" I switched to this theme in VSCode while writing this newsletter. I had to turn the brightness down on my monitor, that's probably a good thing. So far, I like it.

## DevOps'ish Tweet of the Week

{{< tweet 1248953443361918977 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/176/notes/) to see what didn't make it to the newsletter.
