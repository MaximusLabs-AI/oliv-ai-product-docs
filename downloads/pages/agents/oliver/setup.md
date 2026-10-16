---
title: "Set up Oliver"
url: "/agents/oliver/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up Oliver

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Plan Oliver inputs, process ownership, review controls and a representative acceptance exercise.

<a id="scope"></a>
## Choose the first task

Begin with one of the detailed task guides below. Agree the outcome and identify the source systems it requires.

- [Build the revenue process handbook](handbook.md)
- [Review schema and field configuration](schema.md)
- [Define process boundaries and exceptions](boundaries.md)
- [Review and approve handbook evolution](change-review.md)

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



- Confirm versioning, approval controls, regional exceptions and what is propagated to each agent.
- Confirm who can alter CRM schema, which changes are proposals and how existing records are affected.
- The exact granularity of team, region and per-action boundaries requires product confirmation.
- Confirm current approval UI, rollback, effective dates and what happens to active workflows mid-cycle.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
