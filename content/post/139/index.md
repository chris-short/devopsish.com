+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-08-04T07:00:00Z
description = ""
draft = false
slug = "139"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "weekly newsletter", "DevOps news", "Kubernetes news", "JEDI", "Oracle", "jq"]
title = "139: Dark Side of JEDI, "

+++

This week the coverage of JEDI: Oracle's use of a fake dossier, lobbying, and more to persuade the award of a massive government contract to AWS. 

## DevOps'ish Last Week's Top Five

1. [xkcd: Spreadsheets](https://xkcd.com/2180/)
1. [9 people for sysadmins to follow on Twitter](https://opensource.com/article/19/7/twitter-sysadmins)
1. [Goodbye Docker: Purging is Such Sweet Sorrow](https://zwischenzugs.com/2019/07/27/goodbye-docker-purging-is-such-sweet-sorrow/)
1. [Decoupling database migrations from server startup: why and how](https://pythonspeed.com/articles/schema-migrations-server-startup/)
1. [Kubernetes and Containers Best Practices - Health Probes](https://www.magalix.com/blog/kubernetes-and-containers-best-practices-health-probes)

## People

[**X-Team Is Hiring a Team of DevOps Engineers (Remote)**](https://cshort.co/2GImsty)  
We are looking for passionate DevOps engineers to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. [Join X-Team](https://x-team.com/remote-devops-engineer-jobs/?utm_source=devopsish&utm_medium=email-ad) *SPONSORED*

PEOPLE

[**The Business Value of Developer Relations**](https://cshort.co/2K9XsgV)  
Discover the true value of Developer Relations as you learn to build and maintain positive relationships with your developer community. Use the principles laid out in this book to walk through your company goals and discover how you can formulate a plan tailored to your specific needs. *SPONSORED*

## Process

[The Technical Side of the Capital One AWS Security Breach](https://start.jcolemorrison.com/the-technical-side-of-the-capital-one-aws-security-breach/) — Another huge breach thanks to AWS IAM misconfiguration. "Since the Server's `IAM Role` allowed for S3 access to those 700+ Buckets, [Paige A. Thompson] was able to access them"

[Linux Journal: The DevOps Issue](https://www.linuxjournal.com/content/devops-issue?utm_source=devopsish&utm_medium=newsletter&utm_campaign=139) (subscription required) — This month's edition of Linux Journal is all about DevOps. I highly encourage everyone to share with folks getting started on their journey or somewhere along the trough of disillusionment.

[JEDI: Oracle Playing Politics with Nation's Defense](https://chrisshort.net/use-the-force-larry-oracle-playing-politics-with-nations-defense/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=139) — "Senator Marco Rubio has sent letters to the President urging further scrutinization of [JEDI](https://devopsish.com/tags/jedi/). [D]uring his failed presidential run in 2016, Senator Rubio took $4 million from Oracle co-founder Larry Ellison. It's also worth noting that Oracle's CEO was on Trump's Transition Team."

[Amazon vs. Oracle: Effort to turn Trump against Amazon's bid for $10B contract](https://www.cnn.com/2019/07/26/politics/oracle-trump-amazon-defense-contract-conspiracy/index.html) — "White House officials in recent weeks have shown Trump a document that alleges a large conspiracy to award Amazon a 10-year, $10 billion contract to build the Pentagon's cloud computing network, according to three sources familiar with the matter. The document, obtained by CNN, is identical to one created by Oracle's top Washington lobbyist, Kenneth Glueck, an executive vice president with the company, Glueck tells CNN."

[After Trump cites Amazon concerns, Defense Secretary Mark Esper's Pentagon reexamines $10 billion JEDI cloud contract process](https://www.washingtonpost.com/business/2019/08/01/after-trump-cites-amazon-concerns-pentagon-re-examines-billion-jedi-cloud-contract-process/?utm_term=.4efc4954fd9a) (WaPo) — "The 11th-hour Oval Office intervention comes just weeks before the winning bid was expected to be announced and has now left a major military priority up in the air, said the officials, who spoke on the condition of anonymity to discuss the closed-door process freely."

[Kubernetes Pod Escape Using Log Mounts](https://blog.aquasec.com/kubernetes-security-pod-escape-log-mounts) — "In this post you’ll see how a pod running as root and with a mount point to the node’s /var/log directory can expose the entire contents of its host filesystem to any user who has access to its logs. We’ll also talk about your options to mitigate this issue in your cluster."

[Praise](https://devopsish.com/praise/) — If nice people say nice things, save it somewhere for when the impostor syndrome kicks-in. "Self-promotion is a leadership and political skill that is critical to master in order to navigate the realities of the workplace and position you for success." ― Bonnie Marcus

[Treading in Haunted Graveyards by Liz Fong Jones](https://www.honeycomb.io/blog/treading-in-haunted-graveyards/) — "[W]e switched from engineers using direct token access to modify our production environment to centralized push-on-green deployment"

## Tools

[**Get $100 to Demo Blue Matador The Alert Automation Service**](https://cshort.co/2YKgZg4)  
Blue Matador is alert automation for AWS and Kubernetes environments. Our proactive alerts take the time and toil out of monitoring. See production issues before anyone else. We're so confident you'll love it that we're offering $100 to demo it with our team. *SPONSORED*

[Why Kubernetes will disappear](https://levelup.gitconnected.com/why-kubernetes-will-disappear-10ffcfb39f01?gi=9107aafda7ae) — This went viral, for good reason. The article dicusses how, "the prize of ubiquity is invisibility," which, in my opinion, is much the same way Linux has become the universal standard. Kubernetes will eventually be the [layer 7](https://chrisshort.net/drawings/osi-model/) commodity on top of the OS (or the OS itself if you're looking at Google's [Container-Optimized OS](https://cloud.google.com/container-optimized-os/docs/)). This is good! It's good because it reminds us all that while Kubernetes is awesome, it still isn't the destination.

[Kubernetes: What is "reconciliation"? by Tim Hockin](https://speakerdeck.com/thockin/kubernetes-what-is-reconciliation) (slides) — A talk about controller rconcilliation and the best practices around them.

[Learn a little jq, awk, and sed](https://letterstoanewdeveloper.com/2019/07/29/learn-a-little-jq-awk-and-sed/) — I think I blew a former co-worker's mind when I showed them `jq` and `sed` piped together once. Throw in `awk` and you might as started thinking about building an operating system. j/k

[5 Programming Languages That Are Probably Doomed](https://insights.dice.com/2019/07/29/5-programming-languages-probably-doomed/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=139) — Ruby, Haskell, Objective-C, R, and Perl make up the list. I'm still blown away there's as much Perl as there is in the world today. True story, my first job out of the Air Force was at McClatchy Interactive. The CMS that powered thirty-one daily newspaper sites was written in Perl. It was advanced architecturally though (some microservices, definitely some resource pools for different workloads, MySQL database sharding, and a lot of YAML). It ended up collapsing under its own weight but, more the weight of the market. It was the newspaper industry afterall; the glory days had long past. But, to me, that was the last great Perl thing I worked on. What about you?

[airbnb/cloud-maker](https://github.com/airbnb/cloud-maker) — "Building castles in the sky" CloudMaker is a tool for launching and configuring EC2 instances. It works as an extension to the Ubuntu CloudInit system.

[TailorDev/Watson](https://github.com/TailorDev/Watson) — "A wonderful CLI to track your time!"

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week][tweet]](https://twitter.com/iancoldwater/status/1157305426813313024)

[tweet]: 139-tweet-of-the-week.png

Notes from this week's issue can be found on [GitHub](https://github.com/chris-short/devopsish.com/blob/master/content/post/139/notes.md)
