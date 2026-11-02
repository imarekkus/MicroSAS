# MicroSAS opportunity discovery — initial evidence sweep
**Date:** 2026-11-02  
**Status:** Phase 1 started; initial desk research only. No interviews, payments, product tests, customer acquisition or technical feasibility experiments yet.  
**Scope:** Solo-developer SaaS/app with a realistic path to $1k–$3k MRR without an existing large audience or deep prior niche expertise.

## Method & evidence quality
We looked for an **exact recurring workflow** (not an AI feature), public firsthand pain reports, paid incumbents, a plausible small wedge, a first-customer route and contrary evidence.

- **Verified** = vendor's published product features/prices, official platform documentation (not validated subscription volumes).
- **Reported** = identifiable user/community statements, anonymous self-reports and customer anecdotes; not independently verified.
- **Hypothesis** = our untested gap, customer economics, willingness to pay, distribution and proposed MVP.
- Reddit communities contain developer market-research posts, competitors and possible promotional/AI-generated responses. **Never count several crossposts of the same account as independent signals**.
- Preliminary priority considers: pain, money already spent, reachable buyer, recurring need, differentiation, scope, distribution friction and regulatory/API risk. No numerical precision is warranted yet.

## Candidate 1 — Vendor-file exception monitor / pre-import QA
**Segment:** small distributors, multi-supplier retail operators and spreadsheet-dependent operations teams importing periodic third-party CSV/XLSX price, stock or sales feeds. Focus on **identifying bad changes before import**, not replacing the ecommerce store or ETL platform.

**Reported evidence**
- High-engagement dataengineering discussion: monthly datasets break on changed columns, spaces and formats; respondents describe recurring schema drift and strict validation vs tolerance tradeoff. [Reddit, Oct 2025](https://www.reddit.com/r/dataengineering/comments/1o4f1x3).
- Third-party CSV data whose columns evolve: [Reddit, Sep 2024](https://www.reddit.com/r/dataengineering/comments/1fojlau).
- Supplier spreadsheet discussion reports mixed currencies, inconsistent SKUs, empty values, unexpected formats; another respondent explicitly says Excel is sufficient for their workflow. These are **small-sample self-reports in a developer-started thread**, not a representative survey. [Reddit, Sep 2026](https://www.reddit.com/r/InventoryManagement/comments/1w8fzuh/how_do_you_handle_supplier_spreadsheets_when/).
- File-delivery patterns and failures are described in an [open-source reference](https://github.com/wdm0006/recurring-ml-data-pitfalls) (reference material, not buyer demand evidence).

**Verified competing products and contrary evidence**
- [Matrixify](https://matrixify.app/pricing/) already supports substantial Shopify data import/export with Basic $20 / 30 days, Big $50.
- [Flatfile](https://flatfile.com/pricing/) supports file collection, mapping, validation and transformations, quote-based for Projects.
- [OneSchema](https://www.oneschema.co/pricing) offers validation and embeddable importers, contact-sales plans.
- [Everstock](https://sync.usenormalize.com/) markets safe supplier feed sync with preview/hold/revert, including a free plan.
- **Warning:** Shopify-specific import QA is already occupied by serious vendors; generic column-mapping is not a credible wedge.

**Hypothesized gap:** *an independent safety gate for periodic third-party files that works before an existing downstream BI / ERP / finance workflow*, with configured data contracts, pre/post diff, column/type/row-count anomalies, threshold checks, explainable exceptions and optional Slack/email approvals; no database replacement or full data ingestion platform.

**First-10 route:** identify operations/data specialists at small agencies, distributors, logistics firms, marketplace operators; direct targeted outreach with a specific failure story and invite to compare an anonymized before/after file pair.
**Smallest MVP:** drag/drop two files, match key, check columns/uniqueness/nulls/type/thresholds, preview differences, rules save, CSV report + email alert; later scheduled files.
**Pricing hypothesis:** $39–$99/month per monitored recurring feed/customer account, **not validated**.
**Risks:** customers with technical teams build checks in Python; nontechnical buyers may have too small a budget; privacy/security and messy semantics; setup burden; niche access.
**Cheap disconfirming test:** 6–8 interviews split between technical ops and small distributors; obtain >=3 redacted real vendor file-change incidents and determine whether anyone currently pays or is willing to pay for monitoring rather than fixes. Reject a segment if manual work is rare or Excel/scripts are sufficient.

**Priority:** INVESTIGATE; strongest user-builder fit, but segment and unique advantage still unproven.

## Candidate 2 — Client missing-document workflow for tiny bookkeeping firms
**Segment:** 1–5 person bookkeepers/accountants serving repeat monthly clients, struggling to get the *correct, complete* bank statements / receipts without chasing.

**Reported evidence**
- Solo bookkeeper with 22 recurring clients claims ~6 hours chasing in a month; account of failed portals and ignored reminders. [Reddit, Mar 2026](https://www.reddit.com/r/Accounting/comments/1s715ta/how_do_you_get_clients_to_actually_send_you_what/) (same anecdote is cross-posted; count once).
- Tax practitioners discuss repetitive manual document follow-ups. [Reddit, Jun 2026](https://www.reddit.com/r/tax/comments/1tti1n8/how_do_you_handle_chasing_clients_for_documents/).
- More discussion identifies both manual folders and operational solutions. [Reddit, Aug 2026](https://www.reddit.com/r/Bookkeeping/comments/1vkc7a3/psa_keep_and_collect_all_client_documents_in_one/).

**Verified competition / negative evidence**
- [Content Snare](https://contentsnare.com/pricing/): $42/month monthly or $35/month paid annually; already offers no-login client upload, unlimited email reminders, review/approval and integrations.
- Multiple low-priced single-purpose services also exist; do **not** assume that 'no login' or 'automatic reminders' is new.
- Larger practice management suites and even organized Google Drive folders may be sufficient. Sensitive client records impose real security demands.

**Hypothesized gap:** integrate with where small firms **already receive documents** (not a new portal), show exact monthly missing-items status, detect wrong month/duplicate/illegible statements, draft (not autonomously send) compliant reminders.
**First-10 route:** reach independent bookkeepers through public directories/local bookkeeper communities, demonstrate workflow on synthetic files before requesting authorized redacted data.
**Smallest MVP:** month-by-client request checklist + secure no-login upload + basic file-type/date verification + approval before followup; note: the core is largely commoditized.
**Pricing hypothesis:** $29–$59/month/firma, unvalidated.
**Risks:** strong incumbent coverage, customer trust, privacy/security, regulated data, attachment handling, low willingness to switch; competitor marketing activity may exaggerate unmet demand.
**Disconfirming test:** 6 solo firms currently paying for a portal or using Drive; ask what's STILL broken and whether a one-workflow add-on merits extra spend. If current tools suffice, reject.
**Priority:** INVESTIGATE WITH SKEPTICISM; clear pain and paid category but very crowded.

## Candidate 3 — Small contractor scope-change authorization
**Segment:** independent renovation contractors handling extras requested mid-project, where texts and verbal approvals create unpaid extra work or disputed costs.

**Reported evidence**
- Contractors discussing change orders describe the need to capture written scope, price and explicit client authorization before extra work. [Reddit, Oct 2026](https://www.reddit.com/r/Contractor/comments/1x4ljxe/removed/) (original thread removed; only comment evidence: **weak confidence**).
- Change orders and client sign-off are recognized standard workflows; see category comparisons like [Jobber](https://www.getjobber.com/academy/contracting/best-software-for-general-contractors/).

**Verified competition / negative evidence**
- [Jobber](https://www.getjobber.com/academy/contracting/best-software-for-general-contractors/) and other service management suites offer quotations, change orders and client communication; basic plans quoted from $29/month on vendor guide.
- Text+photo+explicit reply may solve the problem at zero incremental software cost, and contractors may dislike entering another system.

**Hypothesized gap:** extremely lightweight mobile job-change link: photo + extra scope + fixed quote or T&M, client consent/time stamp, PDF attached to job, status and payment reconciliation. No full CRM/scheduling.
**First-10 route:** interview independent remodeling and flooring teams sourced from local public directories, then test one paid pilot on real jobs.
**Smallest MVP:** one change record, shareable approval page, timestamped audit log, PDF export, optional invoice link.
**Pricing hypothesis:** $19–$49/month, or per active job; not validated.
**Risks:** approval validity varies by jurisdiction/contracts; mobile-first support; low usage on quiet projects; difficult marketing to fragmented contractors.
**Disconfirming test:** 5 contractors who completed 5+ projects recently; count unbilled changes in last 3 months and ask to show anonymized examples; verify that capturing approval would have changed collection outcome.
**Priority:** EXPLORE; potentially sharp outcome, but weaker evidence and more domain learning required.

## Candidate 4 — Personalized-product proof/approval handoff
**Segment:** merchants selling custom prints/engraving/embroidery needing exact buyer approval of a version before production.

**Verified evidence & alternatives**
- [Etsy official custom-orders guide](https://www.etsy.com/uk/seller-handbook/article/top-tips-for-managing-custom-orders/22821490639) treats proof/revision expectations and buyer communication as operational needs.
- [ProofStage on Shopify](https://apps.shopify.com/proofstage) already offers proof links, no-login review, reminders, production stages and activity logs for Free, $14/month and $49/month tiers.
- [Etsy developer access docs](https://developers.etsy.com/documentation/) indicate app access levels: commercial apps for multiple sellers require review/approval. Platform dependency is material.

**Hypothesized gap:** only if interviews reveal specific missed re-approval for changed engravings, revision lineage or production export requirement **not already covered**.
**First-10 route:** direct outreach to personalized-product Shopify stores and printers with high custom-order volume.
**MVP / price hypothesis:** per-order image proof + status + version lock + export; $19–$49/month (unvalidated).
**Risks:** existing direct, cheap competitors; Etsy app access barrier; fragile integration and lots of niche workflow edge cases.
**Priority:** HOLD until proof of specific gap; generic proof-approval SaaS is not attractive.

## Candidate 5 — Short-form content client approval
**Segment:** small social media agencies that chase approvals across chats, drives and emails.

**Reported evidence:** agency marketers describe version confusion and client-chasing problems [Reddit, Apr 2026](https://www.reddit.com/r/socialmedia/comments/1ske446/as_a_social_media_marketer_what_are_your_biggest/).

**Verified competition:** [Planable](https://planable.io/pricing/) $33/workspace/month Basic, $49/workspace/month Pro as shown at research time; already supports required approvals, versions and substantial workflow. Its [documentation](https://help.planable.io/hc/en-us/articles/22581435847324-How-to-get-client-approval-for-content-in-Planable) notes clients must have Planable accounts to formally approve; view/comment links can be public.
**Hypothesis:** mobile no-login client approvals tied to short video frame-level comments, without requiring a full scheduling tool; may still have direct competitors.
**Acquisition:** outreach to micro-agencies with multiple clients; demo no-login approval.
**MVP / price hypothesis:** shareable review link with version history, approval lock, export; $19–$39/month (unvalidated).
**Risks:** strong incumbents, intense competition, feature overlap with Frame.io, ContentStudio and others.
**Priority:** HOLD pending stronger user-specific gap.

## Candidate 6 — Airbnb turnover/cleaner coordination
**Segment:** hosts with 1–5 listings coordinating cleaners.

**Reported evidence:** host still manually texts checkin/checkout and admits mistakes. [Reddit, Aug 2026](https://www.reddit.com/r/airbnb_hosts/comments/1vnqbo0/sharing_calender_with_cleaners/).
**Verified competition / counterevidence:** [Turno/Hospitable integration](https://help.hospitable.com/en/articles/7178662-connect-hospitable-with-turno-to-automate-your-cleaning-operations) waives Turno subscription for integrated Hospitable users (fees still apply). Airbnb calendar-only permissions/iCal can also solve the narrow problem for free; [Turnover Time](https://www.turnovertime.app/pricing) offers 1 property from $5/month after beta.
**Hypothesis:** a paid niche may exist for multi-platform emergency exceptions; no convincing wedge yet.
**Priority:** DEPRIORITIZE; low price ceiling/free alternatives and integration friction.

## Candidate 7 — Freelancer late-invoice follow-ups
**Segment:** agencies/freelancers with recurring outstanding invoices.

**Reported evidence:** recurring payment-chasing frustration in [Reddit, Jun 2026](https://www.reddit.com/r/freelancing/comments/1uf2emx/how_do_you_guys_handle_late_invoice_followups/), but other respondents say existing reminders suffice.
**Verified competition:** [Paidnice](https://www.paidnice.com/pricing) $69/month Essentials and [Chaser](https://www.chaserhq.com/chaser-pricing) from $259/month (USD Compact) with mature reminders/integrations.
**Hypothesis:** a cheap specialized non-Xero/QuickBooks product could appeal to a distinct invoice source, but built-in invoicing reminders already compete and low-frequency freelancers may not subscribe.
**Priority:** DEPRIORITIZE as generic app; only revisit with specific underserved channel/invoice system.

## Preliminary decisions (not a validated ranking)
1. **Investigate:** pre-import vendor-file exception monitoring for a precise B2B segment. Strongest fit to solo capabilities; must disprove 'Excel and scripts are enough' and Shopify market saturation.
2. **Investigate with skepticism:** bookkeeping monthly document collection. Repeated pain, proven paid tools; must uncover a *missing* workflow and justify paying alongside incumbents.
3. **Explore:** contractor scope-change authorization. Distinct pain-to-money outcome, but evidence weaker, sales/distribution may be harder.
4. **Hold:** personalized-product proofs and social approvals due established competition.
5. **Deprioritize:** Airbnb basic turnover reminders and generic freelancer invoice reminders.

**Important:** These are competing hypotheses for deeper research, **not** recommendations to build.

## Next research actions
1. Deepen the top 3 with **non-promotional first-person evidence** and competitor feature gap tables; try to find at least two independent pain accounts from actual buyers in each narrow segment.
2. Define *precisely* a buyer, trigger, current process and achievable first-10 channel for each.
3. Conduct 5–8 buyer interviews across two best segments as an initial discovery batch, then extend based on what remains uncertain.
4. Validate willingness to pay via an offered paid pilot at a specific price only after learning the current workflow.
5. Avoid coding, architecture selection and mass content production until the Phase 1 selection gate and stronger Phase 2 commitments.

## Open questions / missing evidence
- No directly interviewed customers; all buyer economics and willingness to pay are untested.
- No verified growth rates or market sizing; do not infer them.
- No observed willingness to switch, acquisition costs, churn or margins.
- No technical integration proof or privacy compliance assessment.
- High potential **promotional contamination** in current 2026 search results: investigate authorship and claims before treating testimonials as independent.
