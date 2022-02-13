+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-06-06T07:00:00Z
description = ["On the passing of Peeyush Gupta, Apple employees balk at return to office plans, 1:1 with CNCF's Priyanka Sharma, StackOverflow acquired, Flux, Argo, HTTP 3, and more"]
draft = false
slug = "221"
tags = ["Peeyush Gupta", "Cloud Native", "Apple", "cloud", "DevOps", "Kubernetes", "code", "employees", "observability", "community", "Red Hat", "open source", "developers", "GitOps", "kubectl", "Intel", "Jenkins", "pandemic", "debug", "Priyanka Sharma", "Cloud Native Computing Foundation", "cyberattacks", "vcenter", "IBM", "Flux", "Argo", "petabyte", "Linux", "OpenShift", "Rust"]
title = "DevOps'ish 221: On the passing of Peeyush Gupta, Apple employees balk at return to office plans, 1:1 with CNCF's Priyanka Sharma, StackOverflow acquired, Flux, Argo, HTTP 3, and more"

+++

The Cloud Native community lost a great person; [Peeyush Gupta](https://github.com/cncf/memorials/blob/main/peeyush-gupta.md). He leaves behind a wife and 10-month old child. His employer, Digital Ocean, and the Kubernetes community are trying very hard to make that that mother and child will not be *as devastated*. **I beg of you**, please donate to the [**Peeyush Gupta: Family Education Fund**](https://milaap.org/fundraisers/support-peeyush-gupta-family-education).

*If half the DevOps'ish readership gave $25, we'll hit the current goal of Rs.5,500,000.*

It's been surprisingly difficult for me to deal with the loss of Peeyush. I think I've learned death doesn't get easier with age, at least when the person is a decade younger than you—my deepest condolences to the Gupta family. I cannot imagine what you are dealing with right now.

I've made two public statements on Peeyush's death. Please accept my apologies for quoting myself here.

"I was gobsmacked by the news. The impact Peeyush has had in the community is a large one. It's not possible to sit down and look at GitHub to capture Peeyush's work. It extended into so much more than code."  —Chris Short, [Heartfelt Remembrance for Peeyush Gupta (pensu)](https://groups.google.com/g/kubernetes-dev/c/WpTM45LCkRY)

"Peeyush made me look forward to going to the K8s Upstream Marketing meetings. I was devastated last week when I heard the news. But, he's not gone, his work lives on through his code. He'll be missed deeply." —Chris Short, [Twitter](https://twitter.com/ChrisShort/status/1399782389589725191)

## People

[Apple employees push back against returning to the office in internal letter](https://www.theverge.com/2021/6/4/22491629/apple-employees-push-back-return-office-internal-letter-tim-cook)  
When I first read Apple's policy, it was very apparent to me that the leadership at the company has not learned anything from this pandemic. If you work at Apple, I really do feel for you right now. Your psychological safety might be in jeopardy. There are companies  that will be mostly remote going forward ([my employer](https://devopsish.com/terms/#disclaimer) was mostly remote before the pandemic). If you need a referral into Red Hat, let me know.

Are you looking to learn more about observability practices? Join Honeycomb for [o11ycon+hnycon](https://o11ycon-hnycon.io/devopsish/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=devopsish&utm_adgroup) June 9-10! This is the observability event of the year, where people come together to explore cutting-edge observability practices, new tech like OpenTelemetry, and more. Register for this free virtual conference to connect with peers and learn from top Honeycomb customers and observability experts–including speakers from HelloFresh, Slack, CircleCI & Netflix!

Observe, debug, and improve with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[Emily Wilder's Firing at The A.P. Reminds Us of What We Didn't Expect](https://www.nytimes.com/2021/05/29/technology/emily-wilder-firing-ap.html)  
Deleting social media history is going to be a big thing in the near future. I assume people understand I'm not the same person I was four years ago let alone fourteen years ago when I joined Twitter. I deleted my Facebook account recently considering it had been dormant for quite some time.

[Advice for Junior Developers](https://ashfurrow.com/blog/advice-for-junior-developers/)  
"Software developers aren't paid to code. They're paid to build products that help the business succeed."

[In the Clouds (S2E6) | CNCF's Priyanka Sharma](https://www.youtube.com/watch?v=sRWl9RW5HKo&t=157s)  
I sat down with Priyanka Sharma, General Manager, Cloud Native Computing Foundation this week for a one-on-one conversation.

[What Your Future Employees Want Most](https://hbr.org/2021/05/what-your-future-employees-want-most)

1. Employees overwhelmingly expect flexible options.
1. Employees want to re-imagine how productivity is measured.
1. Employees want to work with a diverse team.

[From Kubernetes for work to Kubernetes for play](https://www.kubernetes.dev/blog/2021/06/01/peeyush-contributor-story/)  
By Peeyush Gupta

## Process

[Stack Overflow acquired by Prosus for $1.8 billion](https://techcrunch.com/2021/06/02/stack-overflow-acquired-by-prosus-for-a-reported-1-8-billion/)  
Shouldn't be any big changes until equity starts vesting. After that, no telling.

[What I Wish I Knew About U2F and Other Hardware MFA Protocols](https://goteleport.com/blog/u2f-lessons-learned/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish)  
We revamped the second-factor authentication in Teleport 6.0. This post provides a birds-eye view of U2F and other cryptographic hardware standards. *SPONSORED*

[F.B.I. Director Compares Danger of Ransomware to 9/11 Terror Threat](https://www.nytimes.com/2021/06/04/us/politics/ransomware-cyberattacks-sept-11-fbi.html)  
"The Biden administration is taking steps to counter the growing threat of cyberattacks on U.S. businesses, and encouraging companies to do more to protect themselves." Probably the appropriate response as US organizations are being laid waste by ransomeware of late.

[This is not a drill: VMware vuln with 9.8 severity rating is under attack](https://arstechnica.com/gadgets/2021/06/under-exploit-vmware-vulnerability-with-severity-rating-of-9-8-out-of-10/)  
As seen in the [Notes from DevOps'ish 220](https://devopsish.com/220/notes), there is a really bad vCenter vulnerability out there. "Code execution flaw in vCenter is exploited to install web shell on unpatched machines."

[The M.T.A. Is Breached by Hackers as Cyberattacks Surge](https://www.nytimes.com/2021/06/02/nyregion/mta-cyber-attack.html)  
"Hackers with suspected ties to China penetrated the New York transit agency's computer systems in April, an M.T.A. document shows. Transit officials say the intrusion did not pose a risk to riders."

## Tools

[Killer Shell](https://killer.sh/)  
CKS, CKA, and CKAD Simulator (made by [Kim Wüstkamp](https://wuestkamp.com/))

[Gain Control of Your Code with Feature Management](https://learn.launchdarkly.com/demo/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
Testing in production?  It's scary until it's not. Get total control of your code like Square, Hulu, Atlassian, Toyota, Intuit & IBM have  to ship fast without breaking things.  Book a demo today and learn how your team can reap the rewards of CI/CD without the risk.
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[**What is DevOps (free eBook)**](https://devopsish.com/what-is-devops/)

[HTTP 3 And Our Firewalls](https://utcc.utoronto.ca/~cks/space/blog/sysadmin/HTTP3AndOurFirewalls)  
Fresh off the heals of QUIC being tagged as [RFC 9000](https://daniel.haxx.se/blog/2021/05/27/quic-is-rfc-9000/), Chris Siebenmann points out that a lot of organizations now need to consider allowing UDP across port 443 into their networks. The answer is, you should.

[GitOps at Home: Automate Code Deploys with Kubernetes and Flux](https://thenewstack.io/gitops-at-home-automate-code-deploys-with-kubernetes-and-flux/)  
A GitOps with Flux overview.

[Introducing Argo Rollouts v1.0. Progressive Delivery done right!](https://blog.argoproj.io/introducing-argo-rollouts-v1-0-803e87f76ef7)  
Future releases will support many more ingress controllers and metric providers, as well as leveraging even more advanced traffic shaping techniques such as header-based routing, or shadow trafficking. For more on what's next, check out our [roadmap](https://argoproj.github.io/argo-rollouts/roadmap/).

[[RFC] Protecting users of kubectl delete](https://groups.google.com/g/kubernetes-dev/c/y4Q20V3dyOk/m/vNbttyY-BgAJ)  
This is a healthy discussion around putting some additional safeties on `kubectl delete` or `krm` if you like to live dangerously and made that alias.

[How National Labs Move Over a Petabyte Per Week](https://www.nextplatform.com/2021/06/01/how-national-labs-move-over-a-petabyte-per-week/)  
An amazing look at how the US National Labs set a goal to be able to transfer a petabyte of data a week. Then set off to build such a system capable of that. Mind blowing scale.

[The Apple M1 compiles Linux 30% faster than my Intel i9](https://www.jeffgeerling.com/blog/2021/apple-m1-compiles-linux-30-faster-my-intel-i9)  
ARM chips will start making Intel chips look like an energy-sucking, high-priced luxury good that performs worse.

[OpenShift Coffee Break: Tekton in action](https://www.youtube.com/watch?v=6cuZZGUNBUM)  
"In this episode we will talk about all CI/CD with Siamak Sadeghianfar, PM for OpenShift GitOps and Pipelines at Red Hat."

[How a Jenkins Job Broke our Jenkins UI](https://slack.engineering/how-a-jenkins-job-broke-our-jenkins-ui/)  
Fucking Jenkins.

[Observatorium](https://observatorium.io/)  
Observability distribution

[nocodb/nocodb](https://github.com/nocodb/nocodb)  
🔥 🔥 The Open Source Airtable alternative.

[TaKO8Ki/awesome-alternatives-in-rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust)  
A curated list of replacements for existing software written in Rust

[jtpio/jupyterlite](https://github.com/jtpio/jupyterlite)  
Wasm powered Jupyter running in the browser 💡

## DevOps'ish Tweet of the Week

[![Jennifer Davis @sigje on Twitter: "I wish instead of "remote work" we started talking about distributed teams." 🧵](https://shortcdn.com/file/devopsish/221-devopsish-tweet-of-the-week.png)](https://twitter.com/sigje/status/1401268238739120131)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/221/notes/) to see what didn't make it to the newsletter but are still worth your time.
