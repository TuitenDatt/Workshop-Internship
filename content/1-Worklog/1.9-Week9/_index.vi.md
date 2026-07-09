---
title: "Worklog Tuần 9"
date: 2026-07-06
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---



### Mục tiêu tuần 9:

* Tiến hành chuyển đổi, đóng gói và triển khai toàn bộ ứng dụng full-stack "Web Cầu Lông Vui" lên môi trường cloud Production của AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Lập trình và hoàn thiện các tính năng cốt lõi của Web Cầu Lông Vui (Đặt sân, lịch trình, thông tin thành viên) ở local.                                                                                          | 22/06/2026   | 22/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Thực hành Dockerize ứng dụng Web Cầu Lông Vui.            | 23/06/2026   | 23/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Khởi tạo hạ tầng mạng trên AWS (VPC, Subnets, ALB) phục vụ cho đồ án. | 24/06/2026   | 24/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Deploy database của ứng dụng lên Amazon RDS và cấu hình bảo mật. | 25/06/2026   | 25/06/2026      |<https://cloudjourney.awsstudygroup.com/> |
| 6   | - Deploy các container ứng dụng lên AWS ECS Fargate, cấu hình qua Load Balancer để nhận traffic. | 26/06/2026   | 26/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 7   | - Tích hợp Amazon S3 để lưu trữ hình ảnh sân cầu lông, avatar người dùng. Kiểm tra toàn bộ luồng hoạt động end-to-end.                                                                                         | 27/05/2026   | 27/05/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 9:

* Dockerize thành công hai thành phần Frontend và Backend của ứng dụng; khởi tạo và phân tách cơ sở dữ liệu trên RDS nằm trong vùng mạng an toàn; deploy thành công các container lên ECS Fargate và tích hợp S3 để quản lý toàn bộ hình ảnh sân bãi, avatar.