+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-08-22T07:00:00Z
description = ["Kubernetes 1.22 release team livestream, problems in Perl, glibc, eBPF, Pod Security Admission, secure supply chains, tools galore, and more"]
draft = false
slug = "231"
tags = ["Kubernetes", "clusters", "security", "cloud native", "cloud", "release", "email", "hardening", "IoT", "eBPF", "Docker", "process", "Postman", "GitOps", "Linux", "pod", "CNCF", "Perl", "T-Mobile", "livestream", "Sackler family", "opioid", "glibc", "patterns", "confusing", "open source", "Google", "community", "incident management", "CIS Benchmark", "NSA", "supply chain", "DC/OS", "automate", "Red Hat", "AWS", "Samsung"]
title = "DevOps'ish 231: Kubernetes 1.22 release team livestream, problems in Perl, glibc, eBPF, Pod Security Admission, secure supply chains, tools galore, and more"

+++

My military service and tech worlds collided this week. I can't say much about it yet but, I've been insanely busy with an array of things I never thought I'd need to do. More to come later. Join the [DevOps'ish subreddit](https://www.reddit.com/r/devopsish/) and talk about how bad the intro was. Our how dope the [notes page](https://devopsish.com/231/notes/) is for this issue.

## People

[Cloud Tech Tuesdays: Kubernetes 1.22](https://www.youtube.com/watch?v=wKbe0T2E0QQ&utm_source=newsletter&utm_campaign=231&utm_id=devopsish)  
Josh Berkus, Amy Marrich, and I sat down for a livestream with Savitha Raghunathan, James Laverack, Jesse Butler, and Guinevere Saenger to discuss all things Kubernetes and the Kubernetes 1.22 release.

[Free eBook: Docker Security Essentials by HackerSploit](https://www.linode.com/content/hackersploit-docker-security-essentials-ebook/?utm_source=devopsish&utm_medium=newsletter_sponsorship&utm_campaign=newsletter_sponsorship-devopsish-security&utm_content=ebook-docker_security&utm_term=)  
Docker is a popular platform to quickly create, deploy and host web applications, databases and other business critical solutions. Learn how to audit and secure Docker in this comprehensive guide and 9-part video series. Download instantly -- no registration required. *SPONSORED*

[Samsung’s leader is out of jail, allowing US factory plans to move forward](https://arstechnica.com/gadgets/2021/08/samsung-leader-jay-y-lee-released-from-prison-on-parole/)  
"Samsung heir served 18 months in prison for capital flight and perjury." Can someone that's got a great understanding of Korean business and politics please reply to this email. I have no idea how this works and I want to understand it before I label it anything.

[The Perl Foundation is fragmenting over Code of Conduct enforcement](https://arstechnica.com/gadgets/2021/08/the-perl-foundation-is-fragmenting-over-code-of-conduct-enforcement/)  
It wasn't that long ago that I learned there's a lot more Perl out there than most folks realize. I wonder how sustainable that is NOW.

[T-Mobile apparently lied to government to get Sprint merger approval, ruling says](https://arstechnica.com/tech-policy/2021/08/t-mobile-apparently-lied-to-government-to-get-sprint-merger-approval-ruling-says/)  
This regulatory ruling stacked on top of multiple data breaches... T-Mobile needs a hard shaking it sounds like.

[Sacklers say they won’t pay $4.5B settlement if judge rejects immunity deal](https://arstechnica.com/tech-policy/2021/08/sacklers-say-they-wont-pay-4-5b-settlement-if-judge-rejects-immunity-deal/)  
This is what happens to billionaires in the US. The Sacklers products reached so far and wide that the second-largest US administration regularly prescribed medications like morphine and fentanyl to its patients (leading to countless overdoses). It is utterly enraging for me. I'm a lucky survivor of the Sacklers' opioid epidemic. Now I also deal with a rather undue process because I need an opioid to control pain from nerve damage. It's a double slap in the face for those trying to live their lives with pain.

## Process

[API platform Postman valued at $5.6 billion in $225 million fundraise](https://techcrunch.com/2021/08/18/api-platform-postman-valued-at-5-6-billion-in-225-million-fundraise/)  
I like Postman. I occasionally use the tool for complex `curl` commands. But, I've got to say, I have no idea how Postman is valued at $5.6 billion. They've added a lot of integrations with common APIs. But, I am starting to think the bubble is real.

[Infrastructure as Code Automation for Terrafrom and GitOps workflows](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter)  
See how env0 automates and simplifies the provisioning of cloud deployments for Terraform. We offer Variables and Secrets granularity, Full CLI support, integration with OPA, Dynamic RBAC and SAML. [Get Started for FREE!](https://www.env0.com/infrastructure-as-code-automation?utm_campaign=devopsish&utm_source=nativeads&utm_medium=newsletter) *SPONSORED*

[Linux glibc security fix created a nastier Linux bug](https://www.zdnet.com/article/linux-glibc-security-fix-created-a-nastier-linux-bug/)  
"Sometimes a programming cure is worse than the disease. That's the case with this Linux glibc security bug." How one CVE's fix lead to another CVE.

[Patterns in confusing explanations](https://jvns.ca/blog/confusing-explanations/)  
"So why do I find all these explanations so confusing? I decided to try and find out! I came up with a list of 12 patterns that make explanations hard for me to understand. For each pattern I’ll also explain what I like to do instead to avoid the issue." This is GREAT reference material for when you're writing docs, guides, READMEs, etc. My personal pet peeve is "[no examples](https://jvns.ca/blog/confusing-explanations/#pattern-11-no-examples)."

[The Absolute minimum every developer must know about AWS security!](https://blog.cloudyali.io/absolute-minimum-every-developer-must-know-about-aws-security)  
Again, not all encompassing but, some decent recommendations and tooling are in this article. Remember, continuous security, always. You're never done improving security just like you're never done learning.

[Email Authenticity 101: DKIM, DMARC, and SPF](https://www.alexblackie.com/articles/email-authenticity-dkim-spf-dmarc/)  
Want to know why email is so hard these days? This article details why. If you don't nail these three things, your email is bound for a spam folder.

[Afghans are being evacuated via WhatsApp, Google Forms, or by any means possible](https://www.technologyreview.com/2021/08/17/1032127/afghanistan-kabul-evacuation-whatsapp-google-forms-security/)  
It's complete chaos. There is a process. But, it's burdensome and is likely limiting the number of people able to get out of the country.

## Tools

[StackRox Community Office Hours (E2): eBPF 101 — Implementing Security & Monitoring Kubernetes](https://www.youtube.com/watch?v=u8EzEC4vC2k&utm_source=newsletter&utm_campaign=231&utm_id=devopsish)  
Robby Cochran and I sat down for a livestream about [**eBPF**](https://ebpf.io/). If you haven't wrapped your head around eBPF yet, this is a great way to get started.

[Making Your On-call and Incident Management Program Stick](https://rootly.io/blog/making-your-on-call-and-incident-management-program-stick?utm_source=newsletter&utm_medium=email&utm_campaign=231&utm_id=devopsish)  
Maintenance of your incident management practice is as important as creation - find out what you can do to keep your engineering organization strong and consistent year over year. *SPONSORED*

[Hands on with Kubernetes Pod Security Admission](https://medium.com/@LachlanEvenson/hands-on-with-kubernetes-pod-security-admission-b6cac495cd11)  
I'll break my [No Medium](https://nomedium.dev/) rule for Lachlan. "Kubernetes v1.22 provides an alpha release for the successor of [Pod Security Policy (PSP)](https://kubernetes.io/docs/concepts/policy/pod-security-policy/) (which is scheduled for deprecation in v1.25). This new enhancement is called [Pod Security Admission (PSA)](https://kubernetes.io/docs/concepts/security/pod-security-admission/). I’ve taken an initial look at PSA and will cover what you need to know about how it works and how you can start playing with it. This will not be a deep dive into the architecture or reasoning behind the implementation. If you want to learn more about that you can find details in the [Kubernetes Enhancement Proposal (KEP)](https://github.com/kubernetes/enhancements/blob/master/keps/sig-auth/2579-psp-replacement/README.md)."

[Forthcoming OpenSSL release](https://mta.openssl.org/pipermail/openssl-announce/2021-August/000205.html)  
"OpenSSL 1.1.1l is a security-fix release. The highest severity issue fixed in this release is [HIGH](https://www.openssl.org/policies/secpolicy.html#high)." Keep an eye on this one, folks.

[Top 10 Kubernetes Application Security Hardening Techniques](https://blog.aquasec.com/kubernetes-hardening-techniques)  
A good overview of some of the security configurations available to you with Kubernetes. This should not be seen as an all encompassing hardening guide though. Use the [CIS Benchmark](https://www.cisecurity.org/benchmark/kubernetes/), [NSA Kubernetes Hardening Guide](https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/), or whatever framework your industry is required to use. If your industry isn't regulated, I'd recommend implementing the CIS Benchmark if you haven't yet (and if you haven't hardened your clusters yet, I'll probably see you in a headline in this newsletter soon).

[Software Supply Chain Best Practices from CNCF TAG Security](https://project.linuxfoundation.org/hubfs/CNCF_SSCP_v1.pdf)  
Speaking of hardening, here are CNCF TAG Security's supply chain recommendations. Build great pipelines, y'all.

[Wildcard LetsEncrypt certificates with Traefik and Cloudflare](https://major.io/2021/08/16/wildcard-letsencrypt-certificates-traefik-cloudflare/)  
There's some really great guides on using [Let's Encrypt](https://letsencrypt.org/) with X and Z out there. Add this one to the list. Nice work, Major.

[Pi calculated to '62.8 trillion digits' with a pair of 32-core AMD Epyc chips, 1TB RAM, 510TB disk space](https://www.theregister.com/2021/08/17/pi_world_record_challenged/)  
That's A LOT of hardware and a lot of digits. The disk array was an interesting design too.

[What domain name to use for your home network](https://www.ctrl.blog/entry/homenet-domain-name.html)  
This was a widely popular article this week. I've switched our home network over to `home.arpa` to see how this works. But, I have to say, I've not seen any significant problems. [YMMV](https://www.acronymfinder.com/Your-Mileage-May-Vary-(YMMV).html)

[How to automatically accept or disable browser cookies notice on any site](https://www.hackread.com/how-to-accept-disable-browser-cookies-notice/)  
Cookie warnings have gotten completely out of control. This GDPR induced UX disaster has a solution or three though.

[Add DC/OS End of Life message by jongiddy](https://github.com/dcos/dcos/pull/7886)  
Put a fork in DC/OS. It's done.

[kubealex/libvirt-ocp4-provisioner](https://github.com/kubealex/libvirt-ocp4-provisioner)  
"Automate your OCP4 installation" This could change the way I deploy my OpenShift clusters in the future. I wish I had more time to help refine projects like this.

[dailymotion-oss/octopilot](https://github.com/dailymotion-oss/octopilot)  
"Automate your Gitops workflow, by automatically creating/merging GitHub Pull Requests"

[iovisor/kubectl-trace](https://github.com/iovisor/kubectl-trace)  
"Schedule bpftrace programs on your kubernetes cluster using the kubectl"

[armosec/kubescape](https://github.com/armosec/kubescape)  
"kubescape is the first tool for testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by to NSA and CISA (<https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/>)"

[homeport/havener: /ˈheɪvənə/](https://github.com/homeport/havener)  
"Think of it as a swiss army knife for Kubernetes tasks"

[kubernetes-sigs/sig-windows-dev-tools](https://github.com/kubernetes-sigs/sig-windows-dev-tools/)  
"This is a batteries included local development environment for Kubernetes on Windows."

[praetorian-inc/gokart](https://github.com/praetorian-inc/gokart)  
"A static analysis tool for securing Go code"

## DevOps'ish Tweet of the Week

[![Alex Cohen (@anothercohen) on Twitter: "Congrats on your $2m seed round. Your small team now only has 3 months of runway after paying for..."](https://shortcdn.com/file/devopsish/231-devopsish-tweet-of-the-week.png)](https://twitter.com/anothercohen/status/1427753293900500997)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/231/notes/) to see what didn't make it to the newsletter but are still worth your time.
