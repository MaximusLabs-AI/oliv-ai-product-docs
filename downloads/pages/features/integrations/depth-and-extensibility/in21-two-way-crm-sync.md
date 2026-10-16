---
title: "Two-way CRM sync [IN21]"
url: "/features/integrations/depth-and-extensibility/in21-two-way-crm-sync/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Two-way CRM sync [IN21]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion IN21: Does it read from and write to the CRM?

<a id="parameter-in21"></a>
## Two-way CRM sync

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in21-buyer-question"></a>
### Buyer question and terminology

Does it read from and write to the CRM?

- Market names: bi-directional sync
- Decision weight: Gate; primary reviewers: RevOps; IT / security

<a id="in21-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /integrations "bidirectional sync"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in21-acceptance"></a>
### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Does it read from and write to the CRM?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in21-limits"></a>
### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../../integrations.md)
- [Integration and sync issues](../../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN21)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
