---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 3:

* Tìm hiểu quy trình mua domain, tích hợp domain với Route 53 và quản lý DNS tập trung trên AWS.
* Nắm vững mô hình hybrid DNS, các loại bản ghi DNS, vai trò của Route 53 và Load Balancer trong hệ thống thực tế.
* Hiểu các best practice về thiết kế hệ thống DNS, HA/DR, bảo mật, tối ưu chi phí khi sử dụng Route 53 và Load Balancer.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Mua domain và thiết lập kết nối với Route 53                                                                                                                                                                                            | 20/01/2026   | 20/01/2026      |                                           |
| 3   | - Thực hiện Lab 10 để tìm hiểu về Route 53 và thiết lập hệ thống hybrid DNS <br> - Khởi chạy máy chủ ảo để triển khai và thiết lập DNS                                                               | 21/01/2026   | 21/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu về Load Balancer <br> - Thực hành kết nối Route 53 với Load Balancer                                                                                                                    | 22/01/2026   | 22/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Họp nhóm, thảo luận và lên ý tưởng cho project                                                                                                                                                | 23/01/2026   | 23/01/2026      |                                           |

### Kết quả đạt được tuần 3:

* Hiểu quy trình mua domain và tích hợp domain với Route 53 để quản lý DNS tập trung trên AWS.
* Nắm được khái niệm, vai trò và các loại bản ghi DNS trong Route 53 (A, CNAME, NS, MX, ...).
* Hiểu mô hình hybrid DNS, sự kết hợp giữa DNS on-premises và Route 53, và các tình huống ứng dụng thực tế.
* Biết cách khởi tạo, cấu hình máy chủ ảo để triển khai dịch vụ DNS nội bộ.
* Nắm được nguyên lý hoạt động của Load Balancer, các loại Load Balancer trên AWS (ALB, NLB, CLB) và cách Route 53 phân phối truy cập đến các endpoint.
* Hiểu vai trò của Route 53 trong việc kết nối, cân bằng tải và đảm bảo tính sẵn sàng cho hệ thống.
* Biết cách sử dụng tính năng health check và DNS failover của Route 53 để tự động chuyển hướng truy cập khi một endpoint gặp sự cố.
* Hiểu các mô hình tích hợp phổ biến giữa Route 53, Load Balancer và các dịch vụ backend (EC2, ECS, Lambda, S3 static website...).
* Nắm được best practice về phân vùng vùng miền (multi-AZ, multi-region) để tăng tính sẵn sàng và khả năng mở rộng cho hệ thống DNS và ứng dụng.
* Nhận diện được các yếu tố cần thiết khi xây dựng ý tưởng project thực tế trên nền tảng AWS, đặc biệt là các yếu tố về HA/DR, bảo mật, và tối ưu chi phí khi thiết kế hệ thống sử dụng Route 53 và Load Balancer.
* ...
