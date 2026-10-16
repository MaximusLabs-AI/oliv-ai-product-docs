---
title: "CRM Manager agent"
url: "/agents/crm-manager/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# CRM Manager agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

CRM Manager applies revenue context to CRM records, keeping account, contact, opportunity, activity and task information current within the configured workflow.

<a id="purpose"></a>
## Purpose and audience

CRM Manager applies revenue context to CRM records, keeping account, contact, opportunity, activity and task information current within the configured workflow.

Primary audience: RevOps, sellers and customer-facing teams. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Connected CRM objects and fields
- Interpretations from the conversation and deal-intelligence layer
- Current qualification and field-mapping rules
- New activity or a requested historical cleanup

<a id="trigger"></a>
## What starts the workflow

New meetings, calls or email activity for ongoing updates; the internal document also describes direct commands for retrospective cleanup and backfill jobs.

<a id="workflow"></a>
## Documented workflow



1. Identify the relevant CRM record and the evidence from connected activity.
2. Determine the fields or records affected by the new information.
3. Prepare proposed values and the reasoning or source moment behind them.
4. Apply the workspace’s verified review or automatic-update policy.
5. Write through the supported connector and expose the resulting record state.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Proposed or applied CRM updates
- Created or enriched records where supported
- Activity and task information
- Review prompts and RevOps reporting described in the source

<a id="actions-and-review"></a>
## Actions and human review

The documentation describes standard, qualification-methodology and customer-specific fields. Actual object coverage, writable fields, connector identity and update conflicts require an implementation-specific mapping.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- The source describes Ask First and Auto-Pilot control modes.
- A customer-specific field must be mapped before it can be reliably populated.
- Record association and duplicate merging are separate operations.
- The source leaves duplicate-resolution thresholds unresolved.

<a id="crm-object-scope"></a>
### Record categories described in the source

The internal reference distinguishes account/contact management, opportunity creation and tracking, activity tracking, task tracking and field population. Verify the supported operations per connector rather than assuming identical coverage across CRMs.

| Field category | Source-described purpose |
| --- | --- |
| Standard fields | Core opportunity and record information |
| Methodology fields | Qualification evidence such as MEDDPICC or the customer’s framework |
| Customer-specific fields | Values unique to the organization’s process, mapped during implementation |

<a id="crm-update-evidence"></a>
### Proposed-update evidence

The source describes showing the reasoning and the conversation moment behind an update, along with review prompts and field-change history. Those are distinct from a complete compliance audit log. Confirm which history is retained and visible in the current product.

<a id="collaboration"></a>
## How it works with other agents

Conversation and deal intelligence produce the interpretation; CRM Manager applies the resulting information. Forecaster, Deal Driver, Coach and customer-success workflows then depend on that record context.

<a id="boundaries"></a>
## Scope and limitations

CRM Manager complements an existing CRM. It is not the CRM itself and should not be described as the source of every underlying inference or as a reporting replacement.

<a id="verify"></a>
## Questions to resolve before publication



- Which objects and custom fields are supported for each connector?
- Which user or service identity performs writes?
- How are simultaneous human and agent edits resolved?
- Can a user reject, undo or recover an applied update?
- Which duplicate cases are merged automatically, if any?
- What happens when authorization expires or a write fails?

<a id="related"></a>
## Related documentation



- [crm updates](../workflows/crm-updates.md)
- [salesforce](../integrations/salesforce.md)
- [hubspot](../integrations/hubspot.md)
- [approvals](../administration/approvals.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Choose CRM review and execution modes](crm-manager/operating-modes.md)
- [Review account and contact changes](crm-manager/accounts-contacts.md)
- [Review opportunity creation and tracking](crm-manager/opportunities.md)
- [Review activity and task logging](crm-manager/activity-task-logging.md)
- [Map standard, methodology and custom fields](crm-manager/field-mapping.md)
- [Accept, edit or reject a proposed CRM update](crm-manager/proposed-updates.md)
- [Plan a retrospective data-quality job](crm-manager/batch-quality.md)
- [Set up CRM Manager](crm-manager/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Choose CRM review and execution modes](crm-manager/operating-modes.md)
- [Review account and contact changes](crm-manager/accounts-contacts.md)
- [Review opportunity creation and tracking](crm-manager/opportunities.md)
- [Review activity and task logging](crm-manager/activity-task-logging.md)
- [Map standard, methodology and custom fields](crm-manager/field-mapping.md)
- [Accept, edit or reject a proposed CRM update](crm-manager/proposed-updates.md)
- [Plan a retrospective data-quality job](crm-manager/batch-quality.md)
- [Set up CRM Manager](crm-manager/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
