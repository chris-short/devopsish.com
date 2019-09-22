+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-09-22T07:00:00Z
description = ""
draft = false
slug = "146"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "weekly newsletter", "DevOps news", "Kubernetes news"]
title = "146: Seth Vargo says hell no—puts Chef on ICE, Kubernetes 1.16, "

+++

Just when you thought an old white guy with bad hygiene was going to dominate the news this week, in walks [Seth Vargo](https://twitter.com/sethvargo). On Thursday, Seth Vargo, a former Chef employee and current Google Cloud engineer, learned something he wasn't comfortable with about code he'd written. Seth discovered Chef had an active contract with the US Department of Homeland Security's Immigration and Customs Enforcement (yes, [that one](https://time.com/5623148/migrant-detention-centers-conditions/)). When Chef wouldn't respond to calls to kill the contract, Seth did something rather extraordinary. He yanked his code (including [chef-sugar](https://github.com/sethvargo/chef-sugar)) from GitHub and RubyGems. This resulted in a number of production systems going offline across the globe. We might see some metrics about impact in a lawsuit at some point. When DM'ing Seth early Friday AM he told me, "It's almost certain that Chef is going to sue."

Before we get into the reasoning, let's think about that for a second. A former employee (and current open source contributor) somehow had the ability to bring an entire DevOps toolchain company to its knees. Sending it into a complete tailspin as it tried to frantically restore production code bases and build artifacts it likely didn't have control over (or maybe even good backups for). Chef CEO, Barry Crist, [had to issue a statement](https://blog.chef.io/2019/09/19/chefs-position-on-customer-engagement-in-the-public-and-private-sectors/) damn near immediately.

One person. One company. One policy. One decision. Global impact. If anyone wants to know why I care about technology's impact on humanity, and use this newsletter as a platform for that position, this is it. As technologists, we have tremendous control over what we do. However, we have little to no control over how our outputs are used. If we are not incredibly thoughtful and deliberate with our decision making the impact could be globally catastrophic. In Seth's own words, "I'm not trying to make a political statement. As software engineers, we have to abide by some sort of moral compass. When I learned that my code was being used for purposes that I perceive as evil, I had to act.

Chef's decision to remain silent on the issue, and their decision to restore an older version of the code, removing me as an author from the metadata, however, speaks volumes to their own moral and ethical standards."

In my opinion, Chef is as culpable as Chef is in all this. The fact someone not at their company anymore could even potentially have an impact like this shows a clear lack of supply chain controls and safeties. The fact their own timeline shows over a day of unavailiability for some components leads me to believe that Chef's footing is even shakier than I suspected.

## DevOps'ish Last Week's Top Five

1. [Remove Richard Stallman](https://medium.com/@selamie/remove-richard-stallman-fec6ec210794)
1. [My top 25 items in a senior engineer's checklist](https://medium.com/@littleblah/my-top-25-items-in-a-senior-engineers-checklist-c8e9f9f6e3c2)
1. [8 Things Leaders Do That Make Employees Quit](https://hbr.org/2019/09/8-things-leaders-do-that-make-employees-quit)
1. [17 Reasons NOT To Be A Manager](https://charity.wtf/2019/09/08/reasons-not-to-be-a-manager/)
1. [If you're not using SSH certificates you're doing SSH wrong](https://smallstep.com/blog/use-ssh-certificates/)

* [Alert Automation for your Cloud Infrastructure](https://www.bluematador.com/devopsish) *SPONSORED*

[See the top ten →](https://devopsish.com/146/notes/)

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[**KubeCon + CloudNativeCon North America 2019**](https://cshort.co/kcna19)  
The Cloud Native Computing Foundation's flagship conference gathers adopters and technologists from leading open source and cloud native communities in San Diego, California from November 18-21, 2019. Join Kubernetes, Prometheus, Envoy, CoreDNS, containerd, Fluentd, OpenTracing, gRPC, CNI, Jaeger, Notary, TUF, Vitess, NATS, Linkerd, Helm, Rook, Harbor, etcd, Open Policy Agent, CRI-O, and TiKV as the community gathers for four days to further the education and advancement of cloud native computing. Use code *KCNACSN10* at checkout for a 10% discount on Corporate Registration.

[See more Events →](https://devopsish.com/146/events/)

## People

[Tech Animals](http://www.git-tower.com/blog/tech-animals) - A side project for a good cause. fournova Software reached out to me directly about an effort they put together to support [Hacker School](https://www.betterplace.org/en/projects/58054-hacker-school-inspire-young-people-for-coding-and-integrate-refugees). I love it! Check it out and let me know what you get (I ordered the Linux mug and am pondering more)!



## Process

PROCESS

## Tools

[**Full Alerting Coverage Without the Toil**](https://www.bluematador.com/devopsish)  
Balance rapid feature development and production stability with alert automation for your cloud infrastructure from Blue Matador. Activate alert automation in your cloud infrastructure today with our free trial. *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

{{< tweet 1174116297468252160 >}}

[See Notes →](https://devopsish.com/146/notes/)
