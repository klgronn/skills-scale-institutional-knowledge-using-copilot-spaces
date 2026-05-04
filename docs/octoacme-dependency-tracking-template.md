# OctoAcme — Dependency Tracking Template

## Purpose
Identify, track, and manage cross-team and cross-system dependencies that could affect delivery. Surfacing dependencies early reduces surprises, unblocks teams sooner, and keeps the project timeline realistic.

## Types of dependencies

| Type | Description | Examples |
|---|---|---|
| **Internal** | Between teams or squads within OctoAcme | API contract from Platform team; design assets from UX |
| **External** | Third-party services, vendors, or partners | Payment gateway, identity provider, data feed |
| **Technical** | Infrastructure, tooling, or platform prerequisites | Cloud environment provisioning, CI/CD pipeline setup |
| **Process** | Approvals, reviews, or compliance gates | Security review, legal sign-off, architecture review board |

## How to use
1. Capture each dependency as a row in the **Dependency Register** below.
2. Assign a **Dependency ID** (e.g., DEP-001).
3. Identify the **Owning Team** (who provides the dependency) and the **Requesting Team** (who needs it).
4. Agree on a **Required By** date and track the **Status** at each weekly sync.
5. Escalate any dependency at risk to the Project Manager immediately.

---

## Dependency Register

| Dep ID | Description | Type | Owning Team / Contact | Requesting Team | Required By | Status | Notes / Escalation |
|---|---|---|---|---|---|---|---|
| DEP-001 | *(what is needed)* | Internal | *(team name)* | *(team name)* | YYYY-MM-DD | On Track | |
| DEP-002 | *(what is needed)* | External | *(vendor/contact)* | *(team name)* | YYYY-MM-DD | At Risk | |

**Status options:** Not Started · In Progress · On Track · At Risk · Blocked · Resolved

---

## Dependency Item Template

Use this when a dependency needs its own detailed record (e.g., it is blocked or complex):

**Dependency ID:** DEP-XXX
**Date identified:** YYYY-MM-DD
**Status:** *(Not Started | In Progress | On Track | At Risk | Blocked | Resolved)*

**Description:**
What is needed and why?

**Owning team / contact:**

**Requesting team / contact:**

**Required by date:** YYYY-MM-DD

**Impact if delayed:**
What milestone or delivery is blocked if this is not resolved on time?

**Mitigation plan:**
What can be done to reduce the risk of delay or unblock the dependency?

**Resolution notes:**
*(Filled in when the dependency is resolved)*

---

## Dependency Tracking Checklist

- [ ] Dependency register created at project kickoff and linked from the Project One-pager
- [ ] All known cross-team and external dependencies are captured
- [ ] Each dependency has a named owner and required-by date
- [ ] Dependency status is reviewed and updated at every weekly sync
- [ ] At-risk and blocked dependencies are escalated to the Project Manager immediately
- [ ] Resolved dependencies are marked and archived to keep the register current
