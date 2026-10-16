---
title: "CRM automation and quality: Automatic updates"
url: "/features/crm-automation/automatic-updates/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# CRM automation and quality: Automatic updates

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate automatic updates within crm automation and quality, with 13 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Review source-grounded record updates while preserving CRM ownership, field conventions and approval boundaries.

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)

<a id="parameter-cr1"></a>
### CR1 — Standard fields updated after every activity (stage, close date, amount, next step)

Does the CRM update itself from what happened?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Standard fields updated after every activity (stage, close date, amount, next step) [CR1]](automatic-updates/cr1-standard-fields-updated-after-every-activity-stage-close-date-amount-n.md)

<a id="parameter-cr2"></a>
### CR2 — Custom fields updated

Will it fill our own custom fields, not only standard ones?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Custom fields updated [CR2]](automatic-updates/cr2-custom-fields-updated.md)

<a id="parameter-cr3"></a>
### CR3 — Meeting notes written to the CRM

Do call notes land in the CRM record?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Meeting notes written to the CRM [CR3]](automatic-updates/cr3-meeting-notes-written-to-the-crm.md)

<a id="parameter-cr4"></a>
### CR4 — All activity logged to the CRM

Are calls, emails and meetings logged as CRM activity?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [All activity logged to the CRM [CR4]](automatic-updates/cr4-all-activity-logged-to-the-crm.md)

<a id="parameter-cr5"></a>
### CR5 — Review-before-write mode

Can every update wait for approval?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Review-before-write mode [CR5]](automatic-updates/cr5-review-before-write-mode.md)

<a id="parameter-cr6"></a>
### CR6 — Fully automatic mode

Can it update without approval once we trust it?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Fully automatic mode [CR6]](automatic-updates/cr6-fully-automatic-mode.md)

<a id="parameter-cr7"></a>
### CR7 — Where reps approve suggested updates

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="cr7-buyer-question"></a>
#### Buyer question and terminology

Do reps approve in Slack, email, the CRM or the Oliv app?

- Market names: approval inbox
- Decision weight: Medium; primary reviewers: Account executive

<a id="cr7-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr7-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Do reps approve in Slack, email, the CRM or the Oliv app?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr7-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR7)

<a id="parameter-cr8"></a>
### CR8 — Source shown for every proposed update

Is every suggestion tied to the moment in the conversation?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Source shown for every proposed update [CR8]](automatic-updates/cr8-source-shown-for-every-proposed-update.md)

<a id="parameter-cr9"></a>
### CR9 — Weekly governance digest with acceptance rate by rep

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr9-buyer-question"></a>
#### Buyer question and terminology

Can RevOps see what was suggested, accepted and cleaned each week?

- Market names: data governance report
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr9-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "Your governance digest lands at 8AM"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr9-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Can RevOps see what was suggested, accepted and cleaned each week?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr9-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR9)

<a id="parameter-cr10"></a>
### CR10 — RevOps can direct the agent with plain-language tasks

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr10-buyer-question"></a>
#### Buyer question and terminology

Can I say "find all duplicate accounts" and have it done?

- Market names: on-demand data jobs
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr10-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager examples

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr10-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Can I say "find all duplicate accounts" and have it done?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr10-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR10)

<a id="parameter-cr11"></a>
### CR11 — Field-level permissions for what agents may write

Can we stop the agent from touching amount or close date?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Field-level permissions for what agents may write [CR11]](automatic-updates/cr11-field-level-permissions-for-what-agents-may-write.md)

<a id="parameter-cr12"></a>
### CR12 — Conflicts between rep edits and agent edits

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="cr12-buyer-question"></a>
#### Buyer question and terminology

What happens if a rep and the agent change the same field?

- Market names: write-back conflict handling
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr12-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr12-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: What happens if a rep and the agent change the same field?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr12-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR12)

<a id="parameter-cr13"></a>
### CR13 — Sync frequency

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="cr13-buyer-question"></a>
#### Buyer question and terminology

Do updates land in real time or overnight?

- Market names: real-time sync; batch sync
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr13-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "Bi-directional… real-time" in founder material; "refreshes deal fields overnight" in /agents/deal-driver copy

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr13-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Do updates land in real time or overnight?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr13-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR13)

<a id="explore"></a>
## Explore

- [Standard fields updated after every activity (stage, close date, amount, next step) [CR1]](automatic-updates/cr1-standard-fields-updated-after-every-activity-stage-close-date-amount-n.md)
- [Custom fields updated [CR2]](automatic-updates/cr2-custom-fields-updated.md)
- [Meeting notes written to the CRM [CR3]](automatic-updates/cr3-meeting-notes-written-to-the-crm.md)
- [All activity logged to the CRM [CR4]](automatic-updates/cr4-all-activity-logged-to-the-crm.md)
- [Review-before-write mode [CR5]](automatic-updates/cr5-review-before-write-mode.md)
- [Fully automatic mode [CR6]](automatic-updates/cr6-fully-automatic-mode.md)
- [Source shown for every proposed update [CR8]](automatic-updates/cr8-source-shown-for-every-proposed-update.md)
- [Field-level permissions for what agents may write [CR11]](automatic-updates/cr11-field-level-permissions-for-what-agents-may-write.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
