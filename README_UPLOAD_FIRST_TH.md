# ชุดงานกลุ่ม ENGSE601 — TheOneBakery

## สิ่งที่อยู่ใน ZIP

- G1 W01: PDF ร่าง Quality Risk Cards
- G2 W02: PDF ร่าง Project Quality Route Map
- G3 W03: PDF ร่าง Critical Requirements + proposed Acceptance Criteria
- G4 W04: PDF Review Log, RTM Lite, Gate A = Not Ready อย่างมีเหตุผล
- G5 W05: PDF draft based on official Case X HLD visual guide and supplied S1 worksheet for AC-X-05/BR-X-02; verify against full SRS/HLD DOCX and confirm v1.0/v1.1 baseline before final submit.
- G6 S1-B: PDF แยกส่วน B ไม่มีรหัสนักศึกษา; แผนผังติดป้ายสร้างย้อนหลังและ finding เป็น static review
- G7 S2-B: PDF draft test design; official worksheet not provided
- G8: execution-report.md, tests/basic.test.js และหลักฐานผลรันจริงของ 3 standalone assertions; API/System/UAT marked Not Executed
- G9: TEAM.md, AI-LOG.md, PROJECT.md, SUBMISSIONS.md

## วิธีเอาขึ้น GitHub ผ่านเว็บ

1. ดาวน์โหลด ZIP แล้วแตกไฟล์ลงในคอมพิวเตอร์
2. เปิด Repo course: https://github.com/Nanthawat67/engse601-2569-TheOneBakery
3. เข้าโฟลเดอร์ปลายทาง แล้วกด Add file → Upload files; อัปโหลด PDF/MD ที่อยู่ในตำแหน่งตรงกับ path ภายใน ZIP และกด Commit changes
4. ไฟล์ markdown ที่ root (`TEAM.md`, `AI-LOG.md`, `PROJECT.md`, `SUBMISSIONS.md`) ต้องอัปเดตแทนไฟล์เดิม ไม่สร้างชื่อซ้ำ; ใช้ปุ่ม Edit this file แล้ววางเนื้อหาใหม่หรือใช้ upload/replace ผ่านหน้าเว็บ
5. W05 PDF is still a draft: compare every citation/requirement phrase against the full Case X SRS/HLD DOCX and confirm the assigned baseline before treating it as final.
6. ตรวจ Actions เป็น completeness check เท่านั้น ไม่ใช่คะแนน และกรอก SUBMISSIONS.md ตามสิ่งที่ส่งจริง
7. อย่าสร้าง Release `engse601-submit` จนกว่าได้ตรวจสิ่งที่ต้องส่ง; ถ้าถึงกำหนดส่งและยังขาด ให้รายงานสถานะตามจริงแทนการอ้างว่าส่งครบ

## ข้อจำกัดที่ต้องรู้

ชุดนี้ไม่ใช่การรับรองว่า G1-G9 สมบูรณ์หรือจะได้คะแนนเต็ม. W01-W04 และ G6-G7 เป็นร่างที่ทีมต้องตรวจ; W05 is a draft requiring line-by-line source review and peer review; API/System/UAT tests are not executed. การเชื่อมต่อ GitHub ที่ใช้อยู่อนุญาตให้ตรวจไฟล์สาธารณะ แต่ปฏิเสธการเขียนไฟล์ จึงยังไม่ได้อัปโหลดชุดนี้เข้า Repo ของคุณโดยตรง.
