---
title: "Review and apply CRM updates"
url: "/workflows/crm-updates/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Review and apply CRM updates

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Use a source conversation to understand a proposed record change, review it under the configured policy and verify the written result.

<a id="before-you-start"></a>
## Before you start



- A supported CRM connection with the required object permissions.
- A known mapping for the target field.
- Correct activity-to-record association.
- A verified review or automatic-update policy.

<a id="steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Open the relevant record and identify the source activity.
2. Review the proposed value and the evidence behind it.
3. Check the field type, destination object and whether newer human edits conflict.
4. Approve, edit or reject through the actual supported review flow.
5. Confirm the final value in the CRM and retain the available change evidence.

<a id="result"></a>
## Expected result

The intended result is a correctly associated, supported field or record update. A proposed value, a queued write and a CRM-accepted change are different states.

<a id="exceptions"></a>
## Variations and exceptions

Expired authorization, read-only fields, validation rules, conflicting edits and ambiguous records can prevent a write. Do not solve these by broadening permissions or merging records without the responsible owner’s decision.

<a id="acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Test a standard field and a customer-specific mapped field.
- Reject one proposed change and confirm no write occurs.
- Compare the acting identity in the CRM with the agreed connector identity.
- Observe a validation failure and the actual retry/support behavior.
- Confirm the correction or recovery path for an incorrect update.

<a id="related"></a>
## Related references



- [crm manager](../agents/crm-manager.md)
- [salesforce](../integrations/salesforce.md)
- [hubspot](../integrations/hubspot.md)
- [approvals](../administration/approvals.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9936748: [Step-by-Step Guide: How to capture Oliv data as fields in HubSpot by creating custom fields ?](https://help.oliv.ai/en/articles/9936748-step-by-step-guide-how-to-capture-oliv-data-as-fields-in-hubspot-by-creating-custom-fields)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
