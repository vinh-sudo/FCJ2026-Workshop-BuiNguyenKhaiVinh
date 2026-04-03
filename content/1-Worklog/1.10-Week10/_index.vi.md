---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 10:

* Xây dựng và tích hợp các chức năng backend quan trọng: lập schedule tự động khi xác nhận plan, pause/resume order, upload file lên S3, notification sử dụng SNS/SQS.
* Thành thạo kết nối các dịch vụ AWS (S3, SNS, SQS) với hệ thống backend.
* Thực hành kiểm thử API, sửa lỗi và đảm bảo hệ thống vận hành ổn định, sẵn sàng cho môi trường thực tế.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2-3 | - Xây dựng chức năng lập schedule tự động khi xác nhận (confirm) plan                                      | 16/03/2026   | 17/03/2026      | Tài liệu nghiệp vụ, backend               |
| 4   | - Xây dựng chức năng pause và resume order                                                                | 18/03/2026   | 18/03/2026      | Tài liệu nghiệp vụ, backend               |
| 5   | - Xây dựng chức năng upload file lên S3 và kết nối bucket với backend                                     | 19/03/2026   | 19/03/2026      | AWS S3, backend                           |
| 6   | - Xây dựng chức năng notification, test chức năng và fix bug                                              | 20/03/2026   | 20/03/2026      | Backend, Postman                          |
| 7   | - Tối ưu performance hệ thống: tránh query lặp N+1, cấu trúc kiến trúc code nhất quán, clean code           | 21/03/2026   | 21/03/2026      | Backend, code review                      |


### Kết quả đạt được tuần 10:

* Đã xây dựng thành công chức năng lập schedule tự động khi xác nhận plan, giúp tự động hóa quy trình vận hành.
* Hoàn thiện và kiểm thử chức năng pause/resume order, tăng tính linh hoạt cho quản lý đơn hàng.
* Tích hợp upload file lên S3 và kết nối bucket với backend, đảm bảo lưu trữ file an toàn.
* Xây dựng chức năng notification sử dụng SNS/SQS, kiểm thử luồng gửi/nhận thông báo end-to-end.
* Thực hành kiểm thử API với Postman, phát hiện và sửa lỗi backend, đảm bảo hệ thống ổn định, tin cậy.
* Tối ưu performance hệ thống: loại bỏ truy vấn N+1, chuẩn hóa kiến trúc code, áp dụng clean code giúp hệ thống dễ bảo trì và mở rộng.
* Nâng cao hiểu biết về tích hợp dịch vụ AWS và best practice cho backend.
* ...
