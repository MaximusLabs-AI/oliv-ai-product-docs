---
title: "Integrations"
url: "/integrations/"
version: "1.0"
status: partial
source_checked: 2026-10-16
product_owner_approved: false
---

# Integrations

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

An integration reference must explain its job, authentication, scope, data direction, setup, failure behavior and removal. A logo alone cannot supply those details.

<a id="integration-types"></a>
## Types of integration



| Type | Examples | Main questions |
| --- | --- | --- |
| CRM | Salesforce, HubSpot | Objects, fields, write identity and sync conflicts |
| Calendar | Google and Microsoft calendars | Meeting coverage, organizer and attendee access |
| Recording | Zoom, Teams and Meet workflows | Native setup, visible note taker and recording permissions |
| Collaboration | Slack and Teams | Destinations, app permissions and message controls |
| Email and outreach | Connected mailboxes and channels | Read scope, drafts, sending and stop rules |
| Additional business context | Usage, support and enrichment sources | Events, association and historical coverage |

<a id="support-levels"></a>
## Read support levels correctly

This V1 distinguishes a working setup described by a dated help article, a current marketed integration and a vendor named only in a picker or example. None of those establishes a fresh end-to-end test for your workspace.

The current website’s broad integration count is not used as a connector-by-connector support matrix. Each connector still needs its own verified data and permission contract.

<a id="integration-contract"></a>
## Required connector contract



- Authentication method and installing role.
- Read and write scopes, object types and field restrictions.
- Sync direction, cadence and source-of-truth rule.
- Historical import and refresh behavior.
- Rate limits, errors, retries and duplicate handling.
- Disconnect procedure and retained-data behavior.
- Plan, add-on and credit implications.

<a id="explore"></a>
## Explore

- [Salesforce integration](integrations/salesforce.md)
- [HubSpot integration](integrations/hubspot.md)
- [Zoom integration](integrations/zoom.md)
- [Microsoft Teams integration](integrations/microsoft-teams.md)
- [Google Meet integration](integrations/google-meet.md)
- [Slack integration](integrations/slack.md)
- [Outlook and Microsoft 365 integration](integrations/outlook.md)
- [Google Calendar and Gmail integration](integrations/google-calendar.md)
- [Other integrations and channels](integrations/other-systems.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
