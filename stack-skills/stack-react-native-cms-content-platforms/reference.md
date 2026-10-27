# React Native: CMS, content platforms, and publishing

Stack-specific implementation for **React Native** (Mobile). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for cms_api controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for workflow controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for supply_chain controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for content_abuse controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for file_upload_ui controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for multi_tenant controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for search_index controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do (use this in React Native)

- Protect cookie-authenticated mutations with CSRF tokens or SameSite + custom headers.

### Don't

- Do not rely on CORS alone to prevent CSRF.

### Verify

- Add automated abuse-case tests for Marketing forms in React Native.
- Run SAST and dependency scans for Mobile in CI.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in React Native)

- Apply domain skill `security-cms-content-platforms` requirements using react-native supported APIs only.
- Use the official react-native security documentation for rbac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

