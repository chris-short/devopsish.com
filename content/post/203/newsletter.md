+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-01-31T07:00:00Z
description = "Job hopping, Block Party, Perl.com pain, SSPL sucks, sudo vuln, cloud trends, the beauty of Windows 3.11, and more"
draft = false
slug = "203"
tags = ["cloud", "Cloud Native", "DevOps", "open source", "Red Hat", "network", "Windows", "sudo", "Tracy Chou", "AWS", "trends", "nmap", "LaunchDarkly", "GitOps", "compensation", "culture", "impact", "community", "development", "software development", "Solarwinds", "security", "disinformation", "infrastructure", "runtime", "Microsoft", "IBM"]
title = "DevOps'ish 203: Job hopping, Block Party, Perl.com pain, SSPL sucks, sudo vuln, cloud trends, the beauty of Windows 3.11, and more"

+++

We don't talk about salaries in the US like people do in other countries. Apparently, we citizens of the United States are extremely conservative when it comes to this topic. I'd like to see that change in my lifetime.

I sat down and looked at my W-2 like I do every year. A number hit me out of the blue. It proved to me job hopping works (to a point). From my first job out of the military to now, I've increased my salary by 3X. I'm not trying to brag at all. It's a living testament that veterans are likely undervalued. Also, that they should take full advantage of their newfound job flexibility.

When you look at my resume, since 2011, I've held 12 different positions. Each one was a pay raise, status boost, morality alignment, or open source work alignment. Then there was a transition from carrying a pager to not carrying one anymore. I've been at Red Hat for two and a half years. Today, my job is the best job I've ever had (and that is saying a lot). But, the two positions before joining Red Hat were only six-month stints with very legitimate reasons for leaving both. But, before that, a year at a great company. It shows that people are willing to work for great companies that align with their morals and ethos. Red Hat is a fantastic tech company with a wonderful culture. Every move to get here was worth it. Because it finally put my value and compensation in sync. It has made up for the previous nine years of not being able to put as much in a college or retirement fund. But, now that's all possible.

I'm writing this for my veteran friends. If I had made it to the 20-year mark, I would have retired last year. They are the ones that need to hear this. Trust your gut. You made it here by doing that many times before. You know when you feel like you might be giving up too much for too little. Always be looking for new opportunities that align your multitude of hard skills with proper compensation. But, once you find that perfect place for you, **STAY PUT**. Do your thing in that company for a few years. Make your best work of your life. Show them you're worth more than what they're paying you in the process. But, always be looking for the next perfect thing for you. My measurement is impact or more so, what kind of impact I can make? Make sure you get paid in the process.

## People

[Tracy Chou builds anti-harassment tools, amid Reddit attacks](https://www.protocol.com/harassment-block-party-app)  
I cannot recommend [Block Party](https://www.blockpartyapp.com/) more highly. I've found a few snakes in the grass already.

[The Non-psychopath's Guide to Managing an Open-source Project](https://queue.acm.org/detail.cfm?ref=rss&id=3447645)  
"Respect your staff, learn from others, and know when to let go." That last one is the most important. If the community can't keep it going and you're the only one that is, rethink your strategies or walk away (it's not a hit).

[Open source software development is booming in Nigeria - Business Insider](https://web.archive.org/web/20210126095059/https://www.businessinsider.com/open-source-booming-in-nigeria-fintech-startups-paystack-nigeria-2021-1?r=DE&IR=T) (archive.org link to get around paywall)  
"In 2016, Paystack became the first Nigerian company to be accepted by the hot Silicon Valley startup incubator Y Combinator in recent years. Its acceptance spurred other firms to apply: In total, 21 Nigerian startups have participated in the program. Paystack made waves again last year when Stripe announced plans in October to acquire it for a reported $200 million." Bucket list: visit Nigerian tech company headquarters.

[Twitter Bots Are a Major Source of Climate Disinformation](https://www.scientificamerican.com/article/twitter-bots-are-a-major-source-of-climate-disinformation/)  
We're doomed.

[Mediacom Warns Top 0.05% of Uploaders to Cut It Out, Cites Network “Stress”](https://stopthecap.com/2021/01/27/mediacom-warns-top-0-05-of-uploaders-to-cut-it-out-cites-network-stress/)  
We upload about 50 GB a week from here. We likely wouldn't be in this group. We're on a business plan since the pandemic because well our everything is internet-based basically and we were blowing through data caps monthly. But, this story makes me feel bad for the folks being targeted.

[Domain for popular programming website Perl.com stolen in ‘hack’](https://portswigger.net/daily-swig/domain-for-popular-programming-website-perl-com-stolen-in-hack)  
Timing is everything... Renewals too. This would have really sucked if it happened to a language you were using.

## Process

[30% of “SolarWinds hack” victims didn’t actually use SolarWinds](https://arstechnica.com/information-technology/2021/01/30-of-solarwinds-hack-victims-didnt-actually-use-solarwinds/)  
*PLOT TWIST*  
[The attackers] gained access to their targets in a variety of ways. This adversary has been creative... it is absolutely correct that this campaign should not be thought of as the SolarWinds campaign.

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[Nmap project becomes latest victim of Google’s ‘wrongful blocking’ of cybersecurity resources](https://portswigger.net/daily-swig/nmap-project-becomes-latest-victim-of-googles-wrongful-blocking-of-cybersecurity-resources)  
Nmap is an amazing swiss army knife of tools to help you troubleshoot. The fact that some people use it for nefarious reasons is irrelevant to me. You can misuse a pencil. Nmap has been around since the 90s and is amazingly useful.

[The SSPL is Not an Open Source License](https://opensource.org/node/1099)  
"And the software commons are now poorer for it. The Elastic projects were offered under the Apache license. Outside contributors donated time and energy with the understanding that their work was going towards the greater good, the public software commons. Now, instead, their contributions are embedded in a proprietary product. If they want to enjoy the fruits of their own and their co-contributors’ labor, they have to agree to a proprietary license or fork."

[On Elastic, its fork, MongoDB, and the SS Public License](https://sfconservancy.org/blog/2021/jan/29/elastic-and-ss-public-license/)  
There you have it! Everyone hates the SSPL.

[Open source is still not a business model](https://funnelfiasco.com/blog/2021/01/22/open-source-business-model/)  
Then there's the license change you missed!

[NAT Slipstreaming v2.0: New Attack Variant Can Expose All Internal Network Devices to The Internet](https://www.armis.com/resources/iot-security-blog/nat-slipstreaming-v2-0-new-attack-variant-can-expose-all-internal-network-devices-to-the-internet/)  
"The new variant attack could allow attackers to bypass NATs & Firewalls and reach any unmanaged device within the internal network from the Internet."

## Tools

[Baron Samedit: Heap-based buffer overflow in Sudo (CVE-2021-3156)](https://www.openwall.com/lists/oss-security/2021/01/26/3)  
This one is gnarly enough for us to mention on-air this week on [OpenShift Administrator's Office Hour](https://www.youtube.com/watch?v=YHswrGunATY). Finish reading this newsletter then go patch sudo. IMMEDIATELY. ([Red Hat](https://access.redhat.com/security/vulnerabilities/RHSB-2021-002) version)

**LaunchDarkly** is a feature management platform that empowers all teams to safely deliver and control software through feature flags. By separating code deployments from feature releases, LaunchDarkly enables you to deploy faster, reduce risk, and iterate continuously. Microsoft, IBM, Atlassian, and 1500+ organizations use LaunchDarkly to build, operate, and learn from their software. [Learn more](https://launchdarkly.com/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) and start your free trial today! *SPONSORED*

[4 cloud trends to watch in 2021](https://www.ciodive.com/news/2021-cloud-trends/593777/)  
"The move to the cloud isn't slowing down, but businesses are tidying strategies to take full advantage of a hot cloud moment. Meanwhile, vendors reap the benefits. For SaaS providers, mass scale remote work led to a cloud market boom as companies pivoted toward digital."

[Kubernetes - How to Debug CrashLoopBackOff in a Container](https://releaseapp.io/blog/kubernetes-how-to-debug-crashloopbackoff-in-a-container)  
"We aren’t going to cover how to configure k8s properly in this article, but instead will focus on the harder problem of debugging your code or, even worse, someone else’s code 😱"

[Kubernetes and GitOps with Flux CD V2.0](https://raynix.info/archives/3769)  
"Following the official instructions it didn’t take me long to fully enable GitOps on my cluster."

[Scaling Kubernetes to 7,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-7500-nodes/)  
"Scaling a single Kubernetes cluster to this size is rarely done and requires some special care, but the upside is a simple infrastructure that allows our machine learning research teams to move faster and scale up without changing their code."

[GParted 1.2 Open-Source Partition Editor Released with exFAT Support](https://9to5linux.com/gparted-1-2-open-source-partition-editor-released-with-exfat-support)  
Everyone's favorite partition manager and disk management tool gets an update.

[Remembering Windows 3.1 themes and user empowerment](https://hisham.hm/2019/07/26/remembering-windows-31-themes-and-user-empowerment/)  
They're right. You could tune everything, every little detail in Windows 3.11. Do you want pink windows with purple letters? TADA! Now we just get dark mode and are thrilled by it.

[berty/berty](https://github.com/berty/berty)  
Berty is a secure peer-to-peer messaging app that works with or without internet access, cellular data or trust in the network

[generalui/s3p](https://github.com/generalui/s3p)  
list/copy/sync/compare S3 buckets 5x-50x faster than aws-cli


## DevOps'ish Tweet of the Week

[![Git. It was designed with actual gatekeeping in mind, and it is far more destructive than CSS. Git is like your high school self's "shit the computer crashed and last I saved my paper hours ago" on STEROIDS.](https://shortcdn.com/file/devopsish/203-devopsish-tweet-of-the-week.png)](https://twitter.com/guincodes/status/1355023910509502470)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/203/notes/) to see what didn't make it to the newsletter.
