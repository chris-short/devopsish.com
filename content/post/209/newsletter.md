+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "GitOps News", "2021"]
date = 2021-03-14T07:00:00Z
description = "Hafnium, dhcpcd needs new maintainer, Beat the Systemic Racism of IT, Google HR issues, OVH disaster, git vulnerability, sigstore and more"
draft = false
slug = "209"
tags = ["Kubernetes", "cloud", "DevOps", "cloud native", "source control", "Git", "Hafnium", "tech", "Microsoft Exchange", "etcd", "code", "engineering", "underrepresented", "AWS", "control plane", "open source", "Hafnium compromise", "AWS", "permissions", "pandemic devastating effect", "Kim Crayton", "Amazon", "Klustered", "Challenger", "dhcpcd", "DevRel", "Antiracist", "Google", "OVH", "KubeCon", "Intel", "sigstore", "Linkerd", "RISC-V"]
title = "DevOps'ish 209: Hafnium, dhcpcd needs new maintainer, Beat the Systemic Racism of IT, Google HR issues, OVH disaster, git vulnerability, sigstore and more"

+++

In a first, there are two DevOps'ish Indexes in flight right now. I did not want this day to ever happen but here we are. Solarwinds and Microsoft both have their hands full. DevOps'ish has your back. Here's all the data points for both incidents so far.

* *NEW* [DevOps'ish Microsoft Exchange Hafnium Compromise Index](/microsoft-exchange-hafnium-compromise-index/)
* [DevOps’ish Solarwinds supply chain compromise Index](/solarwinds-supply-chain-compromise/)

What a time to be alive.

Also, DevOps'ish is 101 subscribers from officially passing the 5,000 subscribers mark. This is a critical point in a newsletter's life. I'd be very appreciative if you forwarded this to a friend, [tweeted](https://twitter.com/intent/tweet?text=I%20read%20DevOps'ish%20and%20you%20should%20too.%20Subscribe%20now!%20devopsish.com/subscribe%20%23devopsish%20%23DevOps%20%23Kubernetes) about the newsletter, or posted something on [LinkedIn](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fdevopsish.com%2Fsubscribe%2F&title=Subscribe%2Cto%2CDevOps'ish&summary=Subcribe%2C+to%2CDevOps'ish!&source=devopsish). Thank you!

## People

[Allan McDonald, Who Refused To Approve Shuttle Challenger Launch, Dead At 83](https://www.npr.org/2021/03/07/974534021/remembering-allan-mcdonald-he-refused-to-approve-challenger-launch-exposed-cover)  
"His job was to sign and submit an official form. Sign the form, he believed, and he'd risk the lives of the seven astronauts set to board the spacecraft the next morning. Refuse to sign, and he'd risk his job, his career and the good life he'd built for his wife and four children.

'And I made the smartest decision I ever made in my lifetime,' McDonald told me. 'I refused to sign it. I just thought we were taking risks we shouldn't be taking.'"

[dhcpcd will need a new maintainer](https://roy.marples.name/archives/dhcpcd-discuss/0003457.html)  
"I have been dealing with cancer for some time and sadly the treatment has not worked. My life expentancy is now fairly short." I'm deeply saddened to read this news.

Go beyond observability hype and get into the specifics of what it means to have [Observability for Developers](https://www.honeycomb.io/guide-observability-for-developers-devopsish/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=guide-observability-for-developers-devopsish). Which data is actually useful to gather? How should you approach front-end services differently? What should you log and how? We show you what matters.

Ready to try it? [Sign up for free](https://ui.honeycomb.io/signup/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=product-signup). Stop guessing and start knowing with [Honeycomb](https://www.honeycomb.io/?&utm_source=devopsish&utm_medium=newsletter&utm_campaign=ad&utm_content=honeycomb-homepage-devopish). *SPONSORED*

[The DevRel Path to Success: Awareness, Enablement, Engagement](https://www.marythengvall.com/blog/2021/3/9/the-devrel-path-to-success-awareness-enablement-engagement)  
"In order for a technical individual to succeed with your product, they need to be confident that they have the ability to use your product, or at least the confidence that they can find the resources which will make them successful."

[Antiracist Economist Kim Crayton on How to Beat the Systemic Racism of IT](https://thenewstack.io/anti-racist-economist-kim-crayton-on-how-to-beat-the-systemic-racism-of-it/)  
"Crayton taught Antiracism 101. Now, this coach of tech leaders is focused on building out an ecosystem based on acknowledging and revolutionizing around four guiding principles:

1. Tech is not neutral. Nor is it apolitical.
2. Intention without strategy is chaos.
3. Lack of inclusion is a risk and crisis management issue.
4. Prioritize the most vulnerable."

[Pandemic Has Devastating Effect on Women in the Workforce on Cheddar](https://cheddar.com/media/pandemic-has-devastating-effect-on-women-in-the-workforce)  
"The pandemic has had a devastating effect on jobs in the U.S., but no one was impacted as much as women. According to the U.S. Bureau of Labor Statistics, nearly 3 million women have left the workforce in the last year. Stephanie Heath, Founder & CEO of Soul Work & Six Figures, joined Cheddar to discuss."

[Google advised mental health care when workers complained about racism and sexism](https://www.nbcnews.com/tech/tech-news/google-advised-mental-health-care-when-workers-complained-about-racism-n1259728)  
🤦‍♀️🤦‍♀️🤦‍♀️🤦‍♀️🤦‍♀️

[Google approach to HBCUs may account for Silicon Valley's lack of Black engineers](https://www.washingtonpost.com/technology/2021/03/04/google-hbcu-recruiting/)  
"'Google allocated resources so disparagingly because of how they tiered — and thought of — our schools,' said former recruiter April Christina Curley, who helped lead Google’s outreach to HBCUs for six years. Curley, who is Black, said she was fired in September largely as a result of continually raising concerns about bias against HBCU students in the interview and hiring process."

[The technical interview practice gap, and how it keeps underrepresented groups out of software engineering](https://blog.interviewing.io/the-technical-interview-practice-gap-and-how-it-keeps-underrepresented-groups-out-of-software-engineering/)  
"I won’t name any specific companies here, but tech giants (many with good intentions and with marching orders to boost their diversity numbers) often do a considerable amount of outreach and pre-interview engagement with candidates from underrepresented backgrounds. This outreach is usually an info session where one engineer speaks to a virtual room of candidates from underrepresented backgrounds. The engineer tells them what to expect in technical interviews, encourages them to learn how to articulate their thought process out loud while solving a problem, and recommends resources like Cracking the Coding Interview. Some companies even go so far as to offer their underrepresented candidates a mock interview or two.

Unfortunately, for candidates who are unfamiliar with the process, neither of these interventions is nearly enough."

## Process

[OVH founder says UPS fixed up day before blaze is early suspect as source of data centre destruction](https://www.theregister.com/2021/03/12/ovh_restoration_roadmap/)  
What a disaster. It takes things to a whole other when [the CEO retweets out to activate your disaster recovery plans](https://twitter.com/olesovhcom/status/1369478732247932929), you know things are really bad.

[Never wait for a staging environment again](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=title&utm_campaign=20210228) 👩‍💻🧑‍💻👨‍💻👩‍💻  
Do you find that your engineers spend too much time creating and maintaining staging environments and yet, there never seems to be enough environments to go around? A shortage of environments is a top driver of low developer productivity and often impacts an engineering team's ability to ship features on time. With Release, you can get a full instance of your app with all of its services with every pull request. You'll never have to wait around for staging environments again. 💡 [Get started now](https://releaseapp.io/?utm_source=devopsish&utm_medium=email&utm_content=get-started&utm_campaign=20210228) 💡 *SPONSORED*

[Google Online Security Blog: A Spectre proof-of-concept for a Spectre-proof web](https://security.googleblog.com/2021/03/a-spectre-proof-of-concept-for-spectre.html)  
Oh fun!

[A look inside the KubeCon + CloudNativeCon schedule selection process](https://www.cncf.io/blog/2021/03/08/a-look-inside-the-kubecon-cloudnativecon-schedule-selection-process/)  
"As part of our commitment to transparency within the cloud native community, we are providing an inside look into the work that goes on behind the scenes to bring the KubeCon + CloudNativeCon schedule to life. Note that every conference we put together has a post-event conference transparency report that includes a lot of the information we cover below. We are committed to improving the process after every conference."

[Zapier’s CEO Reveals How His Automation Startup Reached A $5 Billion Valuation Without Jumping On The VC ‘Hamster Wheel’](https://www.forbes.com/sites/alexkonrad/2021/03/08/zapier-bootstraps-to-5-billion-valuation/)  
"Foster prefers thinking about his customers, he says: museum tour guides, Etsy sellers and coffee shop owners who don’t have time to follow the latest buzzword on tech twitter, or whom VCs have anointed the next big thing."

[Researchers Discover Intel CPU Ring Interconnects Vulnerable To Side Channel Attack](https://www.phoronix.com/scan.php?page=news_item&px=Intel-Interconnects-Side-Chan)  
Can we actually trust anything on an Intel system anymore? I welcome the recent growth of ARM and RISC-V based chips. Not that it's better, but because I hope their cultures are better.

[Critics fume after Github removes exploit code for Exchange vulnerabilities](https://arstechnica.com/gadgets/2021/03/critics-fume-after-github-removes-exploit-code-for-exchange-vulnerabilities/)  
"Microsoft-owned Github pulls down proof-of-concept code posted by researcher." Given the breadth and damage that could be caused, I agree with this decision.

[Daylight Saving Time: Senators once again introduce a bill, Sunshine Protection Act, to make DST permanent](https://www.cnn.com/2021/03/10/us/senators-bill-daylight-saving-time-permanent-trnd/index.html)  
STOP THE MADNESS!!!

## Tools

[git: malicious repositories can execute remote code while cloning](https://www.openwall.com/lists/oss-security/2021/03/09/3)  
Patch all the git packages.

[[Free Book](https://launchdarkly.com/the-definitive-guide-to-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter)] Definitive Guide to Feature Management.  
[Ship Fast. Rest Easy LaunchDarkly.](https://launchdarkly.com/the-definitive-guide-to-feature-management/?utm_source=devopsish&utm_medium=news_pod&utm_campaign=21q1-newsletter) *SPONSORED*

[Rust vs. Go: Why They’re Better Together](https://thenewstack.io/rust-vs-go-why-theyre-better-together/)  
"While others may see Rust and Go as competitive programming languages, neither the Rust nor the Go teams do."

[Amazon's AWS 15 year anniversary; S3's cloud revolution](https://www.protocol.com/enterprise/amazon-aws-s3-15-years)  
Amazon's first real web service brought us everything from Pinterest to coronavirus vaccines. Fifteen years later, insiders tell Protocol how it grew to store 100 trillion objects.

[Klustered (Part IV)](https://youtu.be/Cp6zvBIo5KM)  
"Klustered is a series of live streams in which myself and a guest join forces to fix "broken" Kubernetes clusters ... on the clock.  
These clusters are broken by members of the Kubernetes community."

[Open Source solutions for chaos engineering in Kubernetes](https://blog.flant.com/chaos-engineering-in-kubernetes-open-source-tools/)  
"Chaos engineering for Kubernetes gets more and more popular, and rightly so: after all, K8s was designed with the ideas of availability and resiliency in mind. Therefore these marvelous features must be tested on real-life projects occasionally.

Fortunately, there are many Open Source solutions available that can help you with experimenting. Hopefully our review of them will be useful in your adventure. But let me start with a brief introduction..."

[Announcing Linkerd 2.10: Extensions, Opaque Ports, Multi-cluster TCP, and more!](https://linkerd.io/2021/03/11/announcing-linkerd-2.10/)  
"This release adds pluggable extensions to Linkerd and dramatically reduces the default control plane size by moving non-critical components into opt-in extensions. The 2.10 release also extends Linkerd’s seamless, secure multi-cluster support to all TCP connections, not just HTTP. Finally, Linkerd 2.10 adds opaque ports as a way of extending Linkerd’s coverage to certain situations that are incompatible with protocol detection."

[Ask an OpenShift Admin (Ep 21): Etcd - the heart of the control plane](https://youtu.be/YY62Mof5plY)  
"The heart of the Kubernetes control plane in Red Hat OpenShift is etcd, a key/value store used to persist configuration, status and requested state for everything happening in the cluster. Slow etcd means a slow control plane and slow API, which ripples out to every aspect of OpenShift and your applications. In this episode, we dig into etcd, focusing on performance requirements, protecting the data, and periodic maintenance, so don’t miss this one!"

[A new type of supply-chain attack with serious consequences is flourishing](https://arstechnica.com/gadgets/2021/03/more-top-tier-companies-targeted-by-new-type-of-potentially-serious-attack/)  
"New dependency confusion attacks take aim at Microsoft, Amazon, Slack, Lyft, and Zillow."

[ConsoleMe: A Central Control Plane for AWS Permissions and Access](https://netflixtechblog.com/consoleme-a-central-control-plane-for-aws-permissions-and-access-fd09afdd60a8)  
"At AWS re:Invent 2020, we open sourced two new tools for managing multi-account AWS permissions and access. We’re very excited to bring you ConsoleMe (pronounced: kuhn-soul-mee), and its CLI utility, Weep (pun intended)!"

[Introducing sigstore: software signing for the masses](https://next.redhat.com/2021/03/09/introducing-sigstore-software-signing-for-the-masses/)  
"Sigstore is a project that provides the infrastructure for developers / software maintainers to sign code with no need to manage keys."

[jetstack/preflight](https://github.com/jetstack/preflight)  
Automatically perform Kubernetes cluster configuration checks using Open Policy Agent (OPA)

[Azure/policy-compliance-scan](https://github.com/Azure/policy-compliance-scan)  
A GitHub action that scans the Azure resources for policy violations.

## DevOps'ish Tweet of the Week

[![K8sContributors on Twitter: "Kubernetes crossed 100,000 issues/PRs a few hours ago! That is 100,000 times the project has been improved by contributors like you. Thank you all for contributing :tada:"](["https://shortcdn.com/file/devopsish/209-devopsish-tweet-of-the-week.png)](https://twitter.com/K8sContributors/status/1369304454198071300)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/209/notes/) to see what didn't make it to the newsletter but are still worth your time.
