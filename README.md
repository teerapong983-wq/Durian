# สมุดสวนทุเรียน (แอปมือถือ PWA)

แอปนี้เป็นหน้าเว็บที่ติดตั้งลงมือถือได้ ข้อมูลทั้งหมดอยู่ใน Google Sheet ของคุณ
ผ่าน Apps Script (ไฟล์ Code.gs ในโปรเจกต์)

## ไฟล์ในโฟลเดอร์นี้
- index.html — ตัวแอป
- manifest.webmanifest — ชื่อ ไอคอน สีของแอป
- sw.js — ทำให้เปิดแอปได้แม้ไม่มีสัญญาณ
- icons/ — ไอคอนแอป

## ขั้นตอนขึ้น GitHub Pages
1. สมัคร/เข้าสู่ระบบ github.com
2. New repository → ชื่อ `durian` → Public → Create
3. Add file → Upload files → ลากไฟล์ทั้งหมดในโฟลเดอร์นี้ (รวมโฟลเดอร์ icons) → Commit
4. Settings → Pages → Branch: main, Folder: / (root) → Save
5. รอ 1–2 นาที แล้วเปิด https://<ชื่อผู้ใช้>.github.io/durian/

## ตั้งค่าครั้งแรกในแอป
เปิด Google Sheet → เมนู "สมุดสวน" → "แสดงลิงก์และคีย์แอป"
คัดลอก URL และคีย์มาใส่ในหน้าแรกของแอป

## อัปเดตแอปในอนาคต
อัปโหลด index.html ใหม่ทับไฟล์เดิมใน GitHub แล้วรอ 1–2 นาที
