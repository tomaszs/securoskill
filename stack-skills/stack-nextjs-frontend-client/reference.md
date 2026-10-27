# Next.js: Frontend and client-side security

Stack-specific implementation for **Next.js** (Web UI). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Platform rules (summary)

- Validate and canonicalize all inputs touching Cross-site scripting (reflected, stored, DOM); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cross-site scripting (reflected, stored, DOM).
- Keep dependencies patched; pin versions for Cross-site scripting (reflected, stored, DOM) components.

### How to do this in Next.js

- Default to React/Vue/Angular auto-escaping; never use `dangerouslySetInnerHTML` / `v-html` / `bypassSecurityTrustHtml` without a vetted sanitizer (e.g. DOMPurify).
- Set strict CSP with nonces in Next.js hosting (Next.js `headers()`, Nuxt `routeRules`, etc.).
- Sanitize URL `href` and `javascript:` sinks in Next.js link components.
- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Cross-site scripting (reflected, stored, DOM) before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Cross-site scripting (reflected, stored, DOM) paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Platform rules (summary)

- Validate and canonicalize all inputs touching CSRF and clickjacking; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CSRF and clickjacking.
- Keep dependencies patched; pin versions for CSRF and clickjacking components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for CSRF and clickjacking before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for CSRF and clickjacking paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Platform rules (summary)

- Validate and canonicalize all inputs touching localStorage, sessionStorage, IndexedDB; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to localStorage, sessionStorage, IndexedDB.
- Keep dependencies patched; pin versions for localStorage, sessionStorage, IndexedDB components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for localStorage, sessionStorage, IndexedDB before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for localStorage, sessionStorage, IndexedDB paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Content Security Policy and security headers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Content Security Policy and security headers.
- Keep dependencies patched; pin versions for Content Security Policy and security headers components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Content Security Policy and security headers before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Content Security Policy and security headers paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Platform rules (summary)

- Validate and canonicalize all inputs touching SSR and hydration security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSR and hydration security.
- Keep dependencies patched; pin versions for SSR and hydration security components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for SSR and hydration security before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for SSR and hydration security paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Web Workers and WebAssembly; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Web Workers and WebAssembly.
- Keep dependencies patched; pin versions for Web Workers and WebAssembly components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Web Workers and WebAssembly before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Web Workers and WebAssembly paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Third-party scripts and tags; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party scripts and tags.
- Keep dependencies patched; pin versions for Third-party scripts and tags components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Third-party scripts and tags before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Third-party scripts and tags paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Frontend auth flows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Frontend auth flows.
- Keep dependencies patched; pin versions for Frontend auth flows components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Frontend auth flows before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Frontend auth flows paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Client-side file upload UX; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client-side file upload UX.
- Keep dependencies patched; pin versions for Client-side file upload UX components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Client-side file upload UX before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Client-side file upload UX paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Accessibility vs security UX; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Accessibility vs security UX.
- Keep dependencies patched; pin versions for Accessibility vs security UX components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Accessibility vs security UX before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Accessibility vs security UX paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Mobile web and PWA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile web and PWA.
- Keep dependencies patched; pin versions for Mobile web and PWA components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Mobile web and PWA before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Mobile web and PWA paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Platform rules (summary)

- Validate and canonicalize all inputs touching Frontend dependency risk; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Frontend dependency risk.
- Keep dependencies patched; pin versions for Frontend dependency risk components.

### How to do this in Next.js

- Read normative rules in domain skill `security-frontend-client` / `reference.md`, then apply them using Next.js APIs and deployment model.
- Prefer framework-maintained security features in Next.js over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Frontend dependency risk before merge.
- Pin Next.js dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Frontend dependency risk paths in Next.js.
- Run SAST/dependency scan configured for Web UI.

