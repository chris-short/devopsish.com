+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2017"]
date = 2017-02-05T07:57:00.244Z
description = ""
draft = false
slug = "009"
tags = ["devops", "cloud native", "open source", "rm", "serverless", "linux", "selinux", "SRE", "Site Reliability Engineering", "Docker"]
title = "009: Week of 1486270800"
image ="https://shortcdn.com/devopsish/flexible-shiba-inu.gif"
imagealt = "Be Flexible! Courtesy of Jessica Rose during her Open Source 101 Talk in Raleigh, NC"
aliases = [
    "devopsish-weekly-009-week-of-1486270800-64338dc3a251"
]

+++

What a week in [**DevOps**](https://devopsish.com/) ! There is so much news to share this week it took me an hour to collect it all! I also went to the [Open Source 101](http://opensource101.com/) conference this week to pick up some knowledge on communities. It was a very good conference. If the future of open source software was represented there it will definitely not be a white male dominated field.

## Department of Choice Concepts

Like a lot of sysadmin and DevOps teams, I bet you have some random cron jobs that are critical to your daily/weekly/monthly workflows. The problem with these jobs is that they always seem to never have a great place to live. [Marc Cuva](https://medium.com/@marccuva) and the Serverless movement [might have given us a solution to consider](https://blog.readme.io/writing-a-cron-job-microservice-with-serverless-and-aws-lambda/).

[Make SELinux Enforcing Again!](https://learntemail.sam.today/blog/stop-disabling-selinux:-a-real-world-guide/) We all do it... To some extent. Let's try to stop disabling SELinux in 2017.

18F at GSA ran a small experiment in September and it turned out that [working more hours did not net more productivity](https://18f.gsa.gov/2017/01/19/the-dark-standup/). Confining work schedules and after hours phone checking actually made a team more effective. The crazy thing is this analysis came from a US government agency. Kudos to [The U.S. Digital Service](https://medium.com/@USDigitalService)!

[Kendrick Coleman](https://medium.com/@kendrickcoleman) took us on a [Docker 1.13 journey detailing storage plugins and propagated mounts](https://blog.codedellemc.com/2017/02/02/deep-dive-docker-1-13-storage-plugins-propagated-mounts/?cmp=soc-cor-glbl-us-sprinklr-TWITTER--codeDellEMC-796974590). It might not be production ready but it is definitely interesting.

## Department of Data Defense

The biggest story of the week was the [unintentional meltdown at GitLab and the amazing response to it](https://docs.google.com/document/d/1GCK53YDcBWQveod9kfzW-VCxIABGiryG7_z_6jHdVik/pub). The world watched as a [GitLab](https://medium.com/@gitlab) team member `rm -Rvf a PostgreSQL` directory. GitLab's response was the most open disaster recovery in modern history. I was VERY impressed by the level of openness and honesty; this is how postmortems should work. February 1st was declared "[Check your backups Day!](http://checkyourbackups.work/)"

## Department of Refreshment and Refurbishment

[Etsy](https://medium.com/@etsy) described how their Pattern product [manages HTTPS and stores SSL certificates](https://codeascraft.com/2017/01/31/how-etsy-manages-https-and-ssl-certificates-for-custom-domains-on-pattern/). This is a fascinating write up of what, to many, would be an insurmountable effort.

Facebook has released [delegated-account-recovery](https://github.com/facebookincubator/DelegatedRecovery/). It is, "protocol that allows an application to delegate the capability to recover an account (e.g. in the event of a credential loss or compromise) to an account controlled by the same user at a third party service provider."

Ever needed a cross-platform password management tool for your team? [gopass](https://www.justwatch.com/blog/post/announcing-gopass/) was announced this week and solves several password management problems. I am hoping to introduce to one of my teams in Scotland this week to replace KeePass.

[Kompose](http://kompose.io/) was announced this week. Keep an eye on this one because it's a very simple way to convert a Docker Compose file to run on Kubernetes or OpenShift.

[Visual Studio](https://medium.com/@VisualStudio) (yes, Microsoft's Visual Studio) released GVFS this week. What is GVFS? It stands for [Git Virtual File System](https://blogs.msdn.microsoft.com/visualstudioalm/2017/02/03/announcing-gvfs-git-virtual-file-system/). Its allows dev teams to check out massive repos without having to download them in their entirety. GVFS only pulls down the files you actually need when you're working on them. Pretty smart for those working on big code bases.

## Department of Sane Workplaces

I have not finished reading the Site Reliability Engineering book cover-to-cover yet. But, I have treated it as a sort of reference as of late. The good news is, now we all can call upon Google's [Site Reliability Engineering](https://landing.google.com/sre/book.html) book because it is available completely for free.

## Not DevOps But Still Cool

[Opensource.com](https://opensource.com/) announced their [2017 Community Award Winners](https://opensource.com/article/17/2/community-awards-2017) this week. Congrats to all those selected!

## DevOps'ish One-Liner of the Week

I had to blow away a temp directory that was consuming an enormous amount of inodes this week. rm -rf was running far too slow and I needed a faster solution:

    rsync -a --delete empty_dir/ tmp_dir_consuming_too_many_inodes/
