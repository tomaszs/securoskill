# Prisma: CMS, content platforms, and publishing

Stack-specific implementation for **Prisma** (ORM / data access). Normative rules: domain skill `security-cms-content-platforms` / `reference.md`.

## Headless CMS APIs

**Sub-topics:** Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Platform rules (summary)

- Validate and canonicalize all inputs touching Headless CMS APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Headless CMS APIs.
- Keep dependencies patched; pin versions for Headless CMS APIs components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Headless CMS APIs before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Headless CMS APIs paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## WYSIWYG editors

**Sub-topics:** Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Platform rules (summary)

- Validate and canonicalize all inputs touching WYSIWYG editors; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WYSIWYG editors.
- Keep dependencies patched; pin versions for WYSIWYG editors components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for WYSIWYG editors before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for WYSIWYG editors paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Publish workflows

**Sub-topics:** Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Platform rules (summary)

- Validate and canonicalize all inputs touching Publish workflows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Publish workflows.
- Keep dependencies patched; pin versions for Publish workflows components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Publish workflows before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Publish workflows paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Plugins and themes

**Sub-topics:** Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Platform rules (summary)

- Validate and canonicalize all inputs touching Plugins and themes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Plugins and themes.
- Keep dependencies patched; pin versions for Plugins and themes components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Plugins and themes before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Plugins and themes paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Comments and UGC moderation

**Sub-topics:** Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Platform rules (summary)

- Validate and canonicalize all inputs touching Comments and UGC moderation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Comments and UGC moderation.
- Keep dependencies patched; pin versions for Comments and UGC moderation components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Comments and UGC moderation before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Comments and UGC moderation paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## SEO and metadata injection

**Sub-topics:** OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Platform rules (summary)

- Validate and canonicalize all inputs touching SEO and metadata injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SEO and metadata injection.
- Keep dependencies patched; pin versions for SEO and metadata injection components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SEO and metadata injection before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SEO and metadata injection paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Media libraries

**Sub-topics:** SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Platform rules (summary)

- Validate and canonicalize all inputs touching Media libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Media libraries.
- Keep dependencies patched; pin versions for Media libraries components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Media libraries before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Media libraries paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Multi-site CMS

**Sub-topics:** Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Platform rules (summary)

- Validate and canonicalize all inputs touching Multi-site CMS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-site CMS.
- Keep dependencies patched; pin versions for Multi-site CMS components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Multi-site CMS before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Multi-site CMS paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## CMS search

**Sub-topics:** Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Platform rules (summary)

- Validate and canonicalize all inputs touching CMS search; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS search.
- Keep dependencies patched; pin versions for CMS search components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CMS search before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CMS search paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Marketing forms

**Sub-topics:** Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Platform rules (summary)

- Validate and canonicalize all inputs touching Marketing forms; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketing forms.
- Keep dependencies patched; pin versions for Marketing forms components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Marketing forms before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Marketing forms paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## Static site generators

**Sub-topics:** Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Platform rules (summary)

- Validate and canonicalize all inputs touching Static site generators; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static site generators.
- Keep dependencies patched; pin versions for Static site generators components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Static site generators before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Static site generators paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

## CMS roles and SSO

**Sub-topics:** Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Platform rules (summary)

- Validate and canonicalize all inputs touching CMS roles and SSO; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS roles and SSO.
- Keep dependencies patched; pin versions for CMS roles and SSO components.

### How to do this in Prisma

- Read normative rules in domain skill `security-cms-content-platforms` / `reference.md`, then apply them using Prisma APIs and deployment model.
- Prefer framework-maintained security features in Prisma over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CMS roles and SSO before merge.
- Pin Prisma dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CMS roles and SSO paths in Prisma.
- Run SAST/dependency scan configured for ORM / data access.

