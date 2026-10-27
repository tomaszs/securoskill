# MongoDB: Backend and server-side security

Stack-specific implementation for **MongoDB** (Database). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Do (use this in MongoDB)

- Use typed filters with BSON builders; validate ObjectId strings before queries.

### Don't

- Do not use `$where` with JavaScript from user input.
- Do not pass raw user objects into query operators without schema validation.

### Verify

- Test NoSQL injection payloads on REST filters.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Session management on server

**Sub-topics:** Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Error handling and information disclosure

**Sub-topics:** Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Concurrency and race conditions

**Sub-topics:** TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Server file I/O

**Sub-topics:** Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Deserialization and parsing

**Sub-topics:** JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Background jobs and queues

**Sub-topics:** Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Server-side caching

**Sub-topics:** Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Tenant isolation on server

**Sub-topics:** Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Rate limiting and abuse

**Sub-topics:** Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

## Health and debug endpoints

**Sub-topics:** /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `backend-server`; load stack skill `stack-express-backend-server (or your API stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-backend-server` (domain reference.md).

### Don't

- Do not duplicate `backend-server` controls only in MongoDB config while leaving stack-express-backend-server (or your API stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-backend-server` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-express-backend-server (or your API stack)`.

