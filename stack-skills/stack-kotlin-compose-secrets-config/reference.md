# Kotlin / Jetpack Compose: Secrets and configuration

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-secrets-config` / `reference.md`.

## Environment variables

**Sub-topics:** Leaks in logs, Client exposure, Threat modeling and trust boundaries (Environment variables), Abuse cases and adversarial testing (Environment variables), Logging, audit, and detection (Environment variables)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Config separation

**Sub-topics:** Per-env files, Gitignore, Threat modeling and trust boundaries (Config separation), Abuse cases and adversarial testing (Config separation), Logging, audit, and detection (Config separation)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Feature flags

**Sub-topics:** Kill switches, Privileged features, Threat modeling and trust boundaries (Feature flags), Abuse cases and adversarial testing (Feature flags), Logging, audit, and detection (Feature flags)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Secret rotation

**Sub-topics:** Dual-write, Breakage windows, Threat modeling and trust boundaries (Secret rotation), Abuse cases and adversarial testing (Secret rotation), Logging, audit, and detection (Secret rotation)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## .env handling

**Sub-topics:** Committed secrets, CI injection, Threat modeling and trust boundaries (.env handling), Abuse cases and adversarial testing (.env handling), Logging, audit, and detection (.env handling)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Config servers

**Sub-topics:** ACLs, Encryption, Threat modeling and trust boundaries (Config servers), Abuse cases and adversarial testing (Config servers), Logging, audit, and detection (Config servers)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Hardcoded credentials

**Sub-topics:** Scanning, Prevention, Threat modeling and trust boundaries (Hardcoded credentials), Abuse cases and adversarial testing (Hardcoded credentials), Logging, audit, and detection (Hardcoded credentials)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Public vs confidential clients

**Sub-topics:** Mobile apps, SPAs, Threat modeling and trust boundaries (Public vs confidential clients), Abuse cases and adversarial testing (Public vs confidential clients), Logging, audit, and detection (Public vs confidential clients)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Bootstrap secrets

**Sub-topics:** First deploy, Init containers, Threat modeling and trust boundaries (Bootstrap secrets), Abuse cases and adversarial testing (Bootstrap secrets), Logging, audit, and detection (Bootstrap secrets)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Configuration audit

**Sub-topics:** Drift detection, Threat modeling and trust boundaries (Configuration audit), Abuse cases and adversarial testing (Configuration audit), Logging, audit, and detection (Configuration audit), Access control and least privilege (Configuration audit)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Insecure defaults

**Sub-topics:** Debug=true, Open admin, Threat modeling and trust boundaries (Insecure defaults), Abuse cases and adversarial testing (Insecure defaults), Logging, audit, and detection (Insecure defaults)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Split knowledge

**Sub-topics:** Shamir, M-of-N, Threat modeling and trust boundaries (Split knowledge), Abuse cases and adversarial testing (Split knowledge), Logging, audit, and detection (Split knowledge)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

