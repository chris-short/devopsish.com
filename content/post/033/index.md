+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2017"]
date = 2017-07-23T07:01:01.348Z
description = ""
draft = false
slug = "033"
tags = ["devops", "cloud native", "open source", "kubernetes", "golang", "hiring", "women in tech", "gophercon", "password management", "microservices", "CI/CD"]
title = "033: More GopherCon, Women in Tech, DevOps, Kubernetes, etcdhcp, and More"
image = "/033/burning-oil-well.jpg"
imagealt = "Moving Sucks (and other obvious things)"
aliases = [
    "devopsish-033-more-gophercon-women-in-tech-kubernetes-etcdhcp-and-more-45f0cbd3d3b5"
]
+++

Sunday, I flew back to NC to help close and move out of our house. It has turned into quite the saga that I won't bother with trying to explain to everyone. But, having injections on moving day was not as bad as I thought it was going to be. The world of [**DevOps**](https://devopsish.com/) was quite busy this week. Also, several great [talks from GopherCon are available in various forms](https://github.com/gophercon/2017-talks), including my GopherCon 2017 Lightning Talk: [Golang to the rescue: Saving DevOps from TLS turmoil](https://chrisshort.net/testing-certificate-chains-in-go/). Last, but not least, [happy second birthday, Kubernetes!](https://twitter.com/hashtag/K8sBday?src=hash)

## People

[Right Here, Right Now: 27 Simple Actions to Support Women in Tech](https://shift.newco.co/amp/p/1672110989cd): Below is a list of ideas. They require nothing but intention and time. They apply to men and women, people in leadership roles or individual contributors, people working for themselves or in companies. They won't just benefit women, or even just tech, they'll create a great environment for everyone.

[Charity Majors' Mission to Monitor Microservices](https://thenewstack.io/open-source-leaders-charity-majors-mission-monitor-microservices/): Charity Majors knows first hand the pain every software developer feels upon releasing a carefully built and strenuously tested project into the wild — i.e., that moment where performance monitoring becomes virtually impossible.

[Employees Who Stay In Companies Longer Than Two Years Get Paid 50% Less](https://www.forbes.com/sites/cameronkeng/2014/06/22/employees-that-stay-in-companies-longer-than-2-years-get-paid-50-less/#46872946e07f): [T]he inflation rate is currently 2.1% calculated based on the Consumer Price Index published by the Bureau of Labor Statistics. This means that your raise is actually less than 1%. This is probably sobering enough to make you reach for a drink.

[What Kubernetes means to me](https://www.linkedin.com/pulse/what-kubernetes-means-me-jaice-singer-dumars): Today is an auspicious day. It's Kubernetes' second birthday! And, I want to celebrate it by sharing my Kubernetes journey with you. My disclaimer is this is a very personal post, and that's always a vulnerable thing to do.

[Microsoft is Hiring Go engineers to work on Kubernetes](https://www.reddit.com/r/golang/comments/6o2lc3/microsoft_is_hiring_go_engineers_to_work_on/): We're looking for Go engineers to work on Kubernetes and related cloud/distributed systems. The job description is [here](https://careers.microsoft.com/jobdetails.aspx?ss=&pg=0&so=&rw=1&jid=290815&jlang=EN&pp=SS).

[Azure on a hot streak of hiring, hoovering up developer advocates](https://redmonk.com/jgovernor/2017/07/20/azure-on-a-hot-streak-of-hiring-hoovering-up-developer-advocates/): We're seeing Microsoft establish a new center of gravity for developer advocacy talent in "Cloud City", under Jeff Sandquist, General Manager on the Cloud and Enterprise team.

[A message from The Iron Yard](http://blog.theironyard.com/2017/07/20/message-iron-yard/): In considering the current environment, the board of The Iron Yard has made the difficult decision to cease operations at all campuses after teaching out remaining summer cohorts.

## Process

[Running 4558 Tests in 1m 55sec (or Saving 50 Hours/week)](https://engineering.classdojo.com/blog/2017/05/21/Running-4558-tests-in-1m-55sec/)

[Revisiting the 12 factors, 6 years later](https://blog.codedellemc.com/2017/07/19/revisiting-12-factors-6-years-later/): The 12 factor manifesto proposed patterns and anti-patterns written to guide application architecture for the Heroku PAAS cloud.

['Abstraction' is a dirty word](https://medium.com/@pjsdev/abstract-programmers-acada09df860): We programmers have many tools at our disposal and lofty concepts we can use — but that doesn't mean we should.

[A Look into NASA's Coding Philosophy](https://mystudentvoices.com/a-look-into-nasas-coding-philosophy-b747957c7f8a): Having done work for Kennedy does not imply I'm NASA's mouthpiece. This write-up was made at a personal capacity, and came from a live talk I gave on Twitch.

[Life Is About to Get a Whole Lot Harder for Websites Without HTTPS](https://www.troyhunt.com/life-is-about-to-get-harder-for-websites-without-https/): Here's an important observation on all this: at present, we know secure pages are secure because the browser tells us so. We know non-secure pages are not secure because the browser doesn't tell us that they're secure. Get it? It's the principle of being insecure by default and that's what we're increasingly moving away from.

[On Password Managers](https://www.tbray.org/ongoing/When/201x/2017/07/16/On-Password-Managers): It has come to my at­ten­tion that peo­ple are Wrong On The In­ter­net about pass­word man­ager­s. This mat­ter­s, be­cause al­most ev­ery­body should be us­ing one.

[Verizon accused of throttling Netflix and YouTube, admits to "video optimization"](https://arstechnica.com/information-technology/2017/07/verizon-wireless-apparently-throttles-streaming-video-to-10mbps/): Verizon claims mobile video experience not affected; some customers disagree.

[Monorepos: Monoliths in Disguise](http://shiroyasha.io/monorepos-monoliths-in-disguise.html): Your project and organization are getting bigger, and you start to notice that your monolith is getting out of hand.

[How I tricked Symantec with a Fake Private Key](https://blog.hboeck.de/archives/888-How-I-tricked-Symantec-with-a-Fake-Private-Key.html): Symantec did a major blunder by revoking a certificate based on completely forged evidence. There's hardly any excuse for this and it indicates that they operate a certificate authority without a proper understanding of the cryptographic background.

[A deep dive into AWS S3 access controls — taking full control over your assets](https://labs.detectify.com/2017/07/13/a-deep-dive-into-aws-s3-access-controls-taking-full-control-over-your-assets/): Setting up access control of AWS S3 consists of multiple levels, each with its own unique risk of misconfiguration.

[Overengineering The Deployment of Static HTML With CI/CD Docker and Kubernetes](https://medium.com/@mswehli/overengineering-the-deployment-of-static-html-with-ci-cd-docker-and-kubernetes-ac0441b754ca): I recently found myself creating a CI/CD pipeline for a 3 page static html website, and to be honest, despite how long it took to setup, I think it was worth it!

[How to be proactive about performance](https://pocketgophers.com/proactive-performance/): Instrument your code, monitor its performance, and improve it where it matters most

[How I Reduced my DB Server Load by 80%](https://schneems.com/2017/07/18/how-i-reduced-my-db-server-load-by-80/)

## Tools

[Kubernetes Turns Two](https://coreos.com/blog/kubernetes-turns-two): A Look at The Numbers From This Past Year

[Ansible Silo](https://groupon.github.io/ansible-silo/): Ansible in a 100% controlled environment via Docker.

[Change in location of Ansible packages](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!msg/ansible-project/PVJlQdHCDHU/HovBfx1FBwAJ): In order to align better with Red Hat processes, the Ansible team will be making some changes in how Ansible packages are distributed to the community.

[go-pry](https://github.com/d4l3k/go-pry): An interactive REPL for Go that allows you to drop into your code at any point.

[DBHist](https://www.outcoldman.com/en/archive/2017/07/19/dbhist/): bash history in sqlite

[Eternal Terminal](https://mistertea.github.io/EternalTCP/): Eternal Terminal (ET) is a remote shell that automatically reconnects without interrupting the session.

[etcdhcp](https://github.com/lclarkmichalek/etcdhcp): A DHCP server backed by etcd

[Monospaced Programming Fonts with Ligatures](https://www.hanselman.com/blog/MonospacedProgrammingFontsWithLigatures.aspx): Typographic ligatures are when multiple characters appear to combine into a single character. Simplistically, when you type two or more characters and they magically attach to each other, you're using ligatures that were supported by your OS, your app, and your font.

[Coa](https://github.com/asciimoo/coa): Coa is a local CI tool which can be easily integrated to any project to automatically act on code changes. With Coa you can easily run automated code linters, build tools, tests or any custom project related scripts when your code changes.

[MySQL Performance Tuning](https://haydenjames.io/mysql-performance-tuning-tips-scripts-tools/): Tips, Scripts and Tools

[July 2017 Web Server Survey](https://news.netcraft.com/archives/2017/07/20/july-2017-web-server-survey.html): In the July 2017 survey we received responses from 1,767,964,429 sites and 6,593,508 web-facing computers. This represents a small gain of 1.0 million sites (+0.06%) and 71,000 computers (+1.1%).

[DEP IN 10 MINUTES](http://carolynvanslyck.com/talk/dep/lightning/#/)

[awesome-guidelines](https://github.com/Kristories/awesome-guidelines): A curated list of high quality coding style conventions and standards.

## DevOps'ish Tweet of the Week

[![DevOps'ish 033 Tweet of the Week](/images/033-devopsish-tweet-of-the-week.png)](https://twitter.com/krisnova/status/888751291802898433)
