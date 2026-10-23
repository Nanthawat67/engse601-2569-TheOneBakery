# ENGSE601 Group Submission — TheOneBakery (updated 23 Oct 2026)

แพ็กนี้จัดไฟล์หลักตามรายการงานกลุ่มในประกาศ ENGSE601 ล่าสุด: W01–W05, ใบงานครั้งที่ 1 ส่วน B, ใบงานครั้งที่ 2 ส่วน B และ B1/B3 ของใบงานรวม 3–4. ไม่รวมงานเดี่ยวส่วน A และไม่ทำ B2 ตามประกาศรายวิชาที่อัปเดตล่าสุด.

## วิธีอัปเดต repo ที่มีอยู่แล้ว

1. แตก ZIP ลงเครื่องและเปิด `Nanthawat67/engse601-2569-TheOneBakery`.
2. Upload/replace ไฟล์ตาม path ใน `MANIFEST.txt`; อย่าเอาส่วน A หรือรหัสนักศึกษาขึ้น repo เพราะ repo เป็น Public.
3. ตรวจว่า `SUBMISSIONS.md`, `STATUS.md`, `TEAM.md`, `AI-LOG.md`, `INPUTS/input-register.md` และ `INPUTS/project-links.md` สอดคล้องกับไฟล์ที่อัปโหลด.
4. กรอก reviewer/วันที่/การแก้ไขใน `PEER_REVIEW_TODO.md` หลังให้เพื่อนตรวจจริงเท่านั้น; อย่าสร้าง approval ย้อนหลัง.
5. รัน/ตรวจงานเท่าที่เข้าถึงได้. G8 ในปัจจุบันมีเพียง 3 standalone logic assertions; API/DB/System/UAT ยัง Not Executed. ถ้าทดสอบได้จริง ให้เพิ่มผล/หลักฐานที่เกิดขึ้นจริง. ถ้ารันไม่ได้ ให้คงสถานะและเหตุผลตามจริง.
6. ตรวจ PDF ที่เปิดแล้วทุกหน้าและยืนยันว่าไม่มีข้อมูลส่วนบุคคล/credentials จากนั้นอัปเดต `SUBMISSIONS.md` ตามจริง.
7. ผู้ส่งหลักสร้าง GitHub Release ชื่อ `engse601-submit` และส่ง URL repo ผ่าน Google Form ที่อาจารย์ประกาศ.

## ข้อจำกัดที่ห้ามซ่อน

- Proposal/SRS ที่อนุมัติของโครงงาน THE ONE Bakery ยังไม่อยู่ในชุดไฟล์ที่ตรวจ; `AC-ORD-*` คือ proposed criteria ที่รอ owner confirmation ไม่ใช่ official SRS IDs.
- W05 ใช้ Case X ตามงานกลุ่มสัปดาห์ที่ 5 โดยยึด SRS v1.1 / HLD v0.9; teammate review ต้องเทียบ full DOCX อีกครั้ง.
- ผลทดสอบของแอปต้องมาจากการรันจริง. ผล 3 assertions ไม่ได้พิสูจน์ว่า Express/PostgreSQL application ผ่าน.
- เพิ่มเพื่อน/username และบันทึกการทบทวนด้วยข้อมูลจริงของทีมก่อน Release.
