---
name: stack-openai-api
description: >-
  Routes all 34 security domains to OpenAI API / Agents SDK-specific implementation skills. Use when developing or reviewing OpenAI API / Agents SDK applications.
disable-model-invocation: true
---

# OpenAI API / Agents SDK security (all domains)

Orchestrator for **OpenAI API / Agents SDK** (AI). Each row mirrors one domain skill with stack-specific `reference.md`.

| Domain skill folder | Security domain |
|---------------------|-----------------|
| `stack-openai-api-frontend-client/` | Frontend and client-side security |
| `stack-openai-api-backend-server/` | Backend and server-side security |
| `stack-openai-api-api-integration/` | API and integration security |
| `stack-openai-api-identity-access/` | Identity, authentication, and access control |
| `stack-openai-api-data-databases/` | Data protection and databases |
| `stack-openai-api-cryptography/` | Cryptography and key management |
| `stack-openai-api-network-transport/` | Network and transport security |
| `stack-openai-api-cloud-infrastructure/` | Cloud and infrastructure security |
| `stack-openai-api-containers-k8s/` | Containers and Kubernetes |
| `stack-openai-api-devsecops-cicd/` | DevSecOps and CI/CD |
| `stack-openai-api-supply-chain/` | Software supply chain |
| `stack-openai-api-secrets-config/` | Secrets and configuration |
| `stack-openai-api-logging-monitoring-ir/` | Logging, monitoring, and incident response |
| `stack-openai-api-privacy-compliance/` | Privacy and compliance |
| `stack-openai-api-mobile-security/` | Mobile application security |
| `stack-openai-api-ai-ml-security/` | AI and ML system security |
| `stack-openai-api-business-logic-abuse/` | Business logic and abuse prevention |
| `stack-openai-api-sdlc-threat-modeling/` | SDLC, threat modeling, and secure design |
| `stack-openai-api-email-notifications/` | Email and notifications security |
| `stack-openai-api-realtime-messaging/` | Real-time, WebSocket, and messaging |
| `stack-openai-api-payments-fintech/` | Payments and financial flows |
| `stack-openai-api-observability-security/` | Observability and debugging security |
| `stack-openai-api-multi-tenancy-saas/` | Multi-tenancy and SaaS isolation |
| `stack-openai-api-serverless-edge/` | Serverless, edge, and FaaS security |
| `stack-openai-api-file-object-storage/` | File, blob, and object storage security |
| `stack-openai-api-zero-trust-access/` | Zero trust and secure access |
| `stack-openai-api-blockchain-web3/` | Blockchain, Web3, and smart contracts |
| `stack-openai-api-embedded-iot-ot/` | Embedded, IoT, and operational technology |
| `stack-openai-api-desktop-native/` | Desktop and native application security |
| `stack-openai-api-web-framework-security/` | Web UI framework security |
| `stack-openai-api-server-framework-security/` | Server framework and runtime security |
| `stack-openai-api-data-engineering-analytics/` | Data engineering, analytics, and BI security |
| `stack-openai-api-cms-content-platforms/` | CMS, content platforms, and publishing |
| `stack-openai-api-human-factors-abuse/` | Human factors, social engineering, and support abuse |

## Usage

Load `stack-openai-api-<domain>` for the domain you are working on, or invoke this orchestrator to pick a folder from the table.
