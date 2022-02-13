+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2020"]
date = 2020-10-25T07:00:00Z
description = "Complacency, Zoomsterbating, time zones, website carbon footprints, Docker hub policy changes AGAIN, and more"
draft = false
slug = "189"
tags = ["DevOps", "Kubernetes", "time", "streaming", "cloud", "cloud native", "network", "monitoring", "open source", "security", "attack", "observability", "culture", "release", "privacy", "Red Hat", "AWS", "Alice Goldfuss", "Ian Coldwater", "developers", "MITRE", "CNCF", "environment", "Docker", "Intel", "storage", "uptime", "community", "GitHub", "YouTube", "NTP", "NTS", "Firefox", "Git", "PVC", "pvc autoresizer", "secrets", "Jeffrey Toobin", "Zoom", "Detroit", "Zoomsterbating"]
title = "DevOps'ish 189"

+++

I was incredibly busy this week. I spoke at the [October 2020 CNCF Eastern Canadian Meetup](https://www.youtube.com/watch?v=l_EEZV1P15U). I turned the introduction to last week's newsletter into its own blog post, [Fear and Loathing in YAML](https://chrisshort.net/fear-and-loathing-in-yaml/), and it made the front page of [the orange site](https://news.ycombinator.com/item?id=24848511) (you read it here first). And then, of course, all the [live streaming for Red Hat](https://www.openshift.com/blog/this-past-week-on-openshift.tv).

Speaking of live streaming. When we look back at 2020, it seems like live streaming will be the thing the COVID-19 brought into our daily lives. Twitch is cleaning up its act and trying to be a little more grown up: [Twitch DMCA Purge Deletes Thousands Of Streamers' Videos](https://kotaku.com/twitch-deletes-thousands-of-streamers-videos-and-issues-1845429294). Then a major [US politician got up to 400K people viewing her stream](https://www.wired.com/story/aoc-among-us-twitch-stream/) simultaneously. It seems like, live streaming, in general, is turning into the new Twitter. It’s an exciting world, for sure. I need to sit down and write out some additional thoughts on live streaming, my setup, etc. But that’ll be for another day.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

Want to see your organization in DevOps'ish? Review the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. Give the [DevOps'ish Sponsorship Prospectus](https://devopsi.sh/prospectus) a gander if you need help convincing your marketing team they should spend. *SPONSORED*


## People

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[How to waste your career, one comfortable year at a time](https://apoorvagovind.substack.com/p/how-to-waste-your-career-one-comfortable)  
"I recently saw this tweet asking people about their career's most expensive mistake. The most common one was people staying too long at their jobs and not switching sooner." I can confirm this. The happy medium between keeping your job and losing money by not taking the next opportunity is pretty short in tech. If you're early in your career, always be looking for the next thing. Have a minimum pay raise in mind to cover the sunk costs of changing jobs and risk of it sucking for a year. This number will increase over time. The number should be a percentage of your current salary (10-15% pay raises to change jobs is normal). Once you have your feet under you, you'll have an excellent idea of what metrics matter to you.

[Nude on Zoom: Jeffrey Toobin and other embarrassing video meetings](https://www.scmp.com/news/world/article/3106401/nude-zoom-jeffrey-toobin-and-other-embarrassing-video-meetings)  
Henceforth, pants are mandatory. This kind of behavior is 100% unacceptable and if this ever were to happen on a call I was on, I would push for the employee's immediate termination. There's no reason for this. Check your privilege at the door, please. [Zoomsterbating.com](http://zoomsterbating.com) will point to the [Zoomsterbating tag](https://devopsish.com/tags/zoomsterbating/) here on DevOps'ish. A little shame could go a long way in changing behaviors.

[Falsehoods programmers believe about time zones](https://www.zainrizvi.io/blog/falsehoods-programmers-believe-about-time-zones/)  
This is an absolutely wonderful article about earth's time management. There was an update to the tzdata files this week so I cracked it open and read all about how [America/Detroit came to be](https://gist.github.com/chris-short/168f900a369078fcb862c56ed99a6ee6). Time is fascinating and we very much treat like a construct we control.

[Developer survey: C# losing ground to JavaScript, PHP and Java for cloud apps, still big in gaming](https://www.theregister.com/2020/10/21/developer_survey_c_losing_ground/)  
"Plus: What puts off developers from adopting cloud? Price"

[Tea and Anarchy with Alice Goldfuss and Ian Coldwater](https://www.arresteddevops.com/tea-and-anarchy/)  
"Bridget chats with Alice Goldfuss and Ian Coldwater."

## Process

[Protecting K8s Against MITRE ATT&CK Techniques - Download Whitepaper](https://security.stackrox.com/protecting-against-K8s-threats-white-paper.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes for business-critical operations is driving new security challenges that must be addressed - namely an expansion of the attack surface that exposes you to new threats. The MITRE ATT&CK framework was recently adapted to Kubernetes to identify nine distinct attack vectors and techniques unique to Kubernetes that attackers employ. [Download this whitepaper](https://security.stackrox.com/protecting-against-K8s-threats-white-paper.html?Source=DevOpsIsh&LSource=DevOpsIsh) from StackRox to learn about these nine techniques and the individual tactics within each technique, and get actionable recommendations to protect your environment and reduce your attack surface. *SPONSORED*

[How Local Fonts Can Save The Environment](https://kevq.uk/how-local-fonts-can-save-the-environment/)  
This article talks about how creators of web sites have a responsibility to the planet too. The [Website Carbon Calculator](https://www.websitecarbon.com/) is pretty dope too.

[Docker Hub Image Retention Policy Delayed, Subscription Updates](https://www.docker.com/blog/docker-hub-image-retention-policy-delayed-and-subscription-updates/)  
Docker's gonna Docker.

[Startups, It’s Time to Think Like Camels — Not Unicorns](https://hbr.org/2020/10/startups-its-time-to-think-like-camels-not-unicorns)  
"The world has changed. In the wake of Covid-19, and the global recession it has caused, business leaders, innovators, entrepreneurs, and investors are all girding for a long period of extremely challenging conditions in the global market. How can startups and innovators of all stripes survive in such conditions? Many are not prepared."

[Intel Agrees to Sell Storage Unit to SK Hynix for $9 Billion](https://www.bloomberg.com/news/articles/2020-10-20/intel-agrees-to-sell-storage-unit-to-sk-hynix-for-9-billion)  
This is going to change the storage industry in interesting ways.

## Tools

[Oh Dear, uptime monitoring like no other](https://ohdear.app/)  
With Oh Dear, you get uptime monitoring, SSL certificate alerts, performance monitoring and we'll crawl your entire site, reporting 404's, server errors and more. With our unlimited status pages and cron job monitoring, Oh Dear is all the monitoring you'll ever need. Sign up with code DEVOPSISH and get a 30% discount on your first 3 months. *SPONSORED*

[Discussing/modifying the kubernetes/kubernetes release cadence](https://github.com/kubernetes/sig-release/issues/1290)  
In the wake of 2020 day-to-day life, the Kubernetes community is seriously considering moving to three releases a year.The four releases a year cadence is a breakneck pace given everyone's current situation. The thread is a very healthy debate and I'd encourage everyone to read it. Keep your hot takes to yourself though, or [@ me on Twitter](https://twitter.com/ChrisShort) with them or something.

[RIAA blitz takes down 18 GitHub projects used for downloading YouTube videos](https://www.zdnet.com/article/riaa-blitz-takes-down-18-github-projects-used-for-downloading-youtube-videos/)  
This is total bullshit. I use youtube-dl for legit purposes at least two or three times a week. This isn't cool, GitHub.

[On our Abusive Relationship with Mozilla’s Firefox](https://ruzkuku.com/txt/moz-rel.html)  
It is entirely possible we need to leave Firefox behind and encourage something new.

[Linux interface analytics on-demand with iftop](https://www.redhat.com/sysadmin/linux-interface-iftop)  
Got network bandwidth? Are you sure? Find out with iftop.

[Secure NTP with NTS](https://fedoramagazine.org/secure-ntp-with-nts/)  
"NTS is a new authentication mechanism for NTP. It enables clients to verify that the packets they receive from the server have not been modified while in transit. The only thing an attacker can do when NTS is enabled is drop or delay packets."

[Neon Programming Language](https://neon-lang.dev/)  
"Neon is a high-level, statically typed, garbage collected, imperative programming language intended for teaching and learning the craft of programming."

[Fedora 33 To Be Released Next Week](https://www.phoronix.com/scan.php?page=news_item&px=Fedora-33-Next-Week)  
I'll be updating my server before the streaming rig. We'll see how it goes.

[OpenTelemetry's First Release Candidates](https://opensource.googleblog.com/2020/10/opentelemetrys-first-release-candidates.html)  
"OpenTelemetry has hit another milestone with the tracing specification reaching release candidate status."

[Dangit, Git!?!](https://dangitgit.com/)  
Git is an imperfect tool. Here's some help.

[Network Segmentation: Concepts and Practices](https://insights.sei.cmu.edu/sei_blog/2020/10/network-segmentation-concepts-and-practices.html)  
"By seeking easy and uncomplicated network management--or simply because they don't know better--many organizations can end up with hundreds or thousands of systems connected in a single, massive network. This arrangement can lead to havoc if the network falls victim to attack or even unintentional error. In this blog post, we review the basics of network segmentation and describe how organizations should implement it as an ongoing process."

[Introducing pvc-autoresizer](https://blog.kintone.io/entry/pvc-autoresizer)  
"Today, we are excited to announce `pvc-autoresizer`, which is new, Kubernetes-native, open-source software to provide the ability to expand the size of Persistent Volume Claims (PVCs) on Kubernetes cluster automatically."

[contentful-labs/kube-secret-syncer](https://github.com/contentful-labs/kube-secret-syncer)  
A Kubernetes operator to sync secrets from AWS Secrets Manager

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week from @jbaruch](["https://shortcdn.com/file/devopsish/189-devopsish-tweet-of-the-week.png)](https://twitter.com/jbaruch/status/1318589106725687297)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/189/notes/) to see what didn't make it to the newsletter.

