# ENGSE601 Group Submission Status — TheOneBakery

> Snapshot: 23 Oct 2026. This is the team status register; it is **not** a statement that the instructor accepted the work. Deadline from the current course announcement: Friday 23 Oct 2026, 23:59 (Thailand time).

| Deliverable | Required file/path | Pack status | Remaining check before release |
|---|---|---|---|
| G1 / W01 Quality Risk Cards | `WEEKS/week-01/submission/W01_TheOneBakery_Quality-Risk-Cards_v1.pdf` | Draft prepared | Peer review; formal project Proposal/SRS remains Not Ready |
| G2 / W02 Project Quality Route Map | `WEEKS/week-02/submission/W02_TheOneBakery_Project-Quality-Route-Map_v1.pdf` | Draft prepared | Peer review; confirm source commit and project facts |
| G3 / W03 Revised Critical Requirements | `WEEKS/week-03/submission/W03_TheOneBakery_Revised-Critical-Requirements_v1.pdf` | Draft prepared | Confirm proposed rules/AC with project owner; map to official IDs if SRS is supplied; peer review |
| G4 / W04 SRS Review, RTM Lite, Gate A | `WEEKS/week-04/submission/W04_TheOneBakery_SRS-Review-and-RTM_v1.pdf` | Draft prepared; Gate A = Not Ready | Formal SRS absent; confirm decisions, add reviewers and actual evidence where available |
| G5 / W05 Requirement-to-Design Trace | `WEEKS/week-05/submission/W05_TheOneBakery_Requirement-to-Design-Trace_v1.pdf` | Draft prepared against Case X SRS v1.1 / HLD v0.9 | Peer reviewer must verify full DOCX clause wording and update findings/re-check |
| G6 / S1-B | `01-plan/S1-B_TheOneBakery.pdf` | Reconstructed from provided worksheet Section B; static review only | Peer review, confirm team names/contributions, no runtime claims |
| G7 / S2-B | `02-test-design/S2-B_TheOneBakery.pdf`, `02-test-design/test-cases.md` | Test design draft prepared | Peer review expected results against official S2 instructions; no Pass/Fail in design file |
| G8 / S34-B1 | `03-test-execution/execution-report.md`, `tests/`, `evidence/` | Partial: 3 standalone baseline assertions passed | These do not call Express/PostgreSQL. API/DB/System/UAT remain Not Executed unless actually run and evidenced |
| G9 / S34-B3 | `TEAM.md`, `AI-LOG.md` | Base records prepared | Team must confirm members, usernames, contribution records and actual reviewer details |

## Final release checklist

- [ ] Confirm names/spellings and add GitHub usernames/contribution details for all team members in `TEAM.md`.
- [ ] Have a teammate who did not author each artifact perform a real peer review; record actual date, findings, disposition and re-check in `PEER_REVIEW_TODO.md` and related files.
- [ ] Compare W05 traces against the full Case X SRS v1.1 and HLD v0.9 DOCX.
- [ ] Pin the exact `the-one-bakery-New` commit reviewed in the source register.
- [ ] Check every public file for IDs, credentials, tokens and customer data; do not put individual Section A in this repo.
- [ ] Keep each test status truthful. Add output/screenshots only from real runs. If not run, keep Not Executed with reason.
- [ ] Update `SUBMISSIONS.md` after completing the real checks.
- [ ] Primary submitter creates GitHub Release **`engse601-submit`** and submits this repository URL through the official Google Form.

No course score, instructor approval or final acceptance can be inferred from GitHub Actions passing the repository completeness script.
