---
id: TASK-25
title: Add Surprise Me
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - discovery
dependencies:
  - TASK-6
  - TASK-12
ordinal: 25000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
GET /api/surprise returns a random healthy station, Surprise Me button starts playback and links to the station.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Filters out low bitrate and unknown country stations
- [ ] #2 Friendly error if nothing found
<!-- AC:END -->
