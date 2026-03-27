---
author: Chris Short
categories:
- Weekly
- Newsletter
- '2026'
date: '2026-02-01'
draft: false
slug: '295'
title: "DevOps'ish 295: death of an ingress, Amazon layoffs, my desk, and more"
---

![Batman smacks Robin meme; this time Robin dared to mention Ingress NGINX](https://shortcdn.com/devopsish/ingress-nginx-meme.jpeg)

Next month (March 2026), a widely used Kubernetes ingress controller is going to reach [end of life: **Ingress NGINX**](https://kubernetes.io/blog/2026/01/29/ingress-nginx-statement/). This is one of those things that if you don't replace it in time, you're not going to know if you're compromised until it's too late. There will be no security notices, updates of any kind, or any kind of continued maintenance. The time to start changing your [ingress controllers](https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/) or migrating to [Gateway API](https://gateway-api.sigs.k8s.io/guides/getting-started/), if you haven't already, is NOW. Run this as cluster admin to identify all your instances of Ingress NGINX:

```kubectl get pods --all-namespaces --selector app.kubernetes.io/name=ingress-nginx```

My job hunt continued this week (and I managed to catch whatever sickness was afflicting Julie and Max). If you haven't heard, [I'm looking for a new role](https://chrisshort.net/micro/looking-for-a-new-role-2026/). Reach out if you need someone to elevate your technical storytelling.

[**SCALE 23x**](https://www.socallinuxexpo.org/scale/23x?utm_source=devopsish&utm_medium=newsletter&utm_campaign=scale23x) and [**DevOpsDay LA**](https://devopsdays.org/events/2026-los-angeles/welcome/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=dodla)  
Four days of practical, technical learning across open source infrastructure — the stuff you're running in production right now.  
DevOps'ish readers can get 40% off with discount code ***CHRIS***  
See you March 5-8, 2026 in Pasadena!

KubeCon is an investment. And it can also be incredibly valuable if you show up with the right expectations, goals, and plan. Having a plan that starts now and continues after the event can make the difference. [Kim McMahon is offering a complimentary 25-minute consultation](https://www.mcmahonconsulting.com/) to make sure you get the most out of the event.

[Desk Setup, January 2026](https://chrisshort.net/desk-setup-january-2026/) — For the first time in five years, I wrote up a new blog about how I have my desk configured to work, meet, record, and livestream. As a lot of the gear was procurred in 2020 so I included notes about what I'd do if I had to do it over again today.

[Amazon laying off about 16,000 corporate workers in latest anti-bureaucracy push](https://www.cnbc.com/2026/01/28/amazon-layoffs-anti-bureaucracy-ai.html) — Amazon continued laying off people to buy more GPUs to build more AI to help prop up the economy.  These cuts impacted several people I know. I have not been able to reach out to all of you but I'm around and able to talk and might even lift your spirits about the end of your time at Amazon.

[My time at Amazon, Part I by Becca Saleh](https://beccaselah.substack.com/p/my-time-at-amazon-part-i) — Speaking of Amazon... This article hit very close to home. Amazon is one of those jobs that you spend a solid chunk of time trying to get. But, once you've been there for two or more vests, you start realizing the place is your life and/or you realize your life could be better outside of Amazon.

[The Shape of Leadership](https://mikefisher.substack.com/p/the-shape-of-leadership) — This is a great article on leadership. A must read, in my opinion. The role of leadership in creating psychology safety in our work lives is a critical component of doing what every business wants to do right now: move fast. Good leaders building good environments where folks feel safe to be themselves are the kinds of leaders I want to work with.

[Measuring contributor affiliations is complicated](https://duckalignment.academy/measuring-contributor-affiliations/) — Ben Cotton tackles a question that seems simple on the surface: what percentage of contributors to an open source project are actually contributing as part of their job versus volunteering? Turns out it's a mess to answer, for several reasons.

[AI spending wasn't the biggest engine of U.S. economic growth in 2025, despite popular assumptions](https://www.cnbc.com/2026/01/26/ai-wasnt-the-biggest-engine-of-us-gdp-growth-in-2025.html) — I was just a smidge surprised by this. I thought all the hype around AI wasn't the _only_ thing propping up the economy but, it was close.

[Docker lazy loading at Grab: Accelerating container startup times](https://engineering.grab.com/docker-lazy-loading) — "Large container images for services like Airflow and Spark Connect were taking minutes to download, causing slow cold starts and poor auto-scaling performance. This blog post shares our journey implementing Docker image lazy loading using eStargz and Seekable OCI (SOCI) technologies, the results we achieved, and the lessons learned along the way."

[CNCF Project Release Firehose](https://castrojo.github.io/firehose/) — Jorge Castro built a tool to help you keep track of the latest releases in the Cloud Native ecosystem.

[Moltbot Is Taking Over Silicon Valley](https://archive.is/Se4vs) — "People are letting the viral AI assistant formerly known as Clawdbot run their lives, regardless of the privacy concerns." Clawdbot changed names twice this week too. It's now referred to as [OpenClaw](https://openclaw.ai/) (not to be confused with White Claw despite both having a sense of YOLO to them).

[How I Taught GitHub Copilot Code Review to Think Like a Maintainer](https://angiejones.tech/how-i-taught-github-copilot-code-review-to-think-like-a-maintainer/) — Angie Jones made the Copilot review tool on GitHub actually useful. Just because an AI feature isn't good doesn't mean it has to be a binary decision to enable or disable it; you can tune these things.

[10 things I learned from burning myself out with AI coding agents](https://arstechnica.com/information-technology/2026/01/10-things-i-learned-from-burning-myself-out-with-ai-coding-agents/) — Benj Edwards spent two months obsessively building 50+ projects with AI coding agents and found them genuinely fun and empowering—like 3D printers for software—but far from production-ready or capable of replacing experienced developers. The first lesson learned? You still need people.

{{< subscribe >}}
