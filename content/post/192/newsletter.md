+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-11-15T07:00:00Z
description = ""
draft = false
slug = "192"
tags = []
title = "DevOps'ish 192"

+++

This week has been quite a blur. Working backward (literally and figuratively), we’re re-entering lockdown as a household again. A visit with my pain management doctor on Thursday in which he told me the hospital we both live near has seen COVID-19 admissions double this week pushed things very front of mind. [A statement from our state’s governor on Thursday](https://news.yahoo.com/whitmer-michigan-worst-part-pandemic-220509661.html) put things into motion towards lockdown (which she can no longer mandate thanks to our state legislature passing a law preventing her from doing so; nuts, I know). With lots of data in hand, we made the hard decision Thursday night. I know the readers in European nations (and probably elsewhere) are  wondering, "How weren’t you in lockdown sooner?!?" Well, there’s not a state-level or national-level mandate to do so. We’re flying blind here in the US, and each household has to make its own decision. This is why we’re in the situation we’re in (again). Max took it in stride, saying that he’d still be able to see his friends on Zoom with enthusiasm. Our kids are so resilient. But, I am concerned about the long term effects of all the tumult.

[Dan Kohn's memorial](https://www.gatheringus.com/memorial/dan-kohn/5732?locale=en_US&c=934) was also on Friday. I think Ian Coldwater sums it up nicely with [their tweet](https://twitter.com/IanColdwater/status/1327442525909446656), “HOW ARE WE GOING TO KUBECON NEXT WEEK WITH NO DAN AND WITHOUT EACH OTHER IT JUST ISN’T RIGHT[.]” They’re right; this doesn’t feel right. But, we’re going to push forward because Dan would want us to. KubeCon is a part of the healing process. Dan won’t be the focus next week; the fruits of his labor will be. That feels right.

Even though we can’t network in person, we can network in the [Kubernetes Slack](https://slack.k8s.io/), [CNCF Slack](https://slack.cncf.io/), [DevOps'ish Telegram](https://t.me/devopsish), [OpenShift.tv](https://openshift.tv), and countless other places. Let’s build relationships through text, then video, and then finally, when the time is right, in person like we’re advancing through technology in the late 1990s, early 2000s again. We did this once as a world, lest we forget. We just weren’t stuck at home ALL the time.

And yes! Next week is [KubeCon + CloudNativeCon NA 2020](https://www.cncf.io/events/kubecon-cloudnativecon-north-america-2020/)! I will be trying to be in all possible locations to make myself available and useful as best I can be. I will admit, I’m not as far along in my planning of exactly what I’m doing next week as I should be. But, I know I’ll be helping with [OpenShift Commons Gathering](https://commons.openshift.org/gatherings/Kubecon_North_America_Virtual_OpenShift_Commons_Gathering_2020.html), including an MST-3000 style take with a couple of coworkers on a few of the sessions. We’ll also be doing [a ton of project-specific office hours](https://red.ht/streamcal) as well during KubeCon, so please jump into the ones that interest you most and ask those tough questions; we’ve got the experts assembled. More KubeCon prep help is in the newsletter.

**DevOps'ish is brought to you by** [**Accurics**](https://www.accurics.com/). They're cool people doing cool things with cloud native security. Check them out! [Scanning Kubernetes IaC configurations with Terrascan](https://community.accurics.com/t/scanning-kubernetes-iac-configurations-with-terrascan/51)

## People

[What I Learned From Bombing a Technical Interview](https://www.ceoraford.com/posts/what-i-learned-from-bombing-a-technical-interview/)  
I always love pieces like this. I learned so much from bombing my AWS interview way back in 2012. This article is full of good interviewing skills.

[At Work in Pain S01E01](https://www.youtube.com/watch?v=xnCKeeXqElQ&feature=youtu.be)  
"The first episode of At Work in Pain, with [Chris Short](https://chrisshort.net) and [Julia Ferraioli](https://www.juliaferraioli.com/). During this video, Chris and I kick it off, cover how we cope with pain, and how it we communicate it -- or not -- at work." Julia came to me with this idea and I'm all for it. It's okay for me to hurt. I got injured, y'all. We don't want sympathy. We want understanding.

[The POPCAST: Veterans Day Special with Chris Short and Marky Jackson](https://www.youtube.com/watch?v=EEjiYVYdwwk&feature=youtu.be)  
"A very special Veterans day POPCAST.  in this episode we talk to two veterans who are in the cloud native and Kubernetes space.  Red Hat's Chris Short and CDF's Marky Jackson.  We discuss their service, their sacrifice, their love of the open source community and so much more.  Please stay til the end as both these fellows really are open about what serving their country means to them and coming back and enabling others in the community.  Chris and Marky are absolute class acts and it was an honor to capture their stories." Thank you, Dan Papandrea, for doing this. It ties into the [At Work in Pain](https://www.youtube.com/channel/UC8jhUEJ-K_QfDWbmpmwi4XA) series.

[Millions of Remote Workers Are Now Thinking About Moving](https://thenewstack.io/millions-of-remote-workers-are-now-thinking-about-moving/)  
I worked on and off from home for years before working from home became the norm for me. Our move to Michigan was precipitated around family (as noted in the article, many others are now making that decision). Yes, it did involve an office job for the first six months we were here. But, even then I feel like I worked as much from the office as I did from home due to construction, weather, etc. The point is, we've hit the point where you can probably live where you want (so long as infrastructure is in place to support your work) and work where you want. Something that was not possible at a lot of `<INSERT BIG TECH CORP HERE>` until recently.

[Covid vaccine: Ex-IBM CEO Rometty says remote work is here to stay](https://www.cnbc.com/2020/11/11/covid-vaccine-ex-ibm-ceo-rometty-says-remote-work-is-here-to-stay.html)  
"'I actually don’t think these technology trends are going to reverse themselves,' Rometty told CNBC anchor Karen Tso." I think Ginny Rometty is absolutely right here. Even once say 50%-75% of the population is vaccinated, I still wouldn't be comfortable going into an office (at this point in time, knowing what little we know). Organizations need to treat this as a psychological safety issue. Remember, [psychological safety](https://rework.withgoogle.com/print/guides/5721312655835136/) is the foundation on which everything else in your organization depends upon.

[Pre-Kubecon Warm Up Session - Diane Mueller, Chris Short, Jen Madriaga, and Josh Berkus (Red Hat)](https://www.youtube.com/watch?v=GKLBqq0UoeQ)  
"CNCF's Kubecon week is coming up fast, it can be overwhelming to navigate all the virtual talks, chat rooms, BoFs, Office Hours, booths. [Here are] our tips and tricks to avoid virtual burn out, hear our top picks for talks, co-located sessions, best snack foods and stretches to ensure you maximize your Kubecon experience! From Day Zero to binge watching all the sessions you missed, to virtual after parties!"

## Process

People might say traces can be used anywhere, but let’s face it: you absolutely need them when you’re dealing with distributed systems and microservices. You probably don’t have them yet because instrumenting your apps to collect them will get you super table-flippy. (╯°□°)╯︵ ┻━┻

Until now.

Download [Distributed Tracing: A Guide to Microservices & More](https://info.honeycomb.io/distributed-tracing-with-honeycomb-lp-devopsish?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=distributed-tracing-guide-for-microservices-and-more-honeycomb-lp-devopsish) and get the tracing you deserve the easy peasy way. Guess less & know more with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[This is how I git](https://daniel.haxx.se/blog/2020/11/09/this-is-how-i-git/)  
Daniel Stenberg, of libcurl fame, shares "how to work with git in a smooth way when developing, bug-fixing or extending curl - or how I do it." Some good nuggets in here.

[Ant Group IPO: Chinese President Xi Jinping decided to halt Ant's IPO: WSJ](https://economictimes.indiatimes.com/markets/ipos/fpos/chinese-president-xi-jinping-decided-to-halt-ants-ipo-wsj/articleshow/79206450.cms)  
As I mentioned last week, [Jack Ma said some things](https://technode.com/2020/11/09/china-voices-the-unsigned-op-eds-that-foreshadowed-ant-group-ipo-suspension/), and the CCP got pissed; Xi Jinping specifically.

[Many websites will stop working on older Android versions in 2021](https://www.androidpolice.com/2020/11/07/many-websites-will-stop-working-on-older-android-versions-in-2021/)  
I mean, yes, this sucks. But, aren't these older Android versions vulnerable as hell anyway?

[Google Photos Just Made the Case for Breaking Up Big Tech](https://onezero.medium.com/google-photos-just-made-the-case-for-breaking-up-big-tech-420dc6b5d375)  
I have a policy generally [against linking to Medium](https://nomedium.dev) posts. But, this one brings up a very good point. Google literally trounced any real competition here. "The losers are all the rival photo apps that Google Photos crushed on its way to the top, including startups such as Everpix, Loom, and Picturelife." I used Google Photos for a litle bit and dumped it because I actually got a good photo backup strategy in place. But, my wife has used Google Photos for years and is glad that I went ahead and made sure she's in a family account with me sharing 2 TB of storage in Apple's iCloud for photo backups. Like me, Julie can safely purge whatever she wants out of Google Photos and delete the app. Google is essentially now double-dipping users by 1. harvesting data and image analysis and 2. forcing folks to actually spend money now for a service that was free. Zoom is doing the same thing now that it has a lion's share of the market. It's small things that you had but now have to pay for. Those add up over time and eventually, you end up pissing off the customers, lose market share, and end up not making money.

## Tools

[Create your first Knative app](https://opensource.com/article/20/11/knative)  
"Knative is a great way to get started quickly on serverless development with Kubernetes."

[Eleven Years of Go](https://blog.golang.org/11years)  
"It’s been a tough year, but we've kept Go development moving forward and accumulated quite a few highlights." A tough year... That's putting it mildly.

[Apple drops macOS Big Sur on the world - and it arrives with a thud, sound of breaking glass, sirens in the distance...](https://www.theregister.com/2020/11/13/apple_releases_big_sur/)  
Lots of problems emanating from the Tim's spaceship this week. Big Sur had/has problems. It took half a day to get my new iPhone fully operational. And the [M1 Apple Silicon](https://www.phoronix.com/scan.php?page=news_item&px=Apple-Silicon-M1-Macs) gear has, well, [missing features](https://www.engadget.com/apple-m1-egpu-usb-16gb-224346108.html).

[Apple Retreats After Threatening Devs Of Linux And Unix Shells With App Store Expulsion](https://hothardware.com/news/apple-threatens-shell-app-developers-and-reverses-decision)  
More tools for us is a good thing, Apple. Let us use the compute we own.

[FYI: Alibaba Cloud says it has robot sysadmins that swap faulty disks in four minutes](https://www.theregister.com/2020/11/12/alibaba_singles_day/)  
This is just cool. Also, where was this when I had to swap backup tapes by hand?

[ComodoSecurity/openedr](https://github.com/ComodoSecurity/openedr)  
Open EDR public repository

[konveyor/move2kube](https://github.com/konveyor/move2kube)  
Move2Kube is a command-line tool that accelerates the process of re-platforming to Kubernetes/Openshift.

## DevOps'ish Tweet of the Week

[![DevOps'ish 192 Tweet of the Week](/images/192-devopsish-tweet-of-the-week.png)](https://twitter.com/gvanrossum/status/1326932991566700549)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/192/notes/) to see what didn't make it to the newsletter.
