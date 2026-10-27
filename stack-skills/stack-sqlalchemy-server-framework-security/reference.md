# SQLAlchemy: Server framework and runtime security

Stack-specific implementation for **SQLAlchemy** (ORM / data access). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in SQLAlchemy)

- Use SQLAlchemy 2.x `select()` with bound parameters: `session.execute(select(User).where(User.id == user_id))`.
- Use `text('... WHERE id = :id')` with `{'id': user_id}` mapping only.
- Validate IDs as UUID/int before queries.

### Don't

- Do not embed user input in f-string SQL passed to `text()`.
- Do not use string concatenation for dynamic `ORDER BY` column names without allowlists.

### Verify

- Semgrep `python.sqlalchemy.security` rules in CI.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in SQLAlchemy)

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

### Do (use this in SQLAlchemy)

- Apply domain skill `security-server-framework-security` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for serverless controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

