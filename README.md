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
 


 
