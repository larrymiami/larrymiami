# Larry Miami

**Product Engineer · Secure Cloud Systems**

Nairobi, Kenya · [Portfolio](https://larrymiami.com/) · [LinkedIn](https://www.linkedin.com/in/larrymiami/)

I build software where product workflows, backend systems, cloud infrastructure, and security have to work together. I care about identity, authorization, data boundaries, delivery, observability, failure modes, and evidence that controls actually work.

## What I work across

| Product Engineering | Backend & Data | Cloud Engineering | Security & DevSecOps |
| --- | --- | --- | --- |
| React, Next.js, TypeScript, workflow modelling, design systems, offline-aware UX | Node.js, Fastify, PostgreSQL, MongoDB, Redis, GraphQL, REST | Google Cloud, Cloud Run, Cloud SQL, VPC, IAM, Terraform, logging, monitoring | Threat modelling, least privilege, keyless CI/CD, secrets, IaC security, application security |

## Projects

### [AfyaBridge Cloud Security](https://github.com/larrymiami/Afyabridge-Cloud-Security)

A multi-country cloud-security reference implementation for a fictional community-health organization on Google Cloud.

- Country-isolated landing-zone, IAM, network, data-protection, workload, observability, and public-edge architecture.
- Terraform infrastructure implemented and statically validated across the repository roots.
- Live-validated Terraform bootstrap control plane covering CMEK-backed remote state, service-account impersonation without downloaded keys, least-privilege steady-state IAM, controlled mutation, temporary-privilege cleanup, and a final zero-change plan.
- Application security baseline with deny-by-default authorization, audit events, persistence, concurrency controls, and offline-sync safeguards.
- Completed shift-left security pipeline covering secrets, dependencies, CodeQL, Terraform/package/container scanning, OpenAPI drift, OPA/Rego, exceptions, generated evidence, and a fail-closed security verdict.
- Completed software supply-chain controls covering immutable workflow/build inputs, SBOMs, separated build/sign identities, keyless Cosign signing, GitHub attestations, provenance verification, revocation policy, and negative compromise tests.
- Cloud posture and governance work covering machine-readable desired state, drift decisions, finding lifecycle, remediation SLAs, governed exceptions, and run-bound reporting that keeps repository evidence separate from live-cloud state.
- Current roadmap: **v0.8 security pipeline and v0.9 supply-chain security completed; v0.7 remains in review with the bootstrap control plane live-validated and later GCP stacks pending; v0.10 posture/governance remains in review.**

**Focus:** Google Cloud · Terraform · GitHub Actions · Cloud Security · DevSecOps · Software Supply Chain · Posture Governance

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

A two-sided East African event-ticketing platform for attendees and organizers, with mobile-money payments, inventory concurrency, ticket validation, and organizer operations.

- Next.js 16 / React 19 frontend with a Fastify 5 modular-monolith backend.
- PostgreSQL + Redis ticket inventory, reservation-at-checkout, order lifecycle, and concurrency controls.
- KCB Buni / M-PESA payment callbacks, safe inventory release, ticket issuance, dynamic QR/OTP validation, and transfers.
- Docker + GitHub Actions delivery pipeline with migrations, health checks, and deployment safeguards.

**Focus:** Platform engineering · Fastify · PostgreSQL · Redis · payments · transactional workflows  
[Open product](https://tickettroveafrica.com/) · [Portfolio](https://miami-portfolio.vercel.app/)

## How I think about engineering

**Product first.** Understand the workflow, actors, constraints, and failure modes before choosing the architecture.

**Security by design.** Identity, authorization, data isolation, auditability, recovery, and delivery controls belong in the system model from the beginning.

**Evidence over claims.** I separate what is designed, what is implemented, and what has actually been validated.

## Current focus

My current work sits at the intersection of **product engineering, Google Cloud, cloud security, and DevSecOps**, with implementation-heavy projects that treat security as part of the system rather than a separate layer added after the product is built.

---

If you want the shorter version, start with the [portfolio](https://larrymiami.com/) or the [AfyaBridge Cloud Security repository](https://github.com/larrymiami/Afyabridge-Cloud-Security).
