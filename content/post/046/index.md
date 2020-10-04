+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2017"]
date = 2017-10-22T06:01:00.808Z
description = ""
draft = false
slug = "046"
tags = ["devops", "cloud native", "open source", "kubernetes", "detroit", "docker", "moby", "lambda", "containers"]
title = "046: Docker Reverses Course on Kubernetes, Scoble is Terrible, HQ2, Happy HTTPS, Lambda..."
image = "/046/mountains-by-kris-nova.jpg"
imagealt = "Mountains by Kris Nova"
imagecap = "Mountains by [Kris Nova](https://novasummits.com)"
aliases = [
    "devopsish-046-docker-reverses-course-on-kubernetes-scoble-sucks-hq2-happy-https-lambda-13519b308810"
]

+++

Is DevOps dying? I've had this thought for a few weeks now. Since [DevOpsDays Detroit](https://www.devopsdays.org/events/2017-detroit/welcome/) when Richard I. Cook, M.D. sat shaking his head at Gene Kim on stage in a panel discussion titled, "DevOps, Safety, And Lean". Like a concept twisted by bad marketing DevOps has become almost a cult. There are those that practice it religiously and others that cannot adhere to every tenet every moment of every day but do try to "DevOps". Site Reliability Engineering has gained significant ground. As have many other practices and ideas that if embraced would balance the future of information work. Those of us in DevOps often forget where we came from. Never doing a deploy while the sun is up, only on the lowest traffic period, and rarely completed within the allotted time slot. Damn near anything was better than those days. Let's not be too high and mighty about [DevOps](https://devopsish.com/). We all should focus on making things better for everyone.

I'll be in Raleigh at All Things Open this week. If you're around definitely come say hello and get a DevOps'ish sticker. Also, come check out my [lightning talk on Tuesday](https://youtu.be/Ibnj-YZTypU).

[**Join Our Research Group — GoCD**](https://docs.google.com/forms/d/e/1FAIpQLSdsxfQbVbuVVRizNaDmD1_6nyyG5WNn4pKtfHElzO9kblnz5Q/viewform)  
Take our short survey for the chance to join a great group of continuous delivery practitioners in our research group. You'll be eligible to get your name on our contributors list, and win great schwag, and gift cards. *SPONSORED*

**All Things Open**  
October 23 and 24, Raleigh, NC USA  
3,000+ technologists will descend upon the City of Oaks to attend 200+ sessions from nearly as many speakers. Representative from nearly every major technology company in the U.S. will be in attendance as well.
To get 20% off enter code ***DevOpsish20*** when registering to attend.
Website: [https://allthingsopen.org](https://allthingsopen.org)

**All Day DevOps, Live Online**  
October 24, 2017  
When: October 24, 2017 (24 hours)  
Where: From your desktop, laptop, or mobile device  
Free Registration: All Day DevOps Registration ([http://www.alldaydevops.com](http://www.alldaydevops.com))

On October 24th, [DevOps'ish](https://devopsish.com/) will be supporting the Live Online All Day DevOps Conference. This is a 24-hour event with 5 simultaneous tracks, delivering 96 sessions and 4 keynotes in 38 time zones. Session tracks include Automated Security, CI/CD, Modern Infrastructure, DevOps in Government, and the Tech Crawl, where companies will take you behind the scenes of their DevOps working environments.


## People

[Robert Scoble and Me](https://medium.com/@quinnnorton/robert-scoble-and-me-9b14ee92fffb) by Quinn Foster

[What it's like to be a developer at...](https://increment.com/development/what-its-like-to-be-a-developer-at/) From popular tools to code review, deployment to daily life, get a peek at the developer experience at Slack, Lyft, GitLab, Digital Ocean, Fastly, and Sauce Labs.

[Working on the Go Team at Google](https://medium.com/@ljrudberg/working-on-the-go-team-at-google-917b2c8d35ff) by Leo Rudberg: "Having recently left the Go team at Google, I thought that it might be worthwhile to reflect on and to write about my experience."

[From DevOps to FamilyOps: How to encourage girls in tech](https://techbeacon.com/devops-familyops-how-encourage-girls-tech)

[New law bans California employers from asking applicants their prior salary](http://m.sfgate.com/business/networth/article/New-law-bans-California-employers-from-asking-12274431.php)

[Tech companies to lobby for immigrant 'Dreamers' to remain in U.S.](http://www.reuters.com/article/us-usa-immigration-dreamers/tech-companies-to-lobby-for-immigrant-dreamers-to-remain-in-u-s-idUSKBN1CP03Z)

[Denver-based email company SendGrid files for initial public offering of stock](http://www.denverpost.com/2017/10/19/sendgrid-filing-for-ipo/): Fast-growing company manages billions of transactional emails daily

[Michigan Grows Our First "Unicorn" Tech Company Valued At More Than $1 Billion](http://www.dailydetroit.com/2017/10/18/michigan-grows-first-unicorn-tech-company-valued-1-billion/)

[All the Thirsty Shit Cities Are Doing to Woo Amazon](https://splinternews.com/all-the-thirsty-shit-cities-are-doing-to-woo-amazon-1819683162)

[As Cities Woo Amazon to Build Second Headquarters, Incentives Are Key](https://www.wsj.com/articles/amazon-has-honed-its-site-hunting-expertise-with-in-house-team-1508405401)

[Detroit bid for Amazon HQ2 is on the way; Website launched to showcase city](http://www.wxyz.com/news/detroit-bid-for-amazon-hq2-is-on-the-way-website-launched-to-showcase-city)

{{< youtube DO4J_PC1b5M >}}

## Process

[Departures or How Condé Nast Stopped Worrying and Learned to Love Containers](https://technology.condenast.com/story/departures-building-a-docker-container-based-deployment-platform-at-conde-nast)

[Center stage: Best practices for staging environments](https://increment.com/development/center-stage-best-practices-for-staging-environments/) by Alice Goldfuss

[Canada's 'super secret spy agency' is releasing a malware-fighting tool to the public](http://www.cbc.ca/news/technology/cse-canada-cyber-spy-malware-assemblyline-open-source-1.4361728): 'This is something new for CSE,' says the agency, which is trying to shed its old reputation

[The 6-Step "Happy Path" to HTTPS](https://www.troyhunt.com/the-6-step-happy-path-to-https/) by Troy Hunt

[Bitten by a Kafka Bug — Postmortem](https://honeycomb.io/blog/2017/10/bitten-by-a-kafka-bug---postmortem/)

[Why we switched from Python to Go](https://getstream.io/blog/switched-python-go/)

[API design: Choosing between names and identifiers in URLs](https://cloudplatform.googleblog.com/2017/10/API-design-choosing-between-names-and-identifiers-in-URLs.html)

## Tools

[kris-nova/bashernetes](https://github.com/kris-nova/bashernetes): A Kubernetes implementation in bash (srsly)

[Ubuntu 17.10 (Artful Aardvark) Released](http://releases.ubuntu.com/17.10/)

[Docker Platform and Moby Project add Kubernetes](https://blog.docker.com/2017/10/kubernetes-docker-platform-and-moby-project/)

["Docker doesn't want to be replaced as the container runtime of choice"](https://jaxenter.com/docker-captain-coleman-interview-138098.html)

[Analyzing Docker Container Performance With Native Tools](https://crate.io/a/analyzing-docker-container-performance-native-tools/)

[HashiCorp Consul 1.0 Released](https://www.hashicorp.com/blog/hashicorp-consul-1-0)

[ACME Support in Apache HTTP Server Project](https://letsencrypt.org/2017/10/17/acme-support-in-apache-httpd.html)

[davecheney/httpstat](https://github.com/davecheney/httpstat): It's like curl -v, with colours.

[VIM After 15 Years](https://statico.github.io/vim3.html)

[flomotlik/awsinfo](https://github.com/flomotlik/awsinfo): Bash based AWS read-only client to make the AWS Console less necessary

[Make your Go Binaries Homebrew Installable](https://kev.inburke.com/kevin/install-homebrew-go/): "If you depend on a very specific version of a software package (say, Postgres 9.5.3 with readline support), I highly recommend creating a Homebrew repository and publishing recipes to it."

[AWS Lambda Cheatsheet](https://github.com/srcecde/aws-lambda-cheatsheet/blob/master/README.md)

[My Little Cluster Story](http://carolynvanslyck.com/blog/2017/10/my-little-cluster/) by Carolyn Van Slyck: If someone wants to buy me three Intel NUCs I would really, really like them.

[DotNetAnywhere: An Alternative .NET Runtime](http://mattwarren.org/2017/10/19/DotNetAnywhere-an-Alternative-.NET-Runtime/): This post will look at what DotNetAnywhere is, what you can do with it and how it compares to the full .NET framework.

[How Is New Terminal In VS Code So Fast?](https://codeburst.io/source-reading-how-is-new-terminal-in-vs-code-so-fast-10a40f7f8792)

[kz26/mailproxy](https://github.com/kz26/mailproxy): mailproxy is a simple SMTP proxy. It receives emails through an unencrypted, unauthenticated SMTP interface and retransmits them through a remote SMTP server that requires modern features such as encryption and/or authentication. mailproxy is primarily useful for enabling email functionality in legacy software that only supports plain SMTP.

## DevOps'ish Tweet of the Week

{{< tweet 921155261263499264 >}}
