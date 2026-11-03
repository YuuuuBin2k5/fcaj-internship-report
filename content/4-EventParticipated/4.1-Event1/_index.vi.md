---
title: "Event 1"
weight: 1
chapter: false
pre: "<b>4.1. </b>"
---

# Bài thu hoạch: FCAJ Community Day

**Thông tin sự kiện**

* **Tên sự kiện:** FCAJ Community Day
* **Thời gian:** 09:00–12:00, thứ Bảy, ngày 31/10/2026 (GMT+7).
* **Địa điểm:** Bitexco Financial Tower, Thành phố Hồ Chí Minh.
* **Vai trò:** Người tham dự.
* **Video:** [First Cloud AI Journey: Community Day 31/10](https://www.youtube.com/watch?v=qRSxBAPYttM) trên kênh AWS Study Group.

### Mục đích của sự kiện

* Tìm hiểu các nguồn học và lộ trình tiếp cận AWS.
* Lắng nghe kinh nghiệm thực tập và phát triển ứng dụng trên AWS.
* Tìm hiểu ứng dụng AI, serverless, xử lý bất đồng bộ và đóng góp mã nguồn mở.

### Danh sách diễn giả

* **Minh Tuấn:** Chia sẻ lộ trình học AWS cho người mới.
* **Đức (Henry):** Chia sẻ về ứng dụng AI trong quy trình phát triển phần mềm.
* **Khanh Duong:** Chia sẻ kinh nghiệm thực tập và xây dựng web game.
* **Thịnh Nguyễn:** Giới thiệu AWS Lambda Web Functions.
* **Luong Cam Dao:** Chia sẻ về xử lý bất đồng bộ với Amazon SQS.
* **Hưng Trần:** Chia sẻ kinh nghiệm đóng góp mã nguồn mở.

### Nội dung nổi bật

#### Lộ trình học AWS

* **Học nền tảng:** Sử dụng các khóa học và bài kiểm tra trên AWS Skill Builder để làm quen với cloud.
* **Thực hành:** Làm lab của AWS Study Group theo từng bước, ghi lại lỗi và cách xử lý; dọn tài nguyên sau khi hoàn thành.
* **Chia sẻ:** Tổng hợp kiến thức thành dự án nhỏ hoặc bài viết trên AWS Builder Center.

#### AI trong phát triển phần mềm

* **Trao đổi ý tưởng:** Dùng AI hỗ trợ tổng hợp thảo luận và khám phá các phương án trước khi chọn hướng triển khai.
* **Kiểm tra thay đổi:** Kết hợp review tự động với kiểm thử end-to-end, ảnh trước/sau hoặc video luồng chạy.
* **Môi trường làm việc:** Đưa các tác vụ lint và migration lên máy chủ chung để giảm thời gian chờ trên máy cá nhân.

#### Kinh nghiệm xây dựng web game

* **Kiến trúc serverless:** Sử dụng Lambda và DynamoDB cho các thao tác của game; kết hợp SQS để xử lý các công việc phát sinh khi nhiều trận kết thúc.
* **Công việc theo lịch:** Cập nhật bảng xếp hạng định kỳ và dùng EventBridge cho bài toán theo dõi thời gian.
* **Bài học bảo mật:** Không gom mọi quyền vào một IAM Role; cân nhắc dùng Secrets Manager để quản lý thông tin nhạy cảm.
* **Infrastructure as Code:** Dùng AWS CDK và CloudFormation để mô tả, triển khai hạ tầng nhất quán.

#### AWS Lambda Web Functions

* **Cách hoạt động:** Ứng dụng xử lý HTTP có thể chạy trong môi trường Lambda; một môi trường có thể phục vụ nhiều request đồng thời.
* **Hiệu năng:** Diễn giả so sánh cold start và khả năng phục vụ các request tiếp theo trong bản demo.
* **Tính phí:** Phần chia sẻ đề cập chi phí theo request, CPU hoạt động và bộ nhớ; cần xem cấu hình và mức sử dụng thực tế khi dự toán.
* **Demo:** Website trắc nghiệm tính cách sử dụng CloudFront và Lambda Web Functions.

#### Xử lý bất đồng bộ với Amazon SQS

* **Bài toán:** API chờ xử lý tạo nội dung bằng Amazon Bedrock khiến người dùng phải đợi phản hồi.
* **Giải pháp:** API đưa yêu cầu vào queue và trả trạng thái pending; tác vụ được xử lý phía sau.
* **Loại queue:** Standard và FIFO có đặc điểm khác nhau về thứ tự xử lý và khả năng thông lượng.
* **Xử lý lỗi:** Visibility timeout tạm ẩn message khi xử lý; dead-letter queue lưu các message thất bại sau nhiều lần thử lại.
* **Demo:** Tạo queue, gửi và nhận message qua AWS Console và mã nguồn.

#### Đóng góp mã nguồn mở

* **Bắt đầu:** Chọn issue vừa sức, đọc hướng dẫn đóng góp và tìm hiểu phần mã liên quan.
* **Tạo pull request:** Giữ thay đổi rõ ràng, có phạm vi nhỏ để người review dễ kiểm tra.
* **Duy trì:** Theo dõi thay đổi của dự án, trao đổi với maintainer và đóng góp đều đặn.

### Những gì học được

#### Kiến thức kỹ thuật

* Có thể kết hợp học lý thuyết, làm lab và ghi chú lỗi để hiểu dịch vụ AWS tốt hơn.
* SQS giúp tách việc tiếp nhận yêu cầu khỏi tác vụ xử lý phía sau; cần tìm hiểu thêm cách thử lại và xử lý thông điệp lỗi.
* IAM cần được cấu hình theo quyền cần thiết cho từng thành phần; hạ tầng có thể được mô tả bằng mã để triển khai nhất quán hơn.
* Khi dùng AI hỗ trợ phát triển, vẫn cần kiểm thử và xem lại kết quả trước khi đưa vào dự án.

### Ứng dụng vào công việc

* **Xử lý bất đồng bộ:** Tìm hiểu cách dùng SQS cho tác vụ mất thời gian trong ứng dụng backend.
* **Giám sát:** Tìm hiểu cách kiểm tra log và thông điệp lỗi khi xử lý thất bại.
* **Mã nguồn mở:** Bắt đầu từ một issue nhỏ, đọc hướng dẫn đóng góp và thử tái hiện lỗi trước khi đề xuất thay đổi.

### Trải nghiệm trong sự kiện

#### Tiếp cận kiến thức từ các phiên chia sẻ

Những nội dung trong buổi chia sẻ cho tôi thêm góc nhìn về việc học AWS qua bài lab và dự án thực tế. Phần SQS liên quan trực tiếp đến hướng backend tôi đang tìm hiểu, vì có thể áp dụng cho những công việc không cần hoàn thành ngay trong một request.

#### Một số hình ảnh khi tham gia sự kiện

![Ảnh tại sự kiện First Cloud AI Journey Community Day]({{< asset "images/events/community-day-31-10.png" >}})
