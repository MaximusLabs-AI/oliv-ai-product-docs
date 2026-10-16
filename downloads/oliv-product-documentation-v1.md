# Oliv AI Product Documentation — V1

Public V1 review preview. Source check: 2026-10-16. Product availability and owner approval remain distinct.

## Contents

- [Oliv AI product documentation](#document-home)
- [Getting started](#document-getting-started)
- [Plan your first deployment](#document-getting-started-implementation)
- [Connect your revenue stack](#document-getting-started-connect-your-stack)
- [Run a first workflow](#document-getting-started-first-workflow)
- [Who uses Oliv](#document-getting-started-roles)
- [Platform concepts](#document-platform)
- [Context Capture](#document-platform-context-capture)
- [Context Graph](#document-platform-context-graph)
- [Signal Graph](#document-platform-signal-graph)
- [Process Graph](#document-platform-process-graph)
- [Agent execution and coordination](#document-platform-agent-harness)
- [Agents](#document-agents)
- [Olivia agent](#document-agents-olivia)
- [Oliver agent](#document-agents-oliver)
- [CRM Manager agent](#document-agents-crm-manager)
- [Deal Driver agent](#document-agents-deal-driver)
- [Forecaster agent](#document-agents-forecaster)
- [Meeting Assistant agent](#document-agents-meeting-assistant)
- [Coach agent](#document-agents-coach)
- [Content Curator agent](#document-agents-content-curator)
- [Portfolio Manager agent](#document-agents-portfolio-manager)
- [Gold Digger agent](#document-agents-gold-digger)
- [Researcher agent](#document-agents-researcher)
- [Prospector agent](#document-agents-prospector)
- [Marketplace and agent naming](#document-agents-marketplace)
- [Agent configuration](#document-agents-configuration)
- [Tool modes and action boundaries](#document-agents-configuration-approvals)
- [Triggers and schedules](#document-agents-configuration-triggers)
- [Knowledge and data access](#document-agents-configuration-knowledge)
- [Run history and outputs](#document-agents-configuration-run-history)
- [Apps](#document-apps)
- [Converse app](#document-apps-converse)
- [Forecast app](#document-apps-forecast)
- [Engage app](#document-apps-engage)
- [Enable app](#document-apps-enable)
- [Retain app](#document-apps-retain)
- [Workflows](#document-workflows)
- [Prepare and follow up a meeting](#document-workflows-meeting-preparation)
- [Record meetings with Oliv](#document-workflows-meeting-recording)
- [Review and apply CRM updates](#document-workflows-crm-updates)
- [Run a pipeline review](#document-workflows-pipeline-review)
- [Prepare and review a forecast](#document-workflows-forecast-review)
- [Run a coaching cycle](#document-workflows-coaching)
- [Review and hand off an expansion signal](#document-workflows-expansion)
- [Review customer health and renewals](#document-workflows-customer-success)
- [Prepare an account outreach workflow](#document-workflows-prospecting)
- [Integrations](#document-integrations)
- [Salesforce integration](#document-integrations-salesforce)
- [HubSpot integration](#document-integrations-hubspot)
- [Zoom integration](#document-integrations-zoom)
- [Microsoft Teams integration](#document-integrations-microsoft-teams)
- [Google Meet integration](#document-integrations-google-meet)
- [Slack integration](#document-integrations-slack)
- [Outlook and Microsoft 365 integration](#document-integrations-outlook)
- [Google Calendar and Gmail integration](#document-integrations-google-calendar)
- [Other integrations and channels](#document-integrations-other-systems)
- [Documentation by team](#document-teams)
- [Sales Development](#document-teams-sales-development)
- [Sales](#document-teams-sales)
- [Sales Engineering](#document-teams-sales-engineering)
- [Customer Onboarding](#document-teams-onboarding)
- [Customer Success](#document-teams-customer-success)
- [Account Management](#document-teams-account-management)
- [Enablement](#document-teams-enablement)
- [Revenue Operations](#document-teams-revops)
- [Startups and staged adoption](#document-getting-started-startups)
- [Administration](#document-administration)
- [Access and permissions](#document-administration-access)
- [Approval governance](#document-administration-approvals)
- [Security and privacy](#document-administration-security-and-privacy)
- [Data lifecycle, export and deletion](#document-administration-data-lifecycle)
- [Reference](#document-reference)
- [Plans, credits and usage](#document-reference-plans-and-usage)
- [Limits and availability](#document-reference-limits-and-availability)
- [Data objects and artifacts](#document-reference-data-objects)
- [Briefs, reports and cadence](#document-reference-reporting-cadences)
- [API, MCP and developer interfaces](#document-reference-api-and-mcp)
- [Glossary](#document-reference-glossary)
- [Troubleshooting](#document-troubleshooting)
- [Meeting capture and brief issues](#document-troubleshooting-meetings)
- [Integration and sync issues](#document-troubleshooting-integrations)
- [Agent output and execution issues](#document-troubleshooting-agents)
- [Announcements and release notes](#document-announcements)
- [Monthly announcement format](#document-announcements-monthly-format)
- [Documentation history](#document-announcements-documentation-history)
- [V1 review guide](#document-review)
- [Coverage and checklist review](#document-review-coverage)
- [Source register](#document-review-sources)
- [Open questions and claim conflicts](#document-review-questions)
- [Legacy help and naming migration](#document-review-legacy)
- [Documentation contract and publishing](#document-review-documentation-contract)

<a id="document-home"></a>
# Oliv AI product documentation

*V1 review draft · 2026-10-16 · Varies by plan, configured integrations and rollout*

<a id="document-home-overview"></a>
## Overview

Oliv brings customer activity, account context and revenue processes together so agents can help teams prospect, progress deals, serve customers and identify expansion opportunities.

<a id="document-home-what-oliv-does"></a>
## What Oliv does

Oliv works with an existing revenue stack. Conversations and business records become connected account and opportunity context; specialist agents use that context to prepare work, surface changes and carry out configured actions. Salesforce or HubSpot can remain the system of record.

The current product presentation distinguishes three things: the context foundation, agents that perform specific jobs, and apps that organize team workflows. A team can begin with a defined use case rather than replacing its entire stack.

Capture activity → Connect accounts and opportunities → Interpret signals and process → Prepare or execute agent work → Review outcomes in team workflows

*Conceptual model, not a deployment diagram.*

<a id="document-home-choose-a-start"></a>
## Choose your starting point

Start with the job you want to complete. A seller preparing for a meeting needs different setup and evidence from a RevOps leader allowing CRM writes or a CS manager reviewing account health.

- [Plan a first deployment](#document-getting-started-implementation)
- [Explore agents](#document-agents)
- [Understand the platform](#document-platform)
- [Follow a workflow](#document-workflows)
- [Connect your tools](#document-integrations)

<a id="document-home-reading-v1"></a>
## Read this V1 correctly

This is a source-grounded review draft, not a certification that every described capability is available in every workspace. Current public product pages set the naming and presentation; accessible internal agent documents add detail; dated Help Center articles provide setup and support context.

Each page separates documented behavior from unresolved rules. Source publication dates, HTTP retrieval dates and product release dates are different. A source-backed description does not establish a plan entitlement, enforced permission or guaranteed completion time.

- [Review coverage and unresolved claims](#document-review-coverage)
- [Source register](#document-review-sources)

<a id="document-home-explore"></a>
## Explore

- [Getting started](#document-getting-started)
- [Platform concepts](#document-platform)
- [Agents](#document-agents)
- [Apps](#document-apps)
- [Workflows](#document-workflows)
- [Integrations](#document-integrations)
- [Documentation by team](#document-teams)
- [Administration](#document-administration)
- [Reference](#document-reference)
- [Troubleshooting](#document-troubleshooting)
- [Announcements and release notes](#document-announcements)
- [V1 review guide](#document-review)

<a id="document-home-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/)

<a id="document-getting-started"></a>
# Getting started

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-overview"></a>
## Overview

A successful first deployment has a clear owner, a defined input, an observable output and an agreed point where a human reviews the work.

<a id="document-getting-started-first-use-case"></a>
## Start with one outcome

Choose a bounded workflow: prepare opportunity-linked meetings, propose CRM field updates, review pipeline risk or prepare account-health briefs. Establish which records and people are in scope and what success looks like before increasing volume.

<a id="document-getting-started-setup-sequence"></a>
## Recommended setup sequence



1. Confirm the app and agent entitlement for the selected users.
2. Connect the calendar, CRM and conversation sources needed by that workflow.
3. Provide the relevant qualification criteria, ownership rules and process exceptions.
4. Agree review, approval and notification behavior with the implementation owner.
5. Run a small set of representative cases, including an exception or failure, and check the resulting records.

<a id="document-getting-started-scope-check"></a>
## Check the deployment boundary

Setup instructions vary by connector and organization policy. Some public setup copy describes an assisted rollout rather than a fully self-service configuration. Obtain the current connector steps for your environment instead of assuming every named integration uses the same installation path.

<a id="document-getting-started-explore"></a>
## Explore

- [Plan your first deployment](#document-getting-started-implementation)
- [Connect your revenue stack](#document-getting-started-connect-your-stack)
- [Run a first workflow](#document-getting-started-first-workflow)
- [Who uses Oliv](#document-getting-started-roles)
- [Startups and staged adoption](#document-getting-started-startups)

<a id="document-getting-started-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-getting-started-implementation"></a>
# Plan your first deployment

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-implementation-overview"></a>
## Overview

Use the first deployment to establish a dependable operating workflow, not just a visually complete demonstration.

<a id="document-getting-started-implementation-implementation-scope"></a>
## Define the implementation scope

Write down the job, the users, the records in scope, the expected outputs and the integrations that those outputs depend on. For a CRM update workflow, include the object and field categories; for a meeting workflow, include meeting ownership and recording method.

The website offers customer-operated and Oliv-operated implementation paths. Confirm who maintains the process playbook, connector configuration, exception rules and ongoing improvements in the agreed engagement.

| Decision | Record before rollout |
| --- | --- |
| Business owner | Who accepts the output and owns the workflow |
| Technical owner | Who connects systems and resolves permission issues |
| Scope | Users, teams, accounts, opportunities and excluded records |
| Action boundary | Read, draft, write, send and human review points |
| Evidence | What proves a successful run and where it is recorded |

<a id="document-getting-started-implementation-inputs"></a>
## Prepare the inputs

Provide access to the CRM and the relevant calendars, recordings, email or collaboration sources. Identify the current revenue process and qualification framework. A process document should state actual decisions and exceptions, rather than a desired future process.

Where the source is incomplete or contradictory, record the disagreement for the responsible owner. Do not fill the gap with an inferred discount rule, ownership policy or customer communication permission.

<a id="document-getting-started-implementation-acceptance"></a>
## Recommended acceptance checks



1. Use a representative record and verify the correct account, contact and opportunity associations.
2. Check the proposed output against the source conversation and agreed process.
3. Test a case that should require review and verify the actual approval destination.
4. Confirm that a changed setting persists and that the correct user can change it.
5. Disconnect or expire a test integration in a controlled environment and observe the user-visible failure.
6. Record the entitlement, configuration and verified date with the accepted result.

<a id="document-getting-started-implementation-timelines"></a>
## Timelines and dependencies

Public pages describe several setup timelines for different use cases. These are not a single service-level commitment. Connector approval, historical data access, custom process work and customer review can change the schedule.

Use an agreed implementation plan with explicit milestones. This V1 does not promise a universal five-minute setup, same-week deployment or fixed time to value.

<a id="document-getting-started-implementation-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)

<a id="document-getting-started-connect-your-stack"></a>
# Connect your revenue stack

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-connect-your-stack-overview"></a>
## Overview

Connections serve different purposes: some provide context, some receive notifications, and others allow an agent to write or send information.

<a id="document-getting-started-connect-your-stack-connection-map"></a>
## Map connections to the workflow



| Connection | Typical purpose | Check |
| --- | --- | --- |
| CRM | Account, contact, opportunity and field context | Read/write scope, object coverage and record ownership |
| Calendar | Meeting identification and scheduling context | Connected calendars, organizer identity and attendee visibility |
| Meeting platform or recorder | Recordings and transcripts | Recording mode, consent and access to historical recordings |
| Email | Conversation context and drafts or sending | Mailbox identity, delegated access and send approval |
| Slack or Teams | Briefs, alerts and collaboration | Channel or user destinations and app permissions |
| Usage/support sources | Customer-health and expansion context | Available events, account association and sync cadence |

<a id="document-getting-started-connect-your-stack-connection-prerequisites"></a>
## Before connecting

Confirm that the installing user has the required organization permissions. A personal account connection and an organization-level administrative integration can expose different data. Select the smallest scope that satisfies the workflow.

Confirm the exact connector documentation and approved installation link for the current environment. The Help Center includes older web.oliv.ai routes; the current marketing navigation also uses my.oliv.ai. This V1 does not redirect users into an assumed login or installation flow.

<a id="document-getting-started-connect-your-stack-connection-verification"></a>
## Verify the connection

After installation, check a known record or meeting. Confirm that source ownership, timestamps and associations appear as expected, then test the downstream task. A logo or listed vendor is not evidence that a connector is installed or authorized for that workspace.

Record how to revoke the connection and what happens to already imported data. If removal requires Oliv support, make that dependency explicit in the runbook.

- [Integration reference](#document-integrations)
- [Troubleshoot integrations](#document-troubleshooting-integrations)

<a id="document-getting-started-connect-your-stack-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)

<a id="document-getting-started-first-workflow"></a>
# Run a first workflow

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-first-workflow-overview"></a>
## Overview

Begin with a low-volume, identifiable case so the team can explain exactly what happened and why.

<a id="document-getting-started-first-workflow-choose-record"></a>
## Choose a representative case

Select a meeting linked to an active opportunity, a CRM field update with clear evidence, or an account review with known risk signals. Avoid starting with a broad historical cleanup or a large outbound audience.

Identify the expected source data and the person responsible for checking the result. Remove ambiguity about who owns an opportunity or which account a conversation concerns before judging the agent output.

<a id="document-getting-started-first-workflow-review-sequence"></a>
## Recommended first-run sequence



1. Confirm that the selected agent or workflow is enabled for the workspace.
2. Check the source connections and the relevant account or opportunity.
3. Review the applicable process rules and configured action permissions.
4. Trigger the workflow using the verified production mechanism.
5. Inspect the output, source evidence, destination and any approval request.
6. Accept or reject the result through the verified interface and check the resulting state.

<a id="document-getting-started-first-workflow-prototype-boundary"></a>
## Do not use the prototype as an execution guide

The supplied October 15 extraction describes a frontend prototype. It records controls whose actions or persistence were not implemented in that source. Labels such as Run Agent, Clone Agent or Send therefore cannot establish the production procedure.

The current V1 describes the intended workflow and verification requirements. Exact production clicks, error messages and expected save states must be confirmed in a running environment before this page becomes an end-user tutorial.

<a id="document-getting-started-first-workflow-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-getting-started-roles"></a>
# Who uses Oliv

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-roles-overview"></a>
## Overview

Business personas describe who a workflow helps. They do not automatically define application permissions or plan entitlements.

<a id="document-getting-started-roles-persona-map"></a>
## Choose the workflow by job



| Team | Typical jobs | Start with |
| --- | --- | --- |
| Sales development | Prioritize accounts, research contacts, prepare outreach | Prospector and Researcher |
| Account executives | Prepare meetings, follow up and progress opportunities | Olivia, Meeting Assistant and CRM Manager |
| Sales managers | Review deal risk and coach team performance | Deal Driver and Coach |
| Revenue Operations | Maintain process, data quality and forecast configuration | Oliver, CRM Manager and Forecaster |
| Customer Success | Understand account health, renewals and portfolio priorities | Portfolio Manager and Olivia |
| Account Management | Identify and act on expansion signals | Gold Digger and Prospector |
| Enablement | Select coaching goals and distribute useful examples | Coach and Content Curator |
| Sales Engineering and onboarding | Preserve technical context and implementation handoffs | Team-workflow documentation and current catalog |

<a id="document-getting-started-roles-personas-permissions"></a>
## Separate persona, role and entitlement

A page saying an agent is useful for a manager does not prove that only managers can run it. Likewise, a seat group such as Sell or Grow is a commercial grouping, not a verified RBAC role.

For each action, establish who may see source data, configure agents, approve work, write to external systems and administer connections. Use the access reference for the questions that still need an owner decision.

- [Access and permissions](#document-administration-access)

<a id="document-getting-started-roles-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-platform"></a>
# Platform concepts

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-overview"></a>
## Overview

Oliv’s platform story is a sequence from customer activity to connected context and useful action, with process knowledge guiding how agents operate.

<a id="document-platform-foundation-model"></a>
## A conceptual model

Capture brings in the activity. Context Graph associates it with business entities. Signal Graph interprets revenue questions. Process Graph supplies the organization’s rules and exceptions. Agents prepare or execute work using that context; apps organize the related team workflows.

This is a user-level explanation of the current product presentation. It is not a backend deployment diagram, a database schema or a guarantee about internal event ordering.

Activity and records → Context Graph → Signals + process knowledge → Agents → Apps and team outputs

*Conceptual model, not a deployment diagram.*

<a id="document-platform-separate-concepts"></a>
## Keep the concepts distinct

An activity is an input; a signal is an interpretation of that input; a process rule defines how the organization should act; an agent performs a job; an app is a workspace for related work. Keeping those terms separate makes it easier to explain an incorrect result and identify its owner.

<a id="document-platform-explore"></a>
## Explore

- [Context Capture](#document-platform-context-capture)
- [Context Graph](#document-platform-context-graph)
- [Signal Graph](#document-platform-signal-graph)
- [Process Graph](#document-platform-process-graph)
- [Agent execution and coordination](#document-platform-agent-harness)

<a id="document-platform-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/oliv-tech: [Oliv Tech | Oliv AI](https://oliv.ai/oliv-tech)

<a id="document-platform-context-capture"></a>
# Context Capture

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-context-capture-overview"></a>
## Overview

Context Capture brings customer activity into Oliv so teams and agents can work from more than manually entered CRM notes.

<a id="document-platform-context-capture-captured-sources"></a>
## Activity sources

The current website describes meetings, phone calls, email, messages and in-person conversations, alongside connected business records and supporting data. Availability depends on the source, integration, plan and organization configuration.

For each source, distinguish metadata from full content. An event title or call log is not a transcript; a linked email is not necessarily a mailbox-wide archive. Confirm the actual imported fields, access scope and historical coverage.

| Input | Document the boundary |
| --- | --- |
| Online meetings | Organizer, recording mode, consent, transcript and participant access |
| Phone calls | Supported dialer or capture route and recording availability |
| Email | Mailbox scope, included threads, attachments and retention |
| Messaging | Connected workspace/channel scope and supported history |
| In-person activity | Supported capture application/device and upload process |
| CRM and usage/support data | Objects, fields, event coverage and sync direction |

<a id="document-platform-context-capture-recording-conditions"></a>
## Recording has conditions

The May 2026 recording guide distinguishes internally organized meetings from externally organized meetings when native recording is enabled. An external organizer can require a visible note taker and lobby admission.

A claim that Oliv supports botless recording should therefore include the platform and organization prerequisites. Do not describe every meeting as botless or assume the same behavior for every conferencing tool.

- [Meeting recording workflow](#document-workflows-meeting-recording)

<a id="document-platform-context-capture-capture-checks"></a>
## Recommended verification

Before relying on a downstream agent, check a known activity for its content, participants, timestamps and destination record. Check what happens to private, cancelled, declined or inaccessible meetings, and how a user stops capture.

Missing context can cause an incomplete result without indicating a reasoning failure. Troubleshooting should first establish whether the source activity arrived and was accessible.

<a id="document-platform-context-capture-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/context-capture: [Context Capture – Every Interaction, Captured | Oliv AI](https://oliv.ai/context-capture)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)

<a id="document-platform-context-graph"></a>
# Context Graph

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-context-graph-overview"></a>
## Overview

Context Graph is the relationship layer that places customer activity against the business entities it concerns.

<a id="document-platform-context-graph-associations"></a>
## What the graph connects

The public product description associates conversations and activities with accounts, contacts and opportunities, using relationship history and conversation context rather than only an email-domain match.

A useful activity association should preserve a path back to its source. Review the account, the particular opportunity and the participants before allowing an agent’s interpretation to affect a customer record.

<a id="document-platform-context-graph-ambiguous-cases"></a>
## Cases that need careful review



| Situation | What to verify |
| --- | --- |
| Several open opportunities at one company | The activity belongs to the right product, motion and buying group |
| A partner call mentions several customer accounts | Each discussed customer is associated appropriately |
| An acquisition changes the email domain | The relationship to the prior entity remains understandable |
| Duplicate or stale CRM accounts | The active record is identified without unsafe merging |
| Several deals discussed in one meeting | Shared activity does not overwrite unrelated opportunity state |

<a id="document-platform-context-graph-association-vs-cleanup"></a>
## Association and CRM cleanup are separate decisions

Choosing the likely opportunity for an activity is not the same as authorizing a destructive CRM merge. The CRM Manager document explicitly leaves duplicate-resolution thresholds unresolved.

Verify the current review and correction path for an incorrect association. This V1 does not claim a confidence threshold, automatic merge policy or guaranteed perfect mapping.

<a id="document-platform-context-graph-association-acceptance"></a>
## Recommended acceptance criteria

Use examples of multiple opportunities, duplicates and changed domains in the first deployment review. Require an explanation of the selected record, source evidence and a way to correct an incorrect association.

Document whether a correction changes only the current activity or also related historical associations. That behavior is not established by the available sources.

<a id="document-platform-context-graph-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/context-graph: [Context Graph – Every Signal, Mapped | Oliv AI](https://oliv.ai/context-graph)

<a id="document-platform-signal-graph"></a>
# Signal Graph

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-signal-graph-overview"></a>
## Overview

Signal Graph describes Oliv’s interpretation layer: activity is turned into revenue-relevant context that can be updated as new evidence arrives.

<a id="document-platform-signal-graph-signal-meaning"></a>
## What a signal means

A signal can represent an observed risk, qualification detail, stakeholder change, customer need or expansion indication. It is an interpretation grounded in source activity, not an independently guaranteed outcome.

The website presents specialized models for revenue questions. This V1 explains the user-facing behavior without treating model counts or accuracy claims as verified benchmarks.

<a id="document-platform-signal-graph-signal-evidence"></a>
## Read the signal with its evidence



- Identify the question the signal is answering.
- Check the account or opportunity and the source activity.
- Distinguish a directly stated fact from an interpretation or recommendation.
- Check whether newer information changed the signal.
- Confirm how the signal reaches the relevant agent or workflow.

<a id="document-platform-signal-graph-signal-example"></a>
## Illustrative workflow

An account conversation indicates that a previously supportive stakeholder has changed roles. The account association gives the signal a business location; the process playbook supplies the escalation rule; an agent can prepare a recommended next step.

This example explains the relationship between concepts. It is not a promise that a specific trigger, threshold or escalation is enabled in every workspace.

<a id="document-platform-signal-graph-signal-open-rules"></a>
## Rules still requiring confirmation

Confidence display, refresh timing, human corrections, conflicting evidence and downstream recalculation need production verification. The documentation should describe those rules once established rather than substituting a generic ‘AI confidence’ explanation.

For forecast and health workflows, evaluate the signal against observed outcomes over time. A product example or forecast percentage on a marketing page is not a performance commitment.

<a id="document-platform-signal-graph-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/signal-graph: [Signal Graph | Oliv AI](https://oliv.ai/signal-graph)

<a id="document-platform-process-graph"></a>
# Process Graph

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-process-graph-overview"></a>
## Overview

Process Graph supplies company-specific operating context so agents can apply the team’s actual standards rather than generic sales advice.

<a id="document-platform-process-graph-process-content"></a>
## What belongs in the playbook

The product presentation includes linked knowledge about the market, personas, prospecting, qualification, sales execution, handoffs, onboarding and customer success. The Oliver document adds ownership, methodology, approvals, territory rules and exceptions.

State how the organization currently operates. If a process is aspirational or only proposed, mark that state explicitly. An unapproved process should not silently become the operating rule for customer communications or CRM changes.

<a id="document-platform-process-graph-process-maintenance"></a>
## How process changes are maintained

Oliver’s source documentation describes translating leader and RevOps input into structured handbook updates and aligning dependent agents. It also describes proposing learned changes for human sign-off.

The exact approval interface, authorized approver, propagation timing, version history and rollback behavior are not established for all deployments. Those are governance requirements to confirm before allowing broad process changes.

<a id="document-platform-process-graph-process-example"></a>
## Illustrative rule

A qualification rule can specify what evidence is required before an opportunity advances. An exception can state who may approve advancement when a required stakeholder is unavailable.

A useful documentation entry includes the rule, scope, owner, effective date, evidence and exception path. This is a recommended rule format, not a claim that every field is currently configurable in Oliv.

<a id="document-platform-process-graph-process-conflicts"></a>
## Handle conflicting process sources

When two documents disagree on authority or a threshold, retain the conflict and ask the accountable owner to resolve it. Recency alone is not a reason to override an approved policy.

Use the same approved process vocabulary across agent references, integration mappings and task guides. That prevents a renamed stage or qualification field from receiving several inconsistent explanations.

<a id="document-platform-process-graph-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/process-graph: [Process Graph – Your Playbook, Written for Agents | Oliv AI](https://oliv.ai/process-graph)

<a id="document-platform-agent-harness"></a>
# Agent execution and coordination

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-platform-agent-harness-overview"></a>
## Overview

The agent layer combines a defined job, relevant context, available tools and an action boundary. Coordination determines which specialist handles the work.

<a id="document-platform-agent-harness-agent-components"></a>
## The parts of an agent workflow



| Part | Purpose |
| --- | --- |
| Job and instructions | Define the intended work and success condition |
| Context | Provide the relevant account, opportunity and process knowledge |
| Tools | Read or change information through supported connections |
| Trigger or request | Start work from a verified event, schedule or user interaction |
| Review boundary | Determine what needs human confirmation |
| Run result | Show the output, destination and any unresolved issue |

<a id="document-platform-agent-harness-coordination"></a>
## Super agents and specialists

Olivia is presented as the frontline execution and orchestration agent. Oliver maintains the process and configuration context. Specialist agents focus on particular jobs such as forecast preparation, CRM updates or coaching.

The current public pages provide this conceptual distinction. The prototype’s dropdowns and demo run data do not establish production permission enforcement or runtime precedence.

<a id="document-platform-agent-harness-execution-boundaries"></a>
## Confirm boundaries per action

Separate read-only analysis, draft creation, CRM writes, outbound sending and process configuration. One general ‘autonomous’ label is insufficient to explain those different consequences.

For each action, document whose identity is used, who can enable it, whether approval expires, where the request appears, what is logged and how a failed or rejected action is handled. These are acceptance questions until verified.

<a id="document-platform-agent-harness-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)
- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver)

<a id="document-agents"></a>
# Agents

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-overview"></a>
## Overview

Agents are organized by the work they perform. Start with the relevant task and check its context, action boundary and availability.

<a id="document-agents-super-agents"></a>
## Super agents

Olivia is the frontline orchestration agent; Oliver maintains process and configuration context. Their relationship does not remove the need to verify the permissions of each underlying action.

- [Olivia](#document-agents-olivia)
- [Oliver](#document-agents-oliver)

<a id="document-agents-specialists"></a>
## Specialist jobs



| Job | Agent |
| --- | --- |
| CRM records and data quality | CRM Manager |
| Pipeline awareness and deal risk | Deal Driver |
| Forecast preparation and review | Forecaster |
| Opportunity-aware meeting preparation | Meeting Assistant |
| Revenue coaching cadence | Coach |
| Conversation examples and clip libraries | Content Curator |
| Customer portfolio and renewal awareness | Portfolio Manager |
| Expansion-signal discovery and handoff | Gold Digger |
| First-contact account and person research | Researcher |
| Account prioritization and outreach preparation | Prospector |

<a id="document-agents-catalog-boundary"></a>
## Documented references and the wider catalog

The current navigation contains eleven dedicated agent pages. The accessible internal folder contains eleven references, including Researcher and excluding Prospector. Together they support twelve references in this V1.

The wider marketplace names additional agents. A name and a short description do not establish its tools, controls, release status or entitlement. Those entries remain in the catalog reference rather than receiving invented task instructions.

- [Marketplace and naming](#document-agents-marketplace)
- [Agent configuration](#document-agents-configuration)

<a id="document-agents-explore"></a>
## Explore

- [Olivia agent](#document-agents-olivia)
- [Oliver agent](#document-agents-oliver)
- [CRM Manager agent](#document-agents-crm-manager)
- [Deal Driver agent](#document-agents-deal-driver)
- [Forecaster agent](#document-agents-forecaster)
- [Meeting Assistant agent](#document-agents-meeting-assistant)
- [Coach agent](#document-agents-coach)
- [Content Curator agent](#document-agents-content-curator)
- [Portfolio Manager agent](#document-agents-portfolio-manager)
- [Gold Digger agent](#document-agents-gold-digger)
- [Researcher agent](#document-agents-researcher)
- [Prospector agent](#document-agents-prospector)
- [Marketplace and agent naming](#document-agents-marketplace)
- [Agent configuration](#document-agents-configuration)

<a id="document-agents-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents-marketplace: [Create custom AI agents in minutes](https://www.oliv.ai/agents-marketplace)
- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/)

<a id="document-agents-olivia"></a>
# Olivia agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-olivia-overview"></a>
## Overview

Olivia is the front-facing agent that brings revenue context into team work and coordinates specialists when a task needs a more specific capability.

<a id="document-agents-olivia-purpose"></a>
## Purpose and audience

Olivia is the front-facing agent that brings revenue context into team work and coordinates specialists when a task needs a more specific capability.

Primary audience: AEs, BDRs, CSMs and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-olivia-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Account, opportunity and stakeholder context
- Meetings, email and other connected activity
- The process playbook maintained with Oliver
- The user’s request and the current workflow state

<a id="document-agents-olivia-trigger"></a>
## What starts the workflow

A user request or a configured proactive workflow. The sources describe both conversational interaction and activity-driven follow-through; exact channel availability must be confirmed.

<a id="document-agents-olivia-workflow"></a>
## Documented workflow



1. Read the relevant account, opportunity and activity context.
2. Identify the task and the process rules that apply.
3. Prepare the response or route the job to an appropriate specialist.
4. Bring the specialist’s output back into the user’s workflow.
5. Continue the agreed follow-through within the configured action boundary.

<a id="document-agents-olivia-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Contextual answers and preparation
- Briefs, alerts and suggested next actions
- Specialist work assembled for the requesting team member

<a id="document-agents-olivia-actions-and-review"></a>
## Actions and human review

Olivia can coordinate work whose effects depend on the specialist and connected tool. A prepared response, a draft, a CRM change and a sent message need separate explanations.

<a id="document-agents-olivia-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-olivia-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-olivia-rules"></a>
## Rules and configuration



- Use Oliver’s organizational process context when coordinating the job.
- Do not assume an individual’s access permits organization-wide visibility.
- A specialist’s action permission still needs to be established for the task.

<a id="document-agents-olivia-orchestration-context"></a>
### Context used in coordination

The internal reference describes an ongoing view of deals, accounts, conversations and upcoming work. Proactive alerts and requested actions use that context together with the organization’s process knowledge. Data visibility and personal versus shared context still require explicit permission documentation.

<a id="document-agents-olivia-orchestration-handoff"></a>
### Specialist handoff

A complete handoff identifies the job, source record, relevant process constraint and expected output. The specialist’s result returns to the requesting workflow. This recommended description should be matched to actual runtime evidence before documenting a guaranteed handoff protocol.

<a id="document-agents-olivia-collaboration"></a>
## How it works with other agents

Researcher can prepare first-contact intelligence, Meeting Assistant handles opportunity-aware meeting support, CRM Manager applies field updates, and other specialists handle their defined jobs. The named ensemble is a source description, not a promise that every specialist is enabled.

<a id="document-agents-olivia-boundaries"></a>
## Scope and limitations

Olivia does not replace the organization’s accountable decision makers or independently define the company process. Oliver owns the process layer described in the source documents.

<a id="document-agents-olivia-verify"></a>
## Questions to resolve before publication



- Which interaction channels are enabled in the current workspace?
- What happens when a user request conflicts with an organizational rule?
- Which specialists may Olivia call, and who controls that list?
- How are cross-functional tasks assigned without duplicate work?
- Which conversation setting takes precedence over a tool-level setting?

<a id="document-agents-olivia-related"></a>
## Related documentation



- [oliver](#document-agents-oliver)
- [agent harness](#document-platform-agent-harness)
- [approvals](#document-agents-configuration-approvals)

<a id="document-agents-olivia-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia)

<a id="document-agents-oliver"></a>
# Oliver agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-oliver-overview"></a>
## Overview

Oliver helps maintain the company’s revenue playbook and the configuration context that other agents use.

<a id="document-agents-oliver-purpose"></a>
## Purpose and audience

Oliver helps maintain the company’s revenue playbook and the configuration context that other agents use.

Primary audience: RevOps, revenue leaders and process owners. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-oliver-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Current ICP, personas and territory rules
- Qualification methodologies and stage requirements
- Approval policies, ownership rules and exceptions
- Process feedback from leaders and observed work

<a id="document-agents-oliver-trigger"></a>
## What starts the workflow

A process setup or update conversation, or a proposed improvement surfaced for review. The source describes ongoing maintenance rather than a one-time handbook upload.

<a id="document-agents-oliver-workflow"></a>
## Documented workflow



1. Collect the current process and identify its accountable owners.
2. Translate the process into structured, linked handbook knowledge.
3. Identify the affected configuration or dependent agent behavior.
4. Prepare a proposed change and route it for the required human sign-off.
5. Apply the approved change through the verified workflow and check its effects.

<a id="document-agents-oliver-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A maintained company process handbook
- Proposed process or configuration updates
- Aligned context for specialist agents
- Questions about contradictions or exceptions

<a id="document-agents-oliver-actions-and-review"></a>
## Actions and human review

The source describes playbook, schema and configuration work. It does not establish arbitrary administrative access or an unrestricted right to change customer systems.

<a id="document-agents-oliver-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-oliver-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-oliver-rules"></a>
## Rules and configuration



- The internal source says handbook updates require human sign-off.
- Keep actual operating policy distinct from a proposed improvement.
- A process change can affect more than one agent; scope and propagation must be explicit.

<a id="document-agents-oliver-handbook-structure"></a>
### Playbook subject areas

The sources organize operating knowledge across market and ICP, personas, competitors and proof, prospecting, qualification, commercial work, handoffs, onboarding, account health, renewals and expansion. Cross-links should preserve which rule governs which job.

<a id="document-agents-oliver-process-change-scope"></a>
### Change scope

A proposed ICP or methodology change can affect several agents and data fields. The reviewer should identify the affected teams, rules and dependent workflows before approval. The available sources do not establish the production versioning or rollback mechanism.

<a id="document-agents-oliver-collaboration"></a>
## How it works with other agents

CRM Manager writes the fields that the process says to track; Coach evaluates work against the agreed standards; Forecaster interprets stage and forecast criteria; Olivia coordinates frontline execution inside that context.

<a id="document-agents-oliver-boundaries"></a>
## Scope and limitations

Oliver is not the opportunity-level assistant, CRM writer or coaching agent. Its job is the process and configuration context those workflows depend on.

<a id="document-agents-oliver-verify"></a>
## Questions to resolve before publication



- Who may approve a handbook or schema change?
- Where is the approval request displayed and recorded?
- Can different teams or regions have different rules?
- When do dependent agents adopt an approved change?
- How are versions, rollback and in-flight work handled?

<a id="document-agents-oliver-related"></a>
## Related documentation



- [process graph](#document-platform-process-graph)
- [approvals](#document-administration-approvals)
- [olivia](#document-agents-olivia)

<a id="document-agents-oliver-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver)

<a id="document-agents-crm-manager"></a>
# CRM Manager agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-crm-manager-overview"></a>
## Overview

CRM Manager applies revenue context to CRM records, keeping account, contact, opportunity, activity and task information current within the configured workflow.

<a id="document-agents-crm-manager-purpose"></a>
## Purpose and audience

CRM Manager applies revenue context to CRM records, keeping account, contact, opportunity, activity and task information current within the configured workflow.

Primary audience: RevOps, sellers and customer-facing teams. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-crm-manager-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Connected CRM objects and fields
- Interpretations from the conversation and deal-intelligence layer
- Current qualification and field-mapping rules
- New activity or a requested historical cleanup

<a id="document-agents-crm-manager-trigger"></a>
## What starts the workflow

New meetings, calls or email activity for ongoing updates; the internal document also describes direct commands for retrospective cleanup and backfill jobs.

<a id="document-agents-crm-manager-workflow"></a>
## Documented workflow



1. Identify the relevant CRM record and the evidence from connected activity.
2. Determine the fields or records affected by the new information.
3. Prepare proposed values and the reasoning or source moment behind them.
4. Apply the workspace’s verified review or automatic-update policy.
5. Write through the supported connector and expose the resulting record state.

<a id="document-agents-crm-manager-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Proposed or applied CRM updates
- Created or enriched records where supported
- Activity and task information
- Review prompts and RevOps reporting described in the source

<a id="document-agents-crm-manager-actions-and-review"></a>
## Actions and human review

The documentation describes standard, qualification-methodology and customer-specific fields. Actual object coverage, writable fields, connector identity and update conflicts require an implementation-specific mapping.

<a id="document-agents-crm-manager-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-crm-manager-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-crm-manager-rules"></a>
## Rules and configuration



- The source describes Ask First and Auto-Pilot control modes.
- A customer-specific field must be mapped before it can be reliably populated.
- Record association and duplicate merging are separate operations.
- The source leaves duplicate-resolution thresholds unresolved.

<a id="document-agents-crm-manager-crm-object-scope"></a>
### Record categories described in the source

The internal reference distinguishes account/contact management, opportunity creation and tracking, activity tracking, task tracking and field population. Verify the supported operations per connector rather than assuming identical coverage across CRMs.

| Field category | Source-described purpose |
| --- | --- |
| Standard fields | Core opportunity and record information |
| Methodology fields | Qualification evidence such as MEDDPICC or the customer’s framework |
| Customer-specific fields | Values unique to the organization’s process, mapped during implementation |

<a id="document-agents-crm-manager-crm-update-evidence"></a>
### Proposed-update evidence

The source describes showing the reasoning and the conversation moment behind an update, along with review prompts and field-change history. Those are distinct from a complete compliance audit log. Confirm which history is retained and visible in the current product.

<a id="document-agents-crm-manager-collaboration"></a>
## How it works with other agents

Conversation and deal intelligence produce the interpretation; CRM Manager applies the resulting information. Forecaster, Deal Driver, Coach and customer-success workflows then depend on that record context.

<a id="document-agents-crm-manager-boundaries"></a>
## Scope and limitations

CRM Manager complements an existing CRM. It is not the CRM itself and should not be described as the source of every underlying inference or as a reporting replacement.

<a id="document-agents-crm-manager-verify"></a>
## Questions to resolve before publication



- Which objects and custom fields are supported for each connector?
- Which user or service identity performs writes?
- How are simultaneous human and agent edits resolved?
- Can a user reject, undo or recover an applied update?
- Which duplicate cases are merged automatically, if any?
- What happens when authorization expires or a write fails?

<a id="document-agents-crm-manager-related"></a>
## Related documentation



- [crm updates](#document-workflows-crm-updates)
- [salesforce](#document-integrations-salesforce)
- [hubspot](#document-integrations-hubspot)
- [approvals](#document-administration-approvals)

<a id="document-agents-crm-manager-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager)

<a id="document-agents-deal-driver"></a>
# Deal Driver agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-deal-driver-overview"></a>
## Overview

Deal Driver brings deal changes and risk into a manager’s operating cadence, with briefs, alerts and review preparation.

<a id="document-agents-deal-driver-purpose"></a>
## Purpose and audience

Deal Driver brings deal changes and risk into a manager’s operating cadence, with briefs, alerts and review preparation.

Primary audience: Sales managers and revenue leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-deal-driver-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Opportunity state and qualification context
- Activity and stakeholder engagement
- Team ownership and management relationships
- Configured risk and notification rules

<a id="document-agents-deal-driver-trigger"></a>
## What starts the workflow

Daily and weekly cadence plus configured deal events. The internal document describes morning briefs, event alerts, sunset summaries and pipeline-review preparation.

<a id="document-agents-deal-driver-workflow"></a>
## Documented workflow



1. Review the team’s current opportunities and recent activity.
2. Identify deals that warrant attention or a manager intervention.
3. Attach the evidence and a suggested next step to each item.
4. Deliver the appropriate brief, alert or review preparation.
5. Use the management review to decide and assign follow-through.

<a id="document-agents-deal-driver-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Morning team awareness
- Event-triggered risk alerts
- End-of-day summaries
- Per-rep 1:1 and team pipeline review material

<a id="document-agents-deal-driver-actions-and-review"></a>
## Actions and human review

Deal Driver surfaces risks and administrative gaps. The source assigns actual CRM field writing to CRM Manager and forecast projections to Forecaster.

<a id="document-agents-deal-driver-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-deal-driver-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-deal-driver-rules"></a>
## Rules and configuration



- Risk thresholds and delivery destinations must be configured or confirmed.
- A quiet account, overdue next step and missing qualification evidence are different reasons for attention.
- A manager brief should retain the deal and source context that explains the recommendation.

<a id="document-agents-deal-driver-driver-cadence"></a>
### Brief and review structure



| Output | Source-described content |
| --- | --- |
| Morning brief | Team meetings, priority deals and intervention context |
| Event alert | Changed deal state, risk or missing follow-through |
| Sunset summary | Activity outcomes and open management follow-up |
| Per-rep review | Pipeline, activity and flagged decisions |
| Team review | Coverage, movement and risk across the team |

<a id="document-agents-deal-driver-driver-risk-meaning"></a>
### Risk reason and next step

A useful alert distinguishes inactivity, missing qualification evidence, a timing concern and an ownership gap. Verify the configured threshold and inspect the relevant activity before treating the alert as an outcome prediction.

<a id="document-agents-deal-driver-collaboration"></a>
## How it works with other agents

The internal document groups opportunity-level meeting support with Deal Driver in a bundle and also describes Meeting Assistant as standalone. Confirm that packaging against the current commercial offer. CRM Manager and Coach provide adjacent data and development workflows.

<a id="document-agents-deal-driver-boundaries"></a>
## Scope and limitations

Deal Driver is not a universal forecast engine, a CRM update service or a coaching replacement. It focuses on pipeline awareness and intervention.

<a id="document-agents-deal-driver-verify"></a>
## Questions to resolve before publication



- Which alerts are available and which thresholds are configurable?
- Where do alerts arrive for each deployment?
- Is the sunset summary automatic in all configurations?
- How are multiple managers and territories handled?
- What is the current relationship between Deal Driver and Meeting Assistant packaging?

<a id="document-agents-deal-driver-related"></a>
## Related documentation



- [pipeline review](#document-workflows-pipeline-review)
- [meeting assistant](#document-agents-meeting-assistant)
- [forecaster](#document-agents-forecaster)
- [coach](#document-agents-coach)

<a id="document-agents-deal-driver-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/deal-driver: [Deal Driver – AI Deal Risk Agent | Oliv AI](https://oliv.ai/agents/deal-driver)

<a id="document-agents-forecaster"></a>
# Forecaster agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-forecaster-overview"></a>
## Overview

Forecaster supports a recurring forecast process with recommended deal changes, rep submissions, manager review and historical snapshots.

<a id="document-agents-forecaster-purpose"></a>
## Purpose and audience

Forecaster supports a recurring forecast process with recommended deal changes, rep submissions, manager review and historical snapshots.

Primary audience: Contributors, sales managers, RevOps and leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-forecaster-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Opportunity stages, amounts, close dates and forecast categories
- Current deal activity and qualification evidence
- Targets, measurements, team hierarchy and cadence
- Historical submissions and outcomes where available

<a id="document-agents-forecaster-trigger"></a>
## What starts the workflow

A configured weekly, monthly or quarterly forecast cadence. The internal document describes parallel timeframes and progressive levels of automation.

<a id="document-agents-forecaster-workflow"></a>
## Documented workflow



1. Review current opportunities against deal context and the forecasting rules.
2. Prepare recommendations about category, value, timing or risk.
3. Let the contributor review and submit the forecast where the configured mode requires it.
4. Allow manager adjustments and review at the supported level.
5. Preserve the submission or snapshot used for historical comparison.
6. Compare predictions with observed outcomes to support later review.

<a id="document-agents-forecaster-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Prepared forecast views and recommendations
- Contributor submissions and manager review material
- Team rollups
- Snapshots and accuracy-review context

<a id="document-agents-forecaster-actions-and-review"></a>
## Actions and human review

Forecast recommendations, submissions and CRM writes are separate actions. The exact write-back fields and whether a reviewed change updates the CRM require confirmation.

<a id="document-agents-forecaster-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-forecaster-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-forecaster-rules"></a>
## Rules and configuration



- The source distinguishes contributor, manager and admin/observer views.
- AI-Assisted, AI-Managed and AI-Owned are described as progressive operating modes.
- The source does not establish an automatic threshold for advancing between modes.
- Custom measurement and multi-level approval support remain open questions.

<a id="document-agents-forecaster-forecast-views"></a>
### Views and review responsibilities



| View | Documented responsibility |
| --- | --- |
| Contributor | Review recommendations and submit the forecast |
| Manager | Review contributor submissions, make supported adjustments and inspect the rollup |
| Admin/observer | Configure or view targets, measurements and board settings according to actual permission |

<a id="document-agents-forecaster-forecast-modes"></a>
### Progressive operating modes

The source does not establish a universal time or confidence threshold for moving between these modes. Do not treat illustrative weeks, months or accuracy percentages as an automatic entitlement or product guarantee.

| Mode | Documented relationship to human review |
| --- | --- |
| AI-Assisted | Recommendations support a team-owned forecast |
| AI-Managed | A prepared forecast is reviewed and adjusted |
| AI-Owned | More of the forecast is produced automatically, with uncertainty surfaced for review |

<a id="document-agents-forecaster-forecast-categories"></a>
### Categories and measurements

The internal reference names Forecast, Commit, Best Case and Pipeline in its example workflow. Confirm the workspace’s actual categories and how values, counts, formulas, periods and currencies are handled before comparing totals.

<a id="document-agents-forecaster-collaboration"></a>
## How it works with other agents

CRM Manager supplies maintained opportunity data; Deal Driver adds current deal context; Oliver supplies process and stage criteria. The quality of the resulting forecast depends on those inputs and the chosen review process.

<a id="document-agents-forecaster-boundaries"></a>
## Scope and limitations

Do not convert illustrative mode timelines or accuracy percentages into a guaranteed learning curve. Forecast outcomes vary with the available history, motion and operating process.

<a id="document-agents-forecaster-verify"></a>
## Questions to resolve before publication



- Who enables or changes an operating mode?
- What qualifies a workspace to move to a more automatic mode?
- Which manager hierarchy and multi-level approvals are supported?
- Which metrics and formulas may administrators define?
- How are snapshots retained and separated from other deal history?
- Which forecast changes write back to which CRM fields?

<a id="document-agents-forecaster-related"></a>
## Related documentation



- [forecast](#document-apps-forecast)
- [forecast review](#document-workflows-forecast-review)
- [reporting cadences](#document-reference-reporting-cadences)

<a id="document-agents-forecaster-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/forecaster: [Forecaster | Oliv AI](https://oliv.ai/agents/forecaster)

<a id="document-agents-meeting-assistant"></a>
# Meeting Assistant agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-meeting-assistant-overview"></a>
## Overview

Meeting Assistant prepares an existing opportunity’s context before a meeting and helps turn the conversation into follow-up work afterward.

<a id="document-agents-meeting-assistant-purpose"></a>
## Purpose and audience

Meeting Assistant prepares an existing opportunity’s context before a meeting and helps turn the conversation into follow-up work afterward.

Primary audience: Sellers, CSMs and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-meeting-assistant-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- A meeting associated with an active opportunity
- Stakeholders and previous conversations
- Deal fields and qualification methodology
- A recording or transcript for post-meeting work

<a id="document-agents-meeting-assistant-trigger"></a>
## What starts the workflow

A verified calendar or meeting workflow before a scheduled meeting, followed by processing of the recorded conversation. The exact trigger path differs across integrations and needs confirmation.

<a id="document-agents-meeting-assistant-workflow"></a>
## Documented workflow



1. Identify the opportunity and participants for the upcoming meeting.
2. Prepare the deal summary, qualification gaps, stakeholder context and recommended agenda.
3. Deliver the brief through the configured channel.
4. After the meeting is processed, prepare a follow-up draft and proposed field updates.
5. Review the suggested next steps and apply the verified approval policy.

<a id="document-agents-meeting-assistant-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A concise pre-meeting brief
- A follow-up email draft
- Proposed opportunity or qualification updates
- Flags for missing or changed information

<a id="document-agents-meeting-assistant-actions-and-review"></a>
## Actions and human review

The source describes drafts and proposed field updates. It does not establish that every follow-up is sent automatically or that every proposed value is written without review.

<a id="document-agents-meeting-assistant-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-meeting-assistant-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-meeting-assistant-rules"></a>
## Rules and configuration



- Opportunity context distinguishes Meeting Assistant from first-contact Researcher.
- The September agent document describes a thirty-minute prep window.
- Older public Help Center workflows describe other prep timings; confirm the product and configuration before using a single number.
- Recording completion and processing are prerequisites for transcript-based follow-up.

<a id="document-agents-meeting-assistant-meeting-brief-fields"></a>
### Preparation contents



| Part | Documented context |
| --- | --- |
| Deal summary | Stage, value, close date, recent activity and next steps |
| Qualification | Known evidence and gaps against the active framework |
| Stakeholders | Participant role and relevant prior context |
| Agenda | Topics appropriate to the opportunity and open questions |

<a id="document-agents-meeting-assistant-meeting-followup-parts"></a>
### Post-meeting outputs

The source distinguishes a follow-up draft, proposed deal-field updates and qualification-gap flags. These depend on the processed conversation. None should be described as sent or applied until the relevant destination confirms the action.

<a id="document-agents-meeting-assistant-collaboration"></a>
## How it works with other agents

Researcher adds first-contact intelligence; CRM Manager handles supported writes; Deal Driver uses meeting context for management awareness; qualification and process rules come from the playbook.

<a id="document-agents-meeting-assistant-boundaries"></a>
## Scope and limitations

Preparation for an active opportunity is different from prospecting a new account. A pre-meeting brief is not a substitute for obtaining the meeting recording or reviewing an outbound message.

<a id="document-agents-meeting-assistant-verify"></a>
## Questions to resolve before publication



- Which event starts preparation for each calendar integration?
- What is the current delivery time and channel?
- How are meetings discussing several deals handled?
- Can users customize the brief or agenda?
- Where are follow-up drafts reviewed and sent?

<a id="document-agents-meeting-assistant-related"></a>
## Related documentation



- [meeting preparation](#document-workflows-meeting-preparation)
- [meeting recording](#document-workflows-meeting-recording)
- [researcher](#document-agents-researcher)

<a id="document-agents-meeting-assistant-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/meeting-assistant: [Meeting Assistant – AI Briefs &amp; Follow-ups | Oliv AI](https://oliv.ai/agents/meeting-assistant)

<a id="document-agents-coach"></a>
# Coach agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-coach-overview"></a>
## Overview

Coach turns recorded work into a recurring development process: score activity, identify focus areas, let a manager choose a goal, and track progress.

<a id="document-agents-coach-purpose"></a>
## Purpose and audience

Coach turns recorded work into a recurring development process: score activity, identify focus areas, let a manager choose a goal, and track progress.

Primary audience: Reps, managers, enablement and revenue leaders. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-coach-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Recorded calls, meetings and deal context
- Scorecards and weighted criteria
- Rep ownership and the relevant sales motion
- A manager-selected coaching goal

<a id="document-agents-coach-trigger"></a>
## What starts the workflow

Scoring of recorded activity followed by a monthly goal-setting and weekly progress cadence described in the source document.

<a id="document-agents-coach-workflow"></a>
## Documented workflow



1. Apply the configured scorecards to the relevant activity.
2. Review patterns in meeting effectiveness, execution and foundational skills.
3. Prepare a small set of candidate focus areas with supporting evidence.
4. Have the manager select, edit or replace the proposed goal.
5. Track weekly progress against the chosen goal.
6. Review the completed cycle before starting the next one.

<a id="document-agents-coach-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Call, meeting and deal scoring
- A monthly per-rep review
- Recommended focus areas and a manager-approved goal
- Weekly progress and supporting examples

<a id="document-agents-coach-actions-and-review"></a>
## Actions and human review

The source states that the manager reviews the recommendation before it reaches the rep. This is a documented behavioral boundary; the production approval interface and authorized reviewers still need verification.

<a id="document-agents-coach-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-coach-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-coach-rules"></a>
## Rules and configuration



- Coaching goals should connect to observed work and outcomes.
- Scoring and the coaching cadence are distinct from merely recording calls.
- An evidence-volume threshold is needed before treating patterns as representative.
- The source leaves BDR scope and some team-level reporting unresolved.

<a id="document-agents-coach-coaching-dimensions"></a>
### Scoring dimensions



| Dimension | What the internal reference assesses |
| --- | --- |
| Pipeline coverage | Activity and funnel context relative to the rep’s goal |
| Deal execution | Qualification, stakeholders and next-step discipline |
| Meeting effectiveness | Discovery, positioning, objection handling and follow-through |
| Foundational skills | Listening, questioning, relating, positioning and checking |

<a id="document-agents-coach-scorecard-library"></a>
### Scorecard library

The internal reference names deal, customer, meeting and call scorecards: enterprise, mid-market, SMB and upsell opportunities; customer retention; discovery, demo, POC/pilot review and QBR meetings; qualification and follow-up calls. The current catalog and edit permissions still need confirmation.

<a id="document-agents-coach-collaboration"></a>
## How it works with other agents

Content Curator supplies relevant examples; Deal Driver supplies current pipeline context; Oliver provides process standards. Coach uses those inputs for development rather than owning every adjacent workflow.

<a id="document-agents-coach-boundaries"></a>
## Scope and limitations

Coach is not a legal-compliance assessment or a replacement for the manager-rep relationship. The source’s numerical examples are illustrations, not independently measured customer outcomes.

<a id="document-agents-coach-verify"></a>
## Questions to resolve before publication



- What is the current minimum activity volume for each motion?
- Which scorecards and criteria are configurable?
- Which roles can approve or override a goal?
- Are team-level trend reports supported today?
- How are scoring corrections reflected in later progress reports?

<a id="document-agents-coach-related"></a>
## Related documentation



- [coaching](#document-workflows-coaching)
- [enable](#document-apps-enable)
- [content curator](#document-agents-content-curator)

<a id="document-agents-coach-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/coach: [Coach – AI Sales Coaching Agent | Oliv AI](https://oliv.ai/agents/coach)

<a id="document-agents-content-curator"></a>
# Content Curator agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-content-curator-overview"></a>
## Overview

Content Curator identifies relevant moments in recorded conversations and organizes them into usable examples for enablement and coaching.

<a id="document-agents-content-curator-purpose"></a>
## Purpose and audience

Content Curator identifies relevant moments in recorded conversations and organizes them into usable examples for enablement and coaching.

Primary audience: Enablement, managers and customer-facing teams. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-content-curator-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Accessible call or meeting recordings
- A named intent describing the moments to find
- Library or playlist configuration
- The destination for notifications and sharing

<a id="document-agents-content-curator-trigger"></a>
## What starts the workflow

New recordings evaluated against the configured intent. The internal document describes proactive clipping and delivery rather than requiring a search for each example.

<a id="document-agents-content-curator-workflow"></a>
## Documented workflow



1. Define an intent in plain language and identify its audience.
2. Evaluate relevant recordings for matching moments.
3. Extract the useful segment and retain its source context.
4. Place the clip in the configured library or playlist.
5. Notify the intended users through the verified delivery route.
6. Review irrelevant clips through the supported feedback mechanism.

<a id="document-agents-content-curator-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Clips linked to source recordings
- Metadata such as participants, time and deal context
- Organized examples for coaching or enablement
- Notifications when relevant material is added

<a id="document-agents-content-curator-actions-and-review"></a>
## Actions and human review

Clip detection, library access, external syncing and feedback are distinct controls. The available sources do not establish that all advertised storage or LMS integrations are working in every deployment.

<a id="document-agents-content-curator-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-content-curator-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-content-curator-rules"></a>
## Rules and configuration



- An intent defines what to detect; a library is the destination that organizes clips.
- The source describes private, team and organization sharing scopes, which require production verification.
- Historical backfill, pricing and learning-feedback thresholds remain unresolved.
- Internal copy describes Highspot storage while also listing LMS implementation as a pending area.

<a id="document-agents-content-curator-curator-intent"></a>
### Intent configuration

The source describes an intent with a name, a plain-language detection brief and an access scope. Examples include pricing objections, competitor mentions, useful discovery and onboarding moments. These are examples of detection intent, not keyword rules or guaranteed detections.

<a id="document-agents-content-curator-curator-artifact"></a>
### Clip context and destination

The document describes delivery via configured collaboration channels and a possible digest cadence. Confirm actual destination support, sharing permissions and the external-storage implementation.

| Artifact detail | Purpose |
| --- | --- |
| Source recording link | Preserve the surrounding conversation |
| Timestamp | Locate the selected moment |
| Participants and call date | Understand who spoke and when |
| Account/deal context | Connect the example to the relevant work |
| Library/playlist | Organize and control access to the selected examples |

<a id="document-agents-content-curator-collaboration"></a>
## How it works with other agents

Coach uses selected examples in the development cadence; Meeting Assistant and conversation capture provide source activity; Content Curator focuses on finding and organizing the examples.

<a id="document-agents-content-curator-boundaries"></a>
## Scope and limitations

Content Curator is not the call recorder or a full learning-management system. It depends on accessible recordings and does not establish a license to share every recording with every user.

<a id="document-agents-content-curator-verify"></a>
## Questions to resolve before publication



- Which storage and LMS integrations are available now?
- Can historical recordings be backfilled?
- How are library and clip permissions enforced?
- What does removing a clip change in later detection?
- What limits and credit costs apply to clips and storage?

<a id="document-agents-content-curator-related"></a>
## Related documentation



- [enable](#document-apps-enable)
- [coaching](#document-workflows-coaching)
- [access](#document-administration-access)

<a id="document-agents-content-curator-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/content-curator: [Content Curator | Oliv AI](https://oliv.ai/agents/content-curator)

<a id="document-agents-portfolio-manager"></a>
# Portfolio Manager agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-portfolio-manager-overview"></a>
## Overview

Portfolio Manager assembles account-health context, renewal risk and portfolio priorities so the CS organization can decide where to act.

<a id="document-agents-portfolio-manager-purpose"></a>
## Purpose and audience

Portfolio Manager assembles account-health context, renewal risk and portfolio priorities so the CS organization can decide where to act.

Primary audience: CSMs, CS managers, CS leaders and RevOps. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-portfolio-manager-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Account records and stakeholder relationships
- Customer conversations and engagement
- Usage or support context where connected
- Renewal timing, health standards and account ownership

<a id="document-agents-portfolio-manager-trigger"></a>
## What starts the workflow

Changing account signals and scheduled portfolio-review cadences described in the source document.

<a id="document-agents-portfolio-manager-workflow"></a>
## Documented workflow



1. Review each account’s health, relationship and renewal context.
2. Identify accounts that need attention and the evidence behind each flag.
3. Prepare a recommended next step for the responsible owner.
4. Assemble per-CSM review preparation and team-level recaps.
5. Use the review to assign interventions and check follow-through.

<a id="document-agents-portfolio-manager-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Account risk and health explanations
- Per-CSM 1:1 preparation
- Team portfolio and renewal summaries
- Account-level coaching context described in the source

<a id="document-agents-portfolio-manager-actions-and-review"></a>
## Actions and human review

A health interpretation, a renewal projection and a task or communication are different outputs. Confirm which are persisted or written to connected systems and which require review.

<a id="document-agents-portfolio-manager-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-portfolio-manager-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-portfolio-manager-rules"></a>
## Rules and configuration



- A risk flag should explain the contributing evidence rather than only a color or score.
- Ownership determines who receives a recommendation.
- Usage and support sources are conditional integrations, not assumed inputs.
- The source leaves parts of the CS role vocabulary and broader agent roster unresolved.

<a id="document-agents-portfolio-manager-portfolio-outputs"></a>
### Review outputs



| Output | Documented purpose |
| --- | --- |
| Account alert | Explain a risk and recommend a next step |
| Per-CSM briefing | Prepare the manager’s account review |
| Team recap | Show portfolio health and escalation needs |
| Renewal view | Organize renewal confidence and forward coverage |
| CSM effectiveness view | Surface account-management strengths and development areas |

<a id="document-agents-portfolio-manager-portfolio-coaching"></a>
### Account-level effectiveness dimensions

The internal reference names relationship management, value communication, proactive enablement, expansion development and renewal planning. Confirm whether these dimensions are fixed or configurable and which roles may view the evidence.

<a id="document-agents-portfolio-manager-collaboration"></a>
## How it works with other agents

CRM Manager maintains supporting records; Gold Digger handles expansion signals and the warm handoff motion; Olivia can coordinate team work. Retention forecasting must be distinguished from sales forecasting.

<a id="document-agents-portfolio-manager-boundaries"></a>
## Scope and limitations

Portfolio Manager does not replace a support ticketing system or automatically resolve a customer issue. Avoid claiming complete replacement of a named CS platform without an agreed use-case comparison.

<a id="document-agents-portfolio-manager-verify"></a>
## Questions to resolve before publication



- Which account-health criteria and weights are configurable?
- Which usage and support integrations are enabled?
- Who sees each account and portfolio report?
- How are renewal forecast categories defined?
- Which CS agent names are canonical in the current offer?

<a id="document-agents-portfolio-manager-related"></a>
## Related documentation



- [retain](#document-apps-retain)
- [customer success](#document-workflows-customer-success)
- [gold digger](#document-agents-gold-digger)

<a id="document-agents-portfolio-manager-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/portfolio-manager: [Portfolio Manager | Oliv AI](https://oliv.ai/agents/portfolio-manager)

<a id="document-agents-gold-digger"></a>
# Gold Digger agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-gold-digger-overview"></a>
## Overview

Gold Digger turns expansion indications in customer conversations into evidence-bearing alerts and a warm handoff for the responsible commercial team.

<a id="document-agents-gold-digger-purpose"></a>
## Purpose and audience

Gold Digger turns expansion indications in customer conversations into evidence-bearing alerts and a warm handoff for the responsible commercial team.

Primary audience: Account managers, AEs and CSMs. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-gold-digger-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- Customer-facing CS and AM conversations
- The customer’s current footprint and account context
- Relevant products, use cases and stakeholder relationships
- AE/CSM ownership and the approved handoff process

<a id="document-agents-gold-digger-trigger"></a>
## What starts the workflow

An expansion indication detected in a customer conversation. The source describes alerts after processing the relevant call.

<a id="document-agents-gold-digger-workflow"></a>
## Documented workflow



1. Identify a potentially relevant expansion signal in the conversation.
2. Relate the signal to the customer’s current use and stakeholder context.
3. Attach the source moment and a recommended next step.
4. Prepare a warm-introduction draft for human review.
5. Log the confirmed opportunity through the supported CRM workflow.

<a id="document-agents-gold-digger-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- An expansion alert with evidence
- Context about the account and stakeholder
- A proposed warm introduction
- An expansion opportunity record where configured

<a id="document-agents-gold-digger-actions-and-review"></a>
## Actions and human review

The source describes a CSM review/send step or an agreed delegation to the AE. Detection alone does not authorize a message or establish a qualified expansion opportunity.

<a id="document-agents-gold-digger-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-gold-digger-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-gold-digger-rules"></a>
## Rules and configuration



- Adjacent-team interest, a new use case, growth or a scaling event can be a signal.
- A routine comment is not automatically qualified buying intent.
- The evidence should include the source conversation and relevant moment.
- Do not treat illustrative ARR values or customer names in demonstrations as real proof.

<a id="document-agents-gold-digger-expansion-signal-types"></a>
### Signal examples

The internal reference gives examples such as adjacent-team interest, a new use case, team growth, budget availability, a scaling event, a champion moving roles and dissatisfaction with another tool. They are candidate signals whose relevance depends on the account context.

<a id="document-agents-gold-digger-expansion-evidence"></a>
### Alert and handoff context



| Detail | Why it matters |
| --- | --- |
| Account and participants | Identify the customer relationship |
| Source moment | Verify what was actually said |
| Current footprint | Explain why the need may be adjacent |
| Suggested next step | Give the owner an actionable option |
| Reviewed introduction | Preserve the warm, human-owned handoff |

<a id="document-agents-gold-digger-collaboration"></a>
## How it works with other agents

Portfolio Manager provides account-health and relationship context, CRM Manager supports record maintenance, and the commercial owner decides how to approach the new stakeholder.

<a id="document-agents-gold-digger-boundaries"></a>
## Scope and limitations

Gold Digger is an expansion workflow, not a blanket authorization for cold outreach. A detected signal, a reviewed opportunity and a booked expansion outcome are different states.

<a id="document-agents-gold-digger-verify"></a>
## Questions to resolve before publication



- What distinguishes a candidate signal from a confirmed opportunity?
- Who confirms the signal and owns the CRM record?
- Which channels and destinations receive alerts?
- How are duplicate expansion records prevented?
- What happens when a CSM or AE rejects the proposed handoff?

<a id="document-agents-gold-digger-related"></a>
## Related documentation



- [expansion](#document-workflows-expansion)
- [portfolio manager](#document-agents-portfolio-manager)
- [slack](#document-integrations-slack)

<a id="document-agents-gold-digger-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/gold-digger: [Gold Digger – Expansion Signal Agent | Oliv AI](https://oliv.ai/agents/gold-digger)

<a id="document-agents-researcher"></a>
# Researcher agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-researcher-overview"></a>
## Overview

Researcher prepares account and contact context for a meeting with a new person or an account the team has not engaged recently.

<a id="document-agents-researcher-purpose"></a>
## Purpose and audience

Researcher prepares account and contact context for a meeting with a new person or an account the team has not engaged recently.

Primary audience: Sellers and account managers. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-researcher-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- The upcoming meeting and participants
- Company and contact identifiers
- Accessible professional and company information
- Relevant account history where available

<a id="document-agents-researcher-trigger"></a>
## What starts the workflow

A scheduled first-contact meeting in the workflow described by the internal document. Exact calendar triggers and supported sources require confirmation.

<a id="document-agents-researcher-workflow"></a>
## Documented workflow



1. Identify the company and the people on the calendar event.
2. Gather relevant business, role and recent-event context.
3. Select the most useful points for the meeting.
4. Prepare a short brief and a specific conversation opener.
5. Provide a route to deeper detail where supported.

<a id="document-agents-researcher-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- A concise account and contact brief
- Relevant recent company context
- A suggested icebreaker or opening topic

<a id="document-agents-researcher-actions-and-review"></a>
## Actions and human review

Researcher prepares information. The available description does not establish automatic outbound sending, contact enrichment writes or a lead-qualification decision.

<a id="document-agents-researcher-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-researcher-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-researcher-rules"></a>
## Rules and configuration



- Use Researcher for first-contact preparation and Meeting Assistant for active-opportunity context.
- The source describes a short, prioritized brief rather than an exhaustive dossier.
- Private or unsupported data sources must not be inferred from a broad ‘research’ label.
- The stated prep time needs reconciliation with the other meeting workflows.

<a id="document-agents-researcher-research-scope"></a>
### Account and contact scope

Confirm external-source freshness and correction behavior. Do not turn inferred interests or incomplete public profiles into established personal facts.

| Research area | Source-described examples |
| --- | --- |
| Company | Business, size, sector, products and recent developments |
| Person | Professional role, background and relevant priorities |
| Conversation opening | A specific point useful for the scheduled meeting |

<a id="document-agents-researcher-collaboration"></a>
## How it works with other agents

Prospector prioritizes whom to work and prepares outreach. Researcher prepares for a meeting already scheduled. Olivia can coordinate that preparation with other work.

<a id="document-agents-researcher-boundaries"></a>
## Scope and limitations

Researcher is present in the accessible internal documentation and public marketplace. It was not a dedicated agent page in the current navigation snapshot; its availability remains an owner-confirmation item.

<a id="document-agents-researcher-verify"></a>
## Questions to resolve before publication



- Is Researcher enabled as a standalone agent in the current offer?
- Which sources, regions and languages are supported?
- What initiates the brief and when is it delivered?
- How are stale or conflicting external facts handled?
- Can the user request corrections or refresh the research?

<a id="document-agents-researcher-related"></a>
## Related documentation



- [prospector](#document-agents-prospector)
- [meeting assistant](#document-agents-meeting-assistant)
- [meeting preparation](#document-workflows-meeting-preparation)

<a id="document-agents-researcher-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents-marketplace: [Create custom AI agents in minutes](https://www.oliv.ai/agents-marketplace)

<a id="document-agents-prospector"></a>
# Prospector agent

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-prospector-overview"></a>
## Overview

Prospector helps choose which accounts to work, develops an account-specific point of view and prepares outreach.

<a id="document-agents-prospector-purpose"></a>
## Purpose and audience

Prospector helps choose which accounts to work, develops an account-specific point of view and prepares outreach.

Primary audience: Sales development, sellers and account expansion teams. This reference describes the product sources; workspace availability and plan access require confirmation.

<a id="document-agents-prospector-inputs"></a>
## Inputs and prerequisites

Connect only the sources needed for this job and confirm that the participating users may access the relevant records.

- CRM and conversation context
- The organization’s ICP and territory rules
- Relevant account signals

<a id="document-agents-prospector-trigger"></a>
## What starts the workflow

The current public page describes territory and recurring account-prioritization workflows. The exact schedule and supported trigger configuration need confirmation.

<a id="document-agents-prospector-workflow"></a>
## Documented workflow



1. Apply the current ICP and territory rules to the account pool.
2. Review the reasons to prioritize an account now.
3. Prepare a point of view and outreach for the responsible rep.
4. Review and send the opening email through the approved workflow.

<a id="document-agents-prospector-outputs"></a>
## Outputs and destinations

Check the actual output and destination in the configured workspace. A visual example is not a completed production action.

- Ranked accounts with reasons
- Research and account point of view
- Prepared outreach

<a id="document-agents-prospector-actions-and-review"></a>
## Actions and human review

The current page says the rep reviews and sends the first email, while no-response follow-ups can be automatic. Confirm that behavior for the selected channel and workspace before enabling a sequence.

<a id="document-agents-prospector-action-scope"></a>
### Confirm action scope

Record which actions read context, prepare a draft, write a record or send a communication. The responsible owner should approve the applicable boundary before increasing volume.

<a id="document-agents-prospector-approval-evidence"></a>
#### Evidence to retain

Use the task’s source record, proposed output, reviewer identity where applicable, and observed destination state. These are recommended acceptance records; availability of native audit fields must be verified.

<a id="document-agents-prospector-rules"></a>
## Rules and configuration



- First-party account context supplements external data.
- Territory allocation and account ranking are related but distinct jobs.
- A rank is not a guarantee of conversion.

<a id="document-agents-prospector-collaboration"></a>
## How it works with other agents

Researcher supports meeting preparation; Engage is the associated outreach workspace. Expansion use cases should be coordinated with the account owner.

<a id="document-agents-prospector-boundaries"></a>
## Scope and limitations

This reference has no corresponding original PMM file in the accessible eleven-document folder. Its behavioral description is intentionally narrower; the following checks are editorial requirements, not implemented-feature claims.

<a id="document-agents-prospector-verify"></a>
## Questions to resolve before publication



- Who approves territory and ICP changes?
- Which follow-ups, channels and stop conditions are supported?
- How do opt-outs and customer ownership affect an active sequence?
- What are the rate, credit and volume limits?
- What happens when a person replies through another channel?

<a id="document-agents-prospector-related"></a>
## Related documentation



- [engage](#document-apps-engage)
- [researcher](#document-agents-researcher)
- [prospecting](#document-workflows-prospecting)

<a id="document-agents-prospector-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)

<a id="document-agents-marketplace"></a>
# Marketplace and agent naming

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-marketplace-overview"></a>
## Overview

Use the current navigation as the primary presentation of named agents. Treat the wider marketplace as a catalog whose detailed behavior and availability still need confirmation.

<a id="document-agents-marketplace-dedicated-pages"></a>
## Dedicated references in V1

The live navigation exposes eleven agent pages. This V1 adds Researcher from the original internal documentation and marketplace, giving twelve substantive references. The combined set is not an advertised agent count or a count of GA capabilities.

- [Olivia](#document-agents-olivia)
- [Oliver](#document-agents-oliver)
- [CRM Manager](#document-agents-crm-manager)
- [Deal Driver](#document-agents-deal-driver)
- [Forecaster](#document-agents-forecaster)
- [Meeting Assistant](#document-agents-meeting-assistant)
- [Coach](#document-agents-coach)
- [Content Curator](#document-agents-content-curator)
- [Portfolio Manager](#document-agents-portfolio-manager)
- [Gold Digger](#document-agents-gold-digger)
- [Researcher](#document-agents-researcher)
- [Prospector](#document-agents-prospector)

<a id="document-agents-marketplace-catalog-only"></a>
## Additional marketplace names

The live marketplace lists 36 entries. Many have only a short catalog description. Names outside the detailed reference set are recorded below without invented tools, permissions, triggers or setup instructions.

- Pipeline Tracker; Retention Forecaster; Analyst; Deal Assist; MAP Manager; Case Builder; CRM Assist.
- Territory Planner; Scenario Simulator; Reactivator; Follow-up Maniac; Handoff Hank; Relationship Manager.
- Proposal Pro; Signal Scout; Objection Whisperer; Demo Wizard; Pricing Strategist; Legal Liaison.
- Health Monitor; QBR Builder; Compliance Sentinel; Cross-Sell Cat; Battlecard Builder; Data Cleanser; Collateral Curator; Playbook Author; Event Scanner.

<a id="document-agents-marketplace-name-conflicts"></a>
## Resolve aliases before merging

The prototype extraction uses a different set of agent names. Similar jobs are not enough to prove two names refer to the same shipped agent. For example, a forecast-related name may represent an earlier concept, a specialist or a configuration demonstration.

Keep the current public name as the primary display name, preserve a stable documentation ID, and record a former name only after the product owner confirms the relationship and whether the name was customer-visible.

<a id="document-agents-marketplace-catalog-verification"></a>
## Catalog acceptance requirements



- Confirm the canonical name and job.
- Confirm GA, beta, limited rollout, planned or retired state.
- Identify the working entry point and responsible user.
- Describe sources read, actions written and required human review.
- Confirm plans, add-ons, credits, quotas and supported connectors.

<a id="document-agents-marketplace-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents-marketplace: [Create custom AI agents in minutes](https://www.oliv.ai/agents-marketplace)
- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/)

<a id="document-agents-configuration"></a>
# Agent configuration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-configuration-overview"></a>
## Overview

Configuration determines what an agent may know, what starts its work and what actions it may take. The available sources describe several controls but do not establish every production rule.

<a id="document-agents-configuration-configuration-parts"></a>
## Configuration areas



| Area | What it controls | Reference |
| --- | --- | --- |
| Instructions and process | The job and applicable rules | Process Graph and agent reference |
| Tools and approvals | Available actions and review requirements | Action boundaries |
| Triggers and schedules | Events or cadences that initiate work | Triggers and schedules |
| Knowledge and data | Supporting documents and source access | Knowledge and data |
| Run history | Evidence of attempted and completed work | Run history |

<a id="document-agents-configuration-configuration-source"></a>
## Prototype versus production

The October extraction describes a prototype where several selections exist only for the visit and some action buttons have no implementation. That is useful UI evidence, but it cannot establish persistence, permission enforcement or a working execution path.

Use these references to define what must be checked in the current workspace. Do not promote a selector option into a production guarantee merely because it is visible in the prototype.

<a id="document-agents-configuration-explore"></a>
## Explore

- [Tool modes and action boundaries](#document-agents-configuration-approvals)
- [Triggers and schedules](#document-agents-configuration-triggers)
- [Knowledge and data access](#document-agents-configuration-knowledge)
- [Run history and outputs](#document-agents-configuration-run-history)

<a id="document-agents-configuration-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-agents-configuration-approvals"></a>
# Tool modes and action boundaries

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-configuration-approvals-overview"></a>
## Overview

Approval terminology differs across the sources. Establish the rule for each action rather than assuming one setting governs every workflow.

<a id="document-agents-configuration-approvals-mode-labels"></a>
## Labels in the sources



| Source | Labels or behavior | Interpretation |
| --- | --- | --- |
| Prototype tool selector | Auto Run; Requires Approval; Agent Decides | Observed UI options; runtime enforcement unverified |
| Prototype super-agent conversation | Ask before acting; Act without asking | Separate conversation control; precedence unverified |
| CRM Manager source | Ask First; Auto-Pilot | Described CRM review/automatic modes |
| Oliver source | Human sign-off for handbook changes | Described process-governance boundary |
| Prospector live page | Rep reviews first email; follow-ups can be automatic | Specific outbound behavior to confirm in deployment |

<a id="document-agents-configuration-approvals-precedence"></a>
## Precedence is unresolved

The prototype does not define which setting wins if a conversation control and a tool mode disagree. It also does not demonstrate an approval queue. This does not prove the live product lacks those features.

Before writing an end-user procedure, confirm scope, default, persistence and enforcement for each setting. Check whether an administrator can restrict it and whether a user can override it.

<a id="document-agents-configuration-approvals-approval-contract"></a>
## Recommended approval contract



- State the exact action being approved and the destination system.
- Show the proposed record values or complete outbound content.
- Identify the reviewer and expiry or escalation rule.
- Define reject, edit, cancel and retry behavior.
- Record the result and the identity used for the external action.
- Specify what happens if the underlying record changes while approval is pending.

<a id="document-agents-configuration-approvals-approval-tests"></a>
## Recommended checks

Test a read-only task, a draft, a CRM update and a customer-facing message separately. Verify that an unapproved action does not execute and that a rejected item remains understandable.

The prototype’s Auto Run display default is not proof that agents execute without approval in production. That claim remains blocked until observed or explicitly confirmed by the implementation owner.

<a id="document-agents-configuration-approvals-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)

<a id="document-agents-configuration-triggers"></a>
# Triggers and schedules

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-configuration-triggers-overview"></a>
## Overview

An agent may start from a request, a source event or a schedule. The trigger mechanism and the action permission are separate decisions.

<a id="document-agents-configuration-triggers-trigger-types"></a>
## Trigger types described in sources



| Type | Examples in the product material | Confirm |
| --- | --- | --- |
| Activity-driven | New meeting, call or email context | Supported event and completion condition |
| Record change | Opportunity or account state changes | Fields, filters and event ordering |
| Scheduled | Forecast and portfolio review cadence | Timezone, recurrence and delivery |
| Direct request | Ask an agent to prepare or analyze work | User identity and permitted scope |

<a id="document-agents-configuration-triggers-schedule-rules"></a>
## Schedule rules to document

Record the timezone, recurrence, owner, effective start and destination. State how holidays, missed runs, daylight-saving changes and unavailable inputs are handled.

The prototype schedule dialog contains fixed timezone text and does not demonstrate persistence. Its displayed timezone is not a workspace policy, and a closed dialog does not prove a schedule was created.

<a id="document-agents-configuration-triggers-stop-conditions"></a>
## Stop and duplicate conditions

For event-driven work, confirm duplicate suppression, concurrent runs and what happens when a source record changes again. For customer outreach, confirm reply, opt-out, ownership change and manual-pause behavior.

The available sources do not establish a universal agent pause, global stop or automatic undo facility. Those must be verified before they appear as product instructions.

<a id="document-agents-configuration-triggers-trigger-acceptance"></a>
## Recommended trigger acceptance test



1. Create a known qualifying event in a controlled scope.
2. Verify one corresponding run and its input record.
3. Repeat or modify the event and observe duplicate handling.
4. Check a non-qualifying event that should not start work.
5. Pause or disable the verified trigger path and confirm the observed result.

<a id="document-agents-configuration-triggers-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-agents-configuration-knowledge"></a>
# Knowledge and data access

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-configuration-knowledge-overview"></a>
## Overview

An agent’s context can include organization process knowledge, source records and task-specific supporting material. Uploading a file and authorizing a connector are different operations.

<a id="document-agents-configuration-knowledge-knowledge-types"></a>
## Types of context



| Context | Purpose |
| --- | --- |
| Organization playbook | Approved operating rules, methodology and exceptions |
| Task-specific knowledge | Relevant supporting material for a particular job |
| Connected records | Accounts, contacts, opportunities and activity |
| Conversation evidence | Recordings, transcripts, email and messages within authorized scope |

<a id="document-agents-configuration-knowledge-source-controls"></a>
## Source and access controls

Confirm who may add, replace or remove knowledge, whether access follows the source system, and whether individual or team information can be exposed to other users.

The prototype lists import sources and accepted upload formats, but several import actions have no working behavior. A named source is not a confirmed connector; a prototype file-count label is not a commercial storage limit.

<a id="document-agents-configuration-knowledge-knowledge-lifecycle"></a>
## Lifecycle and updates

Document when changed knowledge becomes available to an agent, how obsolete content is replaced, what is retained after removal and whether historical outputs continue to cite the prior version.

Treat source provenance as part of the workflow. A current rule and an obsolete document can both be retrievable; the product owner must establish how conflicting or superseded material is handled.

<a id="document-agents-configuration-knowledge-knowledge-verification"></a>
## Recommended verification

Use a controlled document with a distinct fact, update that fact, and check subsequent answers and actions. Remove access and verify that the relevant user and agent cannot continue to retrieve restricted content.

Do not claim organization-wide knowledge isolation, automatic deletion from every derived store or a fixed refresh SLA from the current materials.

<a id="document-agents-configuration-knowledge-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-agents-configuration-run-history"></a>
# Run history and outputs

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-agents-configuration-run-history-overview"></a>
## Overview

Run history should help a user explain what an agent attempted, what it produced and what happened next.

<a id="document-agents-configuration-run-history-run-concepts"></a>
## Run concepts



| Concept | Meaning |
| --- | --- |
| Trigger | Why work began |
| Input context | The record and source information used |
| Attempt | A particular execution of the job |
| Output | The prepared answer, draft, proposed change or completed action |
| Review state | Whether a human decision is required or recorded |
| Destination result | What the receiving system accepted or rejected |

<a id="document-agents-configuration-run-history-history-source"></a>
## What the prototype establishes

The extraction records run lists, a details drawer, output presentations and an Agent Feed. Its runs are hand-written examples, predominantly successful, rather than production telemetry.

Those examples do not establish complete logging of every action, failure-state coverage, retention, pagination, export or an audit guarantee. A cleared feed row is also not evidence that a run or its source data was deleted.

<a id="document-agents-configuration-run-history-run-evidence"></a>
## Recommended evidence for a support case



- Agent and workflow name.
- Time, timezone and initiating event.
- Account, opportunity or meeting identifier.
- Observed output and destination.
- Approval or rejection state if shown.
- Error text or the point where expected behavior stopped.

<a id="document-agents-configuration-run-history-run-open-questions"></a>
## Rules to verify

Confirm failed, queued, running, cancelled and retried states; whether retries create new attempts; what the user can correct; and how long history is retained.

If native run IDs or logs are unavailable, describe the support process that actually exists. Do not invent a run export API or a retry button.

<a id="document-agents-configuration-run-history-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-apps"></a>
# Apps

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-overview"></a>
## Overview

Apps group related team workflows. Agents perform jobs that can contribute to those workflows; the app name and the agent name are not interchangeable.

<a id="document-apps-app-map"></a>
## App and agent relationship



| App | Workflow focus | Related agents |
| --- | --- | --- |
| Converse | Conversation capture, library and activity context | Meeting Assistant, Researcher and CRM Manager |
| Forecast | Opportunity management and forecasting | Forecaster, Deal Driver and CRM Manager |
| Engage | Prioritization and outreach execution | Prospector and reactivation workflows |
| Enable | Coaching and useful conversation examples | Coach and Content Curator |
| Retain | Customer health and account management | Portfolio Manager and Gold Digger |

<a id="document-apps-packaging"></a>
## Commercial grouping

The current pricing page uses role-based groups called Amplify, Converse, Sell and Grow. Sell includes Converse and Forecast; Grow includes Sell and Retain. Engage and Enable are presented as separately priced additions.

That summary is a dated website description. Exact entitlements, usage costs and any negotiated agreement must be confirmed for the workspace.

- [Plans, credits and pricing](#document-reference-plans-and-usage)

<a id="document-apps-explore"></a>
## Explore

- [Converse app](#document-apps-converse)
- [Forecast app](#document-apps-forecast)
- [Engage app](#document-apps-engage)
- [Enable app](#document-apps-enable)
- [Retain app](#document-apps-retain)

<a id="document-apps-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-apps-converse"></a>
# Converse app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-converse-overview"></a>
## Overview

Converse is the conversation-capture workspace: bring recordings, transcripts and related activity into a searchable source of customer context.

<a id="document-apps-converse-capture"></a>
## Capture sources

The current app page presents online meetings, phone and in-person capture alongside connected email and messages. Each channel depends on its supported integration and configuration.

For online meetings, distinguish native/botless recording from a visible note taker. A platform-level capture claim does not mean every meeting uses the same recording route.

<a id="document-apps-converse-library"></a>
## Conversation library and context

The app provides a place to find and review conversations and useful moments. Source activity can support meeting preparation, CRM updates, coaching and account-level understanding.

Searchability and downstream use depend on access to the original recording or transcript. Confirm which users can view, share or export each item and how source permissions are preserved.

<a id="document-apps-converse-recording"></a>
## Recording prerequisites

Confirm the connected calendar, meeting platform, organizer, organization recording setup and consent or recording indication. If a visible note taker must enter a lobby, it may need admission before recording can begin.

- [Recording modes and capture checks](#document-workflows-meeting-recording)

<a id="document-apps-converse-converse-limits"></a>
## Limits and verification

Storage, retention, upload formats, recording duration, transcription languages and processing times need current plan-specific evidence. The website’s advertised language count does not establish accuracy for every language or accent.

The app’s capture scope is separate from the permissions of agents that use the resulting context. Verify both before a wider rollout.

<a id="document-apps-converse-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/converse: [Converse – AI Conversation Capture | Oliv AI](https://www.oliv.ai/converse)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)

<a id="document-apps-forecast"></a>
# Forecast app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-forecast-overview"></a>
## Overview

Forecast organizes opportunity and pipeline work, including forecast boards, submissions, snapshots and deal context.

<a id="document-apps-forecast-opportunities"></a>
## Opportunity workspace

The current product presentation includes opportunity grids, qualification tracking, buying-committee context, deal risk, forecast boards, submissions, snapshots and change history.

A grid view, a forecast category and a submitted forecast are separate concepts. Define the current view and the source of each field before comparing two numbers.

<a id="document-apps-forecast-forecast-cadence"></a>
## Forecast operating cadence

Forecaster’s internal reference describes contributor preparation, manager review and an admin/observer configuration layer. Targets, measurements and cadence determine how the process is organized.

Document the actual hierarchy and rollup rule for the workspace. Multi-level approvals, custom formulas and automated mode transitions remain owner-confirmation items.

- [Forecaster agent](#document-agents-forecaster)
- [Forecast review workflow](#document-workflows-forecast-review)

<a id="document-apps-forecast-history"></a>
## Snapshots and change history

A snapshot preserves a historical view used for comparison; a submission records the forecast entered for a cycle; deal change history tracks movement in individual records. They should not be described as one feature.

Confirm snapshot frequency, retention and whether corrected source data changes historical views. The prototype includes multiple deal surfaces and does not establish which is the current production grid.

<a id="document-apps-forecast-forecast-boundaries"></a>
## Boundaries

Do not publish a fixed forecast-accuracy percentage or a guaranteed progression to autonomous operation from the available examples. Check results against the workspace’s actual history and sales motion.

<a id="document-apps-forecast-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/oliv-forecast: [Oliv Forecast – AI-Native Forecasting | Oliv AI](https://oliv.ai/oliv-forecast)

<a id="document-apps-engage"></a>
# Engage app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-engage-overview"></a>
## Overview

Engage is the workspace for account prioritization and outreach, using shared account context to organize the next action.

<a id="document-apps-engage-engagement-work"></a>
## Engagement work

The live page describes a ranked account queue, contextual next actions, email and LinkedIn workflows, plays, signals and flows, with optional calling or messaging channels.

A prioritized account is an input to a workflow. It does not by itself authorize sending or establish that a contact is eligible for outreach.

<a id="document-apps-engage-agents"></a>
## Agents in the workflow

Prospector prepares account prioritization and outreach. The public page also presents a reactivation workflow for stalled accounts. The exact current agent identity, stop conditions and supported sequence behavior require confirmation.

The Prospector page distinguishes a human-reviewed first email from automatic no-response follow-ups. Treat that as a specific described policy to verify, rather than assuming every channel has the same rule.

- [Prospector agent](#document-agents-prospector)
- [Prospecting workflow](#document-workflows-prospecting)

<a id="document-apps-engage-channels"></a>
## Channel configuration

Confirm the primary mailbox, additional mailboxes, phone number and calling allowance, and each selected messaging channel. Sending identity, ownership, stop conditions and external platform limits belong in the setup contract.

The current sources do not establish a universal rate limit, bounce threshold or opt-out implementation. Those require the current connector and sending-policy documentation.

<a id="document-apps-engage-pricing-conflict"></a>
## Current pricing conflict

The live Engage page shows a $39 starting figure in some sections and $29 in another. The main pricing page describes a $29 per-user monthly add-on to an app subscription.

This V1 preserves the conflict for commercial review and does not turn either page into a contractual quote. Use the approved order form and current commercial owner’s confirmation.

<a id="document-apps-engage-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-apps-enable"></a>
# Enable app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-enable-overview"></a>
## Overview

Enable groups coaching and enablement work: identify useful development goals and make strong conversation examples reusable.

<a id="document-apps-enable-enablement-loop"></a>
## The enablement loop

Coach supplies scoring, recommended focus areas and progress tracking. Content Curator supplies relevant examples from accessible recordings. Managers and enablement owners use those outputs to support development.

The current team page presents a multi-stage enablement process. This V1 describes the documented job relationship rather than claiming every illustrated tab or control is available.

<a id="document-apps-enable-scorecards"></a>
## Scorecards and goals

The internal material describes configurable scorecards and criteria, manager-reviewed monthly goals and weekly progress. Confirm the current scorecard library, weighting and supported team scope.

A call score is not a formal performance decision. Establish who can see the evidence and how a manager can correct a recommendation before using the workflow in a personnel process.

<a id="document-apps-enable-examples"></a>
## Clips and access

Define the intent for useful examples, the library destination and the people who may view or share the clip. A clip should preserve the link and context needed to understand the source conversation.

Historical backfill, external LMS syncing and detailed storage limits remain unresolved in the source material.

- [Coach](#document-agents-coach)
- [Content Curator](#document-agents-content-curator)

<a id="document-apps-enable-enable-packaging"></a>
## Packaging

Enable appears on the current pricing page as an add-on. A team’s enablement use case does not establish entitlement for every user; verify seats, credit costs and the selected package before rollout.

<a id="document-apps-enable-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/enablement: [Sales Enablement | Oliv AI](https://www.oliv.ai/enablement)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-apps-retain"></a>
# Retain app

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-apps-retain-overview"></a>
## Overview

Retain groups account-health and customer-management workflows around conversations, account context and renewal priorities.

<a id="document-apps-retain-account-workspace"></a>
## Account workspace

The current pricing presentation associates Retain with customer grids, health scorecards, churn risks, retention forecasting, product usage, support context, whitespace and stakeholder tracking.

These are capability categories. Verify the current integrations and data coverage before describing a specific usage event, support system or health formula.

<a id="document-apps-retain-review-work"></a>
## Review and intervention

Portfolio Manager prepares account and portfolio priorities with contributing evidence. The team decides the intervention, owner and due date. Gold Digger handles the distinct expansion-signal and warm-handoff motion.

A renewal risk score is an interpretation; a renewal forecast is a projection; a customer-facing action is another step. Explain the states separately in operational documentation.

- [Portfolio Manager](#document-agents-portfolio-manager)
- [Customer success workflow](#document-workflows-customer-success)
- [Expansion workflow](#document-workflows-expansion)

<a id="document-apps-retain-account-prerequisites"></a>
## Prerequisites

Confirm account ownership, renewal dates, health standards, the conversation sources and any usage or support connection. Identify which people may see individual accounts and full portfolio views.

Where a data feed is missing, state the resulting coverage limitation. Do not infer usage decline or support risk from an unavailable source.

<a id="document-apps-retain-retain-boundaries"></a>
## Boundaries

The available documentation does not establish a complete support-ticketing replacement, a universal churn prediction accuracy or every account-management automation. Resolve current CS agent names before publishing a broader roster.

<a id="document-apps-retain-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/customer-success: [Customer Success | Oliv AI](https://www.oliv.ai/customer-success)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-workflows"></a>
# Workflows

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-overview"></a>
## Overview

A workflow reference explains the intended outcome and the boundaries between steps. Exact production controls are included only when supported by current evidence.

<a id="document-workflows-workflow-map"></a>
## Choose a workflow



| Outcome | Primary references |
| --- | --- |
| Prepare and follow up a meeting | Meeting Assistant and Researcher |
| Capture a meeting | Converse and recording integrations |
| Maintain CRM fields | CRM Manager and field mapping |
| Review the pipeline | Deal Driver and Forecast |
| Prepare a forecast | Forecaster and forecast configuration |
| Run coaching | Coach and Content Curator |
| Act on expansion | Gold Digger and account ownership |
| Review customer health | Portfolio Manager and Retain |
| Prepare prospecting | Prospector and Engage |

<a id="document-workflows-workflow-evidence"></a>
## The workflow evidence standard

Each operational guide should identify prerequisites, trigger, steps, result, alternate paths, errors and permissions. A source-backed concept can be drafted before a current click path is confirmed, but it must not pretend an untested control works.

The recommended acceptance checks in this V1 are editorial test plans. They are distinct from documented product behavior.

<a id="document-workflows-explore"></a>
## Explore

- [Prepare and follow up a meeting](#document-workflows-meeting-preparation)
- [Record meetings with Oliv](#document-workflows-meeting-recording)
- [Review and apply CRM updates](#document-workflows-crm-updates)
- [Run a pipeline review](#document-workflows-pipeline-review)
- [Prepare and review a forecast](#document-workflows-forecast-review)
- [Run a coaching cycle](#document-workflows-coaching)
- [Review and hand off an expansion signal](#document-workflows-expansion)
- [Review customer health and renewals](#document-workflows-customer-success)
- [Prepare an account outreach workflow](#document-workflows-prospecting)

<a id="document-workflows-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-workflows-meeting-preparation"></a>
# Prepare and follow up a meeting

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-meeting-preparation-overview"></a>
## Overview

Use account, stakeholder and opportunity context to prepare for a conversation and turn it into reviewed follow-through.

<a id="document-workflows-meeting-preparation-before-you-start"></a>
## Before you start



- A supported calendar connection and the relevant meeting.
- Correct participant and account/opportunity association.
- Access to prior context and the active qualification framework.
- A recording or transcript for post-meeting outputs.

<a id="document-workflows-meeting-preparation-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Identify whether this is a first-contact meeting or an active-opportunity discussion.
2. Use Researcher for first-contact background and Meeting Assistant for deal-aware preparation.
3. Review the brief for participant roles, qualification gaps and a useful agenda.
4. After the conversation is processed, review the proposed follow-up and field changes.
5. Send or apply the result using the verified review path and check the destination.

<a id="document-workflows-meeting-preparation-result"></a>
## Expected result

The intended result is a useful brief before the meeting and a contextual draft, proposed updates and qualification flags afterward. The sources do not establish a single universal delivery time.

<a id="document-workflows-meeting-preparation-exceptions"></a>
## Variations and exceptions

Multiple deals, changed participants, cancelled events and unavailable recordings can change the result. Confirm how the current environment selects the opportunity and when it reruns preparation.

<a id="document-workflows-meeting-preparation-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Check a meeting with a known active opportunity.
- Check a first-contact meeting with no opportunity.
- Change a participant or time and observe refresh behavior.
- Confirm the approved brief timing and notification channel.
- Verify that an unsent draft remains distinct from a sent email.

<a id="document-workflows-meeting-preparation-related"></a>
## Related references



- [meeting assistant](#document-agents-meeting-assistant)
- [researcher](#document-agents-researcher)
- [meetings](#document-troubleshooting-meetings)

<a id="document-workflows-meeting-preparation-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack)
- HELP:9334685: [A quick guide to streamline your meetings with try@oliv.ai](https://help.oliv.ai/en/articles/9334685-a-quick-guide-to-streamline-your-meetings-with-try-oliv-ai)

<a id="document-workflows-meeting-recording"></a>
# Record meetings with Oliv

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-meeting-recording-overview"></a>
## Overview

Understand when Oliv records natively and when a visible note taker joins, then check the prerequisites for your meeting.

<a id="document-workflows-meeting-recording-before-you-start"></a>
## Before you start



- The relevant calendar and meeting platform connection.
- Organization-level native recording setup where required.
- Appropriate platform permissions and recording indication.
- The ability to admit a visible note taker when needed.

<a id="document-workflows-meeting-recording-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Identify who organized the meeting.
2. If the organization has native recording enabled and an internal user organized it, check the supported native recording setup.
3. If an external organizer owns the meeting, expect the visible note-taker route described by the current guide.
4. Admit the note taker from the lobby where required and confirm that recording started.
5. After processing, check the recording, transcript and meeting association.

<a id="document-workflows-meeting-recording-result"></a>
## Expected result

The May 2026 guide describes native/botless recording for internally organized meetings and a visible note taker for externally organized meetings, conditional on organization setup.

<a id="document-workflows-meeting-recording-exceptions"></a>
## Variations and exceptions

Without native setup, an internal meeting is not automatically evidence of botless capture. Host permissions, lobby controls, platform settings and unsupported meeting conditions can prevent recording.

<a id="document-workflows-meeting-recording-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Verify the behavior for an internally organized test meeting.
- Verify an externally organized meeting with a lobby.
- Check the recording indication visible to participants.
- Confirm the stop or exclusion control for the current client.
- Check the resulting recording access and sharing boundary.

<a id="document-workflows-meeting-recording-related"></a>
## Related references



- [converse](#document-apps-converse)
- [zoom](#document-integrations-zoom)
- [microsoft teams](#document-integrations-microsoft-teams)
- [meetings](#document-troubleshooting-meetings)

<a id="document-workflows-meeting-recording-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:8796010: [Copilot management options](https://help.oliv.ai/en/articles/8796010-copilot-management-options)
- WEB:/converse: [Converse – AI Conversation Capture | Oliv AI](https://www.oliv.ai/converse)

<a id="document-workflows-crm-updates"></a>
# Review and apply CRM updates

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-crm-updates-overview"></a>
## Overview

Use a source conversation to understand a proposed record change, review it under the configured policy and verify the written result.

<a id="document-workflows-crm-updates-before-you-start"></a>
## Before you start



- A supported CRM connection with the required object permissions.
- A known mapping for the target field.
- Correct activity-to-record association.
- A verified review or automatic-update policy.

<a id="document-workflows-crm-updates-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Open the relevant record and identify the source activity.
2. Review the proposed value and the evidence behind it.
3. Check the field type, destination object and whether newer human edits conflict.
4. Approve, edit or reject through the actual supported review flow.
5. Confirm the final value in the CRM and retain the available change evidence.

<a id="document-workflows-crm-updates-result"></a>
## Expected result

The intended result is a correctly associated, supported field or record update. A proposed value, a queued write and a CRM-accepted change are different states.

<a id="document-workflows-crm-updates-exceptions"></a>
## Variations and exceptions

Expired authorization, read-only fields, validation rules, conflicting edits and ambiguous records can prevent a write. Do not solve these by broadening permissions or merging records without the responsible owner’s decision.

<a id="document-workflows-crm-updates-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Test a standard field and a customer-specific mapped field.
- Reject one proposed change and confirm no write occurs.
- Compare the acting identity in the CRM with the agreed connector identity.
- Observe a validation failure and the actual retry/support behavior.
- Confirm the correction or recovery path for an incorrect update.

<a id="document-workflows-crm-updates-related"></a>
## Related references



- [crm manager](#document-agents-crm-manager)
- [salesforce](#document-integrations-salesforce)
- [hubspot](#document-integrations-hubspot)
- [approvals](#document-administration-approvals)

<a id="document-workflows-crm-updates-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9936748: [Step-by-Step Guide: How to capture Oliv data as fields in HubSpot by creating custom fields ?](https://help.oliv.ai/en/articles/9936748-step-by-step-guide-how-to-capture-oliv-data-as-fields-in-hubspot-by-creating-custom-fields)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)

<a id="document-workflows-pipeline-review"></a>
# Run a pipeline review

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-pipeline-review-overview"></a>
## Overview

Use Deal Driver’s prepared context to focus management time on deal changes, risk and decisions.

<a id="document-workflows-pipeline-review-before-you-start"></a>
## Before you start



- Current opportunity data and recent activity.
- Team ownership and the manager’s scope.
- Agreed risk criteria and review cadence.
- An understood destination for briefs and alerts.

<a id="document-workflows-pipeline-review-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Review the prepared team or per-rep view for the chosen period.
2. Identify changes and the evidence that makes a deal worth attention.
3. Separate qualification gaps from timing, engagement or ownership issues.
4. Decide the intervention and assign a responsible person.
5. Check that follow-through is recorded in the supported workflow.
6. Use Forecaster for the related forecast decision rather than treating every risk flag as a category change.

<a id="document-workflows-pipeline-review-result"></a>
## Expected result

The intended output is a management review with prioritized decisions and attributable next steps, rather than another manual status collection.

<a id="document-workflows-pipeline-review-exceptions"></a>
## Variations and exceptions

Stale CRM fields or missing conversations can produce an incomplete view. Confirm source coverage before concluding that a deal is inactive or that a rep failed to act.

<a id="document-workflows-pipeline-review-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Compare a flagged deal with its latest activity.
- Check manager visibility across the intended team only.
- Confirm the date range and timezone of a summary.
- Verify the path from a suggested action to an owned next step.

<a id="document-workflows-pipeline-review-related"></a>
## Related references



- [deal driver](#document-agents-deal-driver)
- [forecast](#document-apps-forecast)
- [forecast review](#document-workflows-forecast-review)

<a id="document-workflows-pipeline-review-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-workflows-forecast-review"></a>
# Prepare and review a forecast

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-forecast-review-overview"></a>
## Overview

Move from opportunity evidence to contributor submission, manager review and a historical record of the forecast.

<a id="document-workflows-forecast-review-before-you-start"></a>
## Before you start



- Configured categories, targets, measurements and cadence.
- Current opportunity values and ownership.
- A verified contributor/manager hierarchy.
- An agreed review and submission process.

<a id="document-workflows-forecast-review-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Check the board, period and measurement being forecast.
2. Review proposed deal category, value or timing changes with their evidence.
3. Accept, edit or reject recommendations using the supported controls.
4. Submit the contributor forecast where the operating mode requires it.
5. Review manager adjustments and the team rollup.
6. Preserve the submission or snapshot used for later comparison.

<a id="document-workflows-forecast-review-result"></a>
## Expected result

A forecast should identify the period, measurement, submission state and review scope. The outcome is not established merely by displaying a recommended number.

<a id="document-workflows-forecast-review-exceptions"></a>
## Variations and exceptions

Different periods, formulas, currency handling, stale records or incomplete rollup scope can explain a mismatch. Confirm those definitions before changing the forecast.

<a id="document-workflows-forecast-review-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Reconcile a contributor number to the included opportunities.
- Check a manager adjustment separately from a rep submission.
- Verify snapshot cadence and whether historical values are preserved.
- Confirm the criteria for changing automation modes.
- Measure accuracy against actual outcomes using an agreed definition.

<a id="document-workflows-forecast-review-related"></a>
## Related references



- [forecaster](#document-agents-forecaster)
- [forecast](#document-apps-forecast)
- [reporting cadences](#document-reference-reporting-cadences)

<a id="document-workflows-forecast-review-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/oliv-forecast: [Oliv Forecast – AI-Native Forecasting | Oliv AI](https://oliv.ai/oliv-forecast)

<a id="document-workflows-coaching"></a>
# Run a coaching cycle

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-coaching-overview"></a>
## Overview

Turn scored work into a manager-selected goal, weekly progress and relevant conversation examples.

<a id="document-workflows-coaching-before-you-start"></a>
## Before you start



- Sufficient recorded work for the relevant motion.
- Configured scorecards and criteria.
- An authorized manager and participating rep.
- Access to evidence and example clips.

<a id="document-workflows-coaching-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Review the available scoring and the evidence volume.
2. Read the proposed focus areas in the monthly review.
3. Choose, edit or replace the goal before it reaches the rep.
4. Agree what progress against that goal means.
5. Review weekly progress with supporting examples.
6. Close the cycle and select the next development priority.

<a id="document-workflows-coaching-result"></a>
## Expected result

The documented coaching loop combines analysis, a human goal decision and progress tracking. A scorecard alone is not the entire coaching process.

<a id="document-workflows-coaching-exceptions"></a>
## Variations and exceptions

Sparse or unrepresentative activity can produce weak patterns. The source leaves precise thresholds and some team scopes unresolved; confirm them before making performance judgments.

<a id="document-workflows-coaching-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Check the manager review step before goal delivery.
- Verify who can see the rep’s underlying activity.
- Correct a scoring error and observe later reporting.
- Confirm whether the workflow supports the chosen role and motion.
- Keep illustrative improvement percentages separate from measured results.

<a id="document-workflows-coaching-related"></a>
## Related references



- [coach](#document-agents-coach)
- [content curator](#document-agents-content-curator)
- [enable](#document-apps-enable)

<a id="document-workflows-coaching-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-workflows-expansion"></a>
# Review and hand off an expansion signal

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-expansion-overview"></a>
## Overview

Use Gold Digger’s evidence to confirm an expansion opportunity and prepare an owned, warm introduction.

<a id="document-workflows-expansion-before-you-start"></a>
## Before you start



- Accessible customer conversations and account context.
- Known account and commercial ownership.
- The current customer footprint and relevant adjacent use cases.
- An approved handoff and communication policy.

<a id="document-workflows-expansion-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Review the detected signal and the original conversation moment.
2. Check whether it represents an actual adjacent need or a routine comment.
3. Confirm the stakeholder, account context and responsible commercial owner.
4. Review the warm-introduction draft with the CSM or designated owner.
5. Send or delegate through the approved route.
6. Confirm the opportunity record and follow-through without creating duplicates.

<a id="document-workflows-expansion-result"></a>
## Expected result

The intended outcome is a reviewed signal with an owned next step. Detection, qualification, introduction and commercial conversion are different stages.

<a id="document-workflows-expansion-exceptions"></a>
## Variations and exceptions

Conflicting account ownership, several expansion opportunities or a sensitive customer situation can change the handoff. The available sources do not establish a universal automatic qualification or sending policy.

<a id="document-workflows-expansion-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Verify the source quotation and timestamp.
- Check the proposed stakeholder and existing opportunity records.
- Reject a signal and observe its resulting state.
- Confirm who reviews and who sends the introduction.
- Check the recorded opportunity’s source and ownership.

<a id="document-workflows-expansion-related"></a>
## Related references



- [gold digger](#document-agents-gold-digger)
- [portfolio manager](#document-agents-portfolio-manager)
- [retain](#document-apps-retain)

<a id="document-workflows-expansion-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-workflows-customer-success"></a>
# Review customer health and renewals

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-customer-success-overview"></a>
## Overview

Use portfolio context to identify at-risk accounts, choose interventions and prepare CS management reviews.

<a id="document-workflows-customer-success-before-you-start"></a>
## Before you start



- Account ownership and renewal dates.
- Current customer conversation and engagement context.
- Configured health criteria.
- Usage/support connections where the workflow depends on them.

<a id="document-workflows-customer-success-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Review the account or portfolio view for the selected period.
2. Read the evidence behind a health or renewal-risk interpretation.
3. Distinguish account risk from expansion potential and CSM coaching needs.
4. Assign an intervention owner and a concrete next step.
5. Prepare the manager or leadership review with the relevant account context.
6. Check progress and update the supported record or task workflow.

<a id="document-workflows-customer-success-result"></a>
## Expected result

The intended result is a prioritized, evidence-bearing CS review. A color, score or projected renewal category is not a completed intervention.

<a id="document-workflows-customer-success-exceptions"></a>
## Variations and exceptions

Missing usage feeds, outdated renewal data or unclear stakeholder ownership can weaken the view. A support ticket trend cannot be assumed when the support source is not connected.

<a id="document-workflows-customer-success-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Compare a risk flag with current conversations and usage evidence.
- Check access to individual accounts versus portfolio totals.
- Confirm the definitions of renewal categories and health criteria.
- Verify how next actions are assigned and tracked.
- Resolve CS role and agent naming before exposing a broader roster.

<a id="document-workflows-customer-success-related"></a>
## Related references



- [portfolio manager](#document-agents-portfolio-manager)
- [retain](#document-apps-retain)
- [expansion](#document-workflows-expansion)

<a id="document-workflows-customer-success-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-workflows-prospecting"></a>
# Prepare an account outreach workflow

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-workflows-prospecting-overview"></a>
## Overview

Review account priority and a point of view before starting an approved outreach motion.

<a id="document-workflows-prospecting-before-you-start"></a>
## Before you start



- The approved ICP and account territory.
- Account ownership and available first-party context.
- Configured channels and an authorized sending identity.
- Approved review, reply and stop conditions.

<a id="document-workflows-prospecting-steps"></a>
## Workflow sequence

This sequence describes the documented handoffs. Verify current production controls before using it as a click-by-click end-user procedure.

1. Review why the account is prioritized now.
2. Check the account context and proposed point of view.
3. Review the opening communication before sending.
4. Confirm the follow-up policy for the chosen channel.
5. Observe replies, exclusions and ownership changes through the supported workflow.

<a id="document-workflows-prospecting-result"></a>
## Expected result

The intended output is a contextual, reviewed start to outreach. Account ranking does not itself establish contact eligibility or a promise of conversion.

<a id="document-workflows-prospecting-exceptions"></a>
## Variations and exceptions

A reply through another channel, an ownership change or an excluded contact can affect subsequent actions. The current sources do not establish every sequence stop condition or cross-channel reconciliation rule.

<a id="document-workflows-prospecting-acceptance-checks"></a>
## Recommended acceptance checks

The following checks are proposed validation work, not claims that the product already provides every control mentioned.

- Review the account and contact selection.
- Verify that the first message requires the described human decision.
- Test the configured reply and opt-out path before scaling.
- Confirm the actual volume, channel and credit limits.
- Keep preparation and sending permissions separate.

<a id="document-workflows-prospecting-related"></a>
## Related references



- [prospector](#document-agents-prospector)
- [engage](#document-apps-engage)
- [approvals](#document-administration-approvals)

<a id="document-workflows-prospecting-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)
- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage)

<a id="document-integrations"></a>
# Integrations

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-overview"></a>
## Overview

An integration reference must explain its job, authentication, scope, data direction, setup, failure behavior and removal. A logo alone cannot supply those details.

<a id="document-integrations-integration-types"></a>
## Types of integration



| Type | Examples | Main questions |
| --- | --- | --- |
| CRM | Salesforce, HubSpot | Objects, fields, write identity and sync conflicts |
| Calendar | Google and Microsoft calendars | Meeting coverage, organizer and attendee access |
| Recording | Zoom, Teams and Meet workflows | Native setup, visible note taker and recording permissions |
| Collaboration | Slack and Teams | Destinations, app permissions and message controls |
| Email and outreach | Connected mailboxes and channels | Read scope, drafts, sending and stop rules |
| Additional business context | Usage, support and enrichment sources | Events, association and historical coverage |

<a id="document-integrations-support-levels"></a>
## Read support levels correctly

This V1 distinguishes a working setup described by a dated help article, a current marketed integration and a vendor named only in a picker or example. None of those establishes a fresh end-to-end test for your workspace.

The current website’s broad integration count is not used as a connector-by-connector support matrix. Each connector still needs its own verified data and permission contract.

<a id="document-integrations-integration-contract"></a>
## Required connector contract



- Authentication method and installing role.
- Read and write scopes, object types and field restrictions.
- Sync direction, cadence and source-of-truth rule.
- Historical import and refresh behavior.
- Rate limits, errors, retries and duplicate handling.
- Disconnect procedure and retained-data behavior.
- Plan, add-on and credit implications.

<a id="document-integrations-explore"></a>
## Explore

- [Salesforce integration](#document-integrations-salesforce)
- [HubSpot integration](#document-integrations-hubspot)
- [Zoom integration](#document-integrations-zoom)
- [Microsoft Teams integration](#document-integrations-microsoft-teams)
- [Google Meet integration](#document-integrations-google-meet)
- [Slack integration](#document-integrations-slack)
- [Outlook and Microsoft 365 integration](#document-integrations-outlook)
- [Google Calendar and Gmail integration](#document-integrations-google-calendar)
- [Other integrations and channels](#document-integrations-other-systems)

<a id="document-integrations-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)

<a id="document-integrations-salesforce"></a>
# Salesforce integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-salesforce-overview"></a>
## Overview

Use Salesforce account, contact and opportunity context and apply supported CRM updates.

<a id="document-integrations-salesforce-supported-purpose"></a>
## Purpose and available evidence

The dated Help Center describes an administrator connection and managed-package installation, followed by coordination with Oliv. The agent material describes account/contact maintenance, activity and task context, and standard, methodology and custom field updates.

<a id="document-integrations-salesforce-data-direction"></a>
## Data direction and permissions

The intended workflow reads CRM context and can write supported updates. The exact object, field and permission matrix is not available in the current sources.

<a id="document-integrations-salesforce-setup"></a>
## Setup prerequisites

Obtain the current installation link and package version from the implementation owner. Confirm the installing role and organization policy; do not treat the older article’s package link or broad installation setting as a current default.

<a id="document-integrations-salesforce-disconnect"></a>
## Disconnect and retained data

The dated guide directs removal requests through Oliv support. Verify the current disconnect procedure, token revocation and effect on retained data.

<a id="document-integrations-salesforce-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which objects, custom objects and associations are supported?
- Which Salesforce identity performs each write?
- How do validation rules, duplicate rules and field-level security affect updates?
- How are conflicts with human edits resolved?
- What are the API consumption and retry rules?
- Which package and scopes are current?

<a id="document-integrations-salesforce-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-salesforce-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:4940626: [Install Oliv's Salesforce Integration](https://help.oliv.ai/en/articles/4940626-install-oliv-s-salesforce-integration)

<a id="document-integrations-hubspot"></a>
# HubSpot integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-hubspot-overview"></a>
## Overview

Use HubSpot company, contact and deal context and populate mapped fields through the supported connection.

<a id="document-integrations-hubspot-supported-purpose"></a>
## Purpose and available evidence

The dated integration guide describes connecting HubSpot and coordinating with Oliv. A separate September 2024 article describes creating a deal property and adding it to the deal view for captured Oliv information.

<a id="document-integrations-hubspot-data-direction"></a>
## Data direction and permissions

Reading CRM context and writing mapped values are described. Exact object coverage, property types, associations and conflict rules require a current mapping reference.

<a id="document-integrations-hubspot-setup"></a>
## Setup prerequisites

Confirm the installing user, requested scopes and the properties Oliv expects. The older guide recommends rich-text properties for its example; that is not a universal type rule for every field or current HubSpot account.

<a id="document-integrations-hubspot-disconnect"></a>
## Disconnect and retained data

The dated integration article routes removal through support. Verify the current process and whether existing values, source links or historical data remain.

<a id="document-integrations-hubspot-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which deal, company and contact properties are supported?
- Are custom objects and multiple associations supported?
- Which property types and enumerations are writable?
- What maps an activity to the correct deal?
- How are failed validations and concurrent updates handled?
- Which updates need human review?

<a id="document-integrations-hubspot-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-hubspot-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8671280: [Oliv <> HubSpot Integrations](https://help.oliv.ai/en/articles/8671280-oliv-hubspot-integrations)
- HELP:9936748: [Step-by-Step Guide: How to capture Oliv data as fields in HubSpot by creating custom fields ?](https://help.oliv.ai/en/articles/9936748-step-by-step-guide-how-to-capture-oliv-data-as-fields-in-hubspot-by-creating-custom-fields)

<a id="document-integrations-zoom"></a>
# Zoom integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-zoom-overview"></a>
## Overview

Capture supported Zoom meetings and use recordings or meeting context in Oliv workflows.

<a id="document-integrations-zoom-supported-purpose"></a>
## Purpose and available evidence

The Help Center distinguishes a meeting-bot integration from an in-meeting app. A May 2026 guide adds the conditional distinction between native recording for internally organized meetings and a visible note taker for externally organized meetings.

<a id="document-integrations-zoom-data-direction"></a>
## Data direction and permissions

Meeting and recording context flows into Oliv. The in-meeting interface described in the older guide is not evidence of every current write or sharing capability.

<a id="document-integrations-zoom-setup"></a>
## Setup prerequisites

Confirm which Zoom application and organization recording mode are being enabled. The admin-level guide requires a Zoom administrator and coordination with Oliv; exact current scopes must be checked against the installed application.

<a id="document-integrations-zoom-disconnect"></a>
## Disconnect and retained data

Use the current approved Zoom/Oliv disconnect process and confirm recording access after revocation. The older guide describes support-assisted removal.

<a id="document-integrations-zoom-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Who organized the meeting?
- Is native recording enabled for this organization?
- Which host/admin permissions apply?
- What happens in the lobby or without host admission?
- Who can access and share the resulting recording?
- Which scopes are requested by the current app version?

<a id="document-integrations-zoom-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-zoom-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8638345: [Oliv <> Zoom integrations](https://help.oliv.ai/en/articles/8638345-oliv-zoom-integrations)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)

<a id="document-integrations-microsoft-teams"></a>
# Microsoft Teams integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-microsoft-teams-overview"></a>
## Overview

Use supported Teams meeting recording and collaboration routes in Oliv.

<a id="document-integrations-microsoft-teams-supported-purpose"></a>
## Purpose and available evidence

The current recording guide includes Teams in its native-recording explanation when the organization is configured for that mode. Older integration material separately describes a Teams shared-channel route for notifications.

<a id="document-integrations-microsoft-teams-data-direction"></a>
## Data direction and permissions

Meeting capture and message delivery are different connections. Enabling one does not establish the permissions or availability of the other.

<a id="document-integrations-microsoft-teams-setup"></a>
## Setup prerequisites

Confirm tenant administration, organization recording setup, meeting organizer conditions and the intended collaboration destination. Obtain current tenant-specific steps rather than applying the older generic no-integration-needed wording to native recording.

<a id="document-integrations-microsoft-teams-disconnect"></a>
## Disconnect and retained data

Confirm how each meeting and collaboration connection is revoked and what imported recordings or messages remain available.

<a id="document-integrations-microsoft-teams-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which tenant and accounts are authorized?
- Which meetings use native capture versus a visible note taker?
- What happens for external organizers and guests?
- Which users or channels receive output?
- Are external/shared channels supported for this workflow?
- How are access and retention handled after disconnect?

<a id="document-integrations-microsoft-teams-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-microsoft-teams-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)

<a id="document-integrations-google-meet"></a>
# Google Meet integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-google-meet-overview"></a>
## Overview

Capture supported Google Meet meetings through the configured calendar and recording workflow.

<a id="document-integrations-google-meet-supported-purpose"></a>
## Purpose and available evidence

The older integration guide includes Google Meet in the meeting-capture workflow after calendar connection. The newer recording guide explains organizer-dependent modes but does not establish every platform-specific native capability.

<a id="document-integrations-google-meet-data-direction"></a>
## Data direction and permissions

The intended result is meeting content available for Oliv processing and associated with the relevant participants and business context.

<a id="document-integrations-google-meet-setup"></a>
## Setup prerequisites

Confirm the supported capture route for the organization, the calendar connection, organizer identity and admission requirements. Do not assume that Zoom’s native-recording setup applies unchanged to Meet.

<a id="document-integrations-google-meet-disconnect"></a>
## Disconnect and retained data

Confirm how calendar access and the meeting-capture route are disabled separately, and what happens to existing recordings.

<a id="document-integrations-google-meet-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which Meet capture modes are supported today?
- What happens when an external organizer controls admission?
- How are recurring, cancelled and private meetings handled?
- Who may stop or exclude capture?
- How is a meeting linked to the correct opportunity?
- What is retained after the connection is removed?

<a id="document-integrations-google-meet-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-google-meet-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)

<a id="document-integrations-slack"></a>
# Slack integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-slack-overview"></a>
## Overview

Deliver supported briefs, alerts and review-related messages into the team’s collaboration workflow.

<a id="document-integrations-slack-supported-purpose"></a>
## Purpose and available evidence

The revenue-workflow help material describes meeting notifications and summaries, and agent documents describe alerts and briefs. A much older Slack bot manages status and Do Not Disturb from a calendar; that legacy product must be kept separate.

<a id="document-integrations-slack-data-direction"></a>
## Data direction and permissions

Message delivery into Slack and importing Slack activity as context are distinct capabilities. Confirm which is enabled, the destination and the allowed source history.

<a id="document-integrations-slack-setup"></a>
## Setup prerequisites

Identify the workspace, installing role, application and intended user/channel destinations. Verify app installation or a support-assisted shared-channel route for the actual workflow.

<a id="document-integrations-slack-disconnect"></a>
## Disconnect and retained data

Confirm how to disconnect the app or shared channel and how to stop each notification type. Removing a Slack connection does not itself establish deletion of imported context.

<a id="document-integrations-slack-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which users and channels can receive each message?
- Which app permissions are requested?
- Is Slack context imported, or are messages only delivered?
- What history and private/shared-channel coverage applies?
- Where do approvals appear, if Slack approvals are supported?
- What happens when a user leaves or a channel is archived?

<a id="document-integrations-slack-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-slack-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack)
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)

<a id="document-integrations-outlook"></a>
# Outlook and Microsoft 365 integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-outlook-overview"></a>
## Overview

Connect supported Microsoft calendars or mailboxes and use the current Outlook add-in workflow where available.

<a id="document-integrations-outlook-supported-purpose"></a>
## Purpose and available evidence

The Help Center contains Outlook add-in installation and troubleshooting material from 2020, along with a later calendar-access article. These establish historical support context, not a verified current client/tenant compatibility matrix.

<a id="document-integrations-outlook-data-direction"></a>
## Data direction and permissions

Calendar discovery, email context and add-in controls are separate access paths. Confirm the selected account and application consent for each.

<a id="document-integrations-outlook-setup"></a>
## Setup prerequisites

Use current tenant-approved installation and consent instructions. Do not reissue the old workaround that publishes a work calendar and imports it into a personal account without security-owner review.

<a id="document-integrations-outlook-disconnect"></a>
## Disconnect and retained data

Confirm how to revoke calendar/mail access and remove the add-in separately. Organization consent and a local add-in installation are not the same state.

<a id="document-integrations-outlook-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Which Outlook clients and Microsoft tenant policies are supported?
- Is administrator consent required?
- Which calendars and mail folders are in scope?
- How is timezone determined?
- What is the approved solution when tenant access is restricted?
- What recording controls are available in the current add-in?

<a id="document-integrations-outlook-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-outlook-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:3810034: [Install Oliv's Add-in for Outlook](https://help.oliv.ai/en/articles/3810034-install-oliv-s-add-in-for-outlook)
- HELP:4467669: [Missing "Get Add-Ins" button in Outlook](https://help.oliv.ai/en/articles/4467669-missing-get-add-ins-button-in-outlook)
- HELP:9144560: [Overcome Outlook Calendar Access Restrictions](https://help.oliv.ai/en/articles/9144560-overcome-outlook-calendar-access-restrictions)

<a id="document-integrations-google-calendar"></a>
# Google Calendar and Gmail integration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-google-calendar-overview"></a>
## Overview

Provide meeting and email context for supported preparation, capture and follow-up workflows.

<a id="document-integrations-google-calendar-supported-purpose"></a>
## Purpose and available evidence

The integration material describes calendar and Gmail connections. A separate guide addresses Calendly’s participant-recognition setup. The agent documents use calendar events and conversation context for preparation.

<a id="document-integrations-google-calendar-data-direction"></a>
## Data direction and permissions

Meeting metadata, email content, draft creation and sending are distinct permissions and should be documented separately.

<a id="document-integrations-google-calendar-setup"></a>
## Setup prerequisites

Confirm the connected Google account, requested scopes, included calendars and mailbox coverage. Verify attendee recognition for scheduling tools used by the organization.

<a id="document-integrations-google-calendar-disconnect"></a>
## Disconnect and retained data

Confirm account revocation, capture exclusions, disconnected-mailbox behavior and retained-data policy. Do not assume logging out revokes every integration.

<a id="document-integrations-google-calendar-connector-questions"></a>
## Connector contract to confirm

These are unresolved implementation questions. The list is not a claim that all of the named controls already exist.

- Are secondary or shared calendars included?
- How are aliases and multiple participant identities matched?
- What Gmail read/draft/send scopes are required?
- How are private events and attachments handled?
- How does rescheduling affect a prepared brief?
- What changes when Calendly supplies attendee details?

<a id="document-integrations-google-calendar-verify-connection"></a>
## Recommended connection check

Use a controlled source record or meeting, confirm that it arrives with the right owner and associations, and inspect any downstream write or notification. Repeat with a permission or validation exception and record the observed error path.

Record the integration version, scopes, tested objects, plan and verification date. Keep that acceptance record current when the provider changes its API or permissions.

<a id="document-integrations-google-calendar-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:10511705: [How to configure Calendly to work with Oliv](https://help.oliv.ai/en/articles/10511705-how-to-configure-calendly-to-work-with-oliv)

<a id="document-integrations-other-systems"></a>
# Other integrations and channels

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-integrations-other-systems-overview"></a>
## Overview

The broader product material names recording, enrichment, collaboration, support, usage and outreach systems beyond the core setup references.

<a id="document-integrations-other-systems-named-systems"></a>
## Named categories

Examples include other CRMs, call recorders, enrichment sources, customer-success systems, warehouses and messaging channels. A vendor name may represent import, export, agent tooling, enrichment or a proposed integration.

The current V1 does not turn a marketing list or a prototype picker into a verified support statement. Ask for a connector-specific contract before relying on a required object or action.

<a id="document-integrations-other-systems-request-connector"></a>
## Information to request



- The exact vendor product and connection type.
- Current support and rollout state.
- Authentication and permissions.
- Supported objects, fields, events and actions.
- Direction, cadence and historical import.
- Failure, rate-limit and removal behavior.
- Commercial prerequisites and usage charges.

<a id="document-integrations-other-systems-custom-work"></a>
## Custom integration work

If the desired connection is custom or service-assisted, document the implementation owner, supported use case and maintenance responsibility. Do not describe a planned custom connection as a generally available native integration.

The MCP and API reference records the current interface documentation gap.

- [API and MCP](#document-reference-api-and-mcp)

<a id="document-integrations-other-systems-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations)

<a id="document-teams"></a>
# Documentation by team

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-overview"></a>
## Overview

The current website presents eight team entry points. This documentation maps those audiences to tasks, agents, apps and the setup decisions that matter.

<a id="document-teams-team-scope"></a>
## Team scope

Team pages explain jobs and handoffs. They do not establish an RBAC role, a complete app entitlement or availability of every illustrated agent.

Begin with the relevant team, then follow the operational reference for the chosen workflow. A cross-functional handoff should identify one accountable owner for each action.

<a id="document-teams-team-ownership"></a>
## Cross-functional ownership

An AE, CSM and account manager may all have context for the same customer. Agree who owns an expansion introduction, a renewal intervention or a change to the CRM before enabling automatic follow-through.

The same principle applies between RevOps, managers and enablement: configuring the process, reviewing a forecast and selecting a coaching goal are distinct responsibilities.

<a id="document-teams-explore"></a>
## Explore

- [Sales Development](#document-teams-sales-development)
- [Sales](#document-teams-sales)
- [Sales Engineering](#document-teams-sales-engineering)
- [Customer Onboarding](#document-teams-onboarding)
- [Customer Success](#document-teams-customer-success)
- [Account Management](#document-teams-account-management)
- [Enablement](#document-teams-enablement)
- [Revenue Operations](#document-teams-revops)

<a id="document-teams-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/)

<a id="document-teams-sales-development"></a>
# Sales Development

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-sales-development-overview"></a>
## Overview

Prepare a prioritized account motion so BDRs and SDRs can spend more time in relevant customer conversations.

<a id="document-teams-sales-development-jobs"></a>
## Primary jobs



- Review the account pool and the reason to work an account now.
- Prepare a point of view, contact context and an opening message.
- Review the first outreach and monitor the supported follow-up motion.
- Use meeting and call context to improve the next handoff.

<a id="document-teams-sales-development-agent-map"></a>
## Relevant agents

Prospector, Researcher, Olivia. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-sales-development-ownership"></a>
## Ownership and handoffs

Define which accounts belong to the BDR, when a qualified conversation moves to an AE and how duplicates or existing customer relationships are handled.

<a id="document-teams-sales-development-team-boundaries"></a>
## Scope and limitations

The current public page illustrates territory and work-allocation scenarios. Those examples do not establish a guaranteed number of accounts worked, response rate or automated calling capability.

<a id="document-teams-sales-development-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [prospector](#document-agents-prospector)
- [researcher](#document-agents-researcher)
- [engage](#document-apps-engage)
- [prospecting](#document-workflows-prospecting)

<a id="document-teams-sales-development-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/sales-development: [Sales Development – Work All 500 Accounts | Oliv AI](https://www.oliv.ai/sales-development)

<a id="document-teams-sales"></a>
# Sales

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-sales-overview"></a>
## Overview

Keep opportunity context, meeting preparation, follow-up and management awareness connected across the deal cycle.

<a id="document-teams-sales-jobs"></a>
## Primary jobs



- Prepare opportunity-linked meetings with current stakeholder and qualification context.
- Review follow-up drafts and proposed CRM changes.
- Identify deal risk and decide the next intervention.
- Submit and review the forecast in the configured cadence.

<a id="document-teams-sales-agent-map"></a>
## Relevant agents

Olivia, Meeting Assistant, CRM Manager, Deal Driver, Forecaster. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-sales-ownership"></a>
## Ownership and handoffs

Keep the seller’s next action, manager intervention and RevOps configuration responsibilities distinct. A pipeline alert is not an approved CRM change.

<a id="document-teams-sales-team-boundaries"></a>
## Scope and limitations

The source material describes the operating workflow, not a promise that every account is complete or that a risk interpretation predicts the outcome.

<a id="document-teams-sales-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [olivia](#document-agents-olivia)
- [meeting preparation](#document-workflows-meeting-preparation)
- [crm updates](#document-workflows-crm-updates)
- [pipeline review](#document-workflows-pipeline-review)

<a id="document-teams-sales-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/sales: [Automate Your Sales Process with AI Agents | Oliv AI](https://www.oliv.ai/sales)

<a id="document-teams-sales-engineering"></a>
# Sales Engineering

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-sales-engineering-overview"></a>
## Overview

Use the opportunity’s technical and commercial context to prepare demos, support evaluations and preserve handoffs.

<a id="document-teams-sales-engineering-jobs"></a>
## Primary jobs



- Review discovery, technical requirements and stakeholder context before a demo.
- Identify gaps or blockers that need an explicit owner.
- Keep evaluation context connected to the opportunity.
- Prepare a clear handoff from technical sale to implementation.

<a id="document-teams-sales-engineering-agent-map"></a>
## Relevant agents

Meeting Assistant, Olivia, Relevant specialist catalog entries. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-sales-engineering-ownership"></a>
## Ownership and handoffs

The handoff should identify the agreed scope, dependencies, customer success criteria and unresolved technical issues. These are recommended handoff fields until the actual product template is verified.

<a id="document-teams-sales-engineering-team-boundaries"></a>
## Scope and limitations

The current team page names specialist jobs beyond the detailed agent references. This V1 does not invent a working demo, POC or technical-handoff agent configuration from those names alone.

<a id="document-teams-sales-engineering-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [meeting assistant](#document-agents-meeting-assistant)
- [context graph](#document-platform-context-graph)
- [marketplace](#document-agents-marketplace)
- [onboarding](#document-teams-onboarding)

<a id="document-teams-sales-engineering-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/sales-engineering: [Sales Engineering – Full Deal Context for SEs | Oliv AI](https://www.oliv.ai/sales-engineering)

<a id="document-teams-onboarding"></a>
# Customer Onboarding

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-onboarding-overview"></a>
## Overview

Preserve the sold scope and customer context while tracking implementation progress and ownership.

<a id="document-teams-onboarding-jobs"></a>
## Primary jobs



- Read the commercial and technical handoff.
- Review account implementation context and outstanding dependencies.
- Prepare customer and internal updates from the current state.
- Identify a blocked task and assign an accountable next step.

<a id="document-teams-onboarding-agent-map"></a>
## Relevant agents

Olivia, Portfolio Manager, Catalogued onboarding specialists. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-onboarding-ownership"></a>
## Ownership and handoffs

Keep the customer-facing success plan aligned with internal ownership and the current implementation state. Confirm which records, boards or external tools are authoritative.

<a id="document-teams-onboarding-team-boundaries"></a>
## Scope and limitations

The live page illustrates implementation tracking and briefing. Task-state automation, board fields, escalation rules and the exact onboarding specialist roster still require owner confirmation.

<a id="document-teams-onboarding-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [olivia](#document-agents-olivia)
- [portfolio manager](#document-agents-portfolio-manager)
- [retain](#document-apps-retain)
- [process graph](#document-platform-process-graph)

<a id="document-teams-onboarding-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/onboarding: [Onboarding | Oliv AI](https://www.oliv.ai/onboarding)

<a id="document-teams-customer-success"></a>
# Customer Success

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-customer-success-overview"></a>
## Overview

Review account health, understand renewal risk and prepare owned interventions before a customer situation escalates.

<a id="document-teams-customer-success-jobs"></a>
## Primary jobs



- Review the account’s conversation, engagement and usage context.
- Read the evidence behind a risk or health interpretation.
- Prepare the CSM and manager review.
- Coordinate a renewal intervention or an expansion handoff.

<a id="document-teams-customer-success-agent-map"></a>
## Relevant agents

Portfolio Manager, Olivia, Gold Digger. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-customer-success-ownership"></a>
## Ownership and handoffs

Separate the CS account owner, commercial renewal owner and expansion owner. A useful recommendation includes the customer context, responsible person and next step.

<a id="document-teams-customer-success-team-boundaries"></a>
## Scope and limitations

Usage and support coverage depends on connected sources. The current material does not establish a universal health formula, complete CS-platform replacement or guaranteed churn prediction.

<a id="document-teams-customer-success-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [portfolio manager](#document-agents-portfolio-manager)
- [customer success](#document-workflows-customer-success)
- [expansion](#document-workflows-expansion)
- [retain](#document-apps-retain)

<a id="document-teams-customer-success-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/customer-success: [Customer Success | Oliv AI](https://www.oliv.ai/customer-success)

<a id="document-teams-account-management"></a>
# Account Management

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-account-management-overview"></a>
## Overview

Connect customer needs, account footprint and expansion signals to an accountable commercial next step.

<a id="document-teams-account-management-jobs"></a>
## Primary jobs



- Review the customer’s current footprint and stakeholder context.
- Inspect a candidate expansion signal against the original conversation.
- Prepare a warm introduction and relevant point of view.
- Track the confirmed opportunity and avoid duplicate outreach.

<a id="document-teams-account-management-agent-map"></a>
## Relevant agents

Gold Digger, Prospector, Portfolio Manager, Olivia. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-account-management-ownership"></a>
## Ownership and handoffs

Agree when a CSM introduces an AE or account manager and who reviews and sends the message. A detected signal is not itself permission to contact a new stakeholder.

<a id="document-teams-account-management-team-boundaries"></a>
## Scope and limitations

Whitespace scores, monetary examples and trigger illustrations on the live page are not measured expansion revenue or a complete implementation specification.

<a id="document-teams-account-management-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [gold digger](#document-agents-gold-digger)
- [prospector](#document-agents-prospector)
- [expansion](#document-workflows-expansion)
- [retain](#document-apps-retain)

<a id="document-teams-account-management-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/account-management: [Account Management – Catch Expansion Signals | Oliv AI](https://www.oliv.ai/account-management)

<a id="document-teams-enablement"></a>
# Enablement

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-enablement-overview"></a>
## Overview

Use observed work to select development priorities and make useful examples available to the people who need them.

<a id="document-teams-enablement-jobs"></a>
## Primary jobs



- Review scoring and proposed coaching focus areas.
- Support manager selection of an appropriate goal.
- Curate examples that illustrate the target behavior.
- Track progress and identify which interventions need adjustment.

<a id="document-teams-enablement-agent-map"></a>
## Relevant agents

Coach, Content Curator, Oliver. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-enablement-ownership"></a>
## Ownership and handoffs

The manager owns the coaching goal; enablement supports materials and the development process; process owners define the standards being assessed.

<a id="document-teams-enablement-team-boundaries"></a>
## Scope and limitations

Recorded activity, sufficient evidence volume and appropriate access are prerequisites. Do not use demonstration percentages as proof of improved rep performance.

<a id="document-teams-enablement-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [coach](#document-agents-coach)
- [content curator](#document-agents-content-curator)
- [coaching](#document-workflows-coaching)
- [enable](#document-apps-enable)

<a id="document-teams-enablement-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/enablement: [Sales Enablement | Oliv AI](https://www.oliv.ai/enablement)

<a id="document-teams-revops"></a>
# Revenue Operations

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-teams-revops-overview"></a>
## Overview

Maintain the process, data and configuration context that revenue workflows depend on.

<a id="document-teams-revops-jobs"></a>
## Primary jobs



- Translate the current process and exceptions into maintained playbook knowledge.
- Confirm CRM mappings, data quality and supported write behavior.
- Configure the forecast process and review hierarchy.
- Monitor the operational evidence and resolve cross-system discrepancies.

<a id="document-teams-revops-agent-map"></a>
## Relevant agents

Oliver, CRM Manager, Forecaster, Olivia. Availability of each agent and action must be confirmed for the workspace.

<a id="document-teams-revops-ownership"></a>
## Ownership and handoffs

Identify which changes RevOps can approve and which require a revenue leader, security owner or system administrator. Process authority and technical installation permission may belong to different people.

<a id="document-teams-revops-team-boundaries"></a>
## Scope and limitations

The website describes assisted GTM engineering. The division of implementation, ongoing maintenance and customer-operated administration must be agreed for the actual engagement.

<a id="document-teams-revops-recommended-start"></a>
## Recommended first use case

Select one of the jobs above, identify the current source system and review owner, and run a representative case. Check the output and handoff before expanding the workflow across the team.

- [oliver](#document-agents-oliver)
- [crm manager](#document-agents-crm-manager)
- [forecaster](#document-agents-forecaster)
- [administration](#document-administration)

<a id="document-teams-revops-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/revops: [RevOps – Your Revenue Process on Autopilot | Oliv AI](https://www.oliv.ai/revops)

<a id="document-getting-started-startups"></a>
# Startups and staged adoption

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-getting-started-startups-overview"></a>
## Overview

The current startup presentation combines app access, connected context and selected agent work. A smaller team can still benefit from a carefully bounded first workflow.

<a id="document-getting-started-startups-start-small"></a>
## Choose the initial scope

Start with the activity sources the team actually uses and the workflow that creates the clearest operational value. Examples include meeting preparation, reviewed CRM updates or a recurring pipeline review.

A low seat fee is not the entire cost of operation. Identify agent usage, selected add-ons, implementation work and any hardware or external-service dependency before comparing total cost.

<a id="document-getting-started-startups-staged-deployment"></a>
## Recommended staged deployment



1. Connect the minimum source set for the first task.
2. Agree the current ICP, ownership and qualification rules.
3. Use reviewed outputs while the team verifies the workflow.
4. Measure actual usage and the quality of the handoff.
5. Expand to another team or job only after the first scope is dependable.

<a id="document-getting-started-startups-commercial-conditions"></a>
## Commercial conditions

The website’s startup framing and sample cost comparisons are not a signed quote or proof of a universal discount. Use the current role-group pricing as a dated reference and obtain the offer applicable to the team.

Keep current capabilities separate from custom agents or integrations that still require implementation.

<a id="document-getting-started-startups-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/startup: [Oliv for Startups – AI-Native Revenue Platform | Oliv AI](https://www.oliv.ai/startup)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-administration"></a>
# Administration

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-administration-overview"></a>
## Overview

Administration defines who can see context, configure work and authorize actions. The available material does not yet establish a complete production administration specification.

<a id="document-administration-admin-scope"></a>
## Administration scope



| Area | Required decisions |
| --- | --- |
| Access | Users, roles, teams, record visibility and external-system identity |
| Approvals | Action scope, reviewer, precedence, expiry and escalation |
| Security and privacy | Approved policies, attestations and data-use statements |
| Data lifecycle | Import, retention, deletion, export and derived data |
| Operations | Connector health, failures, usage and support ownership |

<a id="document-administration-admin-evidence"></a>
## Evidence before a wider rollout

An administrator should be able to explain the current permission and action boundary with observed behavior or an accountable owner’s specification. The prototype’s lack of RBAC code is not evidence that production has no access control.

Likewise, a certification logo or generic marketing list does not establish scope, current validity or contractual applicability. Use the approved policy and security evidence for the deployment.

<a id="document-administration-explore"></a>
## Explore

- [Access and permissions](#document-administration-access)
- [Approval governance](#document-administration-approvals)
- [Security and privacy](#document-administration-security-and-privacy)
- [Data lifecycle, export and deletion](#document-administration-data-lifecycle)

<a id="document-administration-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-administration-access"></a>
# Access and permissions

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-administration-access-overview"></a>
## Overview

Access must be explained per action and data scope. A persona label such as manager or CSM is not sufficient to define permission.

<a id="document-administration-access-access-dimensions"></a>
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

<a id="document-administration-access-role-matrix"></a>
## Production role matrix remains open

The internal agent documents describe contributor, manager and admin-oriented workflows. They do not supply a complete enforced role matrix. The October prototype extraction explicitly cannot settle production permissions.

Before publishing end-user instructions, obtain the current role names and allowed actions. Do not convert ‘anyone can reach this prototype control’ into a statement about a customer workspace.

<a id="document-administration-access-access-tests"></a>
## Recommended access checks



- A user outside a team cannot retrieve that team’s restricted records.
- A viewer cannot enable a write or change an approval policy without authorization.
- A restricted source recording cannot be exposed through a shared clip or agent answer.
- An offboarded user loses the relevant access and action identity.
- A service connection does not exceed its approved object or mailbox scope.

<a id="document-administration-access-access-limits"></a>
## Unresolved specifics

SSO, SCIM, custom roles, permission inheritance, guest access, impersonation and complete audit coverage require approved production documentation. Their absence from the reviewed source is not a claim that the live product lacks them.

<a id="document-administration-access-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-administration-approvals"></a>
# Approval governance

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-administration-approvals-overview"></a>
## Overview

Approval governance should describe what is approved, who decides, how the decision is enforced and what happens afterward.

<a id="document-administration-approvals-approval-types"></a>
## Different actions need different rules



| Action | Documented source boundary | Still to establish |
| --- | --- | --- |
| CRM updates | CRM Manager describes reviewed and automatic modes | Scope, approver, conflict handling and recovery |
| Handbook changes | Oliver source requires human sign-off | Interface, authorized approver and propagation |
| Coaching goals | Coach source describes manager review | Role enforcement and goal delivery state |
| Opening prospect email | Prospector page describes rep review/send | Channel-specific enforcement and later follow-ups |
| Expansion introduction | Gold Digger source describes CSM review or delegation | Owner, sender and duplicate prevention |
| Other tool actions | Prototype offers three mode labels | Runtime precedence, default and approval destination |

<a id="document-administration-approvals-approval-procedure"></a>
## Recommended policy record

For each workflow, record the action, scope, reviewer, destination, expiry, escalation, rejection and change-after-approval behavior. Identify the authoritative policy owner and effective date.

These are documentation and acceptance requirements, not a claim that all fields appear in an existing administration screen.

<a id="document-administration-approvals-approval-production"></a>
## Production checks

Verify that an action requiring approval does not execute before the decision, that the reviewer sees the actual proposed result, and that rejection or expiry has an observable outcome.

Confirm how tool-level, conversation-level and organization-level policy interact. The available source material does not settle that precedence.

- [Tool modes and terminology](#document-agents-configuration-approvals)

<a id="document-administration-approvals-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector)

<a id="document-administration-security-and-privacy"></a>
# Security and privacy

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-administration-security-and-privacy-overview"></a>
## Overview

This V1 does not certify Oliv’s security posture. It identifies the statements and operating boundaries that need current, accountable evidence.

<a id="document-administration-security-and-privacy-approved-evidence"></a>
## Use approved evidence

Obtain the current security documentation, data-processing terms, applicable attestations and the organization’s deployment agreement. Scope and validity matter: a general logo list cannot substitute for the relevant report or approved statement.

Older derived documents contain broad certification, encryption and compliance statements. Those are claim-discovery inputs, not sufficient authority for repeating the claims in new documentation.

<a id="document-administration-security-and-privacy-security-topics"></a>
## Topics requiring confirmation



| Topic | Required evidence |
| --- | --- |
| Authentication | Supported login, SSO, MFA and provisioning behavior |
| Authorization | Role and record-level access, source inheritance and action identity |
| Data use | AI training use, model/provider handling and customer controls |
| Storage | Location, residency options, encryption and key ownership |
| Operations | Audit, access review, incident support and availability commitments |
| Subprocessors | Current list and applicable data flow |
| Certification | Current attestation, scope and approved public wording |
| Recording | Consent/indication, admission and exclusion behavior |

<a id="document-administration-security-and-privacy-privacy-boundary"></a>
## Privacy follows the data flow

A conversation can contribute to a transcript, clip, account context, signal, agent output and external-system update. The policy should explain which of those artifacts are retained, shared, exported or deleted.

Data minimization, offboarding and source revocation must be assessed against the actual implementation. This V1 does not assert that a source deletion automatically removes every derivative.

<a id="document-administration-security-and-privacy-security-review"></a>
## Publication requirement

The accountable security or legal owner must approve substantive security, privacy and contractual claims. Product UI observation alone cannot establish them. Keep the current source and review date with the approved wording.

<a id="document-administration-security-and-privacy-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)

<a id="document-administration-data-lifecycle"></a>
# Data lifecycle, export and deletion

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-administration-data-lifecycle-overview"></a>
## Overview

A lifecycle reference should explain the state of each data object and what happens to related artifacts when a user changes access or deletes data.

<a id="document-administration-data-lifecycle-lifecycle-events"></a>
## Lifecycle events are different



| Event | Do not assume |
| --- | --- |
| Disconnect a source | All previously imported data is deleted |
| Deactivate a user/account | All associated content is erased |
| Delete an account | Every copy, backup and derived artifact disappears immediately |
| Clear a feed item | The underlying run or evidence is deleted |
| Remove a clip | The source recording is deleted |
| Export | Every object and historical artifact is included |

<a id="document-administration-data-lifecycle-documented-account-flow"></a>
## Existing account guidance

The October 2024 Help Center article distinguishes deactivation and deletion through profile settings. Treat that as a dated procedure requiring current UI and lifecycle verification.

It does not establish the full retention schedule, backup policy, derived-data removal, organization-level deletion authority or contractual export scope.

<a id="document-administration-data-lifecycle-lifecycle-contract"></a>
## Lifecycle contract to confirm



- Each retained object and its owner.
- Retention period and configurable options.
- Access after user offboarding or connector revocation.
- Deletion request, authorization and completion state.
- Treatment of transcripts, clips, signals, agent outputs, logs and backups.
- Export formats, coverage, delivery and limitations.
- Any legal or contractual retention exception.

<a id="document-administration-data-lifecycle-lifecycle-check"></a>
## Recommended acceptance check

Use a controlled record and identify its related artifacts before changing access or requesting deletion. Verify the documented result at each relevant destination. Do not perform deletion tests on production customer data merely to complete this documentation.

<a id="document-administration-data-lifecycle-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9179977: [How to Deactivate / Delete your Oliv account](https://help.oliv.ai/en/articles/9179977-how-to-deactivate-delete-your-oliv-account)

<a id="document-reference"></a>
# Reference

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-overview"></a>
## Overview

Reference pages provide stable definitions and dated facts. They keep unverified limits and release claims out of operational instructions.

<a id="document-reference-reference-types"></a>
## Reference types



| Reference | Use it for |
| --- | --- |
| Glossary | Consistent product and workflow vocabulary |
| Plans and usage | Dated website pricing and commercial questions |
| Limits and availability | Verified values versus unresolved constraints |
| Data objects | The meaning of records and artifacts |
| Reporting cadence | The difference between schedules and service commitments |
| API and MCP | Current interface evidence and missing specification |

<a id="document-reference-reference-ownership"></a>
## Ownership

A numeric limit, default, price or compatibility claim should have an owner and effective date. Preserve former names and history only when the relationship is confirmed.

An unknown value should stay unknown. Do not replace it with an industry norm, a prototype label or a plausible estimate.

<a id="document-reference-explore"></a>
## Explore

- [Plans, credits and usage](#document-reference-plans-and-usage)
- [Limits and availability](#document-reference-limits-and-availability)
- [Data objects and artifacts](#document-reference-data-objects)
- [Briefs, reports and cadence](#document-reference-reporting-cadences)
- [API, MCP and developer interfaces](#document-reference-api-and-mcp)
- [Glossary](#document-reference-glossary)

<a id="document-reference-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-reference-plans-and-usage"></a>
# Plans, credits and usage

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-plans-and-usage-overview"></a>
## Overview

The live pricing page checked on 16 October 2026 presents four role-based groups plus separately charged agent usage and selected add-ons.

<a id="document-reference-plans-and-usage-role-groups"></a>
## Displayed role groups

The values below are a dated website snapshot, not a quote or a statement about a customer’s negotiated agreement. Confirm billing commitments, taxes, currency and applicable terms with the commercial owner.

| Group | Displayed price | Website description |
| --- | --- | --- |
| Amplify | $0 per user per month | Shared context and super-agent access; AI usage charged separately |
| Converse | $19 per user per month | Conversation capture |
| Sell | $49 per user per month | Converse plus Forecast and opportunity work |
| Grow | $79 per user per month | Sell plus Retain and account work |

<a id="document-reference-plans-and-usage-credits"></a>
## Credits are separate from seat fees

The page lists credits at $0.01 each. That does not mean every task costs one credit. Actual consumption depends on the action and usage; the page describes estimating spend during a proof of concept.

Confirm the action-to-credit schedule, included allowances, metering granularity, failed/retried action charges, budget controls and billing visibility before publishing a usage calculator.

<a id="document-reference-plans-and-usage-add-ons"></a>
## Displayed add-ons

The main pricing page lists Engage and Enable as separately priced additions. It also describes optional calling, messaging and additional-mailbox charges. Hardware associated with in-person capture is purchased separately where applicable.

The exact entitlement matrix requires confirmation. A feature row or icon in a pricing table should not be inferred as included for a plan when the accessible text does not establish the cell’s value.

<a id="document-reference-plans-and-usage-pricing-conflicts"></a>
## Unresolved current conflict

Engage’s live app page contains both $39 starting-price copy and a $29 base/add-on description. The main pricing page describes a $29 addition to the app subscription.

The authoritative commercial owner should resolve whether these describe different bundles, stale copy or another condition. This V1 records the conflict and does not silently select the lower or higher figure.

<a id="document-reference-plans-and-usage-commercial-checklist"></a>
## Confirm before quoting



- Seat group and app entitlements for each user.
- Current add-ons and supported channels.
- Agent usage charges and budget controls.
- Implementation or custom integration charges.
- Subscription commitment, renewal and cancellation terms.
- Support, data export and applicable service commitments.

<a id="document-reference-plans-and-usage-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)
- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage)

<a id="document-reference-limits-and-availability"></a>
# Limits and availability

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-limits-and-availability-overview"></a>
## Overview

This V1 does not invent quotas, retention periods or feature rollout states where the source set cannot establish them.

<a id="document-reference-limits-and-availability-availability-states"></a>
## Availability states to confirm



| State | Meaning required in the final docs |
| --- | --- |
| GA | Available to the specified users and conditions |
| Beta | Available with explicit limitations and support conditions |
| Limited rollout | Restricted to named cohorts, regions or workspaces |
| Planned | Not available; no inferred launch date |
| Deprecated/retired | Replacement and migration behavior stated |
| Unconfirmed | The reviewed sources cannot establish the current state |

<a id="document-reference-limits-and-availability-limits-register"></a>
## Limit categories



| Category | Current evidence state |
| --- | --- |
| Agents, tools and triggers per workspace | Not established |
| Runs, concurrency and rate limits | Not established |
| Credit consumption per action | Not established |
| Knowledge storage and upload quotas | Prototype labels do not establish production limits |
| Recording length and storage | Requires current plan/technical evidence |
| Run-history and content retention | Not established |
| Connector API limits and retries | Requires connector-specific reference |
| Language and region availability | Marketing claims require supported-scope confirmation |

<a id="document-reference-limits-and-availability-limit-source"></a>
## What counts as a verified limit

A final reference should record the value, unit, applicable plan, scope, enforcement behavior, overage or error, and effective date. A prototype’s ‘Max 5 files’ label does not establish a universal upload limit.

A displayed count of example runs or a fixed last-run timestamp is sample data, not a quota or retention rule.

<a id="document-reference-limits-and-availability-limit-ownership"></a>
## Publication requirement

The responsible product or engineering owner should confirm each limit before publication. Keep unknowns explicit in V1 and route them to the correct page rather than filling them with general software conventions.

<a id="document-reference-limits-and-availability-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-reference-data-objects"></a>
# Data objects and artifacts

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-data-objects-overview"></a>
## Overview

The available sources name business entities, source activities, interpretations and agent outputs. Those categories should remain distinct.

<a id="document-reference-data-objects-object-map"></a>
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

<a id="document-reference-data-objects-identifiers"></a>
## Identifiers and relationships

Document stable identifiers and relationships in the final schema reference: which opportunity an activity concerns, which recording a clip references and which source supports a proposed change.

The frontend prototype’s sample data does not supply production field types, required values, keys, API schemas or persistence guarantees. Those remain engineering inputs.

<a id="document-reference-data-objects-data-lifecycle"></a>
## Lifecycle and history

Creation, modification, deletion and retention can differ by artifact. A correction to a source or association may affect a later signal without changing a historical snapshot.

Use the lifecycle reference to identify the expected state of each artifact after offboarding, source revocation or deletion.

- [Data lifecycle](#document-administration-data-lifecycle)

<a id="document-reference-data-objects-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-reference-reporting-cadences"></a>
# Briefs, reports and cadence

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-reporting-cadences-overview"></a>
## Overview

Agent materials describe daily, weekly and monthly work. These cadences are workflow concepts whose timezone, configuration and delivery conditions must be confirmed.

<a id="document-reference-reporting-cadences-cadence-map"></a>
## Documented operating rhythms



| Workflow | Source-described rhythm | Confirm |
| --- | --- | --- |
| Deal Driver | Morning, event-driven, sunset and weekly reviews | Delivery time, channel and team scope |
| Forecaster | Weekly, monthly or quarterly | Board settings, hierarchy and snapshot cadence |
| Coach | Monthly goals and weekly progress | Evidence threshold and manager review |
| Portfolio Manager | Account signals, per-CSM reviews and team recaps | Owner, timezone and renewal period |
| Meeting preparation | Before a scheduled meeting | Product-specific delivery window |
| Content Curator | New matching conversation examples | Immediate versus digest configuration |

<a id="document-reference-reporting-cadences-timing-conflict"></a>
## Preparation timing conflict

Different source workflows say ten, twenty or thirty minutes before a meeting. These may describe different products, dates or configurations. The current final rule must be confirmed rather than averaged or selected silently.

Post-meeting processing also depends on source availability and completion. ‘After the meeting’ is not enough to establish a service-level commitment.

<a id="document-reference-reporting-cadences-monthly-distinction"></a>
## Monthly report versus monthly announcement

A monthly coaching report is customer workflow output. A monthly product announcement describes released product changes. A documentation changelog records edits to the documentation. They require separate names, dates and evidence.

Use the announcements area for release-note format and the documentation history for V1 changes.

- [Announcements](#document-announcements)

<a id="document-reference-reporting-cadences-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack)
- HELP:9334685: [A quick guide to streamline your meetings with try@oliv.ai](https://help.oliv.ai/en/articles/9334685-a-quick-guide-to-streamline-your-meetings-with-try-oliv-ai)

<a id="document-reference-api-and-mcp"></a>
# API, MCP and developer interfaces

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-api-and-mcp-overview"></a>
## Overview

The website describes connecting external agent systems through MCP and synchronizing context to other systems. A usable developer reference still requires the actual interface specification.

<a id="document-reference-api-and-mcp-interface-scope"></a>
## What the sources establish

The public platform presentation describes external access and context synchronization. The prototype contains UI labels such as MCP Servers, but those labels are not an endpoint or tool specification.

The historical vault inventory links an Oliv MCP/API guide in ClickUp. That guide could not be retrieved through the available connection during this V1.

<a id="document-reference-api-and-mcp-developer-contract"></a>
## Required developer reference



| Area | Specification needed |
| --- | --- |
| Authentication | Credential method, scopes, identity and revocation |
| MCP | Connection URL, transport, tools, input/output schemas and permissions |
| API | Base URL, version, methods, resources and schemas |
| Writes | Validation, idempotency, conflict handling and approval boundaries |
| Limits | Rate, concurrency, payload and pagination behavior |
| Errors | Codes, retry guidance and support correlation |
| Webhooks | Events, signing, delivery, ordering and replay if supported |
| SDKs | Official packages, compatibility and tested examples if available |

<a id="document-reference-api-and-mcp-no-invented-code"></a>
## No invented endpoint examples

This V1 intentionally does not provide runnable API requests, fabricated MCP tool names or webhook payloads. An apparently useful code sample would be misleading without the real contract.

Once the guide is accessible, build resource-level reference pages and validate examples against a controlled environment. Add version and deprecation policy separately from marketing copy.

<a id="document-reference-api-and-mcp-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/)
- WEB:/oliv-tech: [Oliv Tech | Oliv AI](https://oliv.ai/oliv-tech)

<a id="document-reference-glossary"></a>
# Glossary

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-reference-glossary-overview"></a>
## Overview

The glossary defines the terms used in this V1. It does not resolve unconfirmed aliases or turn a marketing name into a verified implementation.

<a id="document-reference-glossary-platform-terms"></a>
## Platform terms



| Term | Meaning in this documentation |
| --- | --- |
| Context Capture | Bringing supported customer activity into the platform |
| Context Graph | Associating activities with relevant accounts, contacts and opportunities |
| Signal Graph | Interpreting revenue-relevant questions from source context |
| Process Graph | Maintained organization playbook and operating rules |
| Agent | A defined job using relevant context and supported actions |
| Super agent | The current framing for Olivia and Oliver’s broader coordinating/process jobs |
| App | A workspace grouping related revenue tasks |
| Specialist | An agent focused on a particular job |
| MCP | The external-agent connection interface named in the product presentation; actual contract pending |

<a id="document-reference-glossary-workflow-terms"></a>
## Workflow terms



| Term | Meaning |
| --- | --- |
| Trigger | An event, schedule or request that starts work |
| Tool | A supported action or source-access capability available to an agent |
| Run | An attempt to complete a defined job |
| Draft | Prepared content that is not necessarily sent |
| Proposed update | A suggested field or record change that is not necessarily written |
| Approval | An authorized human decision before a defined action |
| Snapshot | A preserved historical view for comparison |
| Submission | A forecast entered for a specific cycle |
| Intent | The detection brief for Content Curator |
| Library/playlist | A destination organizing accessible clips |
| Botless/native recording | Recording through the meeting platform under supported setup conditions |

<a id="document-reference-glossary-commercial-and-review"></a>
## Commercial and review terms

Amplify, Converse, Sell and Grow are commercial role groups in the current pricing presentation. Converse also names an app, so the context of the term matters.

Documented means the reviewed source describes the behavior. Partial means useful detail exists but important rules remain unresolved. Needs confirmation means the current materials cannot support an operational specification. None of those labels means GA or owner-approved.

<a id="document-reference-glossary-aliases"></a>
## Aliases and former names

Keep Deal Assistant, Deal Assist and Meeting Assistant distinct until the product owner confirms which relationships and former names are customer-facing. Likewise, do not merge a prototype forecast-related name into Forecaster based only on similarity.

Use the current dedicated page name for navigation and maintain a separate reviewed alias register when the relationship is established.

<a id="document-reference-glossary-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-troubleshooting"></a>
# Troubleshooting

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-troubleshooting-overview"></a>
## Overview

Troubleshooting begins by separating missing input, incorrect association, incomplete processing, review state and destination failure.

<a id="document-troubleshooting-diagnostic-order"></a>
## Recommended diagnostic order



1. Confirm the source activity or record exists and is accessible.
2. Check whether it arrived in Oliv with the correct identity and time.
3. Verify the account, opportunity and participants.
4. Check the relevant agent or workflow state.
5. Determine whether human review is pending.
6. Inspect the destination system and any observed error.
7. Escalate with the minimum useful evidence.

<a id="document-troubleshooting-support-package"></a>
## Support evidence

Include the workflow and agent name, time and timezone, relevant record or meeting ID, the expected result, the observed state and any exact error text. Avoid sending unrelated customer content.

Do not repeatedly retry a consequential action until you know whether the previous attempt succeeded. The current sources do not establish a universal idempotency or undo mechanism.

<a id="document-troubleshooting-explore"></a>
## Explore

- [Meeting capture and brief issues](#document-troubleshooting-meetings)
- [Integration and sync issues](#document-troubleshooting-integrations)
- [Agent output and execution issues](#document-troubleshooting-agents)

<a id="document-troubleshooting-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8796010: [Copilot management options](https://help.oliv.ai/en/articles/8796010-copilot-management-options)

<a id="document-troubleshooting-meetings"></a>
# Meeting capture and brief issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-troubleshooting-meetings-overview"></a>
## Overview

A missing brief and a missing recording can have different causes. Establish the stage that stopped before changing the workflow.

<a id="document-troubleshooting-meetings-meeting-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| Meeting not recognized | Connected calendar, attendee details, scheduling-tool settings and timezone |
| Visible note taker did not join | Organizer, lobby/admission and configured capture route |
| Expected botless capture did not occur | Organization native-recording setup and supported platform conditions |
| Recording unavailable | Recording permission, completion and access to the artifact |
| Brief missing or late | Correct workflow, delivery channel, current schedule and source coverage |
| Wrong opportunity in brief | Activity association and multi-deal context |
| Follow-up missing | Recording/transcript processing and review state |

<a id="document-troubleshooting-meetings-timing"></a>
## Do not assume one preparation time

The available sources describe different preparation windows. Confirm the current product and workspace rule before treating a ten-, twenty- or thirty-minute expectation as a defect.

A rescheduled meeting or a changed participant can also affect the input context. The refresh and cutoff rules need production confirmation.

<a id="document-troubleshooting-meetings-recording-scope"></a>
## Recording controls

Use the current recording guide and verified client controls to stop or exclude capture. Older calendar-assistant instructions about Slack availability do not necessarily control the 2026 meeting recorder.

If native recording is not enabled, contact the implementation owner for the current platform setup; do not infer a local workaround from a marketing promise.

<a id="document-troubleshooting-meetings-meeting-escalation"></a>
## Escalate with



- Meeting platform, organizer and scheduled time/timezone.
- Connected calendar and attendee-recognition context.
- Expected versus observed recording mode.
- Lobby/admission or permission evidence.
- Recording or meeting identifier and relevant delivery destination.

<a id="document-troubleshooting-meetings-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv)
- HELP:10511705: [How to configure Calendly to work with Oliv](https://help.oliv.ai/en/articles/10511705-how-to-configure-calendly-to-work-with-oliv)

<a id="document-troubleshooting-integrations"></a>
# Integration and sync issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-troubleshooting-integrations-overview"></a>
## Overview

A connected-looking interface does not prove that a particular object or action is authorized and working.

<a id="document-troubleshooting-integrations-sync-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| No source data | Account identity, connector authorization and selected scope |
| Some records missing | Supported objects, filters, ownership and historical import |
| Wrong account or opportunity | Association rules and duplicate or multi-opportunity cases |
| Proposed update not written | Approval state, field mapping and writable field type |
| CRM rejected value | Provider validation, enumeration, required fields and permissions |
| Notifications missing | Destination membership, app permissions and selected channel |
| Old values remain | Refresh cadence, conflict policy and source-of-truth rule |

<a id="document-troubleshooting-integrations-safe-recovery"></a>
## Recovery boundary

Use the connector’s actual reconnect, retry or support path. Reinstalling, widening scopes or recreating records can have broader consequences and should not substitute for finding the failing stage.

Confirm whether the receiving system accepted the previous operation before retrying a write or message. The sources do not establish universal duplicate suppression.

<a id="document-troubleshooting-integrations-sync-escalation"></a>
## Escalate with



- Connector and connected account or tenant.
- Relevant object and source/destination identifiers.
- Field or action affected.
- Observed authorization or validation message.
- Last known successful sync and the current time/timezone.
- Whether approval was required and completed.

<a id="document-troubleshooting-integrations-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv)
- HELP:8671280: [Oliv <> HubSpot Integrations](https://help.oliv.ai/en/articles/8671280-oliv-hubspot-integrations)

<a id="document-troubleshooting-agents"></a>
# Agent output and execution issues

*V1 review draft · 2026-10-16 · Confirm workspace availability*

<a id="document-troubleshooting-agents-overview"></a>
## Overview

An incorrect answer, an unstarted run and an unperformed action are distinct failures.

<a id="document-troubleshooting-agents-agent-symptoms"></a>
## Symptoms and checks



| Symptom | Check first |
| --- | --- |
| Output lacks context | Source coverage, access and correct account/opportunity |
| Recommendation conflicts with policy | Current playbook rule, exception and effective date |
| Configuration appears lost | Verified production save/persistence behavior |
| Action did not execute | Availability, trigger, permission and approval state |
| Duplicate or unexpected action | Concurrent events, retry behavior and ownership |
| No failure details | Available run evidence and support correlation path |

<a id="document-troubleshooting-agents-prototype-warning"></a>
## Prototype evidence is not a production incident

The source kit explicitly describes a frontend prototype with nonfunctional actions and local-state settings. Seeing that behavior in its files does not establish the behavior of the live customer product.

Use a running environment or a current implementation specification to confirm the issue and the recovery path.

<a id="document-troubleshooting-agents-output-review"></a>
## Recommended output review

Check the source facts, association, relevant process rule, requested job and destination independently. Correcting a factual input may not correct an ownership or policy error.

For consequential output, preserve the proposed result and the observed external-system state. Do not infer that an action happened because a feed row says it did in demonstration data.

<a id="document-troubleshooting-agents-agent-escalation"></a>
## Escalate with



- Agent and initiating request or event.
- Input record and relevant source evidence.
- Expected and observed output.
- Approval or configuration state.
- Destination result and any error.
- Whether an earlier attempt may already have succeeded.

<a id="document-troubleshooting-agents-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-announcements"></a>
# Announcements and release notes

*V1 review draft · 2026-10-16 · Documentation format; not a product capability*

<a id="document-announcements-overview"></a>
## Overview

Monthly product announcements should report confirmed product changes with clear availability and action requirements. A documentation draft date is not a product launch date.

<a id="document-announcements-release-policy"></a>
## What a release note needs



- A stable entry ID and an explicit publication date.
- The affected product, app, agent or integration.
- What changed and the customer-visible behavior.
- GA, beta or rollout conditions and applicable plans.
- Any action, migration or permission change.
- A link to the updated current documentation.
- A responsible owner and verified release evidence.

<a id="document-announcements-v1-release-scope"></a>
## V1 release scope

No approved product-release ledger was supplied. This V1 therefore includes a release-note format and a documentation history, without inventing monthly product changes from prototype commits.

Current references explain the latest reviewed behavior; announcement archives explain what changed at a known date. Avoid duplicating the entire feature reference in every monthly note.

- [Monthly announcement format](#document-announcements-monthly-format)
- [Documentation history](#document-announcements-documentation-history)

<a id="document-announcements-explore"></a>
## Explore

- [Monthly announcement format](#document-announcements-monthly-format)
- [Documentation history](#document-announcements-documentation-history)

<a id="document-announcements-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-announcements-monthly-format"></a>
# Monthly announcement format

*V1 review draft · 2026-10-16 · Editorial template*

<a id="document-announcements-monthly-format-overview"></a>
## Overview

This is an editorial template. It is not a record of a released Oliv feature.

<a id="document-announcements-monthly-format-monthly-url"></a>
## URL and heading format

Use /announcements/YYYY-MM/ for an approved monthly archive and a stable entry anchor such as #crm-manager-reviewed-updates. Give an individual change its own page when the migration or impact needs substantial explanation.

Use H2 for a product or change group, H3 for the specific change and H4 for details such as availability, required action or limitations. Explicit IDs should remain stable when the wording of a heading improves.

| Element | Example placeholder |
| --- | --- |
| Archive title | Month YYYY product updates |
| Entry ID | REL-YYYY-MM-001 |
| H3 anchor | crm-manager-reviewed-updates |
| Availability | Confirmed state, cohort, plan and date |
| Action | Required customer step, or explicitly no action |
| Current docs | Link to the maintained capability reference |

<a id="document-announcements-monthly-format-entry-template"></a>
## Release entry template

Change title: state the customer-visible behavior in plain language.

What changed: describe the previous and new behavior only when both are verified.

Availability: state rollout, plans, prerequisites, regions or restrictions.

Action required: give the verified customer step and deadline if one applies.

Limitations: state known exceptions or breaking changes.

Learn more: link to current setup, reference and troubleshooting pages.

<a id="document-announcements-monthly-format-release-verification"></a>
## Release verification

Do not use a source file’s first commit, a marketing-page revision or this V1’s creation date as the product release date. Obtain the release record or the accountable owner’s confirmation.

If the exact release date is unknown, keep the entry in the review queue. Do not create an empty dated product archive that suggests a release occurred.

<a id="document-announcements-monthly-format-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-announcements-documentation-history"></a>
# Documentation history

*V1 review draft · 2026-10-16 · Documentation history only*

<a id="document-announcements-documentation-history-overview"></a>
## Overview

This history records the documentation artifact and its evidence scope. It does not announce new product capabilities.

<a id="document-announcements-documentation-history-v1-2026-10-16"></a>
## 16 October 2026 — V1 review draft

Created a source-grounded V1 documentation set covering agents, apps, platform concepts, workflows, teams, integrations, administration, reference and troubleshooting.

Added stable heading links, search, Markdown downloads and source review. Original source documents and detailed checklist worksheets remain in the private authoring repository.

<a id="document-announcements-documentation-history-known-review-items"></a>
## Known review items

The first publication review must reconcile current agent availability, naming relationships, permissions and approval enforcement, connector scope, limits, credits, security statements and release dates.

Current source conflicts include preparation timing and Engage pricing. No owner approval, production test or product release is implied by the creation of this documentation.

<a id="document-announcements-documentation-history-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-review"></a>
# V1 review guide

*V1 review draft · 2026-10-16 · Internal review material*

<a id="document-review-overview"></a>
## Overview

This review area is for the documentation team and product owners. It is not an end-user feature catalog or an approved release statement.

<a id="document-review-review-order"></a>
## Recommended review order



1. Confirm current names and the availability of the agents and apps.
2. Review one end-to-end customer workflow against a running environment.
3. Confirm permissions, approvals and external action identity.
4. Approve connector mappings, limits and commercial terms.
5. Approve security/data-use and release-history statements.
6. Resolve source conflicts and update the relevant page.
7. Choose the approved pages and indexing policy for a public release.

<a id="document-review-review-deliverables"></a>
## Review deliverables

Download the documentation Markdown, page inventory and public source register to review this preview. Return a correction with the page URL, section link, proposed wording and supporting evidence.

The live preview is publicly accessible and marked noindex. The full authoring repository, original documents and detailed evidence worksheets remain private.

- [Coverage](#document-review-coverage)
- [Sources](#document-review-sources)
- [Open questions](#document-review-questions)
- [Legacy source migration](#document-review-legacy)
- [Documentation contract](#document-review-documentation-contract)

<a id="document-review-explore"></a>
## Explore

- [Coverage and checklist review](#document-review-coverage)
- [Source register](#document-review-sources)
- [Open questions and claim conflicts](#document-review-questions)
- [Legacy help and naming migration](#document-review-legacy)
- [Documentation contract and publishing](#document-review-documentation-contract)

<a id="document-review-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-review-coverage"></a>
# Coverage and checklist review

*V1 review draft · 2026-10-16 · Coverage report; not product availability*

<a id="document-review-coverage-overview"></a>
## Overview

V1 covers the accessible product presentation and documented jobs. It does not claim that every original buyer parameter has been researched and approved.

<a id="document-review-coverage-source-coverage"></a>
## Source coverage

The direct HTTP collection returned 85 successful responses, resolving to 57 distinct page paths: 32 product/navigation pages and 25 listed Help Center articles. Domain aliases and repeated navigation links account for duplicate requests.

The eleven original agent documents were retrieved from their shared folder. Relevant Google Docs add use-case and app context. Videos, authenticated production screens, backend code and the ClickUp MCP/API guide were not fully reviewed.

<a id="document-review-coverage-checklist-baseline"></a>
## Original checklist baseline

The original 555-row checklist and its source evidence are retained in the private documentation repository. This public UI review build omits those worksheet records and the original sixty-question extraction log.

All 92 document routes remain available for navigation and content review. A topic appearing in the navigation does not establish product availability or owner approval.

<a id="document-review-coverage-approval-state"></a>
## Approval state

No claim is marked product-owner approved merely because it has a source. Current feature availability, production permissions, numeric limits and security statements still need accountable confirmation.

Review a page by its claims and workflow, not by the number of headings or the presence of a complete template.

<a id="document-review-coverage-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-review-sources"></a>
# Source register

*V1 review draft · 2026-10-16 · Evidence register*

<a id="document-review-sources-overview"></a>
## Overview

The register records source type, date and access scope. It does not collapse marketing copy, internal descriptions and production verification into one confidence label.

<a id="document-review-sources-precedence"></a>
## Source precedence for V1

The user designated the latest website navigation and agent pages as the current presentation. Those pages set primary names and framing. Original agent documents add detailed behavior where compatible; older help articles are qualified by their displayed dates.

An approved legal or contractual statement is not replaced by newer marketing copy. Conflicts are recorded for the accountable owner rather than resolved through recency alone.

<a id="document-review-sources-source-register"></a>
## Retrieved sources

This hosted register contains the 57 public product and Help Center sources. Private document identifiers, Drive links and source metadata are excluded.

A retrieval date records when a source was checked; it is not a product release or owner-approval date.

- HELP:10511705: [How to configure Calendly to work with Oliv](https://help.oliv.ai/en/articles/10511705-how-to-configure-calendly-to-work-with-oliv) · Public Help Center article · Updated over a year ago
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes) · Public Help Center article · May 15, 2026
- HELP:2248750: [Contact us via chat for help](https://help.oliv.ai/en/articles/2248750-contact-us-via-chat-for-help) · Public Help Center article · August 26, 2020
- HELP:2581088: [Getting started with Oliv's Slack bot](https://help.oliv.ai/en/articles/2581088-getting-started-with-oliv-s-slack-bot) · Public Help Center article · December 19, 2018
- HELP:2581749: [How does the Slack auto responder work?](https://help.oliv.ai/en/articles/2581749-how-does-the-slack-auto-responder-work) · Public Help Center article · December 19, 2018
- HELP:2583960: [Force update Oliv's chrome extension](https://help.oliv.ai/en/articles/2583960-force-update-oliv-s-chrome-extension) · Public Help Center article · February 9, 2020
- HELP:2776531: [How do I fix Oliv's time zone in Office 365?](https://help.oliv.ai/en/articles/2776531-how-do-i-fix-oliv-s-time-zone-in-office-365) · Public Help Center article · July 10, 2019
- HELP:3506201: [How do I add a Zoom link when scheduling meetings?](https://help.oliv.ai/en/articles/3506201-how-do-i-add-a-zoom-link-when-scheduling-meetings) · Public Help Center article · Updated over 6 years ago
- HELP:3506313: [How do I enable Oliv's integration with Zoom?](https://help.oliv.ai/en/articles/3506313-how-do-i-enable-oliv-s-integration-with-zoom) · Public Help Center article · August 26, 2020
- HELP:3564440: [How do I disable Oliv when a meeting ends earlier than planned?](https://help.oliv.ai/en/articles/3564440-how-do-i-disable-oliv-when-a-meeting-ends-earlier-than-planned) · Public Help Center article · December 11, 2019
- HELP:3810034: [Install Oliv's Add-in for Outlook](https://help.oliv.ai/en/articles/3810034-install-oliv-s-add-in-for-outlook) · Public Help Center article · September 21, 2020
- HELP:4467669: [Missing "Get Add-Ins" button in Outlook](https://help.oliv.ai/en/articles/4467669-missing-get-add-ins-button-in-outlook) · Public Help Center article · September 21, 2020
- HELP:4940626: [Install Oliv's Salesforce Integration](https://help.oliv.ai/en/articles/4940626-install-oliv-s-salesforce-integration) · Public Help Center article · February 21, 2021
- HELP:6398707: [How do I uninstall Oliv's calendar assistant?](https://help.oliv.ai/en/articles/6398707-how-do-i-uninstall-oliv-s-calendar-assistant) · Public Help Center article · April 12, 2024
- HELP:8532501: [Integrations settings for Oliv](https://help.oliv.ai/en/articles/8532501-integrations-settings-for-oliv) · Public Help Center article · October 16, 2024
- HELP:8638345: [Oliv <> Zoom integrations](https://help.oliv.ai/en/articles/8638345-oliv-zoom-integrations) · Public Help Center article · October 16, 2024
- HELP:8671280: [Oliv <> HubSpot Integrations](https://help.oliv.ai/en/articles/8671280-oliv-hubspot-integrations) · Public Help Center article · October 16, 2024
- HELP:8796010: [Copilot management options](https://help.oliv.ai/en/articles/8796010-copilot-management-options) · Public Help Center article · October 16, 2024
- HELP:9133182: [Messages Sent by Oliv to Slack](https://help.oliv.ai/en/articles/9133182-messages-sent-by-oliv-to-slack) · Public Help Center article · October 16, 2024
- HELP:9144560: [Overcome Outlook Calendar Access Restrictions](https://help.oliv.ai/en/articles/9144560-overcome-outlook-calendar-access-restrictions) · Public Help Center article · October 17, 2024
- HELP:9179977: [How to Deactivate / Delete your Oliv account](https://help.oliv.ai/en/articles/9179977-how-to-deactivate-delete-your-oliv-account) · Public Help Center article · October 16, 2024
- HELP:9334685: [A quick guide to streamline your meetings with try@oliv.ai](https://help.oliv.ai/en/articles/9334685-a-quick-guide-to-streamline-your-meetings-with-try-oliv-ai) · Public Help Center article · October 17, 2024
- HELP:9470579: [How to access Oliv recordings](https://help.oliv.ai/en/articles/9470579-how-to-access-oliv-recordings) · Public Help Center article · October 17, 2024
- HELP:9936748: [Step-by-Step Guide: How to capture Oliv data as fields in HubSpot by creating custom fields ?](https://help.oliv.ai/en/articles/9936748-step-by-step-guide-how-to-capture-oliv-data-as-fields-in-hubspot-by-creating-custom-fields) · Public Help Center article · September 30, 2024
- HELP:9979279: [How to enable admin-level Zoom recording permissions with Oliv](https://help.oliv.ai/en/articles/9979279-how-to-enable-admin-level-zoom-recording-permissions-with-oliv) · Public Help Center article · October 16, 2024
- WEB:/: [Oliv AI Agents for Revenue Teams](https://www.oliv.ai/) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/account-management: [Account Management – Catch Expansion Signals | Oliv AI](https://www.oliv.ai/account-management) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents-marketplace: [Create custom AI agents in minutes](https://www.oliv.ai/agents-marketplace) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/coach: [Coach – AI Sales Coaching Agent | Oliv AI](https://oliv.ai/agents/coach) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/content-curator: [Content Curator | Oliv AI](https://oliv.ai/agents/content-curator) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/crm-manager: [CRM Manager | Oliv AI](https://oliv.ai/agents/crm-manager) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/deal-driver: [Deal Driver – AI Deal Risk Agent | Oliv AI](https://oliv.ai/agents/deal-driver) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/forecaster: [Forecaster | Oliv AI](https://oliv.ai/agents/forecaster) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/gold-digger: [Gold Digger – Expansion Signal Agent | Oliv AI](https://oliv.ai/agents/gold-digger) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/meeting-assistant: [Meeting Assistant – AI Briefs &amp; Follow-ups | Oliv AI](https://oliv.ai/agents/meeting-assistant) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/oliver: [Oliver – Revenue Process Agent | Oliv AI](https://oliv.ai/agents/oliver) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/olivia: [Olivia – Chief of AI Staff for GTM Teams | Oliv AI](https://oliv.ai/agents/olivia) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/portfolio-manager: [Portfolio Manager | Oliv AI](https://oliv.ai/agents/portfolio-manager) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/agents/prospector: [Prospector | Oliv AI](https://oliv.ai/agents/prospector) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/context-capture: [Context Capture – Every Interaction, Captured | Oliv AI](https://oliv.ai/context-capture) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/context-graph: [Context Graph – Every Signal, Mapped | Oliv AI](https://oliv.ai/context-graph) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/converse: [Converse – AI Conversation Capture | Oliv AI](https://www.oliv.ai/converse) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/customer-success: [Customer Success | Oliv AI](https://www.oliv.ai/customer-success) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/enablement: [Sales Enablement | Oliv AI](https://www.oliv.ai/enablement) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/integrations: [Integrations – Oliv Works With Your Tech Stack | Oliv AI](https://www.oliv.ai/integrations) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/oliv-forecast: [Oliv Forecast – AI-Native Forecasting | Oliv AI](https://oliv.ai/oliv-forecast) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/oliv-tech: [Oliv Tech | Oliv AI](https://oliv.ai/oliv-tech) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/onboarding: [Onboarding | Oliv AI](https://www.oliv.ai/onboarding) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/process-graph: [Process Graph – Your Playbook, Written for Agents | Oliv AI](https://oliv.ai/process-graph) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/revops: [RevOps – Your Revenue Process on Autopilot | Oliv AI](https://www.oliv.ai/revops) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/sales: [Automate Your Sales Process with AI Agents | Oliv AI](https://www.oliv.ai/sales) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/sales-development: [Sales Development – Work All 500 Accounts | Oliv AI](https://www.oliv.ai/sales-development) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/sales-engineering: [Sales Engineering – Full Deal Context for SEs | Oliv AI](https://www.oliv.ai/sales-engineering) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/signal-graph: [Signal Graph | Oliv AI](https://oliv.ai/signal-graph) · Current public product page · Source update date not supplied; checked 2026-10-16
- WEB:/startup: [Oliv for Startups – AI-Native Revenue Platform | Oliv AI](https://www.oliv.ai/startup) · Current public product page · Source update date not supplied; checked 2026-10-16

<a id="document-review-sources-source-limitations"></a>
## Limitations

Public citations are shown where available. Additional source materials and detailed evidence remain in the private authoring repository.

This preview publishes authored documentation, not raw source documents or a mirror of the research collection.

<a id="document-review-sources-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-review-questions"></a>
# Open questions and claim conflicts

*V1 review draft · 2026-10-16 · Review queue*

<a id="document-review-questions-overview"></a>
## Overview

The original kit raised sixty open questions. This V1 adds a smaller, prioritized publication queue that consolidates the most consequential unresolved claims.

<a id="document-review-questions-blocking-questions"></a>
## Publication review queue



<a id="document-review-questions-doc-q001-topic"></a>
### DOC-Q001 — Canonical names and availability

Confirm the canonical twelve-reference set, aliases, and GA/beta/limited/planned/retired state for every documented agent.

Owner: Product / PMM · P0 · Open

<a id="document-review-questions-doc-q002-topic"></a>
### DOC-Q002 — Current production UI

Confirm the production entry points and current UI labels for each documented customer task.

Owner: Product / engineering · P0 · Open

<a id="document-review-questions-doc-q003-topic"></a>
### DOC-Q003 — Approval precedence

Which organization, conversation, agent and tool settings take precedence; where are approval requests enforced and recorded?

Owner: Product / engineering · P0 · Open

<a id="document-review-questions-doc-q004-topic"></a>
### DOC-Q004 — CRM write contract

Confirm objects, fields, mappings, acting identity, conflicts, rejection, retries and correction behavior per CRM.

Owner: RevOps / engineering · P0 · Open

<a id="document-review-questions-doc-q005-topic"></a>
### DOC-Q005 — Engage price conflict

Resolve $39 starting-price copy versus the $29 add-on/base presentation and state the current offer conditions.

Owner: Commercial owner · P0 · Open

<a id="document-review-questions-doc-q006-topic"></a>
### DOC-Q006 — Approved security and data use

Provide current approved security, data-processing, provider/training use, residency and attestation statements.

Owner: Security / legal · P0 · Open

<a id="document-review-questions-doc-q007-topic"></a>
### DOC-Q007 — Permissions

Provide the current enforced role/action matrix, source-access inheritance and restricted-record behavior.

Owner: Product / security · P0 · Open

<a id="document-review-questions-doc-q008-topic"></a>
### DOC-Q008 — Meeting preparation timing

Resolve ten-, twenty- and thirty-minute preparation windows by workflow, product and current configuration.

Owner: Product / engineering · P1 · Open

<a id="document-review-questions-doc-q009-topic"></a>
### DOC-Q009 — Recording modes

Confirm supported platforms, organization native setup, external-organizer behavior, indication and exclusion controls.

Owner: Product / support · P1 · Open

<a id="document-review-questions-doc-q010-topic"></a>
### DOC-Q010 — Credits and limits

Provide per-action consumption, retries/failures charging, quotas, overages and budget controls.

Owner: Product / commercial · P1 · Open

<a id="document-review-questions-doc-q011-topic"></a>
### DOC-Q011 — Data lifecycle

Confirm retention, export, source revocation, offboarding and deletion of primary and derived artifacts.

Owner: Product / engineering · P1 · Open

<a id="document-review-questions-doc-q012-topic"></a>
### DOC-Q012 — API and MCP

Provide the current MCP/API guide, authentication, scopes, schemas, errors, limits and examples.

Owner: Engineering · P1 · Open

<a id="document-review-questions-doc-q013-topic"></a>
### DOC-Q013 — Content Curator storage

Resolve current Highspot/LMS syncing, historical backfill, sharing scopes and feedback behavior.

Owner: Product / engineering · P1 · Open

<a id="document-review-questions-doc-q014-topic"></a>
### DOC-Q014 — Forecast rules

Confirm hierarchy, modes, calibration, custom metrics, snapshot ownership and CRM write-back.

Owner: Product / engineering · P1 · Open

<a id="document-review-questions-doc-q015-topic"></a>
### DOC-Q015 — CS and onboarding roster

Confirm current CS/onboarding specialists and which are independently available versus catalog concepts.

Owner: Product / PMM · P1 · Open

<a id="document-review-questions-doc-q016-topic"></a>
### DOC-Q016 — Failure and run evidence

Confirm production failure states, retry policy, run IDs, history retention and user-visible recovery.

Owner: Product / support · P1 · Open

<a id="document-review-questions-doc-q017-topic"></a>
### DOC-Q017 — Release ledger

Provide actual product release dates, rollout conditions, breaking changes and approved monthly announcements.

Owner: Product / release owner · P1 · Open

<a id="document-review-questions-doc-q018-topic"></a>
### DOC-Q018 — Legacy help disposition

Confirm which legacy calendar-assistant and old setup articles remain applicable, need updating or should be archived.

Owner: Support / product · P2 · Open

<a id="document-review-questions-response-format"></a>
## How to return an answer

Include the question ID, affected page and section, approved wording, evidence or demonstration, accountable reviewer and effective date. If the answer is rollout-specific, identify the eligible workspaces, plans and conditions.

An answer saying only ‘yes’ is insufficient when the question concerns scope, permissions, costs or lifecycle. Record the exception path and actual user-visible behavior.

<a id="document-review-questions-baseline-questions"></a>
## Original question log

The original sixty-question extraction log is retained in the private repository. The concise publication-review queue above identifies the product facts that need confirmation.

Close a question only when its specific behavior and applicable scope have been verified.

<a id="document-review-questions-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.



<a id="document-review-legacy"></a>
# Legacy help and naming migration

*V1 review draft · 2026-10-16 · Migration proposal*

<a id="document-review-legacy-overview"></a>
## Overview

The Help Center mixes calendar-assistant material from 2018–2020 with later revenue-workflow articles and a May 2026 recording guide.

<a id="document-review-legacy-legacy-disposition"></a>
## Recommended disposition



| Source family | Recommended review action |
| --- | --- |
| Calendar-driven Slack status/DND | Confirm legacy product scope; keep outside current revenue agent instructions |
| Older Outlook add-in guidance | Verify current clients, tenant policy and installation procedure |
| 2024 integration and meeting guides | Update setup routes, scopes, capture modes and timings |
| 2026 recording modes | Preserve conditional behavior; verify current platform-specific setup |
| Prototype agent names | Resolve aliases and rollout before merging |
| Draft app landing copy | Use for intent and concepts; validate actions and commercial claims |

<a id="document-review-legacy-redirects"></a>
## URLs and redirects

Do not delete or redirect a legacy help URL simply because it is old. First determine whether customers still use that product and whether the replacement covers the same task.

When a replacement is approved, preserve the task intent, add an explicit migration note and plan the redirect or archive status. Fragment identifiers also need consideration when headings are renamed.

<a id="document-review-legacy-migration-conflicts"></a>
## Specific conflicts

Meeting-prep timing differs across older help flows and September agent documents. The current Engage page and pricing page also disagree on the starting/add-on presentation.

The older Outlook calendar workaround and the broad certification lists in derived documents require responsible-owner review before reuse.

<a id="document-review-legacy-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.

- HELP:2581088: [Getting started with Oliv's Slack bot](https://help.oliv.ai/en/articles/2581088-getting-started-with-oliv-s-slack-bot)
- HELP:9144560: [Overcome Outlook Calendar Access Restrictions](https://help.oliv.ai/en/articles/9144560-overcome-outlook-calendar-access-restrictions)
- HELP:15136310: [Understanding Oliv’s Meeting Recording Modes](https://help.oliv.ai/en/articles/15136310-understanding-oliv-s-meeting-recording-modes)
- WEB:/engage: [Engage – AI-Native Sales Engagement | Oliv AI](https://oliv.ai/engage)
- WEB:/pricing: [Pricing — Role-Based Plans for Revenue Teams | Oliv AI](https://www.oliv.ai/pricing)

<a id="document-review-documentation-contract"></a>
# Documentation contract and publishing

*V1 review draft · 2026-10-16 · Implementation and editorial specification*

<a id="document-review-documentation-contract-overview"></a>
## Overview

The documentation is authored for clear user tasks and source accountability. Machine-readable delivery should reflect the same approved content that a person reads.

<a id="document-review-documentation-contract-url-contract"></a>
## URLs and section IDs

Use lowercase, hyphenated path segments and one canonical route per distinct task or reference. Keep route depth shallow; this V1 has no route deeper than three path segments.

Every H2, H3 and H4 has an explicit stable ID and a copyable section link. The URL path locates the document; the fragment locates its section. Changing a heading’s wording should not change its ID.

<a id="document-review-documentation-contract-heading-contract"></a>
### Heading hierarchy

Use one H1 for the page title, H2 for major sections, H3 for subordinate topics and H4 only for a meaningful detail.

<a id="document-review-documentation-contract-fragment-contract"></a>
#### Fragment behavior

Use ordinary fragment links such as /agents/crm-manager/#actions-and-review. The fragment is resolved in the browser and is not a separate server resource or sitemap URL.

<a id="document-review-documentation-contract-content-contract"></a>
## Content model

The canonical source is lib/content.json. Each page has a URL, title, description, summary, sections, sources, evidence status and availability note. Sections carry stable IDs and can contain prose, steps, lists, tables and subordinate sections.

Markdown and downloads are generated review exports. Editing an export alone does not update the site. Page and section IDs should remain stable when a source changes.

<a id="document-review-documentation-contract-crawlability"></a>
## Readable delivery

The static build includes the full authored content in HTML without requiring client-side rendering. Navigation, breadcrumbs, section links and related references are ordinary links. Search adds convenience without being the only way to discover a page.

The build generates Markdown downloads, a route/metadata inventory, a sitemap and optional llms.txt and llms-full.txt aids. Those aids do not guarantee crawling, understanding or citation by an AI system.

<a id="document-review-documentation-contract-indexing-policy"></a>
## Review and production indexing

This live preview is public and marked noindex. The full authoring repository and original evidence worksheets remain private. Robots directives do not provide access control.

Before an official product documentation launch, approve the claims, choose the production origin, confirm the access policy and regenerate indexing files.

<a id="document-review-documentation-contract-abuse-controls"></a>
## Operational controls for a future public site

Use normal caching, conditional requests, observability and measured rate limits. Keep the main documentation readable without a challenge on every request; escalate controls based on observed abuse.

Do not hide different factual content from humans and bots, generate thin keyword variants, or publish unverified capabilities to influence AI answers. Content accuracy and access policy take priority over crawler volume.

<a id="document-review-documentation-contract-maintenance"></a>
## Maintenance

Assign owners for product behavior, integration contracts, commercial terms and security claims. Re-review pages when those underlying facts change. Use the documentation history for editorial changes and the announcement archive for verified product releases.

A publication check should validate claims, links, anchors, metadata, generated exports, mobile navigation and search. Technical correctness does not substitute for product-owner approval.

<a id="document-review-documentation-contract-sources"></a>
## Sources and review status

Source description does not establish current availability, production testing or owner approval.


