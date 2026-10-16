---
title: "Per-field and per-action approval [P39]"
url: "/features/platform/agent-platform/p39-per-field-and-per-action-approval/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Per-field and per-action approval [P39]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion P39: Can a rep accept one field update and reject another?

<a id="parameter-p39"></a>
## Per-field and per-action approval

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p39-buyer-question"></a>
### Buyer question and terminology

Can a rep accept one field update and reject another?

- Market names: granular approvals
- Decision weight: High; primary reviewers: RevOps; Account executive

<a id="p39-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "Accept, edit, or reject per field"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p39-acceptance"></a>
### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Can a rep accept one field update and reject another?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p39-limits"></a>
### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../../platform/context-graph.md)
- [Process Graph](../../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P39)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
