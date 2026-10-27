# Hibernate / JPA: Mobile application security

Stack-specific implementation for **Hibernate / JPA** (ORM / data access). Normative rules: domain skill `security-mobile-security` / `reference.md`.

## On-device storage

**Sub-topics:** Keychain, Keystore, SQLite, Threat modeling and trust boundaries (On-device storage), Abuse cases and adversarial testing (On-device storage)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Certificate pinning

**Sub-topics:** Bypass tools, Rotation, Threat modeling and trust boundaries (Certificate pinning), Abuse cases and adversarial testing (Certificate pinning), Logging, audit, and detection (Certificate pinning)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Reverse engineering resistance

**Sub-topics:** Obfuscation limits, Threat modeling and trust boundaries (Reverse engineering resistance), Abuse cases and adversarial testing (Reverse engineering resistance), Logging, audit, and detection (Reverse engineering resistance), Access control and least privilege (Reverse engineering resistance)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Deep links and intents

**Sub-topics:** URL scheme hijack, Threat modeling and trust boundaries (Deep links and intents), Abuse cases and adversarial testing (Deep links and intents), Logging, audit, and detection (Deep links and intents), Access control and least privilege (Deep links and intents)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Mobile OAuth

**Sub-topics:** PKCE, Custom URL schemes, Threat modeling and trust boundaries (Mobile OAuth), Abuse cases and adversarial testing (Mobile OAuth), Logging, audit, and detection (Mobile OAuth)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Biometric APIs

**Sub-topics:** Fallback PIN, Threat modeling and trust boundaries (Biometric APIs), Abuse cases and adversarial testing (Biometric APIs), Logging, audit, and detection (Biometric APIs), Access control and least privilege (Biometric APIs)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## WebView bridges

**Sub-topics:** JS interfaces, Threat modeling and trust boundaries (WebView bridges), Abuse cases and adversarial testing (WebView bridges), Logging, audit, and detection (WebView bridges), Access control and least privilege (WebView bridges)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Push notifications

**Sub-topics:** Payload sensitivity, Threat modeling and trust boundaries (Push notifications), Abuse cases and adversarial testing (Push notifications), Logging, audit, and detection (Push notifications), Access control and least privilege (Push notifications)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## App attestation

**Sub-topics:** DeviceCheck, Play Integrity, Threat modeling and trust boundaries (App attestation), Abuse cases and adversarial testing (App attestation), Logging, audit, and detection (App attestation)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Sideloading and jailbreak

**Sub-topics:** Root detection limits, Threat modeling and trust boundaries (Sideloading and jailbreak), Abuse cases and adversarial testing (Sideloading and jailbreak), Logging, audit, and detection (Sideloading and jailbreak), Access control and least privilege (Sideloading and jailbreak)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Screenshots and overlays

**Sub-topics:** FLAG_SECURE, Overlay attacks, Threat modeling and trust boundaries (Screenshots and overlays), Abuse cases and adversarial testing (Screenshots and overlays), Logging, audit, and detection (Screenshots and overlays)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

## Mobile SDK supply chain

**Sub-topics:** Third-party SDKs, Threat modeling and trust boundaries (Mobile SDK supply chain), Abuse cases and adversarial testing (Mobile SDK supply chain), Logging, audit, and detection (Mobile SDK supply chain), Access control and least privilege (Mobile SDK supply chain)

### Do (use this in Hibernate / JPA)

- Hibernate / JPA is not the primary enforcement point for `mobile-security`; load stack skill `security-mobile-security` when you touch that layer.
- Keep Hibernate / JPA configuration aligned with requirements from `security-mobile-security` (domain reference.md).

### Don't

- Do not duplicate `mobile-security` controls only in Hibernate / JPA config while leaving security-mobile-security misconfigured.
- Do not assume Hibernate / JPA defaults satisfy `security-mobile-security` without verification.

### Verify

- Integration test the full path: Hibernate / JPA plus the system covered by `security-mobile-security`.

