# Docker: DevSecOps and CI/CD

Stack-specific implementation for **Docker** (Infrastructure). Normative rules: domain skill `security-devsecops-cicd` / `reference.md`.

## CI secrets

**Sub-topics:** Fork PR leaks, OIDC to cloud, Threat modeling and trust boundaries (CI secrets), Abuse cases and adversarial testing (CI secrets), Logging, audit, and detection (CI secrets)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Static analysis

**Sub-topics:** False positives, Gate policy, Threat modeling and trust boundaries (Static analysis), Abuse cases and adversarial testing (Static analysis), Logging, audit, and detection (Static analysis)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Dynamic analysis

**Sub-topics:** Staging auth, Scope, Threat modeling and trust boundaries (Dynamic analysis), Abuse cases and adversarial testing (Dynamic analysis), Logging, audit, and detection (Dynamic analysis)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Dependency scanning

**Sub-topics:** SBOM, License risk, Threat modeling and trust boundaries (Dependency scanning), Abuse cases and adversarial testing (Dependency scanning), Logging, audit, and detection (Dependency scanning)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Artifact signing

**Sub-topics:** Sigstore, Provenance, Threat modeling and trust boundaries (Artifact signing), Abuse cases and adversarial testing (Artifact signing), Logging, audit, and detection (Artifact signing)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Branch protection

**Sub-topics:** Required reviews, Signed commits, Threat modeling and trust boundaries (Branch protection), Abuse cases and adversarial testing (Branch protection), Logging, audit, and detection (Branch protection)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Deployment gates

**Sub-topics:** Canary, Rollback, Threat modeling and trust boundaries (Deployment gates), Abuse cases and adversarial testing (Deployment gates), Logging, audit, and detection (Deployment gates)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## IaC scanning

**Sub-topics:** Terraform plan, Misconfig, Threat modeling and trust boundaries (IaC scanning), Abuse cases and adversarial testing (IaC scanning), Logging, audit, and detection (IaC scanning)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Container scan in CI

**Sub-topics:** Blocking CVEs, Threat modeling and trust boundaries (Container scan in CI), Abuse cases and adversarial testing (Container scan in CI), Logging, audit, and detection (Container scan in CI), Access control and least privilege (Container scan in CI)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Secret scanning

**Sub-topics:** Pre-commit, History rewrite, Threat modeling and trust boundaries (Secret scanning), Abuse cases and adversarial testing (Secret scanning), Logging, audit, and detection (Secret scanning)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## Environment promotion

**Sub-topics:** Prod data in lower envs, Threat modeling and trust boundaries (Environment promotion), Abuse cases and adversarial testing (Environment promotion), Logging, audit, and detection (Environment promotion), Access control and least privilege (Environment promotion)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

## CI supply chain

**Sub-topics:** Third-party actions, Pinning, Threat modeling and trust boundaries (CI supply chain), Abuse cases and adversarial testing (CI supply chain), Logging, audit, and detection (CI supply chain)

### Do (use this in Docker)

- Run as non-root USER; use multi-stage builds; scan images with Trivy.

### Don't

- Do not use `--privileged` in production compose.
- Do not bake secrets into image layers.

### Verify

- Image scan gate in CI.

