+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2019"]
date = 2019-11-25T07:00:00Z
description = "155"
draft = false
slug = "155"
tags = ["Kubernetes", "KubeCon", "DevOps", "open source", "cloud native", "CNCF", "CNCF Ambassador", "containers", "GitOps", "Moby", "Ansible", "service mesh"]
title = "155: Disappointing KubeCon, employee engagement, death of 10x engineer, GitOps, Kubernetes with all the fixins, service mesh, and more"

+++

Editor's Note: The newsletter passed 3,975 subscribers this week. I'd love to end the month at 4,000 subscribers. If you don't mind, please ask your coworkers, BFFs, and folks on social media to [subscribe to DevOps'ish](https://devopsish.com/subscribe/). Y'all stay awesome!

I'm exhausted. I tweeted midweek that I likely shortened my lifespan at KubeCon this week and I wasn't sure why. It was a net negative experience for me. The people are great. I love meeting contributors and teaching new folks how to contribute. But, the problems that had to be solved on the ground were extreme in some cases. I sent out my unpolished report internally. I will share it when I have the energy to clean it up a lot.

I can tell you for certain, I'm not the only one that feels this way. One CNCF Ambassador already hung it up. I have legitimate concerns about the long term viability of Cloud Native Computing Foundation. At this rate of disregard for the communities forming underneath it, the intent seems to get as much money as possible at all costs. It's frustrating as hell and I'm still mulling what to do. If I end up leaving my CNCF Ambassador title behind, it would free up some time to do more in the community. I will not do a full KubeCon again.

[**X-Team is Hiring Go developers with strong AWS skills (Remote)**](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)  
We are looking for passionate Go developers with strong AWS skills to work with the world's leading brands, from anywhere. We love to work with Kubernetes, Docker, Serverless, and AWS tools. Travel the world while being part of the most energizing community of developers. We provide the funding needed to help you achieve your goals and grow as a remote developer. [Join X-Team](https://x-team.com/remote-go-developer-jobs/?utm_source=devopsish&utm_medium=email-ad)! *SPONSORED*

## People

[geopolitics.dev](https://geopolitics.dev/) — I'm launching a separate newsletter to dive into policy, ethics, and tech. If you like the People and Process section of this newsletter and don't mind living outside your comfort zone, [subscribe today](https://geopolitics.dev/subscribe/)!

[The Secret of Employee Engagement](https://www.sametab.com/blog/employee-engagement) — Context is key.

[Harness KubeCon NA ReCap](https://harness.io/2019/11/kubecon-na-recap-cloud-native-mainstream/) — My buddy, Ravi Lachhman, sums up their KubeCon NA 2019 experience.

[8 habits of successful DevOps team leaders](https://enterprisersproject.com/article/2019/11/devops-habits-successful-leaders) — "What do great leaders do differently as organizations scale DevOps? Use these best practices to set everyone up for success"

[Open Source Community Africa](https://opencollective.com/osca) — "We are a diverse community of open source lovers, collaborating on different projects to make a difference across Africa."

[Fundamentals of Containers, Kubernetes, and Red Hat OpenShift](https://www.edx.org/course/fundamentals-of-containers-kubernetes-and-red-hat) — Learn practical techniques for creating and deploying containers on a Kubernetes cluster using Red Hat® OpenShift Container Platform.

[How Remote Workers Make Work Friends](https://hbr.org/2019/11/how-remote-workers-make-work-friends)

[The death of the 10x engineer](https://www.thoughtworks.com/radar/techniques?blipid=201911057) — "It's more effective to build teams of talented individuals with mixed experiences and diverse backgrounds and provide the right ingredients for teamwork, learning and continuous improvement."

## Process

[The Unicorn Project: A Novel about Developers, Digital Disruption, and Thriving in the Age of Data](https://amzn.to/2XqekFl) — In *The Unicorn Project*, we follow Maxine, a senior lead developer, and architect, as she is exiled to the Phoenix Project, to the horror of her friends and colleagues, as punishment for contributing to a payroll outage. She tries to survive in what feels like a heartless and uncaring bureaucracy and to work within a system where no one can get anything done without endless committees, paperwork, and approvals.

[Is it too late to integrate GitOps?](https://blog.openshift.com/is-it-too-late-to-integrate-gitops/) — "[The] article will walk through the process of migrating an application and its resources that were created manually to a process in which a GitOps tool manages the assets."

[Moby or not Moby. That is the question: Docker devs debate fate of unloved rebranding](https://www.theregister.co.uk/2019/11/22/moby_docker_naming/) — "For developer Asim Aslam, who proposed the name reversion earlier this week, the switch to Moby harmed the project and its developer community and represents a liability." When the CTO of a company finishes a conference and has to [draw a picture on a napkin](https://twitter.com/solomonstre/status/855918630915133440) to explain the changes they just made...

[Kubernetes is the new Java: VMware](https://www.zdnet.com/article/kubernetes-is-the-new-java-vmware/) — Okay... 🤔

[Know Kubernetes — Pictorially](https://medium.com/tarkalabs/know-kubernetes-pictorially-f6e6a0052dd0) — A visual walkthrough of Kubernetes internals.

[Kubernetes and the misconception of multi-cloud portability](https://diginomica.com/kubernetes-and-misconception-multi-cloud-portability) — "It's time to bust a few myths and misconceptions about multi-cloud portability."

[Q&A: Fidelity invests in cloud-native, open-source projects to step up innovation](https://siliconangle.com/2019/11/21/qa-fidelity-invests-cloud-native-open-source-projects-step-innovation-kubecon/) — Fidelity had a keynote on the main stage on the first day. They had a branded graph about the timeline of the company that included when they adopted Kubernetes.

[Debugging network stalls on Kubernetes](https://github.blog/2019-11-21-debugging-network-stalls-on-kubernetes/)

[1.2 Billion Records Found Exposed Online in a Single Server](https://www.wired.com/story/billion-records-exposed-online/) — I was talking to a Kubernetes maintainer this week about how we should bake in functionality that would cut down dramatically on malicious activities. Basic admission controllers to enforce security hygiene and RFC compliance for DNS (port 53) for example. It could help cut down on reflection attacks as more infrastructure lands in containers on Kubernetes.

[Why Continuous Infrastructure Automation is no longer optional](https://medium.com/@CloudSkiff/why-continuous-infrastructure-automation-is-no-longer-optional-8b3e6bc8847)

[Amazon cites Fox News segment, Trump rally in formal protest of Pentagon’s $10B JEDI award](https://www.geekwire.com/2019/amazon-cites-fox-news-segment-trump-rally-formal-protest-pentagons-jedi-award/) — Called it.

## Tools

[The Service Mesh: What Every Software Engineer Needs to Know about the World's Most Over-Hyped Technology](https://servicemesh.io/) — It's written by the creator of Linkerd but it is filled with good information.

[Can someone ELI5 Service Meshes (Consul, Istio, etc)](https://www.reddit.com/r/devops/comments/dy7ecv/can_someone_eli5_service_meshes_consul_istio_etc/f7zu1ga/) — This response to a Reddit asking for a simple explanation of service meshes is great.

[Write secure Kubernetes configuration with help from Snyk](https://snyk.io/blog/write-secure-kubernetes-configuration-with-help-from-snyk/) — "A new Snyk feature to help you find and fix issues with your Kubernetes configuration as part of your development process." 👀

[Fargate Grows Faster Than Kubernetes Among AWS Customers](https://thenewstack.io/fargate-grows-faster-than-kubernetes-among-aws-customers/) — I guess it's time for me to kick the tires on Fargate again.

[What’s wrong with Pipeline as Code or why I don’t like Gitlab](https://medium.com/@raxwunter/whats-wrong-with-pipeline-as-code-or-why-i-don-t-like-gitlab-ca70c39eb52b) — This is why there is choice. Some good points too.

[Introducing Autopilot](https://medium.com/solo-io/introducing-autopilot-an-open-source-project-for-adaptive-service-mesh-3195accc9670) — An open source project for adaptive service mesh

[Continuous Improvements in Ansible and Kubernetes Automation](https://www.ansible.com/blog/continuous-improvements-in-ansible-and-kubernetes-automation) — Some really amazing work has gone into the [Ansible k8s module](https://docs.ansible.com/ansible/latest/modules/k8s_module.html). Yes, you could use Ansible as a Kubernetes client if you needed to.

[GCC Might Finally Have A Static Analysis Framework Thanks To Red Hat](https://www.phoronix.com/scan.php?page=news_item&px=GCC-Static-Analysis-RH-Patches) — GCC might be learning kung fu.

[Diane Mueller of Red Hat lays out all of the new OpenShift announcements](https://video.cube365.net/c/922842) — Among them, [OKD 4 alpha](https://www.okd.io/download.html) is available.

[Bash cheat sheet](https://opensource.com/article/19/11/bash-cheat-sheet) — Key combos and special syntax

[cloud-native-nordics/workshopctl](https://github.com/cloud-native-nordics/workshopctl) — A tool to run workshops with

## Tweet of the Week

[![Ian Coldwater 📦💥 @IanColdwater on Twitter) "Stop Using /v1beta1/"](https://shortcdn.com/devopsish/155-devopsish-tweet-of-the-week.webp)](https://twitter.com/IanColdwater/status/1213607102595424258)
