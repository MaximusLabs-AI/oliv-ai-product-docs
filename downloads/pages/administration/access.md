---
title: "Access and permissions"
url: "/administration/access/"
version: "1.0"
status: needs-confirmation
source_checked: 2026-10-16
product_owner_approved: false
---

# Access and permissions

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="overview"></a>
## Overview

Access must be explained per action and data scope. A persona label such as manager or CSM is not sufficient to define permission.

<a id="access-dimensions"></a>
## Access dimensions



| Dimension | Questions to answer |
| --- | --- |
| Application role | Who invites users and administers configuration? |
| Team/record scope | Which accounts, opportunities and conversations can the user see? |
| Source permission | Does access follow the connected system? |
| Configuration permission | Who changes instructions, schedules, tools and playbooks? |
| Action permission | Who can draft, approve, write, send, delete or merge? |
| External identity | Which account or service identity performs the action? |
| Auditability | What evidence records access or a configuration change? |

<a id="role-matrix"></a>
## Production role matrix remains open

The internal agent documents describe contributor, manager and admin-oriented workflows. They do not supply a complete enforced role matrix. The October prototype extraction explicitly cannot settle production permissions.

Before publishing end-user instructions, obtain the current role names and allowed actions. Do not convert ‘anyone can reach this prototype control’ into a statement about a customer workspace.

<a id="access-tests"></a>
## Recommended access checks



- A user outside a team cannot retrieve that team’s restricted records.
- A viewer cannot enable a write or change an approval policy without authorization.
- A restricted source recording cannot be exposed through a shared clip or agent answer.
- An offboarded user loses the relevant access and action identity.
- A service connection does not exceed its approved object or mailbox scope.

<a id="access-limits"></a>
## Unresolved specifics

SSO, SCIM, custom roles, permission inheritance, guest access, impersonation and complete audit coverage require approved production documentation. Their absence from the reviewed source is not a claim that the live product lacks them.

<a id="sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


