+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-09-10T06:01:00.779Z
description = ""
draft = false
slug = "040"
tags = ["devops", "cloud native", "open source", "observability", "detroit", "solaris", "containers"]
title = "040: Solaris, Observability, Shift Left, Ansible, and More"
image = "/040/gonza-tacos-y-tequila.jpg"
imagealt = "Live and Direct from Gonza Tacos y Tequila on Hillsborough St. in Raleigh, NC"
aliases = [
    "devopsish-040-solaris-observability-shift-left-ansible-and-more-105ad2da1a4c"
]
+++

This week I finished a project that has been in the works for a quite some time. Back before I moved to Detroit but shortly after taking over [Triangle DevOps](https://tridevops.com/), I was offered (and accepted) a spot as a [DevOpsDays Raleigh](https://www.devopsdays.org/events/2017-raleigh/welcome/) organizer. I submitted three talks to the event and one was accepted. Today I opened the event with my talk, "[The Dark Side of DevOps](https://speakerdeck.com/chrisshort/the-dark-side-of-devops)" and thoroughly enjoyed it as well as all the other talks at the event. Huge shout out to the other organizers, volunteers, and speakers for all their hard work in making the second DevOpsDays Raleigh better than the first one. It was great to catch up with friends while I was in town. Back to Detroit for me but what a week for news in general and DevOps!

**GoCD — open source continuous delivery server**  
GoCD is a continuous delivery tool specializing in advanced workflow modeling and dependency management. It lets you track a change from commit to deploy at a glance, providing superior visibility into your workflow. [It's open source, free to use and download](https://www.gocd.org/?utm_campaign=devops_newsletter&utm_medium=email&utm_source=devopsish&utm_content=go_website&utm_term=). *SPONSORED*

**All Things Open 2017**  
October 23 and 24, Raleigh, NC USA
2,500–3,000+ technologists will descend upon the City of Oaks to attend 200+ sessions from nearly as many speakers. Representative from nearly every major technology company in the U.S. will be in attendance as well.
To get 20% off enter code ***DevOpsish20*** when registering to attend.
Website: [https://allthingsopen.org](https://allthingsopen.org)
To Register: [https://allthingsopen.org/register-now](https://allthingsopen.org/register-now)


## People

[Dave Cheney joined Heptio](https://dave.cheney.net/2017/09/06/why-i-joined-heptio) this week. The reason why is pretty awesome.

[Reddit co-founder is latest tech executive to take parental leave](https://www.washingtonpost.com/news/the-switch/wp/2017/09/05/reddit-co-founder-is-latest-tech-executive-to-make-a-public-stand-for-parental-leave/?utm_term=.c0fa18095e75)

[The sudden death and eternal life of Solaris](http://dtrace.org/blogs/bmc/2017/09/04/the-sudden-death-and-eternal-life-of-solaris/): I still loathe Oracle

[Software as a Coloring Book](https://www.coderscoloringbook.com/): A new study tool for students and programmers.

## Process

[The hackers who broke into Equifax exploited a flaw in open-source server software](https://qz.com/1073221/the-hackers-who-broke-into-equifax-exploited-a-nine-year-old-security-flaw/)

[Solaris to Linux Migration 2017](http://www.brendangregg.com/blog/2017-09-05/solaris-to-linux-2017.html): Many people have contacted [Brendan Gregg](http://www.brendangregg.com/blog/index.html) recently about switching from Solaris (or illumos) to Linux, especially since most of the Solaris kernel team were [let go](https://www.theregister.co.uk/2017/09/04/oracle_layoffs_solaris_sparc_teams/) this year.

[Move Your Bugs to the Left](http://samwho.co.uk/blog/2017/09/06/move-your-bugs-to-the-left/): We all want to ship bug-free software. No-one wants to be the person that introduced a show-stopping bug the week before release.

[You can't buy DevOps, but you may need to sell it](https://www.gocd.org/2017/09/05/misconceptions-patterns-devops-adoption.html): Misconceptions and Patterns to drive DevOps Adoption

[Monitoring and Observability](https://medium.com/@copyconstruct/monitoring-and-observability-8417d1952e1c) by Cindy Sridharan: What is the difference between "monitoring" and "observability", if any? Or is the latter just the latest buzzword on the block, to be flogged and shoved down our throats until it has been milked for all its worth?

[Debugging netlink requests](https://jvns.ca/blog/2017/09/03/debugging-netlink-requests/) and [Finding out if/why a server is dropping packets](https://jvns.ca/blog/2017/09/05/finding-out-where-packets-are-being-dropped/) by Julia Evans

[In Search of a Secure Time Source](https://blog.hboeck.de/archives/890-In-Search-of-a-Secure-Time-Source.html): All our computers and smartphones have an internal clock and need to know the current time. As configuring the time manually is annoying it's common to set the time via Internet services. What tends to get forgotten is that a reasonably accurate clock is often a crucial part of security features like certificate lifetimes or features with [expiration times like HSTS](https://www.youtube.com/watch?v=eLhb4jZuv6M). Thus the timesetting should be secure — but usually it isn't.

[Systemd on Ubuntu 16.04 can't (or won't) reliably reboot your server](https://utcc.utoronto.ca/~cks/space/blog/linux/SystemdUbuntuRebootFailure): On some servers, usually the busiest and most important ones, the system will just stop during the shutdown process and sit there. And sit there. And sit there.

## Tools

[Internet Protocol version 10 (IPv10) Specification](https://tools.ietf.org/html/draft-omar-ipv10-06.html): IP version 10 (IPv10) is a new version of the Internet Protocol, designed to allow IP version 6 to communicate to IP version 4 (IPv4) and vice versa.

[Ansible AWX](https://opensource.com/article/17/9/ansible-announces-awx-open-source-project): The code behind Ansible Tower, an IT automation engine for cloud provisioning, configuration, deployment, and orchestration, is now open source.

[geerlingguy.awx](https://galaxy.ansible.com/geerlingguy/awx/): Installs and configures AWX (Ansible Tower's open source version).

[The secret sauce behind Amazon Route53](https://read.acloud.guru/the-secret-sauce-behind-amazon-route53-dae2573293c6) by Corey Quinn: Simplifying the basics of Amazon's complex DNS solution

[CFire](https://rhinosecuritylabs.com/cloud-security/cloudflare-bypassing-cloud-security/): Evading CloudFlare Security Protections

[NGINX Unit](https://www.nginx.com/products/nginx-unit/) is a new, lightweight, open source application server built to meet the demands of today's dynamic and distributed applications.

[AWS Network Load Balancer (NLB)](https://aws.amazon.com/blogs/aws/new-network-load-balancer-effortless-scaling-to-millions-of-requests-per-second/): Effortless Scaling to Millions of Requests per Second

[Idyll](https://idyll-lang.github.io/) is a tool that makes it easier to author interactive narratives for the web. The goal of the project is to provide a friendly markup language — and an associated toolchain — that can be used to create dynamic, text-driven web pages.

[freebsd-docker/containerd](https://github.com/freebsd-docker/containerd): An open and reliable container runtime now on FreeBSD

[hatch](https://github.com/ofek/hatch): A modern project, package, and virtual env manager for Python

[Non-privileged containers based on the scratch image](https://medium.com/@lizrice/non-privileged-containers-based-on-the-scratch-image-a80105d6d341) by Liz Rice

[On Disk IO, Part 1: Flavours of IO](https://hackernoon.com/on-disk-io-part-1-flavours-of-io-8e1ace1de017)

[Time for Makefiles to Make a Comeback](https://medium.com/@jolson88/its-time-for-makefiles-to-make-a-comeback-36cbc358bb0a)

[northwesternmutual/kanali](https://github.com/northwesternmutual/kanali): An extremely efficient Kubernetes ingress controller with robust API management capabilities.

## Jobs

[**DevOps/Cloud Systems Engineer — StockX — Detroit, MI**](https://stockx.com/jobs#op-193701-devopscloud-systems-engineer)
StockX is looking for an experienced Cloud Systems Engineer, or DevOps Engineer, to accelerate the efficiency of our engineering operations and implement scalable infrastructure. You must be passionate about automating all the things that go into software engineering and technical operations.

[**Director, Software Engineering — Bankrate — Detroit, MI**](http://app.jobvite.com/m?3N1q0jw2)
A manager in an agile environment with strong technical skills. Collaborative leader who will understand our people, business, technology, and customers' needs. Leader who helps drive our culture of empowerment, ownership, and accountability to help develop our team technically and professionally. Identify and successfully implement improvements in our engineering processes, tools, and architecture to enable us to deliver on our key initiatives.

## DevOps'ish Tweet of the Week

{{< tweet 905109172953513985 >}}
