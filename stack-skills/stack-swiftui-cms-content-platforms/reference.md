# SwiftUI (iOS): CMS, content platforms, and publishing

Stack-specific implementation for **SwiftUI (iOS)** (Mobile). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in SwiftUI (iOS))

- Store tokens in Keychain with `kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly`.
- Use ATS (HTTPS).

### Don't

- Do not store secrets in UserDefaults.
- Do not disable ATS globally.

### Verify

- MobSF scan on IPA.

