---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

- Họp nhóm để phân chia công việc bắt đầu làm dự án

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Họp mặt online để phân chia các công việc cần làm cho dự án FCAJ | 15/6/2026   | 15/6/2026       |
| 3   | - Khởi tạo môi trường AWS Cloud, cấu hình các dịch vụ dùng chung trong Shared Services & Security Zone bao gồm việc thiết lập các chính sách AWS IAM, khởi tạo khóa mã hóa dữ liệu bằng AWS KMS và cài đặt cảnh báo chi phí qua AWS Budgets| 16/6/2026   | 16/6/2026       | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tạo và cấu hình hai bucket lưu trữ chính trên Amazon S3 bao gồm Amazon S3 Frontend để chứa mã nguồn giao diện tĩnh và Amazon S3 Upload đóng vai trò là kho tiếp nhận tài liệu đầu vào| 17/6/2026   | 17/6/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Thiết lập Amazon API Gateway để làm cổng đón nhận các yêu cầu HTTPS, đồng thời cấu hình tường lửa ứng dụng web AWS WAF đứng trước API Gateway nhằm ngăn chặn các cuộc tấn công khai thác lỗ hổng cơ bản.| 18/6/2026   | 18/6/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Khởi tạo dịch vụ quản lý định danh Amazon Cognito, cấu hình User Pool và thiết lập cơ chế xác thực Token JWT (Token Validation) tích hợp trực tiếp vào các route trên Amazon API Gateway để bảo vệ tài nguyên hệ thống.| 19/6/2026   | 19/6/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 9:

Hoàn thành bộ khung hạ tầng đám mây được bảo mật cơ bản, thiết lập xong cơ chế xác thực người dùng bằng Cognito và vận hành trơn tru luồng tải tài liệu lên S3 Upload bucket thông qua cấu chế Presigned URL bảo mật.
