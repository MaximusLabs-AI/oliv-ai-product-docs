---
title: "Data lifecycle, export and deletion"
url: "/administration/data-lifecycle/"
version: "1.1-expanded"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Data lifecycle, export and deletion

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

A lifecycle reference should explain the state of each data object and what happens to related artifacts when a user changes access or deletes data.

<a id="lifecycle-events"></a>
## Lifecycle events are different



| Event | Do not assume |
| --- | --- |
| Disconnect a source | All previously imported data is deleted |
| Deactivate a user/account | All associated content is erased |
| Delete an account | Every copy, backup and derived artifact disappears immediately |
| Clear a feed item | The underlying run or evidence is deleted |
| Remove a clip | The source recording is deleted |
| Export | Every object and historical artifact is included |

<a id="documented-account-flow"></a>
## Existing account guidance

The October 2024 Help Center article distinguishes deactivation and deletion through profile settings. Treat that as a dated procedure requiring current UI and lifecycle verification.

It does not establish the full retention schedule, backup policy, derived-data removal, organization-level deletion authority or contractual export scope.

<a id="lifecycle-contract"></a>
## Lifecycle contract to confirm



- Each retained object and its owner.
- Retention period and configurable options.
- Access after user offboarding or connector revocation.
- Deletion request, authorization and completion state.
- Treatment of transcripts, clips, signals, agent outputs, logs and backups.
- Export formats, coverage, delivery and limitations.
- Any legal or contractual retention exception.

<a id="lifecycle-check"></a>
## Recommended acceptance check

Use a controlled record and identify its related artifacts before changing access or requesting deletion. Verify the documented result at each relevant destination. Do not perform deletion tests on production customer data merely to complete this documentation.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9179977: [How to Deactivate / Delete your Oliv account](https://help.oliv.ai/en/articles/9179977-how-to-deactivate-delete-your-oliv-account)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
