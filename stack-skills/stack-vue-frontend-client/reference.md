# Vue.js: Frontend and client-side security

Stack-specific implementation for **Vue.js** (Web UI). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Do (use this in Vue.js)

- Use `{{ }}` text interpolation for user data (escaped by default).
- Use `v-text` instead of `v-html` when formatting is not required.
- If `v-html` is required, sanitize with DOMPurify in a computed property first.
- Configure CSP on the host (Nuxt `routeRules` / Vite plugin headers).

### Don't

- Do not use `v-html` with CMS, comment, or API HTML without a sanitizer.
- Do not bind `href` to unvalidated user URLs.
- Do not inject user strings into `<style>` or `<script>` blocks in SFCs dynamically.

### Verify

- Add Vitest tests with typical XSS vectors in props and store state.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in Vue.js)

- Configure `xsrfCookieName` / `xsrfHeaderName` on axios defaults when the API uses cookie sessions.
- Align with your API's CSRF cookie name and header (e.g. `X-XSRF-TOKEN`).

### Don't

- Do not globally set `withCredentials: true` without CSRF pairing.

### Verify

- Vitest axios mock asserts CSRF header on POST.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in Vue.js)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.
- Run eslint-plugin-vue on changes affecting `localStorage, sessionStorage, IndexedDB`.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in Vue.js)

- Map `Content Security Policy and security headers` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Content Security Policy and security headers` before merge.

### Don't

- Do not ship `Content Security Policy and security headers` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Content Security Policy and security headers`.

### Verify

- Peer review `Content Security Policy and security headers` against domain skill `security-frontend-client`.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in Vue.js)

- Map `SSR and hydration security` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `SSR and hydration security` before merge.

### Don't

- Do not ship `SSR and hydration security` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `SSR and hydration security`.

### Verify

- Peer review `SSR and hydration security` against domain skill `security-frontend-client`.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in Vue.js)

- Map `Web Workers and WebAssembly` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Web Workers and WebAssembly` before merge.

### Don't

- Do not ship `Web Workers and WebAssembly` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Web Workers and WebAssembly`.

### Verify

- Peer review `Web Workers and WebAssembly` against domain skill `security-frontend-client`.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in Vue.js)

- Map `Third-party scripts and tags` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Third-party scripts and tags` before merge.

### Don't

- Do not ship `Third-party scripts and tags` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Third-party scripts and tags`.

### Verify

- Peer review `Third-party scripts and tags` against domain skill `security-frontend-client`.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in Vue.js)

- Map `Frontend auth flows` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend auth flows` before merge.

### Don't

- Do not ship `Frontend auth flows` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Frontend auth flows`.

### Verify

- Peer review `Frontend auth flows` against domain skill `security-frontend-client`.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in Vue.js)

- Map `Client-side file upload UX` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Client-side file upload UX` before merge.

### Don't

- Do not ship `Client-side file upload UX` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Client-side file upload UX`.

### Verify

- Peer review `Client-side file upload UX` against domain skill `security-frontend-client`.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in Vue.js)

- Map `Accessibility vs security UX` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Accessibility vs security UX` before merge.

### Don't

- Do not ship `Accessibility vs security UX` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Accessibility vs security UX`.

### Verify

- Peer review `Accessibility vs security UX` against domain skill `security-frontend-client`.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in Vue.js)

- Map `Mobile web and PWA` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Mobile web and PWA` before merge.

### Don't

- Do not ship `Mobile web and PWA` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Mobile web and PWA`.

### Verify

- Peer review `Mobile web and PWA` against domain skill `security-frontend-client`.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in Vue.js)

- Map `Frontend dependency risk` controls to Vue.js APIs documented for `security-frontend-client`.
- Add an abuse-case test or check for `Frontend dependency risk` before merge.

### Don't

- Do not ship `Frontend dependency risk` work in Vue.js with only happy-path tests.
- Do not disable Vue.js security defaults to unblock `Frontend dependency risk`.

### Verify

- Peer review `Frontend dependency risk` against domain skill `security-frontend-client`.

