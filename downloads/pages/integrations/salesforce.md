---
title: "Salesforce integration"
url: "/integrations/salesforce/"
version: "1.1-expanded"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Salesforce integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Use Salesforce account, contact and opportunity context and apply supported CRM updates.

<a id="supported-purpose"></a>
## Purpose and available evidence

The dated Help Center describes an administrator connection and managed-package installation, followed by coordination with Oliv. The agent material describes account/contact maintenance, activity and task context, and standard, methodology and custom field updates.

<a id="data-direction"></a>
## Data direction and permissions

The intended workflow reads CRM context and can write supported updates. The exact object, field and permission matrix is not available in the current sources.

<a id="setup"></a>
## Setup prerequisites

Obtain the current installation link and package version from the implementation owner. Confirm the installing role and organization policy; do not treat the older article’s package link or broad installation setting as a current default.

<a id="disconnect"></a>
## Disconnect and retained data

The dated guide directs removal requests through Oliv support. Verify the current disconnect procedure, token revocation and effect on retained data.

<a id="connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which objects, custom objects and associations are supported?
- Which Salesforce identity performs each write?
- How do validation rules, duplicate rules and field-level security affect updates?
- How are conflicts with human edits resolved?
- What are the API consumption and retry rules?
- Which package and scopes are current?

<a id="verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="connector-contract"></a>
## Connector contract to verify

Account, contact, opportunity and field context. Verify supported object permissions and write scopes.

| Contract field | Required confirmation |
| --- | --- |
| Owner | CRM administrator |
| Authentication | Current authorization method, granted scopes and service or user identity |
| Data direction | Read, proposed write, executed write and unsupported operations |
| Coverage | Exact objects, fields, meeting conditions or channels |
| Freshness | Refresh timing, backfill and behavior after upstream changes |
| Lifecycle | Token expiry, revocation, disconnection and retained data |

<a id="explore"></a>
## Explore

- [Set up Salesforce](salesforce/setup.md)
- [Salesforce data and permissions](salesforce/data-and-permissions.md)
- [Salesforce sync and recovery](salesforce/recovery.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:4940626: [Install Oliv's Salesforce Integration](https://help.oliv.ai/en/articles/4940626-install-oliv-s-salesforce-integration)
- REVIEW:agents: Supplied original Oliv agent references — authored review basis
