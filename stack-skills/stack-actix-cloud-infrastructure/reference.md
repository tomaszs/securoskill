# Actix Web (Rust): Cloud and infrastructure security

Stack-specific implementation for **Actix Web (Rust)** (Rust). Normative rules: domain skill `security-cloud-infrastructure` / `reference.md`.

## Cloud IAM

**Sub-topics:** Overprivileged roles, IAM conditions, Threat modeling and trust boundaries (Cloud IAM), Abuse cases and adversarial testing (Cloud IAM), Logging, audit, and detection (Cloud IAM)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for cloud_iam controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Object storage buckets

**Sub-topics:** Public ACLs, Policy mistakes, Threat modeling and trust boundaries (Object storage buckets), Abuse cases and adversarial testing (Object storage buckets), Logging, audit, and detection (Object storage buckets)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for object_storage controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Compute instances

**Sub-topics:** IMDSv2, SSH keys, Metadata, Threat modeling and trust boundaries (Compute instances), Abuse cases and adversarial testing (Compute instances)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for cloud_compute controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Managed serverless

**Sub-topics:** Function URLs, Concurrency, Threat modeling and trust boundaries (Managed serverless), Abuse cases and adversarial testing (Managed serverless), Logging, audit, and detection (Managed serverless)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for serverless controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Secrets managers

**Sub-topics:** Rotation, Access policies, Threat modeling and trust boundaries (Secrets managers), Abuse cases and adversarial testing (Secrets managers), Logging, audit, and detection (Secrets managers)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for secrets_manager controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## VPC and security groups

**Sub-topics:** 0.0.0.0/0, Peering leaks, Threat modeling and trust boundaries (VPC and security groups), Abuse cases and adversarial testing (VPC and security groups), Logging, audit, and detection (VPC and security groups)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for vpc controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Cloud audit logs

**Sub-topics:** Tampering, Retention, Threat modeling and trust boundaries (Cloud audit logs), Abuse cases and adversarial testing (Cloud audit logs), Logging, audit, and detection (Cloud audit logs)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for cloud_audit controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Infrastructure as code

**Sub-topics:** State files, Drift, Threat modeling and trust boundaries (Infrastructure as code), Abuse cases and adversarial testing (Infrastructure as code), Logging, audit, and detection (Infrastructure as code)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for terraform controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## Multi-cloud identity

**Sub-topics:** Federation, Key sprawl, Threat modeling and trust boundaries (Multi-cloud identity), Abuse cases and adversarial testing (Multi-cloud identity), Logging, audit, and detection (Multi-cloud identity)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for multi_cloud controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## SaaS admin consoles

**Sub-topics:** MFA, SCIM, Threat modeling and trust boundaries (SaaS admin consoles), Abuse cases and adversarial testing (SaaS admin consoles), Logging, audit, and detection (SaaS admin consoles)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for saas_admin controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## CDN and edge

**Sub-topics:** Cache deception, Origin shield, Threat modeling and trust boundaries (CDN and edge), Abuse cases and adversarial testing (CDN and edge), Logging, audit, and detection (CDN and edge)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for cdn controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

## DR and regions

**Sub-topics:** Failover security, Data residency, Threat modeling and trust boundaries (DR and regions), Abuse cases and adversarial testing (DR and regions), Logging, audit, and detection (DR and regions)

### Do (use this in Actix Web (Rust))

- Apply domain skill `security-cloud-infrastructure` requirements using actix supported APIs only.
- Use the official actix security documentation for dr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of actix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on actix projects in CI.

