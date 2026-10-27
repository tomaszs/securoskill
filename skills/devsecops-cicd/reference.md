# Rules reference: DevSecOps and CI/CD

Pipelines, artifacts, and secure delivery.

## CI secrets

Sub-topics: Fork PR leaks, OIDC to cloud, Threat modeling and trust boundaries (CI secrets), Abuse cases and adversarial testing (CI secrets), Logging, audit, and detection (CI secrets)

### Do

- Validate and canonicalize all inputs touching CI secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI secrets.
- Keep dependencies patched; pin versions for CI secrets components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CI secrets in CI secrets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CI secrets (DevSecOps and CI/CD).
- Require security review for material changes affecting CI secrets.

### Design

- Apply least privilege and defense in depth for CI secrets.
- Prefer established patterns and libraries over custom crypto or auth for CI secrets.
- Fail closed: deny by default when CI secrets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CI secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI secrets.
- Keep dependencies patched; pin versions for CI secrets components.

### Verification

- Add automated tests and SAST/DAST coverage for CI secrets paths.
- Run dependency and secret scanning on every change touching CI secrets.
- Perform targeted manual tests (abuse cases) for CI secrets.

### Operations

- Log security-relevant events for CI secrets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CI secrets.
- Review access and configuration for CI secrets on a regular cadence.

## Static analysis

Sub-topics: False positives, Gate policy, Threat modeling and trust boundaries (Static analysis), Abuse cases and adversarial testing (Static analysis), Logging, audit, and detection (Static analysis)

### Do

- Validate and canonicalize all inputs touching Static analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static analysis.
- Keep dependencies patched; pin versions for Static analysis components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Static analysis in Static analysis as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Static analysis (DevSecOps and CI/CD).
- Require security review for material changes affecting Static analysis.

### Design

- Apply least privilege and defense in depth for Static analysis.
- Prefer established patterns and libraries over custom crypto or auth for Static analysis.
- Fail closed: deny by default when Static analysis cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Static analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static analysis.
- Keep dependencies patched; pin versions for Static analysis components.

### Verification

- Add automated tests and SAST/DAST coverage for Static analysis paths.
- Run dependency and secret scanning on every change touching Static analysis.
- Perform targeted manual tests (abuse cases) for Static analysis.

### Operations

- Log security-relevant events for Static analysis without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Static analysis.
- Review access and configuration for Static analysis on a regular cadence.

## Dynamic analysis

Sub-topics: Staging auth, Scope, Threat modeling and trust boundaries (Dynamic analysis), Abuse cases and adversarial testing (Dynamic analysis), Logging, audit, and detection (Dynamic analysis)

### Do

- Validate and canonicalize all inputs touching Dynamic analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dynamic analysis.
- Keep dependencies patched; pin versions for Dynamic analysis components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Dynamic analysis in Dynamic analysis as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Dynamic analysis (DevSecOps and CI/CD).
- Require security review for material changes affecting Dynamic analysis.

### Design

- Apply least privilege and defense in depth for Dynamic analysis.
- Prefer established patterns and libraries over custom crypto or auth for Dynamic analysis.
- Fail closed: deny by default when Dynamic analysis cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Dynamic analysis; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dynamic analysis.
- Keep dependencies patched; pin versions for Dynamic analysis components.

### Verification

- Add automated tests and SAST/DAST coverage for Dynamic analysis paths.
- Run dependency and secret scanning on every change touching Dynamic analysis.
- Perform targeted manual tests (abuse cases) for Dynamic analysis.

### Operations

- Log security-relevant events for Dynamic analysis without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Dynamic analysis.
- Review access and configuration for Dynamic analysis on a regular cadence.

## Dependency scanning

Sub-topics: SBOM, License risk, Threat modeling and trust boundaries (Dependency scanning), Abuse cases and adversarial testing (Dependency scanning), Logging, audit, and detection (Dependency scanning)

### Do

- Validate and canonicalize all inputs touching Dependency scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dependency scanning.
- Keep dependencies patched; pin versions for Dependency scanning components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Dependency scanning in Dependency scanning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Dependency scanning (DevSecOps and CI/CD).
- Require security review for material changes affecting Dependency scanning.

### Design

- Apply least privilege and defense in depth for Dependency scanning.
- Prefer established patterns and libraries over custom crypto or auth for Dependency scanning.
- Fail closed: deny by default when Dependency scanning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Dependency scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Dependency scanning.
- Keep dependencies patched; pin versions for Dependency scanning components.

### Verification

- Add automated tests and SAST/DAST coverage for Dependency scanning paths.
- Run dependency and secret scanning on every change touching Dependency scanning.
- Perform targeted manual tests (abuse cases) for Dependency scanning.

### Operations

- Log security-relevant events for Dependency scanning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Dependency scanning.
- Review access and configuration for Dependency scanning on a regular cadence.

## Artifact signing

Sub-topics: Sigstore, Provenance, Threat modeling and trust boundaries (Artifact signing), Abuse cases and adversarial testing (Artifact signing), Logging, audit, and detection (Artifact signing)

### Do

- Validate and canonicalize all inputs touching Artifact signing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Artifact signing.
- Keep dependencies patched; pin versions for Artifact signing components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Artifact signing in Artifact signing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Artifact signing (DevSecOps and CI/CD).
- Require security review for material changes affecting Artifact signing.

### Design

- Apply least privilege and defense in depth for Artifact signing.
- Prefer established patterns and libraries over custom crypto or auth for Artifact signing.
- Fail closed: deny by default when Artifact signing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Artifact signing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Artifact signing.
- Keep dependencies patched; pin versions for Artifact signing components.

### Verification

- Add automated tests and SAST/DAST coverage for Artifact signing paths.
- Run dependency and secret scanning on every change touching Artifact signing.
- Perform targeted manual tests (abuse cases) for Artifact signing.

### Operations

- Log security-relevant events for Artifact signing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Artifact signing.
- Review access and configuration for Artifact signing on a regular cadence.

## Branch protection

Sub-topics: Required reviews, Signed commits, Threat modeling and trust boundaries (Branch protection), Abuse cases and adversarial testing (Branch protection), Logging, audit, and detection (Branch protection)

### Do

- Validate and canonicalize all inputs touching Branch protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Branch protection.
- Keep dependencies patched; pin versions for Branch protection components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Branch protection in Branch protection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Branch protection (DevSecOps and CI/CD).
- Require security review for material changes affecting Branch protection.

### Design

- Apply least privilege and defense in depth for Branch protection.
- Prefer established patterns and libraries over custom crypto or auth for Branch protection.
- Fail closed: deny by default when Branch protection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Branch protection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Branch protection.
- Keep dependencies patched; pin versions for Branch protection components.

### Verification

- Add automated tests and SAST/DAST coverage for Branch protection paths.
- Run dependency and secret scanning on every change touching Branch protection.
- Perform targeted manual tests (abuse cases) for Branch protection.

### Operations

- Log security-relevant events for Branch protection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Branch protection.
- Review access and configuration for Branch protection on a regular cadence.

## Deployment gates

Sub-topics: Canary, Rollback, Threat modeling and trust boundaries (Deployment gates), Abuse cases and adversarial testing (Deployment gates), Logging, audit, and detection (Deployment gates)

### Do

- Validate and canonicalize all inputs touching Deployment gates; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deployment gates.
- Keep dependencies patched; pin versions for Deployment gates components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Deployment gates in Deployment gates as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Deployment gates (DevSecOps and CI/CD).
- Require security review for material changes affecting Deployment gates.

### Design

- Apply least privilege and defense in depth for Deployment gates.
- Prefer established patterns and libraries over custom crypto or auth for Deployment gates.
- Fail closed: deny by default when Deployment gates cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Deployment gates; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deployment gates.
- Keep dependencies patched; pin versions for Deployment gates components.

### Verification

- Add automated tests and SAST/DAST coverage for Deployment gates paths.
- Run dependency and secret scanning on every change touching Deployment gates.
- Perform targeted manual tests (abuse cases) for Deployment gates.

### Operations

- Log security-relevant events for Deployment gates without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Deployment gates.
- Review access and configuration for Deployment gates on a regular cadence.

## IaC scanning

Sub-topics: Terraform plan, Misconfig, Threat modeling and trust boundaries (IaC scanning), Abuse cases and adversarial testing (IaC scanning), Logging, audit, and detection (IaC scanning)

### Do

- Validate and canonicalize all inputs touching IaC scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IaC scanning.
- Keep dependencies patched; pin versions for IaC scanning components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat IaC scanning in IaC scanning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for IaC scanning (DevSecOps and CI/CD).
- Require security review for material changes affecting IaC scanning.

### Design

- Apply least privilege and defense in depth for IaC scanning.
- Prefer established patterns and libraries over custom crypto or auth for IaC scanning.
- Fail closed: deny by default when IaC scanning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching IaC scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to IaC scanning.
- Keep dependencies patched; pin versions for IaC scanning components.

### Verification

- Add automated tests and SAST/DAST coverage for IaC scanning paths.
- Run dependency and secret scanning on every change touching IaC scanning.
- Perform targeted manual tests (abuse cases) for IaC scanning.

### Operations

- Log security-relevant events for IaC scanning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in IaC scanning.
- Review access and configuration for IaC scanning on a regular cadence.

## Container scan in CI

Sub-topics: Blocking CVEs, Threat modeling and trust boundaries (Container scan in CI), Abuse cases and adversarial testing (Container scan in CI), Logging, audit, and detection (Container scan in CI), Access control and least privilege (Container scan in CI)

### Do

- Validate and canonicalize all inputs touching Container scan in CI; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container scan in CI.
- Keep dependencies patched; pin versions for Container scan in CI components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Container scan in CI in Container scan in CI as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Container scan in CI (DevSecOps and CI/CD).
- Require security review for material changes affecting Container scan in CI.

### Design

- Apply least privilege and defense in depth for Container scan in CI.
- Prefer established patterns and libraries over custom crypto or auth for Container scan in CI.
- Fail closed: deny by default when Container scan in CI cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Container scan in CI; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Container scan in CI.
- Keep dependencies patched; pin versions for Container scan in CI components.

### Verification

- Add automated tests and SAST/DAST coverage for Container scan in CI paths.
- Run dependency and secret scanning on every change touching Container scan in CI.
- Perform targeted manual tests (abuse cases) for Container scan in CI.

### Operations

- Log security-relevant events for Container scan in CI without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Container scan in CI.
- Review access and configuration for Container scan in CI on a regular cadence.

## Secret scanning

Sub-topics: Pre-commit, History rewrite, Threat modeling and trust boundaries (Secret scanning), Abuse cases and adversarial testing (Secret scanning), Logging, audit, and detection (Secret scanning)

### Do

- Validate and canonicalize all inputs touching Secret scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret scanning.
- Keep dependencies patched; pin versions for Secret scanning components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Secret scanning in Secret scanning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secret scanning (DevSecOps and CI/CD).
- Require security review for material changes affecting Secret scanning.

### Design

- Apply least privilege and defense in depth for Secret scanning.
- Prefer established patterns and libraries over custom crypto or auth for Secret scanning.
- Fail closed: deny by default when Secret scanning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secret scanning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret scanning.
- Keep dependencies patched; pin versions for Secret scanning components.

### Verification

- Add automated tests and SAST/DAST coverage for Secret scanning paths.
- Run dependency and secret scanning on every change touching Secret scanning.
- Perform targeted manual tests (abuse cases) for Secret scanning.

### Operations

- Log security-relevant events for Secret scanning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secret scanning.
- Review access and configuration for Secret scanning on a regular cadence.

## Environment promotion

Sub-topics: Prod data in lower envs, Threat modeling and trust boundaries (Environment promotion), Abuse cases and adversarial testing (Environment promotion), Logging, audit, and detection (Environment promotion), Access control and least privilege (Environment promotion)

### Do

- Validate and canonicalize all inputs touching Environment promotion; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment promotion.
- Keep dependencies patched; pin versions for Environment promotion components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Environment promotion in Environment promotion as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Environment promotion (DevSecOps and CI/CD).
- Require security review for material changes affecting Environment promotion.

### Design

- Apply least privilege and defense in depth for Environment promotion.
- Prefer established patterns and libraries over custom crypto or auth for Environment promotion.
- Fail closed: deny by default when Environment promotion cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Environment promotion; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment promotion.
- Keep dependencies patched; pin versions for Environment promotion components.

### Verification

- Add automated tests and SAST/DAST coverage for Environment promotion paths.
- Run dependency and secret scanning on every change touching Environment promotion.
- Perform targeted manual tests (abuse cases) for Environment promotion.

### Operations

- Log security-relevant events for Environment promotion without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Environment promotion.
- Review access and configuration for Environment promotion on a regular cadence.

## CI supply chain

Sub-topics: Third-party actions, Pinning, Threat modeling and trust boundaries (CI supply chain), Abuse cases and adversarial testing (CI supply chain), Logging, audit, and detection (CI supply chain)

### Do

- Validate and canonicalize all inputs touching CI supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI supply chain.
- Keep dependencies patched; pin versions for CI supply chain components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CI supply chain in CI supply chain as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CI supply chain (DevSecOps and CI/CD).
- Require security review for material changes affecting CI supply chain.

### Design

- Apply least privilege and defense in depth for CI supply chain.
- Prefer established patterns and libraries over custom crypto or auth for CI supply chain.
- Fail closed: deny by default when CI supply chain cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CI supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CI supply chain.
- Keep dependencies patched; pin versions for CI supply chain components.

### Verification

- Add automated tests and SAST/DAST coverage for CI supply chain paths.
- Run dependency and secret scanning on every change touching CI supply chain.
- Perform targeted manual tests (abuse cases) for CI supply chain.

### Operations

- Log security-relevant events for CI supply chain without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CI supply chain.
- Review access and configuration for CI supply chain on a regular cadence.

