---
id: TASK-8
title: Add station detail and click API routes
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - api
dependencies:
  - TASK-6
ordinal: 8000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
GET /api/stations/[id] and POST /api/stations/[id]/click.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Unknown or invalid id returns 404
- [ ] #2 Click endpoint never blocks playback and swallows provider errors
<!-- AC:END -->
