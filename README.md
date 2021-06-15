# หาเพื่อนร่วมทีม Opendream 2021

[โอเพ่นดรีม][1] กำลังหา developer มาเป็นเพื่อนร่วมทีม โจทย์ทดสอบนี้หวังว่าจะทำให้เรารู้จักฝีมือกันมากขึ้น

# ลักษณะโจทย์

โจทย์จะมีทั้งหมด 3 ข้อ ดังนี้
## 01 - FizzBuzz

เขียนโปรแกรมที่รับ `input` เป็นชุดตัวเลข `1` ถึง `100` และแสดง `output` ตามเงื่อนไขดังนี้
- ถ้า `input` หารด้วย 3 ลงตัว แสดง `output` เป็น `Fizz`
- ถ้า `input` หารด้วย 5 ลงตัว แสดง `output` เป็น `Buzz`
- ถ้า `input` หารด้วย 3 และ 5 ลงตัว แสดง `output` เป็น `FizzBuzz`
- ถ้า `input` ไม่อยู่ในเงื่อนไขข้างต้น แสดง `output` เป็น `input`
## 02 - หาคู่ตัวเลข

กำหนดให้ array `N` เป็น `input` ที่บรรรจุตัวเลข `1` ถึง `100` 
- ให้เขียนโปรแกรมหาคู่ตัวเลขทั้งหมดใน `N` ที่ `บวก` กันแล้วได้ผลลัพธ์เป็น _จำนวนเฉพาะ_
- ให้เขียนโปรแกรมหาคู่ตัวเลขทั้งหมดใน `N` ที่ `ลบ` กันแล้วได้ผลลัพธ์เป็น _จำนวนเฉพาะ_

## 03 - Front-end API Rendering

เขียน front-end ให้ดูแล้ว `สวยงาม` โดยมีข้อกำหนดดังนี้
- Request `JSON` จาก API: https://jsonplaceholder.typicode.com/posts โดยเนื้อหาประกอบไปด้วย field ดังนี้
  - `userId`
  - `id`
  - `title`
  - `body`
- แสดงผลด้วย React หรือ Vue.js โดยมีข้อกำหนดเบื้องต้นดังนี้
  - แสดง pagination ของผลลัพธ์ทุกๆ 20 ผลลัพธ์
  - User สามารถเรียงลำดับผลลัพธ์ตาม `userId` หรือ `id` ได้ด้วยตัวเอง การเรียงลำดับให้ทำที่ client-side
  - แสดงผลแบบ responsive ได้

# เงื่อนไขการทำโจทย์

ณ วันที่ 15 มิถุนายน 2564 ผู้ทำโจทย์ สามารถเลือกทำโจทย์ด้วยภาษาโปรแกรมหรือเครื่องมือที่ตนเองถนัดได้ดังนี้

- โจทย์ที่ `01` และ `02` ใช้ภาษา `PHP` หรือ `Python`
- โจทย์ที่ `03` ใช้ `React` หรือ `Vue.js`

ผู้ทำโจทย์สามารถเลือกส่งโจทย์ได้ดังนี้
- โจทย์ที่ `01` และ `02`
- โจทย์ที่ `03`
- โจทย์ที่ `01`, `02` และ `03` - **ผู้เลือกทำเงื่อนไขนี้ จะได้รับการพิจารณาเป็นพิเศษ**
# วิธีส่งโจทย์

1. Fork repository นี้ไปยัง account Github ของตัวเอง
2. สร้าง directory เป็น `ชื่อ account Github` ของตัวเอง เช่น `kengggg` ไว้ใน `/solutions`
3. ตั้งชื่อไฟล์ตามลำดับโจทย์ เช่น `01.py`, `02.php` และ `03.html`
4. สร้าง [Pull Request][2] มาที่ branch `main` ของ repository นี้
5. เมื่อทีมโอเพ่นดรีมได้รับแจ้ง Pull Request จะทำการ review เพื่อทำการดำเนินการสัมภาษณ์ต่อไป

[1]: https://www.opendream.co.th
[2]: https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request