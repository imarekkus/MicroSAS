---
name: opportunity-research
description: Evidence-led MicroSAS SaaS opportunity discovery, competitor pricing, customer-pain research and adversarial validation before building. Use for researching, screening and ranking real niches.
---

# Opportunity Research — Claude Code entry point

The **canonical full workflow** is maintained at [`.agents/skills/opportunity-research/SKILL.md`](../../../.agents/skills/opportunity-research/SKILL.md). **Read that file completely and follow it for this task.** This entry point makes the same skill discoverable by Claude Code without creating two diverging copies.

## Essential rules (apply even if the canonical file cannot be loaded)
- Research **specific customer jobs and pain**, not generic AI-app ideas.
- Prefer independently reported pain, observable spending and primary-source competitor pricing; date and link every claim.
- Separate **VERIFIED / REPORTED / HYPOTHESIS**; avoid duplicates, promotional contamination and invented numbers.
- Look for contradictory evidence, reasonable free alternatives and at least 3 strong rejection arguments per serious opportunity.
- Evaluate **buyer pain, purchasing power, reachability, market direction, repeat frequency, build feasibility and support risk**.
- Use Hormozi's offer/outcome framing and The Mom Test's *past-behavior* interviews; no untested claims of buyer commitment.
- Output a ranked research assessment with first-ten-buyer acquisition hypothesis and the **cheapest falsifiable next validation experiment**.
- Keep findings under `research/YYYY-MM-DD-<topic>.md`, following `research/README.md`; never turn research into product implementation without explicit approval.
