# Nuxt: Web UI framework security

Stack-specific implementation for **Nuxt** (Web UI). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do (use this in Nuxt)

- Set security headers in nuxt config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
- Keep secrets and admin logic in server-only modules (no `NEXT_PUBLIC_` for sensitive values on Next).
- Validate and encode user content in server components / loaders before HTML emission.

### Don't

- Do not expose server env vars to client bundles via public config keys.
- Do not render raw HTML from CMS in SSR without sanitization at the server boundary.
- Do not skip auth checks in API routes / server actions assumed 'internal only'.

### Verify

- Scan SSR HTML output for unescaped script injection in integration tests.

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Do (use this in Nuxt)

- Set security headers in nuxt config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
- Keep secrets and admin logic in server-only modules (no `NEXT_PUBLIC_` for sensitive values on Next).
- Validate and encode user content in server components / loaders before HTML emission.

### Don't

- Do not expose server env vars to client bundles via public config keys.
- Do not render raw HTML from CMS in SSR without sanitization at the server boundary.
- Do not skip auth checks in API routes / server actions assumed 'internal only'.

### Verify

- Scan SSR HTML output for unescaped script injection in integration tests.

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Do (use this in Nuxt)

- Set security headers in nuxt config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
- Keep secrets and admin logic in server-only modules (no `NEXT_PUBLIC_` for sensitive values on Next).
- Validate and encode user content in server components / loaders before HTML emission.

### Don't

- Do not expose server env vars to client bundles via public config keys.
- Do not render raw HTML from CMS in SSR without sanitization at the server boundary.
- Do not skip auth checks in API routes / server actions assumed 'internal only'.

### Verify

- Scan SSR HTML output for unescaped script injection in integration tests.

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in Nuxt)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do (use this in Nuxt)

- Set security headers in nuxt config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
- Keep secrets and admin logic in server-only modules (no `NEXT_PUBLIC_` for sensitive values on Next).
- Validate and encode user content in server components / loaders before HTML emission.

### Don't

- Do not expose server env vars to client bundles via public config keys.
- Do not render raw HTML from CMS in SSR without sanitization at the server boundary.
- Do not skip auth checks in API routes / server actions assumed 'internal only'.

### Verify

- Scan SSR HTML output for unescaped script injection in integration tests.

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for debug_endpoints controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in Nuxt)

- Apply domain skill `security-web-framework-security` requirements using nuxt supported APIs only.
- Use the official nuxt security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of nuxt for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on nuxt projects in CI.

