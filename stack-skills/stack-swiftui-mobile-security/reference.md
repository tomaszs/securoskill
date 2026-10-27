# SwiftUI (iOS): Mobile application security

Stack-specific implementation for **SwiftUI (iOS)** (Mobile). Normative rules: domain skill `security-mobile-security` / `reference.md`.

## On-device storage

**Sub-topics:** Keychain, Keystore, SQLite, Threat modeling and trust boundaries (On-device storage), Abuse cases and adversarial testing (On-device storage)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Certificate pinning

**Sub-topics:** Bypass tools, Rotation, Threat modeling and trust boundaries (Certificate pinning), Abuse cases and adversarial testing (Certificate pinning), Logging, audit, and detection (Certificate pinning)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Reverse engineering resistance

**Sub-topics:** Obfuscation limits, Threat modeling and trust boundaries (Reverse engineering resistance), Abuse cases and adversarial testing (Reverse engineering resistance), Logging, audit, and detection (Reverse engineering resistance), Access control and least privilege (Reverse engineering resistance)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Deep links and intents

**Sub-topics:** URL scheme hijack, Threat modeling and trust boundaries (Deep links and intents), Abuse cases and adversarial testing (Deep links and intents), Logging, audit, and detection (Deep links and intents), Access control and least privilege (Deep links and intents)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Mobile OAuth

**Sub-topics:** PKCE, Custom URL schemes, Threat modeling and trust boundaries (Mobile OAuth), Abuse cases and adversarial testing (Mobile OAuth), Logging, audit, and detection (Mobile OAuth)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Biometric APIs

**Sub-topics:** Fallback PIN, Threat modeling and trust boundaries (Biometric APIs), Abuse cases and adversarial testing (Biometric APIs), Logging, audit, and detection (Biometric APIs), Access control and least privilege (Biometric APIs)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## WebView bridges

**Sub-topics:** JS interfaces, Threat modeling and trust boundaries (WebView bridges), Abuse cases and adversarial testing (WebView bridges), Logging, audit, and detection (WebView bridges), Access control and least privilege (WebView bridges)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Push notifications

**Sub-topics:** Payload sensitivity, Threat modeling and trust boundaries (Push notifications), Abuse cases and adversarial testing (Push notifications), Logging, audit, and detection (Push notifications), Access control and least privilege (Push notifications)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## App attestation

**Sub-topics:** DeviceCheck, Play Integrity, Threat modeling and trust boundaries (App attestation), Abuse cases and adversarial testing (App attestation), Logging, audit, and detection (App attestation)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Sideloading and jailbreak

**Sub-topics:** Root detection limits, Threat modeling and trust boundaries (Sideloading and jailbreak), Abuse cases and adversarial testing (Sideloading and jailbreak), Logging, audit, and detection (Sideloading and jailbreak), Access control and least privilege (Sideloading and jailbreak)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Screenshots and overlays

**Sub-topics:** FLAG_SECURE, Overlay attacks, Threat modeling and trust boundaries (Screenshots and overlays), Abuse cases and adversarial testing (Screenshots and overlays), Logging, audit, and detection (Screenshots and overlays)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Mobile SDK supply chain

**Sub-topics:** Third-party SDKs, Threat modeling and trust boundaries (Mobile SDK supply chain), Abuse cases and adversarial testing (Mobile SDK supply chain), Logging, audit, and detection (Mobile SDK supply chain), Access control and least privilege (Mobile SDK supply chain)

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

