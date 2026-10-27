# Vercel: Multi-tenancy and SaaS isolation

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant identification

**Sub-topics:** Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Data isolation models

**Sub-topics:** Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Billing and plan enforcement

**Sub-topics:** Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Custom domains and TLS

**Sub-topics:** Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Tenant export and backup

**Sub-topics:** Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Per-tenant integrations

**Sub-topics:** OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Noisy neighbor and quotas

**Sub-topics:** CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Tenant onboarding

**Sub-topics:** Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Tenant offboarding

**Sub-topics:** Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## Compliance per tenant

**Sub-topics:** Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

## SaaS penetration patterns

**Sub-topics:** Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `multi-tenancy-saas`; load stack skill `security-multi-tenancy-saas` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-multi-tenancy-saas` (domain reference.md).

### Don't

- Do not duplicate `multi-tenancy-saas` controls only in Vercel config while leaving security-multi-tenancy-saas misconfigured.
- Do not assume Vercel defaults satisfy `security-multi-tenancy-saas` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-multi-tenancy-saas`.

