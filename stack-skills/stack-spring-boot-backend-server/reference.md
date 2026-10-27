# Spring Boot: Backend and server-side security

Stack-specific implementation for **Spring Boot** (Java). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Platform rules (summary)

- Validate and canonicalize all inputs touching Injection (SQL, NoSQL, command, LDAP, template); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Injection (SQL, NoSQL, command, LDAP, template).
- Keep dependencies patched; pin versions for Injection (SQL, NoSQL, command, LDAP, template) components.

### How to do this in Spring Boot

- Use Spring Data repositories or JPA named parameters; avoid concatenating HQL/SQL in Spring Boot.
- Use `PreparedStatement` with `?` or named params; disable dangerous SpEL in queries.
- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Injection (SQL, NoSQL, command, LDAP, template) before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Injection (SQL, NoSQL, command, LDAP, template) paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Server-side authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-side authorization.
- Keep dependencies patched; pin versions for Server-side authorization components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Server-side authorization before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Server-side authorization paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Session management on server

**Sub-topics:** Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Session management on server; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Session management on server.
- Keep dependencies patched; pin versions for Session management on server components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Session management on server before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Session management on server paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Error handling and information disclosure

**Sub-topics:** Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Error handling and information disclosure; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Error handling and information disclosure.
- Keep dependencies patched; pin versions for Error handling and information disclosure components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Error handling and information disclosure before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Error handling and information disclosure paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Concurrency and race conditions

**Sub-topics:** TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Concurrency and race conditions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Concurrency and race conditions.
- Keep dependencies patched; pin versions for Concurrency and race conditions components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Concurrency and race conditions before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Concurrency and race conditions paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Server file I/O

**Sub-topics:** Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Server file I/O; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server file I/O.
- Keep dependencies patched; pin versions for Server file I/O components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Server file I/O before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Server file I/O paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Deserialization and parsing

**Sub-topics:** JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Deserialization and parsing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deserialization and parsing.
- Keep dependencies patched; pin versions for Deserialization and parsing components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Deserialization and parsing before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Deserialization and parsing paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Background jobs and queues

**Sub-topics:** Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Background jobs and queues; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Background jobs and queues.
- Keep dependencies patched; pin versions for Background jobs and queues components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Background jobs and queues before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Background jobs and queues paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Server-side caching

**Sub-topics:** Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Server-side caching; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-side caching.
- Keep dependencies patched; pin versions for Server-side caching components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Server-side caching before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Server-side caching paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Tenant isolation on server

**Sub-topics:** Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tenant isolation on server; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant isolation on server.
- Keep dependencies patched; pin versions for Tenant isolation on server components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tenant isolation on server before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tenant isolation on server paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Rate limiting and abuse

**Sub-topics:** Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Rate limiting and abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Rate limiting and abuse.
- Keep dependencies patched; pin versions for Rate limiting and abuse components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Rate limiting and abuse before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Rate limiting and abuse paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

## Health and debug endpoints

**Sub-topics:** /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Health and debug endpoints; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Health and debug endpoints.
- Keep dependencies patched; pin versions for Health and debug endpoints components.

### How to do this in Spring Boot

- Read normative rules in domain skill `security-backend-server` / `reference.md`, then apply them using Spring Boot APIs and deployment model.
- Prefer framework-maintained security features in Spring Boot over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Health and debug endpoints before merge.
- Pin Spring Boot dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Health and debug endpoints paths in Spring Boot.
- Run SAST/dependency scan configured for Java.

