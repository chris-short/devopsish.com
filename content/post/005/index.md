+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = "2017-01-08T05:34:47.583Z"
description = ""
draft = false
slug = "005"
tags = ["devops", "cloud native", "open source", "programming", "ntp", "containers"]
title = "005: Week of 1483851600"
image ="https://shortcdn.com/file/devopsish/snowy-street.jpg"
imagealt = "Snowy Street"
aliases = [
    "005-week-of-1483851600-baf4700357e3"
]

+++

Oh the weather outside is frightful,

But the [**DevOps**](https://devopsish.com/) is so delightful,

And since we've no place to go,

Let It Snow! Let It Snow! Let It Snow!

This song has been in my head all day as the US east coast has been coated in a blanket of frozen participation. We have not taken down our interior Christmas decorations yet either so that might be part of it too.

## Department of Choice Concepts

[Vladimir Vivien](https://medium.com/learning-the-go-programming-language/why-i-wrote-a-book-on-go-programming-b67aa5d3067b#.utvbksmbn) wrote a book on Go. [*Learning Go Programming*](https://vladimirvivien.github.io/learning-go/) was written over the course of a year and a half and is an attempt to make it easier for newcomers. I bought it and intend to read it.

## Department of Dafuq

[When I mentioned the leap second last week](/004/) I was hoping it would go off without a hitch. That was not the case when Cloudflare had a [globally impacting issue with its RRDNS software](https://blog.cloudflare.com/how-and-why-the-leap-second-affected-cloudflare-dns/). Developers have a hard job, I believe all of us in [DevOps](https://devopsish.com/) recognize that. But, this is a good example of how [an assumption caused a big problem](https://chrisshort.net/take-ownership-plant-your-flag/).

## Department of Data Defense

Three hours after the New Year's leap second, Ask Bjørn Hansen reported that [only 26% of servers](https://community.ntppool.org/t/leap-second-2017-status/59) in the [NTP pool](http://www.pool.ntp.org/en/) were not announcing the leap second. That is not that great but given that the bar to enter the pool is quite low it is not surprising.

You know it's bad when The Register is talking about it. [There are 25,000 publicly exposed MongoDB systems out on the Internet](http://www.theregister.co.uk/2017/01/04/mongodb_installs_wiped_by_bitcoin_ransoming_script/) and about 2,000 of them have been taken over by ransomware. I am shaking my head vigorously. Are these MongoDB admins the same people heralding "serverless" (did I go too far there)? If you happen to be a victim make sure you confirm [whether or not the ransomware is a hoax](https://www.databreaches.net/dont-pay-the-mongodb-ransom-until-you-check-to-see-if-its-a-scam/).

## Department of Discussions

Ansible is launching a single day global conference tour called [Ansible Automates](https://www.ansible.com/automates). What is it? Ansible Automates is, "one-track conference that takes the best Ansible content and presents it to regional audiences around the world... we expect crowds of 200–400 people who are interested in learning more about IT automation solutions with Ansible..." Ansible Automates might be an answer to some feedback I provided after AnsibleFest Brooklyn. I did not really like the four track conference because I knew I was missing good content elsewhere.

[Jess Frazelle](https://blog.jessfraz.com/) is [looking for underrepresented folks (minorities, women, veterans, etc.) who want help speaking at conferences this year](https://twitter.com/jessfraz/status/815946957474721796). If you want to get up in front of a group of people and share your experience but want some guidance let Jess know by e-mailing jess at linux dot com.

## Department of Refreshment and Refurbishment

NTPsec is an effort to streamline and optimize the core NTP code into a sustainable effort for a critical core function of the Internet. The project is seriously [considering a move away from C](https://blog.ntpsec.org/2017/01/03/getting-past-c.html) and the post about it is absolutely fascinating.

[OpenEBS is a block storage solution for container environments](https://blog.openebs.io/openebs-the-containerized-storage-f76e394a9543#.tie13be63). It features "Virtual Storage Machines, a concept similar to k8s PODs." It seems pretty straight forward. But will it take off, get sucked up by another project, or be bought and added to the portfolio of another larger product line?

The highly publicized death of Flocker left some folks in a lurch. Thankfully the [{code} by Dell/EMC](http://codedellemc.com/) folks have [a solution with their REX-Ray product](https://blog.codedellemc.com/2017/01/06/migrate_flocker_drivers_rexray/).

[Truffle Hog](https://github.com/dxa4481/truffleHog) searches through git repositories for high entropy strings, digging deep into commit history and branches. This is effective at finding secrets accidentally committed that contain high entropy.
