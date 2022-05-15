+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-05-15T07:00:00Z
description = ["KubeCon EU is here, SUSE discriminates, Windows vulns, scammer footgun, git, GitOps and so much more"]
draft = false
slug = "267"
tags = ["GitOps", "AWS", "Amazon", "open source", "KubeCon", "Kubernetes", "cloud native", "Storage Capacity", "cloud", "DevOps", "EKS", "Honeycomb", "OpenSSL", "git", "squash", "iPod", "SUSE", "Google", "Apple", "policy", "Windows", "attack", "security", "malware", "resolvers", "HashiCorp", "HashiCorp Vault", "drift detection", "Flux", "Argo", "Observability", "DevOpsDays"]
title = "DevOps'ish 267: "
+++

This week was the run up to KubeCon. The mad dash turned into peace and quiet by Friday. I feel really bad about Spain not approving quite a few visas for folks I wanted to meet. I had to help coordinate a few last minute switches from physical to virtual talks. I took part in a few [AWS Container Days sessions](https://www.twitch.tv/videos/1481899649) and an impromptu, during the stream invite to [Anaïs Urlichs and Matty Straton's live stream all about attending KubeCon](https://www.youtube.com/watch?v=fZGNdpVICQU). I'll have those up on [my web site](https://chrisshort.net/) for preservation soon enough.

It was a good week overall (at least the second half). Timing for the newsletter is a little wonky as I'm traveling to KubeCon in Valencia, Spain. I'm writing this week's newsletter from an Air France Lounge at Charles de Gaulle Airport (CDG, eek, I know). If you're attending KubeCon in person or virtually and need something, want to say, "Hi." Please stop me if you see me. If I'm not in a hurry I'll happily chat. If I am busy or on my way to something, you'll be able to tell. Have a great week everyone!

## DevOps'ish is brought to you by...

DevOps'ish is brought to you by your friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).

***"Stop Letting Complexity Slow You Down"***

[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easier to understand and troubleshoot complex relationships within your distributed services. *Solve problems faster*. *Ship reliable and performant features*. *SPONSORED*

## Events

[**AWS Containers Days**](https://awscontainerdayseurope.splashthat.com/)  

MAY 10TH-13TH, AND 17TH  
8:00AM-10:00AM PT | 17:00-19:00 CEST

Join us (me on Thursday) for AWS Containers Days @ KubeCon + CloudNativeCon Europe 2022! In the days leading up to Kubecon + CloudNativeCon we'll be spending the week talking about how you can deploy, manage, and scale containerized applications using Kubernetes on AWS. These sessions, led by our AWS Kubernetes team and guest speakers, will contain technical deep dives, product demos, and best practices.

In the closing keynote on May 17th, Nate Taber, Principal Product Manager, AWS will share the Amazon EKS Vision and Roadmap and throughout the session you will hear directly from our customers.

[**Open Source After Dark EU**](https://opensourceafterdarkeu.splashthat.com/)  

May 18, 2022 | 9:00PM - 11:59PM

Enjoy food, drinks, techno-themed entertainment, and so much more. This is one event you won't want to miss.

[**GitOpsCon Europe 2022**](https://events.linuxfoundation.org/gitopscon-europe/)

MAY 17, 2022

Designed to foster collaboration, discussion, and knowledge sharing on GitOps. This event is aimed at audiences that are new to GitOps as well as those currently using GitOps within their organization. Get connected with others that are passionate about GitOps. Learn from practitioners about pitfalls to avoid, hurdles to jump, and how to adopt GitOps in your cloud native environment. *Schedule release this week*

[**DevOpsDays Ukraine: DevOps in Crisis**](https://devopsdays.com.ua/)

May 17-18th, 2022, Virtual

DevOpsDays Ukraine is a part of the global DevOpsDays family.  
This May we are running a virtual charity event to discuss DevOps during crisis, incident, and business continuity management and collect donations to support Ukrainians.

[**ArgoCon**](https://events.linuxfoundation.org/argocon/)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

## People

[The time SUSE, the German Linux company, banned mentioning Jewish holidays.](https://lunduke.substack.com/p/the-time-suse-the-german-linux-company)  
Bryan Lunduke, formerly SUSE  
This is absolutely abhorrent behavior ESPECIALLY for a German company. It's a really bad look. This is clearly discriminatory behavior. You can't tell someone their not allowed to be the religion of their choosing. I hope SUSE loses customers, gets fined, and those responsible are dealt with swiftly.

[Why I left Google: work-life balance](https://www.scottkennedy.us/balance.html)  
Scott Kennedy, formerly Google  
"Getting things done at Google can be hard. Projects need multi-team cooperation to succeed, so you have to do a lot of work up front to get everybody pulling together. But it makes projects fragile. When any of those teams changes direction, or even just over-stated their original commitment, the project slows down or fails."

[Prominent Apple staffers write letters to management, resign over office return](https://arstechnica.com/gadgets/2022/05/remote-work-conflict-continues-at-apple-with-at-least-one-prominent-staff-departure/)  
Samuel Axon, Ars Technica  
Apple's return to work policy is insane. There I said it. There is no reason folks need to come into an office unless they want/need to for legit reasons. Not "serendipitous moments of collaboration and creation." Hell, I can get that on a live stream and I know I can do that in Slack too. [Zoë Schiffer tweeted](https://twitter.com/zoeschiffer/status/1523017143939309568) that, "Ian Goodfellow, Apple’s director of machine learning, is leaving the company due to its return to work policy. In a note to staff, he said 'I believe strongly that more flexibility would have been the best policy for my team.' He was likely the company’s most cited ML expert." As the article points out, it's VERY rare that Apple employees chastise their employer so publicly.

[Please, stop disabling zoom](https://www.matuzo.at/blog/2022/please-stop-disabling-zoom/)  
Manuel Matuzović  
"I know that you’re not supposed to tell people what to do, but in this particular case I’m really tempted because recently I’ve noticed that a lot of websites are preventing users on mobile to zoom." Don't do this. I've gotten to the point where zoom is a very viable function and I don't care if your web site looks ugly when I do it.

[US college set to permanently close after 157 years, following ransomware attack](https://www.bitdefender.com/blog/hotforsecurity/us-college-set-to-permanently-close-after-157-years-following-ransomware-attack/)  
This is a really sad story. 157 years of existence ended by the pandemic and a ransomware attack.

## Process

[What to Patch Now: Actively Exploited Windows Zero-Day Threatens Domain Controllers](https://www.darkreading.com/application-security/what-to-patch-now-actively-exploited-zero-day-threatens-domain-controllers)  
Tara Seals, Dark Reading  
"Microsoft squashed 74 security vulnerabilities with its May 2022 Patch Tuesday update, including an important-rated zero-day bug that's being actively exploited in the wild and several that are likely widely present across enterprises."

[Hackers are now hiding malware in Windows Event Logs](https://www.bleepingcomputer.com/news/security/hackers-are-now-hiding-malware-in-windows-event-logs/)  
Ionut Ilascu, Bleeping Computer  
"One of the most interesting parts of the attack is injecting shellcode payloads into Windows event logs for the Key Management Services (KMS), an action completed by a custom malware dropper."

[Scammer Infects His Own Machine With Spyware, Reveals True Identity](https://www.darkreading.com/attacks-breaches/scammer-infects-own-machine-reveals-true-identity)  
Jai Vijayan, Dark Reading  
"An operational slip-up led security researchers to an attacker associated with Nigerian letter scams and malware distribution, after he infected himself with Agent Tesla." This is totally worth the read for the self-pwnage alone.

[Spectre and Meltdown Attacks Against OpenSSL](https://www.openssl.org/blog/blog/2022/05/13/spectre-meltdown/)  
OpenSSL Technical Committee  
For numerous reasons, OpenSSL isn't going to be patching for Spectre and Meltdown. It makes way more sense to  handle these mitigations in firmware or the operating system itself. OpenSSL would be buried in work otherwise and it wasn't that long ago that they didn't have enough people to prevent [Heartbleed](https://heartbleed.com/).

[Open DNS resolvers, from bad to worse](https://blog.apnic.net/2022/05/13/open-dns-resolvers-from-bad-to-worse/)  
Ramin Yazdani, APNIC  
"Researchers and operators have made efforts to reduce the number of (unnecessary) open resolvers. However, looking at the dimensions of recent attacks, the residual pool of open resolvers is noticeably more than large enough for attackers."

[Musk says $44 billion Twitter deal on hold over fake account data](https://www.reuters.com/technology/musk-says-44-billion-twitter-deal-hold-2022-05-13/)  
Sheila Dang and Greg Roumeliotis, Reuters  
Good! Maybe this will all go away.

## Tools

[Storage Capacity Tracking reaches GA in Kubernetes 1.24](https://kubernetes.io/blog/2022/05/06/storage-capacity-ga/)  
Patrick Ohly, Intel  
"[S]torage capacity tracking allows a CSI driver to publish information about remaining capacity. The kube-scheduler then uses that information to pick suitable nodes for a Pod when that Pod has volumes that still need to be provisioned... Because CSI drivers publish storage capacity information that gets used at a later time when it might not be up-to-date anymore, it can still happen that a node is picked that doesn't work out after all. Volume provisioning recovers from that by informing the scheduler that it needs to try again with a different node."

[Level up Security Management with HashiCorp Vault and Flux](https://www.weave.works/blog/hashicorp-vault-flux-secret-management)  
HashiCorp  
"HashiCorp Vault is now a native Flux extension enabling secret management for all environments including on premise and hybrid. Secure GitOps automated pipelines with rotating encryption keys in HashiCorp Vault, re-encryption of secrets and audit any changes in git."

[You aren't Doing GitOps without Drift Detection](https://www.weave.works/blog/you-aren-t-doing-gitops-without-drift-detection)  
WeaveWorks  
"As cloud-native practices have begun to unify all parts of the technology stack, drift should not be prevented at every level - application, networking, data, and infrastructure. The older generation of DevOps tooling is unable to deliver such expansive coverage. This is where a modern approach like GitOps is uniquely positioned to be the answer to fighting drift in cloud-native systems that are powered by ​​Kubernetes."

[Squash and Rebase](https://levelup.gitconnected.com/squash-and-rebase-my-method-for-merging-git-branches-3b43c52675b6)  
Dalya Gartzman  
Squashing commits is a painful task. It's not as simple a task with git as it should be. It's painful and frequently done so often the Kubernetes community actually has a command to do this for you.

[Prow and Tide for Kubernetes Contributors](https://chrisshort.net/prow-and-tide-for-kubernetes-contributors/)  
Chris Short, AWS  
"What actually prompted this article is the awesomely amazing folks on the Contributor Comms team saying, “I need to squash my commits and push that.” Which immediately made me remember the wonder of the Tide label: `tide/merge-method-squash`"

[Get good at Git](https://kubesimplify.com/get-good-at-git)  
Bushra Nazish, Kubesimplify  
"Could you be using Git more efficiently? The answer is, probably, a YES. In this blog, we will look at a bunch of different tips and tricks to make you more productive with Git 📝"

[Learn Kubernetes with this Introductory Course in One Hour (All Core Components and Hands On!)](https://www.youtube.com/watch?v=n4zxKk2an3U)  
James Spurin  
This is a very thorough video and I hope James can make more.

[Monitoring Amazon EKS Anywhere using Amazon Managed Service for Prometheus and Amazon Managed Grafana](https://aws.amazon.com/blogs/containers/monitoring-amazon-eks-anywhere-using-amazon-managed-service-for-prometheus-and-amazon-managed-grafana/)  
Elamaran Shanmugam, Gokul Chandra, and ponrama, AWS  
"[A] step-by-step guide on how to monitor your containerized workload running on Amazon EKS Anywhere by publishing metrics to [Amazon Managed Service for Prometheus](https://aws.amazon.com/prometheus/) and using [Amazon Managed Grafana](https://aws.amazon.com/grafana/) to visualize." We probably should make this way easier. Perhaps we will with [EKS Curated Packages](https://www.twitch.tv/videos/1481899649?t=00h31m39s). What? A teaser in the newsletter???

[Observability Engineering [Book]](https://www.oreilly.com/library/view/observability-engineering/9781492076438/)  
Charity Majors, Liz Fong-Jones, George Miranda, Honeycomb  
"Authors Charity Majors, Liz Fong-Jones, and George Miranda from Honeycomb explain what constitutes good observability, show you how to improve upon what you’re doing today, and provide practical dos and don'ts for migrating from legacy tooling, such as metrics, monitoring, and log management. You’ll also learn the impact observability has on organizational culture (and vice versa)."

[The iPod is dead](https://techcrunch.com/2022/05/10/the-ipod-is-dead/)  
Brian Heater, TechCrunch  
It's a little sad when an iconic piece of technology goes the way of the Dodo. But, why am I mentioning this here? Because it was recommended to me by a friend to nabbed a high-capacity iPod Touch for a work "phone." The iPod showed up literally as the discontinuation announcement dropped. The iPod has been returned. If it's EOL'd updates are the next thing to go. In talking to Apple Store folks, they suggest the iPhone SE or the iPad. Sigh... Nevermind that idea. I'll just keep one phone and put it under employer management.

[NVIDIA Releases Open-Source GPU Kernel Modules](https://developer.nvidia.com/blog/nvidia-releases-open-source-gpu-kernel-modules/)  
Ram Cherukuri, Shirish Baskaran, Andy Ritger, Fred Oh and Dwayne Swoboda, NVIDIA  
Rejoice fellow Linux users, soon we'll have the same ability to play REALLY pretty video games.

## DevOps'ish Social Media of the Week

Tweets, toots, reddit posts, etc. will now fill this section.  I want to open it to all social media platforms. If you see something, send it my way, please.

[![As an industry we need more self-reflection and less copy-pasting of other people's engineering culture. (Kelsey Hightower @kelseyhightower on Twitter)](https://shortcdn.com/file/devopsish/267-devopsish-tweet-of-the-week.webp)](https://twitter.com/kelseyhightower/status/1525112570595536896)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and off you go.
