---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 2:

* Hiểu rõ kiến trúc VPC, các thành phần liên quan và mối liên hệ giữa VPC, Security Group, IAM.
* Thực hành tạo, cấu hình, kiểm thử các thành phần VPC, EC2, Security Group, IAM trên AWS Console và CLI.
* Nắm được quy trình kiểm soát truy cập, phân quyền và bảo mật cho hệ thống cloud cơ bản.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về VPC và VPC Group (nhóm các thành phần trong VPC, ví dụ: Subnet, Route Table, Internet Gateway, Security Group, v.v.)                                                                                                         | 13/01/2026   | 13/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu về Security Group <br> - Mối liên hệ giữa VPC và Security Group/VPC Group                                                                                                               | 14/01/2026   | 14/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu EC2 cơ bản (lý thuyết): <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + Security Group <br>&emsp; + Key pair <br>&emsp; + Elastic IP (khái niệm) <br> - Các cách SSH vào EC2 (Windows, Linux, VS Code, ...) <br> - **Thực hành:** <br>&emsp; + Tạo EC2 instance <br>&emsp; + Kết nối SSH vào EC2 | 16/01/2026   | 16/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu IAM: <br>&emsp; + IAM User <br>&emsp; + IAM Role <br>&emsp; + Attach policy trực tiếp cho IAM User/Role <br>&emsp; + Xem và chỉnh sửa JSON policy cơ bản <br>&emsp; + Gán IAM Role cho EC2 (khái niệm & demo cơ bản)           | 17/01/2026   | 17/01/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* Đã tìm hiểu và ghi chú lại các thành phần chính của VPC, mối liên hệ giữa Security Group và VPC.
* Đã thực hành tạo, cấu hình các thành phần VPC trên AWS Console (Subnet, Route Table, Internet Gateway, Security Group...).
* Đã thử tạo và kiểm tra các rule trong Security Group, xác nhận ảnh hưởng tới truy cập EC2.
* Đã thực hành tạo EC2 instance, tạo key pair, SSH thành công vào EC2 từ máy cá nhân.
* Đã thử thay đổi cấu hình Security Group để kiểm soát truy cập EC2 (mở/đóng port, kiểm tra kết nối).
* Đã tạo IAM User, IAM Role, attach policy trực tiếp, chỉnh sửa JSON policy, gán IAM Role cho EC2 và xác nhận quyền truy cập thay đổi theo policy.
* Đã sử dụng cả giao diện web và CLI để thao tác tài nguyên AWS, ghi lại các bước thực hiện và kết quả.
* ...
