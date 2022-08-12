+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-08-07T07:00:00Z
description = ["The little things, dafuq Apple, tech layoffs continue, MinIO and Nutanix, iRobot and Amazon, Kubernetes Removals and Major Changes In 1.25 and more"]
draft = false
slug = "279"
tags = ["Kubernetes", "project", "key", "open source", "cosign", "kernel", "host", "time", "cloud native", "developer", "manager", "Amazon", "password", "AWS", "Linux", "container", "eBPF", "virtual", "security", "observability", "DevOps", "sigstore"]
title = "DevOps'ish 279: The little things, dafuq Apple, tech layoffs continue, MinIO and Nutanix, iRobot and Amazon, Kubernetes Removals and Major Changes In 1.25 and more"
+++

Not going to lie. The GitHub Action cron job that builds the website automatically for me has not worked for weeks. I moved some sites to various services, and DevOps'ish returned to Netlify because of the branch build command granularity. I use Hugo and future dated articles are built when the `-F` flag is passed. This is very helpful in ensuring the newsletter is done just how I like it.

But, since returning to Netlify, the cron job to build the site at the right time of day has been busted. I finally had to go back in the commit history and copy/pasta all that and replace everything I was doing. It *should* work. This shows that no matter what, if you know you can look it up, your brain won't prioritize memorizing it. But, COME ON!!!

## Free Copy of Honeycomb's O'Reilly Book: Observability Engineering

Looking to make the switch from monitoring to observability? [Download your free copy of Honeycomb's O'Reilly book: Observability Engineering](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) to help you get started. Debrief the chapters with the authors themselves during our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112).

### Jobs

Now Hiring: [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003)  
[Camunda](https://camunda.com/) is the leader in process orchestration software. Our software helps orchestrate complex business processes that span people, systems, and devices. With Camunda, business users collaborate with developers to model and automate end-to-end processes using BPMN-powered flowcharts that run with the speed, scale, and resiliency required to compete in today's digital-first world.

As the [Developer Advocacy Manager](https://camunda.com/jobs/?gh_jid=5224679003), you'll be the direct people manager for a team of 4 Developer Advocates, responsible for career growth, performance evaluations, setting of priorities, and overall strategic guidance. You'll also be responsible for strategic planning for the Developer Advocacy function, including quarterly OKRs and annual goals as well as documentation of team responsibilities, goals, and success metrics.

*Note: The hiring manager is on a hard earned vacation.*

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we're expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We're excited to welcome you back to our Deserted Island this September 14th and 15th!

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?utm_source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

## People

[The women calling out Apple's handling of misconduct claims](https://arstechnica.com/tech-policy/2022/08/the-women-calling-out-apples-handling-of-misconduct-claims/)  
Patrick McGee, Ars Technica  
I expect better out of Apple. But, at the same time, I'm not surprised.

[Tech layoffs continue across the board: Here's the latest](https://www.fastcompany.com/90774924/tech-companies-continue-to-cut-costs-resulting-in-massive-layoffs)  
Fast Company  
"The layoffs in the sector are happening for a variety reasons. But it's clear that the market is in an entirely different place than it was in 2021, when dealmaking was happening at a rapid pace, and investors were jumping head first into funding rounds with sky-high valuations."

[Google CEO Sundar Pichai says productivity is “not where it needs to be”](https://arstechnica.com/gadgets/2022/08/google-ceo-calls-for-a-more-focused-and-efficient-google/)  
, Ars Technica  
Pichai changes Google's promotion incentives, wants "more customer focus." What a novel idea.

[Pelosi meeting with TSMC in Taiwan](https://www.washingtonpost.com/technology/2022/08/02/pelosi-tsmc-meeting-taiwan/)  
Jeanne Whalen and Ellen Nakashima , The Washington Post  
"TSMC is building a chip factory in Arizona -- and considering constructing several on the site -- in a project seen as key to U.S. national security" The sad thing is, war in Taiwan seems almost inevitable.

[Twitter slams Elon Musk's response to its lawsuit](https://www.axios.com/2022/08/04/musk-twitter-lawsuit-reply)  
Dan Primack and Sara Fischer, Axios  
Twitter is going to take that man's money.

## Process

[Update: Nutanix Objects Violates MinIO's Open Source License](https://blog.min.io/update-nutanix-violates-minio-opensource/)  
Garima Kapoor, MinIO Blog  
Nutanix's Apache 2 License has been revoked. MinIO ain't playing, Nutanix.

[Amazon and iRobot sign an agreement for Amazon to acquire iRobot](https://www.aboutamazon.com/news/company-news/amazon-and-irobot-sign-an-agreement-for-amazon-to-acquire-irobot?source=devopsish)  
Amazon Staff  
+2 Amazon devices in my house.

[School Kid Uploads Ransomware Scripts to PyPI Repository as 'Fun' Project](https://www.darkreading.com/threat-intelligence/school-kid-uploads-ransomware-scripts-to-pypi-repository-as-fun-research-project)  
Jai Vijayan, Dark Reading  
"The malware packages had names that were common typosquats of a legitimate widely used Python library. One was downloaded hundreds of times."

[Deception at a scale](https://blog.virustotal.com/2022/08/deception-at-scale.html)  
Vicente Díaz, VirusTotal Blog  
![How Malware Abuses Trust](https://shortcdn.com/file/devopsish/decepcion.webp)

## Tools

[Kubernetes Removals and Major Changes In 1.25](https://kubernetes.io/blog/2022/08/04/upcoming-changes-in-kubernetes-1-25/)  
Kat Cosgrove, Frederico Muñoz, and Debabrata Panigrahi; Kubernetes  
"As Kubernetes grows and matures, features may be deprecated, removed, or replaced with improvements for the health of the project. Kubernetes v1.25 includes several major changes and one major removal."

[Go 1.19 Release Notes](https://go.dev/doc/go1.19)  
The Go Programming Language  
And yes, Kubernetes is already upgrading to this version.

[How the 1Password CLI Makes DNS Management Easier](https://blog.1password.com/1password-cli-easier-dns-management/)  
Jack Platten, 1Password  
I might actually try and get this up and working. "Now I can run dnscontrol push --creds “!op inject -i creds.json” to inject my credentials into my template file, return it on stdout and make the changes to my domains, all without my credentials ever touching the disk. And it works on all my computers, as long as I have both the DNSControl executable as well as the 1Password command-line tool installed."

[Welcoming the AWS Customer Incident Response Team](https://aws.amazon.com/blogs/security/welcoming-the-aws-customer-incident-response-team/?source=devopsish)  
Kyle Dickinson, AWS Security Blog  
Open source security tooling for your AWS accounts.

[Fedora Linux to Support Raspberry Pi 4 in Next Release](https://www.tomshardware.com/news/fedora-gets-pi-support)  
Ian Evenden, Tom's Hardware  
It would appear to be the year of Fedora.

[Kubernetes Pi Cluster relase v1.4](https://picluster.ricsanfre.com/blog/2022/08/04/announcing-relase-1.4/)
ricsanfre, Raspberry Pi Kubernetes Cluster Project  
With the addition of an EFK stack!

[Adopting Sigstore Incrementally](https://blog.sigstore.dev/adopting-sigstore-incrementally-1b56a69b8c15)  
Hayden Blauzvern, sigstore  
Developers that maintain their own signing keys but want to migrate to Sigstore can first switch to using Cosign to generate a signature over an artifact. Cosign supports importing an existing RSA, ECDSA, or ED25519 PEM-encoded PKCS#1 or PKCS#8 key with `cosign import-key-pair --key key.pem`, and can sign and verify with `cosign sign-blob --key cosign.key artifact-path`, and `cosign verify-blob --key cosign.pub artifact-path`.

[Linus Torvalds uses an Arm-powered M2 MacBook Air to release latest Linux kernel](https://arstechnica.com/gadgets/2022/08/linus-torvalds-uses-an-arm-powered-m2-macbook-air-to-release-latest-linux-kernel/)  
Andrew Cunningham, Ars Technica  
"It's something I've been waiting for for a loong [sic] time, and it's finally reality, thanks to the Asahi team," Torvalds writes. "We've had arm64 hardware around running Linux for a long time, but none of it has really been usable as a development platform until now."

[Docker and the OCI container ecosystem](https://lwn.net/Articles/902049/)  
Jordan Webb, LWN  
A container is somewhat like a lightweight virtual machine; it shares a kernel with the host, but in most other ways it appears to be an independent machine to the software running inside of it. The Linux kernel itself has no concept of containers; instead, they are created by using a combination of several kernel features:

* Bind mounts and overlayfs may be used to construct the root filesystem of the container.
* Control groups may be used to partition CPU, memory, and I/O resources for the host kernel.
* Namespaces are used to create an isolated view of the system for processes running inside the container.

[Direct host system calls from KVM](https://lwn.net/SubscriberLink/902585/1bd0f132de681475/)  
Jonathan Corbet, LWN  
"As a general rule, virtualization mechanisms are designed to provide strong isolation between a host and the guest systems that it runs. The guests are not trusted, and their ability to access or influence anything outside of their virtual machines must be tightly controlled. So a patch series allowing guests to execute arbitrary system calls in the host context might be expected to be the cause of significantly elevated eyebrows across the net. Andrei Vagin has posted [such a series](https://lwn.net/ml/linux-kernel/20220722230241.1944655-1-avagin@google.com/) with the expected results."

[hktalent/scan4all: vuls Scan](https://github.com/hktalent/scan4all)  
⭐️ 2.5K  
"15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty"

[SummitRoute/aws_breaking_changes](https://github.com/SummitRoute/aws_breaking_changes)  
⭐️ 576  
"List of changes announced for AWS that may break existing code"

[the-markup/vehicle-data-collection](https://github.com/the-markup/vehicle-data-collection)  
⭐️ 23  
'This contains the data for our story "Who Is Collecting Data from Your Car?".'

## DevOps'ish Post of the Week

[![Christian Hernandez on Twitter: "Okay, been working at this for a bit; but I'm excited to announce that I'll be #streaming about #GitOps again! Join @jjasghar and I on August 15th at 1pm Eastern as we kickoff the series: GitOps The Planet")](https://shortcdn.com/file/devopsish/279-devopsish-post-of-the-week.webp)](https://twitter.com/christianh814/status/1555641036713578498?utm_source=devopsish)

### Got a newsletter worthy post?

Have a story for the newsletter? Getting exposure via this newsletter is [a pull request](https://github.com/chris-short/devopsish.com/issues/new/choose) away. Tips is the very first option, click "[Get Started](https://github.com/chris-short/devopsish.com/issues/new?assignees=chris-short&labels=tips&template=TIPS.md&title=%5BTips%5D%3A+)", and send in your shiny, new thing.

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/279/notes.md)