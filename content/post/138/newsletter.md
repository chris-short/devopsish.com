+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2019"]
date = 2019-07-28T07:00:00Z
description = "Let's talk about JEDI. Not the lightsaber wielding kind, it's US Department of Defense's Joint Enterprise Defense Infrastructure (JEDI)."
draft = false
slug = "138"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "GitHub", "cloud native", "security", "DevOps news", "Kubernetes news", "JEDI", "AWS", "docker", "oracle", "community", "developers"]
title = "138: Jeez JEDI, language ladder, killing K8s, floppy finished, and more"

+++

Let's talk about JEDI. Not the lightsaber wielding kind, it's US Department of Defense's [Joint Enterprise Defense Infrastructure (JEDI)](https://devopsish.com/tags/jedi/) kind. JEDI is a $10 billion, single-award, indefinite delivery, indefinite quantity contract for the largest Department in the US government's cloud business. The competition had been whittled down to AWS and Azure but, Oracle has been pitching a Larry Ellison sized fit over it. Actually, Oracle has protested JEDI's selection process almost since its inception. The process started in late 2017 and has been filled with all sorts of twists and turns.

[Last week](https://devopsish.com/137), I shared a story with part of the headline stating, "Judge shoots down Oracle protest." Like any good government procurement process though, this is where the lawyers stepped back and the lobbyist stepped forward. I also linked to a story last week discussing the US President's concern over JEDI. The sitting US President hates Jeff Bezos, owner of the Washington Post and CEO of Amazon. AWS is the clear front runner as the #1 cloud provider *in the world*. The most popular cloud provider in the US by a long shot, [AWS GovCloud](https://aws.amazon.com/govcloud-us/) has been up and running since 2011. The US Intelligence Community uses [AWS Secret Region](https://aws.amazon.com/blogs/publicsector/announcing-the-new-aws-secret-region/) extensively.

If you thought last week's warning shot was the end, you'd be wrong. [Senator Marco Rubio has sent letters to the President](https://www.fedscoop.com/jedi-letter-rubio-republicans/) urging further scrutinization of JEDI. What's interesting is that during his failed presidential run in 2016, [Senator Rubio took $4 million from Oracle co-founder Larry Ellison](https://www.usatoday.com/story/tech/2016/07/17/tech-turns-its-back-trump-except-few/86508920/). It's also worth noting that [Oracle's CEO was on Trump's Transition Team](https://fortune.com/2016/12/15/trump-oracle-safra-catz/). Make no mistake, Oracle is playing *really petty* politics here. I get it, Oracle's future depends a lot on this. If the US government continues its move to AWS, there's little hope Oracle's fledgling cloud business will gain much traction. Oracle seemingly can't compete on features and has decided to compete in other ways. [Amazon is rightfully getting their own lobbyists with Trump ties on board](https://www.geekwire.com/2019/amazon-hires-lobbyist-trump-ties-amid-contentious-pentagon-cloud-contest/). But, I fear it might be too little, too late. President Trump strikes me as someone who values personal connections far more than logic and reason.

The [Joint Staff has already said, "Our warfighters need this capability now."](https://www.fedscoop.com/joint-chiefs-cio-jedi-delay-letter/) I agree with the Joint Staff here. Do you think China, Russia, or any US adversary for that matter, has this problem? Probably not. China is technologically and politically adept enough to have all this sorted out. Russia plays in a very different theater of operations than the US has traditionally. The elasticity and security capabilities of a fully integrated cloud might pay huge dividends against Russian tactics. But, delaying this acquisition from going forward has compounding negative effects as aging systems are yet again expected to survive somehow while the dithering in Washington drags on.

If you are in the US (most of you are), do me a favor this week, please. Reach out to your [Representatives](https://www.house.gov/representatives) and [Senators](https://www.senate.gov/general/contact_information/senators_cfm.cfm). Tell them the politics over JEDI needs to stop and we need to give our service members the tools they need to do their job right. Demand that the JEDI selection moves forward with AWS and Azure as the final two bidders. Don't force the Department of Defense to use potentially inferior tooling. Who wants Oracle getting $10 billion more in US taxpayer money anyway?

A deeper dive on JEDI and how Oracle's objections to it harm US national sercurity interests is available: [Use The Force, Larry: Oracle Playing Politics with Nation's Defense](https://chrisshort.net/use-the-force-larry-oracle-playing-politics-with-nations-defense/)

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

[joshsimmons/inclusion-rider](https://github.com/joshsimmons/inclusion-rider) — An as-yet UNTESTED sample speaker's rider to share with event organizers.

[9 people for sysadmins to follow on Twitter](https://opensource.com/article/19/7/twitter-sysadmins) — Follow these accounts to gain a wealth of knowledge about being a better sysadmin.

[Russia's Secret Intelligence Agency Hacked: 'Largest Data Breach In Its History'](https://www.forbes.com/sites/zakdoffman/2019/07/20/russian-intelligence-has-been-hacked-with-social-media-and-tor-projects-exposed/#e8c8c06b1150) — *Gets popcorn*

[Marcus Hutchins, malware researcher and ‘WannaCry hero,' sentenced to supervised release](https://techcrunch.com/2019/07/26/marcus-hutchins-sentenced-kronos/) — Time served, supervised release, and Marcus will likely never be able to re-enter the US. But, look what Judge J. P. Stadtmueller said, "It's going to take the people like [Hutchins] with your skills to come up with solutions because that's the only way we're going to eliminate this entire subject of the woefully inadequate security protocols." The judge is right.

[**The Business Value of Developer Relations**](https://www.persea-consulting.com/book?utm_source=devopsish&utm_medium=newsletter&utm_campaign=138)  
Discover the true value of Developer Relations as you learn to build and maintain positive relationships with your developer community. Use the principles laid out in this book to walk through your company goals and discover how you can formulate a plan tailored to your specific needs. *SPONSORED*

## Process

[Will complexity kill Kubernetes?](https://www.infoworld.com/article/3409980/will-complexity-kill-kubernetes.html) — Short answer: Complexity kills everything so, yes. However, the author disagrees (for good reason), "Probably not. While Hadoop got more complicated with age, Kubernetes keeps getting easier. While Kubernetes will likely never be 'easy,' per se, its complexity differs from that of Hadoop in critical ways, paving the way for Kubernetes to remain an industry standard for years to come." I don't think Hadoop is a good analog to Kubernetes (let's face it, no one wants Kubernetes to become OpenStack). But, it does speak to a community that tries to grease the skids in versus raising the bar higher and higher.

[Other people's messes by Jessica Kerr](https://blog.jessitron.com/2019/07/21/other-peoples-messes/) — Like a lot of things in life, When it comes to code, context matters. It's a lot less messy when you understand the why behind it.

[IBM-Red Hat: Should developers worry we're headed back to the 1990s?](https://venturebeat.com/2019/07/20/ibm-red-hat-should-developers-worry-were-headed-back-to-the-1990s/) — "A dated playbook of boxing in and trying to control developers through a Big Blue (and now Red) stack could ultimately harm IBM's chances of achieving cloud relevancy." Huh. I thought the heading back to the 90s bit was the AWS, GCP, Azure, and Oracles of the world (vendor lock-in). I guess with Red Hat being a part of IBM now this was bound to happen. But, the author believes that IBM is now going to start shoving Red Hat products down peoples' throats. I guess if IBM didn't already have product in a space maybe? But, it's not like IBM didn't have anything to sell until a few weeks ago. When something is new and shiny, it's going to be at the top of people's minds. Once news of the deal settles and the sales training is into sustainment, I hope folks start to forget Red Hat is a part of IBM. That'd be great.

[Decoupling database migrations from server startup: why and how](https://pythonspeed.com/articles/schema-migrations-server-startup/) — Your code and database schemas shouldn't have to march in lockstep with their releases. Thinking of the database as another codebase (the schema certainly is) has been something I've been trying to get through to folks for a long time on.

[How a Production Outage Was Caused Using Kubernetes Pod Priorities](https://grafana.com/blog/2019/07/24/how-a-production-outage-was-caused-using-kubernetes-pod-priorities/) — Resource limits are EVERYTHING. If you don't use them, WHY!?!

[6 Tech Giants Located in Detroit](https://blog.repurpose.co/6-tech-giants-located-in-detroit) — Don't sleep on Detroit, y'all. When I'm doing non-work speaking, I put [pictures from Detroit](https://devopsish.com/images/awesome-detroit.jpg) at the beginning of the slides. I want to show people it's not what they hear and see in the news. Detroit is an amazing city!

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

[Retrotechtacular: The Floppy Disk Orphaned By Linux](https://hackaday.com/2019/07/26/retrotechtacular-the-floppy-disk-orphaned-by-linux/) — Folks are having issues with Packer as a result. I remember using a virtual floppy from something semi-regularly when I was at Hosted Solutions four years ago. Are you using a floppy disk or drive for anything still?

[Underscoring the "private" in private key](https://koen.io/2019/07/26/underscoring-the-private-in-private-key/) — The private key should be KEPT PRIVATE. It's not to hand out, ever (with very, very few exceptions).

[Goodbye Docker: Purging is Such Sweet Sorrow](https://zwischenzugs.com/2019/07/27/goodbye-docker-purging-is-such-sweet-sorrow/) — I still need Docker on my Mac from time to time and it irritates me to no end.

[jbeda/kinecraft](https://github.com/jbeda/kinecraft) — Start to a Minecraft k8s operator by Joe Beda

[eko/monday](https://github.com/eko/monday) — A dev tool for microservice developers to run local applications and/or forward others from/to Kubernetes SSH or TCP

[envoyproxy/envoy-wasm](https://github.com/envoyproxy/envoy-wasm) — Playground for Envoy WASM filter

[herbrandson/k8dash](https://github.com/herbrandson/k8dash) — Simple Kubernetes realtime dashboard and management

[tumblr/docker-registry-pruner](https://github.com/tumblr/docker-registry-pruner) — Tool to apply retention logic to docker images in a Docker Registry

[geerlingguy/docker-ubi8-ansible](https://github.com/geerlingguy/docker-ubi8-ansible) — UBI 8 Docker container for Ansible playbook and role testing.

## DevOps'ish Tweet of the Week

[![Rebecca Fernandez (@ruhbehka) on Twitter][/138/138-tweet-of-the-week.png]](https://twitter.com/ruhbehka/status/1154142091620102150)

Notes from this week's issue can be found [here](./notes/).
