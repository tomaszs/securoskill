# Django: Mobile application security

Stack-specific implementation for **Django** (Python). Normative rules: domain skill `security-mobile-security` / `reference.md`.

## On-device storage

**Sub-topics:** Keychain, Keystore, SQLite, Threat modeling and trust boundaries (On-device storage), Abuse cases and adversarial testing (On-device storage)

### Platform rules (summary)

- Validate and canonicalize all inputs touching On-device storage; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to On-device storage.
- Keep dependencies patched; pin versions for On-device storage components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for On-device storage before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for On-device storage paths in Django.
- Run SAST/dependency scan configured for Python.

## Certificate pinning

**Sub-topics:** Bypass tools, Rotation, Threat modeling and trust boundaries (Certificate pinning), Abuse cases and adversarial testing (Certificate pinning), Logging, audit, and detection (Certificate pinning)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Certificate pinning; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Certificate pinning.
- Keep dependencies patched; pin versions for Certificate pinning components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Certificate pinning before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Certificate pinning paths in Django.
- Run SAST/dependency scan configured for Python.

## Reverse engineering resistance

**Sub-topics:** Obfuscation limits, Threat modeling and trust boundaries (Reverse engineering resistance), Abuse cases and adversarial testing (Reverse engineering resistance), Logging, audit, and detection (Reverse engineering resistance), Access control and least privilege (Reverse engineering resistance)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Reverse engineering resistance; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Reverse engineering resistance.
- Keep dependencies patched; pin versions for Reverse engineering resistance components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Reverse engineering resistance before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Reverse engineering resistance paths in Django.
- Run SAST/dependency scan configured for Python.

## Deep links and intents

**Sub-topics:** URL scheme hijack, Threat modeling and trust boundaries (Deep links and intents), Abuse cases and adversarial testing (Deep links and intents), Logging, audit, and detection (Deep links and intents), Access control and least privilege (Deep links and intents)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Deep links and intents; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Deep links and intents.
- Keep dependencies patched; pin versions for Deep links and intents components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Deep links and intents before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Deep links and intents paths in Django.
- Run SAST/dependency scan configured for Python.

## Mobile OAuth

**Sub-topics:** PKCE, Custom URL schemes, Threat modeling and trust boundaries (Mobile OAuth), Abuse cases and adversarial testing (Mobile OAuth), Logging, audit, and detection (Mobile OAuth)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Mobile OAuth; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile OAuth.
- Keep dependencies patched; pin versions for Mobile OAuth components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Mobile OAuth before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Mobile OAuth paths in Django.
- Run SAST/dependency scan configured for Python.

## Biometric APIs

**Sub-topics:** Fallback PIN, Threat modeling and trust boundaries (Biometric APIs), Abuse cases and adversarial testing (Biometric APIs), Logging, audit, and detection (Biometric APIs), Access control and least privilege (Biometric APIs)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Biometric APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Biometric APIs.
- Keep dependencies patched; pin versions for Biometric APIs components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Biometric APIs before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Biometric APIs paths in Django.
- Run SAST/dependency scan configured for Python.

## WebView bridges

**Sub-topics:** JS interfaces, Threat modeling and trust boundaries (WebView bridges), Abuse cases and adversarial testing (WebView bridges), Logging, audit, and detection (WebView bridges), Access control and least privilege (WebView bridges)

### Platform rules (summary)

- Validate and canonicalize all inputs touching WebView bridges; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WebView bridges.
- Keep dependencies patched; pin versions for WebView bridges components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WebView bridges before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WebView bridges paths in Django.
- Run SAST/dependency scan configured for Python.

## Push notifications

**Sub-topics:** Payload sensitivity, Threat modeling and trust boundaries (Push notifications), Abuse cases and adversarial testing (Push notifications), Logging, audit, and detection (Push notifications), Access control and least privilege (Push notifications)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Push notifications; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Push notifications.
- Keep dependencies patched; pin versions for Push notifications components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Push notifications before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Push notifications paths in Django.
- Run SAST/dependency scan configured for Python.

## App attestation

**Sub-topics:** DeviceCheck, Play Integrity, Threat modeling and trust boundaries (App attestation), Abuse cases and adversarial testing (App attestation), Logging, audit, and detection (App attestation)

### Platform rules (summary)

- Validate and canonicalize all inputs touching App attestation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to App attestation.
- Keep dependencies patched; pin versions for App attestation components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for App attestation before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for App attestation paths in Django.
- Run SAST/dependency scan configured for Python.

## Sideloading and jailbreak

**Sub-topics:** Root detection limits, Threat modeling and trust boundaries (Sideloading and jailbreak), Abuse cases and adversarial testing (Sideloading and jailbreak), Logging, audit, and detection (Sideloading and jailbreak), Access control and least privilege (Sideloading and jailbreak)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Sideloading and jailbreak; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Sideloading and jailbreak.
- Keep dependencies patched; pin versions for Sideloading and jailbreak components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Sideloading and jailbreak before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Sideloading and jailbreak paths in Django.
- Run SAST/dependency scan configured for Python.

## Screenshots and overlays

**Sub-topics:** FLAG_SECURE, Overlay attacks, Threat modeling and trust boundaries (Screenshots and overlays), Abuse cases and adversarial testing (Screenshots and overlays), Logging, audit, and detection (Screenshots and overlays)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Screenshots and overlays; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Screenshots and overlays.
- Keep dependencies patched; pin versions for Screenshots and overlays components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Screenshots and overlays before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Screenshots and overlays paths in Django.
- Run SAST/dependency scan configured for Python.

## Mobile SDK supply chain

**Sub-topics:** Third-party SDKs, Threat modeling and trust boundaries (Mobile SDK supply chain), Abuse cases and adversarial testing (Mobile SDK supply chain), Logging, audit, and detection (Mobile SDK supply chain), Access control and least privilege (Mobile SDK supply chain)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Mobile SDK supply chain; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile SDK supply chain.
- Keep dependencies patched; pin versions for Mobile SDK supply chain components.

### How to do this in Django

- Read normative rules in domain skill `security-mobile-security` / `reference.md`, then apply them using Django APIs and deployment model.
- Prefer framework-maintained security features in Django over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Mobile SDK supply chain before merge.
- Pin Django dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Mobile SDK supply chain paths in Django.
- Run SAST/dependency scan configured for Python.

