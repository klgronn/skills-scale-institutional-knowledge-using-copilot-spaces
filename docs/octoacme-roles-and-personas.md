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

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master (or Delivery Lead in non-Scrum teams) facilitates the team's agile ceremonies, removes impediments, and protects the team's focus. They coach the team on process and help continuously improve how work gets done.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers and impediments quickly
- Shield the team from unplanned interruptions and scope creep
- Coach team members on agile/delivery best practices
- Track and report delivery metrics (velocity, cycle time, burndown)
- Partner with Project Manager on delivery health and escalations

### Goals
- Maximize team throughput and predictability
- Foster a culture of continuous improvement
- Keep the team focused, energized, and unblocked

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment log updates shared with the Project Manager
- Velocity and health reports at sprint reviews

### How they interact with existing roles
- **Product Managers:** Collaborate on backlog refinement and sprint goal alignment; escalate priority conflicts.
- **Project Managers:** Share delivery metrics, flag risks, and coordinate on escalations and stakeholder communication.
- **Developers:** Remove technical and process blockers; coach on ceremonies and team agreements.

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers champion the end-user experience. They translate user needs into wireframes, prototypes, and design specifications, and validate assumptions through research to ensure what gets built is usable and valuable.

### Responsibilities
- Conduct user research (interviews, usability tests, surveys)
- Create wireframes, prototypes, and interaction specifications
- Define and maintain design standards and component patterns
- Review implemented features against design intent and usability criteria
- Collaborate with Product Managers on problem framing and success metrics
- Advocate for accessibility and inclusive design throughout the project

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs before development begins
- Maintain consistent design language across the product

### Typical Communication
- Design review sessions with Developers and Product Managers
- Usability test results shared with the full project team
- Design specs and annotated prototypes in the project repository

### How they interact with existing roles
- **Product Managers:** Co-define user problems and success criteria; align research findings with roadmap priorities.
- **Project Managers:** Communicate design milestone timelines and flag delays that affect delivery schedules.
- **Developers:** Provide detailed specs and assets; participate in implementation reviews to ensure design fidelity.

---

## Release Manager

### Role Summary
The Release Manager coordinates the end-to-end release process across teams, ensuring releases are planned, communicated, and executed safely. They own the release calendar, manage release notes, and oversee rollback procedures.

### Responsibilities
- Maintain the release calendar and communicate release windows to all stakeholders
- Coordinate readiness gates: code freeze, testing sign-off, and deployment approvals
- Draft and publish release notes and announcements
- Oversee deployment execution and monitor post-release stability
- Maintain rollback and incident playbooks in collaboration with engineering
- Conduct post-release retrospectives and track improvement actions

### Goals
- Deliver smooth, low-risk releases with minimal customer disruption
- Keep all stakeholders informed before, during, and after each release
- Continuously reduce the lead time and effort required for a release

### Typical Communication
- Release readiness reviews with Developers, QA, and Product Managers
- Pre-release announcements to support and customer-facing teams
- Post-release status updates and incident summaries

### How they interact with existing roles
- **Product Managers:** Align on release scope, feature flags, and customer communication timing.
- **Project Managers:** Coordinate release dates with project milestones and overall schedule.
- **Developers:** Confirm code freeze, review release branches, and coordinate hotfix procedures.

---

## Customer Advocate / Support Liaison

### Role Summary
The Customer Advocate (or Support Liaison) represents the voice of the customer within the project team. They surface real user pain points, translate support trends into actionable feedback, and ensure customer concerns inform planning and retrospectives.

### Responsibilities
- Gather and synthesize customer feedback from support tickets, NPS surveys, and user interviews
- Represent customer priorities in backlog refinement and planning sessions
- Validate that user-facing changes meet customer expectations before release
- Coordinate customer communications for impactful changes or incidents
- Track customer-reported defects and ensure they are prioritized appropriately
- Close the feedback loop by informing customers of resolutions

### Goals
- Ensure the customer perspective is never lost in technical or business trade-offs
- Reduce time-to-resolution for customer-impacting issues
- Build customer trust through transparent, timely communication

### Typical Communication
- Support trend summaries shared at sprint reviews and retrospectives
- Customer feedback reports for Product Manager and Project Manager review
- Release announcement reviews to ensure accuracy and clarity for end users

### How they interact with existing roles
- **Product Managers:** Provide customer insight to inform prioritization and roadmap decisions.
- **Project Managers:** Flag customer-impacting risks and coordinate communication plans.
- **Developers:** Share reproduction steps and context for customer-reported defects; validate fixes.

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead provides technical direction for the project, making key architectural and design decisions, setting engineering standards, and ensuring the team builds a reliable and maintainable system.

### Responsibilities
- Define and communicate technical architecture and design decisions
- Lead technical design reviews and approve significant code changes
- Set coding standards, PR review expectations, and engineering best practices
- Identify technical risks and propose mitigation strategies
- Mentor developers and support their technical growth
- Coordinate with the Project Manager on technical dependencies and timelines

### Goals
- Deliver a high-quality, maintainable codebase that meets functional and non-functional requirements
- Reduce technical debt and unplanned rework
- Enable developer effectiveness through clear standards and timely decisions

### Typical Communication
- Technical design docs and Architecture Decision Records (ADRs)
- PR and code review feedback
- Regular syncs with the Project Manager and Product Manager on technical scope and trade-offs

### How they interact with existing roles
- **Product Managers:** Translate technical constraints into plain language; advise on feasibility and trade-offs.
- **Project Managers:** Provide technical input to project plans, risk registers, and dependency maps.
- **Developers:** Guide daily technical decisions, conduct code reviews, and unblock complex problems.

---

## Security / Privacy Champion

### Role Summary
The Security/Privacy Champion promotes a security-first mindset within the project team. They identify security and privacy risks early, ensure compliance requirements are met, and act as the liaison to the security and legal/privacy teams.

### Responsibilities
- Conduct threat modelling and security reviews during planning and design phases
- Review code and infrastructure changes for security vulnerabilities
- Ensure privacy requirements (data minimization, consent, retention) are addressed in feature design
- Maintain the project's security checklist and track remediation of findings
- Liaise with the central Security and Legal/Privacy teams for guidance and approvals
- Respond to and coordinate security incidents affecting the project

### Goals
- Prevent security and privacy issues from reaching production
- Ensure the team understands and applies secure-by-default practices
- Meet all relevant compliance and regulatory obligations

### Typical Communication
- Security review sign-offs before major releases
- Threat model documents shared with engineering leads and Project Manager
- Incident and vulnerability reports with clear remediation timelines

### How they interact with existing roles
- **Product Managers:** Advise on privacy-by-design trade-offs and compliance constraints that affect feature scope.
- **Project Managers:** Ensure security milestones and remediation tasks are tracked in the project plan.
- **Developers:** Pair on secure coding guidance, review PRs for vulnerabilities, and share security tooling best practices.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

