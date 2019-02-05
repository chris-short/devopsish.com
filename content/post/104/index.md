+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2018-12-02T07:00:00Z
description = "DevOps for All, Requirements, Discord Acquisition Coming, Kubernetes Myths, Service Meshes, and More"
draft = false
slug = "104"
tags = ["weekly", "devops", "newsletter", "cloud native", "cloud", "open source", "kubernetes", "automation", "red hat", "ansible", "security", "serverless", "AWS"]
title = "104: AWS (roasting Oracle), Kubernetes, Open Source in 2018, Oh... Google, Breaches, and More"

+++

Did you know that [Chef had layoffs](https://www.geekwire.com/2018/chef-cutting-10-jobs-amid-ongoing-shift-new-application-focused-product-strategy/)? I heard but I didn't think much of it. This week I got a text from [Chris Bailey](https://www.meetup.com/triangle-devops/) who told me another friend got laid off from Chef. Well, that sucks. But, wait, I can do something about that, right?

I'd like to introduce you to **Mark Mzyk** ([LinkedIn](https://www.linkedin.com/in/markmzyk/) | [Twitter](https://twitter.com/mzyk83)). Mark is an, "Engineering Manager looking for his next thing." Mark handed over Triangle DevOps to Chris Bailey and I. He is incredibly organized, intelligent, and a good human. Mark has spent sixteen years in Engineering, the last three have been as a manager. Mark is looking for a new place to call home. The organization should have good leadership with a vision and morals that would make your mom proud. Mark is available immediately. I'd highly recommend you reach out ASAP.

[**Spin up a Continuous Delivery server in less than 5 minutes**](https://www.gocd.org/test-drive-gocd/)  
Trying out new continuous delivery tools can take some time, so the team at GoCD created a quick start option for new users to spin up a GoCD server in under 5 minutes. [Try now](https://www.gocd.org/test-drive-gocd/). *SPONSORED*

[**Webinar with Shannon Lietz: DevSecOps: Finding the Adversaries in Our Midst**](https://info.signalsciences.com/devsecops-finding-the-adversaries-in-our-midst-webinar?utm_medium=newsletter&utm_source=devopsish)  
Discover how you can get greater visibility into how and where you’re being attacked, and use that visibility to build, create, and deploy sites that protect what your business cares about. *SPONSORED*

[**The real story on container, cloud, and data adoption**](https://www.oreilly.com/pub/cpc/175842)  
Poll results reveal where and why organizations choose to use containers, cloud platforms, and data pipelines. *SPONSORED*

{{< sponsor-blurb >}}

## People

[We are Google employees. Google must drop Dragonfly.](https://medium.com/@googlersagainstdragonfly/we-are-google-employees-google-must-drop-dragonfly-4c8a30c5e5eb) — "We are Google employees and we join Amnesty International in calling on Google to cancel project [Dragonfly](https://theintercept.com/2018/08/01/google-china-search-engine-censorship/)." Let's face it, folks, censorship is terrible. There are [millions of Chinese citizens moving in with Chinese Uighurs to spy on them](https://www.usatoday.com/story/news/2018/11/15/china-diplomats-congress-muslim-persecution-rubio-uighur/2010636002/). The US Revolution was literally fought over stuff like this. It goes against the very fabric of freedom to aid in the creation of a wholly censored internet. It is highly likely that Chinese teenagers likely have no idea that [something happened in 1989](/104/china-89.pdf) that led to the putting down of over 10,000 people. US companies should not be in the business of aiding oppressive regimes oppress their people. China might be a market everyone wants to be in but, at what cost, Google?

[Google Employees: Our Executives Engaged in Abuse. Don’t Let Kink and Polyamory Be Their Scapegoats.](https://medium.com/s/story/google-employees-our-executives-engaged-in-abuse-dont-let-kink-and-polyamory-be-their-scapegoats-9099d473e80e) — A New York Times report exacerbated stigma while bringing wrongdoing to light. As if Dragonfly weren't enough, Liz Fong-Jones reminds us change is needed desperately at Google.

[SURPRISE: Alibaba's Jack Ma outed as member of China's Communist Party](https://www.businessinsider.com/alibaba-jack-ma-outed-as-a-member-of-china-communist-party-2018-11) — I'm not sure why this is a surprise. I don't think the richest person in China wouldn't be a party member. I'm more surprised this surprises people.

[Microsoft wins $480M contract to supply U.S. Army with 100K HoloLens headsets](https://www.geekwire.com/2018/microsoft-wins-480m-contract-supply-u-s-army-100k-hololens-headsets/) — Got my eyes on you too, Microsoft.

[Amazon Web Services' Andy Jassy roasts Oracle's Larry Ellison](https://www.businessinsider.com/amazon-web-services-andy-jassy-roasts-oracle-larry-ellison-2018-11)

{{< tweet 1067814465293422595 >}}

[How to Deal with Difficult People on Software Projects](https://people.neilon.software/) — You can explore these Problem Personalities with the [visual map](https://people.neilon.software/). This could come in handy.

[The Science of the Job Search, Part VII: You Only Need 50% of Job “Requirements”](https://talent.works/blog/2018/11/27/the-science-of-the-job-search-part-vii-you-only-need-50-of-job-requirements/) — A lot of data here but basically, "Apply for jobs once you match 50% of job requirements."

[How to Manage Morale When a Well-Liked Employee Leaves](https://hbr.org/2018/11/how-to-manage-morale-when-a-well-liked-employee-leaves) — Remain patient, celebrate, ask for candor, and be ready to take some criticism. Take all this and work through what's next with the remaining team together.

[Open Source is Not About You](https://gist.github.com/richhickey/1563cddea1002958f96e7ba9519972d9) — This is bigger than all of us.

[9 top tech recruiting mistakes to avoid](https://opensource.com/article/18/11/top-tech-recruiting-mistakes-avoid) — We round up common mistakes tech recruiters make and a few best practices to adopt instead.

[Twitter: Friend or Foe? (Episode 30)](http://communitypulse.io/30-twitter/) — "Twitter, Facebook, Instagram, LinkedIn…these are all major parts of what we use every day to stay in touch with the communities we are involved in, personally and professionally. What happens though when those lines blur? When something you say from your personal life gets picked up by people involved in your professional life? Is it all worthwhile?"
{{< adsense-inarticle >}}

## Process

[Dell Systems Hacked to Steal Customer Information](https://www.bleepingcomputer.com/news/security/dell-systems-hacked-to-steal-customer-information/) — To which Marriott said, "Hang on. Hold my beer."

[Marriott Hacking Exposes Data of Up to 500 Million Guests](https://www.nytimes.com/2018/11/30/business/marriott-data-breach.html) — We get to sign up for yet another monitoring service. Yay!

[Half of all Phishing Sites Now Have the Padlock — Krebs on Security](https://krebsonsecurity.com/2018/11/half-of-all-phishing-sites-now-have-the-padlock/) — Be careful out there. Tell your friends too.

[Exclusive interview: How CEO Andy Jassy aims to keep AWS atop the cloud](https://siliconangle.com/2018/11/26/exclusive-interview-ceo-andy-jassy-aims-keep-aws-atop-cloud/) — The interview in which Andy Jassy admits AWS will, "[W]e can never hire enough good people in those areas to have the coverage that we ultimately want." Wow... Imagine having that problem.

[Amazon will be off all Oracle databases by end of 2019, says AWS chief](https://www.cnbc.com/2018/11/28/amazon-will-be-off-all-oracle-databases-by-end-of-2019-says-aws-chief.html) — And just like that, AWS is done with Oracle. If AWS can do it, anyone can potentially dump Oracle.

[Bitcoin-stealing code inserted into popular GitHub-hosted JavaScript library](https://siliconangle.com/2018/11/26/bitcoin-stealing-code-inserted-popular-github-hosted-javascript-library/) — node library Event-Stream was compromised

[Open Source Software Is Under Attack; New Event-Stream Hack Is Latest Proof](https://blog.sonatype.com/open-source-software-is-under-attack-new-event-stream-hack-is-latest-proof) — The software supply chain is under attack. Caring only about software delivery inside your network boundary is not enough. Sadly, your artisanal, vintage software probably has a library that could be exploited. Think about how to handle that BEFORE it happens.

[Asana, a work management platform, nabs $50M growth round at a $1.5B valuation](https://techcrunch.com/2018/11/29/asana-a-work-management-platform-nabs-50m-growth-round-at-a-1-5b-valuation/) — Congrats to the folks at Asana.

[Why Kubernetes Makes Lyft Rides What They Are Today](https://thenewstack.io/why-kubernetes-makes-lyft-rides-what-they-are-today/) — "Ride-sharing firm Lyft will continue to rely heavily on Kubernetes and microservices in the race to offer mobility solutions that should eventually include AI-piloted cars in the very near future."

[Amazon's homegrown 2.3GHz 64-bit Graviton processor was very nearly an AMD Arm CPU • The Register](https://www.theregister.co.uk/2018/11/27/amazon_aws_graviton_specs/) — A little bit of history and a little more info on customized SoC

[Announcing the First AWS Security Conference: AWS re:Inforce 2019 | AWS Security Blog](https://aws.amazon.com/blogs/security/announcing-the-first-aws-security-conference-aws-reinforce-2019/) — "The inaugural AWS re:Inforce, a hands-on gathering of like-minded security professionals, will take place in Boston, MA on June 25th and 26th, 2019 at the Boston Convention and Exhibition Center. The cost for a full conference pass will be $1,099."

[The Amazon Effect on Open Source - The New Stack](https://thenewstack.io/the-amazon-effect-on-open-source/) — "To me, 2018 will be remembered as open source’s breakthrough year. It is the year in which open source companies were able to prove their business value beyond a shadow of a doubt."

[All the Serverless announcements at re:Invent 2018](https://serverless.com/blog/reinvent-2018-serverless-announcements/) — BYOR (Bring Your Own Runtime), Lambda Layers, managed Kafka, and more!

[The don'ts of software engineering](https://www.imaginarycloud.com/blog/the-donts-of-software-engineering/) — Some pretty obvious ones but if you have some new folks on your team it's a good read.
{{< adsense-inarticle >}}

## Tools

[What, No Python in RHEL 8 Beta?](https://developers.redhat.com/blog/2018/11/27/what-no-python-in-rhel-8-beta/) — "Ideally, people will get used to explicitly typing python3 or python2. However for those that want an unversioned command,  let them chose from the beginning which version of Python they actually want. So, yum install python results in a 404." `yum install @python36` or `yum install @python27` are your friends in RHEL 8. There is also a [system-level Python installed](https://www.ansible.com/blog/integrating-ansible-and-red-hat-enterprise-linux-8-beta) (for things like system tools and Ansible).

[Managing containerized system services with Podman](https://developers.redhat.com/blog/2018/11/29/managing-containerized-system-services-with-podman/) — One of these days I will get to drop [petty.company](http://petty.company)'s container runtime and use something without a daemon running. Oh wait! I already can.

[Five most important cloud announcements at AWS re:Invent 2018](https://www.techrepublic.com/article/five-most-important-cloud-announcements-at-aws-reinvent-2018/) — ARM CPUs (not cheap though), bigger network pipes, and P3dn (holy smokes) are my big three. Outposts is a big deal that shows cloud-only is a greenfield dream and not our beige reality. Plus, AWS Ground Station shows, as [Corey Quinn](https://lastweekinaws.com/) said, "AWS Ground Station is an entire service offering around *receiving satellite telemetry from orbit* that they launched. If they'll address that use case, "customers who don't want to move into the cloud" is certainly within their purview of addressable market."

[What’s new in Kubernetes 1.13?](https://sysdig.com/blog/whats-new-in-kubernetes-1-13/) — Kubernetes 1.13 will be out on December 03 2018. `kubectl diff` going beta, dope. AWS ALB ingress controllers, dope. Better Azure support, dope. Drop support for etcd2?!? Holy smokes! That's awesome and [an enormous amount of work went into this](https://github.com/kubernetes/enhancements/issues/622).

[Kubernetes 101 part 2: Deploying apps to Kubernetes Cluster](https://medium.com/rackbrains/kubernetes-101-part-2-deploying-apps-to-kubernetes-cluster-fcad2615d59)

[Git aliases for lazy developers](https://bitsofco.de/git-aliases-for-lazy-developers/) — I just like the sound of *gac*, `alias gac="git add . && git commit -m"`

[The mysterious tale of 0.0.0.0:tcp://172.20.244.217:8080](https://medium.com/@lizrice/the-mysterious-tale-of-0-0-0-0-tcp-172-20-244-217-8080-8c2b3fb09498) — We don't deserve Liz Rice.

[Kubernetes essential guide: 10 must-reads](https://enterprisersproject.com/kubernetes-guide) — Kubernetes, containers, and automation have become crucial to IT goals – and practically beg for continuous learning. Consider this a mini-class

[CI/CD with Rancher Pipelines and Self-hosted GitLab](https://blog.kubernauts.io/ci-cd-with-rancher-pipelines-and-self-hosted-gitlab-b17248294fda)


[Cluster DNS: CoreDNS vs Kube-DNS](https://coredns.io/2018/11/27/cluster-dns-coredns-vs-kube-dns/) — CoreDNS > Kube-DNS. Believe it, we've been using a CoreDNS based DNS solution for a while here in the Short household. You probably should too (and yes, it's a full-fledged DNS server).

[Buildah version 1.5 Release Announcement](https://buildah.io/releases/2018/11/28/Buildah-version-v1.5.html) — Buildah keeps getting better and better

[http3.md](https://gist.github.com/sericaia/b972da882745071a3ebbb091f38837ad) — Some notes on QUIC... I mean HTTP/3

[Bitnami Engineering Portal: Announcing the Bitnami Kubernetes Production Runtime (BKPR)](https://engineering.bitnami.com/articles/announcing-the-bitnami-kubernetes-production-runtime-bkpr.html) — A runtime with all the bits you'd expect from a total solution; monitoring, logging, HTTPS ingress

[MinaOTP/MinaOTP-Shell: TOTP authenticator implement as a terminal tool](https://github.com/MinaOTP/MinaOTP-Shell)

[liangw89/faas_measure: A framework for measuring coldstart latency, io/network throughput, and more in AWS Lambda](https://github.com/liangw89/faas_measure)

## DevOps'ish Tweet of the Week

{{< tweet 1068301077303500805 >}}