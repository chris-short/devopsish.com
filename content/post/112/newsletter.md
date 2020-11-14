+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-01-27T07:00:00Z
description = "Kubernetes Any Way You Want It, Passing the CKA, GitOps, Joy Sparking Meetings, Processes, Containers, and VMs. Oh My! and More"
draft = false
slug = "112"
tags = ["kubernetes", "docker", "devops", "open source", "cloud", "tech", "github", "cloud native", "ansible", "container", "security", "curl", "minikube", "CI/CD", "Kubernetes Operators"]
title = "112: Kubernetes Any Way You Want It, Passing the CKA, GitOps, Joy Sparking Meetings, Processes, Containers, and VMs. Oh My! and More"

+++

I'm struggling to write an intro this week (probably broke a rib). But, I did write a tweet that got a lot more attention than I thought it would this week. I'd like to talk about it:

{{< tweet 1087392106262528004 >}}

This is not to say I decline every meeting invite I get. It's to say that if an invite is not complete (an agenda, location, time, etc.) I'm highly likely to decline it. Also, if there doesn't appear to be value in my going versus something else I could be doing I will typically decline stating the reason politely. In general, I enjoy the meetings I get invited to because I love the work I'm doing. But, I did decline a meeting invite a little bit ago.

[**Use Lead Time Metric to Improve Your CI/CD Process**](https://www.gocd.org/2019/01/14/cd-metrics-deployment-lead-time/)  
Check out GoCD's latest blog in CD Metrics series. It talks about what lead time mean in CD context and guide you how to identify bottlenecks and improve your CI/CD process. *SPONSORED*

[**Triangle DevOps presents DevOps is Not War with Chris Short of Red Hat**](https://www.meetup.com/triangle-devops/events/257189603/)  
Over the past 500 years, there have been 16 cases of a rising power threatening to displace a ruling power. 75% of those cases resulted in war. Although your organizational transformation probably won't lead to war, it could be contentious. History can help prevent conflict when driving change. This talk will analyze human tendencies, historical data, and provide real-world examples of how to prevent conflict during your DevOps journey. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [Five Things To Look For On A DevOps Resume](https://www.forbes.com/sites/forbestechcouncil/2019/01/15/five-things-to-look-for-on-a-devops-resume/#7f8b1f3a2cb1)
2. [Three things to look for if you want to earn more in DevOps](https://puppet.com/blog/three-things-look-if-you-want-earn-more-devops)
3. [Get started with WTF, a dashboard for the terminal](https://opensource.com/article/19/1/wtf-information-dashboard)
4. [The 50 Best Workplaces in Technology](http://fortune.com/2019/01/17/50-best-workplaces-in-technology/)
5. [A Crash Course For Running Istio](https://medium.com/namely-labs/a-crash-course-for-running-istio-1c6125930715)

## People

[CEO of IBM Says Hiring Based on Skills Instead of College Degrees is Vital for the Future of Tech](https://gizmodo.com/ceo-of-ibm-says-hiring-based-on-skills-instead-of-colle-1831977815) — I'm still grappling with this one personally. No, I didn't go to college in the traditional sense. But, I also think colleges play an important role in our society. The real reason this is a topic here in the US is due to the enourmous cost of tuition. For example, we're estimating Max's (age 3) university tuition to be close to $200,000 USD. That's the equivalent of ₹14,180,100.00 Indian Rupees, £151,521.00 Pounds, ¥1,349,460.00 Chinese Yuan, or €175,431.00 Euro.

[Squashing inclusivity bugs in open source software](https://opensource.com/article/18/8/inclusivity-bugs-open-source-software) — Anita Sarma joined the Kubernetes SIG Contributor Experience meeting this week. The research her and her team are doing at Oregon State University is incredible. I had an eye opening moment and would encourage you to look into more of Anita's work and do the same.

[7.5 tips to help you ace the Certified Kubernetes Administrator (CKA) exam](https://kubedex.com/7-5-tips-to-help-you-ace-the-certified-kubernetes-administrator-cka-exam/) — If you're trying to become Kubernetes certified, you need all the help you can get.

[The Ultimate Guide to Passing the CKA Exam](https://medium.com/@ContinoHQ/the-ultimate-guide-to-passing-the-cka-exam-1ee8c0fd44cd)

[This Is What Happens to Your Body When You Hate Your Job](https://www.huffpost.com/entry/hate-your-job-body-symptoms_n_5c40a314e4b0a8dbe16e8373) — When you hate your job all sorts of unsavory things occur. Change your environment, if everyday is hard maybe you're not the problem.

[vmbrasseur/Public_Speaking](https://github.com/vmbrasseur/Public_Speaking) — A repository of resources about public speaking, specifically in the context of software development and IT conferences.

[What Does a Site Reliability Engineer Do?](https://blog.scalyr.com/2019/01/site-reliability-engineer/) — They engineer sites reliably, duh! Wait...

## Process

[The U.S. Department of Defense on How to Detect 'Agile BS'](https://thenewstack.io/the-u-s-department-of-defense-on-how-to-detect-agile-bs/) — The DoD honed the bejesus out of my bullshit detector. Now the Department's BS detection skills are being applied to software. Look out vendors.

[101 More Security Best Practices for Kubernetes](https://rancher.com/blog/2019/2019-01-17-101-more-kubernetes-security-best-practices/) — There are a lot of security considerations when running Kubernetes. This is a good primer.

[Salting and stretching a password](https://www.johndcook.com/blog/2019/01/25/salt-and-stretching/) — Tired: Salting passwords, Wired: Stretching passwords!

[Security Checklist](https://securitycheckli.st/) — An open source checklist of resources designed to improve your online privacy and security. Just like any security conversation, [folks had concerns](https://twitter.com/ChrisShort/status/1089135723901526016).

[9 trends to watch in systems engineering and operations](https://www.oreilly.com/ideas/9-trends-to-watch-in-systems-engineering-and-operations) — Nothing earth shattering here (AIOps... sigh...) but, I do hope the buzzwords for folks trying to tool their way out of the culture problems they have needs to die. Microsoft did us no favors with Azure DevOps. Welcome to the next round of interesting but not transformative buzzwords and concepts.

[What's New in Crunchy PostgreSQL Operator 3.5](https://info.crunchydata.com/blog/crunchy-postgresql-operator-3.5-new-features) — Crunchy does PostgreSQL on Kubernetes better than most. Check their Kubernetes Operator out if you working on PostgreSQL on Kubernetes.

[Microsoft Acquires Citus Data: Creating the World's Best Postgres Experience Together](https://www.citusdata.com/blog/2019/01/24/microsoft-acquires-citus-data/) — Congrats to the folks at Citus and Microsoft. Oh and to my co-worker and SIG mate (is that even a word?) Josh Berkus who sits on the board of Citus.

[IBM HR made me lie to US govt, says axed VP in age-discrim legal row: I was ordered to cover up layoffs of older workers](https://www.theregister.co.uk/2019/01/18/ibm_government_lying_claims/) — Everyone I know with a parent at IBM in the early 2000s has a layoff story. It's sad how systemic this appeared to be to those in the know. Well... IBM's chickens have come home to roost on this one.

[What is the difference between a process, a container, and a VM?](https://medium.com/@jessgreb01/what-is-the-difference-between-a-process-a-container-and-a-vm-f36ba0f8a8f7) — If you don't know, now you know.

[Docker and Kubernetes in high security environments](https://medium.com/@chrismessiah/docker-and-kubernetes-in-high-security-environments-d851645e8b99) — A case-study at the Swedish Police Authority

[Trouble hiring senior engineers? It's probably you](https://hiringengineersbook.com/post/trouble-hiring/) — It's most definitely you.

[The Era of "Move Fast and Break Things" Is Over](https://hbr.org/2019/01/the-era-of-move-fast-and-break-things-is-over) — Only had to have Facebook damage democracy to figure out this was a bad idea. Silicon Valley needs to get out more.

[Requests for info, gag orders and takedowns fired at GitHub users hit an all-time high last year](https://www.theregister.co.uk/2019/01/25/github_transparency_report_2018/) — The "Two cross-border data requests" is intriguing but seems like a possible copyright suit (or, ya know, counterintelligence).

[Feedback and Control - an Essential GitOps Component](https://www.weave.works/blog/feedback-and-control-an-essential-gitops-component) — Feedback is mandatory in software and systems work.

[The Travis CI Blog: Travis CI joins the Idera family](https://blog.travis-ci.com/2019-01-23-travis-ci-joins-idera-inc) — Didn't see that one coming.

[10 ways to learn more about DevOps](https://enterprisersproject.com/article/2019/1/10-ways-learn-about-devops) — If you're reading this newsletter you are on your way!

## Tools

[CoreDNS is all grown up now and ready to roll: Kubernetes network toolkit graduates at last](https://www.theregister.co.uk/2019/01/24/cloud_contender_coredns/) — CoreDNS is something I'd really like to see packaged up nicely with a dashboard ala Pi-Hole.

[With the absence of Visio for Mac, what do you use for diagrams?](https://www.reddit.com/r/devops/comments/ahpppo/with_the_absence_of_visio_for_mac_what_do_you_use/) — A reddit thread discussing all the various diagramming tools available for macOS.

[A Kubernetes Development Workflow for MacOS](https://medium.com/@mo_keefe/a-kubernetes-development-workflow-for-macos-8c41669a4518) — iTerm2, kubectx, [GitOps](https://www.weave.works/technologies/gitops/), VS Code, and more. I'll be using this to fine tune my environment for sure.

[How Kubernetes replace people: Pods – Dmitriy Chaban – Medium](https://medium.com/@dmi3coder/how-kubernetes-replace-people-pods-1535e44310cb) — "This small article's mission is to introduce people with Kubernetes by comparison with old by-hand methods."

[5 Container Alternatives to Docker](https://containerjournal.com/2019/01/22/5-container-alternatives-to-docker/) — Docker being a gross company is all the reason I need.

[Local Kubernetes for Linux — MiniKube vs MicroK8s](https://medium.com/containers-101/local-kubernetes-for-linux-minikube-vs-microk8s-1b2acad068d3) — minikube is still the standard but microk8s is an interesting tool.

[How Tilt updates Kubernetes in Seconds, not Minutes](https://medium.com/windmill-engineering/how-tilt-updates-kubernetes-in-seconds-not-minutes-28ddffe2d79f) — "Developers see [the Tilt dashboard] and grok that Tilt lets them stop playing 20 questions with kubectl."

[Kubernetes Operators — When, how and the gotchas to keep in mind](https://medium.com/@cloudark/kubernetes-operators-when-how-and-the-gotchas-to-keep-in-mind-b13be9830346) — Think of Operators as the glue between your Kubernetes components to handle making everything work as desired.

[BGP in 2018 — The BGP Table](https://blog.apnic.net/2019/01/16/bgp-in-2018-the-bgp-table/) — BGP is the duct tape holding the internet together.

[Useful curl features](https://diamantidis.github.io/2019/01/06/curl-options) — curl is an incredibly useful tool and learning it will help you better understand how the web works.

{{< tweet 1088981000955355136 >}}

[Beginner-Friendly Introduction to GitLab CI/CD](https://dev.to/zurihunter/beginner-friendly-introduction-to-gitlabcicd-4p5a) — Unpopular Opinion: GitLab is miles ahead of where GitHub is as far as total value of features and capabilities.

[Dear Go -- Thank You For Teaching Me PHP Was A Waste of My Time](https://vernonkeenan.com/index.php/2019/01/21/dear-go-thank-you-for-teaching-me-php-was-a-waste-of-my-time/) — Go is a great language but it has its places. PHP is a great language but it has its places. There's nothing wrong with using multiple languages.

[How to run Spark 2.4 on OSX/MiniKube](https://medium.com/@andreyonistchuk/how-to-run-spark-2-4-on-osx-minikube-f0e5fdeb27be) — Need a local Spark in Kubernetes dev environment? This should help.

[Comparing Ansible AWX and Red Hat Ansible Tower](https://www.redhat.com/en/resources/awx-and-ansible-tower-datasheet) — Personally, I would not even think of using AWX in production. But, I know people who do. Now, I know some folks that have paid the price for it too.

[refunc/refunc](https://github.com/refunc/refunc) — A Kubernetes native serverless platform

[TomasTomecek/ansible-bender](https://github.com/TomasTomecek/ansible-bender) — ansible-playbook + buildah = a sweet container image

## DevOps'ish Tweet of the Week

I found out about this first thing Friday morning when I e-mailed Jess asking about Ansible taking advantage of GitHub Actions. Whatever the reason for this abrupt departure, I trust Jess' ability to take care of Jess better than anyone else. No one should judge Jess for leaving GitHub regardless the reason.

 Also, if you work on GitHub Actions, please reach out to myself or John "gundalow" Barker. We have thoughts.

> As of yesterday I am no longer an employee at GitHub. Everyone who works there and GitHub itself will always hold a special place in my heart. @natfriedman has a special place in my heart as well. I wish them nothing but the best.
>
> — Jessie Frazelle (@jessfraz) January 25, 2019

Notes from this week's issue can be found [here](./notes/).
