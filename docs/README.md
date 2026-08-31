# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management knowledge base. This directory contains standardized processes, templates, and guidance for running projects at OctoAcme.

## Overview

OctoAcme operates on principles of customer-first delivery, iterative development, clear ownership, and data-informed decisions. Our project management approach is designed to enable cross-functional teams to deliver product value consistently and predictably.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Processes

OctoAcme follows a structured five-phase project lifecycle designed to deliver value iteratively while maintaining clear ownership and accountability.

### The Five Phases

1. **Initiation** — Validate business need, align stakeholders, and decide go/no-go
2. **Planning** — Define scope, resources, milestones, and dependencies
3. **Execution & Tracking** — Manage day-to-day delivery, quality, and progress
4. **Release & Deployment** — Deploy features to production with reduced risk
5. **Retrospective & Continuous Improvement** — Capture learnings and improve processes

### Process Summary

OctoAcme's foundation is a lightweight but comprehensive set of artifacts—including a Project One-pager, risk register, acceptance criteria, and release notes—that serve as the single source of truth for stakeholders and delivery teams.

**Roles & Communication**: The organization operates with clearly defined personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and measure success; **Developers** implement features with quality and testability; and **QA/Testing** validates acceptance criteria. Communication happens through a predictable cadence: daily standups (15 minutes, focused on progress and blockers), weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, and monthly stakeholder updates. Escalations follow a clear path: team-level triage → PM → Product Lead → Sponsor.

**Execution & Quality**: During execution, teams use a project board (e.g., GitHub Projects) with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Quality is enforced through comprehensive CI/CD: unit tests, integration tests, security scanning, and end-to-end smoke tests for critical flows. Teams track velocity and burndown metrics and use regular demos to validate progress.

**Risk Management & Continuous Improvement**: Risks are proactively managed via a Risk Register reviewed weekly during syncs. After each sprint, release, or milestone, teams conduct blameless retrospectives to capture learnings and identify prioritized action items. This commitment to continuous improvement, combined with standardized release procedures, ensures consistent delivery while building a culture of psychological safety and iterative learning.

## Documentation Index

### Core Guides
- [**Project Management Overview**](octoacme-project-management-overview.md) — Start here to understand OctoAcme's roles, principles, lifecycle, and key artifacts
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Definitions of Project Manager, Product Manager, Developer, and QA roles

### By Lifecycle Phase
- [**Project Initiation**](octoacme-project-initiation.md) — Problem validation, stakeholder alignment, and decision gates
- [**Project Planning**](octoacme-project-planning.md) — Backlog creation, estimation, risk identification, and release planning
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Daily standups, quality standards, blocker escalation, and metrics
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Pre-release checklist, deployment steps, rollback procedures
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Running retros, capturing action items, tracking improvements

### Cross-Cutting Concerns
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Risk lifecycle, escalation paths, and stakeholder communication templates

## Quick Reference: Key Artifacts

- **Project One-pager** — Used in Initiation to confirm business need and success metrics (template in Project Initiation guide)
- **Risk Register** — Maintained throughout project to track risks, mitigation, and status (format in Risk Management guide)
- **Definition of Done** — Documented during Planning to define quality standards (guidance in Project Planning)
- **Release Notes Template** — Used in Release & Deployment phase (template in Release & Deployment guide)
- **Retrospective Action Items** — Tracked in Continuous Improvement phase (template in Retrospective guide)

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach, roles, and key artifacts.

**Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide to validate business need, align stakeholders, and create your Project One-pager.

**Already in delivery?** Check [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance, quality standards, team rhythm, and escalation paths.

**Planning a release?** See the [Release & Deployment](octoacme-release-and-deployment.md) guide for pre-release requirements, deployment checklists, and rollback procedures.

**After project close?** Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and identify improvements for future projects.

**Unclear about roles?** Review [Roles and Personas](octoacme-roles-and-personas.md) to understand responsibilities for Project Managers, Product Managers, Developers, and QA.

## How to Use These Docs

- **Keep your Project Charter updated** in your project repo
- **Reference relevant docs** at each project phase to ensure consistent execution
- **Add process-specific guidance** to your project workspace as needed
- **Contribute improvements** — if you identify gaps or enhancements, submit them via the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template

---

**Questions?** Reach out to your Project Manager or Product Lead for clarification on any process.
