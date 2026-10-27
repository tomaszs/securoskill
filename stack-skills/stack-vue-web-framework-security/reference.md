# Vue.js: Web UI framework security

Stack-specific implementation for **Vue.js** (Web UI). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

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

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

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

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

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

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in Vue.js)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

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

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for debug_endpoints controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in Vue.js)

- Apply domain skill `security-web-framework-security` requirements using vue supported APIs only.
- Use the official vue security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of vue for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on vue projects in CI.

