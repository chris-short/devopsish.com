+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-09-19T07:00:00Z
description = ["Data scientists shouldn't need to know Kubernetes, Pay Transparency, ever popular PHP, Crossplane, Flux, Kubernetes Network Policies, kube-vip, and more"]
draft = false
slug = "235"
tags = ["Kubernetes", "cloud", "cloud native", "DevOps", "Microsoft", "chaos", "network policies", "access controls", "site reliability engineer", "SRE", "PHP", "filesystem", "Facebook", "CNCF", "GitOps", "open source", "programming", "deployments", "Crossplace", "Flux", "Linux", "NTFS", "Flash", "Apple"]
title = "DevOps'ish 235: Data scientists shouldn't need to know Kubernetes, Pay Transparency, ever popular PHP, Crossplane, Flux, Kubernetes Network Policies, kube-vip, and more"

+++

## People

[Why data scientists shouldn't need to know Kubernetes](https://huyenchip.com/2021/09/13/data-science-infrastructure.html)  
I 100% agree with this. At most, a data scientist should be able to make a working Dockerfile that needs hardening and careful inspection.

[Facebook aware of Instagram's harmful effect on teenage girls, leak reveals](https://www.theguardian.com/technology/2021/sep/14/facebook-aware-instagram-harmful-effect-teenage-girls-leak-reveals)  
Facebook isn't a good company rarely that acts in the best interests of its users. They have a market cap over $1 trillion and their stock is still soaring to new heights. We should be actively encouraging people to delete Facebook affiliated tools from their lives.

[Management platform for Infrastructure as Code Automation and Collaboration](https://app.env0.com/login?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform, Terragrunt and GitOps workflows. Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and quality of life features. Free Demo *SPONSORED*

[Pay Transparency Is Coming, and Employers Are Terrified](https://www.businessinsider.com/pay-transparency-salary-range-disclosure-laws-colorado-employers-terrified)  
A great reckoning is coming. Us knowing each others' salaries is a good thing.

[Some of the most iconic 9/11 news coverage is lost. Blame Adobe Flash](https://www.cnn.com/2021/09/10/tech/digital-news-coverage-9-11/index.html)  
Flash strikes history.

[Anonymous leaks gigabytes of data from alt-right web host Epik](https://arstechnica.com/information-technology/2021/09/anonymous-leaks-gigabytes-of-data-from-epik-web-host-of-gab-and-parler/)  
Play stupid games, win stupid prizes.

## Process

[UN Breach Highlights Escalation of Cyber Threats](https://www.cybereason.com/blog/un-breach-highlights-escalation-of-cyber-threats)  
"Hackers have been inside the United Nations network for months. According to a report from Bloomberg, stolen credentials of a UN employee were sold on the Dark Web for as little as $1,000. The report claims that Russian-speaking cybercriminals sold access to the UN systems for months—from April through August of 2021."

[Creating Chaos to Achieve Reliability](https://rootly.io/blog/creating-chaos-to-achieve-reliability?utm_source=devopsish&utm_medium=newsletter&utm_campaign=235&utm_id=rootly&utm_content=sre)  
How can creating chaos achieve better reliability? Chaos and reliability might seem mutually exclusive, but through the use of Chaos Engineering, SREs can bring about meaningful changes to system resiliency. *SPONSORED*

[PHP maintains an enormous lead in server-side programming languages](https://arstechnica.com/gadgets/2021/09/php-maintains-an-enormous-lead-in-server-side-programming-languages/)  
Wordpress is a great example of a PHP-based CMS. Drupal is another example. PHP is a great language for server-side programming and is widely used still.

[The passwordless future is here for your Microsoft account](https://www.microsoft.com/security/blog/2021/09/15/the-passwordless-future-is-here-for-your-microsoft-account/)  
You have to download the Microsoft Authenticator app.

[Tech industry braces for skyrocketing rare earth prices](https://asia.nikkei.com/Business/Technology/Tech-industry-braces-for-skyrocketing-rare-earth-prices)  
If you don't know much about rare earths, I suggest you spend some time investigating the market.

## Tools

[CVE-2021-25741: Symlink Exchange Can Allow Host Filesystem Access · Issue #104980 · kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/issues/104980)  
"A security issue was discovered in Kubernetes where a user may be able to create a container with subpath volume mounts to access files & directories outside of the volume, including on the host filesystem. This issue has been rated **High** (CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H), and assigned CVE-2021-25741."

Learn about leveraging the [right type of AWS IAM policy mechanisms](https://goteleport.com/blog/aws-iam-in-laymans-terms/?utm_campaign=eg&utm_medium=partner&utm_source=DevOpsish) to build the responsibility separation between the “central” team and the individual "development" team. *SPONSORED*

[Crossplane is now a CNCF Incubating project](https://blog.crossplane.io/crossplane-cncf-incubation/)  
Congrats to the Crossplane team!

[CNCF Promotes GitOps Tool Flux to Incubated Status](https://www.infoq.com/news/2021/04/cncf-gitops-flux/)
Congrats to the Flux team!

[Results of Kubernetes Adoption Survey Show it's Everywhere](https://cloud.redhat.com/blog/results-of-kubernetes-adoption-survey-show-its-everywhere)  
"94% of survey participants are using Kubernetes in production." I don't think it's that high industry wide but, that's still a lot of K8s.

[StackRox Office Hours (E3): Kubernetes Network Policies](https://www.youtube.com/watch?v=-ry8lB3CWHA)  
"An important step in securing Kubernetes is reducing the attack surface by enabling network policies. But it's easy to make mistakes in building those YAML files." This was a fun episode.

[Linux 5.15 Delivers Many Features With New NTFS Driver, In-Kernel SMB3 Server, New Hardware](https://www.phoronix.com/scan.php?page=article&item=linux-515-features&num=1)  
What a time to be alive. An in-kernel SMB3 server AND an NTFS driver. 1998 me is blown away.

[WTF? Microsoft makes fixing deadly OMIGOD flaws on Azure your job](https://www.theregister.com/2021/09/17/microsoft_manual_omigod_fixes/)  
"Customers must update vulnerable extensions for their Cloud and On-Premises deployments as the updates become available per schedule outlined in table below." Microsoft should be smarter than this.

[Certs Magic with Walid Shaari](https://www.youtube.com/watch?v=32CtP3czd0E)  

[kube-vip/kube-vip](https://github.com/kube-vip/kube-vip)  
"Kubernetes Control Plane Virtual IP and Load-Balancer"

[roshan8/slo-tracker](https://github.com/roshan8/slo-tracker)  
"A tool to track SLA, SLO and Error budgets"

## DevOps'ish Tweet of the Week

[![🌈 Andrew Bennett ☄️ (@TheRealBnut) on Twitter: "It is decided. Instead of internal wikis/confluence/etc, big business will now hire bards who wander from team to team to teach the lore."](https://shortcdn.com/devopsish/235-devopsish-tweet-of-the-week.png)](https://twitter.com/TheRealBnut/status/1437655865570430984)

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/235/notes.md) to see what didn't make it to the newsletter but are still worth your time.
