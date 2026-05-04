# OctoAcme — Decision Log Template

## Purpose
Record significant project decisions — what was decided, why, who was involved, and what alternatives were considered. A decision log reduces repeated debates, supports onboarding, and provides an audit trail for future reference.

## When to log a decision
Log a decision when it:
- Affects the project scope, timeline, or budget
- Involves a technical architecture or tooling choice
- Resolves a dispute or trade-off between stakeholders
- Has a meaningful impact on users or compliance requirements
- May need to be revisited or explained later

## How to use
1. Assign a sequential **Decision ID** (e.g., DEC-001).
2. Fill in all fields in the template below.
3. Add the completed entry to the **Decision Log** table in this document (or in the project's own copy).
4. Share the log with relevant stakeholders and link it from the Project One-pager.

---

## Single Decision Template

**Decision ID:** DEC-XXX
**Date:** YYYY-MM-DD
**Status:** Proposed | Accepted | Superseded | Deprecated

**Decision title:**
One short sentence summarizing the decision.

**Context:**
What situation or problem prompted this decision? Include relevant constraints, requirements, or background.

**Decision:**
What was decided? Be specific.

**Alternatives considered:**

| Alternative | Reason not chosen |
|---|---|
| Option A | |
| Option B | |

**Consequences:**
What are the known trade-offs, risks, or follow-up actions resulting from this decision?

**Decision makers / approvers:**
- Name / Role:

**Consulted:**
- Name / Role:

**Informed:**
- Name / Role:

---

## Decision Log Table

Use this table as an index of all decisions. Link each **Decision ID** to the full record (in a separate file, a GitHub Issue, or a section below).

| Decision ID | Date | Title | Status | Owner |
|---|---|---|---|---|
| DEC-001 | YYYY-MM-DD | *(title)* | Accepted | *(role)* |
| DEC-002 | YYYY-MM-DD | *(title)* | Proposed | *(role)* |

---

## Decision Log Checklist

- [ ] Decision log file created and linked from the Project One-pager
- [ ] All significant decisions since kickoff are recorded
- [ ] Each entry has a clear decision, context, and owner
- [ ] Superseded decisions are marked with their replacement Decision ID
- [ ] Decision log is reviewed and updated at each sprint review or milestone
