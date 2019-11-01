+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-08-25T07:00:00Z
description = "COBOL, Git got, Kubernetes ~~enables~~ forces collaboration, 2019 State of DevOps, have DevOps your way, and more"
draft = false
slug = "142"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "DevOps news", "Kubernetes news", "COBOL", "git", "ops", "Site Reliability Engineering", "SRE", "WeWork"]
title = "142: COBOL, Git got, Kubernetes ~~enables~~ forces collaboration, 2019 State of DevOps, have DevOps your way, and more"

+++

I wrote something this week on Twitter that I'd like to dive a little deeper into. "I see Kubernetes as an opportunity for Ops folks to reach across the DevOps divides and help Devs understand what concepts Ops has wrangled with every day around DNS, networking, infrastructure, etc. Kubernetes is a tool that could improve collaboration along logical boundaries."

Google's SRE culture influenced their use of containers and vice versa. Kubernetes is an output of that container use and culture. It shouldn't come as a surprise that a tool built from an SRE culture by container wielding engineers ends up helping that culture grow and spread. I've long said SRE is the metrification of DevOps. But, what Kubernetes can enable in an organization is a singular way in which they orchestrate.

Devs have long wondered why Ops can't move faster. Ops is giving Developers this platform, Kubernetes. Developers might be struggling with the bits that Ops has been managing for a while now. Things like DNS, TLS certificates, security, or governance aren't trivial at scale in any organization. Kubernetes ~~enables~~ forces Development and Operations to collaborate in ways we wouldn't without it. Ops would be wise not to beat their chest. Devs would be prudent to ask Ops for help. Remember to be humble and that you’re all working towards the same goals (hopefully).

## DevOps'ish Last Week's Top Five

1. [The Dark Side of DevOps](https://youtu.be/gi-i5NvxVLM) (YouTube)
1. [Three Years of Misery Inside Google, the Happiest Company in Tech](https://www.wired.com/story/inside-google-three-years-misery-happiest-company-tech/)
1. [Why our team canceled our move to microservices](https://medium.com/@steven.lemon182/why-our-team-cancelled-our-move-to-microservices-8fd87898d952)
1. [Is It Time to Let Employees Work from Anywhere?](https://hbr.org/2019/08/is-it-time-to-let-employees-work-from-anywhere)
1. [BPF Performance Tools by Brendan Gregg](https://amzn.to/2z6EeTi) (Amazon)

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[See more Events →](https://devopsish.com/142/events/)

## People

[Conference Question](https://xkcd.com/2191/) — Almost every question I've ever heard at a conference. Kidding. Or am I?

[For Young Female Coders, Internship Interviews Can Be Toxic](https://www.wired.com/story/for-young-female-coders-internship-interviews-can-be-toxic/) — "According to a Girls Who Code survey, many young women, whom the tech industry is counting on to diversify its heavily male workforce, are put off by their first encounters with tech companies."

[WeWTF](https://www.profgalloway.com/wewtf) — WeWork CEO, Adam Neumann, is mentioned 169 times in their S1. This is such a trainwreck.

[Oracle directors give blessing to shareholder lawsuit against Larry Ellison and Safra Catz](https://techcrunch.com/2019/08/22/oracle-directors-give-blessing-to-shareholder-lawsuit-against-larry-ellison-and-safra-catz/) — Speaking of trainwrecks, Oracle's board just approved a lawsuit against Oracle's founder and CEO. The NetSuite deal might have been too sweet. Larry Ellison owned NetSuite when Oracle acquired it.

[Trump Administration Brief Asks Supreme Court To Allow Firing Workers For Being Gay](https://www.buzzfeednews.com/article/dominicholden/trump-scotus-gay-workers) — In case you didn't hear, the US Justice Department just asked the Supreme Court to reinterpret the Civil Rights Act of 1964 to exclude LGTBQ workers at private companies from protections against discrimination.

## Process

[How DevOps is like auto racing](https://developers.redhat.com/blog/2019/08/22/how-devops-is-like-auto-racing/) — "When I talk about desired outcomes or answer a question about where to get started with any part of a DevOps initiative, I like to mention NASCAR or Formula 1 racing." Excerpts from this piece were used in [How to explain DevOps in plain English](https://enterprisersproject.com/article/2019/8/devops-explained-plain-english).

[The 2019 Accelerate State of DevOps: Elite performance, productivity, and scaling](https://cloud.google.com/blog/products/devops-sre/the-2019-accelerate-state-of-devops-elite-performance-productivity-and-scaling)

[Business Roundtable Redefines the Purpose of a Corporation to Promote ‘An Economy That Serves All Americans'](https://www.businessroundtable.org/business-roundtable-redefines-the-purpose-of-a-corporation-to-promote-an-economy-that-serves-all-americans) — Updated Statement Moves Away from Shareholder Primacy, Includes Commitment to All Stakeholders

[A security issue in the net/http library of the Go language affects all versions and all components of Kubernetes](https://hub.packtpub.com/a-security-issue-in-the-net-http-library-of-the-go-language-affects-all-versions-and-all-components-of-kubernetes/) — A lot of FUD around this one but, if your project or product is written in Go, you should have seen updates for them too potentially. If you didn't, check if your vendor/project is being as responsible as the Kubernetes community is.

[It's not always true, but sometimes it is true.](https://www.reddit.com/r/kubernetes/comments/ctn93i/its_not_always_true_but_sometimes_it_is_true/) (/r/kubernetes)

[Making containers safer](https://lwn.net/SubscriberLink/796700/10593f18437c3b70/) — LXD and LXC your cup of tea? You should give this a look see.

[How Compuware Escaped Its Waterfall for True Mainframe DevOps](https://www.infoq.com/articles/compuware-from-waterfall-to-devops/) — Yes, DevOps and Mainframes can co-exist.

[Applying Netflix DevOps Patterns to Windows](https://medium.com/netflix-techblog/applying-netflix-devops-patterns-to-windows-2a57f2dbbf79) — DevOps even works with Windows at Netflix

## Tools

[Command Line Heroes Season 3: The Infrastructure Effect](https://www.redhat.com/en/command-line-heroes/season-3/the-infrastructure-effect) — "COBOL was a giant leap for computers to make industries more efficient. Chris Short describes how learning COBOL was seen as a safe long-term bet. Sixty years later, there are billions of lines of COBOL code that can't easily be replaced—and few specialists who know the language. Ritika Trikha explains that something must change: Either more people must learn COBOL, or the industries that rely on it have to update their codebase. Both choices are difficult. But the future isn't being written in COBOL. Today's IT infrastructure is built in the cloud—and a lot of it is written in Go. Carmen Hernández Andoh shares how Go's designers wanted a language more suited for the cloud. And Kelsey Hightower points out that languages are typically hyper-focused for one task. But they're increasingly open and flexible."

[Git Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html) — This interactive Git cheatsheet could get you out of a jam. It might even teach us a thing or two.

[Git Cheat Sheet Mug](https://shopkvlly.com/products/git-cheat-sheet-mug?utm_source=devopsish&utm_medium=newsletter&utm_campaign=142&utm_term=git) — And if that's not enough, how about a cheat sheet on your coffee mug?

[Git is eating the world](https://j11g.com/2019/08/21/git-is-eating-the-world/) — "One thing is clear however: software is eating the world and Git is the fork with which it is being eaten. (Yes, pun intended)."

[Learn Kubernetes during your Coffee Break - Kubernetes Camp](https://k8s.camp/) — This internet website is designed to teach Kubernetes basics in short easy to follow lessons that you can complete in less time than a coffee break.

[A journey from containerization to orchestration and beyond](https://iximiuz.com/en/posts/journey-from-containerization-to-orchestration-and-beyond/) — Do you want to learn about some containers?

[Google's Eric Brewer on Why Envoy and Istio are the Future of Networking](https://thenewstack.io/googles-eric-brewer-on-why-envoy-and-istio-are-the-future-of-networking/)

[How to navigate Ansible documentation](https://www.redhat.com/sysadmin/navigate-ansible-documentation) — Understanding how Ansible's documentation is organized could enable Ansible to be a lens through which you see the parts of the tech world you don't completely understand.

[kabachook/k8s-security](https://github.com/kabachook/k8s-security) — Kubernetes security notes and best practices

[google/kf](https://github.com/google/kf) — Feels like Cloud Foundry. Runs on Kubernetes. Powered by Knative and Istio.

[walmartlabs/kubeman](https://github.com/walmartlabs/kubeman) — The Hero that Kubernetes deserves

## DevOps'ish Tweet of the Week

{{< tweet 1165383130812833794 >}}

Notes from this week's issue can be found [here](https://devopsish.com/142/notes/).
