\# Contributing to Hello OSS



Cảm ơn bạn đã quan tâm và muốn đóng góp cho dự án Hello OSS.



\## 1. Báo lỗi (Issue)



\- Truy cập repository trên GitHub và mở mục Issues.

\- Chọn New issue.

\- Mô tả rõ lỗi, các bước tái hiện lỗi và kết quả mong đợi.

\- Cung cấp thông tin môi trường nếu cần thiết.



\## 2. Gửi Pull Request



1\. Fork repository nếu bạn không có quyền ghi trực tiếp.

2\. Clone repository của bạn về máy.

3\. Tạo một nhánh mới cho thay đổi:



&#x20;  ```bash

&#x20;  git switch -c fix/description

&#x20;  ```



4\. Thực hiện thay đổi và kiểm tra chương trình.

5\. Thêm và commit các file đã sửa:



&#x20;  ```bash

&#x20;  git add .

&#x20;  git commit -m "Fix: describe the change"

&#x20;  ```



6\. Push nhánh lên GitHub:



&#x20;  ```bash

&#x20;  git push -u origin fix/description

&#x20;  ```



7\. Tạo Pull Request, mô tả thay đổi và chờ người bảo trì xem xét.



\## 3. Quy tắc đặt tên commit



\- Dùng thông điệp ngắn gọn, dễ hiểu.

\- Mô tả đúng nội dung thay đổi.

\- Có thể dùng các tiền tố như `Add:`, `Fix:` hoặc `Docs:`.



Ví dụ:



\- `Docs: improve README`

\- `Fix: correct program output`

\- `Add: contributing guidelines`



\## 4. Nguyên tắc chung



\- Giữ thay đổi đơn giản, tập trung vào một mục tiêu.

\- Kiểm tra chương trình trước khi gửi Pull Request.

\- Tôn trọng ý kiến phản hồi trong quá trình review.

