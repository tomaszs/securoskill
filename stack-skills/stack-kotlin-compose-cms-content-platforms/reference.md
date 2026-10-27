# Kotlin / Jetpack Compose: CMS, content platforms, and publishing

Stack-specific implementation for **Kotlin / Jetpack Compose** (Mobile). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do (use this in Kotlin / Jetpack Compose)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do (use this in Kotlin / Jetpack Compose)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do (use this in Kotlin / Jetpack Compose)

- Protect cookie-authenticated mutations with CSRF tokens or SameSite + custom headers.

### Don't

- Do not rely on CORS alone to prevent CSRF.

### Verify

- Add automated abuse-case tests for Marketing forms in Kotlin / Jetpack Compose.
- Run SAST and dependency scans for Mobile in CI.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in Kotlin / Jetpack Compose)

- Use EncryptedSharedPreferences or Keystore for secrets.
- Set `android:usesCleartextTraffic=false`.

### Don't

- Do not store tokens in plain SharedPreferences.
- Do not export components without permissions.

### Verify

- MobSF scan on APK/AAB.

