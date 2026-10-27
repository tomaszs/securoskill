# Rules reference: Payments and financial flows

PCI scope, webhooks, and money movement.

## Payment webhooks

Sub-topics: Signature verify, Idempotency

### Policy

- Treat Payment webhooks in Payment webhooks as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Payment webhooks (Payments and financial flows).
- Require security review for material changes affecting Payment webhooks.

### Design

- Apply least privilege and defense in depth for Payment webhooks.
- Prefer established patterns and libraries over custom crypto or auth for Payment webhooks.
- Fail closed: deny by default when Payment webhooks cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Payment webhooks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payment webhooks.
- Keep dependencies patched; pin versions for Payment webhooks components.

### Verification

- Add automated tests and SAST/DAST coverage for Payment webhooks paths.
- Run dependency and secret scanning on every change touching Payment webhooks.
- Perform targeted manual tests (abuse cases) for Payment webhooks.

### Operations

- Log security-relevant events for Payment webhooks without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Payment webhooks.
- Review access and configuration for Payment webhooks on a regular cadence.

## Card data handling

Sub-topics: Tokenization, SAQ-A

### Policy

- Treat Card data handling in Card data handling as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Card data handling (Payments and financial flows).
- Require security review for material changes affecting Card data handling.

### Design

- Apply least privilege and defense in depth for Card data handling.
- Prefer established patterns and libraries over custom crypto or auth for Card data handling.
- Fail closed: deny by default when Card data handling cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Card data handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Card data handling.
- Keep dependencies patched; pin versions for Card data handling components.

### Verification

- Add automated tests and SAST/DAST coverage for Card data handling paths.
- Run dependency and secret scanning on every change touching Card data handling.
- Perform targeted manual tests (abuse cases) for Card data handling.

### Operations

- Log security-relevant events for Card data handling without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Card data handling.
- Review access and configuration for Card data handling on a regular cadence.

## Refunds and disputes

Sub-topics: Authorization

### Policy

- Treat Refunds and disputes in Refunds and disputes as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Refunds and disputes (Payments and financial flows).
- Require security review for material changes affecting Refunds and disputes.

### Design

- Apply least privilege and defense in depth for Refunds and disputes.
- Prefer established patterns and libraries over custom crypto or auth for Refunds and disputes.
- Fail closed: deny by default when Refunds and disputes cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Refunds and disputes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Refunds and disputes.
- Keep dependencies patched; pin versions for Refunds and disputes components.

### Verification

- Add automated tests and SAST/DAST coverage for Refunds and disputes paths.
- Run dependency and secret scanning on every change touching Refunds and disputes.
- Perform targeted manual tests (abuse cases) for Refunds and disputes.

### Operations

- Log security-relevant events for Refunds and disputes without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Refunds and disputes.
- Review access and configuration for Refunds and disputes on a regular cadence.

## Currency and rounding

Sub-topics: Manipulation

### Policy

- Treat Currency and rounding in Currency and rounding as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Currency and rounding (Payments and financial flows).
- Require security review for material changes affecting Currency and rounding.

### Design

- Apply least privilege and defense in depth for Currency and rounding.
- Prefer established patterns and libraries over custom crypto or auth for Currency and rounding.
- Fail closed: deny by default when Currency and rounding cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Currency and rounding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Currency and rounding.
- Keep dependencies patched; pin versions for Currency and rounding components.

### Verification

- Add automated tests and SAST/DAST coverage for Currency and rounding paths.
- Run dependency and secret scanning on every change touching Currency and rounding.
- Perform targeted manual tests (abuse cases) for Currency and rounding.

### Operations

- Log security-relevant events for Currency and rounding without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Currency and rounding.
- Review access and configuration for Currency and rounding on a regular cadence.

## PCI scoping

Sub-topics: Networks, Segmentation

### Policy

- Treat PCI scoping in PCI scoping as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for PCI scoping (Payments and financial flows).
- Require security review for material changes affecting PCI scoping.

### Design

- Apply least privilege and defense in depth for PCI scoping.
- Prefer established patterns and libraries over custom crypto or auth for PCI scoping.
- Fail closed: deny by default when PCI scoping cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching PCI scoping; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PCI scoping.
- Keep dependencies patched; pin versions for PCI scoping components.

### Verification

- Add automated tests and SAST/DAST coverage for PCI scoping paths.
- Run dependency and secret scanning on every change touching PCI scoping.
- Perform targeted manual tests (abuse cases) for PCI scoping.

### Operations

- Log security-relevant events for PCI scoping without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in PCI scoping.
- Review access and configuration for PCI scoping on a regular cadence.

## 3-D Secure flows

Sub-topics: Friction, Bypass

### Policy

- Treat 3-D Secure flows in 3-D Secure flows as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for 3-D Secure flows (Payments and financial flows).
- Require security review for material changes affecting 3-D Secure flows.

### Design

- Apply least privilege and defense in depth for 3-D Secure flows.
- Prefer established patterns and libraries over custom crypto or auth for 3-D Secure flows.
- Fail closed: deny by default when 3-D Secure flows cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching 3-D Secure flows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to 3-D Secure flows.
- Keep dependencies patched; pin versions for 3-D Secure flows components.

### Verification

- Add automated tests and SAST/DAST coverage for 3-D Secure flows paths.
- Run dependency and secret scanning on every change touching 3-D Secure flows.
- Perform targeted manual tests (abuse cases) for 3-D Secure flows.

### Operations

- Log security-relevant events for 3-D Secure flows without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in 3-D Secure flows.
- Review access and configuration for 3-D Secure flows on a regular cadence.

## Digital wallets

Sub-topics: Apple Pay, Google Pay

### Policy

- Treat Digital wallets in Digital wallets as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Digital wallets (Payments and financial flows).
- Require security review for material changes affecting Digital wallets.

### Design

- Apply least privilege and defense in depth for Digital wallets.
- Prefer established patterns and libraries over custom crypto or auth for Digital wallets.
- Fail closed: deny by default when Digital wallets cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Digital wallets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Digital wallets.
- Keep dependencies patched; pin versions for Digital wallets components.

### Verification

- Add automated tests and SAST/DAST coverage for Digital wallets paths.
- Run dependency and secret scanning on every change touching Digital wallets.
- Perform targeted manual tests (abuse cases) for Digital wallets.

### Operations

- Log security-relevant events for Digital wallets without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Digital wallets.
- Review access and configuration for Digital wallets on a regular cadence.

## Payouts and KYC

Sub-topics: AML hooks

### Policy

- Treat Payouts and KYC in Payouts and KYC as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Payouts and KYC (Payments and financial flows).
- Require security review for material changes affecting Payouts and KYC.

### Design

- Apply least privilege and defense in depth for Payouts and KYC.
- Prefer established patterns and libraries over custom crypto or auth for Payouts and KYC.
- Fail closed: deny by default when Payouts and KYC cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Payouts and KYC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payouts and KYC.
- Keep dependencies patched; pin versions for Payouts and KYC components.

### Verification

- Add automated tests and SAST/DAST coverage for Payouts and KYC paths.
- Run dependency and secret scanning on every change touching Payouts and KYC.
- Perform targeted manual tests (abuse cases) for Payouts and KYC.

### Operations

- Log security-relevant events for Payouts and KYC without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Payouts and KYC.
- Review access and configuration for Payouts and KYC on a regular cadence.

## Internal ledger integrity

Sub-topics: Double entry, Audit

### Policy

- Treat Internal ledger integrity in Internal ledger integrity as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Internal ledger integrity (Payments and financial flows).
- Require security review for material changes affecting Internal ledger integrity.

### Design

- Apply least privilege and defense in depth for Internal ledger integrity.
- Prefer established patterns and libraries over custom crypto or auth for Internal ledger integrity.
- Fail closed: deny by default when Internal ledger integrity cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Internal ledger integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Internal ledger integrity.
- Keep dependencies patched; pin versions for Internal ledger integrity components.

### Verification

- Add automated tests and SAST/DAST coverage for Internal ledger integrity paths.
- Run dependency and secret scanning on every change touching Internal ledger integrity.
- Perform targeted manual tests (abuse cases) for Internal ledger integrity.

### Operations

- Log security-relevant events for Internal ledger integrity without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Internal ledger integrity.
- Review access and configuration for Internal ledger integrity on a regular cadence.

## Tax and invoicing

Sub-topics: Tampering

### Policy

- Treat Tax and invoicing in Tax and invoicing as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Tax and invoicing (Payments and financial flows).
- Require security review for material changes affecting Tax and invoicing.

### Design

- Apply least privilege and defense in depth for Tax and invoicing.
- Prefer established patterns and libraries over custom crypto or auth for Tax and invoicing.
- Fail closed: deny by default when Tax and invoicing cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Tax and invoicing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tax and invoicing.
- Keep dependencies patched; pin versions for Tax and invoicing components.

### Verification

- Add automated tests and SAST/DAST coverage for Tax and invoicing paths.
- Run dependency and secret scanning on every change touching Tax and invoicing.
- Perform targeted manual tests (abuse cases) for Tax and invoicing.

### Operations

- Log security-relevant events for Tax and invoicing without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Tax and invoicing.
- Review access and configuration for Tax and invoicing on a regular cadence.

## Subscription logic

Sub-topics: Proration abuse

### Policy

- Treat Subscription logic in Subscription logic as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Subscription logic (Payments and financial flows).
- Require security review for material changes affecting Subscription logic.

### Design

- Apply least privilege and defense in depth for Subscription logic.
- Prefer established patterns and libraries over custom crypto or auth for Subscription logic.
- Fail closed: deny by default when Subscription logic cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Subscription logic; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Subscription logic.
- Keep dependencies patched; pin versions for Subscription logic components.

### Verification

- Add automated tests and SAST/DAST coverage for Subscription logic paths.
- Run dependency and secret scanning on every change touching Subscription logic.
- Perform targeted manual tests (abuse cases) for Subscription logic.

### Operations

- Log security-relevant events for Subscription logic without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Subscription logic.
- Review access and configuration for Subscription logic on a regular cadence.

## Fraud scoring

Sub-topics: Bias, Explainability

### Policy

- Treat Fraud scoring in Fraud scoring as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Fraud scoring (Payments and financial flows).
- Require security review for material changes affecting Fraud scoring.

### Design

- Apply least privilege and defense in depth for Fraud scoring.
- Prefer established patterns and libraries over custom crypto or auth for Fraud scoring.
- Fail closed: deny by default when Fraud scoring cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Fraud scoring; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fraud scoring.
- Keep dependencies patched; pin versions for Fraud scoring components.

### Verification

- Add automated tests and SAST/DAST coverage for Fraud scoring paths.
- Run dependency and secret scanning on every change touching Fraud scoring.
- Perform targeted manual tests (abuse cases) for Fraud scoring.

### Operations

- Log security-relevant events for Fraud scoring without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Fraud scoring.
- Review access and configuration for Fraud scoring on a regular cadence.

