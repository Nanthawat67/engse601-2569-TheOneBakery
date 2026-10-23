# หน้าส่งงานกลุ่ม ENGSE601 — TheOneBakery

> กำหนดส่งตามประกาศที่ให้มา: 23 ต.ค. 2569 เวลา 23:59. ตารางนี้เป็น draft status จากไฟล์/แหล่งข้อมูลที่ตรวจได้ในขณะจัดทำ; ผู้ส่งหลักต้อง review/update ก่อนสร้าง Release.

## ข้อมูลทีม

| รายการ | ค่า |
|---|---|
| TeamName | TheOneBakery |
| Project | THE ONE Bakery |
| ผู้ส่งหลัก | นันทวัฒน์ แซ่ย่าง (@Nanthawat67) |
| Repository | https://github.com/Nanthawat67/engse601-2569-TheOneBakery |
| Feature จาก S1-B | การบันทึกคำสั่งซื้อและคำนวณยอดรวม |

## G1-G9 status

| # | งาน | Expected path | Status | หมายเหตุ |
|---|---|---|---|---|
| G1 | W01 Quality Risk Cards | `WEEKS/week-01/submission/W01_TheOneBakery_Quality-Risk-Cards_v1.pdf` | ส่งบางส่วน | ร่าง 3 risks จาก source code + S1-B; formal SRS และ peer review ยังขาด |
| G2 | W02 Project Quality Route Map | `WEEKS/week-02/submission/W02_TheOneBakery_Project-Quality-Route-Map_v1.pdf` | ส่งบางส่วน | route map drafted; formal SRS/HLD, peer review, actual test evidence ยังขาด |
| G3 | W03 Revised Critical Requirements | `WEEKS/week-03/submission/W03_TheOneBakery_Revised-Critical-Requirements_v1.pdf` | ส่งบางส่วน | proposed ACs; draft IDs are not official SRS IDs; owner approval required |
| G4 | W04 SRS Review, RTM Lite, Gate A | `WEEKS/week-04/submission/W04_TheOneBakery_SRS-Review-and-RTM_v1.pdf` | ส่งบางส่วน | Gate A honestly Not Ready because formal SRS/owner decision/test evidence missing |
| G5 | W05 Requirement-to-Design Trace | `WEEKS/week-05/submission/W05_TheOneBakery_Requirement-to-Design-Trace_v1.pdf` | ส่งบางส่วน | Draft based on the official HLD Visual Guide plus AC-X-05/BR-X-02 from supplied S1 worksheet; full SRS/HLD DOCX line-by-line check and peer review still required. SRS baseline v1.0/v1.1 needs confirmation. |
| G6 | ใบงานครั้งที่ 1 ส่วน B | `01-plan/S1-B_TheOneBakery.pdf` | ส่งบางส่วน | Reconstructed from supplied S1 worksheet; graph is marked retrospective; finding is static review, not runtime test; peer review pending |
| G7 | ใบงานครั้งที่ 2 ส่วน B | `02-test-design/S2-B_TheOneBakery.pdf` | ส่งบางส่วน | Draft test design based on template README/current code; official S2 worksheet itself was not supplied; compare against official prompt if available |
| G8 | ใบงานรวม 3-4 ส่วน B1 | `03-test-execution/execution-report.md`, `tests/`, `evidence/` | ส่งบางส่วน | Only standalone basic logic assertions ran: 3 pass. API/DB/System/UAT cases remain Not Executed; no results fabricated. |
| G9 | Team roles / AI log | `TEAM.md`, `AI-LOG.md` | ส่งบางส่วน | Names/roles from S1 worksheet; other GitHub usernames and member confirmation remain needed. AI use is recorded; team review pending. |

## Do not submit as complete until checked

- W01-W04 are drafts based on available S1-B/code because no formal project SRS/Proposal was available.
- W05 PDF is a draft based on the official course HLD visual guide and supplied worksheet statements; compare with the full Case X SRS/HLD DOCX before final submit.
- API/system/UAT results must be added only after actual execution.
- Before upload, ensure no student IDs, credentials, tokens, `.env`, API keys or real customer data exist in the Public course repo.
- Final submit requires creating Release `engse601-submit` and completing the instructor's form as primary submitter.
