# OctoAcme Project Management Docs

This folder contains OctoAcme's project management guidance and process artifacts to help teams consistently plan, deliver, and learn from work. At a high level, OctoAcme uses an outcome-driven, iterative approach with clear roles, lightweight decision gates, and measurable success criteria. Projects move through Initiation → Planning → Execution → Release → Close, with core artifacts such as a Project One‑pager, roadmap/release plan, backlog, Definition of Done, and a risk register.

Planning turns validated initiatives into prioritized, shippable backlog items with acceptance criteria and estimates. Execution follows a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request process (small PRs, link to issues/acceptance criteria, CI checks, and required approvals). Team rhythm includes daily standups, weekly delivery syncs, demos at milestones, and routine PM+PdM alignment to keep scope and priorities clear.

Roles and communication are explicit: Product Managers own outcomes and prioritization; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement and test; QA validates acceptance and quality; and stakeholders are kept informed through a single source of truth (this README and the related docs). Communication templates and escalation paths ensure risks and blockers are surfaced quickly.

Quality assurance and release safety are enforced by layered testing and release checklists: unit and integration tests, end‑to‑end smoke checks for critical flows, CI security scanning, and manual QA when appropriate. Pre-release requirements include passing CI, drafted release notes, a rollback plan, and prepared smoke tests; deployments follow a staged verification approach and an incident/rollback playbook. Retrospectives capture action items that feed back into the backlog for continuous improvement.

Docs index
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

Acceptance checklist (for this README)
- [ ] Content aligns with existing process docs
- [ ] Improves discoverability and onboarding
- [ ] Links to all docs in docs/