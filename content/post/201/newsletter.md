+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2021-01-17T07:00:00Z
description = ""
draft = false
slug = "201"
tags = []
title = "DevOps'ish 201: "

+++

I lost a co-worker from the Ansible team this week. I've been struggling to get past the insanity of people younger than dying. 2021 is off to a real shit start. But, I think the biggest tech story of the week comes from Elastic. Keep reading for the details on Elastic's idiocy. Here's your weekly reminder that open source isn't a business model, though.

But, there's been a moment of justice for those here in Michigan who were impacted by the [Flint Water Crisis](https://en.wikipedia.org/wiki/Flint_water_crisis). [Ex-Michigan governor indicted for 'willful neglect' in Flint water crisis](https://arstechnica.com/tech-policy/2021/01/ex-michigan-governor-indicted-for-willful-neglect-in-flint-water-crisis/). Here's the [grand jury indictment](https://www.michigan.gov/documents/ag/GJ_Indictment_-_Snyder_R_712955_7.pdf) of Former Michigan Governor, Rick Snyder. The Judicial System better not mess this up.

I also learned about the term [Sealioning](https://en.wikipedia.org/wiki/Sealioning) this week. I've seen it done before but, did not know it had a definition that I could shut folks down with. Nice!

**Note**: I'm looking for an intern this summer to help with [OpenShift.tv](https://OpenShift.tv) (live streaming). If you know anyone that may be interested, please ask them to apply. If they have questions, feel free to send them my way ([Twitter DMs](https://twitter.com/ChrisShort), [Telegram](https://t.me/ChrisShort)). Please [apply ASAP](https://us-redhat.icims.com/jobs/83032/openshift.tv-associate-producer-internship/job) as I'm already reviewing resumes this weekend.

## People

[GitHub still won’t explain if it fired someone for saying ‘Nazi,’ and employees are pissed](https://www.theverge.com/2021/1/15/22232766/github-employees-protest-jewish-employee-firing-warn-nazi)  
"Now in protest, they’re using Slack to call Nazis what they are" I'm totally dumbfounded by this. A Jewish employee tells his Jewish friends and coworkers to be safe during the insurrection of 2021 because nazi flags are clearly on display then gets fired. "Now, GitHub workers are saying 'Nazi' repeatedly in Slack, in regards to the US Capitol rioters, to protest what is being perceived as unfair treatment." Fix this GitHub, I know you're reading this.

[I'm an Impostor - Incarceration and Living a Lie](https://theworst.dev/im-an-impostor/)  
"Every day, I walk around telling little lies so I can project this false image of myself. I would like to tell you this is a story about how I feel like I don't know enough, and then I realized that people don't know shit either, but this isn't that story." This is an amazing story of hitting rock bottom and bouncing back. Now, Kurt Kemple in trying to help inmates while bringing awareness to us in tech about those in incarceration. Mad props to you, Kurt.

[Confronting our own racism as white engineering managers](https://leaddev.com/diversity-inclusion/confronting-our-own-racism-white-engineering-managers)  
"But there is very little formal management advice for White people about recognizing and understanding our racism in managing and leading Black and other employees of color." This article makes the argument that if you're a white manager you have not only the organization giving you power but, the echos and often drum beat of White Supremacy as well. I would highly encourage sharing this with your managers. Tell them Chris Short told you to.

[Millions Flock to Telegram and Signal as Fears Grow Over Big Tech](https://www.nytimes.com/2021/01/13/technology/telegram-signal-apps-big-tech.html)  
People dropping WhatsApp like a bad habit. Join DevOps'ish on [Telegram](https://t.me/devopsish) or [Reddit](https://www.reddit.com/r/devopsish/). We're looking into alternative platforms as well in case these become unstable. [Signal went down on Friday](https://www.reuters.com/article/us-signal-outage/signal-back-up-after-outage-idUSKBN29M02O) under the deluge of new users.

[Intel lured new CEO Pat Gelsinger with a package valued at $116 million](https://www.oregonlive.com/silicon-forest/2021/01/intel-lured-new-ceo-pat-gelsinger-with-a-package-valued-at-116-million.html)  
For a cool $116 million you too can have a smooth talking, boisterous, and hopefully transformative CEO. I'm considering this Intel's hail mary against ARM and RISC-V after MANY bad years of not so great outcomes. Check the [Intel tag here on DevOps'ish](https://devopsish.com/tags/intel) if you need a reminder.

[Dropbox to cut 11% of its global workforce](https://www.cnbc.com/2021/01/13/dropbox-to-cut-11percent-of-its-global-workforce.html)  
This sucks.

## Process

[Secondary stock sale to Sequoia values Zapier at more than $4 billion](https://siliconflorist.com/2021/01/15/secondary-stock-sale-to-sequoia-values-zapier-at-more-than-4-billion/)  
I like Zapier and use it for a lot of things that power this newsletter. While an interesting way to invest in a company, it's not uncommon, and Sequoia knows what it's doing. I see this as a very good sign for Zapier's future.

[Download today: Kubernetes security ebook - tips, tricks, best practices](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh)  
The rapid adoption of Kubernetes to manage containerized workloads is driving great efficiencies in application development, deployment, and scalability. However, when security becomes an afterthought, you risk diminishing the greatest gain of containerization - agility. [Download this ebook](https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html?Source=DevOpsIsh&LSource=DevOpsIsh) to learn how to (1) build secure images and prevent untrusted/vulnerable code, (2) configure RBAC, network policies, and runtime privileges, (3) detect unauthorized runtime activity, and (4) secure your Kubernetes infrastructure components such as the API server. *SPONSORED*

[[SECURITY] CVE-2021-24122 Apache Tomcat Information Disclosure](http://mail-archives.apache.org/mod_mbox/www-announce/202101.mbox/%3Cf3765f21-969d-7f21-e34a-efc106175373%40apache.org%3E)  
"When serving resources from a network location using the NTFS file system it was possible to bypass security constraints and/or view the source code for JSPs in some configurations. The root cause was the unexpected behaviour of the JRE API File.getCanonicalPath() which in turn was caused by the inconsistent behaviour of the Windows API (FindFirstFileW) in some circumstances." I know for a fact there are quite a few orgs using NTFS as mount points for Tomcat to consume.

[A security researcher commandeered a country’s expired top-level domain to save it from hackers](https://techcrunch.com/2021/01/15/congo-comandeered/)  
Good triumphs over evil yet again.

[CISA tells agencies to consider ad blockers to fend off 'malvertising'](https://www.cyberscoop.com/ad-blockers-security-nsa-dhs-wyden/)  
Here's a suggestion: Ask your company to donate to [EFF](https://supporters.eff.org/donate/) and start using [Privacy Badger](https://privacybadger.org/) everywhere.

## Tools

[Elasticsearch and Kibana are now business risks](https://anonymoushash.vmbrasseur.com/2021/01/14/elasticsearch-and-kibana-are-now-business-risks)  
My friend, VM (Vicky) Brasseur, points out the the [changes in licenses for Elasticsearch and Kibana](https://www.elastic.co/blog/licensing-change) are, "As licenses go, it’s pretty problematic from a business perspective." Also, don't put your faith in an FAQ when there's a legally binding document that concerns every intellectual property lawyer, "when you agree to a license you are agreeing to the text of that license document and not to a FAQ. If the text of that license document is ambiguous, then so are your rights and responsibilities under that license." [SSPL](https://en.wikipedia.org/wiki/Server_Side_Public_License) is not endorsed by the [OSI](https://opensource.org/), period. It's not an open source license. It's not permissive. This means that if you stick with the open versions of these projects, you're not getting security updates. This is the business problem. Adopting the new SSPL'd projects will require orgs to have to release the entire stack under SSPL, which is kinda bullshit. Read Vicky's post for all the semantics and possibilities that are no longer possible with this change. Needless to say [ELK](https://www.elastic.co/what-is/elk-stack) and [EFK](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-elasticsearch-fluentd-and-kibana-efk-logging-stack-on-kubernetes) stacks are potentially liabilities now. Thanks for nothing, Elastic.

**We need your voice!**

In partnership with the team at ClearPath Strategies, [Honeycomb.io](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish) is collecting insights for changes in software development and operation practices across our industry. How do you see the world and what your team is doing?

[Take the survey](https://clearpathstrategies.sjc1.qualtrics.com/jfe/form/SV_cMAECZ6jv5wmjrL?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=software-production-excellence-survey-clearpath-devopsish&utm_adgroup=) for a chance to win $500 from Apple, HelloFresh, or Fender. *SPONSORED*

[Sysdig 2021 container security and usage report: Shifting left is not enough](https://sysdig.com/blog/sysdig-2021-container-security-usage-report/)  
Now I need to update my Security at Cloud Native speed talk. I haven't had time to read it yet but, this report gave me a ton of ideas and insight last year. I hope for the same this year.

[The Final Report on the Slack Outage](https://devopsish.com/pdf/Slack-Incident-Jan-04-2021-RCA-Final.pdf)  
This one jumped out at me, "We have increased the open file handle limit on our provisioning service workers." That's a tough pill to swallow. I wouldn't imagine this NOT causing a problem of some sort frequently. Mainly capacity issues too.

[Apple removes feature that allowed its apps to bypass macOS firewalls and VPNs](https://www.zdnet.com/article/apple-removes-feature-that-allowed-its-apps-to-bypass-macos-firewalls-and-vpns/)  
"The ContentFilterExclusionList has been removed in macOS 11.2 beta 2."

[Criminals are Bypassing MFA to Access Organisation's Cloud Services](https://www.tripwire.com/state-of-security/featured/hackers-bypassing-mfa-to-access-organisations-cloud-services/)  
"In the case it cited, CISA said it believed the malicious hackers may have used a ["pass-the-cookie" attack](https://stealthbits.com/blog/bypassing-mfa-with-pass-the-cookie/) to waltz around MFA." The full CISA report is here: [Attackers Exploit Poor Cyber Hygiene to Compromise Cloud Security Environments](https://us-cert.cisa.gov/ncas/current-activity/2021/01/13/attackers-exploit-poor-cyber-hygiene-compromise-cloud-security)

[Analyze Kubernetes files for errors with KubeLinter](https://opensource.com/article/21/1/kubelinter)  
"Find and fix errors in your Helm charts and Kubernetes configuration files with KubeLinter."

[Tutorial: Encrypting Kubernetes Secrets with Sealed Secrets](https://www.arthurkoziel.com/encrypting-k8s-secrets-with-sealed-secrets/)  
Sealed Secrets is a solution to store encrypted Kubernetes secrets in version control. This also applies to the GitOps world as well. Rotate these frequently.

[A “no math” (but seven-part) guide to modern quantum mechanics](https://arstechnica.com/science/2021/01/the-curious-observers-guide-to-quantum-mechanics/)  
"Welcome to 'The curious observer's guide to quantum mechanics'–featuring particle/wave duality."

[Issues · kubernetes/kube-state-metrics](https://github.com/kubernetes/kube-state-metrics/labels/help%20wanted)  
kube-state-metrics has some help wanted issues that could be a great way for readers to get involved with this critical Kubernetes component. Plus, you'll get to collaborate with some really awesome people.

[davidhampgonsalves/life-dashboard](https://github.com/davidhampgonsalves/life-dashboard)  
Heads up Display for every day life

[lorin/awesome-limits](https://github.com/lorin/awesome-limits)  
Examples of OS / system limits (*cough* Slack *cough*)

[akinomyoga/ble.sh](https://github.com/akinomyoga/ble.sh)  
Bash Line Editor -- a full-featured line editor written in pure Bash! Syntax highlighting, auto suggestions, vim modes, etc. are available in Bash interactive sessions!

[sandstorm/sku](https://github.com/sandstorm/sku)  
Sandstorm Kubernetes Client - Convenience tools to interact with Kubernetes

## DevOps'ish Tweet of the Week

[![Meanwhile in the "lies @elastic told us" department... How it started: vs. How it's going:](/images/201-devopsish-tweet-of-the-week.png)](https://twitter.com/QuinnyPig/status/1350205491750662146?utm_source=newsletter&utm_medium=devopsish&utm_campaign=201)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/201/notes/) to see what didn't make it to the newsletter.
