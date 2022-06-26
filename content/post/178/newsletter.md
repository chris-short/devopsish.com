+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-08-10T07:00:00Z
description = "DevOps'ish 178"
draft = false
slug = "178"
tags = ["Accurics", "cloud", "DevOps", "cloud native", "AWS", "Red Hat", "AWS bill", "Cloudflare", "development", "GitOps", "CNCF", "Kubernetes", "Rust", "Go", "helpernode", "ZFS", "Windows", "open source", "process", "distributed systems", "data storage", "cluster", "Nginx", "Envoy", "Microsoft", "infrastructure", "community", "safety", "nodes", "loosely coupled", "Christian Hernandez", "crun", "vim", "live stream", "VScode", "Linux", "OKD", "WSL", "kube", "Lili Cosic", "Corey Quinn", "DevSecOps"]
title = "DevOps'ish 178: Return of the G"

+++

Welcome!

DevOps'ish is back.

**What did the hiatus look like? Why did it need to happen at all?**

Like fixing an airplane while it's in-flight, It's hard assessing a problem while you're in the middle of creating it. COVID-19 is just the sort of thing that the world turned upside down enough that I needed to take a break to reassess how to do the newsletter, in general. Meanwhile, sponsorships wholly dried up (for five weeks). The incentive I created for myself to write the newsletter when things were hard was gone two weeks after my family started sheltering. The world was in chaos, my processes weren't aligned to the new state of things, and incentives were gone. When you couple that with [a massive project that I was undertaking at work](https://chrisshort.net/live-streaming-on-openshift.tv-and-some-lessons-learned/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_178) (and spending all my free time researching), the newsletter had to "fall off the plate" as it were. My medical world got turned upside down, too, because of COVID-19. I was rightfully put on hold for routine treatment so the medical infrastructure could adjust also. If my doctors take a break from my treatments, I don't stand a chance at functioning at 100%.

**Why is DevOps'ish back now?**

You can all thank [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_178) for the return of DevOps'ish. They are enabling DevOps'ish to run for as long as our relationship lasts! Huge shoutout to the [leadership team at Accurics](https://www.accurics.com/team/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_178) for making this possible.

I've got some improved ways and expectations around news reading, too (thanks to some enhancements from [Inoreader](https://www.inoreader.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_178)). No longer will my goal be, read all the news every day. That's unsustainable, as I learned. Meanwhile, the cloud native ecosystem had exploded since 2016 when the newsletter started. I still aim to deliver a piece of work that I'm proud of every week. I hope you enjoy this week's issue as much as I enjoy bringing back DevOps'ish.

**Is DevOps'ish moving to Mondays?**

I don't know. Maybe. I think my days of being able to spend Saturday night producing the entire newsletter might be coming to an end as I need to slice my time more and more between work projects, meetings (which there are more of now), real-life (which is harder now), and side projects (which I'll always have). I'd rather keep the email on Sundays, but this week's issue is coming out on Monday because I ended up having to change mail providers in the 11th hour.

## People

[Weekly Distance DevOps Lunch and Learn](https://rackn.com/distance-devops/): This is a fun thing to come out of the crisis. I'm going to be to be joining as a subject of discussion this week, "Q&A with Chris Short about his [no good, very bad AWS bill](https://chrisshort.net/the-aws-bill-heard-around-the-world/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_178)."

[The community hat rules the company hat in open source](https://www.infoworld.com/article/3569373/the-community-hat-rules-the-company-hat-in-open-source.html): "For kube-state-metrics maintainer and Red Hat employee Lili Cosic, what Red Hat wants from the project is beside the point" OMG I know her!!!

[The AWS bill heard around the world](https://chrisshort.net/the-aws-bill-heard-around-the-world/): I cut my fingers on some sharp edges of the cloud. Did you know that Cloudflare might not respect multipart GETs as full file GETs? That's gonna run up a bill real quick. Thank you to AWS for bailing me out of an AWS bill that was more than my mortgage. Thank you, [Corey Quinn](https://www.ref.lastweekinaws.com/7h1z3x), for helping me navigate the process (subscribe to Corey's newsletter). I'm still working on a solution but, it's going to be replacing Cloudflare for sure at this point. I no longer trust Cloudflare.

[What makes great DevOps teams tick](https://enterprisersproject.com/article/2020/7/devops-great-teams): "The principles of DevOps go beyond just improving software development processes. They also help foster stronger, more productive teams"

## Process

[DevSecOps: Risks and Best Practices](https://www.accurics.com/blog/devops/devsecops-risks-and-best-practices/): "It is now more important than ever to understand cloud infrastructure configuration practices that are creating exposures."

[The Five Ideals of DevOps](https://itrevolution.com/five-ideals-of-devops/): "In [The Phoenix Project](https://amzn.to/33Gme2t), we introduced the Three Ways underpinning DevOps. In my follow-up book, [The Unicorn Project](https://amzn.to/3a8OwUA), I revisit Parts Unlimited and describe my learnings through the Five Ideals.

* The First Ideal: Locality and Simplicity
* The Second Ideal: Focus, Flow, and Joy
* The Third Ideal: Improvement of Daily Work
* The Fourth Ideal: Psychological Safety
* The Fifth Ideal: Customer Focus"

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/): "Distributed systems provide a particular challenge to program. They often require us to have multiple copies of data, which need to keep synchronized. Yet we cannot rely on processing nodes working reliably, and network delays can easily lead to inconsistencies. Despite this, many organizations rely on a range of core distributed software handling data storage, messaging, system management, and compute capability. These systems face common problems which they solve with similar solutions. This article recognizes and develops these solutions as patterns, with which we can build up an understanding of how to better understand, communicate and teach distributed system design."

[How to Champion GitOps in Your Organization](https://www.weave.works/blog/how-to-champion-gitops-in-your-organization): "By now you’ve heard all about GitOps and are convinced that GitOps is the most efficient way for development teams to go faster without them having to become Kubernetes gurus. However, making the switch to a cloud native technical solution may be the simplest part in your Kubernetes journey. Getting buy-in from your peers and championing GitOps throughout your organization could very well be the most challenging aspect of the cloud native transition."

[Open Sourcing the etcd Security Audit](https://www.cncf.io/blog/2020/08/05/etcd-security-audit/): The entire report is available [here](https://github.com/etcd-io/etcd/blob/master/security/SECURITY_AUDIT.pdf).

[Cloud Native Backups, Disaster Recovery and Migrations on Kubernetes](https://thenewstack.io/cloud-native-backups-disaster-recovery-and-migrations-on-kubernetes/): "Loosely coupled architectures enable loosely coupled teams. The benefit being that loosely-coupled teams are unblocked; they’re able to iterate as and when they can, free from the scourge of meetings, long release cycles, change control boards and more."

[Backblaze takes aim at ‘costly and complex’ AWS cloud storage](https://www.computerweekly.com/news/252486751/Backblaze-takes-aim-at-costly-and-complex-AWS-cloud-storage): "Backblaze offers free transfer to its S3-based cloud storage – which it claims costs a fraction of AWS et al – as long as it’s more than 50TB and you commit to at least 12 months." After my S3 and Cloudflare debacle, this is interesting. Change is desperately needed in how clouds lock our data up behind excessively expensive egress price rates.

## Tools

[RedMonk Top 20 Languages Over Time: June 2020](https://redmonk.com/rstephens/2020/07/27/redmonk-top-20-languages-over-time-june-2020/): Python has overtaken Java. CSS is #7 which shows you how hard CSS is. TypeScript jumped C! R jumped Go as Go is now tied with Shell likely due to Go's continued tumult. Rust dropped to #20 (sorry, crustaceans). I predict Rust will outrank Go in three years. PHP will also be a strong contender despite interns I've worked with this year having never heard of it. Is PHP the COBOL of the web?

[Christian Hernandez's very helpful helpernode](https://www.youtube.com/watch?v=wZYx4_xBSUQ): "In this live stream, Christian Hernandez and Chris Short will walk through what [helpernode](https://github.com/RedHatOfficial/ocp4-helpernode) is, how to get the [helpernode](https://github.com/RedHatOfficial/ocp4-helpernode) up and running, and getting an OpenShift 4 cluster stood up with [helpernode](https://github.com/RedHatOfficial/ocp4-helpernode)'s assistance."

[Awesome Command-Line tools to boost your productivity](https://dev.to/tasinishmam/awesome-command-line-tools-to-boost-your-productivity-22n8): "The more you can speed up your terminal workflow, the more efficiently you can get work done."

[Why Should You Learn Vim in 2020](https://pragmaticpineapple.com/why-should-you-learn-vim-in-2020/): Surprisingly, the article doesn't start with, "Because it's not emacs." But, it explains why everyone isn't running VScode (even I use [Vim emulation](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) in VScode).

[An introduction to crun, a fast and low-memory footprint container runtime](https://www.redhat.com/sysadmin/introduction-crun): "Check out crun, an OCI-compliant alternative to runc for Linux container runtime."

[Go vs Rust: Writing a CLI tool](https://cuchi.me/posts/go-vs-rust): "They were both very great tools for the job. But of course, they have different priorities. On one side, we have an option which tries to keep software development simple, maintainable, and accessible. On the other hand, we have a language focused on soundness, safety, and performance." If Rust becomes a little more user friendly (by making it an intentional goal), I'd be able to pick it up I bet, shortly thereafter. But, garbage collection is tough to pass up.

[How we migrated Dropbox from Nginx to Envoy](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy): "In this blogpost we’ll talk about the old Nginx-based traffic infrastructure, its pain points, and the benefits we gained by migrating to [Envoy](https://www.envoyproxy.io/). We’ll compare Nginx to Envoy across many software engineering and operational dimensions. We’ll also briefly touch on the migration process, its current state, and some of the problems encountered on the way."

[The easiest and fastest way to deploy an OKD 4.5 cluster in a Libvirt/KVM host](https://www.anstack.com/blog/2020/07/31/the-fastest-and-simplest-way-to-deploy-okd-openshift-4-5.html): "Long story short… We will deploy an OKD 4.5 cluster in ~30 minutes (3 controllers, 1 to 10 workers, 1 service, and 1 bootstrap node) using one single command in around 30 minutes using a tool called KubeInit." I'll be trying this out in the near future.

[An Introduction to ZFS A Place to Start](https://www.servethehome.com/an-introduction-to-zfs-a-place-to-start/): "ZFS has become increasingly popular in recent years. ZFS on Linux (ZoL) has pushed the envelope and exposed many newcomers to the ZFS fold. iXsystems has adopted the newer codebase, now called OpenZFS, into its codebase for TrueNAS CORE. The purpose of this article is to help those of you who have heard about ZFS but have not yet had the opportunity to research it."

[University of Cambridge to decommission its homegrown email service Hermes in favour of Microsoft Exchange Online](https://www.theregister.com/2020/08/04/cambridge_uni_decommissioning_hermes_email/): Email is hard. Fight me.

[Windows 10: HOSTS file blocking telemetry is now flagged as a risk](https://www.bleepingcomputer.com/news/microsoft/windows-10-hosts-file-blocking-telemetry-is-now-flagged-as-a-risk/): Running a Windows 10 rig these days for various reasons, this is quite the anti-user friendly behavior I'm beginning to expect from Microsoft.

[Remote SSH Connections to WSL2](https://www.brianketelsen.com/blog/ssh-to-wsl2/): "In this article I share my learnings on remotely accessing your Windows 10 computer. My motivation was to determine efficient ways to access both the Windows environment, and the WSL2 development environment from another computer."

[bloomberg/goldpinger](https://github.com/bloomberg/goldpinger): "Debugging tool for Kubernetes which tests and displays connectivity between nodes in the cluster."

## DevOps'ish Tweet of the Week

{{< tweet 1290330630576840710 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/178/notes/) to see what didn't make it to the newsletter.
