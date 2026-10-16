---
title: "Forecaster agent"
url: "/agents/forecaster/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Forecaster agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Forecaster supports a recurring forecast process with recommended deal changes, rep submissions, manager review and historical snapshots.

<a id="purpose"></a>
## Purpose and audience

Forecaster supports a recurring forecast process with recommended deal changes, rep submissions, manager review and historical snapshots.

Primary audience: Contributors, sales managers, RevOps and leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Opportunity stages, amounts, close dates and forecast categories
- Current deal activity and qualification evidence
- Targets, measurements, team hierarchy and cadence
- Historical submissions and outcomes where available

<a id="trigger"></a>
## What starts the workflow

A configured weekly, monthly or quarterly forecast cadence. The internal document describes parallel timeframes and progressive levels of automation.

<a id="workflow"></a>
## Documented workflow



1. Review current opportunities against deal context and the forecasting rules.
2. Prepare recommendations about category, value, timing or risk.
3. Let the contributor review and submit the forecast where the configured mode requires it.
4. Allow manager adjustments and review at the supported level.
5. Preserve the submission or snapshot used for historical comparison.
6. Compare predictions with observed outcomes to support later review.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Prepared forecast views and recommendations
- Contributor submissions and manager review material
- Team rollups
- Snapshots and accuracy-review context

<a id="actions-and-review"></a>
## Actions and human review

Forecast recommendations, submissions and CRM writes are separate actions. The exact write-back fields and whether a reviewed change updates the CRM require confirmation.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- The source distinguishes contributor, manager and admin/observer views.
- AI-Assisted, AI-Managed and AI-Owned are described as progressive operating modes.
- The source does not establish an automatic threshold for advancing between modes.
- Custom measurement and multi-level approval support remain open questions.

<a id="forecast-views"></a>
### Views and review responsibilities



| View | Documented responsibility |
| --- | --- |
| Contributor | Review recommendations and submit the forecast |
| Manager | Review contributor submissions, make supported adjustments and inspect the rollup |
| Admin/observer | Configure or view targets, measurements and board settings according to actual permission |

<a id="forecast-modes"></a>
### Progressive operating modes

The source does not establish a universal time or confidence threshold for moving between these modes. Do not treat illustrative weeks, months or accuracy percentages as an automatic entitlement or product guarantee.

| Mode | Documented relationship to human review |
| --- | --- |
| AI-Assisted | Recommendations support a team-owned forecast |
| AI-Managed | A prepared forecast is reviewed and adjusted |
| AI-Owned | More of the forecast is produced automatically, with uncertainty surfaced for review |

<a id="forecast-categories"></a>
### Categories and measurements

The internal reference names Forecast, Commit, Best Case and Pipeline in its example workflow. Confirm the workspace’s actual categories and how values, counts, formulas, periods and currencies are handled before comparing totals.

<a id="collaboration"></a>
## How it works with other agents

CRM Manager supplies maintained opportunity data; Deal Driver adds current deal context; Oliver supplies process and stage criteria. The quality of the resulting forecast depends on those inputs and the chosen review process.

<a id="boundaries"></a>
## Scope and limitations

Do not convert illustrative mode timelines or accuracy percentages into a guaranteed learning curve. Forecast outcomes vary with the available history, motion and operating process.

<a id="verify"></a>
## Questions to resolve before publication



- Who enables or changes an operating mode?
- What qualifies a workspace to move to a more automatic mode?
- Which manager hierarchy and multi-level approvals are supported?
- Which metrics and formulas may administrators define?
- How are snapshots retained and separated from other deal history?
- Which forecast changes write back to which CRM fields?

<a id="related"></a>
## Related documentation



- [forecast](../apps/forecast.md)
- [forecast review](../workflows/forecast-review.md)
- [reporting cadences](../reference/reporting-cadences.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/forecaster: [Forecaster | Oliv AI](https://oliv.ai/agents/forecaster)
