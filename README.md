# Secure Software Engineering Skills for AI Agents

**Free structured security skills for Cursor, Claude Code, Copilot, and other AI coding agents.**  
Cover **secure coding**, **application security**, **cloud security**, **DevSecOps**, and **AI security** with checklists an agent can follow while it writes and reviews code.

Use of this repository is subject to the [LICENSE](LICENSE).

## Two layers of skills

| Layer | Folders | Purpose |
|-------|---------|---------|
| **Domain** (what) | `skills/<domain>/`, `secure-software-engineering/` | Technology-neutral rules: policy, design, implementation, verification, operations (e.g. prevent SQL injection, IDOR, prompt injection). |
| **Stack** (how) | `stack-skills/stack-<tech>-<domain>/` | Same **34 domains** translated into concrete patterns for a specific technology (APIs, configs, libraries). |

**Coverage:** 34 domains × **44 stacks** = **1,496** stack–domain skills, plus **44** stack orchestrators (`stack-skills/stack-react/`, etc.). Each stack skill links to its domain counterpart (`security-<domain>`).

## Supported technologies (44 stacks)

| Category | Technologies |
|----------|----------------|
| **Web UI** | React, Vue.js, Angular, Svelte, Next.js, Nuxt, SvelteKit, Remix, Astro |
| **Node.js server** | Express.js, NestJS, Fastify |
| **Python** | Django, FastAPI, Flask |
| **Java** | Spring Boot |
| **.NET** | ASP.NET Core |
| **Ruby** | Ruby on Rails |
| **PHP** | Laravel, Symfony |
| **Go** | Gin |
| **Rust** | Actix Web |
| **Mobile** | React Native, Flutter, SwiftUI (iOS), Kotlin / Jetpack Compose |
| **Database** | PostgreSQL, MySQL / MariaDB, MongoDB, Redis |
| **ORM / data access** | Prisma, SQLAlchemy, TypeORM, Hibernate / JPA |
| **Cloud** | AWS, Google Cloud, Microsoft Azure |
| **Platform** | Vercel, Cloudflare Workers |
| **Infrastructure** | Kubernetes, Docker, Terraform |
| **AI** | LangChain / LangGraph, OpenAI API / Agents SDK |

Full machine-readable list: [`stack-skills/manifest.json`](stack-skills/manifest.json).

## What you get

| | |
|--|--|
| **34 security domains** | Frontend, backend, APIs, identity, data, crypto, network, cloud, Kubernetes, CI/CD, supply chain, privacy, mobile, AI/ML, payments, Web3, IoT, desktop, and more |
| **408 sub-areas** | SQL injection, XSS, SSRF, IDOR, tenant isolation, smart contracts, etc. |
| **2,000+ sub-topics** | Five or more per sub-area, each with layered rules |
| **Stack implementations** | Every domain mirrored for every supported stack |

## Benefits

- **Normative + practical:** Domain skills state what must hold; stack skills show how in your framework.
- **Fewer missed vulnerabilities:** Agents use concrete APIs (ORM bindings, CSP headers, IAM roles) instead of vague advice.
- **Faster reviews:** `reference.md` in each folder works as a checklist.
- **Offline install:** Use the [skills zip](#install-from-zip-recommended); no build step.

## Skill format (Cursor Agent Skills)

| File | Role |
|------|------|
| `SKILL.md` | YAML `name`, `description`, workflow (`disable-model-invocation: true`). |
| `reference.md` | Full rules or stack-specific implementation detail. |

Domain skill names: `security-<domain>` (e.g. `security-backend-server`).  
Stack skill names: `stack-<tech>-<domain>` (e.g. `stack-django-backend-server`).  
Stack orchestrators: `stack-<tech>` (e.g. `stack-react`).

## Install from zip (recommended)

Download **[`dist/secure-software-engineering-skills.zip`](dist/secure-software-engineering-skills.zip)** (personal use only; see LICENSE).

1. Unzip the archive.
2. Copy **every top-level folder** into your personal skills directory:
   - **macOS / Linux:** `~/.cursor/skills/`
   - **Windows:** `%USERPROFILE%\.cursor\skills\`
3. You should see domain folders (`backend-server`, `secure-software-engineering`, …) and stack folders (`stack-react`, `stack-django-backend-server`, …).  
   Do **not** add an extra `skills/` nesting level.
4. Restart Cursor (or reload the window).
5. **Domain-only work:** invoke `secure-software-engineering` or `security-backend-server`.  
   **Stack-specific work:** invoke `stack-react` or `stack-spring-boot-data-databases`.

### Install from git clone

1. Copy `secure-software-engineering/` and each child of `skills/` into `~/.cursor/skills/`.
2. Copy each child of `stack-skills/` into `~/.cursor/skills/` (or install only the `stack-<tech>*` folders you need).

## How to use

1. **Scope** the change (UI, API, DB, infra).
2. **Domain:** pick `security-<domain>` for requirements and tests.
3. **Stack:** pick `stack-<your-tech>-<domain>` for implementation bullets.
4. **Cross-cut:** `identity-access`, `secrets-config`, `logging-monitoring-ir` when auth, secrets, or logs are involved.

### Example prompts

- “Use `stack-nextjs-frontend-client` for this page.”
- “Review with `security-api-integration` and `stack-fastapi-api-integration`.”
- “`stack-prisma-data-databases` for this schema and queries.”

## Domain index (technology-neutral)

| Folder | Security focus |
|--------|----------------|
| `frontend-client` | Browser, SPA, SSR, CSP, XSS |
| `backend-server` | Injection, authz, sessions |
| `api-integration` | REST, GraphQL, webhooks |
| `identity-access` | Authn, MFA, SSO, RBAC |
| `data-databases` | SQL/NoSQL, encryption, RLS |
| `cryptography` | TLS, keys, JWT |
| `network-transport` | SSRF, DNS, WAF |
| `cloud-infrastructure` | IAM, storage, VPC |
| `containers-k8s` | Images, RBAC, policies |
| `devsecops-cicd` | SAST, DAST, CI secrets |
| `supply-chain` | Dependencies, SBOM |
| `secrets-config` | Env vars, rotation |
| `logging-monitoring-ir` | SIEM, incident response |
| `privacy-compliance` | GDPR, PCI |
| `mobile-security` | iOS, Android |
| `ai-ml-security` | Prompt injection, RAG |
| `business-logic-abuse` | Fraud, IDOR |
| `sdlc-threat-modeling` | STRIDE, secure design |
| `email-notifications` | SPF/DKIM |
| `realtime-messaging` | WebSocket, Kafka |
| `payments-fintech` | PCI, webhooks |
| `observability-security` | Traces, APM |
| `multi-tenancy-saas` | Tenant isolation |
| `serverless-edge` | FaaS, workers |
| `file-object-storage` | Uploads, presigned URLs |
| `zero-trust-access` | ZTNA, device posture |
| `blockchain-web3` | Smart contracts |
| `embedded-iot-ot` | Firmware, MQTT |
| `desktop-native` | Electron, Tauri |
| `web-framework-security` | React, Vue, Angular |
| `server-framework-security` | Node, Django, Spring |
| `data-engineering-analytics` | Warehouses, ETL |
| `cms-content-platforms` | Headless CMS |
| `human-factors-abuse` | Phishing, support abuse |

Parent: **`secure-software-engineering`**.

## Who this is for

Developers using **AI pair programmers**, security champions, and anyone searching for **Cursor security skills**, **stack-specific secure coding**, or **application security checklists**.

## FAQ

**How are domain and stack skills different?**  
Domain = what to enforce. Stack = how to enforce it in a named technology. Always align stack guidance with the domain `reference.md`.

**Is this professional security or legal advice?**  
No. See [LICENSE](LICENSE).

**Can I use this at work?**  
See [LICENSE](LICENSE).
