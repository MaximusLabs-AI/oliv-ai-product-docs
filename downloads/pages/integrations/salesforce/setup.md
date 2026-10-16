---
title: "Set up Salesforce"
url: "/integrations/salesforce/setup/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Set up Salesforce

*V1 review draft · 2026-10-16 · Source-described scope; confirm workspace availability*

<a id="overview"></a>
## Overview

Review Salesforce setup using a verified connector contract and representative data.

<a id="scope"></a>
## Connection scope

Account, contact, opportunity and field context. Verify supported object permissions and write scopes.

<a id="procedure"></a>
## Procedure



1. Confirm entitlement and have the source-system administrator approve the requested access.
2. Use the supported integration entry point in the current Oliv workspace. Do not follow an old UI label without checking it.
3. Review the granted scopes and connected identity before completing authorization.
4. Inspect a representative source record or eligible meeting and verify it appears under the correct account and user.
5. Keep external writes review-required until mapping and access have passed acceptance.

<a id="acceptance"></a>
## Acceptance evidence



- Source identity and approved permission scopes.
- A permitted item with the correct account, user and timestamp.
- A restricted or ineligible item that remains unavailable.
- Confirmed downstream state for any approved write.

<a id="limits"></a>
## Known documentation limits

The supplied Help references mix current recording guidance with older integration UI. This task describes the acceptance sequence; it does not invent unverified button names or promise every object and field is supported.

<a id="references"></a>
## Related references



- [Salesforce integration](../salesforce.md)
- [CRM automation and quality reference](../../features/crm-automation.md)
- [Integration and sync issues](../../troubleshooting/integrations.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:4940626: [Install Oliv's Salesforce Integration](https://help.oliv.ai/en/articles/4940626-install-oliv-s-salesforce-integration)
- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
