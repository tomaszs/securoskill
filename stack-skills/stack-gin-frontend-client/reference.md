# Gin (Go): Frontend and client-side security

Stack-specific implementation for **Gin (Go)** (Go). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Do (use this in Gin (Go))

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in Gin (Go))

- Protect cookie-authenticated mutations with CSRF tokens or SameSite + custom headers.

### Don't

- Do not rely on CORS alone to prevent CSRF.

### Verify

- Add automated abuse-case tests for CSRF and clickjacking in Gin (Go).
- Run SAST and dependency scans for Go in CI.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for browser_storage controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for csp controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for workers controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for file_upload_ui controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for pwa controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in Gin (Go))

- Apply domain skill `security-frontend-client` requirements using gin supported APIs only.
- Use the official gin security documentation for supply_chain controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of gin for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on gin projects in CI.

