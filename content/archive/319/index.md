---
author: Chris Short
date: '2026-07-26'
description: "A back-in-time NTP server that took down an Australian carrier, an OpenAI model that escaped its sandbox and breached Hugging Face, DoorDash's seven-nines cache, and Netflix on running LLMs in-house."
draft: false
slug: '319'
title: "DevOps'ish 319: An NTP server time-traveled to 2006, an OpenAI model broke into Hugging Face, and more"
---

{{< subscribe >}}

[**NTP server that traveled back in time caused massive Aussie mobile outage**](https://www.theregister.com/networks/2026/07/17/ntp-server-that-traveled-back-in-time-caused-massive-aussie-mobile-outage/5274059) (4 minute read)

A Telstra NTP server reset its clock to 2006 during maintenance and cheerfully broadcast the wrong time across the network, knocking out service and failing emergency calls. The root cause was an undocumented design change that left the GPS card misbehaving on restart, plus a software update Telstra knew about but never applied. Time is still the hardest problem in distributed systems, and this is your weekly reminder to keep your clocks in sync.

[**DoorDash Uses Envoy and Valkey for a 1.5M RPS Proxy Cache with 99.99999% Availability**](https://www.infoq.com/news/2026/07/doordash-entity-cache-proxy/) (3 minute read)

DoorDash built Entity Cache, a transparent proxy caching layer on Envoy and Valkey that serves north of 1.5 million requests per second at seven nines, taking load off backend data stores. The interesting part is that service teams did not have to change any application code to get it.

[**In-House LLM Serving at Netflix**](https://netflixtechblog.com/in-house-llm-serving-at-netflix-a5a8e799ea2c) (11 minute read)

Netflix's AI Platform teams walk through why they run the whole LLM stack themselves: engine selection, model packaging, API surface design, deployment strategy, and output constraint enforcement, plus the trade-offs that only surfaced under production load. Worth a read if you are weighing build versus buy for inference.

[**OpenAI says Hugging Face breach caused by one of its models**](https://www.axios.com/2026/07/21/openai-says-hugging-face-breach-caused-by-one-its-models) (3 minute read)

OpenAI says its GPT-5.6 Sol model and a more capable pre-release sibling escaped the testing sandbox during a cybersecurity evaluation and broke into parts of Hugging Face's production infrastructure to steal the test answers. File this one under sentences we did not expect to read in an incident report.

[**Announcing VulnHunter**](https://medium.com/capital-one-tech/announcing-vulnhunter-ce9784834ca9) (5 minute read)

Capital One open sourced VulnHunter, an AI-driven security tool that uses agentic reasoning to trace attacker pathways through source code, find vulnerabilities, and propose targeted fixes. Another entry in the "let the agent read your code for bugs" genre, this one from a bank that has to care whether it works.

[**The Arguments Against Open Source AI are Very Bad**](https://tombedor.dev/arguments-against-open-source-ai-are-very-bad/) (9 minute read)

The author takes apart the usual objections to open source AI models, arguing that open source has historically proven impossible to suppress and that restricting them is both impractical and economically self-defeating. Strong opinions, reasonably argued.

[**AI is more likely than humans to form biases when hiring**](https://www.technologyreview.com/2026/07/20/1140655/ai-biases-hiring-humans/) (5 minute read)

AI does not just inherit stereotypes from its training data; it manufactures fresh ones. New research finds hiring models can cook up their own biases, which is a fun wrinkle if you were hoping automation would make hiring fairer.

[**Why Netflix is betting on systems thinkers, not specialists, in the AI era | Elizabeth Stone (CPTO)**](https://www.youtube.com/watch?v=t0GiTyz4syY) (72 minute watch)

Netflix CPTO Elizabeth Stone on why the company wants systems thinkers over narrow specialists, treats AI fluency as a baseline expectation across the org, and still refuses to compromise on craft in engineering, product, and design.

[**Guide to data tools landscape for developers**](https://sinja.io/blog/data-landscape-guide-for-developers) (45 minute read)

A developer-focused tour of the modern data tooling landscape: the core concepts, the categories, and the buzzwords you keep nodding along to in meetings. Long, but a decent map if the data space makes your eyes glaze over.

[**Problematic Social Media Use and Attention-Deficit/Hyperactivity Disorder Symptoms in Adolescents**](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2851740?guestAccessKey=9298d7c8-e27e-415f-a31e-4e4345a6efcc) (28 minute read)

A longitudinal study of 11,286 U.S. adolescents found that year-over-year increases in problematic social media use tracked with higher parent-reported ADHD symptoms the following year in mid-adolescence, most notably among boys. It is a cohort study, so the usual correlation caveats apply, but it is worth a look.

[**humanlayer/12-factor-agents**](https://github.com/humanlayer/12-factor-agents) - Apache-2.0 / CC BY-SA 4.0 - Twelve design principles for building LLM-powered agents reliable enough to ship, covering context management, human-in-the-loop workflows, state and error handling, and small focused agents over heavy frameworks.

[**unblocked/engineering-social-graph**](https://github.com/unblocked/engineering-social-graph) - MIT - Builds a developer social graph from your GitHub PR review history, using community detection to surface team clusters and domain experts, then renders the whole thing as an interactive visualization.

[**ayghri/i-have-adhd**](https://github.com/ayghri/i-have-adhd) - MIT - A skill for coding agents that stops them from burying the answer: lead with the next action, number the steps, cut the preamble. ADHD-friendly output for Claude Code and Codex.

[**foru17/neko-master**](https://github.com/foru17/neko-master) - MIT - A tidy dashboard for visualizing local network traffic from gateways like OpenClash and Surge, with real-time metrics across domains, IPs, and proxy nodes, plus geolocation and multi-gateway support.

{{< sponsor >}}
