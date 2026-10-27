---
name: stack-cloudflare-workers
description: >-
  Routes all 34 security domains to Cloudflare Workers-specific implementation skills. Use when developing or reviewing Cloudflare Workers applications.
disable-model-invocation: true
---

# Cloudflare Workers security (all domains)

Orchestrator for **Cloudflare Workers** (Platform). Each row mirrors one domain skill with stack-specific `reference.md`.

| Domain skill folder | Security domain |
|---------------------|-----------------|
| `stack-cloudflare-workers-frontend-client/` | Frontend and client-side security |
| `stack-cloudflare-workers-backend-server/` | Backend and server-side security |
| `stack-cloudflare-workers-api-integration/` | API and integration security |
| `stack-cloudflare-workers-identity-access/` | Identity, authentication, and access control |
| `stack-cloudflare-workers-data-databases/` | Data protection and databases |
| `stack-cloudflare-workers-cryptography/` | Cryptography and key management |
| `stack-cloudflare-workers-network-transport/` | Network and transport security |
| `stack-cloudflare-workers-cloud-infrastructure/` | Cloud and infrastructure security |
| `stack-cloudflare-workers-containers-k8s/` | Containers and Kubernetes |
| `stack-cloudflare-workers-devsecops-cicd/` | DevSecOps and CI/CD |
| `stack-cloudflare-workers-supply-chain/` | Software supply chain |
| `stack-cloudflare-workers-secrets-config/` | Secrets and configuration |
| `stack-cloudflare-workers-logging-monitoring-ir/` | Logging, monitoring, and incident response |
| `stack-cloudflare-workers-privacy-compliance/` | Privacy and compliance |
| `stack-cloudflare-workers-mobile-security/` | Mobile application security |
| `stack-cloudflare-workers-ai-ml-security/` | AI and ML system security |
| `stack-cloudflare-workers-business-logic-abuse/` | Business logic and abuse prevention |
| `stack-cloudflare-workers-sdlc-threat-modeling/` | SDLC, threat modeling, and secure design |
| `stack-cloudflare-workers-email-notifications/` | Email and notifications security |
| `stack-cloudflare-workers-realtime-messaging/` | Real-time, WebSocket, and messaging |
| `stack-cloudflare-workers-payments-fintech/` | Payments and financial flows |
| `stack-cloudflare-workers-observability-security/` | Observability and debugging security |
| `stack-cloudflare-workers-multi-tenancy-saas/` | Multi-tenancy and SaaS isolation |
| `stack-cloudflare-workers-serverless-edge/` | Serverless, edge, and FaaS security |
| `stack-cloudflare-workers-file-object-storage/` | File, blob, and object storage security |
| `stack-cloudflare-workers-zero-trust-access/` | Zero trust and secure access |
| `stack-cloudflare-workers-blockchain-web3/` | Blockchain, Web3, and smart contracts |
| `stack-cloudflare-workers-embedded-iot-ot/` | Embedded, IoT, and operational technology |
| `stack-cloudflare-workers-desktop-native/` | Desktop and native application security |
| `stack-cloudflare-workers-web-framework-security/` | Web UI framework security |
| `stack-cloudflare-workers-server-framework-security/` | Server framework and runtime security |
| `stack-cloudflare-workers-data-engineering-analytics/` | Data engineering, analytics, and BI security |
| `stack-cloudflare-workers-cms-content-platforms/` | CMS, content platforms, and publishing |
| `stack-cloudflare-workers-human-factors-abuse/` | Human factors, social engineering, and support abuse |

## Usage

Load `stack-cloudflare-workers-<domain>` for the domain you are working on, or invoke this orchestrator to pick a folder from the table.
