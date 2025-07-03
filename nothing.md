# Moodle Carousal 

github จัดทำขึ้นเพื่อปรับปรุง Website moodle ที่เรารัก โดยมี requiment และเป้าหมายหลักดังนี้ 
1. เพื่อโปรโหมทโชว์ Course ใหม่ๆที่เพิ่งเข้ามา
2. ทำให้ง่ายต่อการเข้าถึง ทุกคนสามารถเข้าใจ และเข้าถึงเมนูต่างๆ ได้ง่าย

โค้ดจะมีทั้งหมด 3 ไฟล์ และ 1 โฟลเดอร์

'''
> image 
|- Carosal_course.html
|- header.html
|- new_carousal.html
'''

### Image Floder 
เป็นโฟลเดอร์เก็บรูปภาพ สำหรับกรณีที่ไม่สามารถดาวน์โหลดรูปจาก API ได้ ระบบจะแสดงรูปเหล่านี้แทนในรูปแบบสุ่ม

### Carosal_course.html & header.html
เป็นโค้ดเก่าที่ไม่ได้ใช้งานแล้ว แต่ยังสามารถปรับปรุงเพื่อใช้ในส่วนอื่นๆได้

### new_carousal.html
เป็น Code ที่ใช้อยู่ ณ ปัจจุบัน มีระบบ Carousal และ Navbar


## วิธีการใช้งาน Code จาก github ใน moodle
เราจะเรียกใช้งานผ่าน HTML block ใน moodle โดยสามารถหาได้จาก

หลังจากเปิด Edit mode > ฟันเฟือง > sumary > show more bottons > "</>" (HTML)

'''
<div style="width: 100%; height:790px; overflow: hidden;  background: #f8f9fa; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;">
    <iframe src="https://PedThong.github.io/API_moodle_Get_Course/new_carousal.html" title="PR Courses" loading="lazy" scrolling="no" style="width: 100%; height: 100%; border: none; overflow: hidden;">
    </iframe>
</div>
'''

ตรงนี้สามารถปรับขนาดได้รวมถึงเรียก File อื่นๆ จากใน github ได้ ***เมื่อแก้ไขใน github ผลลัพธ์จะไม่แสดงผลทันที รอประมาณ 5-10 นาที***





