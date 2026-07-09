---
title: "Event 1"
date: 2026-06-06
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---


# Báo cáo tổng kết: "FCAJ Community Day"

## Thông tin sự kiện

- **Tên sự kiện:** FCAJ Community Day
- **Ngày:** 06 tháng 06 năm 2026
- **Thời gian:** 09:00 – 12:00
- **Địa điểm:** Bitexco Financial Tower, Thành phố Hồ Chí Minh
- **Vai trò:** Người tham dự

---

# Mục tiêu của sự kiện

FCAJ Community Day được tổ chức nhằm chia sẻ các kiến thức và kinh nghiệm thực tiễn trong các lĩnh vực Cloud Computing, An ninh mạng, DevOps, phát triển phần mềm và kỹ năng làm việc nhóm. Thông qua các bài trình bày từ nhiều diễn giả đang làm việc trong ngành, sự kiện giúp người tham dự tiếp cận các công nghệ và mô hình hệ thống đang được áp dụng thực tế trong doanh nghiệp, đồng thời mở rộng định hướng nghề nghiệp trong lĩnh vực Công nghệ thông tin.

Sự kiện hướng đến các mục tiêu sau:

- Giới thiệu các công nghệ và giải pháp hiện đại trong Cloud và Security.
- Trình bày các kiến trúc hệ thống thực tế trong phát triển phần mềm.
- Chia sẻ kinh nghiệm chuyển đổi nghề nghiệp trong lĩnh vực IT.
- Hướng dẫn ứng dụng công cụ DevOps và container hóa trong triển khai hệ thống.
- Nâng cao kỹ năng làm việc nhóm trong các dự án công nghệ.

---

# Phiên 1: AWS WAF & Machine Learning NIDS

Phiên trình bày của anh Lê Hoàng Gia Đại tập trung vào việc kết hợp AWS WAF với Machine Learning nhằm nâng cao khả năng phát hiện và phòng chống tấn công mạng.

### Nội dung chính

- Phân tích hạn chế của AWS WAF truyền thống khi chỉ dựa trên rule-based detection, khó phát hiện các tấn công mới hoặc Zero-day.
- Giới thiệu hệ thống Network Intrusion Detection System (NIDS) ứng dụng Machine Learning.
- Sử dụng bộ dữ liệu CSE-CIC-IDS2018 để huấn luyện mô hình như LightGBM nhằm phát hiện các hành vi bất thường (Botnet, DoS, Brute Force).
- Kiến trúc hệ thống triển khai trên AWS gồm EC2, S3, Kinesis, Lambda và CloudWatch để thu thập, xử lý và giám sát theo thời gian thực.

### Kiến thức rút ra

- Machine Learning giúp nâng cao khả năng phát hiện tấn công so với phương pháp dựa trên rules truyền thống.
- Kiến trúc AWS hỗ trợ tốt cho các hệ thống giám sát an ninh mạng theo thời gian thực.
- Việc kết hợp nhiều dịch vụ AWS giúp mở rộng khả năng xử lý và phân tích dữ liệu.

---

# Phiên 2: Docker – Công nghệ Container hóa

Phiên trình bày của Huỳnh Bảo giới thiệu về Docker và mô hình Containerization trong phát triển phần mềm hiện đại.

### Nội dung chính

- Khái niệm Containerization: đóng gói ứng dụng cùng toàn bộ dependencies để đảm bảo chạy nhất quán trên mọi môi trường.
- So sánh Containerization và Virtualization, trong đó container nhẹ hơn, nhanh hơn và tiết kiệm tài nguyên hơn.
- Giới thiệu các thành phần của Docker: Docker Image, Dockerfile và Docker Engine.
- Các lệnh cơ bản trong Docker phục vụ quản lý container.
- Ứng dụng Docker trong CI/CD, Microservices và hiện đại hóa hệ thống legacy.

### Kiến thức rút ra

- Docker giúp chuẩn hóa môi trường phát triển và triển khai ứng dụng.
- Containerization là nền tảng quan trọng trong kiến trúc Cloud Native.
- Docker giúp tăng tốc quy trình DevOps và triển khai phần mềm.

---

# Phiên 3: Từ IT Helpdesk đến Senior Sysadmin

Phiên trình bày của anh Trần Trung Vinh chia sẻ về hành trình phát triển sự nghiệp từ IT Helpdesk đến Sysadmin và định hướng Cloud/DevOps.

### Nội dung chính

- Kinh nghiệm làm việc ở vị trí Helpdesk: xử lý sự cố và hỗ trợ người dùng trong môi trường áp lực cao.
- Tự học các nền tảng quan trọng như Linux, Networking và xây dựng môi trường lab thực hành.
- Phát triển tư duy hệ thống: tự động hóa tác vụ lặp lại và xây dựng runbooks.
- Nguyên tắc quan trọng trong vận hành: “Không bao giờ thử nghiệm trên production”.
- Chuyển đổi sang Cloud/DevOps với các công cụ như Terraform (Infrastructure as Code) và Docker.

### Kiến thức rút ra

- Kỹ năng nền tảng là yếu tố quan trọng trong phát triển sự nghiệp IT.
- Tự học và thực hành là chìa khóa để chuyển đổi nghề nghiệp.
- DevOps và tự động hóa là xu hướng tất yếu trong ngành công nghệ.

---

# Phiên 4: Kết nối Godot Client với AWS WebSockets

Phiên trình bày của anh Nguyễn Quốc Bảo tập trung vào việc xây dựng hệ thống game multiplayer trên nền tảng Cloud.

### Nội dung chính

- So sánh các mô hình mạng: UDP/ENet, HTTP Polling và WebSocket.
- Lý do lựa chọn WebSocket cho hệ thống game dạng Lobby/Turn-based.
- Kiến trúc AWS gồm API Gateway (WebSocket), AWS Lambda và DynamoDB.
- Tích hợp WebSocket trong Godot 4 bằng WebSocketPeer và JSON messaging.
- Các vấn đề thực tế như chi phí DynamoDB Scan và xử lý stale connections.

### Kiến thức rút ra

- WebSocket phù hợp cho các ứng dụng realtime như game multiplayer.
- Kiến trúc serverless trên AWS giúp dễ mở rộng hệ thống.
- Thiết kế hệ thống cần tối ưu cả hiệu năng và chi phí.

---

# Phiên 5: Nghệ thuật làm việc nhóm hiệu quả

Phiên trình bày của anh Trương Huy Phước tập trung vào kỹ năng làm việc nhóm trong các dự án công nghệ.

### Nội dung chính

- Bốn nguyên tắc làm việc nhóm hiệu quả:
    - Mục tiêu rõ ràng và thống nhất.
    - Phân công đúng người, đúng việc.
    - Giao tiếp cởi mở và lắng nghe chủ động.
    - Trách nhiệm cá nhân trong công việc.
- Công cụ hỗ trợ: Trello, ClickUp, Google Workspace, Slack và Discord.

### Kiến thức rút ra

- Làm việc nhóm hiệu quả phụ thuộc vào giao tiếp và trách nhiệm cá nhân.
- Công cụ quản lý giúp tối ưu hóa hiệu suất dự án.
- Sự phối hợp tốt giúp nâng cao chất lượng sản phẩm.

---

# Các công nghệ AWS được giới thiệu

Trong suốt sự kiện, các diễn giả đã giới thiệu nhiều công nghệ và công cụ quan trọng:

- AWS WAF
- Machine Learning (LightGBM, NIDS)
- Docker & Containerization
- AWS EC2, S3, Kinesis, Lambda, CloudWatch
- Terraform (IaC)
- AWS API Gateway WebSocket
- AWS Lambda
- DynamoDB
- Godot Engine (WebSocketPeer)    
- Trello, ClickUp, Slack, Discord

Các công nghệ này thể hiện xu hướng phát triển mạnh mẽ của Cloud, DevOps, AI/ML và kiến trúc hệ thống hiện đại.

---

# Những kiến thức đạt được

Sau khi tham gia sự kiện, người tham dự có cái nhìn rõ hơn về cách các hệ thống Cloud và ứng dụng hiện đại được xây dựng và vận hành.

Một số bài học quan trọng gồm:

- AI/ML giúp nâng cao khả năng phát hiện tấn công mạng.
- Docker là nền tảng quan trọng trong kiến trúc Cloud Native.
- Kỹ năng Linux, Networking là nền tảng cho DevOps và Cloud.
- WebSocket là giải pháp hiệu quả cho ứng dụng realtime.
- Làm việc nhóm hiệu quả là yếu tố quan trọng trong dự án công nghệ.

---

# Ứng dụng kiến thức

Những kiến thức thu được có thể áp dụng vào thực tế như:

- Xây dựng hệ thống Cloud sử dụng AWS services.
- Áp dụng Docker trong triển khai ứng dụng.
- Nghiên cứu Machine Learning cho an ninh mạng.
- Phát triển ứng dụng realtime sử dụng WebSocket.
- Áp dụng Terraform để quản lý hạ tầng.
- Cải thiện kỹ năng làm việc nhóm trong dự án phần mềm.

---

# Trải nghiệm tham gia sự kiện

Tham gia **FCAJ Community Day** là một trải nghiệm học tập rất bổ ích vì sự kiện mang lại trải nghiệm học tập thực tiễn, giúp người tham dự tiếp cận các công nghệ hiện đại đang được ứng dụng trong doanh nghiệp. Các bài trình bày kết hợp giữa lý thuyết và thực hành giúp dễ dàng hình dung cách xây dựng hệ thống thực tế.

Đặc biệt, các phiên về Machine Learning trong an ninh mạng và Docker giúp mở rộng góc nhìn về kiến trúc hệ thống Cloud hiện đại, trong khi phiên WebSocket và DevOps mang lại kiến thức thực tiễn về phát triển ứng dụng và vận hành hệ thống.

---

# Kết luận

FCAJ Community Day là một sự kiện mang đến nhiều cơ hội để tiếp cận các xu hướng công nghệ hiện đại trong Cloud Computing, DevOps, AI/ML và phát triển phần mềm. Nội dung không chỉ mang tính học thuật mà còn gắn liền với thực tế triển khai trong doanh nghiệp.

Thông qua sự kiện, người tham dự có thêm kiến thức về kiến trúc hệ thống, công nghệ Cloud, an ninh mạng và kỹ năng làm việc nhóm, từ đó có thể áp dụng vào học tập và định hướng nghề nghiệp trong tương lai.

---

## Hình ảnh sự kiện

![AWS FCAJ Community Day](/images/4-EventParticipated/4.1-Event1/)