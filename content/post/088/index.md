+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2018-08-12T07:00:00Z
description ="Survey Results, Kubernetes, Prometheus Graduates 🎓, Blue Light is Bad, CI/CD, Ethics, kubespray, and More!"
draft = false
slug = "088"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "ansible", "survey results", "cicd", "ethics", "prometheus", "kubespray"]
title = "088: Survey Results, Kubernetes, Prometheus Graduates 🎓, Blue Light is Bad, CI/CD, Ethics, kubespray, and More!"

+++

If you participated in the DevOps'ish Summer 2018 Survey, thank you. It was vital to make sure I was putting bits in the right places. The [aggregate results are available](https://docs.google.com/forms/d/1XRAHLduV_ssmPPP_CB_Pbw33LMeaurOfOTEsFDoppkQ/viewanalytics). A few changes you might have noticed last week; [Events](/events/) and [Jobs](/jobs/) now live as pages on the website. While they add value, they also added unnecessary weight to every newsletter. The benefit of them being pages now either of them can be updated as new listings come in. The offer still stands for readers getting their listings on the site for free.

The next cut was the photo header. I thought it was a beautiful thing to add back in 2016. It humanized the newsletter in a way words couldn't. But, the metrics have spoken. With 62 respondents (out of 90) rating it a 5 or less, it was probably past time to pull it. The introduction is staying. Sorry (not sorry) for those of you who think it's too political at times. But, DevOps is about breaking down silos in organizations and I'm about breaking them down in life. Aside from that, not much else is changing.

The newsletter cracked 2,000 this week! Thanks for reading! Tell your friends to subscribe today. [Drop a link](/subscribe/) in your company Slack when you have a moment. I'd like to do some big things in 2019 that will require capital. [Mo' subscriber's, mo' money.](/sponsor/) —Notorious B.I.G. (or someone like that).

[**Blog Series: Continuous Delivery of Microservices - Parts 1 - 5**](https://www.gocd.org/tags/cd-for-microservices.html)  
This blog series from Sheroy Marker cover the principles of CD of microservices. Get a practical guide on designing CD workflows for microservices, testing strategies, trunk based development, feature toggles and environment plans. *SPONSORED*

[**What's Kubernetes Doing? Datadog Knows, So You Can Too!**](https://www.datadoghq.com/monitor-kubernetes/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterKubernetes)  
Get real-time metrics from Docker and Kubernetes with Datadog. Visualize the performance of your entire container infrastructure at a glance and investigate issues quickly. [Start your free Datadog trial today](https://www.datadoghq.com/monitor-kubernetes/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-NewsletterKubernetes) *SPONSORED*


## People

[Chemists discover how blue light speeds blindness](https://phys.org/news/2018-08-chemists-blue.html): Time to get some blue filter computer glasses.

[The Importance of Psychological Safety](https://chrisshort.net/the-importance-of-psychological-safety/): I have mentioned this a few times in various talks, on social media, and in this newsletter; the importance of psychological safety in creating effective teams is often overlooked.

[CNCF Ambassadors](https://twitter.com/rothgar/lists/cncf-ambassadors/members): A special thanks to Justin Garrison for putting together this list of CNCF Ambassadors on Twitter. Follow 'em all!

[Hackers can cook you alive using 'microwave oven' sat-comms – claim](https://www.theregister.co.uk/2018/08/10/satellite_communications_microwave_oven_hacking/): Planes, ships, military equipment at risk due to backdoors, vulns

[Passed the CKA after failing it twice AMAA](https://www.reddit.com/r/kubernetes/comments/95k033/passed_the_cka_after_failing_it_twice_amaa/): /u/mrcrassic on reddit passed the Certified Kubernetes Administrator (CKA). CONGRATS! Then mrcrassic, launched a small AMA.

[The Big Company and What's Next](https://medium.com/@jaydestro/the-big-company-and-whats-next-459cd6bcea8d): My friend, Jay Gordon, formerly of MongoDB is joining Microsoft as a Senior Cloud Ops Advocate. Congrats to, Jay! That's awesome and I'm very happy for him!

[DevOps lessons learned: What I wish I knew sooner](https://enterprisersproject.com/article/2018/8/devops-lessons-learned-what-i-wish-i-knew-sooner?page=1): Eight DevOps veterans share the one thing they wish they'd learned earlier in their careers. Apply their wisdom to your work.

[The Obscene Coupling Known as Spaghetti Code](https://queue.acm.org/detail.cfm?ref=rss&id=3265943): Teach your junior programmers how to read code

## Process

[How to Win at Cloud Native Migrations](https://blog.tidalmigrations.com/how-to-win-at-cloud-native-migrations-ab68abff4671): Start small, hit low hanging fruit first, and then expand.

[Unit testing anti-patterns: Structural Inspection](https://enterprisecraftsmanship.com/2016/07/21/unit-testing-anti-patterns-structural-inspection/): "This post is about the practice of Structural Inspection in unit testing and why I personally consider it an anti-pattern."

[VMware To Acquire Dell EMC Service Assurance Suite - Quick Facts](https://www.nasdaq.com/article/vmware-to-acquire-dell-emc-service-assurance-suite--quick-facts-20180809-01292)

[What is CI/CD?](https://opensource.com/article/18/8/what-cicd): Continuous integration (CI) and continuous delivery (CD) are extremely common terms in software production. But do you know what they really mean?

[How an infrastructure team starts using CI/CD](https://opensource.com/article/18/7/infrastructure-team-starts-using-ci-cd): Using dev test methods in the ops environment may catch potential infrastructure issues before they become problems.

[gobuffalo/shoulders](https://github.com/gobuffalo/shoulders): "This tool will create a custom SHOULDERS.md file for any given Go project allowing OSS maintainers to recognize those who's OSS contributions helped them."

[5 reasons IT struggles to innovate and keep core business systems running](https://www.techrepublic.com/article/5-reasons-it-struggles-to-innovate-and-keep-core-business-systems-running/):
The expanding role that business leaders expect from IT comes with many challenges, according to an Insight Enterprises report.

[How to turn DevOps fakers into believers](https://enterprisersproject.com/article/2018/8/how-turn-devops-fakers-believers): Are some of your people quietly hanging on to their old ways? Here's how to get them on board with a culture of continuous improvement

[Feeling the Heat of High-Frequency Trading](https://hackaday.com/2018/08/06/feeling-the-heat-of-high-frequency-trading/): I once set a tree on fire with a point-to-point microwave radio antenna like those mentioned in this article.

[Prometheus Graduates Within CNCF](https://prometheus.io/blog/2018/08/09/prometheus-graduates-within-cncf/): Prometheus graduates within the CNCF. Recall [DevOps'ish 066](/066/) when Kubernetes graduated, "[Graduation] is meant to be a stamp from the Technical Oversight Committee and the CNCF of what is a sustainable, production ready and mature open source project (i.e., you can bet your business on it)."

[MailChimp bans Alex Jones for hateful conduct](https://techcrunch.com/2018/08/07/mailchimp-bans-alex-jones-for-hateful-conduct/): DevOps'ish uses MailChimp and will continue to do so. This Alex Jones nonsense is NOT a free speech issue. These platforms are not run by the US government. They can silence whomever they wish for the health of their platforms.

[Cultural Bias in Artificial Intelligence](https://thenewstack.io/cultural-bias-in-artificial-intelligence/): "Some of the things we've seen are misclassification or misidentification. For example, Microsoft's Tay AI, a bot that was released on Twitter was famously easily influenced by people talking to it in racist and sexist ways, and it reflected that."

[Hacker swipes Snapchat's source code, publishes it on GitHub](https://thenextweb.com/security/2018/08/07/hacker-swipes-snapchats-source-code-publishes-it-on-github/): Oops...

[Satellite Turla: APT Command and Control in the Sky](https://securelist.com/satellite-turla-apt-command-and-control-in-the-sky/72081/): How the Turla operators hijack satellite Internet links

[ACM Code of Ethics and Professional Conduct](https://www.acm.org/code-of-ethics): "Computing professionals' actions change the world. To act responsibly, they should reflect upon the wider impacts of their work, consistently supporting the public good. The ACM Code of Ethics and Professional Conduct ("the Code") expresses the conscience of the profession."

## Tools

[kubespray 2.6.0](https://github.com/kubernetes-incubator/kubespray/releases/tag/v2.6.0) was released this week. [Kubespray](https://github.com/kubernetes-incubator/kubespray) is an awesome project for standing up Kubernetes clusters.

[niieani/bash-oo-framework](https://github.com/niieani/bash-oo-framework): Bash Infinity is a modern boilerplate / framework / standard library for bash

[Git happens! 6 Common Git mistakes and how to fix them](https://about.gitlab.com/2018/08/08/git-happens/): Whether you added the wrong file, committed directly to master, or some other mishap, we've got you covered.

[How To Do Microservices Integration Testing in the Cloud](https://thenewstack.io/how-to-do-microservices-integration-testing-in-the-cloud/): "Matt Swann, CTO at StubHub, said that testing in production is part of his company's daily routine."

[What you need to know about Kubernetes RBAC](https://about.gitlab.com/2018/08/07/understanding-kubernestes-rbac/): Role-based access control is now default, and expected in most Kubernetes deployments. Here's the What, Why and How of RBAC.

[A Detailed Look at RFC 8446 (a.k.a. TLS 1.3)](https://blog.cloudflare.com/rfc-8446-aka-tls-1-3/): " The latest version of TLS, TLS 1.3 (RFC 8446) was published today. It is the first major overhaul of the protocol, bringing significant security and performance improvements."

[How do tools affect culture?](https://opensource.com/article/18/8/how-tools-affect-culture): Here's how to ensure that the tools you select reinforce the values of your organization.

[Additional Record Types Available with Cloudflare DNS](https://blog.cloudflare.com/additional-record-types-available-with-cloudflare-dns/): DNSKEY and DS, coming to a DevOps'ish near you.

[Netflix Cloud Security: Detecting Credential Compromise in AWS](https://medium.com/netflix-techblog/netflix-cloud-security-detecting-credential-compromise-in-aws-9493d6fd373a): "We on the Netflix Security Tools and Operations team want to share a new methodology for detecting temporary security credential use outside of your AWS environment."

[GLB: GitHub's open source load balancer](https://githubengineering.com/glb-director-open-source-load-balancer/): "GLB Director does not replace services like haproxy and nginx, but rather is a layer in front of these services (or any TCP service) that allows them to scale across multiple physical machines without requiring each machine to have unique IP addresses."

[Rook.io: Ceph Persistent Storage Made Easy on Kubernetes](https://www.linkedin.com/pulse/rookio-ceph-persistent-storage-made-easy-kubernetes-gokul-chandra/)

[Kubernetes Tutorials, Resources, and Courses.](https://medium.com/@pavanbelagatti/kubernetes-tutorials-resources-and-courses-d75c0ce56401)

## DevOps'ish Tweet of the Week

{{< tweet 1028142599750578176 >}}
