# LangChain / LangGraph: Web UI framework security

Stack-specific implementation for **LangChain / LangGraph** (AI). Normative rules: domain skill `security-web-framework-security` / `reference.md`.

## React

**Sub-topics:** dangerouslySetInnerHTML, useEffect fetches, Server Components, RSC leaks, Third-party hooks

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Vue.js

**Sub-topics:** v-html, Template compilation, Vuex persisted state, Nuxt SSR data, Dynamic components

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Angular

**Sub-topics:** DomSanitizer bypass, bypassSecurityTrust*, HttpClient CSRF, SSR transfer state, NgZone XSS

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Next.js and Nuxt

**Sub-topics:** API routes auth, Middleware bypass, ISR cache poisoning, Env NEXT_PUBLIC_, Server actions

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Svelte and SvelteKit

**Sub-topics:** {@html}, Form actions, Hooks auth, Adapter configs, CSR-only secrets

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Astro, Remix, and islands

**Sub-topics:** Hybrid rendering, Endpoint auth, View transitions, MDX components, Edge configs

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Client state libraries

**Sub-topics:** Redux persist tokens, URL state secrets, TanStack Query cache, Zustand devtools, IndexedDB sync

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Client routing security

**Sub-topics:** Route guards only client, Lazy route leaks, Deep link auth, History state, Base href

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## i18n and locale

**Sub-topics:** RTL injection, Locale switch CSRF, Translation XSS, Hreflang open redirect, Collation bugs

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Design system components

**Sub-topics:** Slot content XSS, Icon SVG, Toast HTML, Modal focus trap bypass, Theme injection

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

## Storybook and dev tools

**Sub-topics:** Exposed Storybook, Mock auth in prod, Addon scripts, Source maps public, Chromatic tokens

### Do (use this in LangChain / LangGraph)

- Wrap tools with `@tool` Pydantic schemas; reject extra fields.
- Use LangGraph interrupt points before destructive tool calls.
- Tag RAG documents with tenant_id metadata and filter retriever.

### Don't

- Do not pass raw webpage HTML into the system prompt as instructions.
- Do not expose `shell` or `sql` tools without argument allowlists.

### Verify

- Red-team corpus in CI with indirect injection in retrieved docs.

## Micro-frontends

**Sub-topics:** Module federation trust, Shared dependencies, Cross-app postMessage, Shell auth, Style isolation

### Do (use this in LangChain / LangGraph)

- LangChain / LangGraph is not the primary enforcement point for `web-framework-security`; load stack skill `security-web-framework-security` when you touch that layer.
- Keep LangChain / LangGraph configuration aligned with requirements from `security-web-framework-security` (domain reference.md).

### Don't

- Do not duplicate `web-framework-security` controls only in LangChain / LangGraph config while leaving security-web-framework-security misconfigured.
- Do not assume LangChain / LangGraph defaults satisfy `security-web-framework-security` without verification.

### Verify

- Integration test the full path: LangChain / LangGraph plus the system covered by `security-web-framework-security`.

