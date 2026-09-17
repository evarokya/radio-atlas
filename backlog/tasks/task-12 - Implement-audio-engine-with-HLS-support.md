---
id: TASK-12
title: Implement audio engine with HLS support
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - player
dependencies:
  - TASK-11
priority: high
ordinal: 12000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Client provider owning a single audio element mounted in the root layout. Lazy loads hls.js for HLS streams, maps media events to store states, retries once then surfaces a friendly error.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Playback survives client navigation
- [ ] #2 HLS stations play in Chromium
- [ ] #3 Never retries more than once automatically
<!-- AC:END -->
