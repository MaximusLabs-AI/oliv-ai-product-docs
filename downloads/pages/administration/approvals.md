---
title: "Approval governance"
url: "/administration/approvals/"
version: "1.0"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Approval governance

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Approval governance should describe what is approved, who decides, how the decision is enforced and what happens afterward.

<a id="approval-types"></a>
## Different actions need different rules



| Action | Documented source boundary | Still to establish |
| --- | --- | --- |
| CRM updates | CRM Manager describes reviewed and automatic modes | Scope, approver, conflict handling and recovery |
| Handbook changes | Oliver source requires human sign-off | Interface, authorized approver and propagation |
| Coaching goals | Coach source describes manager review | Role enforcement and goal delivery state |
| Opening prospect email | Prospector page describes rep review/send | Channel-specific enforcement and later follow-ups |
| Expansion introduction | Gold Digger source describes CSM review or delegation | Owner, sender and duplicate prevention |
| Other tool actions | Prototype offers three mode labels | Runtime precedence, default and approval destination |

<a id="approval-procedure"></a>
## Recommended policy record

For each workflow, record the action, scope, reviewer, destination, expiry, escalation, rejection and change-after-approval behavior. Identify the authoritative policy owner and effective date.

These are documentation and acceptance requirements, not a claim that all fields appear in an existing administration screen.

<a id="approval-production"></a>
## Production checks

Verify that an action requiring approval does not execute before the decision, that the reviewer sees the actual proposed result, and that rejection or expiry has an observable outcome.

Confirm how tool-level, conversation-level and organization-level policy interact. The available source material does not settle that precedence.

- [Tool modes and terminology](../agents/configuration/approvals.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)
