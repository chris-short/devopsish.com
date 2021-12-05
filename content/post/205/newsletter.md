+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-02-14T07:00:00Z
description = "Kubernetes Pod Security Policy Deprecation, open source skills are crucial, harms of large language models, Supermicro, water plant breach, VSCode repo FUD, and more"
draft = false
slug = "205"
tags = ["Kubernetes", "K8s", "open source", "security", "hiring", "DevOps", "PSPs", "Pod Security Policy", "deprecation", "cloud native", "Microsoft", "developers", "research", "news", "IBM", "Rust", "learn", "process", "SSH tunnels", "code", "managers", "employees", "chronic illness", "Cloud Native Computing Foundation", "water supply", "Cloudflare", "LaunchDarkly", "OPA", "CSI", "healthcare", "contributors", "vulnerabilities", "marketing", "Google", "Nvidia", "Arm", "CKS", "Apple", "sudo", "VSCodium", "Mercurial", "GCP", "Python", "GPT-3", "VSCode"]
title = "DevOps'ish 205: Kubernetes Pod Security Policy Deprecation, open source skills are crucial, harms of large language models, Supermicro, water plant breach, VSCode repo FUD, and more"

+++

First off, Happy Valentine's Day. I hope you're enjoying it as best you can.

This week I learned that an organization in the healthcare industry is working on a large project involving Kubernetes [Pod Security Policies](https://kubernetes.io/docs/concepts/policy/pod-security-policy/) as a mainstay in their project. In case you haven't heard, Pod Security Policies (PSPs) will begin the [Kubernetes deprecation process](https://kubernetes.io/docs/reference/using-api/deprecation-policy/) in the 1.21 release. Kubernetes 1.21 releases on or about Thursday, April 8th, 2021. With PSPs being completely phased out by the 1.25 release (sometime in mid'ish 2022). When 1.21 is released, you'll see a message similar to the following when touching PSPs, "The PodSecurityPolicy API is deprecated in 1.21, and will no longer be served starting in 1.25." The [Kubernetes Contributor Marketing Team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) is working on an official blog post, but it is taking longer than I'd prefer given the amount of PSP utilization that's out there.

I'm writing this here because I have worked in large banks, healthcare systems, and government agencies where changes like this could take quite some time to plan, test, verify, and implement. But, what is replacing PSPs? Well, that's to be determined, which is equally terrifying to some. But, this is where folks have to have faith in the process. Sometimes we have to plan deprecation of something to force the community to respond to fill the gap.

Right now, from my seat, a viable replacement is [Open Policy Agent's Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/). Open Policy Agent (OPA) has recently moved to a [graduated CNCF Project](https://www.cncf.io/announcements/2021/02/04/cloud-native-computing-foundation-announces-open-policy-agent-graduation/). OPA is ready for production implementation. At this time, again, in my opinion, [OPA](https://www.openpolicyagent.org/) will be the de facto replacement for PSPs in the future. But, I will admit, the future is hard to predict at this level. There very well be many more viable alternatives in six to twelve months.

Other projects and products can help manage and enforce what pod requirements are for Kubernetes clusters. I will not be touching on those because, to be honest, [there are a lot of potential solutions](https://landscape.cncf.io/card-mode?category=security-compliance&grouping=category) in the CNCF Landscape. One of those alternatives has rubbed me wrong during the writing process of the PSP deprecation blog post. It's not their place to force us to provide a complete picture of the ecosystem in a singular blog post. We're trying to stay scoped to inform the masses of a deprecation. In the wake of the [dockershim deprecation](https://devopsish.com/195/), this is already hard enough. The Upstream Marketing team has a [charter](https://github.com/kubernetes/community/blob/master/communication/marketing-team/CHARTER.md). We wrote the [Ethos/Vision part of the subproject's charter](https://github.com/kubernetes/community/blob/master/communication/marketing-team/CHARTER.md#ethosvision) to prevent such behavior. State your case, don't try to force others to state it on your behalf.

Regardless, Kubernetes Pod Security Policies are going away and folks need to prepare for that. Start assessing what is using PSPs in your environment, what requirements it's implementing, and find a solution that can replicate that functionality.

## People

{{< tweet 1360276547018625028 >}}

[Ephemeral Environments as a Service 🤯](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102)  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team’s ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. Your developers will never have to fight over staging environments again. [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102). *SPONSORED*

[Research: How Companies Committed to Diverse Hiring Still Fail](https://hbr.org/2021/02/research-how-companies-committed-to-diverse-hiring-still-fail)  
"Even if your company is committed to diversity inclusion, you might have hidden biases in your hiring strategies. According to recent research on the hiring practices at several prestigious firms, this can take several forms. For example, you might view unpaid internships more favorably than other types of summer jobs, which introduces socioeconomic bias. And you might think that minority and female candidates are less likely to accept a job if offered because so many other firms are also interested in hiring them (something, incidentally, the research doesn’t bear out); because of this, you might be less likely to pursue those candidates. So, if you’re truly committed to diversifying your organization, take a hard look at your hiring processes and face up the fact that they might not be as effective in practice as they are in intention."

[How Managers Can Support Employees with Chronic Illnesses](https://hbr.org/2021/02/how-managers-can-support-employees-with-chronic-illnesses)  
"Chronic illness is extremely common, and the Covid-19 pandemic has helped normalize talking about it in the workplace. It can be hard to know what to say to an employee with a chronic illness — it’s an emotional topic, and your own assumptions can get in the way of real understanding. There are three steps managers can take to ensure they approach these conversations with empathy and confidence. First, take your own emotions out of it. Second, challenge your views about what counts as great work. Third, approach with curiosity and do your research. The experiences of employees experiencing chronic illness can offer valuable lessons to all employees."

[Open source expertise is now key to getting hired, says IBM](https://www.businessinsider.com/open-source-ibm-software-developers-programming-2021-2)  
"A survey of 3,440 technologists commissioned by IBM suggests open source skills are in high demand. 87% of hiring managers say these skills are an important factor when hiring, per the survey. IBM's chief developer advocate says dedicated open source developers help shape the future of tech." Side note: I'm really, really proud of you Kylie.

[OpenAI and Stanford researchers call for urgent action to address harms of large language models like GPT-3](https://venturebeat.com/2021/02/09/openai-and-stanford-researchers-call-for-urgent-action-to-address-harms-of-large-language-models-like-gpt-3/)  
"Participants suggested that developers may only have a six- to nine-month advantage until others can reproduce their results. It was widely agreed upon that those on the cutting edge should use their position on the frontier to responsibly set norms in the emerging field,” the paper reads. “This further suggests the urgency of using the current time window, during which few actors possess very large language models, to develop appropriate norms and principles for others to follow." Just don't fuck it up.

## Process

[Rust Foundation - Hello World!](https://foundation.rust-lang.org/posts/2021-02-08-hello-world/)  
Welcome to the world Rust Foundation!

[10 Docker Security Best Practices](https://snyk.io/blog/10-docker-image-security-best-practices/)  
The top 10 most popular images have more than 30 known vulnerabilities. Learn best practices for choosing a secure base image and fixing container vulnerabilities. Check out the blog: <https://snyk.io/blog/10-docker-image-security-best-practices/> *SPONSORED*

[Supermicro Hack: How China Exploited a U.S. Tech Supplier Over Years](https://www.bloomberg.com/features/2021-supermicro/)  
"For years, U.S. investigators found tampering in products made by Super Micro Computer Inc. The company says it was never told. Neither was the public." Holy shit this is intense.

[Breached water plant employees used the same TeamViewer password and no firewall](https://arstechnica.com/information-technology/2021/02/breached-water-plant-employees-used-the-same-teamviewer-password-and-no-firewall/)  
Someone tried to poison a water supply in Oldsmar, Florida (near my old Tampa stomping grounds). This seems targeted but, the target was also super soft. Luckily an employee watched the whole event occur and set the settings back to normal tolerance.

[Microsoft, Google, and Qualcomm are reportedly nervous about Nvidia acquiring Arm](https://www.theverge.com/2021/2/12/22280262/qualcomm-microsoft-google-nvidia-arm-acquisition-investigations-concerns)  
I hate to say it, but that's probably a good thing. But, the Nvidia-ARM deal has some big hurdles ahead of it.

[Let's Learn CKS Scenarios](https://gumroad.com/l/cksbook)  
"This Book Covers various Scenarios/practice questions related to Kubernetes CKS Certification."

[About the security content of macOS Big Sur 11.2.1, macOS Catalina 10.15.7 Supplemental Update, and macOS Mojave 10.14.6 Security Update 2021-002 - Apple Support](https://support.apple.com/en-us/HT212177)  
Apple's sudo is now patched for CVE-2021-3156.

[Why you should never use Cloudflare Free Plan : devopsish](https://www.reddit.com/r/devopsish/comments/lfhbt6/why_you_should_never_use_cloudflare_free_plan/)  
*record scratch* Cloudflare employee comes out of nowhere and responds to a bad story about Cloudflare in [/r/devopsish](https://www.reddit.com/r/devopsish/). Okay...

## Tools

[Raspberry Pi OS added a Microsoft repo. No, it’s not an evil secret](https://arstechnica.com/gadgets/2021/02/raspberry-pi-os-added-a-microsoft-repo-no-its-not-an-evil-secret/)  
The fact a distro makes it easier to install a Microsoft product shows folks a lot. It also shows us who hasn't been paying attention. I mean, I did switch to [VSCodium](https://vscodium.com/) this week... But, the two events are not related. I still want the VSCode experience.

**LaunchDarkly** is a feature management platform that empowers all teams to safely deliver and control software through feature flags. By separating code deployments from feature releases, LaunchDarkly enables you to deploy faster, reduce risk, and iterate continuously. Microsoft, IBM, Atlassian, and 1500+ organizations use LaunchDarkly to build, operate, and learn from their software. [Learn more](https://launchdarkly.com/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) and start your free trial today! *SPONSORED*

[Mercurial Revision Control System Continues Rust'ing For Better Performance](https://www.phoronix.com/scan.php?page=news_item&px=Mercurial-More-Rust-2021)  
"Mercurial's '[Oxidation Plan](https://www.mercurial-scm.org/wiki/OxidationPlan)' ultimately calls for the main command (hg) to become a Rust binary that embeds and uses a Python interpreter when needed while Mercurial's Python code will call into Rust code." Mercurial is lightyears friendlier than git and should be the predominant version control tool. There I said it.

[Deep PostgreSQL Thoughts: The Linux Assassin](https://info.crunchydata.com/blog/deep-postgresql-thoughts-the-linux-assassin)  
OOM Killer and databases go together like water and electricity.

[kubernetes-sigs/secrets-store-csi-driver: Secrets Store CSI driver for Kubernetes secrets - Integrates secrets stores with Kubernetes via a CSI volume.](https://github.com/kubernetes-sigs/secrets-store-csi-driver)  
Look! New shiny with Vault, Azure, and GCP providers.

[Visual guide to SSH tunnels](https://robotmoon.com/ssh-tunnels/)  
"This page explains use cases and examples of SSH tunnels while visually presenting the traffic flows. For example, here's a reverse tunnel that allows only users from IP address 1.2.3.4 access to port 80 on the SSH client through an SSH server."

[VSCodium - Open Source Binaries of VSCode](https://vscodium.com/)  
"Free/Libre Open Source Software Binaries of VSCode" You do lose some common extensions because the repositories are different. But, I feel cleaner using this version.

[Backblaze Hard Drive Stats for 2020](https://www.backblaze.com/blog/backblaze-hard-drive-stats-for-2020/)  
If you need to add some metrics to your next big hard drive buy, this is a good start.

[Twitter Mulls Subscription Product, Tipping For Generating Revenue](https://www.bloomberg.com/news/articles/2021-02-08/twitter-considers-subscription-fee-for-tweetdeck-unique-content)  
I am not sure how much I'd pay for TweetDeck in its current form. It is lacking a number of features the mobile apps have. If Twitter does this they need to price this very low at first and as feature parity is achieved, increase pricing along the way.

## DevOps'ish Tweet of the Week

[![Tech folx: don't install random software from the internet! Also tech folx: ooooh, let's curl this installation script! — julia ferraioli (@juliaferraioli) February 9, 2021](/images/205-devopsish-tweet-of-the-week.png)](https://twitter.com/juliaferraioli/status/1359280041624915968)

Please comment on this issue of DevOps'ish on [/r/devopsish](https://www.reddit.com/r/devopsish/comments/ljfra9/comments_from_devopsish_205_kubernetes_pod/).

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/205/notes/) to see what didn't make it to the newsletter but are still worth your time.
