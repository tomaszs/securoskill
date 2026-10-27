# React: Frontend and client-side security

Stack-specific implementation for **React** (Web UI). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Do (use this in React)

- Render user text only as JSX children: `<span>{userName}</span>`.
- If HTML is required, sanitize with DOMPurify then pass to `dangerouslySetInnerHTML={{ __html: clean }}`.
- Validate URLs before `href`: allowlist `https:` (and app-needed schemes); reject `javascript:`.
- Use CSP with nonces for any inline script in CRA/Vite via hosting config or middleware.

### Don't

- Do not use `dangerouslySetInnerHTML` with API, markdown, or WYSIWYG output without sanitization.
- Do not build HTML with string concatenation and assign to DOM (including refs and `innerHTML`).
- Do not pass unsanitized user input into `react-markdown` custom components that render raw HTML.
- Do not disable ESLint `react/no-danger` without a documented sanitizer boundary.

### Verify

- Add component tests that assert script tags from user input are not rendered.
- Run OWASP ZAP or similar against staging with authenticated flows.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in React)

- Use SameSite=Lax or Strict on session cookies; prefer token-based APIs with Authorization header.
- If cookie auth: double-submit CSRF token or framework middleware on all state-changing routes.

### Don't

- Do not perform state-changing `fetch` with cookies cross-site without CSRF protection.
- Do not store CSRF secrets only in JS-accessible storage without rotation.

### Verify

- Integration test cross-origin POST without token expects 403.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in React)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for csp controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for file_upload_ui controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for pwa controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in React)

- Apply domain skill `security-frontend-client` requirements using react supported APIs only.
- Use the official react security documentation for supply_chain controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react projects in CI.

