# ทีมและหน้าที่ — TheOneBakery

> Repository นี้เป็น Public. อย่าใส่รหัสนักศึกษา, credential หรือข้อมูลลูกค้าจริง. ตรวจชื่อและบทบาทจากใบงานก่อน Release. ช่องที่ระบุ “ทีมกรอก” คือข้อมูลที่ผู้ใช้จะยืนยันกับสมาชิกเอง.

| รายการ | ข้อมูล |
|---|---|
| TeamName | `TheOneBakery` |
| Project | THE ONE Bakery |
| ผู้ส่งหลัก | นันทวัฒน์ แซ่ย่าง (`Nanthawat67`) |
| Repository | https://github.com/Nanthawat67/engse601-2569-TheOneBakery |
| Source project | https://github.com/Nanthawat67/the-one-bakery-New |

## สมาชิกและบทบาทตามใบงาน S1-B ที่ส่งให้ตรวจ

| สมาชิก | หน้าที่ที่ระบุในใบงาน | GitHub username — ทีมกรอก/ยืนยัน |
|---|---|---|
| นันทวัฒน์ แซ่ย่าง | Test Scope, Strategy, Risk, Entry/Exit | `Nanthawat67` |
| ธนกร ผดุงศิลป์ | Feature และ Business Rule | `thanakon17` |
| อภิรยา สายนาคา | Component และ Data Flow | `[ทีมยืนยันการสะกดชื่อและ username]` |
| ณัฐพงศ์ จันทร์สิงห์ | ตรวจสอบกฎและข้อค้นพบ | `0rea` |

> ตรวจชื่อภาษาไทยกับใบงานฉบับจริงอีกครั้งก่อน Release; ตารางนี้ยึดข้อความจาก S1-B ที่ได้รับ ไม่ได้ยืนยันว่าทุกคนได้ยอมรับหน้าที่แล้ว.

## ใครทำส่วนไหนในชุดนี้

| Work item | Preparation source | Peer reviewer (not author) | สถานะตรวจจริง |
|---|---|---|---|
| W01 | S1-B + static inspection of public source code; AI helped organize risk cards | `ธนกร ผดุงศิลป์` | Draft; no approved project SRS/Proposal in checked sources |
| W02 | S1-B + public source-code paths; AI helped organize route map | `ธนกร ผดุงศิลป์` | Draft; no application API/system evidence |
| W03 | S1-B + static code inspection; AI helped structure proposed requirements/ACs | `ธนกร ผดุงศิลป์` | Proposed only; owner confirmation pending |
| W04 | S1-B + source review + proposed W03 requirements; AI helped organize review/RTM | `ณัฐพงศ์ จันทร์สิงห์` | Gate A `Not Ready`; no formal SRS/sign-off |
| W05 | Current official course Case X sources: SRS v1.1 and HLD v0.9 Visual Guide; AI helped structure trace/findings/questions | `ณัฐพงศ์ จันทร์สิงห์` | Draft; exact wording/sections need verification against full DOCX |
| S1-B | Supplied official S1 worksheet Section B + static source review | `ณัฐพงศ์ จันทร์สิงห์` | Retrospective component flow; static observation only |
| S2-B | Official ENGSE601 S2 course instructions + S1-B feature and code-level proposed test basis | `[เติมหลังเพื่อนตรวจจริง]` | Draft; all test cases Not Executed |
| B1/G8 | Existing three standalone Node assertions and real terminal output in evidence folder | `[เติมหลังเพื่อนตรวจจริง]` | 3 baseline assertions passed; not application/API/DB tests. System/UAT Not Executed |
| B3/G9 / AI log | AI usage and source limitations recorded in AI-LOG.md | `[ให้สมาชิกยืนยันตามจริง]` | Confirmation pending |

## Contribution allocation — team to fill truthfully

| Member | Actual contribution completed | Evidence / file | Confirmed by member? |
|---|---|---|---|
| นันทวัฒน์ แซ่ย่าง | `ประสานงานและจัดเตรียมไฟล์งานกลุ่ม G1–G9 ตรวจสอบโครงสร้างและตำแหน่งไฟล์ให้ตรงตามรายการส่งงาน ใช้ ChatGPT ช่วยร่างและจัดระเบียบเอกสาร พร้อมบันทึกการใช้ AI และรวบรวมรายการที่ต้องตรวจสอบเพิ่มเติม` | `SUBMISSIONS.md`; `TEAM.md`; `AI-LOG.md`; `01-plan/S1-B_TheOneBakery.pdf`; `02-test-design/S2-B_TheOneBakery.pdf`; `WEEKS/week-01/submission/`; `WEEKS/week-02/submission/`; `WEEKS/week-03/submission/`; `WEEKS/week-04/submission/`; `WEEKS/week-05/submission/` | `Yes` |
| ธนกร ผดุงศิลป์ | `ตรวจทานเอกสาร W01–W03 และใบงาน S1-B/S2-B เทียบกับโจทย์อาจารย์ ตรวจความครบถ้วนของข้อกำหนด กรณีทดสอบ และผลที่คาดหวัง พร้อมแจ้งจุดที่ควรแก้ไข` | `WEEKS/week-01/submission/; WEEKS/week-02/submission/; WEEKS/week-03/submission/; 01-plan/S1-B_TheOneBakery.pdf; 02-test-design/S2-B_TheOneBakery.pdf` | `No` |
| อภิรยา สายนาคา | `ตรวจทานเอกสาร W04/W05 กับคำแนะนำและเอกสารต้นฉบับของรายวิชา ตรวจความถูกต้องของการอ้างอิงและความเชื่อมโยงระหว่างข้อกำหนดกับเอกสารออกแบบ พร้อมระบุจุดที่ต้องตรวจสอบเพิ่มเติม` | `WEEKS/week-04/submission/; WEEKS/week-05/submission/; WEEKS/week-05/W05_SOURCE_NOTES.md` | `No` |
| ณัฐพงศ์ จันทร์สิงห์ | `ตรวจทานรายงานการทดสอบ โค้ดทดสอบ และหลักฐานที่จัดเก็บ เทียบผลที่รายงานกับหลักฐานจริง รวมถึงตรวจรายการส่งงานและการบันทึกการใช้ AI` | `03-test-execution/execution-report.md; 03-test-execution/tests/; 03-test-execution/evidence/; SUBMISSIONS.md; AI-LOG.md` | `No` |

## Before Release

- [ ] Confirm name spellings and usernames with all members.
- [ ] Record who actually prepared each artifact and who independently reviewed it.
- [ ] Do not claim a peer review, owner decision, stakeholder approval or test run until it happened and there is evidence.
- [ ] Do not add student IDs to the Public repo.
