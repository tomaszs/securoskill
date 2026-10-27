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

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

