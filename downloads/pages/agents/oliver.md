---
title: "Oliver agent"
url: "/agents/oliver/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Oliver agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Oliver helps maintain the company’s revenue playbook and the configuration context that other agents use.

<a id="purpose"></a>
## Purpose and audience

Oliver helps maintain the company’s revenue playbook and the configuration context that other agents use.

Primary audience: RevOps, revenue leaders and process owners. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Current ICP, personas and territory rules
- Qualification methodologies and stage requirements
- Approval policies, ownership rules and exceptions
- Process feedback from leaders and observed work

<a id="trigger"></a>
## What starts the workflow

A process setup or update conversation, or a proposed improvement surfaced for review. The source describes ongoing maintenance rather than a one-time handbook upload.

<a id="workflow"></a>
## Documented workflow



1. Collect the current process and identify its accountable owners.
2. Translate the process into structured, linked handbook knowledge.
3. Identify the affected configuration or dependent agent behavior.
4. Prepare a proposed change and route it for the required human sign-off.
5. Apply the approved change through the verified workflow and check its effects.

<a id="outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A maintained company process handbook
- Proposed process or configuration updates
- Aligned context for specialist agents
- Questions about contradictions or exceptions

<a id="actions-and-review"></a>
## Actions and human review

The source describes playbook, schema and configuration work. It does not establish arbitrary administrative access or an unrestricted right to change customer systems.

<a id="action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="rules"></a>
## Rules and configuration



- The internal source says handbook updates require human sign-off.
- Keep actual operating policy distinct from a proposed improvement.
- A process change can affect more than one agent; scope and propagation must be explicit.

<a id="handbook-structure"></a>
### Playbook subject areas

The sources organize operating knowledge across market and ICP, personas, competitors and proof, prospecting, qualification, commercial work, handoffs, onboarding, account health, renewals and expansion. Cross-links should preserve which rule governs which job.

<a id="process-change-scope"></a>
### Change scope

A proposed ICP or methodology change can affect several agents and data fields. The reviewer should identify the affected teams, rules and dependent workflows before approval. The available sources do not establish the production versioning or rollback mechanism.

<a id="collaboration"></a>
## How it works with other agents

CRM Manager writes the fields that the process says to track; Coach evaluates work against the agreed standards; Forecaster interprets stage and forecast criteria; Olivia coordinates frontline execution inside that context.

<a id="boundaries"></a>
## Scope and limitations

Oliver is not the opportunity-level assistant, CRM writer or coaching agent. Its job is the process and configuration context those workflows depend on.

<a id="verify"></a>
## Questions to resolve before publication



- Who may approve a handbook or schema change?
- Where is the approval request displayed and recorded?
- Can different teams or regions have different rules?
- When do dependent agents adopt an approved change?
- How are versions, rollback and in-flight work handled?

<a id="related"></a>
## Related documentation



- [process graph](../platform/process-graph.md)
- [approvals](../administration/approvals.md)
- [olivia](olivia.md)

<a id="operational-guides"></a>
## Detailed operational guides



- [Build the revenue process handbook](oliver/handbook.md)
- [Review schema and field configuration](oliver/schema.md)
- [Define process boundaries and exceptions](oliver/boundaries.md)
- [Review and approve handbook evolution](oliver/change-review.md)
- [Set up Oliver](oliver/setup.md)

<a id="source-boundary"></a>
## Availability and validation

These guides explain the supplied agent reference in operational terms. They do not establish that every described control is shipped or included in every plan. Open questions remain visible in each task.

<a id="explore"></a>
## Explore

- [Build the revenue process handbook](oliver/handbook.md)
- [Review schema and field configuration](oliver/schema.md)
- [Define process boundaries and exceptions](oliver/boundaries.md)
- [Review and approve handbook evolution](oliver/change-review.md)
- [Set up Oliver](oliver/setup.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
