+++
author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "Open Source News", "2022"]
date = 2022-10-09T07:00:00Z
description = [""]
draft = false
slug = "288"
tags = []
title = "DevOps'ish 288: Pain points around containers, "
+++

Last week, I shared out the notes I took from an Open Space suggestion I made at DevOpsDays Chicago, "[Container Conundrum: Pain points around containers](https://chrisshort.net/container-conundrum-devopsdays-chicago-2022-open-space-notes/)." The premise was trying to figure out where people are struggling with managing containers and the applications in them in their environments. My friend Ed Vielmetti joined in as well. I want to stress that no one else in the room identified their employer (nor would I have recorded that data or anything that could lead me to it), so your trade secrets are pretty safe. I learned quite a bit, so I'll share more details here.

### Kubernetes Everywhere

Everyone in the room was using Kubernetes. The participants were using no other container orchestrators. This shows that Kubernetes adoption grew tremendously in the three years since the last time I was at a DevOpsDays Chicago in person. One pair of folks in the Open Space were building artisanal vanilla Kubernetes clusters by hand across multiple clouds (AWS, GCP, Azure, and IBM Cloud). But my notes indicate we're not hitting on all cylinders with Kubernetes yet. I'll explain further.

### Security

OMG... I'm scared y'all. Not scared, but we had just left a fantastic ignite talk from [Hannah Sutor](https://twitter.com/hhsutor) about maintaining the least privileged permissions throughout our environments. The question was asked, "Is anyone practicing those least privileges in their environments?" No one in the room spoke up.

This leaves the imagination to wonder. Is Kubernetes RBAC too hard? Is IAM hard? Is getting access and authorization tightly scoped harder than we all wished it was? And that's just my chicken scratch. This is a problem for anyone worried about their containerized applications.

One shocking twist of events made the security team at one organization go from an operational security team to a "non-operational" security team. What this meant for the organization was that the Security team wouldn't be hands-on in fixing security concerns and managing configuration. The team would open issues/tickets instead and leave them for the platform team to clean up. This was a step backward in their DevOps journey. But security teams are overwhelmed, and this extreme case was a solid reminder. I hope this strategy works, but it felt wildly "throw it over the wall" like.

#### Secrets

Wide use of [Kubernetes Secrets](https://kubernetes.io/docs/concepts/configuration/secret/) was no surprise. One organization had a way to spit out an array of credentials for a given application as a [ConfigMap](https://kubernetes.io/docs/concepts/configuration/configmap/) (it was wired up with Vault and a config management system). This sounded like a very cool way of going about secrets. You still have to worry about credentials on disk, but you don't have to juggle a dozen individual secrets for your applications.

Open source and enterprise [Hashicorp Vault](https://www.hashicorp.com/products/vault) saw wide usage in this bunch. But, how the cluster consumed those credentials had a lot of variations. [Sops](https://github.com/mozilla/sops), [External Secrets Operator](https://github.com/external-secrets/external-secrets), and regular ole Kubernetes Secrets were all ways secrets got from their given store to applications. One workflow included using [AWS Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html) with External Secrets, which is a very viable way of storage for configuration data management and secrets management.

It was nice to see a wide range of tooling in use. But, one organization took the cake. They were running open source Hashicorp Vault across their entire Kubernetes fleet. They knew if it ever went down, it'd be an instant Sev1 (high availability is a feature in the enterprise version of Hashicorp Vault). But they were running their Vault in a solid configuration on what I'm assuming is a multi-region Kubernetes cluster. As long as Kubernetes is okay, Vault should be too. But, their entire org would go down if Vault went offline for seemingly any time outside a maintenance window. Build won the build vs. buy discussion partly thanks to the robustness of their Kubernetes services.

#### OPA or Kyver**no**

Here's another red flag: no one raised their hand that they were using *any* kind of policy engine. No [OPA](https://www.openpolicyagent.org/) or [Kyverno](https://kyverno.io/) was to be found in this room. No one had questions about it either, but there was some sheepishness in the lack of raised hands. I think complexity and inability to accurately define who should have access to what are driving factors here. But, dang, not even having the capability at your disposal is wild to think about these days. 

No. No, it's not.

Kubernetes is hard. Much like state, policy in Kubernetes is more complicated. But, establishing some basic baseline policies both projects could agree upon (even if it's just the basics from the NSA security guidelines) would be a boon to the industry. Explaining the how and why behind each policy is critical for understanding. The ease of implementing them is also vital. The first vendor to make a list, or even better navigatable visualization, of a cluster and the traffic rules and policies that could be applied safely will have a big upper hand.

### Filesystems

A chunk of time was spent talking about filesystems. Specifically, mounting filesystems as read-only in-cluster with writes going to an API in front of storage. It was a goal of many people in the room but was also a brand new concept to others in the room. Some folks pointed out they had to have a way to prove a filesystem was read-only for auditing purposes. They had to build tests to confirm that the attached storage was read-only.

Another group had difficulty getting their developers to understand the benefits of a read-only filesystem in a container. The security model was much tighter because you needed valid credentials to write data anywhere. But a whole chunk of code had to be written to implement this in applications. It seemed like much rewriting was required for the organization to get there too. In a nutshell, they weren't there yet but were trying hard.

### Environments

Dev, stage, prod: It's always a problem creating consistency across environments. Data is a huge problem here. Folks didn't have the amounts of data they stored in production environments in their other environments. At most, a subset of sanitized data was provided for use in dev and staging.

But, the problem went even deeper. Dev environments were back to needing TONS of horsepower again. Developing locally now meant running, debugging, and compiling code for applications and running them in a Kubernetes cluster on a laptop or a small cluster that was likely overprovisioned in dev.

Some folks expressed problems getting their development teams to use consistent images across different applications and environments. Getting devs to establish sane standards around Dockerfiles across environments was an issue that was put out there. But think how hard it'd be to maintain 50 apps, all with different OS versions or different OSes, completely across environments. Errors in one environment might not show up at all in another.

One org was having trouble explaining why configuration and code needed to be separated in today's world. I was stunned by this one because I thought we had established this pattern well. Why? Because you never know what your environment will look like a year or two from now. Configuration changes might need to be made wholesale across multiple applications at once.

There are myriad problems with all layers of development, it seems. This is a little troubling given that an ideal state is a cluster-aware IDE where developers can deploy applications to an adequately resourced dev environment. But, even there, resources for Kubernetes are scarce because of operating costs. This is *still* a problem for folks that needs solving.

### Multi-cloud? Yes, but...

Can we put this to bed yet? The only multi-cloud organization represented was due to their procurement process. They would be asked what capacity they needed, and procurement would ask all the vendors for the lowest price. Whoever bid the lowest got that organization's business.

First, ouch! Second, having a seat at the table matters here. It would be best if you had close friends in finance. Ideally, you have a shared language and a common understanding of all sides' concerns.

They were only rolling vanilla Kubernetes clusters because of this procurement process. The folks at this organization had the most questions and comments. They had technical expertise. But, it felt they were overwhelmed by the number of problems to solve.

They didn't detail whether or not they had any cross-cloud activities happening. At least, those questions or comments were not made. This leads me to believe the org was project/product/service driven by the procurement process regarding cloud computing. I extrapolated from there that an entire `$THING` would likely be built on one cloud and done. On to the next lowest bidder for the next `$THING`. I empathized with them immensely. I should have had Kubernetes swag packs for these brave folks.

They did not say anything about cross-cloud connectivity or applications. They had **nothing** positive to say about their multi-cloud experience. I think the idea of spreading yourself across multiple clouds is noble, but the reality is that state (or data) has gravity. State is hard. There are a lot of steps when you start stretching clusters across regions (let alone whole clouds) around keeping that state consistent and accurate (remember, etcd eats IOPS for breakfast).

### Anything else?

Upgrading clusters is a challenge. Creating a new cluster and migrating applications over is an expensive proposition. Most folks in the room were doing in-place upgrades with workloads moving around as needed. The need to make the upgrade process more resilient and accessible would be a colossal savior to Kubernetes users.

Creating Champions in orgs is very effective. This was highlighted in a DevOpsDays Chicago talk and the open space. Kubernetes, read-only filesystems, and almost every new conceptual process need a few champions throughout an organization. Establish a few and watch them work their magic within your org. Grab your nearest developer and see what they think about being a champion for something they're exceptional at.

### The DevOps'ish Podcast

[The DevOps'ish Podcast](https://devopsish.com/podcast/) is off this week. Join us next Monday, October 17th, 10 AM ET/14:00 UTC ([iCal](https://devopsi.sh/iCal) and [Google Calendar](https://devopsi.sh/GCal)).

[Join the Twitter Space](https://twitter.com/i/spaces/1OyKAVmZekqGb) to participate **LIVE**! 
Bring some friends along too!

Subscribe to the [DevOps'ish Podcast](https://anchor.fm/devopsish) via your podcasting software of choice so you can listen on Mondays on your lunch break or ride home.

## O'Reilly Book on Observability Engineering—Get Yours Free from Honeycomb!

Manage complex cloud-native systems, improve customer experiences, and build & run better software using Honeycomb. Get your FREE copy of [our new O'Reilly book](https://info.honeycomb.io/observability-engineering-oreilly-book-2022?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_book_observability_engineering_2022&utm_id=oreillybook2022&utm_content=2113) and register for our [Authors' Cut Series](https://www.honeycomb.io/oreilly-observability-engineering/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=oreilly_authors_cut_series_2022&utm_id=oreillyauthorscut&utm_content=2112) to discuss key concepts.

### Events

**Editor's note:** If your event would suit the DevOps'ish audience, please let me know!

[**Kubernetes Contributor Summit North American 2022**](https://www.kubernetes.dev/events/2022/kcsna/)

October 24, 2022 at [KubeCon](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)

The Summit will have a healthy mix of content tailored to active contributors. To conclude the summit, we'll end with [Contributor Social](https://www.kubernetes.dev/events/2022/kcsna/social) with games and refreshments.

[**KubeCon + CloudNativeCon Detroit 2022**](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/?utm_source=devopsish)  

OCTOBER 24 – 28, 2022

The [Cloud Native Computing Foundation](http://cncf.io/)'s flagship conference gathers adopters and technologists from leading open source and cloud native communities in Detroit, Michigan from October 24 – 28, 2022. Join containerd, CoreDNS, Envoy, etcd, Fluentd, Harbor, Helm, Jaeger, Kubernetes, Linkerd, Open Policy Agent, Prometheus, Rook, TiKV, TUF, Vitess, Argo, Buildpacks, Cilium, CloudEvents, CNI, Contour, Cortex, CRI-O, Crossplane, dapr, Dragonfly, Emissary Ingress, Falco, Flagger, Flux, gRPC, KEDA, KubeEdge, Litmus, Longhorn, NATS, Notary, OpenTelemetry, Operator Framework, SPIFFE, SPIRE, and Thanos as the community gathers for five days to further the education and advancement of cloud native computing. Use code **KCNAIPV22MEET** for a discount at registration.

[**FOSDEM 2023**](https://fosdem.org/2023/)

FEBRUARY 4 - 5, 2023

FOSDEM is a free event for software developers to meet, share ideas and collaborate.

Every year, thousands of developers of free and open source software from all over the world gather at the event in Brussels.

## People

PEOPLE

## Process

PROCESS

## Tools

TOOLS

## DevOps'ish Post of the Week

[![BenTheElder on Twitter: "PSA: The @kubernetesio container image host http://k8s.gcr.io is *actually* getting redirected to the community controlled http://registry.k8s.io starting with a small portion of traffic on October 3rd. If you notice any issues, *please* ping me, @thockin or @ameukam.")](https://shortcdn.com/devopsish/288-devopsish-post-of-the-week.webp)](https://twitter.com/BenTheElder/status/1575898507235323904)

### Notes

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com/blob/main/content/post/288/notes.md?utm_source=devopsish)