---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu chiến lược Tuần 6:

- **Nghiên cứu kiến trúc tầng dữ liệu và tối ưu hóa truyền tải:** Đi sâu vào các giải pháp quản trị lưu trữ đối tượng toàn diện, kết hợp các phương thức tăng tốc phân phối nội dung trên quy mô toàn cầu.
- **Thiết kế giải pháp dự phòng và khắc phục thảm họa (Disaster Recovery):** Hoạch định và xây dựng mô hình phục hồi hệ thống dựa trên việc cân bằng các chỉ số cam kết dịch vụ (SLA) cùng hai thông số kỹ thuật cốt lõi là RTO (Recovery Time Objective) và RPO (Recovery Point Objective).
- **Triển khai thực chiến các tính năng lưu trữ nâng cao:** Thực thi cấu hình các đặc tính chuyên sâu của Amazon S3, tích hợp mạng lưới phân phối nội dung (Amazon CloudFront) và thiết lập cơ chế kiểm soát phiên bản (Versioning) nhằm chủ động phòng chống mã độc tống tiền (Ransomware).

### Kế hoạch triển khai chi tiết:

| Thứ | Nội dung công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------------- |
| 2   | - Nghiên cứu lý thuyết Module 04: Bản chất kiến trúc của Object Storage và cơ chế tự động tối ưu hóa vòng đời dữ liệu thông qua S3 Lifecycle Management.<br>- Khảo sát giải pháp lưu trữ lai (Hybrid Storage) với AWS Storage Gateway và các phương thức vận chuyển dữ liệu vật lý quy mô lớn bằng AWS Snow Family. | 25/05/2026   | 25/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |
| 3   | - Cấu hình tính năng Static Website Hosting trên S3 Bucket để phục vụ cho việc lưu trữ và triển khai mã nguồn ứng dụng đơn trang (SPA).<br>- Thiết lập cấu trúc Bucket Policy bằng định dạng JSON nhằm phân quyền truy cập đọc công khai (Public Read Permissions) một cách an toàn. | 26/05/2026   | 26/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |
| 4   | - Tích hợp mạng lưới phân phối nội dung Amazon CloudFront (CDN) nhằm tối ưu hóa tốc độ phản hồi và tải trang cho người dùng cuối.<br>- Cấu hình ẩn giấu máy chủ gốc (S3 Bucket) và thực thi chính sách chặn toàn bộ truy cập công khai trực tiếp (Block Public Access) tại tầng Bucket để thắt chặt an ninh hạ tầng. | 27/05/2026   | 27/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |
| 5   | - Kích hoạt cơ chế kiểm soát phiên bản (Bucket Versioning) nhằm thiết lập hàng rào bảo mật cho dữ liệu trước các cuộc tấn công Ransomware, chống ghi đè hoặc vô tình xóa tài nguyên.<br>- Cấu hình tính năng Cross-Region Replication (CRR) để thiết lập quy trình sao chép dữ liệu bất đồng bộ sang một AWS Region khác, phục vụ mục đích dự phòng địa lý. | 28/05/2026   | 28/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |
| 6   | - Phân tích chuyên sâu 4 chiến lược khắc phục thảm họa (Disaster Recovery) trên nền tảng AWS bao gồm: *Backup & Restore*, *Pilot Light*, *Warm Standby*, và *Multi-Site* để đánh giá mức độ đánh đổi giữa chi phí và thời gian khôi phục. | 29/05/2026   | 29/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |
| 7   | - Thực thi quy trình dọn dẹp tài nguyên nhằm tối ưu hóa chi phí vận hành (Cost Optimization): Vô hiệu hóa (Disable) và loại bỏ (Delete) các CloudFront Distribution; tiến hành làm rỗng (Empty) và xóa bỏ hoàn toàn các S3 Buckets không còn sử dụng. | 30/05/2026   | 30/05/2026      | Khóa học AWS First Cloud AI Journey (FCAJ) 2026 |

### Kết quả đạt được:

| Thứ | Hạng mục triển khai | Giá trị và kết quả ghi nhận |
| --- | ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | Nghiên cứu công nghệ lưu trữ dữ liệu | Làm chủ bản chất kiến trúc của Amazon S3 dưới dạng lưu trữ đối tượng ngang hàng không phân cấp thư mục. Nắm vững phương thức vận hành của các dòng Storage Gateway (File, Volume, Tape) để thiết lập kết nối đồng bộ giữa môi trường On-Premises và Cloud. |
| 3   | Triển khai Static Website | Khởi tạo hoàn chỉnh S3 Bucket và kích hoạt thành công tính năng phân phối ứng dụng đơn trang (SPA) dựa trên chính sách phân quyền truy cập đọc công khai được kiểm soát chặt chẽ. |
| 4   | Tích hợp mạng CDN CloudFront | Làm chủ quy trình xây dựng kiến trúc website tĩnh hiệu năng cao; ứng dụng thành công cơ chế bảo mật của hạ tầng CDN CloudFront để bao bọc và bảo vệ toàn diện cho máy chủ gốc S3 khỏi các rủi ro lộ lọt an ninh. |
| 5   | Triển khai các tính năng lưu trữ nâng cao | Thiết lập thành công cơ chế lưu trữ đa phiên bản cho đối tượng (Versioning), đồng thời xây dựng quy trình tự động sao chép dự phòng địa lý bất đồng bộ (CRR) sang một vùng AWS khác một cách ổn định. |
| 6   | Thiết lập chính sách Khắc phục sự cố | Nắm vững tư duy thiết kế, phân tích và triển khai các giải pháp phục hồi dữ liệu đám mây toàn diện, đảm bảo hệ thống đáp ứng các tiêu chuẩn an ninh mạng quốc tế và cam kết thời gian hoạt động của doanh nghiệp. |
| 7   | Tối ưu hóa chi phí và dọn dẹp tài nguyên | Thực thi nghiêm ngặt quy trình giải phóng tài nguyên hệ thống; xóa sạch hoàn toàn các đối tượng, các phiên bản ẩn bên trong Bucket cùng các Distribution đã tạo, đảm bảo không phát sinh chi phí ngoài ý muốn trên tài khoản AWS. |