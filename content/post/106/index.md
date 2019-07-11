+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-12-16T00:07:00Z
description = "KubeKhan, KubeCon, AWS Container Roadmap, etcd, More Weird Licenses, Securing Kubernetes, JFrog Go Registry, and More!"
draft = false
slug = "106"
tags = ["weekly", "devops", "newsletter", "cloud native", "cloud", "open source", "kubernetes", "automation", "red hat", "ansible", "security", "serverless", "container", "AWS", "licenses"]
title = "106: KubeKhan, KubeCon, AWS Container Roadmap, etcd, More Weird Licenses, Securing Kubernetes, JFrog Go Registry, and More!"
image = "/106/kubekhan.jpg"
imagealt = "Various pictures taken by Chris Short during KubeCon + CloudNativeCon NA 2018"
imagecap = ""

+++

These are some highlights from an e-mail I sent to my colleagues in my business unit titled, "KubeCon + CloudNativeCon NA 2018 Recap"

"I attended KubeCon + CloudNativeCon NA 2018 in Seattle this week. Full disclosure, I was there Sunday through Wednesday morning then flew to RDU for meetings. I made the most of being there. I wore four hats this trip: Ansible PMM, OpenShift Advocate, opensource.com Community Moderator, and CNCF Ambassador."

"Kubernetes is everything and everything is Kubernetes: This goes without saying at KubeCon but, there were 8,000 attendees in Seattle (more online) and next year in San Diego there is capacity for 12,000+. I'd estimate around 11-12K attendees next year. The growth here is huge."

"Quite a few products use Ansible to get themselves to Kubernetes..."

"The community thinks very big but, the engineers don't always have enterprise experience. Supporting something they built for tens of thousands of people is foreign to a lot of the folks in the community. This is balanced by a cadre of incredibly experienced folks from Google, IBM, VMware, Huawei, Red Hat, etc. I talked to a junior engineer from eastern Europe during a mentoring session on Wednesday morning. He was very interested in how Red Hat tackled feature development as well as IBM acquisition questions. He was a little shocked to find that customers had influence over feature development. I understand that's somewhat anecdotal but, there was a general feeling the community was a little greener than previous years. This is great for Kubernetes and CNCF."

I'll have more later in the week about KubeCon + CloudNativeCon NA 2018 (aka KubeKhan) over on [chrisshort.net](https://chrisshort.net/). I wanted to have that done prior to the newsletter going out. But, that wasn't in the cards. Technically I'm on PTO this week but, I'll be in Durham Wednesday evening through Friday morning. At least all of Red Hat is shut down the week after this one.

[**Continuous delivery on modern infrastructure - Run GoCD on Kubernetes**](https://www.gocd.org/kubernetes)  
Model Docker-based build workflows more effectively with our GoCD Kubernetes integration. Run GoCD natively on Kubernetes, define your build workflow and let GoCD provision and scale build infrastructure on the fly. *SPONSORED*

[**eBook: DevOps Roadmap for Security**](https://info.signalsciences.com/devops-security-roadmap?utm_medium=newsletter&utm_source=devopsish)  
The DevOps Roadmap for Security eBook: Tips and tools for bridging the security tribe into DevOps. Download today. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*

{{< sponsor-blurb >}}

## People

[Ashley McNamara created a Patreon](https://www.patreon.com/ashleymcnamara) (finally) — Y'all know what to do.

[On Leading Engineering Teams](https://medium.com/@simonyoung_uk/on-leading-engineering-teams-39d20d4e8a56) — Balancing a few key things mentioned in this article can go a long way.

[Mesosphere Announces Appointment of Mike Fey as Chief Executive Officer](https://mesosphere.com/blog/mesosphere-announces-mike-fey-as-chief-executive-officer/)

[Seven Remarkable Takeaways From Massive Kubernetes Conference](https://www.forbes.com/sites/jasonbloomberg/2018/12/13/seven-remarkable-takeaways-from-massive-kubernetes-conference/#7f4152e0599d) — "Women are leading the Kubernetes charge. Yes, you read that right. While the audience at KubeCon was perhaps 90% male, the keynote speakers were more than half female.

And no, these women weren't the result of some well-meaning but desperate effort to fill out the speaker ranks to make CNCF look good. These women were senior people in their organizations, many of whom are leading the Kubernetes effort for their companies and the community at large.

To sum up: it warms the cockles of this old tech skeptic's heart to see how well Kubernetes is doing. Its progress is eclipsed only by its promise. It won't be long till we take Kubernetes for granted as a ubiquitous part of the enterprise IT landscape, as we do technologies like Linux and TCP/IP today."

[Dear tech companies, I don't want to see pregnancy ads after my child was stillborn](https://www.washingtonpost.com/lifestyle/2018/12/12/dear-tech-companies-i-dont-want-see-pregnancy-ads-after-my-child-was-stillborn/?noredirect=on&utm_term=.0e34b870ed83) — After our miscarriage last year, it was very painful to go to Amazon in the following weeks. I wrote it off as, "How would they know?" But, if there is enough intelligence in platforms to determine I want to see certain products perhaps there should be a catastrophic event button to turn it off. If this already exists, please let me know.

{{< tweet 1072945965340872704 >}}

{{< carbon_ads >}}

## Process

[aws/containers-roadmap](https://github.com/aws/containers-roadmap) — This is the public roadmap for AWS container services (ECS, ECR, Fargate, and EKS). This is a must read.

[OWASP Core Rule Set Docker Image](https://coreruleset.org/20181212/core-rule-set-docker-image/) — Where was this in 2012 when I needed it? Put a container in front of a vulnerable application as a stop gap measure while a patch is developed and tested.

[Red Hat donates a key open-source Kubernetes tool to the Cloud Native Computing Foundation](https://www.geekwire.com/2018/red-hat-donates-key-open-source-kubernetes-tool-cloud-native-computing-foundation/) — etcd has been donated to CNCF. This makes me very happy! Also, given the AMA I facilitated, etcd is becoming an increasingly behind the scenes tool. Making etcd boring will go a long way towards increased Kubernetes adoption.

[License Changes for Confluent Platform](https://www.confluent.io/blog/license-changes-confluent-platform) — This is getting out of hand. But, I don't want to feel left out either. I have created [**The DevOps'ish License**](https://github.com/chris-short/devopsish-license/). Use it for your next project and it'll be the best thing you ever do. Pull requests welcome.

[We need Sustainable Free and Open Source Communities](https://medium.com/sustainable-free-and-open-source-communities/we-need-sustainable-free-and-open-source-communities-edf92723d619) — "The short version: we should stop focusing on how to protect the revenue models of open source companies, and instead focus on how to create sustainable communities. Both because it leads to better software, but also because it's better for business."

[Tigera raises $30M Series B for its Kubernetes security and compliance platform](https://techcrunch.com/2018/12/12/tigera-raises-30m-series-b-for-its-kubernetes-security-and-compliance-platform/) —  Congrats to Tigera on the Series B!

[Serverless: More Than Just Functions](https://redmonk.com/rstephens/2018/12/14/serverless-more-than-just-functions/) — It's interesting to see forward leaning analysts talking about Serverless while I'm trying to convince other analysts that a lot of their categories are super niche and not doing their customers any justice.

[Liveblog: Hardening Kubernetes Setups](https://blog.scottlowe.org/2018/12/11/liveblog-hardening-kubernetes-setups/) — Kubernetes security isn't really a thing despite it desperately needing to be.

[Applying Best Practice Security Controls to a Kubernetes Cluster](https://blog.giantswarm.io/applying-best-practice-security-controls-to-a-kubernetes-cluster/) — My friend and fellow CNCF Ambassador, Puja Abbassi, walks through how to properly secure Kubernetes.

[Intel, TPG in talks to sell McAfee to Thoma Bravo](https://www.cnbc.com/2018/12/14/intel-tpg-in-talks-to-sell-mcafee-to-thoma-bravo.html) — Oh... Another acquisition is in the work.

[In annual ranking of worst passwords, ‘donald' makes its debut](https://www.washingtonpost.com/technology/2018/12/13/annual-ranking-worst-passwords-donald-makes-its-debut/?utm_term=.f17b6aeda043) — That's hilarious and says a lot.

[Mark your calendar: Google Cloud Next 2019](https://cloud.google.com/blog/products/gcp/mark-your-calendar-google-cloud-next-2019)

[Red Hat Sets Jan. 16, 2019, Special Meeting for Vote on Merger Agreement with IBM](https://www.redhat.com/en/about/press-releases/red-hat-sets-jan-16-2019-special-meeting-vote-merger-agreement-ibm) — The expectation is this will be a quiet event.

{{< carbon_ads >}}

## Tools

[Secure, Private Go Registry](https://jfrog.com/integration/go-registry/) — I went to a private event help by [JFrog](https://jfrog.com/) Tuesday night while at Kubecon. Go Registry was demoed while I was there and I tweeted this out as a response. Check it out!

{{< tweet 1072734647354716160 >}}

[kubeadm Survey for v1.13/GA](https://docs.google.com/forms/d/e/1FAIpQLSd_G3AdnWG96Mtq2MEiZER9sLZZrNmSYjgqYEuv3gb2JPcZ-w/viewform) — The maintainers of `kubeadm` need your help! Please participate in this survey.

[What is CNAB?](https://www.morethanseven.net/2018/12/15/what-is-cnab/) — I'm not really sure what problem CNAB is solving at this point but, it's a thing Docker and Microsoft built. I talked to Gareth Rushgrove about it briefly at #KubeKhan. But, the conversation turned to Docker Enterprise Desktop pretty quickly. From what I can gather, it's a [codification of sorts for packaging](https://github.com/deislabs/cnab-spec) of the abstractions that make up cloud native applications. So it's an abstraction for all your abstractions? I am trying to find a use case and am drawing a blank. [It feels a little like this](https://xkcd.com/927/). Please explain what I'm missing if you think you can.

[Kubernetes Basics for Developers](https://engineering.dollarshaveclub.com/kubernetes-basics-for-developers-27e7097f87c2) — Minimum viable Kubernetes knowledge.

{{< tweet 1073728454477017089 >}}

[Loki: Prometheus-inspired, open source logging for cloud natives | Grafana Labs Blog](https://grafana.com/blog/2018/12/12/loki-prometheus-inspired-open-source-logging-for-cloud-natives/) — This is getting a lot of interest. But, while still in Alpha, I have hope for this one.

[Re-Imagining Virtualization with Kubernetes and KubeVirt](https://blog.openshift.com/re-imagining-virtualization-with-kubernetes-and-kubevirt/) — "Using Kubernetes and KubeVirt allows us to launch containers and virtual machines on the same cluster, same node, using the same networks and same storage infrastructure." Back to bare metal we go!

[NPM helps us learn important open source lessons](https://funnelfiasco.com/blog/2018/12/14/npm-helps-us-learn-important-open-source-lessons/) — Nothing is forever. Even open source maintainership.

[cyberark/KubiScan](https://github.com/cyberark/KubiScan) — A tool to scan Kubernetes cluster for risky permissions

[fntlnz/kubectl-trace](https://github.com/fntlnz/kubectl-trace) — Schedule bpftrace programs on your kubernetes cluster using the kubectl

[influxdata/platform](https://github.com/influxdata/platform) — InfluxDB 2.0: The community version of the InfluxData Platform for Time Series

[The State of the Octoverse: new open source projects in 2018](https://blog.github.com/2018-12-13-new-open-source-projects/) — Congrats to [nocode](https://github.com/kelseyhightower/nocode/)!

[Introducing Crossplane: Open Source Multicloud Control Plane](https://blog.upbound.io/introducing-crossplane-open-source-multicloud-control-plane/) — This is an interesting take tool for hybrid cloud Kubernetes management.

[Ansible in AWS Lambda](https://medium.com/@jacoelho/ansible-in-aws-lambda-980bb8b5791b) — It was only a matter of time but, this came way before I thought it would.

[Ansible AWX in Kubernetes](https://aperogeek.fr/ansible-awx-in-kubernetes/)

[Minikube v0.31.0 released!](https://discuss.kubernetes.io/t/minikube-v0-31-0-released/3811) — Minikube is such a good tool for local development.

[IBM Cloud Functions Adds Native Support for Go 1.11](https://www.ibm.com/blogs/bluemix/2018/12/ibm-cloud-functions-adds-native-support-for-go-1-11/) — Hmm... I wonder if I could make [ssl-tester](https://github.com/chris-short/ssl-tester) serverless somehow.

[Running Rocket.Chat and MongoDB on Kubernetes with StatefulSets](https://medium.com/@jmarhee/running-rocket-chat-and-mongodb-on-kubernetes-with-statefulsets-f3ddef5bd511) — A HOWTO for you!

[Relax by the fire at your Linux terminal](https://opensource.com/article/18/12/linux-toy-aafire) — Throw another yule log on the CLI.

[Improve Your Breadmaking Skills with Go and Open-Source Monitoring](https://blog.gopheracademy.com/advent-2018/observability-in-the-kitchen/)

[Building a CI/CD Bot with Slack and Kubernetes](https://blog.gopheracademy.com/advent-2018/building-ci-cd-slack-bot/)

[Introducing the new GitHub Status Site](https://blog.github.com/2018-12-11-introducing-the-new-github-status-site/)

[Kubernetes on the Edge](https://rancher.com/blog/2018/2018-12-11-kubernetes-on-the-edge/) — The Edge is going to get more and more interesting as it becomes ever increasingly important to put compute closer to users.

[Introducing the New Docker Hub](https://blog.docker.com/2018/12/the-new-docker-hub/) — You mean having seventeen repositories, one for every use case, isn't sustainable? I'm shocked!

## DevOps'ish Tweet of the Week

{{< tweet 1073688115066347520 >}}