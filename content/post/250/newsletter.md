+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-01-02T07:00:00Z
description = ["2021 is so 2020, It's not you, it's them, US 5G rollout issues, P2E gaming, Log4j (still), Microsoft Exchange year 2022 bug, privacy's big year, has serverless peaked, youki, and more"]
draft = false
slug = "250"
tags = ["2021", "year", "Kubernetes", "privacy", "DevOps", "Honeycomb", "code", "tech", "search", "Blackberry", "AWS", "Apple", "speed", "serverless", "transistor", "keycloak", "software", "CLI", "time", "tax", "internet", "engineering", "safety", "aircraft", "United States", "Google", "Log4j", "CVE", "Microsoft", "AWS", "encrypted", "developers", "LastPass", "intelligence", "secure", "performance", "kubectl"]
title = "DevOps'ish 250: 2021 be gone, It's not you, it's them, US 5G rollout issues, P2E gaming, Log4j (still), Microsoft Exchange year 2022 bug, privacy's big year, has serverless peaked, youki, and more"

+++

Happy New Year! 🎉🥳🎊 I wish you the absolute best in 2022.

I'm still in the process of writing my annual learnings and expectations blog post. Please keep your eyes peeled for that to drop on [ChrisShort.net](https://chrisshort.net/) in the coming days. Feel free to subscribe to the [RSS feed](https://chrisshort.net/index.xml) if you'd like. Also, if you're not reading this on the web, check out the new coat of paint applied to [DevOps'ish.com](https://devopsish.com/). I like the [search functionality](https://devopsish.com/search/) I implemented which was sorely missing previously. The site is very lightweight and performant now. Let me know if you see any problems.

In great news for the newsletter, [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) will be the *sole* sponsor of DevOps'ish in 2022. Working with Honeycomb has been an absolute joy and their leadership team 100% supports the work being done here. Do me a favor and give [Honeycomb](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) serious consideration for your observability and telemetry needs in the future. "Guess less. Know more."

As it is a new year and there are likely many new subscribers unaware, I maintain many what I call "helper sites" designed to get you up to speed and keep you informed (pull requests welcomed). I'll list them here for your benefit:

* [DevOps Newsletters](https://devopsnewsletters.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=250)
* [Kubernetes News](https://kubenews.net/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=250)
* [DevOps README.md](https://devopsreadme.xyz/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=250)
* [Kubernetes README](https://kubereadme.com/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=250)
* [What is DevOps](https://devopsish.com/what-is-devops/?utm_source=newsletter&utm_medium=email&utm_campaign=devopsish&utm_id=250) (free ebook)

## People

[SOFTWARE ENGINEER INTERVIEWS BE LIKE | A Maya Bello Short Film](https://www.youtube.com/watch?v=qEjT7MOiifE)  
The interview process is broken. I've flat out rejected doing whiteboard and homework during interviews because you're just wasting my time at that point trying to prove that I know how to do X without any context as to the why behind the question (oh let me pull that out of you by asking a bunch of questions you never considered). It's annoying and superfluous. I don't want to do work for a company I don't work for (there's no way to create passion or pride for that kind of work (even if compensated)). Can we just stop all this nonsense somehow in 2022? Remember, it's not the person's being interviewed job to prove out your interview processes. You have to do that on your own by looking at the outputs of that process. Be better.

[A Lavish Tax Dodge for the Ultrawealthy Is Easily Multiplied](https://www.nytimes.com/2021/12/28/business/tax-break-qualified-small-business-stock.html)  
I've gotta figure out a way to take advantage of this and you should too. But, the right thing to do would be to simplify the US tax code tremendously.

[It's not you, it's them](https://trishagee.com/2021/12/28/nil-carborundum-illegitimi/)  
"But don't let it put you off. Don't let the voices in your head (or on the internet) stop you from trying. It's the trying that counts, that helps us improve."

[How to Know Whether Your New Job is a Shitshow or Not](https://www.honeycomb.io/blog/first-impressions-new-job/?&utm_source=devopsish&utm_medium=newsletter)  
"We here at Honeycomb have some pretty strong opinions on the interviewing and hiring process: Namely, that it is broken af in our industry, for engineering and non-engineering roles alike." Word!

[U.S. officials ask AT&T, Verizon to delay 5G wireless over aviation safety concerns](https://www.reuters.com/business/aerospace-defense/us-officials-ask-att-verizon-delay-5g-wireless-over-aviation-safety-concerns-2021-12-31/)  
Using older C-band spectrums for 5G could cause some major concerns for aircraft flying and landing in the United States. Radio altimeters are quite important for aircraft. Knowing where the ground is has many safety benefits. I see this as a major setback for 5G rollout in the United States.

[2021 End-Of-Year Work Setup](https://jameslittle.me/blog/2021/2021-work-setup/)  
Some useful bits in here if you're looking to update some things on your desk. For example, I might use the keylights mentioned in this post when I finally move into our soon to be finished basement.

[Best of 2021 in Tech [Talks]](https://copyconstruct.medium.com/best-of-2021-in-tech-talks-331ec9454b4)  
"There were a number of very interesting papers that came out in 2021 that made it to my reading list, but I just didn’t manage to read. Here’s hoping 2022 proves to be a more fruitful and productive year."

[Korean government tells Apple and Google stores to take down P2E games](https://cointelegraph.com/news/korean-government-tells-apple-and-google-stores-to-take-down-p2e-games)  
It's just a game (until it's a job). [Paul Butler has a well informed take](https://paulbutler.org/2021/play-to-earn-and-bullshit-jobs/) on pay-to-earn games.

## Process

[Apache Log4j 2.17.1 fixes remote code execution flaw (CVE-2021-44832)](https://securityaffairs.co/wordpress/126135/hacking/new-apache-log4j-cve-2021-44832.html)  
At what point in time do we replace Log4j? It's a CVE factory at the moment and that's scary af for big Java shops trying to go about their business. Security teams have been scrambling for weeks and there isn't a real end in sight at the moment due to enormous uncertainty. I'm not saying rewrite your whole stack, but if you're not contemplating alternatives at this point, I want to know why.

[Microsoft Exchange year 2022 bug in FIP-FS breaks email delivery](https://www.bleepingcomputer.com/news/microsoft/microsoft-exchange-year-2022-bug-in-fip-fs-breaks-email-delivery/)  
I'm sure this is causing a lot of work to happen that could have been avoided. [Microsoft says it has a fix](https://techcommunity.microsoft.com/t5/exchange-team-blog/email-stuck-in-transport-queues/ba-p/3049447). But, after Y2K, how are big software companies not testing their software for year changes???

[More than 1,200 phishing toolkits capable of intercepting 2FA detected in the wild](https://therecord.media/more-than-1200-phishing-toolkits-capable-of-intercepting-2fa-detected-in-the-wild/)  
That is a LOT of ways to crack or bypass 2FA.

[Privacy-focused search engine DuckDuckGo grew by 46% in 2021](https://www.bleepingcomputer.com/news/technology/privacy-focused-search-engine-duckduckgo-grew-by-46-percent-in-2021/)  
Privacy had a BIG year in 2021 (I deleted all my Facebook owned profiles and switched to [DDG](https://duckduckgo.com/) as my default search engine). I saw this coming given the [privacy practices](https://devopsish.com/privacy/) in use for this newsletter since 2018 (y'all really appreciate your privacy and I do too). I don't track your activity aside from web site analytics ([which are public](https://app.usefathom.com/share/acmuyzfw/devopsish.com)). I legit wish I could send you an email without you giving me ANYTHING. But, that's going to require a psychic, which doesn't fit into the double opt-in workflow.

[Apple ditched Intel, and it paid off](https://www.cnbc.com/2021/12/29/apple-ditched-intel-and-it-paid-off.html)  
Yeah it did. `arm64` is the future of compute, and at least for Apple consumers, it has been the reality for a year now.

[We Encrypted the Web: 2021 Year in Review](https://www.eff.org/deeplinks/2021/12/we-encrypted-web-2021-year-review)  
"With various measurement sources reporting over 90% of web traffic encrypted, 2021 saw major browsers deploy key features to put HTTPS first. Thanks to Let’s Encrypt and EFF’s own Certbot, HTTPS deployment has become ubiquitous on the web." I [regularly contribute](https://chrisshort.net/causes/) to [EFF](https://www.eff.org/).

[TikTok tops Google as the most visited website on the internet](https://www.cbsnews.com/news/tiktok-google-facebook-social-media-internet/)  
Both are generally considered invasive and one is tied to a government. Not using either improves your privacy posture.

## Tools

[Kubernetes adoption up, serverless down, developer survey says](https://www.infoworld.com/article/3645374/kubernetes-up-serverless-down-report.html)  
Has serverless peaked? "The proportion of developers involved in serverless architecture fell from 27 percent to 24 percent, the survey found."

[LastPass confirms credential stuffing attack against some of its users](https://therecord.media/lastpass-confirms-credential-stuffing-attack-against-some-of-its-users/)  
Got off LastPass, folks. That ship looks like it is in a bad state.

[Revolutionary New Intelligent Transistor Developed](https://scitechdaily.com/revolutionary-new-intelligent-transistor-developed/)  
"In this way, for example, a NAND gate (a logic not-and gate) can be switched to a NOR gate (a logic neither-nor gate). 'Until now, the intelligence of electronics has come simply from the interconnection of several transistors, each of which had only a fairly primitive functionality. In the future, this intelligence can be transferred to the adaptability of the new transistor itself,' says Prof. Walter Weber. 'Arithmetic operations, which previously required 160 transistors, are possible with 24 transistors due to this increased adaptability. In this way, the speed and energy efficiency of the circuits can also be significantly increased.'"

[The New York Times' 2021 Good Tech Awards](https://www.nytimes.com/2021/12/27/technology/the-2021-good-tech-awards.html)  
As shitty as the tech world is, sometimes actual good comes out of it. Tech to help with a more just judicial system is much appreciated and very welcome.

[Linux 5.17 To Replace SHA1 With BLAKE2s For Faster & More Secure "Random"](https://www.phoronix.com/scan.php?page=news_item&px=Linux-Random-BLAKE2s)  
An update to how `/dev/random` and `/dev/urandom` "using BLAKE2s rather than SHA1 when hashing the entropy pool. This in turn is a big performance speed-up in addition to being more secure." I can't wait.

[glibc is still not Y2038 compliant by default](https://ariadne.space/2021/12/29/glibc-is-still-not-y2038-compliant-by-default/)  
"The approach the GNU project have taken for transitioning to new ABIs is the exact opposite: you must explicitly ask for the new functionality, or you will never get it. This approach leaves open the possibility for changing the defaults in the future, but they have never ever done this so far."

[How a Single Line of Code Made a 24-core Server Slower Than a Laptop](https://pkolaczk.github.io/server-slower-than-a-laptop/)  
A deep dive into the performance hit taken sharing reference counters.

[OIDC Login to Kubernetes and Kubectl with Keycloak](https://www.talkingquickly.co.uk/setting-up-oidc-login-kubernetes-kubectl-with-keycloak)  
"In this post we'll integrate Kubernetes with Keycloak so that when we execute a `kubectl` or `helm` command, if the user is not already authenticated, they'll be presented with a keycloak browser login where they can enter their credentials."

[End of the line finally coming for BlackBerry devices](https://arstechnica.com/information-technology/2021/12/end-of-the-line-finally-coming-for-blackberry-devices/)  
I still have the last Blackberry I ever used. It wasn't my favorite Blackberry ever but, it's a relic I'll hold on to. They were by and large more stable, secure, and had better battery life than Android devices of the day (2000-2010) but, the iPhone pretty much annihilated Blackberry.

[How to automate your GitHub profile README](https://blog.ediri.io/how-to-automate-your-github-profile-readme)  
I need to sit down and figure this tool out.

[containers/youki](https://github.com/containers/youki)  
A container runtime written in Rust 👀

[kubealex/k8s-mediaserver-operator](https://github.com/kubealex/k8s-mediaserver-operator)  
Repository for k8s Mediaserver Operator project

[abahmed/kwatch](https://github.com/abahmed/kwatch)  
Monitor & detect crashes in your Kubernetes(K8s) cluster instantly

[Qovery/pleco](https://github.com/Qovery/pleco)  
Automatically removes Cloud managed services and Kubernetes resources based on tags with TTL

[PopulateTools/ansible-doc-generator](https://github.com/PopulateTools/ansible-doc-generator)  
CLI for documenting Ansible roles into Markdown files.

[awslabs/aws-well-architected-labs](https://github.com/awslabs/aws-well-architected-labs)  
As I find new things I didn't know exist in the AWS world, I'll be sharing them here. "Hands on labs and code to help you learn, measure, and build using architectural best practices."

[aws/copilot-cli](https://github.com/aws/copilot-cli)  
The AWS Copilot CLI is a tool for developers to build, release and operate production ready containerized applications on AWS App Runner, Amazon ECS, and AWS Fargate.

## DevOps'ish Tweet of the Week

[![Ari Paparo Dot Eth (@aripap on Twitter) "This web3 shit is starting to annoy me, so here’s a thread with my opinions on the relevance to media and advertising. 1/21 🧵"](https://shortcdn.com/file/devopsish/250-devopsish-tweet-of-the-week.webp)](https://twitter.com/aripap/status/1474039478671003652)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/250/notes/) to see what didn't make it to the newsletter but are still worth your time.
