+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2016"]
date = 2016-12-18T00:00:00Z
description = "It was the week before Christmas 🤶 🎅 and all through the DevOps world not a creature was stirring not even a mouse 🖱."
draft = false
slug = "002"
tags = ["devops", "cloud native", "open source", "kubernetes", "linux", "github", "google", "containers", "Docker", "containerd"]
title = "002: Week of 1482037200"
image = "/002/santa-ice-skating.jpg"
imagealt = "It was the week before Christmas 🤶 🎅 and all through the DevOps world not a creature was stirring not even a mouse 🖱."
aliases = [
    "002-week-of-1482037200-51127c20054b"
]

+++

It was the week before Christmas 🤶 🎅 and all through the [**DevOps**](https://devopsish.com/) world not a creature was stirring not even a mouse 🖱.

Hardly... You might be in a change freeze but the open source world is a glow with many gifts under the tree this week.

## Department of Refreshment and Refurbishment

Linus' gift to the DevOps world came in the form of [Kernel 4.9](http://www.mail-archive.com/linux-kernel@vger.kernel.org/msg1290645.html). This is a large release coming in at about [22.3 million lines according to Michael Larabel](http://www.phoronix.com/scan.php?page=news_item&px=Linux-4.9-Git-Stats) with, "[a bit over two thirds drivers](http://www.mail-archive.com/linux-kernel@vger.kernel.org/msg1290645.html)".

[Kubernetes 1.5 is out](http://blog.kubernetes.io/2016/12/kubernetes-1.5-supporting-production-workloads.html)! PetSet is now called StatefulSet (beta), Windows server containers are available, and a slew of other features are now available.

[Docker spun out containerd](https://blog.docker.com/2016/12/introducing-containerd/), its core container runtime, into a standalone product, "and will be donating it to a neutral foundation early next year". This is big news especially when you consider [Alibaba, AWS, Google, IBM and Microsoft are all onboard the containerd train](https://blog.docker.com/2016/12/containerd-core-runtime-component/).

[CoreOS Linux has rebranded itself to Container Linux](https://coreos.com/blog/tectonic-self-driving.html). The CoreOS team can do what they want as far as branding but I honestly think this is going to create some confusion in the marketplace. Think about explaining to an overzealous CTO who wants to use containers that Container Linux might not be the best option.

## Department of Happy Little Clouds ☁️☁️☁️

[Google joined the Cloud Foundry Foundation](https://cloudplatform.googleblog.com/2016/12/Google-joins-the-Cloud-Foundry-Foundation.html). Not really a surprise here as Google attempts to change the cloud playing field to a vendor agnostic landscape.

## Department of Dafuq

Yahoo announced [ANOTHER hack affecting 1 billion users](https://yahoo.tumblr.com/post/154479236569/important-security-information-for-yahoo-users) (billion with a B). Interestingly the hashed passwords that were compromised used MD5 (which has been cryptographically compromised for years now). If you are in Ops, ask your Devs what they are doing to keep you out of the news.

This should not even have to be a thing but it is: [neveragain.tech](http://neveragain.tech/). It is a pledge from "engineers, designers, business executives, and others whose jobs include managing or processing data about people" who refuse to participate in overzealous government data collection programs. Where was this in 2001 or even after the Snowden reveal?

## Department of Next Year's Old Tech

[Cisco announced it is going to kill its OpenStack based cloud platform](http://www.theregister.co.uk/2016/12/13/cisco_to_kill_its_intercloud_public_cloud_on_march_31st_2017/). This is more bad news for OpenStack. Rackspace helped invent OpenStack and invested a lot into it in error it would seem. [HP has bailed out of OpenStack](http://www.computerworld.com/article/3146568/cloud-computing/and-there-she-goes-hpe-jettisons-both-openstack-and-cloud-foundry-initiatives.html). [As Kendrick Coleman pointed out](https://twitter.com/KendrickColeman/status/809062687774806016) to me on Twitter, [Dell EMC ditched its OpenStack ambitions](http://www.theregister.co.uk/2016/12/02/dell_emc_kills_off_vxrack_neutrino/) as well recently.

## Department of Sane Workplaces

[Bloomberg did a great piece on GitHub](https://www.bloomberg.com/news/articles/2016-12-15/github-is-building-a-coder-s-paradise-it-s-not-coming-cheap) that showed the platform as an incredibly expensive venture. The piece also detailed what GitHub has done lately. But, I don't think anyone realized how expensive it is to run GitHub. This is good exposure of a fundamental DevOps tool to the world outside of Dev and Ops for sure.

[Jenn Schiffer's talk at XOXO](https://youtu.be/wewAC5X_CZ8) is a little bit older but, it's worth watching every week; timely and hilarious:

{{< youtube wewAC5X_CZ8 >}}

## DevOps'ish One-Liner of the Week

Should you ever need to figure out if an IP address is a TOR exit node or not just run this gem:

    curl --compress -D- --silent [https://check.torproject.org/exit-addresses](https://check.torproject.org/exit-addresses) | egrep -o '[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}' | sort | uniq | sort -n
