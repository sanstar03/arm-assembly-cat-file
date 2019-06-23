second assignment of Computer Organization and Assembly Language
โจทย์
1. cat like สร้างโปรแกรมคล้าย Cat ใน Unix 
-รับชื่อไฟล์เป็น parameter หนึ่งไฟล์และนำข้อมูลมาแสดงผลขึ้นบรรทัดใหม่เมื่อเจอ \n
- สามารถรับ option เป็น parameter
- มี option –c โดยหากไม่เลือก option นี้ ในการแสดงผลจะแสดงผลทุกตัวอักษร หากเลือก –c
จะแสดงผลเฉพาะตัวอักษรที่แสดงผลได้ (ไม่รวม control character)
- มี option –b นับจํานวนบรรทัด ยกเว้นบรรทัดว่าง (เลขบรรทัดจะอยู่ด้านหน้า)
- มี option –t เมื่อเจออักษร Tab ให้จัดตัวอักษรให้ตรงกับ Tab
- มี option –s โดยเมื่อแสดงผลครบ 25 บรรทัด ให้หยุดรอ 
