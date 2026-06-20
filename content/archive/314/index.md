---
author: Chris Short
date: '2026-06-21'
description: "GitHub dismissed the bug reports. Now a supply-chain worm is loose. Norway banned AI for kids. Apple's raising prices. Local Inference."
draft: false
slug: '314'
title: "DevOps'ish 314: GitHub Ignored the Reports, Norway Didn't, AI Needs More Discipline, and More"
---

[A security reviewer on every PR that touches a dependency.](https://www.mendral.com/?utm_source=devopsish) (SPONSOR)  
Most PR reviewers read the diff in your repo. Nobody pulls the source of the dep that just got added or bumped. That's where supply chain attacks live: a new postinstall script, a network call to a fresh domain, an obfuscated blob. Mendral runs on every PR that touches dependencies as a security-minded reviewer. It checks how recently the version was published, reads the dep's actual code diff, and flags suspicious patterns before merge.

[How I'm Solving Local Inference](https://chrisshort.net/how-im-solving-local-inference/) - Running powerful models locally across two laptops using LM Studio's LM Link, trading token costs for portability between a MacBook Air and Framework 13. Worth a look if you're tired of the meter running or have a lightweight daily driver and a beefier box somewhere.

[GitHub dismissed security reports on flaws now exploited by supply-chain worm, researchers say](https://therecord.media/github-dismissed-reports-shai-hulud-deep-specter) - Deep Specter documented two vulnerability reports GitHub rejected, both of which are now being actively exploited by the Shai-Hulud supply-chain worm, which has already compromised hundreds of packages and developer accounts across major code repositories.

[The Korean Telecom Giant at the Center of Anthropic’s Mythos Controversy](https://www.wired.com/story/sk-telecom-anthropic-mythos-export-controls/) - Wired names SK Telecom as the Korean carrier whose access to Anthropic's Claude Mythos model the White House ordered revoked over alleged China ties, a dispute that eventually led the Commerce Department to bar all foreign nationals from accessing Fable 5 and Mythos entirely.

[AI demands more engineering discipline. Not less](https://charitydotwtf.substack.com/p/ai-demands-more-engineering-discipline) - When code generation becomes free and instant, the real engineering work -- understanding user needs, defining invariants, validating behavior -- becomes more critical, not less. Charity Majors argues stricter practices are the answer to cheap code, not loosened ones.

[Working Effectively with Claude Code](https://blog.scottlogic.com/2026/06/18/working-effectively-with-claude-code.html) - Practical strategies for getting the most out of Claude Code, covering parallelization, model selection, workflow optimization, and security considerations. Good field notes from people who have put in the reps.

[Norway imposes near ban on AI in elementary school](https://www.reuters.com/technology/norway-imposes-near-ban-ai-elementary-school-2026-06-19/) - Starting this August, Norway is largely prohibiting generative AI for kids ages 6 to 13 and restricting it for older students, citing declining test scores and concern that AI lets children skip foundational reading, writing, and math.

[Amazon claims data centers are 7-times more water-efficient than rivals as Seattle pauses new builds](https://www.geekwire.com/2026/amazon-claims-data-centers-are-7-times-more-water-efficient-than-rivals-as-seattle-pauses-new-builds/) - Amazon says its data centers use 0.12 liters of water per kilowatt-hour versus the industry average of 0.84, a figure published two days after Seattle unanimously approved a one-year moratorium on new large data centers inside city limits.

[Apple confirms price increases are coming to its products due to RAM shortage](https://9to5mac.com/2026/06/17/apple-confirms-price-increases-are-coming-to-its-products-due-to-ram-shortage/) - Tim Cook confirmed Apple will raise product prices due to memory supply constraints and increased costs from the global RAM shortage. Budget accordingly.

[Making HTTP requests from a container that has no curl, using bash /dev/tcp](https://mareksuppa.com/til/bash-dev-tcp-http-without-curl/) - A clean walkthrough of using bash's built-in `/dev/tcp` to make HTTP requests when curl and wget are nowhere to be found in a minimal container environment. One for the "I knew this was possible but never had a reason to look it up" file.

[Barre/ZeroFS](https://github.com/Barre/ZeroFS) - GNU AGPLv3 - ZeroFS serves S3-compatible buckets as POSIX filesystems over NFS and 9P, or as raw block devices over NBD.

[intel/intel-performance-skills](https://github.com/intel/intel-performance-skills) - MIT - Open-source collection of AI agent skills for CPU performance analysis and optimization on x86 Linux, with support for Claude Code, GitHub Copilot, Codex, and Gemini CLI.

[EpicGames/lore](https://github.com/EpicGames/lore) - MIT - A next-generation, open source version control system from Epic Games.

[tamnd/kage](https://github.com/tamnd/kage) - MIT - Shadow any website for offline viewing, with the JavaScript stripped out.

{{< subscribe >}}
