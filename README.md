## Examination CT519 : Web Personal
 
- **Web site ข้อมูลนักศึกษา** 

- **Features**
   - แสดงชื่อ นามสกุล รหัสนักศึกษา
   - แสดงข้อมูลเกี่ยวกับตนเอง งานอดิเรก กีฬาที่ชอบ
   - แสดงรายละเอียดงานวิจัยที่สนใจ
 

## Installtion

**ก่อนอื่น ขอให้ตรวจสอบว่าในระบบของท่าน ได้ทำการติดตั้ง docker เรียบร้อยแล้ว**
**assume ว่าท่านกำลังอยู่ที่หน้า page ของ Github**

---  

### - เริ่มทำการดึง File จาก git hub
1. กด ปุ่ม code สีเขียว 
2. จะมีหน้าจอ ขนาดเล็ก เปิดขึ้นมา 

![pop](./img/git.png)

3. ใหท่านกดปุ่ม ที่เป็น สี่เหลี่ยมซ้อนกัน (ตามภาพด้านล่าง)

![pop](./img/btn.png)

4. มายังเครื่องคอมฯ ของท่าน
5. ให้ท่านอยู่ที่ folder ที่ท่านต้องการ 
6. ให้ทำการ paste => git clone https://github.com/padeghdev/examct519web.git
7. ระบบจะทำการดึง file ลงมา และเมื่อระบบทำงานเสร็จ ใช้คำสั่ง cd เข้าไปใน folder ชื่อ examct519web
8. ตอนนี้ท่านจะเห็น code ทั้งหมด อยู่ใน folder นี้แล้ว 

### ทำการติดตั้งด้วย docker compose บนเครื่องของท่าน

9. ให้ท่าน อยู่ที่ path เดียวกันกับ file ชื่อ docker-compose.yml
10 ใช้คำสั่ง docker compose up -d --build 
11 ใช้คำสั่ง docker ps เพื่อตรวจสอบว่า มี container ถูกสร้างขึ้นหรือไม่
12 เปิด broswer พิมพ์  url: => http://www.spikyrobotics.com






---




 



