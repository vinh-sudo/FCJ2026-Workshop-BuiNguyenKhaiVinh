---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.12 </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 12:

* Thực hành triển khai ứng dụng thực tế lên AWS (ECR, ECS, Secret Manager, IAM role).
* Thiết lập giám sát hệ thống với CloudWatch, tối ưu chi phí vận hành các dịch vụ AWS.
* Kiểm thử, review và hoàn thiện toàn bộ hệ thống backend, thực hành CI/CD với CodeBuild, CodePipeline.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Build image, push lên ECR, deploy lên ECS kết hợp Secret Manager và IAM role                              | 30/03/2026   | 30/03/2026      | AWS ECR, ECS, Secret Manager, IAM         |
| 3   | - Thiết lập CloudWatch để theo dõi hệ thống                                                               | 31/03/2026   | 31/03/2026      | AWS CloudWatch                            |
| 4   | - Cấu hình lại các service AWS để tối ưu chi phí                                                          | 01/04/2026   | 01/04/2026      | AWS Cost Management, backend              |
| 5   | - Test lại toàn bộ các chức năng hệ thống                                                                 | 02/04/2026   | 02/04/2026      | Backend, Postman                          |
| 6   | - Thử nghiệm CodeBuild, CodePipeline (bị fail do account không đủ quyền), review lại toàn bộ project      | 03/04/2026   | 03/04/2026      | AWS CodeBuild, CodePipeline, backend      |


### Kết quả đạt được tuần 12:

* Đã build image, push lên ECR và deploy lên ECS, tích hợp Secret Manager và IAM role cho bảo mật.
* Thiết lập CloudWatch để theo dõi, giám sát hệ thống backend.
* Cấu hình lại các dịch vụ AWS để tối ưu chi phí vận hành.
* Đã kiểm thử lại toàn bộ chức năng hệ thống, phát hiện và xử lý các lỗi còn tồn đọng.
* Thử nghiệm CodeBuild, CodePipeline (bị fail do account không đủ quyền), rút kinh nghiệm về phân quyền và quy trình CI/CD.
* Review, tổng kết lại toàn bộ quá trình triển khai và vận hành hệ thống trên AWS.
* ...
