---
id: TASK-3
title: Define station domain types and schemas
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - stations
dependencies:
  - TASK-1
priority: high
ordinal: 3000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Station, StationQuery, Facet types and Zod schemas plus the StationProvider interface (docs/architecture.md section 6).
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Types inferred from Zod schemas where they validate input
- [ ] #2 StationQuery schema validates limits, order and offsets
- [ ] #3 Unit tests cover valid and invalid queries
<!-- AC:END -->
