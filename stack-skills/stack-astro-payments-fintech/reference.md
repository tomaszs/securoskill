# Astro: Payments and financial flows

Stack-specific implementation for **Astro** (Web UI). Normative rules: domain skill `security-payments-fintech` / `reference.md`.

## Payment webhooks

**Sub-topics:** Signature verify, Idempotency, Threat modeling and trust boundaries (Payment webhooks), Abuse cases and adversarial testing (Payment webhooks), Logging, audit, and detection (Payment webhooks)

### Do (use this in Astro)

- In Astro, verify Stripe signature with `stripe.Webhook.construct_event` and raw body.
- Use idempotency keys on payment side effects.

### Don't

- Do not parse webhook JSON before signature verification.
- Do not trust `client_reference_id` without server-side ownership check.

### Verify

- Replay old webhook in test env must fail signature or timestamp check.

