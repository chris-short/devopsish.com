+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2020"]
date = 2020-08-23T07:00:00Z
description = "DevOps'ish 180"
draft = false
slug = "180"
tags = ["Kubernetes", "cloud native", "open source", "cloud", "DevOps", "security", "namespaces", "hierarchical namespaces", "Tekton", "proxy", "Linkerd", "Cloud Native Computing Foundation", "CNCF", "KubeCon", "containers", "postgresql", "postgres", "Docker", "Ian Coldwater"]
title = "DevOps'ish 180"

+++

Welcome!

What a week it was. KubeCon EU 2020 was this past week. And amongst all the announcements there was a lot of activity and interaction too. Two things I realized this week were, first, y'all are really bubble gumming and duct taping clusters together into production like it's no big deal just waiting to be bit by something. Second, the Kubernetes community is really an amazing bunch of people, in general.

I asked what some folks thought were the highlights of the week's festivities and I'd like to share those here:

[Alexis "Horgix" Chotard](https://twitter.com/Horgix) said, "The openness and transparency of Case Studies, especially the one from @milesbxf and @suhailpatel [**here**](https://twitter.com/Horgix/status/1296071376760115200)

[Joshua Bezaleel](https://twitter.com/joshuabezaleel/status/1296443783580725248?s=20) said, "[Holly Cummins keynote on climate](https://kccnceu20.sched.com/event/ZfGQ/keynote-how-to-love-k8s-and-not-wreck-the-planet-holly-cummins-worldwide-ibm-garage-developer-lead-ibm). That was amazing."

There was a ton of praise for Ian Coldwater and Brad Geesaman's talk, [Advanced Persistence Threats: The Future of Kubernetes Attacks](https://kccnceu20.sched.com/event/ZesN/advanced-persistence-threats-the-future-of-kubernetes-attacks-ian-coldwater-heroku-brad-geesaman-brad-geesaman-consulting). Ian Coldwater was the talk of the conference pretty much.

I have no idea when any of these talks are going to be publicly available. But, you can log back into the ~~terrible~~ platform and watch the talks and keynotes on demand at the moment.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_180). They have recently released a rewrite of [Terrascan](https://github.com/accurics/terrascan?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_180) that uses the incubating Cloud Native Computing Foundation project, [Open Policy Agent](https://www.openpolicyagent.org/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_180).

## People

[Mozilla is dead](https://kowabit.de/mozilla-is-dead/)  
"If the official news and the unofficial information come true, I believe that Mozilla will die. Ciao Firefox, ciao Thunderbird. Sorry. Also goodbye to all other products that nobody ordered." Pocket is a critical tool in the workflow for DevOps'ish (and yes, I pay for it).

[Thinking of Skipping Vacation? Don't!](https://hbr.org/2020/08/thinking-of-skipping-vacation-dont)  
Definitely been mulling this one over given the current state of the world. This article convinced me to take more time off. I'll be taking a week off at some point in the fall I think.

[Open-source earthquake alert system aims to revolutionize seismic monitoring](https://www.techrepublic.com/article/open-source-earthquake-alert-system-aims-to-revolutionize-seismic-monitoring/)  
"As sensors are deployed around the globe, the open-source project aims to improve current earthquake detection and alert systems and using machine learning and other technologies."

[Atlassian tells employees they can work from home indefinitely](https://www.cnbc.com/2020/08/07/atlassian-tells-employees-they-can-work-from-home-indefinitely.html)  
To an extent, a lot of companies are going to go this route as companies look at how operations have gone and how soon they can get out of leases.

[Equal access to tech can reduce poverty and increase diversity](https://thehill.com/opinion/technology/511436-equal-access-to-tech-can-reduce-poverty-and-increase-diversity)  
"We need to remove the barriers of access to education, technology and career advancement that are keeping people of color from the same opportunities and achievements others enjoy. Even helping one kid in this way would be amazing. This would be one of the greatest hacks ever."

## Process

[Softbank confirms talks to offload Arm as it posts rebound profit](https://www.theregister.com/2020/08/12/softbank_q2_2021/)  
Arm being sold is going to be a game changer. The new owner will have the future of computing in their hands (if they don't screw it up).

[Scribd acquires presentation-sharing service SlideShare from LinkedIn](https://techcrunch.com/2020/08/11/scribd-acquires-slideshare/)  
This is good news so long as they actually decouple it from LinkedIn and allow alternative login methods.

[Webinar | Empower DevOps and Security Teams with Kubernetes-native Security](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh)  
Startups and enterprises alike are embracing containerization and Kubernetes, but security struggles to move at the pace of DevOps, bogged down by tools and processes not suited for cloud-native technology. [Register for this webinar](https://pages.awscloud.com/GLOBAL-partner-OE-containers-stackrox-sept-2020-reg-event.html?ContainersStackRoxSeptember2020&sc_publisher=StackRox&sc_country=USA&sc_geo=NAMER&sc_category=mult&sc_outcome=acq&trk=Partner_DevOpsIsh) where cloud-native security experts from AWS, Informatica, and StackRox will discuss how to apply Kubernetes-native security and controls to protect containers and Kubernetes without slowing down application development and rollout. *Date: Sep 03, 2020 | 10 AM PDT* *SPONSORED*

[Intel Publishes 18 New Security Advisories For 52 Vulnerabilities](https://www.phoronix.com/scan.php?page=news_item&px=Intel-Security-August-2020)  
If it has the word Intel on it, patch it.

[A college kid created a fake, AI-generated blog. It reached #1 on Hacker News](https://www.technologyreview.com/2020/08/14/1006780/ai-gpt-3-fake-blog-reached-top-of-hacker-news/)  
Proof that we're all just gullible meat sacks. “It was super easy actually,“ he says, “which was the scary part."

[NSA discloses new Russian-made Drovorub malware targeting Linux](https://www.bleepingcomputer.com/news/security/nsa-discloses-new-russian-made-drovorub-malware-targeting-linux/)  
"The malicious framework has various modules that ensure stealthiness, persistence, and complete access to the compromised machine with the highest privileges."

## Tools

[Introducing Hierarchical Namespaces](https://kubernetes.io/blog/2020/08/14/introducing-hierarchical-namespaces/)  
Yo dawg, I heard your namespaces need namespaces. "In its simplest form, a hierarchical namespace is a regular Kubernetes namespace that contains a small custom resource that identifies a single, optional, parent namespace. This establishes the concept of ownership across namespaces, not just within them."

[Introducing Tekton Hub](https://cd.foundation/blog/2020/08/10/introducing-tekton-hub/)  
[Tekton Hub](https://hub-preview.tekton.dev/) provides a central hub for searching and sharing Tekton resources across many distributed Tekton catalogs hosted by various organizations and teams.

[pomerium/pomerium](https://github.com/pomerium/pomerium)  
Pomerium is an identity-aware access proxy. They're marketing this as "a VPN alternative."

[Crunchy PostgreSQL for Kubernetes](https://www.crunchydata.com/products/crunchy-postgresql-for-kubernetes/?utm_source=DevOpsish&utm_medium=Week1&utm_campaign=CrunchyK8)  
Crunchy PostgreSQL for Kubernetes takes your favorite database (Postgres) and makes it easy to run on K8s. Includes HA, backups, and monitoring. Need extra support or architectural guidance? Reach out to Crunchy Data and learn how we can help with your Postgres needs. *SPONSORED*

[How the Cortex and Thanos projects collaborate to make scaling Prometheus better for all](https://grafana.com/blog/2020/07/16/how-the-cortex-and-thanos-projects-collaborate-to-make-scaling-prometheus-better-for-all/)  
"Thanos now supports a push-based model via its recently introduced [receiver component](https://thanos.io/components/receive.md/), and many improvements have been done both in terms of scalability and performances. Likewise, Cortex’s operational complexity has been significantly reduced: we introduced the single binary mode, removed some external dependencies, and worked hard to improve the documentation."

[Create a wifi hotspot with Raspberry Pi 3 and Fedora](https://fedoramagazine.org/create-a-wifi-hotspot-with-raspberry-pi-3-and-fedora/)  
I could easily see how this would come in handy in many ways. When I start traveling again, I might be packing one of these.

[Moving from docker-compose to Podman pods](https://www.redhat.com/sysadmin/compose-podman-pods)  
"Follow the migration of a virtual machine from Docker to Podman."

[Under the hood of Linkerd's state-of-the-art Rust proxy, Linkerd2-proxy](https://linkerd.io/2020/07/23/under-the-hood-of-linkerds-state-of-the-art-rust-proxy-linkerd2-proxy/)  
You're going to start seeing a lot more love for Linkerd here. "'Unlike general purpose proxies such as Envoy, NGINX, and haproxy, the open source Linkerd2-proxy is designed to do only one thing and do it better than anyone else: be a service mesh sidecar proxy.'"

[aquasecurity/trivy](https://github.com/aquasecurity/trivy)  
A Simple and Comprehensive Vulnerability Scanner for Containers, Suitable for CI

## DevOps'ish Tweet of the Week

{{< tweet 1293748173937061888 >}}

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/180/notes/) to see what didn't make it to the newsletter.

{{< amazon >}}
