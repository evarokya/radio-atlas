---
id: TASK-23
title: Add now playing API
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - now-playing
dependencies:
  - TASK-22
  - TASK-6
ordinal: 23000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
GET /api/now-playing/[id] reads ICY metadata from the station stream with bounded bytes and timeout, SSRF guarded, rate limited.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Never accepts raw URLs from the client
- [ ] #2 ICY parser unit tested
- [ ] #3 Returns title null when metadata is unavailable
<!-- AC:END -->
