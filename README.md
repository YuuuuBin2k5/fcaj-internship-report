# FCAJ Internship Report

Khung báo cáo thực tập First Cloud AI Journey bằng tiếng Việt và tiếng Anh.
Nội dung cá nhân, đề tài và minh chứng đang chờ bổ sung; các mục trống không phải kết quả đã hoàn thành.

## Cấu trúc

```text
content/
  _index.md / _index.vi.md  # Hồ sơ và mục lục
  1-Worklog/               # 12 tuần, nhật ký từng ngày
  2-Proposal/              # Bài toán, kiến trúc, tiến độ, chi phí, rủi ro
  3-BlogsPosted/           # 3 bài viết kỹ thuật
  4-EventParticipated/     # 3 sự kiện và minh chứng
  5-Workshop/             # 10 phần kỹ thuật, từ tổng quan đến cleanup
  6-Self-evaluation/       # Tự đánh giá
  7-Feedback/              # Chia sẻ, góp ý
static/images/            # Ảnh dùng trong báo cáo
static/attachments/       # PDF, script và tệp đính kèm
assets-source/architecture/ # Bản nguồn sơ đồ tự thiết kế
layouts/                  # Tùy chỉnh giao diện
themes/hugo-theme-learn/  # Theme được lưu trực tiếp trong repository
config.toml               # URL, ngôn ngữ, giao diện
```

## Chỉnh nội dung

- `_index.md`: tiếng Anh; `_index.vi.md`: tiếng Việt. Cập nhật hai bản tương ứng.
- `weight` quyết định thứ tự menu. Giữ tuần 1–12 và các phần Workshop theo thứ tự số.
- Thêm ảnh cá nhân vào `static/images/profile/`, sự kiện vào `static/images/events/`, lab vào `static/images/workshop/`.
- Khi chèn ảnh/tệp, dùng shortcode để giữ đúng đường dẫn con GitHub Pages:

```markdown
![Mô tả ảnh]({{< asset "images/events/event-1.jpg" >}})
[Tải tệp]({{< asset "attachments/budget.pdf" >}})
```

- Không ghi khóa AWS, token hoặc mật khẩu vào nội dung/mã nguồn.
- Thiết kế và hiểu kiến trúc của chính mình; không dùng nguyên kiến trúc do AI tạo làm bài nộp.
- Cấu trúc có sẵn không thay thế yêu cầu về sản phẩm thực tế, blog đã đăng, sự kiện hợp lệ và worklog trung thực.

## Xem trên máy

Cài **Hugo Extended 0.134.3**, phiên bản được workflow sử dụng:

```powershell
hugo server --disableFastRender
```

Mở địa chỉ được Hugo in ra. Dựng bản tĩnh bằng `hugo --minify`; kết quả nằm trong `public/` và không được commit.

## GitHub Pages

Repository: https://github.com/YuuuuBin2k5/fcaj-internship-report

URL đã cấu hình: https://YuuuuBin2k5.github.io/fcaj-internship-report/

Workflow kiểm tra build khi mở pull request. Khi push `main` hoặc chạy thủ công trên nhánh `main`, workflow dựng và đẩy HTML sang `gh-pages`.

Sau lần chạy thành công đầu tiên, vào **Settings → Pages → Deploy from a branch**, chọn **gh-pages / (root)**. URL chỉ hoạt động sau khi cấu hình Pages và triển khai thành công.

Template gốc: https://github.com/thienluhoan/fcj-workshop-template (remote `upstream`). Repository cá nhân dùng remote `origin`. Theme Learn giữ nguyên giấy phép MIT trong thư mục theme.
