---
title: "Integrations and extensibility: Breadth"
url: "/features/integrations/breadth/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Integrations and extensibility: Breadth

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate breadth within integrations and extensibility, with 20 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Evaluate connector scope, identity, synchronization direction, data contracts and recovery.

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)

<a id="parameter-in1"></a>
### IN1 — Integration count stated the same everywhere

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in1-buyer-question"></a>
#### Buyer question and terminology

How many integrations are there, really?

- Market names: integrations
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="in1-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "70+ apps", "70+ integrations", "100+ integrations" and "100+ SaaS tools" all live (Aug 2026 site capture)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in1-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: How many integrations are there, really?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in1-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN1)

<a id="parameter-in2"></a>
### IN2 — Google Calendar

Does it read Google Calendar?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Google Calendar [IN2]](breadth/in2-google-calendar.md)

<a id="parameter-in3"></a>
### IN3 — Outlook and Exchange calendar

Does it read Outlook calendars?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Outlook and Exchange calendar [IN3]](breadth/in3-outlook-and-exchange-calendar.md)

<a id="parameter-in4"></a>
### IN4 — Snowflake



Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Snowflake [IN4]](breadth/in4-snowflake.md)

<a id="parameter-in5"></a>
### IN5 — Databricks

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in5-buyer-question"></a>
#### Buyer question and terminology



- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="in5-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /context-capture

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in5-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in5-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN5)

<a id="parameter-in6"></a>
### IN6 — Amazon Redshift

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in6-buyer-question"></a>
#### Buyer question and terminology



- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="in6-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /context-capture

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in6-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in6-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN6)

<a id="parameter-in7"></a>
### IN7 — Google BigQuery

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in7-buyer-question"></a>
#### Buyer question and terminology



- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: RevOps; IT / security

<a id="in7-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /context-capture

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in7-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in7-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN7)

<a id="parameter-in8"></a>
### IN8 — MySQL and other databases

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in8-buyer-question"></a>
#### Buyer question and terminology



- Market names: database connectors
- Decision weight: Low; primary reviewers: IT / security

<a id="in8-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): "70+ integrations including Redshift, Snowflake and MySQL"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in8-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in8-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN8)

<a id="parameter-in9"></a>
### IN9 — Zendesk

Are Zendesk tickets read into the account picture?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Zendesk [IN9]](breadth/in9-zendesk.md)

<a id="parameter-in10"></a>
### IN10 — Other ticketing tools (Intercom, Freshdesk, ServiceNow, Jira Service Management)

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="in10-buyer-question"></a>
#### Buyer question and terminology



- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: CS leader / CSM

<a id="in10-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not listed

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in10-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in10-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN10)

<a id="parameter-in11"></a>
### IN11 — Customer success platforms (Gainsight, ChurnZero, Totango, Vitally, Planhat)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in11-buyer-question"></a>
#### Buyer question and terminology

Can it read from our current CS platform while we evaluate?

- Market names: CSP integration
- Decision weight: Medium; primary reviewers: CS leader / CSM

<a id="in11-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "connects to your CRM, CSP, email…" (/agents/olivia); platforms not named

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in11-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can it read from our current CS platform while we evaluate?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in11-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN11)

<a id="parameter-in12"></a>
### IN12 — Product analytics (Mixpanel, Amplitude, Pendo, PostHog, Heap)

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="in12-buyer-question"></a>
#### Buyer question and terminology

Can usage come straight from our analytics tool?

- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: CS leader / CSM; RevOps

<a id="in12-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Usage arrives through the warehouse; direct analytics connectors not listed

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in12-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can usage come straight from our analytics tool?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in12-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN12)

<a id="parameter-in13"></a>
### IN13 — Billing (Stripe, Chargebee, Zuora)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in13-buyer-question"></a>
#### Buyer question and terminology

Does billing history feed the account picture?

- Market names: billing integration
- Decision weight: Medium; primary reviewers: CS leader / CSM; CFO / finance

<a id="in13-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "billing history" via the warehouse (/context-capture)

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in13-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Does billing history feed the account picture?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in13-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN13)

<a id="parameter-in14"></a>
### IN14 — Sales engagement tools (Outreach, Salesloft)

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in14-buyer-question"></a>
#### Buyer question and terminology

Can it read sequences from the engagement tool we already run?

- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: SDR / BDR leader; RevOps

<a id="in14-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /integrations "Sales Prospecting Tools"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in14-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can it read sequences from the engagement tool we already run?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in14-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN14)

<a id="parameter-in15"></a>
### IN15 — Data providers (Apollo, ZoomInfo, SalesIntel, Crunchbase, LinkedIn Sales Navigator)

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in15-buyer-question"></a>
#### Buyer question and terminology



- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: SDR / BDR leader

<a id="in15-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /integrations; founder material; /agents/prospector setup

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in15-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: 
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in15-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN15)

<a id="parameter-in16"></a>
### IN16 — Dialers (Aircall, JustCall, Orum, Nooks, RingCentral, Dialpad, Talkdesk, Five9)

Is our dialer supported?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Dialers (Aircall, JustCall, Orum, Nooks, RingCentral, Dialpad, Talkdesk, Five9) [IN16]](breadth/in16-dialers-aircall-justcall-orum-nooks-ringcentral-dialpad-talkdesk-five9.md)

<a id="parameter-in17"></a>
### IN17 — Document tools (Google Drive, Notion, Confluence, SharePoint)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in17-buyer-question"></a>
#### Buyer question and terminology

Can it read our docs and shared drives?

- Market names: knowledge connectors
- Decision weight: Medium; primary reviewers: Enablement; RevOps

<a id="in17-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "Shared Google Drives" (/context-capture); others not named

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in17-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can it read our docs and shared drives?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in17-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN17)

<a id="parameter-in18"></a>
### IN18 — Contract and e-signature tools (DocuSign, Ironclad)

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

<a id="in18-buyer-question"></a>
#### Buyer question and terminology

Do contract redlines count as signal?

- Market names: No additional names recorded.
- Decision weight: Low; primary reviewers: Legal / procurement

<a id="in18-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

Assessment excerpt (9 October 2026): "Contract platforms with back-and-forth redlines" (/context-capture); tools not named

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in18-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Do contract redlines count as signal?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in18-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN18)

<a id="parameter-in19"></a>
### IN19 — Alert channels (Slack, Teams, Google Chat, Workplace)

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="in19-buyer-question"></a>
#### Buyer question and terminology

Where can alerts go?

- Market names: No additional names recorded.
- Decision weight: Medium; primary reviewers: Account executive; Sales manager

<a id="in19-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /integrations "Communication Channels"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in19-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Where can alerts go?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in19-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN19)

<a id="parameter-in20"></a>
### IN20 — Zapier, Make or n8n

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="in20-buyer-question"></a>
#### Buyer question and terminology

Can we connect it to anything else ourselves?

- Market names: workflow automation
- Decision weight: Low; primary reviewers: RevOps

<a id="in20-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not stated

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="in20-acceptance"></a>
#### Acceptance exercise

Connect a test tenant, inspect granted scopes and verify a create, change, failed update and reconnection.

1. Translate this criterion into an observable result: Can we connect it to anything else ourselves?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="in20-limits"></a>
#### Scope and unresolved details

A named connector or logo is not proof of all objects, bidirectional sync, write-back or API availability.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Integrations](../../integrations.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=IN20)

<a id="explore"></a>
## Explore

- [Google Calendar [IN2]](breadth/in2-google-calendar.md)
- [Outlook and Exchange calendar [IN3]](breadth/in3-outlook-and-exchange-calendar.md)
- [Snowflake [IN4]](breadth/in4-snowflake.md)
- [Zendesk [IN9]](breadth/in9-zendesk.md)
- [Dialers (Aircall, JustCall, Orum, Nooks, RingCentral, Dialpad, Talkdesk, Five9) [IN16]](breadth/in16-dialers-aircall-justcall-orum-nooks-ringcentral-dialpad-talkdesk-five9.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
