# PostgreSQL: Backend and server-side security

Stack-specific implementation for **PostgreSQL** (Database). Normative rules: domain skill `security-backend-server` / `reference.md`.

## Injection (SQL, NoSQL, command, LDAP, template)

**Sub-topics:** SQL injection, ORM raw queries, Shell invocation, Server-side template injection, XPath and LDAP

### Do (use this in PostgreSQL)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Server-side authorization

**Sub-topics:** RBAC, ABAC, Object-level checks, Admin routes, Threat modeling and trust boundaries (Server-side authorization)

### Do (use this in PostgreSQL)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

