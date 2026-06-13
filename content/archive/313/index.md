---
author: Chris Short
date: '2026-06-14'
description: ""
draft: false
slug: '313'
title: "DevOps'ish 313: "
---

The Claude Fable launch turned into a complete debacle this week and is a cautionary tale of the times we're in. It's also one of the most botched product releases we've witnessed in quite some time. On Tuesday, June 9th, [Claude Fable 5 and Mythos 5 were released](https://www.wired.com/story/anthropic-releases-claude-fable-5-mythos-5/) to every paying customer for a limited time, before it was slated to move to API billing on June 22nd. Anthropic implemented several safeguards (classifiers) to route sensitive topics such as cybersecurity, chemistry, and biology queries to older models. There were additional checks in place that hindered AI researchers and safety folks from doing their work by invisibly doing the same thing. [Anthropic walked back the invisible safety checks](https://www.wired.com/story/anthropic-responds-to-backlash-on-claudes-secret-sabotage-on-ai-research/), saying, "We made the wrong trade-off and we apologize for not getting the balance right." On Thursday, [Microsoft restricted employees](https://www.theverge.com/report/947575/microsoft-claude-fable-5-restricted-internally) from using the latest Claude models due to a 30-day retention policy that Anthropic implemented as yet another safety feature. I have no doubt numerous other organizations would do the same.

Then on Friday, [the US government decided to weigh in](https://www.anthropic.com/news/fable-mythos-access). According to Anthropic, citing national security concerns, the US government placed export controls on Fable 5 and Mythos 5. The US government was very specific in stating that Anthropic needed to restrict access not only to foreign nations but also to foreign nationals inside the US, including Anthropic's own employees. "The net effect of this order is that we must abruptly disable Fable 5 and Mythos 5 for **all** our customers to ensure compliance," Anthropic said (emphasis theirs). This is quite the release gone wrong. This week's activities really highlight the need for regulatory processes and more coordination between the frontier labs and the US government. But this whole ordeal plays into Anthropic's fear-based marketing strategy, which is unfortunate because fear-mongering is the last thing the world needs from a product like Claude. What an absolute mess.

[Your CI got slower this month. Nobody fixed it.](https://www.mendral.com/?utm_source=devopsish)  
One dep, one job, one cache miss at a time. Pipelines bloat. Nobody owns fixing it because nobody has the time. Mendral profiles your CI, finds the slow steps, and opens PRs that cut real minutes. Better caching, parallel jobs, killing redundant installs and reduces your CI costs. The work a senior engineer would do, if they had a spare week. *SPONSORED*



{{< subscribe >}}
