# Gin (Go): Payments and financial flows

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-payments-fintech` / `reference.md`.

## Payment webhooks

**Sub-topics:** Signature verify, Idempotency, Threat modeling and trust boundaries (Payment webhooks), Abuse cases and adversarial testing (Payment webhooks), Logging, audit, and detection (Payment webhooks)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Payment webhooks; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payment webhooks.
- Keep dependencies patched; pin versions for Payment webhooks components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Payment webhooks before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Payment webhooks paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Card data handling

**Sub-topics:** Tokenization, SAQ-A, Threat modeling and trust boundaries (Card data handling), Abuse cases and adversarial testing (Card data handling), Logging, audit, and detection (Card data handling)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Card data handling; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Card data handling.
- Keep dependencies patched; pin versions for Card data handling components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Card data handling before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Card data handling paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Refunds and disputes

**Sub-topics:** Authorization, Threat modeling and trust boundaries (Refunds and disputes), Abuse cases and adversarial testing (Refunds and disputes), Logging, audit, and detection (Refunds and disputes), Access control and least privilege (Refunds and disputes)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Refunds and disputes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Refunds and disputes.
- Keep dependencies patched; pin versions for Refunds and disputes components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Refunds and disputes before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Refunds and disputes paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Currency and rounding

**Sub-topics:** Manipulation, Threat modeling and trust boundaries (Currency and rounding), Abuse cases and adversarial testing (Currency and rounding), Logging, audit, and detection (Currency and rounding), Access control and least privilege (Currency and rounding)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Currency and rounding; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Currency and rounding.
- Keep dependencies patched; pin versions for Currency and rounding components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Currency and rounding before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Currency and rounding paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## PCI scoping

**Sub-topics:** Networks, Segmentation, Threat modeling and trust boundaries (PCI scoping), Abuse cases and adversarial testing (PCI scoping), Logging, audit, and detection (PCI scoping)

### Platform rules (summary)

- Validate and canonicalize all inputs touching PCI scoping; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to PCI scoping.
- Keep dependencies patched; pin versions for PCI scoping components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for PCI scoping before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for PCI scoping paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## 3-D Secure flows

**Sub-topics:** Friction, Bypass, Threat modeling and trust boundaries (3-D Secure flows), Abuse cases and adversarial testing (3-D Secure flows), Logging, audit, and detection (3-D Secure flows)

### Platform rules (summary)

- Validate and canonicalize all inputs touching 3-D Secure flows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to 3-D Secure flows.
- Keep dependencies patched; pin versions for 3-D Secure flows components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for 3-D Secure flows before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for 3-D Secure flows paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Digital wallets

**Sub-topics:** Apple Pay, Google Pay, Threat modeling and trust boundaries (Digital wallets), Abuse cases and adversarial testing (Digital wallets), Logging, audit, and detection (Digital wallets)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Digital wallets; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Digital wallets.
- Keep dependencies patched; pin versions for Digital wallets components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Digital wallets before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Digital wallets paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Payouts and KYC

**Sub-topics:** AML hooks, Threat modeling and trust boundaries (Payouts and KYC), Abuse cases and adversarial testing (Payouts and KYC), Logging, audit, and detection (Payouts and KYC), Access control and least privilege (Payouts and KYC)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Payouts and KYC; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Payouts and KYC.
- Keep dependencies patched; pin versions for Payouts and KYC components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Payouts and KYC before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Payouts and KYC paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Internal ledger integrity

**Sub-topics:** Double entry, Audit, Threat modeling and trust boundaries (Internal ledger integrity), Abuse cases and adversarial testing (Internal ledger integrity), Logging, audit, and detection (Internal ledger integrity)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Internal ledger integrity; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Internal ledger integrity.
- Keep dependencies patched; pin versions for Internal ledger integrity components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Internal ledger integrity before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Internal ledger integrity paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Tax and invoicing

**Sub-topics:** Tampering, Threat modeling and trust boundaries (Tax and invoicing), Abuse cases and adversarial testing (Tax and invoicing), Logging, audit, and detection (Tax and invoicing), Access control and least privilege (Tax and invoicing)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Tax and invoicing; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Tax and invoicing.
- Keep dependencies patched; pin versions for Tax and invoicing components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Tax and invoicing before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Tax and invoicing paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Subscription logic

**Sub-topics:** Proration abuse, Threat modeling and trust boundaries (Subscription logic), Abuse cases and adversarial testing (Subscription logic), Logging, audit, and detection (Subscription logic), Access control and least privilege (Subscription logic)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Subscription logic; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Subscription logic.
- Keep dependencies patched; pin versions for Subscription logic components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Subscription logic before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Subscription logic paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

## Fraud scoring

**Sub-topics:** Bias, Explainability, Threat modeling and trust boundaries (Fraud scoring), Abuse cases and adversarial testing (Fraud scoring), Logging, audit, and detection (Fraud scoring)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Fraud scoring; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Fraud scoring.
- Keep dependencies patched; pin versions for Fraud scoring components.

### How to do this in Gin (Go)

- Read normative rules in domain skill `security-payments-fintech` / `reference.md`, then apply them using Gin (Go) APIs and deployment model.
- Prefer framework-maintained security features in Gin (Go) over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Fraud scoring before merge.
- Pin Gin (Go) dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Fraud scoring paths in Gin (Go).
- Run SAST/dependency scan configured for Go.

