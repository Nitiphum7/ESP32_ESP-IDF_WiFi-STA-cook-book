# แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- เลือกโปรเจค Wi-Fi Station Example จาก show examples แล้วกด create
![Screenshot 2024-10-28 210423](https://github.com/user-attachments/assets/5c10fb92-2811-4934-8f5f-04c6e6b33039)


## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- ### แก้ไขที่ idf.py menuconfig  ไปที่ example config ตั้งค่ารหัส wifi
![Screenshot 2024-10-28 211647](https://github.com/user-attachments/assets/32ee75e8-6f1f-409e-8ed3-8f0a863ec1ea)


## 3. แสดงขั้นตอนการทำ project
- แก้ไข เพิ่มข้อมูลรหัส wifi ที่  example config กด save แล้วกด build 
### หน้าตอนเชื่อม wifi ไม่สำเร็จ
![Screenshot 2024-10-28 211647](https://github.com/user-attachments/assets/32ee75e8-6f1f-409e-8ed3-8f0a863ec1ea)

- หากไม่สำเร็จให้กด full clean ล้างข้อมูลทั้งหมดแล้วทำใหม่ตรวจเช็คข้อมูลว่ากรอกถูกต้องไหม

## 4. แสดงผลการทำ project
- ### หน้าตอนเชื่อม wifi สำเร็จ

![Screenshot 2024-10-28 211308](https://github.com/user-attachments/assets/8a2a9744-1627-4127-9422-e870e92b85c6)

## 5. สรุปผลการทำ project 
- ### โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
