---
id: TASK-24
title: Show now playing in the player
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - now-playing
dependencies:
  - TASK-23
  - TASK-13
ordinal: 24000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Poll the now-playing API every 30 seconds while a non-HLS station plays and show the title in the player and media session.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Polling stops when paused or station changes
- [ ] #2 Missing metadata shows nothing
<!-- AC:END -->
