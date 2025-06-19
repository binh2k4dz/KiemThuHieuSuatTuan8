# KiemThuHieuSuatTuan8
Ngày Kiểm Thử: 19/06/2025

Người Kiểm Thử: Vũ Duy Bình

1. Mục Tiêu Kiểm Thử: Sử dụng Jmeter để kiểm tra hiệu năng trang WEB

2. Môi Trường Kiểm Thử: Jmeter.

3. Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Jmeter.

4. Kịch Bản Kiểm Thử lần 1:
Tên Kịch Bản: Kiểm thử cơ bản của 1 trang WEB

Mục Đích: Test năng hoạt động của một trang web và phần mềm Jmeter

4.1. Thiết lập Thread Properties:

•	Number of Threads (users): Số lượng users giả lập được gửi vào trang web.

•	Ramp-Up Period (seconds): Thời gian gửi lượng users vào trang web.

•	Loop Count: Số lần lặp.

•	Infinite: Check để lặp không giới hạn, uncheck để lặp bằng số Loop Count.

![image](https://github.com/user-attachments/assets/5b60e454-39ea-4ae7-b57f-cd3840c6dd5b)

Trong hình đã thiết lập gửi 100 users vào trang trong vòng 10 giây, số lần lặp là 2.

Kết quả: Tương đương gửi 200 users vào trang trong vòng 20 giây, mỗi giây sẽ gửi vào 10 users.


4.2. Cấu hình HTTP Request:

Tạo một HTTP Request truy cập vào trang: http://127.0.0.1:8000/

Kiểm tra thời gian phản hồi, tỉ lệ lỗi và khả năng xử lý request của máy chủ.

Để lấy API http://127.0.0.1:8000/ cần config thông tin như sau:

•	Protocol: http

•	Server Name or IP: 127.0.0.1

•	Port Number: 8000

•	Method: GET

•	Path: /

![image](https://github.com/user-attachments/assets/b31d6c16-800f-425e-9351-b589a212394b)

4.3. Kết quả chi tiết:

![image](https://github.com/user-attachments/assets/7a7b4186-bdf3-458b-8535-6123fe945da9)

Hệ thống có khả năng xử lý yêu cầu mà không có lỗi, nhưng thời gian phản hồi trung bình cao (6.6 giây) và biến động lớn giữa các request.
