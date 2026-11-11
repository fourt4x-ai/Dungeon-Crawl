Dungeon Crawl - Android WebView project

โปรเจกต์นี้นำไฟล์เกม HTML ของคุณใส่ไว้ในแอป Android แบบออฟไลน์
ตั้งค่าหน้าจอแนวนอน เต็มจอ เปิด JavaScript และ DOM storage

วิธีสร้าง APK ผ่าน GitHub Actions (ทำจากโทรศัพท์ได้):
1. แตกไฟล์ ZIP นี้
2. สร้าง repository ใหม่บน GitHub แล้วอัปโหลดไฟล์และโฟลเดอร์ทั้งหมดใน ZIP
3. เข้าแท็บ Actions ของ repository
4. เลือก Build Dungeon Crawl APK แล้วกด Run workflow
5. เมื่อเสร็จ เปิดงานที่สำเร็จ แล้วดาวน์โหลด Artifact ชื่อ Dungeon-Crawl-APK
6. แตก ZIP ที่ดาวน์โหลด จะพบ app-debug.apk
7. เปิด APK บน Android และอนุญาตติดตั้งจากแหล่งที่มานี้หากระบบถาม

หมายเหตุ: APK ที่ได้เป็น debug APK สำหรับทดสอบและแชร์ติดตั้งโดยตรง ไม่ใช่ไฟล์ release ที่ลง Play Store
ไฟล์เกมต้นฉบับอยู่ที่ app/src/main/assets/index.html
