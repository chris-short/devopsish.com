+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2019"]
date = 2019-09-15T07:00:00Z
description = "Richard Stallman needs to go, Istio 1.13, intelligence gathering for nation states, Python 2's sunset, and a OOCL Hong Kong's container ship worth of Kubernetes"
draft = false
slug = "145"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "DevOps news", "Kubernetes news", "Python", "Istio", "Microsoft", "Richard Stallman", "AWS"]
title = "145: No more Richard Stallman (or his ilk), spying in tech, apps at AWS, Istio 1.13, SSH certificates, Kubernetes issues with iptables, and more"

+++

There's a lot in the newsletter this week; from Istio to intelligence gathering for nation-states. Python 2's sunset date of 1 Jan 2020 being set is going to have some pretty significant impact. There are also 28 mentions of "Kubernetes" in the source for this week's newsletter. This week's DevOps'ish Tweet of the Week can get you a free copy of [Kubernetes: Up and Running, Second Edition](https://azure.microsoft.com/en-us/resources/kubernetes-up-and-running/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=145&utm_term=kubernetes). Oh and Richard Stallman *MUST* go.

## DevOps'ish Last Week's Top Five

1. [Why doesn't anyone weep for Docker?](https://www.techrepublic.com/article/why-doesnt-anyone-weep-for-docker/)
1. [A Manager's Guide to Kubernetes Adoption](https://unixism.net/2019/08/a-managers-guide-to-kubernetes-adoption/)
1. [hunterlong/statping](https://github.com/hunterlong/statping)
1. [3 Ways to Motivate Yourself When You Don't Have a Deadline](https://hbr.org/2019/09/how-to-motivate-yourself-when-you-dont-have-a-deadline)
1. [Curl Cookbook](https://catonmat.net/cookbooks/curl)

[See the top ten →](https://devopsish.com/145/notes/)

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[See more Events →](https://devopsish.com/145/events/)

## People

[Remove Richard Stallman](https://medium.com/@selamie/remove-richard-stallman-fec6ec210794) — *Immediately*. This is simply unbelievable. That this would be sent out to a work or educational environment is crazy. It belongs on a site ending in the word chan or some fringe social network. Stallman literally said one of Jeffrey Epstein's victims was "entirely willing". This level of toxic, white, male, privilege simply cannot stand. At this point, if Stallman is speaking somewhere near you, the right thing to do is protest the appearance. MIT must do something here.

[8 Things Leaders Do That Make Employees Quit](https://hbr.org/2019/09/8-things-leaders-do-that-make-employees-quit) — Aside from having a socially inept idiot on staff, consistency is key. Too many constraints is bad (duh). Waste kills. Putting people in the wrong roles. Boredom inducing work will surely make people leave. Psychologically safety is everything.

[My top 25 items in a senior engineer's checklist](https://medium.com/@littleblah/my-top-25-items-in-a-senior-engineers-checklist-c8e9f9f6e3c2) — A decent list for reference. Build and tailor to your needs accordingly.

[Trump adviser asked Microsoft why it wouldn't spy for the US, company president reveals in new book](https://www.scmp.com/tech/tech-leaders-and-founders/article/3026951/trump-adviser-asked-microsoft-why-it-wouldnt-spy-us) — We're all in the battle for global dominance whether we like it or not. If you don't want to admit it, that's fine but, it's not reality.

[Chinese prof faces charges of stealing for Huawei as Microsoft comes to its defense](https://siliconangle.com/2019/09/09/chinese-professor-faces-charges-stealing-huawei-microsoft-comes-defense/) — Still don't believe me?

[Kubernetes co-founder Craig McLuckie is as tired of talking about Kubernetes as you are](https://techcrunch.com/2019/09/11/kubernetes-co-founder-craig-mcluckie-is-as-tired-of-talking-about-kubernetes-as-you-are/)

[17 Reasons NOT To Be A Manager](https://charity.wtf/2019/09/08/reasons-not-to-be-a-manager/)

## Process

[Should VMware Change Its Name?](https://www.forbes.com/sites/moorinsights/2019/09/10/should-vmware-change-its-name/#77fceaad4f2f) — Uhhh... Not yet. I don't think they'd land on anything that would be better. Now, adopting the Pivotal name across the product portfolio could be an interesting move.

[Mistake that cost thousands (Kubernetes, GKE)](https://medium.com/@gajus/mistake-that-cost-thousands-kubernetes-gke-2212ea663e1f) — "No exaggeration, unfortunately. As a disclaimer, I will add that this is a really stupid mistake and shows my lack of experience managing auto-scaling deployments. However, it all started with a question with no answer and I feel obliged to share my learnings to help others avoid similar pitfalls."

[JPMorgan's Athena has 35 million lines of Python code, and won't be updated to Python 3 in time](https://www.techrepublic.com/article/jpmorgans-athena-has-35-million-lines-of-python-code-and-wont-be-updated-to-python-3-in-time/) — Python 2 is officially unsupported as of 1 Jan 2020. One of the largest trading platforms in the world won't be ready in time. This will leave JP Morgan's Athena susceptible to whatever fresh hell Python 2 has on the other side of its supported life.

[Modern applications at AWS](https://www.allthingsdistributed.com/2019/08/modern-applications-at-aws.html) — AWS' Werner Vogels walk us through the Amazon way of building applications.

[How Bloomberg Achieves Close to 90-95% Hardware Utilization with Kubernetes](https://www.cncf.io/case-study/bloomberg/) — A CNCF case study into how Bloomberg is getting the most out of their iron with Kubernetes. That's what it's all about, using the compute you have to its fullest. Data center density matters.

[The NetCAT is out of the bag: Intel chipset exploited to sniff SSH passwords as they're typed over the network](https://www.theregister.co.uk/2019/09/10/intel_netcat_side_channel_attack/)

## Tools

[**Full Alerting Coverage Without the Toil**](https://www.bluematador.com/devopsish)  
Balance rapid feature development and production stability with alert automation for your cloud infrastructure from Blue Matador. Activate alert automation in your cloud infrastructure today with our free trial. *SPONSORED*

[Announcing Istio 1.3](https://istio.io/blog/2019/announcing-1.3/) — "The theme of Istio 1.3 is User Experience." For example, `containerPort` is no longer required, Istio Deployment Models concept, and a bevy of other features.

[If you're not using SSH certificates you're doing SSH wrong](https://smallstep.com/blog/use-ssh-certificates/) — I don't blame you if you're not. Adding another service to what might be the connection of last resort doesn't come without risk.

[Kubernetes and Python](https://srcco.de/posts/kubernetes-and-python.html) — "While Go is the language-of-choice in the cloud-native world, Python has a huge community and makes it really easy to extend Kubernetes in only a few lines of code. This post is a follow-up to a talk I gave last week in Prague."

[Input Output Redirection on Linux Explained](https://devconnected.com/input-output-redirection-on-linux-explained/) — I used to have some insane one-line bash scripts I would run:

``` bash
mkdir -p /mnt/SC2i && mount -v -t cifs //HOSTNAME/OFFICE/private/SC2i /mnt/SC2i -o user=USERNAME && cd /mnt/SC2i && find . -type f > /root/SC2i_files.txt && while read N ; do stat -c '%n:%y:%z:%s' "$N" ; done < /root/SC2i_files.txt > /root/SC2i_report.csv && sed -i '1s/^/FILENAME,MODTIME,CHANGETIME,BYTES\n/' /root/SC2i_report.csv
```

[Kubernetes Patterns - Declarative Deployments](https://www.magalix.com/blog/kubernetes-patterns-declarative-deployments) — "I will discuss in this article how you can do zero-downtime releases using Deployments. We will also dig into more advanced deployment scenarios such as Blue/Green and Canary workflows that give you more control on your release process."

[kube-proxy currently incompatible with `iptables >= 1.8` · Issue #71305 · kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/issues/71305) — There some issues with iptables and Kubernetes that you should probably be aware of.

[kubesphere/kubesphere](https://github.com/kubesphere/kubesphere) — Easy-to-use Production Ready Container Management Platform

[golift/imessage](https://github.com/golift/imessage) — Go Library used to interact with iMessage (Messages.app) on macOS

[asdf-vm/asdf: Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more](https://github.com/asdf-vm/asdf)

[ameerthehacker/kubelive](https://github.com/ameerthehacker/kubelive) — Kubernetes command line tool to provide live data about the cluster and its resources

[dumb-password-rules/dumb-password-rules](https://github.com/dumb-password-rules/dumb-password-rules) — Shaming sites with dumb password rules.

## DevOps'ish Tweet of the Week

{{< tweet 1172639048323567618 >}}

[See Notes →](https://devopsish.com/145/notes/)
