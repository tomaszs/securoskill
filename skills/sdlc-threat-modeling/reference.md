# Rules reference: SDLC, threat modeling, and secure design

How teams embed security before code ships.

## STRIDE and threat models

Sub-topics: Diagrams, Trust boundaries, Threat modeling and trust boundaries (STRIDE and threat models), Abuse cases and adversarial testing (STRIDE and threat models), Logging, audit, and detection (STRIDE and threat models)

### Do

- Validate and canonicalize all inputs touching STRIDE and threat models; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to STRIDE and threat models.
- Keep dependencies patched; pin versions for STRIDE and threat models components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat STRIDE and threat models in STRIDE and threat models as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for STRIDE and threat models (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting STRIDE and threat models.

### Design

- Apply least privilege and defense in depth for STRIDE and threat models.
- Prefer established patterns and libraries over custom crypto or auth for STRIDE and threat models.
- Fail closed: deny by default when STRIDE and threat models cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching STRIDE and threat models; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to STRIDE and threat models.
- Keep dependencies patched; pin versions for STRIDE and threat models components.

### Verification

- Add automated tests and SAST/DAST coverage for STRIDE and threat models paths.
- Run dependency and secret scanning on every change touching STRIDE and threat models.
- Perform targeted manual tests (abuse cases) for STRIDE and threat models.

### Operations

- Log security-relevant events for STRIDE and threat models without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in STRIDE and threat models.
- Review access and configuration for STRIDE and threat models on a regular cadence.

## Security requirements

Sub-topics: Non-functionals, Acceptance, Threat modeling and trust boundaries (Security requirements), Abuse cases and adversarial testing (Security requirements), Logging, audit, and detection (Security requirements)

### Do

- Validate and canonicalize all inputs touching Security requirements; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security requirements.
- Keep dependencies patched; pin versions for Security requirements components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Security requirements in Security requirements as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security requirements (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Security requirements.

### Design

- Apply least privilege and defense in depth for Security requirements.
- Prefer established patterns and libraries over custom crypto or auth for Security requirements.
- Fail closed: deny by default when Security requirements cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security requirements; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security requirements.
- Keep dependencies patched; pin versions for Security requirements components.

### Verification

- Add automated tests and SAST/DAST coverage for Security requirements paths.
- Run dependency and secret scanning on every change touching Security requirements.
- Perform targeted manual tests (abuse cases) for Security requirements.

### Operations

- Log security-relevant events for Security requirements without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security requirements.
- Review access and configuration for Security requirements on a regular cadence.

## Design review

Sub-topics: Checklists, Sign-off, Threat modeling and trust boundaries (Design review), Abuse cases and adversarial testing (Design review), Logging, audit, and detection (Design review)

### Do

- Validate and canonicalize all inputs touching Design review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design review.
- Keep dependencies patched; pin versions for Design review components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Design review in Design review as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Design review (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Design review.

### Design

- Apply least privilege and defense in depth for Design review.
- Prefer established patterns and libraries over custom crypto or auth for Design review.
- Fail closed: deny by default when Design review cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Design review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design review.
- Keep dependencies patched; pin versions for Design review components.

### Verification

- Add automated tests and SAST/DAST coverage for Design review paths.
- Run dependency and secret scanning on every change touching Design review.
- Perform targeted manual tests (abuse cases) for Design review.

### Operations

- Log security-relevant events for Design review without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Design review.
- Review access and configuration for Design review on a regular cadence.

## Security-focused code review

Sub-topics: Hotspots, Threat modeling and trust boundaries (Security-focused code review), Abuse cases and adversarial testing (Security-focused code review), Logging, audit, and detection (Security-focused code review), Access control and least privilege (Security-focused code review)

### Do

- Validate and canonicalize all inputs touching Security-focused code review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security-focused code review.
- Keep dependencies patched; pin versions for Security-focused code review components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Security-focused code review in Security-focused code review as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security-focused code review (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Security-focused code review.

### Design

- Apply least privilege and defense in depth for Security-focused code review.
- Prefer established patterns and libraries over custom crypto or auth for Security-focused code review.
- Fail closed: deny by default when Security-focused code review cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security-focused code review; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security-focused code review.
- Keep dependencies patched; pin versions for Security-focused code review components.

### Verification

- Add automated tests and SAST/DAST coverage for Security-focused code review paths.
- Run dependency and secret scanning on every change touching Security-focused code review.
- Perform targeted manual tests (abuse cases) for Security-focused code review.

### Operations

- Log security-relevant events for Security-focused code review without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security-focused code review.
- Review access and configuration for Security-focused code review on a regular cadence.

## Security test planning

Sub-topics: Coverage maps, Threat modeling and trust boundaries (Security test planning), Abuse cases and adversarial testing (Security test planning), Logging, audit, and detection (Security test planning), Access control and least privilege (Security test planning)

### Do

- Validate and canonicalize all inputs touching Security test planning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security test planning.
- Keep dependencies patched; pin versions for Security test planning components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Security test planning in Security test planning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Security test planning (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Security test planning.

### Design

- Apply least privilege and defense in depth for Security test planning.
- Prefer established patterns and libraries over custom crypto or auth for Security test planning.
- Fail closed: deny by default when Security test planning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Security test planning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Security test planning.
- Keep dependencies patched; pin versions for Security test planning components.

### Verification

- Add automated tests and SAST/DAST coverage for Security test planning paths.
- Run dependency and secret scanning on every change touching Security test planning.
- Perform targeted manual tests (abuse cases) for Security test planning.

### Operations

- Log security-relevant events for Security test planning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Security test planning.
- Review access and configuration for Security test planning on a regular cadence.

## Secure defaults culture

Sub-topics: Templates, Golden paths, Threat modeling and trust boundaries (Secure defaults culture), Abuse cases and adversarial testing (Secure defaults culture), Logging, audit, and detection (Secure defaults culture)

### Do

- Validate and canonicalize all inputs touching Secure defaults culture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secure defaults culture.
- Keep dependencies patched; pin versions for Secure defaults culture components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Secure defaults culture in Secure defaults culture as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Secure defaults culture (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Secure defaults culture.

### Design

- Apply least privilege and defense in depth for Secure defaults culture.
- Prefer established patterns and libraries over custom crypto or auth for Secure defaults culture.
- Fail closed: deny by default when Secure defaults culture cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Secure defaults culture; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Secure defaults culture.
- Keep dependencies patched; pin versions for Secure defaults culture components.

### Verification

- Add automated tests and SAST/DAST coverage for Secure defaults culture paths.
- Run dependency and secret scanning on every change touching Secure defaults culture.
- Perform targeted manual tests (abuse cases) for Secure defaults culture.

### Operations

- Log security-relevant events for Secure defaults culture without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Secure defaults culture.
- Review access and configuration for Secure defaults culture on a regular cadence.

## Developer education

Sub-topics: Labs, Phishing sims, Threat modeling and trust boundaries (Developer education), Abuse cases and adversarial testing (Developer education), Logging, audit, and detection (Developer education)

### Do

- Validate and canonicalize all inputs touching Developer education; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Developer education.
- Keep dependencies patched; pin versions for Developer education components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Developer education in Developer education as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Developer education (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Developer education.

### Design

- Apply least privilege and defense in depth for Developer education.
- Prefer established patterns and libraries over custom crypto or auth for Developer education.
- Fail closed: deny by default when Developer education cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Developer education; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Developer education.
- Keep dependencies patched; pin versions for Developer education components.

### Verification

- Add automated tests and SAST/DAST coverage for Developer education paths.
- Run dependency and secret scanning on every change touching Developer education.
- Perform targeted manual tests (abuse cases) for Developer education.

### Operations

- Log security-relevant events for Developer education without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Developer education.
- Review access and configuration for Developer education on a regular cadence.

## Vendor security assessment

Sub-topics: Questionnaires, Threat modeling and trust boundaries (Vendor security assessment), Abuse cases and adversarial testing (Vendor security assessment), Logging, audit, and detection (Vendor security assessment), Access control and least privilege (Vendor security assessment)

### Do

- Validate and canonicalize all inputs touching Vendor security assessment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendor security assessment.
- Keep dependencies patched; pin versions for Vendor security assessment components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Vendor security assessment in Vendor security assessment as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Vendor security assessment (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Vendor security assessment.

### Design

- Apply least privilege and defense in depth for Vendor security assessment.
- Prefer established patterns and libraries over custom crypto or auth for Vendor security assessment.
- Fail closed: deny by default when Vendor security assessment cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Vendor security assessment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vendor security assessment.
- Keep dependencies patched; pin versions for Vendor security assessment components.

### Verification

- Add automated tests and SAST/DAST coverage for Vendor security assessment paths.
- Run dependency and secret scanning on every change touching Vendor security assessment.
- Perform targeted manual tests (abuse cases) for Vendor security assessment.

### Operations

- Log security-relevant events for Vendor security assessment without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Vendor security assessment.
- Review access and configuration for Vendor security assessment on a regular cadence.

## Architecture decision records

Sub-topics: Security ADRs, Threat modeling and trust boundaries (Architecture decision records), Abuse cases and adversarial testing (Architecture decision records), Logging, audit, and detection (Architecture decision records), Access control and least privilege (Architecture decision records)

### Do

- Validate and canonicalize all inputs touching Architecture decision records; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Architecture decision records.
- Keep dependencies patched; pin versions for Architecture decision records components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Architecture decision records in Architecture decision records as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Architecture decision records (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Architecture decision records.

### Design

- Apply least privilege and defense in depth for Architecture decision records.
- Prefer established patterns and libraries over custom crypto or auth for Architecture decision records.
- Fail closed: deny by default when Architecture decision records cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Architecture decision records; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Architecture decision records.
- Keep dependencies patched; pin versions for Architecture decision records components.

### Verification

- Add automated tests and SAST/DAST coverage for Architecture decision records paths.
- Run dependency and secret scanning on every change touching Architecture decision records.
- Perform targeted manual tests (abuse cases) for Architecture decision records.

### Operations

- Log security-relevant events for Architecture decision records without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Architecture decision records.
- Review access and configuration for Architecture decision records on a regular cadence.

## Attack surface management

Sub-topics: Inventory, Exposure, Threat modeling and trust boundaries (Attack surface management), Abuse cases and adversarial testing (Attack surface management), Logging, audit, and detection (Attack surface management)

### Do

- Validate and canonicalize all inputs touching Attack surface management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Attack surface management.
- Keep dependencies patched; pin versions for Attack surface management components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Attack surface management in Attack surface management as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Attack surface management (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Attack surface management.

### Design

- Apply least privilege and defense in depth for Attack surface management.
- Prefer established patterns and libraries over custom crypto or auth for Attack surface management.
- Fail closed: deny by default when Attack surface management cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Attack surface management; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Attack surface management.
- Keep dependencies patched; pin versions for Attack surface management components.

### Verification

- Add automated tests and SAST/DAST coverage for Attack surface management paths.
- Run dependency and secret scanning on every change touching Attack surface management.
- Perform targeted manual tests (abuse cases) for Attack surface management.

### Operations

- Log security-relevant events for Attack surface management without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Attack surface management.
- Review access and configuration for Attack surface management on a regular cadence.

## Purple team exercises

Sub-topics: Scenarios, Threat modeling and trust boundaries (Purple team exercises), Abuse cases and adversarial testing (Purple team exercises), Logging, audit, and detection (Purple team exercises), Access control and least privilege (Purple team exercises)

### Do

- Validate and canonicalize all inputs touching Purple team exercises; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Purple team exercises.
- Keep dependencies patched; pin versions for Purple team exercises components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Purple team exercises in Purple team exercises as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Purple team exercises (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting Purple team exercises.

### Design

- Apply least privilege and defense in depth for Purple team exercises.
- Prefer established patterns and libraries over custom crypto or auth for Purple team exercises.
- Fail closed: deny by default when Purple team exercises cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Purple team exercises; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Purple team exercises.
- Keep dependencies patched; pin versions for Purple team exercises components.

### Verification

- Add automated tests and SAST/DAST coverage for Purple team exercises paths.
- Run dependency and secret scanning on every change touching Purple team exercises.
- Perform targeted manual tests (abuse cases) for Purple team exercises.

### Operations

- Log security-relevant events for Purple team exercises without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Purple team exercises.
- Review access and configuration for Purple team exercises on a regular cadence.

## SDL metrics

Sub-topics: Defect density, Lead time, Threat modeling and trust boundaries (SDL metrics), Abuse cases and adversarial testing (SDL metrics), Logging, audit, and detection (SDL metrics)

### Do

- Validate and canonicalize all inputs touching SDL metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SDL metrics.
- Keep dependencies patched; pin versions for SDL metrics components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SDL metrics in SDL metrics as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SDL metrics (SDLC, threat modeling, and secure design).
- Require security review for material changes affecting SDL metrics.

### Design

- Apply least privilege and defense in depth for SDL metrics.
- Prefer established patterns and libraries over custom crypto or auth for SDL metrics.
- Fail closed: deny by default when SDL metrics cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SDL metrics; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SDL metrics.
- Keep dependencies patched; pin versions for SDL metrics components.

### Verification

- Add automated tests and SAST/DAST coverage for SDL metrics paths.
- Run dependency and secret scanning on every change touching SDL metrics.
- Perform targeted manual tests (abuse cases) for SDL metrics.

### Operations

- Log security-relevant events for SDL metrics without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SDL metrics.
- Review access and configuration for SDL metrics on a regular cadence.

