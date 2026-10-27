# Gin (Go): Server framework and runtime security

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Platform rules (summary)

- Validate and canonicalize all inputs touching Node.js and Express; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Node.js and Express.
- Keep dependencies patched; pin versions for Node.js and Express components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Node.js and Express before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Node.js and Express paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Platform rules (summary)

- Validate and canonicalize all inputs touching NestJS and Fastify; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NestJS and Fastify.
- Keep dependencies patched; pin versions for NestJS and Fastify components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for NestJS and Fastify before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for NestJS and Fastify paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Platform rules (summary)

- Validate and canonicalize all inputs touching Django and Flask; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Django and Flask.
- Keep dependencies patched; pin versions for Django and Flask components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Django and Flask before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Django and Flask paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Platform rules (summary)

- Validate and canonicalize all inputs touching FastAPI and Starlette; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to FastAPI and Starlette.
- Keep dependencies patched; pin versions for FastAPI and Starlette components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for FastAPI and Starlette before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for FastAPI and Starlette paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Platform rules (summary)

- Validate and canonicalize all inputs touching Spring Boot and Java; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Spring Boot and Java.
- Keep dependencies patched; pin versions for Spring Boot and Java components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Spring Boot and Java before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Spring Boot and Java paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Platform rules (summary)

- Validate and canonicalize all inputs touching ASP.NET Core; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ASP.NET Core.
- Keep dependencies patched; pin versions for ASP.NET Core components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for ASP.NET Core before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for ASP.NET Core paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Platform rules (summary)

- Validate and canonicalize all inputs touching Ruby on Rails and Laravel; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Ruby on Rails and Laravel.
- Keep dependencies patched; pin versions for Ruby on Rails and Laravel components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Ruby on Rails and Laravel before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Ruby on Rails and Laravel paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Platform rules (summary)

- Validate and canonicalize all inputs touching Go net/http and Gin; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Go net/http and Gin.
- Keep dependencies patched; pin versions for Go net/http and Gin components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Go net/http and Gin before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Go net/http and Gin paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Platform rules (summary)

- Validate and canonicalize all inputs touching Rust web stacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Rust web stacks.
- Keep dependencies patched; pin versions for Rust web stacks components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Rust web stacks before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Rust web stacks paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Platform rules (summary)

- Validate and canonicalize all inputs touching PHP and WordPress class apps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PHP and WordPress class apps.
- Keep dependencies patched; pin versions for PHP and WordPress class apps components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PHP and WordPress class apps before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PHP and WordPress class apps paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Platform rules (summary)

- Validate and canonicalize all inputs touching GraphQL server frameworks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to GraphQL server frameworks.
- Keep dependencies patched; pin versions for GraphQL server frameworks components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for GraphQL server frameworks before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for GraphQL server frameworks paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Serverless framework adapters

**Sub-topics:** Chalice, Serverless.yml secrets, SAM templates, Cold start IAM, Local invoke creds

### Platform rules (summary)

- Validate and canonicalize all inputs touching Serverless framework adapters; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Serverless framework adapters.
- Keep dependencies patched; pin versions for Serverless framework adapters components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-server-framework-security` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Serverless framework adapters before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Serverless framework adapters paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

