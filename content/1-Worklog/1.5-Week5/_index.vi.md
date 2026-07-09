---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

- Xử lý các bài toán nâng cao về quy mô hệ thống mạng đám mây thông qua việc xây dựng bộ định tuyến trung tâm AWS Transit Gateway.
- Nắm vững các đặc tính cốt lõi của máy chủ ảo EC2, bao gồm phân loại Instance, cơ chế lưu trữ, hệ thống tự động co giãn và chia sẻ file mạng.
- Triển khai giải pháp đảm bảo an toàn dữ liệu, tự động hóa sao lưu và khôi phục sau thảm họa (Disaster Recovery) với AWS Backup và Amazon SNS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu sâu lý thuyết Module 03 về EC2: Phân loại chip CPU (Intel, AMD, ARM/Graviton) và cách tối ưu chi phí <br> - Phân biệt cơ chế lưu trữ giữa EBS Volume và Instance Store (ổ cứng tạm)                | 18/05/2026   | 18/05/2026      | Khóa học First Cloud AI Journey           |
| 3   | - Tìm hiểu tính năng User Data & Metadata của EC2, cơ chế Auto Scaling & Load Balancing <br> - Nghiên cứu giải pháp lưu trữ mạng chia sẻ (Amazon EFS, FSx) và dịch vụ di trú hệ thống AWS MGN                   | 19/05/2026   | 19/05/2026      | Khóa học First Cloud AI Journey           |
| 4   | - Sử dụng CloudFormation khởi tạo nhanh hạ tầng 4 VPC và 4 máy chủ EC2 <br> - Khởi tạo bộ định tuyến trung tâm Transit Gateway để giải quyết bài toán VPC Peering       | 20/05/2026   | 20/05/2026      | Khóa học First Cloud AI Journey           |
| 5   | - Tạo Transit Gateway Attachments để liên kết 4 VPC vào mạng trung tâm <br> - Cấu hình bảng định tuyến TGW (Associations, Propagations) và cập nhật Route Table của từng VPC trỏ luồng đi qua TGW               | 21/05/2026   | 21/05/2026      | Khóa học First Cloud AI Journey           |
| 6   | - Xây dựng Backup Plan định nghĩa quy tắc sao lưu và khởi tạo Backup Vault mã hóa KMS <br> - Cấu hình Amazon SNS tạo Topic gửi cảnh báo sao lưu về Email quản trị                | 22/05/2026   | 22/05/2026      | Khóa học First Cloud AI Journey           |
| 7   | - Kiểm tra mạng qua Reachability Analyzer và SSH thử nghiệm chéo các VPC. Thực hiện Restore Test khôi phục máy chủ EC2 <br> - Thực hiện quy trình dọn dẹp toàn bộ tài nguyên (Backup, SNS, TGW, CloudFormation) | 23/05/2026   | 23/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

| Thứ | Công việc                               | Kết quả đạt được                                                                                                                                                                                           |
| --- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | Nghiên cứu kiến trúc máy chủ ảo EC2     | Hiểu rõ chiến lược chọn CPU (đặc biệt là dòng chip Graviton tiết kiệm 40% chi phí). Phân biệt được độ sẵn sàng 99.999% của mạng lưu trữ EBS so với tốc độ đọc ghi của ổ cứng vật lý Instance Store.        |
| 3   | Cơ chế co giãn và lưu trữ mạng          | Nắm vững cách tự động chạy script bằng User Data và gọi thông tin nội bộ qua Metadata. Hiểu được cơ chế chia sẻ file chuẩn NFSv4 (EFS) và SMB chống trùng lặp dữ liệu (FSx).                               |
| 4   | Khởi tạo hạ tầng mạng tập trung Lab 20  | Xây dựng thành công Stack CloudFormation dựng sẵn 4 VPC độc lập. Hiểu rõ ưu điểm của mô hình Hub-and-Spoke (Transit Gateway) so với kết nối dạng lưới (Mesh) của VPC Peering.                              |
| 5   | Cấu hình định tuyến AWS Transit Gateway | Liên kết thành công các mạng ảo vào cổng trung tâm thông qua TGW Attachments, thực hiện tự động hóa truyền bá định tuyến (Propagation) và định tuyến thông suốt từ VPC ra TGW.                             |
| 6   | Triển khai giải pháp AWS Backup tự động | Thiết lập thành công kế hoạch sao lưu hệ thống an toàn vào kho chứa Backup-LAB-VAULT, đồng thời kích hoạt thành công tính năng tự động gửi cảnh báo sự cố qua Email bằng Amazon SNS.                       |
| 7   | Kiểm thử hệ thống và tối ưu tài nguyên  | Xác nhận kết nối mạng riêng (Private) thông suốt giữa VPC 1, VPC 2, VPC 3 và VPC 4. Khôi phục máy chủ thành công từ Recovery Point. Dọn dẹp hoàn toàn mọi tài nguyên thực hành để tránh phát sinh chi phí. |

