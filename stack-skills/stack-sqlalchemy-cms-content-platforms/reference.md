# SQLAlchemy: CMS, content platforms, and publishing

Stack-specific implementation for **SQLAlchemy** (ORM / data access). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for cms_api controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do (use this in SQLAlchemy)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for workflow controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for supply_chain controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for content_abuse controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do (use this in SQLAlchemy)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for file_upload_ui controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for multi_tenant controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for search_index controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do (use this in SQLAlchemy)

- Protect cookie-authenticated mutations with CSRF tokens or SameSite + custom headers.

### Don't

- Do not rely on CORS alone to prevent CSRF.

### Verify

- Add automated abuse-case tests for Marketing forms in SQLAlchemy.
- Run SAST and dependency scans for ORM / data access in CI.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in SQLAlchemy)

- Apply domain skill `security-cms-content-platforms` requirements using sqlalchemy supported APIs only.
- Use the official sqlalchemy security documentation for rbac controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of sqlalchemy for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on sqlalchemy projects in CI.

