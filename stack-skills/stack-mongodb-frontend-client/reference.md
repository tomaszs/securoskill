# MongoDB: Frontend and client-side security

Stack-specific implementation for **MongoDB** (Database). Normative rules: domain skill `security-frontend-client` / `reference.md`.

## Cross-site scripting (reflected, stored, DOM)

**Sub-topics:** HTML injection in templates, dangerouslySetInnerHTML / v-html, URL fragment and postMessage handlers, Markdown and rich text renderers, SVG and MathML sinks

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## CSRF and clickjacking

**Sub-topics:** Form posts, Cookie-based sessions, iframes, Cross-origin embeds, Threat modeling and trust boundaries (CSRF and clickjacking)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## localStorage, sessionStorage, IndexedDB

**Sub-topics:** Token storage, PII in browser, Cache poisoning, Threat modeling and trust boundaries (localStorage, sessionStorage, IndexedDB), Abuse cases and adversarial testing (localStorage, sessionStorage, IndexedDB)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Content Security Policy and security headers

**Sub-topics:** CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy, Threat modeling and trust boundaries (Content Security Policy and security headers)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## SSR and hydration security

**Sub-topics:** Serialized state, HTML injection at render, Islands architecture, Threat modeling and trust boundaries (SSR and hydration security), Abuse cases and adversarial testing (SSR and hydration security)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Web Workers and WebAssembly

**Sub-topics:** Shared memory, postMessage trust, Wasm module integrity, Threat modeling and trust boundaries (Web Workers and WebAssembly), Abuse cases and adversarial testing (Web Workers and WebAssembly)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Third-party scripts and tags

**Sub-topics:** Analytics, Chat widgets, Tag managers, Subresource Integrity, Threat modeling and trust boundaries (Third-party scripts and tags)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Frontend auth flows

**Sub-topics:** OAuth redirects, PKCE, Implicit flow avoidance, Token in URL, Threat modeling and trust boundaries (Frontend auth flows)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Client-side file upload UX

**Sub-topics:** Type sniffing, Preview gadgets, Size limits, Threat modeling and trust boundaries (Client-side file upload UX), Abuse cases and adversarial testing (Client-side file upload UX)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Accessibility vs security UX

**Sub-topics:** Captcha, Rate limit messaging, Screen reader safe errors, Threat modeling and trust boundaries (Accessibility vs security UX), Abuse cases and adversarial testing (Accessibility vs security UX)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Mobile web and PWA

**Sub-topics:** Service workers, Web push, App shell caching, Threat modeling and trust boundaries (Mobile web and PWA), Abuse cases and adversarial testing (Mobile web and PWA)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

## Frontend dependency risk

**Sub-topics:** npm supply chain, Transitive packages, CDN compromise, Threat modeling and trust boundaries (Frontend dependency risk), Abuse cases and adversarial testing (Frontend dependency risk)

### Do (use this in MongoDB)

- MongoDB is not the primary enforcement point for `frontend-client`; load stack skill `stack-react-frontend-client (or your UI stack)` when you touch that layer.
- Keep MongoDB configuration aligned with requirements from `security-frontend-client` (domain reference.md).

### Don't

- Do not duplicate `frontend-client` controls only in MongoDB config while leaving stack-react-frontend-client (or your UI stack) misconfigured.
- Do not assume MongoDB defaults satisfy `security-frontend-client` without verification.

### Verify

- Integration test the full path: MongoDB plus the system covered by `stack-react-frontend-client (or your UI stack)`.

