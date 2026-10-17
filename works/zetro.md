# ZETRO

**Controlled execution for agent-driven work.**  
*Developer tooling · Local execution runtime · In development*

[Repository](https://github.com/Z-A-R-R-O/zetro) · [Runtime documentation](https://github.com/Z-A-R-R-O/zetro/tree/main/docs) · [Veyminore workspace](https://github.com/Z-A-R-R-O/Veyminore)

## The problem

An agent can issue an action without proving that the intended outcome occurred. A useful execution system needs policy boundaries, records of what happened, and a way to distinguish observed evidence from assumption.

ZETRO explores a local runtime that routes computer actions through controlled interfaces, records execution, and reports what can actually be verified.

## Current implementation boundary

The repository identifies the Antigravity adapter as the first executable slice and includes an offline synthetic RCT demo. The generic computer runtime and dispatcher remain planned. The project documentation explicitly distinguishes proposed behavior from implemented functionality.

## Engineering shape

- Node.js 20+ and a pnpm workspace.
- Adapter-based execution and runtime documentation.
- Policy, security, evidence, recovery, and quality concepts documented under the docs directory.
- Verification entry points documented in the repository: **pnpm -r test**, **pnpm typecheck**, and **pnpm rct:demo**.

These commands are documented entry points, not a claim that they were run successfully for this case study.

## Design principle

**Control first. Execution second. Verification always.**

The engineering question is how to make an automation system useful without letting a successful tool call masquerade as a successful result.

## Current status

ZETRO is in development. The scope is intentionally narrower than the full product vision; planned orchestration and generic computer capabilities should not be presented as shipped features.

*An action is an event. Evidence is what earns the conclusion.*
