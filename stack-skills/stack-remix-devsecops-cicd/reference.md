# Remix: DevSecOps and CI/CD

Stack-specific implementation for **Remix** (Web UI). Normative rules: domain skill `security-devsecops-cicd` / `reference.md`.

## CI secrets

**Sub-topics:** Fork PR leaks, OIDC to cloud, Threat modeling and trust boundaries (CI secrets), Abuse cases and adversarial testing (CI secrets), Logging, audit, and detection (CI secrets)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for ci_secrets controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Static analysis

**Sub-topics:** False positives, Gate policy, Threat modeling and trust boundaries (Static analysis), Abuse cases and adversarial testing (Static analysis), Logging, audit, and detection (Static analysis)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for sast controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Dynamic analysis

**Sub-topics:** Staging auth, Scope, Threat modeling and trust boundaries (Dynamic analysis), Abuse cases and adversarial testing (Dynamic analysis), Logging, audit, and detection (Dynamic analysis)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for dast controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Dependency scanning

**Sub-topics:** SBOM, License risk, Threat modeling and trust boundaries (Dependency scanning), Abuse cases and adversarial testing (Dependency scanning), Logging, audit, and detection (Dependency scanning)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for dependency_scan controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Artifact signing

**Sub-topics:** Sigstore, Provenance, Threat modeling and trust boundaries (Artifact signing), Abuse cases and adversarial testing (Artifact signing), Logging, audit, and detection (Artifact signing)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for signing controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Branch protection

**Sub-topics:** Required reviews, Signed commits, Threat modeling and trust boundaries (Branch protection), Abuse cases and adversarial testing (Branch protection), Logging, audit, and detection (Branch protection)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for branch_protection controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Deployment gates

**Sub-topics:** Canary, Rollback, Threat modeling and trust boundaries (Deployment gates), Abuse cases and adversarial testing (Deployment gates), Logging, audit, and detection (Deployment gates)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for deploy_gates controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## IaC scanning

**Sub-topics:** Terraform plan, Misconfig, Threat modeling and trust boundaries (IaC scanning), Abuse cases and adversarial testing (IaC scanning), Logging, audit, and detection (IaC scanning)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for iac_scan controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Container scan in CI

**Sub-topics:** Blocking CVEs, Threat modeling and trust boundaries (Container scan in CI), Abuse cases and adversarial testing (Container scan in CI), Logging, audit, and detection (Container scan in CI), Access control and least privilege (Container scan in CI)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for container_scan_ci controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Secret scanning

**Sub-topics:** Pre-commit, History rewrite, Threat modeling and trust boundaries (Secret scanning), Abuse cases and adversarial testing (Secret scanning), Logging, audit, and detection (Secret scanning)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for secrets_scan controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## Environment promotion

**Sub-topics:** Prod data in lower envs, Threat modeling and trust boundaries (Environment promotion), Abuse cases and adversarial testing (Environment promotion), Logging, audit, and detection (Environment promotion), Access control and least privilege (Environment promotion)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for env_promotion controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

## CI supply chain

**Sub-topics:** Third-party actions, Pinning, Threat modeling and trust boundaries (CI supply chain), Abuse cases and adversarial testing (CI supply chain), Logging, audit, and detection (CI supply chain)

### Do (use this in Remix)

- Apply domain skill `security-devsecops-cicd` requirements using remix supported APIs only.
- Use the official remix security documentation for supply_chain_ci controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of remix for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on remix projects in CI.

