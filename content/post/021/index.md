+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-04-30T06:01:02.821Z
description = ""
draft = false
slug = "021"
tags = ["devops", "cloud native", "open source", "docker", "golang", "linux", "google", "uber", "lambda", "Docker Inc"]
title = "021: Week of 1493524800"
image ="https://shortcdn.com/file/devopsish/tranquil-lake.jpg"
imagealt = "April Showers Better Bring a TON of May Flowers"
aliases = [
    "devopsish-weekly-021-week-of-1493524800-c976f19e5099"
]

+++

[North Carolina, and particularly the Triangle area, has had an enormous amount of rain this week](http://www.cnn.com/2017/04/25/us/north-carolina-flooding/). The tiny creek behind our house was a rapid early in the week. According to the USGS, [Falls Lake is almost ten feet above it's average levels](https://waterdata.usgs.gov/nc/nwis/uv?cb_00065=on&format=gif_stats&site_no=02087182&period=&begin_date=2017-04-22&end_date=2017-04-29). There was [one fatality as a result of someone driving around a barricade](https://governor.nc.gov/news/governor-cooper-urges-caution-flooding-continues-threaten-eastern-nc-communities) onto a flooded roadway. Common sense is not common. Please stay safe out there, folks.

Meanwhile, back on the [**DevOps**](https://devopsish.com/) ranch, it was a VERY busy week. I'm on-call for two products this week, working on three projects, writing an article inspired by my VP, submitting CFPs, and trying to keep up with the news. With so much going on let's get to the [DevOps'ish](https://devopsish.com/)!

## Department of Choice Concepts

[Boot an OpenSSH server in 10 mins with LinuxKit](http://blog.alexellis.io/boot-linuxkit-in-10-mins/): Hands-on guide to use Docker's LinuxKit to build, run and connect to a bootable Linux system image with OpenSSH.

[Julia Evans wrote about her favorite shell this week](https://jvns.ca/blog/2017/04/23/the-fish-shell-is-awesome/). I just setup [fish shell](https://fishshell.com/) after re-reading Julia's article. Install, add to /etc/shells, and you're off and running. Out of the box it's REALLY awesome.

[I had no idea the most important dimension of the human race, time, isn't namespaced by the Linux kernel](https://blog.jessfraz.com/post/two-objects-not-namespaced-linux-kernel/).

[Going multi-cloud with Google Cloud Endpoints and AWS Lambda](https://cloudplatform.googleblog.com/2017/04/going-multi-cloud-with-Google-Cloud-Endpoints-and-AWS-Lambda.html): This is what cloud *should* be! You want to use them for some things? Fine. You want to use us for other things? Great! You want to use us both to make your product more awesome, resilient, and cost-effective? **FANTASTIC**!

![Brian Grant's Kubernetes Simplified Architectural Summary](/021/kubernetes-simplified-architecture.png)  
*Brian Grant's Kubernetes Simplified Architectural Summary*

Brian Grant has laid out the [Kubernetes Architecture in a way that is very consumable](https://groups.google.com/forum/#!topic/kubernetes-dev/yXMjoMAZRN4) yet sufficiently detailed.

Speaking of Kubernetes, here is a [handy cheatsheet for Kubernetes](https://sematext.com/kubernetes/cheatsheet/) (available as PDF and Markdown).

[Understand Go pointers in less than 800 words or your money back](https://dave.cheney.net/2017/04/26/understand-go-pointers-in-less-than-800-words-or-your-money-back)

Go is a great programming language (especially for [DevOps](https://devopsish.com/)). One feature I feel is missing is its ability to update itself or having some built-in process for doing so. [I think we should be past the days of languages not at least having an integrated update process](https://groups.google.com/forum/#!topic/golang-devexp/-ejglEViXN0). This is not to say that it should auto-update; *I am COMPLETELY against that*. But, the fact I have to use something outside of the golang environment to update go is a little awkward to me in this day and age. [update-golang](https://github.com/udhos/update-golang) looks to simplify the process of updating Go.

## Department of Woke Workplaces

[An accomplished engineer made the horrible choice of taking a job at Uber and it likely cost him his life](http://www.sfchronicle.com/business/article/Suicide-of-an-Uber-engineer-widow-blames-job-11095807.php). Can we all just uninstall Uber and delete our accounts now?

[The fight FOR **net neutrality** is on like Donkey Kong](http://www.theverge.com/2017/4/26/15439622/fcc-net-neutrality-internet-freedom-isp-ajit-pai). I don't care which side of the debate you are on, [**please share your thoughts with the FCC](https://www.fcc.gov/ecfs/search/filings?proceedings_name=17-108)**.

The [*Tech Leavers Study*](http://www.kaporcenter.org/tech-leavers/) is a first-of-its-kind national study examining why people voluntarily left their jobs in tech. The Kapor Center for Social Impact and Harris Poll surveyed a representative sample of more than 2,000 U.S. adults who have left a job in a technology-related industry or function within the last three years.

## Department of Data Defense

[HipChat was breached last weekend](https://blog.hipchat.com/2017/04/24/hipchat-security-notice/). According to Atlassian's Chief Security Officer, Ganesh Krishnan, the incident involved a vulnerability in a third-party library. Patch your dependencies, folks!

Still trying to figure out CAA records? Check out [J. Edward Durrett's SANS ISC diary about CAA Records](https://isc.sans.edu/forums/diary/CAA+Records+and+Certificate+Issuance/22342/).

[The Sysadmin's Guide to Securing Your SaaS Apps](http://www.circleid.com/posts/20170426_the_sysadmins_guide_to_securing_your_saas_apps/)

## Department of Refreshment and Refurbishment

[nginx 1.13.0 was released on Tuesday](http://mailman.nginx.org/pipermail/nginx-announce/2017/000195.html) and summarily broke my website due to an errant line break in a configuration I rarely touch. It includes TLSv1.3 support which makes me stupid happy.

[Julia Evans made tcpdump zine](https://twitter.com/b0rk/status/858077003244855298) and it is absolutely fantastic. She is selling [early releases for $10](https://gumroad.com/l/LcKLx). Support her efforts to make us all smarter!

## Department of Discussion

[Jason van Gumster reminds us that haters gonna hate](https://opensource.com/article/17/4/haters-gonna-hate). Jason also provides some methods of dealing with those that woke up and drank a tall glass of Haterade.

## Department of Next Year's Old Tech

![Docker Project Map](/021/docker-project-map.jpg)

How do you look at this graphic from Docker and not think Docker is killing it's branding for some reason? [Docker's recent rebranding efforts offer a lesson in public decision-making](https://opensource.com/open-organization/17/4/how-branding-decisions-open).

[Debian is shutting down its public FTP services](https://www.debian.org/News/2017/20170425). That's about a decade overdue. When I worked at [McClatchy](http://www.mcclatchy.com/) we had a hell of a time maintaining FTP services. Photographers, journalists, and several other people depended upon FTP's simplicity. But, its lack of security gave us all kinds of headaches. It is way past time for FTP to go the way of [Gopher](https://en.wikipedia.org/wiki/Gopher_(protocol)).

## Department of Sane Workplaces

[Amazon has shared some Leadership Principles](https://www.amazon.jobs/principles?&tag=rnwap-20) that I agree with. I likely wouldn't work at Amazon HQ but it's encouraging to see this.

I got asked a very interesting question today by my VP, "[How do you prep a good sysadmins to be a DevOps engineer in six months?](https://twitter.com/ChrisShort/status/857356577417949184)" E-mail or [tweet DevOps'ish](https://twitter.com/devopsish) to give your thoughts.

## Not DevOps But Still Cool

[Wikipedia cofounder Jimmy Wales is launching a community-powered news site](http://www.businessinsider.com/wikipedia-cofounder-jimmy-wales-wikitribune-community-powered-news-2017-4)

Sarah Novotny coins, "mean time to dopamine" while discussing [how Kubernetes is making contributing easy](https://opensource.com/article/17/4/podcast-kubernetes-sarah-novotny) with Gordon Haff. I have to admit, the Kubernetes community is pretty great.

[Smoked Fried Chicken](https://gist.github.com/bketelsen/3ebe4979e9ee563ed1a8c81435ddf767), 'nuff said.
