# Django: Payments and financial flows

Stack-specific implementation for **Django** (Python). Normative rules: domain skill `security-payments-fintech` / `reference.md`.

## Payment webhooks

**Sub-topics:** Signature verify, Idempotency, Threat modeling and trust boundaries (Payment webhooks), Abuse cases and adversarial testing (Payment webhooks), Logging, audit, and detection (Payment webhooks)

### Do (use this in Django)

- In Django, verify Stripe signature with `stripe.Webhook.construct_event` and raw body.
- Use idempotency keys on payment side effects.

### Don't

- Do not parse webhook JSON before signature verification.
- Do not trust `client_reference_id` without server-side ownership check.

### Verify

- Replay old webhook in test env must fail signature or timestamp check.

## Card data handling

**Sub-topics:** Tokenization, SAQ-A, Threat modeling and trust boundaries (Card data handling), Abuse cases and adversarial testing (Card data handling), Logging, audit, and detection (Card data handling)

### Do (use this in Django)

- Map `Card data handling` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Card data handling` before merge.

### Don't

- Do not ship `Card data handling` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Card data handling`.

### Verify

- Peer review `Card data handling` against domain skill `security-payments-fintech`.

## Refunds and disputes

**Sub-topics:** Authorization, Threat modeling and trust boundaries (Refunds and disputes), Abuse cases and adversarial testing (Refunds and disputes), Logging, audit, and detection (Refunds and disputes), Access control and least privilege (Refunds and disputes)

### Do (use this in Django)

- Map `Refunds and disputes` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Refunds and disputes` before merge.

### Don't

- Do not ship `Refunds and disputes` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Refunds and disputes`.

### Verify

- Peer review `Refunds and disputes` against domain skill `security-payments-fintech`.

## Currency and rounding

**Sub-topics:** Manipulation, Threat modeling and trust boundaries (Currency and rounding), Abuse cases and adversarial testing (Currency and rounding), Logging, audit, and detection (Currency and rounding), Access control and least privilege (Currency and rounding)

### Do (use this in Django)

- Map `Currency and rounding` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Currency and rounding` before merge.

### Don't

- Do not ship `Currency and rounding` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Currency and rounding`.

### Verify

- Peer review `Currency and rounding` against domain skill `security-payments-fintech`.

## PCI scoping

**Sub-topics:** Networks, Segmentation, Threat modeling and trust boundaries (PCI scoping), Abuse cases and adversarial testing (PCI scoping), Logging, audit, and detection (PCI scoping)

### Do (use this in Django)

- Map `PCI scoping` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `PCI scoping` before merge.

### Don't

- Do not ship `PCI scoping` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `PCI scoping`.

### Verify

- Peer review `PCI scoping` against domain skill `security-payments-fintech`.

## 3-D Secure flows

**Sub-topics:** Friction, Bypass, Threat modeling and trust boundaries (3-D Secure flows), Abuse cases and adversarial testing (3-D Secure flows), Logging, audit, and detection (3-D Secure flows)

### Do (use this in Django)

- Map `3-D Secure flows` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `3-D Secure flows` before merge.

### Don't

- Do not ship `3-D Secure flows` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `3-D Secure flows`.

### Verify

- Peer review `3-D Secure flows` against domain skill `security-payments-fintech`.

## Digital wallets

**Sub-topics:** Apple Pay, Google Pay, Threat modeling and trust boundaries (Digital wallets), Abuse cases and adversarial testing (Digital wallets), Logging, audit, and detection (Digital wallets)

### Do (use this in Django)

- Map `Digital wallets` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Digital wallets` before merge.

### Don't

- Do not ship `Digital wallets` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Digital wallets`.

### Verify

- Peer review `Digital wallets` against domain skill `security-payments-fintech`.

## Payouts and KYC

**Sub-topics:** AML hooks, Threat modeling and trust boundaries (Payouts and KYC), Abuse cases and adversarial testing (Payouts and KYC), Logging, audit, and detection (Payouts and KYC), Access control and least privilege (Payouts and KYC)

### Do (use this in Django)

- Map `Payouts and KYC` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Payouts and KYC` before merge.

### Don't

- Do not ship `Payouts and KYC` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Payouts and KYC`.

### Verify

- Peer review `Payouts and KYC` against domain skill `security-payments-fintech`.

## Internal ledger integrity

**Sub-topics:** Double entry, Audit, Threat modeling and trust boundaries (Internal ledger integrity), Abuse cases and adversarial testing (Internal ledger integrity), Logging, audit, and detection (Internal ledger integrity)

### Do (use this in Django)

- Map `Internal ledger integrity` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Internal ledger integrity` before merge.

### Don't

- Do not ship `Internal ledger integrity` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Internal ledger integrity`.

### Verify

- Peer review `Internal ledger integrity` against domain skill `security-payments-fintech`.

## Tax and invoicing

**Sub-topics:** Tampering, Threat modeling and trust boundaries (Tax and invoicing), Abuse cases and adversarial testing (Tax and invoicing), Logging, audit, and detection (Tax and invoicing), Access control and least privilege (Tax and invoicing)

### Do (use this in Django)

- Map `Tax and invoicing` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Tax and invoicing` before merge.

### Don't

- Do not ship `Tax and invoicing` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Tax and invoicing`.

### Verify

- Peer review `Tax and invoicing` against domain skill `security-payments-fintech`.

## Subscription logic

**Sub-topics:** Proration abuse, Threat modeling and trust boundaries (Subscription logic), Abuse cases and adversarial testing (Subscription logic), Logging, audit, and detection (Subscription logic), Access control and least privilege (Subscription logic)

### Do (use this in Django)

- Map `Subscription logic` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Subscription logic` before merge.

### Don't

- Do not ship `Subscription logic` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Subscription logic`.

### Verify

- Peer review `Subscription logic` against domain skill `security-payments-fintech`.

## Fraud scoring

**Sub-topics:** Bias, Explainability, Threat modeling and trust boundaries (Fraud scoring), Abuse cases and adversarial testing (Fraud scoring), Logging, audit, and detection (Fraud scoring)

### Do (use this in Django)

- Map `Fraud scoring` controls to Django APIs documented for `security-payments-fintech`.
- Add an abuse-case test or check for `Fraud scoring` before merge.

### Don't

- Do not ship `Fraud scoring` work in Django with only happy-path tests.
- Do not disable Django security defaults to unblock `Fraud scoring`.

### Verify

- Peer review `Fraud scoring` against domain skill `security-payments-fintech`.

