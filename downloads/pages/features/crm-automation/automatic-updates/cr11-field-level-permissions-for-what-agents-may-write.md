---
title: "Field-level permissions for what agents may write [CR11]"
url: "/features/crm-automation/automatic-updates/cr11-field-level-permissions-for-what-agents-may-write/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Field-level permissions for what agents may write [CR11]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion CR11: Can we stop the agent from touching amount or close date?

<a id="parameter-cr11"></a>
## Field-level permissions for what agents may write

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="cr11-buyer-question"></a>
### Buyer question and terminology

Can we stop the agent from touching amount or close date?

- Market names: write permissions
- Decision weight: High; primary reviewers: RevOps; IT / security

<a id="cr11-evidence"></a>
### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr11-acceptance"></a>
### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Can we stop the agent from touching amount or close date?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr11-limits"></a>
### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../../agents/crm-manager.md)
- [Review and apply CRM updates](../../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR11)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
