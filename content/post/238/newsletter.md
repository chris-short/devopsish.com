+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-10-10T07:00:00Z
description = ["Leaving Red Hat, KubeCon + CloudNativeCon L.A. 2021, Chainguard, BGP for you and me, Data on Kubernetes Report, and more"]
draft = false
slug = "238"
tags = ["Red Hat", "Kubernetes", "People", "KubeCon", "CloudNativeCon", "Data on Kubernetes", "cloud", "cloud native", "Cloudflare", "Chainguard", "DevOps", "BGP", "internet", "contributor", "Tesla", "code", "Facebook", "open source", "DNS", "HTTPS", "CloudNative.tv", "GitOps"]
title = "DevOps'ish 238: Leaving Red Hat, KubeCon + CloudNativeCon L.A. 2021, Chainguard, BGP for you and me, Data on Kubernetes Report, and more"

+++

**Personal Note**: If you're reading this and you're at KubeCon in L.A. and you don't find me and say hello. I'll be sad.

I had a crazy day. I flew on a freaking plane! Two thousand three hundred miles, no less! I'm in Los Angeles, California, for [KubeCon + CloudNativeCon North America 2021](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/). Keep your eyes peeled on [my Twitter](https://twitter.com/ChrisShort/) for the most up to date shenanigans. I already have a travel tip in the books for [folks ride sharing from LAX](https://twitter.com/ChrisShort/status/1446961447976661000).

Also, I [announced my resignation this week from Red Hat](https://youtu.be/VLoeHoL0HdE?t=1306). It has been an incredible three years. I finally can now say I've figured out I'm good at turning a problem with nothing solving it into something that people never thought possible. What I'm most known for at Red Hat is live streaming. But, that was something that became a massive conduit of information and knowledge sharing. The team had a challenge; we needed a solution. I was the right person, with the right gear, at the right time. Sometimes, things work out like that.

I've learned over the years that a great job has three components: the people, the work, and the location. I got to pick the location. I should probably come up with something new for that one. The people were great. The work became great. But then it became a grind. A hard grind because there were so many parts and pieces to the puzzle that couldn't be automated. (an IFTTT for streamers is still a great product idea). We learned [you can make millions on Twitch](https://www.washingtonpost.com/video-games/2021/10/06/twitch-hack-pay-xqc-pokimane-summit1g/) this week. But, Red Hat was not getting money from streaming (which, in light of the Twitch incident, seems like a fault in our model potentially 🤔🤔🤔).

Much like live streaming fell neatly in my lap, a new opportunity fell in my lap as well. I'll fondly remember it as, [OpenShift.tv](https://openshift.tv) grew to something that much like a startup, exited. But no magical Chris Short v2 is waiting in the wings. The one thing the job was doing was increasing my burn rate to an unsustainable trajectory. This feedback is being heard loud and clear. The channel is being made more autonomous. I think that's a good thing for everyone. There's a standard way to produce streams (a web-based option also). The homegrown solution is documented (video recorded even). Standing up streaming rigs in Azure has been automated to the furthest reasonable extent. Folks are doing it regularly enough to get feedback into the process. Believe me, if I can do it multiple times a day with minimal dumpster fires, others can do it too.

Monday, after KubeCon, I'm shipping everything back to Red Hat. I'm going to take a few days off to hang out a little more with Max. Then start the next adventure. You'll still see me in the cloud native ecosystem. I'm not going too far.

Please understand that I am overwhelmed by the response and if you don't/haven't hear/heard from me directly. Please know that I am profoundly appreciative but also only human.

## People

[Red Hat at KubeCon + CloudNativeCon North America 2021](https://www.redhat.com/en/events/KubeConNA2021)  
Here's what's on Red Hat's plate this KubeCon. I'm involved in many things this week too. Here's where you'll find me this week in L.A. As always, if you feel intimidated coming to hang out with a group of Kubernetes folks, remember, they all put their pants on just like you do.

* Sunday: Writing this newsletter in wee hours of the morning; maybe having lunch with some local friends. Badge pickup is 2 PM to 6 PM local time in LACC West. I'm be around the JW Marriott and convention center area in the evening.
* Monday: Checking out all the things prior to my Day 0 events. Some meetings. Some real prep and setup for OpenShift Commons. This is my most open day of the week.
* Tuesday: [OpenShift Commons Gathering](https://commons.openshift.org/gatherings/OpenShift_Commons_Gathering_at_Kubecon_North_America_2021.html), [GitOpsCon 2021](https://events.linuxfoundation.org/gitopscon-north-america/program/schedule/), Contributor Workshop Docs Sprint at Contributor Summit NA 2021, [CloudNative.tv](https://www.twitch.tv/cloudnativefdn) Daily Wrap up @ KubeCon + CloudNativeCon, a reception, and some finding of friends.
* Wednesday: Breakfast, Keynotes (virtualy more than likely), 11:30 AM to 1:30 PM I'll be in the Red Hat booth, Kubernetes Project SIG Meet and Greet, then back in the booth to MC demos. Again, in the evening, I'll be around.
* Thursday: In the Red Hat booth to MC Demos, in the Red Hat booth to talk to folks, an event I'm not sure is public or not, then the panel talk with Bart Farrell, Kunal Kushwaha, Kaslin Fields, Matt Broberg, and I.
* Friday: Checking out, probably going to hang around the Red Hat booth/exhibitor hall, then head to the airport.

[Preventing Data Exfiltration with eBPF](https://goteleport.com/blog/preventing-data-exfiltration-with-ebpf/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish)  
Keep your data protected by developing security policies that target specific processes with eBPF. *SPONSORED*

[Cloudflare doesn't have to cut off copyright-infringing websites, judge rules](https://arstechnica.com/tech-policy/2021/10/cloudflare-doesnt-have-to-cut-off-copyright-infringing-websites-judge-rules/)  
Being a service provider has to be hard these days. There's no way to legitimately vet who is using your platform until after traffic is routed out of your network. Now, Cloudflare doesn't have to know in the case of copyright infringers. The ruling was based around, with or without Cloudflare, the content would still exist on the internet, it just wouldn't be as accessible. While making copyrighted content more accessible illegally is indeed against the law, Cloudflare isn't knowingly doing so. Therefore it can't be held liable. It's an interesting interpretation, yes. But, logically it makes sense. Whatever web server sitting behind Cloudflare will still be there even if Cloudflare isn't in the picture.

[U.S. to tell critical rail, air companies to report hacks, name cyber chiefs](https://www.reuters.com/technology/exclusive-us-tell-critical-rail-air-companies-report-hacks-name-cyber-chiefs-2021-10-06/)  
File this under, should've happened a long time ago. But, the interesting thing is these positions usually have a high turnover rate (for the C-suite at least). 24 percent of Fortune 500 CISOs have been in their current position for an average of 1 year, [according to reporting I read last year](https://cybersecurityventures.com/24-percent-of-fortune-500-cisos-on-the-job-for-just-one-year/).

[Tesla Ordered To Pay Former Black Employee Millions After It Turned A Blind Eye To Racial Abuse](https://peopleofcolorintech.com/front/tesla-ordered-to-pay-former-black-employee-millions-after-it-turned-a-blind-eye-to-racial-abuse/)  
"The firm, founded by billionaire Elon Musk, will now have to pay up after the San Francisco federal court jury awarded Diaz $130 million in punitive damages and $6.9 million (€5.9 million in damages for emotional distress, according to the New York Times." They were also quick to point out that the Tesla of today is very different. I will make a personal note here public. It has been a LONG time since I've heard anything positive about working at Tesla. That may be a different story now but, based off my limited knowledge, I would need to be thoroughly convinced real change has happened.

[It's a New Era for Mental Health at Work](https://hbr.org/2021/10/its-a-new-era-for-mental-health-at-work)  
It has taken a while. But, I finally feel empowered at work to speak up about my mental health issues. There are certain days of the year (even an entire 10 day span in September) where, I'm just not going to be in a happy place. My thoughts will be filled with death and disaster. Then there are days like Saturday morning where I'm up early due to anxiety. Then there are days like last Wednesday where I had a full blown panic attack during therapy (this is why I schedule therapy at the end of the work day). If it's going to impact your work performance, you should feel safe telling your boss about it. It is employers responsibility to understand that their people are people. Not just resources in a Gantt chart. I hope this trend continues.

[With So Many People Quitting, Don't Overlook Those Who Stay](https://hbr.org/2021/10/with-so-many-people-quitting-dont-overlook-those-who-stay)
If you're too worried about bailing water out of the boat, you might lose people through the hole in it. Make sure you tell the people next to you bailing water that you appreciate them OFTEN.

## Process

[LANTENNA: Exfiltrating Data from Air-Gapped Networks via Ethernet Cables](https://arxiv.org/pdf/2110.00104.pdf)  
"In this paper we present LANTENNA - a new type of electromagnetic attack allowing adversaries to leak sensitive data from isolated, air-gapped networks. Malicious code in airgapped computers gathers sensitive data and then encodes it over radio waves emanating from the Ethernet cables, using them as antennas. A nearby receiving device can intercept the signals wirelessly, decode the data, and send it to the attacker."

[Collaboration and Automation for Infrastructure as Code](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and quality of life features. [Free Demo](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Introducing: Chainguard, Inc.](https://chainguard.dev/posts/2021-10-07-introducing-chainguard)  
This is going to be an awesome company that will invoke change forever by, "making software supply chains secure by default." Game changers. [Kylie Robison wrote a great piece about Chainguard, Inc. for Business Insider](https://www.businessinsider.com/5-developers-google-vmware-chainguard-cybersecurity-2021-10). It may be paywalled, but if you can afford it, Kylie's work alone is worth the money. Also, Dan Lorenc, cofounder of [Chainguard](https://chainguard.dev), will be joining me for the [CloudNative.tv](https://www.twitch.tv/cloudnativefdn) KubeCon + CloudNativeCon Day 0 wrap up show on Tuesday.

[More details about the October 4 outage](https://engineering.fb.com/2021/10/05/networking-traffic/outage-details/)  
I don't use any Facebook services so this had no impact on me whatsoever. I generally disregard Facebook news, but it did make y'all more interested in BGP so that's a win. I will say, this Cloudflare blog post explains it from an outsiders perspective quite well: [Understanding How Facebook Disappeared from the Internet](https://blog.cloudflare.com/october-2021-facebook-outage/)

[Having a status page forced Comcast to fix my internet](https://chrisshort.net/having-a-status-page-forced-comcast-to-fix-my-internet/)  
"TL;DR: Comcast had a local area issue. I set up a status page for my house after many outages. The status page actively monitoring connectivity forced Comcast to look outside our home for a fix after several visits."

[First Data on Kubernetes Report Published](https://dok.community/blog/first-data-on-kubernetes-report-published/)  
"Regardless of which survey you read, the use of Kubernetes is on the rise in organizations of all sizes. While Kubernetes was initially designed for stateless workloads, the community has made major strides in supporting stateful workloads. Today, we are excited to announce DoKC [first research report about the state of data on Kubernetes](https://dok.community/dokc-2021-report/)!"

## Tools

[Tools to explore BGP](https://jvns.ca/blog/2021/10/05/tools-to-look-at-bgp-routes/)  
A lot of people got interested in BGP this week (FINALLY!). [What is BGP?](https://www.cloudflare.com/it-it/learning/security/glossary/what-is-bgp/) People were pinging me asking if one BGP package was better than another. Then Julia Evans dropped this magnificent piece which I highly recommend you read and bookmark all the tools for. You can watch routing on the internet change in real time. I used to maintain an autonomous system (ASN), a high level one too, in the early 2000s. BGP is really cool but, very susceptible to exploitation from a sufficiently skilled enough actor. I'm pulling these in from the notes this week: [OpenBGPD](https://www.openbgpd.org/) and [BGP.Tools](https://bgp.tools/).

Find bugs that are hidden across billions of transactions by comparing thousands of highly unique dimensions? No problem! Understand your code like never before. [Use Honeycomb for free](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). Guess less and know more. *SPONSORED*

[What is under the hood of Kubernetes? - Part 1](https://blog.softwheel.io/what-is-under-the-hood-of-kubernetes-1/)  
"This article is Part 1 of my K8S deep dive article, What is under the hood of Kubernetes?, which talks about the Definition and Components. In Part 2, we will touch a little bit on the implementations of some critical components."

[Hurl - Run and Test HTTP Requests](https://hurl.dev/index.html)  
I really kinda fell in love with this tool while I was reading the documentation. "Hurl is a command line tool that runs HTTP requests defined in a simple plain text format." Check it out, I'm curious what you think.

[Apache fixes actively exploited web server zero-day](https://therecord.media/apache-fixes-actively-exploited-web-server-zero-day/)  
Hide your kids, backup your configs, `yum update && yum upgrade httpd`, or `apt upgrade apache2` and move on with life. 

[Trigger a Kubernetes HPA with Prometheus metrics](https://sysdig.com/blog/kubernetes-hpa-prometheus/)  
"In this article, you'll learn how to configure Keda to deploy a Kubernetes HPA that uses Prometheus metrics."

[GoFullPage - Full Page Screen Capture](https://chrome.google.com/webstore/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl/related)  
Do you have a web UI that's essentially the only interface into a thing in your environment? Yeah, they're out there still and it sucks. But, also things like Zoom accounts where the account settings impact the client settings, it's grab to be able to nab all those pages and pages of options in one click. Maybe this will help you out. It helped me this week.

[trailofbits/algo](https://github.com/trailofbits/algo)  
Set up a personal VPN in the cloud (Ansible for WireGuard and IPsec VPNs). What makes me suggest it is this: "It uses the most secure defaults available." Personally, I'm using Tailscale. But, I do understand the desire to own as much of the stack as possible.

[parca-dev/parca](https://github.com/parca-dev/parca)  
Continuous profiling for analysis of CPU, memory usage over time, and down to the line number. Saving infrastructure cost, improving performance, and increasing reliability.

## DevOps'ish Tweet of the Week

[![Blažej Krajňák (@BlazejKrajnak) on Twitter: "Because of missing DNS records for Facebook.com, every device with FB app is now DDoSing recursive DNS resolvers. And it may cause overloading..."](https://shortcdn.com/devopsish/238-devopsish-tweet-of-the-week.png)](https://twitter.com/blazejkrajnak/status/1445063232486531099)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/238/notes.md) to see what didn't make it to the newsletter but are still worth your time.
