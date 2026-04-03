---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 11:

* Xây dựng chức năng gửi email quên mật khẩu với SES (sandbox), tích hợp AI trả lời nghiệp vụ đơn giản.
* Nâng cấp logic báo cáo, bổ sung tính toán tiến độ và hiển thị progress cho line leader.
* Thực hành kiểm thử, hoàn thiện và tối ưu các chức năng backend phục vụ quản lý sản xuất.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tạo SES với trạng thái sandbox, xây dựng chức năng quên mật khẩu gửi email                                | 23/03/2026   | 23/03/2026      | AWS SES, backend                          |
| 3-4 | - Tích hợp AI model, xây dựng chức năng AI trả lời đơn giản về đơn hàng, lịch sản xuất, công suất...      | 24/03/2026   | 25/03/2026      | AI model, backend                         |
| 5   | - Sửa lại logic chức năng báo cáo (report) của line leader                                                | 26/03/2026   | 26/03/2026      | Backend, nghiệp vụ                        |
| 6   | - Thêm tính toán phần trăm số lượng order, hiển thị progress cho line leader, test các chức năng           | 27/03/2026   | 27/03/2026      | Backend, Postman                          |
| 7   | - Backup dữ liệu từ Railway và restore sang RDS                                                           | 28/03/2026   | 28/03/2026      | Railway, AWS RDS                          |


### Kết quả đạt được tuần 11:

* Đã xây dựng thành công chức năng gửi email quên mật khẩu sử dụng SES ở trạng thái sandbox.
* Tích hợp AI model trả lời các câu hỏi nghiệp vụ cơ bản về đơn hàng, lịch sản xuất, công suất...
* Sửa lại logic và nâng cấp chức năng báo cáo cho line leader, đảm bảo phản ánh đúng thực tế sản xuất.
* Bổ sung tính toán phần trăm số lượng order, hiển thị progress trực quan cho line leader.
* Đã kiểm thử, hoàn thiện và tối ưu các chức năng backend, đảm bảo hệ thống vận hành ổn định.
* Đã backup dữ liệu từ Railway và restore sang RDS, đảm bảo an toàn và khả năng chuyển đổi dữ liệu.
* ...
