# หน้าส่งงานกลุ่ม ENGSE601 — TheOneBakery

> กำหนดส่งตามประกาศปัจจุบัน: **ศุกร์ 23 ต.ค. 2569 เวลา 23:59 น. (เวลาไทย)**. เอกสารในชุดนี้คือ draft ที่จัดตาม path แล้ว ไม่ใช่การยืนยันว่าผู้สอนรับรองหรือให้คะแนนแล้ว.

## Team / Repository

| รายการ | ข้อมูล |
|---|---|
| TeamName | `TheOneBakery` |
| Project | THE ONE Bakery |
| ผู้ส่งหลัก | นันทวัฒน์ แซ่ย่าง (`@Nanthawat67`) |
| Repository | https://github.com/Nanthawat67/engse601-2569-TheOneBakery |
| Critical feature from supplied S1-B | การบันทึกคำสั่งซื้อและคำนวณยอดรวม |

## Group submission checklist (G1–G9)

| # | งานตามประกาศ | ตำแหน่งไฟล์ | สถานะปัจจุบัน / สิ่งที่ต้องยืนยัน |
|---|---|---|---|
| G1 | W01 Quality Risk Cards | `WEEKS/week-01/submission/W01_TheOneBakery_Quality-Risk-Cards_v1.pdf` | Draft prepared. Built from S1-B + inspected source code; approved Proposal/SRS not available. Needs peer review. |
| G2 | W02 Project Quality Route Map | `WEEKS/week-02/submission/W02_TheOneBakery_Project-Quality-Route-Map_v1.pdf` | Draft prepared. Static code evidence only; source/version and peer review need confirmation. |
| G3 | W03 Revised Critical Requirements | `WEEKS/week-03/submission/W03_TheOneBakery_Revised-Critical-Requirements_v1.pdf` | Proposed requirements/ACs. `DRAFT-ORD-*`, `DRAFT-INV-*` and `AC-ORD-*` are not approved SRS IDs; owner confirmation needed. |
| G4 | W04 SRS Review, RTM Lite, Gate A | `WEEKS/week-04/submission/W04_TheOneBakery_SRS-Review-and-RTM_v1.pdf` | Gate A = `Not Ready` because no approved project SRS/owner decision and application-level test evidence was available in the checked sources. This is intentional and honest. |
| G5 | W05 Requirement-to-Design Trace (Case X) | `WEEKS/week-05/submission/W05_TheOneBakery_Requirement-to-Design-Trace_v1.pdf` | Draft uses the current course source versions Case X SRS v1.1 + HLD v0.9. A teammate must verify exact clauses against the full DOCX. This W05 is a Case X exercise, not bakery-design evidence. |
| G6 | ใบงานครั้งที่ 1 ส่วน B | `01-plan/S1-B_TheOneBakery.pdf` | Reconstructed only from S1 worksheet Section B and source code review. Component flow is marked retrospective; no runtime test claimed. Peer review pending. |
| G7 | ใบงานครั้งที่ 2 ส่วน B | `02-test-design/S2-B_TheOneBakery.pdf` and `02-test-design/test-cases.md` | Draft includes EP, BVA, decision table, cases, traceability and review plan. No actual results/Pass/Fail belong in this file. Peer review expected results against official worksheet instructions. |
| G8 | ใบงานรวม 3–4 ส่วน B1 | `03-test-execution/execution-report.md`, `03-test-execution/tests/`, `03-test-execution/evidence/` | Three standalone baseline assertions passed in Node; they do not call Express or PostgreSQL. API/DB/System/UAT remain `Not Executed` until real runs are captured. `S34-B1_TheOneBakery.pdf` is included as a summary companion. |
| G9 | ใบงานรวม 3–4 ส่วน B3: duties and AI use | `TEAM.md`, `AI-LOG.md` | Base records prepared. Team member names/usernames/contributions and peer reviewers must be confirmed by the team. AI use is disclosed; no fabricated approvals/test results claimed. |

## Before creating Release

- [ ] Update `TEAM.md` with all confirmed member spellings, GitHub usernames and real contribution assignments. Do not add student IDs to this Public repository.
- [ ] Have teammates actually peer-review the artifacts; fill `PEER_REVIEW_TODO.md` with real dates/findings/fixes/re-checks only after review occurs.
- [ ] Verify W05 exact clauses/sections against Case X SRS v1.1 and HLD v0.9 DOCX.
- [ ] Pin the exact source-code commit of `the-one-bakery-New` used in the review and update `INPUTS/input-register.md`.
- [ ] Keep API/DB/System/UAT as `Not Executed` unless actually run. Do not manufacture results, screenshots, logs, sign-offs or decisions.
- [ ] Ensure no personal IDs, passwords, tokens, secrets, `.env` or real customer data are present.
- [ ] Confirm all expected files and latest statuses in this table after the remaining checks.
- [ ] Primary submitter creates Release named **`engse601-submit`** (`Releases → Draft a new release → tag → Publish`) and submits the repository URL through the official Google Form.

## Official course source of submission rules

- Main course repository: https://github.com/se-rmutl/ENGSE601
- Deliverables list: https://github.com/se-rmutl/ENGSE601/blob/main/docs/deliverables.md
- Current Case X SRS v1.1: https://se-rmutl.github.io/engse601/materials/casex/ENGSE_CaseX_SRS_v1_1_Practical_TH.docx
- Current Case X HLD v0.9: https://se-rmutl.github.io/engse601/materials/casex/ENGSE601_CaseX_HLD_v0_9_Draft_for_Review_TH.docx

A successful GitHub Actions completeness check is not the same as instructor acceptance or a passing grade.
