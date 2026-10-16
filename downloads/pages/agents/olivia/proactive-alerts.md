---
title: "Triage Olivia’s proactive signals"
url: "/agents/olivia/proactive-alerts/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Triage Olivia’s proactive signals

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The source describes proactive deal risk, quiet-account and commitment reminders.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Olivia agent](../olivia.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Inspect why a signal was raised.
2. Compare known customer context.
3. Choose an owner and next action.
4. Correct or dismiss inaccurate signals..

<a id="expected-result"></a>
## Expected result to verify

A relevant signal with an accountable response. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm signal controls, quiet hours, escalation and collaboration between an AE and CSM on the same account.

If the result is absent or inconsistent, retain the source record, timestamps and the review decision. Verify connector health and permissions before repeating an action that could produce an external change.

<a id="acceptance-record"></a>
## Record acceptance



| Field | What to retain |
| --- | --- |
| Scope | Workspace, user role, account/deal/recording and test date |
| Evidence | Source interaction and the output being reviewed |
| Decision | Approved, edited, rejected, blocked or needs confirmation |
| Downstream result | Final CRM, email, report or configuration state, where applicable |
| Owner | Person responsible for unresolved behavior and the next review |

<a id="links"></a>
## Related documentation



- [Tool modes and action boundaries](../configuration/approvals.md)
- [Agent output and execution issues](../../troubleshooting/agents.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
