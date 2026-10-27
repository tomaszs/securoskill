# Docker: Multi-tenancy and SaaS isolation

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant identification

**Sub-topics:** Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Data isolation models

**Sub-topics:** Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Do (use this in Docker)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Billing and plan enforcement

**Sub-topics:** Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Custom domains and TLS

**Sub-topics:** Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Tenant export and backup

**Sub-topics:** Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Per-tenant integrations

**Sub-topics:** OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Noisy neighbor and quotas

**Sub-topics:** CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Tenant onboarding

**Sub-topics:** Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Tenant offboarding

**Sub-topics:** Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Compliance per tenant

**Sub-topics:** Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## SaaS penetration patterns

**Sub-topics:** Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

