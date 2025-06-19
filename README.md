# KiemThuHieuSuatTuan8
Ngày Kiểm Thử: 19/06/2025

Người Kiểm Thử: Vũ Duy Bình

1. Mục Tiêu Kiểm Thử: Sử dụng Jmeter để kiểm tra hiệu năng trang WEB

2. Môi Trường Kiểm Thử: Jmeter.

3. Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Jmeter.

4. Kịch Bản Kiểm Thử lần 1:
Tên Kịch Bản: Kiểm thử cơ bản của 1 trang WEB

Mục Đích: Test năng hoạt động của một trang web và phần mềm Jmeter

HTTP request: www.fpt.com

Tham Số: Resouces, Business

Number of thread (user): 1

Ramp-up period ( seconds): 1

Loop-count : 1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi test:

![image](https://github.com/user-attachments/assets/bc1fb961-cb01-4956-8973-f64cdb2bb86c)

Thời gian phản hồi trung bình: 2 giây

Tỷ lệ yêu cầu thành công: 100%

Kết quả chi tiết:

![image](https://github.com/user-attachments/assets/0146d823-1ff7-40f4-8238-aeeb579b7a71)

Kịch Bản Kiểm Thử lần 2:
Tên Kịch Bản: Kiểm thử cơ bản của 1 trang WEB

Mục Đích: Test năng hoạt động của một trang web khi thay đổi biến số

HTTP request: www.fpt.com

Tham Số: Resouces, Business

Number of thread (user): 10

Ramp-up period ( seconds): 2

Loop-count : 10

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi test:

![image](https://github.com/user-attachments/assets/9a4e6e8a-a6ed-45d5-b869-ea41170048bd)

Thời gian phản hồi trung bình: 15 giây

Tỷ lệ yêu cầu thành công: 100%

Kết quả chi tiết:

![image](https://github.com/user-attachments/assets/58719b64-e12b-48bd-b874-f915b5b8ce1c)

5. Kết quả

Trang web hoạt động khá tốt, thời gian phản hồi rất nhanh và tỉ lệ thật bại rất thập ngay cả khi với nhiều người dùng vào cùng một lúc
