+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-06-04T05:21:58.049Z
description = ""
draft = false
slug = "026"
tags = ["devops", "cloud native", "open source", "kubernetes", "infrastructure", "detroit", "linux", "microservices"]
title = "026: Week of 1496548800"
image = "/026/open-organization-guide-to-it-culture-change.png"
imagealt = "#TheOpenOrg + #Agile + #DevOps = The Open Organization Guide to IT Culture Change"
aliases = [
    "devopsish-026-week-of-1496548800-93fe8fbfa088"
]

+++

It was a very busy week for me personally and in the world of [DevOps](https://devopsish.com/). The [news I hinted at last week](/025/) is my public announcement [I'm leaving SolarWinds MSP, moving to Detroit, and taking the role of Manager, Infrastructure & Operations at Bankrate](https://chrisshort.net/leaving-north-carolina/). I am beyond excited about the position and the work I will be doing. If you want the job I'm vacating, [apply with SolarWinds](http://solarwinds.jobs/durham-nc-nc/senior-aws-systems-engineer/C28A5E389CEE4983B580F6CD0B3799DB/job/).

Not to downplay its significance, but, The Open Organization released its latest book, [*The Open Organization Guide to IT Culture Change*](https://opensource.com/open-organization/resources/culture-change?sc_cid=7016000000127L3AAI) this week. The book as a whole is [a feat of open source community](https://opensource.com/open-organization/17/6/working-open-and-gsd) in and of itself. It is a quality piece of work based off what I read during the open editing process. I'm still trying to read through it between working, packing, staging, and sleeping. I was very fortunate to have been able to contribute to this book. It's a free download and if you want a physical copy it will be available soon in print! Also, if you want to convert the ODT to an ePub [we are accepting pull requests](https://github.com/open-organization-ambassadors/open-org-it-culture/issues/36) (my eyes will thank you).

{{< mc >}}

## Department of Data Defense

[There is/was a super gnarly bug in sudo allowing root access to any user with a shell account](https://www.cyberciti.biz/security/linux-security-alert-bug-in-sudos-get_process_ttyname-cve-2017-1000367/). The [full details are insightful](http://www.openwall.com/lists/oss-security/2017/05/30/16) but, patch, patch, patch!!!

British Airways had quite the debacle. Apparently, [a human error took down all BA flights](http://www.independent.co.uk/news/business/news/british-airways-system-outage-it-worker-power-supply-switch-off-accident-flights-delayed-cancelled-a7768581.html) in and out of their primary hubs. Don't worry, [BA doesn't think of themselves as a technology company so their CEO is staying put](https://www.theguardian.com/business/2017/may/29/british-airways-ceo-will-not-resign-despite-catastrophic-it-failure). This is either blameless culture or incompetence. Where do we draw the line? Does blameless culture go all the way up to the CEO when we strand passengers in airports past their visas?

## Department of Choice Concepts

[Going open-source in monitoring, part I: Deploying Prometheus and Grafana to Kubernetes](https://medium.com/@SergeyNuzhdin/going-open-source-in-monitoring-part-i-deploying-prometheus-and-grafana-to-kubernetes-e3d44460cec6)

[base65536: Unicode's answer to Base64](https://github.com/qntm/base65536)

[Managing microservices with the Istio service mesh](http://blog.kubernetes.io/2017/05/managing-microservices-with-istio-service-mesh.html)

If you somehow think [DevOps](https://devopsish.com/) is still a fad allow me to point out the [June 2017 Hacker News "Who is hiring"](https://news.ycombinator.com/item?id=14460777) has 97 mentions of DevOps.

[gonvim](https://github.com/dzhou121/gonvim) looks really cool.

DNS is everything. I love DNS and DNS hates me back and that's totally okay. But to read [how GitHub re-architected their DNS infrastructure](https://githubengineering.com/dns-infrastructure-at-github/) made me oddly happy. Total nerd out on this one.

[HTTP/2 push is tougher than I thought](https://jakearchibald.com/2017/h2-push-tougher-than-i-thought/): No shit?

## Department of Discussion

[DevOps and the Key to High Performance: Nicole Forsgren at the DevOps Enterprise Summit London](https://www.infoq.com/news/2017/05/forsgren-devops-performance)

I still want to be either Jess Frazelle or Kelsey Hightower when I grow up. Probably more Jess right now after seeing her [Container Linux on the Desktop](https://docs.google.com/presentation/d/17Hml1iFqdXElxOcrh9caQSC5px5mDgaS015Vhaz42ZY/edit#slide=id.p) slides.

## Department of Happy Clouds

[Free tools for auditing the security of an AWS account](https://summitroute.com/blog/2017/05/30/free_tools_for_auditing_the_security_of_an_aws_account/) is a must read.

Damn it! [Who let Oracle discover Kubernetes?!?](https://blogs.oracle.com/developers/kubernetes-community-engagement-time-to-roll)

## Department of Refreshment and Refurbishment

[Pritunl 1.28 was released this week](https://medium.com/@pritunl/pritunl-1-28-release-announcement-5e02c519d8ab). This fixed an odd issue I was having with licensing. Not sure if that was unique to this fix but it was nice to not have to open a support request. There's other awesome stuff in this release too.

Hot on the heels of 3.6, [Alpine Linux 3.6.1 has been released](https://alpinelinux.org/posts/Alpine-3.6.1-released.html) patching quite a few CVEs.

[Ansible 2.3.1 and 2.1.6 FINAL have been released!](https://groups.google.com/forum/#!topic/ansible-announce/i3hsJKuVusQ)