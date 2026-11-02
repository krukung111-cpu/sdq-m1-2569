# ระบบประเมินพฤติกรรมนักเรียน (SDQ) ชั้นมัธยมศึกษาปีที่ 1 ปีการศึกษา 2569
**โรงเรียนศรีเจริญศึกษา สำนักงานเขตพื้นที่การศึกษามัธยมศึกษาอุบลราชธานี อำนาจเจริญ**

## ไฟล์ในชุดติดตั้งสำหรับ GitHub Pages
- `index.html` : ไฟล์เว็บแอปหลักฉบับสมบูรณ์ (รวมตราสัญลักษณ์ แบบประเมิน 25 ข้อ ระบบอัปโหลดรายชื่อ Excel/CSV และระบบพิมพ์รายงาน PDF สรุปผลและรายบุคคล 4 หน้า)
- `.nojekyll` : ไฟล์กำกับให้ GitHub Pages แสดงผลหน้าเว็บทันทีโดยไม่ต้องรัน Jekyll
- `Code.gs` : โค้ด Google Apps Script สำหรับเชื่อมต่อกับโฟลเดอร์ `SDQ69` (`1gulB3ZOTD1RQO8GE4BgUkaaAJsyH49vB`) บน Google Drive

## ขั้นตอนการนำขึ้นฝากบน GitHub Pages (ฟรี)
1. ไปที่ [https://github.com/new](https://github.com/new) เพื่อสร้าง Repository ใหม่
2. ตั้งชื่อ Repository เช่น `sdq-m1-2569` เลือกเป็น **Public** แล้วกด **Create repository**
3. กดลิงก์ **uploading an existing file** (หรือปุ่ม **Add file > Upload files**)
4. ลากไฟล์ `index.html`, `README.md`, และ `.nojekyll` จากโฟลเดอร์นี้ไปวาง แล้วกดปุ่มสีเขียว **Commit changes**
5. ไปที่แท็บ **Settings** (ด้านบนของ Repository) > เลือกเมนู **Pages** (แถบด้านซ้าย)
6. ในหัวข้อ **Build and deployment > Branch** ให้เปลี่ยนจาก `None` เป็น `main` (โฟลเดอร์ `/ (root)`) แล้วกด **Save**
7. รอประมาณ 1–2 นาที รีเฟรชหน้าเว็บ จะปรากฏลิงก์เว็บไซต์ เช่น `https://<ชื่อผู้ใช้ของคุณครู>.github.io/sdq-m1-2569/` สามารถนำลิงก์หรือสร้าง QR Code ส่งให้นักเรียนครูและผู้ปกครองใช้งานได้ทันที
