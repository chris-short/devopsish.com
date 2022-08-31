+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-06-20T07:00:00Z
description = ["Hostile AWS Free Tier, Bye bye Bezos, InfoSec competencies, Rust in Linux Kernel, Git for Computer Scientists, secrets on the CLI, and more"]
draft = false
slug = "223"
tags = ["cloud", "DevOps", "AWS", "Rust", "Linux", "kernel", "cloud native", "secrets", "IAM", "Google", "observability", "software", "support", "leader", "management", "Unix", "InfoSec", "free tier", "security", " development", "open source", "developer", "community"]
title = "DevOps'ish 223: Hostile AWS Free Tier, Bye bye Bezos, InfoSec competencies, Rust in Linux Kernel, Git for Computer Scientists, secrets on the CLI, and more"

+++

In vacation mode this week. News reading played second fiddle to having fun.

## People

[AWS pricing problems could deter new cloud engineers](https://techmonitor.ai/technology/cloud/aws-pricing-problems-gcp-azure)  
I was quoted in this piece. I take the same opinion that the AWS Free Tier is indeed user hostile. Not because it's limited in weird ways but, because new users could be billed thousands and before they know it, it's too late.

Take a deep dive into observability at [o11ycon+hnycon](https://o11ycon-hnycon.io/devopsish/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=devopsish&utm_adgroup), a two-day virtual conference on the future of shipping software. Happening June 9-10, this highly interactive event connects you and your peers to explore cutting-edge capabilities and unique outcomes that define observability. You’ll also hear from top Honeycomb customers and observability experts– including Corey Quinn, Chief Cloud Economist of The Duckbill Group, and Nora Jones, CEO of Jeli!

Guess less and know more with [Honeycomb](https://www.honeycomb.io/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish) *SPONSORED*.

[Upwards of 40% of workers are thinking about quitting their jobs](https://www.axios.com/resignations-companies-e279fcfc-c8e7-4955-8a9b-47562490ee55.html)  
I don't blame anyone for pursuing jobs that fit better to their lifestyle. I also realize a 40% is a tectonic shift in the workforce. If this holds true, we're all going to be impacted in some way.

[Southwest Airlines cancels 500 flights after computer glitch grounds fleet](https://www.reuters.com/business/aerospace-defense/southwest-airlines-temporarily-halted-flights-over-computer-issue-2021-06-15/)  
Southwest had a rough week.

[Petition To Not Allow Jeff Bezos Re-Entry To Earth](https://www.change.org/p/blue-origin-petition-to-not-allow-jeff-bezos-re-entry-to-earth)  
I expect thorough coverage of this in [Last Week in AWS](https://ref.lastweekinaws.com/7h1z3x). But, 17,000+ people are on board with this.

[The iPhone 12 Mini Makes Me Sick (Literally)](https://spectrum.ieee.org/view-from-the-valley/consumer-electronics/audiovideo/the-iphone-12-mini-makes-me-sick-literally)  
How a screen lights itself can cause major problems for some people.

## Process

[(Technical) Infosec Core Competencies](https://www.netmeister.org/blog/infosec-competencies.html)  
"#50 Nothing, absolutely nothing about cryptocurrencies. "Crypto" means "cryptography". That's all you need to know." I can get behind this list. If you know all this, I hope security people in your org know who you are.

[AWS IAM in a layman's terms. IAM policy setup to give development team maximal velocity and autonomy](https://goteleport.com/blog/aws-iam-in-laymans-terms/?utm_campaign=eg&utm_medium=partner&utm_source=DevOpsish)  
Learn about leveraging the right type of AWS IAM policy mechanisms to build the responsibility separation between the “central” team and the individual “development” team. *SPONSORED*

[Google Wants To See Rust Code In The Linux Kernel, Contracts The Main Developer](https://www.phoronix.com/scan.php?page=news_item&px=Google-Wants-Rust-In-Kernel)  
"Google is going public today with their formal support for Rust in the Linux kernel to enhance memory safety and that they have contracted developer Miguel Ojeda to further his work on Rust for the Linux kernel and related security efforts. This contract is going through at least the next year."

[Hacker community jumps on hilarious Twitter meme mocking bad infosec advice from CISOs](https://portswigger.net/daily-swig/hacker-community-jumps-on-hilarious-twitter-meme-mocking-bad-infosec-advice-from-cisos)  
Rub some WAF on it and walk it off.

[How to Handle Secrets on the Command Line](https://smallstep.com/blog/command-line-secrets/)  
"The command line really wasn’t designed for secrets. So, keeping secrets secret on the command line requires some extra care and effort..."

## Tools

[Bye bye Travis CI](https://daniel.haxx.se/blog/2021/06/14/bye-bye-travis-ci/)  
Damn... Even curl can't use Travis CI anymore. How the mighty have fallen indeed.

[LaunchDarkly Named a Leader in Feature Management and Experimentation](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)
Discover why in its first Wave report dedicated to Feature Management And Experimentation, Forrester rates LaunchDarkly's platform a Leader among vendor features that enable development teams to reduce software release headaches and enable true testing in production. [Download today](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)! *SPONSORED*

[OpenSSL 3.0 Release Candidate Arrives With Big Changes](https://www.phoronix.com/scan.php?page=news_item&px=OpenSSL-3.0-Release-Candidate)  
"OpenSSL 3.0 has migrated to a provider-based architecture for allowing greater flexibility. fully "pluggable" TLSv1.3 groups, new encoder and decoder support, a complete Certificate Management Protocol (CMP) implementation, new APIs, and integrated support for kernel TLS are among the many big changes coming with OpenSSL 3.0."

[Rust is not a Company](https://blog.m-ou.se/rust-is-not-a-company/)  
"There are many things for which we should have space, but currently don’t have space for. But if we keep trying. If we keep making small improvements. Keep adapting. Keep looking out for those around us who want to contribute too; how we can empower them, and each other. Then every step will be one in the right direction, making Rust and all of the many people who work on it, and with it, thrive."

[Thousands of Vulnerable VMWare vCenter Servers Still Publicly Exposed (CVE-2021-21985, CVE-2021-21986)](https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/thousands-of-vulnerable-vmware-vcenter-servers-still-publicly-exposed-cve-2021-21985-cve-2021-21986/)  
Using Shodan to Pwn vCenter... Why are these internet accessible?!? Seriously.

[Google’s unified Gmail interface (and Google Chat) launches for everyone](https://arstechnica.com/gadgets/2021/06/gmails-big-merger-with-google-chat-meet-and-docs-launches-for-everyone/)  
It's awful and I want nothing to do with it.

[Git for Computer Scientists](https://eagain.net/articles/git-for-computer-scientists/)  
A nerdy, useful guide.

[Linux Commands Cheat Sheet 2021](https://linuxguidehq.com/linux-commands-cheat-sheet/)  
"This is the ultimate guide to Linux Command Cheat Sheet in 2021." I mean... It's pretty good.

[A DNA-based storage system with files and metadata](https://arstechnica.com/science/2021/06/researchers-build-a-metadata-based-image-database-using-dna-storage/)  
This could be game changing technology.

[ibraheemdev/modern-unix](https://github.com/ibraheemdev/modern-unix)  
A collection of modern/faster/saner alternatives to common unix commands.

[rustdesk/rustdesk](https://github.com/rustdesk/rustdesk)  
Yet another remote desktop software

[benbjohnson/litestream](https://github.com/benbjohnson/litestream)  
Streaming replication for SQLite.

[slok/sloth](https://github.com/slok/sloth)  
🦥 Easy and simple Prometheus SLO (service level objectives) generator

## DevOps'ish Tweet of the Week

[![Cake is Kate. Always has been. 💫 @kefimochi: "You're not a machine. You can't be 110% productive at all times, and that's okay."](https://shortcdn.com/devopsish/223-devopsish-tweet-of-the-week.png)](https://twitter.com/kefimochi/status/1405222523512365056)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/223/notes/) to see what didn't make it to the newsletter but are still worth your time.
