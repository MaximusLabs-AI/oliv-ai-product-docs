---
title: "Activity-to-account mapping that copes with a messy CRM [P9]"
url: "/features/platform/data-foundation-and-context-graph/p9-activity-to-account-mapping-that-copes-with-a-messy-crm/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Activity-to-account mapping that copes with a messy CRM [P9]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion P9: Will calls and emails land on the right account and opportunity when my CRM has duplicates?

<a id="parameter-p9"></a>
## Activity-to-account mapping that copes with a messy CRM

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p9-buyer-question"></a>
### Buyer question and terminology

Will calls and emails land on the right account and opportunity when my CRM has duplicates?

- Market names: object association; activity mapping; AI Activity Mapper (Gong); Einstein Activity Capture matching
- Decision weight: Gate; primary reviewers: RevOps; Account executive

<a id="p9-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /object-graph

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p9-acceptance"></a>
### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Will calls and emails land on the right account and opportunity when my CRM has duplicates?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p9-limits"></a>
### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../../platform/context-graph.md)
- [Process Graph](../../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P9)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
