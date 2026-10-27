# SvelteKit: Multi-tenancy and SaaS isolation

Stack-specific implementation for **SvelteKit** (Web UI). Normative rules: domain skill `security-multi-tenancy-saas` / `reference.md`.

## Tenant identification

**Sub-topics:** Subdomain routing, Header spoofing, JWT tenant claim, Shared login portals, Cross-tenant IDs

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_id controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Data isolation models

**Sub-topics:** Separate DB, Shared schema RLS, Shard keys, Cache namespacing, Search index isolation

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_data controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Tenant-scoped authorization

**Sub-topics:** Admin impersonation, Support access, API keys per tenant, Role templates, Guest users

### Do (use this in SvelteKit)

- Check authorization on every handler after authentication (object-level, not only route-level).
- Centralize policy checks; reuse one guard/middleware pattern across routes.

### Don't

- Do not trust client-sent role flags or hidden form fields for authorization.
- Do not skip authz on 'internal' JSON endpoints.

### Verify

- Add tests for horizontal IDOR (user A cannot access user B ids).

## Billing and plan enforcement

**Sub-topics:** Feature flags per plan, Usage metering, Trial abuse, Seat limits, Upgrade bypass

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_billing controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Custom domains and TLS

**Sub-topics:** Domain verification, Cert provisioning, Host header attacks, Tenant vanity URLs, DNS takeover

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for custom_domains controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Tenant export and backup

**Sub-topics:** Bulk export IDOR, Scheduled exports, Restore to wrong tenant, GDPR per tenant, Retention per tenant

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_export controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Per-tenant integrations

**Sub-topics:** OAuth app installs, Webhook endpoints, SCIM provisioning, API rate per tenant, Third-party tokens

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_integrations controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Noisy neighbor and quotas

**Sub-topics:** CPU limits, Queue fairness, DB connection pools, Rate limits, Burst abuse

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for noisy_neighbor controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Tenant onboarding

**Sub-topics:** Self-signup abuse, Email domain verification, Invite flows, Default permissions, Sandbox tenants

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_onboard controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Tenant offboarding

**Sub-topics:** Data deletion, Legal hold, Reactivation, Orphan resources, Subprocessor notice

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_offboard controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## Compliance per tenant

**Sub-topics:** Data residency, Audit logs per tenant, DPA variants, HIPAA BAA, SOC reports

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for tenant_compliance controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

## SaaS penetration patterns

**Sub-topics:** Horizontal privilege, Vertical to platform admin, Cross-tenant file access, Report IDOR, Shared infrastructure

### Do (use this in SvelteKit)

- Apply domain skill `security-multi-tenancy-saas` requirements using sveltekit supported APIs only.
- Use the official sveltekit security documentation for saas_pentest controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sveltekit for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sveltekit projects in CI.

