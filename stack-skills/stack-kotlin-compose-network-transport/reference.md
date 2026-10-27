# Kotlin / Jetpack Compose: Network and transport security

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-network-transport` / `reference.md`.

## DNS security

**Sub-topics:** DNSSEC, Subdomain takeover, CAA, Threat modeling and trust boundaries (DNS security), Abuse cases and adversarial testing (DNS security)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## WAF and edge protection

**Sub-topics:** Rule tuning, Bypass, Threat modeling and trust boundaries (WAF and edge protection), Abuse cases and adversarial testing (WAF and edge protection), Logging, audit, and detection (WAF and edge protection)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## SSRF

**Sub-topics:** Metadata endpoints, URL parsers, Allowlists, Threat modeling and trust boundaries (SSRF), Abuse cases and adversarial testing (SSRF)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Reverse proxies

**Sub-topics:** Header injection, Path normalization, Threat modeling and trust boundaries (Reverse proxies), Abuse cases and adversarial testing (Reverse proxies), Logging, audit, and detection (Reverse proxies)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## VPN and private networking

**Sub-topics:** Split tunnel, Peering, Threat modeling and trust boundaries (VPN and private networking), Abuse cases and adversarial testing (VPN and private networking), Logging, audit, and detection (VPN and private networking)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## DDoS and volumetric attacks

**Sub-topics:** Rate limits, Anycast, Threat modeling and trust boundaries (DDoS and volumetric attacks), Abuse cases and adversarial testing (DDoS and volumetric attacks), Logging, audit, and detection (DDoS and volumetric attacks)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## IP allowlisting pitfalls

**Sub-topics:** Spoofing, Shared NAT, Threat modeling and trust boundaries (IP allowlisting pitfalls), Abuse cases and adversarial testing (IP allowlisting pitfalls), Logging, audit, and detection (IP allowlisting pitfalls)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## HTTP request smuggling

**Sub-topics:** Front/back desync, Threat modeling and trust boundaries (HTTP request smuggling), Abuse cases and adversarial testing (HTTP request smuggling), Logging, audit, and detection (HTTP request smuggling), Access control and least privilege (HTTP request smuggling)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## WebSocket transport

**Sub-topics:** Origin checks, TLS, Threat modeling and trust boundaries (WebSocket transport), Abuse cases and adversarial testing (WebSocket transport), Logging, audit, and detection (WebSocket transport)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## SMTP security

**Sub-topics:** STARTTLS, SPF/DKIM/DMARC, Threat modeling and trust boundaries (SMTP security), Abuse cases and adversarial testing (SMTP security), Logging, audit, and detection (SMTP security)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## IPv6 and dual stack

**Sub-topics:** Unexpected exposure, Threat modeling and trust boundaries (IPv6 and dual stack), Abuse cases and adversarial testing (IPv6 and dual stack), Logging, audit, and detection (IPv6 and dual stack), Access control and least privilege (IPv6 and dual stack)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Service mesh mTLS

**Sub-topics:** Identity, Policy, Threat modeling and trust boundaries (Service mesh mTLS), Abuse cases and adversarial testing (Service mesh mTLS), Logging, audit, and detection (Service mesh mTLS)

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

