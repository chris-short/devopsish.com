+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-04-25T07:00:00Z
description = ["Prepping for KubeCon, we're languishing, CodeCov debacle, Signal slashes Cellebrite, not so Golden Gophers, ARM deal halted, Kubernetes Gateway API, and more"]
draft = false
slug = "215"
tags = ["Kubernetes", "DevOps", "KubeCon", "cloud native", "open source", "code", "Red Hat", "Cellebrite", "University of Minnesota", "distributed", "tracing", "developers", "ARM", "NVIDIA", "LaunchDarkly", "Linux", "Clubhouse", "Gateway API", "Honeycomb", "handovers", "Operators", "Istio", "tech", "IBM", "homebrew", "languishing", "microservices", "FTP", "jq", "xargs", "COSI", "GitOps"]
title = "DevOps'ish 215: Prepping for KubeCon, we're languishing, CodeCov debacle, Signal slashes Cellebrite, not so Golden Gophers, ARM deal halted, Kubernetes Gateway API, and more"

+++

Two weeks before KubeCon EU and the work is ramping up quickly. If you haven't gotten your tickets yet, grab yours today. As always, if you are underrepresented in tech and still need a ticket, let me know. I will be busy next week prepping for a flip to Central European Summer Time with a lot going on. On May 3rd, I will be mc'ing [**GitOps Con**](https://kccnceu2021.sched.com/event/iZx4/gitops-con-hosted-by-weaveworks-redhat-complimentary-registration-required?iframe=no&w=100%25&sidebar=yes&bg=no). It's going to be awesome. On May 4th, the first anniversary of [OpenShift.tv](https://openshift.tv/) (yeah, it's been a year, y'all), I'll be live streaming [OpenShift Commons Gathering hosted by Red Hat (Complimentary Registration Required)](https://kccnceu2021.sched.com/event/iE1J/openshift-commons-gathering-hosted-by-red-hat-complimentary-registration-required). I'll be in the Red Hat booth for a little bit on May 5th.

We'll also be streaming open source project Office Hours throughout KubeCon EU. Finally, on Friday, I'll be doing my first ever, actual KubeCon talk (I know, weird, right?), [How You Can Tell Your Kubernetes Contributor Story with These Tips - Matt Broberg & Chris Short, Red Hat; Kaslin Fields, Google; Peeyush Gupta, DigitalOcean](https://kccnceu2021.sched.com/event/iE6I/how-you-can-tell-your-kubernetes-contributor-story-with-these-tips-matt-broberg-chris-short-red-hat-kaslin-fields-google-peeyush-gupta-digitalocean). To say the prep for all this is coming to a head this week is an understatement. The pressure is on. Let's get it!

## People

[Feeling Blah During the Pandemic? It's Called Languishing](https://www.nytimes.com/2021/04/19/well/mind/covid-mental-health-languishing.html)  
"It wasn’t burnout — we still had energy. It wasn’t depression — we didn’t feel hopeless. We just felt somewhat joyless and aimless. It turns out there’s a name for that: [languishing](https://www.jstor.org/stable/3090197)."

**Remote instructor-led Kubernetes training** — Learnk8s offers live remote training sessions for individual engineers and companies that want to augment their knowledge in Kubernetes and cloud-native technologies. [Become an expert in Kubernetes](https://learnk8s.io/training) Become an expert in Kubernetes! *SPONSORED*

[Annotating Kubernetes Services for Humans](https://kubernetes.io/blog/2021/04/20/annotating-k8s-for-humans/)  
"One of the problems as Kubernetes applications grow is the proliferation of services. As the number of services grows, developers start to specialize working with specific services. When it comes to troubleshooting, however, developers need to be able to find the source, understand the service and dependencies, and chat with the owning team for any service."

[Harassers and bullies succeed in tech because silence is encouraged](https://www.theregister.com/2021/04/20/harassers_and_bullies_succeed_in/)  
"Countless people signed away the right to have their trauma acknowledged, and that can’t stand"

[Proposed acquisition of ARM Limited by NVIDIA Corporation: public interest intervention](https://www.gov.uk/government/publications/proposed-acquisition-of-arm-limited-by-nvidia-corporation-public-interest-intervention)  
The UK government is stepping in to stop the sale of ARM to NVIDIA. I really don't think that's going to matter. ARM and NVIDIA clearly see a brighter future together than apart. They'll find a way to work more collaboratively with each other even if the sale doesn't close.

## Process

[Codecov users warned after backdoor discovered in DevOps tool](https://portswigger.net/daily-swig/codecov-users-warned-after-backdoor-discovered-in-devops-tool)  
This one is nasty, y'all. "Credential-slurping code lingered in Bash Uploader script for months." Yet another deep penetrating supply chain compromise. These are becoming common enough for you to go to your CIO/CTO if you're not committing significant time to investigate potential holes in your build processes if you're not already. Here is [CodeCov's advisory](https://about.codecov.io/security-update/).

[Learn what LaunchDarkly can do for your organization.](https://learn.launchdarkly.com/demo?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)
LaunchDarkly enables companies like Square, Hulu, Atlassian, Toyota, Intuit, IBM, and others gain a competitive edge with better feature management.  
Move fast without breaking things and learn how your team can reap the rewards of CI/CD without the risk.  
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Exploiting vulnerabilities in Cellebrite UFED and Physical Analyzer from an app's perspective](https://signal.org/blog/cellebrite-vulnerabilities/)  
"Given the number of opportunities present, we found that it’s possible to execute arbitrary code on a Cellebrite machine simply by including a specially formatted but otherwise innocuous file in any app on a device that is subsequently plugged into Cellebrite and scanned. There are virtually no limits on the code that can be executed." Signal hacks back at Cellebrite.

[University Banned From Contributing To Linux Kernel For Intentionally Inserting Bugs](https://www.phoronix.com/scan.php?page=news_item&px=University-Ban-From-Linux-Dev)  
"Greg Kroah-Hartman has banned a US university from trying to mainline Linux kernel patches over intentionally submitting questionable code with security implications and other "experiments" in the name of research." For shame University of Minnesota. The University of Minnesota vows to investigate.

[A Clubhouse Bug Let People Lurk in Rooms Invisibly](https://www.wired.com/story/clubhouse-bug-lurkers-ghost/)  
"Katie Moussouris told me in a private Clubhouse room in February. 'We'll still be talking, but I'll be gone.' And then her avatar vanished. I was alone, or at least that's how it seemed. 'That’s it,' she said from the digital beyond. 'That's the bug. I am a fucking ghost.'" I uninstalled Clubhouse this week after never really using it. There are too many holes in the platform and numerous alternatives.

[Vulnerability in Homebrew macOS package manager could allow arbitrary code execution](https://portswigger.net/daily-swig/vulnerability-in-homebrew-macos-package-manager-could-allow-arbitrary-code-execution)  
"The Japanese researcher found that “in the Homebrew/homebrew-cask repository, it was possible to merge the malicious pull request by confusing the library that is used in the automated pull request review script developed by the Homebrew project”, according to a [blog post](https://blog.ryotak.me/post/homebrew-security-incident-en/) published on April 21."

## Tools

[Hunting down the stuck BGP routes](https://blog.benjojo.co.uk/post/bgp-stuck-routes-tcp-zero-window)  
A the whimsical joy that is Border Gateway Protocol.

Distributed Tracing shows the relationships between microservices in a distributed system. But there is a perception of complexity. At Honeycomb, we aim to democratize distributed tracing. Check out our "[Distributed Tracing for Microservices Guide](https://www.honeycomb.io/distributed-tracing-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=guide-distributed-tracing-devopsish&utm_adgroup)" to learn how Honeycomb Beelines make instrumenting traces easy.

Observe, debug, and improve with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Evolving Kubernetes networking with the Gateway API](https://kubernetes.io/blog/2021/04/22/evolving-kubernetes-networking-with-the-gateway-api/)  
I got excited when I read this article. Kubernetes is getting a little bit easier to use with Gateway API.

[Grafana, Loki, and Tempo will be relicensed to AGPLv3](https://grafana.com/blog/2021/04/20/grafana-loki-tempo-relicensing-to-agplv3/)  
OPEN SOURCE IS NOT A BUSINESS MODEL. Yes, this newsletter is what keeps me from remapping Caps Lock to something more useful.

[How to Successfully Hand Over Systems](https://developers.soundcloud.com/blog/how-to-successfully-hand-over-systems)  
"Having experienced not-so-successful handovers — some of which took place over the course of a one-hour meeting — I was inspired to create a guideline that will help other teams do handovers differently. At the same time, my colleague Antonio N. went through an ownership change with his team. This also had few mishaps, so we joined forces to write a proposal document for doing system handovers at SoundCloud." Every org should have something like this.

[Ask the Product Manager Office Hours: Operators and Helm](https://www.youtube.com/watch?v=YowBHOOZakk)  
I sat down with some brilliant people to talk about Helm and Operators working hand and hand.

[FTP is 50 years old](https://www.filestash.app/2021/04/16/ftp-is-50-years-old/)  
And I bet there are financial institutions still using it. There's [an AWS service for FTP](https://aws.amazon.com/blogs/aws/new-aws-transfer-for-ftp-and-ftps-in-addition-to-existing-sftp/) so I know folks are still using it. Which is kinda wild.

[Upcoming networking changes in Istio 1.10](https://istio.io/latest/blog/2021/upcoming-networking-changes/)  
"Here we can see that the proxy no longer redirects the traffic to the `lo` interface, but instead forwards it to the application on `eth0`. As a result, the standard behavior of Kubernetes is retained, but we still get all the benefits of Istio. This change allows Istio to get closer to its goal of being a drop-in transparent proxy that works with existing workloads with zero configuration. Additionally, it avoids unintended exposure of applications binding only to `lo`."

[Tips for productive DevOps workflows: JSON formatting with jq and CI/CD linting automation](https://about.gitlab.com/blog/2021/04/21/devops-workflows-json-format-jq-ci-cd-lint/)  
How to `jq`.

[gruntwork-io/git-xargs](https://github.com/gruntwork-io/git-xargs)  
"git-xargs is a command-line tool (CLI) for making updates across multiple Github repositories with a single command."

[geerlingguy/internet-monitoring](https://github.com/geerlingguy/internet-monitoring)  
Monitor your network and internet speed with Docker & Prometheus

[kubernetes-sigs/container-object-storage-interface-provisioner-sidecar](https://github.com/kubernetes-sigs/container-object-storage-interface-provisioner-sidecar)  
"Container Object Storage Interface (COSI) provisioner responsible to interface with COSI drivers."

## DevOps'ish Tweet of the Week

[![@skamille on Twitter: "I genuinely love seeing work that involves taking important but unglamorous largely manual processes and adding automation as well as product-minded process improvements to turn them into something that no one minds doing anymore. It's just so beautiful"](https://shortcdn.com/devopsish/215-devopsish-tweet-of-the-week.png)](https://twitter.com/skamille/status/1384910084745084930)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/215/notes.md) to see what didn't make it to the newsletter but are still worth your time.
