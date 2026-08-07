# Larry Miami

**Product Engineer · Secure Cloud Systems**

Nairobi, Kenya · [Portfolio](https://miami-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/larrymiami/)

I build software for real-world operations, from product workflows and backend systems to cloud infrastructure, DevSecOps, and security. I care about the system around the interface: identity, authorization, data boundaries, delivery, observability, failure modes, and evidence that controls actually work.

## What I work across

| Product Engineering | Backend & Data | Cloud Engineering | Security & DevSecOps |
| --- | --- | --- | --- |
| React, Next.js, TypeScript, workflow modelling, design systems, offline-aware UX | Node.js, Fastify, PostgreSQL, MongoDB, Redis, GraphQL, REST | Google Cloud, Cloud Run, Cloud SQL, VPC, IAM, Terraform, logging, monitoring | Threat modelling, least privilege, keyless CI/CD, secrets, IaC security, application security |

## Selected engineering work

### [AfyaBridge Cloud Security](https://github.com/larrymiami/Afyabridge-Cloud-Security)

A production-style, multi-country cloud-security lab for a fictional community-health organization on Google Cloud.

- Country-isolated landing-zone, IAM, network, data-protection, workload, observability, and public-edge architecture.
- Terraform foundation with static validation and explicit live-validation boundaries.
- Application security baseline with deny-by-default authorization, audit events, persistence, concurrency controls, and offline-sync safeguards.
- Shift-left CI pipeline covering secrets, dependencies, CodeQL, Terraform/package/container scanning, OpenAPI drift, OPA/Rego, exceptions, and generated evidence.
- Current roadmap: **v0.7 infrastructure and v0.8 security pipeline in review**.

**Focus:** Google Cloud · Terraform · GitHub Actions · Cloud Security · DevSecOps

---

### PawSuite

A Kenya-first veterinary practice platform designed around clinic, mobile, mixed-practice, and field workflows.

- Workflow-first operating model across clinical work, inventory, billing, payments, and field operations.
- Implemented identity and tenancy foundation with PostgreSQL row-level security and browser-safe authentication boundaries.
- Offline model separates local drafts from server-authoritative final actions.

**Focus:** Product systems · PostgreSQL · multi-tenancy · offline-aware workflows · security boundaries  
[Open product](https://pawsuite-web.vercel.app/) · [Portfolio](https://miami-portfolio.vercel.app/)

---

### Ticket Trove Africa

A two-sided event-ticketing platform for attendees and organizers, built around East African payment and operational realities.

- Next.js 16 / React 19 frontend with a Fastify 5 modular-monolith backend.
- PostgreSQL + Redis ticket inventory, reservation-at-checkout, order lifecycle, and concurrency controls.
- KCB Buni / M-PESA payment callbacks, safe inventory release, ticket issuance, dynamic QR/OTP validation, and transfers.
- Docker + GitHub Actions delivery pipeline with migrations, health checks, and deployment safeguards.

**Focus:** Platform engineering · Fastify · PostgreSQL · Redis · payments · transactional workflows  
[Open product](https://tickettroveafrica.com/) · [Portfolio](https://miami-portfolio.vercel.app/)

---

### [Shamiri Supervisor Copilot](https://github.com/larrymiami/Shamiri-Supervisor-Copilot)

An AI-assisted review workflow for supervisors auditing Fellow-led mental-health sessions for quality and safety.

- Structured AI analysis with schema validation.
- Human-in-the-loop validate / reject / override workflow.
- Human-reviewed final status remains the system of record.
- Next.js 16, PostgreSQL, Prisma, OpenAI, Vitest, and Playwright.

**Focus:** AI product engineering · human-in-the-loop systems · safety workflows · full-stack TypeScript

## How I think about engineering

**Product first.** Understand the workflow, actors, constraints, and failure modes before choosing the architecture.

**Security by design.** Identity, authorization, data isolation, auditability, recovery, and delivery controls belong in the system model from the beginning.

**Evidence over claims.** I separate what is designed, what is implemented, and what has actually been validated.

## Current focus

I am currently deepening the intersection of **product engineering, Google Cloud, cloud security, and DevSecOps** through implementation-heavy projects rather than treating security as a separate layer added after the product is built.

---

If you want the shorter version, start with the [portfolio](https://miami-portfolio.vercel.app/) or the [AfyaBridge Cloud Security repository](https://github.com/larrymiami/Afyabridge-Cloud-Security).
