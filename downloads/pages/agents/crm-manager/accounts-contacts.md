---
title: "Review account and contact changes"
url: "/agents/crm-manager/accounts-contacts/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review account and contact changes

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

The described workflow creates or enriches account and contact context, maps interactions and identifies data quality issues.

<a id="prerequisites"></a>
## Before you begin

Use a workspace where the agent and required source connections have been enabled. Name the user responsible for review and verify access to the representative account, deal or recording.

- [CRM Manager agent](../crm-manager.md)
- [Agent configuration](../configuration.md)

<a id="procedure"></a>
## Review procedure



1. Inspect the account match.
2. Compare source identity and existing records.
3. Review enrichment.
4. Resolve ambiguous duplicates before accepting a change..

<a id="expected-result"></a>
## Expected result to verify

A correctly matched record and an explainable proposed update. This is an acceptance target for the described workflow; record whether it actually occurs in the current deployment.

<a id="exceptions"></a>
## Exceptions and missing information

Duplicate auto-merge thresholds and ambiguous hierarchy handling remain unresolved. Do not infer unlimited enrichment coverage.

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

- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
