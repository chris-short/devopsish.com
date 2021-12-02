+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2018"]
date = 2018-08-18T07:00:00Z
description ="Kubernetes, Get a Dog, GitHub, GitOps, Istio, AKS Woes, and More"
draft = false
slug = "089"
tags = ["devops", "cloud native", "cloud", "open source", "kubernetes", "ansible", "microservices", "metrics", "azure", "containers", "podman", "kafka", "backblaze", "jack dorsey", "Site Reliability Engineering", "SRE", "GitOps"]
title = "089: Kubernetes, Get a Dog, GitHub, GitOps, Istio, AKS Woes, and More"

+++

This week's newsletter is a day early. I'll be moving my daughter into college Sunday and Monday. It's a two-day process because southeastern Michigan isn't as close to southern Ohio as you'd think. I'll be in Dayton on Sunday and Cincinnati on Monday. Lemme know if you're around.

[**Blog Series: Continuous Delivery of Microservices - Parts 1 - 5**](https://www.gocd.org/tags/cd-for-microservices.html)  
This blog series from Sheroy Marker cover the principles of CD of microservices. Get a practical guide on designing CD workflows for microservices, testing strategies, trunk based development, feature toggles and environment plans. *SPONSORED*

[**Correlate request traces, metrics, and logs**](https://www.datadoghq.com/lpgs/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-Newsletter)  
Smoothly navigate between logs, metrics, and request traces for a clear view of all your systems. Visualize and alert on metrics in real-time with anomaly and outlier detection. [Try Datadog's full-stack monitoring for free](https://www.datadoghq.com/lpgs/?utm_source=Advertisement&utm_medium=Advertisement&utm_campaign=Devopsish-Newsletter) *SPONSORED*

[**eBook: Building Continuous Delivery Pipelines**](https://go.weave.works/TPCS-devops-newsletter)  
Learn the steps required to plan and implement a CD pipeline in your organization, including the benefits and best practices. [Download eBook](https://go.weave.works/TPCS-devops-newsletter) *SPONSORED*


## People

[Kwyn Meagher is looking for work](https://blog.kwyn.io/hireme.html): **You should hire Kwyn**. "I'm looking for a senior full-stack role on a product or developer tools team."

[Hackers can cook you alive using 'microwave oven' sat-comms – claim](https://www.theregister.co.uk/2018/08/10/satellite_communications_microwave_oven_hacking/): Planes, ships, military equipment at risk due to backdoors, vulns

[This lifehack will change your life—if you can stand it](https://qz.com/1353399/this-lifehack-will-change-your-life-if-you-can-stand-it/): The secret to achieving excellence is disarmingly simple. You might not like it, though.

[Powerful women told me getting a dog is the key to success. They were right](https://qz.com/work/1347901/powerful-women-told-me-getting-a-dog-was-the-key-to-success-they-were-right/): We don't deserve dogs.

[Netflix CFO David Wells to step down](https://techcrunch.com/2018/08/13/netflix-cfo-david-wells-to-step-down/)

[I started a corporation!](https://jvns.ca/blog/2018/08/14/i-started-a-company-/): "So I decided to start a corporation (just on the side, I still work at the same place ❤) to manage the logistics. I'm pretty excited about this so I wanted to explain why."

[Engineers Say "No Thanks" to Silicon Valley Recruiters, Citing Ethical Concerns](https://spectrum.ieee.org/view-from-the-valley/at-work/tech-careers/engineers-say-no-thanks-to-silicon-valley-recruiters-citing-ethical-concerns): "Some engineers are turning down tech recruiters by citing concerns about corporate values." One good thing the Baby Boomers showed us is that selling your soul for work doesn't actually get you much.

[An Interview with Jez Humble on Continuous Delivery, Engineering Culture, and Making Decisions](https://www.split.io/blog/jez-humble-interview-decisions-2018/)

## Process

[Spectre-Like Flaw Undermines Intel Processors' Most Secure Element](https://www.wired.com/story/foreshadow-intel-secure-enclave-vulnerability/): Another bad week for Intel.

[Pinning its Past, Present, and Future on Cloud Native](https://www.cncf.io/blog/2018/08/14/pinning-its-past-present-and-future-on-cloud-native/): My friend, [Kim McMahon](https://twitter.com/kamcmahon), shows us a talk I sadly missed at KubeCon last year (I was looking for a job after all).

[2FA, SMS, and you](https://www.juliaferraioli.com/blog/2018/08/2fa-sms-you/): Julia Ferraioli (sorry Julia, I probably spelled your name wrong) shows us, "not all 2FA is created equal."

[GitHub goes off the Rails as Microsoft closes in](https://www.theregister.co.uk/2018/08/16/github_rails_microsoft/): Ruby shop turns to Go, Java, and Kubernetes for platform makeover

[Firefighters choke on Oracle's alleged smoke-and-mirrors cloud](https://www.theregister.co.uk/2018/08/13/oracle_sued_cloud_numbers/): Pension fund cries fraud over database giant's boasts about its off-prem biz performance

[Site Reliability Engineering at New Relic](https://newrelic.com/resource/site-reliability-engineering): Philosophies, Habits, and Tools for SRE Success

[What the f*** is the edge?](https://arcentry.com/blog/what-the-f-is-the-edge/): The edge is far and wide and close and narrow all at the same time.

[7 best practices for operating containers](https://cloud.google.com/blog/products/gcp/7-best-practices-operating-containers): "This post goes over what you need to know and do to efficiently run containers in Kubernetes."

[Horrors of using Azure Kubernetes Service in production](https://movingfulcrum.com/horrors-of-using-azure-kubernetes-service-in-production/): Even with all the brain power Microsoft has pulled in, running AKS is a huge challenge.

[Jack Dorsey says he's rethinking the core of how Twitter works](https://www.washingtonpost.com/technology/2018/08/15/jack-dorsey-says-hes-rethinking-core-how-twitter-works/): Twitter CEO Jack Dorsey said he was experimenting with features to address misinformation and reduce "echo chambers."

[Apple says no personal data compromised in teenager hacking incident](https://9to5mac.com/2018/08/17/personal-data-safe-teenager-hacker/): This made me laugh out loud when I read it today. "The individual collected tens of gigabytes of confidential, secure, company files and saved them in a folder named 'hacky hacky hack'."

[cliqz-oss/local-sheriff](https://github.com/cliqz-oss/local-sheriff): Think of Local sheriff as a recon tool in your browser (WebExtension). While you normally browse the internet, Local Sheriff works in the background to empower you in identifying what data points (PII) are being shared / leaked to which all third-parties.

[Logging Best Practices for Kubernetes using Elasticsearch, Fluent Bit and Kibana](https://itnext.io/logging-best-practices-for-kubernetes-using-elasticsearch-fluent-bit-and-kibana-be9b7398dfee): "There are many options for logging when building Cloud Native applications. We've evaluated several options and found a set of tools that work well for us."

[CNCF Seeks to Advance IT Performance Monitoring with OpenMetrics Spec](https://thenewstack.io/cncf-seeks-to-advance-it-performance-monitoring-with-openmetrics-project/): "Prometheus will move to this OpenMetrics model, as will microservices-oriented monitoring software from InfluxData, Sysdig, Weave, and OpenCensus."

## Tools

[Managing Helm releases the GitOps way](https://www.weave.works/blog/managing-helm-releases-the-gitops-way): "using `git push` instead of `kubectl create/apply` or `helm install/upgrade`."

[Multi-stage Serverless on Kubernetes with OpenFaaS and GKE](https://www.openfaas.com/blog/gke-multi-stage/): Learn how to set up OpenFaaS on Google Kubernetes Engine (GKE) with a cost-effective, auto-scaling, multi-stage deployment.

[Health Checks and Graceful Degradation in Distributed Systems](https://medium.com/@copyconstruct/health-checks-in-distributed-systems-aa8a0e8c1672): "The 'health' of a process is a spectrum. What we're really interested in is the quality-of-service — such as how long it takes for a process to return the result of a given unit of work and the accuracy of the result."

[Kubernetes Networking: How to Write Your Own CNI Plug-in with Bash](https://www.altoros.com/blog/kubernetes-networking-writing-your-own-simple-cni-plug-in-with-bash/): Learn how to create a container network interface plug-in, configure and test it, as well as enable external access and communication between containers.

[Automating Deployments Using Ansible AWX & Jenkins](https://n4stack.io/2018/08/15/automating-deployments-ansible-jenkins/): "Jenkins was deployed to intercept the webhook from GitHub and then trigger the correct playbook run in Ansible AWX"

[Rook.io : Ceph Persistent Storage Made Easy on Kubernetes](https://www.linkedin.com/pulse/rookio-ceph-persistent-storage-made-easy-kubernetes-gokul-chandra/)

[Python3 support for Podman](https://medium.com/cri-o/python3-support-for-podman-a0a2395c3b4): "The python3-podman package containers a module that allows you to connect to a Podman socket activated systemd service on the same host or a remote host using a ssh tunnel."

[jesseduffield/lazygit](https://github.com/jesseduffield/lazygit): simple terminal UI for git commands

[A sysadmin's handy cheat sheet for SELinux](https://opensource.com/article/18/8/cheat-sheet-selinux): Improve your skills managing and using Security-Enhanced Linux with this helpful guide.

[The Five Stages of YAML](https://brokenco.de/2018/08/15/five-stages-of-yaml.html)

[Getting started with the Secure DevOps Kit for Azure (AzSK)](https://channel9.msdn.com/Shows/Azure-Friday/Getting-started-with-the-Secure-DevOps-Kit-for-Azure-AzSK): Mark Jacobs joins Scott Hanselman to discuss how Microsoft's internal enterprise increases compliance and creates a more trusted cloud environment using the Secure DevOps Kit for Azure (AzSK).

[Introducing Kafka-Kit: Tools for Scaling Kafka](https://www.datadoghq.com/blog/engineering/introducing-kafka-kit-tools-for-scaling-kafka/): Kafka-Kit is a collection of tools that handle partition to broker mappings, failed broker replacements, storage based partition rebalancing, and replication auto-throttling.

[Istio Aims To Be The Mesh Plumbing For Containerized Microservices](https://www.nextplatform.com/2018/08/15/istio-aims-to-be-the-mesh-plumbing-for-containerized-microservices/): "There is a third piece of the puzzle that is still up in the air, which Istio is designed to meet."

[vr00n/Amazon-Web-Shenanigans](https://github.com/vr00n/Amazon-Web-Shenanigans): A lambda function that checks your account for Public buckets and emails you whenever a new public s3 bucket is created

[Minio as an S3 Gateway for Backblaze B2 Cloud Storage](https://www.backblaze.com/blog/how-to-use-minio-with-b2-cloud-storage/): "Minio is designed to be straightforward to deploy and use. If you're using an S3-compatible integration, or just want to try out Backblaze B2 using your existing knowledge of S3 APIs and commands, then Minio can be a quick solution to getting up and running with Backblaze B2 and taking advantage of the lower cost of B2 cloud storage."

[cattlepi/cattlepi](https://github.com/cattlepi/cattlepi): effortlessly boot, configure, update and monitor your raspberry pi

[Tutorial: How to deploy an app to production with an actual button](https://blog.github.com/2018-08-16-how-to-deploy-to-production-with-an-actual-button/)

## DevOps'ish Tweet of the Week

{{< tweet 1030238942744981505 >}}
