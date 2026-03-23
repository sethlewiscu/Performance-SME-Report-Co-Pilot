# Performance Agent — Logic & Flow Reference

> **Status:** Work in progress — being built out collaboratively.
> Sections marked `[PENDING]` have open questions or decision tables still to be defined.

---

## What This Agent Does

Given a support rep's observations from a customer screen recording about latency issues, the Performance Agent:

1. **Identifies** the relevant product area(s) and performance type(s)
2. **Surfaces** matching engineering tasks tagged `ts - perf` from the EPD Squads space
3. **Creates sub-reports** (subtasks) under the original performance report with structured summaries
4. **Sets statuses** and **links engineering tasks** based on rep decisions
5. **Escalates** to the right person or channel when needed

---

## Routing Dimensions

Unlike single-dimension routing, this agent classifies every issue on **two axes simultaneously**.

### Dimension 1 — Product Area

|                       |               |
| --------------------- | ------------- |
| Automations           | Search        |
| Imports               | List view     |
| Chat                  | Board view    |
| Inbox                 | Table view    |
| Docs                  | Box/Team view |
| Task view             | Timeline view |
| Cards                 | Mindmap       |
| Mobile                | Gantt view    |
| Whiteboards           | Calendar view |
| ClickUp AI            | Workload view |
| Hierarchy             | Sidebar       |
| Fields                | Overviews     |
| Templates/Duplication |               |

### Dimension 2 — Performance Type

There are two **meta types**. Every performance classification maps to one of them.

| Meta type          | Description                                                                                                                 | Sub-symptoms                       | Reportable threshold     | Within expected range |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ------------------------ | --------------------- |
| **`initial_load`** | User loads the app for the first time, refreshes a page, or opens a new tab — regardless of which product area they land in | First app load / Refresh / New tab | > 15 seconds             | ≤ 15 seconds          |
| **`route_change`** | SPA navigation — moving between views or tasks within an already-loaded app session                                         | —                                  | > 5 seconds consistently | ≤ 5 seconds           |

**Modifiers** (applied on top of meta types):

| Modifier           | Applies to                       | Meaning                                                                        |
| ------------------ | -------------------------------- | ------------------------------------------------------------------------------ |
| **Global latency** | `initial_load` or `route_change` | Slowness is widespread — not isolated to one feature, view, or action          |
| **UI delays**      | `route_change` only              | Delayed responsiveness to clicks, navigation, or interactions within a session |

> **Within expected range rule:** If observed timings fall at or below the threshold, no engineering task should be filed. The agent should proactively flag this and ask the rep whether to escalate to `@performance-tim` for managerial approval before communicating "this is normal" to the customer.

### Routing key

The agent's primary key is always a **combination**: `[Product area] + [Meta type (+ modifier if applicable)]`.

> **Important:** It is common for a single rep observation to span multiple product areas (e.g., Dashboard + List view, Brain + Automations). The agent must handle multi-area observations — not assume one primary area per report.

> **Global latency modifier:** When global latency is identified, product area may be secondary or irrelevant. The agent should consider infra/network-level factors regardless of which feature was in use.

---

## Pre-Routing Checks

Before classifying by product area and performance type, the agent must check for two exit conditions. If either applies, the main routing flow does not run.

---

### Check 1 — Screen Sharing Only

**Trigger:** The user exclusively experiences latency while sharing their screen (Zoom, Google Meet, MS Teams, etc.) and has no performance issues otherwise.

**Agent action:** Send the appropriate macro — do not file a performance report or engineering task.

| Scenario                         | Macro                                        | Link                                      |
| -------------------------------- | -------------------------------------------- | ----------------------------------------- |
| Video conferencing tool conflict | Performance::Zoom vs MS Teams or Google Meet | `https://app.clickup-stg.com/t/8xdfqc6yv` |
| General screen sharing impact    | Performance::Impact of screen sharing        | `https://app.clickup-stg.com/t/8xdfqc6u3` |

---

### Check 2 — Non-Chrome / Non-Desktop-App Browser

**Trigger:** The agent identifies Safari or Firefox as the user's browser — from the **Primary Browser** custom field (ID: `7d7d5735-46f6-4fa6-bb2c-3dc0485801f4`) or from the rep's notes.

**Decision tree:**

```
Safari or Firefox detected?
  └── Yes → Ask rep to confirm: is Chrome or the desktop app more performant for this user?
        ├── Chrome / desktop app IS faster
        │     └── Send browser macro (Safari or Firefox, as appropriate)
        │     └── Suggest desktop app (macro: Performance::Try desktop app)
        │     └── Close the Zendesk ticket upon reply
        │     └── Close the performance report
        │           └── Set "Closed reason" custom field → NOT PERF
        └── Chrome is equally slow
              └── Request a new Clip demonstrating the performance issue on Chrome
              └── Resume normal routing flow once Chrome Clip is received
```

**Macros:**

| Scenario               | Macro                        | Link                                          |
| ---------------------- | ---------------------------- | --------------------------------------------- |
| Safari user            | Performance::Safari users    | `https://app.clickup-stg.com/t/333/8xdfnxzge` |
| Firefox user           | Performance::Firefox users   | `https://app.clickup-stg.com/t/333/8xdfnxzgg` |
| Desktop app suggestion | Performance::Try desktop app | `https://app.clickup-stg.com/t/8xdfnj3xm`     |

> **Closed reason custom field ID:** `a4df58af-8e76-4335-8060-e32e4a7935d7` — set value to `NOT PERF`.

---

## Inputs

The rep's observations are drawn from watching customer screen recordings (Clips). A well-formed observation typically contains:

| Field                 | Description                                                           |
| --------------------- | --------------------------------------------------------------------- |
| Product area(s)       | Which feature(s) were affected                                        |
| Performance type      | What kind of slowness was observed                                    |
| Clip link(s)          | Direct URLs to the screen recordings                                  |
| Timestamps            | Specific moments in the clip (e.g., "0:08 to 0:23")                   |
| Location URL          | The exact ClickUp URL where the issue occurred                        |
| View configuration    | Grouped by what field, filters active, task count, etc.               |
| Environment           | Browser (Chrome, Edge, etc.) vs. desktop app                          |
| LP status             | Whether login permissions were granted (`NO LP` = cannot impersonate) |
| DataDog findings      | Shard ID, geographic mismatch between CRM location and DD             |
| User-reported context | Multi-user, multi-device, multi-network confirmations                 |

### Vocabulary the agent must understand

| Term                                | Meaning                                                         |
| ----------------------------------- | --------------------------------------------------------------- |
| `skeleton loading`                  | Loading placeholder UI shown before content renders             |
| `stickiness`                        | General sluggishness across interactions                        |
| `shard`                             | Server assignment (e.g., `prod-us-west-2-3`)                    |
| `repro` / `can't repro in their WS` | Whether the rep reproduced the issue                            |
| `embed` / `embedded Doc`            | Third-party content embedded inside ClickUp                     |
| `pinned views`                      | Views pinned to the sidebar                                     |
| `auto-refresh`                      | Dashboard setting relevant to load behavior                     |
| `NO LP`                             | No login permissions — rep cannot impersonate user to reproduce |

---

## Task Surfacing

When the agent has identified product area(s) and performance type(s), it scans for matching engineering tasks.

### How it works

1. Query the **EPD Squads space** for tasks tagged `ts - perf`
   - Space: `https://app.clickup-stg.com/333/v/s/35400004`
   - Tag: `ts - perf` (exact string — spaces and casing matter)
   - Exclude closed tasks
2. For each result, consume:
   - Task **title**
   - Task **description**
   - Task **comments**
   - **Squad** custom field (ID: `4bbd5486-9e1c-4f0f-b35b-3792250988cc`)
3. **Suggest** the most likely matches to the rep — do not auto-link

### API approach

```
GET /api/v2/team/333/task
  ?space_id=35400004
  &tags[]=ts - perf
  &include_closed=false
  &page=0
```

Note: Comments require a separate call per task (`GET /task/{task_id}/comment`). Fetch comments only for top candidates, not all results.

---

## Specificity Gate

Before creating any sub-reports, the agent must confirm the rep has identified the specific component within each product area that is slow — not just the top-level area.

**Agent behavior:**

1. After identifying product area(s) and performance type(s), prompt the rep:
   > _"Before I create the sub-reports — have you clearly identified the specific [Product area] component that's slow? (e.g., for List view: is it the view header, custom field rendering, row rendering, the blank task row, etc.?)"_
2. Wait for the rep to confirm.
3. Once confirmed, proceed to sub-report creation.

> The agent does not need to enumerate sub-components for the rep — support staff are trained on this level of detail. The prompt is a coaching nudge, not a checklist.

---

## Sub-Report Creation

Sub-reports are **subtasks** created directly under the original performance report the rep is working in.

### Structure

```
[Original performance report]         ← parent task (rep's working task)
  └── {title} #1 - {area | type}      ← sub-report (subtask)
  └── {title} #2 - {area | type}      ← sub-report (subtask)
  └── ...
```

### Title format

```
{Original report title} #{Report number} - {Product area | Performance type}
```

- Report numbers are **1-indexed** (start at 1, not 0)
- Example: `Acme Corp slowness #1 - List view | Initial load > 15s`

### SME Summary (always required)

Always added to the **top** of the sub-report description. Label: **"SME Summary"**.

```
{Product area}: {Performance type}
{Succinct observations from rep's notes}
```

---

## Status Logic

| Status          | When to apply                                                             |
| --------------- | ------------------------------------------------------------------------- |
| `Defect linked` | Rep agrees with one of the agent's suggested engineering tasks            |
| `Defect linked` | Rep asks the agent to create a new defect                                 |
| `Needs TIM`     | Rep wants `@performance-tim` involved — see escalation logic below        |
| `Needs TS`      | Ticket owner needs to reach out to the user — `[PENDING: decision table]` |

---

## Linking an Engineering Task

When status = `Defect linked`, the agent links the sub-report to the engineering task using:

- **Custom field:** `🔗 Linked tasks`
- **Custom field ID:** `79551be6-ace3-4920-8f91-f741dbfcc1ad`

If the rep asks the agent to **create a new defect** (rather than linking an existing one), create it in the **Defects Master List**:

- URL: `https://app.clickup-stg.com/333/v/li/650700028`

---

## Escalation Logic

### Needs TIM (`@performance-tim`)

The agent sets this status and tags `@performance-tim` in a comment on the sub-report under the following conditions:

| Scenario                              | Trigger                                                                                                                                                         |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frustrated / uncooperative user**   | Rep indicates the user is highly frustrated or not cooperative and needs a manager's response                                                                   |
| **Call request**                      | User is requesting a call, OR rep believes TIM's call link should be shared with the user                                                                       |
| **Performance within expected range** | Rep believes the reported slowness is actually within normal performance thresholds — requires managerial approval before telling the customer "this is normal" |
| **General question / clarification**  | Rep has a question or needs guidance not covered by any other scenario                                                                                          |

**Agent behavior when Needs TIM is triggered:**

1. Set sub-report status to `Needs TIM`
2. Ask the rep: _"Should I raise this to @performance-tim?"_
3. If yes: tag `@performance-tim` in a comment on the sub-report

> **Proactive flag opportunity:** For the "within expected range" scenario, the agent should not wait for the rep to raise it manually. If the rep's observed load times or delays fall below the performance type thresholds (e.g., observed 3s load vs. the >15s threshold), the agent should proactively surface this and ask the rep whether to escalate for managerial approval before customer communication.

### Needs TS

`Needs TS` is set when the rep needs to follow up directly with the user. The agent guides which macro(s) to send based on the scenario.

| Scenario                                      | Trigger                                                                                   | Agent action                                                                                |
| --------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Chrome user with many tabs/extensions**     | Rep or agent observes the user is on Chrome with a heavy browser profile                  | Send both: `Performance::Try desktop app` + `Performance::Incognito mode steps`             |
| **Safari or Firefox user**                    | Primary Browser field or rep's notes indicate Safari/Firefox                              | Follow [Check 2 — Browser pre-routing](#check-2--non-chrome--non-desktop-app-browser) above |
| **Old hardware / OS suspected**               | Rep suspects user's machine or OS may be contributing to slowness                         | See OS-specific macros below                                                                |
| **Memory usage complaint (no perf evidence)** | User's primary complaint is high memory usage with no clear performance issue in the Clip | Send: `Performance::High memory usage`                                                      |
| **Large List view with many custom fields**   | Rep notices a List view with ~15+ custom fields                                           | Agent reminds rep to suggest Fast load mode — **agent does not take action directly**       |

**OS-specific machine specs macros:**

| OS             | Macro                                      | Link                                      |
| -------------- | ------------------------------------------ | ----------------------------------------- |
| Windows        | Performance::Machine Specs::Windows        | `https://app.clickup-stg.com/t/8xdfngqb5` |
| macOS or Linux | Performance::Machine Specs::macOS Catalina | `https://app.clickup-stg.com/t/8xdfnqw2d` |

**Fast load mode flow (Large List view scenario):**

```
Rep notices List view with ~15+ custom fields
  └── Agent reminds rep (does not act): suggest Fast load mode to the user
        └── Macro: Performance::Fast load mode
              https://app.clickup-stg.com/t/333/8xdfpk8bv
        └── If customer accepts / is interested:
              ├── Submit the Fast load mode Harness feature flag for approval:
              │     Harness flag: https://app.harness.io/ng/account/NYVU0wI4R0ijpWK5Gyl5pQ/module/fme/orgs/ClickUpFME/projects/ClickUp/org/1ef3b670-01f0-11ec-a057-42851e80ca2c/ws/1f03bc00-01f0-11ec-a057-42851e80ca2c/splits/293bb5b0-1bcd-11f0-9de6-4a4dba886fe3/env/1f08ec20-01f0-11ec-a057-42851e80ca2c/definition
              │     Public docs: https://doc.clickup-stg.com/333/p/h/ad-4833673/cd025ddc6cd3247
              └── Set status to Needs TIM
                    └── Include the Harness flag approval link in the TIM comment
```

**Needs TS macros reference:**

| Macro                             | Link                                          |
| --------------------------------- | --------------------------------------------- |
| Performance::Try desktop app      | `https://app.clickup-stg.com/t/8xdfnj3xm`     |
| Performance::Incognito mode steps | `https://app.clickup-stg.com/t/8xdfngnuh`     |
| Performance::High memory usage    | `https://app.clickup-stg.com/t/8xdfnfyrm`     |
| Performance::Fast load mode       | `https://app.clickup-stg.com/t/333/8xdfpk8bv` |

---

## Key IDs & References

| Resource                        | Value                                  |
| ------------------------------- | -------------------------------------- |
| Team ID (staging workspace)     | `333`                                  |
| EPD Squads space ID             | `35400004`                             |
| Defects Master List ID          | `650700028`                            |
| Squad custom field ID           | `4bbd5486-9e1c-4f0f-b35b-3792250988cc` |
| Linked tasks custom field ID    | `79551be6-ace3-4920-8f91-f741dbfcc1ad` |
| Closed reason custom field ID   | `a4df58af-8e76-4335-8060-e32e4a7935d7` |
| Primary Browser custom field ID | `7d7d5735-46f6-4fa6-bb2c-3dc0485801f4` |
| Performance tag (exact)         | `ts - perf`                            |

---

## Open Items

| #   | Topic                               | Notes                                                                                             |
| --- | ----------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1   | **Needs TIM scenarios**             | ✅ Defined                                                                                        |
| 2   | **Performance type taxonomy**       | ✅ Defined — meta types: `initial_load`, `route_change`; modifiers: global latency, UI delays     |
| 3   | **Screen sharing exit path**        | ✅ Defined                                                                                        |
| 4   | **Browser pre-routing check**       | ✅ Defined                                                                                        |
| 5   | **Needs TS decision table**         | ✅ Defined                                                                                        |
| 6   | **"Closed reason" custom field ID** | ✅ `a4df58af-8e76-4335-8060-e32e4a7935d7`                                                         |
| 7   | **Multi-area tiebreaker logic**     | ✅ No prioritization needed — each product area gets its own sub-report                           |
| 8   | **NO LP fallback playbook**         | ✅ No action — if the user hasn't granted login permissions, the rep proceeds with what they have |
