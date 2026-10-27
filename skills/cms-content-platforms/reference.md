# Rules reference: CMS, content platforms, and publishing

Headless CMS, WYSIWYG, and editorial workflows.

## Headless CMS APIs

Sub-topics: Preview tokens, Draft leakage, Webhook secrets, API tokens, GraphQL CMS

### Do

- Validate and canonicalize all inputs touching Headless CMS APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Headless CMS APIs.
- Keep dependencies patched; pin versions for Headless CMS APIs components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Headless CMS APIs in Headless CMS APIs as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Headless CMS APIs (CMS, content platforms, and publishing).
- Require security review for material changes affecting Headless CMS APIs.

### Design

- Apply least privilege and defense in depth for Headless CMS APIs.
- Prefer established patterns and libraries over custom crypto or auth for Headless CMS APIs.
- Fail closed: deny by default when Headless CMS APIs cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Headless CMS APIs; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Headless CMS APIs.
- Keep dependencies patched; pin versions for Headless CMS APIs components.

### Verification

- Add automated tests and SAST/DAST coverage for Headless CMS APIs paths.
- Run dependency and secret scanning on every change touching Headless CMS APIs.
- Perform targeted manual tests (abuse cases) for Headless CMS APIs.

### Operations

- Log security-relevant events for Headless CMS APIs without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Headless CMS APIs.
- Review access and configuration for Headless CMS APIs on a regular cadence.

## WYSIWYG editors

Sub-topics: Paste HTML, Embed iframes, Link protocols, Image uploads, Collaborative cursors

### Do

- Validate and canonicalize all inputs touching WYSIWYG editors; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WYSIWYG editors.
- Keep dependencies patched; pin versions for WYSIWYG editors components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat WYSIWYG editors in WYSIWYG editors as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for WYSIWYG editors (CMS, content platforms, and publishing).
- Require security review for material changes affecting WYSIWYG editors.

### Design

- Apply least privilege and defense in depth for WYSIWYG editors.
- Prefer established patterns and libraries over custom crypto or auth for WYSIWYG editors.
- Fail closed: deny by default when WYSIWYG editors cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching WYSIWYG editors; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to WYSIWYG editors.
- Keep dependencies patched; pin versions for WYSIWYG editors components.

### Verification

- Add automated tests and SAST/DAST coverage for WYSIWYG editors paths.
- Run dependency and secret scanning on every change touching WYSIWYG editors.
- Perform targeted manual tests (abuse cases) for WYSIWYG editors.

### Operations

- Log security-relevant events for WYSIWYG editors without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in WYSIWYG editors.
- Review access and configuration for WYSIWYG editors on a regular cadence.

## Publish workflows

Sub-topics: Approver bypass, Scheduled publish, Rollback, Multi-env sync, Cache purge

### Do

- Validate and canonicalize all inputs touching Publish workflows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Publish workflows.
- Keep dependencies patched; pin versions for Publish workflows components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Publish workflows in Publish workflows as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Publish workflows (CMS, content platforms, and publishing).
- Require security review for material changes affecting Publish workflows.

### Design

- Apply least privilege and defense in depth for Publish workflows.
- Prefer established patterns and libraries over custom crypto or auth for Publish workflows.
- Fail closed: deny by default when Publish workflows cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Publish workflows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Publish workflows.
- Keep dependencies patched; pin versions for Publish workflows components.

### Verification

- Add automated tests and SAST/DAST coverage for Publish workflows paths.
- Run dependency and secret scanning on every change touching Publish workflows.
- Perform targeted manual tests (abuse cases) for Publish workflows.

### Operations

- Log security-relevant events for Publish workflows without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Publish workflows.
- Review access and configuration for Publish workflows on a regular cadence.

## Plugins and themes

Sub-topics: Third-party PHP, npm theme scripts, Update channels, Supply chain, Sandbox

### Do

- Validate and canonicalize all inputs touching Plugins and themes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Plugins and themes.
- Keep dependencies patched; pin versions for Plugins and themes components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Plugins and themes in Plugins and themes as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Plugins and themes (CMS, content platforms, and publishing).
- Require security review for material changes affecting Plugins and themes.

### Design

- Apply least privilege and defense in depth for Plugins and themes.
- Prefer established patterns and libraries over custom crypto or auth for Plugins and themes.
- Fail closed: deny by default when Plugins and themes cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Plugins and themes; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Plugins and themes.
- Keep dependencies patched; pin versions for Plugins and themes components.

### Verification

- Add automated tests and SAST/DAST coverage for Plugins and themes paths.
- Run dependency and secret scanning on every change touching Plugins and themes.
- Perform targeted manual tests (abuse cases) for Plugins and themes.

### Operations

- Log security-relevant events for Plugins and themes without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Plugins and themes.
- Review access and configuration for Plugins and themes on a regular cadence.

## Comments and UGC moderation

Sub-topics: Spam, Illegal content, Reporter abuse, Auto-approve, Shadow bans

### Do

- Validate and canonicalize all inputs touching Comments and UGC moderation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Comments and UGC moderation.
- Keep dependencies patched; pin versions for Comments and UGC moderation components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Comments and UGC moderation in Comments and UGC moderation as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Comments and UGC moderation (CMS, content platforms, and publishing).
- Require security review for material changes affecting Comments and UGC moderation.

### Design

- Apply least privilege and defense in depth for Comments and UGC moderation.
- Prefer established patterns and libraries over custom crypto or auth for Comments and UGC moderation.
- Fail closed: deny by default when Comments and UGC moderation cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Comments and UGC moderation; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Comments and UGC moderation.
- Keep dependencies patched; pin versions for Comments and UGC moderation components.

### Verification

- Add automated tests and SAST/DAST coverage for Comments and UGC moderation paths.
- Run dependency and secret scanning on every change touching Comments and UGC moderation.
- Perform targeted manual tests (abuse cases) for Comments and UGC moderation.

### Operations

- Log security-relevant events for Comments and UGC moderation without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Comments and UGC moderation.
- Review access and configuration for Comments and UGC moderation on a regular cadence.

## SEO and metadata injection

Sub-topics: OpenGraph XSS, Canonical hijack, Sitemap poisoning, Hreflang, Structured data

### Do

- Validate and canonicalize all inputs touching SEO and metadata injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SEO and metadata injection.
- Keep dependencies patched; pin versions for SEO and metadata injection components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat SEO and metadata injection in SEO and metadata injection as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SEO and metadata injection (CMS, content platforms, and publishing).
- Require security review for material changes affecting SEO and metadata injection.

### Design

- Apply least privilege and defense in depth for SEO and metadata injection.
- Prefer established patterns and libraries over custom crypto or auth for SEO and metadata injection.
- Fail closed: deny by default when SEO and metadata injection cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SEO and metadata injection; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SEO and metadata injection.
- Keep dependencies patched; pin versions for SEO and metadata injection components.

### Verification

- Add automated tests and SAST/DAST coverage for SEO and metadata injection paths.
- Run dependency and secret scanning on every change touching SEO and metadata injection.
- Perform targeted manual tests (abuse cases) for SEO and metadata injection.

### Operations

- Log security-relevant events for SEO and metadata injection without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SEO and metadata injection.
- Review access and configuration for SEO and metadata injection on a regular cadence.

## Media libraries

Sub-topics: SVG in CMS, PDF previews, CDN paths, Alt text XSS, Hotlinking

### Do

- Validate and canonicalize all inputs touching Media libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Media libraries.
- Keep dependencies patched; pin versions for Media libraries components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Media libraries in Media libraries as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Media libraries (CMS, content platforms, and publishing).
- Require security review for material changes affecting Media libraries.

### Design

- Apply least privilege and defense in depth for Media libraries.
- Prefer established patterns and libraries over custom crypto or auth for Media libraries.
- Fail closed: deny by default when Media libraries cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Media libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Media libraries.
- Keep dependencies patched; pin versions for Media libraries components.

### Verification

- Add automated tests and SAST/DAST coverage for Media libraries paths.
- Run dependency and secret scanning on every change touching Media libraries.
- Perform targeted manual tests (abuse cases) for Media libraries.

### Operations

- Log security-relevant events for Media libraries without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Media libraries.
- Review access and configuration for Media libraries on a regular cadence.

## Multi-site CMS

Sub-topics: Site IDOR, Shared users, Domain mapping, SSL per site, Content sync

### Do

- Validate and canonicalize all inputs touching Multi-site CMS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-site CMS.
- Keep dependencies patched; pin versions for Multi-site CMS components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Multi-site CMS in Multi-site CMS as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Multi-site CMS (CMS, content platforms, and publishing).
- Require security review for material changes affecting Multi-site CMS.

### Design

- Apply least privilege and defense in depth for Multi-site CMS.
- Prefer established patterns and libraries over custom crypto or auth for Multi-site CMS.
- Fail closed: deny by default when Multi-site CMS cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Multi-site CMS; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Multi-site CMS.
- Keep dependencies patched; pin versions for Multi-site CMS components.

### Verification

- Add automated tests and SAST/DAST coverage for Multi-site CMS paths.
- Run dependency and secret scanning on every change touching Multi-site CMS.
- Perform targeted manual tests (abuse cases) for Multi-site CMS.

### Operations

- Log security-relevant events for Multi-site CMS without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Multi-site CMS.
- Review access and configuration for Multi-site CMS on a regular cadence.

## CMS search

Sub-topics: Elasticsearch public, Faceted leaks, Admin search, Indexed drafts, Query injection

### Do

- Validate and canonicalize all inputs touching CMS search; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS search.
- Keep dependencies patched; pin versions for CMS search components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CMS search in CMS search as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CMS search (CMS, content platforms, and publishing).
- Require security review for material changes affecting CMS search.

### Design

- Apply least privilege and defense in depth for CMS search.
- Prefer established patterns and libraries over custom crypto or auth for CMS search.
- Fail closed: deny by default when CMS search cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CMS search; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS search.
- Keep dependencies patched; pin versions for CMS search components.

### Verification

- Add automated tests and SAST/DAST coverage for CMS search paths.
- Run dependency and secret scanning on every change touching CMS search.
- Perform targeted manual tests (abuse cases) for CMS search.

### Operations

- Log security-relevant events for CMS search without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CMS search.
- Review access and configuration for CMS search on a regular cadence.

## Marketing forms

Sub-topics: Webhook spam, PII storage, Captcha bypass, Double opt-in, Export GDPR

### Do

- Validate and canonicalize all inputs touching Marketing forms; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketing forms.
- Keep dependencies patched; pin versions for Marketing forms components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Marketing forms in Marketing forms as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Marketing forms (CMS, content platforms, and publishing).
- Require security review for material changes affecting Marketing forms.

### Design

- Apply least privilege and defense in depth for Marketing forms.
- Prefer established patterns and libraries over custom crypto or auth for Marketing forms.
- Fail closed: deny by default when Marketing forms cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Marketing forms; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Marketing forms.
- Keep dependencies patched; pin versions for Marketing forms components.

### Verification

- Add automated tests and SAST/DAST coverage for Marketing forms paths.
- Run dependency and secret scanning on every change touching Marketing forms.
- Perform targeted manual tests (abuse cases) for Marketing forms.

### Operations

- Log security-relevant events for Marketing forms without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Marketing forms.
- Review access and configuration for Marketing forms on a regular cadence.

## Static site generators

Sub-topics: Build-time secrets, ISR vs SSG, Decap CMS, Git-based auth, Preview servers

### Do

- Validate and canonicalize all inputs touching Static site generators; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static site generators.
- Keep dependencies patched; pin versions for Static site generators components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Static site generators in Static site generators as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Static site generators (CMS, content platforms, and publishing).
- Require security review for material changes affecting Static site generators.

### Design

- Apply least privilege and defense in depth for Static site generators.
- Prefer established patterns and libraries over custom crypto or auth for Static site generators.
- Fail closed: deny by default when Static site generators cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Static site generators; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Static site generators.
- Keep dependencies patched; pin versions for Static site generators components.

### Verification

- Add automated tests and SAST/DAST coverage for Static site generators paths.
- Run dependency and secret scanning on every change touching Static site generators.
- Perform targeted manual tests (abuse cases) for Static site generators.

### Operations

- Log security-relevant events for Static site generators without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Static site generators.
- Review access and configuration for Static site generators on a regular cadence.

## CMS roles and SSO

Sub-topics: Editor vs admin, SSO mis-map, API users, Impersonation, Audit trail

### Do

- Validate and canonicalize all inputs touching CMS roles and SSO; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS roles and SSO.
- Keep dependencies patched; pin versions for CMS roles and SSO components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat CMS roles and SSO in CMS roles and SSO as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CMS roles and SSO (CMS, content platforms, and publishing).
- Require security review for material changes affecting CMS roles and SSO.

### Design

- Apply least privilege and defense in depth for CMS roles and SSO.
- Prefer established patterns and libraries over custom crypto or auth for CMS roles and SSO.
- Fail closed: deny by default when CMS roles and SSO cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CMS roles and SSO; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CMS roles and SSO.
- Keep dependencies patched; pin versions for CMS roles and SSO components.

### Verification

- Add automated tests and SAST/DAST coverage for CMS roles and SSO paths.
- Run dependency and secret scanning on every change touching CMS roles and SSO.
- Perform targeted manual tests (abuse cases) for CMS roles and SSO.

### Operations

- Log security-relevant events for CMS roles and SSO without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CMS roles and SSO.
- Review access and configuration for CMS roles and SSO on a regular cadence.

