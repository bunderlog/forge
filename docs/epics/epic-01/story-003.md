# Story: Build Go SDK for Log Shipping (3 points)

**Story ID:** EPIC-01-003  
**Epic:** [EPIC-01: Logging Ingestion & Transport](../epic-01.md)  
**Status:** Not Started  
**Priority:** High

## User Story

As a **Go developer**, I want a **native Go SDK** so that **I can easily integrate log shipping into my Go applications**.

## Description

Create a Go SDK that provides a simple interface for sending logs to the ingestion API with proper error handling and retry logic.

## Tasks

- [ ] Design SDK API interface (Logger, Client structs)
- [ ] Implement HTTP client with authentication
- [ ] Add automatic batching of log entries
- [ ] Implement retry logic with exponential backoff
- [ ] Add configuration options (endpoints, credentials, batch size)
- [ ] Create structured logging helpers
- [ ] Write comprehensive examples
- [ ] Add SDK documentation

## Acceptance Criteria

- [ ] SDK can send logs synchronously and asynchronously
- [ ] Automatic batching reduces network calls
- [ ] Retry logic handles transient failures
- [ ] SDK integrates with popular Go logging frameworks
- [ ] Configuration is flexible and well-documented
- [ ] Examples show common usage patterns

## Definition of Done

- [ ] SDK implemented and tested
- [ ] Unit tests pass (>85% coverage)
- [ ] Integration tests with ingestion API pass
- [ ] Examples are working and documented
- [ ] API documentation is complete
- [ ] Package is ready for distribution (go.mod, versioning)
