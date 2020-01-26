+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2017"]
date = 2017-02-12T16:55:14.962Z
description = ""
draft = false
slug = "010"
tags = ["devops", "cloud native", "open source", "database", "containers"]
title = "010: Week of 1486857600"
image = "/010/edinburgh-scotland-feb-2017.jpg"
imagealt = "Edinburgh, Scotland, United Kingdom — 11 Feb 2017"
aliases = [
    "devopsish-weekly-010-week-of-1486857600-28889c38fd68"
]

+++

It has been a very busy week for me. I have been in Scotland since Tuesday. Jet lag is a real thing but, I have to say I have met some of the nicest people here (and I am a Southerner). As far as [**DevOps**](https://devopsish.com/) this week, I have been head down DevOps'ing. I have also been building bridges between teams in our global company. It is very exciting and despite constantly being tired the connections are happening.

## Department of Choice Concepts

The OpenShift Developer Evangelist Team announced this week that they are [releasing OpenShift tutorials](https://blog.openshift.com/announcing-easy-interactive-openshift-tutorials-developers/) targeting developers. They have teamed up with Katacoda and the first tutorial is [Getting Started with OpenShift for Developers](https://openshift.katacoda.com/introduction/getting-started/).

[philippta](https://github.com/philippta) has released a handful or two of great [*Go Web Examples](https://gowebexamples.github.io/). *The goal is to show simple code snippets to handle common functions with Go.

## Department of Data Defense

[GitLab released their detailed postmortem](https://about.gitlab.com/2017/02/10/postmortem-of-database-outage-of-january-31/) on [last week's](/009/) outage. Two big takeaways: 1) they freely admit their database infrastructure is lacking. 2) A GitLab engineer accidentally started to delete the primary database. Their openness is a breath of fresh air.

Speaking of databases, Mikhail Chinkov reminded us this week that [just because you can run a database in a container doesn't mean you should](https://myopsblog.wordpress.com/2017/02/06/why-databases-is-not-for-containers/). The world has determined that stateless things are great for containers (truth). Why on earth would you put your state in a tool that you designed your stateless infrastructure around?

The Australian Signals Directorate has released some refreshing blunt InfoSec advice. Their [Top 4 and Top 8 lists](http://www.asd.gov.au/infosec/mitigationstrategies.htm) are must reads. At least bookmark them so you can take it to your leadership should you ever need to.

## Department of Discussion

[Erika Heidi](http://erikaheidi.com/) conducted research into [how people utilize Vagrant](http://erikaheidi.com/blog/vagrant-usage-research-2017). Of the 691 responses, Ansible and VirtualBox come in as heavy hitters for provisioners and providers. Ubuntu is the most used OS.

## Not DevOps But Still Cool

[takeover.sh](https://github.com/marcan/takeover.sh) was released this week. It promises to be able to, "Wipe and reinstall a running Linux system via SSH, without rebooting." A crafty idea but I have not attempted to try it yet. YMMV.

## DevOps'ish One-Liner of the Week

Do you have an AWS API key that has more rights than your personal login does? Here is a good way to get into the AWS console with that API key:

    aws --profile <PROFILE> iam create-login-profile --user-name <USERNAME> --password <PASSWORD> --password-reset-required
