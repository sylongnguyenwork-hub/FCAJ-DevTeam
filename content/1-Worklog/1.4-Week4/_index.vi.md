---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

-Xây dựng giải pháp Hybrid DNS sử dụng Route 53 Resolver nhằm thiết lập cơ chế đồng bộ và nhất quán giữa môi trường điện toán đám mây AWS với hệ thống On-Premises truyền thống.

-Khởi tạo và cấu hình kết nối ngang hàng VPC Peering, cho phép các mạng ảo thiết lập kênh giao tiếp nội bộ an toàn và bảo mật cao mà không cần định tuyến qua môi trường Internet công cộng.

-Ứng dụng các nguyên tắc an ninh theo mô hình Zero Trust kết hợp quản trị tài nguyên chặt chẽ nhằm tối ưu hóa chi phí vận hành hạ tầng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                 | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - nghiên cứu nền tảng lý thuyết về cơ chế phân giải tên miền lai (Hybrid DNS) giữa nền tảng đám mây và hệ thống vật lý. Phân tích chuyên sâu dịch vụ Route 53 Resolver, làm rõ nguyên lý hoạt động cũng như phương thức thiết lập các điểm cuối Inbound và Outbound Endpoints        | 11/05/2026   | 11/05/2026      | Khóa học First Cloud AI Journey           |
| 3   | - Sử dụng công cụ CloudFormation để tự động hóa việc khởi tạo hạ tầng và triển khai hệ thống AWS Managed Microsoft AD đóng vai trò giả lập cho DNS Server của môi trường On-Premises| 12/05/2026   | 12/05/2026      | Khóa học First Cloud AI Journey           |
| 4   | - Thực hiện khảo sát và lên phương án hoạch định không gian địa chỉ cho hai phân vùng mạng mạng My VPC và HG VPC, đảm bảo các dải IP được phân tách độc lập, không xảy ra hiện tượng chồng lấn CIDR| 13/05/2026   | 13/05/2026      | Khóa học First Cloud AI Journey           |
| 5   | - CÁp dụng các bộ quy tắc kiểm soát truy cập trên Network ACL để thắt chặt an ninh tại tầng mạng (Subnet)| 14/05/2026   | 14/05/2026      | Khóa học First Cloud AI Journey           |
| 6   | - Thực hiện cập nhật bổ sung các bản ghi định tuyến trên Route Tables nhằm chuyển hướng chính xác lưu lượng thông tin qua kết nối Peering| 15/05/2026   | 15/05/2026      | Khóa học First Cloud AI Journey           |
| 7   | - Cấu hình chi tiết các luật dịch vụ trong Security Group (Luật Inbound) và áp dụng chính sách IAM Policies nhằm phân quyền tối thiểu dựa theo mô hình bảo mật Zero Trust| 16/05/2026   | 16/05/2026      | Khóa học First Cloud AI Journey|

### Kết quả đạt được tuần 4:

| Thứ | Công việc                                | Kết quả đạt được                                                                                                                                                                          |
| --- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | Nghiên cứu lý thuyết Hybrid DNS          | Đã làm chủ được nguyên lý vận hành của dịch vụ Route 53 Resolver                             |
| 3   | Triển khai Lab 10 và kiểm tra hệ thống   | Khởi tạo thành công các điểm cuối trao đổi dữ liệu (Inbound/Outbound Endpoints) cùng hệ thống quy tắc chuyển tiếp dành riêng cho không gian |
| 4   | Quy hoạch hạ tầng VPC Peering            | Hoàn thành thiết lập phân vùng mạng ổn định                              |
| 5   | Thiết lập luồng kết nối ngang hàng       | Thiết lập thành công và đưa trạng thái kết nối của Peering Connection sang chế độ Active.|
| 6   | Định tuyến liên mạng và Cross-Peer DNS   |Hoàn thành cấu hình bảng định tuyến hai chiều, cho phép các thực thể ảo EC2 liên lạc nội bộ trực tiếp. Việc kích hoạt thành công tính năng Cross-Peer DNS giúp tối ưu hóa đáng kể tốc độ phản hồi và phân giải địa chỉ Private giữa các máy chủ.                           |
| 7   | Quản trị bảo mật và tối ưu hóa ngân sách | Nâng cao tư duy xử lý sự cố (troubleshooting) trên hệ thống mạng phức tạp. Tuân thủ nghiêm ngặt quy trình tối ưu chi phí thông qua việc xóa bỏ toàn bộ máy chủ EC2|
