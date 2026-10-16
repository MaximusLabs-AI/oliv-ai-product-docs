---
title: "Set up Gold Digger"
url: "/agents/gold-digger/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up Gold Digger

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Plan Gold Digger inputs, process ownership, review controls and a representative acceptance exercise.

<a id="scope"></a>
## Choose the first task

Begin with one of the detailed task guides below. Agree the outcome and identify the source systems it requires.

- [Review a customer expansion signal](signal-review.md)
- [Prepare an AE notification and ownership handoff](ae-handoff.md)
- [Review a warm introduction draft](warm-introduction.md)
- [Verify expansion CRM logging](expansion-crm.md)

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



- Confirm supported interaction sources, signal taxonomy and how dismissed signals affect later alerts.
- Confirm routing, permissions, duplicate detection and delivery channel; timing examples are not an SLA.
- Confirm sending permissions and delegation; a generated draft is not evidence that an email was sent.
- Confirm whether opportunity creation is automatic or review-required and how duplicate signals are consolidated.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/gold-digger: [Gold Digger – Expansion Signal Agent | Oliv AI](https://oliv.ai/agents/gold-digger)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
