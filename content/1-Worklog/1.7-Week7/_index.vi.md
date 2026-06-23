---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

- Hoàn thành nội dung học tập của Module 06 về Database trên AWS trong chương trình First Cloud AI Journey.
- Ôn tập các khái niệm nền tảng về cơ sở dữ liệu, relational database và non-relational database.
- Tìm hiểu các dịch vụ database chính trên AWS như Amazon RDS, Amazon Aurora, Amazon Redshift và Amazon ElastiCache.
- Thực hành triển khai hệ thống sử dụng Amazon RDS, bao gồm VPC, Security Group, DB Subnet Group, EC2 Instance, RDS Database Instance và Application Deployment.
- Thực hành backup, restore và dọn dẹp tài nguyên sau khi hoàn thành bài lab.
- Thực hành kết nối EC2 bằng RDP Client và Fleet Manager.
- Thực hành cấu hình môi trường source database và target database phục vụ migration.
- Thực hành migration database từ SQL Server/Oracle sang MySQL bằng các công cụ hỗ trợ như Schema Conversion và Migration Task.
- Rèn luyện kỹ năng kiểm tra log, theo dõi trạng thái migration và xử lý lỗi trong quá trình migration database.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Học Module 06-01: Database Concepts Review<br>- Ôn tập các khái niệm nền tảng về database, relational database, non-relational database, schema, table, record, query và transaction<br>- Học Module 06-02: Amazon RDS & Amazon Aurora<br>- Tìm hiểu vai trò của Amazon RDS và Amazon Aurora trong việc triển khai database được quản lý trên AWS<br>- Học Module 06-03: Redshift - ElastiCache<br>- Tìm hiểu tổng quan về data warehouse và caching trên AWS | 29/05/2026 | 29/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Làm Lab05-2.1: Create a VPC<br>- Làm Lab05-2.2: Create EC2 Security Group<br>- Làm Lab05-2.3: Create RDS Security Group<br>- Làm Lab05-2.4: Create DB Subnet Group<br>- Làm Lab05-3: Create EC2 instance<br>- Làm Lab05-4: Create RDS database instance<br>- Làm Lab05-5: Application Deployment<br>- Làm Lab05-6: Backup and restore<br>- Làm Lab05-7: Clean up resources | 01/06/2026 | 01/06/2026 | https://000005.awsstudygroup.com |
| 3 | - Làm Lab43-01: EC2 Connect RDP Client<br>- Làm Lab43-02: EC2 Connect Fleet Manager<br>- Làm Lab43-03: SQLSrv Src Config<br>- Làm Lab43-04: Oracle connect SrcDB<br>- Làm Lab43-05: Oracle config SrcDB<br>- Làm Lab43-06: Drop Constraint<br>- Làm Lab43-07: MSSQL to aur MySQL target config<br>- Chuẩn bị môi trường source database và target database phục vụ quá trình migration | 02/06/2026 | 02/06/2026 | https://000043.awsstudygroup.com |
| 4 | - Làm Lab43-08: MSSQL to MySQL create project<br>- Làm Lab43-09: MSSQL to MySQL Schema Conversion<br>- Làm Lab43-10: Oracle to MySQL Schema Conversion 1<br>- Làm Lab43-11: Create Migration Task and Endpoint<br>- Làm Lab43-12: Inspect S3<br>- Làm Lab43-13: Create Serverless Migration<br>- Ghi chú quy trình chuyển đổi schema và tạo migration task trong quá trình di chuyển database | 03/06/2026 | 03/06/2026 | https://000043.awsstudygroup.com |
| 5 | - Làm Lab43-14: Create Event Notification<br>- Làm Lab43-15: Logs<br>- Làm Lab43-16: Troubleshoot Test Scenario Mem Pressure<br>- Làm Lab43-17: Troubleshoot Test Scenario Table Error<br>- Kiểm tra log, theo dõi trạng thái migration và xử lý lỗi phát sinh trong quá trình thực hành | 04/06/2026 | 04/06/2026 | https://000043.awsstudygroup.com |

### Kết quả đạt được tuần 7:

- Hoàn thành nội dung học tập của Module 06 về Database trên AWS trong chương trình First Cloud AI Journey.
- Hiểu được các khái niệm nền tảng về cơ sở dữ liệu, bao gồm:
  - Database.
  - Table.
  - Record.
  - Schema.
  - Query.
  - Transaction.
  - Relational Database.
  - Non-relational Database.
- Nắm được vai trò của các dịch vụ database chính trên AWS, bao gồm:
  - Amazon RDS.
  - Amazon Aurora.
  - Amazon Redshift.
  - Amazon ElastiCache.
- Hiểu được vai trò của Amazon RDS trong việc triển khai và quản lý relational database trên AWS.
- Hiểu được vai trò của Amazon Aurora trong việc cung cấp database có hiệu năng cao, khả năng mở rộng tốt và độ sẵn sàng cao.
- Hiểu được vai trò của Amazon Redshift trong việc xây dựng data warehouse phục vụ phân tích dữ liệu quy mô lớn.
- Hiểu được vai trò của Amazon ElastiCache trong việc tăng tốc ứng dụng thông qua caching và giảm tải truy vấn trực tiếp đến database.
- Thực hành các bài lab liên quan đến triển khai Amazon RDS, bao gồm:
  - Lab05-2.1: Create a VPC.
  - Lab05-2.2: Create EC2 Security Group.
  - Lab05-2.3: Create RDS Security Group.
  - Lab05-2.4: Create DB Subnet Group.
  - Lab05-3: Create EC2 instance.
  - Lab05-4: Create RDS database instance.
  - Lab05-5: Application Deployment.
  - Lab05-6: Backup and restore.
  - Lab05-7: Clean up resources.
- Biết cách tạo VPC, Security Group và DB Subnet Group để chuẩn bị hạ tầng mạng cho Amazon RDS.
- Biết cách tạo EC2 Instance để làm môi trường kết nối hoặc triển khai ứng dụng truy cập database.
- Biết cách tạo RDS Database Instance và cấu hình kết nối giữa ứng dụng và database.
- Thực hành triển khai ứng dụng có sử dụng database trên AWS.
- Hiểu được quy trình backup và restore database trong Amazon RDS nhằm đảm bảo khả năng khôi phục dữ liệu khi xảy ra sự cố.
- Thực hành các bài lab liên quan đến kết nối và cấu hình môi trường migration database, bao gồm:
  - Lab43-01: EC2 Connect RDP Client.
  - Lab43-02: EC2 Connect Fleet Manager.
  - Lab43-03: SQLSrv Src Config.
  - Lab43-04: Oracle connect SrcDB.
  - Lab43-05: Oracle config SrcDB.
  - Lab43-06: Drop Constraint.
  - Lab43-07: MSSQL to aur MySQL target config.
- Biết cách kết nối vào EC2 Instance bằng RDP Client và Fleet Manager.
- Biết cách chuẩn bị source database và target database phục vụ quá trình migration.
- Thực hành các bài lab liên quan đến chuyển đổi schema và migration database, bao gồm:
  - Lab43-08: MSSQL to MySQL create project.
  - Lab43-09: MSSQL to MySQL Schema Conversion.
  - Lab43-10: Oracle to MySQL Schema Conversion 1.
  - Lab43-11: Create Migration Task and Endpoint.
  - Lab43-12: Inspect S3.
  - Lab43-13: Create Serverless Migration.
- Hiểu được vai trò của schema conversion trong quá trình chuyển đổi database giữa các hệ quản trị khác nhau.
- Biết cách tạo migration task và endpoint để hỗ trợ quá trình di chuyển dữ liệu từ source database sang target database.
- Hiểu được vai trò của Amazon S3 trong việc lưu trữ dữ liệu trung gian hoặc artifact liên quan đến quá trình migration.
- Thực hành các bài lab liên quan đến giám sát, log và xử lý lỗi trong quá trình migration, bao gồm:
  - Lab43-14: Create Event Notification.
  - Lab43-15: Logs.
  - Lab43-16: Troubleshoot Test Scenario Mem Pressure.
  - Lab43-17: Troubleshoot Test Scenario Table Error.
- Biết cách kiểm tra log để theo dõi trạng thái migration và phát hiện lỗi.
- Biết cách xử lý một số tình huống lỗi cơ bản trong quá trình migration database.
- Biết cách dọn dẹp tài nguyên sau khi hoàn thành bài lab nhằm tránh phát sinh chi phí không cần thiết.
- Rèn luyện kỹ năng thực hành AWS Database thông qua các bài lab, bao gồm:
  - Đọc yêu cầu bài lab.
  - Thực hiện từng bước cấu hình trên AWS Console.
  - Quan sát kết quả sau khi cấu hình.
  - Kiểm tra kết quả sau khi triển khai.
  - Ghi nhận lỗi phát sinh nếu có.
  - Dọn dẹp tài nguyên sau khi hoàn thành lab.
- Có khả năng liên kết kiến thức lý thuyết về Amazon RDS, Aurora, Redshift, ElastiCache và database migration với các bài lab thực hành thực tế.
- Hoàn thành ghi chú, tổng hợp kết quả học tập và chuẩn bị nội dung báo cáo cho tuần 7.
