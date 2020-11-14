+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2018"]
date = 2018-02-25T02:00:00Z
description = ""
draft = false
slug = "064"
tags = ["devops", "cloud native", "open source", "Kubernetes", "leadership", "culture", "go", "golang", "linux", "google", "docker", "password management", "containers"]
title = "064: DODCLT, {code} death knell, Leadership, Kubernetes Good and Bad, Docker and moving on from it, and More!"
image = "/064/jet-engine.jpg"
imagealt = "Travel is fatal to prejudice, bigotry, and narrow-mindedness, and many of our people need it sorely on these accounts. —Mark Twain"
imagecap = "\"Travel is fatal to prejudice, bigotry, and narrow-mindedness, and many of our people need it sorely on these accounts. —Mark Twain\""

+++

I'm fresh off the plane from [DevOpsDays Charlotte 2018](https://www.devopsdays.org/events/2018-charlotte/welcome/) when I'm writing this. I have to say a HUGE thank you to the organizers, sponsors, and speakers. [The venue was beyond amazing](https://twitter.com/editingemily/status/966735443436941317). Red Ventures knows how to host a crowd in style. I definitely feel like I need to fly out the morning after these events though. Traveling on a Friday is not ideal. It never fails that I end up missing a connection I wanted to make because I just flat out ran out of time. DevOps is a lot of things. I categorize this newsletter (and DevOps as a whole) into People, Process, and Tools. That is the order of importance; people come first. Always.

[**How to build your first GoCD continuous delivery pipeline?**](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_hacks_no_visual&utm_term=)  
This blog uses a simple web service as an example to show you how to setup your first GoCD continuous delivery pipeline and manage your build version in it. [Check out the blog](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_hacks_no_visual&utm_term=), and [get started with GoCD](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=GOCD_getting_started&utm_term=). *SPONSORED*

## Events

The good folks at Linux Expo of Southern California, Inc. are providing a 50% discount to DevOps'ish readers. Use promo code **SHORT** for 50% off registration to SCALE and DevOpsDay LA!

SCALE  
March 8-11, 2018  
[www.socallinuexpo.org](https://www.socallinuxexpo.org/scale/16x)

DevOpsDay LA  
March 9, 2018  
[devopsdays.org/events/2018-los-angeles/welcome/](https://www.devopsdays.org/events/2018-los-angeles/welcome/)

## People

Tragedy has struck an open source community. I have several friends that will be out of a job on March 2nd (with very little notice). [Dell has decided to shutter the {code} team](https://blog.thecodeteam.com/2018/02/22/final-thank-code-team/). If you need some excellent talent with open source experience reach out to these folks:

Amanda Katona: [Twitter](https://twitter.com/amanda_katona) [LinkedIn](https://www.linkedin.com/in/amandakatona)  
Andrew Kutz: [Twitter](https://twitter.com/ssakutz) [LinkedIn](https://www.linkedin.com/in/akutz)  
April Bacarro: [Twitter](https://twitter.com/a_bacarro) [LinkedIn](https://www.linkedin.com/in/aprilbacarroeventmarketing)  
Chris Duchesne: [Twitter](https://twitter.com/ChrisDuchesne) [LinkedIn](https://www.linkedin.com/in/cduchesne/)  
Clint Kitson: [Twitter](https://twitter.com/clintkitson) [LinkedIn](https://www.linkedin.com/in/clintonkitson/)  
David vonThenen: [Twitter](https://twitter.com/dvonthenen) [LinkedIn](https://www.linkedin.com/in/dvonthenen)  
Jonas Rosland: [Twitter](https://twitter.com/jonasrosland) [LinkedIn](https://www.linkedin.com/in/jonasrosland/)  
Kenny Coleman: [Twitter](https://twitter.com/kendrickcoleman) [LinkedIn](https://www.linkedin.com/in/kendrickcoleman/)  
[Kim McMahon](https://twitter.com/kamcmahon): [Twitter](https://twitter.com/kamcmahon) [LinkedIn](https://www.linkedin.com/in/kimmcmahonmarketingdirector/)  
Steve Wong: [Twitter](https://twitter.com/cantbewong) [LinkedIn](https://www.linkedin.com/in/stevewongcodeteam)  
Travis Rhoden: [Twitter](https://twitter.com/codenrhoden) [LinkedIn](https://www.linkedin.com/in/trhoden)  
Vladimir Vivien: [Twitter](https://twitter.com/VladimirVivien) [LinkedIn](https://www.linkedin.com/in/vvivien)

[Was Twitter Ever Ready for the Future?](https://medium.com/@kylierobison/was-twitter-ever-ready-for-the-future-47a2d63d9c80): Now imagine a platform where any abuser, narcissist, or predator can access their desired victim at any time, any where. With that same power, they're met with little obstacles to torment.

[Team Leader Venn Diagram](https://medium.com/making-meetup/em-el-pm-venn-diagram-764e79b42baf): A tool for gaining a shared understanding of responsibilities

[Cassandra Salisbury](https://medium.com/celebrating-bhm-33-black-womxn-in-tech/cassandra-salisbury-be550f761130), Badass Extraordinaire

["Anywhere that good judgment is not needed, the work should be automated away"](https://devops.jaxlondon.com/blog/devops-conference/awhere-good-judgment-is-not-needed-work-shoul-be-automated/): JAXenter interviews Charity Majors

[FCC chair gets 'courage under fire' award for overseeing net neutrality repeal](https://www.cnn.com/2018/02/23/politics/ajit-pai-nra-cpac-award/index.html): The FCC Chairman was given an award by the NRA this week...

## Process

[Lessons from the Cryptojacking Attack at Tesla](https://blog.redlock.io/cryptojacking-tesla): Hackers infiltrated Tesla Kubernetes consoles that were not password protected, took AWS credentials, began crypto-mining; issue now fixed

[Dropbox is filing for its IPO](https://www.cnbc.com/2018/02/23/dropbox-ipo-form-s-1-prospectus-filing-full-text.html): Their S1 reveals they saved $75M a year by hosting their own infrastructure (instead of AWS).

[Tackling the most important issue in a DevOps transformation](https://opensource.com/article/18/2/most-important-issue-devops-transformation): "You've been appointed the DevOps champion in your organisation: congratulations. So, what's the most important issue that you need to address?"

[Kubernetes is not a DevOps Cure-all](https://www.nebulaworks.com/blog/2018/02/17/kubernetes-not-devops-cure/): "Buying a tool does not equal transformation!"

[The Myth of Cloud Agnosticism](http://blog.reactiveops.com/the-myth-of-cloud-agnosticism) by Corey Quinn

[3 warning flags of DevOps metrics](https://opensource.com/article/18/2/three-warning-flags-devops-metrics): "Human beings adjust behavior based on the metrics they're held against." Choose your metrics carefully.

[The FCC's order gutting net neutrality is now official — but the fight is just getting started](https://techcrunch.com/2018/02/22/the-fccs-order-gutting-net-neutrality-is-now-official-but-the-fight-is-just-getting-started/)

[3 reasons to say 'no' in DevOps](https://opensource.com/article/18/2/3-reasons-say-no-devops)

[Securing your Linux web server](https://hackernoon.com/securing-your-linux-web-server-2be683c223eb): Going back to basics every once in a while is a good thing.

[Cloud Native Computing Foundation Announces Keynotes and Full Agenda for KubeCon + CloudNativeCon Europe in Copenhagen](http://www.cncf.io/announcement/2018/02/20/cloud-native-computing-foundation-announces-keynotes-full-agenda-kubecon-cloudnativecon-europe-copenhagen)

## Tools

[ACMEv2 and Wildcard Launch Delay](https://community.letsencrypt.org/t/acmev2-and-wildcard-launch-delay/53654): Sadness falls over the land...

[Happy 6th Birthday, Ansible](https://twitter.com/i/web/status/967116263955759104)! Also, [AnsibleFest](https://www.ansible.com/ansiblefest) is coming to Austin this year.

[Announcing Chef InSpec 2.0](http://blog.chef.io/2018/02/20/announcing-inspec-2-0/)

[Using Go as a scripting language in Linux](https://blog.cloudflare.com/using-go-as-a-scripting-language-in-linux/): "Can we take Go to the next level and use it as a scripting language for our favourite operating system, Linux?"

[jessfraz/img](https://github.com/jessfraz/img): Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder. (I can't wait to start playing with this)

[Goodbye Docker, hello Containers](https://blog.worldline.tech/2018/02/19/goodbye-docker-hello-containers.html)

[How the docker container creation process works (from docker run to runc)](https://prefetch.net/blog/2018/02/19/how-the-docker-container-creation-process-works-from-docker-run-to-runc/)

[Debugging "FROM scratch" on Kubernetes](http://ahmet.im/blog/debugging-scratch/)

[The journey from Monolith to Docker to Kubernetes: part 1](https://medium.com/@idobry/the-journey-from-monolith-to-docker-to-kubernetes-part-1-f5dbd730f620)

[Kubernetes 1.9 on a Raspberry Pi Cluster](https://harthoover.com/kubernetes-1.9-on-a-raspberry-pi-cluster/): I'm flattered that Hart Hoover referenced my Kubernetes Raspberry Pi work in building a cluster. Thanks, Hart!

[How Kubernetes became the solution for migrating legacy applications](https://opensource.com/article/18/2/how-kubernetes-became-solution-migrating-legacy-applications): You don't have to tear down your monolith to modernize it. You can evolve it into a beautiful microservice using cloud-native technologies.

[Creating a single pane of glass for your multi-cloud Kubernetes workloads with Cloudflare](https://blog.cloudflare.com/creating-a-single-pane-of-glass-for-your-multi-cloud-kubernetes-workloads-with-cloudflare/)

[Latest Intel Security News: Updated Firmware Available for 6th, 7th and 8th Generation Intel Core Processors, Intel Xeon Scalable Processors and More](https://newsroom.intel.com/news/latest-intel-security-news-updated-firmware-available/)

[Choosing a tool to track and mitigate open source security vulnerabilities](https://www.oreilly.com/ideas/choosing-a-tool-to-track-and-mitigate-open-source-security-vulnerabilities)

[BPF comes to firewalls](https://lwn.net/Articles/747551/)

[Wehe](https://dd.meddle.mobi/) uses your device to exchange traffic recorded from real, popular apps like YouTube and Spotify---effectively making it look as if you are using those apps. As a result, if an ISP tries to slow down an YouTube, our app would see the same behavior.

[[kata-dev] Kata with AMD Secure Encrypted Virtualization (SEV)](http://lists.katacontainers.io/pipermail/kata-dev/2018-February/000029.html)

[Caddy 0.10.11 Released with Distributed Auto-HTTPS and Service Discovery](https://caddyserver.com/blog/caddy-0_10_11-released)

[ahnick/encpass.sh](https://github.com/ahnick/encpass.sh): Lightweight solution for using encrypted passwords in shell scripts

[duo-labs/cloudmapper](https://github.com/duo-labs/cloudmapper): CloudMapper creates network diagrams of AWS environments

## DevOps'ish Tweet of the Week

{{< tweet 965857172117737472 >}}
