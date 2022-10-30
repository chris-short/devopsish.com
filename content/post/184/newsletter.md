+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-09-20T07:00:00Z
description = "Observability, Kubernetes, Cloud Native, Bill Gates on Elon Musk and Steve Jobs, 1,000 ways to die and we chose plastic, and More"
draft = false
slug = "184"
tags = ["cloud", "cloud native", "Kubernetes", "DevOps", "data", "open source", "observability", "culture", "Bill Gates", "LAMBDA", "source code", "systems", "Cloud Native Computing Foundation", "Salesforce", "Cisco", "Phish Scale", "IBM", "Evernote", "Microsoft", "Portworx", "Tekton", "Rego", "OPA", "Accurics", "Terrascan", "serverless", "phishing", "Crunchy Data", "postgresql", "ebooks", "workloads", "pipelines", "CI/CD", "Alibaba Cloud", "Jeff Zhang", "Ansible", "Molecule", "CISO"]
title = "DevOps'ish 184"

+++

[![LAMBDA - A Serverless Musical (Hamilton "My Shot" Parody)](https://shortcdn.com/devopsish/LAMBDA-A-Serverless-Musical-Hamilton-My-Shot-Parody.png)](https://youtu.be/zMua0cuhFnc?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_184)

This is quite clever.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). Just announced: [Terrascan](https://www.accurics.com/blog/products/terrascan-kubernetes/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_184) extends Policy as Code to Kubernetes.

## People

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Chris Short: K8s Release Team - Cloud Native Computing Foundation - NVIDIA to buy Arm for $40B - Oracle and TikTok - OpenShift TV - Walmart Brings Back Gateway Computers by Tech Breakfast Podcast](https://anchor.fm/techbreakfast/episodes/Chris-Short-K8s-Release-Team---Cloud-Native-Computing-Foundation---NVIDIA-to-buy-Arm-for-40B---Oracle-and-TikTok---OpenShift-TV---Walmart-Brings-Back-Gateway-Computers-ejk8n1)  
I sat down and talked the news with the folks over at Tech Breakfast Podcast. It was a fun conversation in which I shared my assessment of the Tik Tok situation (it is rather dire).

[Salesforce announces 12,000 new jobs in the next year just weeks after laying off 1,000](https://techcrunch.com/2020/09/18/salesforce-announces-12000-new-jobs-in-the-next-year-just-weeks-after-laying-off-1000/)  
Nice to know Salesforce is the new Cisco.

[A Phish Scale: Rating Human Phishing Message Detection Difficulty (Paper)](https://www.ndss-symposium.org/wp-content/uploads/2019/02/usec2019_02-4_Steves_paper.pdf)  
"[W]e propose a Phish Scale, so CISOs and phishing training implementers can easily rate the difficulty of their phishing exercises and help explain associated click rates."

[Bill Gates: Difference between Elon Musk and Steve Jobs as leaders](https://www.cnbc.com/2020/09/18/bill-gates-difference-between-elon-musk-and-steve-jobs-as-leaders.html)  
Yes, comparing the dead to the living is awkward when you know both people. I gotta agree with Bill on that one.

[IBM made 'top-down' efforts to fire older workers, says US employment discrimination watchdog](https://www.theregister.com/2020/09/14/ibm_age_discrimination_finding/)  
I had friends and friends' parents get caught up in this. I think the thing that bugs me the most is that IBM probably anticipated the cost offset including lawsuits and still decided to be ageist.

[Is Plastic Recycling A Lie? Oil Companies Touted Recycling To Sell More Plastic](https://www.npr.org/2020/09/11/897692090/how-big-oil-misled-the-public-into-believing-plastic-would-be-recycled)  
We're truly doomed. Everything we know is a lie.

[COVID-19, privacy, and school recordings](https://iapp.org/news/a/covid-19-privacy-and-school-recordings/)  
🍿🍿🍿🍿🍿🍿🍿🍿🍿🍿

## Process

[Crunchy HA PostgreSQL - Ensure your data is always available](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week4&utm_campaign=CrunchyHA2)  
Meet your "always on" data requirements with trusted, open source components. Crunchy HA PostgreSQL gives you an all-in-one production PostgreSQL solution: HA, DR, monitoring that is securely deployed. Chat with Crunchy Data to [learn more](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week4&utm_campaign=CrunchyHA2). *SPONSORED*

[The new startup pitch: We're not Uber](https://www.sfchronicle.com/business/article/The-new-startup-pitch-We-re-not-Uber-15579206.php)  
The Uber for XYZ is dead. Finally.

[5 tips for using the Rego language for Open Policy Agent (OPA)](https://www.fugue.co/blog/5-tips-for-using-the-rego-language-for-open-policy-agent-opa)  
Here's your weekly mind bender.

[Microsoft's underwater data centre resurfaces after two years](https://www.bbc.com/news/technology-54146718)  
"That data centre has now been retrieved from the ocean floor, and Microsoft researchers are assessing how it has performed, and what they can learn from it about energy efficiency."

[Evernote's CEO on the company's long, tricky journey to fix itself](https://www.protocol.com/evernote-reboot-ian-small)  
When tech debt got one CEO fired and what the new CEO did to fix it. "18 months later." This is quite the story of transformation.

[Pure to Purchase Portworx for Prowess in Cloud Native Storage](https://thenewstack.io/pure-to-purchase-portworx-for-prowess-in-cloud-native-storage/)  
You might have missed this amongst all the insanity this week.

[Zerologon attack lets hackers take over enterprise networks: Patch now](https://www.zdnet.com/article/zerologon-attack-lets-hackers-take-over-enterprise-networks/)  
Hide yo kids. Patch your Windows.

## Tools

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[A Spotlight on Tekton](https://caylent.com/spotlight-on-tekton)  
"In simple terms, Tekton is designed to make k8s-style resources for declaring CI/CD-style pipelines available natively, making the whole process of managing and automating CI/CD pipelines easier."

[Serverless on Public Cloud: The Ultimate Showdown](https://thenewstack.io/serverless-on-public-cloud-the-ultimate-showdown/)  
An assessment of the various serverless solutions. In a shock to absolutely no one AWS wins.

[New /dev/random Implementation Hits 35th Revision](https://www.phoronix.com/scan.php?page=news_item&px=LRNG-dev-random-35)  
"This new /dev/random works even if the kernel API crypto is not compiled, hash operations are NUMA-node-local for better handling with large parallel systems, other types of DRNGs are supported, it's faster by up to 75% in a critical code path, and other performance advantages including faster entropy collection during boot including for SSD-backed systems and virtual machines."

[Taming the tar command: Tips for managing backups in Linux](https://www.redhat.com/sysadmin/taming-tar-command?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_184)  
"Rob?"  
"I'm so sorry."

[Alibaba debuts a new cloud operating system and its first cloud computer](https://siliconangle.com/2020/09/17/alibaba-debuts-new-cloud-operating-system-first-cloud-computer/)  
"[Alibaba Group Chief Technology Officer Jeff] Zhang said 'Wuying' can be connected to a screen and offers exactly the same functions as a regular personal computer. The only difference is that all workloads and computation are done in the cloud, rather than on the device. As such, 'Wuying' offers an 'infinite amount of computing power,' Zhang said."

[Developing and Testing Ansible Roles with Molecule and Podman - Part 2](https://www.ansible.com/blog/developing-and-testing-ansible-roles-with-molecule-and-podman-part-2?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_184)  
"Molecule helps in the development stage by allowing you to “converge” the instances with the role content. You can test each step without worrying about managing the instances and test environment. It provides quick feedback, allowing you to focus on the role content, ensuring it works in all platforms."

[Cruster](https://cruster.io/)  
"Easily Create and Manage Kubernetes Clusters on Raspberry Pis"

[jbangdev/jbang](https://github.com/jbangdev/jbang)  
Unleash the power of Java for shell scripting

[Kubeinit/kubeinit](https://github.com/kubeinit/kubeinit)  
Ansible automation to have a KUBErnetes cluster INITialized as soon as possible...

## DevOps'ish Tweet of the Week

{{< tweet 1307049532782505985 >}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/184/notes.md) to see what didn't make it to the newsletter.

