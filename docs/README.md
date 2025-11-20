# OctoAcme Project Management Documentation

This README gathers key resources and standardized processes for project and program management at OctoAcme. It helps new and existing team members quickly understand our approach, find core guidance, and access supporting process documents.

## Brief overview of OctoAcme project management processes

- Project life cycle: Initiation → Planning → Execution → Release → Retrospective.
- Roles: Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, Stakeholders.
- Delivery approach: iterative delivery, small increments, continuous feedback and measurement.
- Core artifacts: Project One-pager / Charter, Roadmap, Backlog, Acceptance Criteria / Definition of Done, Risk Register, Retrospectives and action items.
- Team rhythm: daily standups, weekly delivery syncs, demos at end of each sprint/milestone, and periodic stakeholder updates.
- Communication & escalation: weekly status reports, clear stakeholder channels, and defined escalation steps for blockers and incidents.
- Quality & releases: CI, automated tests, security scans, smoke tests for release verification, and a rollback/incident playbook.

## Key docs (links)
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## Quick start: using these docs
- New project: start with the Project Initiation Guide and create a Project One-pager in this repo under docs/ or `.copilot/`.
- Planning: follow the Project Planning doc to create a prioritized backlog, release plan, and risk register.
- Execution: use the Execution & Tracking doc for day-to-day workflow, PR guidance, and CI requirements.
- Release: follow the Release & Deployment Guide for pre-release checks, deployment steps, and rollback playbooks.
- Continuous improvement: after releases or milestones run retrospectives and convert action items to issues in the project board.

## Suggested structure for a project repo
- docs/: process docs and project artifacts (one-pager, release notes)
- .copilot/: optional project-specific context for Copilot Spaces
- project board: backlog, ready, in-progress, in-review, QA, done
- risk-register.md or a Risks section in the project README

## Acceptance criteria for updates to process docs
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

## Maintainers / Ownership
- Primary maintainers: Project Managers and Product Leads
- For doc changes: open an issue using `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` and reference the relevant doc(s).

If you need the file named differently (for example docs/octoacme-project-management-readme.md) or want additional sections (templates, checklists, copy for a new issue), tell me which and I’ll prepare accordingly.
