---
author: Chris Short
date: '2026-07-12'
description: "A 16-year-old KVM flaw, etcd v3.7.0, Go 1.26's quiet fixes, git worktrees, and six GitHub security settings to enable this week."
draft: false
slug: '317'
title: "DevOps'ish 317: Januscape Turns 16, etcd Hits 3.7, and More"
---

[**With Talos, most CVEs never apply, and patching the rest won't break the fleet.**](https://www.siderolabs.com/?utm_source=devopsish&utm_medium=newsletter&utm_campaign=gen-cve)

Patching a CVE means knowing whether it applies to you, then getting the fix to every node without missing one. Talos Linux ships fewer than 50 binaries, because that's all it takes to run Kubernetes, so most CVEs never apply. Omni rolls out the ones that do, staged and health-checked, with automatic rollback if a node fails.

[**Designing IaC Interfaces That Work for Humans, AI Agents, and Whatever Comes Next**](https://events.iacconf.com/designing-iac-interfaces-july-2026-spotlight/?refid=DevOpsish&utm_campaign=46400040-FY26%20-%20Virtual%20Event%20-%20IaCConf%20Designing%20IaC%20Interfaces%20July%202026&utm_source=DevOpsish&utm_medium=email&utm_content=Email%20placement%20-%20WV%20-%20IaCConf%20Spotlight%20July%202026%20-%20variation%20A) (SPONSOR)

AI agents are changing who, or what, uses your Terraform modules. Join Jinger Meilani, Senior DevOps Engineer at MNTN, to learn how to design reusable, self-service IaC interfaces that reduce misuse and work for humans, AI agents, and whatever comes next.

[**Announcing etcd v3.7.0**](https://kubernetes.io/blog/2026/07/08/announcing-etcd-3.7/) (11 minute read)

 SIG etcd ships v3.7.0 with a new RangeStream API for streaming large result sets, keys-only range and faster lease optimizations, plus removal of the legacy v2 store. The quiet workhorse under every Kubernetes cluster gets a meaningful tune-up.

[**6 Security Settings Every GitHub Maintainer Should Enable This Week**](https://github.blog/security/6-security-settings-every-github-maintainer-should-enable-this-week/) (5 minute read)

Six free GitHub features, including SECURITY.md, private vulnerability reporting, secret scanning with push protection, Dependabot, code scanning, and branch protection, that you can turn on in under half an hour. Do it before someone else finds the gaps.

[**16-Year-Old Linux KVM Vulnerability Allows Malicious Guest to Corrupt Host Kernel Memory**](https://cybersecuritynews.com/16-year-old-linux-kvm-vulnerability/) (4 minute read)

CVE-2026-53359, nicknamed Januscape, is a shadow-paging flaw in KVM's nested virtualization that allows a hostile guest to corrupt host kernel memory on both Intel and AMD platforms. If you run untrusted tenants, this is your week.

[**What are git worktrees, and why should I use them?**](https://github.blog/ai-and-ml/github-copilot/what-are-git-worktrees-and-why-should-i-use-them/) (6 minute read)

A plain walkthrough of Git worktrees, the decade-old feature that lets you check out multiple branches into separate folders instead of stashing and switching all day. Suddenly relevant again now that everyone runs three agents at once.

[**GitHub Stacked PRs**](https://github.github.com/gh-stack/) (3 minute read)

A GitHub-native CLI and UI for breaking one enormous change into a stack of small, dependent pull requests that build on each other. Easier to review, easier to land. A practical way to keep big changes moving.

[**The (Petty) Reason We Didn't End Up Using jj**](https://blog.gradle.org/the-petty-reason-we-didnt-end-up-using-jj-at-gradle) (5 minute read)

Gradle's team walks away from adopting Jujutsu because it ignores .gitattributes, leaving phantom modifications on gradlew.bat for every Windows contributor. Small thing, real blocker, honest writeup.

[**Go 1.26 Quietly Fixed the Things That Were Actually Annoying**](https://towardsdev.com/go-1-26-quietly-fixed-the-things-that-were-actually-annoying-5b4876071f04) (7 minute read)

A tour of the Go 1.26 quality-of-life fixes that read less like a changelog and more like a list of apologies for long-standing papercuts. Small changes, big relief.

[**Open source governance isn't one model. Here's how it actually works.**](https://allthingsopen.org/articles/open-source-governance-models-plain-language-guide) (8 minute read)

A plain-language guide that maps the major governance models, from BDFL to lazy consensus, and explains how real projects layer several at once for different kinds of decisions. Useful if your project's governance is currently vibes and a Slack channel.

[**Introducing kiac: Real Kubernetes Nodes on Your Mac, Each Its Own Lightweight VM**](https://blog.kubesimplify.com/introducing-kiac-kubernetes-in-apple-containers) (17 minute read)

kiac runs a local Kubernetes cluster on macOS in which every node is a full lightweight VM via Apple's containerization framework, so you get real isolation and independent failure domains instead of shared-kernel fakery. A cleaner setup for local testing.

[**GitHub Has Restricted Access to Star Data**](https://www.star-history.com/blog/github-stargazer-api-restriction/) (2 minute read)

GitHub locked the stargazers API down to repo admins and collaborators, which broke Star History's charts for repositories you don't own. One more data source quietly walled off. Another subtle change with a broad impact. I know this might help me get spammed less, so I'm all for it.

[**Sandboxing an AI Agent**](https://sajalsharma.com/posts/sandboxing-an-ai-agent/) (14 minute read)

A hands-on look at isolated execution environments for AI agents, weighing two architectures for the security, parallelism, and reproducibility you actually want before you let code run itself.

[**DeepSeek open sources DSpark, a new framework to speed up LLM inference by up to 85%**](https://venturebeat.com/orchestration/deepseek-open-sources-dspark-a-new-framework-to-speed-up-llm-inference-by-up-to-85) (7 minute read)

DeepSeek and Peking University open sourced DSpark, an MIT-licensed speculative decoding framework that claims 60 to 85 percent faster per-user generation and large throughput increases, all on hardware you already own.

[**google/copybara**](https://github.com/google/copybara) - Apache-2.0 - Copybara: A tool for transforming and moving code between repositories.

[**OthmanAdi/planning-with-files**](https://github.com/OthmanAdi/planning-with-files) - MIT - Persistent file-based planning for AI coding agents and long-running agentic tasks. Crash-proof markdown plans that survive context loss and /clear, plus a deterministic completion gate and multi-agent shared state on disk.

{{< subscribe >}}
