+++

author = "Chris Short"
categories = ["Weekly", "Newsletter", "DevOps News", "Cloud Native News", "2020"]
date = 2020-04-12T07:00:00Z
description = "COBOL need grows, Alice Goldfuss wants a job, containers, observability, Tom Scott, Zoom doom, MySQL, PostgreSQL, Kubernetes, markmap-lib, and more"
draft = false
slug = "175"
tags = ["COBOL", "DevOps", "systems", "Kubernetes", "cloud", "developers", "Linux", "applications", "Google", "Ansible", "cloud native", "open source", "containers", "observability", "mainframe", "Microsoft", "Zoom", "MySQL", "PostgreSQL", "Alice Goldfuss", "Tom Scott"]
title = "DevOps'ish 175"

+++

I was going to make a list of things you could learn this week but, the tech world got a notable call to arms this week. We need more COBOL developers in the US. [The glut of unemployment claims](https://thenewstack.io/u-s-unemployment-surge-highlights-dire-need-for-cobol-skills/) has crippled mainframe systems designed to run in a satisfactory government manner under normal conditions. "[The governor of New Jersey just put out the call on live TV that he is desperate for Cobol programmers right now.](https://twitter.com/manicode/status/1246497036389793792)" As insane as this sounds, it's true (and long overdue). We don't need to modernize this; it's not able to run as-is. We need more COBOL programmers now. The University of Limerick has a free [COBOL programming course](http://www.csis.ul.ie/cobol/course/Default.htm). IBM also has a [Master the Mainframe](https://www.ibm.com/it-infrastructure/z/education/master-the-mainframe) course that you can take online now. Even if you don't need a job right now, maybe you know someone who does. We can solve two problems at once here!

## People

[Hire Alice Goldfuss](https://blog.alicegoldfuss.com/hire-me/)  
Be like a shoe and just do it.

[Why Linux containers are a CIO's best friend](https://www.ciodive.com/news/linux-containers-kubernetes/575506/)  
"Linux containers enable developers to package and isolate applications with their entire runtime environment. This makes it easier (and less expensive) to move fully functional applications among dev, test, production and other environments. In turn, it makes it possible to meet the never-ending internal and external demand for those applications."

[Webinar: Providing Business Value Through Observability](https://terazo.com/providing-business-value-with-observability/)  
My good friend, one of the most brilliant minds in DevOps, and great engineering leader, [Chris Bailey](https://twitter.com/seebails), is talking to the universe about observability for free. You should register, I did.

[Microsoft is giving workers 12 weeks of paid parental leave because of school disruptions](https://www.cnn.com/2020/04/09/tech/microsoft-12-weeks-parental-leave/index.html)  
"Microsoft is giving its workers an additional three months of paid parental leave to deal with extended school closures due to the coronavirus outbreak... The company is calling the program '12-Week Paid Pandemic School and Childcare Closure Leave.'" My jaw dropped when I read this. I don't know the complete logistics of it, but having it as an option would be amazing.

[How to Manage Your Stress When the Sky Is Falling](https://hbr.org/2020/04/how-to-manage-your-stress-when-the-sky-is-falling)  
"It's natural to feel stressed right now. As we try to navigate our new normal, we're worried about getting sick or losing our jobs, we're inundated with news about death tolls and an economic recession, and we're isolated from coworkers, friends, and family."

[High Performance MySQL](https://blog.dbsmasher.com/2020/04/08/high-performance-mysql.html)  
Huge congrats to Silvia Botros! What an uplifting story.

[This Video Has 6,637,986 Views (YouTube)](https://www.youtube.com/watch?v=BxV14h0kFs0)  
This Tom Scott video is brilliant.

## Process

[Russian telco hijacks internet traffic for Google, AWS, Cloudflare, and others](https://www.zdnet.com/article/russian-telco-hijacks-internet-traffic-for-google-aws-cloudflare-and-others/)  
"Rostelecom involved in BGP hijacking incident this week impacting more than 200 CDNs and cloud providers."

[Decade of the RATs: Novel APT Attacks Targeting Linux, Windows and Android](https://blogs.blackberry.com/en/2020/04/decade-of-the-rats)  
"BlackBerry researchers have released a new report that examines how five related APT groups operating in the interest of the Chinese government have systematically targeted Linux servers, Windows systems and Android mobile devices while remaining undetected for nearly a decade." And people wonder why COBOL is still around.

[Building Secure and Reliable Systems](https://landing.google.com/sre/books/)  
A new SRE-focused eBook from Google that's free for everyone.

[Be careful when pulling images by short name](https://www.redhat.com/en/blog/be-careful-when-pulling-images-short-name)

[Zoom Rushes to Improve Privacy for Consumers Flooding Its Service](https://www.nytimes.com/2020/04/08/business/zoom-video-privacy-security-coronavirus.html)  
The stories we will tell our grandchildren about Zoom... I can't wait. "The risks, the misuse, we never thought about that." Eric S. Yuan, the chief executive of Zoom Video Communications.

## Tools

[Controlling outbound traffic from Kubernetes](https://monzo.com/blog/controlling-outbound-traffic-from-kubernetes)  
This is brilliant and intense. This is how you keep bad shit from running in your cluster. A little automation and you can find leaky points in your processes and infrastructure at a moment's notice.

[Getting Started with Ansible Security Automation: Investigation Enrichment](https://liquidat.wordpress.com/2020/04/09/getting-started-with-ansible-security-automation-investigation-enrichment/)  
"In this blog post we have a closer look at how Ansible can help to overcome these challenges and support investigation enrichment activities. In the following example we'll see how Ansible can be used to enable programmatic access to information like logs coming from technologies that may not be integrated into a SIEM."

[Optimize PostgreSQL Server Performance Through Configuration](https://info.crunchydata.com/blog/optimize-postgresql-server-performance)  
[I]t's always recommended that one of the first actions performed once an install of PostgreSQL is completed, would be to tune and configure some high-level settings.

[Percona XtraBackup: Backup and Restore of a Single Table or Database](https://www.percona.com/blog/2020/04/10/percona-xtrabackup-backup-and-restore-of-a-single-table-or-database/)  
Percona tools have saved my ass more times than I can count. Give this a read in case you ever end up in a MySQL pickle.

[iRobot Launches Robot Simulator, Free Online Curriculum for Robotics Education](https://spectrum.ieee.org/automaton/robotics/home-robots/irobot-launches-robot-simulator-free-online-curriculum-for-robotics-education)  
"Your kids can learn to program robots from scratch, for free, on their computer or phone"

[AWS Fargate launches Platform Version 1.4](https://aws.amazon.com/about-aws/whats-new/2020/04/aws-fargate-launches-platform-version-14/)  
Still not the container management platform we want (see last week's issue).

[Embrace and Replace: Migrating ZooKeeper into Kubernetes](https://product.hubspot.com/blog/zookeeper-to-kubernetes-migration)  
"We recently migrated hundreds of ZooKeeper instances from individual server instances to Kubernetes without downtime. Our approach used powerful Kubernetes features like endpoints to ease the process, so we're sharing the high level outline of the approach for anyone who wants to follow in our footsteps."

[Announcing unverified.email](https://kerestey.net/writing/2020-04-05-announcing-unverified-dot-email.html)  
"unverified.email is a catch-all SMTP server. You can use it programmatically via its API at https://api.unverified.email, and the article shows an example of its usage."

[markmap-lib](https://markmap.js.org/)  
Turn Markdown into a mind map. I'm going to have some fun with this later.

[ManagedKube/kubernetes-common-services](https://github.com/ManagedKube/kubernetes-common-services)  
"These services help make it easier to manage your applications environment in Kubernetes"

## DevOps'ish Tweet of the Week

[![Ian Coldwater 📦💥 @IanColdwater on Twitter) "I am a person who specializes in cloud native infrastructure, not a COBOL programmer, but if you're like "lol why don't banks and governments migrate to modern systems?!" I have some news for you about the security of bleeding edge systems"](/images/175-devopsish-tweet-of-the-week.webp)](https://twitter.com/IanColdwater/status/1246599504930975744)

Want more? Be sure to check out the [notes from this week's issue](https://devopsish.com/175/notes/) to see what didn't make it to the newsletter.
