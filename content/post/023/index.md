+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-05-14T06:01:00.902Z
description = ""
draft = false
slug = "023"
tags = ["devops", "cloud native", "open source", "database", "intel"]
title = "023: Week of 1494734400"
image = "/023/jumpman.jpg"
imagealt = "Get It?"
aliases = [
    "devopsish-023-week-of-1494734400-a913ad9dfa6a"
]

+++

I have to admit, I am really, really angry this week. For the first time in a long time a worm was unleashed on the web. A little back story. Years ago, the NSA found a vulnerability in Windows. Instead of disclosing the vulnerability responsibility to Microsoft, the NSA decided to keep the vulnerability a secret. Years pass and NSA is happily using this zero-day to exploit the United States' various enemies. Then, one day, several exploits are found on a server somewhere by [The Shadow Brokers](https://en.wikipedia.org/wiki/The_Shadow_Brokers?ref=devopsish). The Shadow Brokers then released the exploits they discovered.

Fast forward to this week and [the WannaCry exploit](https://www.us-cert.gov/ncas/alerts/TA17-132A?ref=devopsish) is unleashed on the web. [The UK's NHS was the first major victim](https://www.theguardian.com/society/live/2017/may/12/england-hospitals-cyber-attack-nhs-live-updates?ref=devopsish). Rapidly the [WannaCry tidal wave was washing over 99 countries](http://money.cnn.com/2017/05/12/technology/ransomware-attack-nsa-microsoft/index.html?ref=devopsish). Meanwhile, back in the UK, [a researcher discovers that there is a kill switch in the exploit](https://www.malwaretech.com/2017/05/how-to-accidentally-stop-a-global-cyber-attacks.html). Apparently, the NSA put a kill switch is in place in case the worm accidentally went public (WHICH IT DID). The kill switch, was a check to see if a specific domain existed; not responding with a 200, not having a specific payload or string, nothing! Just whether or not a domain was REGISTERED controlled the worm! The NSA didn't think to spend the $11 to kill the worm. But, a 22-year-old in the UK saved billions of dollars and probably lives with $11 while *the NSA maintained its horrific negligence*. Unconscionable!

[**Security Newsletter: weekly digest of security news**
](https://securitynewsletter.co/?utm_source=devopsish&utm_medium=email&utm_campaign=devopsish1)  
Weekly e-mail that condenses last week's security news into about 10 items worth knowing about. *SPONSORED*

## Department of Choice Concepts

[CPU Utilization is Wrong](http://www.brendangregg.com/blog/2017-05-09/cpu-utilization-is-wrong.html) (Brendan Gregg)

[hobby-kube](https://github.com/hobby-kube/guide?ref=devopsish): A guide to Kubernetes clusters for the hobbyist

[How To Host a Website with Caddy on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-host-a-website-with-caddy-on-ubuntu-16-04?ref=devopsish) (Digital Ocean)

Want a print copy of Daniel Stenberg's *Everything curl*? [Express your interest here](https://daniel.haxx.se/blog/2017/05/10/everything-curl-printed/?ref=devopsish)!

One of the first steps in DevOps is to understand the need for some failures and learn from them. [Why Failure is Critical to DevOps Culture](http://www.informationweek.com/devops/why-failure-is-critical-to-devops-culture/a/d-id/1328830?ref=devopsish) by Jason Hand.

[Announcing the Modern Incident Resolution Lifecycle](https://www.pagerduty.com/blog/modern-incident-resolution-lifecycle/?ref=devopsish) (PagerDuty)

## Department of Data Defense

[OpenVPN has been thoroughly audited and the discovered vulnerabilities have been patched](https://ostif.org/the-openvpn-2-4-0-audit-by-ostif-and-quarkslab-results/?ref=devopsish). It is good to see audits not finding horrific issues. It's even more reassuring when it's a project as relied upon as OpenVPN.

[Hackers Came, but the French Were Prepared](https://www.nytimes.com/2017/05/09/world/europe/hackers-came-but-the-french-were-prepared.html?ref=devopsish) (New York Times)

This is too good not to share. Troy Hunt's "[Reckon you've seen some stupid security things? Here, hold my beer...](https://www.troyhunt.com/reckon-youve-seen-some-stupid-security-things-here-hold-my-beer/)" is a crying laughing/sad series of security missteps. What's the worst security faux pas you've witnessed?

[Intel's Management Engine is a security hazard, and users need a way to disable it](https://www.eff.org/deeplinks/2017/05/intels-management-engine-security-hazard-and-users-need-way-disable-it?ref=devopsish) (EFF)

## Department of Refreshment and Refurbishment

[GoSolar](https://github.com/mrxinu/gosolar?ref=devopsish) is a SolarWinds client library written in Go. It allows you to submit queries to the SolarWinds Information Service (SWIS) and do various other things.

[Gixy](https://github.com/yandex/gixy?ref=devopsish) is a tool to analyze Nginx configuration. The main goal of Gixy is to prevent security misconfiguration and automate flaw detection.

[k6 is an open-source load testing tool for testing the performance of your systems](https://k6.io/).

[Microsoft's Build 2017 developer conference was this week and there were several DevOps worthy nuggets](http://venturebeat.com/2017/05/10/microsoft-introduces-azure-cosmos-db-a-globally-distributed-database-with-5-consistency-choices/):

* Microsoft introduces Azure Cosmos DB, a globally distributed database with 5 consistency choices

* Azure Cloud Shell provides an authenticated, browser-based shell experience accessible from anywhere.

* Microsoft announced, will be Azure Database for MySQL and Azure Database for PostgreSQL options in Azure.

* Microsoft is offering Storage Service Encryption for Azure Files on all available redundancy types at no additional cost.

* [Linux is coming to the Windows Store](http://www.businessinsider.com/microsoft-store-gets-ubuntu-suse-fedora-linux-2017-5?ref=devopsish). Yes. Ubuntu, Fedora, and Suse will all be downloadable on Windows 10.

## Department of Discussion

Did everyone have a conference this week?!? OSCON, OpenStack Summit Boston, Microsoft Build, and Dell EMC World all took place this week. I saw the most activity around OSCON on Twitter. Surprisingly, Microsoft Build kept popping up in my Twitter stream frequently. As far as buzz, OSCON won the week though. [Highlights from OSCON are available](https://www.oreilly.com/ideas/highlights-from-oscon-austin-2017?ref=devopsish).

Coming up this week, I am co-hosting the [Triangle DevOps](https://tridevops.com/) Meetup this Wednesday, May 17th. Nirmal Mehta will be presenting, "I Got 99 Problems But Technology Ain't One" at 7 PM. [RSVP today if you are interested in going](https://www.meetup.com/Triangle-DevOps/events/238883192/?ref=devopsish).

I have been invited to speak at [Open Source South Carolina](https://www.meetup.com/Open-Source-South-Carolina/events/239747095/?ref=devopsish) on Tuesday, May 23rd at 6:00 PM. I will be doing an extended DevOps 101 complete with deployment demonstration. If you are in or around Columbia, SC come join me!

[DevOpsDays Raleigh](https://www.devopsdays.org/events/2017-raleigh/welcome/?ref=devopsish) is September 7th and 8th. The CFP closes May 15th!!! [Propose your talk ASAP](https://www.devopsdays.org/events/2017-raleigh/propose/?ref=devopsish)! We are looking forward to seeing y'all this fall.

## Department of Interior

The other day my Vice President asked me a question, "[What would it take to turn a good SysAdmin into a DevOps engineer?](https://chrisshort.net/sysadmin-to-devops-six-months/?ref=devopsish)" He followed it up with, "Don't spend more than ten minutes thinking about it." I spent WAY more than ten minutes on it.

The next volume in the [Open Organization](https://opensource.com/open-organization) book series, "Guide to IT Culture Change: Open principles and practices for a more innovative IT department" comes out June 2nd. [Register now](https://opensource.com/open-organization/resources/book-series?ref=devopsish) to be notified when it's available.

## Department of Sane Workplaces

GitHub has created a [Code of Conduct tool](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/?ref=devopsish). Adding a Code of Conduct to your project has never been easier.

[The Engineer/Manager Pendulum](https://charity.wtf/2017/05/11/the-engineer-manager-pendulum/?ref=devopsish) (Charity Majors)

## Not DevOps But Still Cool

[The inventor of the web Tim Berners-Lee on the future of the internet, 'fake news,' and why net neutrality is so important](http://www.businessinsider.com/mathias-dopfner-tim-berners-lee-world-wide-web-interview-2017-5?ref=devopsish) (Business Insider)

[Net neutrality: why the next 10 days are so important in the fight for fair internet](https://www.theguardian.com/technology/2017/may/09/what-is-net-neutrality-fcc-vote-why-it-matters?ref=devopsish) (The Guardian)

## DevOps'ish Tweet of the Week

{{< tweet 862674035745882113 >}}
