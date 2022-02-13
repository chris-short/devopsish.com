+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-04-11T07:00:00Z
description = "Kubernetes 1.21, ArgoCD 2.0, Supreme Court saves industry, Googlers can discuss salary, Amazon made illegal firings, former Facebook recruiter sees diversity policy flaws, and more"
draft = false
slug = "213"
tags = ["DevOps", "cloud", "cloud native", "enhancements", "Google", "GitOps", "environments", "release", "Facebook", "software", "Kubernetes", "Linux", "open source", "LaunchDarkly", "IBM", "observability", "COBOL", "Amazon", "API", "Court", "ArgoCD", "Vault", "developers", "Apple", "Microsoft"]
title = "DevOps'ish 213: Kubernetes 1.21, ArgoCD 2.0, Supreme Court saves industry, Googlers can discuss salary, Amazon made illegal firings, former Facebook recruiter sees diversity policy flaws, and more"

+++

I've had a rough week, please forgive me for not laboring over an intro.

#### Event Call for Papers

**The GitOps Working Group** is putting together a KubeCon + CloudNativeCon Day 0 event! Come share your experiences, practices, and challenges with us at [#GitOpsConEU2021](https://twitter.com/search?q=%23GitOpsConEU2021&src=devopsish)! [**Call for papers**](https://docs.google.com/forms/d/e/1FAIpQLSeNahDbiEolx6WZmtxx4L65qmq7pZTX86nQAltq2uC12tCQYg/viewform) open through April 16, 2021.

## People

[The woman who took on Google and won](https://www.bbc.com/news/technology-56659212)  
"[Google signed a document](https://shortcdn.com/file/devopsish/20210331_nlrbsettlement_alphabet_modis.pdf) saying its employees 'have the right to discuss wage rates, bonuses, and working conditions.'"

[Never wait for a staging environment again](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=title&utm_campaign=20210228) 👩‍💻🧑‍💻👨‍💻👩‍💻  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team's ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. You'll never have to wait around for staging environments again. 💡 [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=20210228) 💡 *SPONSORED*

[Amazon Illegally Fired Activist Workers, Labor Board Finds](https://www.nytimes.com/2021/04/05/technology/amazon-nlrb-activist-workers.html)  
"The two employees had publicly pushed the company to reduce its impact on climate change and address concerns about its warehouse workers."

[Facebook recruiter quit company over hiring bias](https://www.washingtonpost.com/technology/2021/04/06/facebook-discrimination-hiring-bias/)  
"The recruiter quit after 11 months, adding fuel to claims that the company discriminates against Black applicants"

[I no longer answer customer support surveys](https://www.yesthatblog.com/post/0110-i-no-longer-answer-customer-support-surveys/)  
Those surveys aren't actually addressing the systemic problems of an organization. They are helping assign blame in a lot of cases.

[What Working Dads Can Do When a High-Pressure Job Asks Too Much](https://hbr.org/2021/04/what-working-dads-can-do-when-a-high-pressure-job-asks-too-much)  
"The author recommends five steps to take to better align your career choices with your priorities: get over yourself; explore flexible and remote work; prioritize father-friendly employers; consider different industry sectors; and recognize and adjust to financial trade-offs."

## Process

[How the Supreme Court saved the software industry from API copyrights](https://arstechnica.com/tech-policy/2021/04/how-the-supreme-court-saved-the-software-industry-from-api-copyrights/)  
"By a 6-2 vote, the nation's highest court held that Google's copying of Oracle's Java API was fair use. The ruling means Google won't have to pay billions of dollars in damages to Oracle. It also has huge implications for the broader software industry."

[Learn what LaunchDarkly can do for your organization.](https://learn.launchdarkly.com/demo?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
LaunchDarkly enables companies like Square, Hulu, Atlassian, Toyota, Intuit, IBM, and others gain a competitive edge with better feature management.
Move fast without breaking things and learn how your team can reap the rewards of CI/CD without the risk.
Ship Fast. Rest Easy.  LaunchDarkly. *SPONSORED*

[Google Is Testing Its Controversial New Ad Targeting Tech in Millions of Browsers. Here’s What We Know.](https://www.eff.org/deeplinks/2021/03/google-testing-its-controversial-new-ad-targeting-tech-millions-browsers-heres)  
I *finally* got highly motivated to move to [Brave](https://brave.com/). Get off Chrome is now my official stance.

[Facebook isn’t sorry for letting someone steal personal details of half a billion users](https://grahamcluley.com/facebook-isnt-sorry-for-letting-someone-steal-personal-details-of-half-a-billion-users/)  
"So I can assume that Facebook isn’t sorry. It doesn’t even say that it’s going to contact the half a billion users who have had their details leaked onto the internet – not because of the users’ own fault, but because of Facebook’s incompetence and lack of care."

[Update on git.php.net incident](https://externals.io/message/113981)  
* We no longer believe the git.php.net server has been compromised.  
* However, it is possible that the master.php.net user database leaked. master.php.net has been migrated to a new system main.php.net.  
* All php.net passwords have been reset. Go to https://main.php.net/forgot.php to set a new password.  
* git.php.net and svn.php.net are both read-only now, but will remain available for the time being.

## Tools

[Kubernetes 1.21: Power to the Community](https://kubernetes.io/blog/2021/04/08/kubernetes-1-21-release-announcement/)  
"We’re pleased to announce the release of Kubernetes 1.21, our first release of 2021! This release consists of 51 enhancements: 13 enhancements have graduated to stable, 16 enhancements are moving to beta, 20 enhancements are entering alpha, and 2 features have been deprecated."

Observability started out as a fairly obscure technical term but has recently received a lot of attention. Our [Achieving Observability guide](https://www.honeycomb.io/guide-achieving-observability-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_keyword=&utm_content=guide-achieving-observability-devopsish&utm_adgroup) discusses the history, concept, goals, and approaches to achieving observability in today’s software industry, with an eye to the future benefits and potential evolution of the software development practice as a whole.

Observe, debug, and improve with [Honeycomb](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). *PROCESSED*

[Argo CD 2.0 Released!](https://www.cncf.io/blog/2021/04/07/argo-cd-2-0-released/)  
"2.0 brings a wealth of innovation and enhancements to an already feature-rich project,with exciting features from both the Argo Labs ecosystem as well as updates to CD core capabilities."

[Full Tutorial GitOps & ArgoCD | Day 34 of #100DaysOfKubernetes](https://www.youtube.com/watch?v=c4v7wGqKcEY)  
"What is GitOps?  How do we use it? Why would we want to use it and what are the benefits? This tutorial provides an introduction to GitOps and explains how it works. Additionally, we are going to get started with ArgoCD to manage our deployments."

[The Best DevOps Blogs](https://draft.dev/learn/technical-blogs/devops)  
It's a pleasure to be among this list of fine works.

[IBM creates a COBOL compiler – for Linux on x86](https://www.theregister.com/2021/04/07/ibm_cobol_x86_linux/)  
This is going to do a lot but, it's going to bring COBOL folks to Linux and Linux folks can help jump into COBOL workflows. A step closer to DevOps'ing the mainframe. [ETL](https://www.ibm.com/cloud/learn/etl) for all could be interesting too.

[How to compare the performance of different HashiCorp Vault backends](https://blog.flant.com/comparing-hashicorp-vault-backends-performance/)  
"In our case, we ended up using Consul as the backend that handles our project’s loads most optimally. Moreover, it is recommended by Vault developers. Its maintenance is still associated with noticeable overhead, though. However, there can be no compromise when it comes to stability issues: you have to do whatever you can to ensure that your configuration meets business requirements."

[sbarski/serverless-calculator](https://github.com/sbarski/serverless-calculator)  
The calculator to work out pricing for serverless (function-as-a-service) technologies

[bcicen/ctop](https://github.com/bcicen/ctop)  
Top-like interface for container metrics

## DevOps'ish Tweet of the Week

[![@__apf__ on Twitter: "My 9 book picks for engineering leaders 👇"](["https://shortcdn.com/file/devopsish/213-devopsish-tweet-of-the-week.png)](https://twitter.com/__apf__/status/1379973544759582725)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/213/notes/) to see what didn't make it to the newsletter but are still worth your time.
