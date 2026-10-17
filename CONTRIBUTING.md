# แนวทางร่วมพัฒนา (Contributing)

ขอบคุณที่สนใจร่วมพัฒนาโปรเจกต์ของ Saharat Labs 🎉

## ก่อนเริ่ม

1. อ่าน [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
2. ค้นดู Issues/Discussions เก่าก่อน ว่ามีคนเสนอเรื่องนี้แล้วหรือยัง

## การรายงานบั๊ก

- เปิด Issue ด้วยเทมเพลต **Bug report**
- ระบุ: สิ่งที่ทำ, สิ่งที่คาดหวัง, สิ่งที่เกิดขึ้นจริง, ขั้นตอนทำซ้ำ, สภาพแวดล้อม

## การเสนอฟีเจอร์

- เปิด Discussion หมวด **Ideas** หรือ Issue ด้วยเทมเพลต **Feature request**
- อธิบายปัญหา/ประโยชน์ มากกว่าแค่ชื่อฟีเจอร์

## ขั้นตอนส่งโค้ด (Pull Request)

```bash
git checkout main && git pull
git checkout -b feat/ชื่อสั้น ๆ

# แก้โค้ด + ทดสอบ
git add -A
git commit -m "feat: อธิบายสั้น ๆ"
git push -u origin feat/ชื่อสั้น ๆ
gh pr create --fill
```

## รูปแบบ commit (Conventional Commits)

`feat:` ฟีเจอร์ใหม่ · `fix:` แก้บั๊ก · `docs:` เอกสาร · `refactor:` ปรับโครงสร้าง
· `test:` เทสต์ · `chore:` งานจิปาถะ

## มาตรฐานโค้ด

- อ่านง่าย > ฉลาด
- ตั้งชื่อสื่อความหมาย
- เพิ่มคอมเมนต์เฉพาะจุดที่ซับซ้อน
- ทดสอบให้ผ่านก่อนเปิด PR

## ภาษา

สื่อสารภาษาไทยหรืออังกฤษได้ทั้งคู่
