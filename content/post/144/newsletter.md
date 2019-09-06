+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-09-08T07:00:00Z
description = ""
draft = false
slug = "144"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "weekly newsletter", "DevOps news", "Kubernetes news"]
title = "144: Your 39 bps matters, "

+++

This week I read about a study of 17 languages that suggests humans, "no matter how fast or slowly languages are spoken, they tend to send information at about the same rate: [39 bits per second](https://www.sciencemag.org/news/2019/09/human-speech-may-have-universal-transmission-rate-39-bits-second?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144), about twice the speed of Morse code." The study points out that some languages are clearly "faster" than others but, [a steady average rate of 39.15 **bits per second** (bps) kept coming up](https://advances.sciencemag.org/content/5/9/eaaw2594?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144). This study fascinated me since I talk to people as part of my work. My mind jumped to being on stage somewhere and spewing 1s and 0s out at a measly **17.6 kilobytes per hour**. That is such a low data rate. It's relatively equal to [this random file I found on GitHub](https://raw.githubusercontent.com/cttobin/ggthemr/master/misc/build.txt?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144). Telemetry data alone on some of the oldest satellites I ever worked with was 4 kbps of status, position, orientation, and other measurements. That's a continuously updated status page, and it only needed 4 kbps.

Meanwhile, there I am, rendered inadequate with my paltry 39.15 bps. To add insult to injury, the thing giving me impostor syndrome is a device floating in space. No one in the room can see or hear it but, I theorize it is broadcasting 4 kbps at earth at that very moment.

But, then I realize that the 4 kbps is 1s and 0s that are encoded (and hopefully encrypted). That means there are specs, protocols, languages, and a lot of sand doing math to glean anything significant from that data. Then to get that data from [Layer 4 to Layer 7](https://chrisshort.net/drawings/osi-model/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144)  requires even more on top of that (frameworks, other protocols, more languages) to present you with one screen of that telemetry data in a human consumable format. When you take this path of including all the things that have to come together to make that 4 kbps satellite telemetry usable; you suddenly realize it's not the quantity of data that matters. How your transmission is used is what is vital. It's the ability to use that data for something meaningful after it's transmitted. The human voice has that amazing capability because it's attached to a brain. The brain can take decades of inputs and put them into coherent, digestible, and meaningful human-understandable objects. This is why People matter far more than Process or Tools in DevOps. The value of your people is in their ever-increasing ability to turn their inputs into value elsewhere.

Take it a step further and consider everything outside of that 39 bits per second *metadata*. Now, put yourself in a webinar or a Zoom call. Think of all the protocols, frameworks, standards, and other components that make up the hardware and software between you and the person on the other end, speaking and presenting. That now falls under our definition of metadata. That's a ton of metadata to send the paltry 39 bits per second a voice can carry. This is why metadata is so valuable to folks. Because there is so much of it, [metadata often ends up being more useful than the content of the conversation itself](https://www.theguardian.com/film/2015/nov/09/a-good-american-review-nsa-whistleblower-william-binney-911-world-trade-centre?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144). This is why being mindful of others' privacy and concerns as humans are essential in our industry. The thing you're doing today could be generating value you never thought possible.

## DevOps'ish Last Week's Top Five

1. [My Time at Google and After](https://medium.com/@jennifer.blakely/my-time-at-google-and-after-b0af688ec3ab)
1. [Document Like a Scientist](https://noti.st/karissapeth/g3vUiw)
1. [DevOps terms: 10 essential concepts, explained](https://enterprisersproject.com/article/2019/8/devops-terms-10-essential-concepts)
1. [Dell announces new Linux XPS 13 developer edition 7390 laptop](https://www.cyberciti.biz/linux-news/dell-announces-new-linux-xps-13-developer-edition-7390-laptop/)
1. [Female-free speaker list causes PHP show to collapse when diversity-oriented devs jump ship](https://www.theregister.co.uk/2019/08/27/php_europe_cancelled/)

[See the top ten →](https://devopsish.com/144/notes/)

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[See more Events →](https://devopsish.com/144/events/)

## People

[Veronica Hanus](https://www.linkedin.com/in/veronicahanus/) is looking for a full-time developer advocate role. Veronica is based out of NYC, is okay with remote, and would consider relocation for the right opportunity. In talking to Veronica at DevOpsDays Chicago and via Zoom this week I learned that she is exactly what a company trying to level up their Developer Relations program needs. Veronica's experiences will bring a wealth of knowledge to any organization.

## Process

PROCESS

## Tools

[**Full Alerting Coverage Without the Toil**](https://www.bluematador.com/devopsish)  
Balance rapid feature development and production stability with alert automation for your cloud infrastructure from Blue Matador. Activate alert automation in your cloud infrastructure today with our free trial. *SPONSORED*

TOOLS

## DevOps'ish Tweet of the Week

{{< tweet 1169713613088722944 >}}

[See Notes →](https://devopsish.com/144/notes/)
