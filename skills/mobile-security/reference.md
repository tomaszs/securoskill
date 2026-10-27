# Rules reference: Mobile application security

iOS, Android, hybrid, and mobile APIs.

## On-device storage

Sub-topics: Keychain, Keystore, SQLite, Threat modeling and trust boundaries (On-device storage), Abuse cases and adversarial testing (On-device storage)

### Policy

- Treat On-device storage in On-device storage as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for On-device storage (Mobile application security).
- Require security review for material changes affecting On-device storage.

### Design

- Apply least privilege and defense in depth for On-device storage.
- Prefer established patterns and libraries over custom crypto or auth for On-device storage.
- Fail closed: deny by default when On-device storage cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching On-device storage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-device storage.
- Keep dependencies patched; pin versions for On-device storage components.

### Verification

- Add automated tests and SAST/DAST coverage for On-device storage paths.
- Run dependency and secret scanning on every change touching On-device storage.
- Perform targeted manual tests (abuse cases) for On-device storage.

### Operations

- Log security-relevant events for On-device storage without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in On-device storage.
- Review access and configuration for On-device storage on a regular cadence.

## Certificate pinning

Sub-topics: Bypass tools, Rotation, Threat modeling and trust boundaries (Certificate pinning), Abuse cases and adversarial testing (Certificate pinning), Logging, audit, and detection (Certificate pinning)

### Policy

- Treat Certificate pinning in Certificate pinning as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Certificate pinning (Mobile application security).
- Require security review for material changes affecting Certificate pinning.

### Design

- Apply least privilege and defense in depth for Certificate pinning.
- Prefer established patterns and libraries over custom crypto or auth for Certificate pinning.
- Fail closed: deny by default when Certificate pinning cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Certificate pinning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Certificate pinning.
- Keep dependencies patched; pin versions for Certificate pinning components.

### Verification

- Add automated tests and SAST/DAST coverage for Certificate pinning paths.
- Run dependency and secret scanning on every change touching Certificate pinning.
- Perform targeted manual tests (abuse cases) for Certificate pinning.

### Operations

- Log security-relevant events for Certificate pinning without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Certificate pinning.
- Review access and configuration for Certificate pinning on a regular cadence.

## Reverse engineering resistance

Sub-topics: Obfuscation limits, Threat modeling and trust boundaries (Reverse engineering resistance), Abuse cases and adversarial testing (Reverse engineering resistance), Logging, audit, and detection (Reverse engineering resistance), Access control and least privilege (Reverse engineering resistance)

### Policy

- Treat Reverse engineering resistance in Reverse engineering resistance as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Reverse engineering resistance (Mobile application security).
- Require security review for material changes affecting Reverse engineering resistance.

### Design

- Apply least privilege and defense in depth for Reverse engineering resistance.
- Prefer established patterns and libraries over custom crypto or auth for Reverse engineering resistance.
- Fail closed: deny by default when Reverse engineering resistance cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Reverse engineering resistance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Reverse engineering resistance.
- Keep dependencies patched; pin versions for Reverse engineering resistance components.

### Verification

- Add automated tests and SAST/DAST coverage for Reverse engineering resistance paths.
- Run dependency and secret scanning on every change touching Reverse engineering resistance.
- Perform targeted manual tests (abuse cases) for Reverse engineering resistance.

### Operations

- Log security-relevant events for Reverse engineering resistance without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Reverse engineering resistance.
- Review access and configuration for Reverse engineering resistance on a regular cadence.

## Deep links and intents

Sub-topics: URL scheme hijack, Threat modeling and trust boundaries (Deep links and intents), Abuse cases and adversarial testing (Deep links and intents), Logging, audit, and detection (Deep links and intents), Access control and least privilege (Deep links and intents)

### Policy

- Treat Deep links and intents in Deep links and intents as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Deep links and intents (Mobile application security).
- Require security review for material changes affecting Deep links and intents.

### Design

- Apply least privilege and defense in depth for Deep links and intents.
- Prefer established patterns and libraries over custom crypto or auth for Deep links and intents.
- Fail closed: deny by default when Deep links and intents cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Deep links and intents; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deep links and intents.
- Keep dependencies patched; pin versions for Deep links and intents components.

### Verification

- Add automated tests and SAST/DAST coverage for Deep links and intents paths.
- Run dependency and secret scanning on every change touching Deep links and intents.
- Perform targeted manual tests (abuse cases) for Deep links and intents.

### Operations

- Log security-relevant events for Deep links and intents without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Deep links and intents.
- Review access and configuration for Deep links and intents on a regular cadence.

## Mobile OAuth

Sub-topics: PKCE, Custom URL schemes, Threat modeling and trust boundaries (Mobile OAuth), Abuse cases and adversarial testing (Mobile OAuth), Logging, audit, and detection (Mobile OAuth)

### Policy

- Treat Mobile OAuth in Mobile OAuth as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Mobile OAuth (Mobile application security).
- Require security review for material changes affecting Mobile OAuth.

### Design

- Apply least privilege and defense in depth for Mobile OAuth.
- Prefer established patterns and libraries over custom crypto or auth for Mobile OAuth.
- Fail closed: deny by default when Mobile OAuth cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Mobile OAuth; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile OAuth.
- Keep dependencies patched; pin versions for Mobile OAuth components.

### Verification

- Add automated tests and SAST/DAST coverage for Mobile OAuth paths.
- Run dependency and secret scanning on every change touching Mobile OAuth.
- Perform targeted manual tests (abuse cases) for Mobile OAuth.

### Operations

- Log security-relevant events for Mobile OAuth without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Mobile OAuth.
- Review access and configuration for Mobile OAuth on a regular cadence.

## Biometric APIs

Sub-topics: Fallback PIN, Threat modeling and trust boundaries (Biometric APIs), Abuse cases and adversarial testing (Biometric APIs), Logging, audit, and detection (Biometric APIs), Access control and least privilege (Biometric APIs)

### Policy

- Treat Biometric APIs in Biometric APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Biometric APIs (Mobile application security).
- Require security review for material changes affecting Biometric APIs.

### Design

- Apply least privilege and defense in depth for Biometric APIs.
- Prefer established patterns and libraries over custom crypto or auth for Biometric APIs.
- Fail closed: deny by default when Biometric APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Biometric APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Biometric APIs.
- Keep dependencies patched; pin versions for Biometric APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for Biometric APIs paths.
- Run dependency and secret scanning on every change touching Biometric APIs.
- Perform targeted manual tests (abuse cases) for Biometric APIs.

### Operations

- Log security-relevant events for Biometric APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Biometric APIs.
- Review access and configuration for Biometric APIs on a regular cadence.

## WebView bridges

Sub-topics: JS interfaces, Threat modeling and trust boundaries (WebView bridges), Abuse cases and adversarial testing (WebView bridges), Logging, audit, and detection (WebView bridges), Access control and least privilege (WebView bridges)

### Policy

- Treat WebView bridges in WebView bridges as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WebView bridges (Mobile application security).
- Require security review for material changes affecting WebView bridges.

### Design

- Apply least privilege and defense in depth for WebView bridges.
- Prefer established patterns and libraries over custom crypto or auth for WebView bridges.
- Fail closed: deny by default when WebView bridges cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WebView bridges; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebView bridges.
- Keep dependencies patched; pin versions for WebView bridges components.

### Verification

- Add automated tests and SAST/DAST coverage for WebView bridges paths.
- Run dependency and secret scanning on every change touching WebView bridges.
- Perform targeted manual tests (abuse cases) for WebView bridges.

### Operations

- Log security-relevant events for WebView bridges without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WebView bridges.
- Review access and configuration for WebView bridges on a regular cadence.

## Push notifications

Sub-topics: Payload sensitivity, Threat modeling and trust boundaries (Push notifications), Abuse cases and adversarial testing (Push notifications), Logging, audit, and detection (Push notifications), Access control and least privilege (Push notifications)

### Policy

- Treat Push notifications in Push notifications as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Push notifications (Mobile application security).
- Require security review for material changes affecting Push notifications.

### Design

- Apply least privilege and defense in depth for Push notifications.
- Prefer established patterns and libraries over custom crypto or auth for Push notifications.
- Fail closed: deny by default when Push notifications cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Push notifications; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Push notifications.
- Keep dependencies patched; pin versions for Push notifications components.

### Verification

- Add automated tests and SAST/DAST coverage for Push notifications paths.
- Run dependency and secret scanning on every change touching Push notifications.
- Perform targeted manual tests (abuse cases) for Push notifications.

### Operations

- Log security-relevant events for Push notifications without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Push notifications.
- Review access and configuration for Push notifications on a regular cadence.

## App attestation

Sub-topics: DeviceCheck, Play Integrity, Threat modeling and trust boundaries (App attestation), Abuse cases and adversarial testing (App attestation), Logging, audit, and detection (App attestation)

### Policy

- Treat App attestation in App attestation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for App attestation (Mobile application security).
- Require security review for material changes affecting App attestation.

### Design

- Apply least privilege and defense in depth for App attestation.
- Prefer established patterns and libraries over custom crypto or auth for App attestation.
- Fail closed: deny by default when App attestation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching App attestation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to App attestation.
- Keep dependencies patched; pin versions for App attestation components.

### Verification

- Add automated tests and SAST/DAST coverage for App attestation paths.
- Run dependency and secret scanning on every change touching App attestation.
- Perform targeted manual tests (abuse cases) for App attestation.

### Operations

- Log security-relevant events for App attestation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in App attestation.
- Review access and configuration for App attestation on a regular cadence.

## Sideloading and jailbreak

Sub-topics: Root detection limits, Threat modeling and trust boundaries (Sideloading and jailbreak), Abuse cases and adversarial testing (Sideloading and jailbreak), Logging, audit, and detection (Sideloading and jailbreak), Access control and least privilege (Sideloading and jailbreak)

### Policy

- Treat Sideloading and jailbreak in Sideloading and jailbreak as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Sideloading and jailbreak (Mobile application security).
- Require security review for material changes affecting Sideloading and jailbreak.

### Design

- Apply least privilege and defense in depth for Sideloading and jailbreak.
- Prefer established patterns and libraries over custom crypto or auth for Sideloading and jailbreak.
- Fail closed: deny by default when Sideloading and jailbreak cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Sideloading and jailbreak; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Sideloading and jailbreak.
- Keep dependencies patched; pin versions for Sideloading and jailbreak components.

### Verification

- Add automated tests and SAST/DAST coverage for Sideloading and jailbreak paths.
- Run dependency and secret scanning on every change touching Sideloading and jailbreak.
- Perform targeted manual tests (abuse cases) for Sideloading and jailbreak.

### Operations

- Log security-relevant events for Sideloading and jailbreak without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Sideloading and jailbreak.
- Review access and configuration for Sideloading and jailbreak on a regular cadence.

## Screenshots and overlays

Sub-topics: FLAG_SECURE, Overlay attacks, Threat modeling and trust boundaries (Screenshots and overlays), Abuse cases and adversarial testing (Screenshots and overlays), Logging, audit, and detection (Screenshots and overlays)

### Policy

- Treat Screenshots and overlays in Screenshots and overlays as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Screenshots and overlays (Mobile application security).
- Require security review for material changes affecting Screenshots and overlays.

### Design

- Apply least privilege and defense in depth for Screenshots and overlays.
- Prefer established patterns and libraries over custom crypto or auth for Screenshots and overlays.
- Fail closed: deny by default when Screenshots and overlays cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Screenshots and overlays; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Screenshots and overlays.
- Keep dependencies patched; pin versions for Screenshots and overlays components.

### Verification

- Add automated tests and SAST/DAST coverage for Screenshots and overlays paths.
- Run dependency and secret scanning on every change touching Screenshots and overlays.
- Perform targeted manual tests (abuse cases) for Screenshots and overlays.

### Operations

- Log security-relevant events for Screenshots and overlays without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Screenshots and overlays.
- Review access and configuration for Screenshots and overlays on a regular cadence.

## Mobile SDK supply chain

Sub-topics: Third-party SDKs, Threat modeling and trust boundaries (Mobile SDK supply chain), Abuse cases and adversarial testing (Mobile SDK supply chain), Logging, audit, and detection (Mobile SDK supply chain), Access control and least privilege (Mobile SDK supply chain)

### Policy

- Treat Mobile SDK supply chain in Mobile SDK supply chain as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Mobile SDK supply chain (Mobile application security).
- Require security review for material changes affecting Mobile SDK supply chain.

### Design

- Apply least privilege and defense in depth for Mobile SDK supply chain.
- Prefer established patterns and libraries over custom crypto or auth for Mobile SDK supply chain.
- Fail closed: deny by default when Mobile SDK supply chain cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Mobile SDK supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile SDK supply chain.
- Keep dependencies patched; pin versions for Mobile SDK supply chain components.

### Verification

- Add automated tests and SAST/DAST coverage for Mobile SDK supply chain paths.
- Run dependency and secret scanning on every change touching Mobile SDK supply chain.
- Perform targeted manual tests (abuse cases) for Mobile SDK supply chain.

### Operations

- Log security-relevant events for Mobile SDK supply chain without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Mobile SDK supply chain.
- Review access and configuration for Mobile SDK supply chain on a regular cadence.

