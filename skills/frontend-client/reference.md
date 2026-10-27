# Rules reference: Frontend and client-side security

Browsers, SPAs, SSR, Web APIs, and client storage.

## Cross-site scripting (reflected, stored, DOM)

Sub-topics: HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Policy

- Treat Cross-site scripting (reflected, stored, DOM) in Cross-site scripting (reflected, stored, DOM) as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Cross-site scripting (reflected, stored, DOM) (Frontend and client-side security).
- Require security review for material changes affecting Cross-site scripting (reflected, stored, DOM).

### Design

- Apply least privilege and defense in depth for Cross-site scripting (reflected, stored, DOM).
- Prefer established patterns and libraries over custom crypto or auth for Cross-site scripting (reflected, stored, DOM).
- Fail closed: deny by default when Cross-site scripting (reflected, stored, DOM) cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Cross-site scripting (reflected, stored, DOM); never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Cross-site scripting (reflected, stored, DOM).
- Keep dependencies patched; pin versions for Cross-site scripting (reflected, stored, DOM) components.
- Use framework auto-escaping; sanitize HTML only with vetted allowlists.
- Set Content-Security-Policy with nonces or hashes for inline script.

### Verification

- Add automated tests and SAST/DAST coverage for Cross-site scripting (reflected, stored, DOM) paths.
- Run dependency and secret scanning on every change touching Cross-site scripting (reflected, stored, DOM).
- Perform targeted manual tests (abuse cases) for Cross-site scripting (reflected, stored, DOM).

### Operations

- Log security-relevant events for Cross-site scripting (reflected, stored, DOM) without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Cross-site scripting (reflected, stored, DOM).
- Review access and configuration for Cross-site scripting (reflected, stored, DOM) on a regular cadence.

## CSRF and clickjacking

Sub-topics: Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Policy

- Treat CSRF and clickjacking in CSRF and clickjacking as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for CSRF and clickjacking (Frontend and client-side security).
- Require security review for material changes affecting CSRF and clickjacking.

### Design

- Apply least privilege and defense in depth for CSRF and clickjacking.
- Prefer established patterns and libraries over custom crypto or auth for CSRF and clickjacking.
- Fail closed: deny by default when CSRF and clickjacking cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching CSRF and clickjacking; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to CSRF and clickjacking.
- Keep dependencies patched; pin versions for CSRF and clickjacking components.
- Use SameSite cookies and anti-CSRF tokens for state-changing requests.

### Verification

- Add automated tests and SAST/DAST coverage for CSRF and clickjacking paths.
- Run dependency and secret scanning on every change touching CSRF and clickjacking.
- Perform targeted manual tests (abuse cases) for CSRF and clickjacking.

### Operations

- Log security-relevant events for CSRF and clickjacking without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in CSRF and clickjacking.
- Review access and configuration for CSRF and clickjacking on a regular cadence.

## localStorage, sessionStorage, IndexedDB

Sub-topics: Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Policy

- Treat localStorage, sessionStorage, IndexedDB in localStorage, sessionStorage, IndexedDB as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for localStorage, sessionStorage, IndexedDB (Frontend and client-side security).
- Require security review for material changes affecting localStorage, sessionStorage, IndexedDB.

### Design

- Apply least privilege and defense in depth for localStorage, sessionStorage, IndexedDB.
- Prefer established patterns and libraries over custom crypto or auth for localStorage, sessionStorage, IndexedDB.
- Fail closed: deny by default when localStorage, sessionStorage, IndexedDB cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching localStorage, sessionStorage, IndexedDB; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to localStorage, sessionStorage, IndexedDB.
- Keep dependencies patched; pin versions for localStorage, sessionStorage, IndexedDB components.

### Verification

- Add automated tests and SAST/DAST coverage for localStorage, sessionStorage, IndexedDB paths.
- Run dependency and secret scanning on every change touching localStorage, sessionStorage, IndexedDB.
- Perform targeted manual tests (abuse cases) for localStorage, sessionStorage, IndexedDB.

### Operations

- Log security-relevant events for localStorage, sessionStorage, IndexedDB without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in localStorage, sessionStorage, IndexedDB.
- Review access and configuration for localStorage, sessionStorage, IndexedDB on a regular cadence.

## Content Security Policy and security headers

Sub-topics: CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Policy

- Treat Content Security Policy and security headers in Content Security Policy and security headers as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Content Security Policy and security headers (Frontend and client-side security).
- Require security review for material changes affecting Content Security Policy and security headers.

### Design

- Apply least privilege and defense in depth for Content Security Policy and security headers.
- Prefer established patterns and libraries over custom crypto or auth for Content Security Policy and security headers.
- Fail closed: deny by default when Content Security Policy and security headers cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Content Security Policy and security headers; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Content Security Policy and security headers.
- Keep dependencies patched; pin versions for Content Security Policy and security headers components.

### Verification

- Add automated tests and SAST/DAST coverage for Content Security Policy and security headers paths.
- Run dependency and secret scanning on every change touching Content Security Policy and security headers.
- Perform targeted manual tests (abuse cases) for Content Security Policy and security headers.

### Operations

- Log security-relevant events for Content Security Policy and security headers without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Content Security Policy and security headers.
- Review access and configuration for Content Security Policy and security headers on a regular cadence.

## SSR and hydration security

Sub-topics: Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Policy

- Treat SSR and hydration security in SSR and hydration security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for SSR and hydration security (Frontend and client-side security).
- Require security review for material changes affecting SSR and hydration security.

### Design

- Apply least privilege and defense in depth for SSR and hydration security.
- Prefer established patterns and libraries over custom crypto or auth for SSR and hydration security.
- Fail closed: deny by default when SSR and hydration security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching SSR and hydration security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to SSR and hydration security.
- Keep dependencies patched; pin versions for SSR and hydration security components.

### Verification

- Add automated tests and SAST/DAST coverage for SSR and hydration security paths.
- Run dependency and secret scanning on every change touching SSR and hydration security.
- Perform targeted manual tests (abuse cases) for SSR and hydration security.

### Operations

- Log security-relevant events for SSR and hydration security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in SSR and hydration security.
- Review access and configuration for SSR and hydration security on a regular cadence.

## Web Workers and WebAssembly

Sub-topics: Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Policy

- Treat Web Workers and WebAssembly in Web Workers and WebAssembly as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Web Workers and WebAssembly (Frontend and client-side security).
- Require security review for material changes affecting Web Workers and WebAssembly.

### Design

- Apply least privilege and defense in depth for Web Workers and WebAssembly.
- Prefer established patterns and libraries over custom crypto or auth for Web Workers and WebAssembly.
- Fail closed: deny by default when Web Workers and WebAssembly cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Web Workers and WebAssembly; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Web Workers and WebAssembly.
- Keep dependencies patched; pin versions for Web Workers and WebAssembly components.

### Verification

- Add automated tests and SAST/DAST coverage for Web Workers and WebAssembly paths.
- Run dependency and secret scanning on every change touching Web Workers and WebAssembly.
- Perform targeted manual tests (abuse cases) for Web Workers and WebAssembly.

### Operations

- Log security-relevant events for Web Workers and WebAssembly without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Web Workers and WebAssembly.
- Review access and configuration for Web Workers and WebAssembly on a regular cadence.

## Third-party scripts and tags

Sub-topics: Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Policy

- Treat Third-party scripts and tags in Third-party scripts and tags as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Third-party scripts and tags (Frontend and client-side security).
- Require security review for material changes affecting Third-party scripts and tags.

### Design

- Apply least privilege and defense in depth for Third-party scripts and tags.
- Prefer established patterns and libraries over custom crypto or auth for Third-party scripts and tags.
- Fail closed: deny by default when Third-party scripts and tags cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Third-party scripts and tags; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Third-party scripts and tags.
- Keep dependencies patched; pin versions for Third-party scripts and tags components.

### Verification

- Add automated tests and SAST/DAST coverage for Third-party scripts and tags paths.
- Run dependency and secret scanning on every change touching Third-party scripts and tags.
- Perform targeted manual tests (abuse cases) for Third-party scripts and tags.

### Operations

- Log security-relevant events for Third-party scripts and tags without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Third-party scripts and tags.
- Review access and configuration for Third-party scripts and tags on a regular cadence.

## Frontend auth flows

Sub-topics: OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Policy

- Treat Frontend auth flows in Frontend auth flows as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Frontend auth flows (Frontend and client-side security).
- Require security review for material changes affecting Frontend auth flows.

### Design

- Apply least privilege and defense in depth for Frontend auth flows.
- Prefer established patterns and libraries over custom crypto or auth for Frontend auth flows.
- Fail closed: deny by default when Frontend auth flows cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Frontend auth flows; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Frontend auth flows.
- Keep dependencies patched; pin versions for Frontend auth flows components.

### Verification

- Add automated tests and SAST/DAST coverage for Frontend auth flows paths.
- Run dependency and secret scanning on every change touching Frontend auth flows.
- Perform targeted manual tests (abuse cases) for Frontend auth flows.

### Operations

- Log security-relevant events for Frontend auth flows without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Frontend auth flows.
- Review access and configuration for Frontend auth flows on a regular cadence.

## Client-side file upload UX

Sub-topics: Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Policy

- Treat Client-side file upload UX in Client-side file upload UX as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Client-side file upload UX (Frontend and client-side security).
- Require security review for material changes affecting Client-side file upload UX.

### Design

- Apply least privilege and defense in depth for Client-side file upload UX.
- Prefer established patterns and libraries over custom crypto or auth for Client-side file upload UX.
- Fail closed: deny by default when Client-side file upload UX cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Client-side file upload UX; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client-side file upload UX.
- Keep dependencies patched; pin versions for Client-side file upload UX components.

### Verification

- Add automated tests and SAST/DAST coverage for Client-side file upload UX paths.
- Run dependency and secret scanning on every change touching Client-side file upload UX.
- Perform targeted manual tests (abuse cases) for Client-side file upload UX.

### Operations

- Log security-relevant events for Client-side file upload UX without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Client-side file upload UX.
- Review access and configuration for Client-side file upload UX on a regular cadence.

## Accessibility vs security UX

Sub-topics: Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Policy

- Treat Accessibility vs security UX in Accessibility vs security UX as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Accessibility vs security UX (Frontend and client-side security).
- Require security review for material changes affecting Accessibility vs security UX.

### Design

- Apply least privilege and defense in depth for Accessibility vs security UX.
- Prefer established patterns and libraries over custom crypto or auth for Accessibility vs security UX.
- Fail closed: deny by default when Accessibility vs security UX cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Accessibility vs security UX; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Accessibility vs security UX.
- Keep dependencies patched; pin versions for Accessibility vs security UX components.

### Verification

- Add automated tests and SAST/DAST coverage for Accessibility vs security UX paths.
- Run dependency and secret scanning on every change touching Accessibility vs security UX.
- Perform targeted manual tests (abuse cases) for Accessibility vs security UX.

### Operations

- Log security-relevant events for Accessibility vs security UX without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Accessibility vs security UX.
- Review access and configuration for Accessibility vs security UX on a regular cadence.

## Mobile web and PWA

Sub-topics: Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Policy

- Treat Mobile web and PWA in Mobile web and PWA as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Mobile web and PWA (Frontend and client-side security).
- Require security review for material changes affecting Mobile web and PWA.

### Design

- Apply least privilege and defense in depth for Mobile web and PWA.
- Prefer established patterns and libraries over custom crypto or auth for Mobile web and PWA.
- Fail closed: deny by default when Mobile web and PWA cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Mobile web and PWA; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Mobile web and PWA.
- Keep dependencies patched; pin versions for Mobile web and PWA components.

### Verification

- Add automated tests and SAST/DAST coverage for Mobile web and PWA paths.
- Run dependency and secret scanning on every change touching Mobile web and PWA.
- Perform targeted manual tests (abuse cases) for Mobile web and PWA.

### Operations

- Log security-relevant events for Mobile web and PWA without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Mobile web and PWA.
- Review access and configuration for Mobile web and PWA on a regular cadence.

## Frontend dependency risk

Sub-topics: npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Policy

- Treat Frontend dependency risk in Frontend dependency risk as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Frontend dependency risk (Frontend and client-side security).
- Require security review for material changes affecting Frontend dependency risk.

### Design

- Apply least privilege and defense in depth for Frontend dependency risk.
- Prefer established patterns and libraries over custom crypto or auth for Frontend dependency risk.
- Fail closed: deny by default when Frontend dependency risk cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Frontend dependency risk; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Frontend dependency risk.
- Keep dependencies patched; pin versions for Frontend dependency risk components.

### Verification

- Add automated tests and SAST/DAST coverage for Frontend dependency risk paths.
- Run dependency and secret scanning on every change touching Frontend dependency risk.
- Perform targeted manual tests (abuse cases) for Frontend dependency risk.

### Operations

- Log security-relevant events for Frontend dependency risk without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Frontend dependency risk.
- Review access and configuration for Frontend dependency risk on a regular cadence.

