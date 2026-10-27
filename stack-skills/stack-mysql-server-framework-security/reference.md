# MySQL / MariaDB: Server framework and runtime security

Stack-specific implementation for **MySQL / MariaDB** (Database). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in MySQL / MariaDB)

- Create app roles with least privilege (no SUPERUSER, no broad DDL).
- Force SSL for connections; use prepared statements from application drivers.

### Don't

- Do not use the superuser account in application connection strings.
- Do not grant `PUBLIC` access to sensitive schemas.

### Verify

- Periodic privilege review queries on role grants.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in MySQL / MariaDB)

- Enforce max query depth and complexity limits.
- Disable introspection in production unless required for trusted tools.
- Authorize each resolver field (not only top-level entry).

### Don't

- Do not expose admin-only fields on the same schema without field-level auth.
- Do not allow batch aliases to bypass rate limits.

### Verify

- Load-test GraphQL with deeply nested queries; expect rejection.

## Serverless framework adapters

**Sub-topics:** Chalice, Serverless.yml secrets, SAM templates, Cold start IAM, Local invoke creds

### Do (use this in MySQL / MariaDB)

- Apply domain skill `security-server-framework-security` requirements using mysql supported APIs only.
- Use the official mysql security documentation for serverless controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of mysql for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on mysql projects in CI.

