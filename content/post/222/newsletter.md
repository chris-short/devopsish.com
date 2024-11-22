+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-06-13
description = ["Industry under pressure, Holy $%^& I agree with Torvalds, US Congress begins assault on big tech, polkit vuln, ALPACA, How To Love Kubernetes and Not Wreck The Planet, and more"]
draft = false
slug = "222"
tags = ["cloud", "DevOps", "Kubernetes","cluster", "observability", "Cloud Native", "security", "open source", "Linux", "Apple", "hackers", "Slack", "EA", "Argo", "Operators", "container", "FBI", "community", "tech", "systems", "software", "engineering", "eBPF", "Red Hat", "Linus Torvalds"]
title = "DevOps'ish 222: Industry under pressure, Holy $%^& I agree with Torvalds, US Congress begins assault on big tech, polkit vuln, ALPACA, How To Love Kubernetes and Not Wreck The Planet, and more"

+++

I want to point out a few signs that I think we're pushing the industry too hard, too fast. [Fires in AWS data centers](https://twitter.com/QuinnyPig/status/1403100781646028808), [Fastly (the CDN) took an hour-long outage](https://techcrunch.com/2021/06/08/numerous-popular-websites-are-facing-an-outage/) triggered by a [customer finding a bug](https://www.theguardian.com/technology/2021/jun/09/fastly-says-single-customer-triggered-bug-that-caused-mass-outage), [Cloudflare had outages in Chicago and Los Angeles](https://www.cloudflarestatus.com/incidents/0cvlzpvwg251). [Ransomware is running through companies](https://www.washingtonpost.com/technology/2021/07/08/ransomware-human-impact/) like Grant went through Richmond (to the point the [US Justice department is equating them, in some ways, to terrorist attacks](https://www.latimes.com/business/technology/story/2021-06-03/ransomware-targeted-by-justice-department-as-attacks-flourish)).

Things need to change. Moving towards a more hybrid and fluid environment is not just a strategic priority; it's survival at this point. Then making sure that your entire business can't grind to a halt because lowest common denominator security issues happen. I thought we figured it out in the early 2000s. But, technology has changed so much since then, and there are new zero-days every day. We're in a very tight position as technologists. If you're a developer, you're a target. If you're an employee, you're a target. You and every service you touch is a target. Nothing is safe.

## People

[It’s time to ditch Chrome](https://www.wired.co.uk/article/google-chrome-browser-data)  
Yeah... This has gotten out of control.

[Re: Maintainers / Kernel Summit 2021 planning kick-off - Linus Torvalds](https://lore.kernel.org/ksummit/CAHk-=wiB6FJknDC5PMfpkg4gZrbSuC3d391VyReM4Wb0+JYXXA@mail.gmail.com/)  
Holy shit... I agree with Linux Torvalds. I think this is the second time ever.

[Record labels sue another ISP, demanding mass disconnections of Internet users](https://arstechnica.com/tech-policy/2021/06/record-labels-sue-another-isp-demanding-mass-disconnections-of-internet-users/)  
"Frontier sued amid concerns that ISPs will have to disconnect 'innocent' users."

[Less nosy smart speakers](https://news.engin.umich.edu/2021/06/less-nosy-smart-speakers/)  
"The system pieces together the ultrasonic information that's all around us to identify when its services are needed, and sense what's going on around it. Researchers have demonstrated that it can identify household and office activities with greater than 95% accuracy."

[FBI sold phones to organized crime and read 27 million "encrypted" messages](https://arstechnica.com/tech-policy/2021/06/fbi-sold-phones-to-organized-crime-and-read-27-million-encrypted-messages/)  
"But instead of getting backdoors installed into commonly used products—a step that Apple and other companies resisted because it would undermine security for all users—the FBI simply made and sold encrypted devices and monitored the devices' communications." If the intelligence community wants you, it'll find a way.

## Process

[Congress Introduces 5 Antitrust Bills to Rein in Big Tech](https://www.businessinsider.com/congress-big-tech-bills-facebook-google-apple-amazon-antitrust-2021-6)  
BOHICA! But, long overdue.

Observability is critical for managing and improving complex business-critical systems. With observability, any software engineering team can gain a deeper understanding of system performance, so you can perform ongoing maintenance and ship the features your customers need. Preview [Honeycomb's upcoming O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-preview-0?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish&utm_adgroup), written by Charity Majors, Liz Fong-Jones, and George Miranda, to understand the value of observable systems and how to build an observability-driven development practice. *SPONSORED*

[How Hackers Used Slack to Break into EA Games](https://www.vice.com/en/article/7kvkqb/how-ea-games-was-hacked-slack)  
"the process started by purchasing stolen cookies being sold online for $10 and using those to gain access to a Slack channel used by EA. Cookies can save the login details of particular users, and potentially let hackers log into services as that person. In this case, the hackers were able to get into EA's Slack using the stolen cookie." Then it was social engineering the IT team at EA and off they went with valid 2FA and all.

[McDonald's Hit by Data Breach](https://www.wsj.com/articles/mcdonalds-hit-by-data-breach-in-south-korea-taiwan-11623412800)  
"Hack exposed some U.S. business information, customer data in South Korea and Taiwan"

[Privilege escalation with polkit: How to get root on Linux with a seven-year-old bug](https://github.blog/2021-06-10-privilege-escalation-polkit-root-on-linux-with-bug/)  
"[M]any of the most popular Linux distributions didn't ship the vulnerable version until more recently."

[ALPACA Attack](https://alpaca-attack.com/)  
"ALPACA is an application layer protocol content confusion attack, exploiting TLS servers implementing different protocols but using compatible certificates, such as multi-domain or wildcard certificates. Attackers can redirect traffic from one subdomain to another, resulting in a valid TLS session."

## Tools

[Cloud Tech Thursdays: How To Love Kubernetes and Not Wreck The Planet](https://www.youtube.com/watch?v=QlW6quAzupU)  
It turns out that managing your cloud spend effectively is good for the planet too. Timely too because [CO2 levels are at an all-time high — again](https://www.theverge.com/2021/6/7/22522736/carbon-dioxide-co2-record-climate-change).

Teleport allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all environments. [Learn more](https://goteleport.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish_222) *SPONSORED*

[How Netflix uses eBPF flow logs at scale for network insight](https://netflixtechblog.com/how-netflix-uses-ebpf-flow-logs-at-scale-for-network-insight-e3ea997dca96)  
"Netflix has developed a network observability sidecar called Flow Exporter that uses eBPF tracepoints to capture TCP flows at near real time. At much less than 1% of CPU and memory on the instance, this highly performant sidecar provides flow data at scale for network insight."

[Architecting Kubernetes clusters — choosing the best autoscaling strategy](https://learnk8s.io/kubernetes-autoscaling-strategies)  
"TL;DR: Scaling pods and nodes in a Kubernetes cluster could take several minutes with the default settings. Learn how to size your cluster nodes, configure the Horizontal and Cluster Autoscaler, and overprovision your cluster for faster scaling."

[Using Argo to Train Predictive Models](https://flightaware.engineering/using-argo-to-train-predictive-models/)  
"Andrew Brooks continually works to maintain, analyze, and improve FlightAware's predictive models as well as the software and infrastructure that supports them."

[50 TB of Cloud Images](https://techblog.web.cern.ch/techblog/post/50tb-of-cloud-images/)  
"Over the years, the number of Cloud images has been growing in the CERN OpenStack Cloud. We have accumulated more than 50 TB of available Cloud images/snapshots. Unfortunately, Cloud operators have very few tools to control the growth of the OpenStack Image service."

[Introducing kwctl to Kubernetes Administrators](https://www.kubewarden.io/blog/2021/06/kwctl-intro-for-kubernetes-administrators/)  
"Kubewarden policies are distributed via OCI container registries, the very same pieces of infrastructure already used to distribute container images."

[Introduction to Red Hat's UBI Micro](https://www.redhat.com/en/blog/introduction-ubi-micro)  
"UBI Micro is constructed from the exact same packages as UBI Standard, Minimal, and Init, but minimizes the individual image size by excluding a package manager and all of its dependencies which are normally pulled into a container image."

[Siloscape: First Known Malware Targeting Windows Containers to Compromise Cloud Environments](https://unit42.paloaltonetworks.com/siloscape/)  
Sheesh... Windows containers are barely mainsteam and 💥, compromised.

[open-cluster-management/multicloud-operators-subscription](https://github.com/open-cluster-management/multicloud-operators-subscription)  
"CRD and controller for Subscription (Channel Subscription model) for Multicloud Application."

[ilhaan/kubeCDN](https://github.com/ilhaan/kubeCDN)  
"Self-hosted CDN based on Kubernetes"

## DevOps'ish Tweet of the Week

{{< tweet 1402621023296557060 >}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/222/notes.md) to see what didn't make it to the newsletter but are still worth your time.
