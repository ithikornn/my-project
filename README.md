# CS211-661-Project
> Project ภาคต้น 2566

## Project detail
https://saacsos.notion.site/Project-CS211-2566-1c8e195c0ebd4071aea8f733692e3989?pvs=4

---
## รายชื่อสมาชิก
* #### 6510450151 นาย กฤตภาส วรรณวิไล  reecuteboii, ongreektp
  * #### 16
    * ( a ) &nbsp; ระบบลงทะเบียน (registration) สำหรับผู้ใช้ทั่วไป
      ข้อมูลการลงทะเบียนได้แก่ ชื่อสำหรับเข้าสู่ระบบ (username)
      รหัสผ่าน และการยืนยันรหัสผ่าน ชื่อของผู้ใช้ระบบ
      โดยมีการตรวจสอบ username จะต้องไม่ซ้ำกับผู้ใช้ระบบที่มีอยู่แล้ว
  * #### 21
    * ( a ) &nbsp; หน้าแสดงทีมผู้ร่วมจัดอีเวนต์ และแสดงรายชื่อผู้ร่วมทีมในทีมนั้น ผู้จัดอีเวนต์สามารถระงับสิทธิ์ผู้ร่วมทีมได้ ผู้เข้าร่วมอีเวนต์ที่ถูกระงับสิทธิ์จะไม่เห็น “ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม<ชื่อทีม>”
    * ( d ) &nbsp;  ผู้จัดอีเวนต์กำหนดให้ผู้ร่วมทีม 1 คน เป็นหัวหน้าทีม
      - หัวหน้าทีม มีสิทธิ์ในการดูรายชื่อผู้ร่วมทีม และมีสิทธิ์ระงับสิทธิ์ผู้ร่วมทีมได้
      - หัวหน้าทีม มีสิทธิ์ในหน้าจัดการ (เพิ่มและลบ) “ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม<ชื่อทีม>” ได้เหมือนผู้จัดอีเวนต์
      - สิทธิ์ทั้งสองข้างต้นจะถูกระงับเมื่อผู้จัดอีเวนต์เพิกถอนความเป็นหัวหน้าทีม หรือเปลี่ยนหัวหน้าทีม
  * #### 22
    * ( a ) &nbsp; ผู้เข้าทีม เห็นชื่อทีม และ“ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม<ชื่อทีม>” และสามารถแสดงความคิดเห็นภายในกิจกรรม ซึ่งสมาชิกทุกคนในทีมรวมถึงผู้จัดอีเวนต์สามารถดูความคิดเห็นภายในกิจกรรมและโต้ตอบกันได้

---

* #### 6510450658 นาย ปิ่นปวัฒน์ ลิ้มสุวัฒน์ ppwlsw
  * 16
    * ( b ) &nbsp; ผู้ใช้ระบบสามารถเปลี่ยนรหัสผ่านของตนเองได้ หลังจาก Login โดยต้องระบุ password เดิมที่ถูกต้องด้วย พร้อมระบุรหัสผ่านใหม่ การยืนยันรหัสใหม่ที่ตรงกัน จึงจะเปลี่ยนรหัสผ่านได้ และรหัสผ่านใหม่ต้องใช้ได้
    * ( c ) &nbsp; ผู้ใช้ระบบสามารถเปลี่ยนรูปภาพเพื่อใช้เป็นภาพของผู้ใช้ระบบ หากผู้ใช้ไม่เปลี่ยนหรือยังไม่กำหนดภาพ ระบบจะให้ใช้ภาพ default แทนไปก่อน
  * 19
    * ( a ) &nbsp; ต้องเป็น ”ผู้จัดอีเวนต์” นี้เท่านั้นจึงจะจัดการอีเวนต์นี้ได้
    * ( b ) &nbsp; หน้าแก้ไขข้อมูลอีเวนต์ (ข้อมูลตามข้อ 18a.)
    * ( c ) &nbsp; ส่วนจัดการ “การเปิดรับผู้เข้าร่วมอีเวนต์” (เช่น ผู้ร่วมสัมมนา ผู้เข้าแข่งขัน) โดยระบุจำนวนผู้เข้าร่วมอีเวนต์สูงสุด และช่วงเวลาเริ่มต้น-สิ้นสุดที่จะเปิดรับผู้เข้าร่วมอีเวนต์
    * ( e ) &nbsp; ส่วนจัดการ “การเปิดรับทีมผู้ร่วมจัดอีเวนต์” (เช่น ทีมอาสาสมัคร) โดยระบุชื่อทีม จำนวนผู้ร่วมทีมสูงสุด และช่วงเวลาเริ่มต้น-สิ้นสุดที่จะเปิดรับผู้ร่วมทีม ซึ่งสร้างได้หลายทีม และชื่อทีมต้องไม่ซ้ำกันในอีเวนต์เดียวกัน
  * 20
    * ( d ) &nbsp; ผู้จัดอีเวนต์สามารถเรียงลำดับกิจกรรมในตารางได้ โดยใช้ drag-and-drop และข้อมูลถูกเรียงลำดับใหม่ได้ถูกต้อง

---

* #### 6510451069 นางสาว อภิญญา ตานะประทีปกุล Toon apinya
  * 15
    * ( a ) &nbsp; โปรแกรมต้องไม่มีระบบการสร้างบัญชีสำหรับผู้ดูแลระบบ
      ให้นิสิตระบุ username และ password ของผู้ดูแลระบบในไฟล์ pdf (ข้อ 9b)
    * ( b ) &nbsp; ผู้ดูแลระบบสามารถเปลี่ยนรหัสผ่านของตนเองได้ หลังจาก Login โดยต้องระบุ password เดิมที่ถูกต้องด้วย พร้อมระบุรหัสผ่านใหม่ การยืนยันรหัสใหม่ที่ตรงกัน จึงจะเปลี่ยนรหัสผ่านได้ และรหัสผ่านใหม่ต้องใช้ได้
    * ( c ) &nbsp; หน้าแสดงรายชื่อของผู้ใช้ระบบ โดยต้องแสดงภาพของผู้ใช้ ชื่อสำหรับเข้าสู่ระบบ (username) ชื่อผู้ใช้ระบบ และวันเวลาที่เข้าใช้ล่าสุดของผู้ใช้ระบบ เรียงลำดับตามวันเวลาที่เข้าใช้ระบบล่าสุดก่อน
  * 17
    * ( b ) &nbsp; หน้าแสดงประวัติรายการอีเวนต์ที่ตนเองเข้าร่วม โดยแยกอีเวนต์ที่อยู่ระหว่างการจัดงาน และอีเวนต์ที่สิ้นสุดแล้ว
  * 20
    * ( a ) &nbsp; หน้าแสดงรายชื่อผู้เข้าร่วมอีเวนต์ ผู้จัดอีเวนต์สามารถระงับสิทธิ์ผู้เข้าร่วมอีเวนต์ได้ ผู้เข้าร่วมอีเวนต์ที่ถูกระงับสิทธิ์จะไม่เห็น “ตารางกิจกรรมของอีเวนต์สำหรับผู้เข้าร่วมอีเวนต์”
  * 21
    * ( b ) &nbsp; หน้าแสดง และหน้าจัดการ (เพิ่มและลบ) “ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม<ชื่อทีม>” (แต่ละทีมมีตารางกิจกรรมแตกต่างกัน) โดยระบุข้อมูลต่อไปนี้
      - ชื่อกิจกรรม
      - รายละเอียดกิจกรรม
    * ( e ) &nbsp;ผู้จัดอีเวนต์กำหนดได้ว่า กิจกรรมใดเสร็จสิ้นไปแล้ว
      - กิจกรรมที่เสร็จสิ้นแล้วต้องแสดงให้เห็นชัดเจนว่าเสร็จสิ้นแล้วใน “ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม<ชื่อทีม>”

---

* #### 6510451069 นาย อิทธิกร อึงนิยม tent
  * 17
    * ( a ) &nbsp; หน้าแสดงรายการอีเวนต์ที่อยู่ระหว่างการจัดงานทั้งหมดให้ผู้ใช้ทั่วไปดู โดยแสดงภาพอีเวนต์ ชื่ออีเวนต์ และจำนวนที่ว่างเหลือสำหรับเข้าร่วมอีเวนต์
    * ( c ) &nbsp; ส่วนให้ค้นหาอีเวนต์ด้วยบางส่วนของชื่ออีเวนต์
    * ( d ) &nbsp; หน้าแสดงรายละเอียดของอีเวนต์ที่ผู้ใช้เลือกจากข้อ 17a. แสดงรายละเอียดที่เหมาะสม และผู้ใช้สามารถเข้าร่วมอีเวนต์ได้หากมีที่ว่างเหลืออยู่ (หากไม่มีที่ว่างเหลือต้องไม่ให้เข้าร่วม)
      - หากเข้าร่วมอีเวนต์แล้ว ให้แสดง “ตารางกิจกรรมของอีเวนต์”
  * 18
    * ( a ) &nbsp; ส่วนให้ผู้ใช้ทั่วไปสร้างอีเวนต์ เพื่อเป็น “ผู้จัดอีเวนต์” โดยต้องระบุข้อมูลต่อไปนี้
      - ชื่ออีเวนต์
      - ภาพอีเวนต์
      - รายละเอียดของอีเวนต์
      - วันที่เวลาที่เริ่มอีเวนต์
      - วันเวลาที่สิ้นสุดอีเวนต์
    * ( b ) &nbsp; หน้าแสดงรายการอีเวนต์ที่ตนเองเป็นผู้จัดอีเวนต์ ซึ่งสามารถแสดงหน้าจัดการอีเวนต์ได้
  * 20
    * ( c ) &nbsp; หน้าแสดง และหน้าจัดการ (เพิ่มและลบ) “ตารางกิจกรรมของอีเวนต์สำหรับผู้เข้าร่วมอีเวนต์” โดยระบุข้อมูลต่อไปนี้
      - เวลาเริ่มต้น-สิ้นสุดของกิจกรรม
      - ชื่อกิจกรรม
      - รายละเอียดกิจกรรม
  * 21
    * ( e ) &nbsp; ผู้จัดอีเวนต์ กำหนดให้ผู้ร่วมทีมจัดอีเวนต์ เป็นสมาชิกของทีมได้มากกว่า 1 ทีม ในอีเวนต์ตนเอง

---
## วิธีการติดตั้งหรือรันโปรแกรม

---

เข้าไปที่ github repository นี้

    https://github.com/CS211-661/cs211-661-project-tri-o.git

จะสังเกตุเห็น tag ให้กดเข้าไป และเลือก **release 3.0.0** 
ให้ Dowload ไฟล์ที่ชื่อ

    tri-o.zip

เมื่อทำการดาวน์โหลดเสร็จสิ้น ให้ทำการ Extract หรือ แตกไฟล์ tri-o.zip 
และภายในโฟลเดอร์ tri-o จะประกอบไปด้วย

    Windows
    macOS
    --------
    uml
    README.md

ให้เลือกโฟลเดอร์ตามระบบปฎิบัติการของท่าน
### **สำหรับ macOS**

ให้ทำการคลิกขวาที่โฟลเดอร์ macOS ---> copy
และเปิด terminal ขึ้นมาแล้วพิมพ์คำสั่ง
    
    cd เว้นวรรคตามด้วย cmd+v หรือ คลิกขวา->paste แล้วกด enter
    ตัวอย่างคำสั่ง
    cd /Users/ppwlsw/Downloads/tri-o/macOS 

จากนั้นให้พิมพ์คำสั่ง

    java -jar tri-o-1.0.0-shaded.jar

แล้วหน้าต่างโปรแกรมจะแสดงขึ้น

---

### สำหรับ Windows

ให้ทำการเข้าไปในโฟลเดอร์ Windows <br /> วิธีที่ 1 . คลิกขวา -> เลือก Git Bash Here
จากนั้นให้พิมพ์คำสั่ง

    java -jar tri-o-1.0.0-shaded.jar

วิธีที่ 2 ทำการ Double-Click ที่ไฟล์ 
    
    tri-o-1.0.0-shaded.jar

ได้เลย

แล้วหน้าต่างโปรแกรมจะแสดงขึ้น

---



## การวางโครงสร้างไฟล์
<br />

* data 
&emsp;&emsp;  ข้อมูลที่ถูกเก็บไว้ใน directory data นี้จะเป็นไฟล์นามสกุล .csv ซึ่งจะเก็บข้อมูลของโปรแกรมที่สำคัญต่างๆ โดยภายในนั้นจะประกอบไปด้วย <br />
&emsp;&emsp; - comment-list.csv ในไฟล์นี้จะเก็บประวัติการสื่อสารภายในทีม<br />
&emsp;&emsp; - event-list.csv ในไฟล์นี้จะเก็บข้อมูลที่สำคัญของอีเวนต์<br />
&emsp;&emsp; - participant-list.csv ในไฟล์นี้จะเก็บข้อมูลของผู้เข้าร่วมอีเวนต์<br />
&emsp;&emsp; - schedule-list.csv ในไฟล์นี้จะเก็บข้อมูลกิจกรรมสำหรับผู้เข้าร่วมอีเวนต์<br />
&emsp;&emsp; - team-list.csv ในไฟล์นี้จะเก็บข้อมูลของทีมในอีเวนต์<br />
&emsp;&emsp; - team-schedule-list.csv ในไฟล์นี้จะเก็บข้อมูลกิจกรรมของแต่ละทีมในอีเวนต์<br />
&emsp;&emsp; - user-list.csv ในไฟล์นี้จะเก็บข้อมูลที่สำคัญของผู้ใช้<br />
&emsp;&emsp; - volunteer-list.csv ในไฟล์นี้จะเก็บข้อมูลผู้ใช้ที่เข้าร่วมทีมในแต่ละอีเวนต์<br />
* images<br />
&emsp;	- images จะเก็บรูปภาพทั้งหมดในโปรแกรม เช่น รูปของผู้ใช้ , รูปของอีเวนต์ เป็นต้น<br />

* src
  - main
    - java
      - cs211
          - project<br />
            - controllers<br />  &emsp;	- ในส่วนของ controllers จะมีเก็บไฟล์ที่เป็น controller ของหน้าต่างๆโดยทำหน้าที่เป็นตัวกลางในการเชื่อมต่อระหว่าง Model และ View(ไฟล์ fxml) นั้นๆ <br /> &emsp; - ทำหน้าที่คำนวณหรือประมวลผลตรรกะต่างๆของโปรแกรม
            -  cs211661project<br /> &emsp; - ใน cs211661project จะเก็บคลาส HelloApplication ซึ่งจะเป็นคลาสตัวกลางในการรับส่งข้อมูล และ เปลี่ยนการแสดงผล ระหว่างหน้า
              -  models <br /> &emsp; - ในส่วนของ models จะเก็บ model ต่างๆของโปรแกรม
                - collections <br /> &emsp; - ใน collections จะทำหน้าที่เป็น collection ในการเก็บข้อมูล object ของ model ต่างๆในรูปแบบ Dynamic
            - sevices <br /> &emsp; - ส่วนของ sevice จะเก็บคลาสที่เป็นตัวช่วยต่างๆในการเขียนโค้ด เช่น Regex เป็นคลาสเช็ค format การเช็คเวลา, FXRouter เป็นคลาสช่วยในการส่งผ่านข้อมูล และ การอ่าน - เขียนไฟล์ เป็นต้น
            - Main <br /> &emsp; - คลาส Main เป็น
          - module-info.java 
    - resources
      - cs211
        - project
          - views <br /> &emsp; - ใน views จะเป็นการเก็บไฟล์ต่างๆ ที่เกี่ยวกับ user interface ของตัวโปรแกรม ซึ่งไฟล์นามสกุลคือ
                                           .fxml 
      - design <br /> &emsp; - ใน design จะเก็บที่ซึ่งก็เกี่ยวข้องกับ user interface ให้ความสวยงามแก่ตัวโปรแกรม แต่นามสกุลคือ .css 
      - images <br /> &emsp; - ใน images จะเก็บรูปภาพของผู้สร้าง และ ภาพพื้นหลังของหน้าหลักของโปรแกรม และ หน้า Register
* umls
  * ในโฟลเดอร์ uml นี้จะเก็บ UML Diagram ของ Models , Controllers , Services ต่างๆในโปรแกรมนี้
* README.md
* trio_o_guidebook.pdf
  * ไฟล์ pdf คู่มือการใช้งานโปรแกรมอย่างละเอียดพร้อมมีประกอบ

---
## ตัวอย่างข้อมูลผู้ใช้ระบบ
  
  - บัญชี ผู้ดูแลระบบ(Admin) **ซึ่งไม่สามารถสมัครได้**
    - Username : admin
    - Password : 123


  - บัญชีผู้ใช้ทั่วไป (Common User)
    - Username : aofpx
    - Password : pojanineiei

  
  - บัญชีที่ถูกระงับจากโปรแกรม (Banned User)
    - Username : sheryohm
    - Password : ohm2003


 - บัญชี ผู้สร้างอีเวนต์
    - Username : ithikornn
    - Password : tent2547
    - ชื่อ Event ที่สร้าง : Taylor Swift the eras tour , OCTOPOP 2023
   

  - บัญชีที่ถูกระงับจาก Event
    - Username : auero7
    - Password : eurocake
    - ชื่อ Event ที่ถูกระงับ : Taylor Swift the eras tour


  - บัญชีที่เป็นหัวหน้าทีม 
    - Username : _25171
    - Password : pangpangpang
    - ชื่อ Event : Taylor Swift the eras tour
    - Team ที่เป็นหัวหน้า : a-team


  - บัญชีที่เป็นสมาชิกของทีม
    - Username : nammeyyy
    - Password : nutpanam03
    - ชื่อ Event : Taylor Swift the eras tour
    - Team : a-team

  - บัญชีที่ถูกระงับจากทีม
    - Username : nt_pariphat
    - Password : pariphat2546
    - ชื่อ Event : Taylor Swift the eras tour
    - Team : a-team





---
## สรุปสิ่งที่พัฒนาแต่ละครั้งที่นำเสนอความก้าวหน้าของระบบ
* ### ครั้งที่ 1 (11 สิงหาคม 2566)
  * ออกแบบ model, หน้าต่างโปรแกรมและวางแผนการพัฒนาองค์ประกอบของโปรแกรม (ทุกคน)
  * นำเสนอการวางแผนและรูปแบบการเก็บข้อมูลในแต่ละส่วนตาม features ที่ได้รับตามที่แบ่งหัวข้อ (ทุกคน)
  * นำเสนอรูปแบบโปรแกรมเบื้องต้นต่ออาจารย์ที่ปรึกษา

---
* ### ครั้งที่ 2 (1 กันยายน 2566)
  * กฤตภาส วรรณวิไล (ระบบ Login, Register)
  * ปิ่นปวัฒน์ ลิ้มสุวัฒน์ (ส่วนของ User , ใช้ระบบ Bcrypt รหัสผ่าน, เก็บเวลา Login)
  * อิทธิกร อึงนิยม (ระบบ Event และ รับ-ส่งข้อมูลในแต่ละหน้า)
  * อภิญญา ตานะประทีปกุล (ระบบ Admin)


---

* ### ครั้งที่ 3 (22 กันยายน 2566)
  * กฤตภาส วรรณวิไล (ตกแต่งหน้า Login, Register, ระบบแต่งตั้งหัวหน้าทีม )
  * ปิ่นปวัฒน์ ลิ้มสุวัฒน์ (ระบบแก้ไขข้อมูล User ,ระบบสร้างและเข้าร่วม Team, ปรับปรุงระบบ Login, ระบบ Drag-and-Drop เรียงลำดับกิจกรรม, ระบบ Event(แก้ไขอีเวนต์) และปรับปรุงระบบ การเข้าร่วมอีเวนต์ )
  * อิทธิกร อึงนิยม (ระบบแก้ไขข้อมูล Event, เปลี่ยนการส่งข้อมูลเป็นรูปแบบ HashMap, ระบบ Participant หรือ ผู้เข้าร่วมอีเวนต์, สร้างโมเดล Regex เพื่อเช็ค format ของเวลา, ระบบ Shedule ของผู้เข้าร่วม)
  * อภิญญา ตานะประทีปกุล (ระบบแสดงอีเวนต์ที่เข้าร่วมที่ยังดำเนินการอยู่/สิ้นสุดไปแล้ว , แสดงชื่อและสถานะผู้เข้าร่วมทั้งหมดในอีเวนต์, ปรับปรุงระบบ Admin,ระบบ Shedule ของแต่ละทีม,)
  * ระบบ Shedule (ตารางกิจกรรมของอีเวนต์) ทั้งของ ผู้เข้าร่วม(Participator) และ สำหรับทีม(Team)


---

* ### ครั้งเสร็จสมบูรณ์ (13 ตุลาคม 2566)
    * กฤตภาส วรรณวิไล (ตกแต่งโปรแกรมเพิ่มเติม)
    * ปิ่นปวัฒน์ ลิ้มสุวัฒน์ (เขียน README , แก้ bug ในระบบแก้ไขอีเวนต์)
    * อิทธิกร อึงนิยม (ทำความสะอาดโค้ดที่ไม่ได้ใช้ และ ลบคอมเมนต์, ทดสอบรันโปรแกรม)
    * อภิญญา ตานะประทีปกุล (เขียนคู่มือของโปรแกรม)