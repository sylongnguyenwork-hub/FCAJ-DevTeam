---
title: "Event1"
date: 2026-05-26
weight: 3
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch “AWS First Cloud AI Journey Community Day”

### Mục Đích Của Sự Kiện

Nền tảng toán học và quản trị Agentic AI: Đi sâu vào bản chất cấu trúc hạ tầng đứng sau các mô hình ngôn ngữ lớn (LLM), cơ chế tối ưu hóa kỹ thuật xử lý ngữ cảnh (Context Engineering), và phương thức thiết kế hệ thống Multi-Agent (Đa tác nhân) phối hợp trong môi trường doanh nghiệp phức tạp.

Tối ưu hóa và bảo mật hạ tầng Cloud: Khảo sát các mô hình kiến trúc tiên tiến nhằm cân bằng cán cân chi phí - hiệu năng, củng cố rào dậu an ninh từ các điểm phân phối vùng biên (Edge) cho tới máy chủ gốc (Origin).

Tư duy sản phẩm và áp lực thực chiến: Phân tích hành trình chuyển dịch tư duy từ các mô hình học thuật mang tính thử nghiệm sang các sản phẩm thương mại hoàn chỉnh thông qua áp lực mô phỏng từ các cuộc thi Hackathon tốc độ cao, từ đó đáp ứng các tiêu chí khắt khe của thị trường lao động toàn cầu.
### Danh Sách Diễn Giả & Đội Thi

- **Duc Dao** - Solution Architect, Cloud Kinetics
- **Vy Lam** - Senior Business Systems Analyst, VPBank
- **Tinh Trương** - Platform Engineer, GoTymeX
- **Pham Ng Anh Hai** - G-AsiaPacific Vietnam, AWS Community Builder
- **Nguyen Tuan Thinh** - DevOps Engineer
- **Đội thi UTMorpho** - Thí sinh cuộc thi LotusHacks 2026
---
### Nội Dung

#### 1. Tính Bất Định Của Cấu Hình "Định Tính" Trong LLM (Diễn giả Duc Dao)

Dưới sự dẫn dắt của diễn giả Duc Dao, bản chất thực sự của các mô hình LLM đã được bóc tách dưới góc độ một Probabilistic Engine (Động cơ xác suất). Quá trình sinh văn bản của LLM thực chất là chuỗi các phép tính toán điểm số thô (Logits) cho toàn bộ từ điển tại mỗi bước tạo token, trước khi chuẩn hóa thành xác suất thông qua hàm toán học Softmax phục vụ cho việc lấy mẫu.

#### 2. Hệ Thống Multi-Agent Cấp Doanh Nghiệp - Chấm Điểm Tín Dụng Startup (Diễn giả Vy Lam)

Diễn giả Vy Lam đã mang đến một case study thực tế về sự lệch pha dữ liệu (Structural Mismatch) giữa hệ thống tài chính truyền thống và các doanh nghiệp khởi nghiệp (Startup). Trong khi các ngân hàng yêu cầu khắt khe về tài sản thế chấp và báo cáo tài chính kiểm toán tối thiểu 3 năm, thì giá trị của Startup lại nằm ở các nguồn dữ liệu phi cấu trúc và đa chiều như tài sản trí tuệ (IP), năng lực đội ngũ, tốc độ tiêu tiền (Burn rate) hay thời gian sống sót của dòng tiền (Runway).

#### 3. Context Is Everything - Đưa AI Vào Vận Hành Thực Tế (Diễn giả Tinh Trương)
Theo góc nhìn của diễn giả Tinh Trương, ngữ cảnh chính là yếu tố quyết định sự thành bại khi đưa AI vào vận hành thực tế. Một bộ khung ngữ cảnh tiêu chuẩn (Context Framework) bắt buộc phải cấu thành từ 4 cột trụ cốt lõi:

Goal (Mục tiêu): Xác định rõ ràng trạng thái đầu ra mong muốn.

Relevant Info (Thông tin liên quan): Thanh lọc và chỉ cung cấp các dữ liệu có giá trị trực tiếp cho tác vụ.

Constraints (Ràng buộc): Thiết lập các giới hạn kỹ thuật, phong cách ngôn ngữ và định dạng.

Success Criteria (Tiêu chí thành công): Định nghĩa thước đo chất lượng của kết quả đầu ra.
#### 4. Friendly AI Assistant w/ Amazon Quick (Diễn giả Pham Ng Anh Hai)

Nhằm giải quyết triệt để những "nỗi đau" cố hữu của người dùng khối kinh doanh (Business Users) khi phải xử lý thủ công các nguồn dữ liệu rời rạc và các tác vụ văn phòng lặp đi lặp lại, diễn giả Pham Ng Anh Hai đã giới thiệu giải pháp Agentic AI Enterprise dựa trên nền tảng Amazon Quick Suite.

#### 5. CloudFront as Your Foundation - Tối Ưu Hóa Từ Vùng Biên Đến Server Gốc (Diễn giả Nguyen Tuan Thinh)
Diễn giả Nguyen Tuan Thinh đã phân tích một trong những rủi ro lớn nhất đối với các nhà sáng lập công nghệ: nguy cơ đối mặt với các hóa đơn chi phí hạ tầng đột biến (Bill Spikes) lên tới hàng trăm nghìn USD do lưu lượng truy cập tăng vọt bất thường hoặc do các cuộc tấn công từ chối dịch vụ.
#### 6. Hành Trình 36 Giờ Biến Ý Tưởng Thành Thực Tế Tại LotusHacks 2026 (Đội thi UTMorpho)

Chia sẻ từ đội thi UTMorpho đã phác họa một bức tranh chân thực về áp lực và tư duy phát triển sản phẩm trong một chiến dịch Sprint kéo dài 36 giờ liên tục. Đi lên từ những bối rối ban đầu, đội thi đã rút ra một triết lý sâu sắc: Ý tưởng giá trị nhất không đến từ các học thuyết vĩ mô, mà xuất phát từ việc nhìn thẳng vào sự ức chế và các nút thắt trong công việc thực tế hàng ngày (Real Frustration Creates Real Ideas).

### Những Gì Học Được

Ngữ cảnh là nền tảng của trải nghiệm (Context is the Experience): Ngữ cảnh cấu hình không đơn thuần là dữ liệu đầu vào bổ sung, mà đóng vai trò là kiến trúc cốt lõi định hình nên trải nghiệm sản phẩm AI. Việc cung cấp một bộ khung ngữ cảnh chuẩn xác giống như cách một người thầy chuẩn bị giáo án, giúp mô hình AI tối ưu hóa năng lực xử lý một cách hiệu quả nhất.

Tầm nhìn kiến trúc tổng thể (Enterprise Mindset): Việc đưa trí tuệ nhân tạo vào vận hành trong các doanh nghiệp quy mô lớn không đơn thuần là việc viết các câu lệnh Prompt hay, mà là một bài toán tổng hòa mang tính hệ thống. Bài toán này đòi hỏi sự đồng chuẩn của các yếu tố bảo mật (Xác thực, Phân quyền IAM tối thiểu), quản trị an toàn dữ liệu (Guardrails) và tự động hóa toàn vẹn hạ tầng (Terraform/Platform Engineering).

#### Thực Thực Trạng Thị Trường Lao Động
Thị trường tuyển dụng trong lĩnh vực công nghệ đang trải qua giai đoạn sàng lọc và bão hòa khốc liệt. Các doanh nghiệp hiện tại hoàn toàn không có nhu cầu tuyển dụng những nhân sự chỉ dừng lại ở mức độ hiểu biết lý thuyết sách vở hoặc chỉ có khả năng xây dựng các bản Demo mang tính chất "đồ chơi".

Chiến lược hành động không trì hoãn: Với tốc độ phát triển công nghệ hiện tại, năng lực của AI đang ghi nhận mức tăng trưởng lũy tiến (gấp đôi sau mỗi 4 tháng). Việc trì hoãn học tập và thực hành thực tế dù chỉ trong một khoảng thời gian ngắn (một tuần hoặc một tháng) sẽ vô tình tạo ra một khoảng cách thế hệ về mặt năng lực cực kỳ lớn, khiến nhân sự nhanh chóng bị đào thải khỏi guồng quay của ngành.

### Ứng Dụng Vào Công Việc

Chuẩn hóa quy trình kỹ nghệ câu lệnh (Prompt Engineering): Áp dụng triệt để bộ khung Context Framework (Goal, Relevant Info, Constraints, Success Criteria) cho toàn bộ các tác vụ tương tác với AI của bản thân và đội ngũ; kiên quyết loại bỏ thói quen thảo luận lan man nhiều chủ đề trên cùng một luồng hội thoại nhằm tối ưu hóa chất lượng phản hồi của mô hình.

Tối ưu hóa cấu hình hệ thống LLM (Refactoring LLM Configuration): Tiến hành rà soát và cấu hình lại toàn bộ các ứng dụng LLM hiện tại. Thay vì áp dụng mức Temperature cố định bằng 0 (dễ dẫn đến các lỗi lặp từ do sai số tính toán song song), thực hiện điều chỉnh tham số về mức Temperature = 0.1 kết hợp tinh chỉnh bộ chỉ số Repeat Penalty nhằm tìm ra "điểm ngọt" (Sweet Spot) tối ưu giữa độ ổn định dữ liệu và tính linh hoạt ngôn ngữ.

### Trải nghiệm trong event

Phá vỡ các ảo tưởng mang tính lý thuyết: Việc được chứng kiến trực diện các kịch bản sai lệch kết quả do kỹ thuật xử lý Batching của các nhà cung cấp Cloud API lớn, hay lỗi lặp chuỗi từ khi thiết lập Temperature = 0 đã giúp tôi đập tan những tư duy lý thuyết màu hồng, từ đó xây dựng một thế quan sát cẩn trọng và thực tế hơn khi bắt tay vào thiết kế kiến trúc hệ thống.

Thấu hiểu chiều sâu tư duy doanh nghiệp (Enterprise Mindset): Thông qua mô hình chấm điểm tín dụng Startup của chị Vy Lam và bài toán tối ưu hóa hạ tầng của anh Tinh Trương, tôi nhận ra giá trị cốt lõi của một người kỹ sư công nghệ không nằm ở việc tạo ra những câu Prompt hào nhoáng, mà khẳng định ở năng lực đóng gói sản phẩm an toàn, bảo mật, tự động hóa bằng mã nguồn và đem lại các giá trị kinh tế thực tiễn cho tổ chức.

> Tổng kết lại, sự kiện đã giúp em hiểu rõ được doanh nghiệp cần gì , cách sử dụng AI hiểu quả ,sử dụng AI mới một cách tối ưu hiệu quả hơn , thử thách với bản thân qua các cuộc thi : lấy bài toán kinh doanh làm gốc, dùng sản phẩm thực tế làm câu trả lời, và luôn xây dựng hệ thống với tư duy sẵn sàng xử lý tính bất định của công nghệ tương lai.

![](_image/image2.jpg)