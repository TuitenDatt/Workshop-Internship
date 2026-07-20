---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---



### Mục tiêu tuần 4:

* Nắm vững tư duy phân quyền bảo mật, áp dụng nguyên tắc đặc quyền tối thiểu (Least Privilege) bằng việc cấu hình IAM Policy và IAM Role.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về AWS Identity and Access Management (IAM): Users, Groups, Roles và Policies.                                       | 11/05/2026   | 11/05/2026        | <https://aws.amazon.com/iam/> |
| 3   | - Nghiên cứu cú pháp viết IAM Policy bằng JSON (Effect, Action, Resource, Condition).                                                                          | 12/05/2026   | 12/05/2026      | <https://aws.amazon.com/iam/> |
| 4   | - Thực hành thiết lập Multi-Factor Authentication (MFA) cho tài khoản Root và các tài khoản quản trị viên.                                                   | 13/05/2026   | 13/05/2026      | <https://aws.amazon.com/iam/> |
| 5   | - Áp dụng nguyên tắc đặc quyền tối thiểu (Least Privilege): Tạo các nhóm quyền hạn giới hạn cho phòng ban Tester, Developer.                  | 14/05/2026   | 14/05/2026      | <https://aws.amazon.com/iam/> |
| 6   | - Cấu hình IAM Role cho EC2 instance để nó có quyền đọc ghi dữ liệu an toàn vào S3 bucket mà không cần hardcode credentials.                                                                                    | 15/05/2026   | 15/05/2026      | <https://aws.amazon.com/iam/> |
| 7   | - Kiểm tra và đánh giá an toàn bảo mật hệ thống bằng công cụ AWS IAM Access Advisor.                                                                                   | 16/05/2026   | 16/05/2026      | <https://aws.amazon.com/iam/> |

### Kết quả đạt được tuần 4:

* Hiểu sâu sắc cơ chế phân quyền bảo mật AWS IAM, làm chủ cấu trúc IAM Policy JSON.
* Triển khai thành công MFA và phân chia nhóm người dùng theo nguyên tắc Least Privilege.
* Ứng dụng thành thạo IAM Role gán cho EC2 giúp bảo mật source code ứng dụng.
