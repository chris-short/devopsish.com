+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-02-07T07:00:00Z
description = "Jassy's New Jam, KubeCon EU for $10, WFH? Wait for vaccine, GCP lost $5.6B in 2020, cloud shells compared, Well switch my qubits! and more"
draft = false
slug = "204"
tags = ["Cloud", "DevOps", "Kubernetes", "Google", "Open Source", "cloud shells", "environments", "Malware", "vaccine", "KubeCon", "cloud native", "Operators", "Chromium", "DNS", "qubits", "GCP", "developers", "continuous", "vulnerability"]
title = "DevOps'ish 204: Jassy's New Jam, KubeCon EU for $10, WFH? Wait for vaccine, GCP lost $5.6B in 2020, cloud shells compared, Well switch my qubits! and more"

+++

This week's biggest stories (my opinion):

[Email from Jeff Bezos to employees](https://www.aboutamazon.com/news/company-news/email-from-jeff-bezos-to-employees)  
Jassy in charge of the juggernaut come Q3.

[Deserted Island DevOps 2021: Call for Speakers/Papers @ Sessionize.com](https://sessionize.com/deserted-island-devops-2021/)  
I gotta hype this event. It was a very well done event last year.

[KubeCon EU Registration Now Open](https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/register/)  
$10 for a limited time.

[The Next Cyberattack Is Already Under Way](https://www.newyorker.com/magazine/2021/02/08/the-next-cyberattack-is-already-under-way)  
A few nits, but otherwise accurate.

## People

[Don’t Underestimate the Power of a Walk](https://hbr.org/2021/02/dont-underestimate-the-power-of-a-walk)  
"Walking is one of the simplest and most strategic things you can do for yourself. It takes little preparation, minimal effort, no special equipment, and it can contract or expand to fit the exact amount of time you have available. According to the Centers for Disease Control and Prevention, a single bout of moderate-to vigorous activity (including walking) can improve our sleep, thinking, and learning, while reducing symptoms of anxiety." Can confirm from multiple walks this week.

[Ephemeral Environments as a Service](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102)  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team’s ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. Your developers will never have to fight over staging environments again. [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=202102). *SPONSORED*

[DevOps: 5 habits of successful leaders](https://enterprisersproject.com/article/2021/2/devops-5-habits-successful-leaders)  
"Building and improving a DevOps culture requires a special kind of leader. The most successful DevOps leaders model habits including consensus-building and continuous learning"

[If You’ve Been Working from Home, Please Wait for Your Vaccine](https://www.scientificamerican.com/article/if-youve-been-working-from-home-please-wait-for-your-vaccine1/)  
"You can’t ethically go ahead of the very people who made it possible for you to do so—at great personal risk"

[Psychedelics as Antidepressants](https://www.scientificamerican.com/article/psychedelics-as-antidepressants/)  
"As of 2018, nearly one in eight Americans use antidepressants. Unfortunately, more than a third of patients are resistant to the mood-improving benefits of medicine’s best antidepressant drugs."

[Sen. Warner to unveil bill reining in Section 230, seeking to help users fight back against real-world harm](https://www.washingtonpost.com/technology/2021/02/05/senate-warner-section-230-reform/)  
These changes will have ripples across all of tech. "Sen. Ron Wyden (D-Ore.), one of the original law’s architects, said in a statement that the 'admirable goals' motivating the bill did not change the fact it threatened to 'devastate every part of the open internet, and cause massive collateral damage to online speech.'"

## Process

[Nvidia’s $40bn acquisition of Arm faces investigation](https://www.siliconrepublic.com/companies/nvidia-arm-acquisition-eu-investigation)  
We're just gonna pump the brakes on this one? "The EU is now set to join the UK in opening an in-depth competition investigation."

[How to detect the ExternalIP K8s vulnerability](https://snyk.io/blog/detect-externalip-kubernetes-vulnerability-with-snyk/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=snyk&utm_term=kubernetes&utm_content=204)  
Is your Kubernetes deployment at risk to the recently disclosed ExternalIP K8s vulnerability? Read this blog to learn how to scan your configuration files for this security issue and others. *SPONSORED*

[Google Cloud lost $5.6B in 2020](https://techcrunch.com/2021/02/02/google-cloud-lost-5-6b-in-2020/)  
"Google continues to bet heavily on Google Cloud, and, while it is seeing accelerated revenue growth, its losses are also increasing. For the first time today, Google disclosed operating income/loss for its Google Cloud business unit in its quarterly earnings today. Google Cloud lost $5.6 billion in Google’s fiscal year 2020, which ended December 31. That’s on $13 billion of revenue."

[Hildegard: New TeamTNT Cryptojacking Malware Targeting Kubernetes](https://unit42.paloaltonetworks.com/hildegard-malware-teamtnt/)  
"In January 2021, Unit 42 researchers detected a new malware campaign targeting Kubernetes clusters. The attackers gained initial access via a misconfigured kubelet that allowed anonymous access. Once getting a foothold into a Kubernetes cluster, the malware attempted to spread over as many containers as possible and eventually launched cryptojacking operations. Based on the tactics, techniques and procedures (TTP) that the attackers used, we believe this is a new campaign from TeamTNT. We refer to this new malware as Hildegard, the username of the tmate account that the malware used."

[Bad Pods: Kubernetes Pod Privilege Escalation](https://labs.bishopfox.com/tech-blog/bad-pods-kubernetes-pod-privilege-escalation)  
"I will describe eight insecure pod configurations and the corresponding methods to perform privilege escalation."

[A dedicated licence for open-source hardware: CERN OHL approved by OSI](https://www.theregister.com/2021/01/29/cern_ohl_approved/)  
"How do you license open-source hardware? Existing software licences will not do, says CERN"

## Tools

[Desk Setup, January 2021](https://chrisshort.net/desk-setup-january-2021/)  
I've been asked numerous times about the camera, mic, lighting, etc. in use when live streaming. I've written it all up for reference. Check it out, I'd love to hear suggestions or other tips to make the setup better (if you say Stream Deck, tell me why).

[Effective Feature Management](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)  
What if your team could safely ship software features faster? Gain a competitive advantage with Effective Feature Management: Releasing and Operating Software in the Age of Continuous Delivery by O'Reilly, written by LaunchDarkly CTO & Co-founder John Kodumal. So you can deploy when you want, release when you’re ready and enable valuable product innovation. Download your [free copy](https://learn.launchdarkly.com/effective-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) today! *SPONSORED*

[Exploring Kubernetes Operator Pattern](https://iximiuz.com/en/posts/kubernetes-operator-pattern/)  
"In this article, I'll try to take a closer look at the Operators pattern, see which Kubernetes parts are involved in operators implementation, and what makes operators feel like first-class Kubernetes citizens. Of course, with as many pictures as possible."

[Let’s compare the cloud shells offered by AWS, Microsoft Azure, and Google Cloud Platform](https://seroter.com/2021/02/03/lets-compare-the-cloud-shells-offered-by-aws-microsoft-azure-and-google-cloud-platform/)  
An analysis of the various cloud shells that are available from the three biggest cloud providers. I have to admit, Azure is growing on me A LOT lately.

[Quantum ‘Switchable’ Qubit Quickly Flips Between Storage and Fast Calculation Modes](https://thenewstack.io/quantum-switchable-qubit-quickly-flips-between-storage-and-fast-calculation-modes/)  
"Well switch my qubits!" That's what all the cool kids will be saying some day.

[How to unit-test your helm charts with Golang](https://blog.heyal.co.uk/unit-testing-helm-charts/)  
Next week someone will share how they re-wrote this in Rust.

[A visual guide on troubleshooting Kubernetes deployments](https://learnk8s.io/troubleshooting-deployments)  
learnk8s is a really great resource.

[The V Programming Language](https://vlang.io/)  
Anyone tinker with this one yet?

[Analyzing gRPC messages using Wireshark](https://grpc.io/blog/wireshark/)  
Never underestimate Wireshark's power.

[How Chromium reduced Root DNS traffic](https://blog.apnic.net/2021/02/04/how-chromium-reduces-root-dns-traffic/)  
"In August and September 2020, Verisign quantified that upwards of 45.80% of total DNS traffic to the root servers was, at the time, the result of Chromium intranet redirection detection tests. Since then, the Chromium team has redesigned its code to disable the redirection test on Android systems and introduced a multi-state DNS interception policy that supports disabling the redirection test for desktop browsers. This functionality was released mid-November of 2020 for Android systems in Chromium 87 and, quickly thereafter, the root servers experienced a rapid decline of DNS queries." Damn.

[Cloud Native Computing Foundation Announces Open Policy Agent Graduation](https://www.cncf.io/announcements/2021/02/04/cloud-native-computing-foundation-announces-open-policy-agent-graduation/)  
OPA!!! And Gatekeeper too.

## DevOps'ish Tweet of the Week

[![reminder - 'i like to make money' is a good enough reason to want to be paid fairly. — jill wohlner (@JillWohlner) February 3, 2021](/images/204-devopsish-tweet-of-the-week.png)](https://twitter.com/JillWohlner/status/1357082152094040064)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/204/notes/) to see what didn't make it to the newsletter.
