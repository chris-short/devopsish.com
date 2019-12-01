+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News"]
date = 2018-06-17T07:00:00Z
description = "Improving the Workforce, Programming Myths, Kubernetes, New Books, and More"
draft = false
slug = "080"
tags = ["devops", "cloud native", "open source", "kubernetes", "ansible"]
title = "080: Improving the Workforce, Programming Myths, Kubernetes, New Books, and More"
image = "/080/popping-smoke.jpg"
imagealt = "Popping Smoke"
imagecap = ""

+++

This week I announced [I am leaving SJ Technologies](https://twitter.com/ChrisShort/status/1006966230186627072) on June 22, 2018. It's not an easy decision either. I was pretty happy at SJ but, when I announce where I'm landing everyone will completely understand why I'm making the move. I also finished my NEXUS application this week. It made me realize that I have a problem: I change jobs too often. A lot of folks have said that and I've always discredited it slightly. But, when I look back since I've left the Air Force there's a lot of [resume](https://chrisshort.net/resume-cv/) there. What's the issue here? Clearly it's me. Or is it? There are some legit reasons in all of these job changes (pay raises, acquisitions, etc.). But, at some point, it makes you wonder, "WTF is my problem?" I'd like to say that I am on a journey of continual improvement. But, to be honest, I want to be well compensated and work for a great team at Google, Red Hat, Facebook, GitLab, or Linux Foundation. Every job is a step towards that goal. Life is weird, opportunities come and go, and I've been working towards a goal.

[**Webinar: Continuous Delivery with Docker, Kubernetes, and GoCD**](https://info.thoughtworks.com/Continuous-Delivery-Docker-Kubernetes-webinar)  
Docker and Kubernetes provide the platform for organizations to get software to market quickly. In this webinar, you will get a practical guide in designing a Docker-based CD pipeline on Kubernetes with GoCD. *SPONSORED*

## Events

[Chaos Conf](https://chaosconf.splashthat.com/)  
Date: 2018-09-28  
Chaos Conf looks super awesome. Opening the event will be Adrian Cockcroft, VP AWS, who called 2018 "The year of #chaosengineering". Closing out the night will be Jessie Frazelle, one of the top #containers experts on the planet currently at Microsoft.

[AnsibleFest 2018](https://www.ansible.com/ansiblefest)  
Date: 2018-10-02 through 2018-10-03  
AnsibleFest is the annual user conference for the Ansible community and Red Hat Ansible Automation users. For the first time, we've expanded to two-days, jam-packed with content covering all aspects of IT automation, whether you're just getting started or already an advanced automation professional.

## People

['Very Lonely.' The Unsettling Hum of Silicon Valley's Failure to Hire More Black Workers](https://www.bloomberg.com/news/articles/2018-06-08/tech-companies-still-aren-t-hiring-black-workers): Among eight large firms, the portion of black employees in technical roles has risen less than a percentage point since 2014.

[What Managers Can Do to Keep Women in Engineering](https://hbr.org/2018/06/what-managers-can-do-to-keep-women-in-engineering): "Many women tied their ability to stay in the field to their inclusive immediate work group — specifically, the care and peer support they received from line managers and colleagues."

[DevOps Newsletters](https://devopsnewsletters.com/): Ever wonder if you're missing some critical piece of information? I made DevOps Newsletters as a one stop shop for all your newsletter needs. If there's a newsletter that you think should be on this list, let me know!

[Women Won't Achieve Equality In The Professional World Until Dads Achieve Equality As Parents](https://www.refinery29.com/2018/06/201868/sara-mauskopf-winnie-fathers-day): "Prioritizing a woman's career over a man's was considered revolutionary even 20 years ago, but with 90% of new parents being millennials now, it's not so unusual anymore."

[GM will soon have a female CFO and CEO. That's rare](http://money.cnn.com/2018/06/13/news/companies/gm-woman-ceo-cfo/index.html): This is pretty awesome.

[IT executives! Take the lead in DevOps transformations](https://about.gitlab.com/2018/06/14/gary-gruver-interview-post/): Gary Gruver, author of "Starting and Scaling DevOps in the Enterprise," shares his thoughts on the role of executives in a DevOps transformation.

[Just How Bad Is Business Travel for Your Health? Here's the Data.](https://hbr.org/2018/05/just-how-bad-is-business-travel-for-your-health-heres-the-data): Yep. Business travel is terrible for you.

## Process

[Netflix suffers first massive global outage](https://news.alphastreet.com/netflix-suffers-first-massive-global-outage/): The good news is that this isn't a critical service. The bad news is Netflix has a ton of engineers, code, and processes in place to prevent this sort of thing from happening. This. Shit. Is. Hard.

[MYTHS PROGRAMMERS BELIEVE](https://atilanevesoncode.wordpress.com/2018/06/12/myths-programmers-believe/)

[CI/CD with Kubernetes](https://thenewstack.io/ebooks/kubernetes/ci-cd-with-kubernetes/): A new Kubernetes e-book from The New Stack

[Documentation for DevOps: A DevOpsDays Open Space Writeup](https://medium.com/@wiredferret/documentation-for-devops-a-devopsdays-open-space-writeup-76f088ca2c3c): Docs in DevOps are a big deal but, we're always terrible about writing them and/or reading them. Heidi helps us fix that.

[Kubernetes Day 2 Operations: AuthN/AuthZ with OIDC and a Little Help From Keycloak](https://medium.com/@mrbobbytables/kubernetes-day-2-operations-authn-authz-with-oidc-and-a-little-help-from-keycloak-de4ea1bdbbe): Authentication and Authorization explained by CNCF Ambassador, Bob Killen.

[The Practice of System and Network Administration with Tom Limoncelli](http://runasradio.com/Shows/Show/577): "The conversation dives into providing value to the organization, both in the form of keeping the employees productive, as well as safe and secure."

[Serverless Impacts on Business, Process, and Culture](https://thenewstack.io/serverless-impacts-on-business-process-and-culture/)

[Microsoft's failed attempt on Debian packaging](https://www.preining.info/blog/2018/06/microsofts-failed-attempt-on-debian-packaging/): I have felt this pain before. I tore Microsoft's Hyper-V extension RPM apart one day a few years ago.

[5 microservice testing strategies for startups](https://opensource.com/article/18/6/five-microservice-testing-strategies-startups): Testing microservices isn't easy, but the benefits make it worthwhile. Here are five strategies to consider.

[How to Prevent Your Users from Using Breached Passwords](https://developer.okta.com/blog/2018/06/11/how-to-prevent-your-users-from-using-breached-passwords): "The new NIST recommendations mean that every time a user gives you a password, it's your responsibility as a developer to check their password against a list of breached passwords and prevent the user from using a previously breached password."

[How Spotify is migrating from an in-house Docker orchestration platform to Kubernetes](https://www.ciodive.com/news/how-spotify-is-migrating-from-an-in-house-docker-orchestration-platform-to/525465/): The company started small, experimenting with a few services on Kubernetes clusters then moving up to more complex workloads and self-service migration.

## Tools

[Monitoring with Prometheus by James Turnbull](https://www.prometheusbook.com/): The must-buy book of the summer by someone who knows a thing or two about monitoring, James Turnbull.

[Installing and Using Wireguard, obviously with containers](https://blog.jessfraz.com/post/installing-and-using-wireguard/): Do we really need to specify Jess is using containers with her projects? That's a given. Also, Wireguard is cool.

[Ballerina: An API-First Programming Language](https://thenewstack.io/ballerina-an-api-first-programming-language/): "'Ballerina is our approach to addressing integration issues in the marketplace,' said Tyler Jewell, CEO at WSO2"

[Skaffold and Kaniko: Bringing Kubernetes to Developers](https://medium.com/google-cloud/skaffold-and-kaniko-bringing-kubernetes-to-developers-a43914777af9)

[Comprehensive Container-Based Service Monitoring with Kubernetes and Istio](https://www.circonus.com/2018/06/comprehensive-container-based-service-monitoring-with-kubernetes-and-istio/)

[QA Environments on Demand with Kubernetes](https://engineering.dollarshaveclub.com/qa-environments-on-demand-with-kubernetes-5a571b4e273c)

[New NOVA Filesystem](https://www.linuxjournal.com/content/new-nova-filesystem): A log-based filesystem for NVRAM

[Lenovo Crammed A Hexa-Core CPU And 128GB Of Memory Into A Laptop](https://www.tomshardware.com/news/lenovo-thinkpad-p52-mobile-workstation,37292.html): Now you can run Slack AND Chrome.

[It's 2018 and USB Type-C is still a mess](https://www.androidauthority.com/state-of-usb-type-c-870996/): USB-C is the connector we wanted but it has a lot of awful implementation details.

[sethvargo/vault-kubernetes-authenticator](https://github.com/sethvargo/vault-kubernetes-authenticator): An app and container for authenticating services to HashiCorp Vault's via the Kubernetes auth method

[kubernetes-incubator/external-dns](https://github.com/kubernetes-incubator/external-dns): You can now use CoreDNS as an external DNS provider 👀

[google/gif-for-cli](https://github.com/google/gif-for-cli): Takes in a GIF, short video, or a query to the Tenor GIF API and converts it to animated ASCII art.

[Microsoft/Freeflow](https://github.com/Microsoft/Freeflow): High-performance container overlay networks on Linux. Enabling RDMA (on both InfiniBand and RoCE) and accelerating TCP to bare metal performance. Freeflow requires zero modification on application code/binary.

## Jobs

[DevOps Engineer at TiVo in Durham, NC](http://jobs.jobvite.com/careers/tivo/job/o1PA7fwh?__jvst=Employee%20Referral&__jvsd=srq0nhw0&__jvsc=Twitter&bid=ndUrYFwG)  
As a DevOps Engineer, you'll be part of a small operations team responsible for engineering and maintaining the production infrastructure for Tivo's Advanced Search and Recommendations platform in the cloud and on-premises.

## DevOps'ish Tweet of the Week

{{< tweet 1006619292987731969 >}}
