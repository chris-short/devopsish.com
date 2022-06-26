+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2018"]
date = 2018-03-18T07:00:00Z
description = ""
draft = false
slug = "067"
tags = ["devops", "cloud native", "open source", "google cloud", "azure", "cncf", "kubernetes", "microsoft", "security", "Docker"]
title = "067: Microsoft Blowing It, Kubernetes security, NATS, skaffold, and More!"
image ="https://shortcdn.com/file/devopsish/view-from-gke-office.jpg"
imagealt = "View of Bay Area from GKE Office in Sunnyvale"
imagecap = "View of Bay Area from GKE Office in Sunnyvale"

+++

I was in Sunnyvale and San Francisco most of the week and just got home. Thank you to the folks at Google Cloud for putting on an amazing event. I learned a lot during my visit. I'm exhausted though.

**GoCD: Visualize and Model Complex CD Workflows**  
GoCD supports continuous delivery out of the box with its built-in pipelines, advanced traceability and value stream visualization. With GoCD, you can easily model, orchestrate and visualize complex workflows from end to end. GoCD supports modern infrastructure and cloud deployments.

[Learn how to setup your first pipeline](https://www.gocd.org/getting-started/part-1/?utm_source=changelog&utm_campaign=changelog-news&utm_campaign=gocd_visualize_model_workslow&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=GOCD_getting_started&utm_term=) OR [check out their enterprise plugins and support](https://www.gocd.org/enterprise/?utm_campaign=gocd_visualize_model_workslow&utm_medium=newsletter_ad&utm_source=devopsish&utm_content=enterprise_page&utm_term=). *SPONSORED*

## Events

[**Open Source 101 Columbia**](http://opensource101.com/columbia/)  
Date: 2018-04-17  
Sadly I won't be able to participate in Open Source 101 Columbia but if it's half as good as the one held in Raleigh it's a can't miss event. [Open Source 101](http://opensource101.com/columbia/) is such a fantastic and inexpensive event (if you need assistance with a ticket let me know).

[**ChefConf 2018**](https://chefconf.chef.io/)  
Dates: 2018-05-22 through 2018-05-25  
Join an awesome community of #DevOps and automation professionals at [ChefConf](https://chefconf.chef.io/) in Chicago. I'll be presenting a brand spanking new talk, *DevOps is Not a War*. Save 10% with discount code 'Hugs4Chef'.

[**DevOpsDays Toronto 2018**](https://www.devopsdays.org/events/2018-toronto/welcome/)  
Dates: 2018-05-30 through 2018-05-31  
I'll admit it, I've never been to Canada. But, I'm definitely going to [DevOpsDays Toronto](https://www.devopsdays.org/events/2018-toronto/welcome/) this year to present *What the Military Taught Me about DevOps*.

## People

[Microsoft faces 238 complaints of gender discrimination](https://www.engadget.com/2018/03/13/microsoft-faces-238-complaints-of-gender-discrimination-harassment/): The company says not enough women have been affected to warrant a class action. WTF MICROSOFT?!?

[5 Reasons Why Women Aren't Applying to Speak at Your Conference](https://gojanego.co/5-reasons-why-women-arent-applying-to-speak-at-your-conference/): You should follow Chloe Condon, she's going places.

[How to avoid humiliating newcomers: A guide for advanced developers](https://opensource.com/article/18/3/avoid-humiliating-newcomers): To sustain an open source community's growth, we need to welcome new developers. Unfortunately, we are not always a welcoming bunch.

[Building Bridges to GopherCon 2018](https://medium.com/@ashleymcnamara/gophercon-2018-b9a97387b954): Raise money to send folks to GopherCon through buying absolutely amazing Go shirts (art by Ashley McNamara).

## Process

[Say yes to Markdown, no to MS Word](https://medium.com/@drodil/say-yes-to-markdown-no-to-ms-word-be4692e7a8cd): Please, for the love of all things holy, don't be like Oracle and show up for an engagement with a Word doc to copy and paste commands from into a terminal.

[Kubernetes Security Announcement](https://groups.google.com/forum/#!topic/kubernetes-dev/YWizN8DQS5k): Kubernetes 1.7.14, 1.8.9, and 1.9.4 released to address volume vulnerabilities. These vulns spurred me to finally sit down and bang out the [rak8s](https://rak8s.io/) upgrade playbook.

[3 best practices for securing Kubernetes environments](https://opensource.com/article/18/3/best-practices-securing-kubernetes-environments): Get proactive to defend against the biggest risks facing Kubernetes deployments.

[Analysis of a Kubernetes hack — Backdooring through kubelet](https://medium.com/handy-tech/analysis-of-a-kubernetes-hack-backdooring-through-kubelet-823be5c3d67c): It appears someone found a way to drop some crypto mining software on a running container and execute the process.

[Enforcing the 'Two-Person Rule' with AWS CodePipeline](https://www.trek10.com/blog/enforcing-two-person-rule-aws-codepipeline/)

## Tools

[CNCF to Host NATS](https://www.cncf.io/blog/2018/03/15/cncf-to-host-nats/): I really like [NATS](https://nats.io/); it's one of the first Go projects I tinkered with. "NATS is a messaging technology that implements the publish/subscribe, request/reply and distributed queue patterns to help create a performant and secure method of InterProcess Communication (IPC)."

[GoogleCloudPlatform/skaffold](https://github.com/GoogleCloudPlatform/skaffold): Having seen skaffold in action this week at Google, I know it's going to be a huge time saver for folks.

[Service Fabric is going open source](https://blogs.msdn.microsoft.com/azureservicefabric/2018/03/14/service-fabric-is-going-open-source/): Microsoft Azure Service Fabric is going open source under the MIT license and over the coming months we will be transitioning to a completely open development process on GitHub.

[Interactive Linux Kernel Map](http://www.makelinux.net/kernel_map/)

[How to use Ansible to set up system monitoring with Prometheus](https://opensource.com/article/18/3/how-use-ansible-set-system-monitoring-prometheus): In the third part of this Ansible how-to series, learn how to automate system monitoring.

[erroneousboat/slack-term](https://github.com/erroneousboat/slack-term): Slack client for your terminal written in Go

[Jenkins X provides CI/CD for Kubernetes](http://jenkins-x.io/): Not sure what Cloudbees is trying to do here. I tried to get this working on minikube on Wednesday and couldn't. But, at least they realize Kubernetes is a thing they should address.

[gitkube](https://gitkube.sh/): Build and deploy docker images to Kubernetes using git push.

[How to Integrate RollingUpdate Strategy for TPR in Kubernetes](http://blog.kubernetes.io/2018/03/how-to-integrate-rollingupdate-strategy.html)

[Introducing Agones](https://cloudplatform.googleblog.com/2018/03/introducing-Agones-open-source-multiplayer-dedicated-game-server-hosting-built-on-Kubernetes.html): Open-source, multiplayer, dedicated game-server hosting built on Kubernetes

[Mitogen](http://mitogen.readthedocs.io/en/latest/ansible.html): An experimental extension to Ansible is included that implements host connections over Mitogen, replacing embedded shell invocations with pure-Python equivalents invoked via highly efficient remote procedure calls tunnelled over SSH. No changes are required to the target hosts.

[8 DevOps tools that smoothed our migration from AWS to GCP: Tamr](https://cloudplatform.googleblog.com/2018/03/8-DevOps-tools-that-smoothed-our-migration-from-AWS-to-GCP-Tamr.html)

## DevOps'ish Tweet of the Week

{{< tweet 974392354328272897 >}}
