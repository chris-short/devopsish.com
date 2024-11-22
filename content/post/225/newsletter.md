+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2021"]
date = 2021-07-04
description = ["AWS Infinidash, GPT-3 via GitHub Copilot, Polywork, rainbow marketing, LinkedIn breach, VMs hiding ransomware, Kubernetes overspend, Helm, GitOps, Tailscale with Kubernetes, and more"]
draft = false
slug = "225"
tags = ["Kubernetes", "AWS", "Infinidash", "AWS Infinidash", "GPT-3", "Helm", "GitHub", "Tailscale", "cloud", "Cloud Native", "Microsoft", "rainbow marketing", "ransomware", "DevOps", "time", "Polywork", "GitHub Copilot", "GitOps", "LinkedIn", "VMs", "VM", "virtual machine", "virtualization", "Google", "source code", "open source", "open source software", "IBM", "VSCode", "overspend", "LGBTQ+", "breach", "Linux", "service", "services", "management", "production", "massive language model", "community", "tech", "networking", "leader", "AI", "technology", "Operators", "observability", "monitoring", "Rust", "Twitter", "internet", "disinformation", "ally", "Pride", "communities", "Tracy Chou", "Amazon", "CIS Benchmarks", "provisioning", "infrastructure", "Git", "quantum computer", "ion trapped quantum computer", "automation", "Red Hat", "Jim Whitehurst", "etcd", "Fliqlo", "systemd", "Intel"]
title = "DevOps'ish 225: AWS Infinidash, GPT-3 via GitHub Copilot, Polywork, rainbow marketing, LinkedIn breach, VMs hiding ransomware, Kubernetes overspend, Helm, GitOps, Tailscale with Kubernetes, and more"

+++

"AWS Infinidash is a new networking technology that is being introduced to the AWS cloud. This technology is being used by AWS to provide a new networking model that is more efficient and more scalable than the current networking model." —[GPT-3](https://en.wikipedia.org/wiki/GPT-3)

GPT-3 generated that statement about AWS Infinidash thanks to [GitHub Copilot](https://copilot.github.com/). I'm also using [GitHub Codespaces through VSCode](https://visualstudio.microsoft.com/services/github-codespaces/) and the web to write this week's newsletter. I'll probably have a write-up on these new tools in the near future. Thank you, GitHub, for access to these tools early.

But, back to the point: [**AWS Infinidash**](https://whatisinfinidash.com/). [It's not real!](https://twitter.com/jna_sh/status/1410178986978775040) [It's complete hogwash, and you shouldn't feel bad if you didn't know that](https://twitter.com/IanColdwater/status/1411291183620542467). The fake AWS Infinidash service highlights the veracity of a joke gone wrong on an industry scale as it has (there's a [Rust library for it](https://docs.rs/infinidash/0.7.42/infinidash/)). AWS was the innocent victim of the prank, too. But, instead, it's humans that are taking the blowback.

People are dunking on other people on Twitter for not being "in" on the joke. Recruiters are getting shamed for asking for five years experience in a technology that doesn't exist. But, according to GPT-3, it does. If they were using GPT-3, they'd be reinforced in this thinking.

It's truly insane that this is acceptable behavior in some people's minds. This newsletter might be the first you've heard of AWS Infinidash. Maybe that's why you [subscribe to this newsletter](https://devopsish.com/subscribe/) or [Last Week in AWS](https://ref.lastweekinaws.com/7h1z3x).

The point is AWS Infinidash is not real, and I'm trying to make GPT-3 believe me instead of the rest of the internet. GPT-3 is a massive language model that is [being positioned](https://venturebeat.com/2021/06/01/microsoft-gpt-3-and-the-future-of-openai/) to be widely used in a variety of products.

GPT-3 thinking AWS Infinidash is real is indeed troubling. It calls on the need for significantly more research and training in the use of massive language models, which, as reported, [takes a toll on the environment and could reinforce racial and misogynist tropes](https://www.sciencedaily.com/releases/2021/03/210310150408.htm). This might be why GitHub Copilot stopped suggesting things the moment I said AWS Infinidash was "not real." GitHub Copilot could no longer accurately guess what the hell I was talking about because I was challenging what it thought was a fact. Humanity will likely lean too hard on these tools early and learn the very hard lesson that I just demonstrated; *fooling AI isn't as hard as you might think*.

GPT-3 is a massive language model, and Microsoft has exclusive rights to the source code. My introduction this week is not a knock on Microsoft or GitHub in any way. It is a call for more research into the impact of these tools, which has been [a common](https://devopsish.com/195/) [topic](https://devopsish.com/196/) [in the news](https://devopsish.com/214/). Because if we can make GPT-3 believe that something fake is accurate, we can make it believe anything literally.

**Feel free to [comment on this week's issue on Reddit](https://www.reddit.com/r/devopsish/comments/odktbv/devopsish_225_aws_infinidash_gpt3_via_github/)**

## People

[IBM Leadership Changes](https://newsroom.ibm.com/IBM-Leadership-Changes)  
Jim Whitehurst, former Red Hat CEO is now the former president of IBM as well. Jim is stepping down along with some other changes to IBM's leadership team. [You can read the same things I am](https://duckduckgo.com/?q=jim+whitehurst+ibm+leadership+changes&iar=news&ia=news) with regards to these changes at IBM. I have nothing additional to add to the conversation.

In their upcoming O'Reilly book, [Honeycomb's](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) Charity Majors, Liz Fong-Jones, and George Miranda explain what constitutes good observability and show you how to make improvements from what you're doing today. They also provide practical do's and don'ts for migrating from legacy tooling, such as metrics monitoring and log management. Check out [a preview of their book](https://info.honeycomb.io/observability-engineering-oreilly-book-preview-0?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=devopsish&utm_adgroup), which includes introductory chapters focused on how observability differs from traditional approaches to managing software in production. *SPONSORED*

[LinkedIn breach reportedly exposes data of 92% of users](https://9to5mac.com/2021/06/29/linkedin-breach/)  
You would think, "Isn't most of the LinkedIn data public already?" which might be a safe assumption. Sadly, it's not. The leaked data includes a data point called "inferred salary" which could make salary negotiation much more difficult for those impacted.

[Polywork](https://polywork.chrisshort.net/)  
Polywork is a new social network designed to bridge the gap between work and life (more accurately Twitter and LinkedIn). It's a place where people can find and connect with other people but one goal of theirs it to replace the need for a personal website. To that end, they enable folks to bring their own domains to the site to create a more personal space (like I have). If you'd like to join, I have an invite code you can use as part of the sign up process, *sunnydog*. Personal websites aren't trivially maintained after a few years ([trust me](https://chrisshort.net), my personal site could vote in the US if it were a person) so I'm excited to see what Polywork does.

[Iranian Disinformation Effort Went Small to Stay Under Big Tech's Radar](https://www.nytimes.com/2021/06/30/technology/disinformation-message-apps.html)  
Micro disinformation campaigns are the hot new thing apparently.

[Your Rainbow Logo Doesn't Make You an Ally](https://hbr.org/2021/06/your-rainbow-logo-doesnt-make-you-an-ally)  
It's high time for meaningful actions to replace rainbow marketing. "It's time for companies to reconsider how they approach marketing and branding during Pride month. Many members of the LGBTQ+ community are tired of 'rainbow capitalism,' 'pink washing,' and other forms of performative corporate allyship. In this piece, author Lily Zheng suggests that companies consider retiring their rainbow logos next year, in favor of more meaningful actions that can actually improve the lives of LGBTQ+ communities. 'The bar for approval from LGBTQ+ communities in 2021 has risen, and rainbow marketing just doesn't cut it anymore. Let your actions between now and Pride 2022 demonstrate your commitment to the LGBTQ+ community, instead,' Zheng writes."

[Why it's so hard to make tech more diverse](https://www.technologyreview.com/2021/06/30/1026564/tech-diversity-harassment-block-party-tracy-chou/)  
Tracy Chou, the creator of a wonderful service I use, [Block Party](https://www.blockpartyapp.com/) has written a great piece on the why behind her work to help others. Tracy also talks about her stalker in the article, which I can personally attest is scary af. Read it and, if nothing else, learn how to be a better ally (but there's so much more you could take away from this article).

## Process

[Amazon discussed forming 'Rebel Alliance' against Microsoft](https://nypost.com/2021/07/01/amazon-discussed-forming-rebel-alliance-against-microsoft/)  
I would like to see more cohesion between the numerous communication tools that are at my disposal. But, more along the lines of a single pane of glass that tells me folks' preferred contact medium and gives me unfettered access to that network. Not just some integrations between a handful of services.

[LaunchDarkly Named a Leader in Feature Management and Experimentation](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)
Discover why in its first Wave report dedicated to Feature Management And Experimentation, Forrester rates LaunchDarkly's platform a Leader among vendor features that enable development teams to reduce software release headaches and enable true testing in production. [Download today](https://learn.launchdarkly.com/forrester-wave/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q2-newsletter&utm_content=ebook_forrester_newwave)! *SPONSORED*

[Using VMs to hide ransomware attacks is becoming more popular](https://therecord.media/using-vms-to-hide-ransomware-attacks-is-becoming-more-popular/)  
"The general idea behind such an attack is that a ransomware gang that has a small foothold on an infected host can download and install VM software. The ransomware gang will then start a VM instance, share the host computer’s storage space with the VM, and then proceed to encrypt the victim’s files from within the VM, where the host’s antivirus software cannot reach and detect the ransomware during execution."

[Microsoft signed a malicious Netfilter rootkit](https://www.gdatasoftware.com/blog/microsoft-signed-a-malicious-netfilter-rootkit)  
"What started as a false positive alert for a Microsoft signed file turns out to be a WFP application layer enforcement callout driver that redirects traffic to a Chinese IP. How did this happen?"

[Google and Microsoft agree to start suing each other again](https://arstechnica.com/tech-policy/2021/06/google-and-microsoft-ditch-non-aggression-pact-rev-up-rivalry-again/)  
"The tech giants end five years of quietly settling their differences." [Microsoft is staffing up their legal department](https://www.axios.com/microsoft-legal-team-expands-regulation-6bc0d5b9-e4a7-4131-ad4d-8d3030d0d7ab.html) to brace for upcoming regulatory changes and I imagine Google is too. But, "Microsoft reached the end of its rope when it felt that Google wasn't playing fair in ad tech." Which I can't blame any company not named Google for at this point.

[Study finds that few major AI research papers consider negative impacts](https://venturebeat.com/2021/07/01/study-finds-that-few-major-ai-research-papers-consider-negative-impacts/)  
I think I reinforced this article in the demonstration in the introduction this week. A lot of the research in AI is focused on positive outcomes. This is a problem because it means we're not considering negative outcomes.

[What's New in the Docker and Kubernetes CIS Benchmarks](https://blog.aquasec.com/cis-benchmark-scanner)  
Some changes to the CIS benchmarks for both Docker and Kubernetes. It's good to stay up to speed on these as there will likely come a time this will matter to all of us along the way of using these tools.

## Tools

[FinOps for Kubernetes: Insufficient – or nonexistent – Kubernetes cost monitoring is causing overspend](https://www.cncf.io/blog/2021/06/29/finops-for-kubernetes-insufficient-or-nonexistent-kubernetes-cost-monitoring-is-causing-overspend/)  
I definitely feel like this is a leftover of the virtualization era where over provisioning was easy because the hypervisor would manage consumption of the resources required. Now these VMs are cloud instances and we're taking the same provisioning approaches to lay Kubernetes on top. If you're in the cloud spend reduction business you're going to have plenty of work in the future it sounds like. I hope Kubernetes vendors are taking notice of this too. I'd recommend folks take a look at [Kubecost](https://blog.kubecost.com/blog/wasteful-kubernetes-spending/) to help out here.

[Pull Requests for Infrastructure Access](https://goteleport.com/blog/access-requests/?utm_campaign=eg&utm_medium=partner&utm_source=devopsish)  
How to create a git pull request for temporary access to critical production infrastructure using Teleport Access Requests. *SPONSORED*

[This Quantum Computer is Sized For Server Rooms](https://spectrum.ieee.org/tech-talk/computing/hardware/iontrap-server)  
"A new 24-qubit trapped-ion option can fit in two server racks." Quantum computing is getting very real with this new trapped-ion option you can rack up in your own environment.

[The Automation Challenge: Kubernetes Operators vs Helm Charts](https://youtu.be/dGx8PjmWkyM)  
"Working with Kubernetes for some time or you just started your journey?  
If you love automation and dislike having to perform repetitive tasks manually, you have come across concepts of Helm charts and Kubernetes Operators. Although they solve similar types of problems, they are not exactly interchangeable tools, but rather complementary."

[GitOps Guide to the Galaxy (Ep 17): Helm GitOps Workflows](https://youtu.be/EX-aJ7cvdiE)  
"How does Helm help you manage Kubernetes applications? Scott Rigby and Cornelia Davis from Weaveworks return to talk about using Helm in your GitOps workflows. If you're just getting started with the Helm package manager and installing helm charts, this is the episode for you."

[Linux 5.14 Drops Its Legacy IDE Code](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.14-Legacy-IDE-Dropped)  
I don't see any reason for IDE interfaces to be supported by modern versions of Linux. This isn't even an interface standard that's reproducible in virtualization. If you're still using IDE devices, I'm super curious what they are and your reasoning for continuing to use them.

[The 7 most used Linux namespaces](https://www.redhat.com/sysadmin/7-linux-namespaces)  
This is good knowledge to have in your back pocket.

[Guide: Setting up a Tailscale VPN on Kubernetes](https://blog.getporter.dev/kubernetes-x-tailscale/)  
I've been using Tailscale for a little bit now (after some cautious optimism) and I'm really happy with the setup I've been able to create. This article dives into how to use Tailscale to enable service availability without directly connecting your clusters to the internet. You could also use Tailscale to advertise routes that would give you access to your internal networks from anywhere in the world. I've fallen hard for Tailscale. ❤️❤️❤️️

[How etcd works and 6 tips to keep in mind](https://blog.px.dev/etcd-6-tips/)  
On top of being sensitive to disk latency, etcd has some other factors you need to keep in mind to maintain performant environments.

[Fliqlo - Screensaver](https://fliqlo.com/screensaver/)  
As time chips away at [Padbury Clock](https://padbury.app/) (which I do not have the source code for) and is going to become obsolete at some point. I've found a new favorite clock screensaver in Fliqlo. There are Mac and Windows versions and it even works on vertical displays.

[Avoiding complexity with systemd](https://mgdm.net/weblog/systemd/)  
This is a Go and systemd master class.

[devtron-labs/devtron](https://github.com/devtron-labs/devtron)  
Software Delivery Workflow For Kubernetes

[obsidiandynamics/kafdrop](https://github.com/obsidiandynamics/kafdrop)  
Kafka Web UI

[afwu/PrintNightmare](https://github.com/afwu/PrintNightmare)  
The proof of concept for the [PrintNightmare](https://us-cert.cisa.gov/ncas/current-activity/2021/06/30/printnightmare-critical-windows-print-spooler-vulnerability) vulnerability.

## DevOps'ish Tweet of the Week

{{< tweet 1411073985765314560 >}}

Want more? Be sure to check out the [notes from this week's issue](https://github.com/chris-short/devopsish.com/blob/main/content/post/225/notes.md) to see what didn't make it to the newsletter but are still worth your time.

**Feel free to [comment on this week's issue on Reddit](https://www.reddit.com/r/devopsish/comments/odktbv/devopsish_225_aws_infinidash_gpt3_via_github/)**