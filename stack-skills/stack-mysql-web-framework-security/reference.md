# MySQL / MariaDB: Web UI framework security

Stack-specific implementation for **MySQL / MariaDB** (Database). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Platform rules (summary)

- Validate and canonicalize all inputs touching React; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to React.
- Keep dependencies patched; pin versions for React components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for React before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for React paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Platform rules (summary)

- Validate and canonicalize all inputs touching Vue.js; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vue.js.
- Keep dependencies patched; pin versions for Vue.js components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Vue.js before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Vue.js paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Platform rules (summary)

- Validate and canonicalize all inputs touching Angular; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Angular.
- Keep dependencies patched; pin versions for Angular components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Angular before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Angular paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Platform rules (summary)

- Validate and canonicalize all inputs touching Next.js and Nuxt; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Next.js and Nuxt.
- Keep dependencies patched; pin versions for Next.js and Nuxt components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Next.js and Nuxt before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Next.js and Nuxt paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Platform rules (summary)

- Validate and canonicalize all inputs touching Svelte and SvelteKit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Svelte and SvelteKit.
- Keep dependencies patched; pin versions for Svelte and SvelteKit components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Svelte and SvelteKit before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Svelte and SvelteKit paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Platform rules (summary)

- Validate and canonicalize all inputs touching Astro, Remix, and islands; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Astro, Remix, and islands.
- Keep dependencies patched; pin versions for Astro, Remix, and islands components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Astro, Remix, and islands before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Astro, Remix, and islands paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Platform rules (summary)

- Validate and canonicalize all inputs touching Client state libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client state libraries.
- Keep dependencies patched; pin versions for Client state libraries components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Client state libraries before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Client state libraries paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Platform rules (summary)

- Validate and canonicalize all inputs touching Client routing security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client routing security.
- Keep dependencies patched; pin versions for Client routing security components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Client routing security before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Client routing security paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Platform rules (summary)

- Validate and canonicalize all inputs touching i18n and locale; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to i18n and locale.
- Keep dependencies patched; pin versions for i18n and locale components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for i18n and locale before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for i18n and locale paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Platform rules (summary)

- Validate and canonicalize all inputs touching Design system components; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design system components.
- Keep dependencies patched; pin versions for Design system components components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Design system components before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Design system components paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Platform rules (summary)

- Validate and canonicalize all inputs touching Storybook and dev tools; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Storybook and dev tools.
- Keep dependencies patched; pin versions for Storybook and dev tools components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Storybook and dev tools before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Storybook and dev tools paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Platform rules (summary)

- Validate and canonicalize all inputs touching Micro-frontends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-frontends.
- Keep dependencies patched; pin versions for Micro-frontends components.

### How to do this in MySQL / MariaDB

- Read normative rules in domain skill `security-web-framework-security` / `reference.md`, then apply them using MySQL / MariaDB APIs and deployment model.
- Prefer framework-maintained security features in MySQL / MariaDB over custom crypto, auth, or parsers.
- Add stack-appropriate tests (unit + integration) for Micro-frontends before merge.
- Pin MySQL / MariaDB dependencies; monitor CVE advisories for your stack.

### Verify

- Add automated tests for Micro-frontends paths in MySQL / MariaDB.
- Run SAST/dependency scan configured for Database.

