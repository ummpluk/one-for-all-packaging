# OFA REMINDER

> อัปเดต: 2026-05-26 13:00
> แหล่งข้อมูล: `hermes cron list` + `_docs/project-notes.md`

## ⏳ รอดำเนินการ

| Cron Job | รันครั้งถัดไป | สถานะ |
|----------|---------------|-------|
| OFA REMINDER: อัปเดตทุก 60 นาที | 2026-05-26 14:00 (อังคาร) | ⏳ ทุกชั่วโมง จ-ศ 8–17 |
| FB Post: OFA Packaging 29 Apr 8:30 | 2027-04-29 08:30 (พฤหัส) | ⏳ ทุก 29 เม.ย. ของทุกปี |

## 📋 ค้างอยู่

- ⚠️ **OFA REMINDER** (`5f93cf8c0d61`): `deliver=none` — ไม่มี delivery target ทำให้ผลลัพธ์ไม่ถูกส่งไปปลายทาง
  - แก้โดย: `hermes cron set 5f93cf8c0d61 --deliver telegram` (หรือช่องทางอื่น)
- ⚠️ **OFA REMINDER** (`5f93cf8c0d61`): `skills=cronjob` — skill `cronjob` ไม่มีอยู่ในระบบ (ถูก skip ทุกครั้งที่รัน)
  - แก้โดย: `hermes cron set 5f93cf8c0d61 --skill ofa-daily-startup` (หรือ skill อื่นที่เกี่ยวข้อง)
- *(project-notes: ไม่มีงานค้าง — ทุกรายการ status ✅ สำเร็จ)*

## ✅ งานเสร็จล่าสุด 3 รายการ

| วันที่ | หัวข้อ | รายละเอียด |
|--------|--------|------------|
| 2026-05-22 | SP256900082 — Fbt สูตรเร่งสี 1 กก. | Flat Bottom Pouch 50,000 ใบ @10฿ (เซนโค่ย) |
| 2026-05-22 | SP256900081 — Fbt สูตรสมดุล 1 กก. | Flat Bottom Pouch 50,000 ใบ @10฿ (เซนโค่ย) |
| 2026-05-15 | ถุงซิปใส | Facebook post — post_id: `122098309868557706` |
