# SwiftUI (iOS): Backend and server-side security

Stack-specific implementation for **SwiftUI (iOS)** (Mobile). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Do (use this in SwiftUI (iOS))

- Use parameterized queries or ORM equivalents for every database call.

### Don't

- Do not build SQL/command strings with user input.

### Verify

- Static analysis for injection sinks.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Do (use this in SwiftUI (iOS))

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Session management on server

**Sub-topics:** Session fixation, Rotation, Idle timeout, Concurrent sessions, Threat modeling and trust boundaries (Session management on server)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Error handling and information disclosure

**Sub-topics:** Stack traces, Debug endpoints, Verbose validation errors, Threat modeling and trust boundaries (Error handling and information disclosure), Abuse cases and adversarial testing (Error handling and information disclosure)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Concurrency and race conditions

**Sub-topics:** TOCTOU, Double spend, Inventory races, Threat modeling and trust boundaries (Concurrency and race conditions), Abuse cases and adversarial testing (Concurrency and race conditions)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Server file I/O

**Sub-topics:** Path traversal, Zip slip, Symlinks, Temp files, Threat modeling and trust boundaries (Server file I/O)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Deserialization and parsing

**Sub-topics:** JSON bombs, XML external entities, YAML unsafe load, Threat modeling and trust boundaries (Deserialization and parsing), Abuse cases and adversarial testing (Deserialization and parsing)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Background jobs and queues

**Sub-topics:** Job injection, Privilege of workers, Retry storms, Threat modeling and trust boundaries (Background jobs and queues), Abuse cases and adversarial testing (Background jobs and queues)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Server-side caching

**Sub-topics:** Cache key injection, Sensitive data in cache, Threat modeling and trust boundaries (Server-side caching), Abuse cases and adversarial testing (Server-side caching), Logging, audit, and detection (Server-side caching)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Tenant isolation on server

**Sub-topics:** Row-level security, Shared schema leaks, Threat modeling and trust boundaries (Tenant isolation on server), Abuse cases and adversarial testing (Tenant isolation on server), Logging, audit, and detection (Tenant isolation on server)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Rate limiting and abuse

**Sub-topics:** Brute force, Scraping, Account enumeration, Threat modeling and trust boundaries (Rate limiting and abuse), Abuse cases and adversarial testing (Rate limiting and abuse)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Health and debug endpoints

**Sub-topics:** /metrics exposure, Actuator, phpinfo equivalents, Threat modeling and trust boundaries (Health and debug endpoints), Abuse cases and adversarial testing (Health and debug endpoints)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

