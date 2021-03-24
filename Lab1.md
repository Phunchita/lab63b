# การทดลองที่ 1 เรื่อง การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์
## วัตถุประสงค์
1. เพื่อให้นักศึกษาเข้าใจวิธีการเขียนโปรแกรมด้วยplatform io
2. นักศึกษาสามารถนำโปรแกรมที่เขียนได้ไปรันลงไมโครคอนโทลเลอร์ได้
## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรเลอร์ ชนิดESP_01![image](https://user-images.githubusercontent.com/80879365/112280582-bea01c80-8cb7-11eb-9b7c-48a2639f3094.png)
2. USB to serial port
3. อุปกรณ์ต่อพ่วงUSB
4. อุปกรที่ป้อนข้อมูลเข้าไมโครคอนโทรเลอร์ เช่นคอมพิวเตอร์
## ศึกษาข้อมูลเพิ่มเติม
* [ทำความรู้จัก ไมโครคอนโทรเลอร์ ESP_01](https://docs.platformio.org/en/latest/boards/espressif8266/esp01.html)
* [วีดีโอการทดลองแลป1](https://youtu.be/NLIUsWLEpmg)
* [ตัวอย่างโปรแกรมที่1](https://github.com/choompol-boonmee/lab63b/tree/master/examples/01_Serial-Monitor)
## วิธีการทำการทดลอง
1. ต่อ USB to serial port เข้ากับไมโครคอนโทรเลอร์ และคอมพิวเตอร์เข้าด้วยกัน ![image](https://user-images.githubusercontent.com/80879365/112276336-328bf600-8cb3-11eb-8958-5ffa2a7543dd.png)
3. เปิด command prompt ใช้คำสั่งเปิดตัวอย่าง `cd pattani` ตามด้วย `cd 01_Serial_monitor`
4. อัพโหลดโปรแกรมตัวอย่างลงไมโครคอนโทรเลอร์ ด้วยคำสั่ง `pio run-t upload`![image](https://user-images.githubusercontent.com/80879365/112276666-94e4f680-8cb3-11eb-8353-9a8ad3127086.png)
6. เมื่อโปรแกรมกำลังรันให้กดปุ่มสีดำที่บอร์ดค้างไว้ แล้วกดปุ่มสีแดงหนึ่งครั้งเพิ่อรีเซต ![image](https://user-images.githubusercontent.com/80879365/112276796-b3e38880-8cb3-11eb-86f2-186eb7d8e4ae.png)
7. รอจนกระทั่งรันโปรแกรมจบแล้ว ใช้คำสั่ง `pio device momitor` เพื่อดูผลผ่านคอมพิวเตอร์![image](https://user-images.githubusercontent.com/80879365/112276947-d5447480-8cb3-11eb-9a18-131f6c3e24d1.png)
## การบันทึกผลการทดลอง
ผลที่แสดงขึ้นในจอคอมพิวเตอร์ทุกๆวินาทีจะออกมาเป็นตัวเลขที่นับเพิ่มทีละหนึ่งไปเรื่อยๆดังรูป![image](https://user-images.githubusercontent.com/80879365/112277188-12106b80-8cb4-11eb-84c3-3af658333aa0.png)
## อภิปรายผลการทดลอง
จากการทดลอง แสดงให้เห็นว่าplatform io ตัวอย่างที่1 Serial_monitor ที่เราเขียนลงไปในไมโครคอนโทรเลอร์นั้น ทำให้ไมโครคอนโทรเลอร์ควบคุมให้แสดงผลการนับเลขเพิ่มขึ้นทีละ1 ไปเรื่อยๆ
## คำถามหลังการทดลอง
