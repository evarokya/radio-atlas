---
id: TASK-5
title: Implement Radio Browser HTTP client
status: To Do
assignee: []
created_date: '2026-09-17 15:40'
labels:
  - stations
dependencies:
  - TASK-1
priority: high
ordinal: 5000
---

## Description

<!-- SECTION:DESCRIPTION:BEGIN -->
Server-only client for the Radio Browser API: mirror list resolution with fallback, descriptive User-Agent, timeout, one retry on another mirror, Next.js fetch revalidation.
<!-- SECTION:DESCRIPTION:END -->

## Acceptance Criteria
<!-- AC:BEGIN -->
- [ ] #1 Base URL overridable via RADIO_BROWSER_BASE_URL
- [ ] #2 Requests time out after 8 seconds
- [ ] #3 Retries once on a different mirror
- [ ] #4 Unit tests with mocked fetch
<!-- AC:END -->
