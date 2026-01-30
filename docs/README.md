# OctoAcme Project Management Docs

This is the central index for OctoAcme's project management process documentation. These docs provide comprehensive guidance on how we plan, execute, and deliver projects with clear ownership, structured processes, and continuous improvement.

## Summary of Project Management Processes

OctoAcme follows a structured, iterative project management approach built on customer-first principles and clear ownership. Projects move through five distinct lifecycle phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase has defined deliverables and decision gates to ensure alignment before moving forward. The initiation phase focuses on validating business need through a Project One-pager that captures the problem statement, SMART objectives, success metrics, stakeholders, and initial risks. Once approved by the Product Lead and sponsor, projects transition into planning where the team conducts kickoff meetings, creates prioritized backlogs with acceptance criteria, estimates scope, and maps out release milestones with clear dependencies tracked in a Risk Register.

The organization defines three core personas with complementary responsibilities: **Product Managers** own the "what" by defining vision, prioritizing backlogs, and measuring outcomes; **Project Managers** coordinate the "how" by managing timelines, risks, communications, and facilitating team ceremonies; and **Developers** deliver the "implementation" by building testable, maintainable code that meets acceptance criteria. This clear role separation enables efficient collaboration while maintaining accountability. Communication cadence is intentionally structured with daily 15-minute standups focused on progress and blockers, weekly delivery syncs between PM and Product Lead, twice-weekly team standups, monthly stakeholder updates, and regular demos at sprint or milestone boundaries.

Execution follows a pull-request-driven workflow using GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done). The team emphasizes small PRs of 400 lines or fewer, automated testing and linting in CI before review, and at least one approval before merging. Quality assurance is embedded throughout with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. The team tracks velocity, burndown metrics, and monitors success metrics via dashboards. Blocker escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead for cross-team issues, and sponsor-level escalation for business-impacting problems.

Releases are categorized by type (Patch, Minor, Major) and follow a strict checklist requiring passing CI, security scans, release notes, rollback plans, and smoke test verification in staging before production deployment. Post-release, the team conducts timeboxed retrospectives (45-75 minutes) after each sprint, release, or incident to capture what went well, what needs improvement, and 2-3 prioritized action items with clear owners and due dates. This continuous improvement culture converts learnings into actionable backlog items tracked in weekly syncs, creating a feedback loop that strengthens processes over time while maintaining psychological safety and data-informed decision-making.

## Key Process Highlights

- **Iterative delivery:** Work is broken up into small, testable increments and delivered through a structured lifecycle (initiation, planning, execution, release, and retrospective/continuous improvement).
- **Clear roles and artifacts:** Project Manager and Product Lead coordinate the process, using artifacts such as project charters, backlogs, and risk registers.
- **Checklists and templates:** Each phase has a documented checklist or template to ensure consistency and quality, including one-pagers, project plans, release/deployment playbooks, and retrospectives.
- **Transparency:** All process docs are stored in this repo for easy reference and continuous improvement via stakeholder feedback.

## Documents in this folder

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Feedback

Feel free to suggest improvements or submit updates using the issue template!
