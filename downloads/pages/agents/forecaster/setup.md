---
title: "Set up Forecaster"
url: "/agents/forecaster/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up Forecaster

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Plan Forecaster inputs, process ownership, review controls and a representative acceptance exercise.

<a id="scope"></a>
## Choose the first task

Begin with one of the detailed task guides below. Agree the outcome and identify the source systems it requires.

- [Configure targets and measurements](targets-measurements.md)
- [Review deal movement and value signals](deal-signals.md)
- [Inspect snapshots and reconcile accuracy](snapshots.md)
- [Review monthly and quarterly periods](parallel-periods.md)
- [Define forecast review and autonomy boundaries](human-review.md)

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



- Confirm custom metric support, target hierarchy, currency handling and formula constraints.
- Source examples do not establish a calibrated probability model or guaranteed prediction accuracy.
- Confirm snapshot schedule, retention, correction policy and whether history is independent of Forecaster.
- Confirm fiscal calendars, time zones, overlapping periods and whether an allocated value differs from a predicted close.
- Weeks-to-autonomy and accuracy percentages in the source are illustrative claims, not commitments or acceptance evidence.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/forecaster: [Forecaster | Oliv AI](https://oliv.ai/agents/forecaster)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
