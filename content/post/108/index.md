+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-12-30T07:00:00Z
description = "Stats, Emily Freeman, IPOs, Kubernetes Future, Go, and More"
draft = false
slug = "108"
tags = ["devops", "kubernetes", "open source", "cloud", "newsletter", "cloud native", "aws", "gocd", "tech", "security", "serverless", "google", "go"]
title = "108: Stats, Emily Freeman, IPOs, Kubernetes Future, Go, and More"
+++

Since this is the last newsletter of the year, I wanted to provide some stats on how DevOps'ish did in 2018. Thank you, readers, for making DevOps'ish one of the best damn newsletters on the planet! I wish you all the best in 2019.

Note: All stats are for *2018 only* (source, MailChimp)

* Subscribers Added: 1,713
* Number of Emails Sent: 89,402
* Total Opens: 85,789
* Total Clicks: 99,093
* Unique Opens: 45,729
* Unique Clicks: 22,442
* Open Rate: 51.14%
* Click Rate: 25.09%
* Most Unique Opens (email, count): [104: AWS (roasting Oracle), Kubernetes, Open Source in 2018, Oh... Google, Breaches, and More](https://devopsish.com/104/) (1191)
* Most Unique Clicks (email, count): [104: AWS (roasting Oracle), Kubernetes, Open Source in 2018, Oh... Google, Breaches, and More](https://devopsish.com/104/) (578)
* Most Opened (email, rate): [073: DevOps Hiring Guide, RIP RTFM, BGP & DNS, Kubernetes, GitLab, and More](https://devopsish.com/073/) (56.83%)
* Most Clicked (email, rate): [070: Not the Postmortem We Wanted to Run](https://devopsish.com/070/) (31.30%)

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*

{{< sponsor-blurb >}}

## People

[2018 Learnings, 2019 Expectations](https://chrisshort.net/2018-learnings-2019-expectations/) — What I learned this year and what I expect next year. I touched on Kubernetes, SRE, DevOps, Serverless, hypervisors, Impostor Syndrome, and much more.

[Developer Relations: (More Than) The Art of Talking Good](https://emilyfreeman.io/blog/developer-relations-more-than-the-art-of-talking-good) — My amazing friend, [Emily Freeman](https://emilyfreeman.io/), is one of the hardest working people on the planet. DevRel is hard, y'all. If you think it's easy, come get some.

[Highest Paying Tech Companies of 2018 by Levels.fyi](https://www.levels.fyi/2018/) — The facepalm is strong with this one. But, if your company is remote friendly and has an office in Silicon Valley, here's some ammo.

[DevOps engineer interviews: Ask these questions](https://enterprisersproject.com/article/2018/12/hiring-devops-engineer-ask-these-questions) — Single out your best DevOps engineer candidates by asking a mix of soft skill and technical questions

[The truth about impostor syndrome](https://dev.to/kelly/the-truth-about-impostor-syndrome-165h) — Kelly has created something worth printing out and putting on your desk somewhere.

[Tech giants in $80 billion legal battle to help attract top talent](https://www.cnbc.com/2018/12/26/tech-giants-in-80-billion-legal-battle-to-help-attract-top-talent.html) — It's time for "patent trolls" to die. And this headline isn't great.

[The GPS wars have begun](https://techcrunch.com/2018/12/21/the-gps-wars-have-begun/) — Japan has its own satellite navigation system now. China and the EU are hot on their heels with their own systems. India and the UK are working on their own systems too. Who knew knowing where you are is so important?

## Process

[Top Amazon boss privately advised US government on web portal worth billions to tech firm](https://www.theguardian.com/technology/2018/dec/26/amazon-anne-rung-government-services-authority) — Shady...

[12 days of DevOps: Expert tips to help teams succeed](https://enterprisersproject.com/article/2018/12/12-days-devops-expert-tips-how-help-teams-succeed) — "On the twelfth day of DevOps, break out the eggnog!" You're gonna need it.

[Google's Kelsey Hightower Dissects Serverless Hype and Hope](https://thenewstack.io/googles-kelsey-hightower-dissects-serverless-hype-and-hope/) — The need to worry about the server is going away rapidly.

[The biggest technology failures of 2018](https://www.technologyreview.com/s/612646/the-biggest-technology-failures-of-2018/) — Here's the abridged version...

[5 unicorns that will probably go public in 2019 (besides Uber and Lyft)](https://techcrunch.com/2018/12/23/5-unicorns-that-will-probably-go-public-in-2019-besides-uber-and-lyft/) — Always good to know who might be going public soon.

[Unicorn IPOs Said To Accelerate As Public Markets Scare Everyone](https://news.crunchbase.com/news/unicorn-ipos-said-to-accelerate-as-public-markets-scare-everyone/) — Yea... 2019 is going to scare us, y'all.

[The people, processes, and tools of DevOps in 2018](https://opensource.com/article/18/12/top-devops) — The Opensource.com dirty dozen of DevOps articles.

[Surprises and Challenges in My Switch to Fully Remote Work](https://auth0.com/blog/surprises-in-my-switch-to-remote-work/) — Can confirm.

[911 emergency services go down across the US after CenturyLink outage](https://techcrunch.com/2018/12/28/911-service-outage-centurylink/) — This is crazy and it was [likely due to a bad card in Denver](https://www.geekwire.com/2018/report-huge-centurylink-outage-caused-bad-networking-card-colorado/).

[In January, the EU starts running Bug Bounties on Free and Open Source Software](https://juliareda.eu/2018/12/eu-fossa-bug-bounties/) — Projects like Drupal, Tomcat, Kafka, and several others now have EU run bug bounty programs

## Tools

[The Kubernetes Scheduler by Andrew Chen and Dominik Tornow](https://medium.com/@dominik.tornow/the-kubernetes-scheduler-cd429abac02f) — "This blog post provides a concise, detailed model of the Kubernetes Scheduler." If you ever wanted to know anything about the scheduler, it's probably in this blog post.

[The future of Kubernetes is Virtual Machines](https://tech.paulcz.net/blog/future-of-kubernetes-is-virtual-machines/) — Paul thinks the future of Kubernetes will be VMs ([I think Kubernetes will become the hypervisor](https://chrisshort.net/2018-learnings-2019-expectations/)).

[YAML Has Won](https://medium.com/@robmuh/yaml-has-won-ba5dae37e740) — Yes, yes it has. It doesn't mean we have to be happy about it.

[Awesome Golang Security 🕶🔐](https://dev.to/streichsbaer/awesome-golang-security--4d7) — If you write or work with a lot of Go code there are some nuggets in here.

[Validating Pre-Commit Network Configuration Changes at Scale with Batfish and Ansible](https://www.ansible.com/resources/webinars-training/validating-pre-commit-network-configuration-changes-at-scale-with-batfish-ansible)

[Banana Pi to Launch a 24-Core Arm Server](https://www.cnx-software.com/2018/12/26/banana-pi-24-core-arm-server/) — Holy smokes!

[Linux Technology for the New Year: eBPF](https://thenewstack.io/linux-technology-for-the-new-year-ebpf/) — "In the future, you will see a lot more eBPF programs instead of kernel modules." —Brendan Gregg

[sed 's/docker/containers/g'](https://opensource.com/article/18/12/sed-sdockercontainersg) — There's A LOT more to containers than Docker

[Using Go in Devops GopherAcademy](https://blog.gopheracademy.com/advent-2018/go-devops/) — Go and DevOps are like peanut butter and jelly

[jdumars/agileops](https://github.com/jdumars/agileops) — The Agile Operations methodology

[bloomberg/goldpinger](https://github.com/bloomberg/goldpinger) — Debugging tool for Kubernetes which tests and displays connectivity between nodes in the cluster.

## DevOps'ish Tweet of the Week

{{< tweet 1078750833410375680 >}}