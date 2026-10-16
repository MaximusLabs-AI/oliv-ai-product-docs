---
title: "Agent governance: Oversight"
url: "/features/agent-governance/oversight/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Agent governance: Oversight

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate oversight within agent governance, with 7 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Define which data an agent can read, which actions it can propose and who authorizes execution.

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)

<a id="parameter-ag10"></a>
### AG10 — Agents hand over to a human when unsure

Does an agent ask instead of guessing?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Agents hand over to a human when unsure [AG10]](oversight/ag10-agents-hand-over-to-a-human-when-unsure.md)

<a id="parameter-ag11"></a>
### AG11 — Playbook changes need approval

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="ag11-buyer-question"></a>
#### Buyer question and terminology

Can a playbook change happen without RevOps approving it?

- Market names: change approval
- Decision weight: Medium; primary reviewers: RevOps

<a id="ag11-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/oliver "drafts the next process update for your review"; "You just approve"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag11-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Can a playbook change happen without RevOps approving it?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag11-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG11)

<a id="parameter-ag12"></a>
### AG12 — Playbook version history

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="ag12-buyer-question"></a>
#### Buyer question and terminology

Can we see who changed the playbook and when?

- Market names: versioning
- Decision weight: Medium; primary reviewers: RevOps

<a id="ag12-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): /agents/oliver demo shows "History · Edit · Edited 5 days ago by RevOps + Oliver"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag12-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Can we see who changed the playbook and when?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag12-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG12)

<a id="parameter-ag13"></a>
### AG13 — Agent quality measured over time

How do we know an agent is getting better, not worse?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Agent quality measured over time [AG13]](oversight/ag13-agent-quality-measured-over-time.md)

<a id="parameter-ag14"></a>
### AG14 — Acceptance rate per agent

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="ag14-buyer-question"></a>
#### Buyer question and terminology

What share of each agent's suggestions do people accept?

- Market names: suggestion acceptance
- Decision weight: Medium; primary reviewers: RevOps

<a id="ag14-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Weekly governance digest reports acceptance rate by rep for CRM Manager; per-agent reporting not described

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag14-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: What share of each agent's suggestions do people accept?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag14-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG14)

<a id="parameter-ag15"></a>
### AG15 — Agents follow our communication rules

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="ag15-buyer-question"></a>
#### Buyer question and terminology

Will agents avoid claims our legal team has banned?

- Market names: brand rules; banned claims; tone rules
- Decision weight: Medium; primary reviewers: Legal / procurement; Product marketing

<a id="ag15-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Global Handbook holds positioning and approval rules; enforcement of banned phrases not described

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag15-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Will agents avoid claims our legal team has banned?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag15-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG15)

<a id="parameter-ag16"></a>
### AG16 — Reps cannot see each other's private agent memory

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="ag16-buyer-question"></a>
#### Buyer question and terminology

Is one rep's personal memory hidden from others?

- Market names: data separation
- Decision weight: Medium; primary reviewers: IT / security

<a id="ag16-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /process-graph-v2 "visible only to them"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag16-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Is one rep's personal memory hidden from others?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag16-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG16)

<a id="explore"></a>
## Explore

- [Agents hand over to a human when unsure [AG10]](oversight/ag10-agents-hand-over-to-a-human-when-unsure.md)
- [Agent quality measured over time [AG13]](oversight/ag13-agent-quality-measured-over-time.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
