+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-02-13T07:00:00Z
description = ["EARN IT Act is back and worse than ever, SSD chip contamination, technical debt, SBOMs, Tools for Securing Your Kubernetes Cluster, ValidKube, and more"]
draft = false
slug = "256"
tags = ["Kubernetes", "GitOps", "Apple", "security", "EKS", "controller", "open source", "cloud", "policies", "K8s", "scale", "AirTags", "working conditions", "AWS", "Tile", "network", "software", "technical debt", "SBOM", "Ambassador", "CNCF", "clusters", "CVE", "macOS", "DevOps", "EARN IT Act"]
title = "DevOps'ish 256: EARN IT Act is back and worse than ever, SSD chip contamination, technical debt, SBOMs, Tools for Securing Your Kubernetes Cluster, ValidKube, and more"

+++

I hope your week was wonderful, and you're looking forward to the week ahead. I had the honor of being named a [Continuous Delivery Foundation Ambassador](https://cd.foundation/blog/2022/02/03/new-2022-ambassadors-and-community-builders/) this along (alongside the [CNCF Ambassador](https://www.cncf.io/people/ambassadors/) title). Also, I began my official duties as a [co-chair on the GitOps Working Group/OpenGitOps](https://github.com/cncf/tag-app-delivery/blob/main/gitops-wg/CHAIRS.md) projects.

"Why?!? Aren't you busy enough???" One might understandably ask themselves. My [GitOps](https://opengitops.dev/) partner in crime, [Christian Hernandez](https://twitter.com/christianh814), and I realized this odd alignment between GitOps and the organizations to help it grow. CNCF and CDF both have their hands in software delivery. We both applied with the premise of bridging and hopefully connecting the two foundations' GitOps positioning.

I look forward to participating in both communities equally under the GitOps umbrella. It's going to be a fun ride.

The [CFP for GitOpsCon EU ends MONDAY at 11:59 PM PST](https://events.linuxfoundation.org/gitopscon-europe/program/cfp/). Submit your talks **now**!!!

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## People

[The EARN IT Act Is Back, and It's More Dangerous Than Ever](https://cyberlaw.stanford.edu/blog/2022/02/earn-it-act-back-and-it%E2%80%99s-more-dangerous-ever)  
"At first blush, that might sound like a good thing, which is why it will be hard for members of Congress to resist – who could ever vote against child safety? But make no mistake: this was a dangerous bill two years ago, and because it's doubled down on its anti-encryption stance, it's even more dangerous now."

[6 Signs It's Time to Leave Your Job](https://hbr.org/2022/02/6-signs-its-time-to-leave-your-job)  
"There are six signs it may be time to move on from your current role or career. First, it's no longer encouraging your growth. Second, you've achieved what you set out to achieve. Third, you actively look for ways to procrastinate or avoid your job. Fourth, you regularly approach work with dread or have feelings of exhaustion and burnout. Fifth, your job is causing you to develop bad habits that don't align with your values. Finally, your workplace has become harmful to your physical or emotional health."

[SSD prices could spike after Western Digital loses 6.5 billion gigabytes of NAND chips](https://www.theverge.com/2022/2/11/22928867/western-digital-nand-flash-storage-contamination)  
"A manufacturing contamination has led to big losses" and it's going to hit us in the wallets quick, I feel.

[Apple changes employees' titles to ‘associate' after they leave](https://www.washingtonpost.com/technology/2022/02/10/apple-associate/)  
One day, a long time ago, I wanted to work at Apple. Now that I have friends there my opinion has changed. I'd still work there under the right conditions but, those conditions aren't necessarily standard for Apple either. I use a lot of Apple products and services and working on those services at scale would be fun but, I don't think that scale is bigger or more interesting than AWS.

[I Used Apple AirTags, Tiles and a GPS Tracker to Watch My Husband's Every Move](https://www.nytimes.com/2022/02/11/technology/airtags-gps-surveillance.html)  
I find this fascination with AirTags' discoverability interesting. I used Tile tags for years to keep track of important objects. I replaced them with AirTags for three reasons: 1) The alerting if it's traveling with you and it's not your AirTag (wait until I light up a whole airplane with that one day because I always hide one in my luggage). 2) the network it rides on is far superior. 3) As I drive or walk away from them, I get an alert if I leave anything important behind. I could never find anything through the Tile network unless it were at home or near one of my devices. They sure as hell didn't tell people a tracker was near, and no one ever knew about them. There are WORSE devices, too, that you should ACTUALLY be worried about (as mentioned in the article). Oddly, now that Apple is trying to do the right thing (I do understand at scale how hard of a problem it is), they're getting bashed for it. Quite the conundrum. Since my AirTags are a security device, I won't disclose what I attach them to (other than luggage because that's obvious).

[EKS News 005](https://buttondown.email/eks.news/archive/eks-news-005/)  
In case you weren't aware, I maintain a newsletter for $job now called [EKS News](https://eks.news/). I work on it with my boss, it's pretty fun, to be honest. My newsletter count is up to three now (DevOps'ish, contributing to [KubeWeekly](https://www.cncf.io/kubeweekly/), and EKS News). I made it abundantly clear I wasn't going to write a newsletter without some community component. EKS News uses the same DevOps'ish editorial process (never did I think a mechanism to write a newsletter would be so open and so effective). It's pretty cool for me personally because the work of reading, suggesting reads, and the processes I built for this newsletter now contributes to three newsletters. Never underestimate great processes in motion (and don't be afraid to continue iterating).

## Process

[We sound like idiots when we talk about technical debt](https://www.cyclic.sh/posts/we-sound-like-idiots-when-we-talk-about-technical-debt)  
Put things in the businesses context when you're explaining them. Leadership knows about dollar, cents, and time. We know about pain, time, and tooling. The time overlap is a great place to start. Compute density is another great place to find business interest. If you could hire three engineers and cut your cloud spend by more than a percentage point, that's the right way to get the business to let you pay off some debt. Go in with a well researched plan and tailor the explanation of it to your audience.

[Security: The Value of SBOMs](https://fluxcd.io/blog/2022/02/security-the-value-of-sboms/)  
Software Bill of Materials (SBOMs) can sound daunting at first when you start to spider out from the things you know you depend on (above the line) and realize the underlying dependencies you still have (below the line). This article details how GitOps tool, [Flux](https://fluxcd.io/), approached their v2 rewrite and reducing their attack surface at the same time. All the while, their SBOM was kept up to date with a tool from Anchore called [Syft](https://github.com/anchore/syft). If you've never heard of the above/below the line concept, read the paper [Above the Line, Below the Line by Richard I. Cook, M.D.](https://shortcdn.com/devopsish/above-the-line-below-the-line.pdf)

[Kubernetes Policy Management White Paper (PDF)](https://github.com/kubernetes/sig-security/blob/main/sig-security-docs/papers/policy/CNCF_Kubernetes_Policy_Management_WhitePaper_v1.pdf)  
"This paper aims to provide a clear understanding of why Kubernetes
policy management is becoming necessary for security and
automation of Kubernetes clusters and workloads. It also describes what problems Kubernetes policies can help solve and how Kubernetes policies are implemented."

[Argo CD Deals With Our First Zero-Day CVE](https://blog.argoproj.io/argo-cd-deals-with-our-first-zero-day-cve-86e8fb158e8f)  
"[W]e'd like to share how these better security policies helped us respond to [CVE-2022–24348](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-24348) in a quick and responsible fashion."

[Apple addressed a third zero-day in 2022, which is actively exploited](https://securityaffairs.co/wordpress/127894/security/apple-addressed-third-zero-day-2022.html)  
Apple has been having a rough start to the year. macOS 12.2.1 was the fastest I've ever seen a Mac release go from being available to being authorized to install by my IT team. #HugOps to all the security teams out there.

## Tools

[The Top 7 Open Source Tools for Securing Your Kubernetes Cluster](https://mattermost.com/blog/the-top-7-open-source-tools-for-securing-your-kubernetes-cluster/)  
This is actually a good list put together by Mattermost. If you're new to Kubernetes or looking to secure your clusters, this list is for you.

[Auto Scaling CI Agents At Wix](https://www.wix.engineering/post/auto-scaling-ci-agents-at-wix)  
A dive into how Wix is using open source tooling and building a multi-queue architecture for their infrastructure.

[A ‘Hello World' GitOps Example Walkthrough](https://zwischenzugs.com/2021/07/31/a-hello-world-gitops-example-walkthrough/)  
"This post walks through a ‘hello world' GitOps example I use to demonstrate key GitOps principles."

[ValidKube](https://validkube.com/)  
Validate, Clean & Secure Your K8s YAML

[kubernetes-simulator/simulator](https://github.com/kubernetes-simulator/simulator)  
Kubernetes Security Training Platform - Focussing on security mitigation

[jakshin/open-in-iterm](https://github.com/jakshin/open-in-iterm)  
A macOS Finder toolbar app which opens iTerm tabs/windows conveniently

[aws/aws-cloud-map-mcs-controller-for-k8s](https://github.com/aws/aws-cloud-map-mcs-controller-for-k8s)  
K8s controller implementing Multi-Cluster Services API based on AWS Cloud Map

[kubernetes-sigs/aws-load-balancer-controller](https://github.com/kubernetes-sigs/aws-load-balancer-controller)  
A Kubernetes controller for Elastic Load Balancers

[DevOps-Nirvana/Kubernetes-Volume-Autoscaler](https://github.com/DevOps-Nirvana/Kubernetes-Volume-Autoscaler)  
Autoscaling volumes for Kubernetes (with the help of Prometheus)

[Raspberry Pi OS 32-bit vs. 64-bit Performance Review](https://www.phoronix.com/scan.php?page=article&item=raspberrypi-32bit-64bit&num=1)  
Learn how the new 64-bit OS handles work compared to 32-bit.

## DevOps'ish Tweet of the Week

[![Jason H. Moore, PhD (@moorejh on Twitter) "#sciencetwitter"](https://shortcdn.com/devopsish/256-devopsish-tweet-of-the-week.webp)](https://twitter.com/moorejh/status/1491495889809993728)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/256/notes.md) to see what didn't make it to the newsletter but are still worth your time.
