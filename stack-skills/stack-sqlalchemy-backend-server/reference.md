# SQLAlchemy: Backend and server-side security

Stack-specific implementation for **SQLAlchemy** (ORM / data access). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Do (use this in SQLAlchemy)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run bandit on changes affecting `Server-side authorization`.

## Session management on server

**Sub-topics:** Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Do (use this in SQLAlchemy)

- Map `Session management on server` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Session management on server` before merge.

### Don't

- Do not ship `Session management on server` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Session management on server`.

### Verify

- Peer review `Session management on server` against domain skill `security-backend-server`.

## Error handling and information disclosure

**Sub-topics:** Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Do (use this in SQLAlchemy)

- Map `Error handling and information disclosure` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Error handling and information disclosure` before merge.

### Don't

- Do not ship `Error handling and information disclosure` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Error handling and information disclosure`.

### Verify

- Peer review `Error handling and information disclosure` against domain skill `security-backend-server`.

## Concurrency and race conditions

**Sub-topics:** TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Do (use this in SQLAlchemy)

- Map `Concurrency and race conditions` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Concurrency and race conditions` before merge.

### Don't

- Do not ship `Concurrency and race conditions` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Concurrency and race conditions`.

### Verify

- Peer review `Concurrency and race conditions` against domain skill `security-backend-server`.

## Server file I/O

**Sub-topics:** Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Do (use this in SQLAlchemy)

- Map `Server file I/O` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Server file I/O` before merge.

### Don't

- Do not ship `Server file I/O` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Server file I/O`.

### Verify

- Peer review `Server file I/O` against domain skill `security-backend-server`.

## Deserialization and parsing

**Sub-topics:** JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Do (use this in SQLAlchemy)

- Map `Deserialization and parsing` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Deserialization and parsing` before merge.

### Don't

- Do not ship `Deserialization and parsing` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Deserialization and parsing`.

### Verify

- Peer review `Deserialization and parsing` against domain skill `security-backend-server`.

## Background jobs and queues

**Sub-topics:** Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Do (use this in SQLAlchemy)

- Map `Background jobs and queues` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Background jobs and queues` before merge.

### Don't

- Do not ship `Background jobs and queues` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Background jobs and queues`.

### Verify

- Peer review `Background jobs and queues` against domain skill `security-backend-server`.

## Server-side caching

**Sub-topics:** Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Do (use this in SQLAlchemy)

- Map `Server-side caching` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Server-side caching` before merge.

### Don't

- Do not ship `Server-side caching` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Server-side caching`.

### Verify

- Peer review `Server-side caching` against domain skill `security-backend-server`.

## Tenant isolation on server

**Sub-topics:** Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Do (use this in SQLAlchemy)

- Map `Tenant isolation on server` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Tenant isolation on server` before merge.

### Don't

- Do not ship `Tenant isolation on server` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Tenant isolation on server`.

### Verify

- Peer review `Tenant isolation on server` against domain skill `security-backend-server`.

## Rate limiting and abuse

**Sub-topics:** Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Do (use this in SQLAlchemy)

- Map `Rate limiting and abuse` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Rate limiting and abuse` before merge.

### Don't

- Do not ship `Rate limiting and abuse` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Rate limiting and abuse`.

### Verify

- Peer review `Rate limiting and abuse` against domain skill `security-backend-server`.

## Health and debug endpoints

**Sub-topics:** /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Do (use this in SQLAlchemy)

- Map `Health and debug endpoints` controls to SQLAlchemy APIs documented for `security-backend-server`.
- Add an abuse-case test or check for `Health and debug endpoints` before merge.

### Don't

- Do not ship `Health and debug endpoints` work in SQLAlchemy with only happy-path tests.
- Do not disable SQLAlchemy security defaults to unblock `Health and debug endpoints`.

### Verify

- Peer review `Health and debug endpoints` against domain skill `security-backend-server`.

