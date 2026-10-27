# Vercel: Payments and financial flows

Stack-specific implementation for **Vercel** (Platform). Normative rules: domain skill `security-payments-fintech` / `reference.md`.

## Payment webhooks

**Sub-topics:** Signature verify, Idempotency, Threat modeling and trust boundaries (Payment webhooks), Abuse cases and adversarial testing (Payment webhooks), Logging, audit, and detection (Payment webhooks)

### Do (use this in Vercel)

- In Vercel, verify Stripe signature with `stripe.Webhook.construct_event` and raw body.
- Use idempotency keys on payment side effects.

### Don't

- Do not parse webhook JSON before signature verification.
- Do not trust `client_reference_id` without server-side ownership check.

### Verify

- Replay old webhook in test env must fail signature or timestamp check.

## Card data handling

**Sub-topics:** Tokenization, SAQ-A, Threat modeling and trust boundaries (Card data handling), Abuse cases and adversarial testing (Card data handling), Logging, audit, and detection (Card data handling)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Refunds and disputes

**Sub-topics:** Authorization, Threat modeling and trust boundaries (Refunds and disputes), Abuse cases and adversarial testing (Refunds and disputes), Logging, audit, and detection (Refunds and disputes), Access control and least privilege (Refunds and disputes)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Currency and rounding

**Sub-topics:** Manipulation, Threat modeling and trust boundaries (Currency and rounding), Abuse cases and adversarial testing (Currency and rounding), Logging, audit, and detection (Currency and rounding), Access control and least privilege (Currency and rounding)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## PCI scoping

**Sub-topics:** Networks, Segmentation, Threat modeling and trust boundaries (PCI scoping), Abuse cases and adversarial testing (PCI scoping), Logging, audit, and detection (PCI scoping)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## 3-D Secure flows

**Sub-topics:** Friction, Bypass, Threat modeling and trust boundaries (3-D Secure flows), Abuse cases and adversarial testing (3-D Secure flows), Logging, audit, and detection (3-D Secure flows)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Digital wallets

**Sub-topics:** Apple Pay, Google Pay, Threat modeling and trust boundaries (Digital wallets), Abuse cases and adversarial testing (Digital wallets), Logging, audit, and detection (Digital wallets)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Payouts and KYC

**Sub-topics:** AML hooks, Threat modeling and trust boundaries (Payouts and KYC), Abuse cases and adversarial testing (Payouts and KYC), Logging, audit, and detection (Payouts and KYC), Access control and least privilege (Payouts and KYC)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Internal ledger integrity

**Sub-topics:** Double entry, Audit, Threat modeling and trust boundaries (Internal ledger integrity), Abuse cases and adversarial testing (Internal ledger integrity), Logging, audit, and detection (Internal ledger integrity)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Tax and invoicing

**Sub-topics:** Tampering, Threat modeling and trust boundaries (Tax and invoicing), Abuse cases and adversarial testing (Tax and invoicing), Logging, audit, and detection (Tax and invoicing), Access control and least privilege (Tax and invoicing)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Subscription logic

**Sub-topics:** Proration abuse, Threat modeling and trust boundaries (Subscription logic), Abuse cases and adversarial testing (Subscription logic), Logging, audit, and detection (Subscription logic), Access control and least privilege (Subscription logic)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

## Fraud scoring

**Sub-topics:** Bias, Explainability, Threat modeling and trust boundaries (Fraud scoring), Abuse cases and adversarial testing (Fraud scoring), Logging, audit, and detection (Fraud scoring)

### Do (use this in Vercel)

- Vercel is not the primary enforcement point for `payments-fintech`; load stack skill `security-payments-fintech` when you touch that layer.
- Keep Vercel configuration aligned with requirements from `security-payments-fintech` (domain reference.md).

### Don't

- Do not duplicate `payments-fintech` controls only in Vercel config while leaving security-payments-fintech misconfigured.
- Do not assume Vercel defaults satisfy `security-payments-fintech` without verification.

### Verify

- Integration test the full path: Vercel plus the system covered by `security-payments-fintech`.

