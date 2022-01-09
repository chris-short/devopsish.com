+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-01-09T07:00:00Z
description = [""]
draft = false
slug = "251"
tags = []
title = "DevOps'ish 251: "

+++

I wrote a really good introduction last week and forgot to include it in the email newsletter. It is [still on the site](https://devopsish.com/250/) if you'd like to go back and look at it. The three big takeaways are:

1. My traditional end of year blog post is out (as of today): [2021 Learnings, 2022 Expectations](https://chrisshort.net/2021-learnings-2022-expectations/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251). I put a lot of time, effort, and thought into it. I hope it's coherent enough so that you can plot a course in 2022.
1. [DevOps'ish.com](https://devopsish.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251) has been completely redesigned from the ground up to provide a better reading experience. A sorely missing and [incredibly helpful search capability](https://devopsish.com/search/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251) has been added to the site.
1. [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) will be the *sole* sponsor of DevOps'ish in 2022 and I'm very excited about that.

Last week's issue might have been one of the worst performing ones of the year. The lack of an intro left folks wanting more. Next year (2023), I'll plan better and not push out newsletters during significant lulls in internet activity. Plus, I can plan to take a break every once in a while (this isn't a marathon; it's a newsletter).

This week saw 5G rollout over the C-band spectrum on a seesaw after [AT&T and Verizon rejected the FAA's pleas](https://arstechnica.com/tech-policy/2022/01/at-airlines-threaten-mass-flight-cancelations/), then accepted [a two-week delay](https://www.cnet.com/tech/mobile/verizon-at-t-agree-to-faas-request-for-a-two-week-delay-on-5g-expansion-plans/) a day after [rebuffing the FAA](https://www.axios.com/5g-aviation-verizon-att-cband-delay-39184f3f-44db-4134-88a0-6e25c6bea274.html) in a deal [brokered by the White House](https://www.whitehouse.gov/briefing-room/statements-releases/2022/01/04/statement-by-president-joe-biden-on-5g-deployment-agreement/). The FAA also agreed not to ask for more delays which paints them into quite a corner. I'm watching this closely because 5G is a bad pun here in the US, and it really shouldn't be.

## People

[Intel Poaches Apple Engineer Responsible for Arm Transition and M1 Chips](https://www.tomshardware.com/news/intel-poaches-apple-engineer-responsible-for-arm-transition-and-m1-chips)  
"This latest Intel hire is but one of many that the company has embarked upon since CEO Pat Gelsinger took the reins at the company. Under the Intel chief's guidance, the company has made multiple hires from competitors AMD, Nvidia and Apple, with particular focus on the graphics segment as it gears up for launch of its Xe high performance graphics architecture. At the same time, Intel has boosted its compensation structure with a $2.4 billion investment focused on attracting new talent."

[The internet runs on free open-source software. Who pays to fix it?](https://www.technologyreview.com/2021/12/17/1042692/log4j-internet-open-source-hacking/)  
"Volunteer-run projects like Log4J keep the internet running. The result is unsustainable burnout, and a national security risk when they go wrong."

[The anti-muslim Bulli Bai app is just the latest in GitHub's list of moderation failures in India](https://restofworld.org/2022/why-anti-muslim-apps-keep-reappearing-on-github/)  
"Many of the women targeted on Bulli Bai are outspoken critics of Hindu nationalism and have criticized Prime Minister Narendra Modi's handling of religious minorities in the country. The list included journalist Ismat Ara and veteran activist Khalida Parveen, among others."

[Diversity Tech Job Board Guidelines](https://www.diversifytech.co/job-board-guidelines/)  
"[Whiteboard/live coding interviews](https://news.ncsu.edu/2020/07/tech-job-interviews-anxiety/) assess anxiety not coding skills. If you do whiteboard interviewing, we are not the right fit for you." This whole thing is a breath of fresh air.

[The Danger of Leaving Weather Prediction to AI](https://www.wired.com/story/weather-forecasting-artifical-intelligence/)  
"When it comes to forecasting the elements, many seem ready to welcome the machine. But humans still outperform the algorithms—especially in bad conditions."

## Process

[Kubernetes is Moving on From Dockershim: Commitments and Next Steps](https://kubernetes.io/blog/2022/01/07/kubernetes-is-moving-on-from-dockershim/)  
If you use [Docker Engine as a Container Runtime](https://kubernetes.io/docs/tasks/administer-cluster/migrating-from-dockershim/find-out-runtime-you-use/) for your Kubernetes cluster, get ready to migrate to 1.24! To check if you're affected, refer to [Check whether dockershim deprecation affects you](https://kubernetes.io/docs/tasks/administer-cluster/migrating-from-dockershim/check-if-dockershim-deprecation-affects-you/). If you have more questions about the dockershim removal, refer to the [Dockershim Deprecation FAQ](https://kubernetes.io/dockershim). This is still happening, folks, more of you are impacted than you realize it seems. More tooling is coming to help but, please check. Trust but verify.

[FTC warns companies to remediate Log4j security vulnerability](https://www.ftc.gov/news-events/blogs/techftc/2022/01/ftc-warns-companies-remediate-log4j-security-vulnerability)  
"The Log4j vulnerability is part of a broader set of structural issues. It is one of thousands of unheralded but critically important open-source services that are used across a near-innumerable variety of internet companies. These projects are often created and maintained by volunteers, who don't always have adequate resources and personnel for incident response and proactive maintenance even as their projects are critical to the internet economy. This overall dynamic is something the FTC will consider as we work to address the root issues that endanger user security."

[IBM tries to sell Watson Health again](https://www.axios.com/ibm-tries-to-sell-watson-health-again-82f691a4-ab81-4b2b-a5bb-13a7556c8ef1.html)  
I laughed out loud scrolling past this headline on the couch the other night. Watson Health is hogwash. IBM has taken write-downs on most of the businesses that it acquired to build Watson Health.

[GitOpsCon EU 2022 Call For Proposals (CFP) are Open](https://events.linuxfoundation.org/gitopscon-europe/program/cfp/)  
Get those CFPs in folks. The sooner the better!

[community/SIG-diagram.png · kubernetes/community](https://github.com/kubernetes/community/blob/master/SIG-diagram.png)  
Remember, if you ever forget how the Kubernetes world is organized, there's a diagram.

## Tools

[Brave Passes 50 Million Monthly Active Users, Growing 2x for the Fifth Year in a Row](https://brave.com/2021-recap/)  
I made the switch to Brave this year (yes, I know it has some flaws, but it's better than Chrome). As I mentioned in my [2021 Learnings, 2022 Expectations](https://chrisshort.net/2021-learnings-2022-expectations/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251&utm_term=privacy), [privacy](https://chrisshort.net/2021-learnings-2022-expectations/#privacy?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251&utm_term=privacy) had a big year.

[EKS News 000](https://buttondown.email/eks.news/archive/eks-news-000/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=251)  
"Welcome to the first ever issue of [EKS News](https://eks.news/?utm_source=eks.news&utm_medium=email&utm_campaign=eks-news-000)!"

[Updating kube-oidc-proxy](https://www.tremolosecurity.com/post/updating-kube-oidc-proxy)  
"TL;DR: Updated dependencies and Go version, Added better logs for integrating with SIEM, Added kubectl --as support, Moved from Alpine to Ubuntu, Automating rebuilds" This post was very popular this week.

[Amazon Elastic Kubernetes Service Adds IPv6 Networking](https://aws.amazon.com/blogs/aws/amazon-elastic-kubernetes-service-adds-ipv6-networking/)  
Slap IPv6 on your EKS clusters at will.

[New maintainers · Discussion #927 · mozilla/sops](https://github.com/mozilla/sops/discussions/927)  
A discussion that looks pretty bad for the future of `sops`.

[Fluentd v1.14.4 has been released](https://www.fluentd.org/blog/fluentd-v1.14.4-has-been-released)  
Oh, "`in_tail` supports a new option `max_line_size` that allows to skip lines above a certain size."

[The HTTP QUERY Method](https://www.ietf.org/archive/id/draft-ietf-httpbis-safe-method-w-body-02.html)  
"This specification defines a new HTTP method, QUERY, as a safe, idempotent request method that can carry request content." Early draft stage but, never to early to read about new HTTP requests.

[Cleaning up the Linux kernel's 'Dependency Hell': This developer is proposing 2,200 commit changes](https://www.zdnet.com/article/cleaning-up-the-linux-kernels-dependency-hell-this-developer-is-proposing-2200-commit-changes/)  
"Cleaning off decades of code mess isn't for the faint of heart, but leading Linux kernel developer Ingo Molnar is giving it the old college try in the open-source Linux kernel."

[The JED Programmer's Editor](https://www.jedsoft.org/jed/index.html)  
[Jeff Barr](https://twitter.com/jeffbarr) said something on Twitter this week and it reminded me of the editor I used when I first started using Linux in the 1990s: JED.

[Latest web hacking tools – Q1 2022](https://portswigger.net/daily-swig/latest-web-hacking-tools-q1-2022)  
With great power comes great responsibility. Don't be an asshole with these tools. If you do, I will find your mother and tell her what you did.

[solo-io/bumblebee](https://github.com/solo-io/bumblebee)  
Get eBPF programs running from the cloud to the kernel in 1 line of bash

[defenseunicorns/zarf](https://github.com/defenseunicorns/zarf)  
K8s Airgap Buddy

[mittwald/kubernetes-replicator](https://github.com/mittwald/kubernetes-replicator)  
Kubernetes controller for synchronizing secrets & config maps across namespaces

## DevOps'ish Tweet of the Week

{{< tweet 1479643564728532993 >}}

[![KEATS 🚀 (@keatsdidit on Twitter) "How social media apps been acting recently"](https://devopsish.com/images/251-devopsish-tweet-of-the-week.webp)](https://twitter.com/keatsdidit/status/1479643564728532993)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/251/notes/) to see what didn't make it to the newsletter but are still worth your time.
