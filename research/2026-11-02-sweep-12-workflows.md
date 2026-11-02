# MicroSAS — SWEEP #1: 12 recurring workflows, adversarial market screen

**Research date:** 2026-11-02  
**Scope:** Solo developer; $1k–$3k MRR target; no existing large audience; no assumption that app building or AI marketing is the bottleneck.  
**Mode:** `opportunity-research` — SWEEP with adversarial pass, executed in ChatGPT and saved to repository.  
**Research status:** Preliminary public-source market research ONLY. No direct buyer interviews, outreach, pilots, payments, retention, validated willingness to pay, demonstrated acquisition or feasibility tests.

This report expands (and **does not replace**) [initial sweep](2026-11-02-initial-opportunity-sweep.md). It separates two different third-party-file use cases and adds order-packing proof, COI management, employee credentials, agency onboarding and shop-floor inspection reporting. It corrects an overly generic assumption: **paid competitors, especially ones already handling the exact proposed workflow, are negative as well as positive evidence**.

## Executive conclusion

**No confirmed opportunity to build yet.** The useful outcome is 4 investigation theses, 5 holds, 2 low priorities and 1 rejection of its *basic* use case. Prioritization favors: (a) concrete observable work and expense, (b) direct access to users, (c) a narrowly distinct job, and (d) defensible feasibility as a solo builder. The leading area is operational spreadsheet ingestion/report reconciliation, **not generic "AI data quality"**. The next action is narrow buyer interviews on real recurring files and alternative-tool coverage.

### Evidence legend
- **VERIFIED**: current provider product features/prices on their own published page, or documented official platform rules. This **does not** verify subscribers, demand or profits.
- **REPORTED**: attributed, but unverified, first-person buyer/community account. One repeated account/cross-post = one signal. Reddit accounts are not authenticated business owners.
- **HYPOTHESIS**: presumed market gap, buyer budget, reachable audience, acquisition, product scope, revenue, pricing and benefits not yet supported by direct buyer evidence.
- **Confidence** refers to the *specific buyer pain / proposed gap* separately. E.g. **M/L** = reasonable public pain signal, low confidence in a commercially viable product gap.
- Date-sensitive vendor prices are public list prices checked on 2026-11-02; taxes, billing cycle, promotions and tiers vary.

**Source contamination control:** several 2026 posts are overt developer market research, near-duplicate crossposts, and vendor replies. They receive less weight than detailed unsolicited descriptions of real workflows and costs. Strong examples: nearly identical vendor-insurance prompts appeared on multiple subs; the bookkeeping '22 clients, six hours' story was posted to both Accounting and Bookkeeping on the same date; agency onboarding threads are filled with tool vendors. None is treated as many independent buyer confirmations.

## Ranked screening matrix (12 job-to-be-done hypotheses)

| # | Narrow buyer + recurring job | Public pain signal | Incumbent / competing baseline | Specific gap to TEST (not proven) | First-10 route | Major rejection evidence | Decision; pain/gap confidence |
|---|---|---|---|---|---|---|---|
| 1 | Small wholesale/lifestyle brand ops: merge partner sell-through files weekly | Direct Sep 2026 Excel request for weekly+monthly partner sales from inconsistent formats | Sheetgo $50/mo monthly ($35 billed annually); Coupler.io $32/mo Starter monthly; Excel Power Query | Fast per-partner field mapping, SKU normalization, discrepancy alerts + ready-made wholesale weekly report | Target small apparel/lifestyle wholesalers with 5+ retail partners | Only one directly matching firsthand case found; Excel/Power Query or consultants solve it | **INVESTIGATE**, M/L |
| 2 | Multi-supplier SME catalog manager: ingest updated vendor price/stock sheets | Two different specific workflows: 2024 vendor CSV conversion, 2025 40 supplier price lists | Shopify Simple CSV $19/$49; Matrixify $20/$50; OneSchema FileFeeds; scripts | Explainable **pre-import change gate** and human approval across mixed supplier files, separate from ERP/Shopify | Target multi-supplier distributors/ecommerce import managers; use redacted before/after examples | Small Shopify apps already support many mappings; OneSchema tackles recurring transforms; spreadsheet scripts free | **INVESTIGATE**, M/L |
| 3 | 1–5 person bookkeeper: determine which monthly statements are missing and whom to chase | Separate 22-client story and 24-client firm report; dated 2026 | Content Snare $42 monthly; TaxDome $800/year/seat solo; Google Drive | In-place missing-items status from email + current workflows, with verified month/account match | Independent bookkeeping firm directories / targeted email interview requests | Portal and reminders already solved; client nonresponse is a behavioral, not software-only problem | **INVESTIGATE SKEPTICALLY**, M/L |
| 4 | Independent remodeler: document and price extra scope BEFORE doing work | First-person remodel change-order disputes, lost margin and signed-order discussions | Joist Elite $32/mo monthly; Foreman/Jobber; signed text + PDF | Two-tap link with photo, price, approval, tracked scope delta (no CRM) | Target small crews from public contractor directories/trade forums | Joist already offers signed estimates and change orders cheaply; contract/legal variability | **EXPLORE**, M/L |
| 5 | Shopify shop packing high-value orders: prevent "missing item/empty box" claims | 2024 $5.2k dispute, 2026 operator accounts of disputes and packing evidence | Boxwitness free tier, Mify free, other packing proof apps; Shopify built-in chargeback response | Order-scanned proof capture, not generic AI appeal writer | Reach premium custom product packers via Shopify communities/direct | EXACT functionality already sold/free; banks may reject claims despite evidence; video not directly accepted as Shopify evidence upload | **HOLD**, M/L |
| 6 | Small ad agencies: get correct Meta/Google/TikTok account permission after signing | Agency owner reply on missing access/assets; some posts are product research | Leadsie $59/mo monthly with one-link access across major platforms | Only a platform/permission-specific exception handling workflow not already handled by Leadsie | Target specialized micro agencies | Leadsie directly handles access plus troubleshooting, permissions, team links; API complexity | **HOLD**, M/L |
| 7 | Property manager / GC: ensure vendor COIs current | Several COI posts; a few concrete operator replies but high promotional contamination | **Thimble Certificate Manager free** with OCR+reminders; HoundDog quote-based | Complex coverage/endorsement verification in underserved region/segment, NOT expiration reminders | Industry associations / contractor directories | Free baseline captures core proposal; commercial insurance domain expertise required | **LOW PRIORITY**, M/L |
| 8 | HR admin small firm: renew employees' qualifications/licenses | Healthcare & HR reports of spreadsheets; other users built reminders themselves | BambooHR/ADP/SharePoint/Sheets plus Apps Script | Only a tightly regulated occupation-specific renewal workflow | Reach specialized workforce coordinators | Cheap native tools, regional legal/regulatory complexity, sensitive IDs | **LOW PRIORITY**, M/L |
| 9 | Small machine shop: number drawing inspection points and produce reports | Machinists question (Oct 2025) specifically asks for DWG/PDF to inspection spreadsheet | Ideagen Quality Control (InspectionXpert); SolidWorks Inspection | Old drawing formats + small repair-shop repair-specific records | Machine shops/repair shops | CAD drawing understanding, strong established products, specialist sales and domain knowledge | **HOLD**, M/L |
| 10 | Custom print/engraving ecommerce: versioned proof approvals | Seller guidance and product category exists; less direct buyer pain verified in this sweep | ProofStage **free** and $14/$49 per month, with no-login links & reminders | Only distinct version lineage/integration workflow | Personalized product Shopify store contacts | Product already covers precise core workflow cheaply | **LOW PRIORITY**, L/L |
| 11 | Micro social agency: get client sign-off on short videos | Complaints but mostly exploratory research posts | Planable $33/$49 per workspace, with approvals | Specialized video frame-level review AND no account if still unmet | Agency owner outreach | Planable, Frame.io etc. already cover approvals; marginal buyer willingness uncertain | **LOW PRIORITY**, L/L |
| 12 | Airbnb host with 1–5 units: send turnover dates to cleaner without revenue visibility | 2026 host requests; reply explains native calendar-only co-host access | Airbnb built-in calendar-only cohost role; iCal, Turno | Only complex multi-platform exception coordination (different business) | Host groups | Basic pain directly solved for free with native permissions | **REJECT basic use case**, M/Very Low |

Scores are *not* statistical estimates, market share, or revenue projections. Several areas have little evidence on market direction; no growth criterion was scored as known.

---

## Detailed hypothesis A — Partner sell-through report consolidation

**Buyer + trigger:** Sales operations employee at a small wholesale brand (apparel, travel, accessories) receives weekly retail sell-through XLSX/CSV reports from several retailers, needs unified units/revenue by SKU/retailer and weekly, monthly and yearly views. **Current**: manually reconcile templates in Excel and paste to a report; each partner's file differs.

**Evidence:**
- REPORTED (2026-09-20): lifestyle travel brand sales worker explicitly wants weekly retail sales reports consolidated despite retailer-vendor templates differing, retaining units/style number/sales volume. [r/excel firsthand question](https://www.reddit.com/r/excel/comments/1wlutuj/how_would_i_compile_multiple_sales_report_data/).
- REPORTED adjacent workflow, different buyer (2024-08-15): weekly/monthly vendor CSVs have variable columns and formats; scripts became hard to maintain. [r/software](https://www.reddit.com/r/software/comments/1esyn38). **Do not count as independent confirmation of THIS retail sell-through segment**.
- VERIFIED competitors: [Sheetgo Automations](https://www.sheetgo.com/pricing/automations/) $50/month monthly or $35 monthly equivalent annually, and [Sheetgo docs](https://support.sheetgo.com/en/articles/9406485-accessing-sheetgo) explicitly support merge/schedule spreadsheets. [Coupler.io](https://www.coupler.io/pricing) Starter $32/mo monthly (or $24/mo annually), with spreadsheet destinations and transformations; caveat: connector-focused, not automatically suitable for every emailed, partner-specific sheet. Manual Power Query/Excel already strong.

**Offer hypothesis:** "Turn incompatible retailer sell-through reports into a consistent weekly brand sales report, flagging unexpected SKU or field changes **before** the numbers are published."

**Possible smallest paid workflow:** Upload 2+ partner files; user verifies mappings/units/SKU; harmonize currencies and periods; compare against previous week; export a simple spreadsheet with exceptions; save mapping for next week. Do not start with auto-email/OCR/enterprise integrations. Price conjecture $39–$79/month for active users, **unvalidated**.

**Reach first 10:** Select one vertical (e.g., lifestyle apparel wholesalers), find sales ops/import coordinators at 30 brands through brand/team pages or LinkedIn, contact them with a specific research question about the *last report compilation*. Do not seek sensitive raw files initially; synthetic or carefully redacted examples are enough.

**Three strongest rejection arguments:**
1. Only one strong narrowly matching first-person case; problem prevalence unknown.
2. Excel Power Query, Sheetgo and Coupler already may do the entire job cheaply; our extra SaaS may add onboarding rather than save time.
3. Hardest part may be inconsistent SKU semantics requiring ongoing human review, making service/support costs eat low MRR.
Additional: target buyers might lack purchase authority; weekly work may be handled centrally by retailer rather than brand.

**Cheapest falsifiable test:** Interview 6 real people who personally merge 3+ retail-partner weekly reports. Ask for time spent over latest 4 reporting cycles, what broke, whether scripts exist, how they would resolve the same case in Excel, and who pays. **Provisional pass**: >=3 independently demonstrate a recent >60-minute recurring preparation burden, >=2 currently spend money or offer a concrete paid pilot at a stated price, >=1 provides a safe redacted example. **Fail**: no segment-specific proof or Power Query solves all 6 without painful setup. Threshold chosen for speed, not scientific significance.

**Decision:** INVESTIGATE; pain confidence **medium-low**, distinctive wedge confidence **low**, acquisition untested.

## Detailed hypothesis B — Supplier price-file validation before import

**Buyer + trigger:** Small multi-supplier distributor/ecommerce operator receiving price, stock and SKU sheets monthly or weekly; repeated schema/format changes silently corrupt imports or need rewriting scripts.

**Evidence:**
- REPORTED (2024-08-15): supplier price CSVs arrive in inconsistent column formats, need recurring normalization, many copies of scripts [r/software](https://www.reddit.com/r/software/comments/1esyn38).
- REPORTED (2025-01-22): ecommerce site with about 40 vendors converts quarterly XLS/PDF price lists to CSV, with manual repetitive column alignment [r/spreadsheets](https://www.reddit.com/r/spreadsheets/comments/1i7jypz).
- REPORTED (2026-07-22): vendor IDs inconsistent across systems, Excel LET and Power Query attempts problematic for dynamic refresh [r/excel](https://www.reddit.com/r/excel/comments/1v3kinm/excel_text_data_cleaning). Different related ETL use case, not the same buyer.
- VERIFIED paid alternatives: [Simple CSV](https://simplecsv.com/pricing) $19/month Pro and $49 Scale with advanced inventory/pricing rules, mapping and scheduled Shopify imports; [Matrixify](https://matrixify.app/pricing/) $20/30 days Basic and $50 Big; [OneSchema](https://www.oneschema.co/pricing) FileFeeds for recurring CSV/Excel/PDF transformation (Importer plans by sales contact); [Flatfile](https://flatfile.com/pricing/) mapping/validation/approval (contact sales). Strong direct competitive overlap.

**Offer hypothesis:** "Protect your current catalog/import workflow against silent supplier format and price changes. Approve only verified changes, with a clear supplier-by-supplier diff." Narrow to **safety gate for existing workflows**, not replacement ETL.

**Small MVP:** Upload previous/current file, configurable matching SKU, schema/type/duplicate/missing-value/price delta rule checks, explicit hold/approve and CSV export. Pricing *hypothesis*: $49–$99/month account, not validated. Complexity: product catalog semantics, privacy, errors potentially causing business loss, customer-specific mappings.

**Reach first 10:** Identify small distributors who advertise 10+ suppliers or product catalogs, especially operators currently using spreadsheet imports; invite short incident reconstruction and assess actual file-volume/criticality before discussing automation.

**Rejection arguments:**
1. Existing supplier feed import tools already do transformations, scheduling and rules; OneSchema handles recurring files; our gate might be a feature, not a standalone company.
2. Buyer can commission a one-time $200–$500 Python/Power Query script and keep it; low willingness to add recurring fees.
3. Low error tolerance and many exception cases increase support/liability burdens for solo developer.
4. One prospect with 40 vendors doesn't imply widespread recurring spend.

**Cheapest falsifiable test:** Six supplier-data operators in one business vertical; reconstruct 3 separate incidents from last 90 days, estimate hours and measurable cost; demonstrate whether existing import app catches them; propose narrow paid pre-import audit at a real price. **Provisional pass** >=3 nontrivial incidents across >=3 organizations, >=2 budgets/paid commitment, a competitor functionality gap supported by examples. Reject generic "CSV importer" positioning now.

**Decision:** INVESTIGATE, pain **medium**, wedge **low**.

## Detailed hypothesis C — Monthly client document completeness for bookkeepers

**Buyer + trigger:** One-to-five-person bookkeeping firm, 15–60 recurring small business clients, bank and card statements, payroll and receipts arriving by different channels; month-end reporting blocked by missing items.

**Evidence:**
- REPORTED (2026-03-29): solo bookkeeper with 22 recurring clients describes approximately **six hours in a month** of following up; a [r/Accounting](https://www.reddit.com/r/Accounting/comments/1s715ta/how_do_you_get_clients_to_actually_send_you_what/) and [r/Bookkeeping](https://www.reddit.com/r/Bookkeeping/comments/1s718q4/how_do_you_get_clients_to_actually_send_you_what/) copy appears on same date. **One story, not two**.
- REPORTED (2026-08-07): different small firm handling ~24 clients struggles with monthly documents lost in email and varying due dates; asks for dashboard and task integration [r/Bookkeeping](https://www.reddit.com/r/Bookkeeping/comments/1vi9jzd/solutions_for_monthly_client_document_and_task/).
- REPORTED counterevidence (2026-08-10): community recommendation to use structured shared Google Drive folders and QuickBooks missing-attachment reports instead of new software [r/Bookkeeping](https://www.reddit.com/r/Bookkeeping/comments/1vkc7a3/psa_keep_and_collect_all_client_documents_in_one/).
- VERIFIED competitors: [Content Snare](https://contentsnare.com/pricing/) $42/month paid monthly or $35 monthly equivalent annually; unlimited reminders, uploads, approval and basic integrations. [TaxDome](https://taxdome.com/pricing) Essentials $800/year/seat (1-year annual payment, solo only), with structured document requests, portal, automations and email/SMS. That severely restricts a generic reminder product.

**Offer hypothesis:** "See the exact missing monthly statement by account, without making clients learn another portal; notify only when still missing or the file is the wrong period." Avoid direct access to bank account credentials.

**Small MVP:** List per-client expected monthly statements and detected received state, manually mark files, draft one personalized reminder for approval, validate dates/account numbers only on redacted/demo data. Pricing hypothesis $39–$59/month/firm, **unvalidated**.

**Distribution:** Public bookkeeping directories/owner profiles and practitioner groups; ask 8 firms with 15–60 monthly clients about the **most recent month-end exception**, existing tool spend and prior failed fixes. Offer migration-free demo with dummy files.

**Rejection arguments:**
1. This may fundamentally be *client non-compliance*, which no app cures; more reminders may be counterproductive.
2. Content Snare and TaxDome have overlapping features at available prices; selling a second subscription adds friction.
3. Extremely sensitive records and security/contractual obligations impose disproportionate support, auditing and liability.
4. Customer acquisition and feature expectations may require domain expertise beyond a solo builder.

**Cheapest test:** Six to eight interviews split between users of Content Snare/TaxDome and Drive/Asana. Have buyers show how they currently know whether a particular statement is missing; require >=3 distinct recent false-positive/wrong-month incidents that competitor can't already flag. **Provisional pass**: >=2 firms explicitly request a priced pilot after competitor demo or show current paid spend for exactly this unmet add-on. **Fail** if buyer needs clients to simply respond or existing portal covers it.

**Decision:** INVESTIGATE WITH SKEPTICISM; pain **medium**, wedge **low**.

## Detailed hypothesis D — Renovation contractor extra-work authorization

**Buyer + trigger:** Independent 1–5 person remodeler finishing 2–8 jobs per quarter, homeowners ask verbally for extra lights, outlets, tiling, and payments become disputed.

**Evidence:**
- REPORTED (2026-07-09): kitchen remodeler reports client tension after extras were not understood as billable [r/Contractor](https://www.reddit.com/r/Contractor/comments/1urib8q/how_do_you_set_expectations_around_change_orders/).
- REPORTED (2026-01-25): small remodeler described ~$1,100 profit on roughly $15,000 job, with scope and change-order mistakes, and negotiated after work [r/Contractor](https://www.reddit.com/r/Contractor/comments/1qm5wx3/paymentchange_order_advice/).
- REPORTED (2026-09-26): other contractors describe written, signed approvals of all changes [r/Contractor](https://www.reddit.com/r/Contractor/comments/1wqmkfn/when_does_a_minor_change_become_a_change_order/).
- VERIFIED incumbents: [Joist pricing](https://www.joist.com/pricing/) **Elite $32/month billed monthly** contains change orders; Pro $17/month monthly does not. [Joist estimates](https://www.joist.com/features/estimates/) includes digital estimates/approval and change orders. [Foreman change orders](https://foreman.co/features/change-orders) includes online acceptance/signing and budget changes. Handwritten scope change signed and photographed is also a real free alternative.

**Offer hypothesis:** "Photograph an extra request, quote the cost, and receive homeowner agreement before additional work starts — without installing a project management suite."

**MVP:** Link-based change with scope+photo+price+date, consent flow, PDF/shareable log and explicit outstanding amount; NO promises of legally enforceable signatures without jurisdiction-specific counsel. Price hypothesis $19–$39/month or per project, unvalidated.

**First 10:** Local trades (renovation, tiling, cabinetry) from business directories; segment by job-size and average changes; phone interviews with concrete recent invoices. Location-specific pilot before internationalizing.

**Rejection arguments:**
1. Joist at $32/month contains the exact function plus estimates/invoices; a standalone product may be inferior.
2. Change-management discipline depends on contractor behavior and contract terms, not simply app UI.
3. Monthly value may be low/seasonal for micro contractors; onboarding and customer support on phones expensive.
4. Legal/invoicing/e-signature expectations vary by region.

**Cheapest test:** Five contractors with multiple recent renovation jobs: count extra work, approval medium, amounts actually written off in last 3 months; ask them to try Joist demo or share their existing paper process before suggesting a new app. **Provisional pass**: >=3 report a recent unpaid/unbilled change linked to failure to approve, >=2 offer a paid test for faster workflow **after** comparing existing tools. **Fail** if problem is solved with one contract clause and a WhatsApp photo.

**Decision:** EXPLORE; pain **medium**, wedge **low**.

---

## Candidate E — Shopify packing proof, order-linked videos

**REPORTED independent buyer observations:** [2024 large-item seller with $5,200 dispute](https://www.reddit.com/r/smallbusiness/comments/1g0rxx0); [2026 Shopify order-missing/empty-box dispute](https://www.reddit.com/r/shopify/comments/1v7urfx/how_on_earth_are_you_guys_winning_empty_box/); [2026 merchant weighing packed items](https://www.reddit.com/r/shopify/comments/1v24k17/how_do_you_deal_with_liars/). Serious monetary pain (but chargeback evidence effectiveness differs).
**VERIFIED rivals:** [Boxwitness Shopify listing](https://apps.shopify.com/boxwitness) is an exact competitor with barcode+video+PDF and free tier; [Mify Packing Video](https://www.mifycom.app/apps/pack-record) offers free video recording and order links. [Shopify official chargeback process](https://help.shopify.com/en/manual/payments/chargebacks/chargebacks-in-admin) already generates AI response and automatically includes available order evidence; accepted file types are PDF/JPEG/PNG, **not raw video**, which undermines simplistic 'bank accepts video proof' claims.
**Hypothesized gap:** order-level proof verification for a narrow non-Shopify platform. **Counterarguments:** competitor free, hardware/operational friction, evidence cannot guarantee recovery, high storage costs. **Next test:** interview 5 merchants who already record packaging, measure dispute win-rate impact and unmet workflow across non-Shopify platforms. **Decision:** HOLD, pain M/gap L; no generic product.

## Candidate F — Agency asset/access handoff

**REPORTED:** [agency-owner response describing delayed brand assets and permissions](https://www.reddit.com/r/marketingagency/comments/1qv5wdr/agency_owners_quick_question_about_client/) but the thread's OP was explicitly conducting market research; [agency account-access discussion](https://www.reddit.com/r/SocialMediaMarketing/comments/1vaj6ys/agencies_whats_your_current_process_for_getting/) also looks like competitor/customer-discovery content.
**VERIFIED rival:** [Leadsie](https://www.leadsie.com/pricing) Starter **$59/month monthly** (or $49/month equivalent annually), covers Meta, Google, TikTok, LinkedIn and more, custom one-link access, account status, permission troubleshooting; [Leadsie docs](https://help.leadsie.com/article/20-what-can-i-get-access-to-with-leadsie) detail platform coverage.
**Wedge hypothesis:** specialized unresolved permission cases for agency types; **counterarguments:** direct strong incumbent, APIs/accounts/permissions constantly change, support-intensive edge cases, agency market noisy/promotional. **Next test:** 5 agencies already paying for Leadsie with a documented repeat exception the tool fails to fix. **Decision:** HOLD.

## Candidate G — Vendor/subcontractor insurance certificate (COI) renewals

**REPORTED:** [200-unit operator seeking COI solution](https://www.reddit.com/r/PropertyManagement/comments/1u63uhp/coi_tracking_for_tenants_whats_the_best_way_to_do/), [operator almost allowed expired-COI contractor onsite](https://www.reddit.com/r/PropertyManagement/comments/1t00808/new_to_all_of_this_and_almost_had_an_uninsured/); but a proliferation of near-identical developer-market-research prompts with vendor replies, e.g. [2026 thread](https://www.reddit.com/r/Insurance_Companies/comments/1vaa2rv/how_is_everyone_actually_tracking/), makes broader signal low-confidence.
**VERIFIED:** [Thimble Certificate Manager](https://www.thimble.com/certificate-manager) is **free** and includes automated contractor reminders, COI reader and dashboards. [HoundDog](https://www.hounddog.com/pricing) offers verified tracking with quote-based pricing.
**Narrow wedge only:** rare endorsement/coverage-by-job controls missing from current tools; requires insurance expertise. **Reject generic expiry tracker** because free complete alternative. **Decision:** LOW PRIORITY.

## Candidate H — Employee qualifications expiration

**REPORTED:** [2026 HR/healthcare thread](https://www.reddit.com/r/humanresources/comments/1rnwfcm/how_do_you_track_employee_license_and/) includes employer using spreadsheets, replies using BambooHR, ADP/Nursys, SharePoint and Google Apps Script. [2020 growing small company with 10–15 training credentials per worker](https://www.reddit.com/r/humanresources/comments/f1zq2b).
**Alternative verified by accounts:** existing HRIS / reminders / spreadsheets, no urgent standalone buyer-spend signal collected.
**Hypothesis:** occupation-specific regulator-ready renewal procedure. **Risks:** free automation, privacy/security, region-specific regulations, buyer accessibility. **Decision:** LOW PRIORITY.

## Candidate I — Old mechanical drawings to inspection records

**REPORTED:** [2025 repair machinist request](https://www.reddit.com/r/Machinists/comments/1o1au92) to upload vintage DWG/PDF and label inspection points with spreadsheet report.
**VERIFIED:** [Ideagen Quality Control (formerly InspectionXpert)](https://www.inspectionxpert.com/) already auto-balloons CAD/PDF and generates inspection reports including AS9102/PPAP (pricing not publicly confirmed here).
**Hypothesis:** very old repair-drawing / ad hoc non-regulated shop-specific workflow. **Risks:** technical and legal/compliance domain expertise, accuracy, direct incumbent; willingness to pay unknown. **Decision:** HOLD.

## Candidate J — Personalized product proof approvals

**VERIFIED:** [ProofStage Shopify listing](https://apps.shopify.com/proofstage) already provides **free up to 15 proof orders/month**, **$14/month Starter**, **$49/month Pro**; no-login approval, activity log, automated reminders, production status; 3 reviews at research time do not verify product-market fit.
**Hypothesis:** narrow integration/version exception only. **Risks:** no defensible feature gap in basic approvals, low price ceiling, store platform lock-in. **Decision:** LOW PRIORITY.

## Candidate K — Micro-agency social content approvals

**VERIFIED:** [Planable pricing](https://planable.io/pricing/) Basic **$33/workspace/month** and Pro **$49/workspace/month** on displayed rate; [Planable client approval help (updated 2026-10-30)](https://help.planable.io/hc/en-us/articles/22581435847324-How-to-get-client-approval-for-content-in-Planable) formal approval + client account membership. Other creative review tools exist.
**Hypothesis:** ultra-light guest approval for short clips without a formal account. **Risks:** crowded, easy to imitate, already possible with shared links outside formal approval; no independent willingness to pay. **Decision:** LOW PRIORITY.

## Candidate L — Basic Airbnb cleaning calendar sharing

**REPORTED:** [host manually texts check-in/out dates](https://www.reddit.com/r/airbnb_hosts/comments/1vnqbo0/sharing_calender_with_cleaners/); comments point to native Airbnb **calendar-only co-host permission**. Another [host receives same answer](https://www.reddit.com/r/airbnb_hosts/comments/1uvki8g/sharing_the_calendar_with_a_cleaner/).
**Hypothesis:** multi-platform emergency exceptions, a **different job** from basic calendar sharing. **Counterevidence:** exact basic task is free in Airbnb. **Decision:** REJECT basic use case; do not disguise a free permission setting as SaaS.

---

## Comparison / Hormozi and The Mom Test application

The Value Equation is a **positioning heuristic**. No candidate gets a free pass simply because a compelling before/after claim can be written. In order:
1. **Pain:** require a buyer to describe last case and quantify time, costs or loss. A compelling Reddit post is a lead for further interviews, not quantified demand.
2. **Purchasing power:** published incumbent price shows product availability, NOT that our narrow buyer is already paying. Ask which existing subscription/process they pay for and who owns the purchase.
3. **Targetability:** pick specific roles and an accessible channel for first 10, not all of TikTok/Reddit.
4. **Market direction:** **unknown for all twelve**; no market CAGR or market-size estimates asserted.
5. SaaS additions: recurring trigger, time to first successful outcome, solo feasibility and ongoing support burden.

## Gate conditions and interview experiment

**Before Phase 1 shortlist can close**, seek **two independent specific buyer pain signals** per chosen vertical (not same person reposting), current spend or real paid alternative, at least one apparent gap surviving a hands-on competitor check and plausible reachable buyers. At least one niche (#1) still fails independent narrow-buyer signal count. **Research is still in progress.**

**Interview batch proposal (not conducted):**
- 6 retail/wholesale sales-ops coordinators (weekly multi-partner reports); separate from 6 distributor/catalog operators (price feed changes); do not conflate.
- 6 monthly bookkeepers with 15–60 clients, half using paid client portal software.
- 5 small renovation contractors who have completed multiple jobs recently.

For every conversation use [The Mom Test template](../templates/customer-interview.md):
- Last time this happened? Can you show a safe, redacted example? What did it cost? Why was the existing tool insufficient? How frequent? Who decides spending?
- After the workflow is clear, show a small paid-pilot offer **with a real price** and ask for an actual commitment.
- Record uninterested buyers and contradictory outcomes, not just positive quotes.

**Indicative economics, not a forecast:** to reach $2,000 gross MRR, $39/mo needs 52 subscriptions; $49/mo needs 41; $79/mo needs 26; $99/mo needs 21, excluding churn, taxes, payment fees, infrastructure, support and marketing. It is unknown whether any candidate can attract those customers.

### Next cheapest falsifiable step per leading candidate
| Candidate | Single test | Suggested fast pass | Failure/stop |
|---|---|---|---|
| A wholesale reports | 6 interviews + competitor comparison using redacted weekly reports | 3+ buyer organizations with persistent monthly >1h manual burden, 2+ tangible spending/paid pilots, evidence of unsolved specific report inconsistency | All use Power Query/Sheetgo easily; no real buyer budget |
| B supplier feed validation | 6 recent incidents + test against Simple CSV/OneSchema capability | >=3 observed incidents at 3 organizations and >=2 concrete priced-pilot commitments | Incumbents address it or one script solves it permanently |
| C bookkeeping | 6–8 interviews, half current paid-tool users | >=3 real repeated missing/wrong-month incidents not handled by current paid software, >=2 priced-pilot buyers | Pure compliance problem, no useful delta vs Content Snare / TaxDome |
| D contractor changes | 5 recent jobs, compare current process and Joist | >=3 show financially consequential missing signoffs, >=2 request paid test after Joist comparison | Signed text/PDF/Joist resolves problem |

Thresholds are founder screening heuristics; not validated experimental statistics.

## Immediate decision / what NOT to do
- **DO NOT BUILD** a generic CSV importer, document reminder, COI tracker, chargeback AI writer, social approval or Airbnb calendar sharing app.
- **DO NOT** pick a tech stack, localize in 19 languages, create videos with Neuma, or set up store release factory until buyer problem and offer are tested.
- **DO** choose narrower jobs, collect negative evidence, run interviews and compare real alternate workflows.
- React Native/Expo, Neuma, and app-release skills are implementation/distribution resources after demand validation, not an opportunity thesis.

## Research limitations
Desk research quality is uneven: some firsthand Reddit experiences are credible in detail but unverified; user authorship and commercialization may be hidden. We did not quantify total addressable market, verify competitor usage or customer reviews, run product trials, verify vendor pricing at purchase, measure distribution reach, or conduct interviews. Several products are capable enough to negate generic wedges. Exact sources and pricing must be rechecked at validation. No financial projections or guaranteed revenue.

**Current Phase 1 status: In progress — exploratory shortlist only.**
