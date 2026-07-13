# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a short summary of the processes used across projects. Use these docs as the canonical source for how we initiate, plan, execute, release, and learn from projects.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decisions. The process is organized around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During Initiation, teams validate business need and align stakeholders using a lightweight Project One-pager that defines the problem statement, success metrics, and key milestones. Once approved, the Planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This structured approach ensures teams move into Execution with clear scope and realistic timelines.

Execution and tracking rely on a disciplined team rhythm and project board workflow. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs showcase progress and flagged risks. Work flows through GitHub Projects columns—Backlog, Ready, In Progress, In Review, QA, and Done—with small pull requests (≤400 lines) that include issue links and acceptance criteria. Quality is built in throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Manual QA validates feature acceptance when needed. Risks are captured in a Risk Register and escalated through three levels—team triage, PM escalation to Product Leads, and sponsor-level escalation for business-impacting issues.

OctoAcme's core roles include **Project Managers** (who coordinate delivery, schedules, and communications), **Product Managers** (who define outcomes and prioritize the backlog), **Developers** (who implement features and collaborate on design), and **QA/Testing** professionals (who validate quality against acceptance criteria). Clear ownership of each project reduces ambiguity, while regular communication—weekly PM-to-PdM syncs, twice-weekly team standups, and monthly stakeholder updates—keeps all parties aligned. Release and Deployment follows standardized checklists covering pre-release requirements, smoke testing, deployment verification, and rollback procedures. Finally, post-release retrospectives capture learnings and convert them into actionable improvements tracked back into the project backlog, embedding continuous learning into the culture.

## Quick Reference: OctoAcme Process Phases

- **Initiation**: Capture the problem, stakeholders, success metrics, and a one-page project charter to decide go/no-go.
- **Planning**: Turn approved initiatives into a prioritized backlog, define acceptance criteria, estimates, and a release/milestone plan.
- **Execution & Tracking**: Use project boards, small PRs, CI checks, daily standups, and weekly delivery syncs to track progress.
- **Release & Deployment**: Follow pre-release checks, run smoke tests, and document release notes and rollback plans.
- **Retrospective & Continuous Improvement**: Run retros after sprints/releases, create action items, and track improvements in the backlog.
- **Risk & Communication**: Maintain a risk register, communicate weekly status, and follow escalation paths for blockers and incidents.

## Links to Process Docs

- [Project Management Overview](octoacme-project-management-overview.md) — concise introduction and how to use these docs
- [Project Initiation Guide](octoacme-project-initiation.md) — one-pager template and initiation checklist
- [Project Planning](octoacme-project-planning.md) — backlog templates, estimation, planning checklist
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, PR workflow, QA, and tracking
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release types, checklist, and rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retros and tracking outcomes
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register and stakeholder communication
- [Roles & Personas](octoacme-roles-and-personas.md) — role summaries and responsibilities

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick introduction to roles and artifacts.
- **Project kick-off**: Use the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) docs to set up your project.
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance.
- **Before release**: Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist.
- **After sprint/release**: Use the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings.
- **Copilot Spaces context**: Link to this README from your project's Copilot Space to ground guidance in OctoAcme processes.
