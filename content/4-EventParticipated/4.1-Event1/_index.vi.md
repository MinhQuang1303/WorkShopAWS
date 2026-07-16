---
title: "Sự kiện 1: AWS Community Day Vietnam 2026"
date: 2026-05-23T17:00:00+07:00
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

# Bài thu hoạch: AWS Community Day Vietnam 2026

### Thông tin sự kiện
- **Tên sự kiện:** AWS Community Day Vietnam 2026
- **Thời gian:** Ngày 23 tháng 05 năm 2026 (08:00 - 17:00)
- **Địa điểm:** Thành phố Hồ Chí Minh, Việt Nam
- **Vai trò tham gia:** Người tham dự (Attendee)

### Mục đích của sự kiện
AWS Community Day là hội nghị công nghệ quy mô lớn được tổ chức bởi cộng đồng AWS User Group Vietnam. Mục tiêu chính của sự kiện bao gồm:
- Chia sẻ các xu hướng công nghệ mới nhất trong hệ sinh thái điện toán đám mây AWS, đặc biệt là Trí tuệ nhân tạo tạo sinh (GenAI), kiến trúc Serverless và thiết kế ứng dụng hiện đại.
- Kết nối các kỹ sư phần mềm, Kiến trúc sư giải pháp (SA), AWS Community Builders và cộng đồng doanh nghiệp công nghệ tại Việt Nam.
- Chia sẻ các giải pháp thực tế tốt nhất (best practices), các bài học chuyển đổi số và chiến lược tối ưu hóa chi phí đám mây từ các doanh nghiệp hàng đầu (GoTymeX, VPBank, Cloud Kinetics,...).

### Nội dung nổi bật từ các bài tham luận

#### 1. Bối cảnh là tất cả - Cách làm cho AI thực sự hoạt động hiệu quả
- **Diễn giả:** Anh Tính Trương (Platform Engineer, GoTymeX)
- **Nội dung chính:**
  - Chỉ ra nguyên nhân cốt lõi khiến các ứng dụng AI thường xuyên gặp hiện tượng "ảo tưởng" (hallucination) không hẳn do mô hình LLM yếu, mà do thiếu hụt ngữ cảnh (Context) cụ thể và phù hợp.
  - Giới thiệu kiến trúc "Prompt to Memory Pipeline" – minh họa cách xây dựng các đường ống tiêm ngữ cảnh động và giải pháp lưu trữ bộ nhớ dài hạn cho AI.
  - Chia sẻ kinh nghiệm làm việc hiệu quả cùng các trợ lý AI và định hướng phát triển kỹ năng cho sinh viên/lập trình viên trẻ trong kỷ nguyên trí tuệ nhân tạo.

#### 2. Trợ lý AI thân thiện với Amazon Quick
- **Diễn giả:** Chị Phạm Ngọc Hải Anh (G-AsiaPacific Vietnam, AWS Community Builder)
- **Nội dung chính:**
  - Phân tích điểm đau (pain points) của doanh nghiệp: Người dùng thuộc khối kinh doanh mất nhiều thời gian tìm kiếm dữ liệu phân mảnh từ nhiều hệ thống khác nhau.
  - Giới thiệu "Amazon Quick", công cụ trợ lý AI được xây dựng trên nền tảng Amazon Bedrock, tích hợp hơn 40 trình kết nối dữ liệu bảo mật và khả năng tìm kiếm web thông minh.
  - Case Study thực tế: Trợ lý dành cho Quản lý dự án (Project Manager) giúp tự động hóa việc tạo biên bản cuộc họp (MoM), dự thảo email và theo dõi tiến độ công việc của lập trình viên.

#### 3. Từ Biên đến Nguồn: Lấy CloudFront làm nền tảng hạ tầng
- **Diễn giả:** Anh Nguyễn Tuấn Thịnh (DevOps Engineer, First Cloud AI Journey)
- **Nội dung chính:**
  - Giải quyết bài toán chi phí khó lường trong mô hình tính phí CDN truyền thống (trả theo lưu lượng sử dụng).
  - Đề xuất mô hình CDN chi phí cố định tối ưu bằng cách kết hợp Amazon CloudFront, AWS WAF, Route 53 và dịch vụ lưu trữ S3 nhằm tối ưu hóa ngân sách hàng tháng cho doanh nghiệp.
  - Đi sâu vào cấu hình nâng cao: Bảo mật lớp biên (AWS Shield, WAF, Mutual TLS, chặn địa lý), thiết lập cơ chế dự phòng nguồn (Origin Failover), hỗ trợ giao thức HTTP/3 (QUIC) và tùy biến logic ở biên bằng CloudFront Functions hoặc Lambda@Edge.

#### 4. 36 giờ cùng LotusHacks: Hiện thực hóa UTMorpho từ ý tưởng
- **Diễn giả:** Đội ngũ UTMorpho (Thành viên tham gia LotusHacks 2026)
- **Nội dung chính:**
  - Chia sẻ hành trình thiết kế và phát triển ứng dụng thiết kế tạo sinh "UTMorpho" chỉ trong khuôn khổ 36 giờ của cuộc thi hackathon.
  - Kiến trúc hệ thống: Frontend ứng dụng React SPA lưu trữ trên S3 và phân phối qua CloudFront; Backend sử dụng API Gateway + Lambda kết nối dữ liệu với S3 và DynamoDB; Động cơ GenAI dựa trên Amazon Bedrock đảm nhận phân tích bản phác thảo hình ảnh, tạo bố cục UI và stream kết quả xem trước mã nguồn React trực tiếp.
  - Bài học kinh nghiệm về xử lý giới hạn token, kiểm soát hiện tượng tạo thừa dữ liệu của AI và kỹ năng làm việc dưới áp lực thời gian cực hạn.

#### 5. Tính bất định của các thiết lập 'Định tính' trên LLM
- **Diễn giả:** Anh Đức Đào (Solution Architect, Cloud Kinetics)
- **Nội dung chính:**
  - Giải thích hiện tượng dù đã cấu hình tham số `temperature = 0` trên các API LLM thương mại, kết quả đầu ra trả về vẫn có tính bất định (non-deterministic).
  - Phân tích nguyên nhân kỹ thuật: Do các phép tính dấu phẩy động trên GPU không có tính kết hợp khi xử lý song song, kết hợp với cơ chế gom cụm yêu cầu động (dynamic batching) trên các nền tảng inference đa người dùng.
  - Chia sẻ chiến lược giảm thiểu rủi ro: Áp dụng kỹ thuật bỏ phiếu số đông (Majority Voting), tự triển khai mô hình với giới hạn runtime định tính, và áp đặt cấu trúc dữ liệu đầu ra (JSON Mode, cấu trúc Regex Grammar).

#### 6. Hệ thống Multi-Agent cấp doanh nghiệp: Bài toán chấm điểm tín dụng Startup
- **Diễn giả:** Chị Vy Lâm (Senior Business Systems Analyst, VPBank)
- **Nội dung chính:**
  - Giải quyết thách thức thiếu hụt dữ liệu tài chính truyền thống khi đánh giá điểm tín dụng cho các doanh nghiệp khởi nghiệp (Startup).
  - Phân tích hạn chế của hệ thống đơn tác tử (Single-Agent): Dễ bị nghẽn ngữ cảnh, khả năng kiểm toán thấp và tỷ lệ thất bại cao đối với các quyết định phức tạp.
  - Đề xuất mô hình "Hội đồng ảo" sử dụng hệ thống Multi-Agent (phân tách các agent chuyên trách về tài chính, rủi ro, phân tích thị trường) để đạt được sự đồng thuận.
  - Kết quả thực tế tại ngân hàng: Tốc độ xử lý hồ sơ tín dụng tăng 95% (từ vài tuần xuống vài giờ), cắt giảm 95% giờ làm việc thủ công của kiểm toán viên và dự kiến mang lại tỷ lệ ROI vượt trội.

### Bài học rút ra & Tư duy tích lũy

#### Tư duy thiết kế kiến trúc đám mây
- **Bảo mật và Tối ưu hóa tại Lớp biên:** CloudFront không chỉ đơn thuần làm nhiệm vụ lưu bộ nhớ đệm (cách tài nguyên tĩnh) mà còn đóng vai trò là lá chắn phòng thủ vòng ngoài cốt lõi. Việc thiết lập S3 Gateway Endpoints và tối ưu hóa các gói phân phối CDN giúp tiết kiệm đáng kể chi phí băng thông truyền tải dữ liệu ra ngoài (network egress fees).
- **Tiếp cận dựa trên giá trị kinh doanh:** Mọi hoạt động triển khai công nghệ, đặc biệt là tích hợp công nghệ AI, phải xuất phát trực tiếp từ bài toán vận hành thực tế của doanh nghiệp để mang lại giá trị thực và ROI, tránh việc chạy theo xu hướng công nghệ thuần túy.

#### Các khái niệm GenAI chuyên sâu
- **Kiểm soát các hạn chế của LLM:** Việc thấu hiểu tính bất định (non-determinism) giúp lập trình viên backend chủ động xây dựng các cơ chế phòng ngừa lỗi và ràng buộc cú pháp chặt chẽ, không phụ thuộc hoàn toàn vào kết quả thô của LLM.
- **Hệ thống đa tác tử (Multi-Agent):** Sự chuyển dịch từ các ứng dụng chatbot nhập liệu đơn lẻ sang hệ thống các Agent tương tác, cộng tác phối hợp là chìa khóa để giải quyết triệt để các bài toán nghiệp vụ phức tạp trong môi trường doanh nghiệp.

### Ứng dụng thực tế vào dự án NodeJ2Car
Những kiến thức thu nhận từ sự kiện đã được tôi nghiên cứu, đối chiếu và áp dụng trực tiếp vào quá trình thiết kế hệ thống backend cho nền tảng linh kiện ô tô **NodeJ2Car**:
- **Bảo mật lớp biên & CDN:** Triển khai lưu trữ frontend React trên dịch vụ S3 và phân phối qua mạng lưới CloudFront kết hợp chứng chỉ bảo mật ACM SSL/TLS cùng tường lửa AWS WAF bảo mật lớp biên, tương ứng với nội dung thực tế hoàn thành ở **Tuần 12**.
- **Xử lý bất đồng bộ tách rời (Decoupled Processing):** Áp dụng hệ thống hàng đợi tin nhắn Amazon SQS ở **Tuần 5** nhằm giảm tải và tiêu thụ dữ liệu webhook từ cổng thanh toán, bảo vệ máy chủ Express chính khỏi các đợt lưu lượng tăng đột biến.
- **Tối ưu hóa API quét hình ảnh bằng AI:** Ứng dụng kỹ thuật làm sạch siêu dữ liệu/tên file và bổ sung các ràng buộc dữ liệu đầu ra bằng mã Regex nghiêm ngặt cho endpoint quét linh kiện AI tại **Tuần 11** để giảm thiểu tối đa tỷ lệ phân loại sai của mô hình AI Bedrock.

### Hình ảnh ghi nhận tại sự kiện
<img src="{{ "images/event1.jpg" | relURL }}" alt="Toàn cảnh hội trường AWS Community Day Vietnam 2026" width="500" style="border-radius: 8px; margin: 15px 0; display: block;">

### Cảm nhận cá nhân
Sự kiện AWS Community Day Vietnam 2026 mang lại bầu không khí công nghệ vô cùng sôi động và nhiệt huyết. Những bài chia sẻ từ các chuyên gia đầu ngành không chỉ giúp tôi mở rộng góc nhìn kỹ thuật về hạ tầng đám mây và AI thực tế, mà còn mở ra cơ hội kết nối, học hỏi quý báu. Đây chính là nguồn động lực lớn cổ vũ tinh thần nghiên cứu của tôi trong suốt giai đoạn thực tập.

---
