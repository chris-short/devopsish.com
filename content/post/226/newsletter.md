+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-07-11T07:00:00Z
description = ["Kubernetes non-code contributions, don't ban politics at work, engineers waste 1 day a week on technical debt, CentOS Stream is working out, and more"]
draft = false
slug = "226"
tags = ["code", "Kubernetes", "cloud", "time", "DevOps", "observability", "git", "software", "Cloud Native", "technical debt", "AWS", "engineer", "quantum", "contributor", "community", "leader", "Pentagon", "JEDI", "open source", "China", "Jim Whitehurst", "IBM", "Red Hat", "developer", "Didi", "CentOS", "Linux", "Sourcegraph", "printnightmare", "Intel"]
title = "DevOps'ish 226: Kubernetes non-code contributions, don't ban politics at work, engineers waste 1 day a week on technical debt, CentOS Stream is working out, and more"

+++

If you [follow me on Twitter](https://twitter.com/ChrisShort) you know I've had a hard time with stable internet this week. Co-workers asking about my absence, I appreciate you. Sorry, y'all, sometimes everything breaks at once. But then today I get this when working on something newsletter related.

Y'all... I can't. I can't. I can't.

{{< tweet 1413940994333102083 >}}

Then it got worse. I won't go into details but, let's just say it was the cherry on top of a shit week for tech but otherwise good week here at home.

[![Because you know I have to have a real GIF now](https://shortcdn.com/devopsish/big-bang-theory-guy-throwing-papers.gif)]

## People

[How to choose a SIG as a non-code Kubernetes contributor](https://www.kubernetes.dev/blog/2021/07/09/how-to-choose-a-sig-as-a-non-code-kubernetes-contributor/)  
"To join the Kubernetes community, I recommend finding a SIG where your skills align, doing things you want to do in your off time. There's a [list of Kubernetes SIGs](https://www.kubernetes.dev/resources/community-groups/) with a lot of great options. If you're not sure where to go, start with [Contributor Experience](https://github.com/kubernetes/community/tree/master/sig-contributor-experience). We're here to help."

[LaunchDarkly Named a Leader in Feature Management and Experimentation](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)  
Discover why in its first Wave report dedicated to Feature Management And Experimentation, Forrester rates LaunchDarkly's platform a Leader among vendor features that enable development teams to reduce software release headaches and enable true testing in production. [Download today](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)! *SPONSORED*

[Engineering Management for the Rest of Us](https://www.engmanagement.dev/)  
A book by Sarah Drasner. "A lot of Engineering Managers and leaders studied for years and years to become the best Engineer they possibly could be… and then they were promoted." It happens, get on the waitlist for the book.

[Don't Ban "Politics" at Work](https://hbr.org/2021/07/dont-ban-politics-at-work)  
Your politics is my everyday life. "With political polarization on the rise and companies gauging the risks of employees' internal political activism, some are opting to ban political speech at work entirely. The authors, experts in speaking up at work, explain the pitfalls of this approach and instead suggest asking a different question: How can we support employees and encourage them to handle difference, respect one another, listen, and learn? The answer, they suggest, requires four actions on the part of leaders: Building empathy and respect for others' views, inviting different perspectives into the leadership fold, accepting mistakes gracefully, and teaching people how to disagree."

[Strong quantum computational advantage using a superconducting quantum processor](https://arxiv.org/pdf/2106.14734.pdf)  
China now has the fastest quantum computer on the planet. How they did it was interesting too.

[IBM's Jim Whitehurst Says He's Leaving to Find a New Chance to Run Something](https://www.barrons.com/articles/ibm-jim-whitehurst-51625661249)  
Jim Whitehurst is leaving IBM to find a new chance to run something. No crazy shenanigans. [Business as usual at Red Hat](https://www.redhat.com/en/blog/red-hat-still-red-hat).

['Bad mergers' and noncompete clauses targeted in Biden executive order](https://arstechnica.com/tech-policy/2021/07/biden-seeks-trustbuster-status-in-push-to-unwind-bad-mergers/)  
Good.

[SARS-CoV-2 immune evasion by the B.1.427/B.1.429 variant of concern](https://science.sciencemag.org/content/early/2021/06/30/science.abi7994)  
Welcome, epsilon variant.

## Process

[Stepsize: Engineers waste 1 day a week on technical debt](https://venturebeat.com/2021/07/07/stepsize-engineers-waste-1-day-a-week-on-technical-debt/)  
"The average engineer spends 6 hours per week — roughly one day — dealing with technical debt, according to the State of Technical Debt 2021 report from Stepsize, a developer of software development tools. The average time spent on overall maintenance work and legacy systems is 33% — of which more than 50% of the time is spent solely on technical debt. That is time the engineer is not working toward their key goals."

Observability is gaining traction. Our 2021 Observability Maturity Community Research report revealed 61% of teams are currently practicing observability. [Download the full report](https://www.honeycomb.io/observability-maturity-community-findings-2021-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish&utm_adgroup=) to learn where you are on the observability maturity spectrum and see the benefits experienced by organizations on the higher end of the spectrum.

Guess less and know more with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[China tightens rules for global stock offerings, crimping the steady flow of companies seeking to raise funds in worldwide markets](https://www.scmp.com/business/china-business/article/3140076/china-tightens-rules-global-stock-offers-crimping-steady)  
A very odd week for Chinese companies seeking to raise funds in the global markets.  [Didi went public and then immediately got whacked off Chinese app stores by regulators](https://www.nytimes.com/2021/07/04/technology/china-didi-app-removed.html). Investors are obviously not happy because regulators said they shouldn't do the IPO. Oh... Didi got $4.4 billion in the process. Wild stuff!

[New mystery AWS product 'Infinidash' goes viral — despite being entirely fictional](https://www.theregister.com/AMP/2021/07/05/infinidash/)  
"Reg chats to developer whose joke that mere mention of a new prod would appear in job ads came true and spawned books, songs, forks, cryptocoin, and more"

[Pentagon cancels $10 billion JEDI cloud contract](https://www.cnbc.com/2021/07/06/pentagon-cancels-10-billion-jedi-cloud-contract.html)  
JEDI is dead. Now the Pentagon will pursue a multi-cloud approach. To be honest, having been there and done that, I was looking forward to seeing what the Pentagon could do with a single vendor.

## Tools

[CentOS Stream: 'I was slow on the uptake, but I get what they are doing now,' says Rocky Linux founder](https://www.theregister.com/2021/07/09/centos_stream_greg_kurtzer/)  
"HOLY CRAP! For those you pining for moments where the internet is reasonable and things work out for the best - turns out CentOS Stream *was* a good idea after all. (I was always on team good idea, way before it was cool!)" —[Adam Jacob](https://twitter.com/adamhjk/status/1413651685486981126)

[Search your code. ALL of it, everywhere](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text)  
Imagine if you could search all your code across every repo, every language, every code host. You can with [Sourcegraph universal code search](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). Quickly navigate code with contextual hover tooltips that show definitions, references, and usage examples. Construct complex queries and filter code in ways that IDEs and code hosts can't. Find and fix code fast, without losing your flow. Sourcegraph universal code search is a dev's superpower. [Get it now](https://about.sourcegraph.com/?utm_source=devopsish&utm_medium=text&utm_campaign=try-sourcegraph&utm_content=try-text). *SPONSORED*

[Earthly - Better Builds](https://earthly.dev/)  
This is one to keep an eye on.

[The best VS Code extensions to supercharge Git (yes, there's more than GitLens!)](https://dev.to/jamieswift90/the-best-vs-code-extensions-to-supercharge-git-yes-there-s-more-than-gitlens-4588)  
"[W]ork with Git via amazing extensions that not only make working with Git easier but also extend Git with cool new features and superpowers!"

[Install Calico to Enhance Kubernetes’ Built-in Networking Capability](https://thenewstack.io/install-calico-to-enhance-kubernetes-built-in-networking-capability/)  
"The problem many Kubernetes admins find (especially those new to the technology) is that network can quickly become a rather complicated mess of YAML configurations, where you must configure traffic ingress and egress properly, or communication between Kubernetes objects (such as pods and containers) can be difficult."

[Notepad gets a major upgrade, now does Unix line endings](https://arstechnica.com/gadgets/2018/05/notepad-gets-a-major-upgrade-now-does-unix-line-endings/)  
It's like a thousand little problems never happening.

[How To Add eBPF Observability To Your Product](https://www.brendangregg.com/blog/2021-07-03/how-to-add-bpf-observability.html)  
Put software in system. Use software in system. 🌈🌈🌈

[byt3bl33d3r/ItWasAllADream](https://github.com/byt3bl33d3r/ItWasAllADream)  
A PrintNightmare (CVE-2021-34527) Python Scanner. Scan entire subnets for hosts vulnerable to the PrintNightmare RCE

[danistefanovic/build-your-own-x](https://github.com/danistefanovic/build-our-own-x)  
🤓 Build your own (insert technology here)

[che-incubator/configbump](https://github.com/che-incubator/configbump)  
Simple Kubernetes controller that is able to quickly synchronize a set of config maps (selected using labels) to files on the local filesystem.

[statping/statping](https://github.com/statping/statping)  
Status Page for monitoring your websites and applications with beautiful graphs, analytics, and plugins. Run on any type of environment.

[microsoft/ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners)  
12 weeks, 24 lessons, classic Machine Learning for all

[Nudin/iptable_vis](https://github.com/Nudin/iptable_vis)  
visualise your iptables chains

## DevOps'ish Tweet of the Week

[![svbl @svblxyz on Twitter: "This is very accurate 😅"](https://shortcdn.com/devopsish/226-devopsish-tweet-of-the-week.png)](https://twitter.com/svblxyz/status/1413276163859001345)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/226/notes.md) to see what didn't make it to the newsletter but are still worth your time.
