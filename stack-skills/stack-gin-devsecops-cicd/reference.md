# Gin (Go): DevSecOps and CI/CD

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-devsecops-cicd` / `reference.md`.

## CI secrets

**Sub-topics:** Fork PR leaks, OIDC to cloud, Threat modeling and trust boundaries (CI secrets), Abuse cases and adversarial testing (CI secrets), Logging, audit, and detection (CI secrets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CI secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI secrets.
- Keep dependencies patched; pin versions for CI secrets components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CI secrets before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CI secrets paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Static analysis

**Sub-topics:** False positives, Gate policy, Threat modeling and trust boundaries (Static analysis), Abuse cases and adversarial testing (Static analysis), Logging, audit, and detection (Static analysis)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Static analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static analysis.
- Keep dependencies patched; pin versions for Static analysis components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Static analysis before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Static analysis paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Dynamic analysis

**Sub-topics:** Staging auth, Scope, Threat modeling and trust boundaries (Dynamic analysis), Abuse cases and adversarial testing (Dynamic analysis), Logging, audit, and detection (Dynamic analysis)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Dynamic analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dynamic analysis.
- Keep dependencies patched; pin versions for Dynamic analysis components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Dynamic analysis before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Dynamic analysis paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Dependency scanning

**Sub-topics:** SBOM, License risk, Threat modeling and trust boundaries (Dependency scanning), Abuse cases and adversarial testing (Dependency scanning), Logging, audit, and detection (Dependency scanning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Dependency scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dependency scanning.
- Keep dependencies patched; pin versions for Dependency scanning components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Dependency scanning before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Dependency scanning paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Artifact signing

**Sub-topics:** Sigstore, Provenance, Threat modeling and trust boundaries (Artifact signing), Abuse cases and adversarial testing (Artifact signing), Logging, audit, and detection (Artifact signing)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Artifact signing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Artifact signing.
- Keep dependencies patched; pin versions for Artifact signing components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Artifact signing before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Artifact signing paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Branch protection

**Sub-topics:** Required reviews, Signed commits, Threat modeling and trust boundaries (Branch protection), Abuse cases and adversarial testing (Branch protection), Logging, audit, and detection (Branch protection)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Branch protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Branch protection.
- Keep dependencies patched; pin versions for Branch protection components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Branch protection before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Branch protection paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Deployment gates

**Sub-topics:** Canary, Rollback, Threat modeling and trust boundaries (Deployment gates), Abuse cases and adversarial testing (Deployment gates), Logging, audit, and detection (Deployment gates)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Deployment gates; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deployment gates.
- Keep dependencies patched; pin versions for Deployment gates components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Deployment gates before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Deployment gates paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## IaC scanning

**Sub-topics:** Terraform plan, Misconfig, Threat modeling and trust boundaries (IaC scanning), Abuse cases and adversarial testing (IaC scanning), Logging, audit, and detection (IaC scanning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching IaC scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IaC scanning.
- Keep dependencies patched; pin versions for IaC scanning components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for IaC scanning before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for IaC scanning paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Container scan in CI

**Sub-topics:** Blocking CVEs, Threat modeling and trust boundaries (Container scan in CI), Abuse cases and adversarial testing (Container scan in CI), Logging, audit, and detection (Container scan in CI), Access control and least privilege (Container scan in CI)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Container scan in CI; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container scan in CI.
- Keep dependencies patched; pin versions for Container scan in CI components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Container scan in CI before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Container scan in CI paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Secret scanning

**Sub-topics:** Pre-commit, History rewrite, Threat modeling and trust boundaries (Secret scanning), Abuse cases and adversarial testing (Secret scanning), Logging, audit, and detection (Secret scanning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Secret scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret scanning.
- Keep dependencies patched; pin versions for Secret scanning components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Secret scanning before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Secret scanning paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Environment promotion

**Sub-topics:** Prod data in lower envs, Threat modeling and trust boundaries (Environment promotion), Abuse cases and adversarial testing (Environment promotion), Logging, audit, and detection (Environment promotion), Access control and least privilege (Environment promotion)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Environment promotion; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment promotion.
- Keep dependencies patched; pin versions for Environment promotion components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Environment promotion before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Environment promotion paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## CI supply chain

**Sub-topics:** Third-party actions, Pinning, Threat modeling and trust boundaries (CI supply chain), Abuse cases and adversarial testing (CI supply chain), Logging, audit, and detection (CI supply chain)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CI supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI supply chain.
- Keep dependencies patched; pin versions for CI supply chain components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-devsecops-cicd` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CI supply chain before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CI supply chain paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

