# Docker: Serverless, edge, and FaaS security

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in Docker)

- Apply domain skill `security-serverless-edge` requirements using docker supported APIs only.
- Use the official docker security documentation for faas_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of docker for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on docker projects in CI.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in Docker)

- Apply domain skill `security-serverless-edge` requirements using docker supported APIs only.
- Use the official docker security documentation for faas_events controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of docker for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on docker projects in CI.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in Docker)

- Apply domain skill `security-serverless-edge` requirements using docker supported APIs only.
- Use the official docker security documentation for faas_secrets controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of docker for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on docker projects in CI.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in Docker)

- Apply domain skill `security-serverless-edge` requirements using docker supported APIs only.
- Use the official docker security documentation for edge_workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of docker for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on docker projects in CI.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

