---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Làm chủ tư duy phát triển hệ thống lớn thông qua việc thiết lập kiến trúc hướng sự kiện bất đồng bộ phối hợp giữa SQS và SNS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu dịch vụ hàng đợi thông báo AWS SQS (Simple Queue Service): Standard vs FIFO queues.                                                                                          | 25/05/2026   | 25/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu dịch vụ đẩy tin nhắn AWS SNS (Simple Notification Service): Topics, Subscriptions, Push notification.                                            | 26/05/2026   | 26/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Nghiên cứu AWS EventBridge phục vụ quản lý, định tuyến sự kiện toàn hệ thống và AWS Step Functions quản lý workflow. | 27/05/2026   | 27/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Thực hành tạo một mô hình Event-driven đơn giản: Gửi tin nhắn vào SQS để kích hoạt xử lý tuần tự.                  | 28/05/2026   | 28/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Cấu hình SNS topic gửi email thông báo tự động đến người quản trị khi có sự cố phát sinh.                                                                                      | 29/05/2026   | 29/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 7   | - Kết hợp SQS và SNS để xây dựng mô hình phân phối tin nhắn đồng thời (Fan-out architecture) ứng dụng trong xử lý giao dịch.                                                                                    | 30/05/2026   | 30/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
### Kết quả đạt được tuần 6:
*  Hiểu rõ tầm quan trọng của Loosely Coupled Architecture (Kiến trúc giảm liên kết) trong hệ thống lớn.
* Triển khai thành công kiến trúc Fan-out đồng bộ dữ liệu bằng cách kết hợp SQS và SNS.
* Tự động hóa luồng gửi mail thông báo đẩy cho các tác vụ bất đồng bộ.
