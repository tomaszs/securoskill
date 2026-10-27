# Ruby on Rails: Server framework and runtime security

Stack-specific implementation for **Ruby on Rails** (Ruby). Normative rules: domain skill `security-server-framework-security` / `reference.md`.

## Node.js and Express

**Sub-topics:** Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## NestJS and Fastify

**Sub-topics:** Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## Django and Flask

**Sub-topics:** DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## FastAPI and Starlette

**Sub-topics:** Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## Spring Boot and Java

**Sub-topics:** Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## ASP.NET Core

**Sub-topics:** Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## Ruby on Rails and Laravel

**Sub-topics:** Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## Go net/http and Gin

**Sub-topics:** Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## Rust web stacks

**Sub-topics:** unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## PHP and WordPress class apps

**Sub-topics:** include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Do (use this in Ruby on Rails)

- Use ActiveRecord: `User.where(email: params[:email])`.
- Use `where('email = ?', email)` for fragments.

### Don't

- Do not use `where("email = '#{params[:email]}'")`.
- Do not pass user input to `order()` without allowlist.

### Verify

- Brakeman in CI.

## GraphQL server frameworks

**Sub-topics:** Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Do (use this in Ruby on Rails)

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

### Do (use this in Ruby on Rails)

- Apply domain skill `security-server-framework-security` requirements using rails supported APIs only.
- Use the official rails security documentation for serverless controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of rails for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on rails projects in CI.

