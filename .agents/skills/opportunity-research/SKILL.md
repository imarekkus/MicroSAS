---
name: opportunity-research
description: Evidence-led MicroSAS opportunity discovery, competitor analysis, buyer-pain research and adversarial validation. Use to find, screen, rank or deepen SaaS/app opportunities before building. Not for coding or mass content generation.
---

# Opportunity Research — MicroSAS

## Mission
Find an economically viable, **narrow recurring problem** that a solo developer can solve and distribute without a pre-existing large audience. Target **$1k–$3k MRR** as an initial business goal, **not** a revenue forecast. Optimize for learning, credible buyer access and small reversible bets; **never optimize for number of ideas or apps built**.

## Read before starting
- `README.md`, `ROADMAP.md`, `docs/operating-principles.md`
- `research/README.md` for evidence tiers and repository conventions
- `templates/opportunity-scorecard.md`, `templates/customer-interview.md`
- Existing `research/*` before repeating searches; explicitly identify what's new.

## When to activate
Use for: opportunity discovery, market reconnaissance, competitor/pricing intelligence, niche screening, customer-problem investigation, critical/adversarial review, validation experiment design and Phase 1 research updates.

Do **not** use for: generating generic '100 SaaS ideas'; building an app, picking a stack, writing production code, marketing content at scale, or claiming product-market fit from search results. Build/Growth Factory automation happens after appropriate validation gates.

## Modes
Determine from the request:
- **SWEEP** (default when discovery is broad): explore independent narrow problems across multiple industries. Start with 8–12 distinct job-to-be-done hypotheses, filter to roughly 3–5 with evidence, and name why the rest were rejected. Breadth is for discovery, not fluff.
- **DEEP DIVE**: one exact buyer/workflow; reconstruct current process, quantitative pain, incumbent features/prices, segment-specific gap and cheapest disconfirming test.
- **ADVERSARIAL REVIEW**: actively attack a candidate thesis using contrary evidence, cheap alternatives, saturated competition, unworkable distribution, privacy/regulatory/API barriers and support costs.
- **VALIDATION DESIGN**: write non-leading interviews, outreach target definition, paid-offer experiment and hard pass/fail criteria. Never fabricate interviews, buyers, deposits, revenue or direct observations.

## Research sequence
1. **Narrow the buyer and occasion:** Write `For [specific buyer], when [recurring trigger], they currently [steps/workaround], causing [time/cost/risk]`. Reject feature-first descriptions.
2. **Search for independently originating buyer evidence** from complaints, support forums, reviews, community discussions, job postings, procurement requests and observable workflow examples. Find source dates and context. Prefer first-person accounts by likely buyers; avoid assuming every commenter is a paying customer. Search in multiple languages/geographies if relevant.
3. **Evidence audit:** Preserve exact URLs, observed dates, short paraphrases and tier per claim: **VERIFIED** (primary product docs/prices, regulations), **REPORTED** (firsthand unverified account, founder case study), **HYPOTHESIS** (our conjecture). Never present one person's post or crossposts as many independent pain signals. Identify vendor marketing, developer fishing for problems, sponsored/affiliate/promo content and fabricated-looking stories. Do not invent quotes, links, numbers or prices.
4. **Competing solutions:** Include purpose-built products, bundled existing tools, DIY scripts, spreadsheets, human assistants and doing nothing. Verify current pricing/features from primary pages when available; timestamp prices. Identify overlap: a feature already in incumbents **is not** a novel wedge. Look for underserved **buyer + moment + workflow** combinations, not generic 'AI for X'.
5. **Hormozi screen**: pain intensity, ability to pay, reachable/targetable buyers, market direction. Add recurring usage, time to first value, ease of MVP, differentiated promise, compliance burden and ongoing support. Treat scores as **relative judgment**, never objective scientific measurement.
6. **Offer-first framing**: State the desired outcome, evidence increasing confidence, speed to benefit, effort removed and how a narrowly scoped paid version might be priced. Price is a hypothesis until a buyer commits. Don't use deceptive scarcity, impossible guarantees or overclaim AI capability.
7. **Distribution test:** Specify where the *actual* buyer can be found; an honest plan to reach the first 10 people; likely response friction; and a cheapest channel test. Do not assume viral TikTok content, SEO rankings or ads will work. Neuma could coordinate tested content channels later.
8. **Adversarial pass**: Name at least **3 substantive reasons to reject** each serious idea, with evidence or an explicit missing-evidence flag. Ask whether the simplest incumbent or spreadsheet already solves it.
9. **Decision gate**: Suggest INVESTIGATE / VALIDATE / HOLD / REJECT, plus next single cheapest falsifiable experiment and explicit pass/fail threshold. **No build commitment from desk research alone.**

## Deliverables
Write substantive findings to `research/YYYY-MM-DD-<topic>.md`, using a descriptive stable slug; do not overwrite historical research without traceable revision. Link relevant earlier research and preserve source dates. For each candidate provide:
- **Buyer / job / trigger / frequency / current workaround**.
- **Signals:** claim-by-claim URL, date, source independence, VERIFIED/REPORTED/HYPOTHESIS; also conflicting evidence and unverified assumptions.
- **Incumbent table:** real products, actual relevant capabilities, current list prices or "not confirmed", switching friction, and commodity alternatives.
- **Hypothesized wedge:** why this buyer would switch or pay *in addition*, and what specifically cannot be inferred yet.
- **Offer hypothesis:** one-sentence outcome promise, smallest paid workflow, trial/pilot price assumption.
- **Distribution:** first 10 reachable prospects by segment and channel; concrete outreach/experiment and likely obstacles.
- **Economics:** simple MRR customer math, infra/API/support risk; no fake CAC/LTV or retention numbers.
- **Red team:** 3+ strongest counterarguments, risk of source contamination, legal/security/market constraints.
- **Decision:** evidence confidence, next falsifiable test, pass/fail threshold, unanswered questions.

For SWEEP also produce a **ranked matrix** with segment, recurrent pain evidence, paid incumbent, proposed wedge, reachability, major disconfirming evidence and decision. Explicitly distinguish **relative prioritization** from validated revenue potential.

Update `research/README.md` and `ROADMAP.md` only when the actual project status changes. Preserve old findings and refer to them. Do not silently rewrite past decisions.

## Interview discipline — The Mom Test
Ask about the **most recent real incident**: what happened, steps, frequency, consequences, alternatives, spend, failed fixes and authority to buy. Request examples with privacy-conscious redaction. Avoid hypothetical "would you pay for AI?" questions. An interview is **not** evidence until it actually occurs. Compliments, waitlists and signups are weak compared with spend, deposits, paid pilots and repeat behavior.

## Stop / escalate rules
- If up-to-date sources are unavailable, mark the research incomplete and don't fabricate an evidence-backed score.
- If a candidate depends on legal/regulatory, sensitive data, platform API or payments requirements, flag validation by the proper expert.
- Don't contact prospects, spend money, post publicly, modify production systems or collect sensitive personal data without specific authorization.
- No product commitment, implementation or marketing automation unless the user specifically requests it.
- If credible evidence is weak, **say so** and recommend further research or rejection instead of forcing a winner.

## Final chat report
Summarize what was investigated, source confidence, 2–3 strongest candidates (if supported), what could invalidate each, the exact file(s) saved and the next practical validation step. Be candid and concise. Always separate **verified facts** from **research hypotheses**.

## Sources of methodology
- `docs/operating-principles.md` — Hormozi / The Mom Test / Build-Growth Factory principles
- `research/README.md` — evidence standards
- `templates/opportunity-scorecard.md`, `templates/customer-interview.md`
