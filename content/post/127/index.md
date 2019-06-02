+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-05-12T07:00:00Z
description = "Mother's Day, What is DevOps, DevOps is Dead, 1:1s, Oracle Oracling, UBI, KEDA, terraformer, and More"
draft = false
slug = "127"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "container", "security", "linux", "infrastructure", "git", "GitHub", "event driven", "UBI", "KEDA", "Oracle", "Windows", "Mother's Day"]
title = "127: Mother's Day, What is DevOps, DevOps is Dead, 1:1s, Oracle Oracling, UBI, KEDA, terraformer, and More"

+++

Happy Mother's Day! To the single moms, this day should be yours two times over. I'm sorry if you don't even get so much as a bathroom break to yourself today. To the almost moms, this day is yours. Don't let anyone tell you otherwise; if they do, send them my way. To the moms that have lost a child, this day is especially yours. For those of us whose toxic moms have been extricated from our lives, this day might be a little heavier. That's okay too; do what you need to do. No one says you can't celebrate someone else's awesome mom either. For example, Emily Freeman's mom is the human embodiment of DevOps, honor her. Regardless, I hope everyone has a marvelous Mother's Day.

[**Ready for your dream tech job?**](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email3)  
Say goodbye to tech recruiter spam. Indeed Prime matches you with companies that fit your career goals and sends jobs right to your inbox. You'll also have free access to technical career coaches who are here to help you with interview tips, resume best practices and more. [Join for free today](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email3)! *SPONSORED*

[**2019 State of Multicloud**](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE)  
A Report on the Underlying Dynamics Fueling Multicloud Strategies. [Download Today!](https://turbonomic.com/state-of-multicloud/?utm_campaign=7012o000001oRz6AAE) *SPONSORED*

[**How companies adopt and apply cloud native infrastructure--from O'Reilly**](https://www.oreilly.com/pub/cpc/224549)  
Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud. *SPONSORED*

{{< sponsor-blurb >}}

## DevOps'ish Last Week's Top Five

1. [Many Kubernetes Clusters](https://srcco.de/posts/many-kubernetes-clusters.html)
1. [You should have a personal web site](https://writing.markchristian.org/2019/04/29/personal-web-sites/)
1. [Sherlock changelog](https://news.sherlock.stanford.edu/posts/when-setting-an-environment-variable-gives-you-a-40-x-speedup)
1. [Brand loyalty: Red Hat employees permanently inked with new company logo](https://www.wraltechwire.com/2019/05/02/brand-loyalty-red-hat-employees-permanently-inked-with-new-company-logo/)
1. [Grafana Dashboards for Kubernetes Administrators](https://povilasv.me/grafana-dashboards-for-kubernetes-administrators/)

## People

[Dear Hollywood, here are 5 female founders to showcase instead of Elizabeth Holmes](https://techcrunch.com/2019/05/03/dear-hollywood-here-are-five-female-founders-to-showcase-instead-of-elizabeth-holmes/) — I'd rather watch a movie about the five women in this article than anything about Elizabeth Holmes.

[Do These 5 Emotionally Intelligent Things Within 5 Minutes Of Meeting](https://www.fastcompany.com/40441365/do-these-5-emotionally-intelligent-things-within-5-minutes-of-meeting-someone) — This list is good. Hell, if you hit three of the five you're doing great, especially #5.

[How to Stop Worrying About What Other People Think of You](https://hbr.org/2019/05/how-to-stop-worrying-about-what-other-people-think-of-you) — In this line of work, personality matters. "If you start paying less and less attention to what makes you *you* — your talents, beliefs, and values — and start conforming to what others may or may not think, you'll harm your potential."

[10 Mistakes You Should Avoid During Your One on One Meetings](https://www.fellow.app/blog/2019/10-mistakes-you-should-avoid-during-one-on-one-meetings/) — This list is pretty crucial. If you have a not so great manager, try to use this to help guide the discussion during 1:1s.

[How I became a Technology Advocate](https://kenmugrage.com/2019/05/09/how-i-became-a-technology-advocate/) — My friend, Ken Mugrage, explains how he started doing what he does.

[DevOps'ish Telegram](https://devopsi.sh/telegram) — Join the over 230+ DevOps, Kubernetes, SRE, and other technology professionals discussing real-world problems, breaking technology events and outages, and the occasional Spotify playlist.

## Process

[What is DevOps](https://devopsish.com/what-is-devops/) — "If forced to put it in one sentence, I would describe DevOps as follows: 'DevOps is the professional practice of frequent, continued, and iterative improvements through measurable changes, the goal of which is to become a high-velocity organization thus improving business outcomes.'" [Tell me I'm wrong](https://twitter.com/ChrisShort).

[DevOps is Dead with James Turnbull](https://www.realworlddevops.com/episodes/devops-is-dead-with-james-turnbull) — "I mean I'm being honest here on marketing now I think it's probably a factor. To me, DevOps was almost nothing about tools, tools to me were enablers for folks doing DevOps things." Says the gentleman hailing from a company with 'Azure DevOps' as a product. Is it fall? Can someone get me a pumpkin spice latte, please? I... Can't... Even. That's why **tools** are LAST in this newsletter. That's why **people** are first and **process** is right after. Those two things matter more to DevOps than any single tool ever could attempt to. This is why in my end of 2018 article, *Less DevOps, More Everything That Makes Up DevOps*, was a headline. No one wants DevOps, but they do want all the outcomes. *What DevOps Isn't* is a headline in the aforementioned [What is DevOps](https://devopsish.com/what-is-devops/) for good reason too. I don't think Marketing is the issue with DevOps. I have spent time on both sides of the tables now. I feel the lack of clarity about what DevOps actually is from its leaders and founders is what lead us here. Welcome to the trough of disillusionment.

[Oops, We Forgot to Build a Managed Kubernetes Service!](https://www.packet.com/blog/oops-we-forgot-to-build-a-managed-kubernetes-service/) — There is something to be said about pragmatism and sticking to core competencies while a clear path is laid out for you.

[MITRE ATT&CK framework for container runtime security with Sysdig Falco](https://sysdig.com/blog/mitre-attck-framework-for-container-runtime-security-with-sysdig-falco/) — "MITRE ATT&CK is a comprehensive knowledge base and complex framework of over 200 techniques that adversaries may use over the course of an attack."

[How to Use Gitleaks to Prevent Pushing Sensitive Info](https://medium.com/@umutseven/how-to-use-gitleaks-to-prevent-pushing-sensitive-info-cdd0355d5f61)

[13-year old hacks drone to prove cyber attack risk](https://www.washingtonpost.com/video/business/technology/13-year-old-hacks-drone-to-prove-cyber-attack-risk/2019/05/03/181d7197-39ee-493d-8133-6b33e461caf3_video.html) — "A teenage boy successfully hacked a common drone in a stunt aimed at showing how vulnerable web-connected devices and the Internet of Things are to attacks."

[Department of Justice approves $34B IBM acquisition of Red Hat](https://www.wraltechwire.com/2019/05/06/department-of-justice-approves-34b-ibm-acquisition-of-red-hat/) This has been added to the [DevOps'ish IBM Red Hat Acquisition Index](https://devopsish.com/ibm-red-hat-acquisition-index/).

[Negotiations Failed: How Oracle killed Java EE](https://headcrashing.wordpress.com/2019/05/03/negotiations-failed-how-oracle-killed-java-ee/) — "Hence, it not only was inacceptable, but it was simply impossible to agree to Oracle's requests, so the negotiations more or less completely failed."

[Uber Among Worst Big Tech IPOs In A Decade](https://www.forbes.com/sites/rachelsandler/2019/05/10/uber-among-worst-big-tech-ipos-in-a-decade/#22761729480d) — Ouch.

[Slack says director made "unauthorized statements" about firm](https://www.businessinsider.com/slack-director-sec-quiet-period-2019-5) — Quiet periods are a real thing.

## Tools

[Aqua Operator: Automating Security for Kubernetes](https://blog.aquasec.com/aqua-security-kubernetes-operators) — A group of controllers that runs within a Kubernetes or Openshift cluster that provides a means to deploy and manage Aqua Security

[Kubernetes Universal Declarative Operator (KUDO)](https://kudo.dev/) — "Kubernetes Universal Declarative Operator (KUDO) provides a declarative approach to building production-grade Kubernetes Operators. It is an operator that is specifically designed to help provide operations to operators."

[10 Most Interesting Announcements From Microsoft Build](https://www.forbes.com/sites/janakirammsv/2019/05/07/10-most-interesting-announcements-from-microsoft-build/#23559f84531f) — A nice, concise list.

[Coming soon: Windows Terminal—finally a tabbed, emoji-capable Windows command-line](https://arstechnica.com/gadgets/2019/05/coming-soon-windows-terminal-finally-a-tabbed-emoji-capable-windows-command-line/) — The really sad part is Windows users haven't had emoji on the CLI all this time. In all seriousness, this is great for Windows users.

[Introducing the Red Hat Universal Base Image](https://www.redhat.com/en/blog/introducing-red-hat-universal-base-image) — "Less than a full operating system, UBI is three things: 1. A set of three base images (ubi, ubi-minimal, ubi-init) 2. A set of language runtime images (nodejs, ruby, python, php, perl, etc.) 3. A set of associated packages in a YUM repository which satisfy common application dependencies. Freely redistributable for community, partners and customers." Kick the tires on this. I'm genuinely curious what folks think.

[Anchore Enterprise 2.0 is Now Built on the Red Hat Universal Base Image](https://anchore.com/anchore-enterprise-2-0-is-now-built-on-the-red-hat-universal-base-image/)

[Container misconceptions](https://blog.bejarano.io/container-misconceptions.html) — "TL;DR: containers are not VMs; stop calling everything "Docker"; don't use Kubernetes for tiny projects, use Swarm instead; Kubernetes will only solve your org's problems if you are willing to go all-in, anything in between will fail the same way it failed before."

[Using Kind to test a pr for Kubernetes.](https://mauilion.dev/posts/kind-k8s-testing/)

[kedacore/keda](https://github.com/kedacore/keda) — KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes

[monzo/response](https://github.com/monzo/response) — Monzo's real-time incident response and reporting tool

[muesli/beehive](https://github.com/muesli/beehive) — A flexible event/agent & automation system with lots of bees 🐝

[siggy/itermkube](https://github.com/siggy/itermkube) — Kubernetes Context in iTerm2's Status Bar

[GoogleCloudPlatform/terraformer](https://github.com/GoogleCloudPlatform/terraformer) — CLI tool to generate terraform files from existing infrastructure (reverse Terraform). Infrastructure to Code

## DevOps'ish Tweet of the Week

{{< tweet 1127295228854063104 >}}