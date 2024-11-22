+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2022"]
date = 2022-09-11
description = ["9/11/01, Cloudflare drops KiwiFarms, Seekable OCI, A Sequel to SQL, SSD Pricing Could Tumble, and so much more"]
draft = false
slug = "284"
tags = ["http", "argo", "cloud", "cloud native", "open source", "service", "Kubernetes", "Apple", "computing", "container", "Cloudflare", "SOCI", "internet", "DevOps", "globalstar", "git", "iPhone", "eBPF"]
title = "DevOps'ish 284: 9/11/01, Cloudflare drops KiwiFarms, Seekable OCI, A Sequel to SQL, SSD Pricing Could Tumble, and so much more"
+++

9/11/01... 21 years later, it's still not easy. I still get goosebumps at the thought of it. The sight of the date at the US Open women's final was a jarring reminder I wasn't going to get through this weekend without the utmost mental focus. Today is hard for a lot of people for a lot of reasons. I'm not going to let it ruin my day. This is the first 9/11 that all the perpetrators have been either captured or killed. We've reached this critical point in history where I feel things easing, just a little, around this day. My heart goes out to the families of those lost on 9/11 and the US-led wars afterward. Today especially, be kind.

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**Deserted Island DevOps 2022**](https://desertedislanddevops.com/?utm_source=devopsish)

SEPTEMBER 14-15, Live on Twitch from Mackinac Island, Michigan

This year we're expanding our schedule to two days of streaming, and bringing our speakers together to deliver their talks. What does that mean to you? More great talks, with better production values, and new talk types! We're excited to welcome you back to our Deserted Island this September 14th and 15th!

[**ArgoCon**](https://events.linuxfoundation.org/argocon/?utm_source=devopsish)

SEPTEMBER 19 – 21, 2022

ArgoCon is designed to foster collaboration, discussion, and knowledge sharing on the Argo Project, which consists of four projects: Argo CD, Argo Workflows, Argo Rollouts, and Argo Events. This event is aimed at audiences that are new to Argo as well as providing depth to those currently using Argo within their organization. Connect with others that are passionate about Argo and interact with project maintainers. Learn from practitioners about pitfalls to avoid and best practices on how to adopt Argo in your cloud native environment. Get inspired by and provide input to Argo leads on project roadmaps.

[**eBPF Summit**](https://ebpf.io/summit-2022/?utm_source=devopsish)

SEPTEMBER 28 - 29, 2022

eBPF Summit is a virtual event, targeted at DevOps, SecOps, platform architects, security engineers, and developers. Register to save the date and stay updated on event information.

[**Kubernetes Contributor Summit North American 2022**](https://www.kubernetes.dev/events/2022/kcsna/cfp/)

Day 0 KubeCon

Submissions should be applicable for members of one of the Kubernetes orgs, especially if you’re making a change this cycle that affects multiple SIGs or have a topic that would be useful for the entire group

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

## People

[Cloudflare drops KiwiFarms](https://www.washingtonpost.com/technology/2022/09/03/cloudflare-drops-kiwifarms/)  
Joseph Menn and Taylor Lorenz, The Washington Post  
"Company's CEO says the firm had detected imminent threats and that law enforcement could not keep up with them"

[An interview with Ukrainian hacker 'Herm1t' on countering pro-Kremlin attacks](https://therecord.media/an-interview-with-ukrainian-hacker-herm1t-on-countering-pro-kremlin-attacks/)  
Dmitry Smilyanets, The Record by Recorded Future  
When wars are fought in cyberspace, regular citizenry can become regular armies destined to waage asymmetric warfare against any enemy.

[Internet service providers drop challenge of privacy law](https://apnews.com/article/technology-lawsuits-united-states-maine-data-privacy-9b2a40a18839c16df732368ee04ea856)  
Patrick Whittle, AP News  
"Maine created one of the toughest rules in the nation for internet service providers in 2020 when it began enforcing an “opt-in” web privacy standard. The law stops the service providers from using, disclosing, selling or providing access to customers’ personal information without permission."

[After self-hosting my email for twenty-three years I have thrown in the towel. The oligopoly has won](https://cfenollosa.com/blog/after-self-hosting-my-email-for-twenty-three-years-i-have-thrown-in-the-towel-the-oligopoly-has-won.html)  
Carlos Fenollosa  
I'm surprised the complexity of running your own mail server hadn't doomed Carlos sooner. I don't neccesarily agree with the take here. But, running your own mail is next to impossible nowadays and I do not recommend anyone do it. Hell, making delivery work WITH Gmail or Apple's help is not for the faint of heart. Why? SPF, DKIM, and DMARC.

[NSA official: 'Open society' keeps US ahead on cybersecurity, technology](https://therecord.media/nsa-official-open-society-keeps-us-ahead-on-cybersecurity-technology/)  
Martin Matishak, The Record by Recorded Future  
"The U.S. and its democratic allies 'enjoy things that cannot be replicated easily in autocratic societies,' George Barnes, NSA’s deputy director, said during the Billington Cybersecurity Summit in Washington, D.C."

[The New Rules of Work Clothes](https://hbr.org/2022/09/the-new-rules-of-work-clothes)  
Allison Shapira, Harvard Business Review  
In case your leadership hasn't gotten the memo.

## Process

[Virginia has more datacenter capacity than Europe or China](https://www.theregister.com/2022/09/08/virginia_datacenter_alley_capacity)  
Dan Robinson, The Register  
One of those jaw dropping realities; datacenter alley is DENSE.

[Netflix looks to control cloud computing costs with AWS - WSJ](https://www.reuters.com/technology/netflix-looks-control-cloud-computing-costs-with-aws-wsj-2022-09-07/)  
Reuters  
"Netflix is trying to better control rising cloud computing costs with longtime cloud partner Amazon Web Services as part of its efforts to reduce total expenses, the Wall Street Journal reported on Wednesday, citing people familiar with that work." All that custom built software...

[I ran the worlds largest DDoS-for-Hire empire and CloudFlare helped](https://rasbora.dev/blog/I-ran-the-worlds-largest-ddos-for-hire-empire-and-cloudflare-helped)  
Rasbora  
"As the operator of the largest DDoS-for-Hire empire in the history of the internet, I have a unique perspective on the situation CloudFlare finds themselves in."

[What happened with CentOS will not happen with Rocky Linux: Kurtzer](https://www.itworldcanada.com/article/what-happened-with-centos-will-not-happen-with-rocky-linux-kurtzer/501239)  
Paul Barker, IT World Canada News  
"The rules are so iron-clad that even the new organization that Kurtzer is co-founder and CEO of, CIQ, would never be able to gain ownership of Rocky Linux."

[New NSA, CISA, ODNI best practices for securing the open source software supply chain](https://blog.tidelift.com/new-nsa-cisa-odni-best-practices-for-securing-the-open-source-software-supply-chain)  
Donald Fischer, Tidelift  
"While the report highlights several roles for software-only point solutions, the bigger picture it paints is that organizations fundamentally need a comprehensive strategy and process for managing open source, including active engagement of software suppliers—which in the case of open source, means the independent community maintainers behind so many of the projects we rely on."

## Tools

[Introducing Seekable OCI for lazy loading container images](https://aws.amazon.com/about-aws/whats-new/2022/09/introducing-seekable-oci-lazy-loading-container-images/)  
"Seekable OCI (SOCI) is a technology open sourced by AWS that enables containers to launch faster by lazily loading the container image. SOCI works by creating an index (SOCI Index) of the files within an existing container image. This index is a key enabler to launching containers faster, providing the capability to extract an individual file from a container image before downloading the entire archive."

[A Sequel to SQL? An introduction to Malloy](https://carlineng.com/?postid=malloy-intro#blog)  
Carlin Eng  
"SQL is still the primary user interface by which most data professionals interact with their raw materials. The underlying technologies have improved immeasurably, but aside from a handful of updates to the ANSI standard, the core of the language remains untouched. It’s practically a miracle that after 40+ years of use by countless data professionals, our interface to data is effectively the same."

[http://http://http://@http://http://?http://#http://](https://daniel.haxx.se/blog/2022/09/08/http-http-http-http-http-http-http/)  
Daniel Stenberg  
"http://http://http://@http://http://?http://#http://" is a legitimate URL.

[Kubernetes 1.25: KMS V2 Improvements](https://kubernetes.io/blog/2022/09/09/kms-v2-improvements/)  
Anish Ramasekar, Rita Zhang, Mo Khan, and Xander Grzywinski (Microsoft)  
"With Kubernetes v1.25, SIG Auth is introducing a new `v2alpha1` version of the Key Management Service (KMS) API. There are a lot of improvements in the works, and we're excited to be able to start down the path of a new and improved KMS!"

[California Flex Alert: Blackouts May Have Been Averted by a Timely Mobile Text](https://www.bloomberg.com/news/articles/2022-09-07/a-text-alert-may-have-saved-california-from-power-blackouts#xj4y7vzkg)  
Dan Murtaugh and Brian Eckhouse, Bloomberg  
"A timely mobile alert may have prevented hundreds of thousands of Californians from being plunged into darkness in the middle of a heat wave Tuesday night."

[Apple picks Globalstar for emergency satellite service on iPhone 14](https://www.reuters.com/technology/apple-picks-globalstar-satellite-service-iphone-14-series-2022-09-07/)  
Reuters
The sole reason I want everyone in my family to have an iPhone 14. "While Apple will pay for 95% of the approved capital expenditure for the new Globalstar satellites needed to support the service, Globalstar said it would still need to raise additional debt to construct and deploy the satellites." Also, this is how Apple gets into the satellite business.

[Apple A16 Bionic SoC to Power iPhone 14 Pro](https://www.tomshardware.com/news/apple-a16-bionic-soc-to-power-iphone-14-pro)  
Andrew E. Freedman, Tom's Hardware  
Iterative update but, these Apple silicon Arm designs blow my mind.

[Fossil: Fossil Versus Git](https://www.fossil-scm.org/home/doc/trunk/www/fossil-v-git.wiki)  
There are better tools than git and GitHub out there. They just don't have wide adoption.

[Git Cheatsheet](https://dev.to/sarath_pm/git-cheatsheet-414e)  
Sarath P M  
I'm a sucker for a good cheatsheet.

[SSD Pricing Could Tumble as NAND Prices Predicted to Drop by 35%](https://www.tomshardware.com/news/ssd-pricing-could-tumble-as-nand-prices-predicted-to-drop-by-35)  
Mark Tyson, Tom's Hardware  
Too bad I need storage NOW.

## DevOps'ish Post of the Week

[![Ryan Castellucci on Twitter: "Much of hacking is about understanding systems better than those who built them, and using that knowledge to do what is supposed to be 'impossible'.")](https://shortcdn.com/devopsish/284-devopsish-post-of-the-week.webp)](https://twitter.com/ryancdotorg/status/1025899351262941184?utm_source=devopsish)

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/284/notes.md?utm_source=devopsish)
