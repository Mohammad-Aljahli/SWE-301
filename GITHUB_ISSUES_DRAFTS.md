# GitHub Issues — Assignment 2 Backlog

Create each of the following as a **repository Issue** in the same GitHub repository used for Assignment 1.
Set every issue to **Backlog** initially. After creating all issues, move only Issues 1–4 to **Sprint 1 / Ready**.
Issue numbers below are planning labels; GitHub assigns the actual issue numbers.

## Draft Issue 1: Review subscription record fields and acceptance criteria

**Suggested primary owner:** Saleh Alhajri
**Required outcome:** Reviewed and testable subscription-record requirements
**Source:** PROJECT_PROPOSAL.md — Workflow 1 / FR-01, FR-02, FR-03, FR-04

**Description**
Document the service name, price, billing interval, and next renewal date fields; clarify create, view, edit, and delete behavior; record acceptance criteria for each action.

**Acceptance criteria**
- [ ] Required fields are documented.
- [ ] Create, view, edit, and delete outcomes are stated.
- [ ] Acceptance criteria are reviewable and testable.

**Initial Status:** Backlog
**Sprint selection:** Sprint 1; change to Ready

---

## Draft Issue 2: Define subscription data structure and input validation

**Suggested primary owner:** Mohammad Aljahli
**Required outcome:** Reviewed subscription data model and validation rules
**Source:** PROJECT_PROPOSAL.md — Workflow 1 / FR-01, FR-03; Risk: inaccurate data

**Description**
Specify the data fields, valid billing intervals, price constraints, and renewal-date representation using simulated records.

**Acceptance criteria**
- [ ] Subscription fields and types are documented.
- [ ] Valid and invalid input examples are provided.
- [ ] Data structure is reviewed by another team member.

**Initial Status:** Backlog
**Sprint selection:** Sprint 1; change to Ready

---

## Draft Issue 3: Create initial subscription record form and list

**Suggested primary owner:** Mohamed Alaaeldin Daoud
**Required outcome:** Initial prototype for adding and viewing simulated subscriptions
**Source:** PROJECT_PROPOSAL.md — Workflow 1 / FR-01, FR-02

**Description**
Implement a simple web form and list for manually entered subscription records; do not connect to payment or provider accounts.

**Acceptance criteria**
- [ ] A valid simulated subscription can be added.
- [ ] Saved records appear in a list.
- [ ] Basic required-field checks are demonstrated.
- [ ] Evidence is linked in the repository.

**Initial Status:** Backlog
**Sprint selection:** Sprint 1; change to Ready

---

## Draft Issue 4: Define test cases for subscription record management

**Suggested primary owner:** Saleh Alhajri
**Required outcome:** Reviewable test cases for core subscription actions
**Source:** PROJECT_PROPOSAL.md — Workflow 1 / FR-01, FR-02, FR-03, FR-04; NFR-03 related input integrity

**Description**
Prepare expected results for valid/invalid creation and for viewing, editing, and deleting simulated records.

**Acceptance criteria**
- [ ] Test cases cover add, view, edit, and delete.
- [ ] Each test case includes input and expected outcome.
- [ ] Another team member reviews the test cases.

**Initial Status:** Backlog
**Sprint selection:** Sprint 1; change to Ready

---

## Draft Issue 5: Implement editing and deletion of subscription records

**Suggested primary owner:** Mohammad Aljahli
**Required outcome:** Working edit and delete actions
**Source:** PROJECT_PROPOSAL.md — Workflow 1 / FR-03, FR-04

**Description**
Allow a user to update or remove an existing manually entered subscription record.

**Acceptance criteria**
- [ ] An existing record can be edited and saved.
- [ ] An existing record can be deleted.
- [ ] Changes are reflected in the displayed list.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---

## Draft Issue 6: Display subscriptions by upcoming renewal date

**Suggested primary owner:** Saleh Alhajri
**Required outcome:** Renewal-date ordered list
**Source:** PROJECT_PROPOSAL.md — Workflow 2 / FR-05

**Description**
Show saved subscription records in ascending order of next renewal date.

**Acceptance criteria**
- [ ] Records are ordered by next renewal date, earliest first.
- [ ] Order updates after a renewal date is edited.
- [ ] A test with at least three distinct dates passes.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---

## Draft Issue 7: Calculate estimated monthly subscription costs

**Suggested primary owner:** Mohammad Aljahli
**Required outcome:** Dashboard monthly-cost estimate
**Source:** PROJECT_PROPOSAL.md — Workflow 2 / FR-06; Risk: incorrect cost calculations

**Description**
Convert recorded billing intervals into monthly equivalents and display the sum; document the conversion rules before implementation.

**Acceptance criteria**
- [ ] Monthly and annual subscription examples have documented expected results.
- [ ] Dashboard displays the calculated monthly total.
- [ ] Calculation matches the agreed test examples.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---

## Draft Issue 8: Create and update manual cloud-storage records

**Suggested primary owner:** Mohamed Alaaeldin Daoud
**Required outcome:** Working storage record form
**Source:** PROJECT_PROPOSAL.md — Workflow 3 / FR-07

**Description**
Allow manual entry and updates for storage service name, used capacity, and total capacity using simulated data.

**Acceptance criteria**
- [ ] User can add a storage record.
- [ ] User can update an existing storage record.
- [ ] Saved values appear in the storage overview.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---

## Draft Issue 9: Calculate storage usage percentage and reject invalid capacities

**Suggested primary owner:** Saleh Alhajri
**Required outcome:** Correct storage percentage and validated inputs
**Source:** PROJECT_PROPOSAL.md — Workflow 3 / FR-08; NFR-03

**Description**
Calculate used capacity divided by total capacity times 100; reject negative values, zero total capacity, and used capacity greater than total capacity.

**Acceptance criteria**
- [ ] Usage percentage is correct for agreed sample data.
- [ ] All 10 predefined invalid inputs are rejected.
- [ ] Invalid entries are not saved.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---

## Draft Issue 10: Verify dashboard performance and usability targets

**Suggested primary owner:** Mohamed Alaaeldin Daoud
**Required outcome:** Recorded performance and usability test evidence
**Source:** PROJECT_PROPOSAL.md — Workflow 2 and Workflow 3 / NFR-01, NFR-02

**Description**
Run the defined local dashboard-load and user-task tests against the demonstration dataset and record observed results.

**Acceptance criteria**
- [ ] Performance test uses 50 subscriptions and 20 storage records.
- [ ] At least 9 of 10 local loads finish within 2 seconds, or failure is recorded.
- [ ] Five participants attempt adding a subscription and finding its renewal date.
- [ ] At least four complete both tasks unaided within 3 minutes, or failure is recorded.

**Initial Status:** Backlog
**Sprint selection:** Unassigned; remain Backlog

---
