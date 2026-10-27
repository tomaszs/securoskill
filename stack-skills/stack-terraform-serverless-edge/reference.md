# Terraform: Serverless, edge, and FaaS security

Stack-specific implementation for **Terraform** (Infrastructure). Normative rules: domain skill `security-serverless-edge` / `reference.md`.

## Function authentication

**Sub-topics:** IAM roles, Function URLs, API Gateway authorizers, JWT at edge, Anonymous triggers

### Do (use this in Terraform)

- Apply domain skill `security-serverless-edge` requirements using terraform supported APIs only.
- Use the official terraform security documentation for faas_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of terraform for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on terraform projects in CI.

## Event source trust

**Sub-topics:** S3 notifications, SQS/SNS, EventBridge, Cron schedules, Webhook triggers

### Do (use this in Terraform)

- Apply domain skill `security-serverless-edge` requirements using terraform supported APIs only.
- Use the official terraform security documentation for faas_events controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of terraform for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on terraform projects in CI.

## Secrets in serverless

**Sub-topics:** Env vars, Parameter Store, KMS grants, Rotation, Leak in logs

### Do (use this in Terraform)

- Apply domain skill `security-serverless-edge` requirements using terraform supported APIs only.
- Use the official terraform security documentation for faas_secrets controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of terraform for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on terraform projects in CI.

## VPC and network placement

**Sub-topics:** NAT costs, Public subnets, Private API, Egress SSRF, Peering

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Edge workers (CDN)

**Sub-topics:** KV stores, Request rewriting, Cache poisoning, Geo routing, WAF at edge

### Do (use this in Terraform)

- Apply domain skill `security-serverless-edge` requirements using terraform supported APIs only.
- Use the official terraform security documentation for edge_workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of terraform for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on terraform projects in CI.

## Denial of wallet

**Sub-topics:** Unbounded invocations, Recursive triggers, Large payloads, Concurrency limits, Cost alerts

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Idempotency and retries

**Sub-topics:** Duplicate charges, Partial failures, DLQ handling, Poison messages, Exactly-once myths

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Local dev parity

**Sub-topics:** sam local, Serverless offline, Prod creds in dev, Shared stages, Debug endpoints

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Multi-region functions

**Sub-topics:** Replication lag, Regional secrets, Failover auth, Data sovereignty, Routing

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Wasm at edge

**Sub-topics:** Sandbox escapes, Memory limits, Module signing, Third-party modules, CPU time

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Orchestration workflows

**Sub-topics:** State injection, IAM chaining, Long-running abuse, Input size, Observability

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Platform limit abuse

**Sub-topics:** Timeout extension, Memory exhaustion, Tmp storage, Layer injection, Runtime deprecation

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

