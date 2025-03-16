# TestGuy Repository 🚀

เว็บไซต์ทดสอบสำหรับการเรียนรู้และพัฒนา

## 📁 โครงสร้างโปรเจค

```
testguy/
├── guy.html         # หน้าเว็บทดสอบที่ 1
├── hello.html       # หน้าเว็บทดสอบที่ 2
├── pointtohtml.txt  # การตั้งค่า Nginx configuration
└── .gitattributes   # การกำหนดค่า Git attributes
```

2. สำหรับการตั้งค่า Nginx server:
- ทำตามคำแนะนำใน `pointtohtml.txt`
- ตั้งค่า virtual host และ directory paths ตามที่ระบุ

## 📝 รายละเอียด

- **guy.html**: หน้าเว็บแสดงข้อความทักทายและชื่อ Kainapat
- **hello.html**: หน้าเว็บแสดงข้อความทักทายและชื่อ Prachinburi
- **pointtohtml.txt**: ไฟล์คำแนะนำสำหรับการตั้งค่า Nginx server รวมถึง:
  - การกำหนด server blocks
  - การตั้งค่า locations
  - การจัดการ error pages