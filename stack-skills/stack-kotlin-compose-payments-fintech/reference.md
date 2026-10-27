# Kotlin / Jetpack Compose: Payments and financial flows

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-payments-fintech` / `reference.md`.

## Payment webhooks

**Sub-topics:** Signature verify, Idempotency, Threat modeling and trust boundaries (Payment webhooks), Abuse cases and adversarial testing (Payment webhooks), Logging, audit, and detection (Payment webhooks)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Card data handling

**Sub-topics:** Tokenization, SAQ-A, Threat modeling and trust boundaries (Card data handling), Abuse cases and adversarial testing (Card data handling), Logging, audit, and detection (Card data handling)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Refunds and disputes

**Sub-topics:** Authorization, Threat modeling and trust boundaries (Refunds and disputes), Abuse cases and adversarial testing (Refunds and disputes), Logging, audit, and detection (Refunds and disputes), Access control and least privilege (Refunds and disputes)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Currency and rounding

**Sub-topics:** Manipulation, Threat modeling and trust boundaries (Currency and rounding), Abuse cases and adversarial testing (Currency and rounding), Logging, audit, and detection (Currency and rounding), Access control and least privilege (Currency and rounding)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## PCI scoping

**Sub-topics:** Networks, Segmentation, Threat modeling and trust boundaries (PCI scoping), Abuse cases and adversarial testing (PCI scoping), Logging, audit, and detection (PCI scoping)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## 3-D Secure flows

**Sub-topics:** Friction, Bypass, Threat modeling and trust boundaries (3-D Secure flows), Abuse cases and adversarial testing (3-D Secure flows), Logging, audit, and detection (3-D Secure flows)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Digital wallets

**Sub-topics:** Apple Pay, Google Pay, Threat modeling and trust boundaries (Digital wallets), Abuse cases and adversarial testing (Digital wallets), Logging, audit, and detection (Digital wallets)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Payouts and KYC

**Sub-topics:** AML hooks, Threat modeling and trust boundaries (Payouts and KYC), Abuse cases and adversarial testing (Payouts and KYC), Logging, audit, and detection (Payouts and KYC), Access control and least privilege (Payouts and KYC)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Internal ledger integrity

**Sub-topics:** Double entry, Audit, Threat modeling and trust boundaries (Internal ledger integrity), Abuse cases and adversarial testing (Internal ledger integrity), Logging, audit, and detection (Internal ledger integrity)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Tax and invoicing

**Sub-topics:** Tampering, Threat modeling and trust boundaries (Tax and invoicing), Abuse cases and adversarial testing (Tax and invoicing), Logging, audit, and detection (Tax and invoicing), Access control and least privilege (Tax and invoicing)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Subscription logic

**Sub-topics:** Proration abuse, Threat modeling and trust boundaries (Subscription logic), Abuse cases and adversarial testing (Subscription logic), Logging, audit, and detection (Subscription logic), Access control and least privilege (Subscription logic)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Fraud scoring

**Sub-topics:** Bias, Explainability, Threat modeling and trust boundaries (Fraud scoring), Abuse cases and adversarial testing (Fraud scoring), Logging, audit, and detection (Fraud scoring)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

