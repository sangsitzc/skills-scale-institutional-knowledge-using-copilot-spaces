# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interaction with Other Roles
- Collaborate with **QA/Testing Professionals** on acceptance criteria and test strategy
- Work with **Product Managers** to clarify requirements and success criteria
- Coordinate with **Project Managers** on task estimation and timeline management
- Follow **Security Role** guidance on secure coding practices and security scanning requirements
- Participate in **Release Engineer/DevOps** processes for CI/CD and deployment

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interaction with Other Roles
- Report to **Product Lead** on strategic alignment and roadmap progress
- Work with **Project Managers** on prioritization and timeline coordination
- Collaborate with **Developers** on feasibility and technical trade-offs
- Engage **Stakeholders & Sponsors** for business alignment and approval
- Partner with **QA/Testing Professionals** on acceptance criteria and quality gates

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interaction with Other Roles
- Report to **Product Lead** on project status and escalations
- Partner with **Product Managers** on backlog prioritization and scope management
- Coordinate with **Developers** on schedule, capacity, and blockers
- Manage communication with **Stakeholders & Sponsors** on progress and decisions
- Engage **Release Engineer/DevOps** on deployment planning and timelines
- Coordinate with **Security Role** on security milestone planning and incident response

---

## QA/Testing Professionals

### Role Summary
QA and Testing professionals ensure software quality and validate that solutions meet acceptance criteria before release.

### Responsibilities
- Design and execute test plans (unit, integration, end-to-end)
- Validate acceptance criteria compliance
- Conduct quality assurance oversight and remediation tracking
- Perform manual QA for feature acceptance when needed
- Execute pre-release smoke tests
- Report and track defects through resolution

### Goals
- Ensure high-quality, production-ready releases
- Identify risks and quality issues early in the development cycle
- Provide clear quality signals to the delivery team

### Typical Communication
- Participation in sprint planning and acceptance criteria definition
- Test status reports and defect logs
- Release readiness sign-off

### Interaction with Other Roles
- Collaborate with **Developers** on test design, acceptance criteria clarity, and defect resolution
- Partner with **Product Managers** on acceptance criteria validation and feature sign-off
- Coordinate with **Project Managers** on testing timelines and release gates
- Work with **Release Engineer/DevOps** on smoke test execution and deployment validation
- Support **Security Role** in security testing and vulnerability assessment

---

## Security Role

### Role Summary
Security professionals oversee security practices and incident response for projects. They ensure compliance, identify risks, and lead security-related responses.

### Responsibilities
- Coordinate security scanning in CI/CD pipelines
- Review security requirements and risks during planning phases
- Lead security incident response when triggered
- Provide guidance on compliance and data protection
- Participate in risk assessments and threat modeling
- Validate security controls before release

### Goals
- Prevent security incidents and data breaches
- Ensure compliance with organizational and regulatory standards
- Enable secure development practices across the organization

### Typical Communication
- Security incident playbook execution
- Risk register updates and security reviews
- Release sign-off (security validation)
- Security training and best practice guidance

### Interaction with Other Roles
- Advise **Developers** on secure coding practices and security scanning results
- Partner with **QA/Testing Professionals** on security testing and vulnerability assessment
- Coordinate with **Project Managers** on security milestone planning and incident escalation
- Report to **Product Lead** on security risks and compliance status
- Support **Release Engineer/DevOps** on pre-release security validation
- Participate in escalation with **Stakeholders & Sponsors** on critical security issues

---

## Product Lead

### Role Summary
Product Lead provides strategic product direction and oversight for portfolio-level decisions. They align product strategy with business objectives and enable cross-project coordination.

### Responsibilities
- Define strategic product vision and roadmap
- Oversee Product Manager alignment and prioritization across projects
- Coordinate with stakeholders on business strategy and strategic initiatives
- Serve as escalation point for prioritization conflicts and strategic decisions
- Review and approve high-level business cases and roadmap items
- Ensure consistency in product strategy across multiple initiatives

### Goals
- Align product strategy with business objectives
- Ensure consistent prioritization across projects and teams
- Enable cross-project coordination and dependency management
- Maximize portfolio-level business impact

### Typical Communication
- Monthly product strategy reviews
- Stakeholder briefings and strategic alignment sessions
- Escalation resolution and priority trade-off decisions
- Cross-project roadmap coordination

### Interaction with Other Roles
- Oversee and mentor **Product Managers** on strategic alignment
- Provide guidance to **Project Managers** on priority conflicts and strategic direction
- Escalate critical **Security Role** findings and risk decisions to **Stakeholders & Sponsors**
- Engage **Stakeholders & Sponsors** on strategic direction and business alignment
- Support **Release Engineer/DevOps** on major release planning and portfolio-level deployment coordination

---

## Release Engineer / DevOps

### Role Summary
Release Engineers and DevOps professionals manage CI/CD pipelines, deployment orchestration, and infrastructure. They enable automated, reliable delivery and ensure production systems are monitored and healthy.

### Responsibilities
- Build and maintain CI/CD pipelines for automated testing and deployment
- Manage deployment orchestration and release coordination
- Monitor production systems and infrastructure health
- Implement and maintain deployment automation and infrastructure-as-code
- Coordinate with Security on compliance controls and security scanning
- Execute post-deploy verification and monitoring
- Support rollback procedures and incident recovery

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and downtime
- Provide visibility into system health and deployment status

### Typical Communication
- Release coordination and deployment planning
- Infrastructure and pipeline status updates
- Post-deployment monitoring and verification results
- Incident response and recovery coordination

### Interaction with Other Roles
- Collaborate with **Developers** on merge requirements, CI pipeline feedback, and deployment issues
- Coordinate with **QA/Testing Professionals** on smoke tests and deployment validation
- Partner with **Project Managers** on deployment timelines and rollback planning
- Work with **Security Role** on CI/CD security scanning and compliance controls
- Report to **Release Engineer/DevOps** lead on deployment health and pipeline status
- Support **Stakeholders & Sponsors** with deployment notifications and status updates

---

## Support / On-call Engineer

### Role Summary
Support and On-call Engineers provide customer-facing support and participate in incident response activities. They bridge customer needs with the development team and ensure rapid incident resolution.

### Responsibilities
- Respond to customer issues and support requests
- Participate in incident response and triage
- Provide post-incident communication to customers
- Contribute to post-incident retrospectives and root cause analysis
- Provide feedback on product usability, reliability, and customer impact
- Escalate critical issues to appropriate teams
- Maintain support documentation and runbooks

### Goals
- Minimize customer impact during incidents
- Provide transparency and timely communication during outages
- Gather insights for continuous improvement
- Enable faster incident resolution through knowledge sharing

### Typical Communication
- Incident response coordination and triage
- Release communication and support preparation
- Customer issue tracking and escalation
- Post-incident retrospectives

### Interaction with Other Roles
- Alert **Developers** to production issues and provide customer context
- Coordinate with **Project Managers** on incident escalation and communication
- Engage **Release Engineer/DevOps** on infrastructure issues and deployment problems
- Participate in **Security Role** response for security incidents
- Provide feedback to **Product Managers** on reliability and usability issues
- Update **Stakeholders & Sponsors** on critical incidents and customer impact

---

## Stakeholders & Sponsors

### Role Summary
Stakeholders and Sponsors are business and organizational leaders who provide strategic direction, business alignment, and decision authority for projects. They ensure initiatives align with business objectives and have necessary resources.

### Responsibilities
- Define business requirements and strategic objectives
- Provide project approval and funding decisions
- Escalate and resolve prioritization conflicts
- Ensure alignment with organizational strategy
- Provide business context and market insights
- Approve major milestones and release decisions
- Support resource allocation and team empowerment

### Goals
- Ensure projects deliver business value
- Maintain alignment with organizational strategy
- Enable timely decision-making and escalation resolution
- Maximize return on investment for initiatives

### Typical Communication
- Milestone reviews and approval meetings
- Strategic alignment sessions
- Executive status reports and dashboards
- Escalation resolution and decision-making
- Release announcements and stakeholder updates

### Interaction with Other Roles
- Provide strategic direction to **Product Lead** and **Product Managers**
- Approve major decisions escalated by **Project Managers**
- Receive updates from **Developers** on technical feasibility and risks
- Support **Release Engineer/DevOps** on major release decisions
- Participate in critical incident resolution with **Support/On-call Engineer**
- Approve security decisions escalated by **Security Role**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Review the interaction patterns between roles to understand communication flows and dependencies.
- Reference these definitions in risk registers, escalation paths, and decision logs to maintain clarity on roles and responsibilities.
