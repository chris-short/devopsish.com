+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2021"]
date = 2021-11-07T07:00:00Z
description = ["Automation transforms jobs, be directive without being a jerk, YAML strikes again, GitHub CEO change, Dell spins out VMware, Grace Hopper Explains the Nanosecond, Kubernetes tools galore, and more"]
draft = false
slug = "242"
tags = ["Kubernetes", "Red Hat", "cloud", "Cloud Native", "open source", "process", "DevOps", "automation", "people", "Microsoft", "software", "infrastructure", "contributor", "Knative", "Intel", "jobs", "GitHub CEO", "nginx", "Amazon", "directive", "IBM", "Pulumi", "GitHub", "Linux", "VMware", "networking", "architecture", "Ubuntu", "IoT", "ingress", "cluster", "GitHub Copilot", "YAML", "AWS", "programming", "Dell", "tracing", "developer", "Google", "terminal", "Apache", "ArgoCD", "CNCF", "wages", "GitOps"]
title = "DevOps'ish 242: Automation transforms jobs, be directive without being a jerk, YAML strikes again, GitHub CEO change, Dell spins out VMware, Grace Hopper Explains the Nanosecond, Kubernetes tools galore, and more"

+++

Note: The [Notes file this week](https://devopsish.com/242/notes/) is DEFINITELY worth looking at this week too.

[The people have spoken](https://twitter.com/ChrisShort/status/1454614581981106182). **DevOps'ish** won't be changing its name any time soon. I received a lot of great feedback; thank you for that. As I'm writing this, I can feel the effects of my COVID-19 booster kicking in. The joint pain is the tell for me. Max received his first shot today too. He and I will be pretty sore in the morning. Max is genuinely excited to get his vaccinations and get back to gallivanting across the globe. It's looking like we'll be heading to San Diego at some point in Q1 2022. Having just gotten back from Los Angeles, I can definitively say I'm comfortable taking the family back to California.

Meanwhile, onboarding at AWS is going well. Amazon has a rigorous onboarding process that will ultimately inform me more about the culture and how work happens. I know it sounds like I'm marveling at the process, but it's the most rigorous onboarding process I've been through in the private sector. It's awesome. I know where tools are that I would've had to learn through osmosis at other companies. I'm behind on all of it, and while that's fine (the point is to finish it over a longer time arc than I'm allowing). I'm getting through it, but there are just some things I won't fully grasp at first and will need to see in practice (this is a personality trait). I have to commit to adapting to the Process and Tools. I'm starting to see where I can fit in, too, so there will be some technical work starting soon. It's a good feeling because Friday, all I wanted to do was "be productive." Get some onboarding done and some upstream work done. That felt nice. Waking up to merged PRs on a Saturday morning will always feel good.

Remember to check out the Kubernetes contributor site, [**Kubernetes.dev**](https://kubernetes.dev/). It's full of helpful resources and blog posts about SIGs looking for folks to help them. I hear more and more that folks don't know about the contributor site, which makes me sad. We're putting a lot of effort into it. If you're a contributor or looking to be one, there's some helpful content there. The [Kubernetes Upstream Marketing team](https://github.com/kubernetes/community/tree/master/communication/marketing-team) is also working on additional SIG profiles and contributor stories (as well as making the site more discoverable).

## People

[Automation Doesn't Just Create or Destroy Jobs — It Transforms Them](https://hbr.org/2021/11/automation-doesnt-just-create-or-destroy-jobs-it-transforms-them)  
"Automation is everywhere these days. While economists often consider the effects of automation in terms of whether it creates or destroys jobs, less attention is paid to how it changes jobs and the wages paid to the workers that perform them. While there are cases where automation can create higher-paying jobs, more often it drives wages down. For companies considering automation, this can seem like a boon, as cost savings on labor can increase margins. But, there are also potential downsides, as companies may find themselves in trouble when automated systems falter. Firms should ask themselves three questions when deciding to automate: 1) What are the limits of the technology? 2) How do those limits impact the operation? 3) How does the cost of overseeing technology affect its value proposition?" I will say, most people reading this email need more automation so you can have a better life, in general.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[You can be directive without being a jerk](https://larahogan.me/blog/be-directive-without-being-a-jerk/)
From Lara Hogan, "Employing a directive model doesn't mean being a jerk or overly controlling. As you'll see, sometimes, being directive is the most empowering thing you can do for your team."

[13 Things Only Terrible People Say, According to Reddit](https://lifehacker.com/things-only-assholes-say-according-to-reddit-1847941599)  
This is one of those terrible slide-based articles from Lifehacker but, there are a ton of my red flag phrases in here so I thought it might be helpful to some of y'all. Remember, if someone has to tell you they're good or nice, they probably aren't (or at least aren't being good or nice in that moment).

[Red Hat to hire fewer senior engineers after budget frozen](https://www.theregister.com/2021/11/05/red_hat_jobs/)  
All those people that said, "Just wait, IBM will change Red Hat somehow." are cashing in this week. But, to be honest, I was a Principal at Red Hat and that was mainly to justify my pay level (and Red Hat is already on the low end of the pay scale for just about everything technical). Red Hat needs to assess how it compensates employees commensurate to their title in the greater job market to solve these problems. It'll be interesting to see how this pans out. I can talk about this more openly with an a former insider's perspective. I know one of the reasons I left Red Hat was due to it feeling like I had to fight to do my job (which was really the job of 3+ people). Retaining high caliber talent while burning them out is next to impossible with indicators like a hiring and budget freeze. I should point out, [Amazon and AWS have a lot of job openings](https://amazon.jobs/), if we worked together at Red Hat, the referral process is similar and I'd be happy to help.

[YAML strikes again](https://www.reddit.com/r/kubernetes/comments/qlb5xd/yaml_strikes_again/)  
I literally laughed out loud when I saw this.

## Process

[Bandwidth.com expects to lose up to $12M following DDoS extortion attempt](https://therecord.media/bandwidth-com-expects-to-lose-up-to-12m-following-ddos-extortion-attempt/)  
"In a document filed with the US Securities Excahnge Commission last week, Bandwidth said the attacks were large enough to put a dent in its Q3 revenue of $0.7 million, along with bigger losses expected by the end of the year." OUCH!!!

[Pulumi: Developer-First Infrastructure](https://www.pulumi.com/?utm_source=devopsish&utm_medium=sponsored-link&utm_campaign=iac)  
Developing on the cloud is complex. What if you could use your existing programming knowledge to build, deploy, and manage cloud infrastructure using your favorite languages and tools? Pulumi is a cloud engineering platform that lets you write infrastructure as code in any programming language and on any cloud platform. Get started for free at [pulumi.com](https://pulumi.com/) *SPONSORED*

[GitHub gets a new CEO](https://techcrunch.com/2021/11/03/github-gets-a-new-ceo/)  
"GitHub CEO [Nat Friedman](https://www.linkedin.com/in/natfriedman/) is stepping down from his role on November 15 to become the Chairman Emeritus of the Microsoft-owned service. [Thomas Dohmke](https://www.linkedin.com/in/thomas-dohmke-24855b10/), who only recently became GitHub's chief product officer, will step into the CEO role." It's Microsoft's GitHub now.

[Despite having just 5.8% sales, over 38% of bug reports come from the Linux community](https://www.reddit.com/r/gamedev/comments/qeqn3b/despite_having_just_58_sales_over_38_of_bug/)  
A case for distributing Linux versions of your software (in short, we file bugs that benefit your software).

[Dell spins off $64 billion VMware as it battles debt hangover](https://arstechnica.com/information-technology/2021/11/dell-spins-off-64-billion-vmware-as-it-battles-debt-hangover/)  
And the VMware swirling of assets for Wall Street is complete.

[NOBELIUM Demonstrates Why Microsoft Is the Weakest Link](https://www.cybereason.com/blog/nobelium-demonstrates-why-microsoft-is-the-weakest-link)  
Ouch. "There are two troubling takeaways from this. First, Microsoft took what was essentially a customer security advisory and framed it as threat research. The other takeaway--which is even more concerning--is that less than a year after the SolarWinds attacks, Microsoft apparently allowed the same threat actors to slip through again. Microsoft has become the gateway to execute these sophisticated cyber attacks."

[China encourages finance sector to use open source software](https://www.theregister.com/2021/10/29/china_encourages_foss_in_fintech/)  
"China has told its finance sector to embrace free and open source software (FOSS)." This [opinion](http://www.cac.gov.cn/2021-10/27/c_1636928705274546.htm) also calls out the need to be ready for when open source software is found to have a vulnerability and to have a solid understanding of software supply chains. Good stuff.

## Tools

[Video: Admiral Grace Hopper Explains the Nanosecond](https://www.youtube.com/watch?v=9eyFDBPk4Yw)  
Your app or microservice should have a constant goal of serving its output faster. This isn't a one and done thing, this is a continuous process. Psychology shows you should worry about speed and making things faster.

Understand nested relationships across your microservices with distributed tracing and observability. Wrangling production complexity doesn't have to be hard. Make tracing powerful, effective, and easy! [Use Honeycomb for free](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *SPONSORED*

[Knative 1.0 is out!](https://knative.dev/blog/articles/knative-1.0/)  
"Today we release Knative 1.0, reaching an important milestone made possible thanks to the contributions and collaboration of over 600 developers. The Knative project was released by Google in July 2018, and it was developed in close partnership with VMWare, IBM, Red Hat, and SAP. Over the last 3 years, Knative has become the most widely-installed serverless layer on Kubernetes." Congrats to the Knative community!

[What the Arrival of IPv6 Support in Kubernetes Means for You](https://metal.equinix.com/blog/kubernetes-ipv6-ipv4-dual-stack-networking/)  
"Native dual-stack networking in Kubernetes 1.23 carries implications for networking, security, load balancing, and breadth of use cases."

[The Architecture of Open Source Applications (Volume 2): nginx](https://aosabook.org/en/nginx.html)  
Nerd out on nginx's architecture.

[Anatomy of a Terminal Emulator](https://www.poor.dev/terminal-anatomy/)  
Nerd out on your terminal emulator's architecture

[October 2021 Web Server Survey](https://news.netcraft.com/archives/2021/10/15/october-2021-web-server-survey.html)  
These surveys are always eye-opening to me. I haven't looked at one in a while either so it was EXTRA eye opening. Case in point, when was the last time you used Apache httpd? It has been a little while for me too. That shows up in these results.

[Canonical Begins Offering Ubuntu Images Optimized For Intel CPUs](https://www.phoronix.com/scan.php?page=news_item&px=Ubuntu-Intel-IoT-Optimized)  
"Canonical with cooperation from Intel is beginning to publish ISO images of Ubuntu Core 20 and Ubuntu 20.04 LTS desktop that are optimized for Intel Atom X6000E series / Pentium / Celeron N / Celeron J processors (Elkhart Lake) as well as Intel 11th Gen Core processors." Optimized operating systems is increasingly going to become a thing (we're already seeing it with containers and IoT). IoT needs a lightweight, highly-optimized environment to do its work. I like to equate IoT devices to the Apollo or Space Shuttle program. There's only so much processing you can do, thermodynamics matter a lot, and there's typically a high cost of putting the right engineer's hands on the equipment itself.

[A truly Open Source MongoDB alternative](https://www.mangodb.io/)  
"MangoDB is going to be a perfect solution for those looking for MongoDB development experience available as fully Open Source Software." Apache v2 Licensed alternatives to formerly open source projects are always welcome in my book.

[How to Setup an NGINX Kubernetes Ingress Controller](https://adamtheautomator.com/kubernetes-ingress/)  
I always like a fresh perspective on a problem. "Ingress controllers implement networking rules such as incoming TCP connections and routing. One of the most used ingress controllers is NGINX, a powerful web service that acts as an interface between a cluster and the outside work. In this tutorial, you will learn how to set up an NGINX Kubernetes Ingress Controller step by step."

[terrytangyuan/awesome-argo](https://github.com/terrytangyuan/awesome-argo)  
A curated list of awesome projects and resources related to Argo (a CNCF hosted project)

[kubecost/kubectl-cost](https://github.com/kubecost/kubectl-cost)  
CLI for determining the cost of Kubernetes workloads ⭐️⭐️⭐️⭐️⭐️

[corneliusweig/konfig](https://github.com/corneliusweig/konfig)  
konfig helps to merge, split or import kubeconfig files ⭐️⭐️⭐️⭐️⭐️

[patrickdappollonio/kubectl-slice](https://github.com/patrickdappollonio/kubectl-slice)  
Split multiple Kubernetes files into smaller files with ease. Split multi-YAML files into individual files. ⭐️⭐️⭐️⭐️

[aws/eks-anywhere](https://github.com/aws/eks-anywhere)  
Run Amazon EKS on your own infrastructure 🚀

[rikatz/kubepug](https://github.com/rikatz/kubepug)  
Kubernetes PreUpGrade (Checker). This is cool, here's what it does, "Downloads a `swagger.json` from a specific Kubernetes version, parses this json finding deprecation notices, verifies the current kubernetes cluster or input files checking whether objects in deprecated API versions."

[adamgoose/tsk](https://github.com/adamgoose/tsk)  
Quickly connect to your Kubernetes Cluster with Tailscale (using Pulumi). I haven't used this yet as drywall work is being done in the basement and that's where my Dell R820 lives (it's off during this phase of construction).

[digitalis-io/vals-operator](https://github.com/digitalis-io/vals-operator)  
Kubernetes Operator to sync secrets between different secret backends and Kubernetes. I see an increasing need for things like this as companies use of Kubernetes increases.

[github/copilot.vim](https://github.com/github/copilot.vim)  
Neovim plugin for GitHub Copilot. For what it's worth, I've stopped using Copilot. If you've seen some of [my posts about GitHub Copilot on Twitter](https://twitter.com/search?q=Copilot%20(from%3AChrisShort)&src=typed_query), you know why. But, maybe you'll find it helpful.

## DevOps'ish Tweet of the Week

I cannot stress enough how a Dilbert cartoon will immediately disqualify whatever it is you're trying to accomplish.

[![matty stratton, charismatic grifter (@mattstratton) on Twitter) "Reminder to remove all Dilbert references / comics from your slides, decks, and everything. It's not even that funny anymore, but the creator is one of the worst people in existence."](https://shortcdn.com/file/devopsish/242-devopsish-tweet-of-the-week.webp)](https://twitter.com/mattstratton/status/1456137519645483011)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/242/notes/) to see what didn't make it to the newsletter but are still worth your time.
