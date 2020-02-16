+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "2020"]
date = 2020-02-16T07:00:00Z
description = "Kubernetes team secrets, Amazon bending CAP Theorem, JEDI chokes Microsoft, GitHub CLI, Kiali the Istio dashboard, coding bootcamp scams, and more"
draft = false
slug = "167"
tags = ["Kubernetes", "DevOps", "cloud", "cloud native", "open source", "Amazon", "CAP Theorem", "JEDI", "exhaustion", "exhausted", "infrastructure", "Microsoft", "container", "Linux", "Istio", "GitHub", "coding bootcamp", "Kiali", "debt", "funding", "database", "Datadog", "Python", "VScode", "SSH", "Google", "HAProxy", "Linus Torvalds"]
title = "DevOps'ish 167"

+++

I got up this morning and was quickly exhausted from pain. I had noticed this exhausted feeling earlier in the week. It was the day of a doctor’s appointment to get injections to fix the mentally distracting nature of constant, chronic pain. I discovered [burnoutindex.org](https://burnoutindex.org/), which is a nine-question test to give you an idea of your main risk factors of burnout. My two key elements are self-inefficacy and exhaustion ([see my burnout report](/pdf/Chris-Short-Global-IT-Burnout-Index.pdf)). I’ve proven that this exhausted feeling is a real thing; what do I do about it? According to this, I need to figure out what my sources of energy are and bulk up on them while working to figure out what work-related urgencies are overwhelming. I think my problem is that I feel like I’m often trying to move a celestial body into or out of an orbit. The force, effort, time, and energy this requires is enormous. Of course, if you feel like the weight of the world is on you, exhaustion is a natural outcome. I have to remember that I’m sitting behind a keyboard and that I am only human. Hopefully, this too shall pass.

## People

[The Evolution of Trust](https://ncase.me/trust/)  
A beautiful and easy to digest game explaining game theory and to help fix our "epidemic of distrust." You had me at trench warfare.

[Kubernetes: 6 secrets of successful teams](https://enterprisersproject.com/article/2020/2/kubernetes-6-secrets-success)  
Here are six significant things that high-performing teams do when successfully running Kubernetes in production

[Lambda School: the high cost of a free coding bootcamp](https://www.theverge.com/2020/2/11/21131848/lambda-school-coding-bootcamp-isa-tuition-cost-free)  
The coding bootcamp is turning into an exploitative venture. I know a lot of people that went to them. But, I don't think any of them told me they got a lot out of it.

[Why I Contribute to the Open Source Community—and You Should Too](https://upshotstories.com/stories/why-i-contribute-to-the-open-source-community-and-you-should-too)  
"I made up for the shaky foundations provided by my foster residences by building the bedrock of a new reality through coding." My buddy and fellow veteran Marky Jackson provides a must read this week.

[You see pilot error, I see normal work](https://safetydifferently.com/you-see-pilot-error-i-see-normal-work/)  
An amazing breakdown of what the Australian Transport Safety Bureau (ATSB) got wrong about a Jetstar Airways flight that had to do two go-arounds.

## Process

[Scaling to 100k Users](https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html)  
A high level look at how infrastructure changes should occur as you scale. Note that splitting frontend and database is step one.

[Debt is Coming](https://alexdanco.com/2020/02/07/debt-is-coming/)  
The SaaS model is going to open doors to funding things with debt as the value of the cash flow itself becomes the thing that people work to monetize. To some people, companies make money, not products. That perspective changes your view of the world.

[Amazon Found Every 100ms of Latency Cost them 1% in Sales](https://www.gigaspaces.com/blog/amazon-found-every-100ms-of-latency-cost-them-1-in-sales/)  
Having infrastructure isn't good enough. Measuring, researching, and making improvements iteratively should always be a part of your life.

[Amazon EBS addresses the challenge of the CAP Theorem at scale](https://www.amazon.science/blog/amazon-ebs-addresses-the-challenge-of-the-cap-theorem-at-scale)  
I'm sure Corey Quinn will have smarter things to say about this. But, if you have enough infrastructure to host Netflix you can pretty much do away with CAP Theorem. Also, putting the database closer to the work being done helps.

[Microsoft sees $17 billion of market value erased in just 5 minutes after a judge grants Amazon's request to block a key cloud contract](https://markets.businessinsider.com/news/stocks/microsoft-stock-price-17-billion-erased-judge-blocks-cloud-contract-2020-2-1028904685)  
Amazon won an injunction that forced Microsoft and DoD to stop work on the $10 billion JEDI contract. The stock market responded by wiping out $17 billion of Microsoft's market cap.

## Tools

[Python programming language: Now you can take NSA's free course for beginners](https://www.zdnet.com/article/python-programming-language-now-you-can-take-nsas-free-course-for-beginners/)  
Obtained through a FOIA request, NSA's Python course COMP 3221 is now available.

[Visual Studio Code is now my Default SSH Client and Linux file Editor!](https://anthonyspiteri.net/visual-studio-code-ssh-client/)  
I hear the Remote Development extension for VScode is dope. I installed it and it immediately read my SSH config and did a `docker ps`. This is nifty and going to come in handy. Thank you, Anthony Spiteri.

[Kiali: An observability platform for Istio](https://next.redhat.com/2020/02/10/kiali-an-observability-platform-for-istio/)  
Kiali is a graphical dashboard, visualization tool, and user interface for Istio. It allows you to view and modify the Istio configuration for your application directly in your web browser, and to visualize the behavior of your application.

[Dynamic Kubernetes Monitoring](https://www.datadoghq.com/dg/monitor/kubernetes-monitoring-benefits/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=DevOpsish-Newsletter01&utm_content=Kubernetes)  
Monitor and manage your dynamic Kubernetes container fleet with Datadog. Use the Container Map to group, filter, and explore your containers, and the Live Container view to investigate the metrics and processes of individual containers. Try Datadog in your environment with a free 14-day trial. *SPONSORED*

[Google Cloud Advantages over AWS](https://itnext.io/google-cloud-advantages-over-aws-28751469e570)  
"This post is not about GCP vs. AWS... This post is a short summary of the advantages of GCP over AWS." I agree that the network is fast af.

[Supercharge your command line experience: GitHub CLI is now in beta](https://github.blog/2020-02-12-supercharge-your-command-line-experience-github-cli-is-now-in-beta/)  
"Millions of developers rely on GitHub to make building software more fun and collaborative, and `gh` brings the GitHub experience right to your terminal."

[Rolling Updates and Blue-Green Deployments with Kubernetes and HAProxy](https://www.haproxy.com/blog/rolling-updates-and-blue-green-deployments-with-kubernetes-and-haproxy/)  
"The HAProxy Kubernetes Ingress Controller supports two popular deployment patterns for updating applications in Kubernetes: rolling updates and blue-green deployments."

[The History of Git: The Road to Domination](https://www.welcometothejungle.com/en/articles/btc-history-git)  
"In 2005, Linus Torvalds urgently needed a new version control system to maintain the development of the Linux Kernel... Fifteen years later, the platform is the undisputed leader in a crowded field."

[Linus Torvalds Just Made A Big Optimization To Help Code Compilation Times On Big CPUs](https://www.phoronix.com/scan.php?page=news_item&px=Linux-Pipe-Parallel-Job-Opt)  
GNU Make is about to get faster in Linux 5.6 on large core count systems.

## DevOps'ish Tweet of the Week

{{< tweet 1226183144786685952 >}}
