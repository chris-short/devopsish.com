+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-08-27T11:01:38.892Z
description = ""
draft = false
slug = "038"
tags = ["devops", "cloud native", "open source", "kubernetes", "linux", "containers"]
title = "038: Failure, Linux, Save Your Eyes, Alibaba, and MORE!"
image = "/038/l-b-king-and-company-building-eclipse.jpg"
imagealt = "L.B. King and Company Building in Downtown Detroit during the Eclipse"
aliases = [
    "devopsish-038-failure-linux-save-your-eyes-alibaba-and-more-315fcf916bd9"
]

+++

I began thinking about my talk for [DevOpsDays Raleigh](https://www.devopsdays.org/events/2017-raleigh/welcome/) here in a couple weeks. It's based off an already written piece from March. But any time I write something, after a few months I think of ways I could have written the piece better. The sane thing to do is not revisit it but to continue iterating on it. One overarching fact of not only DevOps but also business is, resisting change is stupid, successful businesses find a way to eliminate existential threats. Sometimes the problem with DevOps is that it isn't close enough to the thing making money; the product (and their teams). Unless you work in highly regulated industries there is a huge incentive to getting things done efficiently. Keep in mind, efficiently does not equate to quickly. Getting things done to meet an arbitrary deadline will usually result in shortcuts being taken, technical debt, and often rework (which is awful at deploy time). There is something incredibly refreshing about being able to identify unforeseen issues and adjust the target date accordingly. But, you have to be careful you're not always aiming for the moon and consistently failing to get to orbit.

**GoCD — open source continuous delivery server**  
GoCD is a continuous delivery tool specializing in advanced workflow modeling and dependency management. It lets you track a change from commit to deploy at a glance, providing superior visibility into your workflow. [It's open source, free to use and download](https://www.gocd.org/?utm_campaign=devops_newsletter&utm_medium=email&utm_source=devopsish&utm_content=go_website&utm_term=). *SPONSORED*

**DevOpsDays Raleigh 2017**  
September 7 and 8, Raleigh, NC USA
What do [Ashley McNamara](http://ashleymcnamara.github.io/learn_to_code/), [Nimal Mehta](https://www.linkedin.com/in/nirmalkmehta/), [Chris Short](https://chrisshort.net), and the legendary [John Willis](https://github.com/botchagalupe/my-presentations) all have in common? They will all be speaking at DevOpsDays Raleigh this year! Receive $5 off with discount code ***MEETUP5*** when registering. [Website](https://www.devopsdays.org/events/2017-raleigh/welcome/) | [Registration](https://www.eventbrite.com/e/devopsdays-raleigh-2017-tickets-34044332515?aff=es2)

**All Things Open 2017**  
October 23 and 24, Raleigh, NC USA
2,500–3,000+ technologists will descend upon the City of Oaks to attend 200+ sessions from nearly as many speakers. Representative from nearly every major technology company in the U.S. will be in attendance as well.
To get 20% off enter code ***DevOpsish20*** when registering to attend.
Website: [https://allthingsopen.org](https://allthingsopen.org)
To Register: [https://allthingsopen.org/register-now](https://allthingsopen.org/register-now)

{{< sponsor-blurb >}}

## People

[Hacker Maps](http://www.hackermaps.org/): A consolidated map of B-Sides, 2600, and other hacker events

[The Value of Failure and Feedback by Jono Bacon](http://www.jonobacon.com/2017/08/21/value-failure-feedback-guide/?imm_mid=0f5aaa&cmp=em-webops-na-na-newsltr_20170825): Like many things, failure has two pieces to it: a *logical* and *emotional* component.

[You must go offline to view this page](https://chris.bolin.co/offline/): An interesting take on why it's so hard for us to get shit done these days.

[Fighting Neo-Nazis and the Future of Free Expression](https://www.eff.org/deeplinks/2017/08/fighting-neo-nazis-future-free-expression): But we must also recognize that on the Internet, any tactic used now to silence neo-Nazis will soon be used against others, including people whose opinions we agree with.

[Melinda Gates: I spent my career in technology. I wasn't prepared for its effect on my kids.](https://www.washingtonpost.com/news/parenting/wp/2017/08/24/melinda-gates-i-spent-my-career-in-technology-i-wasnt-prepared-for-its-effect-on-my-kids/?utm_term=.9dd6ec14df13)


## Process

[Building a CI system for Go, with Jenkins](https://medium.com/@zarkopafilis/building-a-ci-system-for-go-with-jenkins-4ab04d4bacd0): Post on what was performed in order to setup a Jenkins CI pipeline for a new Go project.

[Red Hat and Microsoft Simplify Containers to Help Enterprises Accelerate to the Hybrid Cloud](https://www.redhat.com/en/about/press-releases/red-hat-and-microsoft-simplify-containers-help-enterprises-accelerate-hybrid-cloud): What a time to be alive!

[The Zen of PGP](https://medium.com/@thegrugq/the-zen-of-pgp-6f55d44657dd): A Pragmatic Approach


## Tools

[Happy anniversary, Linux](https://opensource.com/article/17/8/linux-anniversary): A look back at where it all began

[Go 1.9 is released](https://blog.golang.org/go1.9): The most important change to the language is the introduction of type aliases: a feature created to support gradual code repair.

[Developer Tip to Save Your Eyes](https://medium.com/@GarmashNikolay/developer-tip-to-save-your-eyes-f83135baa64c): Do this! Your eyes will thank you.

[Using Kubernetes for Local Development — Minikube](https://medium.com/devopslinks/using-kubernetes-minikube-for-local-development-c37c6e56e3db): This blog post introduces the usage of Kubernetes in development mode.

[Building distributed systems with containers](https://www.oreilly.com/ideas/building-distributed-systems-with-containers): Five questions for Brendan Burns: How containers and cluster management have changed systems development, and common patterns for building distributed systems.

[App Engine firewall, an easy way to control access to your app](https://cloudplatform.googleblog.com/2017/08/introducing-App-Engine-firewall-an-easy-way-to-control-access-to-your-app.html): With App Engine firewall, you simply provide a set of rules, order them by priority and specify an IP address, or a set of IP addresses, to block or allow, and we'll take care of the rest.

[Alibaba becomes 2nd largest hosting company](https://news.netcraft.com/archives/2017/08/22/cloud-wars-alibaba-becomes-2nd-largest-hosting-company.html): As the Cloud Wars heat up, the Chinese Alibaba Group has overtaken DigitalOcean to become the second largest hosting company in the world.

[5 things about programming I learned with Go](http://mjk.space/5-things-about-programming-learned-with-go/)

## Jobs

[**DevOps/Cloud Systems Engineer — StockX — Detroit, MI**](https://stockx.com/jobs#op-193701-devopscloud-systems-engineer)
StockX is looking for an experienced Cloud Systems Engineer, or DevOps Engineer, to accelerate the efficiency of our engineering operations and implement scalable infrastructure. You must be passionate about automating all the things that go into software engineering and technical operations.

[**Director, Software Engineering — Bankrate — Detroit, MI**](http://app.jobvite.com/m?3N1q0jw2)
A manager in an agile environment with strong technical skills. Collaborative leader who will understand our people, business, technology, and customers' needs. Leader who helps drive our culture of empowerment, ownership, and accountability to help develop our team technically and professionally. Identify and successfully implement improvements in our engineering processes, tools, and architecture to enable us to deliver on our key initiatives.

## DevOps'ish Tweet of the Week

{{< tweet 900725820070690819 >}}