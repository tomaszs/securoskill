# Fastify: Server framework and runtime security

Stack-specific implementation for **Fastify** (Node.js server). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in Fastify)

- Use `pg` with bound parameters or `@fastify/postgres` with placeholders.
- Validate route params as typed scalars before passing to queries.

### Don't

- Do not embed `request.query` fields in SQL template literals.
- Do not use `eval` on database payloads.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in Fastify)

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

### Do (use this in Fastify)

- Map `Serverless framework adapters` controls to Fastify APIs documented for `security-server-framework-security`.
- Add an abuse-case test or check for `Serverless framework adapters` before merge.

### Don't

- Do not ship `Serverless framework adapters` work in Fastify with only happy-path tests.
- Do not disable Fastify security defaults to unblock `Serverless framework adapters`.

### Verify

- Peer review `Serverless framework adapters` against domain skill `security-server-framework-security`.

