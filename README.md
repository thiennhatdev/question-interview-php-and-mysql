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
 6. Sử dụng AES_ENCRYPT (giá-trị) and AES_DECRYPT ( giá-trị) để mã hoá và giải mã trước khi đưa vào database.
 7. Tính năng quan trọng của lập trình hướng đối tượng là dễ dàng sửa đổi,giúp giảm chi phí bảo trì.Mô hình hoá thế giới thực thực hơn là lập trình hướng thủ tục nên nó có tính linh hoạt hơn và tương tác dễ hơn.
 8. Hàm htmlentities giống hàm htmlspecialchar() dùng để chuyển các kí tự đặc biệt.Ví dụ ta muốn hiển thị 5 dấu cách trong chuỗi nhưng nếu không dùng 2 hàm trên thì trình duyệt sẽ bỏ đi các khoảng cách đó.
 9. Hàm unlink() là xoá 1 file của thư mục,còn unset() xoá 1 biến .
 10. exif_imagetype() kiểm tra type của img,getimagesize() trả về kich thước của img,imagesx() và imagesy() kiểm tra độ rộng và độ cao của image.
 11. Kích thước tối đa của file mà php có thể upload được là 2MB,để thay đổi điều đó thì phải thay đổi upload_max_filesize=2MB trong file php.ini.
 12. Để tối ưu hoá và tăng tốc độ truy vấn mysql thì đầu tiên: thay vì dùng select* from ta sẽ dùng select column1,column2 ...from..., thứ 2 là nếu có thể thì sử dụng where hoặc limit để giới hạn phạm vi truy vấn.
 13. Sử dụng session_id() để lấy id của session hiện tại.
 14. Để huỷ cookie thì cài đặt expried của nó là thời gian trong quá khứ.
 15. Có 2 cách để truyền biến giữa các page là sử dụng method get và post.
 16. Có 2 hàm để đếm số phần tử của mảng là sizeof() và count().
 17. SỬ dụng isNaN() hoặc is_numberic() để kiểm tra một biến có phải là số hay không.
 18. Sử dụng CURRENT_DATE() hoặc CURRENT_TIME() để lấy ngày hoặc giờ ngày hoặc giờ trong Mysql.
 19. Để biết khoảng cách giữa 2 thời gian trong mysql : select datediff('ngày-tháng-năm','ngày-tháng-năm').
 20. Các cách thường dùng để bảo mật: 
  - Xác thực ở input.
  - Sử dụng session ID.
  - Chặn tấn công XSS.
  - ...
 21. Độ dài tên của database,table,hay column là 64 character.
 22. Để biết cấu trúc của table : describe tên-table.
 23. Để thay đổi một cột trong table : alter table tên-table change tên-field-old tên-field-new kiểu-dữ-liệu(number).
 24. Thay đổi kiểu dữ liệu của một column trong table : alter table tên-table modify tên-column kiểu-dữ-liêu(number).
 25. Truy cập các method static bằng dấu ::, có nghĩa sẽ không cần khởi tạo đối tượng, truy cập -> thì phải khởi tạo đối tượng.
 26. Abstract mang tính đơn hình, để khắc phục ta dùng interface có tính đa hình.
 27. Char được dùng lưu trữ dữ liệu nhỏ,làm việc nhanh hơn và lưu dữ liệu có độ dài cố định.Varchar thì dùng lưu dữ liệu lớn,làm việc chậm hơn và có dữ liệu được lưu có độ dài thay đổi.
 28. Để thay đổi tên của table : rename table tên-table to tên-table-mới.
 29. show tables dùng để hiển thị tất cả table.
 30. Primary key khác unique key ở chỗ nó là giá trị duy nhất và ko chấp nhận giá trị null,còn unique key thì có.
 31. select * from tên-table limit number1,number2 : lấy number2 giá trị bắt đầu tại vị trí number1.
 32. select sum(tên-field) as value1 from tên-table : lấy tổng các giá trị trong field trong table rồi đặt dưới tên là value1.
 33. Với từ khoá final trước class thì class đó không thể kết thừa,nếu trước method thì method đó không thể bị ghi đè.
 34. Để chọn tất cả giá trị trong column mà ko lặp lại : select distinct tên-column from tên-table.
 35. Xoá một column trong table : alter table tên-table drop tên-column.
 
  
 


 
