# AI Content Studio — Prototype
ต้นแบบเว็บไซต์ภาษาไทยแบบ responsive มี 6 หน้าหลัก: Dashboard, Create Content, Product Library, My Content, Content Calendar และ Analytics

## วิธีเปิด
1. แตกไฟล์ ZIP
2. เปิด `index.html` ด้วย Safari/Chrome รุ่นใหม่ หรืออัปโหลดไฟล์ทั้งหมดไปยัง static hosting เช่น GitHub Pages
3. ทดลองเปลี่ยนหน้า เพิ่มสินค้า สร้างร่างคอนเทนต์ เปลี่ยนสถานะ และเพิ่มกำหนดการได้

## ฟีเจอร์ในต้นแบบ
- เลือกหมวดหมู่สินค้า, สไตล์คอนเทนต์ 18 แบบ, 5 แพลตฟอร์ม, รูปแบบงาน, Mood & Tone และเทศกาล
- อัปโหลดรูปเพื่อดูตัวอย่าง
- สร้างร่างข้อความ/Storyboard ตัวอย่าง, คัดลอกข้อความ
- เพิ่มสินค้า, ค้นหางาน, เปลี่ยนสถานะ, เพิ่มกำหนดการในปฏิทิน
- บันทึกข้อมูลใน localStorage ของเบราว์เซอร์เครื่องนั้น

## ข้อจำกัดสำคัญ
เป็น frontend prototype เท่านั้น ยังไม่มี AI API จริง, Login/สมาชิก, ฐานข้อมูลออนไลน์, sync ข้ามอุปกรณ์, อีเมลแจ้งเตือน หรือสถิติจากแพลตฟอร์มจริง หากจะใช้งานจริง ต้องเพิ่ม backend, authentication, database และเชื่อมต่อ AI provider โดยเก็บ secret API key ไว้ฝั่ง server เท่านั้น
