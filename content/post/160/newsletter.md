+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2019"]
date = 2019-12-30T07:00:00Z
description = ""
draft = false
slug = "160"
tags = ["DevOps", "Kubernetes", "developers", "open source", "Linux", "security", "cloud", "cloud native", "performance", "Apple", "CNCF", "CNCF Ambassador", "MinIO", "Detroit", "geolite", "Bongo", "Operator", "sysadmin", "entropy", "VMware", "Red Hat", "velocity", "CI/CD", "Kubernetes Operators", "Ansible Operators"]
title = "160: 2019 is a wrap, internet bifurcation, using ML to block BGP hijacking, monitoring entropy, Kubernetes Operators, ops anti-patterns, and more"

+++

Happy Holidays to everyone celebrating this time of year. I hope that your time with family and friends was wonderful and stress-free. I have both of my kids in the same place at the same time this weekend; I am thoroughly enjoying that. Life doesn't go how you plan it. Much like in DevOps, it's not how well you stick to the plan for life; it's how you respond to anomalies and improve the system as a whole. I had a kid at 20. She grew up a military brat and didn't have the easiest of childhoods. But, she's in college now. She's working her ass off too. But, she's doing this so she can take knowledge from us and better herself in the long run. I know it's hard; it's not the life I dreamed for her. But, we have talked about how this will prime her for a better position in life when she graduates. We're working together as a team to learn from some hard-fought lessons while allowing room for mistakes. But, the safties that I didn't have are built-in so that when errors occur, their blast radius can be minimized. Raising kids and teaching young adults how to live is a whole lot like DevOps. Drive towards goals, address errors, build safeties into the system as you go, and continue to iterate on every cycle to find areas to improve. There are so many parallels between life and DevOps.

[**X-Team is Hiring Go developers with strong AWS skills (Remote)**](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)  
We are looking for passionate Go developers with strong AWS skills to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. We provide the funding needed to help you achieve your goals and grow as a remote developer. [Join X-Team](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)! *SPONSORED*

## Events

[Security at Cloud Native Speed (webinar)](https://security.stackrox.com/2020_01SecurityatCloudNativeSpeedWebinar_200Registration.html)  
Online  
January 9, 2020, 11:00 am PT | 2:00 pm ET  
Join our live discussion to get your questions answered on how to improve security and reduce your blast radius while increasing velocity in cloud-native environments. Our speaker, Chris Short, draws on his experience as a principal technical marketing manager for Red Hat, CNCF Ambassador, and editor of KubeWeekly and DevOps'ish to share best practices on applying gates during CI/CD, the critical features for container security, tapping the power of native controls in Kubernetes, leveraging automation to retain velocity.

[DeliveryConf](https://www.deliveryconf.com/)  
Seattle, WA  
January 21-22, 2020  
DELIVERY|CONF 2020 is being held to give people a place to get deeper technical information about Continuous Integration (CI) and Continuous Delivery (CD). Our goal isn't to just tell you to "do the technical thing"; it is to show you real world examples of how others have done it. DELIVERY|CONF 2020 is a not-for-profit event being created by an all-volunteer team with many years of experience both in the technology and with creating conferences.

[Hacking With The Homies Developers Conference Ticket](https://www.eventbrite.com/e/hacking-with-the-homies-developers-conference-tickets-83203845943)  
Detroit, MI  
Feb 29, 2020  
This is the first Software Developer Conference with a 100% focus on Black and Brown software developers. All sessions will be led by developers and will contain an actual code walk-thru. All presenters have a 3 slide limit and everything else has to be code. We have a Happy Hour after the conference where you can network and mingle with other developers. The profits from the conference will go to funding Detroit Black Tech initiatives and events.

## People

[Taking Human Performance Seriously](https://www.adaptivecapacitylabs.com/blog/2017/12/19/taking-human-performance-seriously/) — John Allspaw: "The increasing significance of our systems, the increasing potential for economic, political, and human damage when they don’t work properly, the proliferation of dependencies and associated uncertainty — all make me very worried. And, if you look at your own system and its problems, I think you will agree that we need to do more than just acknowledge this — we need to embrace it."

[The tech CEOs' year of reckoning](https://www.engadget.com/2019/12/27/the-tech-ceo-year-of-reckoning/) — A year in which we all learned startup CEOs aren't going to save us (no shit).

[The unintended consequence of US campaign against Huawei could be a global split in technology standards](https://www.scmp.com/tech/big-tech/article/3042233/unintended-consequence-us-campaign-against-huawei-could-be-global) — I would not be surprised if there were three "internets" by the end of 2020. The US-based internet, a Chinese based one (which is well on its way), and I see a potential for a third internet from either Russia or countries with despotic regimes banding together. I say that not to pick on Russians in particular but, they are moving in that general direction.

[RuNet - Russia successfully concluded tests on its Internet infrastructure Security Affairs](https://securityaffairs.co/wordpress/95564/security/russia-runet-tests.html) — "Russia's government announced that it has successfully concluded a series of tests for its RuNet intranet aimed at country disconnection from the Internet."

[Research: How Women Undersell Their Work](https://hbr.org/2019/12/research-how-women-undersell-their-work) — Self-promotion is how I got to where I am. If you don't toot your own horn, no one else will. But, there are good and bad forms of self-promotion.

[My blogging stack and publishing process](https://blog.frankel.ch/my-blogging-stack-publishing-process/) — Medium is bad. You should stop using it. If you need more reason than what's listed in this article, I give you [nomedium.dev](https://nomedium.dev).

[Travis Kalanick to step down from Uber's board](https://www.cnn.com/2019/12/24/tech/travis-kalanick-uber/index.html) — After selling a massive amount of his equity, Travis Kalanick is officially out at Uber.

## Process

[Significant Changes to Accessing and Using GeoLite2 Databases](https://blog.maxmind.com/2019/12/18/significant-changes-to-accessing-and-using-geolite2-databases/) — The GeoLite2 databases are handy for operational and security applications. Access to them will no longer be open due to new privacy laws.

[Using ML to Block BGP Hijacking](https://www.usenix.org/publications/login/winter2019/camp) — "Bongo uses the Routing Information Base (RIB) to identify changes not in routes but in AS, and then assigns each AS a risk parameter. Based on this parameter, Bongo can create a firewall rule. Alternatively, Bongo may simply issue an alert to the operator, if the change is worthy of note but not high risk." This is the ML I'm here for.

[The Linux Kernel as a Case Study on Rapid Development for Complex Software](https://thenewstack.io/the-linux-kernel-as-a-case-study-on-rapid-development-for-complex-software/) — "The Linux kernel is a massive project that requires rapid development from many developers and development teams. Over the years, this project has been a standard-bearer for how a massive project can function like a well-oiled machine, as well as a study in how to solve problems when they occur."

[10 best sysadmin stories from the trenches](https://www.redhat.com/sysadmin/stories-trenches) — "Check out these sysadmin technical how-tos, advice pieces, and horror stories that people in the trenches submitted for 2019."

[Netflix was the top stock of the decade, delivering over 4,000% return](https://www.cnbc.com/2019/12/23/netflix-was-the-top-stock-of-the-decade-delivering-over-4000percent-return.html) — Interesting to see how this stock will perform in the 2020s with significant competition for everyone's time now.

[Top CI/CD resources to set you up for success](https://opensource.com/article/19/12/cicd-resources) — "Continuous integration and continuous deployment were key topics in 2019 as organizations look to achieve seamless, flexible, and scalable deployments."

[The New Unicorns Of 2019](https://news.crunchbase.com/news/the-new-unicorns-of-2019/) — A look at how money moved in the unicorn market in 2019.

[This holiday's biggest online shopping day was... Black Friday](https://blog.cloudflare.com/this-holidays-biggest-online-shopping-day-was-black-friday/) — Black Friday is the new Cyber Monday.

[On Linux's Random Number Generation](https://research.nccgroup.com/2019/12/19/on-linuxs-random-number-generation/) — Conclusion: "Monitoring entropy levels on Linux systems is not very useful. From a security point of view, the entropy estimates by the kernel are quite off."

[Top 10 DevOps articles of 2019](https://enterprisersproject.com/article/2019/12/devops-top-10-2019) — "Check out our most popular DevOps articles of the year — for lessons you can use in 2020 and answers to key DevOps questions"

[Boeing fires chief executive Dennis A. Muilenburg in wake of 737 Max crisis](https://www.washingtonpost.com/business/2019/12/23/boeing-chief-executive-dennis-muilenburg-resigns-board-seeks-restore-confidence-wake-max-crisis/) — This seems long overdue.

[After a year of acquisitions CloudBees looks at portfolio, says ‘it’s complicated’](https://devclass.com/2019/12/20/cloudbees-to-simplify-portfolio/) — Cloudbees is a legit head-scratcher right now.

[The ingenious way Steve Jobs led design reviews at Apple](https://www.fastcompany.com/90447287/the-ingenious-way-steve-jobs-led-design-reviews-at-apple) — "If you ever found yourself sitting at your desk by yourself with your headphones on, stressing ’cause you felt like you had to figure it out on your own, something was really broken."

## Tools

[Operations Anti-Patterns: DevOps Solutions by Jeff Smith](https://www.manning.com/books/operations-anti-patterns-devops-solutions) — "Operations Anti-Patterns: DevOps Solutions shows how to implement DevOps techniques in the kind of imperfect environments most developers work in. Part technology tutorial, part reference manual, and part psychology handbook, this practical guide shows you realistic ways to bring DevOps to your team when you don’t have the flexibility to make sweeping changes in organizational structure."

[Bringing On-prem Kubernetes to Cloud Parity](https://charlescary.com/bringing-on-prem-kubernetes-to-cloud-parity/) — "The extra components & services you need to be as productive on-prem as in a major cloud provider's environment."

[alauda/kube-ovn](https://github.com/alauda/kube-ovn) — A Kubernetes Network Fabric for Enterprises that Rich in Functions and Easy in Operations

[Journey to a Faster Everyday Super App Where Every Millisecond Counts](https://engineering.grab.com/journey-to-a-faster-everyday-super-app) — A deep dive into how Grab improved performance.

[Apple News No Longer Supports RSS](https://mjtsai.com/blog/2019/12/26/apple-news-no-longer-supports-rss/) — At least I tell people when I kill RSS. Apple users will click RSS links and have News.app open but, nothing will actually happen.

[2019 Linux Performance: Ubuntu Up ~1%, Fedora Up ~2%, Clear Linux Up ~7%](https://www.phoronix.com/scan.php?page=article&item=3-distros-2019&num=1) — Benchmarks are showing that Linux performance is up and to the right.

[Putting the CRD in Christmas Decorations](https://patrick.easte.rs/post/putting-the-crd-in-christmas-decorations/) — "As I was thinking of a good first Ansible operator, I looked up from my couch and saw my Christmas tree. I already had many of my Christmas lights integrated with Home Assistant, so why not take advantage of the easy-to-use REST API and automate my Christmas lights?" A great article on Ansible Operators and their ability to reach outside Kubernetes clusters to work with external services.

[AMD Introduces New Ryzen Mini PCs To Challenge Intel](https://hackaday.com/2019/12/24/amd-introduces-new-ryzen-mini-pcs-to-challenge-intel/) — NUC competition? I like it! Hey, AMD? Can I cop one?

[4 predictions for Open Source in 2020](https://www.idgconnect.com/opinion/1503697/predictions-open-source-2020) — Nothing dramatic but I do agree with the majority of this piece.

[Kubernetes Autoscaling 101 How HPA, VPA and CA work to scale workloads and infrastructure (YouTube)](https://www.youtube.com/watch?v=7DByxtY0Jdg&feature=youtu.be) — A quick hitter on Kubernetes Autoscaling

[11 Resource to Learn Python for Beginners](https://geekflare.com/python-learning-resources/) — "Looking to learn a new language kills beginners’ time. We heard your voice, and here is the curated list of best resources to learn Python."

[VMware to use MinIO object storage in Kubernetes embrace](https://blocksandfiles.com/2019/12/23/vmware-minio-object-storage-kubernetes/) — MinIO is a good choice here. But, what about backend storage recommendations? What do I give to MinIO? RAW disk? NFS? Ceph? Cinder? There's a lot of considerations and tradeoffs there. But, I think VMware is telling folks to do what makes sense for them or this merry band of high dollar consultants can help you narrow down that decision.

## Tweet of the Week

{{< tweet 1209197745497501696 >}}
