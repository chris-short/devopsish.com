+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2017"]
date = 2017-05-07T13:01:01.038Z
description = ""
draft = false
slug = "022"
tags = ["devops", "cloud native", "open source", "kubernetes", "serverless", "intel", "women in tech", "google"]
title = "022: Week of 1494129600"
image ="https://shortcdn.com/file/devopsish/tulips.jpg"
imagealt = "I ❤️ Tulips"
aliases = [
    "devopsish-022-week-of-1494129600-4bee6dbfd01d"
]

+++

[Concerns about Kubernetes Community newcomers](https://groups.google.com/forum/#!topic/kubernetes-dev/k58OyLT4wAU) dominated news this week. An established, well respected member of the Kubernetes community felt unwelcome. Someone they have had bad experiences with in the past was trying to work in the same space the well respected member was in (as part of their day job no less). The community huddled and decided that the new member was not welcome due to past issues. The Kubernetes Team's decision was a huge sigh of relieve. But this does point to a larger issue with Codes of Conduct and how to enforce them outside of the community. One of my concerns (which I'm still trying to address), is how to handle Code of Conduct violators. Asking them to leave could be met with a, "No." Then what?

## Department of Choice Concepts

[5 Common Misconceptions of Serverless Technology](https://devops.com/5-common-misconceptions-serverless-technology/) from DevOps.com (yes, there are still servers)

[Gene Kim's 7 secrets of DevOps success](https://techbeacon.com/gene-kims-7-secrets-devops-success):

1. Change often begins in operations
2. DevOps transformations start small — but not too small
3. Business-savvy technologists take the lead
4. DevOps change agents take risks
5. DevOps demands a culture of trust
6. DevOps expansion requires leaders to evolve
7. CIOs are key enablers of DevOps

[octoDNS is a tool for managing DNS across multiple providers](https://github.com/github/octodns/). It allows you to abstract away the complexity of syncing records between DNS providers. Now you can easily diversify your DNS!

[What's not Actionable & Business Critical Shouldn't Ring: Building the Right Alerting System](https://thoughts.t37.net/whats-not-actionable-business-critical-shouldn-t-ring-building-the-right-alerting-system-e8f4b085a2cb) by [Fred 🤷‍♂️](https://medium.com/@fdevillamil)

[Jonathan Mainguy always wanted his website to be a CLI](https://jmainguy.com/index.php/i-wrote-httpssoh-re-from-scratch-go-check-it-out/). In [DevOps'ish 021](/021/) Jonathan found the piece he needed to make this a reality; GoTTY. He is doing some interesting things and it's worth a peek. Go to [https://soh.re/](https://soh.re/) to tinker with Jonathan's new website.

[Using the Strict-Transport-Security header](https://jvns.ca/blog/2017/04/30/using-strict-transport-security/) by Julia Evans

[Kryptonite](https://krypt.co/) is a mobile app and [Go application](https://github.com/kryptco/kr) to store your private SSH keys on your mobile device. This sounds like a horrible idea to me but maybe you could have a use for it.

[kubectx: a tool to switch between Kubernetes contexts](https://ahmet.im/blog/kubectx/) by Ahmet Alp Balkan

[Buffalo now has automated Docker images that can be used for building, testing, deploying, etc.](https://blog.gobuffalo.io/buffalo-docker-images-ff3938dcaa53) by [Mark Bates](https://medium.com/@markbates)

FINALLY!!! [Truly Seamless Reloads with HAProxy — No More Hacks!](https://www.haproxy.com/blog/truly-seamless-reloads-with-haproxy-no-more-hacks/)

[Sysadmins: Say No to Compulsive Tuning Disorder](http://www.networkcomputing.com/data-centers/sysadmins-say-no-compulsive-tuning-disorder/1771784643). I know I suffer from this sometimes. I need to set a reminder to read this every Wednesday morning or something.

## Department of Data Defense

[David Marcus sent out a note about last weekend's Facebook Messenger outage](https://www.facebook.com/davidm/posts/10158776496615195). I love people being open and honest about their outages.

[A human induced error in a Swedish network brought down a chunk of the web served by Cloudflare in the US](https://www.theregister.co.uk/2017/05/02/telia_hiccups_cloudflare_falls_over/). Network configuration validation and automation need to happen sooner rather than later.

The [Intel AMT Vulnerability](https://www.tenable.com/blog/rediscovering-the-intel-amt-vulnerability) is super easy to invoke. It affects [a wide swath of Intel chips](https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00075&languageid=en-fr).

## Department of Discussion

[Triangle DevOps](https://www.meetup.com/Triangle-DevOps/events/238883192/) is welcoming **Nirmal Mehta**, Chief Technologist in the Strategic Innovations Group at Booz Allen Hamilton specializing in research, implementation, and integration of emerging technologies to Booz Allen's federal government client base. RSVP for the May 17th Meetup if you are interested in attending. I expect there will be a waiting list.

I have been invited to speak at Todd Lewis' Open Source South Carolina Meetup on May 23, 2017. Feel free to [RSVP to A Night of DevOps](https://www.meetup.com/Open-Source-South-Carolina/events/239747095/). I intend to do a live demo that includes detonating [chrisshort.net](https://chrisshort.net) and rebuilding it with two (maybe three) commands because DevOps is dope.

## Department of Happy Little Clouds

[70% cheaper Kubernetes cluster on AWS](https://carlosbecker.com/posts/k8s-sandbox-costs/) by Carlos Alexandro Becker

[CoreOS and Ticketmaster collaborate to bring AWS Application Load Balancer support to Kubernetes](https://coreos.com/blog/alb-ingress-controller-intro)

This week's [Google Cloud Platform Podcast](https://www.gcppodcast.com/) with [Chen Goldberg](https://overcast.fm/+Fd_p6Ocqw) was quite remarkable. Learning more about how Google is driving Kubernetes use in Google while still keeping it a community product is awesome.

[AWS EC2 instances got a little cheaper this week](https://aws.amazon.com/blogs/aws/ec2-price-reductions-reserved-instances-m4-instances/) which is awesome.

## Department of Sane Workplaces

[Thousands of Veterans Want to Learn to Code — But Can't](https://backchannel.com/thousands-of-veterans-want-to-learn-to-code-but-cant-7ed60c167a61) because code schools are not covered by Veterans' GI Bills. The coding school at UNC I looked at attending was so expensive I pretty much could never afford it.

![Believe by The Oatmeal](/022/oatmeal-believe.png)  
*Believe by The Oatmeal*

[O'Reilly's 2016–2017 Web Salary Survey](https://www.oreilly.com/ideas/2016-2017-web-salary-survey) is out. An interesting stat from the survey is that California's average salary is a third higher than the US average. [According to CareerTrends](http://cost-of-living.careertrends.com/d/d/California), the cost of living in Silicon Valley is 40–53% higher than the national average. That math just doesn't work.

Meanwhile, [Ansible is the highest-paying DevOps skill](http://insights.dice.com/2017/04/10/which-devops-skills-pay-most/) according to a Dice survey.

[Think there aren't qualified women in tech? Here are 1,000 names. No more excuses.](https://docs.google.com/spreadsheets/d/1opOWf8lMYOvBk6ou0RBlAt5jfyGvEbTZ1f_wxDs8Lno/htmlview)

[The Tech Pledge](https://thetechpledge.com/): "We have helped organize a number of conversations among workers at tech companies and arrived at the following draft of a pledge they'd like their companies to commit to."

[Francesc created a Twitter list of #womenintech](https://twitter.com/francesc/status/859865128908541954) because someone told him it was hard to find women in tech. [DevOps'ish 014](/014/) has a fantastic list of some of the fantastic people that have influenced and helped me over the course of my DevOps journey. SPOILER: They are all women.

## Not DevOps But Still Cool

[The Setup interviewed Fog Creek's Jenn Schiffer](https://usesthis.com/interviews/jenn.schiffer/)

## DevOps'ish Tweet of the Week

{{< tweet 859922360077623298 >}}
