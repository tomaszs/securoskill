# Flutter: Frontend and client-side security

Stack-specific implementation for **Flutter** (Mobile). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Do (use this in Flutter)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in Flutter)

- Protect cookie-authenticated mutations with CSRF tokens or SameSite + custom headers.

### Don't

- Do not rely on CORS alone to prevent CSRF.

### Verify

- Add automated abuse-case tests for CSRF and clickjacking in Flutter.
- Run SAST and dependency scans for Mobile in CI.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in Flutter)

- Map `localStorage, sessionStorage, IndexedDB` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `localStorage, sessionStorage, IndexedDB` before merge.

### Don't

- Do not ship `localStorage, sessionStorage, IndexedDB` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `localStorage, sessionStorage, IndexedDB`.

### Verify

- Peer review `localStorage, sessionStorage, IndexedDB` against domain skill `security-frontend-client`.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in Flutter)

- Map `Content Security Policy and security headers` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Content Security Policy and security headers` before merge.

### Don't

- Do not ship `Content Security Policy and security headers` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Content Security Policy and security headers`.

### Verify

- Peer review `Content Security Policy and security headers` against domain skill `security-frontend-client`.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in Flutter)

- Map `SSR and hydration security` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `SSR and hydration security` before merge.

### Don't

- Do not ship `SSR and hydration security` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `SSR and hydration security`.

### Verify

- Peer review `SSR and hydration security` against domain skill `security-frontend-client`.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in Flutter)

- Map `Web Workers and WebAssembly` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Web Workers and WebAssembly` before merge.

### Don't

- Do not ship `Web Workers and WebAssembly` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Web Workers and WebAssembly`.

### Verify

- Peer review `Web Workers and WebAssembly` against domain skill `security-frontend-client`.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in Flutter)

- Map `Third-party scripts and tags` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Third-party scripts and tags` before merge.

### Don't

- Do not ship `Third-party scripts and tags` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Third-party scripts and tags`.

### Verify

- Peer review `Third-party scripts and tags` against domain skill `security-frontend-client`.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in Flutter)

- Map `Frontend auth flows` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend auth flows` before merge.

### Don't

- Do not ship `Frontend auth flows` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Frontend auth flows`.

### Verify

- Peer review `Frontend auth flows` against domain skill `security-frontend-client`.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in Flutter)

- Map `Client-side file upload UX` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Client-side file upload UX` before merge.

### Don't

- Do not ship `Client-side file upload UX` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Client-side file upload UX`.

### Verify

- Peer review `Client-side file upload UX` against domain skill `security-frontend-client`.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in Flutter)

- Map `Accessibility vs security UX` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Accessibility vs security UX` before merge.

### Don't

- Do not ship `Accessibility vs security UX` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Accessibility vs security UX`.

### Verify

- Peer review `Accessibility vs security UX` against domain skill `security-frontend-client`.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in Flutter)

- Map `Mobile web and PWA` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Mobile web and PWA` before merge.

### Don't

- Do not ship `Mobile web and PWA` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Mobile web and PWA`.

### Verify

- Peer review `Mobile web and PWA` against domain skill `security-frontend-client`.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in Flutter)

- Map `Frontend dependency risk` controls to Flutter APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend dependency risk` before merge.

### Don't

- Do not ship `Frontend dependency risk` work in Flutter with only happy-path tests.
- Do not disable Flutter security defaults to unblock `Frontend dependency risk`.

### Verify

- Peer review `Frontend dependency risk` against domain skill `security-frontend-client`.

