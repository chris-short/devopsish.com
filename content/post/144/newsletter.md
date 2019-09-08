+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-09-08T07:00:00Z
description = "Your 39 bps matters, happy little hybrid clouds, Kubernetes with a side of service mesh, HA SQLite, and more"
draft = false
slug = "144"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "weekly newsletter", "DevOps news", "Kubernetes news"]
title = "144: Your 39 bps matters, happy little hybrid clouds, Kubernetes with a side of service mesh, HA SQLite, and more"

+++

This week I read about a study of 17 languages that suggests humans, "no matter how fast or slowly languages are spoken, they tend to send information at about the same rate: [39 bits per second](https://www.sciencemag.org/news/2019/09/human-speech-may-have-universal-transmission-rate-39-bits-second?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144), about twice the speed of Morse code." The study points out that some languages are clearly "faster" than others but, [a steady average rate of 39.15 **bits per second** (bps) kept coming up](https://advances.sciencemag.org/content/5/9/eaaw2594?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144). This study fascinated me since I talk to people as part of my work. My mind jumped to being on stage somewhere and spewing 1s and 0s out at a measly **17.6 kilobytes per hour**. That is such a low data rate. It's relatively equal to [this random file I found on GitHub](https://raw.githubusercontent.com/cttobin/ggthemr/master/misc/build.txt?utm_source=devopsish&utm_medium=newsletter&utm_campaign=144). Telemetry data alone on some of the oldest satellites I ever worked with was 4 kbps of status, position, orientation, and other measurements. That's a continuously updated status update, and it only needed 4 kbps.

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

[Police hijack a botnet and remotely kill 850,000 malware infections](https://techcrunch.com/2019/09/01/police-botnet-takedown-infections/) — Taking over a bad thing to do a good thing is generally seen as good, right?

[Bang Bros Bought a Huge Porn Doxing Forum and Set Fire to It](https://www.vice.com/en_us/article/9keb4d/bang-bros-bought-pornwikileaks-doxing-forum-and-set-fire-to-it) — "Over 15,000 performers' real names were listed here. Some had phone numbers, addresses, even family members names posted as well. That type of information wasn't voluntarily submitted. It was stolen from anyone that had it posted." That's one way to make an impact in your industry. Also, a great example of taking over a bad thing to do a good thing.

[Chinese tech firm Huawei says it was hacked by the United States](https://www.grahamcluley.com/chinese-tech-firm-huawei-says-it-was-hacked-by-the-united-states/) — To be honest, I don't think many Americans are going to bat an eye at US government cyber operations against China or Chinese industry. The legalities of the operations aside, Chinese government affiliated groups have been hacking US companies for *years*.

[3 Ways to Motivate Yourself When You Don't Have a Deadline](https://hbr.org/2019/09/how-to-motivate-yourself-when-you-dont-have-a-deadline) — Create a system to build artificial deadlines. Incentivize yourself where your boss might not even realize you need one.

[Every Computer Science Degree Should Require a Course in Cybersecurity](https://hbr.org/2019/08/every-computer-science-degree-should-require-a-course-in-cybersecurity) — I have taken a ton of security related courses. It blows my mind how little security is taught in school.

[The Rise of the Serverless Architect](https://read.acloud.guru/the-rise-of-the-serverless-architect-8800d16e9cd4?gi=cb50b1d51de7) — "The focus has expanded to the entire application lifecycle." Also, serverless admin was too ironic.

## Process

[A Manager's Guide to Kubernetes Adoption](https://unixism.net/2019/08/a-managers-guide-to-kubernetes-adoption/) — Is your organization *really* ready for Kubernetes?

[Why doesn't anyone weep for Docker?](https://www.techrepublic.com/article/why-doesnt-anyone-weep-for-docker/) — For *very* good reasons.

[Tired of Stack Overflow](https://arp242.net/stackoverflow.html) — "Note: this post is something of a rant, and uses strong and emotional language. It's born out of a years-long frustration with seeing almost every single suggestion to make Stack Overflow a friendlier place not just rejected, but met with hostility."

[Accelerate State of DevOps Report 2019](https://www.praqma.com/stories/state-of-devops-report-2019/) — An analysis of the Accelerate State of DevOps Report. "Additionally, more than a third of the low performers already have automatic provisioning and deployment to testing environments. This is truly a feather in the cap of the cloud providers and the Cloud Native Computing Foundation." That's an interesting tidbit.

[Microsoft set to close licensing loopholes, leave cloud rivals high and dry](https://www.computerworld.com/article/3435104/microsoft-set-to-close-licensing-loopholes-leave-cloud-rivals-high-and-dry.html) — Licensing an operating system is hard. Licensing an OS with the same model in the cloud and on-prem just doesn't work. Much like how DevOps has changed the industry, the licensing has to change along with that. Now, with that being said, it's possible Microsoft could've gone about this in a more diplomatic way.

[Partners to AWS: 'We're living in a multi-cloud world – get over it'](https://www.arnnet.com.au/article/665835/partners-aws-we-re-living-multi-cloud-world-get-over-it/) — "Customers are increasingly using services from multiple cloud providers, compelling partners to be 'open-minded' and 'agnostic' about who they work with. So why is AWS putting the brakes on this?" Every other cloud, software, and IT vendor are talking about hybrid or multi cloud environments. Does AWS really think it's going to take the entire market? That's a little disturbing, there's more than enough to go around.

## Tools

[**Full Alerting Coverage Without the Toil**](https://www.bluematador.com/devopsish)  
Balance rapid feature development and production stability with alert automation for your cloud infrastructure from Blue Matador. Activate alert automation in your cloud infrastructure today with our free trial. *SPONSORED*

[How I moved my Kubernetes project from DigitalOcean to Amazon EKS in 4 hours and why](https://telescope.ac/battlefield/digital-ocean-to-amazon-in-4-hours) — How one protocol can ruin a Kubernetes experience. Also, given how many Kubernetes options there are today, a tale of how choice makes a better experience for users.

[How Kubernetes Changed Everything with Brendan Burns (Microsoft), Tim Hockin (Google Cloud), Joe Beda (VMware), and Aparna Sinha (Google) [Video]](https://finance.yahoo.com/video/kubernetes-changed-everything-brendan-burns-213336555.html) — The history and future of Kubernetes.

[Kubernetes Workloads in the Serverless Era: Architecture, Platforms, and Trends](https://www.infoq.com/articles/kubernetes-workloads-serverless-era/) — "The brilliance of Kubernetes lies in its extensibility for new workloads through the Pod abstraction, which also supports the emergence of new cloud-native application patterns." Pods are cool but have you seen CRDs?

[Creating a PostgreSQL Cluster with Kubernetes CRDs](https://info.crunchydata.com/blog/creating-a-postgresql-cluster-with-kubernetes-crds) — Speaking of CRDs...

[Architecting Kubernetes clusters — choosing a worker node size](https://learnk8s.io/kubernetes-node-size/) — How do you choose the right size? Very carefully.

[Announcing Maesh, a Lightweight and Simpler Service Mesh Made by the Traefik Team](https://blog.containo.us/announcing-maesh-a-lightweight-and-simpler-service-mesh-made-by-the-traefik-team-cb866edc6f29?gi=a78282869250)

[Dqlite - High-Availability SQLite](https://dqlite.io/) — "When you absolutely, positively need SQLite, accept no substitutes." —Ordell Robbie

[Curl Cookbook](https://catonmat.net/cookbooks/curl) — "I love to cook with curl. Here are some useful curl recipes I often use."

[danielsagi/kube-dnsspoof](https://github.com/danielsagi/kube-dnsspoof) — A POC for DNS spoofing in kubernetes clusters. Runs with minimum capabilities, on default installations of kuberentes.

[IBM/kone](https://github.com/IBM/kone) — Build and deploy Node.js application on Kubernetes

[hunterlong/statping](https://github.com/hunterlong/statping) — Status Page for monitoring your websites and applications with beautiful graphs, analytics, and plugins. Run on any type of environment.

## DevOps'ish Tweet of the Week

{{< tweet 1169713613088722944 >}}

[See Notes →](https://devopsish.com/144/notes/)
