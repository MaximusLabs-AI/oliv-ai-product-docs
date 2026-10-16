---
title: "Coach agent"
url: "/agents/coach/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Coach agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Coach turns recorded work into a recurring development process: score activity, identify focus areas, let a manager choose a goal, and track progress.

<a id="purpose"></a>
## Purpose and audience

Coach turns recorded work into a recurring development process: score activity, identify focus areas, let a manager choose a goal, and track progress.

Primary audience: Reps, managers, enablement and revenue leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Recorded calls, meetings and deal context
- Scorecards and weighted criteria
- Rep ownership and the relevant sales motion
- A manager-selected coaching goal

<a id="trigger"></a>
## What starts the workflow

Scoring of recorded activity followed by a monthly goal-setting and weekly progress cadence described in the source document.

<a id="workflow"></a>
## Documented workflow



1. Apply the configured scorecards to the relevant activity.
2. Review patterns in meeting effectiveness, execution and foundational skills.
3. Prepare a small set of candidate focus areas with supporting evidence.
4. Have the manager select, edit or replace the proposed goal.
5. Track weekly progress against the chosen goal.
6. Review the completed cycle before starting the next one.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Call, meeting and deal scoring
- A monthly per-rep review
- Recommended focus areas and a manager-approved goal
- Weekly progress and supporting examples

<a id="actions-and-review"></a>
## Actions and human review

The source states that the manager reviews the recommendation before it reaches the rep. This is a documented behavioral boundary; the production approval interface and authorized reviewers still need verification.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- Coaching goals should connect to observed work and outcomes.
- Scoring and the coaching cadence are distinct from merely recording calls.
- An evidence-volume threshold is needed before treating patterns as representative.
- The source leaves BDR scope and some team-level reporting unresolved.

<a id="coaching-dimensions"></a>
### Scoring dimensions



| Dimension | What the internal reference assesses |
| --- | --- |
| Pipeline coverage | Activity and funnel context relative to the rep’s goal |
| Deal execution | Qualification, stakeholders and next-step discipline |
| Meeting effectiveness | Discovery, positioning, objection handling and follow-through |
| Foundational skills | Listening, questioning, relating, positioning and checking |

<a id="scorecard-library"></a>
### Scorecard library

The internal reference names deal, customer, meeting and call scorecards: enterprise, mid-market, SMB and upsell opportunities; customer retention; discovery, demo, POC/pilot review and QBR meetings; qualification and follow-up calls. The current catalog and edit permissions still need confirmation.

<a id="collaboration"></a>
## How it works with other agents

Content Curator supplies relevant examples; Deal Driver supplies current pipeline context; Oliver provides process standards. Coach uses those inputs for development rather than owning every adjacent workflow.

<a id="boundaries"></a>
## Scope and limitations

Coach is not a legal-compliance assessment or a replacement for the manager-rep relationship. The source’s numerical examples are illustrations, not independently measured customer outcomes.

<a id="verify"></a>
## Questions to resolve before publication



- What is the current minimum activity volume for each motion?
- Which scorecards and criteria are configurable?
- Which roles can approve or override a goal?
- Are team-level trend reports supported today?
- How are scoring corrections reflected in later progress reports?

<a id="related"></a>
## Related documentation



- [coaching](../workflows/coaching.md)
- [enable](../apps/enable.md)
- [content curator](content-curator.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Configure coaching scorecards](coach/scorecards.md)
- [Review and approve a monthly coaching goal](coach/monthly-goals.md)
- [Review weekly coaching progress](coach/weekly-progress.md)
- [Review manager and leadership coaching views](coach/manager-visibility.md)
- [Set up Coach](coach/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Configure coaching scorecards](coach/scorecards.md)
- [Review and approve a monthly coaching goal](coach/monthly-goals.md)
- [Review weekly coaching progress](coach/weekly-progress.md)
- [Review manager and leadership coaching views](coach/manager-visibility.md)
- [Set up Coach](coach/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/coach: [Coach – AI Sales Coaching Agent | Oliv AI](https://oliv.ai/agents/coach)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
