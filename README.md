# 5S & GMP Audit — Android APK Builder (Capacitor)

โปรเจกต์นี้ตั้งค่า URL Web App และสิทธิ์ Android (`CAMERA`, `READ_MEDIA_IMAGES`) รวมถึงระบบดาวน์โหลดไฟล์ Excel (`.xlsx`) ไว้เรียบร้อยแล้ว

## วิธีรับไฟล์ `.apk` (ไม่ต้องลงโปรแกรมในคอมพิวเตอร์)

1. แตกไฟล์ `.zip` นี้ออกเป็นโฟลเดอร์
2. สมัครหรือเข้าสู่ระบบที่ [github.com](https://github.com) แล้วกด **New repository** (ตั้งชื่อเช่น `5s-gmp-audit-apk`)
3. กดลิงก์ **uploading an existing file** บนหน้า Repository แล้วลากไฟล์และโฟลเดอร์ทั้งหมดข้างใน (รวมถึงโฟลเดอร์ `.github`) วางลงไปแล้วกด **Commit changes**
   > **ข้อควรระวัง:** หากอัปโหลดผ่านหน้าเว็บ GitHub โดยตรง โฟลเดอร์ที่ขึ้นต้นด้วยจุด (`.github`) อาจไม่ถูกเลือกอัตโนมัติ ให้ตรวจสอบว่ามีไฟล์ `.github/workflows/build-apk.yml` อยู่ใน Repository ด้วย หรือใช้ GitHub Desktop / Git CLI อัปโหลดทั้งโฟลเดอร์
4. ไปที่แท็บ **Actions** ด้านบนของ Repository จะเห็นเวิร์กโฟลว์ **Build Android APK** กำลังทำงาน (รอประมาณ 3–4 นาทีจนขึ้นเครื่องหมายถูกสีเขียว)
5. คลิกเข้าไปในงานที่เสร็จแล้ว เลื่อนลงมาด้านล่างตรงหัวข้อ **Artifacts** แล้วกดดาวน์โหลด **`5S-GMP-Audit-APK`** (ข้างในจะมีไฟล์ `app-debug.apk` พร้อมติดตั้งบนมือถือ Android)
