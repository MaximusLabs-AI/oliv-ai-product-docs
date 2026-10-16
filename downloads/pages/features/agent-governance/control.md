---
title: "Agent governance: Control"
url: "/features/agent-governance/control/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Agent governance: Control

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate control within agent governance, with 9 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Define which data an agent can read, which actions it can propose and who authorizes execution.

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)

<a id="parameter-ag1"></a>
### AG1 — Pause every agent at once

If something goes wrong, can we stop all agents immediately?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Pause every agent at once [AG1]](control/ag1-pause-every-agent-at-once.md)

<a id="parameter-ag2"></a>
### AG2 — Pause or switch off one agent

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="ag2-buyer-question"></a>
#### Buyer question and terminology

Can we turn off one agent without affecting the others?

- Market names: agent on/off
- Decision weight: Medium; primary reviewers: RevOps

<a id="ag2-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag2-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Can we turn off one agent without affecting the others?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag2-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG2)

<a id="parameter-ag3"></a>
### AG3 — Test mode before going live

Can we see what an agent would have done before it acts for real?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Test mode before going live [AG3]](control/ag3-test-mode-before-going-live.md)

<a id="parameter-ag4"></a>
### AG4 — Undo an agent's changes

Can we reverse a batch of changes an agent made?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Undo an agent's changes [AG4]](control/ag4-undo-an-agent-s-changes.md)

<a id="parameter-ag5"></a>
### AG5 — Limits on bulk changes

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="ag5-buyer-question"></a>
#### Buyer question and terminology

Can an agent change a thousand records without a human saying yes?

- Market names: change limits; blast radius
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="ag5-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag5-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Can an agent change a thousand records without a human saying yes?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag5-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG5)

<a id="parameter-ag6"></a>
### AG6 — Customer-facing messages need approval unless we allow otherwise

Can an agent email or message a customer on its own?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Customer-facing messages need approval unless we allow otherwise [AG6]](control/ag6-customer-facing-messages-need-approval-unless-we-allow-otherwise.md)

<a id="parameter-ag7"></a>
### AG7 — Limits on outbound volume per agent

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="ag7-buyer-question"></a>
#### Buyer question and terminology

Is there a cap on how many messages or calls an agent makes?

- Market names: send limits; rate limits
- Decision weight: Medium; primary reviewers: SDR / BDR leader; Legal / procurement

<a id="ag7-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag7-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: Is there a cap on how many messages or calls an agent makes?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag7-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG7)

<a id="parameter-ag8"></a>
### AG8 — Which user the agent writes as in the CRM

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="ag8-buyer-question"></a>
#### Buyer question and terminology

In Salesforce history, can we tell an agent's change from a rep's?

- Market names: agent identity; integration user
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="ag8-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="ag8-acceptance"></a>
#### Acceptance exercise

Run a permitted action, an action requiring approval and a denied action. Check the responsible identity and the final external-system state.

1. Translate this criterion into an observable result: In Salesforce history, can we tell an agent's change from a rep's?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="ag8-limits"></a>
#### Scope and unresolved details

Confirm actual enforcement and audit evidence; a prototype control or policy description does not prove enforcement.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Tool modes and action boundaries](../../agents/configuration/approvals.md)
- [Approval governance](../../administration/approvals.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=AG8)

<a id="parameter-ag9"></a>
### AG9 — Permissions per agent and per role

Can we decide which agents each role may use and what each may touch?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Permissions per agent and per role [AG9]](control/ag9-permissions-per-agent-and-per-role.md)

<a id="explore"></a>
## Explore

- [Pause every agent at once [AG1]](control/ag1-pause-every-agent-at-once.md)
- [Test mode before going live [AG3]](control/ag3-test-mode-before-going-live.md)
- [Undo an agent's changes [AG4]](control/ag4-undo-an-agent-s-changes.md)
- [Customer-facing messages need approval unless we allow otherwise [AG6]](control/ag6-customer-facing-messages-need-approval-unless-we-allow-otherwise.md)
- [Permissions per agent and per role [AG9]](control/ag9-permissions-per-agent-and-per-role.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
