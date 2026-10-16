---
title: "Agent output and execution issues"
url: "/troubleshooting/agents/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Agent output and execution issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

An incorrect answer, an unstarted run and an unperformed action are distinct failures.

<a id="agent-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| Output lacks context | Source coverage, access and correct account/opportunity |
| Recommendation conflicts with policy | Current playbook rule, exception and effective date |
| Configuration appears lost | Verified production save/persistence behavior |
| Action did not execute | Availability, trigger, permission and approval state |
| Duplicate or unexpected action | Concurrent events, retry behavior and ownership |
| No failure details | Available run evidence and support correlation path |

<a id="prototype-warning"></a>
## Prototype evidence is not a production incident

The source kit explicitly describes a frontend prototype with nonfunctional actions and local-state settings. Seeing that behavior in its files does not establish the behavior of the live customer product.

Use a running environment or a current implementation specification to confirm the issue and the recovery path.

<a id="output-review"></a>
## Recommended output review

Check the source facts, association, relevant process rule, requested job and destination independently. Correcting a factual input may not correct an ownership or policy error.

For consequential output, preserve the proposed result and the observed external-system state. Do not infer that an action happened because a feed row says it did in demonstration data.

<a id="agent-escalation"></a>
## Escalate with



- Agent and initiating request or event.
- Input record and relevant source evidence.
- Expected and observed output.
- Approval or configuration state.
- Destination result and any error.
- Whether an earlier attempt may already have succeeded.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


