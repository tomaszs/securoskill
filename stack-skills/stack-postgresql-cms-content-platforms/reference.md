# PostgreSQL: CMS, content platforms, and publishing

Stack-specific implementation for **PostgreSQL** (Database). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do (use this in PostgreSQL)

- PostgreSQL is not the primary enforcement point for `cms-content-platforms`; load stack skill `security-cms-content-platforms` when you touch that layer.
- Keep PostgreSQL configuration aligned with requirements from `security-cms-content-platforms` (domain reference.md).

### Don't

- Do not duplicate `cms-content-platforms` controls only in PostgreSQL config while leaving security-cms-content-platforms misconfigured.
- Do not assume PostgreSQL defaults satisfy `security-cms-content-platforms` without verification.

### Verify

- Integration test the full path: PostgreSQL plus the system covered by `security-cms-content-platforms`.

