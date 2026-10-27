# Django: Web UI framework security

Stack-specific implementation for **Django** (Python). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do (use this in Django)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Do (use this in Django)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Do (use this in Django)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in Django)

- Apply domain skill `security-frontend-client` requirements using django supported APIs only.
- Use the official django security documentation for browser_storage controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do (use this in Django)

- Encode all user-controlled output at the UI sink for this stack.

### Don't

- Do not mix untrusted HTML with framework escape boundaries.

### Verify

- Manual XSS test cases on forms and rich text.

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for debug_endpoints controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in Django)

- Apply domain skill `security-web-framework-security` requirements using django supported APIs only.
- Use the official django security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of django for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on django projects in CI.

