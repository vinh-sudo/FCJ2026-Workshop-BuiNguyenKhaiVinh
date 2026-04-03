---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 5:

* Chốt ý tưởng dự án, hoàn thiện proposal và xác định các AWS service cần thiết cho project.
* Thực hành build image, push lên ECR và triển khai ứng dụng lên ECS.
* Tìm hiểu, thực hành xây dựng pipeline CI/CD với CodeBuild, CodePipeline để tự động hóa quy trình build, test, deploy.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                        | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Chốt ý tưởng dự án, hoàn thiện proposal và xác định các AWS service cần thiết cho project                                    | 02/02/2026   | 02/02/2026      |                                           |
| 3   | - Tìm hiểu về Amazon ECR <br> - Build image và push lên ECR                                                                    | 03/02/2026   | 03/02/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Deploy ứng dụng lên ECS: <br>&emsp; + Tạo task definition <br>&emsp; + Tạo cluster <br>&emsp; + Chạy service                 | 04/02/2026   | 04/02/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tạo CodeBuild và CodePipeline cho project                                                                                   | 05/02/2026   | 05/02/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Deploy image lên ECS sử dụng CodeBuild/CodePipeline                                                                         | 06/02/2026   | 06/02/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

* Đã chốt ý tưởng dự án, hoàn thiện proposal và xác định rõ các AWS service cần thiết (ECR, ECS, CodeBuild, CodePipeline, IAM, S3, v.v.).
* Hiểu kiến trúc ECR, biết cách build image Docker và push lên ECR, nắm quy trình xác thực, phân quyền.
* Đã thực hành deploy ứng dụng lên ECS: tạo task definition, cluster, chạy service, kiểm tra log và trạng thái container.
* Tìm hiểu và tạo pipeline CI/CD với CodeBuild, CodePipeline để tự động build, test, deploy image lên ECS.
* Đã thực hành deploy image lên ECS thông qua pipeline, ghi chú lại các lỗi thực tế và cách xử lý (quyền IAM, cấu hình pipeline, buildspec...).
* ...
