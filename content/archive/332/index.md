---
author: Chris Short
date: '2026-10-25'
description: "PHP2Shell gets exploited before the patch while PHP blames Chainguard for breaking the embargo, eMudhra quits the TLS certificate business after its private keys turn out to be recoverable, the leap second is officially dead, and Meta reworks the page cache patch Linus wrote with Claude Code."
draft: false
slug: '332'
title: "DevOps'ish 332: PHP2Shell blows the embargo, eMudhra loses its keys, the leap second dies, and more"
---

{{< subscribe >}}

[**Docker builds that remember more than layers**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-10-25) (Sponsor)

WarpBuild remote Docker builders are persistent BuildKit machines. They keep your layer cache and your RUN --mount=type=cache directories, so Go, npm, and Cargo caches stay warm between builds. Multi-arch amd64 and arm64 builds work out of the box. Swap in one action and try it with $50 in free credits using code START50.

[**Token Governance Summit: budgets that don’t stop developers mid-task**](https://fandf.co/4znB6ix) (Sponsor)

Hard token budgets can cut developers off mid-task, and dashboards alone don’t tell you which spend is worth it. Join the virtual Token Governance Summit (Oct 27, 12 PM ET) to hear from builders on how they’re managing spend and model routing, ending with a first look at how Stacklet Token Custodian enforces policy.

[**2026 State of OSPOs**](https://fastwonderblog.com/2026/10/20/2026-state-of-ospos/) (3 minute read)

The Linux Foundation and TODO Group released the 2026 State of OSPOs report at Open Source Summit Europe in Prague, and Dawn Foster picked out the parts worth your time. 64% of OSPOs were created in the last five years. Asia-Pacific leads in planned OSPOs at 20%, and Europe has the most organizations that never set one up (49%). She expects that to change with the CRA and the EU's digital sovereignty push. OSPOs making secure software decisions went from 37% in 2024 to 46% in 2026, and 58% now do AI-related work. The hardest part of starting one is still justifying the budget (37%) and getting an exec to care (34%). That tracks with every OSPO conversation I've ever had.

[**PHP blames supply chain security biz Chainguard for putting huge chunks of the web at risk**](https://www.theregister.com/security/2026/10/22/php-blames-supply-chain-security-biz-chainguard-for-putting-huge-chunks-of-the-web-at-risk/5304611) (6 minute read)

PHP2Shell is two memory corruption bugs (CVE-2026-109618 and CVE-2026-109619) that allow unauthenticated remote code execution, and Wiz says every PHP release since 5.4 is hit by at least one of them. The disclosure was a mess. CVE IDs leaked on social media, Calif "mistakenly" posted a PoC video, and the PHP Foundation says Chainguard broke the embargo by shipping fixed images more than six hours early. Dan Lorenc doesn't dispute the timeline. He says people were already getting hit, so Chainguard shipped. He also says he found the same bugs himself on a Friday night with an AI harness and the prompt "find bad vulnerabilities in PHP." That's the part that should keep coordinated disclosure people up at night.

[**Hackers Exploited the PHP Vulnerabilities Days Before They Were Patched**](https://www.wired.com/story/hackers-exploited-the-php-vulnerabilities-days-before-they-were-patched/) (3 minute read)

AWS reviewed its honeypot logs and found someone poking at PHP2Shell from a commercial anonymization network on October 17, four days before the public fix. Nobody knows how they got exploit details while the bugs were still under embargo. AWS CISO CJ Moses says AI makes it cheap to turn a patch diff into a working exploit, so more attackers can move within hours or minutes of disclosure. The PHP Foundation says it knows of no successful RCE yet. Patch anyway.

[**Indian firm eMudhra exits global digital certificates business after vulnerability disclosure**](https://www.reuters.com/legal/litigation/indian-firm-emudhra-exits-global-digital-certificates-business-after-2026-10-22/) (3 minute read)

A researcher found that private keys for some eMudhra intermediate certificates could be rebuilt from the public certificates themselves. Google, Mozilla, Apple, and Microsoft blocked its certs; Mozilla pulled the emSign ECC Root CA - G3 root, and CERT-In issued an advisory. eMudhra is now leaving the global SSL/TLS business, says it's only 1% of revenue, and is pointing customers to Sectigo. Its shares dropped 40% in two days. When the WebPKI decides it's done trusting a CA, it moves fast.

[**The Leap Second Is No More**](https://www.wired.com/story/leap-second-is-abolished-bipm-says/) (4 minute read)

The BIPM will stop issuing leap seconds in May 2027 after adding 32 of them since 1972. A big reason is that Earth has been spinning faster, and a never-tested negative leap second could have been needed as soon as 2029. Industry tests of a negative leap "showed several failures." Anyone who has been paged over a leap second (hi, Qantas in 2012) can stop worrying. There's a leap hour on the books instead, but that's millennia away and somebody else's on-call shift.

[**Linus Torvalds' AI Code Improved: Huge Performance Wins With Reworked Code**](https://www.phoronix.com/news/Reading-Page-Cache-WO-Folio-Ref) (2 minute read)

Last week Linus put up a branch, written with Claude Code, that reads from the page cache without taking folio references. Now Meta's Kiryl Shutsemau has reworked it into an RFC patch series for `filemap_read()` and shmem, where a folio a reader might copy from only gets freed after an RCU grace period. It was benchmarked on EXT4, TMPFS, XFS, and a raw block device with 64 threads on a Threadripper, and the gains look big. Design questions are still open, so don't expect it in mainline next week.

[**Inside Prometheus: Meta's Journey to a Gigawatt-Scale Supercluster**](https://engineering.fb.com/2026/10/19/data-center-engineering/inside-prometheus-meta-gigawatt-scale-supercluster/) (16 minute read)

Meta turned a regular web-serving data center site in New Albany, Ohio, into a training cluster with hundreds of thousands of GPUs, and it's headed toward about 1 million. The ops details are the good part. Each NVL72 rack runs a 64-GPU slice and keeps eight GPUs as in-rack spares, so a dead GPU means a checkpoint restart, not a hardware ticket. The backend aggregation network spans 2 km to over 100 km. When a job starts or stops, the power load can swing by tens of megawatts in seconds, so a system called Dynamo Dimmer caps GPU power before the grid gets a vote. Goodput was over 85% for pre-training and over 90% for RL. Long, but worth it if you run anything at scale.

[**Weak Links in A.I. Borrowing Begin to Emerge**](https://www.nytimes.com/2026/10/17/business/ai-debt-coreweave-oracle-softbank.html?unlocked_article_code=1.JlE.rX3L.o-a8bpYnYQtO&smid=nytcore-ios-share) (6 minute read)

The New York Times looks at the money behind the AI data center boom through CoreWeave, Oracle, and SoftBank. The question is whether their debt troubles are company-specific or a structural crack in how all this capacity is getting financed. CoreWeave's bond yields went past 15% this month. Somebody is going to be holding the bag for a lot of GPUs, and it's worth knowing who before your cloud provider's provider has a bad quarter.

[**Introducing Flint**](https://recursive.com/updates/introducing-recursive-flint) (5 minute read)

Recursive released Flint, a 40B parameter mixture-of-experts coding model that activates 2.5B parameters per token. The weights are on Hugging Face under Apache 2.0. They claim more than 125 tokens per second on an M4 Pro MacBook Pro and say it leads sub-50B MoE models on SWE-Bench Pro v2, Terminal-Bench 2.1, and SWE-Bench Verified. It works with llama.cpp, Ollama, LM Studio, vLLM, and SGLang. The other pitch is that their automated research system, the "Eureka Machine," helped build most of it in under four months, including quantizing the output layer to 4 bits against common practice. Benchmarks are vendor numbers, so try it on your own repo before you believe anything.

[**Encryption Is Getting Squeezed From All Sides**](https://www.wired.com/story/kernel-panic-encryption-is-getting-squeezed-from-all-sides/) (4 minute read)

Canada's C-22 bill could make tech companies, including ones outside Canada, build "technical capabilities" for law enforcement access and keep user metadata. Signal says it would leave Canada. Psiphon says the same, and DuckDuckGo and NordVPN say they'd consider it. The bill promises no "systemic vulnerability," which is the same promise every one of these bills makes and the same one cryptographers keep saying can't be kept. The UK and Australia already have similar powers, so the list of safe places to run a privacy service keeps getting shorter.

[**US bans China's DeepSeek from government in race for AI dominance**](https://www.bbc.com/news/articles/cjkgeq0k1wevo) (3 minute read)

DHS ordered DeepSeek and anything built with its models out of civilian federal agencies like Treasury, State, and Justice. The Department of Defense is excluded. The ban quietly took effect at the end of July and only became public this week. DHS didn't spell out the security concerns. If you're a vendor selling to the government and quietly swapped in DeepSeek to save on inference costs, now's a good time to check your bill of materials.

[**What If Your AWS Bill Suddenly Doubled? Build a Cost Anomaly Detector with Terraform**](https://builder.aws.com/content/3KiMU2ja37QXZFxe8SF1ivoV6H6/what-if-your-aws-bill-suddenly-doubled-build-a-cost-anomaly-detector-with-terraform) (6 minute read)

Sudip Paramanik builds a small serverless cost watchdog in Terraform. EventBridge runs a Lambda daily; it pulls numbers from Cost Explorer, compares yesterday to the prior seven-day average, and emails you through SNS when spending crosses a threshold you set. AWS Cost Anomaly Detection already exists, and the post says so, but building your own is a good way to learn the pieces and lock down IAM to exactly what you need. Cheaper than finding out from your finance team.

[**oxc-project/tsrs**](https://github.com/oxc-project/tsrs) - Apache-2.0 - Rust port of the TypeScript 7 type checker

[**tailscale-dev/ScaleTail**](https://github.com/tailscale-dev/ScaleTail) - MIT - Ready-to-run Docker Compose stacks for 120+ self-hosted apps, each with a Tailscale sidecar and automatic HTTPS

{{< sponsor >}}
