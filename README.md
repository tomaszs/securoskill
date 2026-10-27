# Secure Software Engineering Skills

**Agent-ready security skills for software engineering.**  
Give Cursor, Claude Code, or other AI agents a structured map of what to secure, from frontend XSS to cloud IAM, plus layered rules humans and models can follow in code review and implementation.

## Why this repo

Generic “be secure” prompts fail in practice. This collection spans **22 domains** and hundreds of sub-topics, each with rules at five levels:

| Level | Focus |
|-------|--------|
| Policy | Scope, ownership, risk, compliance |
| Design | Architecture, trust boundaries, defaults |
| Implementation | Code, crypto, validation, dependencies |
| Verification | Tests, SAST/DAST, manual abuse cases |
| Operations | Logging, monitoring, incident response |

Examples covered in depth: **SQL injection**, **XSS**, **SSRF**, **IDOR**, **secrets in CI**, **Kubernetes RBAC**, **prompt injection**, **Stripe webhooks**, **GDPR erasure**, and more.

## Quick start for AI agents

1. Add this repo to your agent’s skills path, or copy the folders you need.
2. Start with the parent skill: [`secure-software-engineering/SKILL.md`](secure-software-engineering/SKILL.md).
3. Load a domain skill when your task matches, for example:
   - `skills/backend-server/` for server-side injection and authorization
   - `skills/frontend-client/` for CSP, XSS, and browser storage
   - `skills/identity-access/` for authn, authz, MFA, SSO
   - `skills/ai-ml-security/` for LLM agents, RAG, and tool use

Each domain folder contains:

- `SKILL.md` – when to use, workflow, sub-area index  
- `rules.md` – full rule lists for every sub-area  

## Domain index

| Folder | Topic |
|--------|--------|
| `skills/frontend-client` | Frontend and client-side |
| `skills/backend-server` | Backend and server-side |
| `skills/api-integration` | APIs, GraphQL, webhooks |
| `skills/identity-access` | Identity and access control |
| `skills/data-databases` | Data and databases |
| `skills/cryptography` | Cryptography and keys |
| `skills/network-transport` | Network and transport |
| `skills/cloud-infrastructure` | Cloud infrastructure |
| `skills/containers-k8s` | Containers and Kubernetes |
| `skills/devsecops-cicd` | DevSecOps and CI/CD |
| `skills/supply-chain` | Software supply chain |
| `skills/secrets-config` | Secrets and configuration |
| `skills/logging-monitoring-ir` | Logging, monitoring, IR |
| `skills/privacy-compliance` | Privacy and compliance |
| `skills/mobile-security` | Mobile applications |
| `skills/ai-ml-security` | AI and ML systems |
| `skills/business-logic-abuse` | Business logic and abuse |
| `skills/sdlc-threat-modeling` | SDLC and threat modeling |
| `skills/email-notifications` | Email and notifications |
| `skills/realtime-messaging` | Real-time and messaging |
| `skills/payments-fintech` | Payments and fintech |
| `skills/observability-security` | Observability security |

## For humans

Use domain `rules.md` files as **review checklists** in PRs and pair them with your own threat models for new features.

## Format

Skills follow the [Cursor Agent Skills](https://cursor.com/docs/context/skills) layout: YAML frontmatter (`name`, `description`) plus actionable markdown. Descriptions are written for **discovery** so agents know when to load each skill.

## License

**Restricted use only.** See [LICENSE](LICENSE).

| Allowed | Not allowed |
|---------|-------------|
| Personal, non-commercial use by a **human** | Commercial use (including employer/client work) |
| Using skills with **your own** AI agents privately | Reuploading, mirroring, or public redistribution |
| Keeping a private copy for that personal use | Selling, licensing, or offering **derivatives** |
| | Reselling content or forked skill packs |

**Breach penalty:** USD **$5,000** per violation under the license (plus other remedies). Do not fork for redistribution; request written permission for any use beyond personal AI-agent use.
