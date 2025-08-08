# Begins Guide – eBook Store

ระบบขาย eBook พร้อม Dashboard / Log / Email / Token download

## 🚀 วิธีเริ่มใช้งานผ่าน GitHub Codespaces

1. คลิกปุ่ม `Code` → `Open with Codespaces`
2. ระบบจะเปิด Visual Studio Code พร้อม environment
3. แก้ไข frontend, Cloudflare Worker ได้ทันที
4. ใช้ `wrangler` deploy ไปยัง Cloudflare Workers

## 📦 Tools ที่ใช้

- Cloudflare Workers + Wrangler
- HTML/CSS/JS หรือ React frontend
- KV สำหรับเก็บลิงก์ดาวน์โหลด
- SMTP สำหรับส่งอีเมล

## 🛠 หลัง Deploy

- แก้ `wrangler.toml` ให้ตรงกับบัญชี Cloudflare ของคุณ
- ตั้งค่ารหัสผ่านอีเมลผ่าน `wrangler secret put`
