+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2019"]
date = 2019-12-23T07:00:00Z
description = "Kubernetes with extra sprinkles, skilling up in DevOps, Google Cloud’s Y2K(23), privileged containers on Santa’s naughty list, and more"
draft = false
slug = "159"
tags = ["Kubernetes", "DevOps", "cloud", "cloud native", "developers", "Google", "Google Cloud", "GCP 2023", "open source", "community", "swift", "Percona", "Kelsey Hightower", "Emily Freeman", "AWS", "Raspberry Pi", "JEDI", "RBAC", "MySQL", "PodCTL", "DevOps for Dummies", "Ansible", "Y2K", "Docker"]
title = "159: Kubernetes with extra sprinkles, skilling up in DevOps, Google Cloud’s Y2K(23), privileged containers on Santa’s naughty list, and more"

+++

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

[Building Compassion](https://www.youtube.com/watch?v=X6qOweQtqTg) — I cried really hard. It would mean the world to me if you watched Julia Ferraioli talk about what she lives with every second of every day. I have peripheral nerve damage. I cannot even fathom what Julia is dealing with (and is successful in spite of it).

[5 interview questions every Kubernetes job candidate should know](https://opensource.com/article/19/12/kubernetes-interview-questions) — "If you're interviewing people for Kubernetes-related roles, here's what to ask and why it matters."

[DevOps for Dummies (PodCTL)](https://podcasts.apple.com/by/podcast/devops-for-dummies/id1270983443?i=1000460425906) — I talk with Emily Freeman, author of DevOps for Dummies, about the biggest challenges faced in cloud adoption and DevOps culture changes.

[How to actually get good at basic DevOps if i'm not already hired (/r/devops)](https://www.reddit.com/r/devops/comments/e9nl05/how_to_actually_get_good_at_basic_devops_if_im/) — The general advice is to get some Raspberry Pis and start hacking on them. This is exactly how I learned Ansible in an evening. I've also taught myself a lot about Kubernetes and containers by using Kubernetes on Raspberry Pis. It's good to know I'm not alone in this thinking. If there's not enough budget for Raspberry Pis, you could always use KVM or Vagrant.

[Ann Arbor & Detroit Rated Top U.S. Tech & Startup Hubs To Watch](https://cronicle.press/2019/12/13/ann-arbor-detroit-rated-top-u-s-tech-startup-hubs-to-watch/) — A lot of brilliant people live and work here in Michigan. Energy prices are fairly low too. Lots of open space for data centers too. It feels like half the Kubernetes community in the US lives here. It makes a lot of sense.

[India shuts down internet once again, this time in Assam and Meghalaya](https://techcrunch.com/2019/12/13/internet-shutdown-india-assam-meghalaya/) — I hate hearing about internet shutdowns.

[The top 15 emerging jobs of 2020, according to LinkedIn](https://qz.com/work/1764751/the-top-15-emerging-jobs-of-2020-according-to-linkedin/) — Cloud engineer, SRE, and JavaScript devs all make the list among some other notables.

## Process

[Google reportedly wants to be top-two player in cloud by 2023](https://www.cnbc.com/2019/12/17/google-reportedly-wants-to-be-top-two-player-in-cloud-by-2023.html) — It should come as a surprise to absolutely no one that Google has high goals for new projects they launch. They also set goals and timelines like any other company. However, the fact Google is known for killing products people actually use (and some employees think it's going to happen) makes this one all too real feeling. Not a good look for Google.

[Google denies report it considered quitting cloud computing business](https://siliconangle.com/2019/12/17/google-denies-report-considered-quitting-cloud-computing-business/) — Of course, Google didn't like being called a spade. "Google told SiliconANGLE in an emailed statement that The Information’s report is 'simply not accurate' and linked to several blog posts detailing its investments in cloud-related infrastructure and sales teams."

[Google Cloud is (Probably) Here to Stay](https://www.lastweekinaws.com/blog/google-cloud-is-probably-here-to-stay/) — I'm a GCP customer so I hope they stay around but, I can use other clouds, I don't have to use GCP. Some folks' whole businesses are on GCP. To pull the plug on that overnight would be some pretty horrific press. Corey Quinn thinks Google is here for the long haul.

[Nginx's office is being searched due to Rambler Group's lawsuit. The complaintant press service confirmed the suit](https://habr.com/en/post/479968/) — Quite the shake to the nginx world. Several folks, myself included, received an e-mail from F5 explaining the situation too early this week. But, it seems like a troll copyright claim taken too far. "Nginx CEO believes the reason for the criminal case and searches was the sale of the project to F5 company for $670 million."

[What do Nginx, Twitch... and the English Premier League have in common? Russians. It's always the Russians](https://www.theregister.co.uk/2019/12/17/twitch_russia_lawsuit/) — It would appear Rambler Group has been putting its attorneys to use to work this week. This is weird.

[The Architecture of a Large-Scale Web Search Engine, circa 2019](https://0x65.dev/blog/2019-12-14/the-architecture-of-a-large-scale-web-search-engine-circa-2019.html) — [Cliqz] Journey to Microservices, Kubernetes and beyond.

[December 12th, 2019 - Server / Workgroup Updates - Swift Forums](https://forums.swift.org/t/december-12th-2019/31735) — "...following a review by IBM of its open source priorities, it has been decided that they will not be continuing to work on Swift in 2020. As a result, they are both standing down from the workgroup." I had high hopes for Swift. The idea of a purpose-built mobile and backend friendly language really intrigued me. But, it never really took off. With IBM pulling out of the working group, I don't think Swift will have an easy path to becoming a de facto backend contender. 🙁🙁🙁

[Kubernetes is booming, but consolidation is coming](https://www.zdnet.com/article/kubernetes-is-booming-but-consolidation-is-coming/) — "The crowded halls of the official Kubernetes conference Kubecon reflect a nascent but important technology whose best future might be to disappear into the background." Kubernetes is not a destination.

[Despite Amazon’s legal challenge, Microsoft reportedly moving forward with JEDI hiring push](https://www.geekwire.com/2019/despite-amazons-legal-challenge-microsoft-reportedly-moving-forward-jedi-hiring-push/) — Looks like Microsoft is preparing to deliver on JEDI despite upcoming challenges on the JEDI contract decision. I can't blame them. The court cases could go on for years.

[Electron joins the OpenJS Foundation](https://openjsf.org/blog/2019/12/11/electron-joins-the-openjs-foundation/) — But will it make Slack better?

## Tools

[Short Talks: A Conversation with Kelsey Hightower - OpenShift Commons Briefing](https://youtu.be/YYHp0oksor4) — "Chris Short, Principal Product Marketing Manager, OpenShift at Red Hat and CNCF Ambassador sits down with Staff Developer Advocate at Google, Kelsey Hightower to discuss Kubernetes. The conversation covers Kubernetes The Hard Way (which Kelsey created) and the rise of curated Kubernetes distributions like OpenShift and OKD."

[RDS Pricing Has More Than Doubled](https://medium.com/@rbranson/rds-pricing-has-more-than-doubled-ef8c3b7e5218) — "[A] 78% premium? Now that gives me pause. Particularly because it is so much more and with no added value². This violates a core expectation of technology: it gets better and cheaper over time even if it was already worth it."

[What is Kubernetes | Kubernetes explained in 15 mins (YouTube)](https://www.youtube.com/watch?v=VnvRFRk_51k&feature=youtu.be) — "Kubernetes popularity rises constantly. So, what is Kubernetes actually and what problems does it solve? In 'Kubernetes explained' I cover Kubernetes basic architecture and concepts, like Pods and Services."

[The Path Less Traveled: Abusing Kubernetes Defaults (YouTube)](https://www.youtube.com/watch?v=HmoVSmTIOxM) — "In this live demonstration-filled talk, we are going to walk through the Kubernetes control plane before using sigs.k8s.io/kind to show some of the attack surface exposed by a default configuration of Kubernetes. There will be multiple exploits involving various moving parts, including cluster takeovers and host escapes. We’ll show you mitigations, and then show you how to get around those."

[Updated XtraDB Cluster, XtraBackup, Percona Servers, New Features in Kubernetes Operator: Release Roundup 12/17/2019](https://www.percona.com/blog/2019/12/17/updated-xtradb-cluster-xtrabackup-percona-servers-new-features-in-kubernetes-operator-release-roundup/) — If you need MySQL in Kubernetes (or anywhere for that matter), Percona offers some very compelling solutions. I know when is was working with MySQL every day, Percona Toolkit was a staple in my life. It's awesome seeing Percona bringing these MySQL database tools into Kubernetes.

[Why Running a Privileged Container in Docker Is a Bad Idea](https://blog.trendmicro.com/trendlabs-security-intelligence/why-running-a-privileged-container-in-docker-is-a-bad-idea/) — Like anything else running as root, if it's compromised the entire system is. Say it with me, "Containers are not a security boundary."

[Ansible for Kubernetes](https://www.ansibleforkubernetes.com/) — "Ansible is a powerful infrastructure automation tool. Kubernetes is a powerful application deployment platform. Learn how to use these tools to automate massively-scalable, highly-available infrastructure." Jeff Geerlin's new LeanPub book.

[Introduction to Java Quarkus for Kubernetes (PodCTL)](http://podcast.podctl.com/110399/2323475-introduction-to-java-quarkus-for-kubernetes) — I talk with Daniel Oh about a new innovation in deploying Java applications on Kubernetes; Quarkus.

[RBAC recipes](https://recipes.rbac.dev/) — "Kubernetes RBAC can sometimes appear to be some sort of black magic. So, let's look behind the curtain." A handy set of RBAC snippets for reference and use.

[Spotify Machine Learning Platform Paved Road](https://labs.spotify.com/2019/12/13/the-winding-road-to-better-machine-learning-infrastructure-through-tensorflow-extended-and-kubeflow/) — Spotify's machine learning teams are second to none. Its third iteration is using Kubeflow Pipelines.

[This Week in Programming: The Time Has Come to Pay Attention to WebAssembly](https://thenewstack.io/this-week-in-programming-the-time-has-come-to-pay-attention-to-webassembly/) — WebAssembly has been embraced by W3C. Bytecode Alliance was launched. Brian Ketelsen has been raving about it for a while now. I think it's time we all start paying attention to WASM.

[CoreDNS-1.6.6 Release](https://coredns.io/2019/12/11/coredns-1.6.6-release/) — One security issue of note, bug fixes, and enhancements.

[What's New in Tekton 0.9](https://cd.foundation/blog/2019/12/12/whats-new-in-tekton-0-9/) — Announcing new Script Mode. I need deep dive into Tekton soon.

[arminc/k8s-platform-lcm](https://github.com/arminc/k8s-platform-lcm) — "A faster and easier way to manage the lifecycle of applications and tools, running and living around your Kubernetes platform"

## Tweet of the Week

{{< tweet 1207682466334609413 >}}
