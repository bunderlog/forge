# Story: Build Node.js SDK for Log Shipping (2 points)

**Story ID:** EPIC-01-004  
**Epic:** [EPIC-01: Logging Ingestion & Transport](../epic-01.md)  
**Status:** Not Started  
**Priority:** Medium

## User Story

As a **Node.js developer**, I want a **native Node.js SDK** so that **I can easily integrate log shipping into my JavaScript/TypeScript applications**.

## Description

Create a Node.js/TypeScript SDK that provides a simple interface for sending logs to the ingestion API with proper error handling and retry logic.

## Tasks

- [ ] Set up Node.js/TypeScript project structure
- [ ] Implement HTTP client using fetch/axios
- [ ] Add authentication handling
- [ ] Implement batching and retry logic
- [ ] Create TypeScript type definitions
- [ ] Add configuration management
- [ ] Write usage examples
- [ ] Create package documentation

## Acceptance Criteria

- [ ] SDK works with both JavaScript and TypeScript
- [ ] Supports async/await and callback patterns
- [ ] Integrates with popular Node.js logging libraries
- [ ] Handles network errors gracefully
- [ ] Configuration is environment-friendly
- [ ] Examples cover common use cases

## Definition of Done

- [ ] SDK implemented and tested
- [ ] Unit tests pass (>80% coverage)
- [ ] Integration tests pass
- [ ] TypeScript definitions are accurate
- [ ] Examples work and are documented
- [ ] NPM package is ready for publishing
