# DM Radar Dashboard

## รันเครื่องตัวเอง (dev)
npm install
npm run dev

## Build สำหรับ production
npm run build
(ไฟล์ผลลัพธ์จะอยู่ที่โฟลเดอร์ dist/)

## Deploy บน Vercel (แนะนำ)
1. อัปโหลดโค้ดทั้งหมดขึ้น GitHub repo
2. เข้า https://vercel.com -> New Project -> เลือก repo นี้
3. Vercel จะตรวจพบว่าเป็นโปรเจกต์ Vite อัตโนมัติ กด Deploy ได้เลย
   (ถ้าถามการตั้งค่า: Build Command = npm run build, Output Directory = dist)

## Deploy บน Netlify
1. อัปโหลดโค้ดขึ้น GitHub repo
2. เข้า https://netlify.com -> Add new site -> Import from Git
3. ตั้งค่า Build command = npm run build, Publish directory = dist
