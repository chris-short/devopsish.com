---
author: Chris Short
date: '2026-06-28'
description: "Supply chain incidents, custom AI silicon, IBM sub-1nm chips, Apple price hikes, Netflix batch compute with Kueue, and the case for doing fewer things better."
draft: false
slug: '315'
title: "DevOps'ish 315: Sub-Nanometer Chips, Supply Chain Whiplash, and the Database Nobody Could Kill, and More"
---

[**We helped build Docker. Now we're building the engineer who maintains it.**](https://www.mendral.com/?utm_source=devopsish) (SPONSOR)

Sam was Docker's first hire. Andrea wrote Docker's first commit. We spent a decade watching teams drown in CI maintenance. Mendral is what we wished we'd had. Three agents in your CI: Security reviews dep PRs, Reliability fixes flaky tests, Performance cuts pipeline time.

[**Designing IaC Interfaces That Work for Humans, AI Agents, and Whatever Comes Next**](https://events.iacconf.com/designing-iac-interfaces-july-2026-spotlight/) (SPONSOR)

AI agents are changing who, or what, uses your Terraform modules. Join Jinger Meilani, Senior DevOps Engineer at MNTN, to learn how to design reusable, self-service IaC interfaces that reduce misuse and work for humans, AI agents, and whatever comes next.

[**Klue Supply Chain Incident and LastPass Response**](https://blog.lastpass.com/posts/klue-supply-chain-incident-and-lastpass-response) (4 minute read)

An unauthorized actor snagged OAuth tokens from Klue, a market intelligence platform, and used them to access LastPass customer contact and CRM data stored in Salesforce. LastPass says vaults and core infrastructure are unaffected, but this is another clean example of why your vendor's vendor is still your problem.

[**OpenAI, Broadcom debut custom Jalapeño chip for AI inference**](https://siliconangle.com/2026/06/24/openai-broadcom-debut-custom-jalapeno-chip-llm-inference/) (5 minute read)

OpenAI and Broadcom have jointly developed Jalapeño, a custom processor built exclusively for AI inference that focuses on reduced data movement and higher performance per watt. Deployment in custom server racks starts by year-end, and OpenAI calls it "the first step in a multi-generation compute platform."

[**IBM claims world's first sub-1 nanometer chip technology**](https://arstechnica.com/gadgets/2026/06/ibm-claims-worlds-first-sub-1-nanometer-chip-technology/) (4 minute read)

IBM's nanostack transistors push semiconductor manufacturing into territory considered physically implausible a few years ago, with the potential to boost chip performance or energy efficiency well beyond current process nodes.

[**Apple announces significant price increases for MacBooks, iPads, more**](https://9to5mac.com/2026/06/25/apple-price-increases-mac-ipad-more/) (4 minute read)

MacBooks are starting $100-$500 higher and iPads up by $100-$200. Tim Cook cited high-bandwidth memory demand from AI servers as making the current cost situation "unsustainable." Budget your hardware refreshes accordingly because a MacBook Pro I had in my cart went from $2800 to $3500. Ouch!

[**How Netflix Simplified Batch Compute with Kueue**](https://netflixtechblog.com/how-netflix-simplified-batch-compute-with-kueue-87860682629c) (6 minute read)

Netflix migrated their batch compute infrastructure from a homegrown platform to Kueue, a Kubernetes-native job queueing system, without disrupting end users. The switch unlocked advanced scheduling features like preemption and fair sharing across their distributed container platform at scale.

[**Introducing Minimus Community Edition: Free Hardened Container Images, Across Our Entire Gallery**](https://www.minimus.io/post/introducing-minimus-community-edition-free-hardened-container-images-across-our-entire-gallery) (4 minute read)

Minimus has launched a free Community Edition offering hundreds of hardened container images validated for FIPS, CIS, NIST SP 800-190, and STIG compliance -- no registration, no procurement. Drop-in replacements that reduce the ongoing vulnerability management tax on your team. I'm starting to use these images where appropriate.

[**CEL finds a new home at github.com/cel-expr!**](https://opensource.googleblog.com/2026/06/cel-finds-a-new-home-at-githubcomcel-expr.html) (3 minute read)

Google has moved Common Expression Language repositories from the `google/` namespace to a dedicated `cel-expr` GitHub organization, consolidating specs and implementations in Go, C++, C, Java, and Python. Web traffic and git operations auto-redirect, but update your dependency configs to point at the new canonical source.

[**The database that refused to die: How Postgres survived its own creators**](https://www.theregister.com/databases/2026/06/22/the-database-that-refused-to-die-how-postgres-survived-its-own-creators/5259716) (10 minute read)

PostgreSQL was nearly abandoned in the mid-1990s before a small volunteer community revived it, added SQL support, and built what is now foundational infrastructure for AWS, Azure, and Google Cloud. Stonebraker's line says it best: "Postgres is the epitome of open source software, because it doesn't belong to anybody."

[**A Practical Guide to SSH Tunnels: Local and Remote Port Forwarding**](https://labs.iximiuz.com/tutorials/ssh-tunnels) (15 minute read)

A clean, visual walkthrough of SSH tunneling covering local port forwarding, remote port forwarding, and dynamic SOCKS proxies, with practical labs for real-world situations like accessing private databases through bastions. Bookmark this for the next time someone asks you to explain it.

[**Vulnerability Reports Are Not Special Anymore**](https://words.filippo.io/vuln-reports/) (7 minute read)

Filippo Valsorda argues that coordinated disclosure has lost its edge now that LLMs can find security flaws nearly as well as human researchers, making the scarcity of insight and confidentiality less meaningful. The focus ought to shift toward efficient triage and prevention rather than treating vuln reports as inherently precious artifacts.

[**Fine-Tuning Your Own Model Is the Best Way to Get the Output You Want with Harper Carroll**](https://www.youtube.com/watch?v=xxhp3LxiIAs) (Video)

Harper Carroll makes the case that custom model fine-tuning is the most reliable path to getting consistent, desired outputs from AI, and walks through useful approaches for doing it effectively.

[**Europe 2031: What happens if Europe loses the AI race**](https://europe2031.ai/) (15 minute read)

A speculative scenario document tracing how Europe's failure to invest in competitive AI capabilities leads to economic sidelines and technological dependence on American and Chinese systems by 2031. The fictional characters and policy timeline make for a pointed read on what "falling behind in AI" actually looks like operationally.

[**Why Spreading Yourself Thin Feels Like Winning**](https://alifeengineered.substack.com/p/why-spreading-yourself-thin-feels) (6 minute read)

The author uses the board game Risk as an analogy for overcommitment: holding too many fronts leaves you exposed everywhere. "Every 'yes' is a check written against the future that has to be cleared." Depth in fewer areas beats breadth across many, especially in a career context.

[**visualdiffer/visualdiffer**](https://github.com/visualdiffer/visualdiffer) - GPL-3.0 - macOS application designed to visually compare folders and files

[**osolmaz/localpager**](https://github.com/osolmaz/localpager) - A local-first triage and paging tool for GitHub issues and pull requests that uses a local AI model to classify and route notifications to Discord

[**darrylmorley/whatcable**](https://github.com/darrylmorley/whatcable) - macOS menu bar app that tells you, in plain English, what each USB-C cable plugged into your Mac can actually do

{{< subscribe >}}
