# Hibernate / JPA: DevSecOps and CI/CD

Stack-specific implementation for **Hibernate / JPA** (ORM / data access). Normative rules: domain skill `security-devsecops-cicd` / `reference.md`.

## CI secrets

**Sub-topics:** Fork PR leaks, OIDC to cloud, Threat modeling and trust boundaries (CI secrets), Abuse cases and adversarial testing (CI secrets), Logging, audit, and detection (CI secrets)

### Do (use this in Hibernate / JPA)

- Map `CI secrets` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `CI secrets` before merge.

### Don't

- Do not ship `CI secrets` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `CI secrets`.

### Verify

- Peer review `CI secrets` against domain skill `security-devsecops-cicd`.

## Static analysis

**Sub-topics:** False positives, Gate policy, Threat modeling and trust boundaries (Static analysis), Abuse cases and adversarial testing (Static analysis), Logging, audit, and detection (Static analysis)

### Do (use this in Hibernate / JPA)

- Map `Static analysis` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Static analysis` before merge.

### Don't

- Do not ship `Static analysis` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Static analysis`.

### Verify

- Peer review `Static analysis` against domain skill `security-devsecops-cicd`.

## Dynamic analysis

**Sub-topics:** Staging auth, Scope, Threat modeling and trust boundaries (Dynamic analysis), Abuse cases and adversarial testing (Dynamic analysis), Logging, audit, and detection (Dynamic analysis)

### Do (use this in Hibernate / JPA)

- Map `Dynamic analysis` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Dynamic analysis` before merge.

### Don't

- Do not ship `Dynamic analysis` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Dynamic analysis`.

### Verify

- Peer review `Dynamic analysis` against domain skill `security-devsecops-cicd`.

## Dependency scanning

**Sub-topics:** SBOM, License risk, Threat modeling and trust boundaries (Dependency scanning), Abuse cases and adversarial testing (Dependency scanning), Logging, audit, and detection (Dependency scanning)

### Do (use this in Hibernate / JPA)

- Map `Dependency scanning` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Dependency scanning` before merge.

### Don't

- Do not ship `Dependency scanning` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Dependency scanning`.

### Verify

- Peer review `Dependency scanning` against domain skill `security-devsecops-cicd`.

## Artifact signing

**Sub-topics:** Sigstore, Provenance, Threat modeling and trust boundaries (Artifact signing), Abuse cases and adversarial testing (Artifact signing), Logging, audit, and detection (Artifact signing)

### Do (use this in Hibernate / JPA)

- Map `Artifact signing` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Artifact signing` before merge.

### Don't

- Do not ship `Artifact signing` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Artifact signing`.

### Verify

- Peer review `Artifact signing` against domain skill `security-devsecops-cicd`.

## Branch protection

**Sub-topics:** Required reviews, Signed commits, Threat modeling and trust boundaries (Branch protection), Abuse cases and adversarial testing (Branch protection), Logging, audit, and detection (Branch protection)

### Do (use this in Hibernate / JPA)

- Map `Branch protection` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Branch protection` before merge.

### Don't

- Do not ship `Branch protection` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Branch protection`.

### Verify

- Peer review `Branch protection` against domain skill `security-devsecops-cicd`.

## Deployment gates

**Sub-topics:** Canary, Rollback, Threat modeling and trust boundaries (Deployment gates), Abuse cases and adversarial testing (Deployment gates), Logging, audit, and detection (Deployment gates)

### Do (use this in Hibernate / JPA)

- Map `Deployment gates` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Deployment gates` before merge.

### Don't

- Do not ship `Deployment gates` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Deployment gates`.

### Verify

- Peer review `Deployment gates` against domain skill `security-devsecops-cicd`.

## IaC scanning

**Sub-topics:** Terraform plan, Misconfig, Threat modeling and trust boundaries (IaC scanning), Abuse cases and adversarial testing (IaC scanning), Logging, audit, and detection (IaC scanning)

### Do (use this in Hibernate / JPA)

- Map `IaC scanning` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `IaC scanning` before merge.

### Don't

- Do not ship `IaC scanning` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `IaC scanning`.

### Verify

- Peer review `IaC scanning` against domain skill `security-devsecops-cicd`.

## Container scan in CI

**Sub-topics:** Blocking CVEs, Threat modeling and trust boundaries (Container scan in CI), Abuse cases and adversarial testing (Container scan in CI), Logging, audit, and detection (Container scan in CI), Access control and least privilege (Container scan in CI)

### Do (use this in Hibernate / JPA)

- Map `Container scan in CI` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Container scan in CI` before merge.

### Don't

- Do not ship `Container scan in CI` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Container scan in CI`.

### Verify

- Peer review `Container scan in CI` against domain skill `security-devsecops-cicd`.

## Secret scanning

**Sub-topics:** Pre-commit, History rewrite, Threat modeling and trust boundaries (Secret scanning), Abuse cases and adversarial testing (Secret scanning), Logging, audit, and detection (Secret scanning)

### Do (use this in Hibernate / JPA)

- Map `Secret scanning` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Secret scanning` before merge.

### Don't

- Do not ship `Secret scanning` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Secret scanning`.

### Verify

- Peer review `Secret scanning` against domain skill `security-devsecops-cicd`.

## Environment promotion

**Sub-topics:** Prod data in lower envs, Threat modeling and trust boundaries (Environment promotion), Abuse cases and adversarial testing (Environment promotion), Logging, audit, and detection (Environment promotion), Access control and least privilege (Environment promotion)

### Do (use this in Hibernate / JPA)

- Map `Environment promotion` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `Environment promotion` before merge.

### Don't

- Do not ship `Environment promotion` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `Environment promotion`.

### Verify

- Peer review `Environment promotion` against domain skill `security-devsecops-cicd`.

## CI supply chain

**Sub-topics:** Third-party actions, Pinning, Threat modeling and trust boundaries (CI supply chain), Abuse cases and adversarial testing (CI supply chain), Logging, audit, and detection (CI supply chain)

### Do (use this in Hibernate / JPA)

- Map `CI supply chain` controls to Hibernate / JPA APIs documented for `security-devsecops-cicd`.
- Add an abuse-case test or check for `CI supply chain` before merge.

### Don't

- Do not ship `CI supply chain` work in Hibernate / JPA with only happy-path tests.
- Do not disable Hibernate / JPA security defaults to unblock `CI supply chain`.

### Verify

- Peer review `CI supply chain` against domain skill `security-devsecops-cicd`.

