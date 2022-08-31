+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2018"]
date = 2018-02-18T02:00:00Z
description = ""
draft = false
slug = "063"
tags = ["devops", "cloud native", "open source", "continuous improvement", "change", "Kubernetes", "serverless", "leadership", "culture", "go", "golang", "linux", "google", "containers", "Kubernetes Operators", "Docker"]
title = "063: Kubernetes Tips & Tricks, Leadership, Serverless, dtrace for Linux, Azure for Go, and More!"
image ="https://shortcdn.com/devopsish/seeing-the-light.jpg"
imagealt = "Seeing the light"

+++

I listened to a very impactful podcast on Wednesday while walking my [best buddy beast (happy birthday, Sunny)](https://www.instagram.com/p/BfL1YAenilh/?taken-by=thechrisshort). On the podcast, the speaker asked the audience five questions. One of those questions was, "When was the last time you changed your mind?" This question struck me. When was the last time I changed my mind? What motivated me to make that change? Would I be able to help others make a similar change should they ask for assistance? My mind raced through a series of events where I felt my mind had changed on something. Some were significant, others were trivial. But, the one thing I realized is that I change my mind often. It goes back to something I've mentioned in this newsletter a few times, **resisting change is a DevOps anti-pattern**. It also harkens back to the [strong opinions, loosely held](/048/) mantra that I have tried to adapt to. The speaker goes on to mention that being able to change your mind requires you to be humble, confident, and able to listen. Listen as in actually listening not pausing until the other person is done speaking.

So much of technology and working with it and in it involves change. Yet, as technologist and humans, we are terrible at change. We fear the unknown. We resist breaking the status quo. The fact of the matter is that as humans, our adaptability is what keeps us alive. Could the human race survive as long as it has without adapting to new things? No. So please, do not mock the person that tries new ways to do things. Do not chastise someone for getting smart home equipment to turn on lights. Those people are the ones iterating on things in their lives as part of their continuous improvement process. If your goal is to be the best light switch operator in the world then focus on that. Don't worry about the rest of the world eliminating the need for the light switch altogether. The best people for business are the ones automating themselves out of their job. Keep giving them more stuff to automate. The podcast? The [Lawfare Podcast: Chuck Rosenberg on Value-Based Leadership](https://lawfareblog.com/lawfare-podcast-chuck-rosenberg-value-based-leadership). Say what you want about Chuck Rosenberg's politics, fine. But, you cannot question the leadership style and lessons learned from this podcast.

[**How to build your first GoCD continuous delivery pipeline?**](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_hacks_no_visual&utm_term=)  
This blog uses a simple web service as an example to show you how to setup your first GoCD continuous delivery pipeline and manage your build version in it. [Check out the blog](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=cd_hacks_no_visual&utm_term=), and [get started with GoCD](https://www.gocd.org/2018/02/13/managing-build-versions-pipeline/?utm_campaign=cd_hacks&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=GOCD_getting_started&utm_term=). *SPONSORED*

[**Next-Gen Immersive Cloud Visualization Interface for your AWS, With Live Topology View!**](https://totalcloud.io/?utm_medium=newsletter_ad&utm_source=devopsish)  
TotalCloud is first-of-its-kind visually-rich interactive & immersive visual platform offering real-time AWS cloud management & monitoring capabilities. Ideal for DevOps and IT managers, this unique platform provides a single pane of glass view of IT infrastructure across all AWS cloud services on a live topology bedecked with rich metric data & insights. [Take 30-day free trial, today](https://totalcloud.io/user-signup.html?utm_medium=newsletter_ad&utm_source=devopsish), and experience quicker & easier contextual monitoring, debugging, cost optimization, cloud operations, and security & compliance fixes on a single gaming-AI powered visual console. *SPONSORED*


## People

[Containers Will Not Fix Your Broken Culture (and Other Hard Truths)](https://queue.acm.org/detail.cfm?id=3185224): I've seen Bridget give this talk a few times and I'm very glad to see it become a written work.

[On-call by Cindy Sridharan](https://medium.com/@copyconstruct/on-call-b0bd8c5ea4e0): "Simply put, building a humane on-call culture and long-term sustainable practices can, in fact, help attract more candidates to the company, as opposed to turning off folks."

[Who Killed The Junior Developer?](https://medium.com/@melissamcewen/who-killed-the-junior-developer-33e9da2dc58c) You have to have a pipeline in your company. Your senior devs will leave at some point.

[Command Line Heroes: DevOps_Tear Down That Wall](https://www.redhat.com/en/command-line-heroes/devops-tear-down-that-wall)

[IBM sues Microsoft's new chief diversity officer over non-compete agreement](https://www.geekwire.com/2018/ibm-sues-microsofts-new-chief-diversity-officer-non-compete-agreement/): What the actual fuck is IBM doing? To say this won't be perceived well is an understatement.

[The Future of Ops](https://blog.realkinetic.com/the-future-of-ops-4e4842664445): "The future of Operations is actually, in many ways, much like the future of QA. Traditional QA roles are shifting away from test-focused to tools-focused."

[The futile comfort of working long hours](https://codewithoutrules.com/2018/02/11/working-long-hours/): "Instead of valuing work, you can value outcomes: outcomes at your job, outcomes in your life, outcomes in the world."

[Power Can Corrupt Leaders. Compassion Can Save Them](http://hbr.org/2018/02/power-can-corrupt-leaders-compassion-can-save-them): "Yes, he apologized, but he didn't seem remorseful. Rather, he seemed a little taken aback by the whole thing, as if he really didn't understand what all the fuss was about."

[SpaceX hits two milestones in plan for low-latency satellite broadband](https://arstechnica.com/information-technology/2018/02/spacexs-satellite-broadband-nears-fcc-approval-and-first-test-launch/): Since my days in the Air Force, I have always been interested in the satcom space (I did have to work with satellites often). If SpaceX has figured out a low-cost way to eliminate the half a second latency across satellite links I'd be very happy.

[Six top US intelligence chiefs caution against buying Huawei phones](http://www.cnbc.com/2018/02/13/chinas-hauwei-top-us-intelligence-chiefs-caution-americans-away.html): I don't think the intel world likes the Chinese.

[Inclusion is a Hack](https://cate.blog/2018/02/13/inclusion-is-a-hack/): "I wish more people understood that (in tech) inclusion – as we talk about it – is a hack."

[Diversity Scholarship Series: KubeCon – Endless Opportunities and The Connections You'll Make](http://www.cncf.io/blog/2018/02/15/diversity-scholarship-series-kubecon-endless-opportunities-connections-youll-make/): "As a fairly new member of the Kubernetes community, my interaction with the community has been overwhelmingly welcoming. Usually offering help even before needing to ask. As a word of encouragement and gratitude, please continue to help each other as you have certainly helped me."

[The Cloud Native Computing Foundation (CNCF) participates in Google's Summer of Code (GSoC)](https://github.com/cncf/soc): CNCF is a great place to spend a summer learning, coding, participating and contributing. We are an exciting open source foundation with a vibrant community of projects, and we look forward to your application and your project ideas!

[Fired Google Engineer Loses Diversity Memo Challenge](http://www.bloomberg.com/news/articles/2018-02-16/google-firing-of-damore-was-legal-u-s-labor-panel-lawyer-said): 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣

## Process

[The CNCF takes steps toward serverless computing](https://www.cncf.io/blog/2018/02/14/cncf-takes-first-step-towards-serverless-computing/): The Cloud Native Computing Foundation has launched a serverless working group. To me, this is a natural evolution for serverless and the CNCF. However, in my opinion, DIY serverless/functions is a solved problem: use [**OpenFaaS**](https://www.openfaas.com/).

[Cloud Native and Serverless Landscape](http://aniszczyk.org/2018/02/16/cloud-native-and-serverless-landscape/): Yep... Another CNCF landscape for your dart practice this time around serverless.

[Your DevOps attempt will fail without these 7 departments buying in](https://opensource.com/article/18/2/essential-roles-devops-culture-success): Achieving customer value requires more than just software development and IT operations.

[Cloud Unfiltered Podcast, Episode 35: Talking Cloud Native with Justin Garrison](https://blogs.cisco.com/cloud/cloud-unfiltered-podcast-episode-35-talking-cloud-native-with-justin-garrison)

[Atos, IT provider for Winter Olympics, hacked months before Opening Ceremony cyberattack](https://www.cyberscoop.com/atos-olympics-hack-olympic-destroyer-malware-peyongchang/): Is anyone surprised?

[Grappling with DevOps Security](https://www.cso.com.au/article/633432/grappling-devops-security/): If you're grappling with security at the speed of DevOps in your organization you should probably reach out to me for professional help.

[Responding to new open source vulnerability disclosures](https://www.oreilly.com/ideas/responding-to-new-open-source-vulnerability-disclosures): "A new vulnerability disclosure is not a new vulnerability. The security flaw existed in your library's code all along, introducing a weakness in your application. However, when a vulnerability is made public, its likelihood of being exploited skyrockets."

[Zero Downtime Deployment with Kubernetes](http://rahmonov.me/posts/zero-downtime-deployment-with-kubernetes/): "It is 2018 and your users will not, I repeat, WILL NOT tolerate any downtime or outage with your application.

[The Linux Foundation Launches Open FinTech Forum: AI, Blockchain, Kubernetes & Quantum on Wall Street](https://events.linuxfoundation.org/events/open-fintech-forum-2018/): The Linux Foundation goes to Wall Street!

[Everything I know about open source I learned from SpaceX](https://opensource.com/article/18/2/everything-i-know-about-open-source-i-learned-spacex)

Want to write for opensource.com and can't come up with a good topic? Reach out to me or take a gander at the [opensource.com editorial calendar](http://opensource.com/resources/editorial-calendar) for inspiration.

## Tools

[dtrace for linux; Oracle does the right thing](https://gnu.wildebeest.org/blog/mjw/2018/02/14/dtrace-for-linux-oracle-does-the-right-thing/): YAY! dtrace is coming to Linux!

[Kubernetes: Cron Jobs](https://chrisshort.net/kubernetes-cron-jobs/): "High-available cron jobs have been a beast I've tried to slay many times. This is now a solved problem and all I have to do is implement it."

[**Go 1.10 is released**](https://blog.golang.org/go1.10): "The most exciting part of this release for many people will probably be that the `go` tool now does automatic caching of build & test results."

[Top 10 Kubernetes tips and tricks](https://hackernoon.com/top-10-kubernetes-tips-and-tricks-27528c2d0222): Not sure how I missed this but these tips are very important to be mindful of when running Kubernetes.

[Kubernetes - A Comprehensive Overview](https://www.slideshare.net/BobKillen/kubernetes-a-comprehensive-overview-updated): Bob Killen, recently presented an in-depth overview of Kubernetes and it's various components. Definitely worth a bookmark for folks being introduced to Kubernetes.

[Rainbow Deploys with Kubernetes](http://brandon.dimcheff.com/2018/02/rainbow-deploys-with-kubernetes/): My friend, Brandon Dimcheff of Olark, walks through how using git SHAs as hex color codes bends the blue/green concept towards something much better IMHO.

[PodCTL #25 – Kubernetes Myths & Misperceptions – Part I](https://blog.openshift.com/podctl-25-kubernetes-myths-misperceptions-part-i/): "Take a look at some of the common and recent myths and misperceptions about containers and Kubernetes."

[Get started with KVM & Kubernetes](https://blog.alexellis.io/kvm-kubernetes-primer/)

[Container runtimes: clarity](https://medium.com/cri-o/container-runtimes-clarity-342b62172dc3): "As a maintainer of the CRI-O container runtime for kubernetes I often get asked the following questions at conferences and meetups: Is CRI-O a replacement for Docker? Is containerd a replacement for CRI-O?"

[Free automated TLS certificates on Kubernetes](https://blog.n1analytics.com/free-automated-tls-certificates-on-k8s/): I will be trying this out on my Raspberry Pi cluster (it probably won't work).

[Exploring the Security of Helm](http://engineering.bitnami.com/articles/helm-security.html): There are several angles from which someone might try to abuse Helm/Tiller

[Leader election in Kubernetes control plane](http://blog.heptio.com/leader-election-in-kubernetes-control-plane-heptioprotip-1ed9fb0f3e6d): #HeptioProTip

[MongoDB gets support for multi-document ACID transactions](https://techcrunch.com/2018/02/15/mongodb-gets-support-for-multi-document-acid-transactions/): Is Mongo trying to be all things database? Has there been a realization that growth requires features? Or... Does this say something about "NoSQL"? You be the judge.

[Building your own CDN for Fun and Profit](https://pasztor.at/blog/building-your-own-cdn): CDNs make the world go round. If you don't understand why they're important or at a high level know how they work, you should.

[Azure for Go developers](https://docs.microsoft.com/en-us/go/azure/)

[How to use Vagrant for Ansible role testing and development](https://blog.keyboardinterrupt.com/testing-ansible-with-vagrant/)

[Teonite t-shirts](https://github.com/teonite/t-shirts): The first Open Source t-shirts (probably)

[spotahome/kooper](https://github.com/spotahome/kooper): Kooper is a simple Go library to create Kubernetes operators and controllers.

## DevOps'ish Tweet of the Week

{{< tweet 963428093292457984 >}}
