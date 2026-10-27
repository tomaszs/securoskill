# Rules reference: Backend and server-side security

Application servers, business logic, and server runtime.

## Injection (SQL, NoSQL, command, LDAP, template)

Sub-topics: SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Policy

- Treat Injection (SQL, NoSQL, command, LDAP, template) in Injection (SQL, NoSQL, command, LDAP, template) as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Injection (SQL, NoSQL, command, LDAP, template) (Backend and server-side security).
- Require security review for material changes affecting Injection (SQL, NoSQL, command, LDAP, template).

### Design

- Apply least privilege and defense in depth for Injection (SQL, NoSQL, command, LDAP, template).
- Prefer established patterns and libraries over custom crypto or auth for Injection (SQL, NoSQL, command, LDAP, template).
- Fail closed: deny by default when Injection (SQL, NoSQL, command, LDAP, template) cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Injection (SQL, NoSQL, command, LDAP, template); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Injection (SQL, NoSQL, command, LDAP, template).
- Keep dependencies patched; pin versions for Injection (SQL, NoSQL, command, LDAP, template) components.
- Use parameterized queries and ORM bindings exclusively for SQL.
- Never pass user input to exec, eval, or shell interpreters.

### Verification

- Add automated tests and SAST/DAST coverage for Injection (SQL, NoSQL, command, LDAP, template) paths.
- Run dependency and secret scanning on every change touching Injection (SQL, NoSQL, command, LDAP, template).
- Perform targeted manual tests (abuse cases) for Injection (SQL, NoSQL, command, LDAP, template).

### Operations

- Log security-relevant events for Injection (SQL, NoSQL, command, LDAP, template) without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Injection (SQL, NoSQL, command, LDAP, template).
- Review access and configuration for Injection (SQL, NoSQL, command, LDAP, template) on a regular cadence.

## Server-side authorization

Sub-topics: RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Policy

- Treat Server-side authorization in Server-side authorization as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Server-side authorization (Backend and server-side security).
- Require security review for material changes affecting Server-side authorization.

### Design

- Apply least privilege and defense in depth for Server-side authorization.
- Prefer established patterns and libraries over custom crypto or auth for Server-side authorization.
- Fail closed: deny by default when Server-side authorization cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Server-side authorization; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-side authorization.
- Keep dependencies patched; pin versions for Server-side authorization components.

### Verification

- Add automated tests and SAST/DAST coverage for Server-side authorization paths.
- Run dependency and secret scanning on every change touching Server-side authorization.
- Perform targeted manual tests (abuse cases) for Server-side authorization.

### Operations

- Log security-relevant events for Server-side authorization without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Server-side authorization.
- Review access and configuration for Server-side authorization on a regular cadence.

## Session management on server

Sub-topics: Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Policy

- Treat Session management on server in Session management on server as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Session management on server (Backend and server-side security).
- Require security review for material changes affecting Session management on server.

### Design

- Apply least privilege and defense in depth for Session management on server.
- Prefer established patterns and libraries over custom crypto or auth for Session management on server.
- Fail closed: deny by default when Session management on server cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Session management on server; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Session management on server.
- Keep dependencies patched; pin versions for Session management on server components.

### Verification

- Add automated tests and SAST/DAST coverage for Session management on server paths.
- Run dependency and secret scanning on every change touching Session management on server.
- Perform targeted manual tests (abuse cases) for Session management on server.

### Operations

- Log security-relevant events for Session management on server without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Session management on server.
- Review access and configuration for Session management on server on a regular cadence.

## Error handling and information disclosure

Sub-topics: Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Policy

- Treat Error handling and information disclosure in Error handling and information disclosure as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Error handling and information disclosure (Backend and server-side security).
- Require security review for material changes affecting Error handling and information disclosure.

### Design

- Apply least privilege and defense in depth for Error handling and information disclosure.
- Prefer established patterns and libraries over custom crypto or auth for Error handling and information disclosure.
- Fail closed: deny by default when Error handling and information disclosure cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Error handling and information disclosure; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Error handling and information disclosure.
- Keep dependencies patched; pin versions for Error handling and information disclosure components.

### Verification

- Add automated tests and SAST/DAST coverage for Error handling and information disclosure paths.
- Run dependency and secret scanning on every change touching Error handling and information disclosure.
- Perform targeted manual tests (abuse cases) for Error handling and information disclosure.

### Operations

- Log security-relevant events for Error handling and information disclosure without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Error handling and information disclosure.
- Review access and configuration for Error handling and information disclosure on a regular cadence.

## Concurrency and race conditions

Sub-topics: TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Policy

- Treat Concurrency and race conditions in Concurrency and race conditions as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Concurrency and race conditions (Backend and server-side security).
- Require security review for material changes affecting Concurrency and race conditions.

### Design

- Apply least privilege and defense in depth for Concurrency and race conditions.
- Prefer established patterns and libraries over custom crypto or auth for Concurrency and race conditions.
- Fail closed: deny by default when Concurrency and race conditions cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Concurrency and race conditions; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Concurrency and race conditions.
- Keep dependencies patched; pin versions for Concurrency and race conditions components.

### Verification

- Add automated tests and SAST/DAST coverage for Concurrency and race conditions paths.
- Run dependency and secret scanning on every change touching Concurrency and race conditions.
- Perform targeted manual tests (abuse cases) for Concurrency and race conditions.

### Operations

- Log security-relevant events for Concurrency and race conditions without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Concurrency and race conditions.
- Review access and configuration for Concurrency and race conditions on a regular cadence.

## Server file I/O

Sub-topics: Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Policy

- Treat Server file I/O in Server file I/O as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Server file I/O (Backend and server-side security).
- Require security review for material changes affecting Server file I/O.

### Design

- Apply least privilege and defense in depth for Server file I/O.
- Prefer established patterns and libraries over custom crypto or auth for Server file I/O.
- Fail closed: deny by default when Server file I/O cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Server file I/O; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server file I/O.
- Keep dependencies patched; pin versions for Server file I/O components.

### Verification

- Add automated tests and SAST/DAST coverage for Server file I/O paths.
- Run dependency and secret scanning on every change touching Server file I/O.
- Perform targeted manual tests (abuse cases) for Server file I/O.

### Operations

- Log security-relevant events for Server file I/O without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Server file I/O.
- Review access and configuration for Server file I/O on a regular cadence.

## Deserialization and parsing

Sub-topics: JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Policy

- Treat Deserialization and parsing in Deserialization and parsing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Deserialization and parsing (Backend and server-side security).
- Require security review for material changes affecting Deserialization and parsing.

### Design

- Apply least privilege and defense in depth for Deserialization and parsing.
- Prefer established patterns and libraries over custom crypto or auth for Deserialization and parsing.
- Fail closed: deny by default when Deserialization and parsing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Deserialization and parsing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deserialization and parsing.
- Keep dependencies patched; pin versions for Deserialization and parsing components.

### Verification

- Add automated tests and SAST/DAST coverage for Deserialization and parsing paths.
- Run dependency and secret scanning on every change touching Deserialization and parsing.
- Perform targeted manual tests (abuse cases) for Deserialization and parsing.

### Operations

- Log security-relevant events for Deserialization and parsing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Deserialization and parsing.
- Review access and configuration for Deserialization and parsing on a regular cadence.

## Background jobs and queues

Sub-topics: Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Policy

- Treat Background jobs and queues in Background jobs and queues as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Background jobs and queues (Backend and server-side security).
- Require security review for material changes affecting Background jobs and queues.

### Design

- Apply least privilege and defense in depth for Background jobs and queues.
- Prefer established patterns and libraries over custom crypto or auth for Background jobs and queues.
- Fail closed: deny by default when Background jobs and queues cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Background jobs and queues; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Background jobs and queues.
- Keep dependencies patched; pin versions for Background jobs and queues components.

### Verification

- Add automated tests and SAST/DAST coverage for Background jobs and queues paths.
- Run dependency and secret scanning on every change touching Background jobs and queues.
- Perform targeted manual tests (abuse cases) for Background jobs and queues.

### Operations

- Log security-relevant events for Background jobs and queues without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Background jobs and queues.
- Review access and configuration for Background jobs and queues on a regular cadence.

## Server-side caching

Sub-topics: Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Policy

- Treat Server-side caching in Server-side caching as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Server-side caching (Backend and server-side security).
- Require security review for material changes affecting Server-side caching.

### Design

- Apply least privilege and defense in depth for Server-side caching.
- Prefer established patterns and libraries over custom crypto or auth for Server-side caching.
- Fail closed: deny by default when Server-side caching cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Server-side caching; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Server-side caching.
- Keep dependencies patched; pin versions for Server-side caching components.

### Verification

- Add automated tests and SAST/DAST coverage for Server-side caching paths.
- Run dependency and secret scanning on every change touching Server-side caching.
- Perform targeted manual tests (abuse cases) for Server-side caching.

### Operations

- Log security-relevant events for Server-side caching without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Server-side caching.
- Review access and configuration for Server-side caching on a regular cadence.

## Tenant isolation on server

Sub-topics: Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Policy

- Treat Tenant isolation on server in Tenant isolation on server as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tenant isolation on server (Backend and server-side security).
- Require security review for material changes affecting Tenant isolation on server.

### Design

- Apply least privilege and defense in depth for Tenant isolation on server.
- Prefer established patterns and libraries over custom crypto or auth for Tenant isolation on server.
- Fail closed: deny by default when Tenant isolation on server cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tenant isolation on server; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tenant isolation on server.
- Keep dependencies patched; pin versions for Tenant isolation on server components.

### Verification

- Add automated tests and SAST/DAST coverage for Tenant isolation on server paths.
- Run dependency and secret scanning on every change touching Tenant isolation on server.
- Perform targeted manual tests (abuse cases) for Tenant isolation on server.

### Operations

- Log security-relevant events for Tenant isolation on server without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tenant isolation on server.
- Review access and configuration for Tenant isolation on server on a regular cadence.

## Rate limiting and abuse

Sub-topics: Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Policy

- Treat Rate limiting and abuse in Rate limiting and abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Rate limiting and abuse (Backend and server-side security).
- Require security review for material changes affecting Rate limiting and abuse.

### Design

- Apply least privilege and defense in depth for Rate limiting and abuse.
- Prefer established patterns and libraries over custom crypto or auth for Rate limiting and abuse.
- Fail closed: deny by default when Rate limiting and abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Rate limiting and abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Rate limiting and abuse.
- Keep dependencies patched; pin versions for Rate limiting and abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Rate limiting and abuse paths.
- Run dependency and secret scanning on every change touching Rate limiting and abuse.
- Perform targeted manual tests (abuse cases) for Rate limiting and abuse.

### Operations

- Log security-relevant events for Rate limiting and abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Rate limiting and abuse.
- Review access and configuration for Rate limiting and abuse on a regular cadence.

## Health and debug endpoints

Sub-topics: /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Policy

- Treat Health and debug endpoints in Health and debug endpoints as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Health and debug endpoints (Backend and server-side security).
- Require security review for material changes affecting Health and debug endpoints.

### Design

- Apply least privilege and defense in depth for Health and debug endpoints.
- Prefer established patterns and libraries over custom crypto or auth for Health and debug endpoints.
- Fail closed: deny by default when Health and debug endpoints cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Health and debug endpoints; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Health and debug endpoints.
- Keep dependencies patched; pin versions for Health and debug endpoints components.

### Verification

- Add automated tests and SAST/DAST coverage for Health and debug endpoints paths.
- Run dependency and secret scanning on every change touching Health and debug endpoints.
- Perform targeted manual tests (abuse cases) for Health and debug endpoints.

### Operations

- Log security-relevant events for Health and debug endpoints without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Health and debug endpoints.
- Review access and configuration for Health and debug endpoints on a regular cadence.

