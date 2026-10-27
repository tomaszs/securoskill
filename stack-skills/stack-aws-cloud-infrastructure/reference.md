# Amazon Web Services: Cloud and infrastructure security

Stack-specific implementation for **Amazon Web Services** (Cloud). Normative rules: domain skill `security-cloud-infrastructure` / `reference.md`.

## Cloud IAM

**Sub-topics:** Overprivileged roles, IAM conditions, Threat modeling and trust boundaries (Cloud IAM), Abuse cases and adversarial testing (Cloud IAM), Logging, audit, and detection (Cloud IAM)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Object storage buckets

**Sub-topics:** Public ACLs, Policy mistakes, Threat modeling and trust boundaries (Object storage buckets), Abuse cases and adversarial testing (Object storage buckets), Logging, audit, and detection (Object storage buckets)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Compute instances

**Sub-topics:** IMDSv2, SSH keys, Metadata, Threat modeling and trust boundaries (Compute instances), Abuse cases and adversarial testing (Compute instances)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Managed serverless

**Sub-topics:** Function URLs, Concurrency, Threat modeling and trust boundaries (Managed serverless), Abuse cases and adversarial testing (Managed serverless), Logging, audit, and detection (Managed serverless)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Secrets managers

**Sub-topics:** Rotation, Access policies, Threat modeling and trust boundaries (Secrets managers), Abuse cases and adversarial testing (Secrets managers), Logging, audit, and detection (Secrets managers)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## VPC and security groups

**Sub-topics:** 0.0.0.0/0, Peering leaks, Threat modeling and trust boundaries (VPC and security groups), Abuse cases and adversarial testing (VPC and security groups), Logging, audit, and detection (VPC and security groups)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Cloud audit logs

**Sub-topics:** Tampering, Retention, Threat modeling and trust boundaries (Cloud audit logs), Abuse cases and adversarial testing (Cloud audit logs), Logging, audit, and detection (Cloud audit logs)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Infrastructure as code

**Sub-topics:** State files, Drift, Threat modeling and trust boundaries (Infrastructure as code), Abuse cases and adversarial testing (Infrastructure as code), Logging, audit, and detection (Infrastructure as code)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## Multi-cloud identity

**Sub-topics:** Federation, Key sprawl, Threat modeling and trust boundaries (Multi-cloud identity), Abuse cases and adversarial testing (Multi-cloud identity), Logging, audit, and detection (Multi-cloud identity)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## SaaS admin consoles

**Sub-topics:** MFA, SCIM, Threat modeling and trust boundaries (SaaS admin consoles), Abuse cases and adversarial testing (SaaS admin consoles), Logging, audit, and detection (SaaS admin consoles)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## CDN and edge

**Sub-topics:** Cache deception, Origin shield, Threat modeling and trust boundaries (CDN and edge), Abuse cases and adversarial testing (CDN and edge), Logging, audit, and detection (CDN and edge)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

## DR and regions

**Sub-topics:** Failover security, Data residency, Threat modeling and trust boundaries (DR and regions), Abuse cases and adversarial testing (DR and regions), Logging, audit, and detection (DR and regions)

### Do (use this in Amazon Web Services)

- Attach IAM roles to Lambda/ECS/EKS workloads; no static `AWS_ACCESS_KEY_ID` in apps.
- Enable S3 Block Public Access at account level.

### Don't

- Do not attach `AdministratorAccess` to CI users.
- Do not open security group `0.0.0.0/0` on SSH/RDP.

### Verify

- AWS Config rules + tfsec on every Terraform PR.

