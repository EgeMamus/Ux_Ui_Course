<!-- Slide 1 — Cover -->
# Cross-border Road Payments
### One trip. Different payment systems.

**UX/UI Design Project**

Ege Mamuş · University of Pécs  
Neptun: S7FBKT

---

<!-- Slide 2 — Comparison table -->
## 01 / The Problem
### Three countries, different rules

| Country | Road charge | Typical action |
|:--|:--|:--|
| Bulgaria | E-vignette | Check validity |
| Serbia | Toll booths | Pay on the road |
| Hungary | E-vignette | Check validity |

**Challenge:** Payment methods and valid dates differ across the trip.

---

<!-- Slide 3 — Research finding -->
## 02 / User Research

> **“Can I handle the eligible online charges together?”**

### What we investigated
- One driver interview and journey map
- BGTOLL interface audit
- Road-charge tasks and user needs

**Finding:** Group eligible online items, but explain country-specific actions.

*One interview; not a finding about all drivers.*

---

<!-- Slide 4 — Capability table -->
## 03 / Design Direction
### One journey overview, clear responsibilities

| In the application | Kept separate |
|:--|:--|
| Dates and vehicle | Country-specific rules |
| Eligible online items | Serbian toll-booth action |
| Payment-status overview | Unresolved or pending items |

**Goal:** Know what is covered — and what still needs action.

---

<!-- Slide 5 — Sequence -->
## 04 / The Main User Flow

### S1 · Trip & vehicle
Enter or change sample details

↓

### S2 · Country charges
Check eligibility and coverage

↓

### S3 · Review → S4 · Results
Confirm sample items; see outstanding actions

---

<!-- Slide 6 — Prototype walkthrough -->
## 05 / Clickable Prototype
### A short Figma demo

**1. Change** the crossing date or sample vehicle  
**2. Review** Bulgaria, Serbia and Hungary separately  
**3. Confirm** the simulated online selection  
**4. Check** confirmed, pending or failed results

*No live payments. Products, prices and statuses are simulated.*

---

<!-- Slide 7 — Research results table -->
## 06 / Usability Testing
### Three participants · One main task

| User | Reported feedback |
|:--|:--|
| U1 | Date and vehicle controls were clear |
| U2 | “Pending” seemed like a card problem |
| U3 | Liked country sections; wanted a calendar |

**3/3 finished without help**, as reported by the project owner.

*Completion time was not recorded.*

---

<!-- Slide 8 — Before/after table -->
## 07 / Iteration & Handoff
### Feedback → Design decision

| Issue or request | Design response |
|:--|:--|
| Pending looks like failure | Explain: result not final; do not pay again |
| Date choice is limited | Calendar with Confirm and Cancel |
| Clear country grouping | Keep it; preserve visible actions |

**Handoff:** Reusable buttons, fields and payment-status states.

*Revisions have not been retested with participants.*

---

<!-- Slide 9 — Closing -->
## 08 / Key Takeaways

**Clear actions:** Explain what is paid and what remains.  
**Clear status:** Task completion does not guarantee understanding.  
**Next steps:** Retest the new messages and calendar; verify real-provider rules.

**Good UX explains what happened — and what comes next.**

### Thank you!
