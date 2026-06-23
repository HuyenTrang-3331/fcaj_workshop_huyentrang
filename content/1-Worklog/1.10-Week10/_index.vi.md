---
title: "Worklog Tuần 10"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tìm hiểu và ôn tập các dịch vụ hỗ trợ xây dựng ứng dụng cloud trên AWS.
* Củng cố kiến thức về kiến trúc web application trên AWS.
* Tìm hiểu luồng hoạt động giữa User, Route 53, CloudFront, WAF, ALB, EC2, S3 và RDS.
* Ôn tập các thành phần mạng như VPC, Subnet, Route Table, Internet Gateway, NAT Gateway và Security Group.
* Rèn luyện kỹ năng nhận xét, phân tích và chỉnh sửa sơ đồ kiến trúc AWS.
* Tìm hiểu các phương án bảo mật hệ thống nội bộ như IP Allowlist, HTTPS, Authentication, API Key và HMAC.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Ôn tập kiến trúc web application trên AWS <br> - Tìm hiểu luồng truy cập User → Route 53 → CloudFront/WAF → ALB → EC2 <br> - Ghi chú vai trò của từng thành phần trong kiến trúc | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/architecture/ |
| 2 | - Ôn tập VPC, Public Subnet, Private Subnet, Route Table, Internet Gateway và NAT Gateway <br> - Phân biệt tài nguyên nằm trong Region, VPC, Subnet và tài nguyên global <br> - Ghi chú cách đặt service đúng vị trí trong sơ đồ kiến trúc | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/vpc/ |
| 3 | - Tìm hiểu vai trò của ALB, CloudFront, WAF và S3 trong hệ thống web <br> - Phân biệt luồng CloudFront đến S3 và luồng CloudFront/WAF đến ALB <br> - Ghi chú các lỗi thường gặp khi vẽ sơ đồ kiến trúc AWS | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/ |
| 4 | - Tìm hiểu các phương án bảo mật dashboard nội bộ <br> - So sánh WAF, VPN, IP Allowlist, HTTPS, Authentication, API Key và HMAC <br> - Ghi chú cách lựa chọn phương án bảo mật phù hợp với chi phí và nhu cầu project | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/waf/ |
| 5 | - Tổng hợp kiến thức kiến trúc AWS tuần 10 <br> - Nhận xét và chỉnh sửa sơ đồ kiến trúc theo đúng logic <br> - Hoàn thiện ghi chú báo cáo tuần 10 <br> - Dọn dẹp tài nguyên hoặc tài liệu lab không còn sử dụng | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/blogs/architecture/ |

### Kết quả đạt được tuần 10:

* Hiểu rõ hơn cách xây dựng kiến trúc web application cơ bản trên AWS.
* Biết cách xác định luồng truy cập chính của người dùng vào hệ thống.
* Nắm được luồng kiến trúc phổ biến:
  * User
  * Route 53
  * CloudFront
  * AWS WAF
  * Application Load Balancer
  * EC2 Backend
  * RDS Database
* Hiểu được CloudFront có thể dùng để phân phối nội dung tĩnh từ S3.
* Biết rằng WAF không nên được vẽ như một node mạng trung gian độc lập mà thường được gắn với CloudFront hoặc ALB.
* Hiểu rõ hơn vai trò của các thành phần mạng trong AWS, bao gồm:
  * VPC
  * Public Subnet
  * Private Subnet
  * Route Table
  * Internet Gateway
  * NAT Gateway
  * Security Group
* Phân biệt được tài nguyên nằm trong VPC và tài nguyên không nằm trong VPC.
* Hiểu được NAT Gateway chủ yếu dùng cho outbound traffic từ private subnet ra Internet.
* Biết cách phân tích sơ đồ kiến trúc và phát hiện một số lỗi thường gặp, ví dụ:
  * Vẽ IAM như một luồng xử lý dữ liệu
  * Đặt WAF sai vị trí
  * Nhầm lẫn giữa Internet Gateway và Application Load Balancer
  * Thiếu Security Group hoặc Route Table
  * Không thể hiện rõ public subnet và private subnet
* Hiểu được các phương án bảo mật dashboard nội bộ.
* Biết rằng nếu không dùng WAF thì hệ thống vẫn cần có lớp bảo mật thay thế.
* Nắm được một số phương án bảo mật phù hợp cho hệ thống nội bộ, bao gồm:
  * VPN
  * IP Allowlist
  * HTTPS
  * Authentication
  * API Key
  * HMAC
* Biết cách cân nhắc giữa bảo mật, chi phí và độ phức tạp khi thiết kế kiến trúc.
* Rèn luyện kỹ năng nhận xét sơ đồ kiến trúc AWS một cách ngắn gọn, đúng trọng tâm.
