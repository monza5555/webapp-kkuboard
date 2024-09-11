# webapp-kkuboard
bootstrap: https://getbootstrap.com/docs/5.3/getting-started/introduction/
11 pages
- sign in
- sign up
- home
- category
- 'myblogs'
- addblog,editblog*
- 'myblog'
- blog
- blogwpoll*
- (A)blogs
- (A)hideblog

หน้าmyblogs คือหน้ารวมบล็อกที่ผู้ใช้สร้างขึ้นทั้งหมด
หน้าmyblog คือหน้าblogที่มีปุ่ม'จัดการบล็อก'ให้

หน้าeditblog คือหน้าaddblog ที่เปลี่ยนh3 จาก'เพิ่มบล็อกใหม่'เป็น'แก้ไขบล็อก'
และทำให้'หมวดหมู่'เป็นdisbled (แก้ไขหมวดหมู่ไม่ได้)

หน้าblogwpoll คือหน้าblog ที่เปลี่ยนlay outจากมีรูปอยู่ตรงกลางอย่างเดียว
เป็นมีรูปและโพลล์แบ่งกันอยู่

ปุ่มเข้าสู่ระบบ:
<button class="btn btn-outline-light rounded-5" type="button">เข้าสู่ระบบ</button>
ปุ่มออกจากระบบ:
<button class="btn btn-outline-danger rounded-5" type="button">ออกจากระบบ</button>
