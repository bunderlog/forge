# Epic 4: Website & UX (13 points)

**Status:** Not Started  
**Priority:** High  
**Epic ID:** EPIC-04

## Description

Implement a user-facing web application for viewing, searching, and managing logs, plus dashboards and alerting configuration.

## Key Tasks

- Create UI with primary views: Log stream, Log detail, Search, Dashboards, Alerts, Settings, and User management
- Implement reusable components: time-range picker, query bar, result table, log viewer with expand/collapse and syntax highlighting
- Integrate with Query API and support deep-linking to query states
- Add role-based access control (RBAC) and auth integration (OAuth, SSO)
- Implement basic dashboards and ability to save queries

## Acceptance Criteria

- Users can search logs, open a specific log event, and view context
- Saved queries and dashboard views persist per user or team
- UI is responsive and accessible (basic a11y checks)

## Dependencies

- [Epic 3: Query API & Filtering](epic-03.md) - Requires backend API

## Related Epics

- [Epic 6: Security, Privacy & Compliance](epic-06.md) - RBAC and auth integration
- [Epic 8: Alerts & Integrations](epic-08.md) - Alert configuration UI
- [Epic 9: Onboarding, Documentation & Developer SDKs](epic-09.md) - Onboarding flow

