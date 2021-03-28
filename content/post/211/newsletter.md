+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-03-28T07:00:00Z
description = "He who was mentioned in DevOps'ish 145, OpenSSL updates, New AWS CEO, Apple linked to Chinese tracking apps, 92% of all on-premises Microsoft Exchange servers patched, TSMC, coffee shortage, and more"
draft = false
slug = "211"
tags = ["DevOps", "Linux", "cloud", "cloud native", "Microsoft", "open source", "Google", "Exchange", "vulnerabilities", "FSF", "Kubernetes", "TLS", "Red Hat", "OpenSSL", "Discord", "Rust", "Windows", "AWS", "CEO", "Cloud Native Computing Foundation", "Apple", "Uyghur", "Outreachy", "Asian", "Linux Torvalds", "kubectl", "OpenSSH"]
title = "DevOps'ish 211: He who was mentioned in DevOps'ish 145, OpenSSL updates, New AWS CEO, Apple linked to Chinese tracking apps, 92% of all on-premises Microsoft Exchange servers patched, TSMC, coffee shortage, and more"

+++

Well, what’s it like living in the last throes of the Free Software Foundation (FSF)? Many companies came out against the FSF's recent decision to re-add [he who was mentioned in DevOps'ish 145](https://devopsish.com/145/). [Red Hat probably gave the most scathing repudiation](https://www.redhat.com/en/blog/red-hat-statement-about-richard-stallmans-return-free-software-foundation-board). I can think of no worse strategy than bringing back someone who for so long abused, criticized, belittled, harassed, and bullied the people (especially women) around them. I used to support FSF and only did so after [he who was mentioned in DevOps'ish 145](https://devopsish.com/145/) ([droves of others are denouncing the decision too](https://arstechnica.com/tech-policy/2021/03/free-software-advocates-seek-removal-of-richard-stallman-and-entire-fsf-board/)).

It's truly rare that I reassess my automated donations and think about where I'm donating money. I'm glad this utterly insane event sparked this reevaluation for me. Now that [he who was mentioned in DevOps'ish 145](https://devopsish.com/145/) is back at the FSF, [I put out a call on Twitter](https://twitter.com/ChrisShort/status/1374110058016092168) for suggested charities or foundations I could support. Folks came through.

I've not only found a better place to send money than FSF, but I also added more causes in the process. I try to live life as transparently as possible. I do list what [Causes I support](https://chrisshort.net/causes/) on my website. I'm happy to say that I added the [Software Freedom Conservancy](https://sfconservancy.org/), [Outreachy](https://www.outreachy.org/), and [/dev/color](https://www.devcolor.org/) this week. I probably should have been supporting Outreachy long ago but, it's better late than never. There are probably many other places I could be putting money to foster a more inclusive tech sector. If you, dear reader, have suggestions about which non-profits I should be engaged with, please hit reply and let me know.

**Editor's Note**: Another newsletter I contribute to ([KubeWeekly](https://kubeweekly.io/)) recently toyed with the idea of a section for videos, streams, podcasts, etc. I am wondering what you would think about a section specifically for Audio and Video content on DevOps'ish. [**Vote here**](https://www.strawpoll.me/42863619)!

## People

[How Anti-Asian Activity Online Set the Stage for Real-World Violence](https://www.nytimes.com/2021/03/19/technology/how-anti-asian-activity-online-set-the-stage-for-real-world-violence.html)  
"On platforms such as Telegram and 4chan, racist memes and posts about Asian-Americans have created fear and dehumanization."

Running queries and getting results fast should be table stakes so you can find hidden problems. See how Honeycomb allows you to ask any question and get results fast, no matter how many fields, without writing new code.

Observe, debug, and improve with [Honeycomb](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish)—join our [Weekly Live Demo](https://honeycomb.zoom.us/webinar/register/7216158407556/WN_R8Sd0hmyS0eG7i6EKH-eAw) to learn more. *SPONSORED*

[AWS announces next CEO](https://www.aboutamazon.com/news/company-news/aws-announces-next-ceo)  
"I want to share that Adam Selipsky will be the next CEO of AWS."

[LEGO IDEAS - Women of Computing](https://ideas.lego.com/projects/3bf5b46c-6c87-4a2d-a2e1-d31ed0e2739e)  
I want this set. Vote for this!

[What happens when ICE asks Google for your user information](https://www.latimes.com/business/technology/story/2021-03-24/federal-agencies-subpoena-google-personal-information)  
"The email, sent from Google’s Legal Investigations Support team, notified the recipient that Google may hand over personal information to DHS unless it receives within seven days a copy of a court-stamped motion to quash the request. That’s a high bar to clear in a short amount of time, said Paromita Shah, co-founder and executive director of immigration rights law firm Just Futures."

[Be More Realistic About the Time You Have](https://hbr.org/2021/03/be-more-realistic-about-the-time-you-have)  
"It’s no surprise that many of us overload our workday, assuming we can take on many tasks in a small amount of time. Yet, at the end of the day, we’re stunned to find that work remains unfinished. Despite past evidence, our predictive engines gum up, and we’re convinced we’ll be able to achieve the extraordinary in an ordinary day. This is called “magical thinking,” and it can cause you to disappoint others, miss deadlines, feel depleted, and lose your inspiration. But you can break free of this habit."

[Working from home is causing breakdowns. Ignoring the problem and blaming the pandemic is no longer an option](https://www.theglobeandmail.com/business/article-people-are-at-the-point-of-emotional-exhaustion-why-white-collar/)  
"What followed was something she described as a total 'collapse.' She spent days in bed, mostly hiding in the darkness of her room. Ultimately, Ms. Durant took a six-week leave from work, marking the first time in her professional career she had been off for more than two weeks at one time."

[100 Women Share Their Earliest Memories of Experiencing Racism](https://www.oprahdaily.com/life/a35844692/100-women-of-color-first-encounter-with-racism/)  
"Tiffany Haddish, Patti LaBelle, Secretary Deb Haaland, Misty Copeland, Gayle King, and dozens more remind us that words matter."

## Process

[Report claims Apple hosts apps run by sanctioned Chinese organization with Uyghur persecution links](https://www.imore.com/report-claims-apple-hosts-apps-run-sanctioned-chinese-organization-uyghur-persecution-links)  
"Apps for various uses were reportedly made by "various units of the Xinjiang Production and Construction Corps" which is accused of links to Uyghur abuses."

[Never wait for a staging environment again](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=title&utm_campaign=20210228) 👩‍💻🧑‍💻👨‍💻👩‍💻  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team's ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. You'll never have to wait around for staging environments again. 💡 [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=20210228) 💡 *SPONSORED*

[Microsoft Defender Antivirus now automatically mitigates Exchange Server vulnerabilities](https://www.zdnet.com/article/microsoft-defender-antivirus-now-patches-exchange-server-vulnerabilities/)  
This plus a lot of hard work has led to [92% of all on-premises Microsoft Exchange servers exposed online affected by the ProxyLogon vulnerabilities are now patched](https://securityaffairs.co/wordpress/115896/security/microsoft-exchange-patched.html).

[Open Source Contributor Index (OSCI)](https://opensourceindex.io/)  
"The table below shows the OSCI ranking for GitHub activity in February 2021. This month we’ve also extended the ranking to show over 250 organisations that contribute to Open Source. A significant observation this month is the overall increase in the level of engagement compared to February 2020; suggesting a long-term upward trend in the growth of corporate Open Source activity."

[The U.S. Air Force Just Admitted The F-35 Stealth Fighter Has Failed](https://www.forbes.com/sites/davidaxe/2021/02/23/the-us-air-force-just-admitted-the-f-35-stealth-fighter-has-failed/)  
Wow... Just wow.

[TSMC: How a Taiwanese chipmaker became a linchpin of the global economy](https://arstechnica.com/gadgets/2021/03/tsmc-how-a-taiwanese-chipmaker-became-a-linchpin-of-the-global-economy/)  
This was a truly fascinating read.

[The World Is Facing a Coffee Deficit in Supply Chain ‘Nightmare’](https://www.bloombergquint.com/business/coffee-trade-reeling-from-virus-faces-nightmare-freight-snags)  
"Coffee supplies in the U.S. are shrinking and wholesale prices are surging, with the hard-hit market bracing for further fallout from a global shortage of shipping containers that’s upended the food trade."

## Tools

[Release OpenSSL_1_1_1k · openssl/openssl](https://github.com/openssl/openssl/releases/tag/OpenSSL_1_1_1k)  
This release of OpenSSL patch two HIGH rated vulnerabilities. CVE-2021-3450 deals with a bypass of checks against certs. CVE-2021-3449 fixes a potential denial of service in all versions of OpenSSL 1.1.1. More details can be found on the [OpenSSL vulnerabilities page](https://www.openssl.org/news/vulnerabilities.html).

[[Free Book] Definitive Guide to Feature Management](https://launchdarkly.com/the-definitive-guide-to-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
Feature management is a new class of software development tools & techniques powered by feature flags. A feature management platform like LaunchDarkly fills the gaps of conventional feature toggles. Learn the ins & outs of feature management today.
Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Report: Microsoft in advanced talks to buy Discord, deal could come next month](https://siliconangle.com/2021/03/25/report-microsoft-advanced-talks-buy-discord-deal-come-next-month/)  
In my opinion, Discord could say no to this and IPO on a significant exchange in a year. Discord is already better in a lot of ways than Teams. This is quite the conundrum.

[Red Hat Enterprise Linux Presents... Diving into /proc](https://www.youtube.com/watch?v=y8C4MytPci8)  
"A show that features the people and technology that make Red Hat® Enterprise Linux® into the world’s leading enterprise Linux platform."

[Linus Torvalds on where Rust will fit into Linux](https://www.zdnet.com/article/linus-torvalds-on-where-rust-will-fit-into-linux/)  
"Slowly but surely the Rust language is making its way into Linux. I talked with Linus Torvalds and Greg Kroah-Hartman about where they see Rust and Linux working together."

[Samsung Announces 512GB DDR5 Memory That Is Twice As Fast As DDR4](https://hothardware.com/news/samsung-512gb-ddr5-memory-2x-faster-ddr4)  
The ability to run multiple Electron apps has arrived.

[Silly Kubectl Tricks](https://starkandwayne.com/silly-kubectl-tricks/)  
"In the fall of 2019, we had a vision: to produce the worlds best video and blog series about the little micro-optimizations and fun tricks you can make the Kubernetes CLI do. This is that series. Silly Kubectl Tricks."

[RFC 8996 - Deprecating TLS 1.0 and TLS 1.1](https://datatracker.ietf.org/doc/rfc8996/)  
Goodbye, TLS 1.0 and TLS 1.1.

[How to Set Up OpenSSH on a Windows Server [Complete Guide]](https://adamtheautomator.com/openssh-windows/)  
"In this tutorial, you’re going to learn how to SSH into your Windows Server just as easily as Linux. You’ll learn how to get OpenSSH installed (or updated) on Windows, add appropriate firewall rules, and configure public key, password, and certificate-based authentication."

[ContainerSolutions/k8s-deployment-strategies](https://github.com/ContainerSolutions/k8s-deployment-strategies)  
Kubernetes deployment strategies explained

[argoproj-labs/argocd-image-updater](https://github.com/argoproj-labs/argocd-image-updater)  
Automatic container image update for Argo CD

## DevOps'ish Tweet of the Week

[![@thelongshanx on Twitter: "Shared this photo with my mostly-tech-industry pandemic-bubble and my non-tech sweetie replied: I'm gonna assume this is what you all mean by 'Ship it.'"](/images/211-devopsish-tweet-of-the-week.png)](https://twitter.com/thelongshanx/status/1375685164836134919)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/211/notes/) to see what didn't make it to the newsletter but are still worth your time.
