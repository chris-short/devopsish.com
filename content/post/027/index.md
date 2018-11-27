+++

author = "Chris Short"
categories = ["Newsletter"]
date = 2017-06-11T06:01:01.105Z
description = ""
draft = false
slug = "027"
tags = ["devops", "cloud native", "open source", "patents", "intel", "linux", "uber"]
title = "027: Week of 1497153600"
image = "/027/grinder-sparks.jpg"
imagealt = "There is no such thing as a completed DevOps transition."
aliases = [
    "devopsish-027-week-of-1497153600-5997c150660"
]

+++

Quite the week in the greater world of technology. [Apple had an event](https://developer.apple.com/wwdc/) and [folks had a meltdown about their new show](http://www.businessinsider.com/apple-planet-of-the-apps-ad-developer-rarely-saw-his-kids-2017-6). GitHub had a rough week, Uber sunk to new lows, and Intel has fired a massive warning shot at the future of computing. A lot of [DevOps](/) happened too. Let's break it all down.

[**Full Stack Fest 2017: Problems of today, wonders from the future.**](https://2017.fullstackfest.com)  
Barcelona, 4–8 Sept. 2017  
Are you a curious mind? [Full Stack Fest](https://2017.fullstackfest.com) is a week-long conference based in the amazing city of Barcelona that peeks into the web of tomorrow. Serverless, Blockchain, WebVR, Distributed Web, Progressive Web Apps... Come and see! *SPONSORED*

{{< upscribe >}}

## Department of Patent Pedantry

Intel took us down memory lane this week with a [blog post discussing how X86 is almost forty years old](https://newsroom.intel.com/editorials/x86-approaching-40-still-going-strong/). Remember the 8086? MMX? SSE 1 through 4? VMX? Good times! Oh and remember that Intel has 1,600 patents and they are not afraid to sue the bejesus out of you.

Intel is firing a shot across the bow for anyone trying to do X86 emulation without ponying up licensing fees to Intel. "...we fully expect other companies to continue to respect Intel's intellectual property rights." [Axios points out](https://www.axios.com/intel-steer-clear-of-our-patents-2437931228.html), "Microsoft and Qualcomm have announced plans for a version of Windows 10 on Qualcomm's Snapdragon 835 that uses emulation to run older applications designed for x86-based Windows machines."

Emulation (software mimicking hardware) is important for the advancement of microprocessors. Emulation can be used for older workloads instead having to buy expensive, overpowered hardware to maintain something that could run on a much cheaper component. Emulation comes in so that you don't have to completely rewrite your legacy stack because you can't get new hardware for it to run on. This will be a story that won't end anytime soon.

## Department of Choice Concepts

[Gene Kim weighed in on last week's British Airways debacle](https://itrevolution.com/imaginary-apology-letter-airline-ceo/). Gene wrote a fictitious letter that is what [Willie Walsh](https://en.wikipedia.org/wiki/Willie_Walsh_(businessman)) should have written. "The accident last week was not due to a power failure, or an IT failure — this was a business failure. After all, we were unable to perform some of our most critical business operations for nearly three days." Bravo! 👏👏👏

Also from Gene Kim land, [2017 State of DevOps Report](https://puppet.com/resources/whitepaper/state-of-devops-report) is out. There are a lot of takeaways from this report but one of the key findings stands out to me: Dimensions of transformational leadership. High performing teams have leadership that shares five characteristics; vision, intellectual stimulation, recognition, inspirational communication, and "supportive leadership".

Red Hat is offering free [Fundamentals of Red Hat Enterprise Linux](https://www.edx.org/course/fundamentals-red-hat-enterprise-linux-red-hat-rh066x#!) training through edX. This is going to be helpful when people ask me how to get started with Linux.

Brendan Gregg has updated his awesome [Linux Performance Tools](http://www.brendangregg.com/linuxperf.html) diagrams. This is something I print out and have very handy at all times.

Julia Evans shares, "[A few things I've learned about Kubernetes](https://jvns.ca/blog/2017/06/04/learning-about-kubernetes/)" complete with awesome sketches.

## Department of Data Defense

[Why set up a complex process to communicate with command and control systems for your malware when you could just use Britney Spears' Instagram comments?](https://arstechnica.com/security/2017/06/russian-hackers-turn-to-britney-spears-for-help-concealing-espionage-malware/) This is a fairly brilliant tactic; good luck taking down Britney Spears social media profiles and risk pissing tens of millions of fans.

As previously mentioned, GitHub has had a hard time of late. [GitHub experienced two "major service outage" events this week](https://status.github.com/messages/2017-06-10). I feel for the team there; it's not easy running the services that distribute a ton of the world's code.

[Kaspersky is suing Microsoft claiming that Microsoft's heavy marketing of Windows Defender violates antitrust law](http://www.theregister.co.uk/2017/06/06/windows_defender_competition_complaint/). Kaspersky called Windows Defender, "inferior" in its claim. Damn!

## Department of Sane Workplaces

[This reddit thread exploded this week](https://www.reddit.com/r/cscareerquestions/comments/6ez8ag/accidentally_destroyed_production_database_on/). A new, junior member of a development team was given shoddy documentation with production connection string, credentials, and table names to setup their dev environment. No one told them that they shouldn't actually use that information and they ended up blowing away the production database. It's a great read (yes, even the comments, to an extent).

Uber sunk to new lows this week. [Uber fired more than 20 employees after receiving 215 claims in probe of sex harassment and other incidents](http://www.businessinsider.com/uber-fired-more-than-20-employees-as-part-of-its-sex-harassment-probe-2017-6). [A top Uber executive, who obtained the medical records of a customer who was a rape victim, has been fired](https://www.recode.net/2017/6/7/15754316/uber-executive-india-assault-rape-medical-records). [Uber CEO Travis Kalanick advised employees on sex rules for a company celebration in 2013 'Miami letter'](https://www.recode.net/2017/6/8/15765514/2013-miami-letter-uber-ceo-kalanick-employees-sex-rules-company-celebration). [Kalanick has started meditating in an office lactation room, says Arianna Huffington](https://www.cnbc.com/amp/2017/06/07/arianna-huffington-says-uber-ceo-travis-kalanick-has-started-meditating.html). If you still are working at Uber, I'd like to know why? Seriously.

## Tweet of the Week

{{< tweet 872073119682498560 >}}