+++

author = "Chris Short"
categories = ["Newsletter"]
date = 2017-01-15T07:32:00.595Z
description = ""
draft = false
slug = "006"
tags = ["devops", "cloud native", "open source", "kubernetes", "linux", "containers"]
title = "006: Week of 1484456400"
image = "/006/snowy-mountain-lake.jpg"
imagealt = "Snowy Mountain Lake"
aliases = [
    "006-week-of-1484456400-ceb344fd9ab0"
]

+++

Welcome to this week's edition of [**DevOps'ish**](/) where we cover Dev, Ops, and all the ish in between.

I hope you had a productive week and are looking forward to another productive week ahead!

So much [**DevOps**](/) , so little time.

## Department of Assemblage Obtainment

[Trello was acquired by Atlassian for a whopping $425 million](http://www.forbes.com/sites/alexkonrad/2017/01/09/atlassian-acquires-popular-team-productivity-app-trello-for-425-million/). This is an acquisition that makes a lot of sense for Atlassian. Trello could be used as a sort of gateway drug into the much more complicated Atlassian software products.

[Chris Lattner, the creator of Swift, is leaving Apple and joining the Autopilot team at Tesla](https://9to5mac.com/2017/01/10/swift-chris-lattner-leaving-apple/). According to a [Business Insider](http://www.businessinsider.com/how-apples-culture-of-secrecy-wears-down-its-top-developers-2017-1) source, Chris Lattner left because he felt, "He always felt constrained at Apple in terms of what he could discuss publicly." But, [Chris vehemently denied this report](https://twitter.com/clattner_llvm/status/819974025371787264) in a tweet saying, "Folk just want to make 🍎 look bad. 😠".

[Ashley McNamara](https://twitter.com/ashleymcnamara) maintains a "[Curated list of resources for budding developers](http://ashleymcnamara.github.io/learn_to_code/)" that is a consolidated treasure trove of language resources.

[blockloop has a good post on bash and the terminal](https://www.blockloop.io/mastering-bash-and-terminal). It's pretty basic stuff and a little macOS centric. But, it does discuss my two favorite CLI utilities in macOS: pbcopy and pbpaste.

{{< mc >}}

## Department of Choice Concepts

I don't know how I missed this last week but Flickr (yes, Flickr) has a great post about how they [tried to go through 2016 without buying new storage systems](https://code.flickr.net/2017/01/05/a-year-without-a-byte/).

[LinkedIn has a vending machine for IT equipment](https://theagileadmin.com/2017/01/10/but-how-can-it-do-devops/) much like factories have vending of parts and PPE. That's one way to automate IT functions.

![Photo Courtesy [the agile admin](https://theagileadmin.com/2017/01/10/but-how-can-it-do-devops/)](/006/linkedin-vending-machine.jpg)  
*Photo Courtesy [the agile admin](https://theagileadmin.com/2017/01/10/but-how-can-it-do-devops/)*

Tom Croucher of Uber brings us a "I've seen the light!" moment in [*Don't gamble when it comes to reliability*](https://www.oreilly.com/ideas/dont-gamble-when-it-comes-to-reliability)

## Department of Dafuq

[Dell EMC is planning to layoff a big chunk of its workforce](http://www.theregister.co.uk/2017/01/12/emc_layoffs/) post-merger. The cuts could affect as much as a quarter of Dell EMC employees (that is up to 35,000 people). Insiders say things have been a little awkward inside the company since the beginning of their fiscal Q4.

## Department of Data Defense

[Docker 1.12.6 was released](https://github.com/docker/docker/releases/tag/v1.12.6) this week to address [CVE-2016–9962](http://seclists.org/fulldisclosure/2017/Jan/21). The [vulnerability was pretty gnarly](https://bugzilla.suse.com/show_bug.cgi?id=1012568): "runC passes a file descriptor from the host's filesystem to the 'runc init' bootstrap process when joining a container. This allows a malicious process inside a container to gain access to the host
filesystem with its current privilege set." [Red Hat demonstrated that SELinux could have saved you](http://rhelblog.redhat.com/2017/01/13/docker-0-day-stopped-cold-by-selinux/) from this bug ever happening in your environment.

[Ansible had a pretty gnarly bug announced this week](http://www.theregister.co.uk/2017/01/11/ansible_patches_own_the_farm_vulnerability/). CVE-2016–9587 was discovered by [Computest](https://www.computest.nl/advisories/CT-2017-0109_Ansible.txt). According to James Cammarata, Ansible Lead/Sr. Principal Software Engineer, "[a compromised remote system being managed via Ansible can lead to commands being run on the Ansible controller (as the user running the ansible or ansible-playbook command).](https://groups.google.com/forum/#!topic/ansible-devel/SyrgcUySAIQ)" Multiple release candidates came out during the week. [A stable 2.x release should be coming January 16, 2017](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!msg/ansible-project/ydfEh11hlXA/eaOPE3p_AQAJ). If you are still running Ansible 1.x code, you should upgrade to the 2.1.4 or 2.2.1 release as soon as possible.

## Department of Discussion

There was a great crowd at the [Triangle Kubernetes and OpenShift Meetup](https://www.meetup.com/Triangle-Kubernetes-Meetup/) this past week. I got some helpful tips from Thomas Wiest about running Kubernetes in AWS. I have made [my notes from the Meetup available](https://www.evernote.com/l/AAV9Qz3Q7IhLCqRM05VZbis3oJm6duhVdi0).

![Photo courtesy of [Red Hat OpenShift](https://twitter.com/openshift/status/819690494393520131)](/006/triangle-openshift-meetup.jpg)  
*Photo courtesy of [Red Hat OpenShift](https://twitter.com/openshift/status/819690494393520131)*

## Department of Refreshment and Refurbishment

​[Red Hat Enterprise Linux 6.9 beta has been released](http://www.zdnet.com/article/red-hat-enterprise-linux-6-9-beta-out-now/). This release brings TLS 1.2 to the 6.x branch of RHEL which is a very welcomed (albeit late) improvement.

[Go 1.8 RC1 was released](https://groups.google.com/forum/m/#!topic/golang-nuts/tr2ZKSQ42zE) this past week. The feature I'm most excited for is a default $GOPATH. I swear every time I install Go I never remember where I put my $GOPATH so the default will lower the bar to entry for newer folk (and help the senile).

## Not DevOps But Still Cool

The fantastic Hacker News alternative, [**Lobsters](https://lobste.rs/)** is having a membership drive of sorts. If you would like an invite just let me know.

If you are a Linux DevOps person with AWS talents please [consider joining my Global DevOps team](http://solarwinds.jobs/durham-nc/senior-aws-systems-engineer/866A1F89D368408CB7F6F774409D961A/job/).

## Tweet of the Week

This week's one-liner comes courtesy of [Jérôme Petazzoni](https://twitter.com/jpetazzo/status/819288097376583680):

{{< tweet 819288097376583680 >}}
