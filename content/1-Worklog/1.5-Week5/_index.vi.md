---
title: "Worklog Tuần 5"
date: 2026-06-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Thực hành khởi tạo máy chủ Amazon EC2, sao lưu với AWS Backup và lưu trữ Amazon S3.
* Cấu hình lưu trữ trang web tĩnh Static Website Hosting trên S3 kết hợp CDN Amazon CloudFront.
* Tìm hiểu tính năng quản lý phiên bản Bucket Versioning và sao chép dữ liệu Replication.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | Thực hành khởi tạo máy chủ EC2 Linux, thiết lập Security Group và kết nối qua SSH. | 02/06/2026 | 02/06/2026 | EC2 User Guide |
| Thứ 3 | Tìm hiểu dịch vụ Amazon S3, thực hành tạo Bucket và bật tính năng Versioning. | 03/06/2026 | 03/06/2026 | S3 User Guide |
| Thứ 4 | Cấu hình Static Website Hosting trên Amazon S3 và phân quyền public read Policy. | 04/06/2026 | 04/06/2026 | S3 Hosting Guide |
| Thứ 5 | Tích hợp Amazon CloudFront với S3 Bucket để tăng tốc độ phân phối trang web tĩnh. | 05/06/2026 | 06/06/2026 | CloudFront Guide |
| Chủ Nhật | Tìm hiểu cơ chế Cross-Region Replication trên S3 và cấu hình lập lịch sao lưu tự động với AWS Backup. | 07/06/2026 | 08/06/2026 | AWS Backup Guide |

### Kết quả đạt được tuần 5:
* Quản lý thành thạo EC2 và thiết lập kế hoạch sao lưu hệ thống tự động qua AWS Backup.
* Triển khai thành công website tĩnh trên Amazon S3 và tối ưu tốc độ phản hồi qua CloudFront.
* Hiểu rõ cơ chế chống mất mát dữ liệu nhờ Bucket Versioning và S3 Replication.