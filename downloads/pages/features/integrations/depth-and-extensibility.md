---
title: "Integrations and extensibility: Depth and extensibility"
url: "/features/integrations/depth-and-extensibility/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Integrations and extensibility: Depth and extensibility

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate depth and extensibility within integrations and extensibility, with 6 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Evaluate connector scope, identity, synchronization direction, data contracts and recovery.

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)

<a id="parameter-in21"></a>
### IN21 — Two-way CRM sync

Does it read from and write to the CRM?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Two-way CRM sync [IN21]](depth-and-extensibility/in21-two-way-crm-sync.md)

<a id="parameter-in22"></a>
### IN22 — Public REST API

Can our engineers build on it?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Public REST API [IN22]](depth-and-extensibility/in22-public-rest-api.md)

<a id="parameter-in23"></a>
### IN23 — Webhooks

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="in23-buyer-question"></a>
#### Buyer question and terminology

Can it push events into our own systems?

- Market names: event webhooks
- Decision weight: Medium; primary reviewers: IT / security

<a id="in23-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in23-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can it push events into our own systems?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in23-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN23)

<a id="parameter-in24"></a>
### IN24 — Historical data import (CRM history, past emails, past calls)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in24-buyer-question"></a>
#### Buyer question and terminology

Does it learn from our history on day one, or only from new activity?

- Market names: backfill
- Decision weight: Medium; primary reviewers: RevOps

<a id="in24-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): Gong history import is offered; CRM and email backfill not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in24-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Does it learn from our history on day one, or only from new activity?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in24-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN24)

<a id="parameter-in25"></a>
### IN25 — New integration requests

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in25-buyer-question"></a>
#### Buyer question and terminology

Can we ask for an integration we need?

- Market names: integration roadmap
- Decision weight: Low; primary reviewers: RevOps

<a id="in25-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /integrations "Request an Integration"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in25-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can we ask for an integration we need?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in25-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN25)

<a id="parameter-in26"></a>
### IN26 — Sandbox to try the product without signing up

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in26-buyer-question"></a>
#### Buyer question and terminology

Can I try it before talking to sales?

- Market names: product sandbox; interactive demo
- Decision weight: Medium; primary reviewers: RevOps; Founder / CEO

<a id="in26-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): sandbox.oliv.ai

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in26-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can I try it before talking to sales?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in26-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN26)

<a id="explore"></a>
## Explore

- [Two-way CRM sync [IN21]](depth-and-extensibility/in21-two-way-crm-sync.md)
- [Public REST API [IN22]](depth-and-extensibility/in22-public-rest-api.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
