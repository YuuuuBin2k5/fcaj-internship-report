---
title: "Event 1"
weight: 1
chapter: false
pre: "<b>4.1. </b>"
---

# Bài thu hoạch: First Cloud AI Journey Community Day

### Thông tin sự kiện

* **Tên sự kiện:** First Cloud AI Journey: Community Day 31/10
* **Thời gian:** 31/10 — năm và giờ chưa xác nhận.
* **Địa điểm:** Chưa xác nhận.
* **Vai trò:** Người tham dự.
* **Video:** [First Cloud AI Journey: Community Day 31/10](https://www.youtube.com/watch?v=qRSxBAPYttM) trên kênh AWS Study Group.

### Mục đích của sự kiện

Sự kiện gồm các phiên chia sẻ về lộ trình học AWS, kinh nghiệm thực tập và những chủ đề trong phát triển phần mềm như AI, serverless, xử lý bất đồng bộ và đóng góp mã nguồn mở.

### Danh sách diễn giả

* **Trường Minh Tuấn:** Chia sẻ lộ trình học AWS cho người mới.
* **Anh Đức (Henry):** Chia sẻ về ứng dụng AI trong quy trình phát triển phần mềm.
* **Phúc Khang:** Chia sẻ kinh nghiệm thực tập và xây dựng web game.
* **Thịnh Nguyễn:** Giới thiệu AWS Lambda Web Functions.
* **Cẩm Đào:** Chia sẻ về xử lý bất đồng bộ với Amazon SQS.
* **Hưng Trần:** Chia sẻ kinh nghiệm đóng góp mã nguồn mở.

### Nội dung nổi bật

#### Lộ trình học AWS

Phiên đầu giới thiệu cách kết hợp AWS Skill Builder để học nền tảng, các bài lab của cộng đồng để thực hành và AWS Builder Center để tìm đọc, chia sẻ kiến thức. Người học nên ghi lại lỗi và những gì đã hiểu sau mỗi bài lab. ([Xem từ 02:17](https://www.youtube.com/watch?v=qRSxBAPYttM&t=137))

#### AI trong phát triển phần mềm

Diễn giả chia sẻ cách sử dụng AI trong quá trình review mã nguồn và tự động hóa một số công việc. Nhóm sử dụng kiểm thử end-to-end, ảnh hoặc video để kiểm tra thay đổi, đồng thời chuyển các tác vụ như lint và migration lên máy chủ chung. ([Xem từ 38:06](https://www.youtube.com/watch?v=qRSxBAPYttM&t=2286))

#### Kinh nghiệm xây dựng web game

Phúc Khang trình bày quá trình xây dựng game nhiều người chơi với Lambda, DynamoDB, SQS và EventBridge. Phần chia sẻ đề cập việc xử lý các trận kết thúc đồng thời, phân quyền IAM và quản lý hạ tầng bằng AWS CDK. Những khó khăn trong quá trình làm giúp minh họa tầm quan trọng của việc đọc tài liệu và kiểm tra cấu hình dịch vụ. ([Xem từ 52:29](https://www.youtube.com/watch?v=qRSxBAPYttM&t=3149))

#### AWS Lambda Web Functions

Phiên này giới thiệu cách chạy ứng dụng HTTP trên Lambda và khả năng xử lý nhiều request đồng thời trong một môi trường. Bản demo là một website trắc nghiệm tính cách; diễn giả cũng trao đổi về cold start và chi phí khi ứng dụng chờ phản hồi từ dịch vụ khác. ([Xem từ 1:20:17](https://www.youtube.com/watch?v=qRSxBAPYttM&t=4817))

#### Xử lý bất đồng bộ với Amazon SQS

Cẩm Đào trình bày bài toán API phải chờ lâu khi yêu cầu tạo nội dung được xử lý. Giải pháp được giới thiệu là đưa công việc vào hàng đợi SQS, trả trạng thái chờ và xử lý sau. Phiên chia sẻ cũng đề cập Standard Queue, FIFO Queue, visibility timeout, long polling và dead-letter queue. ([Xem từ 1:42:19](https://www.youtube.com/watch?v=qRSxBAPYttM&t=6139))

#### Đóng góp mã nguồn mở

Phiên cuối chia sẻ cách bắt đầu từ các issue phù hợp với khả năng, viết pull request rõ ràng và duy trì việc đóng góp. Diễn giả cũng khuyến khích tìm hiểu các thay đổi của AWS để tìm cơ hội đóng góp cho những dự án như AWS CDK. ([Xem từ 2:04:53](https://www.youtube.com/watch?v=qRSxBAPYttM&t=7493))

### Những gì học được

* Có thể kết hợp học lý thuyết, làm lab và ghi chú lỗi để hiểu dịch vụ AWS tốt hơn.
* SQS giúp tách việc tiếp nhận yêu cầu khỏi tác vụ xử lý phía sau; cần tìm hiểu thêm cách thử lại và xử lý thông điệp lỗi.
* IAM cần được cấu hình theo quyền cần thiết cho từng thành phần; hạ tầng có thể được mô tả bằng mã để triển khai nhất quán hơn.
* Khi dùng AI hỗ trợ phát triển, vẫn cần kiểm thử và xem lại kết quả trước khi đưa vào dự án.

### Ứng dụng vào việc học

Trong quá trình tìm hiểu backend trên AWS, tôi dự định tìm hiểu sâu hơn cách dùng SQS cho tác vụ xử lý mất thời gian và cách kiểm tra log khi công việc thất bại. Tôi cũng có thể bắt đầu tìm hiểu mã nguồn mở từ một issue nhỏ, đọc hướng dẫn đóng góp và thử tái hiện lỗi trước khi đề xuất thay đổi.

### Trải nghiệm trong sự kiện

Những nội dung trong buổi chia sẻ cho tôi thêm góc nhìn về việc học AWS qua bài lab và dự án thực tế. Phần SQS liên quan trực tiếp đến hướng backend tôi đang tìm hiểu, vì có thể áp dụng cho những công việc không cần hoàn thành ngay trong một request.

### Hình ảnh tham gia sự kiện

Chưa bổ sung ảnh check-in.
