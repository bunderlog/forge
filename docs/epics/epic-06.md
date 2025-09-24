# Epic 6: Security, Privacy & Compliance (8 points)

**Status:** Not Started  
**Priority:** Medium  
**Epic ID:** EPIC-06

## Description

Ensure logs are handled securely, with options for redaction, encryption, and compliance (e.g., GDPR) controls.

## Key Tasks

- Provide redaction pipeline or masking rules for sensitive fields
- Encrypt logs at rest and in transit (TLS, SSE)
- Implement access controls and audit logging for user actions
- Provide export/deletion workflows for compliance requests

## Acceptance Criteria

- Sensitive fields can be redacted before ingestion or at indexing
- Audit logs capture user actions in the web UI
- Deletion requests remove data according to retention and compliance policies

## Dependencies

- [Epic 2: Storage & Indexing](epic-02.md) - Encryption and retention integration

## Related Epics

- [Epic 4: Website & UX](epic-04.md) - RBAC and audit logging UI
- [Epic 1: Logging Ingestion & Transport](epic-01.md) - Redaction pipeline integration

