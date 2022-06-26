+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-02-06T07:00:00Z
description = ["Open source operational transparency, npm security, Blackberry sells off patents, Samba vuln, Minecraft server in 10, GitOps Terraform controller for Kubernetes, and more"]
draft = false
slug = "255"
tags = ["services", "Great Resignation", "Pandora", "cobalt", "vulnerability", "Right to Repair", "sensitive information", "attack", "npm", "Linux", "Samba", "rust", "Honeycomb", "transparency", "Kubernetes", "Helm", "Argo CD", "Blackberry", "DevOps", "GitOps", "Ansible", "Terraform", "open source"] 
title = "DevOps'ish 255: Open source operational transparency, npm security, Blackberry sells off patents, Samba vuln, Minecraft server in 10, GitOps Terraform controller for Kubernetes, and more"

+++

DevOps'ish is brought to you our friends at [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
***"Stop Letting Complexity Slow You Down"***  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

## People

[There Is a Much Larger Problem Than the Great Resignation. No One Wants to Talk About It.](https://themakingofamillionaire.com/there-is-a-much-larger-problem-than-the-great-resignation-no-one-wants-to-talk-about-it-3922cf8aefd2)  
It's okay to go to a two-year school and build up some experience to increase your value. That's what I did. I insisted on touching keyboards more and more.

[North Korea Hacked Him. So He Took Down Its Internet](https://www.wired.com/story/north-korea-hacker-internet-outage/)  
"P4x says he has largely automated his attacks on the North Korean systems, periodically running scripts that enumerate which systems remain online and then launching exploits to take them down. 'For me, this is like the size of a small-to-medium pentest,' P4x says, using the abbreviation for a 'penetration test,' the sort of whitehat hacking he's carried out in the past to reveal vulnerabilities in a client's network. 'It's pretty interesting how easy it was to actually have some effect in there.'"

[The Right to Repair Should be Protected by Law](https://www.scientificamerican.com/article/some-electronics-repairs-are-illegal-federal-law-could-change-that/)  
Right to repair until recently has been a fundamental part of owning something. Oddly, this has become a "political" issue. It's even weirder to read articles like this one [about the right to repair in Massachusetts](https://arstechnica.com/cars/2022/02/a-fight-over-the-right-to-repair-cars-turns-ugly/).

[The dark side of Cobalt, the digital age’s miracle metal](https://www.thestar.com/news/canada/2022/01/30/the-dark-side-of-cobalt-the-digital-ages-miracle-metal.html)  
Cobalt, Ontario, Canada, a mere 381 miles from where I'm writing this newsletter, is the scene for this article about the cobalt industry. "The story of Cobalt is about the looting of one of the great treasure boxes of the earth. But it is also a story of people who believed it was possible to create an alternate future with this immense natural wealth." Yeah, it's bad.

[You want HOW MANY years experience?!](https://howoldisit.glitch.me/)  
I know a few recruiters read this newsletter. This is something you should bookmark right away.

## Process

[Why open source projects should embrace operational transparency](https://leaddev.com/agile-other-ways-working/why-open-source-projects-should-embrace-operational-transparency)  
"But wherever possible, increasing transparency around how work gets done sets clear expectations for contributors, raises the visibility of when a project is in need of support, and reduces the amount of effort that falls on the maintainers' collective shoulders."

[Malicious Kubernetes Helm Charts can be used to steal sensitive information from Argo CD deployments](https://apiiro.com/blog/malicious-kubernetes-helm-charts-can-be-used-to-steal-sensitive-information-from-argo-cd-deployments/)  
Well this is no good. From the TLDR...

* A 0-day vulnerability, discovered by Apiiro’s Security Research team, allows malicious actors to load a Kubernetes Helm Chart YAML file to the vulnerability and “hop” from their application ecosystem to other applications’ data outside of the user’s scope.
* The actors can read and exfiltrate secrets, tokens, and other sensitive information residing on other applications.
* The impact of the attack includes privilege escalation, sensitive information disclosure, lateral movement attacks, and more.
* Although Argo CD contributors were aware of this weak point in 2019 and implemented an anti-path-traversal mechanism, a bug in the control allows for exploitation of this vulnerability.

[Top-100 npm package maintainers now require 2FA, and additional security-focused improvements to npm](https://github.blog/2022-02-01-top-100-npm-package-maintainers-require-2fa-additional-security/)  
That's a good start. I have to be honest, this might have been poorly timed given the recent [shenanigans in the npm community](https://www.yahoo.com/now/developer-sabotaged-own-open-source-185931413.html). This would do nothing to prevent the situation that occurred last month. I am curious what big Node.js shops are doing to mitigate issues like developer sabotage. Remember [this happened to Chef in 2019](https://chrisshort.net/seth-vargo-says-hell-noputs-chef-on-ice/). Are y'all running caches for your CI pipelines? How are you verifying what that cache is pulling in works? This is a tough problem to solve.

[BlackBerry sells mobile and messaging patents for $600 million](https://arstechnica.com/gadgets/2022/01/blackberry-sells-mobile-and-messaging-patents-for-600-million/)  
As the article states, "If the name "Catapult IP Innovations" didn't give it away, weaponizing BlackBerry patents is the most obvious outcome of this deal." If you're curious, "BlackBerry's main businesses today revolve around car infotainment—where its QNX operating system is a popular option for car manufacturers—and enterprise security."

[“Deprioritized” Google Stadia to pivot to “Google Stream” white-label service](https://arstechnica.com/gadgets/2022/02/deprioritized-google-stadia-to-pivot-to-google-stream-white-label-service/)  
The halls of Killed by Google get a quick entrant. I hate to say I saw this coming, but the gaming industry is challenging and sometimes takes years of runway. But, that underlying infrastructure and those lessons learned will make it interesting to see how this white-label service fares.

## Tools

[Reclaiming the lost art of Linux server administration](https://www.pietrorea.com/2022/01/28/reclaiming-the-lost-art-of-linux-server-administration)  
Linux system administrator is a foundational layer of mine and many readers' careers. I was kinda forced to learn to put parts and pieces together. But, nowadays, thanks to a lot of advances on a lot of fronts, today's DevOps folks might be more dev heavy than ops. Cool article.

[how I wound up causing a major outage of my services and destroying my home directory by accident](https://ariadne.space/2022/02/04/how-i-wound-up-causing-a-major-outage-of-my-services-and-destroying-my-home-directory-by-accident/)  
"As a result of my FOSS maintenance and activism work, I have a significant IT footprint, to support the services and development environments needed to facilitate everything I do. Unfortunately, I am also my own system administrator, and I am quite terrible at this. This is a story about how I wound up knocking most of my services offline and wiping out my home directory, because of a combination of Linux `mdraid` bugs and a faulty SSD. Hopefully this will be helpful to somebody in the future, but if not, you can at least share in some catharsis."

[Tens of Thousands of Outdated HPE iLO Interfaces Exposed to the Internet and Rootkits](https://www.servethehome.com/tens-of-thousands-of-outdated-hpe-ilo-interfaces-exposed-to-the-internet-and-rootkits/)  
Scan your networks, folks. Check your IP in <shodan.io> every once in a while.

[Critical Samba flaw presents code execution threat](https://portswigger.net/daily-swig/critical-samba-flaw-presents-code-execution-threat)  
"All versions of Samba prior to 4.13.17 are vulnerable to an out-of-bounds heap read write vulnerability that allows remote attackers to execute arbitrary code as root on affected Samba installations that use the VFS module vfs_fruit."

[tag-security/supply-chain-security/compromises](https://github.com/cncf/tag-security/tree/main/supply-chain-security/compromises)  
"This repository contains links to articles of software supply chain compromises. The goal is not to catalog every known supply chain attack, but rather to capture many examples of different kinds of attack, so that we can better understand the patterns and develop best practices and tools."

[Build a fully functional Minecraft server in less than 10 minutes with Ansible](https://minecraftadmin.linuxtek.ca/2022/01/30/build-a-fully-functional-minecraft-server-in-less-than-10-minutes-with-ansible/)  
Rub a little Ansible on it and 💥Minecraft server💥

[How Prime Video updates its app for more than 8,000 device types](https://www.amazon.science/blog/how-prime-video-updates-its-app-for-more-than-8-000-device-types)  
"Overall, we think that this investment in Rust and WebAssembly has paid off: after a year and 37,000 lines of Rust code, we have significantly improved performance, stability, and CPU consumption and reduced memory utilization." A great WASM and Rust story.

[weaveworks/tf-controller](https://github.com/weaveworks/tf-controller)  
"A GitOps Terraform controller for Kubernetes" Scott Rigby is dropping bombs on folks in the #gitops channel on CNCF's Slack. Did you know this was a thing?!? I didn't, and I feel like you probably would like to use this at some point.

[cybersecsi/HOUDINI](https://github.com/cybersecsi/HOUDINI)  
"Hundreds of Offensive and Useful Docker Images for Network Intrusion. The name says it all." Remember, with great power comes great responsibility.

[infracost/infracost](https://github.com/infracost/infracost)  
"Cloud cost estimates for Terraform in pull requests💰📉 Love your cloud bill!"

## DevOps'ish Tweet of the Week

[![OpenGitOps (@OpenGitOps on Twitter) "#GitOpsCon CFP is still open! Come share your experiences with GitOps at our Co-located event at #KubeConEU! CFP Closes February 14th!"](https://shortcdn.com/file/devopsish/255-devopsish-tweet-of-the-week.webp)](https://twitter.com/OpenGitOps/status/1488958489711943690)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/255/notes/) to see what didn't make it to the newsletter but are still worth your time.
