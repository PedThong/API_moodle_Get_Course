# 🎡 Moodle Carousel

โปรเจกต์นี้จัดทำขึ้นเพื่อปรับปรุงหน้าตาและประสบการณ์ผู้ใช้ของระบบ **Moodle** ที่เรารัก ❤️ โดยมีเป้าหมายหลัก:

1. เพื่อโปรโมท/โชว์คอร์สใหม่ ๆ ที่เพิ่มเข้ามาในระบบ
2. ทำให้ผู้ใช้งานเข้าถึงเนื้อหาหลักของเว็บไซต์ได้ง่ายขึ้น

---

## 📁 โครงสร้างไฟล์


> image 
|- Carosal_course.html
|- header.html
|- new_carousal.html



---

### 🖼️ image/

โฟลเดอร์นี้ใช้เก็บ **ภาพสำรอง (fallback)** สำหรับกรณีที่ไม่สามารถโหลดภาพจาก API ได้  
ระบบจะสุ่มแสดงภาพจากโฟลเดอร์นี้แทน

---

### 🗂️ Carosal_course.html & header.html

เป็น **โค้ดเวอร์ชันเก่า** ที่ยังไม่ใช้งานแล้ว  
แต่ยังสามารถนำไป **ปรับปรุง / นำบางส่วนมาใช้ในอนาคตได้**

---

### ✅ new_carousal.html

คือ **ไฟล์หลักที่ใช้อยู่ในปัจจุบัน**  
มีระบบ **Carousel Slide** ที่โหลดข้อมูลจาก API และมี **Navbar แบบโต้ตอบ**

---

## ⚙️ วิธีฝังใช้งานใน Moodle

1. เปิด **Edit mode** ในหน้า Moodle
2. คลิกฟันเฟืองของ Section → เลือก `Edit summary`
3. คลิกปุ่ม **Show more buttons**
4. คลิกที่ปุ่ม `</>` (HTML Mode)
5. แปะโค้ดนี้ลงไป:

```html
<div style="width: 100%; height:790px; overflow: hidden;  background: #f8f9fa; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;">
  <iframe src="https://PedThong.github.io/API_moodle_Get_Course/new_carousal.html"
          title="PR Courses"
          loading="lazy"
          scrolling="no"
          style="width: 100%; height: 100%; border: none; overflow: hidden;">
  </iframe>
</div>
```

ตรงนี้สามารถปรับขนาดได้รวมถึงเรียก File อื่นๆ จากใน github ได้ ***เมื่อแก้ไขใน github ผลลัพธ์จะไม่แสดงผลทันที รอประมาณ 5-10 นาที***





