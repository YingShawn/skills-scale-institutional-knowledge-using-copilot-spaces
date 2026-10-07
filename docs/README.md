# OctoAcme Project Management Docs

Welcome! This folder contains the complete guide to how OctoAcme runs projects. Whether you're a new team member, Project Manager, Product Manager, or Developer, start here to understand our approach, find the guidance you need, and stay aligned.

## Quick Overview

OctoAcme follows a structured project lifecycle with clear phases, roles, and communication practices:
1. **Initiation** — Validate business need and align stakeholders
2. **Planning** — Break work into actionable increments
3. **Execution** — Build, test, and iterate
4. **Release** — Deploy and verify in production
5. **Retrospective** — Capture learnings and improve

## OctoAcme Project Management Approach

OctoAcme uses a structured lifecycle that begins with project initiation and ends with retrospective and continuous improvement. New work is validated through a one-pager that defines the problem, goals, stakeholders, success metrics, and initial risks before the team decides to proceed into planning. Once approved, the team moves into backlog creation, milestone planning, dependency mapping, and definition of done so work is broken into shippable increments with clear ownership and measurable outcomes.

The process emphasizes clear roles and collaboration across functions. The PM manages scheduling, risks, and communications, while the Product Lead or Product Manager defines outcomes, prioritization, and success metrics. Developers build and test the solution, QA validates feature acceptance and quality, and stakeholders provide input and approvals. These role definitions help align responsibilities across the full delivery lifecycle and give team members a common expectation for how decisions, ownership, and accountability are handled.

Communication is intentionally regular and layered. The team follows a cadence of standups, weekly delivery syncs, sprint or milestone demos, and stakeholder updates, while ad hoc escalation handles blockers or high-impact issues. The docs also recommend maintaining a single source of truth such as the project README or release doc, using risk registers, and documenting status in a clear format focused on progress, next steps, risks, and decisions needed. This keeps cross-functional work transparent, reduces confusion, and ensures dependencies and escalations are handled quickly.

Quality and delivery rigor are built into the workflow through recurring review and validation steps. The documentation calls for CI checks, unit and integration testing, smoke tests for critical paths, security scanning, and manual QA where needed. PRs are expected to be small, include links to issues and acceptance criteria, and require review before merge. Release management adds further safeguards through pre-release checks, deployment verification, rollback planning, and post-release communication, while retrospectives capture lessons learned and convert them into action items that improve future delivery.

## Documentation Guide

| Document | Purpose | For Whom |
|---|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and key artifacts | Everyone - start here |
| [Project Initiation](octoacme-project-initiation.md) | How to validate and kick off a new project | PMs, PdMs, Sponsors |
| [Project Planning](octoacme-project-planning.md) | How to create roadmaps, backlogs, and release plans | PMs, PdMs, Tech Leads |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery, team rhythms, and progress tracking | Developers, PMs, QA |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, track, and communicate risks | PMs, PdMs, Team Leads |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release checklist and deployment procedures | Developers, Release Engineers, PMs |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retros and convert learnings to improvements | PMs, Team Leads, All Roles |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed descriptions of key roles and responsibilities | Everyone |

## How to Use These Docs

- **New to OctoAcme?** Read the [Project Management Overview](octoacme-project-management-overview.md) first.
- **Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide.
- **In delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythms and processes.
- **Preparing to release?** Check [Release & Deployment](octoacme-release-and-deployment.md) for the pre-release checklist.
- **Looking for your role details?** See [Roles & Personas](octoacme-roles-and-personas.md).
- **Managing risks or communicating status?** Use [Risk Management & Communication](octoacme-risks-and-communication.md) as your guide.
- **Running a retrospective?** Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named owners with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning
