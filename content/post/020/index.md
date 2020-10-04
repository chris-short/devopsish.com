+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2017"]
date = 2017-04-23T12:39:39.310Z
description = ""
draft = false
slug = "020"
tags = ["devops", "cloud native", "open source", "linux", "google", "go", "docker", "moby", "lambda"]
title = "020: Week of 1492920000"
image = "/020/docker-moby-wtf.png"
imagealt = "Docker, Moby, Captain Ahab, Huh?"
aliases = [
    "devopsish-weekly-020-week-of-1492920000-65abf362f4f0"
]

+++

Not quite sure what Docker is doing? Few people are. Docker is still Docker except when it's [Moby](https://mobyproject.org/). Moby is open source and Docker isn't (kind of). According to the [official Moby Project announcement](https://blog.docker.com/2017/04/introducing-the-moby-project/), Moby Project is **NEW**! But, Moby Project is actually the new [upstream](https://chrisshort.net/upstream-vs-downstream/) for the Docker project. Interestingly enough, the Moby Project exists to create "An open framework to assemble specialized container systems without reinventing the wheel." (Emphasis added.) The best analysis of the whole S.N.A.F.U. [fittingly comes from The Register](https://www.theregister.co.uk/2017/04/21/docker_renames_open_source_code_moby/).

I used [Comic Sans](https://en.wikipedia.org/wiki/Comic_Sans) in the above image because this is a PR fustercluck. The worst part of the announcement was that it was timed REALLY poorly (or not at all). I learned of it when I click a GitHub issue for Docker and it took me to [github.com/moby/moby/issues/4717](https://github.com/moby/moby/issues/4717). I legitimately thought something was horribly wrong with GitHub. Nope! All the branding shenanigans appeared to happen all at once during DockerCon.

Containers are hard to explain to people because [containers aren't really a thing](https://blog.jessfraz.com/post/containers-zones-jails-vms/). Linux containers are a combination of pre-existing Linux kernel components. The Founder of Docker, Solomon Hykes, [tweeted out two sketches to explain the Moby Project](https://twitter.com/solomonstre/status/855918630915133440). The fact that this was necessary shows how awkward this is to explain. Now, the container waters are even muddier than they already were by this rough re-branding effort.

## Department of Choice Concepts

[Mini-Guide to Google's Golang and Why It's Perfect for DevOps](https://blog.bluematador.com/posts/mini-guide-google-golang-why-its-perfect-for-devops/)

[MIT no longer owns 18.0.0.0/8](https://ma.ttias.be/mit-no-longer-owns-18-0-0-08/): MIT is [selling off it's IPv4 block to fund its transition to IPv6](https://gist.github.com/simonster/e22e50cd52b7dffcf5a4db2b8ea4cce0).

[What's Wrong With Open Source Telegram?](https://yalantis.com/blog/whats-wrong-telegram-open-api/) Apparently a lot!

## Department of Refreshment and Refurbishment

[Announcing LinuxKit: A Toolkit for Building Secure, Lean AND Portable Linux Subsystems](https://blog.docker.com/2017/04/introducing-linuxkit-container-os-toolkit/) ([GitHub](https://github.com/linuxkit/linuxkit))

[Digitial Rebar Provision](https://github.com/digitalrebar/provision) looks to be an awesome replacement to the venerable Cobbler.

Here is a handy reference for enterprise Linux distros' life cycles: [linuxlifecycle.com](https://linuxlifecycle.com/?utm_source=cronweekly.com)

## Department of Data Defense

[Red Hat Suffers Massive Data Center Network Outage](https://linux.slashdot.org/story/17/04/21/1623233/red-hat-suffers-massive-data-center-network-outage)

Friend of DevOps'ish [Mattias Geniar has officially launched DNS Spy](https://ma.ttias.be/dns-spy-launched/)! In case you don't recall, [back in 2013, several news and media websites were hacked by exploiting their domain name registrars](http://readwrite.com/2013/08/27/new-york-times-twitter-huffpo-hacked-syrian-electronic-army/). [**DNS Spy**](https://dnsspy.io/) will alert you almost immediately to any changes to your DNS records. This could indicate something is afoot or, at the very least, misconfigured.

[LWN.net has a fantastic analysis of a talk at KubeCon 2017 that covers security in Kubernetes](https://lwn.net/SubscriberLink/720215/867f710e3d145b55/).

According to Akamai, [Connectionless LDAP is being exploited in a new breed of DDoS attack](http://www.darkreading.com/attacks-breaches/new-breed-of-ddos-attack-on-the-rise/d/d-id/1328620).

[Linux Container Hardening](https://containerhardening.org/): "This project will focus on hardening of Linux containers. It will help contribute patches to the [Kernel Self Protection Project](https://kernsec.org/wiki/index.php/Kernel_Self_Protection_Project) that evolve the primitives in the Linux kernel used by containers (namespaces, cgroups, etc) to be more secure."

## Department of Happy Little Clouds

[AWS Lambda Supports Python 3.6](https://aws.amazon.com/about-aws/whats-new/2017/04/aws-lambda-supports-python-3-6/)

[AWS CodeStar](https://aws.amazon.com/codestar/) is a [cloud service designed to make it easier to develop, build, and deploy applications on AWS by simplifying the setup of your entire development project](https://aws.amazon.com/blogs/aws/new-aws-codestar/).

![Get this awesome shirt at [runk8s.io](https://runk8s.io/)](/020/run-k8s-tshirt.jpg)  
*Get this awesome shirt at [runk8s.io](https://runk8s.io/)*

[Ubuntu on AWS gets serious performance boost with AWS-tuned kernel](https://insights.ubuntu.com/2017/04/05/ubuntu-on-aws-gets-serious-performance-boost-with-aws-tuned-kernel/)

## Department of Woke Workplaces

[The newest Silicon Valley perk? Paid time off to protest Trump.](https://www.washingtonpost.com/news/business/wp/2017/04/18/the-newest-silicon-valley-perk-paid-time-off-to-protest-trump/?utm_term=.3d2e13c39de5)

A great episode of a great podcast with friend, Ashley McNamara, talking about her new job, being a woman and mom in the world today, and how to become a coder. [Go Time 43: Getting Better, Mentoring, and Drawing Gophers with Ashley McNamara](https://overcast.fm/+GnKbwnxKI)

## Department of Story Time

This [Microsoft Flight Simulator support case](https://blogs.msdn.microsoft.com/oldnewthing/20170418-00/?p=95985) reminds me of a call I answered when I worked at a dial-up ISP. The customer called in late at night to figure out why he couldn't get online. It was late but, I was in the office because of a bad thunderstorm potentially affecting phone lines, modems, etc. I went through several troubleshooting steps only to find out that there was nothing being displayed on his monitor. When I asked if his monitor was turned on he informed me the power was out due to the storm. I was dumbfounded that this seemingly intelligent human did not realize his computer wasn't powered by the phone line. He asked, "If I can call you, why can't I get online?" I can't...

## DevOps'ish Tweet of the Week

Putting the period on the end of the Docker/Moby change:

> How many times can you open source a project?
> One.
> But I'll just change the...
> One.
>
> — Jessie Frazelle (@jessfraz) April 19, 2017
