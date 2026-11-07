# แผนที่วิทยาลัยพณิชยการบางนา (PWA Project)

โปรเจกต์เว็บแอปพลิเคชันแผนที่นำทางและค้นหาข้อมูลอาคารเรียน วิทยาลัยพณิชยการบางนา พร้อมระบบ Progressive Web App (PWA)

## โครงสร้างไฟล์ในโฟลเดอร์

```
bangna-map-pwa/
├── index.html        # ไฟล์หลัก (หน้าเว็บ + SVG Map + CSS + JavaScript)
├── manifest.json     # คอนฟิกสำหรับ PWA
├── sw.js             # Service Worker สำหรับรองรับการใช้งานแบบ PWA / PWABuilder
├── README.md         # เอกสารแนะนำการใช้งาน
└── images/           # โฟลเดอร์เก็บรูปภาพอาคารและไอคอนแอป
    ├── icon-192.png  # ไอคอนแอปขนาด 192x192 px
    ├── icon-512.png  # ไอคอนแอปขนาด 512x512 px
    ├── b1.jpg ... b12.jpg  # รูปภาพอาคารตึก 1-12
```

## วิธีนำขึ้น GitHub & PWABuilder

1. อัพโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น Repository บน **GitHub**
2. ไปที่ **Settings > Pages** เลือก Branch `main` แล้วกด **Save**
3. คัดลอก URL ของ GitHub Pages (เช่น `https://username.github.io/repository-name/`)
4. นำ URL ไปวางใน **[PWABuilder.com](https://www.pwabuilder.com)** เพื่อกด Generate เป็นไฟล์ `.apk` สำหรับ Android หรือติดตั้งเป็น App ได้ทันที
