---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---



### Mục tiêu tuần 10:

- Xây dựng được cơ sở dữ liệu đủ để lưu trữ dự án

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Thiết lập cơ sở dữ liệu NoSQL Amazon DynamoDB, tiến hành thiết kế cấu trúc bảng (Tables, Partition Key, Sort Key) tối ưu cho việc lưu trữ thông tin bóc tách từ hóa đơn, danh mục tài liệu và dữ liệu thanh toán.| 22/6/2026   | 22/6/2026|
| 3   | - Cấu hình tính năng Event: ObjectCreated trên Amazon S3 Upload bucket để mỗi khi có tài liệu mới được tải lên, hệ thống sẽ tự động phát sinh một sự kiện và đẩy thông báo này vào hàng đợi thông điệp Amazon SQS.| 23/6/2026   | 23/6/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Khởi tạo hàm AWS Lambda AI-Worker chịu trách nhiệm xử lý logic cốt lõi, đồng thời cấu hình cơ chế Trigger để hàm Lambda này tự động lắng nghe và tiêu thụ (consume) các thông điệp được đẩy tới từ Amazon SQS.| 24/6/2026   | 24/6/2026| <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Viết mã nguồn cho Lambda AI-Worker để tích hợp dịch vụ trí tuệ nhân tạo Amazon Textract, cấu hình tính năng Analyze Queries giúp bóc tách các trường dữ liệu tùy biến theo câu hỏi nghiệp vụ định sẵn từ tài liệu được tải lên.| 25/6/2026| 25/6/2026| <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Bổ sung logic xử lý hậu bóc tách (post-processing) trong hàm Lambda AI-Worker nhằm chuẩn hóa toàn bộ dữ liệu văn bản thu được thành cấu trúc JSON, sau đó thực hiện lệnh ghi dữ liệu (Store JSON Data) vào Amazon DynamoDB.| 26/6/2026| 26/6/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 10:

Trục xử lý thông minh IDP được kích hoạt hoàn toàn tự động và khép kín; hệ thống có khả năng tự bóc tách thông tin có độ chính xác cao từ tài liệu phi cấu trúc thông qua Textract và lưu trữ đồng bộ vào DynamoDB.