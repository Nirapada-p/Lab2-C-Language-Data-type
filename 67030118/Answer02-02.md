คำถาม

1.1 ทำไม 10 / 3.0 (เมื่อตัวหารเป็น float หรือ double) ถึงได้ผลลัพธ์เป็นทศนิยม แต่เมื่อตัวหารถูกแปลงเป็น int แล้วผลลัพธ์เป็นจำนวนเต็ม?
เพราะ float และ double สามารถเก็บตัวเเปรที่เป็น ทศนิยมได้ เเต่ int เก็บตัวแแปรที่เป็นตัวนวนเต็มเเต่ไม่สามารถเก็บตัวเเปรที่เป็นทศนิยมได้ ดังนั้นเมื่อหารเเล้วมีเศษ จะทำการปัดเศษทิ้งเเละเก็บค่าเเค่จำนวนเต็ม

1.2 ในการเขียนโปรแกรม ต้องทำ Type Casting ในสถานการณ์ใดบ้าง
ควรทำ Type Casting เมื่อจำเป็นต้องใช้ข้อมูลในชนิดที่เป็นตัวอักษรใช้ char หรือการหารที่ต้องการผลลัพธ์แบบทศนิยมต้องแปลงเป็น float เพื่อความถูกต้องในการคำนวณเเละความเที่ยงตรงของการหาร
