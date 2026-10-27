# Flutter: Mobile application security

Stack-specific implementation for **Flutter** (Mobile). Normative rules: domain skill `security-mobile-security` / `reference.md`.

## On-device storage

**Sub-topics:** Keychain, Keystore, SQLite, Threat modeling and trust boundaries (On-device storage), Abuse cases and adversarial testing (On-device storage)

### Do (use this in Flutter)

- Map `On-device storage` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `On-device storage` before merge.

### Don't

- Do not ship `On-device storage` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `On-device storage`.

### Verify

- Peer review `On-device storage` against domain skill `security-mobile-security`.

## Certificate pinning

**Sub-topics:** Bypass tools, Rotation, Threat modeling and trust boundaries (Certificate pinning), Abuse cases and adversarial testing (Certificate pinning), Logging, audit, and detection (Certificate pinning)

### Do (use this in Flutter)

- Map `Certificate pinning` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Certificate pinning` before merge.

### Don't

- Do not ship `Certificate pinning` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Certificate pinning`.

### Verify

- Peer review `Certificate pinning` against domain skill `security-mobile-security`.

## Reverse engineering resistance

**Sub-topics:** Obfuscation limits, Threat modeling and trust boundaries (Reverse engineering resistance), Abuse cases and adversarial testing (Reverse engineering resistance), Logging, audit, and detection (Reverse engineering resistance), Access control and least privilege (Reverse engineering resistance)

### Do (use this in Flutter)

- Map `Reverse engineering resistance` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Reverse engineering resistance` before merge.

### Don't

- Do not ship `Reverse engineering resistance` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Reverse engineering resistance`.

### Verify

- Peer review `Reverse engineering resistance` against domain skill `security-mobile-security`.

## Deep links and intents

**Sub-topics:** URL scheme hijack, Threat modeling and trust boundaries (Deep links and intents), Abuse cases and adversarial testing (Deep links and intents), Logging, audit, and detection (Deep links and intents), Access control and least privilege (Deep links and intents)

### Do (use this in Flutter)

- Map `Deep links and intents` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Deep links and intents` before merge.

### Don't

- Do not ship `Deep links and intents` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Deep links and intents`.

### Verify

- Peer review `Deep links and intents` against domain skill `security-mobile-security`.

## Mobile OAuth

**Sub-topics:** PKCE, Custom URL schemes, Threat modeling and trust boundaries (Mobile OAuth), Abuse cases and adversarial testing (Mobile OAuth), Logging, audit, and detection (Mobile OAuth)

### Do (use this in Flutter)

- Map `Mobile OAuth` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Mobile OAuth` before merge.

### Don't

- Do not ship `Mobile OAuth` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Mobile OAuth`.

### Verify

- Peer review `Mobile OAuth` against domain skill `security-mobile-security`.

## Biometric APIs

**Sub-topics:** Fallback PIN, Threat modeling and trust boundaries (Biometric APIs), Abuse cases and adversarial testing (Biometric APIs), Logging, audit, and detection (Biometric APIs), Access control and least privilege (Biometric APIs)

### Do (use this in Flutter)

- Map `Biometric APIs` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Biometric APIs` before merge.

### Don't

- Do not ship `Biometric APIs` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Biometric APIs`.

### Verify

- Peer review `Biometric APIs` against domain skill `security-mobile-security`.

## WebView bridges

**Sub-topics:** JS interfaces, Threat modeling and trust boundaries (WebView bridges), Abuse cases and adversarial testing (WebView bridges), Logging, audit, and detection (WebView bridges), Access control and least privilege (WebView bridges)

### Do (use this in Flutter)

- Map `WebView bridges` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `WebView bridges` before merge.

### Don't

- Do not ship `WebView bridges` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `WebView bridges`.

### Verify

- Peer review `WebView bridges` against domain skill `security-mobile-security`.

## Push notifications

**Sub-topics:** Payload sensitivity, Threat modeling and trust boundaries (Push notifications), Abuse cases and adversarial testing (Push notifications), Logging, audit, and detection (Push notifications), Access control and least privilege (Push notifications)

### Do (use this in Flutter)

- Map `Push notifications` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Push notifications` before merge.

### Don't

- Do not ship `Push notifications` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Push notifications`.

### Verify

- Peer review `Push notifications` against domain skill `security-mobile-security`.

## App attestation

**Sub-topics:** DeviceCheck, Play Integrity, Threat modeling and trust boundaries (App attestation), Abuse cases and adversarial testing (App attestation), Logging, audit, and detection (App attestation)

### Do (use this in Flutter)

- Map `App attestation` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `App attestation` before merge.

### Don't

- Do not ship `App attestation` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `App attestation`.

### Verify

- Peer review `App attestation` against domain skill `security-mobile-security`.

## Sideloading and jailbreak

**Sub-topics:** Root detection limits, Threat modeling and trust boundaries (Sideloading and jailbreak), Abuse cases and adversarial testing (Sideloading and jailbreak), Logging, audit, and detection (Sideloading and jailbreak), Access control and least privilege (Sideloading and jailbreak)

### Do (use this in Flutter)

- Map `Sideloading and jailbreak` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Sideloading and jailbreak` before merge.

### Don't

- Do not ship `Sideloading and jailbreak` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Sideloading and jailbreak`.

### Verify

- Peer review `Sideloading and jailbreak` against domain skill `security-mobile-security`.

## Screenshots and overlays

**Sub-topics:** FLAG_SECURE, Overlay attacks, Threat modeling and trust boundaries (Screenshots and overlays), Abuse cases and adversarial testing (Screenshots and overlays), Logging, audit, and detection (Screenshots and overlays)

### Do (use this in Flutter)

- Map `Screenshots and overlays` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Screenshots and overlays` before merge.

### Don't

- Do not ship `Screenshots and overlays` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Screenshots and overlays`.

### Verify

- Peer review `Screenshots and overlays` against domain skill `security-mobile-security`.

## Mobile SDK supply chain

**Sub-topics:** Third-party SDKs, Threat modeling and trust boundaries (Mobile SDK supply chain), Abuse cases and adversarial testing (Mobile SDK supply chain), Logging, audit, and detection (Mobile SDK supply chain), Access control and least privilege (Mobile SDK supply chain)

### Do (use this in Flutter)

- Map `Mobile SDK supply chain` controls to Flutter APIs documented for `security-mobile-security`.
- Add an abuse-case test or check for `Mobile SDK supply chain` before merge.

### Don't

- Do not ship `Mobile SDK supply chain` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Mobile SDK supply chain`.

### Verify

- Peer review `Mobile SDK supply chain` against domain skill `security-mobile-security`.

