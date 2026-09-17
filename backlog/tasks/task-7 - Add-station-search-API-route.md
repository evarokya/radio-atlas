---
id: TASK-7
title: Add station search API route
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - api
dependencies:
  - TASK-6
priority: high
ordinal: 7000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
GET /api/stations validates query params with Zod and returns normalized stations.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Invalid params return 400 with a friendly message
- [ ] #2 Provider failures return 502 with a friendly message
- [ ] #3 Responses have sensible cache headers
<!-- AC:END -->
