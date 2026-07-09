---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

- Thiết kế frontend và dashboard để hoat động ổn định 

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Triển khai hai hàm API đầu tiên thuộc Dashboard APIs Layer là AWS Lambda API-Get-Invoices (lấy danh sách hóa đơn) và AWS Lambda API-Get-Stats (truy xuất số liệu thống kê tổng quan) từ cơ sở dữ liệu DynamoDB.| 29/6/2026   | 29/6/2026|
| 3   | - Hoàn thiện hai hàm API còn lại trong layer là AWS Lambda API-Get-Category (lấy thông tin phân loại tài liệu) và AWS Lambda API-Get-Payment (truy vấn thông tin chi tiết các khoản thanh toán).  | 30/6/2026   | 30/6/2026       | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Thực hiện ánh xạ các HTTP GET Requests trên Amazon API Gateway tới cụm 4 hàm AWS Lambda thuộc Dashboard APIs Layer, cấu hình ánh xạ dữ liệu (mapping templates) và bật tính năng CORS cho API.| 1/7/2026   | 1/7/2026       | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Rà soát và gia cố an toàn thông tin hệ thống, áp dụng nguyên tắc đặc quyền tối thiểu (Least Privilege) cho các vai trò IAM Role, đồng thời cấu hình các luật chặn nâng cao trên AWS WAF để bảo vệ lớp API Dashboard.| 2/7/2026| 2/7/2026| <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Thực hiện kết nối mã nguồn Frontend trên giao diện với lớp API Gateway để hiển thị dữ liệu động (danh sách hóa đơn, biểu đồ thống kê, trạng thái thanh toán) lấy từ cơ sở dữ liệu lên màn hình người dùng. | 3/7/2026   | 3/7/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 11:

Hệ thống Dashboard APIs hoạt động ổn định, giao diện Frontend hiển thị dữ liệu thời gian thực một cách trực quan, toàn bộ kiến trúc Serverless được gia cố bảo mật nghiêm ngặt và sẵn sàng bàn giao đưa vào vận hành.