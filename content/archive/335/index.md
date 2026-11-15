---
author: Chris Short
date: '2026-11-15'
description: "Jensen Huang resigns as Nvidia CEO, KubeVirt graduates from the CNCF, an outage grounds every US flight, a 256-character password walks into musl-based sshd, and GitHub rebuilds its Git storage to survive the agents."
slug: '335'
title: "DevOps'ish 335: Jensen Huang resigns, KubeVirt graduates, the FAA grounds everything, and more"
---

{{< subscribe >}}

[**Your CI volume doubled. Your ARC team did not.**](https://www.warpbuild.com/start?utm_source=devopsish&utm_medium=newsletter&utm_campaign=h2-2026&utm_content=devopsish-2026-11-15) (Sponsor)

Every AI-assisted pull request runs your pipeline, and self-hosted runners need someone to scale, patch, and debug them. Move those jobs to WarpBuild with one runs-on change. Capacity scales elastically, and runners are twice as fast at half the cost. Try it with $50 in free credits using code START50.

[**Cloud Native Computing Foundation Announces KubeVirt Graduation**](https://www.cncf.io/announcements/2026/11/10/cloud-native-computing-foundation-announces-kubevirt-graduation/) (5 minute read)

KubeVirt graduated at KubeCon North America in Salt Lake City, ten years after Red Hat started it. It went Sandbox in 2019, Incubating in 2022, and now has 2,088 contributors from 520 organizations. Production users include ByteDance, Cloudflare, CoreWeave, and NVIDIA, and Swisscom runs 390 clusters on it for a sovereign managed Kubernetes service. The roadmap is where it gets interesting: GPU claims through Dynamic Resource Allocation hit beta in v1.9, confidential VMs cover AMD SEV, IBM Secure Execution, and Intel TDX, and a pluggable framework should let Cloud Hypervisor, OpenVMM, or Firecracker stand in for KVM. Plenty of folks are looking for somewhere to land their VMs right now. This makes that conversation easier.

[**Claude for CNCF maintainers**](https://claude.ai/cncf) (1 minute read)

Lucy Sweet announced at KubeCon that Anthropic is giving the CNCF 3,000 Claude Ultra codes for project maintainers. If you maintain a CNCF project, ask for one through the CNCF ServiceDesk.

[**Flights halted at airports across US due to air traffic control communications problems, FAA says**](https://apnews.com/article/flights-halted-airports-faa-f81b0904331dafad6133f291e5f531a8) (4 minute read)

On Friday the FAA grounded every flight in the country over a telecommunications outage hitting the 22 regional centers that handle planes en route. It's only the second nationwide stop since 9/11 and the first since the NOTAM system face-planted in January 2023. More than 800 flights diverted before the ground stop lifted that evening. Homeland Security says there's no sign of a cyberattack. Later reporting has officials blaming FAA updates and checking for any link to a new AI system being rolled out to reroute planes. No official root cause yet.

[**Jensen Huang Resigns as Nvidia CEO**](https://www.wired.com/story/nvidia-ceo-jensen-huang-steps-down/) (5 minute read)

Jensen Huang resigned as Nvidia's CEO and left the board on Thursday, four days after the board opened an investigation into his affair with Alice Huang, an alleged Chinese Ministry of State Security asset (China denies she's a spy). CFO Colette Kress is interim CEO while the board looks at internal and external candidates. A WIRED source says the reported relationship with a direct report and his dealings with Megaspeed, a Singapore AI company tied to export control questions, probably mattered more to the board than the espionage angle. Nvidia holds about 90% of the GPU market, so this ripples through everybody's capacity plans.

[**Inside GitHub's new Git storage architecture**](https://github.blog/engineering/architecture-optimization/inside-githubs-new-git-storage-architecture/) (16 minute read)

Last week OpenAI explained Pando. This week GitHub shows its own answer to agents hammering Git. One repo's daily requests went from about 44 million to 181 million between March and May, so they built a storage layer that keeps Git objects in Azure Blob Storage, treats replica disks as rebuildable cache, and puts references in Ref-CAS, a quorum-replicated compare-and-swap log. Their first two prototypes failed in instructive ways, and the post walks through both. Internal tests hit 5,000 concurrent agents and 7,200 pushes per second on a single repo. It's in limited private preview with a wider rollout early next year. Read it for the compaction and garbage collection details alone.

[**AWS gives developers a free local stand-in for its cloud, built from scratch by AI agents**](https://www.geekwire.com/2026/aws-gives-developers-a-free-local-stand-in-for-its-cloud-built-from-scratch-by-ai-agents/) (5 minute read)

AWS Emulator simulates more than 200 AWS services on your laptop and ships under CC0 with the full commit history on GitHub. AWS says its engineers didn't write or review any of the code. Agent teams on Bedrock AgentCore write fidelity tests against real AWS, file issues when the emulator fails them, and fix them one agent per issue. It doesn't do throttling, outages, regional differences, or sandboxing yet, and the known gaps live in a folder literally called "things-that-do-not-work." I appreciate the honesty. The timing is pointed too, since LocalStack's free tier now needs an account and is noncommercial only.

[**sshole**](https://sshhole.com/) (7 minute read)

If sshd was built against musl without PAM (think Alpine, OpenWrt, Buildroot, Yocto), any password longer than 256 characters logs you into accounts whose password field is `*`. musl's `crypt()` returned `*` on failure, its SHA-512 crypt fails past 256 bytes, and `*` matches the locked account. Ozgun Kultekin found it after about 17,600 login attempts across sshd builds, and the repo says it's been there since 2016. Upgrade OpenSSH, or set `PasswordAuthentication no`, which you should've done years ago anyway. There's a check script and PoC in [oz9un/sshole](https://github.com/oz9un/sshole) (MIT).

[**Discord is ditching Electron and its new app uses less RAM**](https://www.theverge.com/news/1027379/discord-ditching-electron-web-app) (3 minute read)

Discord is moving its whole client to Rust. CTO Stanislav Vishnevskiy says Electron and React Native both go away, and mobile keeps native UI while sharing app code with desktop through Rust. He posted a Windows build using 290 MB of RAM, compared to the 1 GB or more the current app can eat with just a few servers open. No ship date beyond "testing with users soon." My laptop fans are cautiously optimistic.

[**See what your Argo CD applications cost**](https://octopus.com/blog/argocd-cost-intelligence) (8 minute read)

Cost Intelligence for Argo CD is an Apache 2.0 extension that adds a cost tab to each application. It queries OpenCost after every sync, projects monthly spend, flags idle resources, pulls rightsizing hints from VPA or Goldilocks, and exports per-app cost metrics to Prometheus. The caveats are worth reading first: it only sees the cluster where both Argo CD and OpenCost run, it falls back to list prices without cloud billing data, and the default read-only role may see the platform cost page. It's a community project, not an Argo or CNCF one.

[**Hiring Junior Engineers**](https://eng.lyft.com/hiring-junior-engineers-1edc53e0fd5f) (3 minute read)

Ashley Lorden joined Lyft as a junior engineer in 2013 and now hires them. Her top criterion is mindset: curiosity and humility balanced with ownership and drive. She admits that's hard to show in an interview. Algorithms and data structures still matter even when agents write the syntax, because you have to know which tradeoff to ask for and catch the wrong one in review. The bar is recent experience shipping significant amounts of production-quality code, whether that came from school, side projects, or a non-engineering job. It's good to see somebody at a big company say out loud that they're still hiring juniors.

[**Adyen/kubectl-rexec**](https://github.com/Adyen/kubectl-rexec) - MIT - Tooling to make audited kubectl exec easy

{{< sponsor >}}
