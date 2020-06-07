web-application ประกอบไปด้วย
    - client (React)
    - server (Nodejs)
    - database (MySql)

ความต้องการของระบบ
    - node version 10.16.3 หรือ สูงกว่า

database
    - ใช้ xampp ในสร้าง Mysql server และ phpmyadmin โหลดได้จาก https://www.apachefriends.org/index.html
    - ทำการติดตั้งโปรแกรม แล้วทำการเปิดโปรแกรมเมื่อเสร็จสิ้น
    - เปิดใช้งาน apache และ mysql โดยกดที่ start
    - กด admin ของ mysql เพื่อจะทำการ import database
    - กด import ที่บริเวณ header จากนั้น choose file จาก ./db/partyhann.sql จากนั้นกด Go *ถ้า import ไม่ได้ แก้ไขตามนี้ https://bit.ly/2BBxQI4

back-end 
    - ติดตั้ง Nodejs จาก https://nodejs.org/en/download/
    - เข้าโฟลเดอร์ server จากนั้นใช้คำสั่ง $yarn install
    - เมื่อติดตั้งแล้ว รันด้วยคำสั่ง $yarn dev
 **ถ้าเชื่อมต่อ database ไม่ได้ โปรดตรวจสอบที่ ./server/database/db.js เพื่อตรวจสอบ username&password ของ MySql

front-end 
    - ติดตั้ง Nodejs จาก https://nodejs.org/en/download/ *ถ้าติดตั้งแล้วข้ามข้อนี้ไป
    - เข้าโฟลเดอร์ client จากนั้นใช้คำสั่ง $yarn install
    - เมื่อติดตั้งแล้ว รันด้วยคำสั่ง $yarn start
    - เข้าใช้งานได้ที่ http://localhost:3000