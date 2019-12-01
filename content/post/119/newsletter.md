+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2019-03-17T07:00:00Z
description = "Serverless, k8s on k8s on k8s, gRPC (Yeah You Know Me), Foundation Fatigue, Self Care, and More"
draft = false
slug = "119"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "cloud native", "cncf", "serverless", "ansible", "container", "security", "google", "azure", "k8s", "grpc"]
title = "119: Serverless, k8s on k8s on k8s, gRPC (Yeah You Know Me), Foundation Fatigue, Self Care, and More"

+++

I learned this week that [I've had Shingles since at least November](https://twitter.com/ChrisShort/status/1105211715413790720). If you don't know, [Shingles](https://www.mayoclinic.org/diseases-conditions/shingles/symptoms-causes/syc-20353054) is adult chickenpox and can suck the life out of you ([get your kids vaccinated](https://www.cdc.gov/vaccines/vpd/varicella/public/index.html)). I didn't notice the first sign of shingles, pain, due to all the medications I'm already taking. I chalked up the fatigue to a busier than normal travel schedule. I had several opportunities to get the first outbreak looked at and didn't. This second outbreak did get looked at and it is a wake-up call. The point is if you don't take care of yourself, how able are you going to take care of anything else?

> "Every day is a new beginning, take a deep breath and start again." —Unknown

**New Microsoft Azure Elastic Agent Plugin for GoCD**  
With GoCD's new Azure plugin, run your CI/CD pipelines on Azure virtual machines, and let GoCD scale up on-demand agents based on your need. Remove bottlenecks and reduce the cost of your agent infrastructure.

Learn more about GoCD: [www.gocd.org](https://www.gocd.org)  
Learn more about GoCD's Azure plugin: https://extensions-docs.gocd.org/azure/current/ *SPONSORED*

[**The Cloud Pod**](https://www.thecloudpod.net/)  
Keeping up with the avalanche of new features, blog posts, industry news, and all things cloud is a daunting task for anyone working in DevOps. Subscribe today to let Justin, Jonathan, and Peter break down the AWS, Azure and Google cloud news each week where you listen to podcasts. [www.thecloudpod.net/subscribe](https://www.thecloudpod.net/subscribe/) *SPONSORED*


## DevOps'ish Top Five from Last Week

1. [Goodbye Docker and Thanks for all the Fish](https://technodrone.blogspot.com/2019/02/goodbye-docker-and-thanks-for-all-fish.html)
2. [The saddest thing I've ever heard on an airplane](https://theoatmeal.com/comics/airplane_heard)
3. [Ansible and Terraform: Better Together](https://www.hashicorp.com/resources/ansible-terraform-better-together)
4. [You Don't Need All That Complex/Expensive/Distracting Infrastructure](https://blog.usejournal.com/you-dont-need-all-that-complex-expensive-distracting-infrastructure-a70dbe0dbccb) (NOTE: You can't stop innovating)
5. [How to ace the Certified Kubernetes Administrator Exam in 7 days](https://medium.com/@writetomiglani/how-to-ace-the-certified-kubernetes-administrator-exam-in-7-days-e4603ac40746)

## People

[The 737Max and Why Software Engineers Might Want to Pay Attention](https://medium.com/@jpaulreed/the-737max-and-why-software-engineers-should-pay-attention-a041290994bd) — J. Paul Reed nails my concerns around how software dependent big companies are becoming. The 737 Max is the tip of the iceberg in this problem space.

[DevOps For Dummies (For Dummies (Computer/Tech)) by Emily Freeman](https://amzn.to/2TFOQFe) — My dear friend, Emily Freeman, is writing a book, y'all! Pre-order it today because it's going to be great and Emily has worked her ass off on it.

[A simple reason why there aren't more women in tech - we're okay with misogyny](https://huyenchip.com/2019/03/11/silicon-valley-misogyny.html) — "While looking for books on the tech world, I came across [Chaos Monkeys: Obscene Fortune and Random Failure in Silicon Valley](https://amzn.to/2UGaTbp). The book is advertised as "exposé of life inside the tech bubble." A glimpse into his mind and the rave reviews of his male-dominated audience, I suddenly understood why there aren't more women in tech."

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[Google moves dozens of employees out of its laptop and tablet division](https://www.businessinsider.com/google-moved-dozens-employees-out-of-laptop-and-tablet-division-2019-3) — The moment in which Google hardware products go the same way as Google Reader. I'm very happy with deciding to buy a new MacBook Air over a Pixelbook. Remember, [Fuschia](https://www.techradar.com/news/google-fuchsia) is coming and [Google killed Google Fiber because of 5G](https://chrisshort.net/the-demise-of-google-fiber-and-internet-under-dirt/) which is still a year or more away from widespread deployment. Google got what it wanted out of the hardware venture I'm betting and now they're out.

[Mozilla introduces gender transitioning guidelines and policy](https://blog.mozilla.org/inclusion/2019/03/04/mozilla-introduces-gender-transitioning-guidelines-and-policy/) — I don't know if or when I'll leave Red Hat ever but the next company I go to will have a policy around helping Transgender employees. The motivation is purely selfish too. Companies with this capability are also going to be able to help Veterans with minimal effort. These companies have unlocked HR 2.0 (aka whatever Human Resources becomes) to enable their employees to not have to worry too much about who they are so that they can perform at a higher level.

[Why Are We Still Promoting Incompetent Men?](https://hbr.org/ideacast/2019/03/why-are-we-still-promoting-incompetent-men) — "While we should be promoting people based on their competence and potential, it's often the incompetent, overconfident candidates — most of them men — who get ahead... To improve leadership across the board, we need to focus on the metrics proven to enhance performance and set higher standards for everyone."

[Physicists reverse time using quantum computer](https://phys.org/news/2019-03-physicists-reverse-quantum.html) — Huh... Did time travel become a little closer to reality?

## Process

**Calling all those who DevOps!** Can you spare 25 minutes to help the DORA research team know what it takes to make great software? [**Take the Accelerate State of DevOps survey today!**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5)

[Creating a commit on behalf of an organization](https://github.blog/changelog/2019-03-15-creating-a-commit-on-behalf-of-an-organization/) — Developers can indicate their intent to contribute to a project on behalf of an organization.

[Nginx is getting acquired by F5 Networks](https://www.businessinsider.com/nginix-f5-networks-670-million-acquisition-2019-3) — This is existential for both companies. Good luck!

[Serverless Golang APIs in 60 seconds](https://medium.com/@tjholowaychuk/serverless-golang-apis-in-60-seconds-46e4ac36b680) — Get Serverless with Go and Apex Up

[What the Fork, Amazon?](https://thenewstack.io/what-the-fork-amazon/) — I have really big problems with what Amazon is doing here. But, Elastic did make this bed so now they have to lay in it.

[AWS intends for their new project to be an Elasticsearch fork](https://www.influxdata.com/blog/aws-intends-for-their-new-project-to-be-an-elasticsearch-fork/) — "In this post, I'll argue that it is absolutely AWS' intention to fork the Elastic community. I'll also explore the implications for the Elasticsearch community and Elastic the company, and ponder what this could mean for other commercial open source vendors."

[New Red Team Project Aims to Help Secure Open Source Software](https://www.linuxfoundation.org/blog/2019/03/new-red-team-project-aims-to-help-secure-open-source-software/) — There were a lot of new Linux Foundation sub-foundations founded this week. This one flew under the radar but, it's the one that has me the most interested.

[Kubernetes Patterns](http://shop.oreilly.com/product/0636920242598.do) — A new book from O'Reilly by Bilgin Ibryam and Roland Huß discussing "Reusable Elements for Designing Cloud Native Applications"

[Why isn't CPU time more valuable?](https://www.johndcook.com/blog/2019/03/07/cpu-time/) — "Surely it should be possible to think of something for a computer to do that produces more than 2.5 cents per CPU hour of value. But is it?"

[How Airbnb Simplified the Kubernetes Workflow for 1000+ Engineers](https://www.infoq.com/news/2019/03/airbnb-kubernetes-workflow)

[Notepad++ No Longer Code Signed, Dev Won't Support Overpriced Cert Industry](https://www.bleepingcomputer.com/news/software/notepad-no-longer-code-signed-dev-wont-support-overpriced-cert-industry/) — The dev behind my favorite Windows text editing tool isn't going to pony up the dough for a certificate anymore. I don't blame them. "The time wasted in while trying to get a new signing certificate and the unreasonable price tags such a product comes with were two other causes behind [Don] Ho's decision to drop code signing from the Notepad++ 7.6.4 release."

[CD Foundation Launches with Jenkins, Jenkins X, Spinnaker, Tekton](https://thenewstack.io/continuous-delivery-foundation-launches-with-jenkins-jenkins-x-spinnaker-tekton/) — More questions than answers here at the moment. But, I see this is a much-needed change. Jenkins (and Cloudbees as a result) has rested on its laurels for far too long. Bringing change to continuous delivery tool sets are NECESSARY.

[Hey, DevOps fans. We've got another TLA for you to write down: CDF](https://www.theregister.co.uk/2019/03/12/continuous_delivery_foundation/) — And The Register's take on Continuous Delivery Foundation (CDF). 'You could look at Jenkins X and Spinnaker and say they're kind of overlapping a bit," before insisting that there is "more synergy than overlap".' I side-eye the fuck out of anyone using the word "synergy" in a sentence.

[Kubernetes - The Fast and Furious?](https://www.weave.works/blog/kubernetes-the-fast-and-furious) — "After a brief introduction on the CNCF and its role, Alexis [Richardson] then explained the type of projects and how they get accepted to the foundation before diving into how enterprises can benefit by adopting cloud native technology."

[DevOps for the Database](https://www.vividcortex.com/resources/devops-for-the-database-ebook) — "In his all-new ebook, DevOps for the Database, Baron Schwartz – noted author and founder/CTO of VividCortex – looks at what DevOps really means and how it can drive automation of database operations and collaboration across teams to make their systems and processes faster, better and cheaper."

[The 12 Worst Serverless Security Risks](https://www.darkreading.com/cloud/the-12-worst-serverless-security-risks/a/d-id/1334079)

## Tools

[Kubernetes: AWS vs GCP vs Azure vs DigitalOcean](https://medium.com/@andreidascalu/kubernetes-aws-vs-gcp-vs-azure-vs-digitalocean-24d71067c795) — "Given the popularity of Kubernetes, I'd say it's time to have a look at what's what (through a beginner's eyes) while keeping costs in mind as well."

[Ansible Lint for GitHub Action](https://github.com/marketplace/actions/ansible-lint) — "This action allows you to run ansible-lint with no additional options" in GitHub Actions

[Creating a Kubernetes Cluster with Digital Ocean and Terraform](https://ponderosa.io/blog/kubernetes/2019/03/13/terraform-cluster-create/) — I have been using Digital Ocean's Kubernetes offering for the past two weeks and I am *REALLY* liking it.

[Kubernetes Setup Using Ansible and Vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/) — "This blog post describes the steps required to setup a multi node Kubernetes cluster for development purposes. This setup provides a production-like cluster that can be setup on your local machine."

[Get HTTPS for your local endpoints with inlets and Caddy](https://blog.alexellis.io/https-inlets-local-endpoints/) — (THIS IS NOT AN ENDORSEMENT OF CADDY) If you're working behind a restrictive firewall inlets can definitely help.

[Quick take on Hasura: a daemon for GraphQL on Postgres](https://redmonk.com/jgovernor/2019/03/11/quick-take-on-hasura-a-daemon-for-graphql-on-postgres/) — GraphQL is a big deal and Postgres is increasingly the RDBMS of choice. [Hasura](https://hasura.io/) is on to something here.

[Announcing Submariner, Multi-Cluster Network Connectivity for Kubernetes](https://rancher.com/blog/2019/announcing-submariner-multi-cluster-kubernetes-networking/) — I was worried about Rancher prior to their shift to Kubernetes. Not anymore! "Submariner creates the necessary tunnels and routes needed to enable containers in different Kubernetes clusters to connect directly."

[Why Serverless Architecture?](https://read.acloud.guru/why-serverless-architecture-2b2610fb23fd)

[gRPC to AWS Lambda: Is it Possible?](https://blog.coinbase.com/grpc-to-aws-lambda-is-it-possible-4b29a9171d7f) — "I was curious about whether it was even possible to make a gRPC call through API gateway to a Lambda and have a response return all the way to the client. Turns out, it's very close to possible for unary request / response gRPC calls."

[gRPC Load Balancing inside Kubernetes](https://blog.nobugware.com/post/2019/kubernetes_mesh_network_load_balancing_grpc_services/) — "How to deal with disconnections/re-connections, maintenance? What about gRPC specifically? The answer is heavily connected to the network stack used by Kubernetes, but with the "Mesh Network" revolution, It's not always clear how it works anymore and what the options are."

[Kafka on Kubernetes, the easy way](https://banzaicloud.com/blog/kafka-on-k8s-simplified/) — If you want Kafka on Kubernetes, start here.

[Kage - Graphical User Interface for Metasploit Meterpreter and Session Handler](https://cybarrior.com/blog/2019/03/11/kage-graphical-user-interface-for-metasploit-meterpreter-and-session-handler/) — Kage (ka-geh) is a tool inspired by AhMyth designed for Metasploit RPC Server to interact with meterpreter sessions and generate payloads.

[Kubernetes cheatsheets in english and french](https://itnext.io/kubernetes-cheatsheets-in-english-and-french-e655a8dcd452) — "Long story short, here are two cheatsheets for Kubernetes (tested on 1.13), one in English, and one in French. It will give you some useful commands using kubectl, kubectx, kubens, kubetail, ... and also some manifest samples for Ingress and PersistentVolumeClaim." I printed this out as it's just enough to exercise the one brain cell holding all my Kubernetes knowledge.

[Molecule v2.20 pre-release announcement](https://www.reddit.com/r/ansible/comments/ayetme/molecule_v220_prerelease_announcement/) — Molecule is a project brought under Ansible's wings last year. This is the first release fully managed since Ansible taking over stewardship of Molecule. I'm excited about this tool as it's VERY extendable. But, I need to prove its importance to my direct co-workers.

[Will it cluster? k3s on your Raspberry Pi](https://blog.alexellis.io/test-drive-k3s-on-raspberry-pi/) — Managing a full blown Kubernetes platform on Raspberry Pis is REALLY hard (see [rak8s](https://github.com/rak8s/rak8s)). "The k3s binary comes in at around 40 MB and bundles all the low-level components required such as containerd, runc and even kubectl. k3s can take the place of kubeadm." Maybe rak3s will become a thing with all the free time I have.

[How to deploy NuoDB on Kubernetes with OpenEBS](https://blog.openebs.io/how-to-deploy-nuodb-on-kubernetes-with-openebs-6e15d4064db5)

[keptn/keptn](https://github.com/keptn/keptn) — Fabric for cloud-native lifecycle automation at enterprise scale

[itwars/k3s-ansible](https://github.com/itwars/k3s-ansible) — Ansible playbook to deploy k3s Kubernetes cluster

[pirate/ArchiveBox](https://github.com/pirate/ArchiveBox): The open source self-hosted web archive. Takes browser history/bookmarks/Pocket/Pinboard/etc., saves HTML, JS, PDFs, media, and more

[boot2podman](https://github.com/boot2podman/boot2podman/releases) — boot2podman 0.20 is out!

[miguelmota/ipdr](https://github.com/miguelmota/ipdr) — IPFS-backed Docker Registry

[kubernetes/minikube](https://github.com/kubernetes/minikube/releases/tag/v0.35.0) — Update your minikube installations

[micro/go-micro](https://github.com/micro/go-micro) — A microservice framework

## DevOps'ish Tweet of the Week

{{< tweet 1106012106950770693 >}}

Notes from this week's issue can be found [here](./notes/).
