+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2020"]
date = 2020-02-23T16:00:00Z
description = "Two universes of IBM and Red Hat, Impact of Istio and Knative not going to a foundation, compensation questions, technical debt, and more"
draft = false
slug = "168"
tags = ["open source", "Kubernetes", "DevOps", "IBM", "Red Hat", "cloud", "Cloud Native", "technical debt", "engineer", "Google", "Ansible", "Linux Foundation", "trust", "Oracle", "Istio", "Knative", "CNCF", "platform", "infrastructure", "Xerox", "Linux", "observability", "monitoring", "performance", "Kelsey Hightower", "Datadog", "containers", "Moore's Law", "Cloud Native Computing Foundation", "parallel"]
title = "DevOps'ish 168"

+++

I spent this week in Las Vegas, working at IBM's FastStart 2020 event. The event is for IBM sellers, partners, and technical folks to come to learn the new bits of knowledge about the products they're selling and enabling at their clients' sites. I went in my usual technical capacity and learned very quickly IBM and Red Hat speak two different languages. This is expected but, I wanted to look a little further into the why behind that. As a surprise to no one, I found a DevOps parallel here.

In DevOps, change starts one of two ways based on the type of change happening. The more natural way (for me) is to start with the teams with their hands on the keyboard doing the work. Talk to them about their problems in their language. Tell them how your tool's features help to solve their problems. Pull out a laptop and prove to them you're not full of shit. This is the bottom-up approach to DevOps. It's an engineer built and run transformation. Leadership stakeholders are updated about results. Leadership buys-in because the results prove themselves.

The other approach to change I've seen is a top-down approach. This is often implemented poorly at first, from the engineer's point of view. It's often implemented as an edict from on high making what appears to be an ill-informed decision. This approach works well when an agreement that change is necessary is reached beforehand. It's also a great approach when the corporate culture is fantastic. Yes, I've seen it done as an executive driven decision with mass firing and all the trimmings. That approach rarely goes well.

IBM uses a top-down approach to sales and enablement because it has established trust with its clients. This trust is very much with the top of the org chart, though.  An engineer and developer-first world full of projects and tools the IBM crowd has never seen or even heard of before is foreign. This world is also eating into the IBM world. If Red Hat and IBM establish a new common language and figure out our collective strengths together, watch out.

## People

[Jeffrey Paul: Discord Is Not An Acceptable Choice For Free Software Projects](https://sneak.berlin/20200220/discord-is-not-an-acceptable-choice-for-free-software-projects/)  
An argument against Discord for use with open source and public interest projects. The privacy and censorship point of view is one I appreciate but, a lot of the arguments could be made about a lot of communication systems in use today, not only Discord (namely IRC and Slack).

[DOJ backs Oracle over Google in long-running copyright dispute](https://siliconangle.com/2020/02/19/doj-backs-oracle-google-long-running-copyright-dispute/)  
Anytime the US Department of Justice gets behind Oracle, it's a sign of dark times for us all. The [IEEE has an overview of the Google v. Oracle case](https://spectrum.ieee.org/tech-talk/computing/software/google-v-oracle-explained-supreme-court-news-apis-software) and its implications if you're not up to speed. This could change the course of history.

[Questions you can ask about compensation](https://jvns.ca/blog/compensation-questions/)  
Next time salary comes up in a job interview, ask them to answer some questions ⁦from Julia Evans' list. It will help you understand a lot about the company as well as how you’ll extract more money for yourself from the value you create for the organization.

[Stop Calling It "Innovation"](https://hbr.org/2020/02/stop-calling-it-innovation)  
"When engaging internally with employees, Danfoss, a global manufacturing company, has branded its innovation process around the simple, manageable word 'idea.' While not everyone think they can be innovative, nearly everyone has at least one idea."

[U.S. agency that handles Trump's secure communication suffered data breach](https://www.reuters.com/article/us-usa-defense-breach-idUSKBN20E27A)  
Having done an enormous amount of work with DISA in the past, I'm patiently waiting for my copy of [this letter](https://shortcdn.com/file/devopsish/disa-pii-breach.jpg) and the next round of free, US government-issued credit monitoring service.

## Process

[Will Google donate open-source Istio to a foundation](https://www.protocol.com/google-open-source-istio)  
"'It's a real problem,' said Nicolas Chaillan, chief software officer for the U.S. Air Force, which has made a sizable bet on Istio as a key component of its cloud strategy. 'I reached out to Google [after Kubecon] to say that if we don't get Istio within the CNCF, we'll have to drop it.'"

[The Linux Foundation identifies most important open-source software components and their problems](https://www.zdnet.com/article/the-linux-foundation-identifies-the-most-important-open-source-software-components-and-their-problems/)  
"In its latest study, the Linux Foundation's Core Infrastructure Initiative discovered just how prevalent open-source components are in all software and their shared problems and vulnerabilities."

[Open Source-based Cloud Observability](https://logz.io/freeshirt/?utm_source=podcast&utm_medium=devopish&utm_campaign=freeshirt)  
If you are like many of your friends in DevOps, you might prefer using open source solutions. Logz.io's [cloud observability platform](https://logz.io/freeshirt/?utm_source=podcast&utm_medium=devopish&utm_campaign=freeshirt) is designed to help deliver the open source experience you love, at the scale you need. Log management and Cloud SIEM based on ELK, and Infrastructure monitoring based on Grafana. All on one unified platform to help you correlate quickly between logs and metrics. Sign up for a [free trial today](https://logz.io/freeshirt/?utm_source=podcast&utm_medium=devopish&utm_campaign=freeshirt) and receive a Logz.io t-shirt! *SPONSORED*

[The Wall of Technical Debt](https://verraes.net/2020/01/wall-of-technical-debt/)  
"Or perhaps fixing it isn't worth it? That's not a matter of aesthetics or opinion anymore. It's a matter of empirically collected metrics. Congratulations, you're negotiating tradeoffs as a team."

[HP adopts limited shareholder rights plan to fend off Xerox takeover attempt](https://siliconangle.com/2020/02/20/hp-adopts-limited-duration-shareholder-rights-plan-fend-off-xerox-takeover-attempt/)  
The HP/Xerox saga continues. I'm starting to wonder when Xerox runs out of clock on this. There has to be some critical reason(s) Xerox's board sees this as it's future. Eventually, investors are going to want this work to pay off. If it never materializes, which seems more and more likely, then what Xerox?

[3 steps for product marketing your open source project](https://opensource.com/article/20/2/product-marketing-open-source-project)  
"How do I market my open source XYZ?" is a question I get at least once a week. At some point, I'll write a book about it. But, for now, I'm still trying to figure it out. But, the one thing I tell folks is to be consistent and authentic. This builds trust. Everything in open source is based on a degree of trust.

## Tools

[Kubernetes Performance Trouble Spots: Airbnb's Take](https://thenewstack.io/kubernetes-performance-troublespots-airbnbs-take/)  
Running thousands of pods in prod leads to a number of ways performance inconsistencies could pop up.

[The Kubernetes Collection for Ansible](https://www.jeffgeerling.com/blog/2020/kubernetes-collection-ansible)  
Jeff Geerling has made significant strides in getting an Ansible collection of Kubernetes tools together. If you're doing templating with Ansible, need to use Ansible in CI to mangle your Kubernetes objects, or something else with Ansible give it a look.

[The Staying Power of Kubernetes with Kelsey Hightower](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/the-staying-power-of-kubernetes-with-kelsey-hightower/)  
Kelsey answers a "grumpy Unix sysadmin's" questions. Because, "It's not like there's a second kind of Unix sysadmin you're ever going to encounter."

[Dynamic Kubernetes Monitoring](https://www.datadoghq.com/dg/monitor/kubernetes-monitoring-benefits/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=DevOpsish-Newsletter01&utm_content=Kubernetes)  
Monitor and manage your dynamic Kubernetes container fleet with Datadog. Use the Container Map to group, filter, and explore your containers, and the Live Container view to investigate the metrics and processes of individual containers. Try Datadog in your environment with a free 14-day trial. *SPONSORED*

[Stop making data scientists manage Kubernetes clusters](https://towardsdatascience.com/stop-making-data-scientists-manage-kubernetes-clusters-53c3b584cb08)  
The case for a career trajectory that has job titles like, Machine learning infrastructure engineer, Data science platform engineer, and ML production engineer. I could definitely get down with this line of work.

[Census II](https://shortcdn.com/file/devopsish/census_ii_vulnerabilities_in_the_core.pdf)  
"Census II identifies the most commonly used free and open source software (FOSS) components in production applications and begins to examine them for potential vulnerabilities, which can inform actions to sustain the long-term security and health of FOSS." I'm actually a little surprised at this list. I figured there would be things like NTP and DNS knowledge.

[COBOL stays top of mind for businesses in 2020](https://www.techradar.com/news/cobol-remains-an-important-programming-priority)  
COBOL is still going strong after all these years. These systems aren't going anywhere because they were built to last. Figuring out the best abstraction points will be critical in the future. Understanding the design of these systems and the way your systems interface with them will be increasingly important.

[Moore's Law is not Ending Soon and the Reason May Surprise You](http://highscalability.com/blog/2020/2/19/moores-law-is-not-ending-soon-and-the-reason-may-surprise-yo.html)  
Long live Moore's Law!

[VMware Kubernetes — Epic Fail In Flight](https://www.linkedin.com/pulse/vmware-kubernetes-epic-fail-flight-jay-valentine-1f/)  
One person's view on how VMware's Kubernetes play could be doomed before it even gets off the ground.

[5 arguments to make managers care about technical debt](https://understandlegacycode.com/blog/5-arguments-to-make-managers-care-about-technical-debt/)  
Debt is a tool. But, managing that debt is vital. Letting debt manage you leads to horrible things. I'm talking about money here but, your org's codebases might be old enough to be at this level of impact too. But, much like you had to learn some money management terms to navigate the financial world, you'll have to adopt new language to get management to understand the need to manage this tech debt sooner rather than later.

## DevOps'ish Tweet of the Week

{{< tweet 1229842910239166465 >}}
