---
title: "Worklog Tuần 3"
weight: 3
chapter: false
pre: "<b>1.3. </b>"
---

### Mục tiêu tuần 3:

* Tìm hiểu cách quản lý quyền truy cập tài nguyên AWS bằng IAM.
* Phân biệt IAM User, Group, Policy và Role.
* Nắm được quy trình tạo người dùng, gán quyền và chuyển đổi vai trò theo bài hướng dẫn.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 4 | - Đọc phần giới thiệu AWS IAM, phân biệt tài khoản root với IAM User.<br>- Tìm hiểu User, Group, Policy và Role; cách quản lý quyền thông qua nhóm người dùng.<br>- Đọc hướng dẫn tạo AdminGroup, AdminUser và đăng nhập bằng IAM User.<br>- Tìm hiểu cách tạo AdminRole, OperatorUser và cấp quyền `sts:AssumeRole` để thực hiện Switch Role.<br>- Đọc phần dọn dẹp các tài nguyên IAM dùng trong bài lab. | 21/10/2026 | 21/10/2026 | [Quản lý quyền truy cập với AWS IAM](https://000002.awsfcaj.com/) |

### Kết quả đạt được tuần 3:

* Phân biệt được IAM User, Group, Policy và Role; hiểu vai trò của từng thành phần trong việc quản lý truy cập.
* Hiểu cách người dùng nhận quyền từ policy gắn vào group và vì sao cần hạn chế sử dụng tài khoản root cho công việc hằng ngày.
* Nắm được các bước tạo người dùng, nhóm và role theo bài hướng dẫn.
* Hiểu Switch Role là cách sử dụng quyền của một role trong phiên làm việc; cần cấu hình quyền chuyển role và quan hệ tin cậy phù hợp.
* Biết cần cấp quyền theo nhu cầu sử dụng và xóa các tài nguyên IAM thử nghiệm khi không còn dùng.
