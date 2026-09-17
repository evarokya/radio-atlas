---
id: TASK-27
title: Add discover API and UI
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - discovery
dependencies:
  - TASK-26
  - TASK-22
  - TASK-19
ordinal: 27000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
POST /api/discover returns intent and stations. Uses AI SDK generateObject when an AI key is configured, otherwise the deterministic parser. Discover input on the home page.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Works with no AI key
- [ ] #2 AI output validated with Zod and falls back on failure
- [ ] #3 Rate limited
<!-- AC:END -->
