# Actix Web (Rust): Multi-tenancy and SaaS isolation

Stack-specific implementation for **Actix Web (Rust)** (Rust). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant identification

**Sub-topics:** Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Do (use this in Actix Web (Rust))

- Map `Tenant identification` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Tenant identification` before merge.

### Don't

- Do not ship `Tenant identification` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Tenant identification`.

### Verify

- Peer review `Tenant identification` against domain skill `security-multi-tenancy-saas`.

## Data isolation models

**Sub-topics:** Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Do (use this in Actix Web (Rust))

- Map `Data isolation models` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Data isolation models` before merge.

### Don't

- Do not ship `Data isolation models` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Data isolation models`.

### Verify

- Peer review `Data isolation models` against domain skill `security-multi-tenancy-saas`.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Do (use this in Actix Web (Rust))

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).
- Run cargo audit + clippy on changes affecting `Tenant-scoped authorization`.

## Billing and plan enforcement

**Sub-topics:** Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Do (use this in Actix Web (Rust))

- Map `Billing and plan enforcement` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Billing and plan enforcement` before merge.

### Don't

- Do not ship `Billing and plan enforcement` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Billing and plan enforcement`.

### Verify

- Peer review `Billing and plan enforcement` against domain skill `security-multi-tenancy-saas`.

## Custom domains and TLS

**Sub-topics:** Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Do (use this in Actix Web (Rust))

- Map `Custom domains and TLS` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Custom domains and TLS` before merge.

### Don't

- Do not ship `Custom domains and TLS` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Custom domains and TLS`.

### Verify

- Peer review `Custom domains and TLS` against domain skill `security-multi-tenancy-saas`.

## Tenant export and backup

**Sub-topics:** Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Do (use this in Actix Web (Rust))

- Map `Tenant export and backup` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Tenant export and backup` before merge.

### Don't

- Do not ship `Tenant export and backup` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Tenant export and backup`.

### Verify

- Peer review `Tenant export and backup` against domain skill `security-multi-tenancy-saas`.

## Per-tenant integrations

**Sub-topics:** OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Do (use this in Actix Web (Rust))

- Map `Per-tenant integrations` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Per-tenant integrations` before merge.

### Don't

- Do not ship `Per-tenant integrations` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Per-tenant integrations`.

### Verify

- Peer review `Per-tenant integrations` against domain skill `security-multi-tenancy-saas`.

## Noisy neighbor and quotas

**Sub-topics:** CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Do (use this in Actix Web (Rust))

- Map `Noisy neighbor and quotas` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Noisy neighbor and quotas` before merge.

### Don't

- Do not ship `Noisy neighbor and quotas` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Noisy neighbor and quotas`.

### Verify

- Peer review `Noisy neighbor and quotas` against domain skill `security-multi-tenancy-saas`.

## Tenant onboarding

**Sub-topics:** Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Do (use this in Actix Web (Rust))

- Map `Tenant onboarding` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Tenant onboarding` before merge.

### Don't

- Do not ship `Tenant onboarding` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Tenant onboarding`.

### Verify

- Peer review `Tenant onboarding` against domain skill `security-multi-tenancy-saas`.

## Tenant offboarding

**Sub-topics:** Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Do (use this in Actix Web (Rust))

- Map `Tenant offboarding` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Tenant offboarding` before merge.

### Don't

- Do not ship `Tenant offboarding` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Tenant offboarding`.

### Verify

- Peer review `Tenant offboarding` against domain skill `security-multi-tenancy-saas`.

## Compliance per tenant

**Sub-topics:** Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Do (use this in Actix Web (Rust))

- Map `Compliance per tenant` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `Compliance per tenant` before merge.

### Don't

- Do not ship `Compliance per tenant` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `Compliance per tenant`.

### Verify

- Peer review `Compliance per tenant` against domain skill `security-multi-tenancy-saas`.

## SaaS penetration patterns

**Sub-topics:** Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Do (use this in Actix Web (Rust))

- Map `SaaS penetration patterns` controls to Actix Web (Rust) APIs documented for `security-multi-tenancy-saas`.
- Add an abuse-case test or check for `SaaS penetration patterns` before merge.

### Don't

- Do not ship `SaaS penetration patterns` work in Actix Web (Rust) with only happy-path tests.
- Do not disable Actix Web (Rust) security defaults to unblock `SaaS penetration patterns`.

### Verify

- Peer review `SaaS penetration patterns` against domain skill `security-multi-tenancy-saas`.

