# DigitalWork — Static HTML GitHub Pages

เว็บไซต์เวอร์ชัน **HTML + CSS + Vanilla JavaScript** ไม่มี React, Vite, npm หรือไฟล์ `.env` และไม่ต้อง build

## เปิดใช้งาน

- อัปโหลด `index.html` ไปยัง root ของ GitHub Repository (ไม่ต้องอัปโหลด ZIP)
- Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save
- เปิด `https://USERNAME.github.io/REPOSITORY/` หลัง GitHub Pages เผยแพร่สำเร็จ
- หรือเปิด `index.html` ในเบราว์เซอร์เพื่อดูหน้าเว็บ (บางเบราว์เซอร์จำกัด module import เมื่อเปิดผ่าน `file://`; GitHub Pages เป็นวิธีที่แนะนำ)

## หมายเหตุ

- JavaScript โหลด `ethers@6.13.5` จาก CDN `https://esm.sh` จึงต้องมีอินเทอร์เน็ต
- MetaMask ต้องใช้ Sepolia testnet และมี Sepolia ETH สำหรับค่า gas
- Contract address: `0x509CA7bcc61fcb7cC7652170d7218Ec84b44Ec91` (คัดมาจากโปรเจกต์ต้นฉบับ; **ไม่ได้ยืนยันว่ามี contract deploy อยู่จริง**) 
- การเลือกไฟล์คำนวณ SHA-256 ในเบราว์เซอร์ ไม่ได้อัปโหลดไฟล์ไปเก็บไว้ที่อื่น
- การแสดงข้อมูลจาก Blockchain ต้องอาศัย MetaMask และ RPC ที่เข้าถึงได้
