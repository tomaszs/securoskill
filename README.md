# Secure Software Engineering Skills for AI Agents

**Free structured security skills for Cursor, Claude Code, Copilot, and other AI coding agents.**  
Cover **secure coding**, **application security**, **cloud security**, **DevSecOps**, and **AI security** with checklists an agent can follow while it writes and reviews code.

Use of this repository is subject to the [LICENSE](LICENSE).

## What you get

| | |
|--|--|
| **34 security domains** | Frontend, backend, APIs, identity, data, crypto, network, cloud, Kubernetes, CI/CD, supply chain, privacy, mobile, AI/ML, payments, Web3, IoT, desktop, frameworks, and more |
| **408 sub-areas** | Each with concrete topics (SQL injection, XSS, SSRF, IDOR, prompt injection, tenant isolation, presigned URLs, smart contract reentrancy, Electron hardening, etc.) |
| **2,000+ fine-grained topics** | Five or more sub-topics per sub-area, each with layered rules |
| **5 rule layers** | Policy, design, implementation, verification, and operations |

## Benefits

- **Fewer missed vulnerabilities:** Agents get domain-specific rules instead of generic “write secure code” prompts.
- **Faster reviews:** `reference.md` files work as PR checklists for humans and as context for agents.
- **Consistent depth:** Same five-level structure across all domains.
- **Stack-aware:** Dedicated skills for **React, Vue, Angular, Next.js**, **Django, Spring, .NET, Node**, and other common frameworks.
- **Modern risks included:** LLM prompt injection, RAG ACLs, multi-tenant SaaS isolation, serverless denial-of-wallet, observability data leaks.
- **Offline install:** Use the [skills zip](#install-from-zip-recommended) with no build step.

## Skill format (Cursor Agent Skills)

This package follows the open [Cursor Agent Skills](https://cursor.com/docs/context/skills) layout:

| File | Role |
|------|------|
| `SKILL.md` | Required. YAML `name` and `description`, when to use, workflow (`disable-model-invocation: true` so skills load when you invoke them). |
| `reference.md` | Detailed rules (progressive disclosure). Linked from `SKILL.md`. |

**Coverage:** 34 top-level domains, each with **at least 12 sub-areas**; each sub-area has **at least 5 sub-topics** and **five rule levels** (policy through operations). One parent skill (`secure-software-engineering`) plus 34 domain skills.

## Install from zip (recommended)

Download **[`dist/secure-software-engineering-skills.zip`](dist/secure-software-engineering-skills.zip)** (personal use only; see LICENSE).

The archive is laid out for a direct copy into your agent skills folder:

1. Unzip the file.
2. Copy **every top-level folder** from the zip into your personal skills directory:
   - **macOS / Linux:** `~/.cursor/skills/`
   - **Windows:** `%USERPROFILE%\.cursor\skills\`
3. You should end up with folders such as `secure-software-engineering`, `frontend-client`, `backend-server`, … each containing `SKILL.md` and `reference.md`.  
   Do **not** nest an extra `skills/` directory inside `.cursor/skills/`.
4. Copy `LICENSE` from the zip somewhere you keep for your records (optional).
5. Restart Cursor (or reload the window) so skills are picked up.
6. In chat, invoke the parent skill or a domain by name, for example `secure-software-engineering` and `security-backend-server`.

### Install from a git clone

If you cloned this repository instead of using the zip:

1. Copy `secure-software-engineering/` into `~/.cursor/skills/`.
2. Copy **each** subdirectory inside `skills/` (for example `skills/backend-server/`) into `~/.cursor/skills/` as `backend-server/`, not as `skills/backend-server/`.

## How to use

1. **Scope** the change (UI, API, database, infra, third-party).
2. **Pick** domain skills from the [index](#domain-index) below.
3. **Read** `SKILL.md` for workflow, then `reference.md` for rules that match your task.
4. **Cross-cut:** For auth, secrets, or logging, also use `identity-access`, `secrets-config`, and `logging-monitoring-ir`.

### Example prompts

- “Use `security-frontend-client` while building this React form.”
- “Review this PR with `security-api-integration` and `security-data-databases`.”
- “Threat-model this SaaS feature with `security-multi-tenancy-saas` and `security-business-logic-abuse`.”

## Domain index

| Folder (in zip or `skills/`) | Security focus |
|-------------------------------|----------------|
| `frontend-client` | Browser, SPA, SSR, CSP, XSS, CSRF |
| `backend-server` | Injection, authz, sessions, file I/O, jobs |
| `api-integration` | REST, GraphQL, gRPC, webhooks, OAuth APIs |
| `identity-access` | Authn, MFA, SSO, RBAC, IDOR |
| `data-databases` | SQL/NoSQL, encryption, backups, RLS |
| `cryptography` | TLS, keys, JWT, hashing, KMS |
| `network-transport` | SSRF, DNS, WAF, mTLS |
| `cloud-infrastructure` | IAM, S3, VPC, IaC |
| `containers-k8s` | Images, RBAC, network policy |
| `devsecops-cicd` | SAST, DAST, secrets in CI |
| `supply-chain` | Dependencies, SBOM, CVEs |
| `secrets-config` | Env vars, rotation, feature flags |
| `logging-monitoring-ir` | SIEM, audit, incident response |
| `privacy-compliance` | GDPR, PCI, HIPAA-aligned controls |
| `mobile-security` | iOS, Android, WebView |
| `ai-ml-security` | Prompt injection, RAG, agents |
| `business-logic-abuse` | Fraud, workflows, bots |
| `sdlc-threat-modeling` | STRIDE, secure design |
| `email-notifications` | SPF/DKIM, templates, push |
| `realtime-messaging` | WebSocket, Kafka, WebRTC |
| `payments-fintech` | PCI, payment webhooks |
| `observability-security` | Traces, APM, session replay |
| `multi-tenancy-saas` | Tenant isolation, custom domains |
| `serverless-edge` | Lambda, workers, event abuse |
| `file-object-storage` | Uploads, presigned URLs |
| `zero-trust-access` | ZTNA, device posture |
| `blockchain-web3` | Smart contracts, wallets |
| `embedded-iot-ot` | Firmware, MQTT, OT |
| `desktop-native` | Electron, Tauri, updates |
| `web-framework-security` | React, Vue, Angular, Next |
| `server-framework-security` | Node, Django, Spring, .NET, Go |
| `data-engineering-analytics` | Warehouses, ETL, BI |
| `cms-content-platforms` | Headless CMS, WYSIWYG |
| `human-factors-abuse` | Phishing, support takeover |

Parent orchestrator: **`secure-software-engineering`** (`name: secure-software-engineering` in `SKILL.md`).

## Who this is for

Developers using **AI pair programmers**, security champions, students, and anyone searching for **Cursor security skills**, **AI agent secure coding rules**, or **application security checklists**.

## FAQ

**Is this professional security or legal advice?**  
No. See [LICENSE](LICENSE).

**How are `SKILL.md` and `reference.md` different?**  
`SKILL.md` is short: discovery metadata, when to use, and workflow. `reference.md` holds the full rule set so agents load detail only when needed.

**Can I use this at work?**  
See [LICENSE](LICENSE) for permitted use.
