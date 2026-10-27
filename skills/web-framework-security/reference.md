# Rules reference: Web UI framework security

React, Vue, Angular, Svelte, and meta-frameworks.

## React

Sub-topics: dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do

- Validate and canonicalize all inputs touching React; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to React.
- Keep dependencies patched; pin versions for React components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat React in React as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for React (Web UI framework security).
- Require security review for material changes affecting React.

### Design

- Apply least privilege and defense in depth for React.
- Prefer established patterns and libraries over custom crypto or auth for React.
- Fail closed: deny by default when React cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching React; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to React.
- Keep dependencies patched; pin versions for React components.

### Verification

- Add automated tests and SAST/DAST coverage for React paths.
- Run dependency and secret scanning on every change touching React.
- Perform targeted manual tests (abuse cases) for React.

### Operations

- Log security-relevant events for React without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in React.
- Review access and configuration for React on a regular cadence.

## Vue.js

Sub-topics: v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Do

- Validate and canonicalize all inputs touching Vue.js; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vue.js.
- Keep dependencies patched; pin versions for Vue.js components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Vue.js in Vue.js as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Vue.js (Web UI framework security).
- Require security review for material changes affecting Vue.js.

### Design

- Apply least privilege and defense in depth for Vue.js.
- Prefer established patterns and libraries over custom crypto or auth for Vue.js.
- Fail closed: deny by default when Vue.js cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Vue.js; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Vue.js.
- Keep dependencies patched; pin versions for Vue.js components.

### Verification

- Add automated tests and SAST/DAST coverage for Vue.js paths.
- Run dependency and secret scanning on every change touching Vue.js.
- Perform targeted manual tests (abuse cases) for Vue.js.

### Operations

- Log security-relevant events for Vue.js without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Vue.js.
- Review access and configuration for Vue.js on a regular cadence.

## Angular

Sub-topics: DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Do

- Validate and canonicalize all inputs touching Angular; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Angular.
- Keep dependencies patched; pin versions for Angular components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Angular in Angular as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Angular (Web UI framework security).
- Require security review for material changes affecting Angular.

### Design

- Apply least privilege and defense in depth for Angular.
- Prefer established patterns and libraries over custom crypto or auth for Angular.
- Fail closed: deny by default when Angular cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Angular; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Angular.
- Keep dependencies patched; pin versions for Angular components.

### Verification

- Add automated tests and SAST/DAST coverage for Angular paths.
- Run dependency and secret scanning on every change touching Angular.
- Perform targeted manual tests (abuse cases) for Angular.

### Operations

- Log security-relevant events for Angular without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Angular.
- Review access and configuration for Angular on a regular cadence.

## Next.js and Nuxt

Sub-topics: API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do

- Validate and canonicalize all inputs touching Next.js and Nuxt; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Next.js and Nuxt.
- Keep dependencies patched; pin versions for Next.js and Nuxt components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Next.js and Nuxt in Next.js and Nuxt as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Next.js and Nuxt (Web UI framework security).
- Require security review for material changes affecting Next.js and Nuxt.

### Design

- Apply least privilege and defense in depth for Next.js and Nuxt.
- Prefer established patterns and libraries over custom crypto or auth for Next.js and Nuxt.
- Fail closed: deny by default when Next.js and Nuxt cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Next.js and Nuxt; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Next.js and Nuxt.
- Keep dependencies patched; pin versions for Next.js and Nuxt components.

### Verification

- Add automated tests and SAST/DAST coverage for Next.js and Nuxt paths.
- Run dependency and secret scanning on every change touching Next.js and Nuxt.
- Perform targeted manual tests (abuse cases) for Next.js and Nuxt.

### Operations

- Log security-relevant events for Next.js and Nuxt without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Next.js and Nuxt.
- Review access and configuration for Next.js and Nuxt on a regular cadence.

## Svelte and SvelteKit

Sub-topics: {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do

- Validate and canonicalize all inputs touching Svelte and SvelteKit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Svelte and SvelteKit.
- Keep dependencies patched; pin versions for Svelte and SvelteKit components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Svelte and SvelteKit in Svelte and SvelteKit as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Svelte and SvelteKit (Web UI framework security).
- Require security review for material changes affecting Svelte and SvelteKit.

### Design

- Apply least privilege and defense in depth for Svelte and SvelteKit.
- Prefer established patterns and libraries over custom crypto or auth for Svelte and SvelteKit.
- Fail closed: deny by default when Svelte and SvelteKit cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Svelte and SvelteKit; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Svelte and SvelteKit.
- Keep dependencies patched; pin versions for Svelte and SvelteKit components.

### Verification

- Add automated tests and SAST/DAST coverage for Svelte and SvelteKit paths.
- Run dependency and secret scanning on every change touching Svelte and SvelteKit.
- Perform targeted manual tests (abuse cases) for Svelte and SvelteKit.

### Operations

- Log security-relevant events for Svelte and SvelteKit without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Svelte and SvelteKit.
- Review access and configuration for Svelte and SvelteKit on a regular cadence.

## Astro, Remix, and islands

Sub-topics: Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do

- Validate and canonicalize all inputs touching Astro, Remix, and islands; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Astro, Remix, and islands.
- Keep dependencies patched; pin versions for Astro, Remix, and islands components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Astro, Remix, and islands in Astro, Remix, and islands as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Astro, Remix, and islands (Web UI framework security).
- Require security review for material changes affecting Astro, Remix, and islands.

### Design

- Apply least privilege and defense in depth for Astro, Remix, and islands.
- Prefer established patterns and libraries over custom crypto or auth for Astro, Remix, and islands.
- Fail closed: deny by default when Astro, Remix, and islands cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Astro, Remix, and islands; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Astro, Remix, and islands.
- Keep dependencies patched; pin versions for Astro, Remix, and islands components.

### Verification

- Add automated tests and SAST/DAST coverage for Astro, Remix, and islands paths.
- Run dependency and secret scanning on every change touching Astro, Remix, and islands.
- Perform targeted manual tests (abuse cases) for Astro, Remix, and islands.

### Operations

- Log security-relevant events for Astro, Remix, and islands without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Astro, Remix, and islands.
- Review access and configuration for Astro, Remix, and islands on a regular cadence.

## Client state libraries

Sub-topics: Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do

- Validate and canonicalize all inputs touching Client state libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client state libraries.
- Keep dependencies patched; pin versions for Client state libraries components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Client state libraries in Client state libraries as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Client state libraries (Web UI framework security).
- Require security review for material changes affecting Client state libraries.

### Design

- Apply least privilege and defense in depth for Client state libraries.
- Prefer established patterns and libraries over custom crypto or auth for Client state libraries.
- Fail closed: deny by default when Client state libraries cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Client state libraries; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client state libraries.
- Keep dependencies patched; pin versions for Client state libraries components.

### Verification

- Add automated tests and SAST/DAST coverage for Client state libraries paths.
- Run dependency and secret scanning on every change touching Client state libraries.
- Perform targeted manual tests (abuse cases) for Client state libraries.

### Operations

- Log security-relevant events for Client state libraries without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Client state libraries.
- Review access and configuration for Client state libraries on a regular cadence.

## Client routing security

Sub-topics: Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do

- Validate and canonicalize all inputs touching Client routing security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client routing security.
- Keep dependencies patched; pin versions for Client routing security components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Client routing security in Client routing security as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Client routing security (Web UI framework security).
- Require security review for material changes affecting Client routing security.

### Design

- Apply least privilege and defense in depth for Client routing security.
- Prefer established patterns and libraries over custom crypto or auth for Client routing security.
- Fail closed: deny by default when Client routing security cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Client routing security; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Client routing security.
- Keep dependencies patched; pin versions for Client routing security components.

### Verification

- Add automated tests and SAST/DAST coverage for Client routing security paths.
- Run dependency and secret scanning on every change touching Client routing security.
- Perform targeted manual tests (abuse cases) for Client routing security.

### Operations

- Log security-relevant events for Client routing security without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Client routing security.
- Review access and configuration for Client routing security on a regular cadence.

## i18n and locale

Sub-topics: RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do

- Validate and canonicalize all inputs touching i18n and locale; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to i18n and locale.
- Keep dependencies patched; pin versions for i18n and locale components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat i18n and locale in i18n and locale as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for i18n and locale (Web UI framework security).
- Require security review for material changes affecting i18n and locale.

### Design

- Apply least privilege and defense in depth for i18n and locale.
- Prefer established patterns and libraries over custom crypto or auth for i18n and locale.
- Fail closed: deny by default when i18n and locale cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching i18n and locale; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to i18n and locale.
- Keep dependencies patched; pin versions for i18n and locale components.

### Verification

- Add automated tests and SAST/DAST coverage for i18n and locale paths.
- Run dependency and secret scanning on every change touching i18n and locale.
- Perform targeted manual tests (abuse cases) for i18n and locale.

### Operations

- Log security-relevant events for i18n and locale without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in i18n and locale.
- Review access and configuration for i18n and locale on a regular cadence.

## Design system components

Sub-topics: Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do

- Validate and canonicalize all inputs touching Design system components; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design system components.
- Keep dependencies patched; pin versions for Design system components components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Design system components in Design system components as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Design system components (Web UI framework security).
- Require security review for material changes affecting Design system components.

### Design

- Apply least privilege and defense in depth for Design system components.
- Prefer established patterns and libraries over custom crypto or auth for Design system components.
- Fail closed: deny by default when Design system components cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Design system components; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Design system components.
- Keep dependencies patched; pin versions for Design system components components.

### Verification

- Add automated tests and SAST/DAST coverage for Design system components paths.
- Run dependency and secret scanning on every change touching Design system components.
- Perform targeted manual tests (abuse cases) for Design system components.

### Operations

- Log security-relevant events for Design system components without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Design system components.
- Review access and configuration for Design system components on a regular cadence.

## Storybook and dev tools

Sub-topics: Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do

- Validate and canonicalize all inputs touching Storybook and dev tools; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Storybook and dev tools.
- Keep dependencies patched; pin versions for Storybook and dev tools components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Storybook and dev tools in Storybook and dev tools as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Storybook and dev tools (Web UI framework security).
- Require security review for material changes affecting Storybook and dev tools.

### Design

- Apply least privilege and defense in depth for Storybook and dev tools.
- Prefer established patterns and libraries over custom crypto or auth for Storybook and dev tools.
- Fail closed: deny by default when Storybook and dev tools cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Storybook and dev tools; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Storybook and dev tools.
- Keep dependencies patched; pin versions for Storybook and dev tools components.

### Verification

- Add automated tests and SAST/DAST coverage for Storybook and dev tools paths.
- Run dependency and secret scanning on every change touching Storybook and dev tools.
- Perform targeted manual tests (abuse cases) for Storybook and dev tools.

### Operations

- Log security-relevant events for Storybook and dev tools without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Storybook and dev tools.
- Review access and configuration for Storybook and dev tools on a regular cadence.

## Micro-frontends

Sub-topics: Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do

- Validate and canonicalize all inputs touching Micro-frontends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-frontends.
- Keep dependencies patched; pin versions for Micro-frontends components.

### Don't

- Do not skip server-side validation for this sub-area.
- Do not disable security controls for performance without review.

### Policy

- Treat Micro-frontends in Micro-frontends as in-scope for threat modeling and security requirements before implementation.
- Define acceptable risk, data classification, and ownership for Micro-frontends (Web UI framework security).
- Require security review for material changes affecting Micro-frontends.

### Design

- Apply least privilege and defense in depth for Micro-frontends.
- Prefer established patterns and libraries over custom crypto or auth for Micro-frontends.
- Fail closed: deny by default when Micro-frontends cannot be validated.

### Implementation

- Validate and canonicalize all inputs touching Micro-frontends; never trust client-side checks alone.
- Use parameterized queries / safe APIs; avoid string concatenation for queries and commands.
- Encode output appropriately for the sink (HTML, URL, JS, SQL) relevant to Micro-frontends.
- Keep dependencies patched; pin versions for Micro-frontends components.

### Verification

- Add automated tests and SAST/DAST coverage for Micro-frontends paths.
- Run dependency and secret scanning on every change touching Micro-frontends.
- Perform targeted manual tests (abuse cases) for Micro-frontends.

### Operations

- Log security-relevant events for Micro-frontends without logging secrets or excessive PII.
- Define alerts and runbooks for abuse or failure modes in Micro-frontends.
- Review access and configuration for Micro-frontends on a regular cadence.

