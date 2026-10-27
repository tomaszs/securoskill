# Rules reference: Secrets and configuration

Env vars, config files, and feature flags.

## Environment variables

Sub-topics: Leaks in logs, Client exposure, Threat modeling and trust boundaries (Environment variables), Abuse cases and adversarial testing (Environment variables), Logging, audit, and detection (Environment variables)

### Do

- Validate and canonicalize all inputs touching Environment variables; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment variables.
- Keep dependencies patched; pin versions for Environment variables components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Environment variables in Environment variables as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Environment variables (Secrets and configuration).
- Require security review for material changes affecting Environment variables.

### Design

- Apply least privilege and defense in depth for Environment variables.
- Prefer established patterns and libraries over custom crypto or auth for Environment variables.
- Fail closed: deny by default when Environment variables cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Environment variables; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Environment variables.
- Keep dependencies patched; pin versions for Environment variables components.

### Verification

- Add automated tests and SAST/DAST coverage for Environment variables paths.
- Run dependency and secret scanning on every change touching Environment variables.
- Perform targeted manual tests (abuse cases) for Environment variables.

### Operations

- Log security-relevant events for Environment variables without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Environment variables.
- Review access and configuration for Environment variables on a regular cadence.

## Config separation

Sub-topics: Per-env files, Gitignore, Threat modeling and trust boundaries (Config separation), Abuse cases and adversarial testing (Config separation), Logging, audit, and detection (Config separation)

### Do

- Validate and canonicalize all inputs touching Config separation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config separation.
- Keep dependencies patched; pin versions for Config separation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Config separation in Config separation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Config separation (Secrets and configuration).
- Require security review for material changes affecting Config separation.

### Design

- Apply least privilege and defense in depth for Config separation.
- Prefer established patterns and libraries over custom crypto or auth for Config separation.
- Fail closed: deny by default when Config separation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Config separation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config separation.
- Keep dependencies patched; pin versions for Config separation components.

### Verification

- Add automated tests and SAST/DAST coverage for Config separation paths.
- Run dependency and secret scanning on every change touching Config separation.
- Perform targeted manual tests (abuse cases) for Config separation.

### Operations

- Log security-relevant events for Config separation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Config separation.
- Review access and configuration for Config separation on a regular cadence.

## Feature flags

Sub-topics: Kill switches, Privileged features, Threat modeling and trust boundaries (Feature flags), Abuse cases and adversarial testing (Feature flags), Logging, audit, and detection (Feature flags)

### Do

- Validate and canonicalize all inputs touching Feature flags; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature flags.
- Keep dependencies patched; pin versions for Feature flags components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Feature flags in Feature flags as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Feature flags (Secrets and configuration).
- Require security review for material changes affecting Feature flags.

### Design

- Apply least privilege and defense in depth for Feature flags.
- Prefer established patterns and libraries over custom crypto or auth for Feature flags.
- Fail closed: deny by default when Feature flags cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Feature flags; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature flags.
- Keep dependencies patched; pin versions for Feature flags components.

### Verification

- Add automated tests and SAST/DAST coverage for Feature flags paths.
- Run dependency and secret scanning on every change touching Feature flags.
- Perform targeted manual tests (abuse cases) for Feature flags.

### Operations

- Log security-relevant events for Feature flags without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Feature flags.
- Review access and configuration for Feature flags on a regular cadence.

## Secret rotation

Sub-topics: Dual-write, Breakage windows, Threat modeling and trust boundaries (Secret rotation), Abuse cases and adversarial testing (Secret rotation), Logging, audit, and detection (Secret rotation)

### Do

- Validate and canonicalize all inputs touching Secret rotation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret rotation.
- Keep dependencies patched; pin versions for Secret rotation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Secret rotation in Secret rotation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secret rotation (Secrets and configuration).
- Require security review for material changes affecting Secret rotation.

### Design

- Apply least privilege and defense in depth for Secret rotation.
- Prefer established patterns and libraries over custom crypto or auth for Secret rotation.
- Fail closed: deny by default when Secret rotation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secret rotation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secret rotation.
- Keep dependencies patched; pin versions for Secret rotation components.

### Verification

- Add automated tests and SAST/DAST coverage for Secret rotation paths.
- Run dependency and secret scanning on every change touching Secret rotation.
- Perform targeted manual tests (abuse cases) for Secret rotation.

### Operations

- Log security-relevant events for Secret rotation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secret rotation.
- Review access and configuration for Secret rotation on a regular cadence.

## .env handling

Sub-topics: Committed secrets, CI injection, Threat modeling and trust boundaries (.env handling), Abuse cases and adversarial testing (.env handling), Logging, audit, and detection (.env handling)

### Do

- Validate and canonicalize all inputs touching .env handling.env handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to .env handling.
- Keep dependencies patched; pin versions for .env handling.env handling components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat .env handling in .env handling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for .env handling.env handling (Secrets and configuration).
- Require security review for material changes affecting .env handling.env handling.

### Design

- Apply least privilege and defense in depth for .env handling.env handling.
- Prefer established patterns and libraries over custom crypto or auth for .env handling.env handling.
- Fail closed: deny by default when .env handling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching .env handling.env handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to .env handling.
- Keep dependencies patched; pin versions for .env handling.env handling components.

### Verification

- Add automated tests and SAST/DAST coverage for .env handling.env handling paths.
- Run dependency and secret scanning on every change touching .env handling.env handling.
- Perform targeted manual tests (abuse cases) for .env handling.env handling.

### Operations

- Log security-relevant events for .env handling.env handling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in .env handling.env handling.
- Review access and configuration for .env handling.env handling on a regular cadence.

## Config servers

Sub-topics: ACLs, Encryption, Threat modeling and trust boundaries (Config servers), Abuse cases and adversarial testing (Config servers), Logging, audit, and detection (Config servers)

### Do

- Validate and canonicalize all inputs touching Config servers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config servers.
- Keep dependencies patched; pin versions for Config servers components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Config servers in Config servers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Config servers (Secrets and configuration).
- Require security review for material changes affecting Config servers.

### Design

- Apply least privilege and defense in depth for Config servers.
- Prefer established patterns and libraries over custom crypto or auth for Config servers.
- Fail closed: deny by default when Config servers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Config servers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Config servers.
- Keep dependencies patched; pin versions for Config servers components.

### Verification

- Add automated tests and SAST/DAST coverage for Config servers paths.
- Run dependency and secret scanning on every change touching Config servers.
- Perform targeted manual tests (abuse cases) for Config servers.

### Operations

- Log security-relevant events for Config servers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Config servers.
- Review access and configuration for Config servers on a regular cadence.

## Hardcoded credentials

Sub-topics: Scanning, Prevention, Threat modeling and trust boundaries (Hardcoded credentials), Abuse cases and adversarial testing (Hardcoded credentials), Logging, audit, and detection (Hardcoded credentials)

### Do

- Validate and canonicalize all inputs touching Hardcoded credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Hardcoded credentials.
- Keep dependencies patched; pin versions for Hardcoded credentials components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Hardcoded credentials in Hardcoded credentials as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Hardcoded credentials (Secrets and configuration).
- Require security review for material changes affecting Hardcoded credentials.

### Design

- Apply least privilege and defense in depth for Hardcoded credentials.
- Prefer established patterns and libraries over custom crypto or auth for Hardcoded credentials.
- Fail closed: deny by default when Hardcoded credentials cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Hardcoded credentials; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Hardcoded credentials.
- Keep dependencies patched; pin versions for Hardcoded credentials components.

### Verification

- Add automated tests and SAST/DAST coverage for Hardcoded credentials paths.
- Run dependency and secret scanning on every change touching Hardcoded credentials.
- Perform targeted manual tests (abuse cases) for Hardcoded credentials.

### Operations

- Log security-relevant events for Hardcoded credentials without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Hardcoded credentials.
- Review access and configuration for Hardcoded credentials on a regular cadence.

## Public vs confidential clients

Sub-topics: Mobile apps, SPAs, Threat modeling and trust boundaries (Public vs confidential clients), Abuse cases and adversarial testing (Public vs confidential clients), Logging, audit, and detection (Public vs confidential clients)

### Do

- Validate and canonicalize all inputs touching Public vs confidential clients; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Public vs confidential clients.
- Keep dependencies patched; pin versions for Public vs confidential clients components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Public vs confidential clients in Public vs confidential clients as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Public vs confidential clients (Secrets and configuration).
- Require security review for material changes affecting Public vs confidential clients.

### Design

- Apply least privilege and defense in depth for Public vs confidential clients.
- Prefer established patterns and libraries over custom crypto or auth for Public vs confidential clients.
- Fail closed: deny by default when Public vs confidential clients cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Public vs confidential clients; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Public vs confidential clients.
- Keep dependencies patched; pin versions for Public vs confidential clients components.

### Verification

- Add automated tests and SAST/DAST coverage for Public vs confidential clients paths.
- Run dependency and secret scanning on every change touching Public vs confidential clients.
- Perform targeted manual tests (abuse cases) for Public vs confidential clients.

### Operations

- Log security-relevant events for Public vs confidential clients without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Public vs confidential clients.
- Review access and configuration for Public vs confidential clients on a regular cadence.

## Bootstrap secrets

Sub-topics: First deploy, Init containers, Threat modeling and trust boundaries (Bootstrap secrets), Abuse cases and adversarial testing (Bootstrap secrets), Logging, audit, and detection (Bootstrap secrets)

### Do

- Validate and canonicalize all inputs touching Bootstrap secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bootstrap secrets.
- Keep dependencies patched; pin versions for Bootstrap secrets components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Bootstrap secrets in Bootstrap secrets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bootstrap secrets (Secrets and configuration).
- Require security review for material changes affecting Bootstrap secrets.

### Design

- Apply least privilege and defense in depth for Bootstrap secrets.
- Prefer established patterns and libraries over custom crypto or auth for Bootstrap secrets.
- Fail closed: deny by default when Bootstrap secrets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bootstrap secrets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bootstrap secrets.
- Keep dependencies patched; pin versions for Bootstrap secrets components.

### Verification

- Add automated tests and SAST/DAST coverage for Bootstrap secrets paths.
- Run dependency and secret scanning on every change touching Bootstrap secrets.
- Perform targeted manual tests (abuse cases) for Bootstrap secrets.

### Operations

- Log security-relevant events for Bootstrap secrets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bootstrap secrets.
- Review access and configuration for Bootstrap secrets on a regular cadence.

## Configuration audit

Sub-topics: Drift detection, Threat modeling and trust boundaries (Configuration audit), Abuse cases and adversarial testing (Configuration audit), Logging, audit, and detection (Configuration audit), Access control and least privilege (Configuration audit)

### Do

- Validate and canonicalize all inputs touching Configuration audit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Configuration audit.
- Keep dependencies patched; pin versions for Configuration audit components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Configuration audit in Configuration audit as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Configuration audit (Secrets and configuration).
- Require security review for material changes affecting Configuration audit.

### Design

- Apply least privilege and defense in depth for Configuration audit.
- Prefer established patterns and libraries over custom crypto or auth for Configuration audit.
- Fail closed: deny by default when Configuration audit cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Configuration audit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Configuration audit.
- Keep dependencies patched; pin versions for Configuration audit components.

### Verification

- Add automated tests and SAST/DAST coverage for Configuration audit paths.
- Run dependency and secret scanning on every change touching Configuration audit.
- Perform targeted manual tests (abuse cases) for Configuration audit.

### Operations

- Log security-relevant events for Configuration audit without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Configuration audit.
- Review access and configuration for Configuration audit on a regular cadence.

## Insecure defaults

Sub-topics: Debug=true, Open admin, Threat modeling and trust boundaries (Insecure defaults), Abuse cases and adversarial testing (Insecure defaults), Logging, audit, and detection (Insecure defaults)

### Do

- Validate and canonicalize all inputs touching Insecure defaults; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure defaults.
- Keep dependencies patched; pin versions for Insecure defaults components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Insecure defaults in Insecure defaults as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Insecure defaults (Secrets and configuration).
- Require security review for material changes affecting Insecure defaults.

### Design

- Apply least privilege and defense in depth for Insecure defaults.
- Prefer established patterns and libraries over custom crypto or auth for Insecure defaults.
- Fail closed: deny by default when Insecure defaults cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Insecure defaults; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure defaults.
- Keep dependencies patched; pin versions for Insecure defaults components.

### Verification

- Add automated tests and SAST/DAST coverage for Insecure defaults paths.
- Run dependency and secret scanning on every change touching Insecure defaults.
- Perform targeted manual tests (abuse cases) for Insecure defaults.

### Operations

- Log security-relevant events for Insecure defaults without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Insecure defaults.
- Review access and configuration for Insecure defaults on a regular cadence.

## Split knowledge

Sub-topics: Shamir, M-of-N, Threat modeling and trust boundaries (Split knowledge), Abuse cases and adversarial testing (Split knowledge), Logging, audit, and detection (Split knowledge)

### Do

- Validate and canonicalize all inputs touching Split knowledge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Split knowledge.
- Keep dependencies patched; pin versions for Split knowledge components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Split knowledge in Split knowledge as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Split knowledge (Secrets and configuration).
- Require security review for material changes affecting Split knowledge.

### Design

- Apply least privilege and defense in depth for Split knowledge.
- Prefer established patterns and libraries over custom crypto or auth for Split knowledge.
- Fail closed: deny by default when Split knowledge cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Split knowledge; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Split knowledge.
- Keep dependencies patched; pin versions for Split knowledge components.

### Verification

- Add automated tests and SAST/DAST coverage for Split knowledge paths.
- Run dependency and secret scanning on every change touching Split knowledge.
- Perform targeted manual tests (abuse cases) for Split knowledge.

### Operations

- Log security-relevant events for Split knowledge without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Split knowledge.
- Review access and configuration for Split knowledge on a regular cadence.

