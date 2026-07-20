---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---



### Mục tiêu tuần 3:

* Tự thiết kế và cấu hình hoàn chỉnh hệ thống mạng Custom VPC bảo mật theo mô hình phân tầng (Multi-tier Network) chuẩn doanh nghiệp.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu khái niệm Virtual Private Cloud (VPC), Subnets (Public/Private), Route Tables.<br>Học cách phân chia dải IP CIDR.                                                                                             | 04/05/2026   | 04/05/2026      | <https://aws.amazon.com/vpc/>|
| 3   | - Tìm hiểu cơ chế bảo mật mạng: Phân biệt Security Groups (Stateful) và Network ACLs (Stateless).                                   | 05/05/2026   | 05/05/2026      | <https://aws.amazon.com/vpc/>
| 4   | - Nghiên cứu Internet Gateway (IGW) phục vụ kết nối ngoài và NAT Gateway giúp Private Subnet đi Internet bảo mật. | 06/05/2026   | 06/05/2026      | <https://aws.amazon.com/vpc/>|
| 5   | - Thực hành tự thiết kế và khởi tạo một Custom VPC hoàn chỉnh theo sơ đồ kiến trúc chuẩn.                  | 07/05/2026   | 07/05/2026      | <https://aws.amazon.com/vpc/> |
| 6   | - Triển khai kiến trúc Multi-tier Network: Đặt Web server ở Public Subnet và DB Server ở Private Subnet.                                                                                         | 08/05/2026   | 08/05/2026      | <https://aws.amazon.com/vpc/>|
| 7   | - Cấu hình định tuyến chi tiết, kiểm tra khả năng bảo mật bảo vệ DB server khỏi các truy cập trực tiếp từ Internet.                                                                                         | 09/05/2026   | 09/05/2026      | <https://aws.amazon.com/vpc/>|

### Kết quả đạt được tuần 3:

* Nắm vững kiến thức cốt lõi về VPC, phân chia Subnets, thiết lập Route Tables logic.
* Tự thiết kế và cấu hình thành công mô hình Multi-tier Network an toàn, bảo mật cao.
* Sử dụng thành thạo NAT Gateway và Internet Gateway để kiểm soát luồng giao thông mạng.
