---
title: "Worklog Tuần 4"
weight: 4
chapter: false
pre: "<b>1.4. </b>"
---

### Mục tiêu tuần 4:

* Ôn tập VPC và cách kiểm soát truy cập bằng Security Group.
* Tìm hiểu EC2, kết nối máy chủ Linux và chuẩn bị môi trường chạy ứng dụng Node.js.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Ôn lại VPC và CIDR; xác định dải địa chỉ của VPC và các subnet.<br>- Phân biệt public subnet với private subnet dựa trên bảng định tuyến.<br>- Tìm hiểu route local, route ra Internet Gateway và cách liên kết route table với subnet.<br>- So sánh Security Group và Network ACL: phạm vi áp dụng, inbound/outbound, stateful và stateless.<br>- Đọc lại cấu hình mạng trong bài VPC để chuẩn bị môi trường cho EC2. | 26/10/2026 | 26/10/2026 | [Amazon VPC](https://000003.awsfcaj.com/) |
| 4 | - Kiểm tra VPC, public subnet, route table và Internet Gateway dùng cho bài thực hành tại văn phòng.<br>- Tìm hiểu vai trò của AMI, instance type, EBS và key pair khi tạo EC2.<br>- Theo hướng dẫn chọn Amazon Linux, cấu hình ổ đĩa và đặt tên cho instance.<br>- Chọn subnet, thiết lập public IP và Security Group; tìm hiểu cách giới hạn SSH theo IP máy cá nhân.<br>- Thử khởi tạo instance, kiểm tra trạng thái và ghi lại thông tin cần dùng để kết nối. | 28/10/2026 | 28/10/2026 | [Amazon EC2](https://000004.awsfcaj.com/) |
| 5 | - Đọc hướng dẫn SSH: địa chỉ máy chủ, tên đăng nhập ec2-user và tệp khóa riêng.<br>- Tìm hiểu cách kiểm tra IP, cổng 22 và rule Security Group khi không kết nối được.<br>- Làm quen pwd, ls, cd, mkdir, cat và nano để thao tác thư mục và tệp trên Linux.<br>- Đọc cách cài Node.js bằng nvm; tìm hiểu cách kiểm tra phiên bản bằng node -v và npm -v.<br>- Tìm hiểu Git và các bước đưa mã nguồn ứng dụng lên máy chủ. | 29/10/2026 | 29/10/2026 | [Kết nối EC2 Linux](https://000004.awsfcaj.com/4-launchlinuxinstance/4.2-connectlinuxinstance/) |
| 6 | - Tại văn phòng, tiếp tục kiểm tra kết nối EC2 và các bước chuẩn bị Node.js, npm, Git.<br>- Thử tạo ứng dụng Node.js nhỏ có endpoint trả về nội dung kiểm tra.<br>- Tìm hiểu địa chỉ lắng nghe, cổng ứng dụng và rule Security Group cần thiết để truy cập từ máy cá nhân.<br>- Thử gửi request từ máy chủ và trình duyệt; đối chiếu phản hồi với log ứng dụng.<br>- Lưu kết quả thực tế; rà instance, EBS và tài nguyên mạng của bài lab trước khi dọn dẹp. | 30/10/2026 | 30/10/2026 | [Node.js trên EC2](https://000004.awsfcaj.com/6-awsfcjmanagement-linux/6.2-setupnodejsonec2linux/) |

### Kết quả đạt được tuần 4:

* Dự kiến nắm rõ hơn luồng kết nối từ Internet đến EC2 qua subnet, route table và Security Group.
* Dự kiến biết cách chọn AMI, tạo key pair, khởi tạo EC2 Linux và kết nối SSH.
* Mục tiêu thực hành là chạy ứng dụng Node.js đơn giản; kết quả triển khai sẽ cập nhật theo thực tế.
