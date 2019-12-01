+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2017-04-16T06:06:01.283Z
description = ""
draft = false
slug = "019"
tags = ["devops", "cloud native", "open source", "kubernetes", "interview", "Susan Fowler"]
title = "019: Week of 1492315200"
image = "/019/easter-basket.jpg"
imagealt = "Enjoy your Easter!"
aliases = [
    "devopsish-weekly-019-week-of-1492315200-eda43f3abc83"
]

+++

Happy Easter! Hope you are enjoying your [**DevOps**](https://devopsish.com/)'ing selves. I have family in from the northern reaches of the US. Trying to optimize time this week so no "monologue"; let's get it!

## Department of Refreshment and Refurbishment

[Ex-Facebook engineers launch Honeycomb, a new tool for your debugging nightmares](http://www.techrepublic.com/article/ex-facebook-engineers-launch-honeycomb-a-new-tool-for-your-debugging-nightmares/): Friend of [DevOps'ish](https://devopsish.com/), Charity Majors, and her fellow team members have officially launched [Honeycomb.io](https://honeycomb.io/). Honeycomb.io is an impressive product. I ingested a week's worth of nginx logs in seconds and had a beautiful dashboard up in running in as much time as it took to write this sentence. Dope!

[Ansible 2.3 has been released](https://www.redhat.com/en/about/press-releases/red-hat-delivers-advanced-network-automation-latest-version-ansible?sc_cid=7016000000127NJAAY)! This release appears to focus on bringing more advocates into the Ansible fold as it enhances Windows and networking capabilities. I welcome the additional features as a fully unified management platform for all components in an enterprise has never really panned out.

[OpenEBS 0.2 was released this week](https://blog.openebs.io/openebs-sprinting-ahead-0-2-released-28f5001deeaa)

Kelsey Hightower has assembled [an unofficial collection of tutorials and hacks for using Go with Google Cloud Functions](https://github.com/kelseyhightower/google-cloud-functions-go).

## Department of Assemblage Obtainment

Kubernetes tooling firm, [Deis, has been acquired by Microsoft](https://deis.com/blog/2017/deis-to-join-microsoft/). I was not sure how to feel about this (Microsoft does not do open source well, in my experience). CNBC says Microsoft, "[is racing to grab a bigger share of the market as companies rapidly move workloads out of their own data centers and into the cloud.](http://www.cnbc.com/2017/04/10/microsoft-acquires-deis-in-latest-bid-to-catch-aws.html)" I hope this works out for Deis.

## Department of Data Defense

[Your Government's Hacking Tools Are Not Safe](https://motherboard.vice.com/en_us/article/your-governments-hacking-tools-are-not-safe): When governments say they want a backdoor remind them the CIA and NSA had their tools compromised for MONTHS without telling a soul (including the software vendors).

[DNS CAA (Certificate Authority Authorization) records](https://tools.ietf.org/html/rfc6844) are something you need to familiarize yourself with. A CAA record allows domain owners to declare which certificate authorities are allowed to issue a certificate for a domain. [Mattias Geniar states, "As of September 2017, Certificate Authorities are obligated to check for CAA records and honor those preferences."](https://ma.ttias.be/caa-checking-becomes-mandatory-ssltls-certificates/?utm_source=cronweekly.com)

[5 tips for securing your Docker containers](http://www.techrepublic.com/article/5-tips-for-securing-your-docker-containers/)

## Department of Happy Little Clouds

When running your own Kubernetes cluster on Raspberry Pis wouldn't it be cool to have [a visual indicator](https://youtu.be/a7MX6ED2zVM)?

[Vagrant Up Docker, Mesos and Kubernetes with Persistent Storage](https://blog.codedellemc.com/2017/04/12/vagrant-docker-mesos-kubernetes-persistent-storage/)

[Test Driving Docker Function As A Service (FaaS)](https://www.brianchristner.io/test-driving-docker-function-as-a-service-faas/)

## Department of Sane Workplaces

Susan Fowler has landed at Stripe and is doing something very awesome. [Increment](https://increment.com/) looks to be, "a software engineering magazine dedicated to providing *practical and useful insight into what effective teams are doing so that the rest of us can learn from them more quickly*."

[A Seamless Way to Keep Track of Technical Debt in Your Source Code](http://philippe.bourgau.net/a-seamless-way-to-keep-track-of-technical-debt-in-your-source-code/)

[Dave Chaney went full on H.A.M. on Slack and how it is inappropriate for open source communications](https://dave.cheney.net/2017/04/11/why-slack-is-inappropriate-for-open-source-communications). I agree with the sentiment but the problem is the barrier to entry with IRC is just slightly higher than Slack. Slack was released 25 years after IRC came on the scene and it is barely more user friendly. This is a problem that still needs solving in my opinion.

## Department of Interior

As [mentioned last week](/018/), I have been tinkering with macOS monitoring. Not much success in that arena until I looked at one of the Solarwinds' families of products: [Librato](https://www.librato.com/). It's a pretty awesome tool that I like and would use regardless of the company affiliation. To get an idea of how awesome Librato is check out their [Bay Area DMV wait times dashboard](https://metrics.librato.com/s/public/r623c3itn?duration=21600&end_time=1489696705&intercom=true).

## Not DevOps But Still Cool

[Go has created the Developer eXperience Working Group (DXWG)](https://blog.golang.org/developer-experience).

[Kyle Kingsbury](https://aphyr.com/) did an [interview with The Setup](https://usesthis.com/interviews/kyle.kingsbury/) that I found fascinating. His desktop is, "a ridiculous 48-way Xeon (2x E5–2697v2), with 128GB of ECC DDR3 and 11 TB of miscellaneous SSDs & spinning rust."
