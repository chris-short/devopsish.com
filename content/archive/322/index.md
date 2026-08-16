---
author: Chris Short
date: '2026-08-16'
description: "The Linux wireless maintainer stops arguing with LLMs, KYAML gets kubectl to quit lying about Norway, Charity Majors says the skepticism window has closed, and five AI rivals agree on a plugin format that punts on permissions."
draft: false
slug: '322'
title: "DevOps'ish 322: Linux wireless shuts the door on AI slop patches, KYAML fixes the Norway Bug, and more"
---

{{< subscribe >}}

[**How to Pretty-Print Your Kubernetes YAML as KYAML and Why You'd Want To**](https://kubernetes.io/blog/2026/08/11/how-to-pretty-print-kubernetes-yaml-as-kyaml/) (5 minute read)

KYAML is a strict subset of YAML out of SIG CLI, proposed in KEP 5295. It double-quotes every value string, braces every map, brackets every list, and stops depending on whitespace for structure. That kills the Norway Bug, where `country: NO` quietly parses as boolean false. There is no new parser here; every KYAML file is still valid YAML, so any version of kubectl will eat it. `-o kyaml` shipped alpha in 1.34 and is beta and on by default in 1.35, and SIG CLI says there are no plans to make it the default output. Two separate `yamlfmt` binaries will convert what you already have.

[**Linux Wireless Maintainer Takes Firm Stance Against AI/LLM Generated Slop Patches**](https://www.phoronix.com/news/Linux-WiFi-Strict-AI-Slop-Patch) (3 minute read)

Johannes Berg, who maintains 802.11, mac80211, WWAN, and rfkill, will ignore essentially all syzbot AI generated patches unless a three second review says obviously right. His line: he will absolutely not "argue with an LLM that can bullshit out code faster than another computer can even deliver it to me by email." The scaling argument is the one that matters. Sprinkling checks all over the code with no regard for the architecture is not maintenance, and review bandwidth is a finite human resource. Syzbot has been turned off for wireless as a result.

[**Stop being skeptical about AI for development with Charity Majors**](https://newsletter.pragmaticengineer.com/p/stop-being-skeptical-about-ai-for) (5 minute read)

Charity Majors argues that skepticism was rational in 2025 and is not anymore, with her turning point in November 2025 and the credit going less to the model than to the harness around it going from shell script to serious infrastructure. She also delivers a verdict on twenty years of DevOps: half of it failed. "Ops people, learn to code" worked. "Software engineers, understand your code in production" did not, to this day. Her actual ask is that the people telling AI success stories also tell the cost story. Nobody on the Honeycomb team uses AI on Wednesdays.

[**Agentic Code Quality**](https://addyo.substack.com/p/agentic-code-quality) (8 minute read)

Addy Osmani's thesis is that code review does not scale once agents produce more code than any human will read, so quality has to move into the harness and the environment: unit and property tests, mutation testing, complexity budgets, lint rules that encode your architecture. When change volume outruns verification capacity, you get three options and only three. Scale the verification system, slow the agents down, or lower the bar. He is honest that the gap between useful output and slop still comes down to the skill of the team operating the loop.

[**Five AI rivals just backed a shared plugin standard. Here's why it matters for developers.**](https://thenewstack.io/agent-plugins-open-standard/) (5 minute read)

OpenAI, AWS, Cursor, GitHub, and Microsoft are behind Agent Plugins 1.0.0, a Vercel-initiated format that packages Agent Skills and MCP servers into a directory with a `plugin.json` manifest. Read it for the critique as much as the news. Pavan Madduri at Grainger points out that the minute something becomes write once run anywhere for agents, it becomes compromise once run everywhere, and the spec deliberately defers governance, installation policy, and permissions to the client. Version 1.0.0 covers exactly two component types. Commands, hooks, and agents stay vendor specific.

[**The Tokenpocalypse Is Here: Companies Are Scrambling To Stop Spending So Much on AI**](https://simonwillison.net/2026/Aug/7/pdfs-are-terrible/) (1 minute read)

Simon Willison's link blog on 404 Media reporting built from leaked Accenture meeting audio. Accenture's own internal data says it is not the engineers driving token consumption, it is everyone else, and one of the biggest chewers is converting PDFs into images and then into markdown. Simon's closing shot is the reason to click: maybe if Accenture works out that PDFs are a terrible medium for communicating information, they can push that message to the rest of the business world.

[**The Kubernetes Noisy Neighbour Problem Is Actually a Permissions Problem**](https://www.syntasso.io/post/the-kubernetes-noisy-neighbour-problem-is-actually-a-permissions-problem) (6 minute read)

Abby Bangser reframes noisy neighbours as an RBAC problem. Broad Kubernetes API access granted to one team is blast radius for every other tenant, plus re-verification work on every cluster upgrade. The Helm critique is fair on its own terms: Helm templates YAML but cannot watch cluster state and react, cannot gate on an approval workflow, and cannot pause mid-rollout. The back half is a Kratix pitch, and to Syntasso's credit they say plainly that Kratix itself needs broad permissions to manage CRDs and Jobs. The Kyverno and OPA advice for constraining who gets to author controllers stands regardless of what you buy.

[**Linux Bridge STP Timer Use-After-Free**](https://ssd-disclosure.com/linux-bridge-stp-timer-use-after-free/) (4 minute read)

A use-after-free in the bridge Spanning Tree Protocol code, found by n132 and sven sze and good for second place in the Linux privilege escalation category at TyphoonPWN 2026. A bridge that is administratively down with kernel STP enabled, plus a port driven into the LEARNING state, arms periodic STP timers with no `IFF_UP` guard, which leaves timer lists queued on per-CPU timer bases after the `net_device` is freed. Fixed upstream in commit 2a00517db8de. Go patch your kernels.

[**Terraform + Terragrunt + Ansible: A Hands-On Learning Journey**](https://dev.to/tahayagizguler/terraform-terragrunt-ansible-a-hands-on-learning-journey-jed) (8 minute read)

A working lab instead of a think piece. Taha Yağız Güler builds three Terraform modules for VPC, security group, and EC2 on AWS, runs three environments off one shared base config through Terragrunt, keeps state in S3 with a DynamoDB lock table, and hands off to Ansible via an `aws_ec2` dynamic inventory keyed on tags. The parts worth stealing are the verification exercises: an IAM isolation test where a dev-scoped state policy correctly gets AccessDenied writing to prod, and an idempotency run that goes from changed=8 to changed=0. Companion repo is linked at the end.

[**srelens/srelens**](https://github.com/srelens/srelens) - MIT - The Kubernetes control room, built in Rust, ready for engineers and AI agents. A local-first Tauri desktop workspace on kube-rs with multi-cluster switching, server-side apply with dry-run diffs, log streaming, port forwarding, Helm rollbacks, and a built-in MCP server.

[**vitali87/code-graph-rag**](https://github.com/vitali87/code-graph-rag) - MIT - The ultimate RAG for your monorepo. Tree-sitter parses thirteen languages into a Memgraph knowledge graph, natural language questions become Cypher queries, and runtime tracing merges the calls that static analysis never sees.

[**AntigmaLabs/ante**](https://github.com/AntigmaLabs/ante) - Apache-2.0 - A self-contained agent harness in a single 15MB Rust binary with no runtime dependencies, 17 provider presets, and offline inference through a pinned llama.cpp. Worth noting the core harness is not open sourced yet; this repo holds the docs, protocol, and SDK.

[**denoland/celld**](https://github.com/denoland/celld) - Apache-2.0 - Self-hosted, distributed Durable Objects. Runs Cloudflare Workers and Durable Objects on your own machines, each cell its own SQLite database, coordinated through a bucket you own with no control plane and no consensus.

{{< sponsor >}}
