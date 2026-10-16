---
title: "Standard fields updated after every activity (stage, close date, amount, next step) [CR1]"
url: "/features/crm-automation/automatic-updates/cr1-standard-fields-updated-after-every-activity-stage-close-date-amount-n/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Standard fields updated after every activity (stage, close date, amount, next step) [CR1]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion CR1: Does the CRM update itself from what happened?

<a id="parameter-cr1"></a>
## Standard fields updated after every activity (stage, close date, amount, next step)

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr1-buyer-question"></a>
### Buyer question and terminology

Does the CRM update itself from what happened?

- Market names: CRM auto-update; AI Data Extractor (Gong); Deal Agent (Outreach); Momentum
- Decision weight: Gate; primary reviewers: RevOps; Account executive; Sales manager

<a id="cr1-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "Writes to your CRM after every activity"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr1-acceptance"></a>
### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Does the CRM update itself from what happened?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr1-limits"></a>
### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../../agents/crm-manager.md)
- [Review and apply CRM updates](../../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR1)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
