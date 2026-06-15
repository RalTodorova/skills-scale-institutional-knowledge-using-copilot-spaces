# OctoAcme Project Management Docs

Welcome to OctoAcme's project management process documentation. This folder contains the authoritative guides for running projects at OctoAcme, designed to centralize scattered knowledge, accelerate onboarding, and ensure consistent execution across teams.

## Quick Overview

OctoAcme follows a structured, five-phase project lifecycle that emphasizes **customer value**, **iterative delivery**, and **clear ownership**:

1. **Initiation** — Validate business needs and align stakeholders through a lightweight Project One-pager capturing the problem statement, success metrics, and high-level timeline.

2. **Planning** — Break work into shippable increments with prioritized backlogs, acceptance criteria, a Definition of Done, and a release plan that identifies dependencies and risks.

3. **Execution & Tracking** — Maintain a daily rhythm of 15-minute standups, weekly delivery syncs, and regular demos, using GitHub Projects to track progress through standard columns (Backlog, Ready, In Progress, In Review, QA, Done). Quality is embedded through unit tests, integration tests, smoke tests, and CI security scanning.

4. **Release & Deployment** — Deploy features through a standardized checklist including pre-release validations, smoke testing on staging, post-deploy verifications, and documented rollback plans to minimize production risk.

5. **Retrospective & Continuous Improvement** — Capture learnings after each sprint, release, or milestone, convert action items into backlog work, and measure the impact of improvements to drive iterative enhancements.

### Core Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments frequently.
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM).
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning through blameless retrospectives.

### Key Roles

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications.
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success.
- **Developers** — Implement features, collaborate on design and testability.
- **QA/Testing** — Validate quality and acceptance criteria.
- **Stakeholders** — Provide inputs, approvals, and strategic direction.

## Documentation Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's principles, core roles, key artifacts, and high-level lifecycle. Start here.

### Phase-Specific Guides
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define initial steps to validate business need, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and prioritized backlog. Covers kickoff, estimation, dependencies, and Definition of Done.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and progress toward milestones. Includes team rhythm, PR workflow, quality standards, metrics, and blocker escalation.

- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, and rollback playbook.

### Cross-Phase Guidance
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies. Includes Risk Register template, stakeholder communication strategies, and escalation paths.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Covers retrospective structure, action item tracking, and building a continuous improvement culture.

### Reference
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role summaries, responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers.

## How to Use These Docs

### For New Team Members
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's approach and key roles.
2. Browse the phase-specific guides relevant to your role and current project stage.
3. Use the [Roles & Personas](octoacme-roles-and-personas.md) guide to understand responsibilities and communication patterns.

### For Project Teams
- Keep the Project Charter (One-pager) updated in your project repository.
- Reference the phase-specific guides during kickoff, planning, execution, and retrospectives.
- Use templates and checklists (e.g., Backlog Item Template, Risk Register, Weekly Status Template) to standardize artifacts.

### For Updating Process Docs
- Found a gap, ambiguity, or improvement opportunity? [Create an issue](https://github.com/RalTodorova/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) using the **"Add Content to Project Management Process Docs"** template.
- Proposed updates are reviewed for alignment with existing guidance and stakeholder input.
- Approved changes are merged into the main branch and indexed in this README.

## Repository Structure

```
.
├── docs/
│   ├── README.md (this file)
│   ├── octoacme-project-management-overview.md
│   ├── octoacme-project-initiation.md
│   ├── octoacme-project-planning.md
│   ├── octoacme-execution-and-tracking.md
│   ├── octoacme-risks-and-communication.md
│   ├── octoacme-release-and-deployment.md
│   ├── octoacme-retrospective-and-continuous-improvement.md
│   └── octoacme-roles-and-personas.md
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── add-update-content-to-process-docs.yml
└── README.md (repository overview)
```

## Communication Cadence

- **Daily** — 15-minute team standups (progress, blockers, dependencies)
- **Weekly** — PM + PdM sync; team delivery sync; risk register review
- **Milestone/Sprint** — Demo/review; retrospective
- **Monthly** — Stakeholder updates
- **Ad-hoc** — Escalations and incident response

## Questions or Feedback?

If you have questions about OctoAcme's project management processes, or suggestions for improving these docs:
- Post in the project repository discussions (if available)
- Create an issue using the [process docs update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- Reach out directly to your Project Manager or Product Manager

---

**Last updated:** June 2026  
**Maintained by:** OctoAcme Project Management Community
