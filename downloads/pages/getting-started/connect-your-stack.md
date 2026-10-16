---
title: "Connect your revenue stack"
url: "/getting-started/connect-your-stack/"
version: "1.0"
status: documented
source_checked: 2026-10-16
product_owner_approved: false
---

# Connect your revenue stack

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Connections serve different purposes: some provide context, some receive notifications, and others allow an agent to write or send information.

<a id="connection-map"></a>
## Map connections to the workflow



| Connection | Typical purpose | Check |
| --- | --- | --- |
| CRM | Account, contact, opportunity and field context | Read/write scope, object coverage and record ownership |
| Calendar | Meeting identification and scheduling context | Connected calendars, organizer identity and attendee visibility |
| Meeting platform or recorder | Recordings and transcripts | Recording mode, consent and access to historical recordings |
| Email | Conversation context and drafts or sending | Mailbox identity, delegated access and send approval |
| Slack or Teams | Briefs, alerts and collaboration | Channel or user destinations and app permissions |
| Usage/support sources | Customer-health and expansion context | Available events, account association and sync cadence |

<a id="connection-prerequisites"></a>
## Before connecting

Confirm that the installing user has the required organization permissions. A personal account connection and an organization-level administrative integration can expose different data. Select the smallest scope that satisfies the workflow.

Confirm the exact connector documentation and approved installation link for the current environment. The Help Center includes older web.oliv.ai routes; the current marketing navigation also uses my.oliv.ai. This V1 does not redirect users into an assumed login or installation flow.

<a id="connection-verification"></a>
## Verify the connection

After installation, check a known record or meeting. Confirm that source ownership, timestamps and associations appear as expected, then test the downstream task. A logo or listed vendor is not evidence that a connector is installed or authorized for that workspace.

Record how to revoke the connection and what happens to already imported data. If removal requires Oliv support, make that dependency explicit in the runbook.

- [Integration reference](../integrations.md)
- [Troubleshoot integrations](../troubleshooting/integrations.md)

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
