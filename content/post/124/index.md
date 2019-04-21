+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-04-21T07:00:00Z
description = ""
draft = false
slug = "124"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "container", "security", "system"]
title = "124:"

+++

INTRO

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*

[**170+ live online training courses opened for March and April**](https://www.oreilly.com/pub/cpc/213941)  
Get hands-on training in machine learning, AWS, Kubernetes, Python, Java, and many other topics *SPONSORED*

{{< sponsor-blurb >}}

## DevOps'ish Top Five from Last Week

1. [How to Get Into SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre/)
1. [A beginner's guide to building DevOps pipelines with open source tools](https://opensource.com/article/19/4/devops-pipeline)
1. [Lessons from 300k+ Lines of Infrastructure Code](https://www.infoq.com/presentations/infrastructure-cookbook)
1. [Google's remote work employee survey](https://www.fastcompany.com/90329043/exclusive-google-asked-100000-employees-about-remote-work-this-is-what-they-learned)
1. [Hannah Montana Linux](http://hannahmontana.sourceforge.net/) 👀🤣🤣🤣

## People

[Want an awesome job, working in a great team, with a tremendous leader?](https://social.icims.com/viewjob/pt1553611085158445da) — If you're in Europe and want to work on the Ansible team with other fellow Red Hatters. This is the job for you (maybe)!

[Sonatype, Senior Technical Ambassador, DevOps Community](https://jobs.lever.co/sonatype/eb80a45e-dd73-4cc2-beae-58f2d4b937b2) — My friends at Sonatype are looking for an awesome DevOps person to talk about their great products and practices.

[The introvert's guide to Red Hat Summit](https://www.redhat.com/en/blog/introverts-guide-red-hat-summit) — If you're like me, going to Red Hat Summit but, have to ninja off to be a normal version of yourself for a little bit every once in a while, this guid is for you. Yes, I'll be at Red Hat Summit in Boston. Let me know if you'll be attending.

[What Happened When The DEA Demanded Passwords From LastPass](https://www.forbes.com/sites/thomasbrewster/2019/04/10/what-happened-when-the-dea-demanded-passwords-from-lastpass/#190345307ebe) — LastPass couldn't give the DEA the passwords because of their encryption implementation. But, there is always metadata and metadata can sometimes paint an even better picture than the data itself. An interesting tale of how you can do everything right and still screw your customers (or yourself, depending on the point of view).

[How much does a DevOps engineer make?](https://enterprisersproject.com/article/2019/4/devops-engineer-salary) — Putting debates around the term DevOps engineer aside, let’s explore data points on salaries for this hot job title

## Process

[**Accelerate: State of DevOps 2019 Survey**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5):  Nicole Forsgren, PhD is conducting the State of DevOps 2019 Survey. Your input is incredibly important. On several occassions, I have referenced [the 2018 report](https://cloudplatformonline.com/2018-state-of-devops.html) since its release for real world work that impacts real numbers. Nicole's group also wrote, [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2), which I cannot recommend enough either.

[Homeland Security warns of security flaws in enterprise VPN apps](https://techcrunch.com/2019/04/12/enterprise-security-flaws/) — A hole in OpenVPN means there's a whole in your backdoor, eek! Seriously, upgrade ASAP. I stepped back from OpenVPN a couple years ago for a few reasons. If you need an alternative I'd recommend [WireGuard](https://www.wireguard.com/) (for personal use there is also [Outline](https://getoutline.org/)).

[The top two most popular Docker base images each have over 500 vulnerabilities](https://snyk.io/blog/the-top-two-most-popular-docker-base-images-each-have-over-500-vulnerabilities/) — "The last scan as of March 11, 2019 shows that the official Node.js image ships with 567 vulnerable system libraries. The remaining nine images ship with at least 31 publicly known vulnerabilities each." Remember, containers make it easy to ship software vulnerabilities too.

## Tools

[Introducing Fenrir: How Coinbase is Scaling Serverless Applications](https://blog.coinbase.com/introducing-fenrir-how-coinbase-is-scaling-serverless-applications-9ba6e3a74761) — "Fenrir is our AWS SAM deployer; at its core is a reimplementation of the `sam deploy` command as an AWS Step Function, so it’s a serverless serverless (serverless²) deployer." 🤯🤯🤯

[The Future of Serverless is... Functionless?](https://www.stackery.io/blog/future-of-serverless/) — "With [AWS] [AppSync](https://aws.amazon.com/appsync/), DynamoDB Tables, SQL Databases (via Aurora Serverless), Lambda Functions, and ElasticSearch domains have all been elevated as [first-class “Data Sources” for GraphQL resolvers](https://docs.aws.amazon.com/appsync/latest/devguide/tutorials.html)."

[How Google Cloud Run Combines Serverless with Containers](https://thenewstack.io/how-google-cloud-run-combines-serverless-with-containers/) — Cloud Run is a Google made layer on top of knative on top of Kubernetes on top of compute (which on GCP is probably a container in a container of containers). We might have finally hit enough abstractions to start measuring them by "inceptions" (five abstractions is one inception). Thoughts?

## DevOps'ish Tweet of the Week

{{< tweet 1118816110571339778 >}}