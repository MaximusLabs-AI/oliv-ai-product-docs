---
title: "Agent configuration"
url: "/agents/configuration/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Agent configuration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Configuration determines what an agent may know, what starts its work and what actions it may take. The available sources describe several controls but do not establish every production rule.

<a id="configuration-parts"></a>
## Configuration areas



| Area | What it controls | Reference |
| --- | --- | --- |
| Instructions and process | The job and applicable rules | Process Graph and agent reference |
| Tools and approvals | Available actions and review requirements | Action boundaries |
| Triggers and schedules | Events or cadences that initiate work | Triggers and schedules |
| Knowledge and data | Supporting documents and source access | Knowledge and data |
| Run history | Evidence of attempted and completed work | Run history |

<a id="configuration-source"></a>
## Prototype versus production

The October extraction describes a prototype where several selections exist only for the visit and some action buttons have no implementation. That is useful UI evidence, but it cannot establish persistence, permission enforcement or a working execution path.

Use these references to define what must be checked in the current workspace. Do not promote a selector option into a production guarantee merely because it is visible in the prototype.

<a id="explore"></a>
## Explore

- [Tool modes and action boundaries](configuration/approvals.md)
- [Triggers and schedules](configuration/triggers.md)
- [Knowledge and data access](configuration/knowledge.md)
- [Run history and outputs](configuration/run-history.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


