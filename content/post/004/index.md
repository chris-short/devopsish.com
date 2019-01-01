+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-01-01T08:02:01.322Z
description = ""
draft = false
slug = "004"
tags = ["devops", "cloud native", "open source", "linux", "ansible", "hashicorp"]
title = "004: Week of 1483246800"
image = "/004/fireworks-over-downtown.jpg"
imagealt = "2016 has come to an end. For auld lang syne, my dear!"
aliases = [
    "004-week-of-1483246800-f780b9b00f3"
]

+++

2016 has come to an end. For auld lang syne, my dear!

2016 has gotten a pretty bad rap (deservedly so, in my opinion). Let's try to leave the past where it is, dump the negative energy, and wake up to new opportunities.

I like this time of year for the wrap-up pieces and year in reviews. Here are a few that I enjoyed this week:

* [Predictions for DevOps in 2017](https://dzone.com/articles/predictions-for-devops-in-2017-1)

* [5 DevOps predictions for 2017](http://www.techrepublic.com/article/5-devops-predictions-for-2017/)

* [In 2017, I'm going to stop watching the news](https://ma.ttias.be/stop-watching-news/)

* [What I Learned in 2016](https://chrisshort.net/what-i-learned-in-2016/)

{{< mc >}}

## Department of Next Year's Old Tech

Please, for the love of God, do not let leap seconds bite you in the ass ever again. Percona has a great piece for getting this problem solved: [Don't Let a Leap Second Leap on Your Database!](https://www.percona.com/blog/2016/12/27/prepare-for-the-new-leap-second/)

## Department of Choice Concepts

[Julia Evans](https://jvns.ca/) wrote a fantastic article (and comic), [How to ask good questions](https://jvns.ca/blog/good-questions/). Essentially good questions come from the need to plug information gaps, not from a complete lack of knowledge. Do your research then confirm what you need confirmed. This is a skill more people need to solidify.

I wrote a piece on [Ansible Vault](https://opensource.com/article/16/12/devops-security-ansible-vault) for opensource.com. Ansible Vault is a super simple solution to encrypting files and variables natively in Ansible. It is not [Hashicorp's Vault](https://www.vaultproject.io/) (don't confuse the two) but Ansible Vault is **very** handy.

[Jeff Geerling](http://www.jeffgeerling.com/) wrote up a great piece on [why he closes pull requests for his open source projects](http://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes). It is a pretty simple concept, they are his projects that he uses. If your PR is not useful to the intended use case it is generally closed. Submitting upstream is not a right; fork and go.

## Department of Dafuq

The Linux Foundation has created a credit card (yeah... so weird). [The Linux Credit Card](https://www.linuxfoundation.org/offerings/linux-credit-card) page states, "For every card activation, the Linux Foundation will receive $50 as well as a percentage of every purchase made with the Linux credit card." I am scratching my head on this one.

## Department of Data Defense

CVE Details has a run down for the [Top 50 Vendors By Total Number Of "Distinct" Vulnerabilities in 2016](http://www.cvedetails.com/top-50-vendors.php?year=2016). Shockingly Microsoft is #4. Linux is #12.

## Department of Refreshment and Refurbishment

{{< tweet 815144386434568193 >}}

Joel Sing pointed out this week that [migrating to OpenSSL 1.1 is really (unnecessarily) hard](https://www.mail-archive.com/tech@openbsd.org/msg36437.html). I have to agree, it should not be as hard as he describes. Want a good example? Compile nmap configured to use OpenSSL 1.1.

## Tweet of the Week

{{< tweet 814871794649808896 >}}
