# Astro: Cryptography and key management

Stack-specific implementation for **Astro** (Web UI). Normative rules: domain skill `security-cryptography` / `reference.md`.

## TLS and certificates

**Sub-topics:** mTLS, Pinning pitfalls, Cert rotation, Threat modeling and trust boundaries (TLS and certificates), Abuse cases and adversarial testing (TLS and certificates)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Symmetric encryption

**Sub-topics:** AES-GCM, Nonce reuse, Key derivation, Threat modeling and trust boundaries (Symmetric encryption), Abuse cases and adversarial testing (Symmetric encryption)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Asymmetric crypto

**Sub-topics:** RSA padding, ECDH, Signature algorithms, Threat modeling and trust boundaries (Asymmetric crypto), Abuse cases and adversarial testing (Asymmetric crypto)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Hashing and passwords

**Sub-topics:** bcrypt/argon2, SHA-256 misuse, Threat modeling and trust boundaries (Hashing and passwords), Abuse cases and adversarial testing (Hashing and passwords), Logging, audit, and detection (Hashing and passwords)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Randomness and IDs

**Sub-topics:** CSPRNG, Predictable UUIDs, Threat modeling and trust boundaries (Randomness and IDs), Abuse cases and adversarial testing (Randomness and IDs), Logging, audit, and detection (Randomness and IDs)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## KMS and HSM

**Sub-topics:** Envelope encryption, Cloud KMS policies, Threat modeling and trust boundaries (KMS and HSM), Abuse cases and adversarial testing (KMS and HSM), Logging, audit, and detection (KMS and HSM)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## JWT and JOSE

**Sub-topics:** alg none, Key confusion, JWK sets, Threat modeling and trust boundaries (JWT and JOSE), Abuse cases and adversarial testing (JWT and JOSE)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## PGP and email crypto

**Sub-topics:** Key management, Ubiquitous encryption gaps, Threat modeling and trust boundaries (PGP and email crypto), Abuse cases and adversarial testing (PGP and email crypto), Logging, audit, and detection (PGP and email crypto)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Specialized crypto uses

**Sub-topics:** Tokenization, Format-preserving, Threat modeling and trust boundaries (Specialized crypto uses), Abuse cases and adversarial testing (Specialized crypto uses), Logging, audit, and detection (Specialized crypto uses)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Crypto agility

**Sub-topics:** Algorithm deprecation, Inventory, Threat modeling and trust boundaries (Crypto agility), Abuse cases and adversarial testing (Crypto agility), Logging, audit, and detection (Crypto agility)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Secrets derivation

**Sub-topics:** PBKDF2, scrypt, HKDF, Threat modeling and trust boundaries (Secrets derivation), Abuse cases and adversarial testing (Secrets derivation)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

## Side channels

**Sub-topics:** Constant-time compare, Padding oracles, Threat modeling and trust boundaries (Side channels), Abuse cases and adversarial testing (Side channels), Logging, audit, and detection (Side channels)

### Do (use this in Astro)

- Astro is not the primary enforcement point for `cryptography`; load stack skill `security-cryptography` when you touch that layer.
- Keep Astro configuration aligned with requirements from `security-cryptography` (domain reference.md).

### Don't

- Do not duplicate `cryptography` controls only in Astro config while leaving security-cryptography misconfigured.
- Do not assume Astro defaults satisfy `security-cryptography` without verification.

### Verify

- Integration test the full path: Astro plus the system covered by `security-cryptography`.

