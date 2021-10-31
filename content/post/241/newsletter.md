+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-10-31T07:00:00Z
description = ["REvil roasted, exfil with eBPF, stop your standups, find your coding font, VSCode in browser, and more"]
draft = false
slug = "241"
tags = ["cloud", "Cloud Native", "Kubernetes", "DevOps", "newsletter", "open source", "data", "WebAssembly", "SiFive", "RISC-V", "KubeCon", "AWS", "distributed", "Apple", "tracing", "CPU", "eBPF", "FCC", "go generics", "Honeycomb", "CNCF", "coding fonts", "multicluster", "cilium", ""]
title = "DevOps'ish 241: REvil roasted, exfil with eBPF, stop your standups, find your coding font, VSCode in browser, and more"

+++

**Happy Halloween 🎃💀👻**

I started my new role as a [Senior Developer Advocate on the AWS Kubernetes team](https://chrisshort.net/joining-amazon-elastic-kubernetes-service-team/) this week. Working for the second largest employer in the United States and the #1 cloud in the world is an extremely interesting dynamic. I'm adapting slowly but surely to the scale. It has a surprisingly familiar feel. I guess that's what happens when one of your friends brings you in. But, I also have so many friends at AWS and Amazon too. It's not like the Kubernetes world is that big to begin with. Tech isn't that much bigger. But, it's nice someone you met in 2017, another person you met in 2018, and on and on is DM'ing you welcome messages throughout the week. I genuinely feel appreciated. It's an odd feeling; I don't think I've ever felt to this extent. I have a very real feeling of belonging. Also, Max turned six this weekend. It's been a really good week. I hope your upcoming week is awesome!

NOTE: [Alison Dowdney](https://www.linkedin.com/in/alisondowdney/)) is looking for a new opportunity. She's an absolute powerhouse in the Kubernetes community.

Also, Please take part in this Twitter poll about rebranding the newsletter. I would love your feedback. Feel free to hit reply too.

{{< tweet 1454614581981106182 >}}

## People

[EXCLUSIVE Governments turn tables on ransomware gang REvil by pushing it offline](https://www.reuters.com/technology/exclusive-governments-turn-tables-ransomware-gang-revil-by-pushing-it-offline-2021-10-21/)  
You don't make headlines that many times and not make some incredibly patient and powerful enemies.

[Preventing Data Exfiltration with eBPF](https://goteleport.com/blog/preventing-data-exfiltration-with-ebpf/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish)  
Keep your data protected by developing security policies that target specific processes with eBPF. *SPONSORED*

[Stand-up Meetings Are Dead (and What To Do Instead)](https://www.honeycomb.io/blog/standup-meetings-are-dead/)  
More frequent, asynchronous and synchronous communications are far better. Especially in our newly distributed world.

[Mark Zuckerberg was more involved in decision making at Facebook than he let on](https://www.washingtonpost.com/technology/2021/10/25/mark-zuckerberg-facebook-whistleblower/)  
"The SEC has been asked to probe whether his iron-fisted management style, described in newly released documents and by insiders, led to disastrous outcomes."

[MIT professor Thomas Malone says the future of work is at home](https://www.washingtonpost.com/technology/2021/10/26/thomas-malone-mit-faq-work/)  
"There are many jobs where physical presence is required, of course. But where it isn't, I can't see any reason we'll be returning to a traditional office." The places that can let you work remotely and don't will have a tough time recruiting I'd imagine. The pandemic is a real game changer for how we work, especially in this sector.

[Apple (AAPL) Will Force Unvaccinated Office Workers to Get Tested Daily](https://www.bloomberg.com/news/articles/2021-10-20/apple-will-force-unvaccinated-office-workers-to-get-tested-daily)  
Mark my words, your vaccination status will impact your health insurance coverage soon.

## Process

[American ISPs slammed for spying on their own subscribers](https://www.theregister.com/2021/10/22/ftc_isp_privacy/)  
"Watchdog finds dubious data gathering, illusory solicitations for consent" ([FTC Report](https://www.ftc.gov/system/files/documents/public_statements/1597790/20211021_isp_privacy_6b_statement_of_chair_khan_final.pdf))

[Automated provisioning of Terraform workflows and IaC](https://www.env0.com/why-env0?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
Automated, collaborative remote-run workflows management for cloud deployments on Terraform, Terragrunt and custom flows. env0 offers Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. Get Started for FREE *SPONSORED*

[White House names Jessica Rosenworcel to become first female chair at FCC](https://siliconangle.com/2021/10/26/white-house-names-jessica-rosenworcel-become-first-female-chair-fcc/)
President Biden's choices tilt the balance of the FCC back towards a pro-Net Neutrality stance. I really hope this is on their immediate agenda.

[expectations for generics in Go 1.18](https://groups.google.com/g/golang-dev/c/iuB22_G9Kbo?pli=1)  
A note from Russ Cox. "This mail explains a bit what the inclusion of generics does and does not mean for us and for users."

[Forensic investigation environment strategies in the AWS Cloud](https://aws.amazon.com/blogs/security/forensic-investigation-environment-strategies-in-the-aws-cloud/)  
"When a deviation from your secure baseline occurs, it's crucial to respond and resolve the issue quickly and follow up with a forensic investigation and root cause analysis. Having a preconfigured infrastructure and a practiced plan for using it when there's a deviation from your baseline will help you to extract and analyze the information needed to determine the impact, scope, and root cause of an incident and return to operations confidently."

[Twitter (TWTR) earnings Q3 2021](https://www.cnbc.com/2021/10/26/twitter-reports-third-quarter-revenue-growth-of-37percent-and-says-apple-changes-had-minimal-impact.html)  
Wow... Twitter did good. Meanwhile at Meta...
![Everything is burning](/images/burning.gif)

## Tools

[Cloud Native WebAssembly Applications Are Already Here](https://thenewstack.io/cloud-native-webassembly-applications-are-already-here/)  
"So far in 2021, the Cloud Native Computing Foundation has officially accepted at least three WebAssembly projects, including WasmEdge Runtime, a cloud native WebAssembly runtime, wasmCloud, a WebAssembly application framework, and Krustlet, a tool to run WebAssembly programs in Kubernetes pods, with many more existing CNCF projects starting to adopt WebAssembly."

Honeycomb makes distributed tracing easy to use. Find hidden slowness, detect deeply buried anomalies, and find the right source of issues the first time. [Get started with Honeycomb's](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) distributed tracing and OpenTelemetry–Free! Always bee tracing. *SPONSORED*

[CSS Is Finally Getting If/Else Statements!](https://scribe.rip/css-is-finally-getting-if-else-statements-3fabcec72a1f)  
This sounds insane to me. But, I guess it could be very useful too.

[Coding Font by Typogram – Find Your True Love of Coding Fonts](https://www.codingfont.com/)  
This tool pits two fonts against each other until it finds the one you like best. I'm a Roboto Mono fan apparently.

[Visual Studio Code for Web Browser](https://acloudguru.com/blog/engineering/visual-studio-code-for-web-means-you-can-develop-on-your-ipad)  
From what I hear, it's not quite there yet with the Apple keyboards. But, I'm looking forward to writing this newsletter from my iPad on a plane some day.

[SiFive teases next RISC-V CPU for PCs, servers, mobile](https://www.theregister.com/2021/10/21/sifive_riscv_cpu/)  
There are some really cool chips landing in the market that will make inroads against Intel's dominance. 

[From One to Many: The Road to Multicluster](http://kaslin.rocks/from-one-to-many-the-road-to-multicluster/)  
"This is a blog post version of my KubeCon NA 2021 keynote of the same name. You can check out the recording here!" Kaslin did such an amazing job with this KubeCon talk.

[Kubernetes Multicluster with Kind and Cilium](https://piotrminkowski.com/2021/10/25/kubernetes-multicluster-with-kind-and-cilium/)  
Kick the tires and light the fires on Cilium from your laptop.

[Encrypting Postgres Data at Rest in Kubernetes](https://blog.crunchydata.com/blog/encrypting-postgres-data-at-rest-in-kubernetes)  
I love how Jonathan S. Katz breaks this down and makes it feel almost easy, thanks to the examples.

[Controlling the CPU scheduler with BPF](https://lwn.net/SubscriberLink/873244/170d233eac5dd69c/)  
"Gushchin notes that, at Facebook, the first experiments using these hooks 'look very promising.' By posting the patch set, he hoped to start a conversation on how BPF could be used within the scheduler."

[Stargate Is The Newest Open-Source Digital Audio Workstation](https://www.phoronix.com/scan.php?page=news_item&px=Stargate-DAW)  
"Stargate is an open-source digital audio workstation with an aim to provide 'everything you need to make music on a computer.' The free software project aims for a 'unique and carefully curated experience,' function on older hardware while scaling to today's modern multi-core systems, provide robust stability, and work across the vast open-source/Linux ecosystem."

[gautamkrishnar/nothing-private](https://github.com/gautamkrishnar/nothing-private#readme)  
Do you think you are safe using private browsing or incognito mode?. This will prove that you're wrong.

## DevOps'ish Tweet of the Week

[![GitHub @github on Twitter) "What is DevOps? @editingemily gives us the skinny at #GitHubUniverse. You dig? http://GitHubUniverse.com](/images/241-devopsish-tweet-of-the-week.webp)](https://twitter.com/github/status/1453760137005518848)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/241/notes/) to see what didn't make it to the newsletter but are still worth your time.
