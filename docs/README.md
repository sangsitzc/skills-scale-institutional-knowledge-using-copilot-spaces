# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management process docs. This is your complete guide to how we run projects, manage teams, and deliver value.

## Overview

OctoAcme follows a structured, iterative approach to project management that emphasizes customer value, clear ownership, data-informed decisions, and psychological safety. Our methodology is designed to help cross-functional teams deliver features, services, and integrations with consistency, transparency, and minimal risk.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and gather feedback
- **Clear ownership**: Each project has named roles with clear responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Quick Start

New to OctoAcme? Start here:

1. Read the **[Project Management Overview](./octoacme-project-management-overview.md)** to understand our core principles, roles, and lifecycle
2. Identify your role: [Developers](./octoacme-roles-and-personas.md#developers), [Product Managers](./octoacme-roles-and-personas.md#product-managers), or [Project Managers](./octoacme-roles-and-personas.md#project-managers)
3. Follow the process documents in order as your project progresses through its lifecycle

## Process Documents

### 1. [Project Management Overview](./octoacme-project-management-overview.md)
**Introduction to OctoAcme's approach, core roles, and key artifacts**
- Core principles and values
- Role definitions (PM, PdM, Developers, QA, Stakeholders)
- Key artifacts and lifecycle overview
- Communication cadence and how to use these docs

### 2. [Project Initiation](./octoacme-project-initiation.md)
**Validating ideas and authorizing work**
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Create the Project One-pager
- Decision gate: go/no-go to planning

### 3. [Project Planning](./octoacme-project-planning.md)
**Breaking work into shippable increments and creating backlogs**
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and risks
- Create release plan and milestone map

### 4. [Execution & Tracking](./octoacme-execution-and-tracking.md)
**Managing day-to-day delivery, progress tracking, and quality**
- Daily standups and weekly delivery syncs
- Pull Request workflow and quality standards
- Project board management (Backlog, Ready, In Progress, In Review, QA, Done)
- Testing and security practices
- Blocker escalation paths

### 5. [Risk Management & Communication](./octoacme-risks-and-communication.md)
**Identifying, tracking, and communicating risks and dependencies**
- Risk Register creation and lifecycle
- Stakeholder communication strategies and templates
- Weekly status updates and incident communication
- Escalation paths and response procedures

### 6. [Release & Deployment](./octoacme-release-and-deployment.md)
**Standardizing releases and deployments to reduce risk**
- Release types (Patch, Minor, Major)
- Pre-release requirements and deployment checklist
- Post-deploy verification and rollback procedures
- Release notes template and incident playbook

### 7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
**Capturing learnings and driving improvements**
- Retrospective structure and timing
- How to track and measure improvement action items
- Building a continuous improvement culture
- Action item templates and success criteria

### 8. [Roles & Personas](./octoacme-roles-and-personas.md)
**Detailed definitions of key roles and responsibilities**
- **Developers** — Design, build, test, and deliver software
- **Product Managers** — Define outcomes, prioritize, and measure success
- **Project Managers** — Coordinate delivery, manage risks and communications
- How these personas are used in exercises and scenarios

## Project Lifecycle

Our projects follow a five-phase structured lifecycle:

### 1. **Initiation**
- Validate the business problem and customer need
- Align stakeholders and identify champions
- Create the Project One-pager with success metrics
- **Decision gate**: Approve to move into planning

### 2. **Planning**
- Define scope and break work into shippable increments
- Create prioritized backlog with acceptance criteria
- Estimate effort and define Definition of Done
- Identify cross-team dependencies and risks
- Create release plan and milestone map

### 3. **Execution**
- Build and test features to meet acceptance criteria
- Conduct daily standups and weekly delivery syncs
- Track progress on project board
- Identify and escalate blockers
- Perform continuous quality and security checks

### 4. **Release**
- Ensure all acceptance criteria met and tests passing
- Run smoke tests and pre-deployment verification
- Deploy to staging and production
- Post-deploy verification and monitoring
- Announce release to stakeholders

### 5. **Close & Retrospective**
- Capture learnings and successes
- Identify improvement action items
- Document and share outcomes and metrics
- Plan for sustainment and follow-on work

## Key Artifacts

Throughout the project lifecycle, you'll create and maintain these key artifacts:

| Artifact | Purpose | Maintained By |
|----------|---------|---|
| **Project One-pager** | Defines problem, goal, success metrics, stakeholders, timeline | Product Manager |
| **Backlog** | Prioritized list of work items with acceptance criteria | Product Manager + Team |
| **Definition of Done** | Clear criteria for when work is complete | Team + QA |
| **Risk Register** | Identifies, tracks, and mitigates project risks | Project Manager |
| **Project Board** | Visual tracking of work status (Backlog → Done) | Project Manager |
| **Release Notes** | Communicates what changed and any migration needs | Product Manager |
| **Retrospective Notes** | Captures learnings and improvement action items | Project Manager |

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Delivery team syncs (as needed)
- **Weekly**: PM + PdM alignment meeting
- **Weekly**: Risk and status review with stakeholders
- **Monthly**: Stakeholder updates and demos
- **Ad-hoc**: Escalations and incident response

## How to Use These Docs

- **As a New Team Member**: Start with the [Project Management Overview](./octoacme-project-management-overview.md), then read docs in order
- **As a Project Manager**: Keep the Project One-pager and this README updated in your project repository
- **As a Copilot Space User**: Add these docs to `.copilot/` or project context to get role-specific guidance
- **For Continuous Improvement**: When you identify gaps or improvements, use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

## Contributing to Process Docs

Have feedback or want to suggest improvements to these processes?

- Open an issue using the **[Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
- Describe the gap, improvement, or clarification needed
- Include suggested content or rationale
- Collaborate with the team to refine and integrate improvements

---

**Last Updated**: September 2024  
**Maintained By**: OctoAcme Project Management Team
