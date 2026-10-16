---
title: "Deal Driver agent"
url: "/agents/deal-driver/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Deal Driver agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Deal Driver brings deal changes and risk into a manager’s operating cadence, with briefs, alerts and review preparation.

<a id="purpose"></a>
## Purpose and audience

Deal Driver brings deal changes and risk into a manager’s operating cadence, with briefs, alerts and review preparation.

Primary audience: Sales managers and revenue leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Opportunity state and qualification context
- Activity and stakeholder engagement
- Team ownership and management relationships
- Configured risk and notification rules

<a id="trigger"></a>
## What starts the workflow

Daily and weekly cadence plus configured deal events. The internal document describes morning briefs, event alerts, sunset summaries and pipeline-review preparation.

<a id="workflow"></a>
## Documented workflow



1. Review the team’s current opportunities and recent activity.
2. Identify deals that warrant attention or a manager intervention.
3. Attach the evidence and a suggested next step to each item.
4. Deliver the appropriate brief, alert or review preparation.
5. Use the management review to decide and assign follow-through.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Morning team awareness
- Event-triggered risk alerts
- End-of-day summaries
- Per-rep 1:1 and team pipeline review material

<a id="actions-and-review"></a>
## Actions and human review

Deal Driver surfaces risks and administrative gaps. The source assigns actual CRM field writing to CRM Manager and forecast projections to Forecaster.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Risk thresholds and delivery destinations must be configured or confirmed.
- A quiet account, overdue next step and missing qualification evidence are different reasons for attention.
- A manager brief should retain the deal and source context that explains the recommendation.

<a id="driver-cadence"></a>
### Brief and review structure



| Output | Source-described content |
| --- | --- |
| Morning brief | Team meetings, priority deals and intervention context |
| Event alert | Changed deal state, risk or missing follow-through |
| Sunset summary | Activity outcomes and open management follow-up |
| Per-rep review | Pipeline, activity and flagged decisions |
| Team review | Coverage, movement and risk across the team |

<a id="driver-risk-meaning"></a>
### Risk reason and next step

A useful alert distinguishes inactivity, missing qualification evidence, a timing concern and an ownership gap. Verify the configured threshold and inspect the relevant activity before treating the alert as an outcome prediction.

<a id="collaboration"></a>
## How it works with other agents

The internal document groups opportunity-level meeting support with Deal Driver in a bundle and also describes Meeting Assistant as standalone. Confirm that packaging against the current commercial offer. CRM Manager and Coach provide adjacent data and development workflows.

<a id="boundaries"></a>
## Scope and limitations

Deal Driver is not a universal forecast engine, a CRM update service or a coaching replacement. It focuses on pipeline awareness and intervention.

<a id="verify"></a>
## Questions to resolve before publication



- Which alerts are available and which thresholds are configurable?
- Where do alerts arrive for each deployment?
- Is the sunset summary automatic in all configurations?
- How are multiple managers and territories handled?
- What is the current relationship between Deal Driver and Meeting Assistant packaging?

<a id="related"></a>
## Related documentation



- [pipeline review](../workflows/pipeline-review.md)
- [meeting assistant](meeting-assistant.md)
- [forecaster](forecaster.md)
- [coach](coach.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Review the manager morning brief](deal-driver/morning-brief.md)
- [Triage event-triggered deal alerts](deal-driver/risk-alerts.md)
- [Review rep-level next-step nudges](deal-driver/rep-nudges.md)
- [Review an end-of-day pipeline recap](deal-driver/sunset-summary.md)
- [Prepare 1:1 and team pipeline reviews](deal-driver/weekly-manager-review.md)
- [Set up Deal Driver](deal-driver/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Review the manager morning brief](deal-driver/morning-brief.md)
- [Triage event-triggered deal alerts](deal-driver/risk-alerts.md)
- [Review rep-level next-step nudges](deal-driver/rep-nudges.md)
- [Review an end-of-day pipeline recap](deal-driver/sunset-summary.md)
- [Prepare 1:1 and team pipeline reviews](deal-driver/weekly-manager-review.md)
- [Set up Deal Driver](deal-driver/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/deal-driver: [Deal Driver – AI Deal Risk Agent | Oliv AI](https://oliv.ai/agents/deal-driver)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
