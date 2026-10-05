---
author: Chris Short
date: '2026-10-04'
description: "Netflix lets an automated tuner shrink its media processing containers in production and owns up to the 50% memory cut that sent retries past 60%, Netlify swaps V8 isolates for Firecracker MicroVMs and gets Edge Functions down to about 6ms, codecentric argues Terraform has no business running your developer platform while Pinterest shows how to fence it in anyway, and Microsoft ships Linux containers on Windows with WSLC."
draft: false
slug: '329'
title: "DevOps'ish 329: Netflix lets a robot shrink its containers, Netlify dumps V8 isolates, Terraform is the wrong tool, and more"
---

{{< subscribe >}}

[**Work Through Real Problems at AWS re:Invent**](https://bit.ly/4y9YC1b)  (SPONSOR)

AWS re:Invent runs November 30 to December 4 in Las Vegas. Roughly 70% of the 2,200+ sessions are hands-on or discussion-based: chalk talks, builders' sessions, workshops, and code talks where you sit with the engineers who built the service. Topics run from ETL and EDA to microservices on Kubernetes and inference at scale on EKS, with 70+ security sessions included. Register today.

[**Netflix Stratum Media Processing: Automated Container Right-Sizing**](https://netflixtechblog.medium.com/netflix-stratum-media-processing-automated-container-right-sizing-ddf9aa68a801) (14 minute read)

Netflix built a tuner that shrinks over-provisioned media processing containers in production with no human in the loop. Every recommendation goes through a synthetic replay, then a 5% production canary, then 90 days of monitoring. The best part is the failure story. A 50% memory cut passed every check, ran fine for two weeks, and then a traffic shift pushed retries past 60%. Now reductions are capped at 15% per step with automatic reverts. One encoder went from 8 CPUs to 4.

[**5x faster Edge Functions: How we replaced v8 isolates with Firecracker MicroVMs**](https://www.netlify.com/blog/edge-functions-firecracker-microvms/) (9 minute read)

Netlify moved Edge Functions off a hosted V8 isolate service and onto Firecracker MicroVMs inside its own network, working with Unikraft. Warm invocations dropped from 25 to 40ms down to about 5 to 6ms at the median. Rendezvous hashing keeps a function on the same compute node so it stays warm, and that stickiness gets relaxed when one customer's traffic would swamp a node. They're blunt about why they moved: "V8 isolates, no matter their name, do not provide this level of isolation." Also, it wasn't always DNS. Their words, not mine.

[**Terraform is the wrong tool for building developer platforms**](https://www.codecentric.de/en/knowledge-hub/blog/terraform-is-the-wrong-tool-for-building-internal-developer-platforms) (14 minute read)

Marc Schnitzius argues that Terraform has no runtime. It reads state, talks to providers, and exits. Build a platform on it, and you end up owning state locking, cron-driven "reconciliation," and pipelines that hand back an exit code where a status should be. His answer is Kubernetes, Crossplane, and ClusterAPI, with Terraform kept for bootstrapping and slow-moving resources. The section on agents hitting a pull-request-shaped platform at machine speed is the part to share with your platform team.

[**Securing Infrastructure at Scale: Introducing Pinterest's Resource Provisioner Pipeline (RPP)**](https://medium.com/pinterest-engineering/securing-infrastructure-at-scale-introducing-pinterests-resource-provisioner-pipeline-rpp-8283bb12cbe5) (6 minute read)

And here's the other side of that argument. Pinterest kept Terraform and fenced it in. RPP runs hundreds of workspaces across tens of thousands of AWS resources via centralized GitHub Actions. GitHub OIDC gets you a central role, a source-of-truth file maps each workspace to one repo path, and only then does the pipeline chain down to a team-scoped IAM role. The pipeline fails the build if someone points a backend block at another team's state. Apply takes an explicit PR comment. If you're stuck with multiple repos, this is a design worth copying.

[**Microsoft Announces General Availability Of WSLC: Linux Containers On Windows**](https://www.phoronix.com/news/Microsoft-WSLC-Linux-Containers) (2 minute read)

WSLC is now GA. You get a `wslc.exe` command, each session gets its own storage VHD, and the networking model differs from regular WSL. Microsoft says it's open source, and the code lives in the microsoft/wsl repo. Docker Desktop on Windows just picked up a first-party competitor.

[**A Staff Engineer's Guide to Inventing Work**](https://sujithjay.com/inventing-work) (8 minute read)

Platform teams rarely get a product manager or a revenue line, so the work only exists if an engineer comes up with it. Sujith Jay Nair lists where to look: postmortems, the cloud bill, your own toil, users bending your platform to jobs it was never built for, and things your manager says twice in one week. The warning I liked is that your toil isn't your users' toil. Fixing the first helps unit economics. Fixing the second helps the people you're actually there for.

[**Putting the trace before the loop**](https://dbln.me/blog/building-an-ai-agent-observability-first) (15 minute read)

Dragos Bilaniuc built the whole tracing layer for an AI support agent before writing the agent loop. That forced him to ask production debugging questions on day one, like what the trace should show when a tool span never finishes. Then the span tree turned out to be the loop's control flow. Langfuse is a place for humans to look, never a source for evals. He's honest about the downsides, and there's a section for people who don't have a fresh codebase.

[**Modern Motherfucking Website**](https://modernmotherfuckingwebsite.dreamstation.systems/) (7 minute read)

A 2026 sequel to the 2013 classic, and just as profane. Semantic elements, `<details>`, JSON-LD, Open Graph, responsive images, and dark mode are all plain HTML and CSS. The page itself is a single file of about 23 KB with no build step. It also takes on the "but I have 500 pages" and "but I'm building a real app" objections fairly, which the original version never bothered to do. View source when you're done.

[**First Principles Thinking**](https://sunilsadasivan.com/writing/first-principles-thinking/) (3 minute read)

Sunil Sadasivan, writing off the back of Sunil Pai's "the senior engineer death spiral," says the engineers doing well with agents are the ones willing to put their experience in a box long enough to see the problem again. Short and worth it. Bonus points for the two-Sunils bit.

[**An Ode to Showing Up**](https://thegrowtheq.com/an-ode-to-showing-up/) (5 minute read)

Brad Stulberg on consistency beating intensity. 25 publishers rejected his first book, and he hit the bestseller list 20 years after his first published piece. "How I feel in the moment doesn't determine how this will go." Anyone who's carried a pager or kept a weekly newsletter going knows the feeling.

[**yonahd/kor**](https://github.com/yonahd/kor) - MIT - A Golang tool to discover unused Kubernetes resources. Kor lists orphaned ConfigMaps, Secrets, Services, PVCs, CRDs, RBAC objects, and about 20 other kinds, and it shows why each one counts as unused. Install it with Homebrew, krew, Docker, or `go install`, or use the Helm chart to run it as a CronJob that posts to Slack. It can also delete with `--delete`, and it asks Y/N for each object unless you tell it not to. Let it ask. A paid multi-cluster product called KorPro sits on top, but the CLI is the useful bit.

[**nklmilojevic/sofka**](https://github.com/nklmilojevic/sofka) - MIT or Apache-2.0 - A Kubernetes TUI, reimagined in Rust, built on kube-rs and ratatui. It's k9s-shaped, but Flux and Argo CD controls are built in through native API patches, so you don't need the `flux` or `argocd` binaries. There's a native Helm release inspector too. The `X` key opens a deterministic "why is this broken" view with no AI or external service involved, and read-only guardrails make "never delete in prod" something it enforces instead of something you remember. Three months old, 1,600 stars, and named after a Russian Blue that stares at the monitor. macOS binaries aren't signed yet.

[**awslabs/iam-policy-autopilot**](https://github.com/awslabs/iam-policy-autopilot) - Apache-2.0 - Static code analysis that writes baseline IAM identity policies from the AWS SDK calls in your code. It's a CLI and an MCP server, so your coding assistant can call it. It supports Go, Java, JavaScript, TypeScript, and Python, and it can also read a Terraform plan in JSON. Pass `--service-hints`, or a method called `listAccounts()` might drag in Organizations permissions you never asked for. It doesn't do resource policies, SCPs, or permission boundaries. Use `uvx` or `pip` instead of the `curl | sudo sh` option.

[**mobile-next/mobile-mcp**](https://github.com/mobile-next/mobile-mcp) - Apache-2.0 - MCP server for mobile automation and scraping on iOS and Android emulators, simulators, and real devices. It reads the native accessibility tree first and only falls back to screenshots and coordinate taps when needed, so you skip the vision model and the image tokens. It covers app install, launch, gestures, deep links, and screen recording without XCUITest or Espresso. 8,600 stars. A paid cloud device fleet is part of the pitch.

[**dirien/jev-router**](https://github.com/dirien/jev-router) - Apache-2.0 - Pass-through model router for Claude Code and Codex CLI that uses TypeSafe AI's Jev to pick a model tier each time a human sends a message. It only decides when a person writes, and within a session it only moves up, because switching models mid-task wrecks the prompt cache. No runtime dependencies beyond Node 22. Install it as `@ediri/jev-router`, because the unscoped npm name belongs to an unrelated project. Nine days old and 8 stars, so treat it like a weekend project you're curious about.

[**NVIDIA/Model-Optimizer**](https://github.com/NVIDIA/Model-Optimizer) - Apache-2.0 - A unified library of model optimization techniques: quantization, distillation, pruning, neural network search, speculative decoding, and sparsity. It takes Hugging Face, PyTorch, or ONNX models and exports checkpoints for TensorRT-LLM, vLLM, and SGLang. The recent NVFP4 work with quantization-aware distillation is the headline, including a Qwen3.6-35B-A3B tutorial claiming up to 1.30x vLLM throughput over BF16 with 3.1x smaller checkpoints. Formerly TensorRT Model Optimizer.

{{< sponsor >}}
