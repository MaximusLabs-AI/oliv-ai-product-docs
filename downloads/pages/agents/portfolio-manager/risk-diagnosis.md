---
title: "Review an account risk diagnosis"
url: "/agents/portfolio-manager/risk-diagnosis/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review an account risk diagnosis

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Portfolio Manager’s reference describes a risk flag with supporting customer context and a recommended next step.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [Portfolio Manager agent](../portfolio-manager.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Inspect the source interactions and available usage data.
2. Check stakeholder change.
3. Validate the diagnosis with the account owner..

<a id="expected-result"></a>
## Expected result to verify

A reviewed account risk and intervention. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Confirm health-score inputs and weighting; usage coverage depends on connected data and is not universal.

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

- WEB:/agents/portfolio-manager: [Portfolio Manager | Oliv AI](https://oliv.ai/agents/portfolio-manager)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
