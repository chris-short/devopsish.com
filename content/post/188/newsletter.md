+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2020"]
date = 2020-10-18
description = "YAML, Kubernetes Steering Committee, BleedingTooth, ContainerDrip, TrickBot, Kubernetes, Van Halen's rider, Rust, and more"
draft = false
slug = "188"
tags = ["YAML", "Kubernetes", "DevOps", "Rust", "monitoring", "Docker", "infrastructure", "code", "build", "open source", "systems", "security", "bleedingtooth", "cloud", "cloud native", "git", "configuration", "observability", "learn", "culture", "developers", "Microsoft", "Python", "container", "thanos", "deployment", "platform"]
title = "DevOps'ish 188"

+++

[We kinda went down a rabbit hole](https://twitter.com/brunoborges/status/1315230767207784450) this week when I suggested folks check out [*yq*](https://dev.to/vikcodes/yq-a-command-line-tool-that-will-help-you-handle-your-yaml-resources-better-8j9), "The aim of the project is to be the jq or sed of yaml files." First, there's nothing wrong with this project. I like it, I find the tool useful, and that's that. But the great debate started over our lord and savior, [YAML](https://yaml.org/). Yeah, I know, XML vs. JSON vs. YAML vs. TOML vs. the next thing is a tired and old debate.

Let me level set here. I routinely joke about how I’m a “Calendar Driven YAML Engineer” and have been for years on [openshift.tv](https://openshift.tv). But I'm not too fond of YAML. Let me tell you a story...

In 2012, I worked at McClatchy Interactive (before the really dark times) and enjoyed the systems and security work I was doing. We had our machine creation down to a finite science. Bare metal spun up, you punched the MAC address into a database file, and off the machine went to get all the needed packaging and code to run as its defined purpose in our infrastructure.

[CFEngine](https://en.wikipedia.org/wiki/CFEngine) provisioned the machine accordingly based on purpose and positioned it in the network ready for code deployment. DevOps was something the company was embracing at the time. So instead of using the existing CFEngine infrastructure, the DevOps tandem at the time was using [Puppet](https://en.wikipedia.org/wiki/Puppet_(company)) for code deploys. This system worked fine until it didn't. There were clear lines between infrastructure (typical IT in the datacenter) and software deployment and configuration (developers). In our case, DevOps represented the development team more so than the Operations team. Sound familiar?

But, as you can imagine, even with all the automation in place, it was still a throw over the wall kind of scenario. When Puppet needed system packages installed because of modifications to the codebase (requiring a newer version of Perl, for example) or new services coming online using different OS packages, Puppet now had to do the task CFEngine was doing; systems management. The idea was to build an overarching WebOps team that was cross-functional, spirited, and deeply technical. The first edict laid down to the team by the DevOps lead was, "read the [YAML spec](https://yaml.org/spec/1.2/spec.html)." We were all jumping into the Puppet pool to help integrate our processes and procedures better.

"Ugh..." I thought to myself. "I have to read this horribly written spec." It was not an RFC, which I am fond of reading, but something about the YAML spec made me sad and frustrated. Syntax *really* mattered. Whitespace *really* mattered. My days in the military (which I was a mere two years removed from) taught me that rote memorization and getting humans to see the absence of something were incredibly difficult tasks. I exploited these things in my day-to-day work in the military to defeat US enemies and train US allies on how to be harder targets. I was not too fond of this non-markup language for these reasons.

It irked me that the YAML creators laid out goal #1 as "YAML is easily readable by humans." It is human-readable because you see the human-readable words in the scalars and structures, but there was something off-putting about YAML. It was a markup language claiming not to be a markup language. I held the firm belief that markup languages are supposed to make things simpler for humans, not harder (XML is the antithesis of markup languages, in my opinion).

Here I was, relatively fresh to the DevOps game, learning some core developer concepts to understand a markup language, the crux of which was two Achilles heels. I also didn't like how big, bulky, and cumbersome Puppet was to work with. But, here I was thrust headfirst into this world. Might as well make the best of it. I've since embraced YAML, but it doesn't mean I'm writing my notes in YAML format.

Close to ten years later, I see YAML in the same somewhat offputting light. It's not friendly to new people in the same sense [git](https://git-scm.com/) isn't. [Kubernetes](https://www.kubernetes.dev/) has almost abused YAML to the point that it has become a punchline. And we've stuck ourselves with it for a long time to come too. If Kubernetes is the platform of the future, that means we'll be using a spec written in 2009 well into the 2030s (and likely beyond).

I hope that a drop in replacement is possible. The fact that we need tools like [yq](https://github.com/mikefarah/yq/) does show that there is some work to be done when it comes to wrangling the YAML beast at scale. In 2009, when the latest version of the YAML spec was written, no one thought of applying pod security policies to massive Kubernetes deployments spread out across data centers the world over. Something better will come along and I hope adopting it isn't as painful as adopting YAML is.

Remember, comparing things relatively to like something (YAML vs. XML or YAML vs. JSON) completely throws out the beginner's journey. Start from the newb and go forward from there. YAML doesn't. Git doesn't. Incrementally, YAML is better than XML but, it sucks compared to something like HTML or Markdown (which I can teach to execs and children alike). Yes, balancing machine and human readability is hard. The compromises suck, but, at some point, there's enough compute to run a process to take in something 100% human-readable and make it 100% machine-readable. In the same sense that compute has become so readily available that we gzip and encrypt almost all HTTP traffic today, I hope we can do the same with systems configuration languages. Move the complexity from the human to code. Computers are better at remembering things and syntax-semantics than humans could ever hope to be.

There's always a happy medium between human and machine readability. However, I'd much rather see a human first, [80/20](https://en.wikipedia.org/wiki/Pareto_efficiency) approach here where entry-level skills can solve 80% of the markup language's use cases. That's the true nirvana, in my opinion. There will always be complexity and a need to understand the tool you're using. But, YAML gives us an example that there can and should be better things.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

Want to see your ad in DevOps'ish? Review the [newsletter sponsor](https://devopsish.com/sponsor/) page for all the details. Give the [DevOps'ish Sponsorship Prospectus](https://devopsi.sh/prospectus) a gander if you need help convincing your marketing team they should spend. *SPONSORED*

## People

One lone hero in production is not sustainable-not for you, not for high-functioning teams, and not for customers who depend on your service. Collaborate well by instrumenting observability from the very beginning, and enable more resilient teams to build more reliable systems sustainably.

In our guide, [Developing a Culture of Observability](https://info.honeycomb.io/developing-a-culture-of-observability-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=developing-a-culture-of-observability-devopsish), we lay out why o11y culture and tools go hand-in-hand. Learn how to build a culture of observability with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Announcing the 2020 Kubernetes Steering Committee Election Results](https://kubernetes.io/blog/2020/10/12/steering-committee-results-2020/)  
Congratulations to Davanum Srinivas, Jordan Liggitt, Bob Killen. May you steer us well!

[FCC changes its stance on Section 230 policy after months of Trump tweets](https://www.washingtonpost.com/technology/2020/10/16/fcc-facebook-twitter-section-230/)  
Well, this is just going to fuck things right on up.

[Five Eyes governments, India, and Japan make new call for encryption backdoors](https://www.zdnet.com/article/five-eyes-governments-india-and-japan-make-new-call-for-encryption-backdoors/)  
The assault on encryption will never stop. If you have nothing to hide then please drive around Manhattan with all your PII on display. This isn't about terrorists versus governments. This is about the right to free speech and against unreasonable searches and seizures.

[Tech Should Enable Change, Not Drive It](https://hbr.org/2020/10/tech-should-enable-change-not-drive-it)  
"Companies that place humans at the center - while leveraging technology at speed and enabling innovation at scale - accelerate the value they create in the long-term, while making strides to reframe and thrive in the future."

[Open Invention Network open-source, non-aggression patents now covers Android and exFAT.](https://www.zdnet.com/article/open-invention-network-open-source-non-aggression-patents-now-covers-android-and-exfat/)  
"Open source's main patent protection organization is expanding its reach far beyond just Linux."

[Twitter’s ban almost doubled attention for Biden misinformation](https://www.technologyreview.com/2020/10/16/1010644/twitter-ban-hunter-biden-emails-backfires/)  
"The social media company’s attempt to stop misinformation from spreading brought the Streisand Effect into action."

[San Francisco Apartment Rents Crater Up to 31%, Most in U.S. During Covid](https://www.bloomberg.com/news/articles/2020-10-13/san-francisco-studio-apartment-rents-plunge-31-most-in-u-s)  
Duh!

## Process

[Protecting K8s Against MITRE ATT&CK Techniques - Download Whitepaper](https://security.stackrox.com/protecting-against-K8s-threats-white-paper.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes for business-critical operations is driving new security challenges that must be addressed - namely an expansion of the attack surface that exposes you to new threats. The MITRE ATT&CK framework was recently adapted to Kubernetes to identify nine distinct attack vectors and techniques unique to Kubernetes that attackers employ. [Download this whitepaper](https://security.stackrox.com/protecting-against-K8s-threats-white-paper.html?Source=DevOpsIsh&LSource=DevOpsIsh) from StackRox to learn about these nine techniques and the individual tactics within each technique, and get actionable recommendations to protect your environment and reduce your attack surface. *SPONSORED*

BleedingTooth Coverage:

* [BleedingTooth: critical kernel Bluetooth vulnerability](https://lwn.net/Articles/834297/rss)
* [Linux: Heap-Based Type Confusion in L2CAP (BleedingTooth)](https://github.com/google/security-research/security/advisories/GHSA-h637-c88j-47wq)
* [BleedingTooth - Kernel Bluetooth vulnerabilities - CVE-2020-12351, CVE-2020-12352, and CVE-2020-24490](https://access.redhat.com/security/vulnerabilities/BleedingTooth)

[CVE-2020-15157 "ContainerDrip" Write-up](https://darkbit.io/blog/cve-2020-15157-containerdrip)  
"If an attacker publishes a public image with a crafted manifest that directs one of the image layers to be fetched from a web server they control and they trick a user or system into pulling the image, they can obtain the credentials used by ctr/containerd to access that registry."

[Microsoft wins court order to take down TrickBot, a botnet that threatens election integrity](https://www.washingtonpost.com/technology/2020/10/12/microsoft-trickbot-ransomware/)  
"The software giant won a court order to seize servers used by the Trickbot botnet, a network of infected computers that Microsoft says might have been used to lock up voter-registration systems."

[Undocumented backdoor that covertly takes snapshots found in kids’ smartwatch](https://arstechnica.com/information-technology/2020/10/a-watch-designed-exclusively-for-kids-has-an-undocumented-spying-backdoor/)  
"The X4, made and jointly developed in China, raises concerns."

[Further analysis of PyPI typosquatting](https://lwn.net/SubscriberLink/834078/d7c69dad72e414af/)  
"They identified two types of package typosquatting: misspelling and confusion. The first type relies on package names that are slightly misspelled, djanga instead of django or urlib3 instead of urllib3. The confusion attacks rely upon changing the order of the "words" in the name (e.g. nmap-python rather than python-nmap), removing or changing separators (e.g. easyinstall vs. easy_install), or otherwise changing the elements of the name (e.g. crypt/crypto, python-sqlite/pysqlite). Of the 40 attacks identified, 18 were of the misspelling variety, while 24 were confusing-two were both, which accounts for the overlap."

## Tools

[Oh Dear, uptime monitoring like no other](https://ohdear.app/)  
With Oh Dear, you get uptime monitoring, SSL certificate alerts, performance monitoring and we'll crawl your entire site, reporting 404's, server errors and more. With our unlimited status pages and cron job monitoring, Oh Dear is all the monitoring you'll ever need. Sign up with code DEVOPSISH and get a 30% discount on your first 3 months. *SPONSORED*

[Who Needs a Dashboard? Why the Kubernetes Command Line Is Not Enough](https://thenewstack.io/who-needs-a-dashboard-why-the-kubernetes-command-line-is-not-enough/)  
"Developers don’t use them, but enterprises won’t buy a product without them. What’s the deal with dashboards? And why do they matter for Kubernetes?"

[Room-temperature superconductivity has been achieved for the first time](https://www.technologyreview.com/2020/10/14/1010370/room-temperature-superconductivity/)  
"It was in a tiny sample under extremely high pressure, so don’t start dismantling the world’s energy infrastructure quite yet." But, it is a pretty giant leap forward.

[shellcheck](https://wizardzines.com/comics/shellcheck/)

[PostgreSQL Monitoring for Application Developers: The DBA Fundamentals](https://info.crunchydata.com/blog/postgresql-monitoring-for-application-developers-dba-stats)  
"These statistics provide an overall look at PostgreSQL database activity and can help you spot problems with performance and availability, and can provide 'early warnings' before 'bad things' start to happen."

[Rust after the honeymoon](http://dtrace.org/blogs/bmc/2020/10/11/rust-after-the-honeymoon/)  
Bryan Cantrill and the folks at Oxide still appreciate Rust. They've been using it for two years now. I'm not sure if they've made any money but, they like Rust.

[Van Halen's rider and how it can help improve software development](https://blog.scottlogic.com/2020/10/15/van-halens-rider-and-software-development.html)  
You should always have an quality indicator when working with third parties. If you can't make up one, something is wrong. Use this as a constant measuring stick whenever there's a handoff.

[It's Time to Forget About Docker](https://martinheinz.dev/blog/35)  
"In the ancient times of containers (really more like 4 years ago) Docker was the only player in the container game. That's not the case anymore though and Docker is not the only, but rather just another container engine on the landscape. Docker allows us to build, run, pull, push or inspect container images, but for each of these tasks there are other alternative tools, which might just do better job at it than Docker. So, let's explore the landscape and (just maybe) uninstall and forget about Docker altogether..."

[Orchestrating CloudEvents (with Knative and Zeebe)](https://knative.dev/blog/2020/10/10/orchestrating-cloudevents-with-knative-and-zeebe/)  
"Knative Eventing and Workflow Engine Integration for gaining visibility, decoration and orchestration scenarios."

[exelban/stats](https://github.com/exelban/stats)  
macOS system monitor in your menu bar (I usually don't recommend Mac apps unless I'm actively using them)

[n3wscott/sockeye](https://github.com/n3wscott/sockeye/)  
Websocket based CloudEvents viewer.

[thanos-io/kube-thanos](https://github.com/thanos-io/kube-thanos)  
Kubernetes specific configuration for deploying Thanos.

[sassman/t-rec-rs](https://github.com/sassman/t-rec-rs)  
Blazingly fast terminal recorder that generates animated gif images for the web written in rust

[dandavison/delta](https://github.com/dandavison/delta)  
A viewer for git and diff output

[5 Fun Ways to Use Kubernetes](https://thechief.io/c/editorial/5-fun-ways-use-kubernetes/)  
Next time you have some time to burn and some Kubernetes to learn.

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week from @aycabs](https://shortcdn.com/devopsish/188-devopsish-tweet-of-the-week.png)](https://twitter.com/aycabs/status/1315229327076683778)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/188/notes.md) to see what didn't make it to the newsletter.
