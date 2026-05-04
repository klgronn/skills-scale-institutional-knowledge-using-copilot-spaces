# OctoAcme — RACI Ownership Mapping Template

## Purpose
Establish clear ownership for every key activity during project kickoff. Use this template to eliminate ambiguity about who makes decisions, who does the work, who needs to be consulted, and who needs to be kept informed.

## How to use
1. List all major project activities or deliverables in the **Activity** column.
2. For each activity, assign one of the four RACI roles to each team member or role:
   - **R — Responsible:** Does the work.
   - **A — Accountable:** Owns the outcome; final decision-maker (there should be exactly one A per row).
   - **C — Consulted:** Provides input before the work is done; two-way communication.
   - **I — Informed:** Kept up-to-date on progress or decisions; one-way communication.
3. Review the completed RACI with all stakeholders at project kickoff.
4. Store the completed RACI in the project repository and link it from the Project One-pager.

> **Tip:** If a row has no **A**, assign one before moving forward. Multiple **R** entries on the same row are fine as long as ownership is clear.

---

## RACI Matrix

| Activity / Deliverable | Project Manager | Product Manager | Tech Lead | Developer(s) | UX Designer | Release Manager | Security Champion | Scrum Master | Customer Advocate | Stakeholder / Sponsor |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project charter / one-pager | A | C | C | I | I | I | I | I | I | C |
| Backlog creation and prioritization | C | A | C | C | C | I | I | I | C | C |
| Architecture / technical design | I | C | A | R | C | I | C | I | I | I |
| UX design and prototypes | I | C | C | C | A | I | I | I | C | I |
| Sprint planning | C | C | C | R | R | I | I | A | I | I |
| Development and code review | I | I | A | R | I | I | C | I | I | I |
| Security review | C | C | C | C | I | C | A | I | I | I |
| Release readiness sign-off | C | C | C | C | I | A | C | I | I | C |
| Deployment to production | I | I | C | R | I | A | C | I | I | I |
| Stakeholder status updates | A | C | I | I | I | I | I | I | I | I |
| Retrospective facilitation | C | I | I | I | I | I | I | A | I | I |
| Customer communication | C | C | I | I | I | C | I | I | A | I |
| Decision log maintenance | A | C | C | I | I | I | I | I | I | I |
| Risk register maintenance | A | C | C | C | I | C | C | I | I | I |

> Replace, add, or remove rows to fit your specific project. Add columns for additional roles as needed.

---

## RACI Checklist

- [ ] All key activities and deliverables are listed
- [ ] Every row has exactly one **A** (Accountable)
- [ ] No role is over-assigned (too many **R** entries spread across too many activities)
- [ ] All team members and stakeholders have reviewed and agreed to their assignments
- [ ] RACI is linked from the Project One-pager and stored in `docs/`
- [ ] RACI will be reviewed and updated at each major project phase boundary
