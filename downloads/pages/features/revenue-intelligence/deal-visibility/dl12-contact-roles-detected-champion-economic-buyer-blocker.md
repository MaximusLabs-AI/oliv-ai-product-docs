---
title: "Contact roles detected (champion, economic buyer, blocker) [DL12]"
url: "/features/revenue-intelligence/deal-visibility/dl12-contact-roles-detected-champion-economic-buyer-blocker/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Contact roles detected (champion, economic buyer, blocker) [DL12]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion DL12: Does it work out who the champion and the economic buyer are?

<a id="parameter-dl12"></a>
## Contact roles detected (champion, economic buyer, blocker)

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="dl12-buyer-question"></a>
### Buyer question and terminology

Does it work out who the champion and the economic buyer are?

- Market names: role detection; persona tagging
- Decision weight: High; primary reviewers: Account executive; Sales manager

<a id="dl12-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): Champion Identification and Economic Buyer models (/intent-graph)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="dl12-acceptance"></a>
### Acceptance exercise

Use an active deal, a stalled deal and a deal with contradictory CRM and conversation signals. Inspect why a risk was raised.

1. Translate this criterion into an observable result: Does it work out who the champion and the economic buyer are?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="dl12-limits"></a>
### Scope and unresolved details

Separate a source-derived risk signal from a prediction or a manager-approved decision.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Deal Driver agent](../../../agents/deal-driver.md)
- [Run a pipeline review](../../../workflows/pipeline-review.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=DL12)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
