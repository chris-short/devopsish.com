+++

author = "Chris Short"
categories = ["Weekly", "Newsletter"]
date = 2017-11-05T13:35:27.663Z
description = ""
draft = false
slug = "048"
tags = ["devops", "cloud native", "open source", "kubernetes", "serverless", "programming", "golang", "hiring"]
title = "048: On Opinions, MySQL, Kubernetes and Go Tools, Much DevOps, Very More"
image = "/048/hot-air-balloon.jpg"
imagealt = "Hot Air Balloon"
aliases = [
    "devopsish-048-on-opinions-mysql-kubernetes-and-go-tools-much-devops-very-more-1a566c4a796d"
]

+++

Strong opinions, loosely held: is a state of mind I've been striving to achieve both personally and professionally. Coming from a military background, this is an incredibly hard thing to do. The Air Force, despite its rank and structure, optimized itself around free-thinking innovation. You could easily come in and punch the clock and leave at the end of the day in the Air Force. But, if you wanted to go further, it helped if you thought outside the box. As you can imagine, me thinking outside a Department of Defense box was pretty much modus operandi. I didn't do anything crazy with secret information or weird infrastructure bits that wouldn't scale. But, I certainly pushed the outer limits of outside the box thinking and had to defend it at all costs. This meant my opinion had to be so strongly held as it flew in the face of the "by the book" types that my ideas would succeed and not be sabotaged as the thought floated up the often lengthy chain of command. These days, my opinions are based on experience, assessment, and achievability. These are all fine things that are quite defensible. But, it's better to let the opinion be presented on merit and let others come around to it as opposed to forcing it through. It is okay to have a strong opinion about something. But, do not shutdown outside ideas as a result of your strong opinion. Be agile and adept. Don't death grip your ideas, be open to free thinking.

[**[Video] Continuous Delivery 101 from GoCD**](https://www.gocd.org/2017/07/13/introduction-continuous-delivery-101/?utm_campaign=CD_101_video&utm_medium=email&utm_source=devopsish&utm_content=cd_101_video&utm_term=)  
This video series covers the history of CD, concepts, best practices, how to get started, and popular tools. You'll gain a holistic view of continuous delivery and a deeper understanding and appreciation of critical concepts. *SPONSORED*

[**Bankrate Needs More DevOps Minds**](http://app.jobvite.com/m?3W7Q7jwO)  
Bankrate.com is looking for a DevOps Engineer! Are you ready for the next phase of your DevOps journey? Join us!

[**OpenShift Commons Gathering**](http://openshiftgathering.com/openshiftgathering/austin)  
December 5, 2017  
Where users, partners, customers, contributors and upstream project leads come together to collaborate and work together on OpenShift.

{{< sponsor-blurb >}}

## People

[The Five Love Languages of DevOps](https://medium.com/@mattstratton/the-five-love-languages-of-devops-77606263c910) by Matt Stratton

[20 questions DevOps hiring managers should be prepared to answer](https://opensource.com/article/17/11/inclusive-workforce-takes-work): Fostering a diverse, inclusive work environment is more important than ever — especially for DevOps teams, where candidates often call the shots. Here's how one situation went wrong, and some questions to keep your hiring on track.

[A Twitter employee on their last day of work took down Trump's account for 11 minutes](http://www.businessinsider.com/trumps-twitter-account-gone-disappeared-2017-11): My hero ❤️ but, what can we learn from this outage?

[All Things Open 2017](http://princessleia.com/journal/2017/11/all-things-open-2017/) by [Elizabeth Krumbach Joseph](http://princessleia.com/): A lovely recap of one of my all time favorite tech conferences.

[7 Non-Technical Skills You Need To Succeed In A DevOps Career](https://www.forbes.com/sites/laurencebradford/2017/10/30/7-non-technical-skills-you-need-to-succeed-in-a-devops-career/#594f9026f49e): Number 1 is HUGE. I have such a hard problem getting people to just want to learn.

[Four Semesters of Computer Science in Six Hours](https://btholt.github.io/four-semesters-of-cs/): I need to find six hours to do this.

[{code} Catalyst Spotlight — Phil Estes, Senior Technical Staff at IBM](https://youtu.be/atsNztKmjsk)

[Microsoft Presenter Gives Up On Edge, Installs Chrome](https://www.gizmodo.com.au/2017/10/microsoft-presenter-gives-up-on-edge-installs-chrome/)

[Internet Association Endorses Internet Censorship Bill](https://www.eff.org/deeplinks/2017/11/internet-association-endorses-internet-censorship-bill) (EFF): "It shouldn't really come as a surprise that the Internet Association has fallen in line to endorse SESTA. The Internet Association doesn't represent the Internet — it represents the few companies that profit the most off of Internet activity."

Ashley McNamara led Microsoft Azure OpenDev and [the entire event is available for your viewing pleasure](https://azure.microsoft.com/en-us/opendev/).

[DevOps In Politics](https://www.devopsdays.org/events/2017-seattle/program/nell-shamrell-harrington/): Working technology for a political campaign involves the shortest timelines, tightest deadlines, and highest stakes you will likely ever encounter in a technology career.
{{< carbon_ads >}}

## Process

[Stop supporting old releases](https://medium.com/@mikeal/stop-supporting-old-releases-70cfa0e04b0c): A call to action for maintainers to support themselves and move forward.

[Microsoft says 40 percent of all VMs in Azure now are running Linux](http://www.zdnet.com/article/microsoft-says-40-percent-of-all-vms-in-azure-now-are-running-linux/): A year ago, Microsoft officials said nearly a third of all the VMs on Azure were running Linux. Now it's 40 percent.

[Cloud-Native, Seven Years On...](https://thenewstack.io/cloud-native-seven-years/)

[Securing SSH Services — Go Blue Team!!](https://isc.sans.edu/forums/diary/Securing+SSH+Services+Go+Blue+Team/22992/) Too often I find insecure SSH configurations. If you're using a tool like Ansible and SSH is not configured properly you're going to have a bad time.

[Open source database startup MariaDB confirms $27M investment led by Alibaba](https://techcrunch.com/2017/11/02/mariadb-confirms-27m-investment-led-by-alibaba/)

[My VM is Lighter (and Safer) than your Container](http://cnp.neclab.eu/projects/lightvm/lightvm.pdf) (PDF): But your VM is more expensive to pipeline (maybe).

[Writing a 9P server from scratch](https://blog.aqwari.net/9p/)

[Google Developer Documentation Style Guide](https://developers.google.com/style/)
{{< carbon_ads >}}

## Tools

[Why Go is skyrocketing in popularity](https://opensource.com/article/17/11/why-go-grows): In only two years, Golang leaped from the 65th most popular programming language to #17. Here's what's behind its rapid growth. Editor's Note: I've long thought of Go as the DevOps language. That is panning out.

[What are the Most Disliked Programming Languages?](https://stackoverflow.blog/2017/10/31/disliked-programming-languages/) I'll go ahead and throw mine out there: Java.

[MySQL vs. MariaDB: Reality Check](https://www.percona.com/blog/2017/11/02/mysql-vs-mariadb-reality-check/): "The goal of this blog post is to evaluate, at a higher level, MySQL, MariaDB and Percona Server for MySQL side-by-side to better inform the decision making process. It is largely an unofficial response to published comments from the MariaDB Corporation."

[Web Scraping Tips and Tricks](http://go-colly.org/articles/scraping_tips/)

[Profiling Go](http://www.integralist.co.uk/posts/profiling-go/) by [Mark McDonnell](http://www.integralist.co.uk/): "With Go the GC is executed concurrently, so users don't notice pauses or delays even though the GC is running."

[Running Kubernetes on Travis CI with minikube](https://blog.travis-ci.com/2017-10-26-running-kubernetes-on-travis-ci-with-minikube)

[An introduction to Docker and Kubernetes for Node.js developers](https://speakerdeck.com/georgecrawford/an-introduction-to-docker-and-kubernetes-for-node-dot-js-developers)

[HTTP(S) Proxy in Golang in less than 100 lines of code](https://medium.com/@mlowicki/http-s-proxy-in-golang-in-less-than-100-lines-of-code-6a51c2f2c38c): The goal is to implement a proxy server for HTTP and HTTPS.

[Handling errors in gRPC and go-kit services](https://hackernoon.com/handling-errors-in-golang-grpc-and-go-kit-services-d0fa0a112449)

[The Serverless Spectrum](https://read.acloud.guru/the-serverless-spectrum-147b02cb2292): Like so many things in life, serverless is a spectrum with multiple dimensions along which the degree of each can vary

[Docker: Useful Command Line Stuff](http://www.revsys.com/tidbits/docker-useful-command-line-stuff/)

[Tips and Tricks of the Docker Captains](https://blog.docker.com/2017/11/tips-tricks-docker-captains/): "The motivation for the talk was to enable users to quickly gain a higher level of proficiency and understanding in Docker."

[Go Funcs — Baby-Gopher's Visual Guide](https://blog.learngoprogramming.com/golang-funcs-params-named-result-values-types-pass-by-value-67f4374d9c0a): Easily understand Go funcs with visuals.

[Fastly Varnish](http://www.integralist.co.uk/posts/fastly-varnish/) by [Mark McDonnell](http://www.integralist.co.uk/): "This post is about Varnish and explaining a couple of specific features (such as hit-for-pass and serving stale) and how they work in relation to Fastly's implementation of Varnish."

[adnanh/webhook](https://github.com/adnanh/webhook): webhook is a lightweight configurable tool written in Go, that allows you to easily create HTTP endpoints (hooks) on your server, which you can use to execute configured commands.

[tidwall/evio](https://github.com/tidwall/evio): Fast event-loop networking for Go

[timest/goscan](https://github.com/timest/goscan): goscan is a simple and efficient IPv4 network scanner that discovers all active devices on local subnet.

[ufoym/deepo](https://github.com/ufoym/deepo): A Docker image containing almost all popular deep learning frameworks: theano, tensorflow, sonnet, pytorch, keras, lasagne, mxnet, cntk, chainer, caffe, torch.

[go-ego/riot](https://github.com/go-ego/riot): Go Open Source, Distributed, Simple and efficient Search Engine

[98, 99, 100 CloudFront Points of Presence!](https://aws.amazon.com/blogs/aws/98-99-100-cloudfront-points-of-presence/)

[AWS Direct Connect Enables Global Access](https://aws.amazon.com/about-aws/whats-new/2017/11/aws-direct-connect-enables-global-access/): Minus China (of course)

[Making it easy to use Envoy as a Kubernetes load balancer](https://blog.heptio.com/making-it-easy-to-use-envoy-as-a-kubernetes-load-balancer-dde82959f171)

[Introducing Tarmak — the toolkit for Kubernetes cluster provisioning and management](https://blog.jetstack.io/blog/introducing-tarmak/)

## DevOps'ish Tweet of the Week

{{< tweet 926431612606275584 >}}