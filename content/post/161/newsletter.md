+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2020"]
date = 2020-01-06T07:00:00Z
description = ""
draft = false
slug = "161"
tags = ["automation imagination", "DevOps", "Kubernetes", "open source", "Y2K", "DENT", "Python", "DENT", "Apache Pulsar", "AWS", "automation", "webassembly", "RDS", "cloud", "developers", "software", "code", "google", "cloud native", "faasd", "network", "Linux", "anxiety", "GitHub", "GitHub Actions", "security", "CNCF", "community", "development", "operations", "UPS", "CI/CD", "certificates"]
title = "161: Getting you back in the groove, hello 2020, anxiety, Y2K, AWS RDS certificates, faasd, Apache Pulsar, DENT, WebAssembly, and more"

+++

Let's begin the new year with the top ten stories from the past three issues of DevOps'ish to get you up to speed on what you might have missed while you were off lollygagging:

1. [5 interview questions every Kubernetes job candidate should know](https://opensource.com/article/19/12/kubernetes-interview-questions)
1. [How to actually get good at basic DevOps if i'm not already hired /r/devops](https://www.reddit.com/r/devops/comments/e9nl05/how_to_actually_get_good_at_basic_devops_if_im/)
1. [RDS Pricing Has More Than Doubled (Medium)](https://medium.com/@rbranson/rds-pricing-has-more-than-doubled-ef8c3b7e5218) (please [build your own blog](https://nomedium.dev/) in 2020)
1. [Kubernetes is booming, but consolidation is coming](https://www.zdnet.com/article/kubernetes-is-booming-but-consolidation-is-coming/)
1. [SSH to remote hosts though a proxy or bastion with ProxyJump](https://www.redhat.com/sysadmin/ssh-proxy-bastion-proxyjump)
1. [10 best sysadmin stories from the trenches](https://www.redhat.com/sysadmin/stories-trenches)
1. [The top 15 emerging jobs of 2020, according to LinkedIn](https://qz.com/work/1764751/the-top-15-emerging-jobs-of-2020-according-to-linkedin/)
1. [Building Compassion - YouTube](https://www.youtube.com/watch?v=X6qOweQtqTg)
1. [Operations Anti-Patterns: DevOps Solutions](https://www.manning.com/books/operations-anti-patterns-devops-solutions)
1. [Top CI/CD resources to set you up for success](https://opensource.com/article/19/12/cicd-resources)

A [CSV](/csv/devopsish-2020-new-year-catch-up.csv) is available with all the links sorted by total clicks if you want to get completely up to speed.

Thank you to each and every one of you. The fact you subscribe to something I write and hopefully gain something from fuels my fire. In 2020, expect some changes, like always, as DevOps'ish is iterated on more and more. I hope to continue to provide the right information, to the right people at the right time. I have a question for all DevOps'ish readers though. If I were to choose a charity to donate a portion of all proceeds from sponsorships to, what would it be? Please [use this form to make a suggestion](https://devopsi.sh/charity_suggest?utm_source=devopsish&utm_medium=email&utm_campaign=161). Thank you very much!

[**Sponsor DevOps'ish**](https://devopsi.sh/prospectus?utm_source=devopsish&utm_medium=email&utm_campaign=161)  
The cost of maintaining this newsletter and the associated social media streams is not zero. At the very least it is an enourmous investment of time. Sponsoring DevOps'ish provides brand recognition and engagement from readers across the globe. The native ad format makes sure your message gets seen. Read the [prospectus](https://devopsi.sh/prospectus?utm_source=devopsish&utm_medium=email&utm_campaign=161) then email me at [chris@devopsish.com](mailto:chris@devopsish.com) to get started today!

## Events

[Security at Cloud Native Speed (webinar)](https://security.stackrox.com/2020_01SecurityatCloudNativeSpeedWebinar_200Registration.html)  
Online  
January 9, 2020, 11:00 am PT | 2:00 pm ET  
Join our live discussion to get your questions answered on how to improve security and reduce your blast radius while increasing velocity in cloud-native environments. Our speaker, Chris Short, draws on his experience as a principal technical marketing manager for Red Hat, CNCF Ambassador, and editor of KubeWeekly and DevOps'ish to share best practices on applying gates during CI/CD, the critical features for container security, tapping the power of native controls in Kubernetes, leveraging automation to retain velocity.

[DeliveryConf](https://www.deliveryconf.com/)  
Seattle, WA  
January 21-22, 2020  
DELIVERY|CONF 2020 is being held to give people a place to get deeper technical information about Continuous Integration (CI) and Continuous Delivery (CD). Our goal isn't to just tell you to "do the technical thing"; it is to show you real world examples of how others have done it. DELIVERY|CONF 2020 is a not-for-profit event being created by an all-volunteer team with many years of experience both in the technology and with creating conferences.

[Hacking With The Homies Developers Conference Ticket](https://www.eventbrite.com/e/hacking-with-the-homies-developers-conference-tickets-83203845943)  
Detroit, MI  
Feb 29, 2020  
This is the first Software Developer Conference with a 100% focus on Black and Brown software developers. All sessions will be led by developers and will contain an actual code walk-thru. All presenters have a 3 slide limit and everything else has to be code. We have a Happy Hour after the conference where you can network and mingle with other developers. The profits from the conference will go to funding Detroit Black Tech initiatives and events.

## People

[![xkcd: I Love the 20s](https://imgs.xkcd.com/comics/i_love_the_20s.png)](https://xkcd.com/2249/)

[2019 Learnings, 2020 Expectations by Chris Short](https://chrisshort.net/2019-learnings-2020-expectations/) — I call out GitOps and WebAssembly as two things I expect to see more of in 2020. There is a lot more there though that will spark some ideas. There are even more predictions about 2020 in this newsletter too.

[‘Rude’ peer reviews inflict most damage on women and minorities](https://www.timeshighereducation.com/news/rude-peer-reviews-inflict-most-damage-women-and-minorities) — Don't be a dick during peer reviews. Honest feedback only. No jockeying, no posturing.

[Our top 10 articles of 2019 for IT leaders](https://enterprisersproject.com/article/2019/12/our-top-10-articles-2019-it-leaders) — "Our readers found these articles - on robotic process automation (RPA), Kubernetes, emotional intelligence, agile, and more - the most valuable. Dig in for IT leadership wisdom to start the new year" Note the schism between IT leadership content and this newsletter's content. What is broken there?

[Internet shutdowns used to be rare. They're increasingly becoming the norm](https://www.cnn.com/2019/12/21/asia/internet-shutdowns-china-india-censorship-intl-hnk/index.html) — Openness wins every time. The problem is, you can't have too many secrets and be open. Governments are going to have to figure that out or we'll see more shutdowns in the years to come.

[Hyperscaler Infrastructure for the Masses with Jessie Frazelle, Steve Tuck, and Bryan Cantrill of Oxide Computing](https://share.transistor.fm/s/f527fc61) — Corey Quinn sits down with the folks at Oxide Computing to discuss the problem they are solving that no one else is.

[My 2020 resolution: Pay for news!](https://www.keithrozario.com/2020/01/2020-resolution-pay-for-news.html) — I think it is vitally important to pay for news to keep journalism thriving and but, more importantly, honest. I pay for WaPo, NYT, HBR, LWN, Wired, and I'm likely forgetting many others. This is the citizenry's last gaurd against corruption and ruin. But, it's also fuel and context for newsletters like DevOps'ish and many others.

[Google veterans: The company has become 'unrecognizable'](https://www.cnbc.com/2019/12/31/google-veterans-the-company-has-become-unrecognizable.html) — I would work at Google under the right circumstances. I'm sure some parts of the business are operating like the Google we all fondly remember.

[How Anxiety Traps Us, and How We Can Break Free](https://hbr.org/2020/01/how-anxiety-traps-us-and-how-we-can-break-free)

## Process

[20 Years Since Y2K: The Evolution of IT Operations and DevOps](https://www.transposit.com/blog/2019.12.30-20-years-since-y2k-evolution-of-it-operations-and-devops/) — "A comparison of IT operations tooling at the time of Y2K versus the DevOps tooling we have today"

[Google's Formula for Elite DevOps Performance](https://thenewstack.io/googles-formula-for-elite-devops-performance/)

[Amazon RDS customers: Update your SSL/TLS certificates by February 5, 2020](https://aws.amazon.com/blogs/database/amazon-rds-customers-update-your-ssl-tls-certificates-by-february-5-2020/) — This seems really important to get done sooner rather than later.

[What happens if the Air Force’s command center for all its tankers and cargo planes gets hacked?](https://www.c4isrnet.com/air/2019/12/27/what-happens-if-the-air-forces-command-center-for-all-its-tankers-and-cargo-planes-gets-hacked/) — Been there, done that, already got rid of the t-shirt. But, it is awesome to see folks talking about this more openly.

[8 must-read DevOps articles for success in 2020](https://opensource.com/article/19/12/devops-resources) — "Get up to speed on DevOps with [opensource.com's] eight most popular DevOps articles [in 2019]."

[Network Automation and the Lack of Innovation in the Management Plane](https://thenewstack.io/network-automation-and-the-lack-of-innovation-in-the-management-plane/) — This touches on the lack of "*Automation Imagination™️*" that humans inherrently lack or hesitate to implement. It's okay to automate things. The best employers will keep giving you things to automate.

[VMware completes $2.7 billion Pivotal acquisition](https://techcrunch.com/2019/12/30/vmware-completes-2-7-billion-pivotal-acquisition/) — I met some disgruntled Pivotal folks throughout the end of 2019. With the acquisition now complete. What happens with VMware becomes even more interesting. Pivotal (the company) cannot be seen as a win in my eyes (much like Docker (the company)).

## Tools

[alexellis/faasd](https://github.com/alexellis/faasd) — faasd - serverless with containerd 🐳

[Python Software Foundation: Press Release 20-Dec-2019](https://www.python.org/psf/press-release/pr20191220/) — "The CPython core developer community is retiring the Python 2 series after nearly 20 years of development. The last major version 2.7 will be released in April 2020, and then all development will cease for Python 2." Python 2 is effectively dead. Serious question: If you haven't managed to move to Python 3, what's the hold up?

[Apache Pulsar](https://pulsar.apache.org/) — Apache Pulsar is an open-source distributed pub-sub messaging system originally created at Yahoo and now part of the Apache Software Foundation

[DENT](https://dent.dev/) — "As a new Linux Foundation project, DENT will utilize the Linux Kernel, Switchdev, and other Linux based projects as the basis for building a new standardized network operating system without abstractions or overhead. All underlying infrastructure — including ASIC and Silicon for networking and datapath — will be treated equally; while existing abstractions, APIs, drivers, low-level overhead, and other open software will be simplified. DENT will unite silicon vendors, ODMs, SIs, OEMs, and end users across all verticals and enable the transition to disaggregated networks." Interesting news for network folks.

[Can Embedded Clustering Kill Kubernetes?](https://www.titanoboa.io/cluster.html) — Perhaps pulling the pieces of Kubernetes that are actually needed directly into your code base is a better approach. It isn't practical today but, I could see a future where a component of K8s is embedded in the app as opposed to the cluster itself. It's an interesting thought piece at the very least.

[Grafana Series Part 2: Monitoring a UPS with Grafana on Linux](https://blog.linuxserver.io/2018/11/15/monitoring-a-ups-with-grafana-on-linux/) — A faulty UPS ever bite you? I've had them blow up in my face before. Sure is nice to have UPS metrics so that you can find anomolous ones.

[aws/jsii](https://github.com/aws/jsii) — "jsii allows code in any language to naturally interact with JavaScript classes. It is the technology that enables the AWS Cloud Development Kit to deliver polyglot libraries from a single codebase!"

[WebAssembly 2019 Year In Review](https://blog.scottlogic.com/2019/12/24/webassembly-2019.html) — Being able to run your C, Rust, or other code in the browser is going to open up a world of possibilities for applications and services.

[A tutorial on Github Actions](https://www.pixelstech.net/article/1577096152-A-tutorial-on-Github-Actions) — GitHub Actions will become a de facto CI/CD tool in 2020 simply because it's available. My blog stack uses GitHub and GitLab for CI and backups. I doubt I'll change that any time soon. But, GitHub Actions are ceratinly something I'm learning in 2020.

[bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) — Prevent cloud misconfigurations during build time.

[ahmetb/kubectl-tree](https://github.com/ahmetb/kubectl-tree) — `kubectl` plugin to browse Kubernetes object hierarchies as a tree 🎄 (using? star the repo!)

[rq/rq](https://github.com/rq/rq) — Simple job queues for Python

[imsnif/bandwhich](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool (formerly known as "what")

[gchq/stroom](https://github.com/gchq/stroom) — Stroom is a highly scalable data storage, processing and analysis platform.

## DevOps'ish Tweets of the Week

{{< tweet 1211999070350299138 >}}
