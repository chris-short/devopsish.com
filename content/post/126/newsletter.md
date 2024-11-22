+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "Open Source News", "2019"]
date = 2019-05-05
description = "Ransom Attacks Hit Git, Managing Many Clusters, Kubernetes Failure Stories, Ansible-based Kubernetes Operators, Deadlines are Horrible, and More"
draft = false
slug = "126"
tags = ["kubernetes", "devops", "open source", "cloud", "tech", "github", "container", "security", "linux", "Red Hat", "docker", "ansible", "Ansible-based Operators", "logo", "AWS", "Amazon Web Services", "clusters", "infrastructure", "git", "GitHub", "GitLab", "Kubernetes Operators"]
title = "126: Ransom Attacks Hit Git, Managing Many Clusters, Kubernetes Failure Stories, Ansible-based Kubernetes Operators, Deadlines are Horrible, & More"

+++

Friday afternoon (US east coast time), some oddities around git repos being taken for ransom [started to pop-up](https://twitter.com/tomgilray/status/1124027843233615873). Safe to say, I'm paranoid af when it comes to the software delivery pipeline (GitHub and GitLab are both used to manage DevOps'ish). I immediately changed passwords everywhere I have code stored (and you should too if you haven't already). [GitLab chimed in](https://about.gitlab.com/2019/05/03/suspicious-git-activity-security-update/) on the issue to confirm it did not appear to be a total loss of data on affected repos and provided potential fixes. GitLab also provided extensive incident details I recommend checking out. The cause? The age-old problem of exposing version control dot directory when deploying a web site. [Don't publicly expose .git or how we downloaded your website's source code](https://en.internetwache.org/dont-publicly-expose-git-or-how-we-downloaded-your-websites-sourcecode-an-analysis-of-alexas-1m-28-07-2015/).

[**Find your next tech job**](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email2)  
No more inbox spam from recruiters! Indeed Prime matches you with top tech companies and only sends tech job opportunities that match your career goals, technical skill set, location, and salary preferences. [Join for free today](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email2)! *SPONSORED*

[**Bay Area DevOps meetup, May 9 in Mountain View**](https://bit.ly/2H1y8sb)  
Cloud Foundry, IBM, LogDNA share how open ecosystems, interoperability & multi-cloud are here to stay.  
[RSVP now](https://bit.ly/2H1y8sb) to save your seat.  
Try LogDNA - [Start free trial](https://logdna.com/sign-up/?utm_medium=Syndication&utm_campaign=DevOpsish&utm_source=DevOpsish) *SPONSORED*


## DevOps'ish Last Week's Top Five

1. [Tweet: Hertz has sued Accenture for failing to deliver on a $32 million "digital transformation" project.](https://twitter.com/allafarce/status/1121174850226147328)
2. [Python Project Tooling explained](https://write.as/chobeat/python-project-tooling-explained)
3. [The Difference Between Goals, Strategies, Metrics, OKRs, KPIs, and KRIs](https://danielmiessler.com/blog/the-difference-between-goals-strategies-metrics-okrs-kpis-and-kris/)
4. [Istio the Easy Way](https://medium.com/solo-io/istio-the-easy-way-de66e6eba4a1) (*cough* [nomedium.dev](https://nomedium.dev/) *cough*)
5. [How to run systemd in a container](https://developers.redhat.com/blog/2019/04/24/how-to-run-systemd-in-a-container/)

## People

[Deadlines are horrible](https://groups.google.com/forum/m/#!msg/kubernetes-sig-release/dGVBrlkOXQo/5m1zFTT7AwAJ) — I have stopped apologizing for being "behind" on Kubernetes community work. I wish I could do more and commit to more things but, it's not my full-time job. Open source work is largely volunteer-based and we shouldn't be this stressed helping folks out. Right?

[Product Marketing Manager — Ansible Automation](https://us-redhat.icims.com/jobs/69628/product-marketing-manager---ansible-automation/job?mobile=false&width=1638&height=500&bga=true&needsRedirect=false&jan1offset=-300&jun1offset=-240) — There are two or three open reqs on my team right now. If you're interested let me know (if I don't know you personally, send your LinkedIn profile too). I'll send you a unique URL to apply if I think you might be a good fit. Not a good fit but still need a job? [Indeed Prime](https://www.indeedprime.com/devopsish/?sid=us_other-EmailSponsor_JS_ACQ&kw=Devopsish_Email2) is a sponsor this week.

[Brand loyalty: Red Hat employees permanently inked with new company logo](https://www.wraltechwire.com/2019/05/02/brand-loyalty-red-hat-employees-permanently-inked-with-new-company-logo/) — Red Hat revealed its new logo this week. Personally, I really like it. Red Hatters have gotten the company logo tattooed on themselves for years. It's not a cult; it's called a great place to work. I'm sorry if folks haven't ever had [that feeling](https://chrisshort.net/the-importance-of-psychological-safety/).

[Call for AWS Birds-of-Feather at KubeCon Barcelona](https://discuss.kubernetes.io/t/call-for-aws-birds-of-feather-at-kubecon-barcelona/6173?u=errordeveloper) — Going to KubeCon Barcelona and use AWS? That's probably a hard, yes. There's a BoF forming and if you're interested, speak up.

[What do companies expect from Python devs in 2019?](https://cvcompiler.com/blog/what-do-companies-expect-from-python-devs-in-2019/)

[Sorting algorithm reference, for coding interviews and computer science classes](https://www.interviewcake.com/sorting-algorithm-cheat-sheet) — I'm approaching forty years old and learn new things every day. I'll be referencing this more and more as we all move towards a world full of data and code.

[Upskill Your Team To Address The Cloud, Kubernetes Skills Gap](https://www.forbes.com/sites/forbestechcouncil/2019/05/03/upskill-your-team-to-address-the-cloud-kubernetes-skills-gap/#43c363ec449f)

[You should have a personal web site](https://writing.markchristian.org/2019/04/29/personal-web-sites/) — Yes, you must have a personal web site. chrisshort.net is massive and has served me very well over the years. I modeled it a little bit after [Bridget Kromhout's site](https://bridgetkromhout.com/) which is also great.

[Gail Duval Talks Mandrake Linux and /e/ Telephone](https://fossforce.com/2019/04/gael-duval-father-of-user-friendly-linux-on-mandrake-and-e-phone/) — I loved Mandrake back in the day.

## Process

[**Accelerate: State of DevOps 2019 Survey**](https://google.qualtrics.com/jfe/form/SV_0v2VZMeA2Eha365?sp=5):  Nicole Forsgren, PhD is conducting the State of DevOps 2019 Survey. Your input is incredibly important. On several occasions, I have referenced [the 2018 report](https://cloudplatformonline.com/2018-state-of-devops.html) since its release for real-world work that impacts real numbers. Nicole's group also wrote, [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2), which I cannot recommend enough either.

*Note: DevOps'ish may earn compensation for sales from links on this post through [affiliate programs](/terms/).*

[A Week Later, Docker Offers Scant Details on Hub Attack](https://thenewstack.io/a-week-later-docker-offers-scant-details-on-hub-attack/) — Docker did conduct a very long maintenance this week. But, it hasn't offered much in terms of additional details regarding the [Docker Hub Breach](https://devopsish.com/125/) last week. There will likely be more to this story in the future.

[Compilation of public failure/horror stories related to Kubernetes](https://github.com/hjacobs/kubernetes-failure-stories)

[80% of developers are not addressing Docker security](https://snyk.io/blog/80-of-developers-are-not-addressing-docker-security/) — Super awesome to read after the [Docker Hub Breach](https://devopsish.com/125/).

[Canonical Fires Shots at Red Hat with Ubuntu Advantage Launch](https://www.cbronline.com/news/ubuntu-advantage-canonical) — "Direct contrast to the complexity and cost of offerings from Red Hat and VMware" There is a lot to be said for a simplified billing model.

[How companies adopt and apply cloud native infrastructure](https://www.oreilly.com/ideas/how-companies-adopt-and-apply-cloud-native-infrastructure) — Survey results reveal the path organizations face as they integrate cloud native infrastructure and harness the full power of the cloud.

[Kubernetes Deployment Strategies](https://www.weave.works/blog/kubernetes-deployment-strategies)

[What a pain in the Azzz-ure: Microsoft Azure, SharePoint, etc knocked offline by DNS blunder](https://www.theregister.co.uk/2019/05/02/microsoft_azure_outage_dns/) — I appreciate the difficult nature of DNS. But, outages like this are going to become less and less tolerated as more reliability is baked into infrastructure.

[Brand New: New Logo for Red Hat](https://www.underconsideration.com/brandnew/archives/new_logo_for_redhat.php) — "The new logo is quite literal: it's a red hat, but it's red AF and hat AF."

## Tools

[Many Kubernetes Clusters](https://srcco.de/posts/many-kubernetes-clusters.html) — "Zalando runs 100+ Kubernetes clusters on AWS. Each cluster runs in its own AWS account. We always create a pair of prod/non-prod clusters per 'product community', i.e. only half of our clusters (50+) are marked as "production" and have full 24x7 on-call support." The reasoning behind Zalando's Kubernetes deployment methods as detailed in the article are great. A must read.

[Sherlock changelog](https://news.sherlock.stanford.edu/posts/when-setting-an-environment-variable-gives-you-a-40-x-speedup) — Like all those awesome colors in `ls`? They come at a price thanks to `LS_COLORS`. I'd wish I'd known this tweak years ago.

[Memory Limit of POD and OOM Killer](https://medium.com/@zhimin.wen/memory-limit-of-pod-and-oom-killer-891ee1f1cad8) — "Kubernetes manages the Pod memory limit with cgroup and OOM killer. We need to be careful to separate the OS OOM and the pods OOM."

[I forgot how to manage a server](https://ma.ttias.be/i-forgot-how-to-manage-a-server/) — "My config management does this for me. Whether it's Puppet, Ansible, Chef, ... all of the boring parts of being a sysadmin have been hidden behind management tools. Yet here I am, trying to quickly configure a personal server, without my company-managed config management to aid me." In a world of automation, the manual becomes foreign.

[Building Operators with Ansible](https://www.ansible.com/integrations/containers/operators) — I have been working hard with my co-workers and OpenShift team to make sure Ansible-based Operators for Kubernetes are a known solution. Want to run Day 2 operations inside your Kubernetes cluster? You might already have what you need in the form of an Ansible Playbook or Role. Operators are pretty dope technology. Making them with Ansible is something I'll be talking about in two mini-theater sessions at Red Hat Summit this week.

[Introducing Red Hat Quay 3 - A Registry for your Linux and Windows Containers](https://www.redhat.com/en/blog/introducing-red-hat-quay-3-registry-your-linux-and-windows-containers) — Normally, I would not feature a product announcement from Red Hat unless it was something I worked on. But, as I mentioned last week, I really like Quay. It is now capable of multiarch builds which is very handy as well as a few other nice features from a container registry.

[Grafana Dashboards for Kubernetes Administrators](https://povilasv.me/grafana-dashboards-for-kubernetes-administrators/) — Minimum Viable Dashboards for Kubernetes via Grafana

[Why Script Based Deployments to Kubernetes Don't Scale](https://blog.armory.io/why-script-based-deployments-to-kubernetes-dont-scale/) — "Why use Spinnaker when I can just keep doing the same thing I've done before?"

[Synthetic Kubernetes cluster monitoring with Kuberhealthy](https://opensource.com/article/19/4/kuberhealthy) — "By enabling some simple synthetic checking, we stand a much better chance of catching these kinds of ephemeral and limited-scope disturbances in our infrastructure before customers or developers notice."

[A Guided Kubernetes Meditation](https://medium.com/@gabe_50302/a-guided-kubernetes-meditation-63cc4193582c) — Take a deep breath and [CrashLoopBackOff](https://crashloopbackoff.dev), y'all. Namaste, bitches.

[Kubernetes Ingress Tutorial: Beginners Series](https://devopscube.com/kubernetes-ingress-tutorial/) — "You will learn the concept of ingress resource and ingress controllers used for routing external traffic to Kubernetes deployments."

[Cilium 1.5: Scaling to 5k nodes and 100k pods, BPF-based SNAT, and Rolling Key Updates for Transparent Encryption](https://cilium.io/blog/2019/04/24/cilium-15/) — Cilium 1.5 now officially supports an eye-watering, "5k nodes, 100k pods and 20k services."

[gopls](https://github.com/golang/go/wiki/gopls) — `gopls` (pronounced: "go please") is an implementation of the Language Server Protocol (LSP) server for Go. The LSP allows any text editor to be extended with IDE-like features.

[derailed/k9s: 🐶 Kubernetes CLI To Manage Your Clusters In Style!](https://github.com/derailed/k9s)

[infracloudio/botkube: App that helps you monitor your Kubernetes cluster, debug critical deployments & gives recommendations for standard practices](https://github.com/infracloudio/botkube)

[se7entyse7en/pydockenv: Python virtual environment, but backed by Docker!](https://github.com/se7entyse7en/pydockenv)

[bloomreach/s4cmd: Super S3 command line tool](https://github.com/bloomreach/s4cmd)

[docker/buildx: Docker CLI plugin for extended build capabilities with BuildKit](https://github.com/docker/buildx)

[micronaut-projects/micronaut-core: Micronaut Application Framework](https://github.com/micronaut-projects/micronaut-core)

## DevOps'ish Tweet of the Week

This thread from Justin Garrison is everything.

{{< tweet 1124698927997960192 >}}

Notes from this week's issue can be found [on GitHub](https://github.com/chris-short/devopsish.com).
