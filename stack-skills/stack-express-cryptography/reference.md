# Express.js: Cryptography and key management

Stack-specific implementation for **Express.js** (Node.js server). Normative rules: domain skill `security-cryptography` / `reference.md`.

## TLS and certificates

**Sub-topics:** mTLS, Pinning pitfalls, Cert rotation, Threat modeling and trust boundaries (TLS and certificates), Abuse cases and adversarial testing (TLS and certificates)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for tls controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Symmetric encryption

**Sub-topics:** AES-GCM, Nonce reuse, Key derivation, Threat modeling and trust boundaries (Symmetric encryption), Abuse cases and adversarial testing (Symmetric encryption)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for crypto_symmetric controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Asymmetric crypto

**Sub-topics:** RSA padding, ECDH, Signature algorithms, Threat modeling and trust boundaries (Asymmetric crypto), Abuse cases and adversarial testing (Asymmetric crypto)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for crypto_asymmetric controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Hashing and passwords

**Sub-topics:** bcrypt/argon2, SHA-256 misuse, Threat modeling and trust boundaries (Hashing and passwords), Abuse cases and adversarial testing (Hashing and passwords), Logging, audit, and detection (Hashing and passwords)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for hashing controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Randomness and IDs

**Sub-topics:** CSPRNG, Predictable UUIDs, Threat modeling and trust boundaries (Randomness and IDs), Abuse cases and adversarial testing (Randomness and IDs), Logging, audit, and detection (Randomness and IDs)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for randomness controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## KMS and HSM

**Sub-topics:** Envelope encryption, Cloud KMS policies, Threat modeling and trust boundaries (KMS and HSM), Abuse cases and adversarial testing (KMS and HSM), Logging, audit, and detection (KMS and HSM)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for kms controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## JWT and JOSE

**Sub-topics:** alg none, Key confusion, JWK sets, Threat modeling and trust boundaries (JWT and JOSE), Abuse cases and adversarial testing (JWT and JOSE)

### Do (use this in Express.js)

- Use RS256 or ES256; validate `aud`, `iss`, `exp`; store keys in KMS.
- Rotate signing keys with overlap.

### Don't

- Do not accept `alg: none` or HS256 with public client secrets.
- Do not put PII in JWT payloads.

### Verify

- Use jwt lint tools in CI for sample tokens.

## PGP and email crypto

**Sub-topics:** Key management, Ubiquitous encryption gaps, Threat modeling and trust boundaries (PGP and email crypto), Abuse cases and adversarial testing (PGP and email crypto), Logging, audit, and detection (PGP and email crypto)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for pgp controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Specialized crypto uses

**Sub-topics:** Tokenization, Format-preserving, Threat modeling and trust boundaries (Specialized crypto uses), Abuse cases and adversarial testing (Specialized crypto uses), Logging, audit, and detection (Specialized crypto uses)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for crypto_generic controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Crypto agility

**Sub-topics:** Algorithm deprecation, Inventory, Threat modeling and trust boundaries (Crypto agility), Abuse cases and adversarial testing (Crypto agility), Logging, audit, and detection (Crypto agility)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for crypto_generic controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Secrets derivation

**Sub-topics:** PBKDF2, scrypt, HKDF, Threat modeling and trust boundaries (Secrets derivation), Abuse cases and adversarial testing (Secrets derivation)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for kdf controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

## Side channels

**Sub-topics:** Constant-time compare, Padding oracles, Threat modeling and trust boundaries (Side channels), Abuse cases and adversarial testing (Side channels), Logging, audit, and detection (Side channels)

### Do (use this in Express.js)

- Apply domain skill `security-cryptography` requirements using express supported APIs only.
- Use the official express security documentation for side_channel controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of express for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on express projects in CI.

