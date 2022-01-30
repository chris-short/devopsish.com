+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2022"]
date = 2022-01-30T03:30:00Z
description = ["Mired in many migrations, No Substack, Kubernetes security, Nvidia's Arm deal is really dead, big Kubernetes cluster, systemd playground, and more"]
draft = false
slug = "254"
tags = ["Kubernetes", "Google", "Docker", "Apple", "macOS", "Kubernetes clusters", "GSuite", "security", "policy", "podman", "validation", "systemd", "remote", "Fedora", "minikube", "open source", "Honeycomb", "AWS", "service discovery", "DNS"]
title = "DevOps'ish 254: Mired in many migrations, No Substack, Kubernetes security, Nvidia's Arm deal is really dead, big Kubernetes cluster, systemd playground, and more"

+++

DevOps'ish is brought to you by [**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup).  
"Stop Letting Complexity Slow You Down"  
[**Honeycomb**](https://ui.honeycomb.io/signup?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup) makes it easy to understand and troubleshoot complex relationships within your distributed services. Solve problems faster. Ship reliable and performant features. *SPONSORED*

I mentioned [on Twitter](https://twitter.com/ChrisShort/status/1486725424939888648) this week that I have multiple migrations going on right now. The first and easiest migration is already done. I even wrote a blog post about it: [Moving off Spotify](https://chrisshort.net/moving-off-spotify/).

The next migration is moving off GSuite or Google Workplace or whatever it’s called. That one is technically 50% done as far as the two GSuite accounts I have. I migrated one over to Apple+. The Apple tooling is rigid and unforgiving. It will likely instruct you to make a bad SPF record if you send mail using more than one tool. I intend to write a blog post about it during the coming weeks. The funny thing about it is that I moved the Google account I was already paying for. Now I have to move the one with the data gravity, but I have until July to do that. I am lucky and maintain a firm policy not to sign in with a Google account unless I am forced. But, to be honest, not moving, taking the easy path, even if it costs money, is likely the path I’ll take for the legacy free account. I’ll only pay for ONE Google account, though.

Finally, the quest for new container tooling begins in earnest, with Docker Desktop becoming a paid product soon. The `docker` cli tool is a native option on macOS but, I hate Docker and am not going to give them life. My replacement is using VScode remote environments to a Fedora box in my office where `podman` is installed. Both devices are on my VPN, so I can access them from anywhere in the world. If push comes to shove, I can always use `minikube` locally (it has grown on me lately). I’ve also used the minikube SSH driver to spin up remote clusters here in the house. It’s a question that doesn’t have as direct an answer as I want right now. I wish `podman` ran better on macOS. But you pretty much have to run Fedora to get the best out of `podman` right now. I’m aware of the Suse/Rancher thing but, I’m not ***THAT*** desperate.

## People

[Should you learn Docker before learning Kubernetes?](https://www.youtube.com/watch?v=PT2Iu1JkVOI)  
It's cool to see other people's opinions. Obviously, my experiences are way different. I did learn containers in depth well after learning Kubernetes. Clearly your experience will be different. I would say your Docker knowledge matters less and less the deeper you go into the sharp edges (kinda like git too). As long as you have a build tool you're happy with, that's what matters. Remember, we're all standing on common ground, so "[no feigning surprise](https://jvns.ca/blog/2017/04/27/no-feigning-surprise/)" and help each other.

[Newsletter company Substack profits off misinformation](https://www.washingtonpost.com/technology/2022/01/27/substack-misinformation-anti-vaccine/)  
Looks like I'll be doing something with [nosubstack.com](http://nosubstack.com) sometime soon. Good lord, these misinformation campaigns.

[Joe Biden Formally Backs Consumers' Right to Repair Their Electronics](https://www.vice.com/en/article/qjbzpw/joe-biden-formally-backs-right-to-repair)  
Good. This could be the single issue I vote on next year. You can't sell me something and then sue me for modifying something I own.

[A white supremacist website got hacked, airing all its dirty laundry](https://arstechnica.com/information-technology/2022/01/data-leak-from-neo-nazi-site-shows-members-conspiring-in-hate-crimes/)  
"Friday’s published report said that the leak comprised about 400GB of data and came from a self-hosted instance of RocketChat, an open source chat server that’s similar to Slack and Discord. It’s only the latest example of a hate group being hacked and its private discussions being dumped online."

[Aha! Moments Pop Up from below the Level of Conscious Awareness](https://www.scientificamerican.com/article/aha-moments-pop-up-from-below-the-level-of-conscious-awareness/)  
The human mind is so fascinating.

## Process

[Apple Releases Security Updates for Multiple Products](https://www.cisa.gov/uscert/ncas/current-activity/2022/01/27/apple-releases-security-updates-multiple-products)  
You know it's bad when CISA says something about Apple TVs. But, seriously, upgrade your stuff sooner rather than later.

[2022.01.25 Issue with TLS-ALPN-01 Validation Method - Incidents - Let's Encrypt Community Support](https://community.letsencrypt.org/t/2022-01-25-issue-with-tls-alpn-01-validation-method/170450)  
"A third party informed Let’s Encrypt / ISRG that, while examining the Boulder codebase, they had noticed two instances of specification non-compliance in our implementation of the “TLS Using ALPN” validation method (BRs 3.2.2.4.20, RFC 8737). As a result, we have made two changes 1.2k to the way that our TLS-ALPN-01 challenge validation works." More to come on this one; should be interesting.

[Incorrect proxying of 24 hostnames on January 24, 2022](https://blog.cloudflare.com/incorrect-proxying-of-24-hostnames-on-january-24-2022/)  
"This event exposed previously unknown gaps in our process and technology that directly impacted our customers." Humbling.

[Kubernetes cluster security assessment with kube-bench and kube-hunter](https://blog.flant.com/kubernetes-security-with-kube-bench-and-kube-hunter/)  
How to use two powerful tools to assess your Kubernetes clusters' security posture.

[Google relents: Legacy G Suite users will be able to migrate to free accounts](https://arstechnica.com/gadgets/2022/01/google-relents-legacy-g-suite-users-will-be-able-to-migrate-to-free-accounts/)  
If you have a free GSuite account from back in the day, it's not going to be free much longer. Of the two Google domains I have, I migrated one over to Apple. The other is the free GSuite account I've had for over a decade. That's a lot of data that has to get moved. I can stomach paying for one Google account (not two). But, I should probably de-Google my life even if that means I'm going all in on Apple.

[Nvidia's Arm Acquisition Expected to Fail, Nvidia Would Lose $1.25B Deposit](https://www.tomshardware.com/news/nvidia-arm-acquisition-expected-to-fail-nvidia-loses-dollar125b-deposit-report)  
This is an expensive lesson learned.

## Tools

[Two reasons Kubernetes is so complex](https://buttondown.email/nelhage/archive/two-reasons-kubernetes-is-so-complex/)  
Kubernetes is a cluster operating system. Everything in Kubernetes is a control loop. Some finer points: “Errors are delayed,” “all configuration is declarative,” and “how pluggable and configurable Kubernetes is.”

[Introducing AWS Cloud Map MCS Controller for K8s | AWS Open Source Blog](https://aws.amazon.com/blogs/opensource/introducing-the-aws-cloud-map-multicluster-service-controller-for-k8s-for-kubernetes-multicluster-service-discovery/)  
"It allows a Kubernetes-native service discovery capability that works across Kubernetes (K8s) clusters. Multicluster service discovery allows applications to understand what services exist in an environment so that they can discover and communicate with each other, even when applications are deployed across several Kubernetes clusters. It simplifies building and operating services that run across multiple Kubernetes clusters."

[Scaling Kubernetes to Over 4k Nodes and 200k Pods](https://medium.com/paypal-tech/scaling-kubernetes-to-over-4k-nodes-and-200k-pods-29988fad6ed)  
I like big clusters and I cannot lie. But, this cluster is REALLY big. There are a lot of optimizations you have to make along the way to making a cluster this big.

[Kubernetes Vault Integration via Sidecar Agent Injector vs. CSI Provider](https://www.hashicorp.com/blog/kubernetes-vault-integration-via-sidecar-agent-injector-vs-csi-provider)  
Both are viable ways to provide secrets to your apps. But, one method might be more beneficial given the circumstances.

[Cracking Kubernetes Network Policy](http://arthurchiao.art/blog/cracking-k8s-network-policy/)  
"This post digs into the Kubernetes NetworkPolicy model, then designs a policy enforcer based on the technical requirements and further implements it with less than 100 lines of eBPF code. Hope that after reading through this post, readers will get a deeper understanding on how network policies are enforced in the underlying."

[Running macOS inside Linux with Docker-OSX](https://gombosg.com/2022/01/running-macos-inside-linux/)  
"Trying this experiment really shows how advanced our current virtualization technology is and allows you to use macOS for legitimate use cases like security research inside a secure virtual machine."

[systemd by example - the systemd playground](https://systemd-by-example.com/)  
Break someone else's `systemd` and not your own.

[life of a DNS query](https://wizardzines.com/comics/life-of-a-dns-query/)  
Another great Julia Evans zine on DNS.

[Flatpak App of the Week: Extension Manager - Browse and Install GNOME Shell Extensions](https://9to5linux.com/flatpak-app-of-the-week-extension-manager-browse-and-install-gnome-shell-extensions)  
I'm installing this tomorrow.

[appvia/cosign-keyless-admission-webhook](https://github.com/appvia/cosign-keyless-admission-webhook)  
Kubernetes admission webhook that uses cosign verify to check the subject and issuer of the image matches what you expect

## DevOps'ish Tweet of the Week

[![jill wohlner (@JillWohlner on Twitter) "Okay, but actually starting your career remote _does_ sound difficult to me (and I say this having worked remotely for like 6 years). I'm not saying it's not doable, but I am saying that it sounds hard!"](https://devopsish.com/images/254-devopsish-tweet-of-the-week.webp)](https://twitter.com/JillWohlner/status/1486370807009873924)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/254/notes/) to see what didn't make it to the newsletter but are still worth your time.
