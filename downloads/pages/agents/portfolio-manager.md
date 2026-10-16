---
title: "Portfolio Manager agent"
url: "/agents/portfolio-manager/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Portfolio Manager agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Portfolio Manager assembles account-health context, renewal risk and portfolio priorities so the CS organization can decide where to act.

<a id="purpose"></a>
## Purpose and audience

Portfolio Manager assembles account-health context, renewal risk and portfolio priorities so the CS organization can decide where to act.

Primary audience: CSMs, CS managers, CS leaders and RevOps. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Account records and stakeholder relationships
- Customer conversations and engagement
- Usage or support context where connected
- Renewal timing, health standards and account ownership

<a id="trigger"></a>
## What starts the workflow

Changing account signals and scheduled portfolio-review cadences described in the source document.

<a id="workflow"></a>
## Documented workflow



1. Review each account’s health, relationship and renewal context.
2. Identify accounts that need attention and the evidence behind each flag.
3. Prepare a recommended next step for the responsible owner.
4. Assemble per-CSM review preparation and team-level recaps.
5. Use the review to assign interventions and check follow-through.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Account risk and health explanations
- Per-CSM 1:1 preparation
- Team portfolio and renewal summaries
- Account-level coaching context described in the source

<a id="actions-and-review"></a>
## Actions and human review

A health interpretation, a renewal projection and a task or communication are different outputs. Confirm which are persisted or written to connected systems and which require review.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- A risk flag should explain the contributing evidence rather than only a color or score.
- Ownership determines who receives a recommendation.
- Usage and support sources are conditional integrations, not assumed inputs.
- The source leaves parts of the CS role vocabulary and broader agent roster unresolved.

<a id="portfolio-outputs"></a>
### Review outputs



| Output | Documented purpose |
| --- | --- |
| Account alert | Explain a risk and recommend a next step |
| Per-CSM briefing | Prepare the manager’s account review |
| Team recap | Show portfolio health and escalation needs |
| Renewal view | Organize renewal confidence and forward coverage |
| CSM effectiveness view | Surface account-management strengths and development areas |

<a id="portfolio-coaching"></a>
### Account-level effectiveness dimensions

The internal reference names relationship management, value communication, proactive enablement, expansion development and renewal planning. Confirm whether these dimensions are fixed or configurable and which roles may view the evidence.

<a id="collaboration"></a>
## How it works with other agents

CRM Manager maintains supporting records; Gold Digger handles expansion signals and the warm handoff motion; Olivia can coordinate team work. Retention forecasting must be distinguished from sales forecasting.

<a id="boundaries"></a>
## Scope and limitations

Portfolio Manager does not replace a support ticketing system or automatically resolve a customer issue. Avoid claiming complete replacement of a named CS platform without an agreed use-case comparison.

<a id="verify"></a>
## Questions to resolve before publication



- Which account-health criteria and weights are configurable?
- Which usage and support integrations are enabled?
- Who sees each account and portfolio report?
- How are renewal forecast categories defined?
- Which CS agent names are canonical in the current offer?

<a id="related"></a>
## Related documentation



- [retain](../apps/retain.md)
- [customer success](../workflows/customer-success.md)
- [gold digger](gold-digger.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/portfolio-manager: [Portfolio Manager | Oliv AI](https://oliv.ai/agents/portfolio-manager)
