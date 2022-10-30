+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-12-26T07:00:00Z
description = ["The Log4j gift that keeps on giving, Kubernetes Contributor Awards, CKAD Help, web3 & NFTs, DuckDuckGo, self-hosting, EKS News, OpenKruise, and more"]
draft = false
slug = "249"
tags = ["open source", "log4j", "Kubernetes", "cloud", "DevOps", "Rust", "Julia Ferraioli", "web3", "NFT", "GitOps", "NSO", "GitHub", "Erica Brescia", "maintainers", "vulnerability", "Corey Quinn", "artists", "Karpenter", "DuckDuckGo", "Cloud Native", "developers", "Kris Nova"]
title = "DevOps'ish 249: The Log4j gift that keeps on giving, Kubernetes Contributor Awards, CKAD Help, web3 & NFTs, DuckDuckGo, self-hosting, EKS News, OpenKruise, and more"

+++

Happy Holidays everyone! This is the last DevOps'ish of the year 2021. This month has this year into one that is somehow worse than 2020. I intend to continue the annual tradition of writing down my [learnings and expectations](https://chrisshort.net/2020-learnings-2021-expectations/) for 2021 and 2022. But, looking back, it's pretty challenging to say what to expect next year. I might land on more upheaval out of necessity. If there is a breakout technology/concept/company you think is about to get big in 2022, hit reply and let me know your thoughts (full credit given; make sure you share a link to your website or social media profile).

[DevOps'ish](https://devopsish.com/) for a fresh theme. I'm considering a VERY simplistic version of the website (one designed on this side of the century). It's a work in progress, but I hope to roll it out over the next week. I want to point out this is in an MVP stage. The final product will look different. But, at its core, I like this theme because it keeps things clean and simple (visually and from a maintainers perspective). Would you mind hitting reply and telling me what you think?

If you're wondering why I haven't built an [Index](https://devopsish.com/categories/indexes/) for the [Log4Shell](https://en.wikipedia.org/wiki/Log4Shell) vulnerability, trust me, I've wanted to but, I have not had the time or have been in too much pain over the last few weeks to dedicate time to it. This coming week, I intend to assemble it. For now, check the [notes from this week's newsletter](https://github.com/chris-short/devopsish.com/blob/main/content/post/249/notes.md) as well as the [past](https://github.com/chris-short/devopsish.com/blob/main/content/post/248/notes.md) [two](https://github.com/chris-short/devopsish.com/blob/main/content/post/247/notes.md).

## People

[2021 Awards | Kubernetes Contributors](https://www.kubernetes.dev/community/awards/2021/)  
Congrats to all the award winners! Your hard work is what makes the Kubernetes community a wonderful place to exist.

[Took my CKAD, failed the first time, passed using retake with 98%](https://www.reddit.com/r/kubernetes/comments/rnfq81/took_my_ckad_failed_the_first_time_passed_using/)  
"I put loads of effort into this blog. I hope more people can benefit from my blog and learn from my mistake and be successful."

[Google warns that NSO hacking is on par with elite nation-state spies](https://arstechnica.com/information-technology/2021/12/google-warns-that-nso-hacking-is-on-par-with-elite-nation-state-spies/)  
The market for knowledgeable and deft intelligence-focused hackers is incredibly lucrative. The fact that the NSO group was outperforming actual intelligence operations speaks to the volume of security vulnerabilities folks can profit from. NSO will have a hard time existing going forward but, there are many others in this space. Also, [New analysis further links Pegasus spyware to Jamal Khashoggi murder](https://www.theverge.com/2021/12/21/22848485/pegasus-spyware-jamal-khashoggi-murder-nso-hanan-elatr-new-analysis), which is widely seen as a gross violation of international norms AND civil rights, in general (on top of a truck load of other things).

[Redpoint Snags Another GitHub Exec, Names Erica Brescia New Partner](https://www.forbes.com/sites/kenrickcai/2021/12/20/redpoint-snag-erica-brescia-github-coo-as-new-early-stage-partner/)  
"When Erica Brescia first met Satish Dharmaraj, she was trying to sell tech services from her company Bitrock—developers of Bitnami, which helps developers package and deploy applications—to Dharmaraj's email software firm Zimbra. They didn't close the deal. But, it still paid off. More than a decade later, Brescia is leaving GitHub, where she's been serving as chief operating officer. In January, she will join the early stage team alongside Dharmaraj (No. 6 on the [Midas List](http://www.forbes.com/midas/)) at VC firm Redpoint Ventures."

[Into the Great Wide Open Source with Julia Ferraioli](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/into-the-great-wide-open-source-with-julia-ferraioli/)  
"After crossing paths at Monktoberfest, Julia Ferraioli, co-founder of Open Source Stories, has been politely badgered by Core[y] to come on the show. Now she has set down to chat with Corey to cover the open source spread. From her own work, to things that need change, to what works, Julia has a lot to offer! Julia talks about the general project at Open Source Stories, and the ways they are making the user a primary motivation when building out products. She and Corey reflect on the open source community and what her definition of open source is. They take a deep dive into some of the nuances of open source and Julia’s observations are articulate, well thought out, and worthwhile."

[On Non-Fungible Tokens, Faces of Our Leadership, and Supporting Artists](https://sfconservancy.org/blog/2021/dec/23/nft-faces-of-open-source/)  
All for folks getting paid. "But we think NFTs is the wrong approach." [Kris Nóva](https://nivenly.com/lib/2021-12-22-nft/), discusses waking up to learn you're an NFT, the idea of supporting artists, and artists' need to be more precise about how artists notify subjects about this process (especially with open source maintainers). Let the record reflect, I'm 100% with Kris.

[A Site Reliability Engineer's Guide to the Holiday Season](https://rootly.com/blog/a-site-reliability-engineer-s-guide-to-the-holiday-season)  
A non-nonsense approach to getting through the holidays. Remember, this coming week will be very quiet too.

[Meet the Self-Hosters, Taking Back the Internet One Server at a Time](https://www.vice.com/en/article/pkb4ng/meet-the-self-hosters-taking-back-the-internet-one-server-at-a-time)  
"Tired of Big Tech monopolies, a community of hobbyists is taking their digital lives off the cloud and onto DIY hardware that they control." I might join these ranks in 2022.

## Process

[Apache Issues 3rd Patch to Fix New High-Severity Log4j Vulnerability](https://thehackernews.com/2021/12/apache-issues-3rd-patch-to-fix-new-high.html)  
Log4j, the gift that keeps on giving.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[New Log4J Flaw Caps Year of Relentless Cybersecurity Crises](https://www.wsj.com/articles/new-log4j-flaw-caps-year-of-relentless-cybersecurity-crises-11640178004)  
When The Wall Street Journal writes a report on something we work with, we need to pay special attention to the language. This will tell us what FUD we will have to deal with and what facts we need to present to show that software today is just broken. OpenSSL didn't get support until Heartbleed. Log4j didn't until the past few weeks. It makes me wonder, is there, in any form, a list of critical software and libraries that are vital to the internet and how much support is actually given to them? You can only change what you identify and monitor.

[Apache Log4j bug: China's industry ministry pulls support from Alibaba Cloud for not reporting flaw to government first](https://www.scmp.com/tech/big-tech/article/3160670/apache-log4j-bug-chinas-industry-ministry-pulls-support-alibaba-cloud)  
Thank you, Alibaba Cloud, for doing the right thing.

[How We Saved 70K Cores Across 30 Mission-Critical Services (Large-scale, Semi-Automated Go GC Tuning @Uber)](https://eng.uber.com/how-we-saved-70k-cores-across-30-mission-critical-services/)  
This post on Go garbage collection tuning is fascinating.

[Open Source in China: Next Four Years](https://interconnected.blog/open-source-in-china-next-four-years/)
"Since then, the landscape has changed significantly as “open source” continues to receive top-down attention from the central government. Recently, the Ministry of Industry and Information Technology (MIIT, China's main regulator of its tech industry) released a new set of development planning guidance. “Open source” is prominently featured; the term was used 27 times."

[Links to cross-origin destinations are unsafe](https://web.dev/external-anchors-use-rel-noopener/?utm_source=lighthouse&utm_medium=devtools)  
I did not know this until this week while I was doing web site building for [EKS News](https://eks.news)

## Tools

[Using Admission Controllers to Detect Container Drift at Runtime](https://kubernetes.io/blog/2021/12/21/admission-controllers-for-container-drift/)  
"With the power of admission controllers, we are able to secure our K8s clusters by detecting potentially mutated containers at runtime, and evicting their Pods without affecting service availability. We also utilize kubectl plugins to provide flexibility of the eviction time and hence, bringing a better and more self-independent experience to service owners. We are proud to announce that we have open-sourced the whole project for the community to leverage in their own K8s clusters."

In modern architecture, slow is the new down. Distributed tracing shows your deeply hidden problems so you can fix the right issue the first time. It's never been easier to get started. [Use Honeycomb and OpenTelemetry](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) to quickly find hidden slowness–for free. *SPONSORED*

[EKS News](https://eks.news/)  
Coming to an inbox near you in 2022.

[How To Auto-Scale Kubernetes Clusters With Karpenter](https://www.youtube.com/watch?v=C-2v7HT-uSA)  
A great overview of how Karpenter works.

[OpenKruise v1.0, reaching new peaks of application automation](https://www.cncf.io/blog/2021/12/23/openkruise-v1-0-reaching-new-peaks-of-application-automation/)  
A new tool that could be used for GitOps enters the fray.

[DuckDuckGo in 2021: Building the Privacy Super App](https://spreadprivacy.com/duckduckgo-2021-review/)  
Yo... I cannot wait for this. Brave is bloated and heavy handed. If DuckDuckGo pulls this off well, Google will have to seriously reconsider what its doing in the world. Looking at year stats for all my web sites, DuckDuckGo was #2 after Google and Bing was #3. That's pretty amazing.

[Jack Dorsey's hot Web3 takes are apparently too much for Marc Andreessen to handle](https://www.theverge.com/2021/12/22/22850558/jack-pmarca-a16z-web3-block-twitter?scrolla=5eb6d68b7fedc32c19ef33b4)  
web3 in its current form is a pipe dream. More hopes and wishes than actual implementation details. When you call someone's baby ugly though, they'll take offense.

[Stop Whining about Rust Hype - A Pro-Rust Rant](https://thenewwazoo.github.io/whining.html)  
I'm all for Rust. Stop calling every new thing a fad and realize the point at which something has stopped being a fad and is something very, very real. Rust is here. Rust is safer than C and in many cases outperforms it. Memory safe languages are just better in our current timeline.

[Using Route53 as a Key Value Store in GitHub Actions](https://doug.sh/posts/using-route53-as-a-key-value-store-in-github-actions/)  
Corey Quinn's favorite key-value store in full effect. Subscribe to Corey's newsletter, [Last Week in AWS](https://ref.lastweekinaws.com/7h1z3x), for some of the best AWS coverage in the business.

[A Quadrillion Mainframes on Your Lap](https://spectrum.ieee.org/ibm-mainframe)  
"Your laptop is way more powerful than you might realize"

[This 8-bit processor built in Minecraft can run its own games](https://www.pcworld.com/article/559794/8-bit-computer-processor-built-in-minecraft-can-run-its-own-games.html)  
Wow... This is so cool.

[QOI — The Quite OK Image Format](https://qoiformat.org/)  
I hope this gets browser support ASAP.

[Running your own email is increasingly an artisanal choice, not a practical one](https://utcc.utoronto.ca/~cks/space/blog/sysadmin/EmailServersNoLongerPractical)  
Hell, just standing up a new newsletter this week required a ton of very specific DNS records; DKIM, SPF, DMARC, and other TXT records. Doing this on your own public facing infrastructure is next to impossible these days.

[Qovery/pleco](https://github.com/Qovery/pleco)  
Automatically removes Cloud managed services and Kubernetes resources based on tags with TTL

[up9inc/mizu](https://github.com/up9inc/mizu)  
API traffic viewer for Kubernetes. Think TCPDump and Wireshark re-invented for Kubernetes

[wader/fq](https://github.com/wader/fq)  
jq for binary formats

## DevOps'ish Tweet of the Week

[![commandasaurus 🦦 (@amcasari) on Twitter) "We can *already* give you one example of where this falls short — attribution in open source. Receipts: https://arxiv.org/abs/2103.11007"](https://shortcdn.com/devopsish/249-devopsish-tweet-of-the-week.webp)](https://twitter.com/amcasari/status/1473321726226452483)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/XXX/notes.md) to see what didn't make it to the newsletter but are still worth your time.
