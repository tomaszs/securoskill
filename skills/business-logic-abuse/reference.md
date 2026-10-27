# Rules reference: Business logic and abuse prevention

Fraud, workflows, and domain-specific attacks.

## Payment and checkout abuse

Sub-topics: Coupon stacking, Currency, Threat modeling and trust boundaries (Payment and checkout abuse), Abuse cases and adversarial testing (Payment and checkout abuse), Logging, audit, and detection (Payment and checkout abuse)

### Do

- Validate and canonicalize all inputs touching Payment and checkout abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payment and checkout abuse.
- Keep dependencies patched; pin versions for Payment and checkout abuse components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Payment and checkout abuse in Payment and checkout abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Payment and checkout abuse (Business logic and abuse prevention).
- Require security review for material changes affecting Payment and checkout abuse.

### Design

- Apply least privilege and defense in depth for Payment and checkout abuse.
- Prefer established patterns and libraries over custom crypto or auth for Payment and checkout abuse.
- Fail closed: deny by default when Payment and checkout abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Payment and checkout abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payment and checkout abuse.
- Keep dependencies patched; pin versions for Payment and checkout abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Payment and checkout abuse paths.
- Run dependency and secret scanning on every change touching Payment and checkout abuse.
- Perform targeted manual tests (abuse cases) for Payment and checkout abuse.

### Operations

- Log security-relevant events for Payment and checkout abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Payment and checkout abuse.
- Review access and configuration for Payment and checkout abuse on a regular cadence.

## Workflow bypass

Sub-topics: State machine skips, Threat modeling and trust boundaries (Workflow bypass), Abuse cases and adversarial testing (Workflow bypass), Logging, audit, and detection (Workflow bypass), Access control and least privilege (Workflow bypass)

### Do

- Validate and canonicalize all inputs touching Workflow bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workflow bypass.
- Keep dependencies patched; pin versions for Workflow bypass components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Workflow bypass in Workflow bypass as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Workflow bypass (Business logic and abuse prevention).
- Require security review for material changes affecting Workflow bypass.

### Design

- Apply least privilege and defense in depth for Workflow bypass.
- Prefer established patterns and libraries over custom crypto or auth for Workflow bypass.
- Fail closed: deny by default when Workflow bypass cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Workflow bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Workflow bypass.
- Keep dependencies patched; pin versions for Workflow bypass components.

### Verification

- Add automated tests and SAST/DAST coverage for Workflow bypass paths.
- Run dependency and secret scanning on every change touching Workflow bypass.
- Perform targeted manual tests (abuse cases) for Workflow bypass.

### Operations

- Log security-relevant events for Workflow bypass without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Workflow bypass.
- Review access and configuration for Workflow bypass on a regular cadence.

## Insecure direct object references

Sub-topics: UUID guessing, IDOR in APIs, Threat modeling and trust boundaries (Insecure direct object references), Abuse cases and adversarial testing (Insecure direct object references), Logging, audit, and detection (Insecure direct object references)

### Do

- Validate and canonicalize all inputs touching Insecure direct object references; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure direct object references.
- Keep dependencies patched; pin versions for Insecure direct object references components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Insecure direct object references in Insecure direct object references as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Insecure direct object references (Business logic and abuse prevention).
- Require security review for material changes affecting Insecure direct object references.

### Design

- Apply least privilege and defense in depth for Insecure direct object references.
- Prefer established patterns and libraries over custom crypto or auth for Insecure direct object references.
- Fail closed: deny by default when Insecure direct object references cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Insecure direct object references; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Insecure direct object references.
- Keep dependencies patched; pin versions for Insecure direct object references components.

### Verification

- Add automated tests and SAST/DAST coverage for Insecure direct object references paths.
- Run dependency and secret scanning on every change touching Insecure direct object references.
- Perform targeted manual tests (abuse cases) for Insecure direct object references.

### Operations

- Log security-relevant events for Insecure direct object references without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Insecure direct object references.
- Review access and configuration for Insecure direct object references on a regular cadence.

## Mass assignment

Sub-topics: Hidden fields, DTO allowlists, Threat modeling and trust boundaries (Mass assignment), Abuse cases and adversarial testing (Mass assignment), Logging, audit, and detection (Mass assignment)

### Do

- Validate and canonicalize all inputs touching Mass assignment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mass assignment.
- Keep dependencies patched; pin versions for Mass assignment components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Mass assignment in Mass assignment as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Mass assignment (Business logic and abuse prevention).
- Require security review for material changes affecting Mass assignment.

### Design

- Apply least privilege and defense in depth for Mass assignment.
- Prefer established patterns and libraries over custom crypto or auth for Mass assignment.
- Fail closed: deny by default when Mass assignment cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Mass assignment; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mass assignment.
- Keep dependencies patched; pin versions for Mass assignment components.

### Verification

- Add automated tests and SAST/DAST coverage for Mass assignment paths.
- Run dependency and secret scanning on every change touching Mass assignment.
- Perform targeted manual tests (abuse cases) for Mass assignment.

### Operations

- Log security-relevant events for Mass assignment without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Mass assignment.
- Review access and configuration for Mass assignment on a regular cadence.

## Bots and automation

Sub-topics: CAPTCHA alternatives, Behavior, Threat modeling and trust boundaries (Bots and automation), Abuse cases and adversarial testing (Bots and automation), Logging, audit, and detection (Bots and automation)

### Do

- Validate and canonicalize all inputs touching Bots and automation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bots and automation.
- Keep dependencies patched; pin versions for Bots and automation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Bots and automation in Bots and automation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Bots and automation (Business logic and abuse prevention).
- Require security review for material changes affecting Bots and automation.

### Design

- Apply least privilege and defense in depth for Bots and automation.
- Prefer established patterns and libraries over custom crypto or auth for Bots and automation.
- Fail closed: deny by default when Bots and automation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Bots and automation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Bots and automation.
- Keep dependencies patched; pin versions for Bots and automation components.

### Verification

- Add automated tests and SAST/DAST coverage for Bots and automation paths.
- Run dependency and secret scanning on every change touching Bots and automation.
- Perform targeted manual tests (abuse cases) for Bots and automation.

### Operations

- Log security-relevant events for Bots and automation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Bots and automation.
- Review access and configuration for Bots and automation on a regular cadence.

## Referral and loyalty abuse

Sub-topics: Self-referral, Threat modeling and trust boundaries (Referral and loyalty abuse), Abuse cases and adversarial testing (Referral and loyalty abuse), Logging, audit, and detection (Referral and loyalty abuse), Access control and least privilege (Referral and loyalty abuse)

### Do

- Validate and canonicalize all inputs touching Referral and loyalty abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Referral and loyalty abuse.
- Keep dependencies patched; pin versions for Referral and loyalty abuse components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Referral and loyalty abuse in Referral and loyalty abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Referral and loyalty abuse (Business logic and abuse prevention).
- Require security review for material changes affecting Referral and loyalty abuse.

### Design

- Apply least privilege and defense in depth for Referral and loyalty abuse.
- Prefer established patterns and libraries over custom crypto or auth for Referral and loyalty abuse.
- Fail closed: deny by default when Referral and loyalty abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Referral and loyalty abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Referral and loyalty abuse.
- Keep dependencies patched; pin versions for Referral and loyalty abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Referral and loyalty abuse paths.
- Run dependency and secret scanning on every change touching Referral and loyalty abuse.
- Perform targeted manual tests (abuse cases) for Referral and loyalty abuse.

### Operations

- Log security-relevant events for Referral and loyalty abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Referral and loyalty abuse.
- Review access and configuration for Referral and loyalty abuse on a regular cadence.

## Marketplace trust

Sub-topics: Chargeback, Escrow, Threat modeling and trust boundaries (Marketplace trust), Abuse cases and adversarial testing (Marketplace trust), Logging, audit, and detection (Marketplace trust)

### Do

- Validate and canonicalize all inputs touching Marketplace trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketplace trust.
- Keep dependencies patched; pin versions for Marketplace trust components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Marketplace trust in Marketplace trust as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Marketplace trust (Business logic and abuse prevention).
- Require security review for material changes affecting Marketplace trust.

### Design

- Apply least privilege and defense in depth for Marketplace trust.
- Prefer established patterns and libraries over custom crypto or auth for Marketplace trust.
- Fail closed: deny by default when Marketplace trust cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Marketplace trust; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketplace trust.
- Keep dependencies patched; pin versions for Marketplace trust components.

### Verification

- Add automated tests and SAST/DAST coverage for Marketplace trust paths.
- Run dependency and secret scanning on every change touching Marketplace trust.
- Perform targeted manual tests (abuse cases) for Marketplace trust.

### Operations

- Log security-relevant events for Marketplace trust without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Marketplace trust.
- Review access and configuration for Marketplace trust on a regular cadence.

## Content abuse

Sub-topics: Spam, Illegal content, Threat modeling and trust boundaries (Content abuse), Abuse cases and adversarial testing (Content abuse), Logging, audit, and detection (Content abuse)

### Do

- Validate and canonicalize all inputs touching Content abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Content abuse.
- Keep dependencies patched; pin versions for Content abuse components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Content abuse in Content abuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Content abuse (Business logic and abuse prevention).
- Require security review for material changes affecting Content abuse.

### Design

- Apply least privilege and defense in depth for Content abuse.
- Prefer established patterns and libraries over custom crypto or auth for Content abuse.
- Fail closed: deny by default when Content abuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Content abuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Content abuse.
- Keep dependencies patched; pin versions for Content abuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Content abuse paths.
- Run dependency and secret scanning on every change touching Content abuse.
- Perform targeted manual tests (abuse cases) for Content abuse.

### Operations

- Log security-relevant events for Content abuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Content abuse.
- Review access and configuration for Content abuse on a regular cadence.

## Quota and limit bypass

Sub-topics: Parallel requests, Threat modeling and trust boundaries (Quota and limit bypass), Abuse cases and adversarial testing (Quota and limit bypass), Logging, audit, and detection (Quota and limit bypass), Access control and least privilege (Quota and limit bypass)

### Do

- Validate and canonicalize all inputs touching Quota and limit bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Quota and limit bypass.
- Keep dependencies patched; pin versions for Quota and limit bypass components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Quota and limit bypass in Quota and limit bypass as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Quota and limit bypass (Business logic and abuse prevention).
- Require security review for material changes affecting Quota and limit bypass.

### Design

- Apply least privilege and defense in depth for Quota and limit bypass.
- Prefer established patterns and libraries over custom crypto or auth for Quota and limit bypass.
- Fail closed: deny by default when Quota and limit bypass cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Quota and limit bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Quota and limit bypass.
- Keep dependencies patched; pin versions for Quota and limit bypass components.

### Verification

- Add automated tests and SAST/DAST coverage for Quota and limit bypass paths.
- Run dependency and secret scanning on every change touching Quota and limit bypass.
- Perform targeted manual tests (abuse cases) for Quota and limit bypass.

### Operations

- Log security-relevant events for Quota and limit bypass without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Quota and limit bypass.
- Review access and configuration for Quota and limit bypass on a regular cadence.

## Admin misuse

Sub-topics: Separation of duties, Threat modeling and trust boundaries (Admin misuse), Abuse cases and adversarial testing (Admin misuse), Logging, audit, and detection (Admin misuse), Access control and least privilege (Admin misuse)

### Do

- Validate and canonicalize all inputs touching Admin misuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Admin misuse.
- Keep dependencies patched; pin versions for Admin misuse components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Admin misuse in Admin misuse as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Admin misuse (Business logic and abuse prevention).
- Require security review for material changes affecting Admin misuse.

### Design

- Apply least privilege and defense in depth for Admin misuse.
- Prefer established patterns and libraries over custom crypto or auth for Admin misuse.
- Fail closed: deny by default when Admin misuse cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Admin misuse; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Admin misuse.
- Keep dependencies patched; pin versions for Admin misuse components.

### Verification

- Add automated tests and SAST/DAST coverage for Admin misuse paths.
- Run dependency and secret scanning on every change touching Admin misuse.
- Perform targeted manual tests (abuse cases) for Admin misuse.

### Operations

- Log security-relevant events for Admin misuse without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Admin misuse.
- Review access and configuration for Admin misuse on a regular cadence.

## Time-based logic

Sub-topics: Timezone, Leap seconds, Threat modeling and trust boundaries (Time-based logic), Abuse cases and adversarial testing (Time-based logic), Logging, audit, and detection (Time-based logic)

### Do

- Validate and canonicalize all inputs touching Time-based logic; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Time-based logic.
- Keep dependencies patched; pin versions for Time-based logic components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Time-based logic in Time-based logic as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Time-based logic (Business logic and abuse prevention).
- Require security review for material changes affecting Time-based logic.

### Design

- Apply least privilege and defense in depth for Time-based logic.
- Prefer established patterns and libraries over custom crypto or auth for Time-based logic.
- Fail closed: deny by default when Time-based logic cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Time-based logic; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Time-based logic.
- Keep dependencies patched; pin versions for Time-based logic components.

### Verification

- Add automated tests and SAST/DAST coverage for Time-based logic paths.
- Run dependency and secret scanning on every change touching Time-based logic.
- Perform targeted manual tests (abuse cases) for Time-based logic.

### Operations

- Log security-relevant events for Time-based logic without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Time-based logic.
- Review access and configuration for Time-based logic on a regular cadence.

## Feature gating bypass

Sub-topics: Client flags, Threat modeling and trust boundaries (Feature gating bypass), Abuse cases and adversarial testing (Feature gating bypass), Logging, audit, and detection (Feature gating bypass), Access control and least privilege (Feature gating bypass)

### Do

- Validate and canonicalize all inputs touching Feature gating bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature gating bypass.
- Keep dependencies patched; pin versions for Feature gating bypass components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Feature gating bypass in Feature gating bypass as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Feature gating bypass (Business logic and abuse prevention).
- Require security review for material changes affecting Feature gating bypass.

### Design

- Apply least privilege and defense in depth for Feature gating bypass.
- Prefer established patterns and libraries over custom crypto or auth for Feature gating bypass.
- Fail closed: deny by default when Feature gating bypass cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Feature gating bypass; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Feature gating bypass.
- Keep dependencies patched; pin versions for Feature gating bypass components.

### Verification

- Add automated tests and SAST/DAST coverage for Feature gating bypass paths.
- Run dependency and secret scanning on every change touching Feature gating bypass.
- Perform targeted manual tests (abuse cases) for Feature gating bypass.

### Operations

- Log security-relevant events for Feature gating bypass without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Feature gating bypass.
- Review access and configuration for Feature gating bypass on a regular cadence.

