# TypeORM: Server framework and runtime security

Stack-specific implementation for **TypeORM** (ORM / data access). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in TypeORM)

- Use TypeORM repositories or Prisma Client; avoid string-built `query(` calls.
- Use `prisma.user.findUnique({ where: { id } })`; for raw SQL use `$queryRaw` with tagged templates.

### Don't

- Do not concatenate user input into SQL in `@Query()` strings.
- Do not expose `$queryRawUnsafe` / `executeRaw` with user strings.

### Verify

- eslint-plugin-security + integration tests on search/filter endpoints.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in TypeORM)

- Enforce max query depth and complexity limits.
- Disable introspection in production unless required for trusted tools.
- Authorize each resolver field (not only top-level entry).

### Don't

- Do not expose admin-only fields on the same schema without field-level auth.
- Do not allow batch aliases to bypass rate limits.

### Verify

- Load-test GraphQL with deeply nested queries; expect rejection.

