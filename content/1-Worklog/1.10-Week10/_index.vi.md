---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---



### Mục tiêu tuần 10:

* Nâng cấp hệ thống bảo mật theo tiêu chuẩn doanh nghiệp và tiến hành thử nghiệm khả năng chịu tải thực tế của trang web.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu và cấu hình AWS WAF (Web Application Firewall) để bảo vệ Web Cầu Lông Vui khỏi các cuộc tấn công phổ biến (SQL Injection, XSS).                                                                                             | 22/06/2026   | 22/06/2026      |<https://cloudjourney.awsstudygroup.com/> |
| 3   | - Cấu hình SSL/TLS mã hóa lưu trữ bằng AWS Certificate Manager (ACM) tích hợp vào Application Load Balancer để chạy HTTPS. | 23/06/2026   | 23/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Sử dụng AWS Secrets Manager để quản lý tập trung và tự động thay đổi (rotate) thông tin cấu hình nhạy cảm (database credentials, API keys).                                                                                                                                 | 24/06/2026   | 24/06/2026      |<https://cloudjourney.awsstudygroup.com/> |
| 5   | Thực hành kiểm thử tải (Load Testing/Stress Testing) hệ thống bằng các công cụ như Apache JMeter hoặc Locust để kiểm tra giới hạn chịu tải.                  | 25/06/2026   | 25/06/2026      |<https://cloudjourney.awsstudygroup.com/> |
| 6   | Phân tích biểu đồ CloudWatch Metrics trong quá trình test tải, xác định các điểm nghẽn (bottlenecks) về CPU, Memory hoặc kết nối Database.                                                                                      | 26/06/2026   | 26/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 7   | - Đánh giá cấu hình Auto-scaling cho ECS Cluster, đảm bảo hệ thống tự động tăng giảm số lượng container khi lượng người đặt sân cầu lông biến động.                                                                                         | 27/06/2026   | 27/06/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 10:

* Cấu hình AWS WAF chặn các cuộc tấn công web phổ biến, cài đặt chứng chỉ SSL (HTTPS) qua ACM; giấu toàn bộ thông tin nhạy cảm vào AWS Secrets Manager; chạy kiểm thử tải (Load Test) thành công và tối ưu hóa cơ chế Auto-scaling của ECS khi lượng người dùng đặt sân tăng đột biến.
