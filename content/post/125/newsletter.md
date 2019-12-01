+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2019-04-28T07:00:00Z
description = "Docker Hub Breach, Drupal in Kubernetes, Localize Kubernetes, Get Into Open Source, Apple's AWS Bill, Hertz Sues Accenture, and Much More"
draft = false
slug = "125"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "container", "security", "system", "Docker Hub breach", "docker", "docker hub", "compromise", "Docker Inc"]
title = "125: Docker Hub Breach, Drupal in Kubernetes, Localize Kubernetes, Get Into Open Source, Apple's AWS Bill, Hertz Sues Accenture, and Much More"
image = "/125/docker-hub-breach.png"
imagealt = "Docker Hub breach impacting at least 190,000 accounts"

+++

> **NOTE**: Please read my [Disclaimer](https://devopsish.com/terms/) before breaking out the tar and feathers.

What a series of unfortunate events for [**Docker**](http://petty.company) in 2019. In what appeared to be a massive talent flush due to what looks like a potential earnings miss, the Great Docker Culling of 2019 happened. Docker appears to have laid off the vast majority of its well-known talent. [Andrea Luzzardi](https://twitter.com/aluzzard), [Sam Alba](https://www.linkedin.com/in/samalba/), and [Gareth Rushgrove](https://twitter.com/garethr) are among a slew of recent [Docker layoffs](https://devopsish.com/117/) discussed in this newsletter earlier this year. According to one source teams were, "killed," and Docker, "missed their number, and by a lot."

Fast forward to Friday night on the US east coast (like we weren't going to notice?!?). Many people (myself included) [received an e-mail from Docker](https://devopsish.com/125/docker-hub-breach-email.pdf) about a **Docker Hub breach** impacting at least 190,000 accounts. According to the e-mail, "Data includes usernames and hashed passwords... as well as Github and Bitbucket tokens for Docker autobuilds." Audit any Docker Hub tokens right now. Docker also, "revoked GitHub tokens and access keys. This means your autobuilds will fail." Nothing like a page on a weekend because Docker broke your builds. Check your [Docker Hub Linked Accounts](https://cloud.docker.com/settings) and re-link them. You'll then likely have to do a weird do-si-do in the Build config of one of your image pages to get everything working as is.

This Docker Hub breach is a **significant breach**. If any of the tokens of any of the common base images had been compromised — packages like Alpine, busybox, Node.JS, or any of the major databases — these could have easily permeated into the wild with little or no knowledge. From my point of view, the only way to be sure you're not affected is to somehow verify with the image provider that their account has been cleaned up and redeploy all your containers. Cleaned up as [directed by Docker](https://success.docker.com/article/docker-hub-user-notification) (note the URL, "success"). Why? Because it's likely some upstream used Docker Hub even if you didn't. In other words, "Nuke the entire site from orbit. It's the only way to be sure." Yes, it's that bad until it's confirmed otherwise.

*What a Docker freaking mess we're in*. At the risk of being extra petty, I can't help but mention I started using [Quay](https://quay.io/) when I joined Red Hat and I'm pretty happy with it. It's a container registry, not an Alexander Wang piece. Quay is not perfect but, I'm not expecting a whole lot here. It looks like I'll be moving more images off Docker Hub in the future.

[**Hit send on your last tech job application**](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email1)  
One application, many tech opportunities. Indeed Prime makes job hunting quick and easy. Save time and let us do the heavy lifting for you by matching you with top tech companies. [Join for free today](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email1)! *SPONSORED*

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [How much does a DevOps engineer make?](https://enterprisersproject.com/article/2019/4/devops-engineer-salary)
1. [What Happened When The DEA Demanded Passwords From LastPass](https://www.forbes.com/sites/thomasbrewster/2019/04/10/what-happened-when-the-dea-demanded-passwords-from-lastpass/#e337d747ebeb)
1. [The Problem with SSH Agent Forwarding](https://defn.io/2019/04/12/ssh-forwarding/)
1. [The 5 communication problems that destroy company morale](https://qz.com/work/1587170/the-five-types-of-communication-problems-that-destroy-company-morale/)
1. [Alikhll/golang-developer-roadmap: Roadmap to becoming a Go developer in 2019](https://github.com/Alikhll/golang-developer-roadmap)

## People

[Google Walkout Organizers Say They're Facing Retaliation](https://www.wired.com/story/google-walkout-organizers-say-theyre-facing-retaliation/) — "Two employee activists at Google say they have been retaliated against for helping to organize a walkout among thousands of Google workers in November." I'm pretty sure this is illegal, no? The [dispute intensified](https://www.wired.com/story/dispute-googles-alleged-retaliation-intensifies/) at a town hall on Friday. [#NotOkGoogle](https://twitter.com/hashtag/NotOkGoogle)

[Hire People or Optimize Processes: A cost-benefit analysis for engineering leaders](https://codeclimate.com/blog/scale-engineering-calculator/) — Help to figure out if you should hire more people or optimize your widget making.

[Kubernetes jobs hunt: How to land that role](https://enterprisersproject.com/article/2019/4/kubernetes-jobs-hunt-how-land-role) — Trying to get a job working with Kubernetes? Consider these five tips.

[The Difference Between Goals, Strategies, Metrics, OKRs, KPIs, and KRIs](https://danielmiessler.com/blog/the-difference-between-goals-strategies-metrics-okrs-kpis-and-kris/) — The differences and similarities between the most common types of business measurement systems

[DNS over HTTPS is coming whether ISPs and governments like it or not](https://nakedsecurity.sophos.com/2019/04/24/dns-over-https-is-coming-whether-isps-and-governments-like-it-or-not/) — Encrypting your DNS queries in the payload of an HTTPS packet means that countries and companies can't as easily hijack DNS to control internet access or to monitor employee activity. Conversely, blocking known bad DNS entries (sinkhole) and using DNS query logs to hunt for indicators of compromise are common security measures. This becomes a MUCH harder problem.

[The Science Behind DevOps with Dr. Nicole Forsgren — Real World DevOps](https://share.transistor.fm/s/433ecde0)

[DevOps'ish Telegram](https://devopsi.sh/telegram) — Join the over 230+ DevOps, Kubernetes, SRE, and other technology professionals discussing real-world problems and solutions to modern-day issues.

## Process

[**Accelerate: State of DevOps 2019 Survey**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5):  Nicole Forsgren, PhD is conducting the State of DevOps 2019 Survey. Your input is incredibly important. On several occasions, I have referenced [the 2018 report](https://cloudplatformonline.com/2018-state-of-devops.html) since its release for real-world work that impacts real numbers. Nicole's group also wrote, [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2), which I cannot recommend enough either.

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[How You Can Help Localize Kubernetes Docs](https://kubernetes.io/blog/2019/04/26/how-you-can-help-localize-kubernetes-docs/) — If you're interested in helping an existing Kubernetes localization please help us out!

[7 advantages of open source for agile teams](https://enterprisersproject.com/article/2019/4/7-advantages-open-source-agile) — "Adopting DevOps and agile practices is how companies are managing the velocity of change. I imagine it's possible to do agile or DevOps in a closed source world. The question then becomes, why put that hurdle there?"

[Open Source Software: The Complete Wired Guide](https://www.wired.com/story/wired-guide-open-source-software/) — Some knowledge about open source software that's easily consumable by the unknowing.

[Forge Your Future with Open Source: Build Your Skills. Build Your Network. Build the Future of Technology. by VM (Vicky) Brasseur](https://pragprog.com/book/vbopens/forge-your-future-with-open-source) — And if you want to get going in Open Source, I highly recommend Vicky's book.

[Slack files to go public, reports $138.9M in losses on revenue of $400.6M](https://techcrunch.com/2019/04/26/slack-files-to-go-public/) — And the tech IPOs just keep on coming.

[Some internet outages predicted for the coming month as '768k Day' approaches](https://www.zdnet.com/article/some-internet-outages-predicted-for-the-coming-month-as-768k-day-approaches/) — Some routers will crash soon due to ternary content-addressable memory needs of over 768K. [BGP and DNS are the bubble gum and duct tape of the internet](https://twitter.com/ChrisShort/status/1071033552551206912).

[Apple spends more than $30 million a month on Amazon Web Services](https://www.cnbc.com/2019/04/22/apple-spends-more-than-30-million-on-amazon-web-services-a-month.html) — People freaked out when they heard this number. Apple uses a lot of different cloud providers for various reasons (I used to work for one). But, I think the bigger story is, [Apple Slashed Amazon Cloud Spending 50 Percent in Bid for Self-Sufficiency](https://www.theinformation.com/articles/apple-curbed-amazon-cloud-spending-in-bid-for-self-sufficiency)

[A Roadmap to Convergence – OpenTracing](https://medium.com/opentracing/a-roadmap-to-convergence-b074e5815289) — "We are creating a new, unified set of libraries and specifications for observability telemetry. It will [merge the OpenTracing and OpenCensus projects](https://medium.com/opentracing/merging-opentracing-and-opencensus-f0fe9c7ca6f0), and provide a supported migration path."

[The DevOps Institute Has Been Brandjacked](https://devops.com/the-devops-institute-has-been-brandjacked/) This is some pretty gross behavior by [QuickStart](https://www.quickstart.com/) but, trademark and copyright law exist for a reason. I certainly hope QuickStart Learning Inc. finds out about the law very soon.

[Accenture sued over website redesign so bad it Hertz: Car hire biz demands $32m+ for 'defective' cyber-revamp](https://www.theregister.co.uk/2019/04/23/hertz_accenture_lawsuit/) — This is so bad y'all. [This Twitter thread](https://twitter.com/allafarce/status/1121174850226147328) is also gold.

[DevOps'ish with Chris Short – Newsletterers – The Tim Show – S02E01](https://devopsi.sh/timshow) — Ever wonder how the DevOps'ish newsletter started, how I build it, or what it's like to write a newsletter? Check out fellow Red Hatter Tim Hildred's podcast on that very topic!

## Tools

[Running Drupal in Kubernetes with Docker in production](https://www.jeffgeerling.com/blog/2019/running-drupal-kubernetes-docker-production) — "You really have to be on your game in the world of containerized-Drupal-in-production!"

[Hardware Accelerated SSL/TLS Termination in Ingress Controllers using Kubernetes Device Plugins and RuntimeClass](https://kubernetes.io/blog/2019/04/24/hardware-accelerated-ssl-tls-termination-in-ingress-controllers-using-kubernetes-device-plugins-and-runtimeclass/)

[Packets-per-second limits in EC2](https://stressgrid.com/blog/pps_limits_in_ec2/) — "[W]e determined that each EC2 instance type has a packet-per-second budget. Surprisingly, this budget goes toward the total of incoming and outgoing packets. Even more surprisingly, the same budget gets split between multiple network interfaces, with some additional performance penalty."

[How to run systemd in a container](https://developers.redhat.com/blog/2019/04/24/how-to-run-systemd-in-a-container/) — Trying to run systemd in a container is hard af. I've had to do it to test deployments before and I have to say, Dan's method is probably better than any I've ever seen. I want to change the Podman name so bad though, Man.

[Kubernetes Tutorial - Step by Step Guide to Basic Kubernetes Concepts](https://auth0.com/blog/kubernetes-tutorial-step-by-step-introduction-to-basic-concepts/) — This is a nice introduction to k8s from Auth0. Good for them for getting a little out of their comfort zone to help lower the barrier to entry a little.

[Leveraging Jenkins on Kubernetes](https://caylent.com/leveraging-jenkins-on-kubernetes/)

[Kubernetes Network Policy APIs](https://octetz.com/posts/k8s-network-policy-apis) — "This post explores multiple ways network policy can be expressed in Kubernetes." In other words, way more than I want to know about Kubernetes networking. But, good to have as a reference.

[Improving the security of Kubernetes clusters using Istio](https://blog.giantswarm.io/Improving-security-with-Istio/) — Istio does SO MUCH.

[Istio the Easy Way](https://medium.com/solo-io/istio-the-easy-way-de66e6eba4a1) — Oh good there's an easy way! Thank you, Christian Posta and solo.io for this.

[Python Project Tooling explained](https://write.as/chobeat/python-project-tooling-explained) — Instant bookmark. Please share with others that are new or even a little old to Python.

[All That You Need to Know About Microsoft's New Programming Language: Bosque](https://dev.to/0xrumple/all-what-you-need-to-know-about-microsoft-s-new-programming-language-bosque-38c0) — "The Bosque programming language is a Microsoft Research project that is investigating language designs for writing code that is simple, obvious, and easy to reason about for both humans and machines."

[Why Go? – Key advantages you may have overlooked](https://yourbasic.org/golang/advantages-over-java-python/) — I hear good things about these [Gopher](https://www.gophercon.com/) people. Not those [gopher](https://en.wikipedia.org/wiki/Gopher_(protocol)) people.

[Open Sourcing Jingo, a Faster JSON Encoder for Go](https://bet365techblog.com/open-sourcing-jingo-a-faster-json-encoder-for-go) — This package provides the ability to encode golang structs to a buffer as JSON very quickly.

[Building platform stacks with in-house scripts vs. Kubernetes Operators](https://medium.com/@cloudark/building-platform-stacks-with-in-house-scripts-vs-kubernetes-operators-95541e555025) — STOP HAND ROLLING SCRIPTS! YOUR ARTISANAL SCRIPTS DON'T BELONG! GET OFF MY LAWN!

[ricardbejarano/haproxy](https://github.com/ricardbejarano/haproxy) — 🏎 Built-from-source container image of the HAProxy load balancer

[cdr/sshcode](https://github.com/cdr/sshcode) — Run VS Code on any server over SSH

[bxcodec/gotcha](https://github.com/bxcodec/gotcha) — gotcha: inmemory-cache in Go (Golang) with customizable algorithm

[mhausenblas/kboom](https://github.com/mhausenblas/kboom) — The Kubernetes scale & soak load tester (do you want to shred some clusters with me?!?)

[GoogleCloudPlatform/berglas](https://github.com/GoogleCloudPlatform/berglas) — A tool for managing secrets on Google Cloud (I hope Google does End of Life this before the newsletter goes live)

[operator-framework/community-operators](https://github.com/operator-framework/community-operators) — The canonical source for Kubernetes Operators that appear on OperatorHub.io, OpenShift Container Platform, and [OKD](https://www.okd.io/)

## DevOps'ish Tweet of the Week

{{< tweet 1122117406372057090 >}}

Notes from this week's issue can be found [here](./notes/).
