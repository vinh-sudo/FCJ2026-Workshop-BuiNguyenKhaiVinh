---
title: "Xác thực, bảo mật & secrets"
weight: 6
---

# 6.6 Xác thực, bảo mật & quản lý secrets

Phần này mô tả cách hệ thống IMS xử lý xác thực, phân quyền, bảo mật mạng
và quản lý thông tin nhạy cảm (secrets).

## Xác thực & phân quyền

- Backend sử dụng **Spring Security** để bảo vệ API và kiểm soát truy cập theo vai trò.
- Các vai trò chính:
  - `ADMIN` – quản trị hệ thống.
  - `MANAGER` – lập kế hoạch và theo dõi sản xuất.
  - `LINE_LEADER` – thực thi công việc trên line.
- Frontend tích hợp với API auth thông qua `authService` và lưu token ở phía client.

Bạn có thể mở rộng thiết kế auth hiện tại bằng cách tích hợp **Amazon Cognito** làm identity provider:
- User Pool để quản lý user và trang đăng nhập hosted UI.
- Cognito phát hành JWT, backend Spring Boot kiểm tra và ánh xạ quyền.
- Phân quyền chi tiết hơn qua group Cognito map với role của ứng dụng.

## Bảo mật mạng

- Tất cả service chạy trong **VPC** riêng.
- **Security Group** giới hạn traffic:
  - ALB cho phép HTTP/HTTPS từ internet.
  - ECS chỉ nhận traffic từ ALB.
  - RDS chỉ nhận traffic từ ECS (và máy quản trị nếu cần).
- Khuyến nghị: ECS và RDS ở private subnet, ALB và NAT gateway ở public subnet.

## IAM Role & Quyền truy cập

- **ECS Task Role**:
  - Đọc secrets từ **AWS Secrets Manager**.
  - Truy cập S3 (đọc/ghi tài liệu sản xuất nếu cần).
  - Gửi/nhận message với SQS/SNS.
  - Gửi email qua SES.
- **Role cho CI/CD** (CodeBuild / CodePipeline):
  - Quyền pull/push image ECR.
  - Cập nhật ECS service & task definition.
  - Upload artifact lên S3.

Luôn tuân thủ nguyên tắc **least privilege** và tránh dùng policy `*:*` trong môi trường production.

## Quản lý secrets

Sử dụng **AWS Secrets Manager** để lưu trữ:
- Thông tin đăng nhập database (username, password).
- JWT signing key hoặc OAuth client secret.
- Thông tin SMTP/Access key cho SES.
- API key cho dịch vụ AI (nếu có).

Trong ECS Task Definition, tham chiếu secrets bằng:
- Biến môi trường lấy từ Secrets Manager.
- Hoặc ứng dụng gọi AWS SDK với quyền của task role.

Không hard-code secrets trong:
- Source code.
- Docker image.
- Frontend bundle.

Với mô hình xác thực, mạng, IAM và secrets như vậy, hệ thống IMS có thể đáp ứng
các yêu cầu bảo mật phổ biến trong môi trường doanh nghiệp.

