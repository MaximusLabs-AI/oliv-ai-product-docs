---
title: "HubSpot integration"
url: "/integrations/hubspot/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# HubSpot integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Use HubSpot company, contact and deal context and populate mapped fields through the supported connection.

<a id="supported-purpose"></a>
## Purpose and available evidence

The dated integration guide describes connecting HubSpot and coordinating with Oliv. A separate September 2024 article describes creating a deal property and adding it to the deal view for captured Oliv information.

<a id="data-direction"></a>
## Data direction and permissions

Reading CRM context and writing mapped values are described. Exact object coverage, property types, associations and conflict rules require a current mapping reference.

<a id="setup"></a>
## Setup prerequisites

Confirm the installing user, requested scopes and the properties Oliv expects. The older guide recommends rich-text properties for its example; that is not a universal type rule for every field or current HubSpot account.

<a id="disconnect"></a>
## Disconnect and retained data

The dated integration article routes removal through support. Verify the current process and whether existing values, source links or historical data remain.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which deal, company and contact properties are supported?
- Are custom objects and multiple associations supported?
- Which property types and enumerations are writable?
- What maps an activity to the correct deal?
- How are failed validations and concurrent updates handled?
- Which updates need human review?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8671280: [Oliv <> HubSpot Integrations](https://help.oliv.ai/en/articles/8671280-oliv-hubspot-integrations)
- HELP:9936748: [Step-by-Step Guide: How to capture Oliv data as fields in HubSpot by creating custom fields ?](https://help.oliv.ai/en/articles/9936748-step-by-step-guide-how-to-capture-oliv-data-as-fields-in-hubspot-by-creating-custom-fields)
