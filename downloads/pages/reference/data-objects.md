---
title: "Data objects and artifacts"
url: "/reference/data-objects/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Data objects and artifacts

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

The available sources name business entities, source activities, interpretations and agent outputs. Those categories should remain distinct.

<a id="object-map"></a>
## Object map



| Object or artifact | Meaning |
| --- | --- |
| Account/company | The business entity in the customer relationship |
| Contact/stakeholder | A person and their role or relationship |
| Opportunity/deal | A specific commercial motion at an account |
| Meeting/call | A source activity and its participants/time |
| Recording/transcript | Captured content used as evidence |
| Clip | A selected portion of a source recording |
| Signal | An interpretation of relevant evidence |
| Playbook entry | Company process knowledge or a rule |
| Agent run | An attempt to perform a defined job |
| Draft/proposed update | An output that is not necessarily sent or applied |
| Forecast submission/snapshot | A period-specific record used for review |

<a id="identifiers"></a>
## Identifiers and relationships

Document stable identifiers and relationships in the final schema reference: which opportunity an activity concerns, which recording a clip references and which source supports a proposed change.

The frontend prototype’s sample data does not supply production field types, required values, keys, API schemas or persistence guarantees. Those remain engineering inputs.

<a id="data-lifecycle"></a>
## Lifecycle and history

Creation, modification, deletion and retention can differ by artifact. A correction to a source or association may affect a later signal without changing a historical snapshot.

Use the lifecycle reference to identify the expected state of each artifact after offboarding, source revocation or deletion.

- [Data lifecycle](../administration/data-lifecycle.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


