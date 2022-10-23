+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-09-27T07:00:00Z
description = "COVID-19 hits too close to home, Kubernetes Contributor site, Accurics, OpenShift TV, dangers of averages, and more"
draft = false
slug = "185"
tags = ["Kubernetes Contributors", "Kubernetes", "DevOps", "DevSecOps", "open source", "AWS", "Microsoft", "Microsoft Windows", "cloud", "cloud native", "security", "community", "observability", "o11y", "build", "systems", "culture", "tools", "Crunchy Data", "postgresql", "Todoist", "Linkerd", "privacy", "Northvile", "Kubernetes SIGs", "averages", "practices", "Snyk", "network", "secure", "SNS", "kustomize", "RAID10", "Trello", "Mozilla", "Accurics", "StackRox", "Honeycomb", "Netflix", "Social Dilemma", "Blacklight", "COVID-19", "Docker"]
title = "DevOps'ish 185"

+++

My daughter just informed me she very likely has contracted COVID-19. My apologies but, I'm going to forgo my usual introduction in the newsletter this week.

I was going to discuss this lengthy piece but, give it a read instead: [The Developer-Led Landscape](https://tylerjewell.substack.com/p/the-developer-led-landscape-20-08-28).

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

## People

[Kubernetes Contributors](https://www.kubernetes.dev/)  
"It is intended to be the hub for all things related to the Kubernetes Contributor experience. Who exactly is a contributor? We all are - Whether you’re writing docs, reviewing code, participating in the community and its many [Special Interest Groups] SIGs, everyone is welcome. We hope this site will be a pathway to success for our 35000+ Kubernetes contributors, providing current, up-to-date information on community events, contributor resources, Kubernetes SIGs, and more."

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[The Social Dilemma](https://www.netflix.com/title/81254224)  
A must watch Netflix documentary for everyone in or using tech.

[This Past Week on OpenShift TV](https://www.openshift.com/blog/this-past-week-on-openshift-tv)  
My life at $job in a synopsis blog post.

[DevOps 049: DevOps, Open Source, and OpenShift with Chris Short](https://devchat.tv/adventures-in-devops/devops-049-devops-open-source-and-openshift-with-chris-short/)  
Talking about my day-to-day activities to pay the bills and give back somehow.

[These Chrome extensions protect you against creepy web tracking](https://www.wired.co.uk/article/chrome-extensions-privacy-ad-tracking-blocker)  
[Privacy Badger](https://privacybadger.org/) is a Godsend. There is also [Blacklight](https://themarkup.org/blacklight) if you want to inspect a site before visiting.

[Family of Northville man killed in hit and run increases reward to $15,000](https://www.fox2detroit.com/video/853147?fbclid=IwAR3Pf_81Cd0dKL_wqyNF-hDLiuTEyKcsdyikzZ3e6CKtLKtZGtnesVNSwrg)  
A tragic story impacting a friend of one of my teammates (who happens to live here in Michigan). If you know something, please contact the Northville PD at 248-349-5100. Thank you.

## Process

[Crunchy HA PostgreSQL - Ensure your data is always available](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week4&utm_campaign=CrunchyHA2)  
Meet your "always on" data requirements with trusted, open source components. Crunchy HA PostgreSQL gives you an all-in-one production PostgreSQL solution: HA, DR, monitoring that is securely deployed. Chat with Crunchy Data to [learn more](https://www.crunchydata.com/products/crunchy-high-availability-postgresql/?utm_source=DevOpsish&utm_medium=Week4&utm_campaign=CrunchyHA2). *SPONSORED*

[Microsoft warns hackers are actively targeting Zerologon vulnerability. Patch pronto!](https://grahamcluley.com/microsoft-warns-hackers-are-actively-targeting-zerologon-vulnerability-patch-pronto/)  
This is being called the worst bug in Windows history. Like, I don't know how much more fucking terrified into patching your systems you should be but, if you haven't patched your systems by the time you're reading this, you've got some serious explaining to do.

[Don't Compare Averages](https://martinfowler.com/articles/dont-compare-averages.html)  
Comparing averages or even [trying to determine an average in some cases](https://www.thestar.com/news/insight/2016/01/16/when-us-air-force-discovered-the-flaw-of-averages.html) (if you've never read this piece you should) can be a horrible, no good, awful practice.

[10 Best Practices Worth Implementing to Adopt Kubernetes](https://containerjournal.com/topics/container-management/10-best-practices-worth-implementing-to-adopt-kubernetes/)  
Not a terrible list.

[The Windows XP source code was allegedly leaked online](https://www.bleepingcomputer.com/news/microsoft/the-windows-xp-source-code-was-allegedly-leaked-online/)  
The next few weeks should be interesting in terms of low level Windows things being discovered. Of course, now that it's leaked, can we actually use it in any other application ever? What if there are bits in here that aren't licensed properly and invoke lawsuits? What if it somehow exposes a monopolistic plot? Who knows what'll happen! 🍿🍿🍿🍿🍿

[Snyk Acquires DeepCode to Apply AI to DevSecOps](https://devops.com/snyk-acquires-deepcode-to-apply-ai-to-devsecops/)  
It's my understanding that Snyk is or at least was in a hardcore acquisition mode.

[Why Magic Leap Failed: AR Hype Exceeded Product's Capabilities](https://www.bloomberg.com/news/features/2020-09-23/why-magic-leap-failed-ar-hype-exceeded-product-s-capabilities)  
Next time, call me before you spend over $10 million on something. I'll tell you if it's legit or not for $250K. Dead serious.

## Tools

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsish&LSource=DevOpsish) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[fatal: coudn't find remote ref master · Issue #55 · openshift-evangelists/kbe](https://github.com/openshift-evangelists/kbe/issues/55)  
Ryan Jarvinen teaches me how to sanely go about renaming my default branches.

[I'm losing trust in AWS. SNS is broken for 24 days.](https://cloudonaut.io/loosing-trust-in-aws-sns-broken-for-24-days/)  
"I'm frustrated. A major service of AWS is broken for 24 days. The Simple Notification Service (SNS) delivers messages to HTTPS subscriptions with a delay of more than 30 minutes. That issue impacts our SaaS business. But AWS did not fix the problem yet and did not even reveal an ETA for resolving the issue." And no one I reached out to at AWS has said a damn thing in response to me. Not a good look, y'all.

[Rebuilding Linkerd's continuous integration (CI) with Kubernetes in Docker (kind) and GitHub Actions](https://buoyant.io/2020/09/16/linkerds-ci-kubernetes-in-docker-github-actions/)  
"This post will detail Linkerd's CI journey from a single, persistent Kubernetes cluster to theoretically unlimited one-off kind clusters. This journey includes a few detours on what patterns and tools worked well (and not so well) for Linkerd's use case."

[YAML Templating Solutions: Helm & Kustomize](https://www.dex.dev/dex-videos/templating-solutions)  
Writing config files by hand is like coding with Notepad instead of an IDE. Let's find a better way, and take an overview of the popular solutions Helm & Kustomize.

[Meet the ‘DPU' - accelerated network cards designed to go where CPUs and GPUs can't be bothered](https://www.theregister.com/2020/09/25/smartnic_dpu/)  
General purpose processors are going to start becoming userland in a hurry. With the shot in the Arm Nvidia has, there'll be single purpose chips, ASICs, and FPGAs like we've never thought or heard of before raining from the heavens.

[Linux 5.10 To See RAID10 DISCARD Improvement - From 259 Seconds To Less Than 1 Second](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.10-Faster-RAID10-Trim)  
As a RAID 10 user, I *really* like the sound of that.

[10 Best Open Source Static Site Generators [2020]](https://itsfoss.com/open-source-static-site-generators/)
The annual reminder that static web sites are within your reach and that [you shouldn't use Medium](https://nomedium.dev/) (which I'll remind you about often).

[Todoist takes a shot at Trello with Kanban-style ‘boards’](https://thenextweb.com/plugged/2020/09/23/todoist-takes-a-shot-at-trello-with-kanban-style-boards/)  
Todoist just murdered Trello with a throat slit in the dark of night, in my opinion. I went Pro on Todoist the second the board feature went into beta. It's life changing.

Two bad things about Mozilla this week:  
* [Firefox usage is down 85% despite Mozilla's top exec pay going up 400%](http://calpaterson.com/mozilla.html)  
* [Killed by Mozilla](https://killedbymozilla.com/)

[couler-proj/couler](https://github.com/couler-proj/couler)  
Unified Interface for Constructing and Managing Workflows on different workflow engines, such as Argo Workflows, Tekton Pipelines, and Apache Airflow.

[jetstack/version-checker](https://github.com/jetstack/version-checker)  
Kubernetes utility for exposing image versions in use, compared to latest available upstream, as metrics.

[polyaxon/polyaxon](https://github.com/polyaxon/polyaxon)  
Machine Learning Platform for Kubernetes

## DevOps'ish Tweet of the Week

{{< tweet 1306585313586761729 >}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/185/notes.md) to see what didn't make it to the newsletter.

