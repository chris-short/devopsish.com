+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2018-02-10T02:00:00.766Z
description = ""
draft = false
slug = "062"
tags = ["devops", "cloud native", "open source", "kubernetes", "go", "golang", "18f", "meltdown", "chaos engineering", "ansible", "database", "detroit", "spectre"]
title = "062: Saddling Up, Mergers, Deaths, What's Up with 18F, Chaos Engineering, Performance Impact of Meltdown and More!"
image = "/062/kris-nova-cascades-mt-rainier.jpg"
imagealt = "Cascades from Mt. Rainier by Kris Nova"
imagecap = "Cascades from Mt. Rainier by [Kris Nova](https://novasummits.com/)"

+++

This was a very interesting week for me. I participated in a chronic pain treatment study at the Ann Arbor VA Hospital early Tuesday morning. The experience, while odd, went incredibly well. Today is the first day I have felt noticeable pain which is likely due to managing Max at my nephew's birthday date. If you know me, you know this is an incredible feat. On Thursday, I attended a brand new [Kubernetes Meetup in Downtown Detroit](https://www.meetup.com/Detroit-Kubernetes-Docker-all-things-Cloud-Native/). It was fabulous! Mack and Uzo have some great ideas and I hope to collaborate with them on a few ideas we came up with after the Meetup. The coming week will be nuts!

* Monday: Lunch in Royal Oak, MI
* Tuesday AM: Meeting in Ann Arbor, MI
* Wednesday: Meeting in Washington, D.C.
* Thursday: [Detroit Go Meetup](https://www.meetup.com/DetroitGolang/) in Downtown Detroit
* Friday-Sunday AM: [Open Source 101](http://opensource101.com/raleigh/talks/avoiding-devops-pit-misery-tips-trenches/) in Raleigh, NC

If you're around any of these places or events please don't hesitate to stop me and say hello. Then I'll be speaking at [DevOpsDays Charlotte](https://www.devopsdays.org/events/2018-charlotte/) the following week. DevOps the fuck up, y'all!

[**Scale Continuous Delivery for Your Enterprise?**](https://www.gocd.org/enterprise/?utm_campaign=enterprise_page&utm_medium=email&utm_source=devopsish_newsletter&utm_content=enterprise_page&utm_term=)  
GoCD is a Continuous Delivery tool allowing you to model, orchestrate, and visualize complex workflows. Our enterprise offering provides plugins and professional support to help your scale CD in your organization. [Check out GOCD's enterprise features and performance upgrades now!](https://www.gocd.org/enterprise/?utm_campaign=enterprise_page&utm_medium=email&utm_source=devopsish_newsletter&utm_content=enterprise_page&utm_term=) *SPONSORED*


## People

[Codeship and CloudBees Join Forces!](https://www.cloudbees.com/blog/codeship-and-cloudbees-join-forces)

[John Perry Barlow, Internet Pioneer, 1947-2018](https://www.eff.org/deeplinks/2018/02/john-perry-barlow-internet-pioneer-1947-2018)

[12 emerging IT job titles with a bright future](https://enterprisersproject.com/article/2017/11/12-emerging-it-job-titles-bright-future): If you would have asked me this time last year I would have told you "DevOps Engineer" is a legit title. But, I now know that is no longer the case. If you're creating a DevOps team within a larger engineering organization you are creating silos.

[Tech workers are now earning an average of $135,000 but black tech workers are getting 'shortchanged'](http://www.businessinsider.com/tech-workers-tend-to-earn-135000-depending-on-their-race-2018-2): This needs to stop, folks. Show them the money!

[Career Change Into DevOps With Michael Hedgpeth, Annie Hedgpeth, And Megan Bohl (ADO102)](https://www.arresteddevops.com/career-change-into-devops/)

[The rise and fall of 18F](https://www.fedscoop.com/rise-fall-18f/): This is a sad truth I feared would happen in the wake of the downsizing of the federal government. I use the term downsizing in lieu of whatever it is the current administration is doing.

[The many-faced god of operational excellence, DevOps and now 'site reliability engineering'](http://www.theregister.co.uk/2018/02/06/devops_no_ops_less_ops/)

[Kolton Andrus On Designing and Deploying Internet Scale Services](https://www.meetup.com/papers-we-love-too/events/247656710/): The [CEO of Gremlin](https://twitter.com/KoltonAndrus) is speaking about the paper, "On Designing and Deploying Internet-Scale Services". If you're in SF on February 28th, I highly recommend checking this out.

My friend, [Tammy Butow](http://tammybutow.com/), also of Gremlin, will be speaking at the [Melbourne AWS User Group: Chaos Engineering Month](https://www.eventbrite.com/e/melbourne-aws-user-group-chaos-engineering-month-registration-43014538643) on February 28th as well. Tammy is one of my favorite speakers so if you're in Melbourne definitely signup to see this. If you're not familiar with Tammy she killed it at [GopherCon 2017](https://youtu.be/5doOcaMXx08) and the Australian government just hosted her for a talk on [Chaos Engineering](https://youtu.be/qHykK5pFRW4).

[Lyft riders can now add to fares and donate to Black Girls Code](http://www.usatoday.com/story/tech/2018/02/09/lyft-riders-can-now-add-fares-and-donate-black-girls-code/321414002/)

[Russian nuclear scientists arrested for 'Bitcoin mining plot'](http://www.bbc.com/news/world-europe-43003740): Who needs nukes when you can have Bitcoin?

## Process

[When building a DevOps culture, go slowly and don't force it](http://devopsagenda.techtarget.com/opinion/When-building-a-DevOps-culture-go-slowly-and-dont-force-it)

[How DevOps helps deliver cool apps to users](https://opensource.com/article/18/2/devops-delivers-cool-apps-users)

[Deploying new releases: Feature flags or rings?](http://red.ht/2nlBOKQ)

[Open-source drug discovery](https://lwn.net/Articles/746663/)

[KPTI/KAISER Meltdown Initial Performance Regressions](http://www.brendangregg.com/blog/2018-02-09/kpti-kaiser-meltdown-performance.html) by Brendan Gregg: "The patches that workaround Meltdown introduce the largest kernel performance regressions I've ever seen."

[The Impact of Spectre and Meltdown on the Cloud](https://thenewstack.io/impact-spectre-meltdown-cloud/) by Heptio's Craig McLuckie

[When to use Serverless? When to use Kubernetes?](http://heidloff.net/article/when-to-use-serverless-kubernetes)

[Open Source and Standards Team: How Red Hat Measures Open Source Success](https://www.linuxfoundation.org/blog/open-source-standards-team-red-hat-measures-open-source-success/)

## Tools

[CNCF Adds Vitess Database Orchestration Project](https://containerjournal.com/2018/02/06/cncf-adds-vitess-database-orchestration-project/): Y'all want some MySQL in your clusters?

[What is a monolithic application?](https://blog.heptio.com/what-is-a-monolithic-application-e375f5ad5ecb)

[Java 9 has six weeks to live](http://blog.joda.org/2018/02/java-9-has-six-weeks-to-live.html)

GitHub is not a package repo:[jteeuwen/go-bindata](https://github.com/jteeuwen/go-bindata) was created because GitHub allows reuse of usernames and jteeuwen blew away the official jteeuwen/go-bindata repo. [GitHub Shouldn't Allow Username Reuse](https://donatstudios.com/GithubsTotalSecurityFacepalm) btw.

[Heptio Makes Case for Kubernetes Subscription Service](https://containerjournal.com/2018/02/07/heptio-makes-case-for-kubernetes-subscription-service/)

[Turn Any CLI into a Function with OpenFaaS](https://blog.alexellis.io/cli-functions-with-openfaas/) by Alex Ellis: "Logging into servers to run CLIs is manual and slow. Let's show how you can work smarter by turning your favorite CLIs into Functions with their own API via OpenFaaS."

[Your Database Should Work Like a CDN](https://www.cockroachlabs.com/blog/distributed-database-performance/)

[Coming Soon: Networking Features in Ansible 2.5](https://www.ansible.com/blog/coming-soon-networking-features-in-ansible-2.5) by Sean Cavanaugh (the Ansible networking expert)

[ANSIBLE COMMUNITY - 2017 YEAR IN REVIEW](https://www.ansible.com/blog/2017-community-year-in-review) by Greg DeKoenigsberg

[How We Scaled Nocode To An Infinite Number Of NoServers](https://medium.com/@alexshenoy/how-we-scaled-nocode-to-an-infinite-number-of-noservers-b8332f5bf080): Kelsey Hightower's [nocode](https://github.com/kelseyhightower/nocode) is the future.

[vmware/govmomi](https://github.com/vmware/govmomi): A Go library for interacting with VMware vSphere APIs (ESXi and/or vCenter).

[NVIDIA/k8s-device-plugin](https://github.com/NVIDIA/k8s-device-plugin): NVIDIA device plugin for Kubernetes

[pmorie/osb-starter-pack](https://github.com/pmorie/osb-starter-pack): A quickstart for making a new Open Service Broker

[devops-israel/aws-inventory](https://github.com/devops-israel/aws-inventory): AWS Inventory in a single HTML file using JS AWS-SDK & Bootstrap

## DevOps'ish Tweet of the Week

{{< tweet 960827149585395712 >}}
