# sevendogStore
online e-commerce


🛠️ คู่มือสร้าง
Seven-Dog-Store Backend (Node.js + Express + Prisma + PostgreSQL)
ฉบับ Step-by-Step พร้อมอธิบายเหตุผลทุกบรรทัด
──────────────────────────────
0. สรุปสิ่งที่เราจะสร้าง
• RESTful API สำหรับร้านสุนัขออนไลน์ (สินค้า, สต็อก, คำสั่งซื้อ, การชำระเงิน, ผู้ใช้)
• ฐานข้อมูล PostgreSQL ผ่าน Prisma ORM
• ระบบ Authentication JWT + bcrypt
• อัพโหลดรูปภาพ → Cloudinary
• ชำระเงินผ่าน Stripe (บัตรเครดิต) และ PromptPay QR (ไทย)
• โครงสร้าง Clean-Architecture (controllers, services, middlewares, routes, utils)
• ใช้ nodemon พัฒนา hot-reload
──────────────────────────────



เตรียมเครื่อง + ติดตั้งโปรแกรมพื้นฐาน
1.1 ติดตั้งโปรแกรม
• Node.js ≥ 20
• PostgreSQL ≥ 15
• Git, VS Code
1.2 สร้างฐานข้อมูลใหม่

CREATE DATABASE sevendogstore;   
