# ผลการรันจริง (B1) — TheOneBakery

> สถานะนี้แยกผลจริงออกจากสิ่งที่ยังไม่ได้รัน ห้ามอ้างว่าระบบ THE ONE Bakery ผ่าน API/DB/System test จาก basic.test.js

| รายการ | ข้อมูล |
|---|---|
| Team / feature | TheOneBakery / การบันทึกคำสั่งซื้อและคำนวณยอดรวม |
| Source | https://github.com/Nanthawat67/the-one-bakery-New (branch main; exact commit ยังไม่ได้ pin) |
| Command ที่รันจริง | `node --test 03-test-execution/tests/basic.test.js` ใน workspace เตรียมงานนี้ |
| ผลจริง | 3 passed, 0 failed — ดู `evidence/TC-BASE_unit_2026-10-23.txt` |
| ขอบเขตของ test | ตรวจ state-flow array, batch-rounding formula, association metric arithmetic เท่านั้น ไม่เรียก backend API และไม่ต่อ PostgreSQL |

## ขั้นที่ 1 — เลือกระดับ

| TC | ระดับ | เหตุผล | สถานะ |
|---|---|---|---|
| TC-01 | Integration/API | POST /api/orders เชื่อม Express route กับ PostgreSQL | Not Executed |
| TC-02 | Integration/API | ตรวจ invalid/missing/inactive product ที่ API/DB boundary | Not Executed |
| TC-03 | Integration/API | ตรวจ quantity 1, 0, -1, 1.5 และผล validation | Not Executed |
| TC-04 | Integration | ตรวจ resource shortage และไม่มี partial insert/stock change | Not Executed |
| TC-05 | Integration/System | ตรวจ role, ลำดับสถานะ และ status history | Not Executed |
| TC-06 | Integration | ตรวจ recipe deduction, rollback และการตัดซ้ำ | Not Executed |

## ขั้นที่ 2 — Automated test

- Code: `tests/basic.test.js`
- Command: `node --test 03-test-execution/tests/basic.test.js`
- Evidence: `evidence/TC-BASE_unit_2026-10-23.txt`
- Actual status: Pass, 3/3 assertions in the isolated Node runner. This is not proof of application API behavior.

## ขั้นที่ 3 — System ทำมือ

- Scenario: เลือกสินค้า, ตั้งจำนวน, ตรวจยอด checkout, ส่งออเดอร์, รับเลขออเดอร์และเปิดหน้า track
- Actual status: `Not Executed` — ไม่มี app instance/isolated test DB ที่เชื่อมต่อได้ใน workspace นี้
- Next action: สมาชิกเปิด app กับ test DB ของทีมและ capture ภาพจริงที่เห็น input, result, timestamp; ไม่ใช้ข้อมูลลูกค้าจริง

## ขั้นที่ 4 — UAT

- Scenario: ตัวแทนร้านทำ order จริงใน test environment ตั้งแต่ review → production → packing → pickup
- Actual status: `Not Executed` — ยังไม่มี session ที่ผู้ใช้ตัวแทนดำเนินการและบันทึกไว้
- Plan: นัดผู้ใช้ตัวแทน, ใช้ข้อมูล synthetic, บันทึกขั้นตอน/ผลจริง/วันที่และภาพหน้าจอ

## ขั้นที่ 5 — Summary

| Group | Result |
|---|---|
| TC-BASE standalone assertions | Pass 3 / Fail 0 |
| TC-01..TC-06 app API/DB tests | Not Executed |
| Manual System | Not Executed |
| UAT | Not Executed |

Fail = 0 ในชุด baseline ไม่ได้หมายความว่า app ผ่าน test; ยังต้องทดสอบ API/DB/System/UAT และเก็บหลักฐานจริง
