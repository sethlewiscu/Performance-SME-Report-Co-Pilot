# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a documentation repository for **Bug Goblin**, an internal AI-powered technical support agent at ClickUp. Currently it contains mapping documents that define Bug Goblin's routing logic, squad ownership, and troubleshooting workflows.

## Repository Contents

- `Bug Goblin Mapping Document-*.md` — Comprehensive reference document covering:
  - Keyword-to-compendium mappings for routing support issues to the correct squad
  - Helpdesk troubleshooting maps linked to Help Center articles
  - DB Ops patterns mapped to squads and Ops request templates
  - Squad dropdown IDs mapped to Compendium documentation URLs
  - Squad-to-chat-channel routing (ClickUp Chat + Slack)
  - Customer email routing by tone/intent with context-gathering checklists
  - Frontend Bisect tool usage for identifying regressions

## Architecture Notes

Bug Goblin routes inbound support signals (customer emails, Zendesk tickets, internal requests) through a series of mapping tables to:

1. Identify the relevant ClickUp squad or feature area
2. Surface the appropriate Compendium documentation
3. Escalate to the right Chat/Slack channel
4. Trigger DB Ops procedures when needed

The mapping document is the source of truth for these routing decisions and is intended to be consumed by the agent as reference context.
