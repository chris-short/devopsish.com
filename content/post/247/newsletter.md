+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-12-12T07:00:00Z
description = ["Kubernetes 1.23, Kubernetes Contributor Celebration, DevOps'ish turns 5, Log4j vulnerability, Hashicorp IPO, and more"]
draft = false
slug = "247"
tags = ["Kubernetes", "security", "cloud", "cloud native", "DevOps", "pod", "GitOps", "privacy", "infrastructure", "log4j", "code", "software", "employees", "stock", "Kubernetes Contributor Celebration", "Google", "IPv6", "git", "platform", "equity", "compensation", "billion", "MySQL", "Bluetooth", "open source"]
title = "DevOps'ish 247: Kubernetes 1.23, Kubernetes Contributor Celebration, DevOps'ish turns 5, Log4j vulnerability, Hashicorp IPO, and more"

+++

Hi all, if you thought last week was terrible, I give you this week. I'm not going to add to the already well-detailed list from last week. Instead, I'd like to celebrate something.

## Happy Birthday, DevOps'ish

DevOps'ish turns five years old today! Max was a year old. I told my wife I was starting a newsletter. Two-hundred forty-seven issues later, we've arrived here. This morning, I told Julie, who thought I was nuts at the launch, that DevOps'ish is one of the best things I've done for my career. This has paid off on the home front and improved our overall quality of life. I guess this shouldn't come as a surprise, but the newsletter also enabled MORE charitable giving than before too. Has DevOps'ish been a success? [Yes](https://devopsish.com/praise/).

### DevOps'ish at 5

Is the newsletter self-sustaining? Yes. I've optimized costs as much as possible. I've filled sponsorships as much as I can. The balance sheet is good. The newsletter has pivoted from being a metrics-focused newsletter to being very privacy aware over its five years. I don't want to know anything about the DevOps'ish readership unless they volunteer it. I don't track clicks or open rates, and I'm very upfront about that with sponsors.

Moving off Google Analytics and going to [Fathom Analytics](https://usefathom.com/ref/Z8NTXN) was another win for the privacy-conscious. Fathom has also added on to the excellent services they offer too. Another good move was getting off Mailchimp. It was bumpy for a little bit, but [EmailOctopus](https://emailoctopus.com/?urli=n6msM) provides an excellent service for newslettering. It is also privacy-conscious in that it allows me to turn off tracking features customarily enabled by default and not changeable on other platforms. I hope readers understand and appreciate the great lengths gone in the name of privacy.

After being on Netlify for years this past month, I finally had to start a paid plan. I'm buying time as I think through how to refactor the DevOps'ish website to optimize build times. I could write a whole blog post about the one dumb design decision that has created an infrastructure problem for myself (and I probably will at some point). But, I can buy time, as I said. Which is nice given how hectic life is right now.

### DevOps'ish going from 5 to 10

One area where I'm not thrilled with the newsletter is in the subscriber count. Sharing how I feel or how one thing interacts with a societal structure thus, "politics" are discussed in the newsletter leads to a narrowing of the audience. This leaves me with a choice: A) don't associate anything political thing with anything in tech (like purists think it should be, which isn't reality) or B) make me more aware of their surroundings.

I'm going to choose option B. That will rub people the wrong way. The worst thing that can happen to DevOps'ish is subscriber count stagnation. The privacy policies discussed earlier mean the only metric I can sell sponsors on is the number of subscribers. The success of this newsletter lies in its ability to get folks to subscribe to it.

I see a referral program in the future. But I feel like that means a swag shop for rewards too. These are all great things. But, it's work too and takes time to manage. Let me know if you know of an excellent swag store or agency. I haven't researched it because I haven't had the time.

An interesting fact about DevOps'ish: it isn't a marketing tool or a tool used to sell something (outside of native ads in the newsletter itself). It's used to inform people. This puts it in a weird position for marketing to folks. I've done Twitter Ads in the past with some success. I'm currently testing Google Ads (as gross as that sounds). Buying subscribers is a loss leader, but the native Google Ads experience brings people to the site. But, this relatively high price for a subscriber is not lost on me. But, these are small, manageable ad runs once or twice a year. I need to figure out the best way to put money back into the newsletter to keep it growing still.

### DevOps'ish in 2022

It's wild thinking about it now. But, going into 2022, I want to make sure this newsletter is something I want to focus on. Is it still worth the time?

I read a lot (and I always will) but, I'm not necessarily reading what I want to (I used to read books). I'm burning down an unread count in Inoreader (which they are making easier to do). One thing I can do in 2022 is start to read less of the mainstream tech news sites (The Register, Wired, etc.) and more of the incredible work y'all are putting on your blogs. This would cut down on the amount of reading significantly. I'm at a point now where if a story is big enough, it will bubble up naturally for me on social media or in Inoreader. The log4j vulnerability this week is a perfect example. I was slammed all day Friday. But, when I opened the news, I got up to speed on it real quick.

One thing is for sure. Life needs to become a little more bearable in the next few weeks for a successful 2022.

## People

[The new American dream: getting paid to do nothing?](https://www.theverge.com/c/22820291/tech-jobs-outsourcing-infosys-bench-paid-to-do-nothing?scrolla=5eb6d68b7fedc32c19ef33b4)  
This is when you work two jobs to keep your skills fresh for the other job you might get called up to do. But, eek, Infosys. How is this profitable?

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Better.com has mass layoffs on Zoom before holidays](https://www.sfgate.com/tech/article/Better-mortgage-firm-has-mass-layoff-Zoom-16673576.php)  
Then Better.com CEO's is taking some time off as its board does a leadership assessment (aka they're firing this guy eventually).

[Wichita Sisters Become First Black Women In Kansas To Raise $1M For Tech Startup](https://peopleofcolorintech.com/break-into-tech/wichita-sisters-become-first-black-women-in-kansas-to-raise-1m-for-tech-startup/)  
"Angela Muhwezi-Hall and Deborah Gladney's dating app style platform matching job seekers with employers have raised $1.41 million."

[Software development pushes us to get better as people](https://jessitron.com/2021/11/28/software-development-pushes-us-to-get-better-as-people/)  
"There is an alignment between writing really good software and being good people together."

[What to Know About Equity Compensation](https://future.a16z.com/equity-compensation-in-tech/)  
"A decade ago, equity compensation — paying employees with company stock — was a perk reserved solely for executives. The practice was largely deployed by companies as a way to optimize retention while keeping their balance sheets clean. Since then, equity compensation has expanded quickly. Within the next 10 years, it's estimated that public companies will compensate employees with nearly $800 billion in Restricted Stock Units (RSUs), stock promised to employees upon meeting certain conditions." If you're not used to playing ball with stock, you should read this piece.

[Announcing the Kubernetes Contributor Celebration 2021](https://www.kubernetes.dev/blog/2021/12/07/announcing-the-kubernetes-contributor-celebration-2021/)  
"Like last year, this year also we are back with Kubernetes Contributor Celebration, the annual end of the year celebration, to recognize our achievements and have some fun! It's a time for us to relax, chat and do something fun with your fellow contributors!"

## Process

[Apache Log4j2 Security Bulletin (CVE-2021-44228)](https://aws.amazon.com/security/security-bulletins/AWS-2021-005/)  
This is oh so very bad and very deserving of the name Log4Shell. A log4j 0-day with POC in the wild. Who doesn't use log4j is probably a better question to ask. Seriously folks, leave no stone unturned on this one.

[Pulumi: Infrastructure as Code](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)  
Developing on the cloud is complex. What if you could use your existing programming knowledge to build, deploy, and manage cloud infrastructure using your favorite languages and tools? Pulumi is a cloud engineering platform that lets you write infrastructure as code in any programming language and on any cloud platform. Get started for free at pulumi.com *SPONSORED*

[GitOps: An implementation of DevOps](https://chrisshort.net/gitops-an-implementation-of-devops/)  
"GitOps is a prescriptive way of implementing DevOps. You will not succeed in using GitOps if you haven't embraced some DevOps philosophies along the way."

[Howie: The Post-Incident Guide](https://www.jeli.io/howie-the-post-incident-guide/)  
"Recent events have shown how critical digital services are to individuals, organizations and society as a whole. Now more than ever, learning from incidents is crucial to helping maintain service reliability requirements so companies can continue delivering on their commitments to clients and keep employees connected and productive"

[SolarWinds hackers have a whole bag of new tricks for mass compromise attacks](https://arstechnica.com/information-technology/2021/12/solarwinds-hackers-have-a-whole-bag-of-new-tricks-for-mass-compromise-attacks/)
"The Kremlin-backed hacking outfit's toolbox seems to grow by the month."

[Software Firm HashiCorp Tops IPO Goal to Raise $1.2 Billion](https://www.bloomberg.com/news/articles/2021-12-09/hashicorp-is-said-to-price-ipo-above-range-at-80-a-share)  
"HashiCorp Inc. raised $1.2 billion in an initial public offering, exceeding its goal for the share sale and adding to a record-setting year for software companies."

## Tools

[Kubernetes 1.23: The Next Frontier](https://kubernetes.io/blog/2021/12/07/kubernetes-1-23-release-announcement/)  
"This release consists of 47 enhancements: 11 enhancements have graduated to stable, 17 enhancements are moving to beta, and 19 enhancements are entering alpha. Also, 1 feature has been deprecated."

This week—Get started with observability at [Honeycomb Developer Week](https://www.honeycomb.io/developer-week-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish) (Dec 13-15). With FREE snackable sessions spread across two short days, you'll learn how to quickly debug your production services. With distributed tracing, OpenTelemetry, and [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) you can figure out exactly why performance is slow and who it's slow for. Up-level your skills. Win prizes along the way! *SPONSORED*

[Pod Security Graduates to Beta](https://kubernetes.io/blog/2021/12/09/pod-security-admission-beta/)  
"With the release of Kubernetes v1.23, Pod Security admission has now entered beta. Pod Security is a built-in admission controller that evaluates pod specifications against a predefined set of Pod Security Standards and determines whether to admit or deny the pod from running. Pod Security is the successor to PodSecurityPolicy which was deprecated in the v1.21 release, and will be removed in Kubernetes v1.25."

[Kubernetes 1.23: Dual-stack IPv4/IPv6 Networking Reaches GA](https://kubernetes.io/blog/2021/12/08/dual-stack-networking-ga/)  
""When will Kubernetes have IPv6?" This question has been asked with increasing frequency ever since alpha support for IPv6 was first added in k8s v1.9. While Kubernetes has supported IPv6-only clusters since v1.18, migration from IPv4 to IPv6 was not yet possible at that point. At long last, [dual-stack IPv4/IPv6 networking](https://github.com/kubernetes/enhancements/tree/master/keps/sig-network/563-dual-stack/) has reached general availability (GA) in Kubernetes v1.23."

[Kubernetes Version 1.23: What's New for Security?](https://blog.aquasec.com/kubernetes-version-1.23-security-features)  
Ephemeral containers, Windows HostProcess containers, and the aforementioned Pod Security.

[Leaving MySQL](https://blog.sesse.net/blog/tech/2021-12-05-16-41_leaving_mysql.html)  
While highlighting how MySQL has not aged well, Steinar H. Gunderson writes, "if you're using MySQL and it works for you, sure, go ahead. But perhaps consider taking a look at the other side of that fence at some point, past the 'OMG vacuum' memes."

[The vice president should not be using Bluetooth headphones](https://www.theverge.com/2021/12/7/22822431/kamala-harris-bluetooth-security-hacking-headphones)  
The US Vice President was criticized by one news outlet for having a "phobia" of Bluetooth devices. I know, it's the [most ridiculous story of the week](https://charlotteclymer.substack.com/p/the-media-coverage-of-kamala-harris), by far. I would be allergic to Bluetooth too if I had even a smidgen of national security responsibilities.

[Branchless Git](https://benjamincongdon.me/blog/2021/12/07/Branchless-Git/)  
Using git like this would definitely take some getting used to. But, I wonder what pains you completely avoid by using git in this manner.

[charmbracelet/soft-serve](https://github.com/charmbracelet/soft-serve)  
A tasty, self-hostable Git server for the command line🍦

[antonmedv/llama](https://github.com/antonmedv/llama)  
Terminal file manager

[danielmiessler/SecLists](https://github.com/danielmiessler/SecLists)  
SecLists is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more.

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/247/notes/) to see what didn't make it to the newsletter but are still worth your time.
