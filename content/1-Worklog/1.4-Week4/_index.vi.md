---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 4:

* Tìm hiểu kiến trúc serverless với Lambda và cách xây dựng hàm xử lý sự kiện trên AWS.
* Thực hành tích hợp Lambda với API Gateway để xây dựng RESTful API.
* Làm quen với quy trình CI/CD tự động hóa triển khai Lambda/API Gateway bằng GitHub Actions, CodeBuild, CodePipeline.
* Hiểu vai trò của IAM Role/Policy khi tích hợp các dịch vụ AWS và đảm bảo bảo mật cho pipeline.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                        | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu và thực hành AWS Lambda                                                                                            | 27/01/2026   | 27/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu về API Gateway                                                                                                     | 28/01/2026   | 28/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tạo thử Lambda tích hợp với API Gateway                                                                                     | 29/01/2026   | 29/01/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu về CI/CD: GitHub Actions, AWS CodeBuild, AWS CodePipeline                                                         | 30/01/2026   | 30/01/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

* Hiểu rõ kiến trúc serverless với AWS Lambda: function được thực thi theo sự kiện, không cần quản lý hạ tầng, tự động scale, chỉ trả phí theo số lần gọi.
* Đã thực hành tạo Lambda function, so sánh ưu nhược điểm, hiểu về handler, môi trường thực thi, giới hạn timeout, memory, và cách debug log qua CloudWatch.
* Nắm được các trigger phổ biến cho Lambda: test trực tiếp, trigger qua API Gateway, S3...
* Tìm hiểu API Gateway: phân biệt REST API, HTTP API; hiểu về resource, method, mapping template, cấu hình CORS.
* Đã thực hành tích hợp Lambda với API Gateway, tạo endpoint RESTful, kiểm thử qua Postman, hiểu luồng request/response, các lỗi thường gặp (timeout, mapping, quyền IAM thiếu) và cách khắc phục.
* Hiểu về mô hình CI/CD trên AWS: pipeline tự động hóa build, test, deploy cho Lambda/API Gateway.
* Đã thực hành kết nối GitHub Actions với AWS, sử dụng CodeBuild để build/test, CodePipeline để tự động deploy.
* Nhận diện vai trò của IAM Role/Policy khi tích hợp các dịch vụ AWS, biết cách cấp quyền tối thiểu cần thiết cho pipeline hoạt động an toàn.
* Ghi chú lại các bước thực hành, các lỗi phát sinh thực tế và cách xử lý khi triển khai CI/CD.
* ...
