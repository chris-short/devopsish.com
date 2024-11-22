+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2019"]
date = 2019-12-02
description = "156"
draft = false
slug = "156"
tags = ["Kubernetes", "KubeCon", "DevOps", "cloud", "cloud native", "open source", "developers", "VMware", "git", "Ansible", "AWS", "security", "Operator", "community", "Kubernetes Operators"]
title = "156: KubeCon analysis, Kubernetes security, ‘learn-it-alls’, AWX Kubernetes Operator, and more"

+++

Editor's Note: The newsletter passed 4,000 subscribers this week. Thank you to everyone that help spread the word. I'd love to get to 5,000 subscribers as quickly as possible though. If you don't mind, please ask your coworkers, BFFs, family, and folks on social media to [subscribe to DevOps'ish](https://devopsish.com/subscribe/). Y'all keep being awesome!

It is worth noting that the metrics-based system I use to help write DevOps’ish has broken. This week, I lost the ability to post to Twitter due to rate limiting of Tweets sent by IFTTT. Thank you in advance to all the folks that will suggest Zapier, Buffer, etc. But, this isn't a normal use case for any of those tools. Also, I don't want to be for a service. I'm looking for a solution but, to be honest, I'd like to build an open source tool to handle the [DIY Buffer using IFTTT](https://chrisshort.net/drawings/diy-buffer-using-ifttt/) I've cobbled together (and has worked just fine for YEARS). But, I don't have the skills to do it nor the time, even if I did. If you're interested in working on such a project, let me know. I can provide support, full credit where it's due, and mentions throughout all the work I do.

[**X-Team is Hiring Go developers with strong AWS skills (Remote)**](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)  
We are looking for passionate Go developers with strong AWS skills to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. We provide the funding needed to help you achieve your goals and grow as a remote developer. [Join X-Team](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)! *SPONSORED*

## People

[The Mind at Work: Guido van Rossum on how Python makes thinking in code easier](https://blog.dropbox.com/topics/work-culture/-the-mind-at-work--guido-van-rossum-on-how-python-makes-thinking) — "A conversation with the creator of the world’s most popular programming language on removing brain friction for better work."

[Kubernetes Security](https://www.arresteddevops.com/kubernetes-security/) — Bridget [Kromhout] chats with Ian Coldwater about Kubernetes security on the Arrested DevOps podcast

[Red Hat's Chris Short on Redirecting A War Vet's Energy To Lifelong Learning & Technical Leadership](https://cronicle.press/2019/11/29/redhats-chris-short-on-redirecting-a-war-vets-energy-to-lifelong-learning-technical-leadership/) — Cronicle Press interviewed me at DevOpsDays Detroit. They did way more with the interview than I thought they would. Thank you to them for the opportunity.

[Why we'll need to evolve from ‘know-it-alls’ into ‘learn-it-alls’ in 2020](https://www.siliconrepublic.com/careers/leann-renninger-workplaces-2020) — "LeeAnn Renninger holds a PhD in cognitive psychology with a specialisation in idea transfer, rapid skill acquisition and leadership development. And, according to her, there’s no time like the present to starting refocusing our ways of thinking and our measures of success."

[Finding Her Balance: How this Software Engineer's Mental Health Journey Inspired a Life-Saving App](https://peopleofcolorintech.com/career-growth/finding-her-balance-how-this-software-engineers-mental-health-journey-inspired-a-life-saving-app/) — "One of Ananya’s priorities in building Anemone was to destigmatize the idea of seeking and asking for help with mental health challenges. She feels that this stigma prevented her from seeking help earlier on in her struggle."

[Oracle finally responds to wage discrimination claims... by suing US Department of Labor](https://www.theregister.co.uk/2019/11/27/oracle_wage_discrimination/) — A law firm holding a bunch of patents acting like a tech firm will certainly take the worst parts of both industries and apply them to their business.

[Navigating Conflict](https://hbr.org/podcast/2019/11/navigating-conflict) — "Whatever your natural tendency is, dealing with conflict is a crucial skill to succeed at work. It can lead to higher job satisfaction, stronger relationships with colleagues, and innovation."

[geopolitics.dev](https://geopolitics.dev/) — I've launched a separate newsletter to dive into policy, ethics, and tech. If you like the People and Process section of this newsletter, enjoy living outside your comfort zone, and have capacity for another newsletter [subscribe today](https://geopolitics.dev/subscribe/)!

## Process

[The Unicorn Project: A Novel about Developers, Digital Disruption, and Thriving in the Age of Data](https://amzn.to/2XqekFl) — In *The Unicorn Project*, we follow Maxine, a senior lead developer, and architect, as she is exiled to the Phoenix Project, to the horror of her friends and colleagues, as punishment for contributing to a payroll outage. She tries to survive in what feels like a heartless and uncaring bureaucracy and to work within a system where no one can get anything done without endless committees, paperwork, and approvals. Out now!

[The New Norm: Trend Micro Security Predictions for 2020](https://www.trendmicro.com/vinfo/us/security/research-and-analysis/predictions/2020) — There are a lot of problems to solve out there. But, now those problems can get really big before we're able to even respond.

[Caller Poses as CISA Rep in Extortion Scam](https://www.us-cert.gov/ncas/current-activity/2019/11/29/caller-poses-cisa-rep-extortion-scam) — The best weapon against malware and phishing attacks are educated humans. Teach people how to identify malware/mail and you'll be in a much better security posture.

[Why the Midwest Is a Hotbed for Innovation](https://fortune.com/2019/11/15/chris-olsen-drive-capital/) — There is somewhat of a bias against venture capital in tech to spent in the middle part of the US. Turns out, there's a lot of great talent and infrastructure out here.

[Facebook and Instagram crash on Thanksgiving](https://www.theguardian.com/technology/2019/nov/28/facebook-instagram-crash-thanksgiving) — It's interesting that we look up to companies like Facebook and Twitter as examples of managing scale in microservices and users. But, it's also really interesting when they falter on a holiday I would expect an increase in capacity being needed for.

[Did You Forget the Ops in DevOps?](https://www.infoq.com/articles/did-you-forget-ops-in-devops/) — Yeah, you probably did. But, there is a way to recover.

[Hope Is Not A Strategy: How Hardware Issues Affect Your PostgreSQL Data](https://info.crunchydata.com/blog/hope-is-not-a-strategy-the-hpe-ssd-issues-and-protecting-your-postgresql-data) — This is why hardware matters. HPE has a bug that is killing SSDs after a little over three years. "Remember, 'the cloud is just someone else's computer', right? Now that you are aware of the firmware issue you should be asking some questions of your own..."

[A hacking group is hijacking Docker systems with exposed API endpoints](https://www.zdnet.com/article/a-hacking-group-is-hijacking-docker-systems-with-exposed-api-endpoints/)

[VMware Stock Could Fall as Kubernetes Cloud Shift Comes Too Late](https://www.barrons.com/articles/vmware-stock-cloud-containers-kubernetes-51574459195) — You have to wonder if VMware is making so much noise because they know the Kubernetes ship has long left the dock. They do have to execute on a number of things and last I heard, a lot of the decisions still needed to be made on what is net new and what is reused from VMware's existing portfolio. That's kinda wild considering VMware wants to release Tanzu sooner rather than later. If VMware is successful (which I believe they will be to a certain degree), we're probably all going to look back on it as a major dodged bullet by VMware. Same with Red Hat being bought by IBM. It's an awesome time to be in tech right now.

## Tools

[Run Ansible Tower or AWX in Kubernetes or OpenShift with the Tower Operator](https://www.jeffgeerling.com/blog/2019/run-ansible-tower-or-awx-kubernetes-or-openshift-tower-operator) — A Kubernetes Operator written in Ansible to install Ansible Tower or AWX on the Kubernetes cluster of your choice! Also, yes, you can build CRDs with Ansible. Awesome stuff happens when folks discover the Operator Framework and Ansible work well together. Huge thanks to Jeff Geerling.

[Systemd 244 Released With New Init System Features For Black Friday](https://www.phoronix.com/scan.php?page=news_item&px=systemd-244-released) — cgroups v2, y'all!

[Top Kubernetes Operators advancing across the Operator Capability Model](https://blog.openshift.com/top-kubernetes-operators-advancing-across-the-operator-capability-model/) — Shoutout to the teams out there making it incredibly easy to manage their applications on Kubernetes!

[How to set up a serious Kubernetes terminal](https://medium.com/free-code-camp/how-to-set-up-a-serious-kubernetes-terminal-dd07cab51cd4) — Pick and choose what works best for you.

[Interactively Debugging the Rego Policy Language with Fregot](https://www.fugue.co/blog/interactively-debugging-the-rego-policy-language-with-fregot)

[Vagaries of Git Merge](http://tycon.github.io/git-inconsistencies.html) — "The bottom line is that: Git merge is inconsistent and Git merge is unintuitive" You had me at git and unintuitive. I often wonder what using a tool like git has on the industry overall; it's not an easy to use tool outside of clone, branch, commit, and push. And even then, it can have it's inconsistencies.

[Resolving a minor turkey day networking mystery](https://rachelbythebay.com/w/2019/11/28/sb8200/) — Oh the joys of going home for the holidays!

[Amazon's cloud unit has designed a more powerful datacenter chip](https://venturebeat.com/2019/11/28/amazons-cloud-unit-has-designed-a-more-powerful-datacenter-chip/) — And it's Arm-based! "One of the sources familiar with the matter said it will be at least 20% faster than Amazon’s first Arm-based chip, named Graviton, which was released last year as a low-cost option for easier computing tasks."

[10 Things To Boost Your Workflow in Visual Studio Code](https://medium.com/better-programming/10-things-to-boost-your-workflow-in-visual-studio-code-1a64d20cc6e4) _ YMMV but, I use a few of these for writing this newsletter alone.

[Making your Go app configurable](https://travix.io/making-your-go-app-configurable-bb5e5f4a9df9) — "Using a good settings strategy can make local development and deployment a lot easier."

[Writing a reverse proxy in Go](https://developer20.com/writing-proxy-in-go/)

[sukeesh/k8s-job-notify](https://github.com/sukeesh/k8s-job-notify) — Kuberenets Job/CronJob Notifier

[alibaba/Alink](https://github.com/alibaba/Alink) — Alink is the Machine Learning algorithm platform based on Flink, developed by the PAI team of Alibaba computing platform.

[laurent22/joplin](https://github.com/laurent22/joplin) — Joplin - an open source note taking and to-do application with synchronization capabilities for Windows, macOS, Linux, Android and iOS.

[localstack/localstack](https://github.com/localstack/localstack) — A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline!

## Tweet of the Week

{{< tweet 1198977232452145152 >}}
