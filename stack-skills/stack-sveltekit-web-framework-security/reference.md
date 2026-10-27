# SvelteKit: Web UI framework security

Stack-specific implementation for **SvelteKit** (Web UI). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do (use this in SvelteKit)

- Set security headers in sveltekit config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
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

### Do (use this in SvelteKit)

- Set security headers in sveltekit config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
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

### Do (use this in SvelteKit)

- Set security headers in sveltekit config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
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

### Do (use this in SvelteKit)

- Map `Next.js and Nuxt` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Next.js and Nuxt` before merge.

### Don't

- Do not ship `Next.js and Nuxt` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Next.js and Nuxt`.

### Verify

- Peer review `Next.js and Nuxt` against domain skill `security-web-framework-security`.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in SvelteKit)

- Map `Svelte and SvelteKit` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Svelte and SvelteKit` before merge.

### Don't

- Do not ship `Svelte and SvelteKit` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Svelte and SvelteKit`.

### Verify

- Peer review `Svelte and SvelteKit` against domain skill `security-web-framework-security`.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in SvelteKit)

- Map `Astro, Remix, and islands` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Astro, Remix, and islands` before merge.

### Don't

- Do not ship `Astro, Remix, and islands` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Astro, Remix, and islands`.

### Verify

- Peer review `Astro, Remix, and islands` against domain skill `security-web-framework-security`.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in SvelteKit)

- Store access tokens in memory or HttpOnly Secure SameSite cookies when possible.
- Use short-lived tokens and refresh via backend.

### Don't

- Do not store refresh tokens or PII in localStorage/sessionStorage.
- Do not read JWTs in client JS if they are only needed server-side.

### Verify

- Audit `localStorage.setItem` usage in frontend bundle.
- Run eslint-plugin-svelte on changes affecting `Client state libraries`.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in SvelteKit)

- Map `Client routing security` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Client routing security` before merge.

### Don't

- Do not ship `Client routing security` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Client routing security`.

### Verify

- Peer review `Client routing security` against domain skill `security-web-framework-security`.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in SvelteKit)

- Map `i18n and locale` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `i18n and locale` before merge.

### Don't

- Do not ship `i18n and locale` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `i18n and locale`.

### Verify

- Peer review `i18n and locale` against domain skill `security-web-framework-security`.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do (use this in SvelteKit)

- Set security headers in sveltekit config (`headers()`, `nitro.routeRules`, `astro.config` middleware).
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

### Do (use this in SvelteKit)

- Map `Storybook and dev tools` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Storybook and dev tools` before merge.

### Don't

- Do not ship `Storybook and dev tools` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Storybook and dev tools`.

### Verify

- Peer review `Storybook and dev tools` against domain skill `security-web-framework-security`.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in SvelteKit)

- Map `Micro-frontends` controls to SvelteKit APIs documented for `security-web-framework-security`.
- Add an abuse-case test or check for `Micro-frontends` before merge.

### Don't

- Do not ship `Micro-frontends` work in SvelteKit with only happy-path tests.
- Do not disable SvelteKit security defaults to unblock `Micro-frontends`.

### Verify

- Peer review `Micro-frontends` against domain skill `security-web-framework-security`.

