# Angular: CMS, content platforms, and publishing

Stack-specific implementation for **Angular** (Web UI). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for cms_api controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do (use this in Angular)

- Use default interpolation `{{ expression }}` for user-controlled text (auto-escaped).
- For HTML snippets, run `DomSanitizer.sanitize(SecurityContext.HTML, untrusted)` before binding.
- Use Angular's `HttpClient` and treat response bodies as data, not HTML templates.
- Enable strict CSP at the server / `index.html` and avoid inline script except nonced.

### Don't

- Do not use `bypassSecurityTrustHtml`, `bypassSecurityTrustUrl`, or `bypassSecurityTrustResourceUrl` on user or API data.
- Do not bind `[innerHTML]` to raw API or CMS HTML without sanitization.
- Do not construct templates dynamically from user input (template injection).
- Do not use `eval` or `new Function` with user-controlled strings in browser bundles.

### Verify

- Unit-test components with XSS payloads in inputs; expect escaped output, not script execution.
- Enable Angular ESLint security-related rules in CI.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for workflow controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for supply_chain controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for content_abuse controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do (use this in Angular)

- Use default interpolation `{{ expression }}` for user-controlled text (auto-escaped).
- For HTML snippets, run `DomSanitizer.sanitize(SecurityContext.HTML, untrusted)` before binding.
- Use Angular's `HttpClient` and treat response bodies as data, not HTML templates.
- Enable strict CSP at the server / `index.html` and avoid inline script except nonced.

### Don't

- Do not use `bypassSecurityTrustHtml`, `bypassSecurityTrustUrl`, or `bypassSecurityTrustResourceUrl` on user or API data.
- Do not bind `[innerHTML]` to raw API or CMS HTML without sanitization.
- Do not construct templates dynamically from user input (template injection).
- Do not use `eval` or `new Function` with user-controlled strings in browser bundles.

### Verify

- Unit-test components with XSS payloads in inputs; expect escaped output, not script execution.
- Enable Angular ESLint security-related rules in CI.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for file_upload_ui controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for multi_tenant controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for search_index controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do (use this in Angular)

- Use SameSite=Lax or Strict on session cookies; prefer token-based APIs with Authorization header.
- If cookie auth: double-submit CSRF token or framework middleware on all state-changing routes.

### Don't

- Do not perform state-changing `fetch` with cookies cross-site without CSRF protection.
- Do not store CSRF secrets only in JS-accessible storage without rotation.

### Verify

- Integration test cross-origin POST without token expects 403.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in Angular)

- Apply domain skill `security-cms-content-platforms` requirements using angular supported APIs only.
- Use the official angular security documentation for rbac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of angular for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on angular projects in CI.

