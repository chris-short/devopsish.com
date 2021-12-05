+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2019"]
date = 2019-11-10T07:00:00Z
description = "UNIX: A History and a Memoir, systemd ~, JEDI, Jaeger, Fitbit, DKIM, Ansible Operators, Quarkus, Img, Podman, Contour, and More"
draft = false
slug = "153"
tags = ["DevOps", "KubeCon", "KubeKhan", "Kubernetes", "cloud native", "AWS", "Microsoft", "PodCTL", "open source", "OpenTitan", "Vitess", "GitOps", "security", "Helm", "Ansible Operators"]
title = "153: The week before KubeCon, KubeKhan is back, PodCTL, Microsoft making moves, GitOps, AWS Savings Plans, OpenTitan, Vitess, and more"

+++

Note: DevOps'ish will no longer publish an RSS feed. It's a [business decision](https://github.com/chris-short/devopsish.com/commit/8a1c7e0ec934aff626a10bf5f7b8b6d2e3faf53c) at this point. Please [subscribe](https://devopsish.com/subscribe/) via e-mail. Subscribers seem to be the only metric potential sponsors care about. This change should ensure the long term viability of DevOps'ish.

Are you ready for [KubeCon](https://cshort.co/kcna19)? I'm not, but I hope to be by end of day Friday. There are a number of events every night (see Events section). If your calendar isn't booked and you're looking for something to do, several sponsors are hosting things across San Diego. I'll be arriving on Sunday midday and heading over to [Cloud Native Rejekts](https://cloud-native.rejekts.io/). Monday, I'll be helping at the New Contributor Summit. Tuesday and Wednesday are going to be non-stop Kubernetes and cloud native awesomeness. Thursday things seem to slow a little. When in doubt, I'll be near the Red Hat booth or supporting my friends that are speaking. I tell my family that this is essentially our Super Bowl for the year. I hope it doesn't disappoint.

But, the event of the year we all know is [#KubeKhan](https://twitter.com/search?q=(%23KubeKhan)&src=typed_query&f=live). The come as you are, judgment-free gathering is back this year with a little extra oomph thanks to our friends at [Cloud Native Computing Foundation](https://cncf.io). It's casual and will take place every night of KubeCon activities in some capacity. But, the first official night of #KubeKhan will be Monday, November, 18th at the Marriott Marquis® San Diego Marina starting around 7-ish. The [KubeCon Code of Conduct](https://events19.linuxfoundation.org/events/kubecon-cloudnativecon-north-america-2019/attend/code-of-conduct/) will be adhered to.

## Events

[**KubeCon + CloudNativeCon North America 2019**](https://cshort.co/kcna19)  
The Cloud Native Computing Foundation's flagship conference gathers adopters and technologists from leading open source and cloud native communities in San Diego, California from November 18-21, 2019. Join Kubernetes, Prometheus, Envoy, CoreDNS, containerd, Fluentd, OpenTracing, gRPC, CNI, Jaeger, Notary, TUF, Vitess, NATS, Linkerd, Helm, Rook, Harbor, etcd, Open Policy Agent, CRI-O, and TiKV as the community gathers for four days to further the education and advancement of cloud native computing. Use code *KCNACSN10* at checkout for a 10% discount on KubeCon Corporate Registration.

[Diversity and Inclusion Lunches and Hacks - KubeCon + CloudNativeCon North America 2019](https://events19.linuxfoundation.org/events/kubecon-cloudnativecon-north-america-2019/attend/diversity-and-inclusion/?utm_source=devopsish&utm_campaign=153)

[KubeHunt San Diego 2019](http://view.ceros.com/turbonomic/kubehunt-san-diego-2019/p/1?utm_source=devopsish&utm_campaign=153) — Complete the form. Spots are limited. Registration will close at 3pm on Monday, November 18th, 2019.

[San Diego Mixer: Meet the DigitalOcean Kubernetes Team & Kick-Off KubeCon Tickets, Mon, Nov 18, 2019 at 6:30 PM](https://www.eventbrite.com/e/san-diego-mixer-meet-the-digitalocean-kubernetes-team-kick-off-kubecon-tickets-76347761209?utm_source=devopsish&utm_campaign=153)

[KubeCon k8s Rooftop Happy Hour Registration, Mon, Nov 18, 2019 at 6:30 PM](https://www.eventbrite.com/e/kubecon-k8s-rooftop-happy-hour-registration-76084848831?utm_source=devopsish&utm_campaign=153)

[Snyk & CloudBees Happy Hour at KubeCon, Monday, November 18th at 5:30 PM](https://info.snyk.io/kubecon/cloudbees/happyhour?utm_source=devopsish&utm_campaign=153)

[K8s or Die! Party by Mirantis, Tuesday, Nov 19th, 2019 at 8:30pm](https://k8sordie.com/party/?utm_source=devopsish&utm_campaign=153)

## People

[The Intersection of DevOps and Kubernetes](https://podcasts.apple.com/gb/podcast/the-intersection-of-devops-and-kubernetes/id1270983443?i=1000456263929)  
"Brian talks with Chris Short ([@ChrisShort](https://twitter.com/ChrisShort), Technical Marketing Red Hat, CNCF Ambassador, writes at DevOps’ish) about DevOps 10th birthday, how Kubernetes helps DevOps."


 [We recorded an episode](http://podcast.podctl.com/110399/2024361-the-intersection-of-devops-and-kubernetes?utm_source=devopsish&utm_campaign=153) during the calm before the KubeCon storm. [A fancy mic for my iPhone](https://amzn.to/2NYe0t0) is now part of my kit and we're off to the races.

[My Job Interview at Google](https://catonmat.net/my-job-interview-at-google) — A walkthrough of the Google SRE hiring process.

[Microsoft finds workers are more productive with a 4-day workweek](https://mspoweruser.com/microsoft-4-day-workweek/) — "More importantly from a bottom-line standpoint, however, productivity went up 39.9%, as fewer and shorter meetings were held, often virtually rather than in person." That right there is reason enough to try it for me.

[Tikam02/DevOps-Guide](https://github.com/Tikam02/DevOps-Guide) — DevOps Guide from basic to advanced with Interview Questions and Notes 🔥

[In a world of infosec rockstars, shutting down sexual harassment is hard work for victims](https://www.theregister.co.uk/2019/11/04/hackers_and_harassment/) — How a close-knit hero-worshiping culture can make reporting abusers difficult – and how help is at hand

[Welcome, Singular “They”](https://apastyle.apa.org/blog/singular-they) — The Publication Manual of the American Psychological Association has adopted singular They/Their as opposed to "his or hers." That's going to save me a lot of mental capacity in their long run.

## Process

[At Ignite, Microsoft pitches its new role embracing the wider tech ecosystem](https://siliconangle.com/2019/11/05/analysts-see-latest-releases-as-evidence-of-evolving-new-role-for-microsoft-msignite/) — As Microsoft, VMware, and Google look to get into running faster on their new long term business strategies it seems that Microsoft has eeked ahead ever so slightly this week.

[5 GitOps Best Practices](https://blog.argoproj.io/5-gitops-best-practices-d95cb0cbe9ff) — "Here are some of the key best practices we’ve discovered while engineering Argo CD and running it at scale managing thousands of apps in production at Intuit."

[Cloud Native Chaos Engineering - Enhancing Kubernetes Application Resiliency](https://www.cncf.io/blog/2019/11/06/cloud-native-chaos-engineering-enhancing-kubernetes-application-resiliency/) — A look at the MayaData stack

[Re-Licensing Sentry](https://blog.sentry.io/2019/11/06/relicensing-sentry) — Sentry isn't an open source company anymore.

[Cloud Native Computing Foundation Announces Vitess Graduation](https://www.cncf.io/announcement/2019/11/05/cloud-native-computing-foundation-announces-vitess-graduation/) — Congrats to the Vitess team!

[Helm Security Audit Results](https://helm.sh/blog/2019-11-04-helm-security-audit-results/) — Ship it! Helm is ready to set sail into its Tillerless future.

[Python overtakes Java to become second-most popular language on GitHub after JavaScript](https://www.theregister.co.uk/2019/11/07/python_java_github_javascript/) — "Build once, run anywhere" versus "I have three versions of this on my system and seven virtual envs (that I know of)."

## Tools

[AWS Begins Sunsetting RIs; Replaces Them With Something Much, Much Better](https://www.lastweekinaws.com/blog/aws-begins-sunsetting-ris-replaces-them-with-something-much-much-better/) — "AWS announced 'Savings Plans,' which sounds like a bank’s Christmas Club account offering but is in fact something far more compelling. It amounts to nothing less than a complete overhaul of the AWS compute pricing model."

[OpenTitan - open sourcing transparent, trustworthy, and secure silicon](https://security.googleblog.com/2019/11/opentitan-open-sourcing-transparent.html) — A big step forward for securing compute.

[Istio: Up and Running: Using a Service Mesh to Connect, Secure, Control, and Observe](https://amzn.to/2PGCQAk) — "In this book, Lee Calcote and Zack Butcher explain why your services need a service mesh and demonstrate step-by-step how Istio fits into the life cycle of a distributed application. You'll learn about the tools and APIs for enabling and managing many of the features found in Istio."

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](https://devopsish.com/terms/).*

[Kubernetes Patterns by Bilgin Ibryam and Roland Huß](https://www.redhat.com/en/engage/kubernetes-containers-architecture-s-201910240918?utm_source=devopsish&utm_campaign=153) — One of the best reference books for Kubernetes is now available after signup. However, the signup form is annoying as hell and for that I am sorry. Disclaimer: My views do not reflect those of Red Hat.

[Mario's Adventures in Tekton Land](https://devops.com/marios-adventures-in-tekton-land/)

[BLESSing away SSH worries](https://medium.com/@ikshitijsharma/blessing-away-ssh-worries-ultimate-practical-guide-to-setup-netflix-bless-in-under-60-minutes-d6880f2a8e23) — "Ultimate Practical Guide to setup Netflix Bless in under 60 minutes from scratch with the Go Client"

[The 10 Best Linux Books To Read in 2019](https://devconnected.com/the-10-best-linux-books-to-read-in-2019/)

[Introducing Pkger — Static File Embedding in Go](https://blog.gobuffalo.io/introducing-pkger-static-file-embedding-in-go-1ce76dc79c65) — "Today I would like to introduce Pkger, a tool for embedding static files into Go binaries that is idiomatic, lossless, and less complex."

[Kubernetes Multi-Operator Stacks and Advanced Pod Scheduling](https://medium.com/@cloudark/kubernetes-multi-operator-stacks-and-advanced-pod-scheduling-c3131dde3755) — "Kubernetes provides several advanced Pod scheduling constructs. As an Operator developer it is important for you to carefully evaluate these constructs when designing your Custom Resources and Custom Controllers."

[Basic security principles for containers and container runtimes](https://www.redhat.com/sysadmin/basic-security-principles-containers)

[Primer: What Is Container Security?](https://thenewstack.io/primer-what-is-container-security/) — "The way modern DevOps operates, it is impossible to implement successful controls without automation. The scale and dynamic nature are too much to try and keep up by using static or manually updated tools. If your security tool cannot keep up with the way your DevOps teams operate, then it is unlikely it will be adopted or effective."

[Basic troubleshooting with telnet and netcat](https://www.redhat.com/sysadmin/telnet-netcat-troubleshooting) — Two popular tools for testing network services on a basic level are telnet and Netcat. Here's how to use them.

[aquasecurity/tracee](https://github.com/aquasecurity/tracee) — [EXPERIMENTAL] Container tracing using eBPF

[linki/chaoskube](https://github.com/linki/chaoskube) — chaoskube periodically kills random pods in your Kubernetes cluster

[kubecost/cost-model](https://github.com/kubecost/cost-model) — Cross-cloud cost allocation models for workloads running on Kubernetes

[DShield-ISC/dshield](https://github.com/DShield-ISC/dshield) — DShield Raspberry Pi Sensor

[No Maintenance Intended](http://unmaintained.tech/) — "The linking project's code is provided as-is, and is not actively maintained."

## Tweet of the Week

{{< tweet 1191789413279264768 >}}
