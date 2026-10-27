# Secure Software Engineering Skills for AI Agents

**Free structured security skills for Cursor, Claude Code, Copilot, and other AI coding agents.**  
Cover **secure coding**, **application security**, **cloud security**, **DevSecOps**, and **AI security** with checklists an agent can follow while it writes and reviews code.

> Personal, non-commercial use only. See [LICENSE](LICENSE) before copying or installing.

## What you get

| | |
|--|--|
| **34 security domains** | Frontend, backend, APIs, identity, data, crypto, network, cloud, Kubernetes, CI/CD, supply chain, privacy, mobile, AI/ML, payments, Web3, IoT, desktop, frameworks, and more |
| **408 sub-areas** | Each with concrete topics (SQL injection, XSS, SSRF, IDOR, prompt injection, tenant isolation, presigned URLs, smart contract reentrancy, Electron hardening, etc.) |
| **1,200+ fine-grained topics** | Nested sub-topics with actionable rules |
| **5 rule layers** | Policy, design, implementation, verification, and operations for every sub-area |

Skills use the open **[Cursor Agent Skills](https://cursor.com/docs/context/skills)** format (`SKILL.md` + reference files) so tools can discover when to load them.

## Benefits

- **Fewer missed vulnerabilities:** Agents get domain-specific rules instead of generic “write secure code” prompts.
- **Faster reviews:** `rules.md` files work as PR checklists for humans and as context for agents.
- **Consistent depth:** Same five-level structure everywhere, from governance to production monitoring.
- **Stack-aware:** Dedicated skills for **React, Vue, Angular, Next.js**, **Django, Spring, .NET, Node**, and other common frameworks.
- **Modern risks included:** LLM prompt injection, RAG ACLs, multi-tenant SaaS isolation, serverless denial-of-wallet, and observability data leaks.
- **Works offline:** Clone once; no API or subscription required to use the markdown skills.

## How to install and use

### Cursor

1. Clone this repository (or download a zip for personal use).
2. Copy `secure-software-engineering/` and the `skills/` folders into your personal skills directory, for example `~/.cursor/skills/` on macOS/Linux or `%USERPROFILE%\.cursor\skills\` on Windows.
3. In chat, reference the parent skill or a domain skill, for example: “Use **secure-software-engineering** and **security-backend-server** for this API change.”
4. For each task, open the matching `skills/<domain>/rules.md` and apply rules from policy through operations.

### Claude Code, Codex, or other agents

1. Add the repo (or selected `skills/<domain>/` folders) to the agent’s skill, rules, or project knowledge path.
2. Start with [`secure-software-engineering/SKILL.md`](secure-software-engineering/SKILL.md) to pick domains.
3. Load only the domains relevant to the current file or feature to save context.

### Suggested workflow

1. **Scope:** List components touched (UI, API, database, infra, third-party).
2. **Map:** Match components to domain folders (table below).
3. **Apply:** For each matching sub-area in `rules.md`, check implementation and tests.
4. **Cross-cut:** Always consider `identity-access`, `secrets-config`, and `logging-monitoring-ir` when auth, credentials, or logs are involved.

### Example prompts

- “Follow `security-frontend-client` while building this React form.”
- “Review this PR using `security-api-integration` and `security-data-databases`.”
- “Threat-model this SaaS feature with `security-multi-tenancy-saas` and `security-business-logic-abuse`.”

## Domain index

| Skill folder | Security focus |
|--------------|----------------|
| `skills/frontend-client` | Browser, SPA, SSR, CSP, XSS, CSRF |
| `skills/backend-server` | Injection, authz, sessions, file I/O, jobs |
| `skills/api-integration` | REST, GraphQL, gRPC, webhooks, OAuth APIs |
| `skills/identity-access` | Authn, MFA, SSO, RBAC, IDOR, zero trust identity |
| `skills/data-databases` | SQL/NoSQL, encryption, backups, RLS |
| `skills/cryptography` | TLS, keys, JWT, hashing, KMS |
| `skills/network-transport` | SSRF, DNS, WAF, mTLS, email transport |
| `skills/cloud-infrastructure` | IAM, S3, VPC, IaC, SaaS admin |
| `skills/containers-k8s` | Images, RBAC, network policy, runtime |
| `skills/devsecops-cicd` | SAST, DAST, secrets in CI, signing |
| `skills/supply-chain` | Dependencies, SBOM, CVE response |
| `skills/secrets-config` | Env vars, rotation, feature flags |
| `skills/logging-monitoring-ir` | SIEM, audit, incident response |
| `skills/privacy-compliance` | GDPR, PCI, HIPAA-aligned controls |
| `skills/mobile-security` | iOS, Android, WebView, attestation |
| `skills/ai-ml-security` | Prompt injection, RAG, agents, tools |
| `skills/business-logic-abuse` | Fraud, workflows, bots, IDOR |
| `skills/sdlc-threat-modeling` | STRIDE, secure design, purple team |
| `skills/email-notifications` | SPF/DKIM, templates, SMS/push |
| `skills/realtime-messaging` | WebSocket, Kafka, WebRTC |
| `skills/payments-fintech` | PCI, Stripe webhooks, ledger |
| `skills/observability-security` | Traces, APM, session replay |
| `skills/multi-tenancy-saas` | Tenant isolation, custom domains, plans |
| `skills/serverless-edge` | Lambda, workers, event triggers, cost abuse |
| `skills/file-object-storage` | Uploads, presigned URLs, malware scan |
| `skills/zero-trust-access` | ZTNA, device posture, workload identity |
| `skills/blockchain-web3` | Smart contracts, wallets, DeFi |
| `skills/embedded-iot-ot` | Firmware, MQTT, OT/SCADA |
| `skills/desktop-native` | Electron, Tauri, auto-update, OS APIs |
| `skills/web-framework-security` | React, Vue, Angular, Next, Nuxt, Svelte |
| `skills/server-framework-security` | Node, Django, Spring, .NET, Go, PHP |
| `skills/data-engineering-analytics` | Warehouses, ETL, BI, notebooks |
| `skills/cms-content-platforms` | Headless CMS, WYSIWYG, publishing |
| `skills/human-factors-abuse` | Phishing, support takeover, insiders |

Parent orchestrator: [`secure-software-engineering/SKILL.md`](secure-software-engineering/SKILL.md)

## Who this is for

- Developers using **AI pair programmers** who need reliable security guardrails  
- Security champions building **lightweight AppSec** playbooks  
- Students and hobbyists learning **secure software engineering** topics in context  
- Anyone searching for **Cursor security skills**, **AI agent secure coding rules**, or **application security checklists**

## FAQ

**Is this a replacement for a professional penetration test?**  
No. These skills improve everyday coding and review; they do not replace legal advice, compliance audits, or hired security testing.

**Can I use this at work?**  
The [LICENSE](LICENSE) allows **personal, non-commercial** use only. Commercial or team use requires separate permission from the copyright holder.

**Can I redistribute or sell these skills?**  
No. Reuploading, mirroring, selling, or distributing derivatives is prohibited. Breach penalty: **USD $5,000** per violation under the license.

**How are skills structured?**  
Each domain has `SKILL.md` (when to use, workflow) and `rules.md` (full rules for every sub-area).

## License

**Restricted use only.** [LICENSE](LICENSE)

| Allowed | Not allowed |
|---------|-------------|
| Personal, non-commercial use by a **human** | Commercial use (including employer/client work) |
| Using skills with **your own** AI agents privately | Reuploading, mirroring, or public redistribution |
| Keeping a private copy for that personal use | Selling, licensing, or offering **derivatives** |

**Breach penalty:** USD **$5,000** per violation (plus other remedies). Request written permission for any use beyond personal AI-agent use.
