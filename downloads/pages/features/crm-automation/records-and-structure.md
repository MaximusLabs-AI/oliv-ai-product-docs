---
title: "CRM automation and quality: Records and structure"
url: "/features/crm-automation/records-and-structure/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# CRM automation and quality: Records and structure

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate records and structure within crm automation and quality, with 14 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Review source-grounded record updates while preserving CRM ownership, field conventions and approval boundaries.

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)

<a id="parameter-cr14"></a>
### CR14 — Contacts created from new meeting attendees

Are new people on calls added as contacts?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Contacts created from new meeting attendees [CR14]](records-and-structure/cr14-contacts-created-from-new-meeting-attendees.md)

<a id="parameter-cr15"></a>
### CR15 — Accounts created and enriched

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr15-buyer-question"></a>
#### Buyer question and terminology

Are new companies created and filled in?

- Market names: auto account creation
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr15-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "enriching new records"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr15-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are new companies created and filled in?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr15-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR15)

<a id="parameter-cr16"></a>
### CR16 — Opportunities created from qualification criteria

Does it open a deal when a conversation meets our criteria?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Opportunities created from qualification criteria [CR16]](records-and-structure/cr16-opportunities-created-from-qualification-criteria.md)

<a id="parameter-cr17"></a>
### CR17 — Contact enrichment (title, email, phone, LinkedIn)

Are contacts enriched with role and contact details?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Contact enrichment (title, email, phone, LinkedIn) [CR17]](records-and-structure/cr17-contact-enrichment-title-email-phone-linkedin.md)

<a id="parameter-cr18"></a>
### CR18 — Account enrichment (firmographics)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="cr18-buyer-question"></a>
#### Buyer question and terminology

Are industry, size and location filled in?

- Market names: firmographic enrichment
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr18-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Enrichment claimed; sources not named

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr18-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are industry, size and location filled in?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr18-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR18)

<a id="parameter-cr19"></a>
### CR19 — Duplicate accounts and contacts resolved

Does it find and merge duplicates?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Duplicate accounts and contacts resolved [CR19]](records-and-structure/cr19-duplicate-accounts-and-contacts-resolved.md)

<a id="parameter-cr20"></a>
### CR20 — Account hierarchies built and repaired

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr20-buyer-question"></a>
#### Buyer question and terminology

Does it fix broken parent and child accounts?

- Market names: parent-child accounts; hierarchy management
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr20-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "Rebuild broken account hierarchies"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr20-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Does it fix broken parent and child accounts?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr20-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR20)

<a id="parameter-cr21"></a>
### CR21 — Acquisitions and reorganisations mapped

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr21-buyer-question"></a>
#### Buyer question and terminology

Are acquired companies linked correctly?

- Market names: No additional names recorded.
- Decision weight: Low; primary reviewers: RevOps

<a id="cr21-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "mapping acquisitions and reorgs"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr21-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are acquired companies linked correctly?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr21-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR21)

<a id="parameter-cr22"></a>
### CR22 — Unassigned contacts cleaned up

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr22-buyer-question"></a>
#### Buyer question and terminology

Are contacts with no account or owner fixed?

- Market names: orphan contacts
- Decision weight: Low; primary reviewers: RevOps

<a id="cr22-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager "Clean unassigned contacts in pipeline"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr22-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are contacts with no account or owner fixed?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr22-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR22)

<a id="parameter-cr23"></a>
### CR23 — Historical batch clean-up

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="cr23-buyer-question"></a>
#### Buyer question and terminology

Can it clean the backlog, not only new records?

- Market names: bulk data clean-up
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr23-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/crm-manager FAQ "in real time and in batch"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr23-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Can it clean the backlog, not only new records?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr23-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR23)

<a id="parameter-cr24"></a>
### CR24 — Stale data detected (bounced emails, departed contacts)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="cr24-buyer-question"></a>
#### Buyer question and terminology

Does it notice when a contact has left?

- Market names: data decay
- Decision weight: Medium; primary reviewers: RevOps

<a id="cr24-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Stakeholder change alerts exist; decay detection not described

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr24-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Does it notice when a contact has left?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr24-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR24)

<a id="parameter-cr25"></a>
### CR25 — Lead-to-account matching

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="cr25-buyer-question"></a>
#### Buyer question and terminology

Are inbound leads matched to existing accounts?

- Market names: L2A matching; LeanData
- Decision weight: Medium; primary reviewers: RevOps; SDR / BDR leader

<a id="cr25-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr25-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are inbound leads matched to existing accounts?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr25-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR25)

<a id="parameter-cr26"></a>
### CR26 — Lead routing

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="cr26-buyer-question"></a>
#### Buyer question and terminology

Are leads routed to the right owner automatically?

- Market names: lead routing; Chili Piper; LeanData
- Decision weight: Medium; primary reviewers: SDR / BDR leader; RevOps

<a id="cr26-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Quick Qualifier "routes high-intent inbound leads to the right person" (outreach blurbs)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr26-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Are leads routed to the right owner automatically?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr26-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR26)

<a id="parameter-cr27"></a>
### CR27 — Privacy compliance monitoring in CRM and email

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="cr27-buyer-question"></a>
#### Buyer question and terminology

Does it catch GDPR and CCPA problems in our records?

- Market names: Compliance Sentinel
- Decision weight: Medium; primary reviewers: Legal / procurement; RevOps

<a id="cr27-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Compliance Sentinel (/agents-marketplace), availability unknown

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="cr27-acceptance"></a>
#### Acceptance exercise

Test a standard field, methodology field and custom field. Include a duplicate contact, conflicting values and an unwriteable field.

1. Translate this criterion into an observable result: Does it catch GDPR and CCPA problems in our records?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="cr27-limits"></a>
#### Scope and unresolved details

Check proposed versus accepted values and the CRM after execution. Do not assume every field or CRM object is supported.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [CRM Manager agent](../../agents/crm-manager.md)
- [Review and apply CRM updates](../../workflows/crm-updates.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=CR27)

<a id="explore"></a>
## Explore

- [Contacts created from new meeting attendees [CR14]](records-and-structure/cr14-contacts-created-from-new-meeting-attendees.md)
- [Opportunities created from qualification criteria [CR16]](records-and-structure/cr16-opportunities-created-from-qualification-criteria.md)
- [Contact enrichment (title, email, phone, LinkedIn) [CR17]](records-and-structure/cr17-contact-enrichment-title-email-phone-linkedin.md)
- [Duplicate accounts and contacts resolved [CR19]](records-and-structure/cr19-duplicate-accounts-and-contacts-resolved.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
