+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-09-24T07:00:00Z
description = "Linus Apologizes, Giveaway Winners, Kubernetes, Istio, Dark Debt, Mage, and More"
draft = false
slug = "094"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "automation", "ansible", "Linus Torvalds", "kernel", "development", "community", "apology", "serverless", "change", "linux", "code of conduct", "microsoft", "culture", "istio"]
title = "094: Linus Apologizes, Giveaway Winners, Kubernetes, Istio, Dark Debt, Mage, and More"

+++

Shortly after [DevOps'ish 093](/093/) went out last week, Linus Torvalds rocked the Linux kernel development community to its core with his note to LKML, [Linux 4.19-rc4 released, an apology, and a maintainership note](https://www.lkml.org/lkml/2018/9/16/167). In it, Linus apologized, "to the people that my personal behavior hurt and possibly drove away from kernel development entirely." Also, a [Code of Conduct](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=8a104f8b5867c682d994ffa7a74093c54469c11f) has been adopted by the Linux kernel development community.

*In my opinion*, this is a welcome change. But, I can't help but think this is WAY too little, WAY too late. The sickening amount of toxic behavior in the open source software development world has used Linus as its scapegoat for decades. Some people are decrying the new Code of Conduct as ushering in politics that will lead to the downfall of the kernel development community. Decades of deplorable behavior towards humans has led us to this moment. I can't help but think of the Jean de La Fontaine quote, "Our destiny is frequently met in the very paths we take to avoid it."  I'll posit their desires for an environment free of politics and humanism would have been better defended by actually adhering to the principles in the now dead [Linux Code of Conflict](https://www.kernel.org/doc/html/v4.17/process/code-of-conflict.html). "Be excellent to each other" clearly wasn't enough. There is so much to unpack here and it has only been a week. More to come for sure. A quick aside, I see a lot of parallels between the kernel development community and the current US political climate.

**Congratulations** to the winners of the free copy of [**Cloud Native DevOps with Kubernetes**](https://www.safaribooksonline.com/library/view/cloud-native-devops/9781492040750/). The winners have been contacted via [Telegram](https://devopsi.sh/telegram) and will be announced publicly once their copies have been claimed. Join the DevOps'ish group on Telegram to discuss this week's latest newsletter! [https://devopsi.sh/telegram](https://devopsi.sh/telegram)

[**Remediation Strategy for Continuous Delivery of Microservices**](https://www.gocd.org/2018/09/11/cd-microservices-remediation-strategy/)  
In systems based on microservices architecture, you have multiple services getting updated frequently. How do you respond when a deployment of a service introduces instability or bugs? Sheroy Marker offers some remediation strategies [in this blog](https://www.gocd.org/2018/09/11/cd-microservices-remediation-strategy/). *SPONSORED*

[**Kelsey Hightower and Chris Gaun on serverless and Kubernetes**](https://www.oreilly.com/pub/cpc/168517)  
Enjoy this episode of the O'Reilly Podcast, featuring a conversation on serverless and Kubernetes, with Kelsey Hightower, developer advocate for Google Cloud Platform at Google (and co-author of Kubernetes: Up and Running), and Chris Gaun, Kubernetes product marketing manager at Mesosphere. *SPONSORED*

{{< sponsor-blurb >}}

## People

**The Linus Torvalds Apology**:

* [Code of Conduct: Let's revamp it.](https://github.com/torvalds/linux/commit/8a104f8b5867c682d994ffa7a74093c54469c11f) (GitHub)
* [After Years of Abusive E-mails, the Creator of Linux Steps Aside](https://www.newyorker.com/science/elements/after-years-of-abusive-e-mails-the-creator-of-linux-steps-aside) (The New Yorker)
* [New Yorker claims credit for Torvalds' apology on behaviour](https://www.itwire.com/open-source/84590-new-yorker-claims-credit-for-torvalds-apology-on-behaviour.html) (ITWire)
* [With Linux's founder stepping back, will the community change its culture?](https://www.theverge.com/2018/9/21/17883442/linux-founder-linus-torvalds-apology-code-of-conduct-change-enforcement) (The Verge)
* [Linux creator says he's taking time off, and apologizes for 'unprofessional and uncalled for' behavior](https://www.cnbc.com/2018/09/17/linux-creator-linus-torvalds-takes-time-off-apologizes-for-behavior.html) (CNBC)
* [Linus, His Apology, And Why We Should Support Him](https://www.jonobacon.com/2018/09/16/linus-his-apology-and-why-we-should-support-him/) (Jono Bacon)
* [Linux's Creator Is Sorry. But Will He Change?](https://www.wired.com/story/linuxs-creator-is-sorry-but-will-he-change/) (Wired)
* [Linux Has a Code of Conduct and Not Everyone is Happy With it](https://itsfoss.com/linux-code-of-conduct/) (It's FOSS)
* ​[Linus Torvalds takes a break from Linux](https://www.zdnet.com/article/linus-torvalds-takes-a-break-from-linux/) (ZDNet)
* [Torvalds Steps Back From Linux Leadership to Fix 'Tooling' Issues](http://www.eweek.com/enterprise-apps/torvalds-steps-back-from-linux-leadership-to-fix-tooling-issues) (eWeek)

[#WhyIDidntReport and the Tragic Banality of Rape in America](https://www.wired.com/story/whyididntreport-hashtag/): Chances are you personally know someone that has been raped.

[Tell us your automation story!](https://docs.google.com/forms/d/e/1FAIpQLSc669FN9Mvhsj9eE_e1e66EmUxSRdcJiFSqWnM9NWHLT0beVg/viewform)

[Growth in Fear](https://emilyfreeman.io/blog/growth-in-fear): New Microsoft Azure CloudOps Advocate Emily Freeman opens up.

[Engineering Productivity](https://medium.com/@skamille/engineering-productivity-b1ea12db02e4): "a great engineering manager is capable of creating a highly productive engineering team"

[The 'Opsec Fail' That Helped Unmask a North Korean State Hacker](https://www.darkreading.com/threat-intelligence/the-opsec-fail-that-helped-unmask-a-north-korean-state-hacker-/d/d-id/1332870): How Park Jin Hyok - charged by the US government for alleged computer crimes for the Sony, Bank of Bangladesh, WannaCry cyberattacks - inadvertently blew his cover via email accounts.

[For Hackers, Anonymity Was Once Critical. That's Changing.](https://www.nytimes.com/2018/09/22/technology/defcon-hackers-privacy-anonymity.html): At Defcon, one of the world's largest hacking conferences, new pressures are reshaping the community's attitudes toward privacy and anonymity.

[DevOps: Take people with you, but allow them to leave if they don't want to come along on the journey](https://www.computing.co.uk/ctg/news/3063090/devops-take-people-with-you-but-allow-them-to-leave-if-they-dont-want-to-come-along-on-the-journey): A panel of experts at Computing's recent DevOps North Live event discusses the cultural issues in implementing a DevOps culture

[OK, Google](https://medium.com/@nathenharvey/ok-google-95fa8617293f): Nathen goes to Google

## Process

[My Notes for Certified Kubernetes Application Developer — Part 1, Core Concepts](https://medium.com/@elliot_f/my-notes-for-certified-kubernetes-application-developer-part-1-core-concepts-d1bab7bc2446): "This won't be a comprehensive view of Kubernetes, but it should give anyone reading it a solid-enough grounding to base their own studies off of."

[Increasing Security of Istio Deployments by Removing the Need for Privileged Containers](https://blog.openshift.com/increasing-security-of-istio-deployments-by-removing-the-need-for-privileged-containers/): "Pods that belong to the Istio mesh require elevated privileges in order to function properly. In this article we will present the istio-pod-network-controller, a solution to mitigate this issue."

[How to Fix ‘Dark Debt' in Your IT Organization's Culture](https://devops.com/how-to-fix-dark-debt-in-your-it-organizations-culture/): This is a great article about culture and debt and its implication.

[Buildah](https://buildah.io/) now has a proper website.

[Microsoft reveals train of mistakes that killed Azure in the South Central US 'incident'](https://www.theregister.co.uk/2018/09/17/azure_outage_report/): Thunderbolt and lightning, Azure outage frightening

[A New Chapter For Mesosphere](https://mesosphere.com/blog/a-new-chapter-for-mesosphere/): "I believe that it makes sense to transition Mesosphere from a founder-led company to one headed by someone who has experience leading companies into public markets."

[GitLab's 2019 product vision for DevOps Create](https://about.gitlab.com/2018/09/21/create-vision/): Take an early look at where collaboration, merge requests, and the Web IDE are heading in 2019.

[Sourcegraph Master Plan](https://about.sourcegraph.com/plan/): What we're building, and why it matters.

[5 ways DevSecOps changes security](https://opensource.com/article/18/9/devsecops-changes-security): Security must evolve to keep up with the way today's apps are written and deployed.

[Is cloud native starting to kill Hadoop? This CTO says yes](https://siliconangle.com/2018/09/20/cloud-native-starting-kill-hadoop-cto-says-yes-cubenyc/): "Yaron Haviv, founder and chief technology officer of Iguazio Systems Ltd, believes that Hadoop may be outmaneuvered in the future with other solutions."

[CRI-O is now our default container runtime interface](https://kubic.opensuse.org/blog/2018-09-17-crio-default/): "We're really excited to announce that as of today, we now officially supports the CRI-O Container Runtime Interface as our default way of interfacing with containers on your Kubic systems!"

## Tools

[Kube YAML validations](https://kubeyaml.com/): Enter your Kubernetes yaml and see which versions it is valid for.

[Kubernetes By Example](http://kubernetesbyexample.com/): This is a hands-on introduction to Kubernetes.

[What is Istio?](https://opensource.com/article/18/9/what-istio): Learn how a service mesh can help to manage your microservice deployments.

[Ansible 101: Part 1: In the beginning there was YAML](https://www.redhat.com/en/blog/ansible-101-part-1-beginning-there-was-yaml): "In this series the fruit we will be striving for is automation with Ansible."

[Idempotently adding an SSH key for a host to known_hosts file with bash](https://www.jeffgeerling.com/blog/2018/idempotently-adding-ssh-key-host-knownhosts-file-bash): This breaks when GitHub changes their keys (which has happened before).

[Azure DevOps - Why It's A Big Deal For Microsoft And The Community](https://www.forbes.com/sites/janakirammsv/2018/09/16/azure-devops-why-its-a-big-deal-for-microsoft-and-the-community/#4200c6a56780)

[Azure DevOps: Dockerfiles with multiline environment variables, private repos, and ssh keys](https://jessicadeen.com/tech/azure-devops-dockerfiles-with-multiline-environment-variables-private-repos-and-ssh-keys/)

[New Linux distro specifically designed for Windows comes to the Microsoft Store](https://mspoweruser.com/new-linux-distro-specifically-designed-for-windows-comes-to-the-microsoft-store/): "WLinux is based on Debian, and the developer, [Whitewater Foundry](https://whitewaterfoundry.com/), claims their custom distro will also allow faster patching of security and compatibility issues that appear from time to time between upstream distros and WSL."

[Getting started with Tmux](https://linuxize.com/post/getting-started-with-tmux/): It's part concept and part key bindings.

[Containers as I didn't know them](https://itnext.io/containers-as-i-didnt-know-them-67cd4eaf3739): "Today let's talk about how containers could make your life better even if you've sworn to never deploy your precious cat-ranking app to anything but bare metal."

[A neglected serverless data store: Cloud Directory](https://cloudonaut.io/a-neglected-serverless-data-store-cloud-directory/): "I am convinced that Cloud Directory is a neglected Serverless data store that deserves much more attention."

[Introducing new Cloud Source Repositories](https://cloud.google.com/blog/products/application-development/introducing-new-cloud-source-repositories): "Newly revamped Cloud Source Repositories in beta availability"

[kubernauts/tk8](https://github.com/kubernauts/tk8): CLI to deploy kubernetes using kubespray and also install additional addons

[Write a Kubernetes controller (operator) with operator-sdk](https://www.tailored.cloud/kubernetes/write-a-kubernetes-controller-operator-sdk/)

[Expanding DNSSEC Adoption](https://blog.cloudflare.com/automatically-provision-and-maintain-dnssec/): "This week we are announcing our full support for CDS and CDNSKEY from RFC 8078."

[Mage - make/rake for Go](https://npf.io/2018/09/mage/): Mage is conceptually just like Make, except you write Go instead of Bash.

[The world's biggest curl installations](https://daniel.haxx.se/blog/2018/09/17/the-worlds-biggest-curl-installations/): "curl is quite literally used everywhere. It is used by a huge number of applications and devices."

[Does your website support TLS 1.3?](https://tls.bejarano.io/): As of August 2018, TLS 1.3 is an IETF Internet Standard, are you ready?

[Ubuntu does Kubernetes](https://blog.ubuntu.com/2018/09/20/ubuntu-kubernetes): "The Canonical Distribution of Kubernetes (CDK) is pure upstream Kubernetes tested across the widest range of clouds — from public clouds to private data centres, from bare metal to virtualised infrastructure."

[Contour v0.6.0](https://github.com/heptio/contour/releases/tag/v0.6.0): A new version of Contour is available.

[Writing More Compact Bash Code](https://www.linuxjournal.com/content/writing-more-compact-bash-code): Some interesting ways to write cleaner Bash.

[Microsoft Highlights Kubernetes Support on Windows Server 2019](https://redmondmag.com/articles/2018/09/21/kubernetes-support-windows-server-2019.aspx): "Microsoft's No. 1 networking feature for the forthcoming Windows Server 2019 product is Kubernetes support, according to a Wednesday announcement."

## DevOps'ish Tweet of the Week

Two Tweets of the Week this week because Sage covers the Linus Torvalds news from her POV so well and Abby is 100% right (there's more to life than just tech and it's all connected).

{{< tweet 1042769391279063040 >}}

"keep it to technical content/stop complaining/be professional/these things don't even happen/not all men/unfollowing bc feminism" 

Guess what? These issues are important: they affect our whole community. We're going to keep talking about them.

We're more than just our jobs.

— Abby Fuller (@abbyfuller) [September 17, 2018](https://twitter.com/abbyfuller/status/1041691120332431361?ref_src=twsrc%5Etfw)
