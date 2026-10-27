# SvelteKit: Serverless, edge, and FaaS security

Stack-specific implementation for **SvelteKit** (Web UI). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_events controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_secrets controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_network controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for edge_workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_cost controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_idempotency controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_dev controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_multi_region controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for wasm_edge controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for orchestration controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in SvelteKit)

- Apply domain skill `security-serverless-edge` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for faas_limits controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

