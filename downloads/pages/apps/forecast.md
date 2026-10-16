---
title: "Forecast app"
url: "/apps/forecast/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Forecast app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Forecast organizes opportunity and pipeline work, including forecast boards, submissions, snapshots and deal context.

<a id="opportunities"></a>
## Opportunity workspace

The current product presentation includes opportunity grids, qualification tracking, buying-committee context, deal risk, forecast boards, submissions, snapshots and change history.

A grid view, a forecast category and a submitted forecast are separate concepts. Define the current view and the source of each field before comparing two numbers.

<a id="forecast-cadence"></a>
## Forecast operating cadence

Forecaster’s internal reference describes contributor preparation, manager review and an admin/observer configuration layer. Targets, measurements and cadence determine how the process is organized.

Document the actual hierarchy and rollup rule for the workspace. Multi-level approvals, custom formulas and automated mode transitions remain owner-confirmation items.

- [Forecaster agent](../agents/forecaster.md)
- [Forecast review workflow](../workflows/forecast-review.md)

<a id="history"></a>
## Snapshots and change history

A snapshot preserves a historical view used for comparison; a submission records the forecast entered for a cycle; deal change history tracks movement in individual records. They should not be described as one feature.

Confirm snapshot frequency, retention and whether corrected source data changes historical views. The prototype includes multiple deal surfaces and does not establish which is the current production grid.

<a id="forecast-boundaries"></a>
## Boundaries

Do not publish a fixed forecast-accuracy percentage or a guaranteed progression to autonomous operation from the available examples. Check results against the workspace’s actual history and sales motion.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/oliv-forecast: [Oliv Forecast – AI-Native Forecasting | Oliv AI](https://oliv.ai/oliv-forecast)
