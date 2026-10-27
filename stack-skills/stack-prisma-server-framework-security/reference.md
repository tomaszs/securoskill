# Prisma: Server framework and runtime security

Stack-specific implementation for **Prisma** (ORM / data access). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in Prisma)

- Use Prisma Client query API for all CRUD.
- Use `$queryRaw` only with `Prisma.sql` tagged template and bound parameters.

### Don't

- Do not use `$queryRawUnsafe` or string-built SQL with user input.
- Do not pass unvalidated sort field names into `orderBy` without allowlist.

### Verify

- Code search in CI for `$queryRawUnsafe` and `executeRaw`.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in Prisma)

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

### Do (use this in Prisma)

- Prisma is not the primary enforcement point for `server-framework-security`; load stack skill `security-server-framework-security` when you touch that layer.
- Keep Prisma configuration aligned with requirements from `security-server-framework-security` (domain reference.md).

### Don't

- Do not duplicate `server-framework-security` controls only in Prisma config while leaving security-server-framework-security misconfigured.
- Do not assume Prisma defaults satisfy `security-server-framework-security` without verification.

### Verify

- Integration test the full path: Prisma plus the system covered by `security-server-framework-security`.

