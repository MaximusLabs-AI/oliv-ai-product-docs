---
title: "Platform and context: Agent platform"
url: "/features/platform/agent-platform/"
version: "1.1-expanded"
status: editorial
source_checked: 2026-10-16
product_owner_approved: false
---

# Platform and context: Agent platform

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Evaluate agent platform within platform and context, with 19 source-assessed criteria and explicit confirmation requirements.

<a id="group-scope"></a>
## Scope of this group

Keep the CRM as the system of record while evaluating shared context, process definitions and coordinated agent work.

Compare source links, identity matching and permissions before an action is proposed.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)

<a id="parameter-p34"></a>
### P34 — Pre-built agents available on day one

How many working agents do I get without building anything?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Pre-built agents available on day one [P34]](agent-platform/p34-pre-built-agents-available-on-day-one.md)

<a id="parameter-p35"></a>
### P35 — Availability status published per agent

Which agents are generally available today and which are beta?

Source assessment: Unknown, ask Oliv. The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

- [Availability status published per agent [P35]](agent-platform/p35-availability-status-published-per-agent.md)

<a id="parameter-p36"></a>
### P36 — Orchestrator agent that routes work to specialist agents

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p36-buyer-question"></a>
#### Buyer question and terminology

Is there one agent my team talks to, which then hands work to the right specialist?

- Market names: super agent; orchestration agent; Gong Assistant; Outreach Omni Agent
- Decision weight: Medium; primary reviewers: RevOps; Account executive

<a id="p36-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): Olivia, "Chief of AI Staff"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p36-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Is there one agent my team talks to, which then hands work to the right specialist?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p36-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P36)

<a id="parameter-p37"></a>
### P37 — Configuration agent that RevOps instructs in plain language

Can RevOps change how the system works by chatting, without engineering?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Configuration agent that RevOps instructs in plain language [P37]](agent-platform/p37-configuration-agent-that-revops-instructs-in-plain-language.md)

<a id="parameter-p38"></a>
### P38 — Autonomy modes per agent

Can I start with every action approved and move to full automation later?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Autonomy modes per agent [P38]](agent-platform/p38-autonomy-modes-per-agent.md)

<a id="parameter-p39"></a>
### P39 — Per-field and per-action approval

Can a rep accept one field update and reject another?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Per-field and per-action approval [P39]](agent-platform/p39-per-field-and-per-action-approval.md)

<a id="parameter-p40"></a>
### P40 — Evidence shown for every agent action

When an agent changes something, can I see exactly why?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Evidence shown for every agent action [P40]](agent-platform/p40-evidence-shown-for-every-agent-action.md)

<a id="parameter-p41"></a>
### P41 — Log of every agent action

Can I review everything every agent did last week?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Log of every agent action [P41]](agent-platform/p41-log-of-every-agent-action.md)

<a id="parameter-p42"></a>
### P42 — Agent harness with scoped tools, memory, permissions and guardrails

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p42-buyer-question"></a>
#### Buyer question and terminology

Is each agent limited to the tools and data its job needs?

- Market names: agent harness; Revenue Harness (Gong); guardrails
- Decision weight: Medium; primary reviewers: IT / security

<a id="p42-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/olivia "Agent Harness"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p42-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Is each agent limited to the tools and data its job needs?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p42-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P42)

<a id="parameter-p43"></a>
### P43 — Custom agents built by our team

Can we build our own agents for our own processes?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Custom agents built by our team [P43]](agent-platform/p43-custom-agents-built-by-our-team.md)

<a id="parameter-p44"></a>
### P44 — Custom agents built for us on request

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p44-buyer-question"></a>
#### Buyer question and terminology

Will Oliv build an agent for a workflow we describe?

- Market names: agent build service
- Decision weight: Medium; primary reviewers: RevOps

<a id="p44-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents-marketplace "Request your custom AI Agent"

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p44-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Will Oliv build an agent for a workflow we describe?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p44-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P44)

<a id="parameter-p45"></a>
### P45 — Event and schedule triggers for agents

Can an agent run when a call ends, a deal goes quiet, or every Monday at 8am?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Event and schedule triggers for agents [P45]](agent-platform/p45-event-and-schedule-triggers-for-agents.md)

<a id="parameter-p46"></a>
### P46 — Configurable alert thresholds

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p46-buyer-question"></a>
#### Buyer question and terminology

Can each manager set what counts as a stalled deal?

- Market names: alert rules
- Decision weight: Medium; primary reviewers: Sales manager

<a id="p46-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/deal-driver FAQ: inactivity windows, field completion, deal value thresholds, per manager or team

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p46-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Can each manager set what counts as a stalled deal?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p46-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P46)

<a id="parameter-p47"></a>
### P47 — Agents deliver work where people already are

Do briefs and alerts arrive in Slack, Teams, email and the CRM, or only in another dashboard?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Agents deliver work where people already are [P47]](agent-platform/p47-agents-deliver-work-where-people-already-are.md)

<a id="parameter-p48"></a>
### P48 — Agents share one context and work together

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p48-buyer-question"></a>
#### Buyer question and terminology

Does what one agent learns reach the others?

- Market names: multi-agent collaboration
- Decision weight: Medium; primary reviewers: RevOps

<a id="p48-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): "Every agent shares context" sections on agent pages

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p48-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Does what one agent learns reach the others?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p48-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P48)

<a id="parameter-p49"></a>
### P49 — Agents improve from feedback

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

<a id="p49-buyer-question"></a>
#### Buyer question and terminology

If we reject a suggestion, does the agent learn?

- Market names: learning from rejections
- Decision weight: Medium; primary reviewers: RevOps; Sales manager

<a id="p49-evidence"></a>
#### Evidence and claim boundary

The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

Assessment excerpt (9 October 2026): /agents/forecaster and /agents/content-curator FAQs

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p49-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: If we reject a suggestion, does the agent learn?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p49-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P49)

<a id="parameter-p50"></a>
### P50 — Agents work on incomplete data

Do we need a CRM clean-up project before we start?

Source assessment: Evidenced. The 9 October assessment found a source claim. Confirm the applicable scope and current behavior before relying on it.

- [Agents work on incomplete data [P50]](agent-platform/p50-agents-work-on-incomplete-data.md)

<a id="parameter-p51"></a>
### P51 — Access to the context layer from our own AI tools

Can Claude, ChatGPT or our internal tools query Oliv's context?

Source assessment: Partial. The 9 October assessment found incomplete or narrower evidence. Treat the unresolved portion as a requirement to validate.

- [Access to the context layer from our own AI tools [P51]](agent-platform/p51-access-to-the-context-layer-from-our-own-ai-tools.md)

<a id="parameter-p52"></a>
### P52 — Choice of underlying model

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

<a id="p52-buyer-question"></a>
#### Buyer question and terminology

Can we choose or restrict which AI models are used?

- Market names: bring your own LLM; model choice
- Decision weight: Low; primary reviewers: IT / security

<a id="p52-evidence"></a>
#### Evidence and claim boundary

The source assessment is unconfirmed. Missing evidence does not mean Oliv lacks the capability.

Assessment excerpt (9 October 2026): Not published

Oliv owner decision: Not marked by Oliv. Current production behavior: Not independently verified.

<a id="p52-acceptance"></a>
#### Acceptance exercise

Map an account, its contacts and an opportunity across connected sources. Check conflicting owners, stale fields and restricted records.

1. Translate this criterion into an observable result: Can we choose or restrict which AI models are used?
2. Choose a representative permitted example and an edge case. Record the tenant, user role, connected systems and test date.
3. Compare the result with its source records and the downstream system. Capture evidence of success, failure and any reviewer intervention.
4. Ask the accountable product owner to state supported scope, exclusions, availability and the approved claim. Leave the decision open until evidence is supplied.

<a id="p52-limits"></a>
#### Scope and unresolved details

Compare source links, identity matching and permissions before an action is proposed.

- Confirm plan, seat role, entitlement and credit impact for this specific requirement.
- Confirm permissions, data freshness, failure behavior and the person responsible for recovery.
- A source statement, a working pilot and permission to make a public claim are three distinct records.

- [Context Graph](../../platform/context-graph.md)
- [Process Graph](../../platform/process-graph.md)
- [Filter this criterion in the evidence workbench](/evaluation/?q=P52)

<a id="explore"></a>
## Explore

- [Pre-built agents available on day one [P34]](agent-platform/p34-pre-built-agents-available-on-day-one.md)
- [Availability status published per agent [P35]](agent-platform/p35-availability-status-published-per-agent.md)
- [Configuration agent that RevOps instructs in plain language [P37]](agent-platform/p37-configuration-agent-that-revops-instructs-in-plain-language.md)
- [Autonomy modes per agent [P38]](agent-platform/p38-autonomy-modes-per-agent.md)
- [Per-field and per-action approval [P39]](agent-platform/p39-per-field-and-per-action-approval.md)
- [Evidence shown for every agent action [P40]](agent-platform/p40-evidence-shown-for-every-agent-action.md)
- [Log of every agent action [P41]](agent-platform/p41-log-of-every-agent-action.md)
- [Custom agents built by our team [P43]](agent-platform/p43-custom-agents-built-by-our-team.md)
- [Event and schedule triggers for agents [P45]](agent-platform/p45-event-and-schedule-triggers-for-agents.md)
- [Agents deliver work where people already are [P47]](agent-platform/p47-agents-deliver-work-where-people-already-are.md)
- [Agents work on incomplete data [P50]](agent-platform/p50-agents-work-on-incomplete-data.md)
- [Access to the context layer from our own AI tools [P51]](agent-platform/p51-access-to-the-context-layer-from-our-own-ai-tools.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:buyer-map: Buyer evaluation baseline — 9 October 2026
