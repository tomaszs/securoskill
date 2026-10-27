# Vercel: Serverless, edge, and FaaS security

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in Vercel)

- Use Vercel env vars for secrets; server-only in Route Handlers and Server Actions.

### Don't

- Do not prefix secrets with `NEXT_PUBLIC_`.
- Do not commit `.env` to git.

### Verify

- Build fails if client bundle contains `sk-` patterns (secret scan).

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in Vercel)

- Use Vercel env vars for secrets; server-only in Route Handlers and Server Actions.

### Don't

- Do not prefix secrets with `NEXT_PUBLIC_`.
- Do not commit `.env` to git.

### Verify

- Build fails if client bundle contains `sk-` patterns (secret scan).

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in Vercel)

- Use Vercel env vars for secrets; server-only in Route Handlers and Server Actions.

### Don't

- Do not prefix secrets with `NEXT_PUBLIC_`.
- Do not commit `.env` to git.

### Verify

- Build fails if client bundle contains `sk-` patterns (secret scan).

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_network controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in Vercel)

- Use Vercel env vars for secrets; server-only in Route Handlers and Server Actions.

### Don't

- Do not prefix secrets with `NEXT_PUBLIC_`.
- Do not commit `.env` to git.

### Verify

- Build fails if client bundle contains `sk-` patterns (secret scan).

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_cost controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_idempotency controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_dev controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_multi_region controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for wasm_edge controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for orchestration controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in Vercel)

- Apply domain skill `security-serverless-edge` requirements using vercel supported APIs only.
- Use the official vercel security documentation for faas_limits controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vercel for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vercel projects in CI.

