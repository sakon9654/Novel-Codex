# ตั้งค่า ChatGPT Project ให้ใช้ Novel-Codex

เอกสารนี้ใช้เชื่อม ChatGPT Project สำหรับนิยายกับสกิลและข้อมูลใน repo `sakon9654/Novel-Codex` โดยตรง

## 1. เชื่อม GitHub

ใน ChatGPT เปิด **Settings → Apps/Connectors** แล้วเชื่อม GitHub พร้อมอนุญาต repo `sakon9654/Novel-Codex` หากมีตัวเลือกจำกัด repo ให้เลือกเฉพาะ repo นี้ก็พอ

GitHub connector ทำให้ ChatGPT ค้นและดึงไฟล์ที่ได้รับอนุญาตตามต้องการ แต่ไม่ได้ซิงก์ทุกไฟล์ไว้ล่วงหน้า และความพร้อมใช้งานอาจต่างกันตามแพ็กเกจหรือพื้นที่ทำงาน

## 2. ใส่ Project Instructions

<<<<<<< HEAD
เปิด ChatGPT Project สำหรับนิยาย → เมนู **⋯ → Project settings → Project instructions** แล้ววางข้อความจากไฟล์ [`CHATGPT-PROJECT-INSTRUCTIONS.md`](CHATGPT-PROJECT-INSTRUCTIONS.md)
=======
เปิด ChatGPT Project สำหรับนิยาย → เมนู **⋯ → Project settings → Project instructions** แล้ววางข้อความจากไฟล์ [CHATGPT-PROJECT-INSTRUCTIONS.md](CHATGPT-PROJECT-INSTRUCTIONS.md)
>>>>>>> 9d238a24c370bb92991bd9abf369b187c8510c57

## 3. เริ่มแชตใน Project

ก่อนเริ่มระดมพล็อตหรือเขียน ให้บอก ChatGPT ให้ค้น repo `sakon9654/Novel-Codex` และอ่านไฟล์ต้นทางตาม instructions อย่าใช้แชตนอก Project เพราะ instructions และไฟล์ของ Project มีผลเฉพาะใน Project นั้น

ถ้า ChatGPT ค้น repo ไม่ได้ หรือ GitHub ไม่ปรากฏในเครื่องมือ ให้แนบไฟล์สกิลและโน้ตที่ต้องใช้ใน Project Sources แทน และบอกให้ชัดว่าไฟล์เหล่านั้นคือฉบับล่าสุด

## ข้อควรรู้เกี่ยวกับ Obsidian vault

ไฟล์ `Novel Vault/` ที่อยู่ใน working tree อาจยังไม่ได้ commit/push จึงยังอ่านผ่าน GitHub ไม่ได้ จนกว่าจะส่งไฟล์ขึ้น branch ที่ ChatGPT เข้าถึงได้ ตรวจสถานะด้วย `git status` ก่อนตั้งความคาดหวังว่า ChatGPT จะเห็น canon ล่าสุด
<<<<<<< HEAD

=======
>>>>>>> 9d238a24c370bb92991bd9abf369b187c8510c57
