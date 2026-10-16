---
title: "Review manager and leadership coaching views"
url: "/agents/coach/manager-visibility/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review manager and leadership coaching views

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The original reference describes manager visibility into active goals and progress, with broader team and organizational views for leaders.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Coach agent](../coach.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Verify team membership.
2. Inspect rep-level evidence.
3. Compare aggregate trends.
4. Check that restricted users cannot see another team..

<a id="expected-result"></a>
## Expected result to verify

A scoped view of coaching progress and development needs. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm whether team-level reporting is generally available and how manager hierarchies are enforced.

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

- WEB:/agents/coach: [Coach – AI Sales Coaching Agent | Oliv AI](https://oliv.ai/agents/coach)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
