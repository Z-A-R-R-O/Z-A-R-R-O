# IFZ14

**A personal performance system built around feedback, not just checklists.**  
*React · TypeScript · Local-first design · Interactive prototype*

[Repository](https://github.com/Z-A-R-R-O/IFZ14) · [Live site](https://ifz14.vercel.app)

## The idea

IFZ14 treats daily execution, tasks, goals, routines, and personal signals as related inputs to a larger picture. Instead of stopping at “what did I complete?”, it explores how to make patterns and trade-offs easier to see.

## What the repository contains

- A React and TypeScript frontend built with Vite.
- Zustand-based stores for daily entries, tasks, goals, analytics, preferences, and related state.
- Scoring and analysis modules for execution, progress, patterns, goals, suggestions, and risk signals.
- Report and analytics views, with tests present for selected calculation and reporting modules.
- A Node/Express API slice with MariaDB support and optional session-token configuration.

The scoring model is a product heuristic. It should not be treated as a clinical assessment or an objective measure of human worth.

## Engineering considerations

The project is local-first in its browser workflow and also contains optional API-backed persistence. Those modes have different trust boundaries and should be configured and tested deliberately. Before presenting the backend as production-ready, verify session configuration, account isolation, authorization, error handling, and deployment settings.

## Why I built it

IFZ14 is an attempt to turn personal-system thinking into an inspectable application: capture inputs, compute signals, display patterns, and keep the underlying rules visible enough to question.

## Current status

The repository is an evolving application. See the source and current setup instructions before relying on a feature; a deployed interface alone does not verify every backend pathway.

*Measure the system. Keep the human bigger than the score.*
