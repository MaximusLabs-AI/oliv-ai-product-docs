---
title: "Set up CRM Manager"
url: "/agents/crm-manager/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up CRM Manager

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Plan CRM Manager inputs, process ownership, review controls and a representative acceptance exercise.

<a id="scope"></a>
## Choose the first task

Begin with one of the detailed task guides below. Agree the outcome and identify the source systems it requires.

- [Choose CRM review and execution modes](operating-modes.md)
- [Review account and contact changes](accounts-contacts.md)
- [Review opportunity creation and tracking](opportunities.md)
- [Review activity and task logging](activity-task-logging.md)
- [Map standard, methodology and custom fields](field-mapping.md)
- [Accept, edit or reject a proposed CRM update](proposed-updates.md)
- [Plan a retrospective data-quality job](batch-quality.md)

<a id="connect"></a>
## Prepare inputs



1. Verify workspace entitlement and the current agent entry point with Oliv.
2. Connect the relevant CRM, calendar, recording, email or notification source with approved access.
3. Confirm account and user matching using representative data.
4. Document the process definitions, thresholds and output ownership needed for the first task.

<a id="review"></a>
## Start with human review

Require review of recommendations and external actions until the supported execution policy and permissions have been tested. A source describing automation is not enough to enable it for every action.

<a id="test"></a>
## Acceptance and recovery

Run one normal task and one case with missing, conflicting or restricted data. Inspect the source evidence and final result. If acceptance fails, stop external writes for that task and resolve the input, mapping or permission issue with its owner.

<a id="questions"></a>
## Agent-specific confirmation



- Confirm per-field and per-action granularity, audit logs, rollback and criteria for automatic execution.
- Duplicate auto-merge thresholds and ambiguous hierarchy handling remain unresolved. Do not infer unlimited enrichment coverage.
- Confirm required signals, supported objects, duplicate prevention and stage-transition approvals.
- Confirm email and channel scope, ambiguous multi-deal meetings, task completion detection and object permissions.
- Confirm who maintains mappings, supported formulas and picklists, and behavior when schema changes.
- Confirm current control labels, rejected-proposal behavior, edit history and whether proposals expire after later changes.
- Do not assume destructive merges, bulk writes or automatic backfill are available or safe without a verified contract.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
