---
title: "Platform and context: Data foundation and context graph"
url: "/features/platform/data-foundation-and-context-graph/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Platform and context: Data foundation and context graph

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate data foundation and context graph within platform and context, with 18 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Keep the CRM as the system of record while evaluating shared context, process definitions and coordinated agent work.

Compare source links, identity matching and permissions before an action is proposed.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)

<a id="parameter-p7"></a>
### P7 — Unified revenue data foundation

Where does all revenue data land, and can the AI reason over all of it at once?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Unified revenue data foundation [P7]](data-foundation-and-context-graph/p7-unified-revenue-data-foundation.md)

<a id="parameter-p8"></a>
### P8 — Persistent account memory

Does the system keep a living understanding of each account, or rebuild it every time I ask?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Persistent account memory [P8]](data-foundation-and-context-graph/p8-persistent-account-memory.md)

<a id="parameter-p9"></a>
### P9 — Activity-to-account mapping that copes with a messy CRM

Will calls and emails land on the right account and opportunity when my CRM has duplicates?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Activity-to-account mapping that copes with a messy CRM [P9]](data-foundation-and-context-graph/p9-activity-to-account-mapping-that-copes-with-a-messy-crm.md)

<a id="parameter-p10"></a>
### P10 — Correct mapping when one account has several open opportunities

When we sell two products into one company, does each call land on the right deal?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Correct mapping when one account has several open opportunities [P10]](data-foundation-and-context-graph/p10-correct-mapping-when-one-account-has-several-open-opportunities.md)

<a id="parameter-p11"></a>
### P11 — One call covering several customer accounts split correctly

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p11-buyer-question"></a>
#### Buyer question and terminology

On a partner call about three customers, does each discussion land on the right account?

- Market names: partner call mapping
- Decision weight: Medium; primary reviewers: RevOps

<a id="p11-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /object-graph

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p11-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: On a partner call about three customers, does each discussion land on the right account?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p11-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P11)

<a id="parameter-p12"></a>
### P12 — Acquisitions and domain changes followed

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p12-buyer-question"></a>
#### Buyer question and terminology

If a buyer's company is acquired and their email domain changes, is the activity kept?

- Market names: M&A mapping; domain change handling
- Decision weight: Medium; primary reviewers: RevOps

<a id="p12-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /object-graph "acquisition adjacencies surfaced through live web research"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p12-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: If a buyer's company is acquired and their email domain changes, is the activity kept?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p12-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P12)

<a id="parameter-p13"></a>
### P13 — Duplicate records resolved during mapping

When an account exists twice, does it pick the live one?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Duplicate records resolved during mapping [P13]](data-foundation-and-context-graph/p13-duplicate-records-resolved-during-mapping.md)

<a id="parameter-p14"></a>
### P14 — Full content kept, not only metadata

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p14-buyer-question"></a>
#### Buyer question and terminology

Does it store the transcript and email body, or just that a meeting happened?

- Market names: content capture vs metadata capture
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="p14-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /object-graph contrasts Oliv with metadata-only capture

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p14-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Does it store the transcript and email body, or just that a meeting happened?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p14-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P14)

<a id="parameter-p15"></a>
### P15 — Meaning-based signal detection, not keywords

If a prospect mentions a competitor in passing, is that flagged the same as actively evaluating them?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Meaning-based signal detection, not keywords [P15]](data-foundation-and-context-graph/p15-meaning-based-signal-detection-not-keywords.md)

<a id="parameter-p16"></a>
### P16 — Number of out-of-the-box signal models

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p16-buyer-question"></a>
#### Buyer question and terminology

How many questions does it answer out of the box?

- Market names: SLM library; signal library
- Decision weight: Medium; primary reviewers: RevOps

<a id="p16-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): "100+ specialized SLMs", about 80 named on /intent-graph

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p16-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: How many questions does it answer out of the box?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p16-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P16)

<a id="parameter-p17"></a>
### P17 — Signals tuned to what we sell

Will it ignore pains that have nothing to do with our product?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Signals tuned to what we sell [P17]](data-foundation-and-context-graph/p17-signals-tuned-to-what-we-sell.md)

<a id="parameter-p18"></a>
### P18 — Reasons over the full account history, not retrieved fragments

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p18-buyer-question"></a>
#### Buyer question and terminology

Does the AI read all 10+ calls and the email thread, or a few chunks?

- Market names: synthesis vs RAG; long-context reasoning
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="p18-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /intent-graph; outreach blurbs "Gong retrieves… Oliv synthesizes"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p18-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Does the AI read all 10+ calls and the email thread, or a few chunks?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p18-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P18)

<a id="parameter-p19"></a>
### P19 — Published accuracy and hallucination method

Is there evidence behind the accuracy claim?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Published accuracy and hallucination method [P19]](data-foundation-and-context-graph/p19-published-accuracy-and-hallucination-method.md)

<a id="parameter-p20"></a>
### P20 — Signal model refresh as our business changes

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p20-buyer-question"></a>
#### Buyer question and terminology

When we launch a product or new persona, do the signals update?

- Market names: model retraining; re-research
- Decision weight: Medium; primary reviewers: RevOps; Product marketing

<a id="p20-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /intent-graph "quarterly re-research"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p20-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: When we launch a product or new persona, do the signals update?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p20-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P20)

<a id="parameter-p21"></a>
### P21 — Product usage, billing and ticket data from the warehouse

Can it see what customers actually do in our product, not only what they say?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Product usage, billing and ticket data from the warehouse [P21]](data-foundation-and-context-graph/p21-product-usage-billing-and-ticket-data-from-the-warehouse.md)

<a id="parameter-p22"></a>
### P22 — Shared Slack and Teams channels with customers monitored

Does it read the shared channel where the customer actually talks to us?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Shared Slack and Teams channels with customers monitored [P22]](data-foundation-and-context-graph/p22-shared-slack-and-teams-channels-with-customers-monitored.md)

<a id="parameter-p23"></a>
### P23 — Activity in other apps (contract redlines, shared drives, sequences)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="p23-buyer-question"></a>
#### Buyer question and terminology

Does work in our contract tool or shared drive count as account context?

- Market names: app activity capture
- Decision weight: Low; primary reviewers: RevOps

<a id="p23-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): /context-capture "Activity through apps"; apps not named

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p23-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Does work in our contract tool or shared drive count as account context?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p23-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P23)

<a id="parameter-p24"></a>
### P24 — Third-party data blended with first-party context

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="p24-buyer-question"></a>
#### Buyer question and terminology

Does it combine our own conversations with external company data?

- Market names: data enrichment; waterfall enrichment
- Decision weight: Medium; primary reviewers: SDR / BDR leader; RevOps

<a id="p24-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): /context-capture "Third-party data and the web"; Apollo data partnership in founder material, not on site

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p24-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Does it combine our own conversations with external company data?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p24-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P24)

<a id="explore"></a>
## Explore

- [Unified revenue data foundation [P7]](data-foundation-and-context-graph/p7-unified-revenue-data-foundation.md)
- [Persistent account memory [P8]](data-foundation-and-context-graph/p8-persistent-account-memory.md)
- [Activity-to-account mapping that copes with a messy CRM [P9]](data-foundation-and-context-graph/p9-activity-to-account-mapping-that-copes-with-a-messy-crm.md)
- [Correct mapping when one account has several open opportunities [P10]](data-foundation-and-context-graph/p10-correct-mapping-when-one-account-has-several-open-opportunities.md)
- [Duplicate records resolved during mapping [P13]](data-foundation-and-context-graph/p13-duplicate-records-resolved-during-mapping.md)
- [Meaning-based signal detection, not keywords [P15]](data-foundation-and-context-graph/p15-meaning-based-signal-detection-not-keywords.md)
- [Signals tuned to what we sell [P17]](data-foundation-and-context-graph/p17-signals-tuned-to-what-we-sell.md)
- [Published accuracy and hallucination method [P19]](data-foundation-and-context-graph/p19-published-accuracy-and-hallucination-method.md)
- [Product usage, billing and ticket data from the warehouse [P21]](data-foundation-and-context-graph/p21-product-usage-billing-and-ticket-data-from-the-warehouse.md)
- [Shared Slack and Teams channels with customers monitored [P22]](data-foundation-and-context-graph/p22-shared-slack-and-teams-channels-with-customers-monitored.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
