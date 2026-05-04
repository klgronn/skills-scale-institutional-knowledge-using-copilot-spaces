# OctoAcme Process Documentation

This folder is the **structured knowledge source** for OctoAcme's program and project management processes. It is connected to the team's Copilot Space so that every document here can serve as grounding context — converting scattered, tacit team knowledge into searchable, versioned artifacts that are accessible to all team members equally.

## Purpose

- Centralize project management knowledge in one place.
- Give every team member equal access to processes, decisions, and the rationale behind them.
- Accelerate onboarding and reduce single-person dependency risk.
- Enable consistent, repeatable project execution by keeping process docs as living documentation.

## Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to how OctoAcme runs projects — principles, core roles, key artifacts, and lifecycle. |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight kick-off plan. |
| [Project Planning](octoacme-project-planning.md) | Guidance on scope definition, milestones, resource planning, and dependency mapping. |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | How the team builds, tracks progress, manages scope change, and keeps stakeholders informed during delivery. |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk identification, scoring, mitigation, and escalation paths alongside communication templates. |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release readiness checklist, deployment steps, rollback plan, and post-release verification. |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action-item tracking, and the feedback loop that feeds improvements back into these docs. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of the roles used across all process docs — Developers, Product Managers, Project Managers, and more. |

## Proposing Changes

All additions and updates to these documents are tracked through GitHub Issues so the rationale behind every change is preserved alongside the content itself.

### How to open an issue

1. Go to **Issues → New Issue** in this repository.
2. Choose the **"Add Content to Project Management Process Docs"** template.
3. Fill in each field:

   | Field | What to include |
   |---|---|
   | **Which process document?** | Pick the file you want to update from the dropdown, or select `<new document>` if you are proposing an entirely new doc. |
   | **Summary of New Content** | A brief description of what you want to add or change. |
   | **Why is this update needed?** | The rationale — gap in coverage, team feedback, alignment with a new practice, etc. |
   | **Suggested Content** *(optional)* | Draft text, a checklist, a table, or an example you'd like to see included. |
   | **Acceptance Criteria** | Check the boxes that apply to confirm the change meets quality expectations. |

4. Submit the issue. A maintainer or contributor will pick it up, refine the content collaboratively, and open a pull request targeting `docs/`.

## Contributor Guidance

Following these conventions keeps all documents consistent and easy to use as Copilot Space grounding context.

### Tone and style
- Write in clear, direct language — prefer short sentences and active voice.
- Address the reader as "you" or describe the team in third person ("the PM", "the team").
- Avoid jargon without definition; if you must introduce a term, define it on first use.

### Document structure
Every process doc should open with these sections (in order):

```
# <Title>

## Purpose
One or two sentences explaining what this doc covers and why it exists.

## <Content sections…>
```

Use `##` for top-level sections and `###` for sub-sections. Keep heading names descriptive but concise.

### Checklists and templates
- Use Markdown task-list syntax (`- [ ]`) for actionable checklists so they render as checkboxes on GitHub.
- Include at least one checklist or template in any procedural doc so readers have a concrete starting point.

### Adding a new process document

1. **Open an issue** using the template above and select `<new document>` from the dropdown.
2. Agree on the filename in the issue (use the pattern `octoacme-<topic>.md`, all lowercase with hyphens).
3. Create the file in `docs/` following the structure above.
4. Add a row for the new document to the [Documents table](#documents) in this README.
5. Open a pull request referencing the issue.

> **Note:** After a new document is merged, open a follow-up issue or PR to add the filename to the dropdown in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` so future contributors can select it.
