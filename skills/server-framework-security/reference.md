# Rules reference: Server framework and runtime security

Node, Python, Java, .NET, Go, PHP, and Ruby stacks.

## Node.js and Express

Sub-topics: Prototype pollution, Middleware order, JSON body limits, Cluster creds, vm module

### Policy

- Treat Node.js and Express in Node.js and Express as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Node.js and Express (Server framework and runtime security).
- Require security review for material changes affecting Node.js and Express.

### Design

- Apply least privilege and defense in depth for Node.js and Express.
- Prefer established patterns and libraries over custom crypto or auth for Node.js and Express.
- Fail closed: deny by default when Node.js and Express cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Node.js and Express; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Node.js and Express.
- Keep dependencies patched; pin versions for Node.js and Express components.

### Verification

- Add automated tests and SAST/DAST coverage for Node.js and Express paths.
- Run dependency and secret scanning on every change touching Node.js and Express.
- Perform targeted manual tests (abuse cases) for Node.js and Express.

### Operations

- Log security-relevant events for Node.js and Express without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Node.js and Express.
- Review access and configuration for Node.js and Express on a regular cadence.

## NestJS and Fastify

Sub-topics: Guards vs pipes, Validation decorators, GraphQL plugins, Microservices TCP, Swagger exposure

### Policy

- Treat NestJS and Fastify in NestJS and Fastify as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for NestJS and Fastify (Server framework and runtime security).
- Require security review for material changes affecting NestJS and Fastify.

### Design

- Apply least privilege and defense in depth for NestJS and Fastify.
- Prefer established patterns and libraries over custom crypto or auth for NestJS and Fastify.
- Fail closed: deny by default when NestJS and Fastify cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching NestJS and Fastify; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to NestJS and Fastify.
- Keep dependencies patched; pin versions for NestJS and Fastify components.

### Verification

- Add automated tests and SAST/DAST coverage for NestJS and Fastify paths.
- Run dependency and secret scanning on every change touching NestJS and Fastify.
- Perform targeted manual tests (abuse cases) for NestJS and Fastify.

### Operations

- Log security-relevant events for NestJS and Fastify without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in NestJS and Fastify.
- Review access and configuration for NestJS and Fastify on a regular cadence.

## Django and Flask

Sub-topics: DEBUG=True, SECRET_KEY rotation, ORM extra(), Jinja autoescape, Admin URL

### Policy

- Treat Django and Flask in Django and Flask as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Django and Flask (Server framework and runtime security).
- Require security review for material changes affecting Django and Flask.

### Design

- Apply least privilege and defense in depth for Django and Flask.
- Prefer established patterns and libraries over custom crypto or auth for Django and Flask.
- Fail closed: deny by default when Django and Flask cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Django and Flask; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Django and Flask.
- Keep dependencies patched; pin versions for Django and Flask components.

### Verification

- Add automated tests and SAST/DAST coverage for Django and Flask paths.
- Run dependency and secret scanning on every change touching Django and Flask.
- Perform targeted manual tests (abuse cases) for Django and Flask.

### Operations

- Log security-relevant events for Django and Flask without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Django and Flask.
- Review access and configuration for Django and Flask on a regular cadence.

## FastAPI and Starlette

Sub-topics: Dependency injection auth, OpenAPI public, Background tasks, Pydantic coercion, WebSocket routes

### Policy

- Treat FastAPI and Starlette in FastAPI and Starlette as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for FastAPI and Starlette (Server framework and runtime security).
- Require security review for material changes affecting FastAPI and Starlette.

### Design

- Apply least privilege and defense in depth for FastAPI and Starlette.
- Prefer established patterns and libraries over custom crypto or auth for FastAPI and Starlette.
- Fail closed: deny by default when FastAPI and Starlette cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching FastAPI and Starlette; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to FastAPI and Starlette.
- Keep dependencies patched; pin versions for FastAPI and Starlette components.

### Verification

- Add automated tests and SAST/DAST coverage for FastAPI and Starlette paths.
- Run dependency and secret scanning on every change touching FastAPI and Starlette.
- Perform targeted manual tests (abuse cases) for FastAPI and Starlette.

### Operations

- Log security-relevant events for FastAPI and Starlette without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in FastAPI and Starlette.
- Review access and configuration for FastAPI and Starlette on a regular cadence.

## Spring Boot and Java

Sub-topics: Actuator endpoints, SpEL injection, Deserialization, JPA injection, Shiro defaults

### Policy

- Treat Spring Boot and Java in Spring Boot and Java as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Spring Boot and Java (Server framework and runtime security).
- Require security review for material changes affecting Spring Boot and Java.

### Design

- Apply least privilege and defense in depth for Spring Boot and Java.
- Prefer established patterns and libraries over custom crypto or auth for Spring Boot and Java.
- Fail closed: deny by default when Spring Boot and Java cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Spring Boot and Java; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Spring Boot and Java.
- Keep dependencies patched; pin versions for Spring Boot and Java components.

### Verification

- Add automated tests and SAST/DAST coverage for Spring Boot and Java paths.
- Run dependency and secret scanning on every change touching Spring Boot and Java.
- Perform targeted manual tests (abuse cases) for Spring Boot and Java.

### Operations

- Log security-relevant events for Spring Boot and Java without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Spring Boot and Java.
- Review access and configuration for Spring Boot and Java on a regular cadence.

## ASP.NET Core

Sub-topics: Mass assignment, DataProtection keys, Kestrel limits, Blazor Server state, Minimal APIs auth

### Policy

- Treat ASP.NET Core in ASP.NET Core as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for ASP.NET Core (Server framework and runtime security).
- Require security review for material changes affecting ASP.NET Core.

### Design

- Apply least privilege and defense in depth for ASP.NET Core.
- Prefer established patterns and libraries over custom crypto or auth for ASP.NET Core.
- Fail closed: deny by default when ASP.NET Core cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching ASP.NET Core; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to ASP.NET Core.
- Keep dependencies patched; pin versions for ASP.NET Core components.

### Verification

- Add automated tests and SAST/DAST coverage for ASP.NET Core paths.
- Run dependency and secret scanning on every change touching ASP.NET Core.
- Perform targeted manual tests (abuse cases) for ASP.NET Core.

### Operations

- Log security-relevant events for ASP.NET Core without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in ASP.NET Core.
- Review access and configuration for ASP.NET Core on a regular cadence.

## Ruby on Rails and Laravel

Sub-topics: Strong params, Mass assignment, Blade unescaped, Queue workers, Debug bar prod

### Policy

- Treat Ruby on Rails and Laravel in Ruby on Rails and Laravel as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Ruby on Rails and Laravel (Server framework and runtime security).
- Require security review for material changes affecting Ruby on Rails and Laravel.

### Design

- Apply least privilege and defense in depth for Ruby on Rails and Laravel.
- Prefer established patterns and libraries over custom crypto or auth for Ruby on Rails and Laravel.
- Fail closed: deny by default when Ruby on Rails and Laravel cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Ruby on Rails and Laravel; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Ruby on Rails and Laravel.
- Keep dependencies patched; pin versions for Ruby on Rails and Laravel components.

### Verification

- Add automated tests and SAST/DAST coverage for Ruby on Rails and Laravel paths.
- Run dependency and secret scanning on every change touching Ruby on Rails and Laravel.
- Perform targeted manual tests (abuse cases) for Ruby on Rails and Laravel.

### Operations

- Log security-relevant events for Ruby on Rails and Laravel without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Ruby on Rails and Laravel.
- Review access and configuration for Ruby on Rails and Laravel on a regular cadence.

## Go net/http and Gin

Sub-topics: Handler auth middleware, Template html/template, Race in handlers, pprof exposure, JWT libraries

### Policy

- Treat Go net/http and Gin in Go net/http and Gin as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Go net/http and Gin (Server framework and runtime security).
- Require security review for material changes affecting Go net/http and Gin.

### Design

- Apply least privilege and defense in depth for Go net/http and Gin.
- Prefer established patterns and libraries over custom crypto or auth for Go net/http and Gin.
- Fail closed: deny by default when Go net/http and Gin cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Go net/http and Gin; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Go net/http and Gin.
- Keep dependencies patched; pin versions for Go net/http and Gin components.

### Verification

- Add automated tests and SAST/DAST coverage for Go net/http and Gin paths.
- Run dependency and secret scanning on every change touching Go net/http and Gin.
- Perform targeted manual tests (abuse cases) for Go net/http and Gin.

### Operations

- Log security-relevant events for Go net/http and Gin without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Go net/http and Gin.
- Review access and configuration for Go net/http and Gin on a regular cadence.

## Rust web stacks

Sub-topics: unsafe blocks, SQLx literals, Tokio spawn abuse, Serde untagged, Cargo audit

### Policy

- Treat Rust web stacks in Rust web stacks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Rust web stacks (Server framework and runtime security).
- Require security review for material changes affecting Rust web stacks.

### Design

- Apply least privilege and defense in depth for Rust web stacks.
- Prefer established patterns and libraries over custom crypto or auth for Rust web stacks.
- Fail closed: deny by default when Rust web stacks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Rust web stacks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Rust web stacks.
- Keep dependencies patched; pin versions for Rust web stacks components.

### Verification

- Add automated tests and SAST/DAST coverage for Rust web stacks paths.
- Run dependency and secret scanning on every change touching Rust web stacks.
- Perform targeted manual tests (abuse cases) for Rust web stacks.

### Operations

- Log security-relevant events for Rust web stacks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Rust web stacks.
- Review access and configuration for Rust web stacks on a regular cadence.

## PHP and WordPress class apps

Sub-topics: include paths, unserialize, upload dirs, wp-admin hardening, Composer vendors

### Policy

- Treat PHP and WordPress class apps in PHP and WordPress class apps as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PHP and WordPress class apps (Server framework and runtime security).
- Require security review for material changes affecting PHP and WordPress class apps.

### Design

- Apply least privilege and defense in depth for PHP and WordPress class apps.
- Prefer established patterns and libraries over custom crypto or auth for PHP and WordPress class apps.
- Fail closed: deny by default when PHP and WordPress class apps cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PHP and WordPress class apps; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PHP and WordPress class apps.
- Keep dependencies patched; pin versions for PHP and WordPress class apps components.

### Verification

- Add automated tests and SAST/DAST coverage for PHP and WordPress class apps paths.
- Run dependency and secret scanning on every change touching PHP and WordPress class apps.
- Perform targeted manual tests (abuse cases) for PHP and WordPress class apps.

### Operations

- Log security-relevant events for PHP and WordPress class apps without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PHP and WordPress class apps.
- Review access and configuration for PHP and WordPress class apps on a regular cadence.

## GraphQL server frameworks

Sub-topics: Resolver authz, DataLoader leaks, Introspection prod, Query cost, Subscriptions

### Policy

- Treat GraphQL server frameworks in GraphQL server frameworks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for GraphQL server frameworks (Server framework and runtime security).
- Require security review for material changes affecting GraphQL server frameworks.

### Design

- Apply least privilege and defense in depth for GraphQL server frameworks.
- Prefer established patterns and libraries over custom crypto or auth for GraphQL server frameworks.
- Fail closed: deny by default when GraphQL server frameworks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching GraphQL server frameworks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to GraphQL server frameworks.
- Keep dependencies patched; pin versions for GraphQL server frameworks components.

### Verification

- Add automated tests and SAST/DAST coverage for GraphQL server frameworks paths.
- Run dependency and secret scanning on every change touching GraphQL server frameworks.
- Perform targeted manual tests (abuse cases) for GraphQL server frameworks.

### Operations

- Log security-relevant events for GraphQL server frameworks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in GraphQL server frameworks.
- Review access and configuration for GraphQL server frameworks on a regular cadence.

## Serverless framework adapters

Sub-topics: Chalice, Serverless.yml secrets, SAM templates, Cold start IAM, Local invoke creds

### Policy

- Treat Serverless framework adapters in Serverless framework adapters as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Serverless framework adapters (Server framework and runtime security).
- Require security review for material changes affecting Serverless framework adapters.

### Design

- Apply least privilege and defense in depth for Serverless framework adapters.
- Prefer established patterns and libraries over custom crypto or auth for Serverless framework adapters.
- Fail closed: deny by default when Serverless framework adapters cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Serverless framework adapters; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Serverless framework adapters.
- Keep dependencies patched; pin versions for Serverless framework adapters components.

### Verification

- Add automated tests and SAST/DAST coverage for Serverless framework adapters paths.
- Run dependency and secret scanning on every change touching Serverless framework adapters.
- Perform targeted manual tests (abuse cases) for Serverless framework adapters.

### Operations

- Log security-relevant events for Serverless framework adapters without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Serverless framework adapters.
- Review access and configuration for Serverless framework adapters on a regular cadence.

