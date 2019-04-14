+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-04-07T07:00:00Z
description = ""
draft = false
slug = "122"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "container", "security", "red hat", "envoy", "OPA", "BPF", "Chef"]
title = "122: Chefnanigans, Emotional Intelligence, Derek the DevOps Dinosaur, BPF, Envoy Convoy, Crates of k8s, OPA, and More"

+++

Chef announced this week they were giving up on letting users have binaries for free. Instead, you now can have all the source code for free but, [not any of the binaries](https://blog.chef.io/2019/04/02/chef-software-announces-the-enterprise-automation-stack/). [Adam Jacobs](https://medium.com/@adamhjk/goodbye-open-core-good-riddance-to-bad-rubbish-ae3355316494) cited one company as having already adopted this model; **Red Hat** (my employer, see [disclaimer](https://devopsish.com/terms/)). It's a rather dubious claim because this [Free Software Product](https://sfosc.org/business-models/free-software-product/) model, developed mostly by [Adam Jacobs in the past sixth months](https://github.com/sfosc/sfosc/graphs/contributors), definitely does not predate Red Hat. I sure haven’t seen an announcement about how Red Hat is changing anything. Nor have I seen any policy about adopting this specific model (full disclosure, I was on PTO Friday). Regardless, I guess the thinking is if you can’t beat ‘em, join ‘em? ¯\\\_(ツ)\_/¯

But, what if the Red Hat model didn't work? [Red Hat is getting acquired by IBM](https://investors.redhat.com/news-and-events/press-releases/2018/10-28-2018-184027500) but, is that a win? That remains to be seen. The Red Hat model is likely a win for investors once the acquisition closes. But, is that a win for open source? Are we even playing the same game? 🤔🤔🤔

Don't get me wrong, I'm excited to see where all this goes. It's a ridiculously exciting time to be working in this industry. It's also a ridiculously turbulent time. Whether any of this works remains to be seen.

> "Trust yourself. Create the kind of self that you will be happy to live with all your life." —Golda Meir

[**Log Management Modernized**](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish)  
With LogDNA's fast, multi-cloud logging platform, DevOps and Engineering teams can easily and quickly aggregate all system and application logs into one efficient platform.  
Whether on-premise, in the cloud, or a hybrid solution, we have you covered. Don't take our word for it. Try it yourself.

[Get started logging in a few minutes with a free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish). *SPONSORED*

[**Audiobook: Lean Enterprise**](https://devopsi.sh/g8MpN7)  
How well does your organization respond to changing market conditions, customer needs, and emerging technologies? This practical guide presents Lean and Agile principles and patterns that enable you to move fast at scale—and demonstrates why and how to apply these methodologies throughout your organization, rather than in just one department or team. Through case studies, you'll learn how successful enterprises have rethought everything from governance and financial management to systems architecture and organizational culture in the pursuit of radically improved performance. *SPONSORED*

{{< sponsor-blurb >}}

## DevOps'ish Top Five from Last Week

1. [Kubernetes has a problem called etcd](https://www.reddit.com/r/kubernetes/comments/b6g90j/kubernetes_has_a_problem_called_etcd/)
1. [5 Ways to Leave Your Work Stress at Work](https://hbr.org/2019/03/5-ways-to-leave-your-work-stress-at-work)
1. [Istio monitoring explained](https://blog.giantswarm.io/Istio-monitoring-explained/)
1. [Kubernetes v1.14: What you need to know](https://developers.redhat.com/blog/2019/03/25/kubernetes-v1-14-what-you-need-to-know/)
1. [Endlessh](https://nullprogram.com/blog/2019/03/22/)

## People

[Want an awesome job, working in a great team, with a tremendous leader?](https://social.icims.com/viewjob/pt1553611085158445da) — If you're in Europe and want to work on the Ansible team with other fellow Red Hatters. This is the job for you (maybe)!

[Sonatype, Senior Technical Ambassador, DevOps Community](https://jobs.lever.co/sonatype/eb80a45e-dd73-4cc2-beae-58f2d4b937b2) — My friends at Sonatype are looking for an awesome DevOps person to talk about their great products and practices.

[Please Vote for Command Line Heroes in the Webby Awards](https://vote.webbyawards.com/PublicVoting/#/2019/podcasts/features/best-branded-podcast-or-segment) — Command Line Heroes is a podcast produced by my employer, Red Hat, but, it's definitely not sales pitchy (at all). I have friends that have appeared on the podcast and just last week I sat here in my office with a producer and recorded for an episode. Please take the time to vote. Thank you!

[Verify @ashleymcnamara](https://chrisshort.net/verify-ashleymcnamara/) — A lot of people were asking about *认证 @ashleymcnamara* so I had to write a thing. In a nutshell, it's Twitter being hypocritical as usual. IT'S NOT DIRECTLY DEVOPS RELATED. However, it is DevOps adjacent, as our network is engaging on Twitter. According to one Twitter engineer not at liberty to discuss the matter fearing retribution, the verified account program, "is still on hold." But, confirmed someone is in charge of the program despite being on hold for two years. When pressed on [a celebrity's baby being verified](https://slate.com/technology/2018/05/you-cant-get-verified-on-twitter-anymore-but-serena-williams-baby-can.html), the engineer reminded me, "[Twitter] reserves the right to continue to verify on a case by case basis." I don't feel like I need to make a case for Ashley, Twitter. Verify her and every other woman in tech like her that have applied (like [Emily Freeman](https://twitter.com/editingemily/)). It's called goodwill after being a shitty platform.

[10 signs of emotionally intelligent teams](https://enterprisersproject.com/article/2019/4/emotional-intelligence-teams-signs) — "Does your team show strong or weak emotional intelligence? Here’s how to gauge and improve your team’s EQ"

[IBM Again Faces Allegations of Targeting Older Workers in Layoffs](https://spectrum.ieee.org/view-from-the-valley/at-work/tech-careers/ibm-again-faces-allegations-of-targeting-older-workers)

[Intel lays off hundreds of tech administrators](https://www.oregonlive.com/silicon-forest/2019/03/intel-lays-off-hundreds-of-tech-administrators.html) — "The layoffs numbered in the hundreds, according to people with direct knowledge of the cuts who asked not to be identified because they were not authorized to speak about their employer."

[These 5 Skills Are Critical for Success and Career Advancement](https://www.entrepreneur.com/article/330080) — People skills play a huge role in your success.

[‘Developers’ lives matter’ – Chinese software engineers use Github to protest against the country’s 996 work schedule](https://www.scmp.com/tech/start-ups/article/3003691/developers-lives-matter-chinese-software-engineers-use-github)

## Process

[Take the Accelerate State of DevOps survey today!](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5) — Can you spare some time to help the DORA research team know what it takes to make great software?

[We Built A Broken Internet. Now We Need To Burn It To The Ground.](https://www.buzzfeednews.com/article/mikemonteiro/we-built-a-broken-internet-now-we-need-to-burn-it) — In an edited extract from his upcoming book [Ruined by Design](https://devopsi.sh/46ec0), Silicon Valley veteran Mike Monteiro explains how designers destroyed the world.

[Derek the DevOps Dinosaur](https://medium.com/@springdo/derek-the-devops-dinosaur-f9ece02030ad) — My level of animation to explain DevOps in a very consumable way. Bravo, Donal.

[Disclosing a directory traversal vulnerability in Kubernetes copy - CVE-2019-1002101](https://www.twistlock.com/labs-blog/disclosing-directory-traversal-vulnerability-kubernetes-copy-cve-2019-1002101/) — "This post explains the discovery process, the vulnerability details and its impact and exploitation methods."

[Oncall of Duty](https://www.dorothyjung.com/oncall-game/)

[Turns out Amazon buying Eero wasn’t the startup success story we thought](https://www.theverge.com/2019/4/5/18297619/amazon-eero-price-fire-sale-mesh-wi-fi-buyout) — Eero was in deep shit apparently.

[Google’s constant product shutdowns are damaging its brand](https://arstechnica.com/gadgets/2019/04/googles-constant-product-shutdowns-are-damaging-its-brand/) — Google would kill its own grandmother.

[How To Establish a High Severity Incident Management Program](https://www.gremlin.com/community/tutorials/how-to-establish-a-high-severity-incident-management-program/) — "In this guide, we will share how to establish and measure the success of your own high severity incident management program."

[Managing Documentation at Scale](https://engineering.linkedin.com/blog/2019/04/managing-documentation-at-scale)

## Tools

[Linux Observability with BPF](https://learning.oreilly.com/library/view/linux-observability-with/9781492050193/) — "Want to master the BPF virtual machine in the Linux Kernel? This practical guide shows you how to write applications that use BPF to observe and modify the kernel’s behavior on demand—without having prior knowledge of Linux Kernel development."

[We deployed Envoy Proxy to make Monzo faster](https://monzo.com/blog/2019/04/03/deploying-envoy-proxy/) — "We eventually settled on Envoy because of its high performance capabilities, relative maturity, and wide adoption in large engineering teams and projects."

[Envoy Proxy — high severity vulnerabilities that can lead to exposure of unauthorized services.](https://medium.com/solo-io/envoy-proxy-high-severity-vulnerabilities-that-can-lead-to-exposure-of-unauthorized-services-e5af25b022de) — Speaking of Envoy 👀🚨

[The Road to an Envoy Service Mesh](https://medium.com/square-corner-blog/the-road-to-an-envoy-service-mesh-d1a51cbd31dd) — "In this post I’ll talk about how Square has handled this in the past and where we’re at today — actively migrating towards a full service mesh."

[Reducing sysadmin toil with Kubernetes controllers](https://opensource.com/article/19/3/reducing-sysadmin-toil-kubernetes-controllers) — Controllers can ease a sysadmin's workload by handling things like creating and managing DNS addresses and SSL certificates.

[kube-proxy Subtleties: Debugging an Intermittent Connection Reset](https://kubernetes.io/blog/2019/03/29/kube-proxy-subtleties-debugging-an-intermittent-connection-reset/)

[Sticky Sessions in Kubernetes](https://medium.com/@zhimin.wen/sticky-sessions-in-kubernetes-56eb0e8f257d) — "Sometimes, we still need the session affinity or sticky session for the request to come to the same pod replica that was responding to the request before."

[CNCF to Host Open Policy Agent (OPA)](https://www.cncf.io/blog/2018/03/29/cncf-to-host-open-policy-agent-opa/) — "The Open Policy Agent (OPA) is an open source, general-purpose policy engine that enables unified, context-aware policy enforcement across the entire stack."

[9 open source tools for building a fault-tolerant system](https://opensource.com/article/19/3/tools-fault-tolerant-system) — Maximize uptime and minimize problems with these open source tools.

[Announcing FireHydrant, a tool to manage incidents](https://www.firehydrant.io/blog/announcing-firehydrant-a-tool-to-manage-incidents/) — "FireHydrant delivers a modern incident management process that will automate and apply industry best-practices allowing your team to put out fires faster, learn from your incidents, and focus on preventing them in the future."

[terraform-provider-dominos](https://ndmckinley.github.io/terraform-provider-dominos/) — "[E]ven though it’s a joke it will still order you a pizza. You are going to get a pizza. You should be careful with this provider, if you don’t want a pizza." Storing my credit card info in Vault seems natural now.

[valeriansaliou/sonic](https://github.com/valeriansaliou/sonic) — 🦔 Fast, lightweight & schema-less search backend. An alternative to Elasticsearch that runs on a few MBs of RAM.

[xyproto/algernon](https://github.com/xyproto/algernon) — Small self-contained pure-Go web server with Lua, Markdown, HTTP/2, QUIC, Redis and PostgreSQL support

[regner/gssh](https://github.com/regner/gssh) — A utility to make SSHing with the gcloud SDK easier and enjoyable

[vinyldns/vinyldns](https://github.com/vinyldns/vinyldns) — Vendor agnostic DNS front-end for streamlining DNS operations and enabling self-service for your DNS infrastructure

[cue](https://cue.googlesource.com/cue) — "Configure, Unify, Execute. CUE is an open source data constraint language which aims to simplify tasks involving defining and using data. It is a superset of JSON, allowing users familiar with JSON to get started quickly."

[zeromake/docker-debug](https://github.com/zeromake/docker-debug) — Use new container attach on already container go on debug

## DevOps'ish Tweet of the Week

{{< tweet 1113239960348499968 >}}