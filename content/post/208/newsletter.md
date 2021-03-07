+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2021"]
date = 2021-03-07T07:00:00Z
description = "KubeCon problems, tech is the easy part, Okta eats Auth0 whole, Exchange vulns, Digital Ocean IPO, #100DaysOfKubernetes, and more"
draft = false
slug = "208"
tags = ["Kubernetes", "cloud", "cloud native", "hybrid cloud", "KubeCon", "community", "DevOps", "exploit", "open source", "Digital Ocean", "Red Hat", "Kirsten Newcomer", "CNCF Ambassador", "software engineer"]
title = "DevOps'ish 208: KubeCon problems, tech is the easy part, Okta eats Auth0 whole, Exchange vulns, Digital Ocean IPO, #100DaysOfKubernetes, and more"

+++

This week I heard about and witnessed some pretty disgusting behavior in the greater cloud native community. First, I saw a tweet from a CNCF Ambassador saying KubeCon was pay to play (the tweet is gone now but, you better believe they lost a follower that day). If KubeCon were pay to play, I'd have spoken at the last three years of KubeCons. Red Hat spends a shitload of money sponsoring KubeCon and the Linux Foundation. It does not, nor should it ever influence the talk selection process.

Next, I heard firsthand about people jumping into KubeCon track committee members' DMs and chastising them for not selecting their talk. I won't be naming and shaming. They've done that for themselves. But, I can guarantee you, this is not how you want to make a name for yourself in the community.

Oh… Some random Google software engineer got blocked because they did not understand any word I wrote. Then proceeded to put words into my mouth about how the selection process works. At some point in the process, a deciding factor in the talk selection process could be looking for a submitter's online presence (yes, speaker names get Googled routinely). The submission process does involve some links to social media and/or GitHub, for example, if memory serves me right. Building a KubeCon track is a super laborious process that you have to dedicate serious time to in a brief time window. **IT'S HARD WORK**.

Back to my point about online presence; you've got to make sure you're putting your best foot forward these days. Why? Nowadays, there are so many submissions that I think it's like less than 20% of the talks submitted get picked up.

If you've only got a GitHub account out, it's hard to get a great idea of who a speaker is (if they're new to the speaking circuit). I know when I rated talks for KubeCon, quite a few people's names got Googled. A lot of research went into figuring out folks' expertise. Actual digging was ordinary to determine if talks were a sales pitch or legit technical content.

The best thing you can do is the basics. If you've talked at Meetups or other virtual events, show that in your CFP. That's going to give whoever is reviewing your submission a great idea of who you are on stage. The good news is, [some brilliant folks and I are doing a talk about telling your Kubernetes story](https://sched.co/iE6I). This talk will help you get your talk submitted next go-round if you've put in the work in the community and have it documented (yes, I know more work). It makes you stand above a majority of submissions.

Let's put it like this. I've been in the CNCF arena for five or six years now. This will be my first real KubeCon talk. But, I've not even submitted a talk in years because I'm aware of the competition. You have to be too. This is not to say I like the selection process (I don't. I really don't.). But, it's the process for now and mastering it requires more than a CFP. You've got to put in the work, not be self-centered, and then show you have some chops. This ain't your local DevOpsDays. With that being said, I know some folks slant their ratings toward new speakers and topics. Others don't. It's really all in the hands of the track chairs. As is your behavior after the fact.

Note: The [DevOps'ish Solarwinds supply chain compromise Index](https://devopsish.com/solarwinds-supply-chain-compromise/) has some updates this week.

## People

[Rookie coding mistake prior to Gab hack came from site’s CTO](https://arstechnica.com/gadgets/2021/03/rookie-coding-mistake-prior-to-gab-hack-came-from-sites-cto/)  
A former Facebook software engineer turned CTO committing faulty code exposing right wing site’s entire user base. Probably no impact to his employment, I’d bet. That’s a secure pipeline… NOT! 🤣🤣🤣

Go beyond observability hype and get into the specifics of what it means to have [Observability for Developers](https://www.honeycomb.io/guide-observability-for-developers-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=guide-observability-for-developers-devopsish). Which data is actually useful to gather? How should you approach front-end services differently? What should you log and how? We show you what matters.

Ready to try it? [Sign up for free](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). Stop guessing and start knowing with [Honeycomb](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[18F: Digital service delivery | Technical problems are not the hardest ones to solve](https://18f.gsa.gov/2021/03/04/technical-problems-are-not-the-hardest-ones-to-solve/)  
"But in the vast majority of our projects, the technological problem is not the most challenging aspect of the problem we face. When we work on  the technical solution, we often uncover non-technical problems that need to be collaboratively solved by 18F and the partners to ensure the project will be successful." Tech is easy, people are hard —Nirmal Metha

[Senators call on FCC to quadruple base high-speed internet speeds](https://www.theverge.com/2021/3/4/22312065/fcc-highspeed-broadband-service-ajit-pai-bennet-angus-king-rob-portman)  
Long overdue. I know my European readers might grouse at me, but the providers’ capabilities and services provided are at a very high mismatch. This new standard would make innovation and access to knowledge far greater. Opposing this is pretty close to oppression in my book. The internet changed my life. Everyone should have that same opportunity.

['Screen access technology has existed for decades': Visually impaired man sues Dell over 'inaccessible' website](https://www.theregister.com/2021/03/05/giannaros_v_dell/)  
Get with it folks. A11y matters a whole lot.

[GPS jamming around Cyprus gives our air traffic controllers a headache, says Eurocontrol](https://www.theregister.com/2021/03/05/gps_jamming_eurocontrol/)
Unbridled control of enormously powerful jamming equipment makes the air space around the eastern Mediterranean rather dangerous.

## Process

[Okta acquires cloud identity startup Auth0 for $6.5B](https://techcrunch.com/2021/03/03/okta-acquires-cloud-identity-startup-auth0-for-6-5b/?guccounter=1)  
"As Okta announced earnings today after the bell, it revealed that it’s buying cloud identity startup Auth0 for a hefty $6.5 billion. The company had a valuation of $1.92 billion when it raised $120 million led by Salesforce Ventures last July."

[Never wait for a staging environment again](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=title&utm_campaign=20210228) 👩‍💻🧑‍💻👨‍💻👩‍💻  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team's ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. You'll never have to wait around for staging environments again. 💡 [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=20210228) 💡 *SPONSORED*

[cyber.dhs.gov - Emergency Directive 21-02](https://cyber.dhs.gov/ed/21-02/)  
"CISA partners have observed active exploitation of vulnerabilities in Microsoft Exchange on-premises products. Neither the vulnerabilities nor the identified exploit activity is currently known to affect Microsoft 365 or Azure Cloud deployments. Successful exploitation of these vulnerabilities allows an attacker to access on-premises Exchange Servers, enabling them to gain persistent system access and control of an enterprise network." Jesus... I might have to build another [Index](https://devopsish.com/categories/indexes/).

[First Fully Weaponized Spectre Exploit Discovered Online](https://therecord.media/first-fully-weaponized-spectre-exploit-discovered-online/)  
"A fully weaponized exploit for the Spectre CPU vulnerability was uploaded on the malware-scanning website VirusTotal last month, marking the first time a working exploit capable of doing actual damage has entered the public domain."

[In the Clouds: DevSec + SecOps w/ Kirsten Newcomer](https://youtu.be/mxt--OLHDps?t=81)  
I sat down with the brilliant Kirsten Newcomer and talked all things security, Kubernetes, and DevSecOps. We make a pretty good team and the time absolutely flew by.

[DigitalOcean Files For IPO Among A Sea Of SPACs](https://news.crunchbase.com/news/digitalocean-files-for-ipo-among-a-sea-of-spacs/)  
Congrats to my Digital Ocean friends. Always one of my fav providers.

[US roads got more dangerous in 2020 even though we stayed at home](https://arstechnica.com/cars/2021/03/traffic-deaths-rose-8-percent-in-2020-despite-fewer-miles-travelled/)  
"It is tragic that in the US, we took cars off the roads and didn't reap any safety benefits," said Lorraine M. Martin, president and CEO of the National Safety Council. "These data expose our lack of an effective roadway safety culture. It is past time to address roadway safety holistically and effectively, and NSC stands ready to assist all stakeholders, including the federal government." Folks in the US drove 13% less last year and deaths and injuries still went up.

## Tools

[#100DaysOfKubernetes](https://devops.anaisurl.com/kubernetes)  
Watch the introductory video to learn more about the goal and Anaïs Urlichs' idea behind #100DaysOfKubernetes

[[Free Book]](https://launchdarkly.com/the-definitive-guide-to-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) Definitive Guide to Feature Management. Ship Fast. Rest Easy. LaunchDarkly. *SPONSORED*

[Hassle-free multi-tenant K8S clusters management using Argo CD](https://blog.argoproj.io/hassle-free-multi-tenant-k8s-clusters-management-using-argo-cd-7dd35619046a)  
"Finally, the next version of the Argo CD is getting more features that make multi-tenancy easier. The ApplicationSet is one of such features. Stay tuned and don’t hesitate to share your ideas of how Argo CD can be improved!"

[NetworkPolicy Editor: Create, Visualize, and Share Kubernetes NetworkPolicies](https://cilium.io/blog/2021/02/10/network-policy-editor)  
"Over the past years, we have learned a lot about the common challenges while working with many of you in the Cilium community implementing Kubernetes Network Policy. Today, we are excited to announce a new free tool for the community to assist you in your journey with Kubernetes NetworkPolicy: <https://editor.cilium.io>"

[HTTPWTF | HTTP Toolkit](https://httptoolkit.tech/blog/http-wtf/)  
This is the kind of knowledge that got me my first job in the real world. This stuff is relatively static (for tech standards), so once you know it, you know it. But, I read this and learned a few things too.

[Understanding the Kubernetes Event Horizon](https://www.weave.works/blog/understanding-kubernetes-events)  
"Have you ever listened to what your cluster is telling you? Like, really listened?" Also, is your cluster running? Well you better go get it!

[Development on Windows is Painful](https://christine.website/blog/windows-pain-2021-03-03)  
Hell yes, it is. The hoops and loops are all pretty old, which means feedback from devs isn’t entering the product appropriately.

[AdguardTeam/cname-trackers: This repository contains a list of popular CNAME trackers](https://github.com/AdguardTeam/cname-trackers)  
At this point, you should setup a process to start sinkholing these domains. I should point out [EmailOctopus](https://emailoctopus.com/?urli=n6msM) (DevOps'ish's new newsletter service) requested I create a tracking domain. I did, passed their tests, then ripped it out. Your privacy is more important than this newsletter.

[dolthub/dolt: Dolt – It's Git for Data](https://github.com/dolthub/dolt)

[AbsaOSS/k8gb: A cloud native Kubernetes Global Balancer](https://github.com/AbsaOSS/k8gb)

## DevOps'ish Tweet of the Week

[![stephenaugustus on Twitter: "I'm trying to say this in the nicest way possible, but seriously, what is wrong with some of you? I've seen several tweets with people being salty about getting KubeCon talks rejected and gotten multiple reports about Program Committee members being accosted in DMs or meetings."](/images/208-devopsish-tweet-of-the-week.png)](https://twitter.com/stephenaugustus/status/1366823310873436160)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/208/notes/) to see what didn't make it to the newsletter but are still worth your time.
