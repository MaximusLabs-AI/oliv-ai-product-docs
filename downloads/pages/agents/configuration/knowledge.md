---
title: "Knowledge and data access"
url: "/agents/configuration/knowledge/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Knowledge and data access

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

An agent’s context can include organization process knowledge, source records and task-specific supporting material. Uploading a file and authorizing a connector are different operations.

<a id="knowledge-types"></a>
## Types of context



| Context | Purpose |
| --- | --- |
| Organization playbook | Approved operating rules, methodology and exceptions |
| Task-specific knowledge | Relevant supporting material for a particular job |
| Connected records | Accounts, contacts, opportunities and activity |
| Conversation evidence | Recordings, transcripts, email and messages within authorized scope |

<a id="source-controls"></a>
## Source and access controls

Confirm who may add, replace or remove knowledge, whether access follows the source system, and whether individual or team information can be exposed to other users.

The prototype lists import sources and accepted upload formats, but several import actions have no working behavior. A named source is not a confirmed connector; a prototype file-count label is not a commercial storage limit.

<a id="knowledge-lifecycle"></a>
## Lifecycle and updates

Document when changed knowledge becomes available to an agent, how obsolete content is replaced, what is retained after removal and whether historical outputs continue to cite the prior version.

Treat source provenance as part of the workflow. A current rule and an obsolete document can both be retrievable; the product owner must establish how conflicting or superseded material is handled.

<a id="knowledge-verification"></a>
## Recommended verification

Use a controlled document with a distinct fact, update that fact, and check subsequent answers and actions. Remove access and verify that the relevant user and agent cannot continue to retrieve restricted content.

Do not claim organization-wide knowledge isolation, automatic deletion from every derived store or a fixed refresh SLA from the current materials.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- REVIEW:agents: Supplied original Oliv agent references — authored review basis
