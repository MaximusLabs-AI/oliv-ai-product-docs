---
title: "Agents hand over to a human when unsure [AG10]"
url: "/features/agent-governance/oversight/ag10-agents-hand-over-to-a-human-when-unsure/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Agents hand over to a human when unsure [AG10]

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Buyer criterion AG10: Does an agent ask instead of guessing?

<a id="parameter-ag10"></a>
## Agents hand over to a human when unsure

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="ag10-buyer-question"></a>
### Buyer question and terminology

Does an agent ask instead of guessing?

- Market names: human escalation; confidence threshold
- Decision weight: High; primary reviewers: RevOps; Legal / procurement

<a id="ag10-evidence"></a>
### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /process-graph-v2 "loops in humans instead of acting confidently using outdated knowledge"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag10-acceptance"></a>
### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Does an agent ask instead of guessing?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag10-limits"></a>
### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../../agents/configuration/approvals.md)
- [Approval governance](../../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG10)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
