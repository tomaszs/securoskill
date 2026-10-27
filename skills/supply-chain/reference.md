# Rules reference: Software supply chain

Dependencies, vendors, and build integrity.

## Package registries

Sub-topics: Typosquatting, Maintainer takeover, Threat modeling and trust boundaries (Package registries), Abuse cases and adversarial testing (Package registries), Logging, audit, and detection (Package registries)

### Do

- Validate and canonicalize all inputs touching Package registries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Package registries.
- Keep dependencies patched; pin versions for Package registries components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Package registries in Package registries as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Package registries (Software supply chain).
- Require security review for material changes affecting Package registries.

### Design

- Apply least privilege and defense in depth for Package registries.
- Prefer established patterns and libraries over custom crypto or auth for Package registries.
- Fail closed: deny by default when Package registries cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Package registries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Package registries.
- Keep dependencies patched; pin versions for Package registries components.

### Verification

- Add automated tests and SAST/DAST coverage for Package registries paths.
- Run dependency and secret scanning on every change touching Package registries.
- Perform targeted manual tests (abuse cases) for Package registries.

### Operations

- Log security-relevant events for Package registries without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Package registries.
- Review access and configuration for Package registries on a regular cadence.

## Lockfiles and reproducibility

Sub-topics: Integrity hashes, Threat modeling and trust boundaries (Lockfiles and reproducibility), Abuse cases and adversarial testing (Lockfiles and reproducibility), Logging, audit, and detection (Lockfiles and reproducibility), Access control and least privilege (Lockfiles and reproducibility)

### Do

- Validate and canonicalize all inputs touching Lockfiles and reproducibility; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lockfiles and reproducibility.
- Keep dependencies patched; pin versions for Lockfiles and reproducibility components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Lockfiles and reproducibility in Lockfiles and reproducibility as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Lockfiles and reproducibility (Software supply chain).
- Require security review for material changes affecting Lockfiles and reproducibility.

### Design

- Apply least privilege and defense in depth for Lockfiles and reproducibility.
- Prefer established patterns and libraries over custom crypto or auth for Lockfiles and reproducibility.
- Fail closed: deny by default when Lockfiles and reproducibility cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Lockfiles and reproducibility; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Lockfiles and reproducibility.
- Keep dependencies patched; pin versions for Lockfiles and reproducibility components.

### Verification

- Add automated tests and SAST/DAST coverage for Lockfiles and reproducibility paths.
- Run dependency and secret scanning on every change touching Lockfiles and reproducibility.
- Perform targeted manual tests (abuse cases) for Lockfiles and reproducibility.

### Operations

- Log security-relevant events for Lockfiles and reproducibility without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Lockfiles and reproducibility.
- Review access and configuration for Lockfiles and reproducibility on a regular cadence.

## Vendoring

Sub-topics: Fork drift, Patch review, Threat modeling and trust boundaries (Vendoring), Abuse cases and adversarial testing (Vendoring), Logging, audit, and detection (Vendoring)

### Do

- Validate and canonicalize all inputs touching Vendoring; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendoring.
- Keep dependencies patched; pin versions for Vendoring components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Vendoring in Vendoring as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Vendoring (Software supply chain).
- Require security review for material changes affecting Vendoring.

### Design

- Apply least privilege and defense in depth for Vendoring.
- Prefer established patterns and libraries over custom crypto or auth for Vendoring.
- Fail closed: deny by default when Vendoring cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Vendoring; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendoring.
- Keep dependencies patched; pin versions for Vendoring components.

### Verification

- Add automated tests and SAST/DAST coverage for Vendoring paths.
- Run dependency and secret scanning on every change touching Vendoring.
- Perform targeted manual tests (abuse cases) for Vendoring.

### Operations

- Log security-relevant events for Vendoring without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Vendoring.
- Review access and configuration for Vendoring on a regular cadence.

## Build integrity

Sub-topics: SLSA levels, Hermetic builds, Threat modeling and trust boundaries (Build integrity), Abuse cases and adversarial testing (Build integrity), Logging, audit, and detection (Build integrity)

### Do

- Validate and canonicalize all inputs touching Build integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Build integrity.
- Keep dependencies patched; pin versions for Build integrity components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Build integrity in Build integrity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Build integrity (Software supply chain).
- Require security review for material changes affecting Build integrity.

### Design

- Apply least privilege and defense in depth for Build integrity.
- Prefer established patterns and libraries over custom crypto or auth for Build integrity.
- Fail closed: deny by default when Build integrity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Build integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Build integrity.
- Keep dependencies patched; pin versions for Build integrity components.

### Verification

- Add automated tests and SAST/DAST coverage for Build integrity paths.
- Run dependency and secret scanning on every change touching Build integrity.
- Perform targeted manual tests (abuse cases) for Build integrity.

### Operations

- Log security-relevant events for Build integrity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Build integrity.
- Review access and configuration for Build integrity on a regular cadence.

## Third-party SaaS

Sub-topics: DPAs, Subprocessors, Threat modeling and trust boundaries (Third-party SaaS), Abuse cases and adversarial testing (Third-party SaaS), Logging, audit, and detection (Third-party SaaS)

### Do

- Validate and canonicalize all inputs touching Third-party SaaS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party SaaS.
- Keep dependencies patched; pin versions for Third-party SaaS components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Third-party SaaS in Third-party SaaS as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Third-party SaaS (Software supply chain).
- Require security review for material changes affecting Third-party SaaS.

### Design

- Apply least privilege and defense in depth for Third-party SaaS.
- Prefer established patterns and libraries over custom crypto or auth for Third-party SaaS.
- Fail closed: deny by default when Third-party SaaS cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Third-party SaaS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party SaaS.
- Keep dependencies patched; pin versions for Third-party SaaS components.

### Verification

- Add automated tests and SAST/DAST coverage for Third-party SaaS paths.
- Run dependency and secret scanning on every change touching Third-party SaaS.
- Perform targeted manual tests (abuse cases) for Third-party SaaS.

### Operations

- Log security-relevant events for Third-party SaaS without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Third-party SaaS.
- Review access and configuration for Third-party SaaS on a regular cadence.

## License compliance

Sub-topics: Copyleft in SaaS, Threat modeling and trust boundaries (License compliance), Abuse cases and adversarial testing (License compliance), Logging, audit, and detection (License compliance), Access control and least privilege (License compliance)

### Do

- Validate and canonicalize all inputs touching License compliance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to License compliance.
- Keep dependencies patched; pin versions for License compliance components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat License compliance in License compliance as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for License compliance (Software supply chain).
- Require security review for material changes affecting License compliance.

### Design

- Apply least privilege and defense in depth for License compliance.
- Prefer established patterns and libraries over custom crypto or auth for License compliance.
- Fail closed: deny by default when License compliance cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching License compliance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to License compliance.
- Keep dependencies patched; pin versions for License compliance components.

### Verification

- Add automated tests and SAST/DAST coverage for License compliance paths.
- Run dependency and secret scanning on every change touching License compliance.
- Perform targeted manual tests (abuse cases) for License compliance.

### Operations

- Log security-relevant events for License compliance without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in License compliance.
- Review access and configuration for License compliance on a regular cadence.

## Binary dependencies

Sub-topics: Provenance, Checksums, Threat modeling and trust boundaries (Binary dependencies), Abuse cases and adversarial testing (Binary dependencies), Logging, audit, and detection (Binary dependencies)

### Do

- Validate and canonicalize all inputs touching Binary dependencies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Binary dependencies.
- Keep dependencies patched; pin versions for Binary dependencies components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Binary dependencies in Binary dependencies as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Binary dependencies (Software supply chain).
- Require security review for material changes affecting Binary dependencies.

### Design

- Apply least privilege and defense in depth for Binary dependencies.
- Prefer established patterns and libraries over custom crypto or auth for Binary dependencies.
- Fail closed: deny by default when Binary dependencies cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Binary dependencies; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Binary dependencies.
- Keep dependencies patched; pin versions for Binary dependencies components.

### Verification

- Add automated tests and SAST/DAST coverage for Binary dependencies paths.
- Run dependency and secret scanning on every change touching Binary dependencies.
- Perform targeted manual tests (abuse cases) for Binary dependencies.

### Operations

- Log security-relevant events for Binary dependencies without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Binary dependencies.
- Review access and configuration for Binary dependencies on a regular cadence.

## Git submodules

Sub-topics: Pinned refs, URL hijack, Threat modeling and trust boundaries (Git submodules), Abuse cases and adversarial testing (Git submodules), Logging, audit, and detection (Git submodules)

### Do

- Validate and canonicalize all inputs touching Git submodules; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Git submodules.
- Keep dependencies patched; pin versions for Git submodules components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Git submodules in Git submodules as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Git submodules (Software supply chain).
- Require security review for material changes affecting Git submodules.

### Design

- Apply least privilege and defense in depth for Git submodules.
- Prefer established patterns and libraries over custom crypto or auth for Git submodules.
- Fail closed: deny by default when Git submodules cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Git submodules; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Git submodules.
- Keep dependencies patched; pin versions for Git submodules components.

### Verification

- Add automated tests and SAST/DAST coverage for Git submodules paths.
- Run dependency and secret scanning on every change touching Git submodules.
- Perform targeted manual tests (abuse cases) for Git submodules.

### Operations

- Log security-relevant events for Git submodules without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Git submodules.
- Review access and configuration for Git submodules on a regular cadence.

## Internal packages

Sub-topics: Namespace, Publishing tokens, Threat modeling and trust boundaries (Internal packages), Abuse cases and adversarial testing (Internal packages), Logging, audit, and detection (Internal packages)

### Do

- Validate and canonicalize all inputs touching Internal packages; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Internal packages.
- Keep dependencies patched; pin versions for Internal packages components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Internal packages in Internal packages as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Internal packages (Software supply chain).
- Require security review for material changes affecting Internal packages.

### Design

- Apply least privilege and defense in depth for Internal packages.
- Prefer established patterns and libraries over custom crypto or auth for Internal packages.
- Fail closed: deny by default when Internal packages cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Internal packages; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Internal packages.
- Keep dependencies patched; pin versions for Internal packages components.

### Verification

- Add automated tests and SAST/DAST coverage for Internal packages paths.
- Run dependency and secret scanning on every change touching Internal packages.
- Perform targeted manual tests (abuse cases) for Internal packages.

### Operations

- Log security-relevant events for Internal packages without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Internal packages.
- Review access and configuration for Internal packages on a regular cadence.

## CVE response

Sub-topics: Triage, Emergency patches, Threat modeling and trust boundaries (CVE response), Abuse cases and adversarial testing (CVE response), Logging, audit, and detection (CVE response)

### Do

- Validate and canonicalize all inputs touching CVE response; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CVE response.
- Keep dependencies patched; pin versions for CVE response components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CVE response in CVE response as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CVE response (Software supply chain).
- Require security review for material changes affecting CVE response.

### Design

- Apply least privilege and defense in depth for CVE response.
- Prefer established patterns and libraries over custom crypto or auth for CVE response.
- Fail closed: deny by default when CVE response cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CVE response; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CVE response.
- Keep dependencies patched; pin versions for CVE response components.

### Verification

- Add automated tests and SAST/DAST coverage for CVE response paths.
- Run dependency and secret scanning on every change touching CVE response.
- Perform targeted manual tests (abuse cases) for CVE response.

### Operations

- Log security-relevant events for CVE response without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CVE response.
- Review access and configuration for CVE response on a regular cadence.

## Malware in repos

Sub-topics: Obfuscated scripts, Postinstall, Threat modeling and trust boundaries (Malware in repos), Abuse cases and adversarial testing (Malware in repos), Logging, audit, and detection (Malware in repos)

### Do

- Validate and canonicalize all inputs touching Malware in repos; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware in repos.
- Keep dependencies patched; pin versions for Malware in repos components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Malware in repos in Malware in repos as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Malware in repos (Software supply chain).
- Require security review for material changes affecting Malware in repos.

### Design

- Apply least privilege and defense in depth for Malware in repos.
- Prefer established patterns and libraries over custom crypto or auth for Malware in repos.
- Fail closed: deny by default when Malware in repos cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Malware in repos; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Malware in repos.
- Keep dependencies patched; pin versions for Malware in repos components.

### Verification

- Add automated tests and SAST/DAST coverage for Malware in repos paths.
- Run dependency and secret scanning on every change touching Malware in repos.
- Perform targeted manual tests (abuse cases) for Malware in repos.

### Operations

- Log security-relevant events for Malware in repos without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Malware in repos.
- Review access and configuration for Malware in repos on a regular cadence.

## SBOM distribution

Sub-topics: VEX, Consumer updates, Threat modeling and trust boundaries (SBOM distribution), Abuse cases and adversarial testing (SBOM distribution), Logging, audit, and detection (SBOM distribution)

### Do

- Validate and canonicalize all inputs touching SBOM distribution; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SBOM distribution.
- Keep dependencies patched; pin versions for SBOM distribution components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SBOM distribution in SBOM distribution as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SBOM distribution (Software supply chain).
- Require security review for material changes affecting SBOM distribution.

### Design

- Apply least privilege and defense in depth for SBOM distribution.
- Prefer established patterns and libraries over custom crypto or auth for SBOM distribution.
- Fail closed: deny by default when SBOM distribution cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SBOM distribution; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SBOM distribution.
- Keep dependencies patched; pin versions for SBOM distribution components.

### Verification

- Add automated tests and SAST/DAST coverage for SBOM distribution paths.
- Run dependency and secret scanning on every change touching SBOM distribution.
- Perform targeted manual tests (abuse cases) for SBOM distribution.

### Operations

- Log security-relevant events for SBOM distribution without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SBOM distribution.
- Review access and configuration for SBOM distribution on a regular cadence.

