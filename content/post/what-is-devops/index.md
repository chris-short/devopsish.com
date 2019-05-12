+++

author = "Chris Short"
date = 2019-05-05T15:23:00Z
description = "DevOps is the professional practice of frequent, continued, and iterative improvements through measurable changes, the goal of which is to become a high-velocity organization thus improving business outcomes."
draft = false
slug = "what-is-devops"
tags = ["DevOps", "business", "outcomes", "change", "open source", "high-velocity organization", "iterative improvement"]
title = "What is DevOps"
image = "/what-is-devops/devops.svg"
imagealt = "DevOps Toolchain graphic is provided under the CC BY-SA 4.0 via Wikimedia Commons"

+++

**DevOps** was intentionally left undefined (or loosely defined) at the first DevOpsDays event held in Ghent, Belgium. There are many good reasons for leaving it undefined. Back in 2009 in Ghent, no one could be sure how DevOps would impact the industry. But, the lack of a definition has left it available to be defined by anyone (myself included). This means a product can be DevOps and a business process can be DevOps. Neither of these is "wrong" but, one adheres to the spirit of DevOps more than the other. Allow me to attempt to define and scope DevOps.

## Definition

If forced to put it in one sentence, I would describe DevOps as follows:

> ***DevOps*** is the professional practice of frequent, continued, and iterative improvements through measurable changes, the goal of which is to become a high-velocity organization thus improving business outcomes.

Etymological Note: DevOps, the word itself, should be used in an active voice. The word itself is the combining of two words Development and Operations. The word itself indicates that there will be a removal of silos as intended throughout this document.

There's a lot to unpack in this definition. Let's dive into specific words and phrases to provide more color and further explain why this is my definition for DevOps.

### Professional Practice

Professional Practice, in the case of DevOps, means that the folks doing the work are, in a similar vein as doctors and lawyers, practitioners. Much like how the underlying principles of medicine and law change over time, technology does too. Technology moves at a much faster rate of change though. Thus it's imperative to continuously hone the methods and processes through which business activity, or at the very least software development and operations, is conducted. This also requires thoughts on scientific methods for measuring systems as inputs impact outputs.

### Frequent, Continued, and Iterative Improvement

Most DevOps practices embrace [Agile](https://agilemanifesto.org/) as a method for managing work. This does not mean Agile will always work nor always be the best for every organization. Agile enables features and tools to be iterated on over many releases and developed faster than more traditional methods. When coupled with [Lean thinking](https://en.wikipedia.org/wiki/Lean_thinking) business principles, customers can expect high-quality features, bug fixes, and modifications delivered at regular intervals.

These delivery intervals get shorter in length and more frequent as the organization embraces DevOps practices. Several deployments an hour is entirely realistic for more mature DevOps organizations. At some point along an organization's DevOps journey, a pipeline is built. This pipeline enables automation of changes and modifications to the system through controlled inputs. Whether this is completely automated from development to production in a continuous deployment model or something short of that is ultimarely a business decision.

For years, we've been taught that [speed kills](https://youtu.be/va1o_btLDt8). While that may be true in a few facets of life, it is not the case in software delivery. DevOps Research & Assessment (DORA) has collected survey data for over five years from organizations and professionals delivering and maintaining software across the globe. In 2018, [Accelerate: State of DevOps Report](https://cloudplatformonline.com/2018-state-of-devops.html) (ASDOR) described the highest performers as, "excelling at all aspects of throughput and stability." The Elite Performers are delivering software faster with shorter lead times for changes than the rest of the industry.

As counterintuitive as this might sound to some, when it comes to software, smaller, more frequent releases will improve stability a lot more than a 900 line spreadsheet and detailed planning ever will. If a pipeline allows for safe, rapid, iterative improvements to a system, it becomes increasingly easier to deploy to fix issues that arise as they happen. This often leads to growth in capabilities as more work becomes automated and mind power is allowed to focus on more complex issues.

### High-Velocity Organization

A consensus is forming around the idea of organizations being technology organizations first and widget makers second. This means that a component of technology can improve everything between a business' logic and the market itself. Being able to integrate business processes more tightly with existing or new technologies can lead to improved outcomes. Time to market, lead time, mean time to resolution (recovery), change failure rate, and myriad other metrics can be gleaned from day-to-day operations. Focusing on improving the metrics that matter most to your business will lead to discussions about change, automation, and greater collaboration between otherwise disparate groups.

There are many environments and models for achieving higher velocity. No one model is better than another but, one model will be better for an organization and the people within it. Often strict adherence to any one model isn't possible either. If the business is maintaining commercial passenger jets doing multiple transatlantic crossings a day, several deployments an hour to production might not be workable (or wise). The point is, one size or style rarely fits all. Figuring this out and what metrics matter to your business are the pain people frequently described as a "journey."

### Measurable Changes

Measurable, in the sense of DevOps, can mean any of several different ways to track, measure, and analyze changes to the system. This translates to some disciplines such as version control ([git](https://git-scm.com/) being the most popular), monitoring, observability, record keeping, and analysis.

As work occurs in the system be it normal operation, routine maintenance, or full system upgrades all changes should be tracked, recorded, and measured. This allows for short or long-term analysis to determine the state of the system at a point in time or throughout normal operations. It's incredibly challenging to fix pain points when data can't back up what the problem is.

### Business Outcomes

Business Outcomes can be defined as top-level organizational goals and/or Objectives and Key Results (OKRs). These are the things that organizational leadership has determined are strategic goals of the business activity. DevOps must facilitate the desired outcomes to maximize the impact of the objectives and goals. By tying the purpose of the technology teams to the goals of the business the table is set for technology to better impact the business.

## DevOps Culture

Organizational culture is often the biggest hurdle in achieving higher velocity. There is little the organization can do but change. But, human resistance to change is often very real. One of the most egregious cases of resistance to change was detailed in The Ops Mutiny section of [The Dark Side of DevOps](https://chrisshort.net/the-dark-side-of-devops/). But, fear not, culture changes are happening across the globe every day as more and more organizations realize that the way business has been done is not the way it can continue to be done.

In [The Dark Side of DevOps](https://chrisshort.net/the-dark-side-of-devops/) there is another story of a rebellious gang of developers and researchers I worked with. We used the existing restrictive processes and a team written white paper to accelerate cultural change. It worked. Ensuring the business is sitting at the table with the right members of the technology organization is critical to providing greater success. Iterative changes at an increasing velocity leading to improved business outcomes is the goal.

## What DevOps Isn't

[![Lemi Orhan Ergin on Twitter](/what-is-devops/lemiorhan-859158123722010628-devops.png "Lemi Orhan Ergin on Twitter")](https://twitter.com/lemiorhan/status/859158123722010628?ref_url=https:/devopsish.com/what-is-devops/)

* DevOps is not something you can buy.
* DevOps is not a tool.
* DevOps is not using the cloud.
* DevOps is not ping pong tables and beer.
* DevOps is not Agile.
* DevOps is not Kanban.
* DevOps is not one team.
* DevOps is not one person.

[Like Obi Won Kenobi talking about Darth Vader, "DevOps is more fluff now than actual outcomes. Its purpose has become twisted."](https://chrisshort.net/2018-learnings-2019-expectations/) There is a long list of companies that are more than willing to help organizations embrace a component or two of DevOps. Some of those companies will sell you a tool with DevOps in the name. Others will sell consulting and process evaluation. Regardless, DevOps is not a one-time engagement, a standalone project, or a box that is checked. Much like law and medicine, DevOps professionals are practitioners and continuous learners.

## Where To Learn More About DevOps

* [DevOps README.md](https://chrisshort.net/devops-readme.md/)
* [*DevOps For Dummies*](https://amzn.to/2TFOQFe)
* [*Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations*](https://amzn.to/2Xnc5S2)

### Special Thanks

A very special thanks to [Nathen Harvey](https://twitter.com/nathenharvey), [Kim McMahon](https://kimmcmahon.me), and [Emily Freeman](https://emilyfreeman.io/).

[DevOps Toolchain](https://commons.wikimedia.org/wiki/File:Devops-toolchain.svg) graphic is provided under the CC BY-SA 4.0 via Wikimedia Commons