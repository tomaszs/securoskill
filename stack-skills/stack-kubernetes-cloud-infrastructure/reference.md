# Kubernetes: Cloud and infrastructure security

Stack-specific implementation for **Kubernetes** (Infrastructure). Normative rules: domain skill `security-cloud-infrastructure` / `reference.md`.

## Cloud IAM

**Sub-topics:** Overprivileged roles, IAM conditions, Threat modeling and trust boundaries (Cloud IAM), Abuse cases and adversarial testing (Cloud IAM), Logging, audit, and detection (Cloud IAM)

### Do (use this in Kubernetes)

- Map `Cloud IAM` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Cloud IAM` before merge.

### Don't

- Do not ship `Cloud IAM` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Cloud IAM`.

### Verify

- Peer review `Cloud IAM` against domain skill `security-cloud-infrastructure`.

## Object storage buckets

**Sub-topics:** Public ACLs, Policy mistakes, Threat modeling and trust boundaries (Object storage buckets), Abuse cases and adversarial testing (Object storage buckets), Logging, audit, and detection (Object storage buckets)

### Do (use this in Kubernetes)

- Map `Object storage buckets` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Object storage buckets` before merge.

### Don't

- Do not ship `Object storage buckets` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Object storage buckets`.

### Verify

- Peer review `Object storage buckets` against domain skill `security-cloud-infrastructure`.

## Compute instances

**Sub-topics:** IMDSv2, SSH keys, Metadata, Threat modeling and trust boundaries (Compute instances), Abuse cases and adversarial testing (Compute instances)

### Do (use this in Kubernetes)

- Map `Compute instances` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Compute instances` before merge.

### Don't

- Do not ship `Compute instances` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Compute instances`.

### Verify

- Peer review `Compute instances` against domain skill `security-cloud-infrastructure`.

## Managed serverless

**Sub-topics:** Function URLs, Concurrency, Threat modeling and trust boundaries (Managed serverless), Abuse cases and adversarial testing (Managed serverless), Logging, audit, and detection (Managed serverless)

### Do (use this in Kubernetes)

- Map `Managed serverless` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Managed serverless` before merge.

### Don't

- Do not ship `Managed serverless` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Managed serverless`.

### Verify

- Peer review `Managed serverless` against domain skill `security-cloud-infrastructure`.

## Secrets managers

**Sub-topics:** Rotation, Access policies, Threat modeling and trust boundaries (Secrets managers), Abuse cases and adversarial testing (Secrets managers), Logging, audit, and detection (Secrets managers)

### Do (use this in Kubernetes)

- Map `Secrets managers` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Secrets managers` before merge.

### Don't

- Do not ship `Secrets managers` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Secrets managers`.

### Verify

- Peer review `Secrets managers` against domain skill `security-cloud-infrastructure`.

## VPC and security groups

**Sub-topics:** 0.0.0.0/0, Peering leaks, Threat modeling and trust boundaries (VPC and security groups), Abuse cases and adversarial testing (VPC and security groups), Logging, audit, and detection (VPC and security groups)

### Do (use this in Kubernetes)

- Map `VPC and security groups` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `VPC and security groups` before merge.

### Don't

- Do not ship `VPC and security groups` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `VPC and security groups`.

### Verify

- Peer review `VPC and security groups` against domain skill `security-cloud-infrastructure`.

## Cloud audit logs

**Sub-topics:** Tampering, Retention, Threat modeling and trust boundaries (Cloud audit logs), Abuse cases and adversarial testing (Cloud audit logs), Logging, audit, and detection (Cloud audit logs)

### Do (use this in Kubernetes)

- Map `Cloud audit logs` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Cloud audit logs` before merge.

### Don't

- Do not ship `Cloud audit logs` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Cloud audit logs`.

### Verify

- Peer review `Cloud audit logs` against domain skill `security-cloud-infrastructure`.

## Infrastructure as code

**Sub-topics:** State files, Drift, Threat modeling and trust boundaries (Infrastructure as code), Abuse cases and adversarial testing (Infrastructure as code), Logging, audit, and detection (Infrastructure as code)

### Do (use this in Kubernetes)

- Map `Infrastructure as code` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Infrastructure as code` before merge.

### Don't

- Do not ship `Infrastructure as code` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Infrastructure as code`.

### Verify

- Peer review `Infrastructure as code` against domain skill `security-cloud-infrastructure`.

## Multi-cloud identity

**Sub-topics:** Federation, Key sprawl, Threat modeling and trust boundaries (Multi-cloud identity), Abuse cases and adversarial testing (Multi-cloud identity), Logging, audit, and detection (Multi-cloud identity)

### Do (use this in Kubernetes)

- Map `Multi-cloud identity` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `Multi-cloud identity` before merge.

### Don't

- Do not ship `Multi-cloud identity` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `Multi-cloud identity`.

### Verify

- Peer review `Multi-cloud identity` against domain skill `security-cloud-infrastructure`.

## SaaS admin consoles

**Sub-topics:** MFA, SCIM, Threat modeling and trust boundaries (SaaS admin consoles), Abuse cases and adversarial testing (SaaS admin consoles), Logging, audit, and detection (SaaS admin consoles)

### Do (use this in Kubernetes)

- Map `SaaS admin consoles` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `SaaS admin consoles` before merge.

### Don't

- Do not ship `SaaS admin consoles` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `SaaS admin consoles`.

### Verify

- Peer review `SaaS admin consoles` against domain skill `security-cloud-infrastructure`.

## CDN and edge

**Sub-topics:** Cache deception, Origin shield, Threat modeling and trust boundaries (CDN and edge), Abuse cases and adversarial testing (CDN and edge), Logging, audit, and detection (CDN and edge)

### Do (use this in Kubernetes)

- Map `CDN and edge` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `CDN and edge` before merge.

### Don't

- Do not ship `CDN and edge` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `CDN and edge`.

### Verify

- Peer review `CDN and edge` against domain skill `security-cloud-infrastructure`.

## DR and regions

**Sub-topics:** Failover security, Data residency, Threat modeling and trust boundaries (DR and regions), Abuse cases and adversarial testing (DR and regions), Logging, audit, and detection (DR and regions)

### Do (use this in Kubernetes)

- Map `DR and regions` controls to Kubernetes APIs documented for `security-cloud-infrastructure`.
- Add an abuse-case test or check for `DR and regions` before merge.

### Don't

- Do not ship `DR and regions` work in Kubernetes with only happy-path tests.
- Do not disable Kubernetes security defaults to unblock `DR and regions`.

### Verify

- Peer review `DR and regions` against domain skill `security-cloud-infrastructure`.

