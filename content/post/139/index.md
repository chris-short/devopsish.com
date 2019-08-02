+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-08-04T07:00:00Z
description = ""
draft = false
slug = "139"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "weekly newsletter", "security", "DevOps news", "Kubernetes news", "JEDI", "Oracle"]
title = "139:"

+++

INTRO

[**Get $100 to Demo Blue Matador The Alert Automation Service**](https://www.bluematador.com/demo-for-100-devopsish)  
Blue Matador is alert automation for AWS and Kubernetes environments. Our proactive alerts take the time and toil out of monitoring. See production issues before anyone else. We're so confident you'll love it that we're offering $100 to demo it with our team. *SPONSORED*

## DevOps'ish Last Week's Top Five

1. [The cloud skills shortage and the unemployed army of the certified](https://itnext.io/the-cloud-skills-shortage-and-the-unemployed-army-of-the-certified-bd405784cef1)
1. [Have you ever wondered what the hiring process was 20 years ago compared to today? Probably not, but I'll tell you anyway](https://www.reddit.com/r/cscareerquestions/comments/brjexy/have_you_ever_wondered_what_the_hiring_process/)
1. [Kubernetes Deployments: The Ultimate Guide by Jérôme Petazzoni](https://semaphoreci.com/blog/kubernetes-deployment)
1. [The Kubernetes Hierarchy of Needs](https://thenewstack.io/the-kubernetes-hierarchy-of-needs/)
1. [6 Causes of Burnout, and How to Avoid Them](https://hbr.org/2019/07/6-causes-of-burnout-and-how-to-avoid-them)

## People

[**X-Team Is Hiring a Team of DevOps Engineers (Remote)**](https://x-team.com/remote-devops-engineer-jobs/?utm_source=devopsish&utm_medium=email-ad)  
We are looking for passionate DevOps engineers to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. [Join X-Team](https://x-team.com/remote-devops-engineer-jobs/?utm_source=devopsish&utm_medium=email-ad) *SPONSORED*

PEOPLE

[**The Business Value of Developer Relations**](https://cshort.co/2K9XsgV)  
Discover the true value of Developer Relations as you learn to build and maintain positive relationships with your developer community. Use the principles laid out in this book to walk through your company goals and discover how you can formulate a plan tailored to your specific needs. *SPONSORED*

## Process

[Will complexity kill Kubernetes?](https://www.infoworld.com/article/3409980/will-complexity-kill-kubernetes.html) — Short answer: Complexity kills everything so, yes. However, the author disagrees (for good reason), "Probably not. While Hadoop got more complicated with age, Kubernetes keeps getting easier. While Kubernetes will likely never be 'easy,' per se, its complexity differs from that of Hadoop in critical ways, paving the way for Kubernetes to remain an industry standard for years to come." I don't think Hadoop is a good analog to Kubernetes (let's face it, no one wants Kubernetes to become OpenStack). But, it does speak to a community that tries to grease the skids in versus raising the bar higher and higher.

[Other people's messes by Jessica Kerr](https://blog.jessitron.com/2019/07/21/other-peoples-messes/) — Like a lot of things in life, When it comes to code, context matters. It's a lot less messy when you understand the why behind it.

[IBM-Red Hat: Should developers worry we're headed back to the 1990s?](https://venturebeat.com/2019/07/20/ibm-red-hat-should-developers-worry-were-headed-back-to-the-1990s/) — "A dated playbook of boxing in and trying to control developers through a Big Blue (and now Red) stack could ultimately harm IBM's chances of achieving cloud relevancy." Huh. I thought the heading back to the 90s bit was the AWS, GCP, Azure, and Oracles of the world (vendor lock-in). I guess with Red Hat being a part of IBM now this was bound to happen. But, the author believes that IBM is now going to start shoving Red Hat products down peoples' throats. I guess if IBM didn't already have product in a space maybe? But, it's not like IBM didn't have anything to sell until a few weeks ago. When something is new and shiny, it's going to be at the top of people's minds. Once news of the deal settles and the sales training is into sustainment, I hope folks start to forget Red Hat is a part of IBM. That'd be great.

[Decoupling database migrations from server startup: why and how](https://pythonspeed.com/articles/schema-migrations-server-startup/) — Your code and database schemas shouldn't have to march in lockstep with their releases. Thinking of the database as another codebase (the schema certainly is) has been something I've been trying to get through to folks for a long time on.

[How a Production Outage Was Caused Using Kubernetes Pod Priorities](https://grafana.com/blog/2019/07/24/how-a-production-outage-was-caused-using-kubernetes-pod-priorities/) — Resource limits are EVERYTHING. If you don't use them, WHY!?!

[6 Tech Giants Located in Detroit](https://blog.repurpose.co/6-tech-giants-located-in-detroit) — Don't sleep on Detroit, y'all. When I'm doing non-work speaking, I put [pictures from Detroit](https://devopsish.com/138/awesome-detroit.jpg) at the beginning of the slides. I want to show people it's not what they hear and see in the news. Detroit is an amazing city!

## Tools

[The RedMonk Programming Language Rankings: June 2019](https://redmonk.com/sogrady/2019/07/18/language-rankings-6-19/) — JavaScript came in at #1 (duh). Java, Python, and PHP rounded out the Top 4. CSS is #7 🤢. TypeScript moved up two spots to #10. Go slid to number 16 while Perl showed up at number 18. "Go's lack of versatility – perceived or otherwise – has limited its upside."

[Kubernetes and Containers Best Practices - Health Probes](https://www.magalix.com/blog/kubernetes-and-containers-best-practices-health-probes) — Use Kubernetes `readinessProbe` and the `livenessProbe` as part of high-observability principle.

[Istio the Easy Way (Again!)](https://medium.com/solo-io/istio-the-easy-way-again-b0504347b7ce) — Managing service meshes is starting to get easier.

[xkcd: Spreadsheets](https://xkcd.com/2180/) — It's funny because it's true.

[Understanding Docker container escapes](https://blog.trailofbits.com/2019/07/19/understanding-docker-container-escapes/) — "The `--privileged` flag introduces significant security concerns, and the exploit relies on launching a docker container with it enabled. When using this flag, containers have full access to all devices and lack restrictions from seccomp, AppArmor, and Linux capabilities."

[Apologies for try-ing](https://medium.com/@rocketlaunchr.cloud/apologies-for-try-ing-6cb093455ce8) — Oh Go... There never seems to be any shortage of dramatics in the Go community. "Once the `try` proposal was rejected, the `must` proposal (which can exist independently) unfortunately got prematurely rejected as cannon fodder."

[Intel Prepares To Graft Google's Bfloat16 Onto Processors](https://www.nextplatform.com/2019/07/15/intel-prepares-to-graft-googles-bfloat16-onto-processors/) — "Essentially, they were able to get the benefit of the 16-bit throughput for free, the slight caveat being that some of the work, like the fused-multiply add (FMA), needs an FP32 accumulator. But, according to Dubey, depending on how much you're able to keep the computations in the bfloat16 realm, you should be able to improve training speed by at least 1.7x.  Which is a big deal when training a model takes days or even weeks."

[Get started with Kubernetes (using Python)](https://kubernetes.io/blog/2019/07/23/get-started-with-kubernetes-using-python/) — A walkthrough of taking some Python code, containerizing it, and deploying it to a Kubernetes cluster.

[Remote SSH access with Visual Studio Code](https://code.visualstudio.com/blogs/2019/07/25/remote-ssh)

[Retrotechtacular: The Floppy Disk Orphaned By Linux](https://hackaday.com/2019/07/26/retrotechtacular-the-floppy-disk-orphaned-by-linux/) — A complaint about this came up a few weeks ago in the [DevOps'ish Telegram group](https://t.me/devopsish). Folks are having issues with Packer as a result. I remember using a virtual floppy from something semi-regularly when I was at Hosted Solutions four years ago. Are you using a floppy disk or drive for anything still?

[Underscoring the "private" in private key](https://koen.io/2019/07/26/underscoring-the-private-in-private-key/) — The private key should be KEPT PRIVATE. It's not to hand out, ever (with very, very few exceptions).

[Goodbye Docker: Purging is Such Sweet Sorrow](https://zwischenzugs.com/2019/07/27/goodbye-docker-purging-is-such-sweet-sorrow/) — I still need Docker on my Mac from time to time and it irritates me to no end.

[jbeda/kinecraft](https://github.com/jbeda/kinecraft) — Start to a Minecraft k8s operator by Joe Beda

[eko/monday](https://github.com/eko/monday) — A dev tool for microservice developers to run local applications and/or forward others from/to Kubernetes SSH or TCP

[envoyproxy/envoy-wasm](https://github.com/envoyproxy/envoy-wasm) — Playground for Envoy WASM filter

[herbrandson/k8dash](https://github.com/herbrandson/k8dash) — Simple Kubernetes realtime dashboard and management

[tumblr/docker-registry-pruner](https://github.com/tumblr/docker-registry-pruner) — Tool to apply retention logic to docker images in a Docker Registry

[geerlingguy/docker-ubi8-ansible](https://github.com/geerlingguy/docker-ubi8-ansible) — UBI 8 Docker container for Ansible playbook and role testing.

## DevOps'ish Tweet of the Week

[![DevOps'ish Tweet of the Week][tweet]](https://twitter.com/ruhbehka/status/1154142091620102150)

[tweet]: 138-tweet-of-the-week.png

Notes from this week's issue can be found on [GitHub](https://github.com/chris-short/devopsish.com/blob/master/content/post/138/notes.md)
