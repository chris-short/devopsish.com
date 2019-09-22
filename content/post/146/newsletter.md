+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2019-09-22T14:00:00Z
description = "We're going to need a bigger boat for this week's newsletter. From Anthos to Chef to Seth to words with Z in them there's something for everyone!"
draft = false
slug = "146"
tags = ["DevOps", "Kubernetes", "cloud", "open source", "cloud native", "weekly newsletter", "DevOps news", "Kubernetes news", "Seth Vargo", "Chef", "Google Anthos", "VMware Project Pacific", "linux", "kernel", "AWS", "Linus Torvalds", "Richard Stallman"]
title = "146: Seth Vargo says hell no—puts Chef on ICE, Kubernetes 1.16, Linus Torvalds on kernel development, fluffy clouds, DevOps terms, and more"

+++

Just when you thought a toxic, old, white guy with lousy hygiene was going to dominate the news this week, in walks [Seth Vargo](https://twitter.com/sethvargo). On Thursday, Seth Vargo, a former Chef employee, learned something he wasn't comfortable with about code he'd written. Seth discovered Chef had an active contract with the US Department of Homeland Security's Immigration and Customs Enforcement. Seth then did something rather extraordinary. He yanked his code (including [chef-sugar](https://github.com/sethvargo/chef-sugar)) from GitHub and RubyGems. This resulted in many production systems going offline across the globe. We could see some metrics about impact in a lawsuit at some point. When DM'ing Seth early Friday AM he told me, "It's almost certain that Chef is going to sue." [Read More →](https://chrisshort.net/seth-vargo-says-hell-noputs-chef-on-ice/)

## DevOps'ish Last Week's Top Five

1. [Remove Richard Stallman](https://medium.com/@selamie/remove-richard-stallman-fec6ec210794)
1. [My top 25 items in a senior engineer's checklist](https://medium.com/@littleblah/my-top-25-items-in-a-senior-engineers-checklist-c8e9f9f6e3c2)
1. [8 Things Leaders Do That Make Employees Quit](https://hbr.org/2019/09/8-things-leaders-do-that-make-employees-quit)
1. [17 Reasons NOT To Be A Manager](https://charity.wtf/2019/09/08/reasons-not-to-be-a-manager/)
1. [If you're not using SSH certificates you're doing SSH wrong](https://smallstep.com/blog/use-ssh-certificates/)

* [Alert Automation for your Cloud Infrastructure](https://www.bluematador.com/devopsish) *SPONSORED*

[See the top ten →](https://devopsish.com/146/notes/)

## Events

Event season is upon us but the good news is DevOps'ish has discounts to some of the hottest events this year.

[**PagerDuty Summit 2019**](https://summit.pagerduty.com/) is Sept 23-25 in San Francisco. It's three days of interactive workshops, keynotes, and breakouts with topics focusing on cutting edge incident response techniques, resilience engineering, managing team health, continuous improvement, DevSecOps, machine learning, and other intersections with real-time operations. Join experts from Google, Microsoft, Hashicorp, Twilio, Salesforce, Gremlin, Honeycomb, Adobe, AWS, and more. [Register](https://summit.pagerduty.com/summit2019/register?c_280637=PDS19OT) with code *PDS19DOISH* to save 50% and attend for $350. *SPONSORED*

[**KubeCon + CloudNativeCon North America 2019**](https://cshort.co/kcna19)  
The Cloud Native Computing Foundation's flagship conference gathers adopters and technologists from leading open source and cloud native communities in San Diego, California from November 18-21, 2019. Join Kubernetes, Prometheus, Envoy, CoreDNS, containerd, Fluentd, OpenTracing, gRPC, CNI, Jaeger, Notary, TUF, Vitess, NATS, Linkerd, Helm, Rook, Harbor, etcd, Open Policy Agent, CRI-O, and TiKV as the community gathers for four days to further the education and advancement of cloud native computing. Use code *KCNACSN10* at checkout for a 10% discount on Corporate Registration.

[See more Events →](https://devopsish.com/146/events/)

## People

[Tech Animals](http://www.git-tower.com/blog/tech-animals) - A side project for a good cause. fournova Software reached out to me directly about an effort they put together to support [Hacker School](https://www.betterplace.org/en/projects/58054-hacker-school-inspire-young-people-for-coding-and-integrate-refugees). I love it! Check it out and let me know what you get (I ordered the Linux mug and am pondering more)!

[The real cost of not wearing makeup at the office](https://www.fastcompany.com/90400807/the-real-cost-of-not-wearing-makeup-at-the-office) — If you're a dude, you need to read this. "I spend 15 times more than my husband when it comes to personal grooming. But finance experts don’t often talk about the professional cost of opting out."

[Richard Stallman and the Fall of the Clueless Nerd](https://www.wired.com/story/richard-stallman-and-the-fall-of-the-clueless-nerd/) — Time's up!

[Open letter to the Free Software Foundation Board of Directors](https://www.redhat.com/en/blog/open-letter-free-software-foundation-board-directors)

[Linus Torvalds on the kernel development community](https://lwn.net/SubscriberLink/799219/cfc5362a1bf6bc5a/) — Some pretty interesting nuggets in here. "Torvalds responded that he doesn't even check for presence in linux-next early in the merge window; he is happy enough to get an early pull request that nothing more is required. As the merge window approaches its end, though, he does start checking, and absence from linux-next (earlier in the merge window) can result in pull requests not being acted upon."

[On the occasion of leaving Google](https://medium.com/@Irenes/on-the-occasion-of-leaving-google-b8c7029c8d8b) — "This isn’t really a 'why I’m leaving' post. You all know many of the reasons, and I do believe retaliation occurred. This is a 'what you should do about it' post."

[A Black Engineer’s Perspective on Why Diversity Matters in Tech](https://peopleofcolorintech.com/interview/a-black-engineers-perspective-on-why-diversity-matters-in-tech/)

[How I passed my CKAD with 97%](https://medium.com/@kgamanji/how-i-passed-my-ckad-with-97-6b54dcffa72f) — Some useful nuggets for Certified Kubernetes Application Developer test takers.

## Process

[Chef roasted for tech contract with family-separating US immigration, forks up attempt to quash protest](https://www.theregister.co.uk/2019/09/20/chef_roasted_for_ice_dealings/) — "Software house hits nuclear option after Ruby Gems yanked for moral reasons"

[WeWTF, Part Deux](https://www.profgalloway.com/wewtf-part-deux) — The WeWork shit show must go on!

[How ConvertKit Could Lower Its $64K Monthly AWS Bill](https://www.lastweekinaws.com/blog/how-convertkit-could-lower-its-64k-monthly-aws-bill/) — ConvertKit released a post about their AWS bill. Cloud economist, Corey Quinn, analyzes how ConvertKit could cut $64,000 a month from their AWS bill.

[Software Architecture is Overrated, Clear and Simple Design is Underrated](https://blog.pragmaticengineer.com/software-architecture-is-overrated/) — What's wrong with software architecture patterns? "I see them similarly in usefulness as coding design patterns. They can give you ideas on how to improve your code or architecture... I spent a lot of time reading and comprehending the Gang of four design patterns, they've had far less impact on becoming a better coder than the feedback I've gotten from other engineers on my code."

[DevOps terms: 10 advanced concepts to know](https://enterprisersproject.com/article/2019/9/devops-terms-10-advanced) — "Are you moving farther down the path with DevOps and tripping on the lingo? Experts explain key DevOps terms and phrases that teams should understand"

[Kubernetes’ next step could be to try orchestrating everything else](https://www.zdnet.com/article/kubernetes-next-step-could-be-to-try-orchestrating-everything-else/) — We already see this with OpenShift, Project Pacific, and Google Anthos. The concepts of Kubernetes as the control plane for damn near everything will eventually feed back into vanilla Kubernetes in due time. Keep in mind, spinning up a small Kubernetes cluster to provision and install a larger cluster is a common Kubernetes pattern.

[The New Target That Enables Ransomware Hackers to Paralyze Dozens of Towns and Businesses at Once](https://www.propublica.org/article/the-new-target-that-enables-ransomware-hackers-to-paralyze-dozens-of-towns-and-businesses-at-once) — If you utilize or operate a managed service provider, you're on the front lines of a cybersecurity hellscape right now.

## Tools

[**Full Alerting Coverage Without the Toil**](https://www.bluematador.com/devopsish)  
Balance rapid feature development and production stability with alert automation for your cloud infrastructure from Blue Matador. Activate alert automation in your cloud infrastructure today with our free trial. *SPONSORED*

[Kubernetes 1.16: Custom Resources, Overhauled Metrics, and Volume Extensions](https://kubernetes.io/blog/2019/09/18/kubernetes-1-16-release-announcement/) — I hope y'all are ready for the CRD tsunami because here it comes! Thank you so much to the 1.16 release team! Y'all did a really amazing job.

[Deprecated APIs Removed In 1.16: Here’s What You Need To Know](https://kubernetes.io/blog/2019/07/18/api-deprecations-in-1-16/) — Instead of `NetworkPolicy` use `networking.k8s.io/v1`. `PodSecurityPolicy` is now in `policy/v1beta1`. `DaemonSet`, `Deployment`, `StatefulSet`, and `ReplicaSet` are now part of `apps/v1`. `Ingress` is moving to `networking.k8s.io/v1beta1` in Kubernetes 1.20, which should be released this time next year.

[30 Linux Permissions Exercises for Sysadmins](https://devconnected.com/30-linux-permissions-exercises-for-sysadmins/) — Need a run-through on Linux perms? Here ya go!

[OpenShift 4.2 Disconnected Install](https://blog.openshift.com/openshift-4-2-disconnected-install/) — Install OpenShift in a restricted environment with limited access to the Internet.

[What to Know About VMware’s Project Pacific](https://thenewstack.io/5-things-to-know-about-vmwares-project-pacific/) — It's a single control plane for everything from VMs to Kubernetes clusters to pods (yes, pods). Kubernetes Scheduler and Kubelet have been replaced by a Supervisor Cluster and Spherelet ("a proprietary version of Kubelet"). A concept called Native Pods is a thing to be aware of. Oh and [Photon OS](https://vmware.github.io/photon/). Analysis: This is a lot. VMware is going to have to get implemented and scaled up quickly. If VMware wants to gather a greater than 10% share of the container orchestration market, speedy execution is key.

[What’s Going on with GKE and Anthos?](https://bravenewgeek.com/whats-going-on-with-gke-and-anthos/) — Google Anthos is a little bit of an oddity at the moment. Yes, Google Cloud admits it has an enterprise problem to an extent. Using the Google Cloud UI is smart as it keeps customer experience consistent and codebases to a minimum. But, while Google Anthos helps Google Cloud's enterprise problem, it isn't a lot of actual stuff you can kick the tires on. Their configuration management tool is a git repo with a Kubernetes Operator watching for changes (which is fine). Their control plane is GKE which is also fine. But, the marketing around Google Anthos feels more like a pitch for Site Reliability Engineering as a business model. This is okay too. But, keep in mind, in [DevOps README.md](https://github.com/chris-short/DevOps-README.md) (back in 2017) I call out Google SRE as, "proof setting a pile of money on fire is a viable solution to engineering problems." I'm wondering how many people will buy Google Anthos and end up with large consulting contracts as a result.

[containers/podman-compose](https://github.com/containers/podman-compose) — A script to run docker-compose.yml using podman

[Python 2 End of Life Announced as January 1st 2020](https://www.infoq.com/news/2019/09/python-2-end-of-life-approaching/) — Python 2's end of life is nigh.

[dylanaraps/pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible) — 📖 A collection of pure bash alternatives to external processes

[How Intel's Clear Linux Team Cut The Kernel Boot Time From 3 Seconds To 300 ms](https://www.phoronix.com/scan.php?page=news_item&px=Clear-Linux-Kernel-3s-to-300ms) — "Intel engineer Feng Tang spoke at this week's Linux Plumbers Conference in Lisbon, Portugal on how the Clear Linux team managed to boot their kernel faster. They started out with around a three second kernel boot time but cut it down to just 300 ms."

[deajan/osync](https://github.com/deajan/osync) — A robust two way (bidirectional) file sync script based on rsync with fault tolerance, POSIX ACL support, time control and near realtime sync

[Highly Effective Kubernetes Deployments with GitOps](https://medium.com/@timfpark/highly-effective-kubernetes-deployments-with-gitops-c7a0354f1446) — "In a GitOps based deployment, a pod running in the cluster watches a specific git repo that contains the set of resource manifests that should be running in the cluster."

[IBM will soon launch a 53-qubit quantum computer](https://techcrunch.com/2019/09/18/ibm-will-soon-launch-a-53-qubit-quantum-computer/) — I think it looks like a bong personally. But, after talking to a few folks at IBM, I am really impressed with the strides being made in this space. Also, I bought [quantumbongs.com](http://quantumbongs.com/) in case that takes off.

## DevOps'ish Tweet of the Week

{{< tweet 1174116297468252160 >}}

[See Notes →](https://devopsish.com/146/notes/)
