# HospitalX

**Care flows further.**  
*Hospital operations · Team-built prototype · Bit N Build 2026*

[Repository](https://github.com/Z-A-R-R-O/HospitalX) · [Live site](https://veyminore-hx.vercel.app) · [README](https://github.com/Z-A-R-R-O/HospitalX#readme)

## The problem

A patient’s story travels across teams, shifts, queues, and systems. When context gets fragmented, people lose time reconstructing what happened and deciding who should act next.

HospitalX explores a calmer operational layer that keeps patient context, ownership, and the next action connected.

## What the project explores

- A Command Center for operational overview and work that needs attention.
- Connected workflow surfaces for patient registration, appointments, beds, orders, inventory, billing, referrals, and screening.
- Offline-conscious foundations and recovery paths for unreliable connectivity.
- Audit-friendly workflow design and a clear boundary around AI assistance.

These are documented product surfaces and engineering foundations; this case study does not imply that every workflow has been independently validated for hospital use.

## Engineering shape

The repository is a Next.js application using React, JavaScript/TypeScript, PostgreSQL/Neon, and Drizzle ORM. The codebase documents unit, integration, security, workflow, reliability, and Playwright end-to-end test commands. Defining a test command is not the same as proving that the suite passes; current test status should be checked before a release.

## Safety and readiness

HospitalX is a prototype and engineering foundation—not approved clinical software or a clinical decision system. It must not be used for diagnosis, treatment, prescribing, emergency triage, or real patient care until the required controls are implemented, independently validated, and approved.

## Why it matters to my work

HospitalX brings product thinking and engineering constraints into the same conversation: continuity, visible ownership, resilient user experience, and honest treatment of unfinished capabilities.

*The goal is not more screens. It is less lost context.*
