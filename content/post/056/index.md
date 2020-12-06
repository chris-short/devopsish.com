+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2017"]
date = 2017-12-31T07:01:01.997Z
description = ""
draft = false
slug = "056"
tags = ["devops", "cloud native", "open source", "kubernetes", "serverless", "Docker"]
title = "056: Is Docker Dead, Tech Bros, Kubernetes, Tools Galore, and More!"
image = "/056/macbook-hour-glass.jpg"
imagealt = "The sand is almost at the bottom of 2017's hourglass"
aliases = [
    "devopsish-056-is-docker-dead-tech-bros-kubernetes-tools-galore-and-more-89edb0cc703e"
]

+++

The end of 2017 is upon us. Whether your 2017 was amazing or terrible I wish you all the best in 2018. I have very mixed feelings about this year. I feel like DevOps and open source software as a whole had a good 2017. I think 2018 will be quite interesting for this space. There will be numerous opportunities for open source software and its methodologies to continue to penetrate deeper into industries like the automotive and banking spaces.

I don't like to do prediction pieces typically (although I do read them). Feedback from [DevOps'ish 054](/054/) led me to believe that further analysis was needed on a brief piece of commentary I made regarding Docker: [**Docker, Inc. is Dead**](https://chrisshort.net/docker-inc-is-dead/). The name Docker, while it remains a command on people's systems, is more the name of a company and commercial service offering now than a container platform. I thought that was clear in the post but I had to change the title based on feedback I received. All feedback is appreciated; trolling does not equal feedback. When I say, "Docker is dead" I am referring to the company, not the software. The software will live on in one form or another for a long time; the company will not.

[**GoCD — Open Source Continuous Delivery Server**](https://devopsish.us14.list-manage.com/track/click?u=631fcd11ad2a643d08035c221&id=5a1471dfb5&e=7cc492dc98)  
GoCD is a continuous delivery tool supporting modern infrastructure with elastic on-demand agents and cloud deployments. With GoCD, you can easily model, orchestrate and visualize complex workflows from end to end. [It's open source, free to use and download](https://devopsish.us14.list-manage.com/track/click?u=631fcd11ad2a643d08035c221&id=3133731028&e=7cc492dc98). *SPONSORED*


## People

[The Night Before Christmas, AWS Version (Video)](https://youtu.be/sNDaJqGwKjI)

[The LAPD has arrested a man in connection with the Kansas swatting death](https://www.theverge.com/2017/12/30/16833228/call-of-duty-swatting-prank-wichita-kansas-suspect-arrested): This is tragic and the fact someone can pick up a phone and get a SWAT team to someone's house in this country is disconcerting.

[Tech Bros Bought Sex Trafficking Victims by Using Amazon and Microsoft Work Emails](http://www.newsweek.com/metoo-microsoft-amazon-trafficking-prostitution-sex-silicon-valley-755611): After dealing with idiots in the Air Force surfing porn from unclassified networks and setting up servers full of porn on classified networks, I'm not surprised by this at all.

[The future of DevOps: What to expect for 2018](https://www.itproportal.com/features/the-future-of-devops-what-to-expect-for-2018/): Security will be HUGE.

[Mark Zuckerberg's real campaign: Save Facebook](http://www.axios.com/mark-zuckerbergs-real-campaign-save-facebook-2520448137.html)

['The most important Apple executive you've never heard of' is now also Apple's second-best paid](http://www.businessinsider.com/apple-johny-srouji-second-best-paid-executive-2017-12): The fact Apple is becoming a very viable chip maker (look at the iPhone's latest chips) should scare the hell out of Intel.

[How I learned to program](https://danluu.com/learning-to-program/)

## Process

[Nation-State Hacking: 2017 in Review](https://www.eff.org/deeplinks/2017/12/2017-year-nation-state-hacking)

[New York State Eyes Its Own Net Neutrality Law](http://www.techdirt.com/articles/20171226/10390638883/new-york-state-eyes-own-net-neutrality-law.shtml)

[How "expensive" is crypto anyway?](https://medium.com/cloudflare-blog/how-expensive-is-crypto-anyway-920d08fe71ee)

## Tools

[Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)

[Tips and resources for learning Kubernetes](https://opensource.com/article/17/12/resources-learning-kubernetes)

[Serverless and OpenFaas with Alex Ellis](https://www.hanselminutes.com/612/serverless-and-openfaas-with-alex-ellis): I met Alex at KubeCon, he's good people.

[Is Docker Dead?](https://www.infoq.com/presentations/docker-serverless) Nic Jackson compares and contrasts the development and deployment flow for both a Docker and a Serverless project, attempting to see if Docker has already been made obsolete by serverless.

[Let's hand write DNS messages](https://routley.io/tech/2017/12/28/hand-writing-dns-messages.html): "In this post, we'll explore the Domain Name Service (DNS) binary message format, and we'll write one by hand."

[A Look at Ten New Database Systems Released in 2017](https://medium.com/@peterc/a-look-at-ten-new-database-systems-released-in-2017-94a3aa4c2aab)

[File crash consistency and filesystems are hard](https://danluu.com/file-consistency/)

[The state of netbooting Raspberry Pis](http://blog.alexellis.io/the-state-of-netbooting-raspberry-pi/): "It's undeniable — Raspberry Pis capture the imagination of techies of all ages. Combine several Raspberry Pis into a cluster and you now have an x10 or x100 multiplier, but there are some problems with SD Cards. Netbooting is meant to fix this — but there are some limitations to its usefulness."

[chrisanthropic/terraform-infra-as-code-coverage-badges](https://github.com/chrisanthropic/terraform-infra-as-code-coverage-badges): A small script that is useful to track the level of 'infrastructure-as-code' coverage; ie how much of your AWS infrastructure is managed by Terraform?

[briandowns/sky-island](https://github.com/briandowns/sky-island): Sky Island is a FaaS platform built utilizing FreeBSD jails, on ZFS, for running raw Go functions, with interaction through a REST API.

[jonmosco/kube-ps1](https://github.com/jonmosco/kube-ps1): A Kubernetes (k8s) bash and zsh prompt that displays the current cluster context and the namespace.

[hwayne/awesome-cold-showers](https://github.com/hwayne/awesome-cold-showers): It's great when people get excited about things, but sometimes they get a little *too* excited. This an awesome (rigorous and respectful) and curated (I read every suggestion and make judgement calls) list of cold showers on overhyped topics.

[dgryski/go-perfbook](https://github.com/dgryski/go-perfbook): This is a work-in-progress book in Go performance.

[docker/docker-bench-security](https://github.com/docker/docker-bench-security): The Docker Bench for Security is a script that checks for dozens of common best-practices around deploying Docker containers in production.

## DevOps'ish Tweet of the Week

{{< tweet 946480696893116416 >}}
