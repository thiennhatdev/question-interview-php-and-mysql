# question-interview-php-and-mysql
1. Có bao nhiêu cách truy xuất dữ liệu từ Mysql dùng php: 
  - Mysql_fetch_arrow : Dữ liệu trả về có dạng Array(0=>'value1',1=>'value2',..).
  - Mysql_fetch_assoc : Dữ liệu trả về có dạng Array('field1'=>'value1','field2'=>'value2',..).
  - Mysql_fetch_array : 
  - Mysql_fetch_object : Dữ liệu trả về có dạng Object('filed1'=>'value1',...).Lấy ra bằng cách $obj->ten_field.
  * Sự khác nhau của mysql_fetch_array và mysql_fetch_object là kiểu dữ liệu trả về,và giống nhau thì chúng chỉ có thể gọi ra bởi tên key chứ ko phải là số.
 2. $$ là toán tử   để tham chiếu tới các biến có tên linh động.
 3. Sử dụng mysql_create_db(name) để tạo database với tên name .
 4. Để chuyển cú pháp <??> thành <?php?> thì tại file php.ini sửa đổi dòng : set short_open_tag=on.
 5. Hàm Nl2br() sẽ chuyển chuỗi trong nó có \n thành thẻ <br> để xuống dòng.
 6. 
 
