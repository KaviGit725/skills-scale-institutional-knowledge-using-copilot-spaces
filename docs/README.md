# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains the processes, roles, and practices that guide how OctoAcme plans, builds, and ships work.

## Overview

OctoAcme employs a structured, customer-first project lifecycle centered on iterative delivery and clear ownership. The organization operates through five core phases: Initiation (defining problems and stakeholders), Planning (scoping work and identifying dependencies), Execution (building and testing with daily coordination), Release (deployment and verification), and Close & Retrospective (capturing learnings). This framework is supported by well-defined key artifacts including project charters, roadmaps, sprint backlogs, acceptance criteria, risk registers, and retrospective documentation. The approach prioritizes psychological safety, data-informed decisions, and measurable outcomes to ensure customer value is consistently delivered in testable increments.

OctoAcme's organizational structure is built on four primary personas, each with distinct responsibilities and communication patterns. Project Managers (PMs) coordinate delivery schedules, manage risks, and ensure stakeholder alignment; Product Managers (PdMs) define outcomes and prioritize the backlog based on customer impact; Developers design, build, and maintain quality code while participating in design reviews and risk identification; and QA/Testing personnel validate against acceptance criteria. Weekly syncs between PM and PdM, twice-weekly team standups, and monthly stakeholder updates create a structured communication rhythm that maintains transparency and enables rapid issue escalation through defined paths: team-level → PM → Product Lead → Sponsor.

Quality assurance and risk management are embedded throughout OctoAcme's execution model. The organization maintains a risk register tracking impact, likelihood, ownership, and mitigation strategies, reviewed weekly during delivery syncs. Technical quality gates include unit tests, integration tests, end-to-end smoke tests, security scanning in CI/CD pipelines, and mandatory code reviews (requiring at least one approval before merge). Pull requests are kept small (≤400 lines) and linked to backlog items with clear acceptance criteria, while automated linting and testing run before human review. This multi-layered approach—combining clear roles, scheduled communication cadences, documented escalation paths, and quality gates—enables OctoAcme to deliver projects on time, minimize unplanned work, and maintain high organizational confidence in commitments.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) — Purpose, scope, principles, core roles, and key artifacts of OctoAcme's project management approach.
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of the personas involved in delivering projects, their responsibilities, and how they collaborate.
- [Project Initiation](octoacme-project-initiation.md) — How new projects are proposed, scoped, and kicked off, including required stakeholders and artifacts.
- [Project Planning](octoacme-project-planning.md) — How work is scoped, sequenced, and prepared for execution, including roadmaps and dependency management.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery practices, including standups, sprint tracking, and coordination.
- [Risks and Communication](octoacme-risks-and-communication.md) — How risks are identified, tracked, and mitigated, and how communication flows across teams and stakeholders.
- [Release and Deployment](octoacme-release-and-deployment.md) — Steps and quality gates for releasing and deploying work safely.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — How teams close out projects, capture learnings, and improve processes over time.

## Quick Start Guide

New to OctoAcme project management? Here's a suggested reading order to get up to speed quickly:

1. Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the overall lifecycle, principles, and key artifacts.
2. Review [Roles and Personas](octoacme-roles-and-personas.md) to learn who does what and how to identify your point of contact for different needs.
3. Read [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) to understand how projects get started and scoped.
4. Follow up with [Execution and Tracking](octoacme-execution-and-tracking.md) to see how day-to-day delivery works.
5. Reference [Risks and Communication](octoacme-risks-and-communication.md) whenever you need to escalate an issue or understand communication cadences.
6. Check [Release and Deployment](octoacme-release-and-deployment.md) before shipping any change to production.
7. Finish with [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to understand how teams reflect and improve after each project.

If you have questions after reading through these docs, reach out to your Project Manager or Product Manager for clarification.
