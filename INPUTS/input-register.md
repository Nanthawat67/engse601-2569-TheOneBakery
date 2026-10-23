# Input Register and Source of Truth — TheOneBakery

> Updated 23 Oct 2026. This register states only sources currently verified as available. A blank/unavailable formal project requirement is **Not Ready**, not inferred as an approved baseline.

| Input ID | Artifact | Path / URL | Version / date | Owner | Status | Used by | Notes / next action |
|---|---|---|---|---|---|---|---|
| IN-01 | Proposal / project proposal | Not supplied in the checked evidence pack | Version not available | Project owner/team | **Not Ready** | W01–W04 | Add approved/current file or accessible URL; record version and approval/source-of-truth date. |
| IN-02 | Formal Requirement/SRS for THE ONE Bakery | Not supplied in the checked evidence pack | Version not available | Project owner/team | **Not Ready** | W01–W04 | W03 IDs `DRAFT-ORD-*` and criteria `AC-ORD-*` are temporary drafting IDs, not approved SRS IDs. Confirm requirements with the owner before treating them as baseline. |
| IN-03 | Bakery HLD / detailed design | Not supplied in the checked evidence pack | Version not available | Developer/team | **Not Ready** | W02, W04–W05 handoff | Source-code structure was reconstructed as a retrospective map and is explicitly labelled as such; it is not an approved design artifact. |
| IN-04 | ENGSE212 project source repository | https://github.com/Nanthawat67/the-one-bakery-New | Public repository, branch `main`; checked 23 Oct 2026; exact reviewed commit SHA still to be pinned by team | Project/team | Existing source code | W01–W04 and test planning | Relevant files: `routes/orders.js`, `routes/production.js`, `middleware/auth.js`, `database/schema.sql`, `README-FIX12.md`, `tests/basic.test.js`. Recheck the exact commit used before release. |
| IN-05 | Official ENGSE601 worksheet, S1 Section B | Local source used when preparing S1-B; team copy/path must be retained as course source if available | Worksheet source; no project SRS version implied | Course / team | Existing reference | S1-B, W01–W04 | The worksheet states the selected feature as order recording and correct total calculation. It is not an approved formal SRS for the project. |
| IN-06 | Official Case X SRS | https://se-rmutl.github.io/engse601/materials/casex/ENGSE_CaseX_SRS_v1_1_Practical_TH.docx | v1.1 per current official course repository | Course source | Existing external course reference | W05 | Keep separate from THE ONE Bakery requirement baseline. Verify exact clause wording/locations in the full DOCX during peer review. |
| IN-07 | Official Case X HLD | https://se-rmutl.github.io/engse601/materials/casex/ENGSE601_CaseX_HLD_v0_9_Draft_for_Review_TH.docx | v0.9 draft for review | Course source | Existing external course reference | W05 | This is a design under review, not an approved “correct answer”. Verify every trace row against full DOCX. |
| IN-08 | Official Case X HLD Visual Guide | https://se-rmutl.github.io/engse601/materials/casex/ENGSE601_CaseX_HLD_v0_9_Visual_Guide_TH.html | v0.9 visual guide | Course source | Existing external course reference | W05 | Used to identify the described components and stated design relationships; distinguish the guide’s statements from inference. |

## Status meaning

- `Existing`: a source is actually available/openable; this does not by itself mean its claims are approved.
- `Planned`: an artifact or test is planned but not executed/completed.
- `Not Ready`: a required source, decision, or approval is missing.
- `Not Executed`: a test has been designed but not actually run.

## Change log

| Date | Change | Reason | Action / owner |
|---|---|---|---|
| 23 Oct 2026 | Added source register and separated bakery project sources from Case X course sources | Avoid mixing the ENGSE212 project with the Case X exercises | Team to pin exact source commit and add approved Proposal/SRS if available |
