---
title: "Context Graph"
url: "/platform/context-graph/"
version: "1.1-expanded"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Context Graph

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Context Graph is the relationship layer that places customer activity against the business entities it concerns.

<a id="associations"></a>
## What the graph connects

The public product description associates conversations and activities with accounts, contacts and opportunities, using relationship history and conversation context rather than only an email-domain match.

A useful activity association should preserve a path back to its source. Review the account, the particular opportunity and the participants before allowing an agent’s interpretation to affect a customer record.

<a id="ambiguous-cases"></a>
## Cases that need careful review



| Situation | What to verify |
| --- | --- |
| Several open opportunities at one company | The activity belongs to the right product, motion and buying group |
| A partner call mentions several customer accounts | Each discussed customer is associated appropriately |
| An acquisition changes the email domain | The relationship to the prior entity remains understandable |
| Duplicate or stale CRM accounts | The active record is identified without unsafe merging |
| Several deals discussed in one meeting | Shared activity does not overwrite unrelated opportunity state |

<a id="association-vs-cleanup"></a>
## Association and CRM cleanup are separate decisions

Choosing the likely opportunity for an activity is not the same as authorizing a destructive CRM merge. The CRM Manager document explicitly leaves duplicate-resolution thresholds unresolved.

Verify the current review and correction path for an incorrect association. This V1 does not claim a confidence threshold, automatic merge policy or guaranteed perfect mapping.

<a id="association-acceptance"></a>
## Recommended acceptance criteria

Use examples of multiple opportunities, duplicates and changed domains in the first deployment review. Require an explanation of the selected record, source evidence and a way to correct an incorrect association.

Document whether a correction changes only the current activity or also related historical associations. That behavior is not established by the available sources.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/context-graph: [Context Graph – Every Signal, Mapped | Oliv AI](https://oliv.ai/context-graph)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
