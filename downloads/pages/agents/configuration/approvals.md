---
title: "Tool modes and action boundaries"
url: "/agents/configuration/approvals/"
version: "1.0"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Tool modes and action boundaries

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Approval terminology differs across the sources. Establish the rule for each action rather than assuming one setting governs every workflow.

<a id="mode-labels"></a>
## Labels in the sources



| Source | Labels or behavior | Interpretation |
| --- | --- | --- |
| Prototype tool selector | Auto Run; Requires Approval; Agent Decides | Observed UI options; runtime enforcement unverified |
| Prototype super-agent conversation | Ask before acting; Act without asking | Separate conversation control; precedence unverified |
| CRM Manager source | Ask First; Auto-Pilot | Described CRM review/automatic modes |
| Oliver source | Human sign-off for handbook changes | Described process-governance boundary |
| Prospector live page | Rep reviews first email; follow-ups can be automatic | Specific outbound behavior to confirm in deployment |

<a id="precedence"></a>
## Precedence is unresolved

The prototype does not define which setting wins if a conversation control and a tool mode disagree. It also does not demonstrate an approval queue. This does not prove the live product lacks those features.

Before writing an end-user procedure, confirm scope, default, persistence and enforcement for each setting. Check whether an administrator can restrict it and whether a user can override it.

<a id="approval-contract"></a>
## Recommended approval contract



- State the exact action being approved and the destination system.
- Show the proposed record values or complete outbound content.
- Identify the reviewer and expiry or escalation rule.
- Define reject, edit, cancel and retry behavior.
- Record the result and the identity used for the external action.
- Specify what happens if the underlying record changes while approval is pending.

<a id="approval-tests"></a>
## Recommended checks

Test a read-only task, a draft, a CRM update and a customer-facing message separately. Verify that an unapproved action does not execute and that a rejected item remains understandable.

The prototype’s Auto Run display default is not proof that agents execute without approval in production. That claim remains blocked until observed or explicitly confirmed by the implementation owner.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)
