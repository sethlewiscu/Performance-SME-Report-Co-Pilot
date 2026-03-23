# ClickUp Super Agent Mapping Document

# ClickUp Super Agent Mapping Document

This document provides a mapping of key terms and keywords to their exact Compendium documentation, including category, squad, and notes. Each entry is based on the full context of the Troubleshooting Compendium and its subpages. Subpages are included for each squad/feature area where available.

> **How this document is used by Bug Goblin**  
> Bug Goblin treats this mapping table as its **primary index** over the Troubleshooting Compendium. It uses the terms here to infer Category and Squad, then follows the Compendium links to load only the smallest set of relevant pages (for example, report-type templates and SME Knowledge) instead of the entire Compendium. The Compendium remains the source of truth; this mapping keeps routing fast, stable, and predictable.  
> **Multi-squad surfaces (clipboard, inline mentions, previews)**  
> When a mapping row lists **multiple squads** (for example, `Docs Squad + Integration Services` for clipboard / copy-paste / inline mentions), Bug Goblin must:  
> Treat **all listed squads as equal candidates** when doing regression / PR searches.  
> Include repos and components from **each** squad’s area when building GitHub queries.  
> Avoid discarding PRs solely because they are owned by a different squad than the defect’s primary Squad field.

| Term / Keyword                    | Compendium Doc URL                                                                                                               | Category                | Squad/Feature Area         | Notes                                                                              |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | -------------------------- | ---------------------------------------------------------------------------------- |
| External Tools                    | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5838413](https://app.clickup-stg.com/333/docs/ad-876561/ad-5838413)) | Tools & Resources       | Technical Support          | Chrome Extension, cURL, BrowserStack, see subpages for specifics                   |
| Defect Title Best Practices       | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5534045](https://app.clickup-stg.com/333/docs/ad-876561/ad-5534045)) | Bug Reporting           | All Support                | Title structure, clarity, actionable reporting, F.A.C.T. acronym                   |
| Hierarchy                         | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945)) | Product Troubleshooting | Hierarchy Squad            | Location IDs, DataDog logs, FAQs, SME knowledge, see subpages for report types     |
| HAR/COSL File                     | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5479025](https://app.clickup-stg.com/333/docs/ad-876561/ad-5479025)) | Diagnostics             | All Support                | When/how to collect, file security, best practices, references to related SOPs     |
| Access Management / User Platform | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633)) | Product Troubleshooting | Access Management Squad    | API troubleshooting, syntax, platform, see subpages for report types and team tips |
| Integration Services              | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913)) | Product Troubleshooting | Integration Services Squad | Troubleshooting steps, DataDog, permissions, see subpages for SME knowledge        |
| Core Services                     | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829)) | Product Troubleshooting | Core Services Squad        | SSO/SCIM, SAML, Okta, Microsoft, troubleshooting, see subpages for SME knowledge   |
| Project Management                | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361)) | Product Troubleshooting | Project Management Squad   | Settings, ClickApps, HAR for time tracking, SME knowledge, see subpages            |
| Integrations                      | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813)) | Product Troubleshooting | Integrations Squad         | 3rd-party integrations, reconnecting, DataDog, see subpages for SME knowledge      |
| Internal Tools                    | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5838185](https://app.clickup-stg.com/333/docs/ad-876561/ad-5838185)) | Tools & Resources       | Technical Support          | Chrome Extension, bug management, see subpages for details                         |
| Attachments                       | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673)) | Docs Troubleshooting    | Docs Squad                 | Copy-by-reference, PAL, Trash, permissions, see subpages for report types          |
| Repro Steps                       | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5514949](https://app.clickup-stg.com/333/docs/ad-876561/ad-5514949)) | Bug Reporting           | All Support                | Numbered steps, clarity, visual aids, self-contained reports                       |
| Email From ClickUp                | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533189](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533189)) | Product Troubleshooting | Task Squad                 | EML files, error codes, troubleshooting, see subpages for SME knowledge            |
| Work Analytics                    | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285)) | Product Troubleshooting | Work Analytics Squad       | HAR for views, troubleshooting, Master Feature List tasks, see subpages            |
| Email into List/Task              | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533213](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533213)) | Product Troubleshooting | Task Squad                 | Email-to-task, logs, evidence gathering, see subpages for SME knowledge            |
| Notifications                     | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732233](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732233)) | Docs Troubleshooting    | Docs Squad                 | Channel scoping, bundling, ClickBot, email delivery, see subpages for report types |
| Billing / CRM                     | (No direct Compendium doc found, see note below)                                                                                 | Product Troubleshooting | CRM & Billing              | For billing/CRM, refer to internal escalation or SME for guidance                  |

| Term / Keyword                                                | Compendium Doc URL                                            | Category                | Squad/Feature Area                                                              | Notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AI / ClickUp AI                                               | [](https://app.clickup-stg.com/333/v/dc/ad-876561/ad-5433921) | Product Troubleshooting | AI Squad                                                                        | SSO/SCIM, SAML, Okta, Microsoft, troubleshooting, see subpages for SME knowledge. For SSO Ops Requests (true DB-side fixes rather than config-only changes), Bug Goblin should:<br>Use the SSO Compendium content here plus the [SSO Full Coverage](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-1556329) and [SSO Troubleshooting SOP](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-2617149) docs to understand whether the problem is policy/config vs data.<br>Prefer configuration and login-policy flows first; treat DB Ops as additive and high-risk, owned by Core Services.<br>When Bug Goblin is roughly 85% confident that the ticket matches a DB Ops pattern that the TS team is allowed to request, its reply to the TS rep should coach them to (a) gather the missing fields called out in the mapping/SSO docs, and (b) prepare a proper post in the [](https://app.clickup-stg.com/333/chat/r/ad-1836837)summarising the intended Ops Request, before creating or linking an Ops Request task.<br>For the DB-side changes themselves, route via the [Bug Goblin DB Ops Mapping Document](https://app.clickup-stg.com/333/v/dc/ad-4102969/ad-7624037) so Ops Requests are clearly scoped with validation and rollback considerations, but leave exact query design to Core Services. |
| Search                                                        | [](https://app.clickup-stg.com/333/v/dc/ad-876561/ad-5472229) | Product Troubleshooting | Search / Platform Squad                                                         | Primary index for search-feature incidents (workspace/global search and filters); combine with Hierarchy or Work Analytics templates when issues span search plus data; prefer this mapping over generic Compendium root search when user language clearly indicates the search feature.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Billing / CRM                                                 |
| Clipboard / Copy-Paste / Inline Mentions                      | [](https://app.clickup-stg.com/333/v/dc/ad-876561/ad-5664913) | Product Troubleshooting | Docs Squad + Integration Services                                               | Use when reports mention copy/paste, clipboard, link previews, or inline task previews in chat, comments, or docs. For regressions, treat this as a cross-surface issue: Docs owns the visible editor surface; Integration Services owns the clipboard / link-mention pipeline. Bug Goblin should consider PRs from both squads and must not filter PR candidates only by the defect’s primary Squad field.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [](https://app.clickup-stg.com/333/v/dc/ad-876561/ad-5879861) | Product Troubleshooting                                       | CRM & Billing Squad     | Compendium gap for billing/CRM; default to SME escalation and process guidance. |

## Subpages for Each Squad/Feature Area

### Hierarchy Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433949](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433949))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433965](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433965))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433953](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433953))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433961](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433961))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433957](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433957))

### Access Management Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478653](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478653))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478649](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478649))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478645](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478645))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478641](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478641))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478637](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478637))

### Integration Services Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664917](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664917))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664933](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664933))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664925](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664925))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664921](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664921))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664929](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664929))

### Core Services Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879837](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879837))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879833](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879833))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879841](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879841))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879845](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879845))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879849](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879849))

### Project Management Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535369](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535369))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535377](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535377))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535365](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535365))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535373](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535373))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535381](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535381))

### Integrations Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664829](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664829))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664817](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664817))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664821](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664821))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664833](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664833))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664825](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664825))

### Docs Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732689](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732689))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732685](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732685))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732677](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732677))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732693](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732693))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732681](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732681))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732249](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732249))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732245](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732245))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732237](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732237))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732253](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732253))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732241](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732241))

### Task Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533201](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533201))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533209](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533209))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533197](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533197))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533205](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533205))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533193](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533193))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533225](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533225))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533233](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533233))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533221](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533221))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533217](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533217))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533229](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533229))

### Work Analytics Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553297](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553297))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553301](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553301))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553289](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553289))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553305](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553305))
- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553293](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553293))

### CRM & Billing Squad

- There is currently no Troubleshooting Compendium coverage for billing/CRM. Treat this as a **Compendium gap**, not a Bug Goblin mapping bug. Default behavior: Goblin should gather a clean problem statement + environment and recommend escalation to the appropriate CRM/Billing SME or process.

### AI Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433921](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433921))
  > **Note:** The AI Compendium section is currently a single high-level page rather than a full set of `Confirmed/Unconfirmed/Known Issue` templates. Bug Goblin should still use this page to:  
  > Infer that an issue belongs to the **AI Squad**.  
  > Pull any SME guidance and common scenarios from this page.  
  > Fall back to general report-type templates from related squads (for example, Core Services or Work Analytics) when AI-specific report templates are not defined.

### Search / Platform Squad

- Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5472229](https://app.clickup-stg.com/333/docs/ad-876561/ad-5472229))
  > **Note:** As with AI, the Search Compendium coverage is currently focused on a single feature-area page. Bug Goblin should:  
  > Use this page to recognize **search-feature incidents** (workspace search, global search, filter behavior).  
  > Combine this with Hierarchy or Work Analytics templates when a bug spans both search and data-sourcing.  
  > Prefer this mapping over generic Compendium root search when user language clearly indicates the search feature.

---

**If you need to add more squads or terms, or want to update this mapping, please provide the relevant documentation or SME contacts.**

# Helpdesk Troubleshooting Map — Help Center Tech Pages

# Helpdesk Troubleshooting Map — Help Center Tech Pages

## Purpose

This page maps key ClickUp Help Center articles related to Technical Support troubleshooting into internal context so agents like **Bug Goblin** can seamlessly cross-reference user-facing and internal resources.

## Structure

- Each section corresponds to a main Help Center category or topic that Technical Support handles.
- Each entry includes:
  - Help Center article title
  - URL
  - Short summary
  - Key internal keywords for contextual reference (search/Compendium alignment)

## Sections

### Data & Privacy (GDPR/DMD/DSR)

- **GDPR / DMD / DSR Requests**

URL: [https://help.clickup.com/hc/en-us/articles/15141672260375--GDPR-DMD-DSR-Requests](https://help.clickup.com/hc/en-us/articles/15141672260375--GDPR-DMD-DSR-Requests)

Summary: Explains how customers can submit data modification, deletion, or download (DSR) requests. Includes compliance timelines and team responsibilities.

Keywords: `GDPR requests`, `data deletion`, `data export`, `privacy support`, `data management`

### Account Access & Authentication

(Placeholder for technical support Help Center pages such as login issues, password resets, and access troubleshooting)

### Integrations & API

(Placeholder for key guides like Zapier setup, API key management, OAuth troubleshooting)

### Workspace Management

(Placeholder for Help Center articles about workspace transfer, admin rights, and user management troubleshooting)

### Performance & Errors

(Placeholder for troubleshooting guides related to speed, downtime, and browser errors)

### Notifications & Emails

(Placeholder for articles dealing with notification issues and email sending/receiving problems)

## Integration Plan

- To be nested under the Private ([https://app.clickup-stg.com/333/docs/ad-4102969/ad-7163241](https://app.clickup-stg.com/333/docs/ad-4102969/ad-7163241)).
- Used internally by **Bug Goblin** for Compendium linking.
- Can be expanded over time to include all Technical Support categories with both public and internal doc alignment.

---

_Last updated automatically via Agent Editor setup._

# Helpdesk Context Mapping

# Helpdesk Context Mapping Table

This document provides a full mapping of all technical support tools — both internal and external — connected to ClickUp’s Helpdesk processes. It maps each tool to its troubleshooting context, linked internal documentation, and team ownership. This page is used internally by Bug Goblin and TSE engineers for rapid contextual lookups.

| Tool Name                   | Tool Type                 | Primary Function                                   | Linked Internal Doc(s)                                                                                                           | Squad / Team Context   | Notes / Internal Tips                                                                                                |
| --------------------------- | ------------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Zendesk**                 | External Helpdesk         | Customer ticket management and escalation tracking | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1226581](https://app.clickup-stg.com/333/docs/ad-614317/ad-1226581)) | Customer Support / TSE | Used for inbound customer cases. Tickets escalated → internal TSE list. Include data sync behavior.                  |
| **CRM (Browser)**           | Internal Tool             | Tracks account interactions & customer data        | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-3679717](https://app.clickup-stg.com/333/docs/ad-614317/ad-3679717)) | Sales / TSE            | Used to confirm CRM → ClickUp link correlation for user orgs.                                                        |
| **Qualtrics (CSAT)**        | Feedback System           | Collects satisfaction survey responses             | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1147865](https://app.clickup-stg.com/333/docs/ad-614317/ad-1147865)) | Customer Experience    | Connects to escalation matrix via feedback scoring logic.                                                            |
| **Ada Bot**                 | Automation / AI Assistant | Customer-facing support automation                 | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1154457](https://app.clickup-stg.com/333/docs/ad-614317/ad-1154457)) | CS Automations / TSE   | Use for tracking user entry points and auto-resolved flows.                                                          |
| **BrowserStack**            | External Tool             | Mobile/web compatibility testing                   | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-3546105](https://app.clickup-stg.com/333/docs/ad-614317/ad-3546105)) | Engineering QA         | Reference for mobile build validation steps.                                                                         |
| **DataDog**                 | Monitoring Tool           | Tracks telemetry & performance traces              | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1793189](https://app.clickup-stg.com/333/docs/ad-614317/ad-1793189)) | Datadog Infra Squad    | Do not pull trace data directly; refer to [@Datadog Analysis](https://app.clickup-stg.com/333/ai/agents/ad-3616821). |
| **Salesforce**              | CRM Platform              | Handles account data for enterprise clients        | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-4159869](https://app.clickup-stg.com/333/docs/ad-614317/ad-4159869)) | Sales Operations / TSE | Use for customer hierarchy and contract confirmation details.                                                        |
| **Zendesk Sidebar + Tools** | Internal Extension        | Agent companion dashboard                          | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1157781](https://app.clickup-stg.com/333/docs/ad-614317/ad-1157781)) | Customer Success       | Provides quick context in ticket sidebar.                                                                            |
| **Customer POV Guide**      | Internal Tool             | Shows complete customer environment lens           | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-1250429](https://app.clickup-stg.com/333/docs/ad-614317/ad-1250429)) | TSE / Engineering      | Used to recreate customer view for reproduction.                                                                     |

# Helpdesk Context Mapping (Placeholder Update)

# Helpdesk Context Mapping - Temporary Placeholder

⚠️ **This page’s previous content has been deprecated.**

The prior table included outdated internal-only references and has been cleared pending rebuild.

### Next Steps for Editors

- Use this placeholder as a staging area.
- The new mapping should reference the **ClickUp Help Center – Internal Knowledge Base category** located here:

[https://help.clickup.com/hc/en-us/categories/14395224289047--INTERNAL-Knowledge-Base](https://help.clickup.com/hc/en-us/categories/14395224289047--INTERNAL-Knowledge-Base)

### What To Do

1. **Remove this placeholder note** after adding the correct Help Center data.
2. **Rebuild the mapping table** using article data and sections from the linked Help Center category.
3. Include columns for:
   - Article Title / Link
   - Help Center Section
   - Primary Function / Topic
   - Related Squad / Category (if applicable)
   - Internal Notes / Relationship to TSE Flows

This ensures Bug Goblin and TSE agents pull consistent, officially maintained knowledge instead of workspace-specific references.

# Helpdesk Context Mapping — Internal Knowledge Base

# Helpdesk Context Mapping — Internal Knowledge Base

This mapping aligns the ClickUp Help Center’s **Internal Knowledge Base** category articles to internal support context for Technical Support Engineers (TSEs) and Bug Goblin workflows. Each row connects an article with its functional purpose, related tools or features, and internal usage notes.

| Help Center Article                                | Section                 | Primary Focus                                             | Related Tool / Feature          | Squad / Category      | Link                                                            |
| -------------------------------------------------- | ----------------------- | --------------------------------------------------------- | ------------------------------- | --------------------- | --------------------------------------------------------------- |
| **Performance Issues**                             | Troubleshooting         | Steps and diagnostics for app performance problems        | Infrastructure, App Performance | Platform Engineering  | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Handling User Data**                             | Compliance & Privacy    | Data handling processes and privacy requirements          | Security Tools, API             | Security / Infra      | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Merging Defects**                                | Defect Management       | Instruction on merging duplicate defects                  | 🐞 Defects Master Lists         | TSE / QA              | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Recording in the User’s Workspace**              | Session Analysis        | Describes field recording and reproduction best‑practices | Workspace Explorer              | TSE / QA              | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Chargebacks and Disputes**                       | Billing & Issues        | Financial dispute resolution standards                    | Billing Platform                | Finance / CS          | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Splitting Tickets**                              | Zendesk Ops             | Workflows for automating ticket splits                    | Zendesk                         | Support Operations    | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Problem Manager Contact**                        | Escalation              | Escalation contact structure and flow                     | Internal Escalations            | Support Leadership    | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Shared Microsoft Account Access**                | Secure Auth             | Secure credential sharing                                 | Okta / OneLogin                 | IT / Security         | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Internal Unsubscribe Utility – Support Version** | Tools                   | Guide for automated unsubscribe tool usage                | Unsubscribe Utility             | CS Tools              | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Internal Unsubscribe Utility – General Use**     | Tools                   | General unsubscribe automation                            | Unsubscribe Utility             | Internal Ops          | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Guide Knowledge Base**                           | Reference               | Documentation hub for internal support knowledge          | Compendium System               | All Teams             | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Non‑Billing Questions**                          | Support FAQs            | Handling non‑invoice questions with accuracy              | CS Platforms                    | Billing               | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Workspace Knowledge Base**                       | General Operations      | Workspace operations documentation structure              | Docs / Platform                 | Platform Team         | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Internal Comms**                                 | Collaboration           | Coordination and team communication improvements          | Slack / Internal Messaging      | Support Comms         | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Customer Support**                               | Service Delivery        | Overview of customer support processes and service tiers  | Helpdesk Platform               | Support Org           | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Customer Experience (CX)**                       | Service Delivery        | CX metrics and standards                                  | CSAT / Qualtrics                | Support Org           | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Internal Knowledge to Docs**                     | Publishing              | Workflow for converting internal notes to public articles | Docs Platform                   | Product Education     | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **ClickUp Brain Knowledge Wiki**                   | AI Knowledge            | Overview of ClickUp Brain as a knowledge management tool  | ClickUp Brain / AI              | Product / Engineering | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Core Services Knowledge Base — Overview**        | Systems                 | Foundational technical documentation for core services    | Core Services                   | Engineering           | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Knowledge Management Convergence Script**        | Process                 | Description of convergence process for KB integrity       | Knowledge Ops                   | Enablement            | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Knowledge Management Strategy + Vision Doc**     | Organizational Strategy | Long‑term document governance goals                       | Documentation Tools             | Enablement            | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Performance Troubleshooting Checklist**          | Troubleshooting         | Checklist for recurring app or network issues             | Core Performance Tools          | Platform / QA         | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Post‑Call Summary**                              | Customer Service        | Template and standards for post‑interaction documentation | Zendesk / CRM                   | TSE / CS              | [View Article](https://help.clickup.com/hc/en-us/articles/....) |
| **Problem Escalation Chain**                       | Escalation Management   | Responsibilities and routing details                      | Escalation Matrix               | TSE / Leadership      | [View Article](https://help.clickup.com/hc/en-us/articles/....) |

---

### Notes for Editors

- This table reflects the **Internal Knowledge Base** category structure as of the latest Help Center index.
- To update automatically, Bug Goblin uses `Search Help Center` to retrieve canonical URLs and refresh rows.
- Each mapping entry supports Helpdesk, Bug Goblin, and TSE reference workflows for faster troubleshooting automation.

# Bug Goblin DB Ops Mapping Document

# Bug Goblin DB Ops Mapping Document

This document is a **DB/Ops-specific mapping index** for Bug Goblin. It mirrors the structure of the main Private ([https://app.clickup-stg.com/333/docs/ad-4102969/ad-7163241](https://app.clickup-stg.com/333/docs/ad-4102969/ad-7163241)), but is scoped to cases where the correct next step is a **database operation / Ops Request**.

> **How this document is used by Bug Goblin**
>
> Bug Goblin uses this table as its **primary index over DB/Ops flows**, especially the content in:  
> Ops Request How To's: ([https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8](https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8))  
> 980200190204 ([https://app.clickup-stg.com/333/v/li/980200190204](https://app.clickup-stg.com/333/v/li/980200190204))
>
> When user language and context indicate that a DB change is needed (rather than a pure product bugfix or feature change), Bug Goblin should:  
> Use this mapping table to infer the relevant **Ops pattern / area**.  
> Pull guidance from the linked Ops docs/queries.  
> Draft a clean, triage-ready **Ops Request** for the Ops Request Queue using the template in the Ops Request How To's doc.
> **For TS reps:** When you have a ticket that might require a DB Ops Request and Bug Goblin is ~85% confident it matches one of the patterns in the table below, its reply should (1) tell you which DB/Ops pattern it matched, (2) list any missing fields you still need to collect, and (3) guide you to prepare a post in the Private ([https://app.clickup-stg.com/333/chat/r/ad-1836837](https://app.clickup-stg.com/333/chat/r/ad-1836837)) using the Ops Request template from Ops Request How To's: ([https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8](https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8)). Only once that information is ready should you create/link the Ops Request task in the 980200190204 ([https://app.clickup-stg.com/333/v/li/980200190204](https://app.clickup-stg.com/333/v/li/980200190204)).

---

## DB/Ops Mapping Table

| Term / Keyword                                                                                  | Ops Doc / Query Reference                                                                                                                                                                  | Category (Ops Area)                              | Squad / Owner                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Notes / Query Idea                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mass unsubscribe / marketing unsubscribe                                                        | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Email / Marketing                                | Core Services / Email                                                                                                                                                                                                                                                                                                                                                                                                                                                     | When to use: Customer needs a bulk marketing unsubscribe that cannot be done safely via UI. Query idea: `UPDATE task_mgmt.users` + `task_mgmt.email_ma_status` to set `hubspot_marketing_field` and `ma_status` to `unsubscribed` for a scoped list of emails. Goblin should confirm consent, exact email list (or deterministic filter), and impact before proposing this Ops Request.                                                                                                                                                                                                                                 |
| Reset sprint state                                                                              | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Tasks / Sprints                                  | Project Management                                                                                                                                                                                                                                                                                                                                                                                                                                                        | When to use: Sprint stuck in incorrect state or needs a hard reset after incident. Query idea: `UPDATE task_mgmt.subcategories SET sprint_status = NULL, sprint_date_done = NULL WHERE id = {subcategory_id}`. Goblin should capture which sprint(s) (workspace/space/list + sprint IDs) and why a reset is safer than manual UI edits.                                                                                                                                                                                                                                                                                 |
| Add / adjust email license counts                                                               | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Licensing / Add-ons                              | Core Services / Billing                                                                                                                                                                                                                                                                                                                                                                                                                                                   | When to use: Need to adjust email license counts via DB (e.g., unblock account, align with contract) where normal billing flows are insufficient. Query idea: `INSERT ... ON CONFLICT` into `task_mgmt.team_addons` for addon_id `'email_accounts'`, updating `total`. Goblin should confirm team_id, target total vs delta, contract/go-to-market approvals, and that this aligns with CRM/Billing.                                                                                                                                                                                                                    |
| Provision / adjust other add-ons (automations, etc.)                                            | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Licensing / Add-ons                              | Core Services / Billing                                                                                                                                                                                                                                                                                                                                                                                                                                                   | When to use: One-off correction to add-on entitlements (e.g., automations) not fixable in UI. Query idea: `INSERT INTO task_mgmt.team_addons (team_id, addon_id, ...) VALUES (...)` with appropriate addon_id and total. Goblin should request addon_id, desired entitlement, and any existing entries to avoid over-provisioning.                                                                                                                                                                                                                                                                                      |
| Public form toggle stuck / cannot deactivate                                                    | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Forms / Sharing                                  | Project Management                                                                                                                                                                                                                                                                                                                                                                                                                                                        | When to use: Publicly shared form cannot be turned off/on in UI due to stale DB state. Query idea: `UPDATE task_mgmt.views SET public_share_expires_on = NULL WHERE view_id = 'VIEWID'`. Goblin should collect the exact view_id, workspace, and user expectation (what they tried, what happened) for the Ops Request.                                                                                                                                                                                                                                                                                                 |
| Count / find guests in a workspace                                                              | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Access / Permissions                             | Access Management                                                                                                                                                                                                                                                                                                                                                                                                                                                         | When to use: TSE or Ops needs a DB-level count of guests or a list of guest users scoped by role/team. Query idea: multi-UNION `SELECT` over `task_mgmt.team_members`, projects, categories, subcategories, items, and group_members to count distinct guest user IDs for a given team_id + role. Goblin should treat this primarily as a read-only investigation and be explicit about filters (team_id, role).                                                                                                                                                                                                        |
| Find tasks by workspace + search term                                                           | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Tasks / Search                                   | Hierarchy Squad / Platform                                                                                                                                                                                                                                                                                                                                                                                                                                                | When to use: Need a DB-level list of tasks matching a name pattern within a specific workspace/team to investigate scope or prepare a follow-up DB change. Query idea: `SELECT items.* FROM task_mgmt.teams JOIN projects/categories/subcategories/items ... WHERE teams.id = {TeamID} AND items.name ILIKE '%SearchTerm%'`. Goblin should classify this as read-only unless explicitly paired with an update/backfill in the request.                                                                                                                                                                                  |
| List all tasks in a space                                                                       | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | Tasks / Hierarchy                                | Hierarchy Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                           | When to use: Need complete task set in a space by `projects.id` for investigation, reporting, or to scope a potential DB update. Query idea: `SELECT items.* FROM task_mgmt.projects JOIN categories/subcategories/items ... WHERE projects.id = {ProjectID}`. Goblin should help TSE articulate why this dataset is needed and what follow-up action (if any) is expected.                                                                                                                                                                                                                                             |
| Check user last login date                                                                      | [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)                                                                                                                               | User Metadata                                    | Core Services                                                                                                                                                                                                                                                                                                                                                                                                                                                             | When to use: Need authoritative DB last-login info for audit or to validate behavioral assumptions when deciding on Ops work (e.g., safe to modify inactive users). Query idea: `SELECT id, username, to_char(to_timestamp(users.last_login_web / 1000.0), ...) FROM task_mgmt.users WHERE id = {userid}`. Goblin should use this as supporting investigation, not as a standalone Ops Request in most cases.                                                                                                                                                                                                           |
| One-off data fixes (tasks, hierarchy, permissions)                                              |
| SSO required but user not linked / cannot log in                                                | [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-2617149)                                                                                                                              | SSO / Access Management                          | Core Services Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                       | When to use: Workspace has SSO required and a specific user is locked out because their ClickUp account is not linked to the IdP, and normal policy adjustments + login-bypass flows have been exhausted. DB Ops guidance: Default stance is to resolve via configuration and login policy (as in SSO Troubleshooting SOP). Bug Goblin should only suggest DB Ops as a last resort (e.g., correcting a bad internal SSO flag or policy row) and must route to Core Services SME with a clearly scoped Ops Request, referencing the SOP steps already attempted. No direct SQL shapes should be invented by Goblin here. |
| SSO login policy / enforcement corrections after drift                                          | [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-1556329),[](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-2617149)                                                                | SSO Policy / Security                            | Core Services Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                       | When to use: Org-level SSO policy (optional/guests-only/required) has drifted from intended state and is blocking correct login behavior across many users. DB Ops guidance: Bug Goblin should first guide TSEs through policy UI changes and login-bypass flows. If Core Services confirms a DB repair is needed (e.g., bulk correction of a mis-set SSO policy flag), Goblin’s Ops Request should describe the intended policy, affected workspaces, and number of users, but leave the exact query details to Core Services.                                                                                         |
| SAML metadata / attribute corrections (IdP config is fixed, but ClickUp state is stale)         | [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-2617149), [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-1556377),[](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-1574793) | SSO / SAML                                       | Core Services Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                       | When to use: Identity Provider configuration and attributes have been corrected, but users are still blocked because of stale SAML metadata or attributes stored on the ClickUp side. DB Ops guidance: Bug Goblin should help the TSE document: workspace/team IDs, IdP type, examples of affected users, and links to XML metadata. Any DB Ops request here should be framed as “align ClickUp-stored SAML metadata/attributes with current IdP configuration,” not a hand-written query. Query design belongs to Core Services.                                                                                       |
| SCIM provisioning corrections (Okta SCIM → ClickUp)                                             | [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-1556369)                                                                                                                              | SSO / SCIM Provisioning                          | Core Services Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                       | When to use: Okta SCIM has created or updated users incorrectly (wrong workspace, wrong roles, duplicate records) and normal SCIM sync/config isn’t enough to repair data at scale. DB Ops guidance: Bug Goblin should classify these as high-risk DB Ops and only propose them after config-level fixes are confirmed. Ops Requests should focus on: which SCIM objects/users are wrong, target state, and sample records. Actual SQL patterns should come from Core Services/SCIM SMEs, not from Goblin.                                                                                                              |
| SSO identity / account mapping repairs (wrong ClickUp user linked to IdP identity)              | [](https://app.clickup-stg.com/333/v/dc/ad-100291/ad-2617149)                                                                                                                              | SSO / Identity Linking                           | Core Services Squad                                                                                                                                                                                                                                                                                                                                                                                                                                                       | When to use: A ClickUp account is incorrectly linked to an IdP identity (wrong person, reused email, etc.), and simple unlink/relink steps cannot resolve it. DB Ops guidance: Bug Goblin should help gather: workspace IDs, ClickUp user IDs, IdP identifiers (email, NameID), and a clear description of which accounts should be linked/unlinked. Ops Requests should ask Core Services to design and run any sensitive identity-linking updates; Goblin must not propose direct edits to identity-link tables itself.                                                                                               |
| [](https://app.clickup-stg.com/333/v/dc/ad-384345/ad-615237)\+ appropriate Compendium squad doc | Hierarchy / Permissions / Tasks                                                                                                                                                            | Hierarchy Squad / Access Management / Task Squad | When to use: Corrupted hierarchy, orphaned objects, or mis-set permissions where UI tools cannot fix data at scale. Query idea: Case-by-case, combining patterns from Ops How To's with the owning squad's Compendium doc. Goblin should 1) confirm DML vs MFL ownership, 2) propose a narrow, auditable DB change with predicates + validation queries, and 3) clearly distinguish between the defect/feature record and the Ops Request that applies the manual repair. |

> **Note:** This table is intentionally small to start. As new DB/Ops patterns are formalized, add new rows with:  
> Clear terms/keywords that show up in TSE language.  
> A stable query or doc reference.  
> The owning squad/area.  
> Opinionated guidance in the Notes column about when DB Ops is appropriate vs. when to prefer DML/MFL only.

---

## Special Multi-Squad / Cross-Surface DB Patterns

Some DB operations cut across multiple product surfaces or squads (e.g., data corrections that affect tasks, notifications, and analytics). For these, Bug Goblin should:

- Treat **all listed squads** as relevant when looking up context and report templates.
- Preserve the correct **primary Squad** on DML/MFL, but not over-filter Ops-related evidence to a single squad.
- Make trade-offs explicit in Notes (e.g., performance impact vs. user experience fix).

| Pattern                                                                  | Related Squads                        | Notes for Bug Goblin                                                                                                                                                                                          |
| ------------------------------------------------------------------------ | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Large-scale data backfills touching hierarchy + analytics                | Hierarchy + Work Analytics            | Bug Goblin should flag that both data integrity and reporting must be validated. Ops Requests must include validation plans (e.g., sample queries) and clear rollback criteria.                               |
| Cross-feature permission/visibility repairs (tasks, docs, notifications) | Access Management + Docs + Task Squad | Use DB Ops only after exhausting configuration and UI options. Goblin should help TSE spell out which users/workspaces are impacted and how to verify that visibility is restored without over-exposing data. |

---

## Relevant Ops Docs & Subpages

This section mirrors the "Subpages for Each Squad/Feature Area" pattern from the Super Agent doc, but points Bug Goblin at DB/Ops-relevant materials.

### Core / Email / Marketing Ops

- Ops Request How To's: ([https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8](https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8)) – mass unsubscribe, email license updates, user last login checks, etc.
- Email/notification-related Compendium pages (via Super Agent Mapping) – use for understanding feature behavior and report structure before proposing DB changes.

### Project Management / Tasks / Sprints

- Ops Request How To's: ([https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8](https://doc.clickup-stg.com/d/h/ad-615237/18e79a57cf058f8)) – reset sprint, task-level queries.
- Project Management squad Compendium pages – use for regression scope and UI expectations around sprints and tasks.

### Hierarchy / Access / Permissions

- Ops/DB snippets involving team_ids, workspace structures, or team_addons (inside Ops Request How To's).
- Hierarchy + Access Management Compendium pages for correct ownership and reporting.

### SSO / Core Services

- Private ([https://app.clickup-stg.com/333/docs/ad-100291/ad-1556329](https://app.clickup-stg.com/333/docs/ad-100291/ad-1556329)) – overview of SSO architecture, providers, and policy options.
- Private ([https://app.clickup-stg.com/333/docs/ad-100291/ad-2617149](https://app.clickup-stg.com/333/docs/ad-100291/ad-2617149)) – core login policy flows, common SSO failure modes, and safe workarounds before any DB intervention.
- Private ([https://app.clickup-stg.com/333/docs/ad-100291/ad-2617185](https://app.clickup-stg.com/333/docs/ad-100291/ad-2617185)) – provider-specific setup/troubleshooting (Microsoft, Okta, Google, SAML). Use these to confirm configuration is correct before considering DB Ops.

---

## Gaps & Escalation Guidance

- Some DB Ops patterns are **intentionally rare** or undocumented. When Bug Goblin encounters:
  - Security-sensitive requests (bulk deletions, cross-workspace moves, GDPR/PII-related operations), or
  - Anything not represented in this mapping table,

it should **not** invent a DB flow. Instead it should:

1. Help the TSE write a clean problem statement and environment summary.
2. Suggest filing/linking a DML and/or MFL as appropriate.
3. Recommend escalation to TIM / the appropriate squad SME for DB guidance, noting "DB Ops mapping gap" as part of the summary.

As this DB Ops mapping matures, new rows should be added to the table above so Bug Goblin can handle more patterns autonomously while keeping routing predictable and safe.

# Squad Dropdown ID to Compendium Mapping

# Squad Dropdown ID to Compendium Mapping

This page maps each dropdown option ID from the custom field `👥 Squad` (ID: 4bbd5486-9e1c-4f0f-b35b-3792250988cc) to the relevant Compendium documentation search. Use this mapping to quickly index the DML and locate squad-specific documentation.

| Dropdown Option                                  | Dropdown ID                          | Compendium Search/Doc                                                                                                            |
| ------------------------------------------------ | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Access Management                                | 2597f33f-b8cd-4b8a-b413-85141c120df4 | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633)) |
| AI Platform                                      | 6dcffd7f-4718-4808-beda-c80815b8ba07 | _(Search: "AI Platform" in Compendium)_                                                                                          |
| AI Product                                       | 518dd417-661d-4343-a985-f6030836de05 | _(Search: "AI Product" in Compendium)_                                                                                           |
| All or Many                                      | 0ebc0055-2bf7-4608-8e96-5359ab6b229c | _(Search: "All or Many" in Compendium)_                                                                                          |
| All Squad Program                                | e3a87c3b-d945-4a7b-a3ec-e7bd5fba7616 | _(Search: "All Squad Program" in Compendium)_                                                                                    |
| Automations                                      | 214b89b1-682f-44ba-b2a4-52b070eb30d2 | _(Search: "Automations" in Compendium)_                                                                                          |
| Calendar                                         | 4ce1a74a-5363-4bc0-ad5b-76ccadaccc3c | _(Search: "Calendar" in Compendium)_                                                                                             |
| Cards                                            | 71965ef4-5604-480e-ac03-0538d0a30a4e | _(Search: "Cards" in Compendium)_                                                                                                |
| CCE                                              | b7756dc0-0e79-4c72-ab72-ec7e1c57d3e7 | _(Search: "CCE" in Compendium)_                                                                                                  |
| Chat                                             | b914a475-a09c-476c-9a6b-9aa3da8047de | _(Search: "Chat" in Compendium)_                                                                                                 |
| Clips                                            | 1a0efb06-6b9b-452c-8851-473a2f30e838 | _(Search: "Clips" in Compendium)_                                                                                                |
| Cloud Platform                                   | d9db6380-686c-485a-8f9f-5a43544f7044 | _(Search: "Cloud Platform" in Compendium)_                                                                                       |
| Content Strategy / Help Center                   | 7b06326e-7f8c-4b0e-9f2d-62ae63177fb6 | _(Search: "Content Strategy" or "Help Center" in Compendium)_                                                                    |
| Core Services                                    | 8e5b6060-d164-4041-b744-2c03b4a33078 | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829)) |
| CRM & Billing                                    | e2455c1d-279e-4048-a347-c39ae18ece92 | _(No direct doc, escalate or SME)_                                                                                               |
| Data Eng                                         | 02a1dda1-f99e-4f53-861c-e9245620adaa | _(Search: "Data Eng" in Compendium)_                                                                                             |
| Data Platform                                    | 1c81a2e0-9125-4262-b9f0-90f99a65d027 | _(Search: "Data Platform" in Compendium)_                                                                                        |
| db                                               | dc75efcd-d7f5-41df-928c-84c28005676f | _(Search: "db" in Compendium)_                                                                                                   |
| DB Ops                                           | 3894d798-1225-40da-8ec7-ab4ebc8beaf4 | _(Search: "DB Ops" in Compendium)_                                                                                               |
| DevOps - Deprecated                              | 1790cfc5-9330-4d3a-8e8a-21db360dcaf9 | _(Search: "DevOps" in Compendium)_                                                                                               |
| Docs                                             | 8cac43a8-fabe-42a1-891c-f59aef936018 | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673)) |
| Eng Prod                                         | 3c862d75-70fc-4572-84a5-257a2199be52 | _(Search: "Eng Prod" in Compendium)_                                                                                             |
| Engineering Productivity                         | 115cdcf8-2915-4faa-a1a6-16df8ac9461f | _(Search: "Engineering Productivity" in Compendium)_                                                                             |
| EU SRE                                           | a820dc92-7f47-4d61-9c7c-1c8348e1ec50 | _(Search: "EU SRE" in Compendium)_                                                                                               |
| Extensions                                       | 97054dd1-ce0d-4f5a-8998-4dc962079969 | _(Search: "Extensions" in Compendium)_                                                                                           |
| FE Eng Sys                                       | 08a9ecc0-db0d-4a36-92ba-b71dcb0216c3 | _(Search: "FE Eng Sys" in Compendium)_                                                                                           |
| FE Platform                                      | 358bfe55-2bf4-4dd0-8927-dacf595b494d | _(Search: "FE Platform" in Compendium)_                                                                                          |
| Fields                                           | 8ec55f6a-d577-4e1f-ba4e-5a9cb4b47d60 | _(Search: "Fields" in Compendium)_                                                                                               |
| Forms                                            | 5ce577bc-1a16-421d-bf94-2a80234250e1 | _(Search: "Forms" in Compendium)_                                                                                                |
| Growth                                           | 122cf4dd-e7c0-40cd-a314-c690508dd807 | _(Search: "Growth" in Compendium)_                                                                                               |
| Hierarchy                                        | e9a4a4a8-e06b-43b0-9175-c3be44b95d8c | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945)) |
| Hubs & Widgets                                   | 35bbe303-4deb-4b39-92f1-548ca8315df5 | _(Search: "Hubs & Widgets" in Compendium)_                                                                                       |
| Imports                                          | 361731e6-3e3c-45da-b7cc-6a5d34e16d19 | _(Search: "Imports" in Compendium)_                                                                                              |
| Inbox                                            | 283a7b10-0f2f-403b-a170-ed049427cd2c | _(Search: "Inbox" in Compendium)_                                                                                                |
| Infra                                            | fab5c827-c21d-4985-8f16-d567b3984cbe | _(Search: "Infra" in Compendium)_                                                                                                |
| Initiatives                                      | a6a35215-6959-48af-967d-6926fa4098de | _(Search: "Initiatives" in Compendium)_                                                                                          |
| Innovation                                       | b39b4ab1-3fe7-4e18-bbb7-1f1435ad7f40 | _(Search: "Innovation" in Compendium)_                                                                                           |
| Integration Services                             | afc78632-ff4a-4f2d-b785-ce2261c79233 | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913)) |
| Integrations                                     | 99ce0cf3-752d-497b-8a65-74b02414374d | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813)) |
| Kitemaker                                        | 72919a6f-e127-44cd-858a-7a5d776b877a | _(Search: "Kitemaker" in Compendium)_                                                                                            |
| MAX                                              | d9e8d20a-85c4-4500-9bfc-7afd8abd1eb5 | _(Search: "MAX" in Compendium)_                                                                                                  |
| Meetings                                         | 2257ce53-dc31-4a96-a6c4-476fda843805 | _(Search: "Meetings" in Compendium)_                                                                                             |
| Mobile                                           | 92b681fd-10a0-4cc7-873b-2b85df2826c3 | _(Search: "Mobile" in Compendium)_                                                                                               |
| Not Classified                                   | 46362215-7103-45ee-85dc-227b4acaf254 | _(Search: "Not Classified" in Compendium)_                                                                                       |
| People Management (Do not use or Delete for now) | 3f55e30f-28f5-4680-90f1-7d041f0a27e6 | _(Search: "People Management" in Compendium)_                                                                                    |
| Performance                                      | d48db9fb-409d-4859-9edd-8df8ac6ae176 | _(Search: "Performance" in Compendium)_                                                                                          |
| Product Design                                   | 3c74453d-9143-4b0a-8b65-abc37702037c | _(Search: "Product Design" in Compendium)_                                                                                       |
| Project Management                               | 9bf20572-a2b4-4bea-af7b-5e68fb0be14b | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361)) |
| QA Automation                                    | 6e0cae79-2bdb-4947-9a1d-a429e74d6c2d | _(Search: "QA Automation" in Compendium)_                                                                                        |
| SD Platform                                      | 94764681-5c07-4cae-af23-07ed4e2c798b | _(Search: "SD Platform" in Compendium)_                                                                                          |
| Search                                           | 2ac0429a-017f-4582-bf1b-e35471723b22 | _(Search: "Search" in Compendium)_                                                                                               |
| Security                                         | d1d4dd2a-9e39-4d1f-b02c-4256d4294f64 | _(Search: "Security" in Compendium)_                                                                                             |
| SRE                                              | 070a6021-0e74-4c35-add5-f249f5c9216b | _(Search: "SRE" in Compendium)_                                                                                                  |
| Support                                          | 4406a9e5-1b08-4757-b5d3-d53b0d42158c | _(Search: "Support" in Compendium)_                                                                                              |
| \[Support\] Performance                          | 73bdb4d0-ee6b-4f18-abca-ab404fe5c0ca | (Search: "Performance" in **\[\[TBD\]\]**)                                                                                       |
| Tasks                                            | b0a2b00f-f5c4-4871-98b8-6cd4377d9d2e | _(Search: "Tasks" in Compendium)_                                                                                                |
| Templates                                        | c4db3ddc-0e6e-4341-b1fc-159f939e5398 | _(Search: "Templates" in Compendium)_                                                                                            |
| UI Team                                          | e9f4eaea-4f95-436f-afdb-86f963a9eccd | _(Search: "UI Team" in Compendium)_                                                                                              |
| Unknown                                          | dcd52ed6-f5ec-4bdd-95d6-62b5ef22dd01 | _(Search: "Unknown" in Compendium)_                                                                                              |
| User Platform                                    | 206d550a-08e9-472e-9c40-d9321f169158 | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633)) |
| Views                                            | 00103a8a-8a71-4b12-9ce5-f153646dd022 | _(Search: "Views" in Compendium)_                                                                                                |
| Web Engineering                                  | 074a1a2e-cbfb-495f-b25b-fd394f312858 | _(Search: "Web Engineering" in Compendium)_                                                                                      |
| Whiteboards                                      | 6cead2bf-6597-4fe1-b385-c164f4f0989d | _(Search: "Whiteboards" in Compendium)_                                                                                          |
| Work Analytics                                   | efd1e1ab-60e5-4da0-ab74-bc063892fdea | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285)) |

_For options marked "Search", use the dropdown value as a keyword in the Compendium. For direct links, click to access the mapped documentation. For CRM & Billing, escalate or consult an SME as no direct doc exists._

# Squad to Chat Channel Mapping

# Squad to Chat Channel Mapping

This page maps each dropdown option from the custom field `👥 Squad` to the most relevant chat channels.

Notes:

- Prefer the primary squad channel first (usually a squad ClickUp Chat channel, then Slack if applicable).
- Add additional niche channels (bugs, weekly updates, alerts, Zendesk handoff) only if they are commonly used for routing.

| Squad Dropdown Option | Dropdown ID                          | Primary Channels                                                                                                                                                                                                                                          | Secondary / Purpose-specific Channels                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --------------------- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Access Management     | 2597f33f-b8cd-4b8a-b413-85141c120df4 | Private ([https://app.clickup-stg.com/333/chat/r/5-98020019713-8](https://app.clickup-stg.com/333/chat/r/5-98020019713-8)) , Private ([https://app.clickup-stg.com/333/chat/r/6-980700097332-8](https://app.clickup-stg.com/333/chat/r/6-980700097332-8)) | Private ([https://app.clickup-stg.com/333/chat/r/6-980700083419-8](https://app.clickup-stg.com/333/chat/r/6-980700083419-8)) , Private ([https://app.clickup-stg.com/333/chat/r/ad-2003949](https://app.clickup-stg.com/333/chat/r/ad-2003949)) , Private ([https://app.clickup-stg.com/333/chat/r/6-980200071161-8](https://app.clickup-stg.com/333/chat/r/6-980200071161-8)) , Private ([https://app.clickup-stg.com/333/chat/r/6-980700181787-8](https://app.clickup-stg.com/333/chat/r/6-980700181787-8)) , [#squad-access-management](https://click-up.slack.com/archives/C03RP3PD9CL)                                                                                                                                               |
| User Platform         | 206d550a-08e9-472e-9c40-d9321f169158 | Private ([https://app.clickup-stg.com/333/chat/r/5-98020099151-8](https://app.clickup-stg.com/333/chat/r/5-98020099151-8)) , Private ([https://app.clickup-stg.com/333/chat/r/5-405300091-8](https://app.clickup-stg.com/333/chat/r/5-405300091-8))       | Private ([https://app.clickup-stg.com/333/chat/r/6-980700097331-8](https://app.clickup-stg.com/333/chat/r/6-980700097331-8)) , Private ([https://app.clickup-stg.com/333/chat/r/6-980200068525-8](https://app.clickup-stg.com/333/chat/r/6-980200068525-8)) , Private ([https://app.clickup-stg.com/333/chat/r/6-1155300048-8](https://app.clickup-stg.com/333/chat/r/6-1155300048-8)) , Private ([https://app.clickup-stg.com/333/chat/r/ad-2003945](https://app.clickup-stg.com/333/chat/r/ad-2003945)) , [#squad-user-platform](https://click-up.slack.com/archives/C01P8EQLHUN) , [#standup-user-platform](https://click-up.slack.com/archives/C01NYTC7EMQ) , [#retro-user-platform](https://click-up.slack.com/archives/C01NZ47EMMH) |
| Core Services         | 8e5b6060-d164-4041-b744-2c03b4a33078 | Private ([https://app.clickup-stg.com/333/chat/r/5-582300075-8](https://app.clickup-stg.com/333/chat/r/5-582300075-8))                                                                                                                                    | Private ([https://app.clickup-stg.com/333/chat/r/ad-1741545](https://app.clickup-stg.com/333/chat/r/ad-1741545))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Integration Services  | afc78632-ff4a-4f2d-b785-ce2261c79233 | Private ([https://app.clickup-stg.com/333/chat/r/5-98020101114-8](https://app.clickup-stg.com/333/chat/r/5-98020101114-8))                                                                                                                                | _(Add more as identified)_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Integrations          | 99ce0cf3-752d-497b-8a65-74b02414374d | Private ([https://app.clickup-stg.com/333/chat/r/5-405300087-8](https://app.clickup-stg.com/333/chat/r/5-405300087-8))                                                                                                                                    | [#squad-integrations](https://click-up.slack.com/archives/C02EVJ61M0B) , [#help-ps-integrations](https://click-up.slack.com/archives/C06S85HAERF) , [#integration-monitor](https://click-up.slack.com/archives/C02CMU2RF35) , [#integrations-alerts](https://click-up.slack.com/archives/C0828MKNG7K)                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Project Management    | 9bf20572-a2b4-4bea-af7b-5e68fb0be14b | Private ([https://app.clickup-stg.com/333/chat/r/6-980200065832-8](https://app.clickup-stg.com/333/chat/r/6-980200065832-8)) , Private ([https://app.clickup-stg.com/333/chat/r/5-98020018038-8](https://app.clickup-stg.com/333/chat/r/5-98020018038-8)) | Private ([https://app.clickup-stg.com/333/chat/r/ad-2003877](https://app.clickup-stg.com/333/chat/r/ad-2003877)) , Private ([https://app.clickup-stg.com/333/chat/r/6-980700097330-8](https://app.clickup-stg.com/333/chat/r/6-980700097330-8)) , [#product-project-management](https://click-up.slack.com/archives/C0392GB271P)                                                                                                                                                                                                                                                                                                                                                                                                          |
| Work Analytics        | efd1e1ab-60e5-4da0-ab74-bc063892fdea | Private ([https://app.clickup-stg.com/333/chat/r/6-980200189908-8](https://app.clickup-stg.com/333/chat/r/6-980200189908-8))                                                                                                                              | _(Add more as identified)_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Hierarchy             | e9a4a4a8-e06b-43b0-9175-c3be44b95d8c | [#squad-hierarchy](https://click-up.slack.com/archives/C035T90M2BY)                                                                                                                                                                                       | _(Add ClickUp Chat channel if one exists)_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Docs                  | 8cac43a8-fabe-42a1-891c-f59aef936018 | Private ([https://app.clickup-stg.com/333/chat/r/5-4202216-8](https://app.clickup-stg.com/333/chat/r/5-4202216-8))                                                                                                                                        | Private ([https://app.clickup-stg.com/333/chat/r/6-980200047020-8](https://app.clickup-stg.com/333/chat/r/6-980200047020-8)) , [#squad-docs-and-clips](https://click-up.slack.com/archives/C02GU2X0HM3) , [#collab-docs-ambassadors](https://click-up.slack.com/archives/C05FDQR04TY)                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

_Add rows over time as squads and their canonical channels become clear._

| Squad Dropdown Option | Dropdown ID                          | Primary Channels                                                                                                                                           | Secondary / Purpose-specific Channels |
| --------------------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| Hierarchy             | e9a4a4a8-e06b-43b0-9175-c3be44b95d8c | [](https://app.clickup-stg.com/333/v/cn/5-801300031-8), [https://click-up.slack.com/archives/C035T90M2BY](https://click-up.slack.com/archives/C035T90M2BY) |                                       |

| Squad                                | Custom Field Value                                    | Primary Channels                                                                                                       | Secondary / Purpose-specific                                                                                                                                                                                                                                                                                                                           |
| ------------------------------------ | ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- | ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- | --- |
|                                      | Chat                                                  | b914a475-a09c-476c-9a6b-9aa3da8047de                                                                                   | [](https://app.clickup-stg.com/333/chat/r/5-98020015389-8)                                                                                                                                                                                                                                                                                             |     | b914a475-a09c-476c-9a6b-9aa3da8047de | , [](https://app.clickup-stg.com/333/chat/r/5-98020015389-8),[](https://app.clickup-stg.com/333/chat/r/5-98020015389-8) |     |
| Calendar                             | 4ce1a74a-5363-4bc0-ad5b-76ccadaccc3c                  | [](https://app.clickup-stg.com/333/chat/r/6-980200202682-8),[](https://app.clickup-stg.com/333/chat/r/5-98020117552-8) | [](https://app.clickup-stg.com/333/chat/r/6-980200162494-8), [](https://app.clickup-stg.com/333/chat/r/ad-4157005), [https://click-up.slack.com/archives/C06HU32K20L](https://click-up.slack.com/archives/C06HU32K20L)                                                                                                                                 |
| Clips                                | 1a0efb06-6b9b-452c-8851-473a2f30e838                  | [](https://app.clickup-stg.com/333/chat/r/ad-952673)                                                                   | [https://click-up.slack.com/archives/C051HDDHEDT](https://click-up.slack.com/archives/C051HDDHEDT)                                                                                                                                                                                                                                                     |
|                                      |
| Access Management                    | 2597f33f-b8cd-4b8a-b413-85141c120df4                  | [](https://app.clickup-stg.com/333/chat/r/5-98020019713-8),[](https://app.clickup-stg.com/333/chat/r/6-980700097332-8) | [](https://app.clickup-stg.com/333/chat/r/6-980700083419-8), [](https://app.clickup-stg.com/333/chat/r/ad-2003949), [](https://app.clickup-stg.com/333/chat/r/6-980200071161-8), [](https://app.clickup-stg.com/333/chat/r/6-980700181787-8), [https://click-up.slack.com/archives/C03RP3PD9CL](https://click-up.slack.com/archives/C03RP3PD9CL) ,<br> |
| 2ac0429a-017f-4582-bf1b-e35471723b22 | [](https://app.clickup-stg.com/333/chat/r/ad-2428873) |                                                                                                                        |

# Agent Bug Goblin: Customer Email Mapping Path

# Agent Bug Goblin: Customer Email Mapping Path

Use this page as a **fast routing map** for customer emails. It combines **tone selection** plus **terms/keywords** so the agent can jump directly to the right playbook and minimize follow-up questions.

## Quick routing table (tone + keywords -> page + what to do)

| Customer signal (tone + intent)                                      | Terms / keywords to match                                                                                                  | Go to page(s)                                                                                                                                                                                                                                                                                                                                                                                        | What to extract / do (so you don’t need more context)                                                               | Special notes to reduce back-and-forth                                                                                                    |
| -------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Frustrated / angry / “this is unacceptable” / demands escalation** | “frustrated”, “angry”, “unacceptable”, “escalate”, “manager”, “cancel”, “I’ve asked before”, hostile tone, excessive caps  | Private ([https://app.clickup-stg.com/333/docs/ad-3125233/ad-5895029](https://app.clickup-stg.com/333/docs/ad-3125233/ad-5895029))                                                                                                                                                                                                                                                                   | Use LEAP (Listen, Empathize, Acknowledge, Provide solutions); determine escalation path (Bronze/Silver/Golden Hour) | Personalize even when using macros; set a clear next step plus timeline (what you’ll test, what you’ll ask for if it persists)            |
| **Neutral tone, but needs on-brand response quality**                | “quick question”, “can you help”, general support tone                                                                     | Private ([https://app.clickup-stg.com/333/docs/ad-614317/ad-2580661](https://app.clickup-stg.com/333/docs/ad-614317/ad-2580661))                                                                                                                                                                                                                                                                     | Apply greeting, structure, formatting rules (links, dates, bolding guidance), confident language                    | Avoid internal acronyms; keep paragraphs short; answer questions in order; use clean hyperlinks (no unfurled links)                       |
| **ClickUp-generated email delivery issues**                          | “email notification”, “didn’t receive”, “ClickUp email”, “digest”, “no email”, “bounce”, “unsubscribe”, “delivery”         | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533189](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533189))                                                                                                                                                                                                                                                                     | Identify the email type; gather evidence; confirm expected vs actual behavior                                       | Ask for timestamp, recipient address, subject line; confirm whether it impacts one user or many                                           |
| **Email-to-task / email into list problems**                         | “email to task”, “email into list”, “forwarded email”, “didn’t create task”, “created wrong task”, “inbound email address” | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5533213](https://app.clickup-stg.com/333/docs/ad-876561/ad-5533213))                                                                                                                                                                                                                                                                     | Determine target (list vs task); confirm inbound address used; request EML if needed                                | Ask for sending address, destination address, and whether it ever worked before                                                           |
| **Docs attachment issues**                                           | “attachment missing”, “can’t download”, “failed upload”, “permission”, “preview”, “file access”, “PAL”, “trash”            | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732673))                                                                                                                                                                                                                                                                     | Identify attachment type and permission state; follow troubleshooting and report path                               | Ask: file type/size, where attached (task/doc/comment), exact error, web vs mobile, and whether others can reproduce                      |
| **Docs notification issues**                                         | “not getting notified”, “mentions”, “watching”, “ClickBot”, “notification spam”, “bundled”, “channel”                      | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5732233](https://app.clickup-stg.com/333/docs/ad-876561/ad-5732233))                                                                                                                                                                                                                                                                     | Determine delivery channel (in-app/email/mobile) and scoping; validate expected notification behavior               | Ask: where they expected it (email vs in-app), which object, whether they are watching/following, and if it is consistent vs intermittent |
| **Hierarchy / structure / location issues**                          | “space”, “folder”, “list”, “location”, “missing list”, “moved”, “can’t find”, “wrong place”, “IDs”                         | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945](https://app.clickup-stg.com/333/docs/ad-876561/ad-5433945))                                                                                                                                                                                                                                                                     | Use location ID guidance; route to the correct report type                                                          | Always capture location ID(s) and the exact navigation path; confirm permission vs data vs UI                                             |
| **Access / permissions / user platform**                             | “permission denied”, “can’t access”, “invite”, “role”, “guest”, “owner”, “API”, “token”, “403”, “unauthorized”             | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633](https://app.clickup-stg.com/333/docs/ad-876561/ad-5478633))                                                                                                                                                                                                                                                                     | Identify the permission model involved; gather error and API context (if applicable)                                | Ask for role type, affected user(s), where it fails (web/mobile/API), and any error IDs/codes/screenshots                                 |
| **SSO/SCIM/SAML provisioning**                                       | “SSO”, “SAML”, “Okta”, “Azure”, “SCIM”, “login loop”, “provisioning”, “IdP”                                                | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829](https://app.clickup-stg.com/333/docs/ad-876561/ad-5879829))                                                                                                                                                                                                                                                                     | Follow SSO/SCIM troubleshooting; determine whether it’s auth vs provisioning vs configuration                       | Ask which IdP, exact error message, whether all users are affected, and last known good time                                              |
| **3rd-party integration not working**                                | “integration”, “sync”, “reconnect”, “token”, “auth”, integration app name (e.g., Slack, Google, Outlook, Zapier, GitHub)   | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664813)) and/or Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913](https://app.clickup-stg.com/333/docs/ad-876561/ad-5664913))                                                                                                                             | Identify integration type and failure mode; follow the right troubleshooting playbook                               | Ask: integration name, account scope, reconnect attempts, exact error, whether it changed after permissions/admin updates                 |
| **Project setup / ClickApps / settings**                             | “ClickApps”, “automation”, “status”, “custom field”, “views”, “settings”, “workflow”, “template”                           | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361](https://app.clickup-stg.com/333/docs/ad-876561/ad-5535361))                                                                                                                                                                                                                                                                     | Confirm intended workflow; provide exact steps using platform wording                                               | Ensure steps match UI labels; request a screenshot of the settings panel if needed                                                        |
| **Work analytics/reporting**                                         | “dashboard”, “report”, “workload”, “time tracking view”, “analytics”, “chart wrong”, “data mismatch”                       | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285](https://app.clickup-stg.com/333/docs/ad-876561/ad-5553285))                                                                                                                                                                                                                                                                     | Determine which report/view; follow evidence capture steps (HAR if relevant)                                        | Ask for report type, filters, time range, expected calculation, and screenshots of filter panels                                          |
| **Bug-quality write-up (any area)**                                  | “bug”, “defect”, “repro”, “steps”, “expected vs actual”, “screenshots”, “HAR”                                              | Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5534045](https://app.clickup-stg.com/333/docs/ad-876561/ad-5534045)); Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5514949](https://app.clickup-stg.com/333/docs/ad-876561/ad-5514949)); Private ([https://app.clickup-stg.com/333/docs/ad-876561/ad-5479025](https://app.clickup-stg.com/333/docs/ad-876561/ad-5479025)) | Convert the email into a clean internal summary; request only missing details                                       | Capture: environment (web/mobile), browser/app version, timestamps, minimal repro, and impact statement                                   |
| **Billing / CRM**                                                    | “invoice”, “charge”, “refund”, “billing”, “CRM”, “subscription”, “trial”, “seats”                                          | (No direct Compendium page in this mapping doc)                                                                                                                                                                                                                                                                                                                                                      | Route to internal escalation/SME guidance per the note in the main mapping                                          | Avoid deep troubleshooting here; clarify plan/workspace context and hand off appropriately                                                |

## Always-ask mini checklist (to reduce context gathering)

Use this checklist when you need more info. Ask only what’s missing.

- **Where**: workspace URL/name and the specific location (space/folder/list/task/doc) if applicable
- **Who**: affected user role (Owner/Admin/Member/Guest), and whether it impacts **one user or many**
- **What**: expected vs actual behavior, exact error text/code, screenshots (if available)
- **When**: timestamps and last known good time
- **Environment**: Web vs Mobile; browser name/version or mobile OS/app version
- **Repro**: minimal steps to reproduce, and whether it reproduces in a test workspace

## How to choose the right Compendium subpage once you land in a feature area

Within a squad/feature area, use these report types to avoid reinventing the approach:

- **Team Tips**: fastest known checks and common gotchas
- **Confirmed Repro Report**: you can reproduce; document cleanly
- **Unconfirmed Repro Report**: you cannot reproduce; request targeted evidence
- **Known Issue Report**: matches an existing issue; set expectations and share workarounds
- **SME Knowledge**: deeper context, logs/tools pointers, escalation nuances

# Bug Goblin: Bisect tool usage (with prefilled URLs)

## Goal

Help Bug Goblin guide TS reps through using the Frontend Bisect tool, including generating ready-to-use URLs when needed.

## Primary bisect SOP (recommended)

Use this page as the canonical “how to”:

- Private ([https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421](https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421))

## Quick overview (what bisect is)

The bisect tool helps you identify the specific PR (or commit) that introduced a frontend regression by testing a sequence of PR preview deployments and marking each step as **Good** (issue not reproducible) or **Bad** (issue reproducible).

## Inputs Bug Goblin should ask for

When a user asks for help bisecting, Bug Goblin should try to collect:

1. **Where to reproduce** (the path/route the rep needs to load)
2. **Backend environment** (qa, staging, etc.)
3. **Frontend app** (usually client)
4. **Good reference**: PR URL where the issue is _not_ reproducible (or a known good release ref)
5. **Bad reference**: PR URL where the issue _is_ reproducible (or a known bad release ref)

## Bisect tool entrypoints

- Main app: [Frontend Bisect](https://frontend-bisect.clickup-dev.com/)
- Configure screen: [Configure Bisect](https://frontend-bisect.clickup-dev.com/configure-bisect)
- Token screen (if required): [Set token](https://frontend-bisect.clickup-dev.com/set-token)

## Creating a prefilled Configure URL

Bug Goblin can provide a “prefilled” Configure URL when it already has the good and bad references plus environment/path.

### Example (real reference)

This page includes a concrete prefilled URL example Bug Goblin can pattern-match from:

- Private ([https://app.clickup-stg.com/333/docs/ad-1704165/ad-4098869](https://app.clickup-stg.com/333/docs/ad-1704165/ad-4098869))

### What to include in the URL

Bug Goblin can build a Configure URL that includes:

- `goodRef=` a known-good ref (often a release tag, e.g. `frontend@3.43.0`)
- `badRef=` usually `pull-request` when providing a PR URL
- `badPullRequest=` the GitHub PR URL for the known-bad PR (URL-encoded)
- `path=` the route to load (no base URL)
- `backend=` environment to run against (for example `qa`)
- `frontend=` app (for example `client`)

If only one side is known (only good or only bad), you can often use an environment option for the other side to widen/narrow the range (see “Bisect process” docs below).

## Troubleshooting and gotchas to mention

- If the bisect page is stuck or behaving oddly, token/local storage issues can be a factor (see Brent’s guide below).
- Refreshing the page may reset progress (some docs note this explicitly).

## Additional bisect documentation to link in Bug Goblin responses

These pages contain useful complementary details, screenshots, and troubleshooting:

- Private ([https://app.clickup-stg.com/333/docs/ad-880813/ad-3257701](https://app.clickup-stg.com/333/docs/ad-880813/ad-3257701)) (overview + clip)
- Private ([https://app.clickup-stg.com/333/docs/ad-628148/ad-3639813](https://app.clickup-stg.com/333/docs/ad-628148/ad-3639813)) (includes troubleshooting clip for loading issues)
- Private ([https://app.clickup-stg.com/333/docs/ad-1044101/ad-3377097](https://app.clickup-stg.com/333/docs/ad-1044101/ad-3377097)) (detailed step options, notes)
- Private ([https://app.clickup-stg.com/333/docs/ad-823457/ad-3274269](https://app.clickup-stg.com/333/docs/ad-823457/ad-3274269)) (similar content plus additional clip reference)
- Private ([https://app.clickup-stg.com/333/docs/ad-3271893/ad-7297593](https://app.clickup-stg.com/333/docs/ad-3271893/ad-7297593)) (TIM Lite process framing)

## Suggested Bug Goblin response template (copy/paste)

1. Confirm repro path and env (qa/staging/etc.).
2. Ask for a **Good PR** URL and a **Bad PR** URL (or last-good release and first-bad release).
3. Send the SOP link: Private ([https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421](https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421)).
4. Provide the bisect entry link: [Configure Bisect](https://frontend-bisect.clickup-dev.com/configure-bisect).
5. If enough info is available, include a prefilled Configure URL (pattern from: Private ([https://app.clickup-stg.com/333/docs/ad-1704165/ad-4098869](https://app.clickup-stg.com/333/docs/ad-1704165/ad-4098869))).

# Regression Mapping & GitHub MCP Index

# Regression Mapping & GitHub MCP Index

## Purpose

This section teaches ClickUp agents (like Bug Goblin) how to:

- Recognize **regression candidates** from arbitrary user and TIM language.
- Map requests to the right **frontend surface(s)** and **backend component(s)**.
- Use those mappings to scope **GitHub MCP** searches (repos, PRs, releases).
- Prepare **Bisect Tool** inputs for deeper regression confirmation.

This mapping is designed to be **dynamic and pattern-based**, not hardcoded to a single error or feature. Each entry acts as a reusable rule that can fire for many different reports.

---

## Page tree for regression mapping

1. **Frontend Regression Surfaces**

Mapping from user-visible surfaces (e.g., Task view, List view, Docs, Dashboards, Notifications, Permissions UI, Automations) to squads and GitHub hints.

2. **Backend Services & Error Codes**

Mapping from backend components (services, endpoints, error codes) to squads, repos, and regression behavior.

3. **Regression Heuristics & Routing Rules**

Global rules for recognizing regressions and combining frontend + backend mappings.

4. **Examples & Test Cases**

Concrete examples that show end-to-end behavior for common regression patterns.

---

## How agents should use this section

When a regression-related request comes in (TIM task, bug report, Zendesk ticket, DM):

1. **Normalize a regression fingerprint**

Extract from the request:

- Surface nouns: where in the product? (e.g., "Task view", "List view", "Docs", "Notifications", "Permissions", "Automations").
- Error codes / text: HTTP codes, ACCESS_0xx, API codes, on-screen messages.
- Timeline: "used to", "after the last update", "since version X", etc.
- Platform & env: web / desktop / mobile; prod vs QA; workspace ID (when available).

2. **Match frontend surface(s)**

Use **Frontend Regression Surfaces** to:

- Find one or more matching surfaces by name, user phrases, or UI hints.
- Pull each surface’s **Squad / Area** and **GitHub Component / Repo Hints**.

3. **Match backend component(s)**

Use **Backend Services & Error Codes** to:

- Match error codes and backend language (service names, endpoint paths) to components.
- Pull each component’s **GitHub repos** and any special **regression search hints**.

4. **Merge mappings into a scoped GitHub search plan**
   - Combine all matched surfaces and services into a small set of **repos and components** to investigate.
   - Build GitHub MCP queries using:
     - Error codes and key nouns from the fingerprint.
     - Time window from the regression timeline.
     - The repos/services provided by the mappings.
5. **Drive regression workflows**
   - For Regressions list tasks or regression-flagged TIMs:
     - Use these mappings to select likely **good** and **bad** PRs/releases.
     - Prepare a **Bisect Tool** configuration (good PR, bad PR, route) for humans.
   - Post structured findings back to the task, including:
     - Mapped surfaces and services (by name, not implementation detail).
     - Candidate PR(s)/release(s) with confidence and rationale.
     - Any recommended next steps (Bisect, Datadog, repro checks).

---

## Seeding status and remaining areas

This page tracks which product areas have seeded regression mappings, and which are still to-do.

### Seeded now (frontend + backend mappings and examples will exist on subpages)

- [x] Permissions / Access Management (ACCESS_0xx, Teams, sharing)
- [x] List View (task visibility, filters, grouping)
- [x] Docs (doc editor, doc availability)
- [x] Notifications (in-app + email notifications, Inbox)
- [x] Automations (automations engine, triggers/actions firing)

### Remaining areas to seed next (from current Super Agent Mapping + Compendium squads)

These areas should each get at least one frontend surface and, where applicable, backend component entry over time.

- [x] Hierarchy (spaces, folders, lists, task hierarchy beyond List view) d frontend + backend seeded; examples started d frontend + backend seeded; examples started
- [x] Project Management (settings, ClickApps, time tracking views) d frontend + backend seeded; examples started d frontend + backend seeded; examples started
- [x] Integrations (3rd party integrations: GitHub, Slack, Google, etc.) d frontend + backend seeded; examples started d frontend + backend seeded; examples started
- [ ] Integration Services (import/export, sync engines)
- [ ] Core Services (SSO/SCIM, auth foundations)
- [ ] Core Services (SSO/SCIM, auth foundations)
- [x] Task Squad surfaces beyond Task View 3.0 (e.g., Quick Create, bulk actions) d frontend + backend seeded; examples started d frontend + backend seeded; examples started
- [ ] Work Analytics (dashboards, reports, analytics widgets)
- [ ] CRM & Billing (billing portal, CRM features)
- [ ] AI (ClickUp AI experiences)
- [x] Search / Platform (global search, filters, Command Center) d frontend + backend seeded; examples started d frontend + backend seeded; examples started
- [ ] Email from ClickUp / Email into List/Task (email send + ingest)
- [ ] Docs / Attachments edge surfaces not covered by the main Docs editor row

As we seed additional areas, update these checkboxes and add the corresponding rows to the **Frontend Regression Surfaces** and **Backend Services & Error Codes** subpages.

# Backend Services & Error Codes

# Backend Services & Error Codes

## Purpose

Map backend components (services, endpoints, error codes) to:

- Squad / area
- Typical regression signatures
- GitHub repos
- How to bias GitHub MCP searches and Bisect Tool inputs

---

## Backend mapping table (seeded areas)

| Service / Component                     | Identifier(s)                                                                                       | Squad / Area                           | Typical Regression Signatures                                                                                                                                                                                                                                                      | Error Codes / Messages                                                                                                                                                                                                               | GitHub Repo(s) / Component Hints                                                                                                                                                                                   | Regression / Bisect Hints                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Access / Permissions Service            | `access-service`, `permissions-service` (conceptual identifiers)                                    | Access Management Squad                | Permission resolution flips behavior; users lose access or get ACCESS_0xx after role/team changes; permission outcome changes after deploy or after team membership updates.                                                                                                       | `ACCESS_081`, other ACCESS_0xx messages; generic "You don’t have permission" errors when user should have edit rights.                                                                                                               | Back-end service(s) responsible for permission checks and access resolution; any repos with `access`, `permissions`, `sharing` in name or path.                                                                    | When fingerprint includes ACCESS_0xx + permissions/team/list/sharing language, restrict GitHub MCP search to these repos and include `"ACCESS_0"` + `permissions` + `team` + `list`/`sharing` in PR search queries within the suspected regression window.                                                                                                                                                        |
| List View Data Service                  | `list-view-service`, list query layer                                                               | Hierarchy / List View Squad            | Tasks disappearing from list, list views blank or erroring, filters suddenly hiding items that used to show, infinite loading in list view after release.                                                                                                                          | HTTP 4xx/5xx from list-related endpoints; errors shown in UI like "We ran into trouble loading your view".                                                                                                                           | Backend services that power list queries and aggregation; any repos with `list-view`, `task-query`, or similar naming.                                                                                             | For list-visibility regressions, scope GitHub MCP searches to these repos and include list-related endpoint names and error text; correlate with front-end List View surface mappings to choose candidate good/bad releases.                                                                                                                                                                                      |
| Docs Service                            | `docs-service`, document storage/editor API                                                         | Docs Squad                             | Docs editing disabled, documents stuck in read-only, failures saving content after a deploy, editor and document content going out of sync.                                                                                                                                        | Document-specific error strings, editor save failures, 5xx from docs endpoints.                                                                                                                                                      | Backend `docs` / `documents` service; any repos that handle doc persistence or collaboration.                                                                                                                      | For doc-editing regressions, prefer these repos and include doc-related endpoints and error fragments in PR search; cross-check against versions where docs editing was known-good.                                                                                                                                                                                                                               |
| Notifications / Delivery Service        | `notifications-service`, `notification-delivery`, email worker(s)                                   | Notifications Squad                    | Notifications (in-app or email) suddenly stop, only certain channels fail, or timing changes sharply after a deploy; Inbox stops reflecting new events.                                                                                                                            | Email delivery errors, notification queue errors, delivery provider error messages.                                                                                                                                                  | Backend services that enqueue and deliver notifications; any repos with `notification`, `inbox`, `alerts` or related naming.                                                                                       | For notification regressions, scope PR and release searches to these repos and include notification and delivery keywords; match with frontend Notifications surface to establish a good/bad release window.                                                                                                                                                                                                      |
| Automations Engine                      | `automations-service`, `rules-engine`, job runners                                                  | Automations Squad                      | Automations that were firing reliably stop running, or only certain triggers/actions fail after a release; automation runs disappear or fail silently.                                                                                                                             | Automation-specific log/error strings, 5xx from automations endpoints, worker failures.                                                                                                                                              | Backend automations/rules engine repos and job runners; any services with `automation`, `rules`, `workflow` names.                                                                                                 | When automations regressions are suspected, restrict GitHub MCP search to these repos and use trigger/action-specific keywords from the task in PR queries; align with release windows of the Automations Builder frontend.                                                                                                                                                                                       |
| Hierarchy Metadata Service              | `hierarchy-service`, `spaces-service`, `folders-service` (conceptual identifiers)                   | Hierarchy / Spaces & Folders Squad     | Spaces/folders/lists vanish from the sidebar or appear under the wrong parent after a deploy; archive/restore works inconsistently between users; hierarchy in Everything/Sidebar disagrees with reality even when filters look fine.                                              | HTTP 4xx/5xx from spaces/folders/lists/hierarchy endpoints; generic "We ran into some trouble loading your view" errors when loading the sidebar or Everything tree; internal errors mentioning `hierarchy`, `spaces`, or `folders`. | Backend services that own spaces/folders/lists metadata and the hierarchy tree API; repos/components with `hierarchy`, `spaces`, `folders`, or `tree` in their names or paths.                                     | When the fingerprint emphasizes structure/placement of spaces/folders/lists (disappearing, moving under wrong parents, hierarchy mismatch) without strong filter language, treat as a Hierarchy candidate: scope GitHub MCP searches to these repos, include endpoint names and hierarchy terms in queries, and compare PRs/releases around the last "hierarchy looked correct" vs "hierarchy broken" timestamps. |
| Project Configuration Service           | `project-config-service`, `clickapps-service`, `workflow-settings-service` (conceptual identifiers) | Project Management Squad               | Global or per-Space settings silently revert after a deploy; ClickApps toggles ignore changes; default statuses, custom fields, or time-tracking options appear/disappear across many Spaces at once.                                                                              | 4xx/5xx on settings/ClickApps endpoints; validation errors when saving unchanged settings; internal errors mentioning `clickapps`, `project-config`, `workflow-settings`.                                                            | Backend services that own Space/Folder/List settings, ClickApps configuration, and project-level workflow metadata; repos/components with `settings`, `clickapps`, `workflow`, or `project-config` in their names. | When many Spaces suddenly share the same broken configuration (statuses vanished, ClickApp disabled everywhere, time tracking views gone), treat as a Project Management config regression: focus GitHub MCP searches on these services and settings endpoints, then compare PRs that touched configuration schemas or feature toggles in the regression window.                                                  |
| Integrations / OAuth Connectors Service | `integrations-hub`, `oauth-service`, `third-party-connectors` (conceptual identifiers)              | Integrations Squad                     | New or existing Slack/GitHub/Google/etc. connections fail to create or silently disconnect across many workspaces shortly after a release; OAuth flows stall on callback; integrations section reports "not authorized" even when users just reconnected.                          | Provider-specific OAuth errors, HTTP 4xx/5xx on integrations/oauth callback and connection endpoints; internal errors mentioning `oauth`, `integrations-hub`, `connector`.                                                           | Backend services that own third-party app connections and OAuth token storage/refresh; repos/components with `integrations`, `oauth`, `connectors`, or specific provider names (Slack, GitHub, Google, etc.).      | When the fingerprint is about connecting or staying connected to external tools (as opposed to syncing/importing data), treat as an Integrations connectors regression: scope GitHub MCP to these services, include provider + `oauth` terms in queries, and compare PRs touching OAuth flows or token lifecycle in the regression window.                                                                        |
| Integration Sync & Import Service       | `integration-sync-service`, `import-service`, `webhook-sync-engine` (conceptual identifiers)        | Integration Services Squad             | Data that used to sync between ClickUp and external tools (GitHub, Slack, calendar, CRM, etc.) silently stops moving after a release; imports hang or fail across many workspaces; sync jobs appear stuck or replay the same items repeatedly while connections remain authorized. | HTTP 4xx/5xx on integrations/sync/import endpoints; job/worker errors mentioning `integration-sync`, `import`, `webhook`, or provider-specific sync failures; timeouts or queue backlog warnings.                                    | Backend services that own ongoing sync/import pipelines and webhook processing; repos/components with `integration-sync`, `importer`, `sync-engine`, or provider-specific sync names.                              | When the fingerprint is about data not moving (or moving incorrectly) between ClickUp and other systems while integrations still show as connected, treat as an Integration Services regression: scope GitHub MCP to these services and sync/import endpoints, and compare PRs that changed job scheduling, backoff/retry, or mapping logic in the regression window.                                             |
| Auth & Identity Service                 | `auth-service`, `identity-service`, `sso-gateway`, `scim-service` (conceptual identifiers)          | Core Services / Auth Foundations Squad | Users across multiple workspaces suddenly can’t log in or complete SSO after a release; login redirects loop; tokens expire too quickly or sessions are rejected even after successful IdP auth; SCIM provision/deprovision behavior shifts in lockstep with a deploy.             | 401/403 responses on login/auth/SSO endpoints; SAML/OIDC error messages; internal logs mentioning `auth`, `identity`, `sso`, or `scim`; generic "Something went wrong" login errors when nothing changed in the IdP.                 | Backend services responsible for authentication, identity, SSO, and SCIM; repos/components with `auth`, `identity`, `sso`, `login`, or `scim` in their names.                                                      | When multiple customers suddenly report SSO/login issues (or SCIM flakiness) aligned with a ClickUp release, treat as a Core Services regression: narrow GitHub MCP to auth/identity/SSO/SCIM services and login-related frontend modules, and look for PRs that updated token validation, callback handling, or session lifecycle in the last few releases as Bisect Tool candidates.                            |

Task Creation Workflow Service
`task-create-service`, `task-command-handler` (conceptual identifiers)
Task Squad
Quick create or create-from-anywhere flows intermittently fail; tasks aren’t created even though the modal appears to save; users see errors only when using quick create but not when creating from full Task view.
4xx/5xx on task-creation endpoints; validation or generic errors returned from task create APIs; logs mentioning `task-create`, `task-command`, or similar.
Backend services that own task creation commands and validation; repos/components with `task-create`, `task-command`, or similar naming.
When regressions are limited to **creation** (especially via quick create or command-center create) and not editing existing tasks, bias GitHub MCP searches toward these services and endpoints; compare PRs that touched creation flows or validation logic in the regression window.
Bulk Operations Service
`bulk-actions-service`, `mass-update-service` (conceptual identifiers)
Task Squad
Bulk close/move/assign operations partially apply or silently no-op after a release; some selected tasks update, others don’t, or the bulk bar doesn’t trigger server-side changes.
4xx/5xx on bulk update/move endpoints; errors mentioning `bulk`, `mass-update`, `batch`; internal logs showing partial failure on bulk operations.
Backend services that own bulk task update/move/close operations; repos/components with `bulk`, `mass-update`, `batch`, or `bulk-actions` in their names.
For regressions where **single-task edits still work but bulk operations fail or partially succeed**, treat as a Bulk Operations candidate: scope GitHub MCP searches to these services and bulk endpoints, and look for PRs around the time bulk started misbehaving.
Search Indexing / Query Service
`search-service`, `search-indexer`, `search-api` (conceptual identifiers)
Search / Platform Squad
Newly created or recently edited tasks/docs don’t appear in global search or Command Center for a long time after changes; some entities never show up in search even though users can navigate to them directly.
4xx/5xx on search endpoints; internal errors mentioning `search`, `index`, `query`; timeouts or partial-results warnings.
Backend services responsible for indexing and serving search results; repos/components with `search`, `indexer`, or `query-service` in their names.
When regressions are about **results missing or stale** in global search/Command Center, bias GitHub MCP searches toward these services; use the date the results were last known-good vs first-bad as the regression window and look for PRs touching indexing or query logic.
Platform Filters / Query Normalization Service
`platform-query-service`, `filters-service`, `query-normalizer` (conceptual identifiers)
Search / Platform Squad
Filters that used to include/exclude the right items suddenly behave differently across views (List vs Board vs Command Center); saved filters produce inconsistent results or ignore some tokens (e.g., closed/open, assignees, tags).
4xx/5xx on filter/query endpoints; internal logs referencing `filters`, `query-normalizer`, `tokenizer`; errors when loading saved views with complex filters.
Shared backend layer that parses and normalizes filters/queries across multiple views; repos/components with `filters`, `query`, or `platform-query` naming.
When the fingerprint focuses on **filter semantics** (e.g., closed tasks unexpectedly excluded across multiple views) rather than pure missing search results, treat as a Filters Engine regression: scope GitHub MCP searches to these services and saved-view/query handling, and compare PRs that changed filter parsing or query generation.

---

## How agents should use this page

1. From the regression fingerprint, extract:
   - Named services (if the report or logs mention them).
   - Endpoint paths or HTTP errors.
   - Error codes and messages.
2. Match against **Identifier(s)** and **Error Codes / Messages**.
3. Use **GitHub Repo(s) / Component Hints** and **Regression / Bisect Hints** to:
   - Narrow GitHub MCP searches to relevant components.
   - Decide how to phrase search queries (tokens, filters, repo scopes, date ranges).
4. Combine these backend hints with frontend surface mappings to choose:
   - A small set of candidate repos.
   - Good/bad releases and PRs for Bisect Tool inputs.

Over time, add more rows so that every major backend component that appears in the Super Agent Mapping / Compendium also appears here with regression-aware guidance.

### How backend mappings interact with a frontend-only Bisect Tool

The Bisect Tool currently runs only against frontend code (for example, `clickup_frontend`). Use this page to **guide and constrain** Bisect-related work, but do not add backend repos directly to the Bisect configuration.
This does **not** mean backend repos should be ignored during general regression analysis. When someone asks to "check for any regression" or when you are doing non-Bisect regression investigation, you should still use these backend mappings to scope GitHub MCP searches across the relevant backend services and repos as well as the frontend. The frontend-only constraint applies specifically to which repo you pass into the Bisect Tool, not to which repos you examine when looking for regressions overall.
When a backend component is mapped:

- Use its **Identifier(s)**, **Typical Regression Signatures**, and **Error Codes / Messages** to refine:
  -       *   Which `clickup_frontend` PRs/releases to inspect (based on features and flows that surface the backend behavior).

    - The regression time window (based on when backend symptoms first appeared).
  - Treat backend repos as **evidence and context** for the human engineer, not as Bisect targets.

If a regression is clearly backend- or infra-only with no meaningful `clickup_frontend` surface to exercise, prioritize:

-       *   GitHub MCP searches scoped to the relevant backend services.

  - Log/metrics investigation.
  - Manually prepared reproduction steps, rather than forcing a Bisect run.

# Frontend Regression Surfaces

# Frontend Regression Surfaces

## Purpose

Map user-visible surfaces (views, screens, flows) to:

- Squad / feature area
- Related Compendium docs
- Common user phrases
- GitHub repos/components to prioritize

Agents use this page to turn arbitrary user descriptions into a normalized **surface ID** and a small set of GitHub targets.

---

## Surface mapping table (seeded areas)

| Surface Name                             | Canonical ID                    | Squad / Area                                                                                                                          | Compendium Link                                                                          | Common User Phrases                                                                                                                                                            | Related Features / Flows                                                                                                                        | GitHub Component / Repo Hints                                                                                                                                     |
| ---------------------------------------- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Task View 3.0                            | `task_view_3`                   | Task Squad                                                                                                                            |                                                                                          | "can’t open task", "task pane not loading", "task details panel missing", "click does nothing"                                                                                 | List view → Task view, My Work → Task view, notifications → task                                                                                | Web client task-view code paths; any `task-view` or `task-pane` modules in the main frontend repo.                                                                |
| List View                                | `list_view`                     | Hierarchy / List View Squad                                                                                                           |                                                                                          | "can’t see tasks in list", "list won’t load", "no matching results", "list view blank"                                                                                         | Filters, group by, subtask display, closed-task visibility                                                                                      | Web client list-view module(s); list-query/reactive data layer; any dedicated `list-view` frontend package.                                                       |
| Permissions UI / Sharing Dialog          | `permissions_ui`                | Access Management Squad                                                                                                               |                                                                                          | "ACCESS_081", "lost access", "can’t share list", "team permissions wrong", "user can only comment now"                                                                         | List/Folder/Space sharing, Teams, Guests, roles                                                                                                 | Web client permissions/sharing dialog components; any `permissions`, `sharing`, or `access` UI modules.                                                           |
| Notifications / Inbox                    | `notifications_inbox`           | Notifications Squad                                                                                                                   |                                                                                          | "stopped getting notifications", "inbox empty", "no bell icon alerts", "notifications delayed"                                                                                 | In-app notifications, Inbox, email notification surface, @mentions → Inbox                                                                      | Web client notifications center, bell/inbox UI; any `notifications`, `inbox`, or `activity-feed` frontend modules.                                                |
| Automations Builder / Triggers & Actions | `automations_builder`           | Automations Squad                                                                                                                     |                                                                                          | "automation stopped running", "rules no longer fire", "automation card missing"                                                                                                | Automations builder UI, rule lists, trigger/action config, logs surface                                                                         | Web client automations builder modules; any `automations`, `rules-engine`, or `workflow` frontend components.                                                     |
| Hierarchy Sidebar & Settings             | `hierarchy_sidebar_settings`    | Hierarchy / Spaces & Folders Squad                                                                                                    |                                                                                          | "sidebar not loading", "space/folder/list disappeared from sidebar", "can’t expand space", "moved list but hierarchy looks wrong", "Everything view hierarchy doesn’t match"   | Sidebar 3.0 navigation, Space/Folder/List create/move/archive/restore, expand/collapse behavior in Everything and Sidebar, hierarchy reordering | Web client hierarchy/sidebar/nav-tree modules; any frontend packages with `sidebar`, `hierarchy`, `spaces-panel`, or similar naming.                              |
| Project Management Settings & ClickApps  | `project_mgmt_settings`         | Project Management Squad                                                                                                              |                                                                                          | "can’t enable ClickApp", "statuses disappeared", "lost my custom fields", "time tracking options missing", "project settings page blank"                                       | Space/Folder/List settings pages, ClickApps configuration, default statuses & workflows, time tracking configuration surfaces                   | Frontend settings and ClickApps modules; any components/packages named `settings`, `clickapps`, `workflow-settings`, `time-tracking-views`, or similar.           |
| Integrations Settings & Connections      | `integrations_settings`         | Integrations Squad                                                                                                                    |                                                                                          | "can’t connect Slack", "GitHub integration page blank", "Authorize button does nothing", "integration disconnects after refresh", "integration settings missing"               | Workspace Integrations page, per-Space/Folder/List integration settings, OAuth connect/reconnect flows, app directory listings                  | Frontend integrations settings and app-connection modules; components with `integrations-settings`, `oauth-connections`, `app-directory`, or similar naming.      |
| Integration Sync & Import Views          | `integration_sync_import_views` | Integration Services Squad                                                                                                            |                                                                                          | "GitHub tasks stopped syncing", "Slack messages no longer appear in ClickUp", "import stuck at 0%", "sync spinner never finishes", "no new records coming in from integration" | Import wizards, one-time imports, recurring sync views, integration sync status/log UIs                                                         | Frontend modules that show sync/import progress, logs, or mapping configuration; components with `integration-sync`, `imports`, `sync-status`, or similar naming. |
| Login & SSO Flows                        | `login_sso_flows`               |
| Quick Create Task Modal                  | `quick_create_task_modal`       | Task Squad                                                                                                                            |                                                                                          | "quick create not opening", "can’t create task from + button", "quick create modal blank", "quick create stuck loading"                                                        | Header + button quick-create, keyboard shortcuts that open quick create, Command Center "create task" flows                                     | Web client quick-create modal and task-creation UX modules; components/packages with `quick-create`, `task-create-modal`, or similar naming.                      |
| Bulk Actions Toolbar                     | `bulk_action_toolbar`           | Task Squad                                                                                                                            |                                                                                          | "can’t select multiple tasks", "bulk close does nothing", "bulk assign fails", "bulk toolbar not showing"                                                                      | List view multi-select and bulk edit, status/assignee changes from the bulk bar, mass move/close/delete flows                                   | Frontend bulk-selection + bulk-action components; any `bulk-actions`, `multi-select`, or `bat-toolbar` modules tied to Task Squad.                                |
| Global Search & Command Center           | `global_search_command_center`  | Search / Platform Squad                                                                                                               |                                                                                          | "search not finding tasks", "docs not showing in search", "command center search empty", "recent tasks missing from search"                                                    | Top nav search bar, Command Center search, quick search overlays, global search results for tasks/docs/comments                                 | Frontend search and Command Center modules; components with `global-search`, `command-center`, `spotlight`, or similar naming.                                    |
| Cross-View Filters Engine                | `platform_filters_engine`       | Search / Platform Squad                                                                                                               |                                                                                          | "filters ignoring closed tasks setting", "saved view filter behaves differently in different views", "command center filter tokens wrong"                                      | Filters and query-building used across List/Board/Calendar/Command Center, global filter chips, saved view filter definitions                   | Shared filter/query engine components; any frontend packages named `filters-engine`, `query-builder`, or `platform-filters`.                                      |
| Core Services / Auth Foundations Squad   |                                 | "can’t log in", "SSO button does nothing", "redirect loop on login", "SSO used to work and now fails", "stuck on generic login error" | Workspace login page, SSO provider redirect/return flows, SSO/SCIM settings entry points | Frontend login/auth modules including SSO buttons and redirect handlers; components with `login`, `auth`, `sso`, or `signin` in their names.                                   |

---

## How agents should use this page

Given a regression fingerprint:

1. Match key phrases in the user’s description to **Surface Name** and **Common User Phrases**.
2. Use the **Canonical ID** + **Squad / Area** to:
   - Anchor Compendium lookups.
   - Influence GitHub MCP search scopes.
3. Use **GitHub Component / Repo Hints** as the **primary repo set** when constructing GitHub MCP queries and when deciding which releases/PRs to treat as candidates for Bisect Tool inputs.

Over time, add more rows so that every significant surface from the Super Agent Mapping and Compendium has a corresponding regression surface entry.

### Bisect-specific usage (clickup_frontend)

When preparing Bisect Tool runs:

- Treat `clickup_frontend` as the **default repo** for all frontend regression surfaces on this page.
- For each mapped surface, use its **Common User Phrases** and **GitHub Component / Repo Hints** to choose `clickup_frontend` PRs that most likely touch the affected modules (for example, Task view, quick create modal, bulk actions toolbar, global search, filters engine).
  Do not add non-frontend repos to the Bisect configuration. Instead, use backend mappings only to:
-       *   Refine which `clickup_frontend` PRs/releases you investigate.

  - Adjust the regression time window and search keywords.
- If there is no obvious frontend surface for a regression (purely backend/infra), log it as a regression candidate but prioritize GitHub MCP search + human review over a forced Bisect run.

# Examples & Test Cases

# Examples & Test Cases

## Purpose

Provide concrete, end-to-end examples that show how agents should apply:

- Frontend Regression Surfaces
- Backend Services & Error Codes
- Regression Heuristics & Routing Rules

Each example is written so it can be adapted into tests or prompt snippets.

---

### Example 1 – ACCESS_081 permissions regression candidate

- **Source:** TIM regression flag task.
- **User snippet:** "After being added to another Team, I can no longer edit checklist items and see ACCESS_081 errors."
- **Fingerprint:**
  - Surface nouns: `Permissions UI`, `Tasks`, `Checklist items`.
  - Error: `ACCESS_081`.
  - Timeline: "After being added to another Team".
- **Frontend mapping:**
  - Match to `Permissions UI / Sharing Dialog` (`permissions_ui`) in Frontend Regression Surfaces.
  - Squad: Access Management.
  - GitHub hints: permissions/share dialogs in the main web client.
- **Backend mapping:**
  - Match `ACCESS_081` to **Access / Permissions Service** in Backend Services & Error Codes.
  - GitHub hints: access/permissions backend repos.
- **GitHub MCP plan:**
  - Search PRs in combined access/permissions repos with tokens: `"ACCESS_081"`, `permissions`, `team`, `list` inside the suspected regression window.
- **Bisect prep:**
  - Once likely good/bad releases are known, surface candidate good/bad PRs + route, ready for the Bisect Tool.

---

### Example 2 – List view tasks disappear after release

- **Source:** Support ticket escalated to TIM.
- **User snippet:** "Since last week’s update, several tasks no longer appear in our main List view, even though filters are unchanged."
- **Fingerprint:**
  - Surface nouns: `List view`, `tasks not visible`.
  - Timeline: "since last week’s update".
- **Frontend mapping:**
  - Match to `List View` (`list_view`) in Frontend Regression Surfaces.
  - Squad: Hierarchy / List View.
- **Backend mapping:**
  - Match to **List View Data Service** in Backend Services & Error Codes based on symptoms (list queries missing tasks).
- **GitHub MCP plan:**
  - Restrict searches to list-view/frontend + list-query/backend repos.
  - Use tokens like `"list view"`, `filter`, `visibility`, endpoint names, and a date window around the last-known-good → first-bad timeframe.
- **Bisect prep:**
  - Identify good/bad PRs spanning the change in behavior and output a prep block for the Bisect Tool.

---

### Example 3 – Docs editing regression

- **Source:** Bug report from multiple workspaces.
- **User snippet:** "We used to edit docs fine, but after the latest release the editor frequently says it can’t save and content is lost."
- **Fingerprint:**
  - Surface nouns: `Docs editor`, `editing`, `save`.
  - Timeline: "after the latest release".
- **Frontend mapping:**
  - Match to `Docs Editor` (`docs_editor`) in Frontend Regression Surfaces.
  - Squad: Docs.
- **Backend mapping:**
  - Match to **Docs Service** in Backend Services & Error Codes.
- **GitHub MCP plan:**
  - Scope to docs frontend + docs-service repos.
  - Use tokens like `"doc"`, `"editor"`, `"save"`, endpoint names, and the release window.
- **Bisect prep:**
  - Provide candidate good/bad PRs affecting docs editor or persistence.

---

### Example 4 – Notifications stop after deploy

- **Source:** Incident across multiple customers.
- **User snippet:** "Notifications stopped entirely in-app and via email starting Friday’s deploy."
- **Fingerprint:**
  - Surface nouns: `Notifications`, `Inbox`, `email`.
  - Timeline: "starting Friday’s deploy".
- **Frontend mapping:**
  - Match to `Notifications / Inbox` (`notifications_inbox`).
  - Squad: Notifications.
- **Backend mapping:**
  - Match to **Notifications / Delivery Service**.
- **GitHub MCP plan:**
  - Constrain to notifications frontend + notification-delivery backend repos.
  - Search PRs around the Friday deploy with `notification`, `inbox`, `email`, and any specific error strings.
- **Bisect prep:**
  - Choose candidate PRs affecting notification sending; output them as Bisect Tool candidates.

---

### Example 5 – Automations stop firing

- **Source:** Regression flagged by TIM.
- **User snippet:** "Several automations that used to run on status change no longer trigger after the most recent release; no errors are shown."
- **Fingerprint:**
  - Surface nouns: `Automations builder`, `status change trigger`.
  - Timeline: "after the most recent release".
- **Frontend mapping:**
  - Match to `Automations Builder / Triggers & Actions` (`automations_builder`).
  - Squad: Automations.
- **Backend mapping:**
  - Match to **Automations Engine**.
- **GitHub MCP plan:**
  - Focus on automations builder UI + rules/automations backend repos.
  - Use tokens like `automation`, `trigger`, `status change`, with the regression window.
- **Bisect prep:**
  - Select good/bad PRs that touched automations trigger handling to feed into the Bisect Tool.

---

Over time, add more examples covering the remaining squads/areas listed in the main **Regression Mapping & GitHub MCP Index** page so that every area has at least one concrete test case.

# Regression Heuristics & Routing Rules

# Regression Heuristics & Routing Rules

## Purpose

Define global rules for when to treat something as a regression and how to merge frontend + backend mappings into a single routing and GitHub search plan.

---

## Regression detection heuristics

Treat a report as a **regression candidate** when:

- Language includes markers like: "used to", "after the last update", "since \[date/version\]", "broke after deploy", "was working before"; **and**
- The described behavior contradicts what the product previously allowed or what the Compendium describes as intended behavior.

If the report is tagged or categorized as a regression in TIM workflows (for example, **Request Type = Possible Regression Flag 🚨** or the task lives in a dedicated Regressions list), treat that as a strong regression signal even when language is less explicit.

---

## Routing rules

### 1\. Front-of-house routing (Category / Squad / Surface)

- Use the **ClickUp Super Agent Mapping Document** plus **Frontend Regression Surfaces** to assign:
  - Category
  - Squad / Area
  - One or more **Canonical Surface IDs** (e.g., `task_view_3`, `list_view`, `permissions_ui`, `notifications_inbox`, `automations_builder`).
- When multiple surfaces are implicated (for example, List view → Task view), keep all of them in the fingerprint.

### 2\. Back-of-house routing (Services / Repos)

### 3.5 Frontend-first strategy for Bisect (clickup_frontend)

For now, the Bisect Tool only supports running against **frontend code**. Treat `clickup_frontend` as the **primary repo** for Bisect runs, even when backend services are implicated.
When preparing Bisect-related regression work:

- Always anchor Bisect candidates in **`clickup_frontend`** **PRs/releases**.
- Use **Frontend Regression Surfaces** as the main driver for which parts of `clickup_frontend` to pay attention to (Task View, List View, Permissions UI, Notifications, Automations, Task Squad extras, Search/Platform, etc.).
- Use **Backend Services & Error Codes** as **context only** for Bisect: they help choose keywords, time windows, and impacted flows, but the actual good/bad PRs must live in `clickup_frontend`.
  Practical rules:
  These frontend-only rules apply **only when you are preparing Bisect Tool runs**. For general regression checks (for example, when a user asks you to "check for any regression" without mentioning Bisect), you should still consider both frontend and backend repos and services when using GitHub MCP search. The constraint to `clickup_frontend` is specific to the Bisect Tool configuration, not to overall regression analysis.
  If a regression clearly has a user-facing surface (e.g., List view, Task quick create, Bulk actions, Global search, Filters):
-       *   Prioritize `clickup_frontend` PRs that touch modules/components aligned with that surface’s hints.
      *   Use backend mappings to refine the search (e.g., error codes, endpoints) but do not add non‑frontend repos to the Bisect configuration.
  If a regression appears mostly backend-driven (e.g., pure data sync issues, backend-only errors with little/no visible UI change):
-       *   You may still use backend mappings + logs to find candidate root causes.
      *   Only run Bisect when you can point to a **specific frontend surface** that changed behavior and can be exercised by a route/flow in `clickup_frontend`.
      *   Otherwise, lean on GitHub MCP search + human investigation instead of forcing a Bisect run.
  This keeps Bisect runs tightly focused on `clickup_frontend`, while still allowing backend mappings to guide how we search and interpret candidate PRs.
- Use **Backend Services & Error Codes** to:
  - Identify impacted services and repos using error codes, endpoint paths, and service names when present.
  - Enrich the fingerprint with backend context (e.g., `access-service`, `notifications-service`, `automations-service`).

### 3\. GitHub MCP search strategy (mapping-driven)

When you have a regression fingerprint plus surface/service mappings:

- Restrict **PR/release/commit** searches to:
  - Repos listed in the matched frontend surfaces’ **GitHub Component / Repo Hints**.
  - Repos listed in the matched backend components’ **GitHub Repo(s) / Component Hints**.
- Build search queries using:
  - Error codes (e.g., `"ACCESS_081"`).
  - Key nouns from the surface (e.g., `"List view"`, `"notifications"`, `"doc editor"`, `"automation"`).
  - Time window from the regression timeline (between last-known-good and first-bad when known).
- Prefer a **small, high-signal repo set** over broad organization-wide searches, to keep results focused and interpretable.

### 4\. Bisect prep and evidence gathering

Once likely good/bad releases are identified for a repo:

- Choose at least one **good** PR from the last-known-good release.
- Choose at least one **bad** PR from the first-bad release.
- Prepare a **Bisect Tool prep block** in the regression task, including:
  - Good PR URL
  - Bad PR URL
  - Repo/component name
  - Any route/URL hints required by the Bisect Tool configuration
- Use the Private ([https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421](https://app.clickup-stg.com/333/docs/ad-229021/ad-3587421)) instructions to:
  - Fill `good` and `bad` PR links
  - Set the initial route to the repro location
  - Run the bisect and record the commit that introduced the regression

---

## Dynamic behavior across arbitrary requests

These rules are intentionally **pattern-based**, so that agents can handle new and unexpected reports:

- As long as a request can be reduced to:
  - One or more **frontend surfaces** (from Frontend Regression Surfaces), and/or
  - One or more **backend components** (from Backend Services & Error Codes), and
  - A clear **before vs after** story,
- The same routing + GitHub search + Bisect prep behavior applies, even if the exact error string or feature combination has never been seen before.

When no mapping row exists yet for a given surface or service:

- Fall back to general regression heuristics.
- Log the missing surface/service for later addition to the mapping tables.
- Prefer more conservative language ("possible regression" vs "confirmed regression") until mappings and evidence are stronger.

# Regression Mapping – Squad Index

# Regression Mapping – Squad Index

## Purpose

Organize regression mapping and GitHub MCP hints **by squad**, so agents can:

- Take a regression-flavored request from a TIM task, defect, or ticket.
- Route it to the correct **squad page** using Compendium + the Super Agent Mapping doc.
- Within that squad page, find:
  - Frontend surfaces
  - Backend services & error codes
  - Workspace search (`search_workspace`) patterns for validation and code checks
  - GitHub MCP search & Bisect Tool hints

This is intended to be **dynamic**: entries are pattern-based, not tied to a single error code. Any report that matches a pattern should benefit from the same mapping.

---

## How agents should use this index

1. Use Compendium + the main Super Agent Mapping table to infer **Category** and **Squad**.
2. Open the corresponding **Regression –** page listed below.
3. On that squad page:
   - Normalize the regression fingerprint (surfaces, errors, timeline).
   - Run recommended `search_workspace` checks to validate the mapping and look for prior art / GitHub links.
   - Use the GitHub MCP & Bisect strategy section to scope:
     - `search_pull_requests`
     - `list_releases`
     - `list_commits`
   - Output a **Bisect prep** block + summary back to the regression task.

---

## Squad pages

Create / use the following subpages (initial set):

- **Regression – Access Management**
- **Regression – Task / List View**
- **Regression – Docs**
- **Regression – Notifications**

Future additions can follow the same pattern, e.g.:

- Regression – Integrations
- Regression – Core Services
- Regression – Work Analytics
- Regression – AI

Each squad page should follow the shared template:

1. Squad scope (regression view)
2. Frontend surfaces
3. Backend services & error codes
4. Workspace validation & code-adjacent checks (`search_workspace`)
5. GitHub MCP search & Bisect strategy
6. Examples & test cases

# Regression – Docs

# Regression – Docs

## 1\. Squad scope (regression view)

- **Squad:** Docs
- **Primary areas:** Docs editor, comments, permissions/sharing for docs, public docs.
- **Common regression themes:**
  - Users unable to edit docs that they previously could edit.
  - "Editing unavailable" / doc locked states appearing after releases.
  - Public docs access/visibility changing unexpectedly.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name               | Canonical ID   | Example User Phrases                                   | Related Flows                                   | GitHub Frontend Hints                     |
| -------------------------- | -------------- | ------------------------------------------------------ | ----------------------------------------------- | ----------------------------------------- |
| Docs Editor                | `docs_editor`  | "can’t edit doc", "editing unavailable", "doc locked"  | Inline editing, collaborative editing, comments | <docs editor frontend repos/modules>      |
| Docs Sharing / Public View | `docs_sharing` | "public link stopped working", "guests can’t open doc" | Sharing docs, public docs, permissions          | <docs sharing/public frontend components> |

---

## 3\. Backend services & error codes for this squad

| Service / Component | Identifier(s)                                | Typical Regression Signatures                                | Error Codes / Messages                       | GitHub Backend Hints |
| ------------------- | -------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------- | -------------------- |
| Docs Service        | `docs-service`, YJS/Codox-related components | Edit operations failing after release; collaboration desyncs | Editor error toasts; 5xx from docs endpoints |                      |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Docs editing outages/bugs**

`search for defects in 🐞 Defects Master Lists where title or description contains "editing unavailable" OR "can’t edit doc" AND Squad = Docs`

- **Public docs regressions**

`search workspace for tasks mentioning "public doc" AND ("stopped working" OR "access denied")`

- **Existing GitHub links**

`search workspace for GitHub PR links in tasks/docs that also contain "docs editor" OR "YJS" OR "Codox"`

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to docs frontend/backend repos.
- Build PR search queries like:
  - `"editing unavailable" doc`
  - `"public doc" AND ("access" OR "permission")`
  - `YJS OR Codox` for deeper editor engine changes.
- Use known release windows from workspace search/defects to identify last-good vs first-bad.
- Select good/bad PRs and output Bisect prep in the regression task.

---

## 6\. Example – Doc editing disabled after release

- **Input snippet:** "After the latest release, team members can no longer edit a doc they owned before; they see 'editing unavailable'."
- **Fingerprint:**
  - Surface: `docs_editor`.
  - Timeline: "after the latest release".
- **Workspace validation:** find similar Docs squad defects + any linked PRs.
- **GitHub MCP:** scope to docs repos; search for PRs mentioning doc editing + permissions.
- **Bisect prep:** pick good/bad PRs that bracket the regression window.

# Regression – Notifications

# Regression – Notifications

## 1\. Squad scope (regression view)

- **Squad:** Notifications
- **Primary areas:** Bell/inbox notifications, email notifications, mobile push, notification rules.
- **Common regression themes:**
  - Notifications stop sending after a deploy.
  - Only certain channels (email vs in-app vs mobile) stop.
  - Notification volume changes dramatically without config changes.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name               | Canonical ID          | Example User Phrases                                                   | Related Flows                               | GitHub Frontend Hints                  |
| -------------------------- | --------------------- | ---------------------------------------------------------------------- | ------------------------------------------- | -------------------------------------- |
| Inbox / Bell Notifications | `notifications_inbox` | "stopped getting notifications", "bell is empty", "inbox not updating" | Inbox, notification feed, mark-read/archive | <notifications frontend repos/modules> |

---

## 3\. Backend services & error codes for this squad

| Service / Component   | Identifier(s)                                       | Typical Regression Signatures                                       | Error Codes / Messages                               | GitHub Backend Hints |
| --------------------- | --------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------- | -------------------- |
| Notifications Service | `notifications-service`, messaging/queue components | All or some notifications stop after release; delays or duplication | Delivery failure logs, queue errors, provider errors |                      |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Notifications defects by squad**

`search for defects in 🐞 Defects Master Lists where title or description contains "notifications" AND Squad = Notifications`

- **Recent outages/incidents**

`search workspace for incident/impact tasks mentioning "notifications" OR "inbox" OR "bell" in the last X days`

- **Existing GitHub links**

`search workspace for GitHub PR links in tasks/docs that also contain "notifications" OR names of notification providers`

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to notifications frontend + backend repos.
- Build PR search queries like:
  - `"notifications" AND ("inbox" OR "bell" OR "email")`
  - Provider-specific queries if external provider is mentioned.
- Use incident/deploy timelines from workspace search to define last-good vs first-bad.
- Select good/bad PRs for Bisect prep.

---

## 6\. Example – Inbox notifications stopped

- **Input snippet:** "Since Thursday’s deploy, users stopped receiving in-app inbox notifications, but emails still arrive."
- **Fingerprint:**
  - Surface: `notifications_inbox`.
  - Services: notifications service + relevant channel.
  - Timeline: "since Thursday’s deploy".
- **Workspace validation:** find other incidents/defects with same symptom and any PRs.
- **GitHub MCP:** search in notifications repos for PRs touching inbox/bell logic around that deploy.
- **Bisect prep:** bracket the regression window with good/bad PRs.

# Regression – Access Management

# Regression – Access Management

## 1\. Squad scope (regression view)

- **Squad:** Access Management / User Platform
- **Primary areas:** Permissions, Teams, Guests, sharing at Space/Folder/List/Task, roles.
- **Common regression themes:**
  - Users unexpectedly lose edit/access rights after role/team changes.
  - ACCESS_0xx errors when attempting actions they previously could perform.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                 | Canonical ID     | Example User Phrases                                                                   | Related Flows                                                             | GitHub Frontend Hints                                            |
| ---------------------------- | ---------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Permissions / Sharing Dialog | `permissions_ui` | "can’t share list", "lost access", "ACCESS_081 when editing", "team permissions wrong" | Changing Teams/roles, sharing Lists/Folders/Spaces, adjusting permissions | <web client module(s) rendering sharing dialog / permissions UI> |

---

## 3\. Backend services & error codes for this squad

| Service / Component          | Identifier(s)                                               | Typical Regression Signatures                                                                                 | Error Codes / Messages               | GitHub Backend Hints                       |
| ---------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------ |
| Access / Permissions Service | `access-service`, `permissions-service`, relevant endpoints | Permission resolution changes after deploy; users drop from Full Edit to Comment-only after role/team changes | `ACCESS_081`, other ACCESS_0xx codes | <primary access/permissions backend repos> |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Defects for ACCESS_0xx in Access Management**

`search for defects in 🐞 Defects Master Lists where title or description contains "ACCESS_0" and Compendium/Squad indicates Access Management`.

- **TIM / regression tasks with ACCESS_081**

`search workspace for tasks mentioning "ACCESS_081" AND "permissions" AND "team"`.

- **Existing GitHub links for ACCESS_0xx**

`search workspace for GitHub PR links in tasks/docs that also contain "ACCESS_0" and "permissions"`.

Use these hits to:

- Confirm we’re truly in the Access Management domain.
- Reuse any known good/bad version notes or PR links.

---

## 5\. GitHub MCP search & Bisect strategy for Access Management

- Restrict GitHub MCP operations to repos listed in **GitHub Frontend Hints** + **GitHub Backend Hints**.
- Build PR search queries like:
  - `"ACCESS_081" permissions team list`
  - `"ACCESS_0" AND (permissions OR sharing) AND team`
- Use release timelines (from Regressions list tasks, prior defects, or workspace search hits) to define last-good vs first-bad.
- When good/bad releases are known, choose representative good/bad PRs and output a **Bisect prep** block in the regression task.

---

## 6\. Example – ACCESS_081 after team change

- **Input snippet:** "After being added to another Team, I can no longer edit checklist items and see ACCESS_081 errors."
- **Fingerprint:**
  - Surface: `permissions_ui` (Permissions / Sharing Dialog).
  - Error: `ACCESS_081`.
  - Timeline: "After being added to another Team".
- **Workspace validation:**
  - Find prior TIM/defect tasks matching ACCESS_081 + permissions + team.
  - Collect any GitHub PR links or release notes attached there.
- **GitHub MCP:**
  - Search PRs in access/permissions repos with tokens `"ACCESS_081"`, `permissions`, `team`, `list` inside the suspected regression window.
- **Bisect prep:**
  - Choose good/bad PRs based on last-known-good / first-bad releases.
  - Output Bisect config in the regression task for humans to run.

# Regression – Task / List View

# Regression – Task / List View

## 1\. Squad scope (regression view)

- **Squad:** Task / Hierarchy / List View (adjust name to your squad taxonomy)
- **Primary areas:** List view, Task view entry, filtering/sorting/grouping, subtask visibility.
- **Common regression themes:**
  - Tasks disappearing from List view (filters, closed items, subtask modes).
  - Clicks in List view not opening Task view.
  - Sort/group behavior changing after releases.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                    | Canonical ID            | Example User Phrases                                                           | Related Flows                                                 | GitHub Frontend Hints              |
| ------------------------------- | ----------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------- | ---------------------------------- |
| List View                       | `list_view`             | "tasks disappeared from list", "no matching results", "list won’t load"        | Filters, group by, columns, show closed, subtask display mode | <list-view frontend modules/repos> |
| Task View 3.0 (entry from List) | `task_view_3_from_list` | "clicking a task does nothing", "task pane blank", "can’t open task from list" | Opening tasks from List; split view vs full-screen            | <task view frontend modules/repos> |

---

## 3\. Backend services & error codes for this squad

| Service / Component      | Identifier(s)                                      | Typical Regression Signatures                                                  | Error Codes / Messages                                               | GitHub Backend Hints      |
| ------------------------ | -------------------------------------------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------------------- | ------------------------- |
| Task / List Data Service | `task-service`, `list-service`, relevant endpoints | Tasks missing or counts off after release; list queries failing intermittently | HTTP 4xx/5xx from task/list endpoints; "no matching results" in logs | <task/list backend repos> |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Recent list-view defects**

`search for defects in 🐞 Defects Master Lists where title or description contains "List view" OR "no matching results" AND Squad = Task/Hierarchy`

- **Tasks not opening from List**

`search workspace for tasks/docs mentioning "clicking a task does nothing" OR "task pane blank"`

- **Existing GitHub links**

`search workspace for GitHub PR links in tasks/docs that also contain "List view" or "task pane"`

Use hits to confirm we’re in Task/List, and reuse any known good/bad version notes or PRs.

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to:
  - List view frontend/backend repos
  - Task view frontend/backend repos (when entry from List is involved)
- Build PR search queries like:
  - `"List view" AND ("no matching results" OR "disappeared")`
  - `"task pane" OR "task modal" AND "click"`
- Use timelines from regression tasks/defects to pick last-good vs first-bad.
- Once releases are known, select good/bad PRs and output a Bisect prep block.

---

## 6\. Example – Task won’t open from List view

- **Input snippet:** "Since last week’s update, clicking on tasks in List view doesn’t open the task pane."
- **Fingerprint:**
  - Surface: `list_view`, `task_view_3_from_list`.
  - Timeline: "since last week’s update".
- **Workspace validation:** search for similar complaints and any attached PRs.
- **GitHub MCP:** search scoped Task/List repos for PRs mentioning List view + task open/selection.
- **Bisect prep:** choose good/bad PRs around that deploy window.

# Regression Mapping – Squad Index

# Regression Mapping – Squad Index

## Purpose

Organize regression mapping and GitHub MCP hints **by squad**, so agents can:

- Take a regression‑flavored request.
- Route it to the correct **squad page** using Compendium + mapping.
- Within that squad page, find:
  - Frontend surfaces
  - Backend services & error codes
  - Workspace search patterns (for validation & prior art)
  - GitHub MCP search & bisect hints

---

## How agents should use this index

1. Use existing Compendium + Super Agent Mapping to infer **Category** and **Squad**.
2. Open the corresponding **Regression –** page from the list below.
3. Follow that page to:
   - Normalize the regression fingerprint (surfaces, errors, timeline).
   - Confirm it against real data via `search_workspace`.
   - Drive **scoped GitHub MCP** searches and Bisect prep.

---

## Squad pages

Create and maintain one subpage per squad, for example:

- Regression – Access Management
- Regression – Task / List View
- Regression – Docs
- Regression – Notifications
- Regression – Integrations
- Regression – Core Services
- Regression – Work Analytics / Dashboards
- Regression – AI (future)

Each squad page should follow the standard per‑squad regression template (scope, surfaces, services, workspace validation patterns, GitHub MCP strategy, examples).

# Regression – Access Management

# Regression – Access Management

## 1\. Squad scope (regression view)

- **Squad:** Access Management / User Platform
- **Primary areas:** Permissions, Teams, Guests, sharing at Space/Folder/List/Task, roles.
- **Common regression themes:**
  - Users unexpectedly lose edit/access rights after role/team changes.
  - ACCESS_0xx errors when attempting actions they previously could perform.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                 | Canonical ID     | Example User Phrases                                                                   | Related Flows                                                             | GitHub Frontend Hints                                          |
| ---------------------------- | ---------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | -------------------------------------------------------------- |
| Permissions / Sharing Dialog | `permissions_ui` | "can’t share list", "lost access", "ACCESS_081 when editing", "team permissions wrong" | Changing Teams/roles, sharing Lists/Folders/Spaces, adjusting permissions | <web client modules rendering sharing dialog / permissions UI> |

---

## 3\. Backend services & error codes for this squad

| Service / Component          | Identifier(s)                                               | Typical Regression Signatures                                                                                 | Error Codes / Messages                 | GitHub Backend Hints                       |
| ---------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ------------------------------------------ |
| Access / Permissions Service | `access-service`, `permissions-service`, relevant endpoints | Permission resolution changes after deploy; users drop from Full Edit to Comment‑only after role/team changes | `ACCESS_081`, other `ACCESS_0xx` codes | <primary access/permissions backend repos> |

---

## 4\. Workspace validation & code‑adjacent checks (`search_workspace`)

Recommended validation queries:

- **Defects for ACCESS_0xx in Access Management**

search for defects in 🐞 Defects Master Lists where title or description contains "ACCESS_0" and Compendium/Squad indicates Access Management.

- **TIM / regression tasks with ACCESS_081**

search workspace for tasks mentioning "ACCESS_081" AND "permissions" AND "team".

- **Existing GitHub links for ACCESS_0xx**

search workspace for GitHub PR links in tasks/docs that also contain "ACCESS_0" and "permissions".

Use these hits to:

- Confirm we’re truly in the Access Management domain.
- Reuse any known good/bad version notes or PR links.

---

## 5\. GitHub MCP search & Bisect strategy for Access Management

- Restrict GitHub MCP operations to repos listed in **GitHub Frontend Hints** + **GitHub Backend Hints**.
- Build PR search queries like:
  - `"ACCESS_081" permissions team list`
  - `"ACCESS_0" AND (permissions OR sharing) AND team`
- Use release timelines (from Regressions list tasks, prior defects, or workspace search hits) to define last‑good vs first‑bad.
- When good/bad releases are known, choose representative good/bad PRs and output a **Bisect prep** block in the regression task.

---

## 6\. Example – ACCESS_081 after team change

- **Input snippet:** "After being added to another Team, I can no longer edit checklist items and see ACCESS_081 errors."
- **Fingerprint:**
  - Surface: `permissions_ui` (Permissions / Sharing Dialog).
  - Error: `ACCESS_081`.
  - Timeline: "After being added to another Team".
- **Workspace validation:** search for prior TIM/defect tasks matching ACCESS_081 + permissions + team, and collect any GitHub PR links.
- **GitHub MCP:** search scoped access/permissions repos for PRs mentioning `"ACCESS_081"`, `permissions`, `team`, `list` inside the suspected regression window.
- **Bisect prep:** choose good/bad PRs around the regression window and include them in a Bisect prep block in the regression task.

# Regression – Docs

# Regression – Docs

## 1\. Squad scope (regression view)

- **Squad:** Docs
- **Primary areas:** Docs editor, comments, permissions/sharing for docs, public docs.
- **Common regression themes:**
  - Users unable to edit docs that they previously could edit.
  - "Editing unavailable" / doc locked states appearing after releases.
  - Public docs access/visibility changing unexpectedly.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name               | Canonical ID   | Example User Phrases                                   | Related Flows                                   | GitHub Frontend Hints                     |
| -------------------------- | -------------- | ------------------------------------------------------ | ----------------------------------------------- | ----------------------------------------- |
| Docs Editor                | `docs_editor`  | "can’t edit doc", "editing unavailable", "doc locked"  | Inline editing, collaborative editing, comments | <docs editor frontend repos/modules>      |
| Docs Sharing / Public View | `docs_sharing` | "public link stopped working", "guests can’t open doc" | Sharing docs, public docs, permissions          | <docs sharing/public frontend components> |

---

## 3\. Backend services & error codes for this squad

| Service / Component | Identifier(s)                                | Typical Regression Signatures                                | Error Codes / Messages                       | GitHub Backend Hints |
| ------------------- | -------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------- | -------------------- |
| Docs Service        | `docs-service`, YJS/Codox-related components | Edit operations failing after release; collaboration desyncs | Editor error toasts; 5xx from docs endpoints |                      |

---

## 4\. Workspace validation & code‑adjacent checks (`search_workspace`)

Recommended validation queries:

- **Docs editing outages/bugs**

search for defects in 🐞 Defects Master Lists where title or description contains "editing unavailable" OR "can’t edit doc" AND Squad = Docs.

- **Public docs regressions**

search workspace for tasks mentioning "public doc" AND ("stopped working" OR "access denied").

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain "docs editor" OR "YJS" OR "Codox".

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to docs frontend/backend repos.
- Build PR search queries like:
  - `"editing unavailable" doc`
  - `"public doc" AND ("access" OR "permission")`
  - `YJS OR Codox` for deeper editor engine changes.
- Use known release windows from workspace search/defects to identify last-good vs first-bad.
- Select good/bad PRs and output Bisect prep in the regression task.

---

## 6\. Example – Doc editing disabled after release

- **Input snippet:** "After the latest release, team members can no longer edit a doc they owned before; they see 'editing unavailable'."
- **Fingerprint:**
  - Surface: `docs_editor`.
  - Timeline: "after the latest release".
- **Workspace validation:** find similar Docs squad defects + any linked PRs.
- **GitHub MCP:** scope to docs repos; search for PRs mentioning doc editing + permissions.
- **Bisect prep:** pick good/bad PRs that bracket the regression window and include them in a Bisect prep block in the regression task.

# Regression – Task / List View

# Regression – Task / List View

## 1\. Squad scope (regression view)

- **Squad:** Task / Hierarchy / List View (adjust to your actual squad name)
- **Primary areas:** List view, Task view entry from List, filtering/sorting/grouping, subtask visibility.
- **Common regression themes:**
  - Tasks disappearing from List view (filters, closed items, subtask modes).
  - Clicks in List view not opening Task view.
  - Sort/group behavior changing after releases.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                    | Canonical ID            | Example User Phrases                                                           | Related Flows                                                 | GitHub Frontend Hints              |
| ------------------------------- | ----------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------- | ---------------------------------- |
| List View                       | `list_view`             | "tasks disappeared from list", "no matching results", "list won’t load"        | Filters, group by, columns, show closed, subtask display mode | <list-view frontend modules/repos> |
| Task View 3.0 (entry from List) | `task_view_3_from_list` | "clicking a task does nothing", "task pane blank", "can’t open task from list" | Opening tasks from List; split view vs full-screen            | <task view frontend modules/repos> |

---

## 3\. Backend services & error codes for this squad

| Service / Component      | Identifier(s)                                      | Typical Regression Signatures                                                  | Error Codes / Messages                                               | GitHub Backend Hints      |
| ------------------------ | -------------------------------------------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------------------- | ------------------------- |
| Task / List Data Service | `task-service`, `list-service`, relevant endpoints | Tasks missing or counts off after release; list queries failing intermittently | HTTP 4xx/5xx from task/list endpoints; "no matching results" in logs | <task/list backend repos> |

---

## 4\. Workspace validation & code‑adjacent checks (`search_workspace`)

Recommended validation queries:

- **Recent list-view defects**

search for defects in 🐞 Defects Master Lists where title or description contains "List view" OR "no matching results" AND Squad = Task/Hierarchy.

- **Tasks not opening from List**

search workspace for tasks/docs mentioning "clicking a task does nothing" OR "task pane blank".

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain "List view" or "task pane".

Use hits to confirm we’re in Task/List, and reuse any known good/bad version notes or PRs.

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to:
  - List view frontend/backend repos.
  - Task view frontend/backend repos (when entry from List is involved).
- Build PR search queries like:
  - `"List view" AND ("no matching results" OR "disappeared")`
  - `"task pane" OR "task modal" AND "click"`.
- Use timelines from regression tasks/defects to pick last-good vs first-bad.
- Once releases are known, select good/bad PRs and output a Bisect prep block.

---

## 6\. Example – Task won’t open from List view

- **Input snippet:** "Since last week’s update, clicking on tasks in List view doesn’t open the task pane."
- **Fingerprint:**
  - Surfaces: `list_view`, `task_view_3_from_list`.
  - Timeline: "since last week’s update".
- **Workspace validation:** search for similar complaints and any attached PRs.
- **GitHub MCP:** scoped search in Task/List repos for PRs mentioning List view + task open/selection.
- **Bisect prep:** choose good/bad PRs around that deploy window and include them in a Bisect prep block in the regression task.

# Regression – Core Services

# Regression – Core Services

## 1\. Squad scope (regression view)

- **Squad:** Core Services (SSO/SCIM, auth, platform‑level services)
- **Primary areas:** Login, SSO (Okta, Google, Microsoft, etc.), SCIM provisioning, core platform APIs.
- **Common regression themes:**
  - Users who previously could log in or SSO now can’t.
  - SCIM syncs start failing.
  - Core APIs return new errors after deploy.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                | Canonical ID       | Example User Phrases                                       | Related Flows                                      | GitHub Frontend Hints            |
| --------------------------- | ------------------ | ---------------------------------------------------------- | -------------------------------------------------- | -------------------------------- |
| Login / SSO Screen          | `login_sso`        | "SSO stopped working", "Okta login fails", "can’t sign in" | Email/password login, SSO providers, error banners | <frontend modules for login/SSO> |
| Account / Security Settings | `account_security` | "security settings disappeared", "2FA options changed"     | Changing passwords, 2FA, SSO configuration         | <account/security UI repos>      |

---

## 3\. Backend services & error codes for this squad

| Service / Component         | Identifier(s)                                | Typical Regression Signatures                                               | Error Codes / Messages                                                   | GitHub Backend Hints     |
| --------------------------- | -------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------------------ |
| Auth / SSO Service          | `auth-service`, provider‑specific components | Users lose ability to log in or SSO after release; provider‑specific errors | SAML/OAuth error codes, "invalid assertion", "invalid redirect" messages | <auth/SSO backend repos> |
| SCIM / Provisioning Service | `scim-service`, `provisioning-service`       | SCIM syncs that used to work start failing or mis‑provisioning              | SCIM error responses, HTTP 4xx/5xx from SCIM endpoints                   |                          |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **SSO/SCIM defects**

search for defects in 🐞 Defects Master Lists where title or description contain "SSO", provider names, or "SCIM" AND Squad = Core Services.

- **Recent login outages/incidents**

search workspace for incident/impact tasks mentioning "login" OR "SSO" OR provider names in the last X days.

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain "SSO", provider names, or "SCIM".

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to core auth/SSO/SCIM repos.
- Build PR search queries like:
  - `"SSO" OR provider names AND ("login" OR "authentication")`.
  - `"SCIM" AND ("provision" OR "sync")`.
- Use outage windows from workspace search to define last-good vs first-bad.
- Select good/bad PRs and output Bisect prep in regression tasks.

---

## 6\. Example – Okta SSO regressions

- **Input snippet:** "Okta SSO worked last week but now users get an invalid assertion error when logging in."
- **Fingerprint:**
  - Surface: `login_sso`.
  - Services: auth/SSO service, Okta‑specific components.
  - Timeline: "worked last week", now broken.
- **Workspace validation:** search for SSO/Okta incidents + defects and any PRs.
- **GitHub MCP:** search in auth/SSO repos for PRs mentioning Okta/SAML assertion changes.
- **Bisect prep:** bracket the regression window with good/bad PRs and include them in a Bisect prep block in the regression task.

# Regression – Integrations

# Regression – Integrations

## 1\. Squad scope (regression view)

- **Squad:** Integrations / Integration Services
- **Primary areas:** 3rd‑party app connections (GitHub, Slack, email providers, calendar, etc.), sync jobs, webhooks.
- **Common regression themes:**
  - Syncs or automations stop after a deploy.
  - Specific providers stop working while others continue.
  - Webhooks or API callbacks that used to fire no longer do.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name                        | Canonical ID            | Example User Phrases                                                                       | Related Flows                                   | GitHub Frontend Hints |
| ----------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------- | --------------------- |
| Integrations Settings UI            | `integrations_settings` | "GitHub integration disconnected", "can’t reconnect Slack", "integration settings missing" | Connecting/disconnecting tools, managing tokens |                       |
| Integration Status / Activity Views | `integrations_status`   | "sync history is empty", "sync shows errors"                                               | Sync status UIs, logs, retry buttons            |                       |

---

## 3\. Backend services & error codes for this squad

| Service / Component         | Identifier(s)                                    | Typical Regression Signatures                                    | Error Codes / Messages                                                        | GitHub Backend Hints          |
| --------------------------- | ------------------------------------------------ | ---------------------------------------------------------------- | ----------------------------------------------------------------------------- | ----------------------------- |
| Integration Services        | `integration-service`, provider‑specific workers | Sync jobs failing or silently stopping after release             | Provider errors, HTTP 4xx/5xx from external APIs, internal retry/queue errors |                               |
| Webhook / Events Dispatcher | `webhook-service`, `events-service`              | Webhooks stop firing, external systems no longer receive updates | Delivery failures, timeouts, signature errors                                 | <webhook/event backend repos> |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Integration defects by provider**

search for defects in 🐞 Defects Master Lists where title or description mention the provider name ("GitHub", "Slack", etc.) AND Squad = Integrations.

- **Recent sync/automation incidents**

search workspace for incident/impact tasks mentioning "integration" OR provider names AND "stopped" OR "no longer".

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain the provider name and "integration".

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to:
  - Integration services repos.
  - Webhook/event dispatcher repos when callbacks are involved.
- Build PR search queries like:
  - `"<Provider Name>" AND integration AND (sync OR webhook OR authorization)`.
  - `"integration" AND ("stopped" OR "no longer")`.
- Use deploy/incident timelines from workspace search to define last-good vs first-bad.
- Select good/bad PRs for Bisect prep.

---

## 6\. Example – GitHub integration stopped syncing

- **Input snippet:** "After last Thursday’s deploy, the GitHub integration stopped syncing new PRs into our workspace."
- **Fingerprint:**
  - Surfaces: `integrations_settings`, `integrations_status`.
  - Services: integration service(s) for GitHub.
  - Timeline: "after last Thursday’s deploy".
- **Workspace validation:** find other GitHub integration defects/incidents and any linked PRs.
- **GitHub MCP:** scope to integration repos; search PRs mentioning GitHub integration + sync.
- **Bisect prep:** choose good/bad PRs bracketing the deploy window and include them in a Bisect prep block in the regression task.

# Regression – Notifications

# Regression – Notifications

## 1\. Squad scope (regression view)

- **Squad:** Notifications
- **Primary areas:** Bell/inbox notifications, email notifications, mobile push, notification rules.
- **Common regression themes:**
  - Notifications stop sending after a deploy.
  - Only certain channels (email vs in-app vs mobile) stop.
  - Notification volume changes dramatically without config changes.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name               | Canonical ID          | Example User Phrases                                                   | Related Flows                               | GitHub Frontend Hints                  |
| -------------------------- | --------------------- | ---------------------------------------------------------------------- | ------------------------------------------- | -------------------------------------- |
| Inbox / Bell Notifications | `notifications_inbox` | "stopped getting notifications", "bell is empty", "inbox not updating" | Inbox, notification feed, mark-read/archive | <notifications frontend repos/modules> |

---

## 3\. Backend services & error codes for this squad

| Service / Component   | Identifier(s)                                       | Typical Regression Signatures                                       | Error Codes / Messages                               | GitHub Backend Hints |
| --------------------- | --------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------- | -------------------- |
| Notifications Service | `notifications-service`, messaging/queue components | All or some notifications stop after release; delays or duplication | Delivery failure logs, queue errors, provider errors |                      |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Notifications defects by squad**

search for defects in 🐞 Defects Master Lists where title or description contains "notifications" AND Squad = Notifications.

- **Recent outages/incidents**

search workspace for incident/impact tasks mentioning "notifications" OR "inbox" OR "bell" in the last X days.

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain "notifications" OR names of notification providers.

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to notifications frontend + backend repos.
- Build PR search queries like:
  - `"notifications" AND ("inbox" OR "bell" OR "email")`.
  - Provider-specific queries if external provider is mentioned.
- Use incident/deploy timelines from workspace search to define last-good vs first-bad.
- Select good/bad PRs for Bisect prep.

---

## 6\. Example – Inbox notifications stopped

- **Input snippet:** "Since Thursday’s deploy, users stopped receiving in-app inbox notifications, but emails still arrive."
- **Fingerprint:**
  - Surface: `notifications_inbox`.
  - Services: notifications service + relevant channel.
  - Timeline: "since Thursday’s deploy".
- **Workspace validation:** find other incidents/defects with same symptom and any PRs.
- **GitHub MCP:** search in notifications repos for PRs touching inbox/bell logic around that deploy.
- **Bisect prep:** bracket the regression window with good/bad PRs and include them in a Bisect prep block in the regression task.

# Regression – Work Analytics / Dashboards

# Regression – Work Analytics / Dashboards

## 1\. Squad scope (regression view)

- **Squad:** Work Analytics / Dashboards
- **Primary areas:** Dashboards, widgets, charts, card calculations, reporting.
- **Common regression themes:**
  - Dashboard cards that used to show correct values now show wrong or empty data.
  - Filters/groupings on dashboard cards behave differently after a release.
  - Exported reports no longer match in‑app values.

---

## 2\. Frontend surfaces owned by this squad

| Surface Name   | Canonical ID     | Example User Phrases                                                  | Related Flows                                            | GitHub Frontend Hints              |
| -------------- | ---------------- | --------------------------------------------------------------------- | -------------------------------------------------------- | ---------------------------------- |
| Dashboard View | `dashboard_view` | "dashboard card wrong", "widgets stopped updating", "chart looks off" | Creating/editing dashboards, filtering/grouping on cards | <dashboard frontend repos/modules> |

---

## 3\. Backend services & error codes for this squad

| Service / Component           | Identifier(s)                            | Typical Regression Signatures                                         | Error Codes / Messages                                  | GitHub Backend Hints                |
| ----------------------------- | ---------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------- | ----------------------------------- |
| Analytics / Reporting Service | `analytics-service`, `reporting-service` | Counts/metrics change unexpectedly after release; cards show zero/NaN | Internal analytics errors, 5xx from reporting endpoints | <analytics/reporting backend repos> |

---

## 4\. Workspace validation & code-adjacent checks (`search_workspace`)

Recommended validation queries:

- **Analytics/dashboard defects**

search for defects in 🐞 Defects Master Lists where title or description contain "dashboard" OR "widget" OR "card" AND Squad = Work Analytics.

- **Report mismatch incidents**

search workspace for tasks mentioning "dashboard" AND ("wrong" OR "incorrect" OR "mismatch").

- **Existing GitHub links**

search workspace for GitHub PR links in tasks/docs that also contain "dashboard" OR "analytics".

---

## 5\. GitHub MCP search & Bisect strategy

- Restrict GitHub MCP operations to dashboard/frontend and analytics/backend repos.
- Build PR search queries like:
  - `"dashboard" AND ("card" OR "widget") AND ("calculation" OR "metric")`.
  - `"analytics" AND ("count" OR "aggregation")`.
- Use defect/incident timelines from workspace search to define last-good vs first-bad.
- Select good/bad PRs and output Bisect prep in the regression task.

---

## 6\. Example – Dashboard card shows wrong counts

- **Input snippet:** "Since the last release, our task count dashboard card shows half the tasks it used to, without any filter changes."
- **Fingerprint:**
  - Surface: `dashboard_view`.
  - Services: analytics/reporting service.
  - Timeline: "since the last release".
- **Workspace validation:** find similar Work Analytics defects; collect any linked PRs.
- **GitHub MCP:** search in analytics + dashboard repos for PRs mentioning card counts/filters.
- **Bisect prep:** bracket the regression window with good/bad PRs and include them in a Bisect prep block in the regression task.

# Bug Goblin – Regression MCP Repo & Mapping Integration

# Bug Goblin – Regression MCP Repo & Mapping Integration

## Purpose

Define how Bug Goblin should use:

- The **Regression Mapping – Squad Index** and squad subpages, and
- The **GitHub MCP repos** (`clickup` for backend, `clickup_frontend` for frontend),

to run fast, scoped regression checks and PR searches.

This page is written as configuration guidance for Bug Goblin’s instructions.

---

## 1\. GitHub MCP repo mapping

Bug Goblin should treat these as its canonical monorepos:

- **Frontend monorepo**: `clickup/clickup_frontend`
- **Backend monorepo**: `clickup/clickup`

All regression‑related MCP calls should be **scoped to these repos**, then optionally narrowed further by squad/surface/service context.

---

## 2\. Regression mapping pages Bug Goblin should use

Bug Goblin should rely on the following pages when handling regression candidates:

- **Regression Mapping – Squad Index**

– URL: (index page)

– Use to locate the correct squad page based on the Category/Squad it has already inferred via the Super Agent Mapping Document.

Squad pages (examples):

- Regression – Access Management
- Regression – Task / List View
- Regression – Docs
- Regression – Notifications
- Regression – Integrations
- Regression – Core Services
- Regression – Work Analytics / Dashboards

Each squad page defines:

- Squad scope & common regression themes
- Frontend surfaces (table) with canonical IDs and hints
- Backend services & error codes (table)
- Recommended `search_workspace` validation patterns
- GitHub MCP & Bisect strategy for that squad
- At least one end‑to‑end example

---

## 3\. High‑level algorithm for regression handling

When Bug Goblin detects a **regression candidate** (from task/ticket language or a dedicated regressions list):

1. **Build a regression fingerprint**
   - Surfaces: views/screens/flows mentioned (List view, Task view, Docs, Notifications, Permissions UI, etc.).
   - Error signals: HTTP codes, `ACCESS_0xx`, SSO/SCIM messages, editor toasts, provider errors.
   - Timeline: phrases like "used to", "since last release", specific dates or versions.
   - Environment: web/desktop/mobile, workspace, any linked defect/regression tasks.
2. **Infer Category/Squad as usual**
   - Use the **ClickUp Super Agent Mapping Document** + Compendium context to map the problem to a **Category** and **Squad/Feature Area**.
3. **Jump into the correct regression squad page**
   - Open **Regression Mapping – Squad Index**.
   - From the index, select the **Regression –** page matching the inferred squad.
4. **Map frontend surfaces and backend services**
   - On that squad page:
     - Match the fingerprint to one or more **frontend surfaces** using the table of Surface Name / Canonical ID / Example Phrases.
     - Match error codes/messages and component names to one or more **backend services** using the Backend Services & Error Codes table.
5. **Validate the mapping with workspace search**
   - Use the squad page’s recommended `search_workspace` queries to:
     - Confirm you’re in the correct squad area.
     - Find recent **defects** or **incidents** with similar symptoms.
     - Collect any **existing GitHub links, PRs, commits, or release notes** already stored in tasks/docs.
   - Fold those findings back into the fingerprint (e.g., known good/bad releases, specific endpoint names).
6. **Construct a scoped GitHub MCP search plan**
   - Frontend scope: always include `clickup/clickup_frontend`.
   - Backend scope: always include `clickup/clickup`.
   - Narrow further using:
     - The squad page’s **GitHub Frontend Hints** and **GitHub Backend Hints** (e.g., modules or directories).
     - The error codes/phrases and component names from the fingerprint.
   - For each side (frontend/backend), plan to call MCP tools such as:
     - `search_pull_requests` – queries including error codes, surface names, component names, and regression window.
     - `list_releases` – to anchor last‑known‑good vs first‑bad release candidates.
     - (Optionally) `search_code` when a particular symbol or error string is important.
7. **Identify candidate releases and PRs**
   - Use release timelines, incident timestamps, and workspace evidence to:
     - Choose one or more **last‑good** releases.
     - Choose one or more **first‑bad** releases.
   - Within those bounds, use `search_pull_requests` to:
     - Rank PRs that mention the relevant surfaces, endpoints, errors, or providers.
8. **Prepare Bisect Tool inputs (when appropriate)**
   - For the best candidate repo + regression window:
     - Pick a **good** PR (known or highly likely to be from a last‑good release).
     - Pick a **bad** PR (from a first‑bad release).
   - Output a **Bisect prep block** in the regression task so humans can plug it into the Bisect Tool.
9. **Write back a structured summary**
   - In the regression task or TIM task, post a comment that includes:
     - Mapped squad and surfaces/services.
     - Any confirming workspace evidence (defects/incidents, existing PR links).
     - Top candidate PRs and why they’re likely related.
     - Bisect prep details if generated.

---

## 4\. Where this plugs into Bug Goblin’s config

Human maintainers can:

- Add a **"Regression Mapping & MCP"** section to Bug Goblin’s configuration that:
  - Points to this page and the **Regression Mapping – Squad Index** page.
  - Embeds the algorithm above as explicit instructions.
- Ensure that when Bug Goblin recognizes regression‑ish language or runs on a regression list, it:
  - Follows this algorithm,
  - Scopes MCP calls to `clickup/clickup` and `clickup/clickup_frontend`, and
  - Uses the squad regression pages as its dynamic mapping source instead of hard‑coded rules.

This keeps Bug Goblin’s regression behavior **data‑driven** by the mapping pages while staying aligned with the actual MCP repo layout.
