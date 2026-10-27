# React Native: Web UI framework security

Stack-specific implementation for **React Native** (Mobile). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for ssr controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in React Native)

- Apply domain skill `security-frontend-client` requirements using react-native supported APIs only.
- Use the official react-native security documentation for browser_storage controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for frontend_auth controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for generic_frontend controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do (use this in React Native)

- Prefer native `Text` components over WebView for untrusted content.

### Don't

- Do not enable `javaScriptEnabled` on WebView showing user HTML without a strict CSP and URL allowlist.

### Verify

- Static analysis with MobSF or platform linters on release builds.

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for debug_endpoints controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in React Native)

- Apply domain skill `security-web-framework-security` requirements using react-native supported APIs only.
- Use the official react-native security documentation for third_party_scripts controls.
- Add automated tests for abuse cases before merging.

### Don't

- Do not disable security features of react-native for convenience in production.
- Do not copy generic examples from blogs that skip validation or authz.

### Verify

- Run stack-appropriate SAST/DAST on react-native projects in CI.

