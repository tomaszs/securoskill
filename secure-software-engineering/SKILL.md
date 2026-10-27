---
name: secure-software-engineering
description: >-
  Orchestrates secure software engineering across frontend, backend, APIs, identity, data, cloud, serverless, multi-tenancy, frameworks, databases, Web3, IoT, desktop, AI, payments, and SDLC. Use when building or reviewing software for security, threat modeling, or preparing security checklists for AI agents and human developers.
---

# Secure software engineering

## Purpose

Structured security guidance for AI coding agents and engineers: **34 domains**, **408 sub-areas**, and layered rules from policy through operations.

## How to use

1. Identify which domain(s) your change touches (see table below).
2. Open the matching skill under `skills/<domain>/SKILL.md` and its `rules.md`.
3. Apply rules top-down: governance → design → code → tests → operations.
4. For cross-cutting issues (auth, secrets, logging), also load **identity-access**, **secrets-config**, and **logging-monitoring-ir**.

## Domain skills

| Skill folder | Domain |
|--------------|--------|
| `skills/frontend-client/` | Frontend and client-side security |
| `skills/backend-server/` | Backend and server-side security |
| `skills/api-integration/` | API and integration security |
| `skills/identity-access/` | Identity, authentication, and access control |
| `skills/data-databases/` | Data protection and databases |
| `skills/cryptography/` | Cryptography and key management |
| `skills/network-transport/` | Network and transport security |
| `skills/cloud-infrastructure/` | Cloud and infrastructure security |
| `skills/containers-k8s/` | Containers and Kubernetes |
| `skills/devsecops-cicd/` | DevSecOps and CI/CD |
| `skills/supply-chain/` | Software supply chain |
| `skills/secrets-config/` | Secrets and configuration |
| `skills/logging-monitoring-ir/` | Logging, monitoring, and incident response |
| `skills/privacy-compliance/` | Privacy and compliance |
| `skills/mobile-security/` | Mobile application security |
| `skills/ai-ml-security/` | AI and ML system security |
| `skills/business-logic-abuse/` | Business logic and abuse prevention |
| `skills/sdlc-threat-modeling/` | SDLC, threat modeling, and secure design |
| `skills/email-notifications/` | Email and notifications security |
| `skills/realtime-messaging/` | Real-time, WebSocket, and messaging |
| `skills/payments-fintech/` | Payments and financial flows |
| `skills/observability-security/` | Observability and debugging security |
| `skills/multi-tenancy-saas/` | Multi-tenancy and SaaS isolation |
| `skills/serverless-edge/` | Serverless, edge, and FaaS security |
| `skills/file-object-storage/` | File, blob, and object storage security |
| `skills/zero-trust-access/` | Zero trust and secure access |
| `skills/blockchain-web3/` | Blockchain, Web3, and smart contracts |
| `skills/embedded-iot-ot/` | Embedded, IoT, and operational technology |
| `skills/desktop-native/` | Desktop and native application security |
| `skills/web-framework-security/` | Web UI framework security |
| `skills/server-framework-security/` | Server framework and runtime security |
| `skills/data-engineering-analytics/` | Data engineering, analytics, and BI security |
| `skills/cms-content-platforms/` | CMS, content platforms, and publishing |
| `skills/human-factors-abuse/` | Human factors, social engineering, and support abuse |

## Rule levels (every sub-area)

| Level | Question |
|-------|----------|
| Policy | Is this in scope, owned, and aligned with risk appetite? |
| Design | Are boundaries, defaults, and platform choices safe? |
| Implementation | Are inputs, outputs, crypto, and dependencies handled correctly? |
| Verification | Do tests and scanners prove it? |
| Operations | Can you detect, respond, and audit in production? |
