+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-10-14T07:00:00Z
description = "Kubernetes, Amazon Woes, Serverless, JEDI, Spinnaker, and More"
draft = false
slug = "097"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "automation", "ansible", "security", "google", "amazon"]
title = "097: Kubernetes, Amazon Woes, Serverless, JEDI, Spinnaker, and More"

+++

I spent the week in Orlando. The first two days for work and the last three for play. This is the second business trip the family has been on with me in as many months. It's interesting to chaos test your travel routines with weird bookings due to work needs. I try to spend very little time proving who I am or what I do when I travel. I've had horrific experiences traveling and I go out of my way to reduce the chances of that happening. I've optimized for smoother sailing through government and security checkpoints. My family has no status or extra vetting. It's amazing to see what happens when traveling with them. Throwing a toddler into the mix changes everything. All systems seemed to be geared toward not having a toddler meltdown. We often comment here in the US how all the "added" security post-9/11 is more theater than actual security. We all have stories of smuggling something we forgot to take out of a bag through security. This makes me wonder about how much of what we do might actually be more theater than anything. Dashboards are great but, if the most important dashboard a team has is the one that only leadership looks at (never used by anyone else) perhaps that's more theater than improved outcomes. What else in our day-to-day operations is theater and not adding any real value to our work?

[**Webinar: Actionable Continuous Delivery Metrics**](https://info.thoughtworks.com/Actionable_CD_Metrics.html)  
Want to deliver faster? Join our free webinar: Actionable Continuous Delivery Metrics. Gain insights into software delivery pipeline and learn to use metrics to improve your path to production. *SPONSORED*

[**Finally, it's time for actionable APM!**](https://raygun.com/)  
Raygun delivers what New Relic and other APM tools can't: an intuitive and easy to use interface with unparalleled detail into app transactions. [Now available for .NET.](https://raygun.com/) *SPONSORED*

[**Sponsor DevOps'ish**](/sponsor/)  
A new sponsor was supposed to have their ad copy here this week. But, they never sent it to me (invoice is paid and all). Maybe your company can do better?

{{< sponsor-blurb >}}

## People

[I'm Leaving Google — Here's the Real Deal Behind Google Cloud](https://medium.com/@amirh1/im-leaving-google-and-here-s-the-real-deal-behind-google-cloud-1b86513be01b): The good and bad of GCP through the eyes of someone leaving Google.

[Stop hiring for culture fit: 4 ways to get the talent you want](https://opensource.com/open-organization/18/10/reconsider-culture-fit): If you're looking for talented people you can turn into cultural doppelgängers—rather than seeking to align productive differences toward a common goal—you're doing it wrong.

[What's a senior engineer's job?](https://jvns.ca/blog/senior-engineer/): I like how Julia points out what a senior engineer IS NOT. If you're doing 1:1s with folks, you're a manager.

[Why Some Amazon Workers Are Fuming About Their Raise](https://www.nytimes.com/2018/10/09/technology/amazon-workers-pay-raise.html): Amazon has raised it's minimum wage to $15 after getting dogged by Bernie Sanders for a long time. However, that money has been recouped by restructuring bonuses and stock grants for employees. There's a lot of FUD out there about this. But, a few folks I know that work at Amazon as hourly employees are getting raises and they're happy about it. If you're impacted by this and you're not happy about it, please let me know how. I'd like to understand this a little better.

[Annual "CNCF Community Awards" Nominations Kick Off – Winners to be Recognized at KubeCon + CloudNativeCon Seattle](https://www.cncf.io/blog/2018/10/08/annual-cncf-community-awards-nominations-kick-off-winners-to-be-recognized-at-kubecon-cloudnativecon-seattle/)

[Amazon scraps secret AI recruiting tool that showed bias against women](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight/amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK08G): Amazon built a tool to speed hiring. It "learned" that most candidates were male and became biased against women.

[GitLab + STEM Gems: Giving girls role models in tech](https://about.gitlab.com/2018/10/08/stem-gems-give-girls-role-models/): Meet the GitLabbers working to inspire the next generation to pursue careers in STEM.
{{< carbon_ads >}}

## Process

[The Non-Code Contributor's Guide to Kubernetes opens the field to users of all developing levels](https://jaxenter.com/kubernetes-non-code-contributors-guide-150422.html): "Want to help contribute to Kubernetes but you're not a coder? No problem! Thanks to the Non-Code Contributor's Guide, the Kubernetes community explicitly spells out how fans can help out even if they're still learning all that developing stuff."

[Five Tips for Kubernetes Network Security and Compliance](https://www.tigera.io/blog/five-tips-for-kubernetes-network-security-and-compliance/): "Kubernetes changes the way that we implement security controls. Here are some best practices for securing those environments."

[Serverless DevOps: Where Does Ops Belong?](https://www.serverlessops.io/blog/serverless-devops-where-does-ops-belong): "The operations team will go away." Heh... Sure... So will mainframes.

[Announcing upcoming changes to our consumer Google+ and Gmail services; Increased investment in Google+ for the enterprise](https://cloud.google.com/blog/products/g-suite/announcing-upcoming-changes-to-our-consumer-googleplus-and-gmail-services-increased-investment-in-googleplus-for-the-enterprise): Also known as, "We hid a security flaw for months and are now killing the service entirely." [Google for months kept secret a bug that imperiled the personal data of Google+ users](https://www.washingtonpost.com/technology/2018/10/08/google-overhauls-privacy-rules-after-discovering-exposure-user-data/)

[PagerDuty's 3-Year Journey to DevOps Culture](https://thenewstack.io/pagerdutys-3-year-journey-to-devops-culture/): "If you don't have 150 percent conviction, don't bother."

[Oracle? On my server? I must have been hacked! *Penny drops* Oh sh-](https://www.theregister.co.uk/2018/10/08/who-me/): This is my server. That's your server. No, wait, that's your server...

[Managing Kubernetes](http://shop.oreilly.com/product/0636920146667.do): Operating Kubernetes Clusters in the Real World by Brendan Burns and Craig Tracey

[I find your lack of faith disturbing, IBM: Big Blue fires photon torpedo at Pentagon JEDI cloud contract](https://www.theregister.co.uk/2018/10/10/ibm_jedi_contract/): But Oracle shot first

[Google Cloud drops out of the running for the Pentagon's $10B cloud contract](https://www.geekwire.com/2018/google-cloud-drops-running-pentagons-10b-cloud-contract/): The JEDI contract stuff is getting weird now.

[Who Cares if Supermicro Happened. Supply Chain Attacks are Real and It's Time to Pay Attention](https://blog.sonatype.com/is-supermicro-real-who-cares.-supply-chain-attacks-are-happening-and-its-time-to-talk-about-it): Act as if everything is compromised and it's amazing how your perspective on the world will change.

[Fortnite squads have 5 lessons for agile teams](https://enterprisersproject.com/article/2018/10/fortnite-squads-have-5-lessons-agile-teams): Fortnite players have plenty to teach agile and DevOps teams. So let's head over to Tilted Towers and build your skills

[Netlify just got $30 million to change the way developers build websites](https://techcrunch.com/2018/10/09/netlify-just-got-30-million-to-change-the-way-developers-build-websites/): Congrats to the folks at Netlify!

[BBC News disrupted by software glitch](https://www.bbc.com/news/technology-45812540): An upgrade gone wrong.
{{< carbon_ads >}}

## Tools

[Securing Your Application Metrics & Distributed Logging with SPIFFE, Prometheus and Fluentd](https://blog.scytale.io/secure-application-metrics-distributed-logging-with-spiffe-f54f9f798124)

[Buildah version 1.4 Release Announcement](https://buildah.io/releases/2018/10/08/Buildah-version-v1.4.html)

[Spinnaker is the next big open source project to watch](https://techcrunch.com/2018/10/09/spinnaker-is-the-next-big-open-source-project-to-watch/): Yes, a slightly clickbaity headline. But, the Spinnaker team is putting pieces in place to make it successful. Time will show us whether or not things will pan out for Spinnaker.

[Facebook Continues Making Extensive Use Of systemd](https://www.phoronix.com/scan.php?page=news_item&px=Facebook-systemd-2018): Facebook is leveraging a lot of cool things in systemd.

[Security release of minikube v0.30.0 - CVE-2018-1002103](https://discuss.kubernetes.io/t/security-release-of-minikube-v0-30-0-cve-2018-1002103/3078): A security issue was discovered in minikube versions v0.29.0 or older. The issue is Critical and upgrading to v0.30.0 of minikube is encouraged to fix this issue.

[Ansible reboot Linux machine or server with playbooks](https://www.cyberciti.biz/faq/ansible-reboot-linux-machine-or-server-with-playbooks/): A guide on how to use the new reboot module in Ansible 2.7.

[Google GKE vs Microsoft AKS vs Amazon EKS](https://kubedex.com/google-gke-vs-microsoft-aks-vs-amazon-eks/): "There have been many comparisons done between these cloud hosted Kubernetes providers already. However, probably none as honest as this one."

[Orleans](https://dotnet.github.io/orleans/): A straightforward approach to building distributed, high-scale applications in .NET

[Introducing Volume Snapshot Alpha for Kubernetes](https://kubernetes.io/blog/2018/10/09/introducing-volume-snapshot-alpha-for-kubernetes/): "Kubernetes v1.12 introduces alpha support for volume snapshotting. This feature allows creating/deleting volume snapshots, and the ability to create new volumes from a snapshot natively using the Kubernetes API."

[Cloud Foundry embraces Kubernetes](https://www.zdnet.com/article/cloud-foundry-embraces-kubernetes/): Kubernetes mastery of cloud container management takes another step forward.

[Outline: secure access to the open web](https://opensource.googleblog.com/2018/10/outline-secure-access-to-open-web.html): I've been using Outline for a while now. It's nice in the, "it just works" sort of way. Easy to stand up and easy for users of all skill levels to use.

[bpftrace (DTrace 2.0) for Linux 2018](http://www.brendangregg.com/blog/2018-10-08/dtrace-for-linux-2018.html): "It's shaping up to be a DTrace version 2.0: more capable, and built from the ground up for the modern era of the eBPF virtual machine."

[Garie](https://garie.io/) was built with simplicity in mind and to help developers start monitoring their web performance.

[zegl/kube-score](https://github.com/zegl/kube-score): Kubernetes object static code analysis

[Dropbox traffic infrastructure: Edge network](https://blogs.dropbox.com/tech/2018/10/dropbox-traffic-infrastructure-edge-network/)

[Kubernetes v1.12: Introducing RuntimeClass](https://kubernetes.io/blog/2018/10/10/kubernetes-v1.12-introducing-runtimeclass/): RuntimeClass is an alpha feature for selecting the container runtime configuration to use to run a pod's containers.

[Go 1.11 got me to stop ignoring Go](https://drewdevault.com/2018/10/08/Go-1.11.html)

[Puppet rolls out new tools to measure, accelerate devOps](https://www.zdnet.com/article/puppet-rolls-out-new-tools-to-measure-accelerate-devops/): The IT automation company is introducing a metrics tool that should enable IT leaders to make a quantifiable business case for scaling devOps.

[Systems Monitoring: top vs Htop vs Glances](http://tech.marksblogg.com/top-htop-glances.html): "In this post I'm going to look at three popular tools often used for ad-hoc monitoring as well as look at a simplistic solution for monitoring distributed systems."

## DevOps'ish Tweet of the Week

If you find yourself commenting code, this is a sign that it is not written clearly enough. Code should be self-documenting.

For the same reason, no process at work should be documented: A well-run business is its own documentation.

— Reginald Braithwaite (@raganwald) [October 9, 2018](https://twitter.com/raganwald/status/1049716731172638722?ref_src=twsrc%5Etfw)