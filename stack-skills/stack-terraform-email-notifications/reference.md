# Terraform: Email and notifications security

Stack-specific implementation for **Terraform** (Infrastructure). Normative rules: domain skill `security-email-notifications` / `reference.md`.

## Email authentication

**Sub-topics:** SPF, DKIM, DMARC, Threat modeling and trust boundaries (Email authentication), Abuse cases and adversarial testing (Email authentication)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Template injection in email

**Sub-topics:** SSTI in mailers, Threat modeling and trust boundaries (Template injection in email), Abuse cases and adversarial testing (Template injection in email), Logging, audit, and detection (Template injection in email), Access control and least privilege (Template injection in email)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Links in email

**Sub-topics:** Open redirect, Tracking, Threat modeling and trust boundaries (Links in email), Abuse cases and adversarial testing (Links in email), Logging, audit, and detection (Links in email)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Bounce and webhook handling

**Sub-topics:** Forged events, Threat modeling and trust boundaries (Bounce and webhook handling), Abuse cases and adversarial testing (Bounce and webhook handling), Logging, audit, and detection (Bounce and webhook handling), Access control and least privilege (Bounce and webhook handling)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## List management

**Sub-topics:** Header injection, Threat modeling and trust boundaries (List management), Abuse cases and adversarial testing (List management), Logging, audit, and detection (List management), Access control and least privilege (List management)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Brand impersonation

**Sub-topics:** From addresses, BIMI, Threat modeling and trust boundaries (Brand impersonation), Abuse cases and adversarial testing (Brand impersonation), Logging, audit, and detection (Brand impersonation)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Attachments

**Sub-topics:** Malware scanning, Threat modeling and trust boundaries (Attachments), Abuse cases and adversarial testing (Attachments), Logging, audit, and detection (Attachments), Access control and least privilege (Attachments)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## SMS and push

**Sub-topics:** OTP leakage, SIM swap awareness, Threat modeling and trust boundaries (SMS and push), Abuse cases and adversarial testing (SMS and push), Logging, audit, and detection (SMS and push)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## User inbox rules attacks

**Sub-topics:** Forwarding rules, Threat modeling and trust boundaries (User inbox rules attacks), Abuse cases and adversarial testing (User inbox rules attacks), Logging, audit, and detection (User inbox rules attacks), Access control and least privilege (User inbox rules attacks)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Email provider APIs

**Sub-topics:** API keys, Send-as, Threat modeling and trust boundaries (Email provider APIs), Abuse cases and adversarial testing (Email provider APIs), Logging, audit, and detection (Email provider APIs)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## PII in email bodies

**Sub-topics:** Encryption, Retention, Threat modeling and trust boundaries (PII in email bodies), Abuse cases and adversarial testing (PII in email bodies), Logging, audit, and detection (PII in email bodies)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

## Email abuse

**Sub-topics:** Forgot password spam, Threat modeling and trust boundaries (Email abuse), Abuse cases and adversarial testing (Email abuse), Logging, audit, and detection (Email abuse), Access control and least privilege (Email abuse)

### Do (use this in Terraform)

- Pin module versions; store state in encrypted remote backend.
- Use `terraform plan` in CI with policy checks.

### Don't

- Do not commit `terraform.tfstate` with secrets.
- Do not use `0.0.0.0/0` security groups without review.

### Verify

- tfsec/checkov on every PR.

