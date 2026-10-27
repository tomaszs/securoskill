# Angular: Frontend and client-side security

Stack-specific implementation for **Angular** (Web UI). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

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

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in Angular)

- Enable `HttpClientXsrfModule` and ensure cookie `XSRF-TOKEN` is readable by Angular for mutating requests.
- Use `withCredentials` only to trusted API origins configured in `environment.ts`.

### Don't

- Do not disable XSRF module while using cookie sessions.
- Do not store CSRF token only in localStorage without double-submit validation.

### Verify

- E2E: POST without `X-XSRF-TOKEN` header returns 403.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in Angular)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.
- Run @angular-eslint and security rules on changes affecting `localStorage, sessionStorage, IndexedDB`.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in Angular)

- Map `Content Security Policy and security headers` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Content Security Policy and security headers` before merge.

### Don't

- Do not ship `Content Security Policy and security headers` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Content Security Policy and security headers`.

### Verify

- Peer review `Content Security Policy and security headers` against domain skill `security-frontend-client`.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in Angular)

- Map `SSR and hydration security` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `SSR and hydration security` before merge.

### Don't

- Do not ship `SSR and hydration security` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `SSR and hydration security`.

### Verify

- Peer review `SSR and hydration security` against domain skill `security-frontend-client`.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in Angular)

- Map `Web Workers and WebAssembly` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Web Workers and WebAssembly` before merge.

### Don't

- Do not ship `Web Workers and WebAssembly` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Web Workers and WebAssembly`.

### Verify

- Peer review `Web Workers and WebAssembly` against domain skill `security-frontend-client`.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in Angular)

- Map `Third-party scripts and tags` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Third-party scripts and tags` before merge.

### Don't

- Do not ship `Third-party scripts and tags` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Third-party scripts and tags`.

### Verify

- Peer review `Third-party scripts and tags` against domain skill `security-frontend-client`.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in Angular)

- Map `Frontend auth flows` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend auth flows` before merge.

### Don't

- Do not ship `Frontend auth flows` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Frontend auth flows`.

### Verify

- Peer review `Frontend auth flows` against domain skill `security-frontend-client`.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in Angular)

- Map `Client-side file upload UX` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Client-side file upload UX` before merge.

### Don't

- Do not ship `Client-side file upload UX` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Client-side file upload UX`.

### Verify

- Peer review `Client-side file upload UX` against domain skill `security-frontend-client`.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in Angular)

- Map `Accessibility vs security UX` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Accessibility vs security UX` before merge.

### Don't

- Do not ship `Accessibility vs security UX` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Accessibility vs security UX`.

### Verify

- Peer review `Accessibility vs security UX` against domain skill `security-frontend-client`.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in Angular)

- Map `Mobile web and PWA` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Mobile web and PWA` before merge.

### Don't

- Do not ship `Mobile web and PWA` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Mobile web and PWA`.

### Verify

- Peer review `Mobile web and PWA` against domain skill `security-frontend-client`.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in Angular)

- Map `Frontend dependency risk` controls to Angular APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend dependency risk` before merge.

### Don't

- Do not ship `Frontend dependency risk` work in Angular with only happy-path tests.
- Do not disable Angular security defaults to unblock `Frontend dependency risk`.

### Verify

- Peer review `Frontend dependency risk` against domain skill `security-frontend-client`.

