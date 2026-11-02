# MicroSAS — Operating principles & reference library
_Last updated: 2026-11-02. Reference material; not a market-validation result._

## North star
Build a **solo-developer-friendly app or SaaS capable of $1,000–$3,000 in monthly recurring revenue** with a plausible path to more. The goal is a profitable **business**, not a high count of applications. This target is a milestone, not a forecast.

## A. Alex Hormozi — apply, don't imitate blindly

### 1. Choose a market before building
Use the four market-selection heuristics from *$100M Offers*:
- **Pain:** Is the problem serious, expensive or recurrent?
- **Purchasing power:** Can the buyer justify a subscription or recurring payment?
- **Targetability:** Can we identify/reach the first 10 specific buyers without a pre-existing audience?
- **Market direction:** Is the market healthy, growing, or in flux?

For SaaS, add: **frequency of use, fast time to first value, retention potential, founder support burden**.

### 2. Sell the outcome, not the technology
Hormozi's **Value Equation** (a conceptual positioning tool, not a measurable law):
> Perceived value ∝ (Dream outcome × Perceived likelihood of achievement) / (Time delay × Effort & sacrifice)

Translate each feature into a specific customer outcome:
- Not: "OCR, AI chat and analytics."
- Better: "Photograph an expense receipt and always know how much renovation budget remains."
- Proof and real demonstrations increase confidence; effortless setup and fast results decrease time/effort.

### 3. Design an offer, not just a feature list
For each prospect segment record:
- Exact buyer, moment of pain, current workaround and economic cost.
- One-sentence promised outcome, how quickly achieved, what proof supports it.
- Narrow paid pilot or trial offer, price hypothesis, risks and realistic limitations.
- An acquisition route to the first 10 paying customers.
- No manufactured urgency, exaggerated guarantees or inflated results.

### 4. Distribution is part of product design
Ideas from *$100M Leads*: warm/cold outreach, useful free content, paid promotion and partnerships.
- Prioritize channels **where the particular buyer is already reachable**.
- Neuma can coordinate content and outreach tooling, but no AI creates demand automatically.
- Favor qualified visits, conversions and retention over views or sheer posting volume.
- Don't launch on every platform by default.

### 5. Optimize the constraint
Identify the current bottleneck and fix that one:
- No interviews → research/reach buyers; no interest → positioning/market; traffic but no activation → onboarding/value; activation but no paid conversion → offer/pricing; payments but churn → product/retention.
- Resist the temptation to build another app to escape distribution or retention problems.

## B. The Mom Test — evidence from behavior, not compliments
Ask about past behavior: **last occurrence, steps taken, severity/frequency, tools used, actual spend, failed fixes, who owns budget**.
- Ask to see a redacted example whenever possible.
- Avoid "Would you use our AI app?" and "Would you pay $49?" before establishing context.
- Treat compliments, generic enthusiasm, hypothetical willingness to pay as **weak evidence**.
- Stronger: current payments to alternatives, repeated manual work, paid pilot/deposit/preorder, actual usage and retention.
- Existing paid competitors confirm a category exists, **not** that our proposed niche gap is real or that we can acquire customers.

## C. Two factories — after validation

### Build Factory (Claude Code/Codex)
Product brief → minimal UX/spec → engineering/test plan → implementation → automated tests, secrets/security checks → deploy → real-device testing → release → telemetry.
- Consider reusable release scripts for stores, localizations, screenshots, privacy declarations and payments.
- Human checkpoints: product decisions, security/privacy review, credentials, store approvals, release decision.
- Don't blindly adopt another author's SwiftUI + Compose + NestJS + AWS architecture. Web vs mobile and stack follow the validated workflow.
- Explore Expo/React Native for cross-platform mobile, Next.js for web, and simple managed backends where appropriate.
- Published in a store ≠ customers, revenue, reliability, or product-market fit.

### Growth Factory (Neuma as orchestrator)
Research positioning/hooks → draft content/scripts → generate **real product demonstration** assets → human approval → schedule/post through permitted integrations → attribute visits/signups/purchases → run the next experiment.
- TikTok, Instagram, Facebook and YouTube are **candidate channels**, not mandatory channels.
- Set up UTMs, source tracking, activation events, conversion and cohort retention.
- Respect API limits, publisher requirements, user trust and platform rules.
- AI-generated volume is not a substitute for credibility and specificity.

### Standard shared contract
Each opportunity/product should have a versioned brief:
`buyer_segment`, `recurring_job`, `last_observed_pain`, `existing_alternatives`, `evidence_links`, `offer`, `pricing_hypothesis`, `time_to_value`, `primary_channel`, `activation_event`, `conversion_event`, `retention_event`, `confidence`, `status`.
This contract feeds both factories, preventing marketing claims from drifting from real product capabilities.

## D. Decision process
1. **Discover** a broad pool of *specific jobs to be done*; collect opposing evidence too.
2. **Screen** pain, spend, reachable buyer, market, recurring usage, implementation feasibility, differentiation, distribution, economics.
3. **Validate** 2–3 shortlisted problems through non-leading interviews and credible buying signals.
4. **Build** only the smallest reliable paid workflow after evidence meets a gate.
5. **Distribute and measure**, iterate or pivot explicitly.

### Sample gates (starting assumptions, revise with evidence)
- Research shortlist: at least 2 independent customer pain signals, known paid alternative or observable spending, a plausible reachable buyer/channel, scoped MVP and identifiable disconfirming evidence.
- Pre-MVP: multiple real conversations with the precise segment plus meaningful commitment (ideally paid pilot/paid pre-order); do not treat sign-up intent as proof of willingness to pay.
- Post-launch: monitor acquisition costs, activation, paid conversion, retention, infrastructure+support costs and founder time.

## E. Revenue math, not forecasts
- $2,000 MRR at $10/mo requires **200** active paying customers before costs.
- $2,000 MRR at $49/mo requires **41** paying customers rounded up.
- $1,000–$3,000 MRR at $49/mo requires **21–62** paying customers.
Choose price only after understanding outcome value and buyers' budgets; consider annual vs monthly, churn, payment fees and tax.

## F. Learning queue (just-in-time)
**Read for the next decision, not for completionism.**
1. *The Mom Test* — interviewing prospects without leading them.
2. *$100M Offers* — market, outcome and offer design.
3. *$100M Leads* — matching real channels to reachable buyers.
4. Review a reusable `app-release` skill / Neuma integrations **only once** a validation-ready product requires them.

### Working rule
> Research first. Sell/validate the specific outcome second. Build third. Automate what repeats fourth.

## References / further reading
- Alex Hormozi, *$100M Offers*, *$100M Leads*; training: https://www.acquisition.com/training
- Rob Fitzpatrick, *The Mom Test*.
- Internal: [ROADMAP](../ROADMAP.md), [Research standards](../research/README.md), [Opportunity template](../templates/opportunity-scorecard.md), [Interview guide](../templates/customer-interview.md).

**Status:** These principles are working hypotheses and management heuristics. They do not substitute for external market evidence.
