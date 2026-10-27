# ASP.NET Core: Backend and server-side security

Stack-specific implementation for **ASP.NET Core** (.NET). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Do (use this in ASP.NET Core)

- Use EF Core LINQ; parameters are automatic.
- Use `FromSqlInterpolated` only when necessary; prefer LINQ.
- Use Dapper with anonymous objects for parameters.

### Don't

- Do not use `FromSqlRaw` with string concatenation from request data.
- Do not build dynamic SQL for column names without allowlists.

### Verify

- Roslyn analyzers + integration tests on filter APIs.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Do (use this in ASP.NET Core)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Session management on server

**Sub-topics:** Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for sessions controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Error handling and information disclosure

**Sub-topics:** Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for error_disclosure controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Concurrency and race conditions

**Sub-topics:** TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for concurrency controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Server file I/O

**Sub-topics:** Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for path_traversal controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Deserialization and parsing

**Sub-topics:** JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for deserialization controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Background jobs and queues

**Sub-topics:** Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for jobs controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Server-side caching

**Sub-topics:** Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for cache controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Tenant isolation on server

**Sub-topics:** Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for multi_tenant controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Rate limiting and abuse

**Sub-topics:** Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for rate_limit controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

## Health and debug endpoints

**Sub-topics:** /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Do (use this in ASP.NET Core)

- Apply domain skill `security-backend-server` requirements using aspnet-core supported APIs only.
- Use the official aspnet-core security documentation for debug_endpoints controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of aspnet-core for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on aspnet-core projects in CI.

