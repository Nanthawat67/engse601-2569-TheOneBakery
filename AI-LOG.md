# AI-LOG — TheOneBakery

AI was used to help organize and draft portions of the ENGSE601 evidence pack. This log is a disclosure, not a claim that the team or project owner has approved the drafts. The team must independently check, accept, change or reject each suggestion before release.

| Date | User | Tool | Purpose | Use/decision status | Verification needed | Affected artifact |
|---|---|---|---|---|---|---|
| 2026-10-23 | นันทวัฒน์ แซ่ย่าง (`@Nanthawat67`) | ChatGPT | Map public project source files to W01-W04 structure; organize quality risks, proposed testable requirements, review findings, traceability and Gate A | Drafting/structuring assistance used; team review is pending | Compare to actual source commit, supplied worksheet, and approved Proposal/SRS if available. Proposed IDs are not official SRS IDs. | W01-W04, S1-B |
| 2026-10-23 | นันทวัฒน์ แซ่ย่าง (`@Nanthawat67`) | ChatGPT | Organize EP/BVA/decision-table test design and test case set | Draft test design used; no actual result generated | Teammate checks inputs, expected results, source rules and official S2 instructions; owner confirms business rules. | S2-B, `02-test-design/test-cases.md` |
| 2026-10-23 | นันทวัฒน์ แซ่ย่าง (`@Nanthawat67`) | ChatGPT | Structure W05 Requirement-to-Design trace for Case X | Draft assistance used; exact clause review remains pending | Teammate must verify exact clauses/sections from full Case X SRS v1.1 and HLD v0.9 DOCX, then record the actual peer review. | W05 PDF, W05 source notes |
| 2026-10-23 | นันทวัฒน์ แซ่ย่าง (`@Nanthawat67`) | ChatGPT | Clarify how to report baseline checks and application tests separately | AI did not create screenshots or claim app API/DB/System/UAT results. The local baseline command output is real for the included three assertions only. | Confirm output from a real run in the team environment if claiming the same run; add new evidence only after a test has actually run. | B1/G8, `execution-report.md`, `evidence/` |

## Limits and responsible use

- Current three standalone assertions do not call Express or PostgreSQL. They do not establish that the application passed functional, API or database tests.
- API/DB/System/UAT statuses remain `Not Executed` unless the team runs them and records the real outcome.
- Formal Proposal/SRS and owner-approved HLD for THE ONE Bakery were not available in the checked source pack. `DRAFT-ORD-*` and `AC-ORD-*` are temporary IDs, not approved requirements.
- W05 uses the official **Case X** course exercise (SRS v1.1 / HLD v0.9); it is separate from the THE ONE Bakery project requirement baseline.
- Peer review, member confirmation, stakeholder decisions and approvals must be completed/recorded by people who actually performed them; AI cannot be used to manufacture them.
