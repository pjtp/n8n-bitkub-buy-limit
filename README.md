# n8n-bitkub-buy-limit

Workflow สำหรับ n8n ที่ใช้เชื่อมต่อกับ [Bitkub](https://www.bitkub.com) API เพื่อทำคำสั่งซื้อเหรียญแบบ Limit Order โดยอัตโนมัติ

## 📁 ไฟล์ภายในโปรเจกต์

- `bitkub.json` – ไฟล์ workflow สำหรับ import เข้า n8n

## ⚙️ วิธีใช้งาน

1. เปิด [n8n](https://n8n.io/) บนเครื่องคุณ
2. ไปที่ **Import Workflow**
3. เลือกไฟล์ `bitkub.json` จาก repository นี้
4. กำหนดค่า API Key / Secret ของ Bitkub ใน Credentials
5. ตั้งค่าพารามิเตอร์ต่างๆ (เช่น คู่เหรียญ, ราคา, จำนวน) ตามต้องการใน workflow
6. ทดสอบการรัน workflow

## ✅ คุณสมบัติ

- รองรับการสั่งซื้อแบบ Limit
- เชื่อมต่อผ่าน Bitkub API

## 🛡️ ข้อควรระวัง

- ควรใช้ Bitkub API ในโหมดทดสอบก่อนใช้งานจริง
- เก็บ API Key/Secret อย่างปลอดภัย
- ตรวจสอบค่าเงินก่อนซื้อเพื่อหลีกเลี่ยงความผิดพลาด

## 📄 License

MIT

---

🛠 พัฒนาขึ้นโดย [pjtp](https://github.com/pjtp)
