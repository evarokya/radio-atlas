---
id: TASK-34
title: Add service worker offline support
status: To Do
assignee: []
created_date: '2026-09-17 15:41'
labels:
  - pwa
dependencies:
  - TASK-33
ordinal: 34000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Hand-written service worker: precache shell and offline page, stale-while-revalidate for station API GETs, network-first pages with offline fallback, never intercept audio. Offline notice in UI.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 App shell and favorites load offline
- [ ] #2 Audio requests are not intercepted
<!-- AC:END -->
