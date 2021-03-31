# การทดลองที่ 7 
## วัตถุประสงค์
1. เพื่อนำการทดลองที่ 4 เรื่องการเขียนโปรแกรมอินพุทสัญญาณดิจิทัลมาต่อยอดเพื่อพัฒนาโปรแกรม
2. เพื่อให้นักศึกษามีทักษะความคิดสร้างสรรค์ในการเขียนโปรแกรมมากขึ้น
## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรเลอร์ ชนิดESP_01
2. USB to serial port
3. อุปกรณ์ต่อพ่วงUSB
4. อุปกรณ์ที่ป้อนข้อมูลเข้าไมโครคอนโทรเลอร์ เช่นคอมพิวเตอร์
5. อะแดปเตอร์ ต่อ พอร์ต0และ1 แสดงผลเป็นLED 0 ขาว 1 เหลือง
6. เซนเซอร์แสงกับตัวต้านทาน
## ศึกษาข้อมูลเพิ่มเติม
* [ทำความรู้จัก ไมโครคอนโทรเลอร์ ESP_01](https://docs.platformio.org/en/latest/boards/espressif8266/esp01.html)
* [วีดีโอการทดลองแลป4](https://www.youtube.com/watch?v=nFqoZT26U5k)
* [ตัวอย่างโปรแกรมที่4](https://github.com/choompol-boonmee/lab63b/tree/master/examples/04_Input-Port)
## วิธีการทำการทดลอง
1. ต่อ USB to serial port เข้ากับอแดปเตอร์พอร์ต0และ1 และ ไมโครคอนโทรเลอร์ และคอมพิวเตอร์เข้าด้วยกันดังภาพด้านขวา![image](https://user-images.githubusercontent.com/80879365/112296432-7d176d80-8cc7-11eb-8ec1-c189472eef10.png)
2. เปิด command prompt ใช้คำสั่งเปิดตัวอย่าง `cd pattani` ตามด้วย `cd 04_Input-Port`
3. ดูเนื้อหาโปรแกรมได้ด้วยคำสั่ง `src/main.cpp`![image](https://user-images.githubusercontent.com/80879365/112296920-daabba00-8cc7-11eb-91d9-6fd8ab662ea5.png)
4. อัพโหลดโปรแกรมตัวอย่างลงไมโครคอนโทรเลอร์ ด้วยคำสั่ง `pio run-t upload`![image](https://user-images.githubusercontent.com/80879365/112297051-ffa02d00-8cc7-11eb-8c9e-d8db657e31eb.png)
5. เมื่อโปรแกรมกำลังรันให้กดปุ่มอัปโหลด สีดำที่บอร์ดค้างไว้ แล้วกดปุ่มสีแดงหนึ่งครั้งเพิ่อรีเซต![image](https://user-images.githubusercontent.com/80879365/112297180-25c5cd00-8cc8-11eb-9424-19df25f9c8d2.png)
6. รอจนกระทั่งรันโปรแกรมจบแล้ว ใช้คำสั่ง `pio device momitor` เพื่อดูผลผ่านคอมพิวเตอร์![image](https://user-images.githubusercontent.com/80879365/112297299-4c840380-8cc8-11eb-9c0d-9af4e28864e3.png)
7. นำสายไฟเส้นinputสีขาว ไปเสียบที่ขั้วสายสีดำ สังเกตที่หลอดไฟLED
8. นำสายไฟเส้นinputสีขาว ไปเสียบที่ขั้วสายสีแดง สังเกตที่หลอดไฟLED
9. ลองกดปุ่มสีดำ สังเกตที่หลอดไฟLED
10. ปิดหน้าสัมผัสเซนเอร์แสง สังเกตที่หลอดไฟLED
## การบันทึกผลการทดลอง
* นำสายไฟเส้นinputสีขาว ไปเสียบที่ขั้วสายสีดำ บันทึกผลได้ดังนี้ ![image](https://user-images.githubusercontent.com/80879365/112297709-ccaa6900-8cc8-11eb-9818-f4339d59ae6d.png)
* นำสายไฟเส้นinputสีขาว ไปเสียบที่ขั้วสายสีแดง ![image](https://user-images.githubusercontent.com/80879365/112298069-30349680-8cc9-11eb-9378-a336f8cdc263.png)
* กดปุ่มสีดำได้ผลดังนี้ ![image](https://user-images.githubusercontent.com/80879365/112297970-15622200-8cc9-11eb-95f1-c52f483d063a.png)
* เปิดหน้าสัมผัสเซนเอร์แสง![image](https://user-images.githubusercontent.com/80879365/112300267-3b88c180-8ccb-11eb-8b6e-2237d821de3c.png)
* ปิดหน้าสัมผัสเซนเอร์แสง![image](https://user-images.githubusercontent.com/80879365/112300457-768af500-8ccb-11eb-9e4e-e2b47ba15a41.png)
## อภิปรายผลการทดลอง
*
## คำถามหลังการทดลอง
* 
* 



  
                
          
            
