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

# Báo cáo thu hoạch: Ngày hội Cộng đồng HCM_FCAJ 2026 (AWS Community Day)

### Thông tin sự kiện
- **Tên sự kiện:** Ngày hội Cộng đồng HCM_FCAJ 2026 (FCAJ Community Day)
- **Thời gian:** Thứ Bảy, 23/05/2026 (08:00 - 17:00)
- **Địa điểm:** Văn phòng AWS Việt Nam, Tầng 26 & Tầng 36, Tòa nhà Bitexco / MPlaza, Thành phố Hồ Chí Minh, Việt Nam
- **Quy mô:** Hơn 500 người tham dự (Lấp đầy toàn bộ hội trường chính tầng 26, phát trực tiếp sang khu vực tầng 36)
- **Vai trò:** Sinh viên thực tập / Người tham dự

---

### Mục Đích Của Sự Kiện
Ngày hội Cộng đồng HCM_FCAJ 2026 là sự kiện công nghệ quy mô lớn quy tụ hơn 500 sinh viên, kỹ sư đám mây và những người đam mê AI tại TP.HCM. Các mục tiêu chính của sự kiện bao gồm:
- Chia sẻ kiến thức thực chiến về sự kết hợp giữa **Cloud & Generative AI (GenAI)**, tối ưu hóa hạ tầng đám mây AWS và phát triển ứng dụng hiện đại.
- Tạo môi trường kết nối (networking) mạnh mẽ giữa sinh viên chương trình **First Cloud AI Journey (FCAJ)**, các diễn giả giàu kinh nghiệm và chuyên gia kiến trúc giải pháp AWS.
- Truyền cảm hứng học tập liên tục thông qua trải nghiệm thực tế từ các cuộc thi Hackathon và case study triển khai đám mây trong doanh nghiệp.

---

### Tóm Tắt Nội Dung Các Bài Thuyết Trình Nổi Bật

Sự kiện bao gồm 6 phiên tham luận chuyên sâu xoay quanh hai trụ cột chính: **Hạ tầng đám mây (Cloud Infrastructure)** và **Trí tuệ nhân tạo (Generative AI)**.

#### 1. Context Is Everything - Making AI Actually Work for You
- **Diễn giả:** Anh Tịnh Trương (Platform Engineer, GoTymeX)
- **Nội dung chính:**
  - Phân tích lý do các ứng dụng AI thường gặp hiện tượng ảo giác (hallucination) xuất phát từ việc thiếu Ngữ cảnh (Context) cụ thể hơn là do mô hình LLM yếu.
  - Giới thiệu kiến trúc "Prompt to Memory Pipeline", trình diễn cách đưa ngữ cảnh động (dynamic context injection) và tích hợp bộ nhớ dài hạn cho quy trình làm việc AI thực tế trong doanh nghiệp.

#### 2. Friendly AI Assistant w/ Amazon Quick
- **Diễn giả:** Chị Phạm Ngọc Hải Anh (G-AsiaPacific Vietnam, AWS Community Builder)
- **Nội dung chính:**
  - Giải quyết rào cản trong doanh nghiệp khi người dùng tốn nhiều thời gian tra cứu dữ liệu phân mảnh ở nhiều hệ thống khác nhau.
  - Giới thiệu "Amazon Quick", trợ lý AI phát triển trên nền tảng **Amazon Bedrock**, tích hợp hơn 40 cổng kết nối dữ liệu an toàn và khả năng tìm kiếm web thông minh.
  - Trình diễn trợ lý quản lý dự án (PM) tự động tạo Biên bản cuộc họp (MoM), gửi email nhắc lịch và đồng bộ tiến độ của lập trình viên.

#### 3. From Edge to Origin: CloudFront as Your Foundation
- **Diễn giả:** Anh Nguyễn Tuấn Thịnh (DevOps Engineer, First Cloud AI Journey)
- **Nội dung chính:**
  - Giải quyết bài toán chi phí CDN thiếu ổn định bằng mô hình gói cước cố định kết hợp **Amazon CloudFront**, **AWS WAF**, **Route 53** và **S3**.
  - Nhấn mạnh các cơ chế bảo mật biên (AWS Shield, WAF, Mutual TLS, chặn địa lý), cấu hình Origin Failover, hỗ trợ HTTP/3 (QUIC) và tùy biến logic tại vùng biên với CloudFront Functions / Lambda@Edge.

#### 4. 36 hrs with LotusHacks: Building UTMorpho from Idea to Reality
- **Đại diện đội thi:** UTMorpho Team (Thành viên tham dự LotusHacks 2026)
- **Nội dung chính:**
  - Chia sẻ hành trình 36 giờ thiết kế và phát triển ứng dụng Generative Design "UTMorpho" tại cuộc thi Hackathon.
  - Chi tiết kiến trúc Serverless: React SPA trên S3 + CloudFront, API Gateway + Lambda + DynamoDB, sử dụng Amazon Bedrock để phân tích bản phác thảo hình ảnh thành mã nguồn giao diện React xem trực tiếp.

#### 5. Non-Determinism of 'Deterministic' LLM Settings
- **Diễn giả:** Anh Đức Đào (Solution Architect, Cloud Kinetics)
- **Nội dung chính:**
  - Giải thích nguyên nhân kết quả trả về của LLM không hoàn toàn đồng nhất dù đã đặt tham số `temperature = 0`.
  - Phân tích góc độ kỹ thuật: Do tính chất không kết hợp của phép toán số thực dấu phẩy động trên GPU khi tính toán song song và cơ chế gom cụm yêu cầu động (dynamic request batching).
  - Đề xuất giải pháp: Sử dụng cơ chế bầu chọn đa số (Majority Voting), tự host mô hình với cấu hình deterministic chặt chẽ và ràng buộc định dạng đầu ra (JSON Mode / Regex).

#### 6. Enterprise-Grade Multi-Agent System: The Case of Startup Credit Scoring
- **Diễn giả:** Chị Vy Lâm (Senior Business Systems Analyst, VPBank)
- **Nội dung chính:**
  - Giải quyết bài toán đánh giá điểm tín dụng cho các doanh nghiệp khởi nghiệp thiếu lịch sử tài chính truyền thống.
  - Chứng minh việc thay thế 1 Agent đơn lẻ bằng **Hệ thống đa tác nhân (Multi-Agent System)** chuyên biệt giúp rút ngắn thời gian xử lý hồ sơ từ vài tuần xuống còn vài giờ (nhanh hơn 95%) với độ minh bạch cao.

---

### Những Bài Học Rút Ra & Trải Nghiệm Thực Tế

1. **Tư Duy Kiến Trúc & Hạ Tầng Đám Mây:**
   - **Tối ưu hóa bảo mật tại vùng biên:** CloudFront đóng vai trò là lớp phòng vệ biên thiết yếu (Security at Edge) giúp chặn các cuộc tấn công DDoS và giảm tải cho máy chủ Backend, thay vì chỉ đơn thuần là bộ nhớ đệm tài nguyên tĩnh.
   - **Quản lý hạn chế của LLM:** Hiểu rõ tính chất không đồng nhất của mô hình ngôn ngữ lớn giúp lập trình viên thiết kế các cơ chế dự phòng và kiểm soát dữ liệu đầu ra chặt chẽ khi tích hợp AI vào API.

2. **Tinh Thần Cộng Đồng & Kết Nối:**
   - Cảm nhận nguồn năng lượng học tập tích cực từ hơn 500 người tham dự tại hai tầng hội trường sự kiện tạo thêm nhiều động lực cho hành trình thực tập.
   - Củng cố tư duy "Business-First": Công nghệ và AI phải xuất phát từ nhu cầu thực tế của doanh nghiệp để tối ưu quy trình vận hành và mang lại giá trị ROI rõ ràng.

---

### Ứng Dụng Thực Tế Vào Dự Án Thực Tập (NodeJ2Car)
- **Phân phối nội dung & Bảo mật biên:** Triển khai ứng dụng React Frontend lên S3 kết hợp CloudFront CDN, AWS WAF và chứng chỉ SSL/TLS (ACM) để bảo mật ứng dụng.
- **Xử lý tác vụ bất đồng bộ:** Áp dụng tư duy phân tách hệ thống (decoupling) qua hàng đợi Amazon SQS để tiếp nhận webhook và tránh gây tắc nghẽn cho máy chủ Express chính.

---

### Hình ảnh ghi nhận tại sự kiện
<img alt="AWS Community Day Vietnam 2026" src="../../../images/event1.jpg">

---

