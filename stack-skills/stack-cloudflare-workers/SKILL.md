---
name: stack-cloudflare-workers
description: >-
  Routes 14 security domains to Cloudflare Workers-specific implementation skills. Use when developing or reviewing Cloudflare Workers applications.
disable-model-invocation: true
---

# Cloudflare Workers security (stack domains)

Orchestrator for **Cloudflare Workers** (Platform). Each row is a domain where this stack has concrete `reference.md` guidance.

| Domain skill folder | Security domain |
|---------------------|-----------------|
| `stack-cloudflare-workers-backend-server/` | Backend and server-side security |
| `stack-cloudflare-workers-api-integration/` | API and integration security |
| `stack-cloudflare-workers-identity-access/` | Identity, authentication, and access control |
| `stack-cloudflare-workers-cryptography/` | Cryptography and key management |
| `stack-cloudflare-workers-network-transport/` | Network and transport security |
| `stack-cloudflare-workers-ai-ml-security/` | AI and ML system security |
| `stack-cloudflare-workers-business-logic-abuse/` | Business logic and abuse prevention |
| `stack-cloudflare-workers-realtime-messaging/` | Real-time, WebSocket, and messaging |
| `stack-cloudflare-workers-payments-fintech/` | Payments and financial flows |
| `stack-cloudflare-workers-multi-tenancy-saas/` | Multi-tenancy and SaaS isolation |
| `stack-cloudflare-workers-serverless-edge/` | Serverless, edge, and FaaS security |
| `stack-cloudflare-workers-server-framework-security/` | Server framework and runtime security |
| `stack-cloudflare-workers-data-engineering-analytics/` | Data engineering, analytics, and BI security |
| `stack-cloudflare-workers-human-factors-abuse/` | Human factors, social engineering, and support abuse |

## Usage

Load `stack-cloudflare-workers-<domain>` for the domain you are working on, or invoke this orchestrator to pick a folder from the table.
