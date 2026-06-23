---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

- Hoàn thành nội dung học tập của Module 04 về dịch vụ lưu trữ trên AWS.
- Tìm hiểu các dịch vụ lưu trữ chính trên AWS như Amazon S3, AWS Storage Gateway, Snow Family, Disaster Recovery và AWS Backup.
- Nắm được các khái niệm quan trọng của Amazon S3 như Access Point, Storage Class, Static Website, CORS, Control Access, Object Key, Performance và Glacier.
- Thực hành tạo S3 Bucket, triển khai infrastructure, tạo Backup Plan, thiết lập notification, kiểm tra restore và dọn dẹp tài nguyên.
- Thực hành migration máy ảo từ môi trường on-premises lên AWS thông qua VMware Workstation, export/import virtual machine và triển khai instance từ AMI.
- Thực hành cấu hình AWS Storage Gateway, File Shares và mount file shares trên máy on-premises.
- Thực hành tạo Amazon FSx file system, kiểm tra hiệu năng, giám sát hiệu năng, bật data deduplication, shadow copies, user quotas và scale capacity.
- Thực hành triển khai website tĩnh trên Amazon S3, cấu hình CloudFront, versioning, move objects, replication multi-region và dọn dẹp tài nguyên sau lab.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Học Module 04-01: Storage Services on AWS<br>- Học Module 04-02: Amazon Simple Storage Service S3 - Access Point - Storage Class<br>- Học Module 04-03: S3 Static Website & CORS - Control Access - Object Key & Performance - Glacier<br>- Học Module 04-04: Snow Family - Storage Gateway - Backup<br>- Ghi chú các khái niệm quan trọng về S3, Storage Class, Glacier, Storage Gateway, Snow Family và AWS Backup | 15/05/2026 | 15/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Làm Lab13-02.1: Create S3 Bucket<br>- Làm Lab13-02.2: Deploy Infrastructure<br>- Làm Lab13-03: Create Backup plan<br>- Làm Lab13-04: Set up notifications<br>- Làm Lab13-05: Test Restore<br>- Làm Lab13-06: Clean up resources<br>- Ghi chú quy trình tạo backup plan, cấu hình thông báo, kiểm tra restore và dọn dẹp tài nguyên | 18/05/2026 | 18/05/2026 | https://000013.awsstudygroup.com |
| 3 | - Làm Lab14-01: VMware Workstation<br>- Làm Lab14-02.1: Export Virtual Machine from On-premises<br>- Làm Lab14-02.2: Upload virtual machine to AWS<br>- Làm Lab14-02.3: Import virtual machine to AWS<br>- Làm Lab14-02.4: Deploy Instance from AMI<br>- Làm Lab14-03.1: Setting up S3 bucket ACL<br>- Làm Lab14-03.2: Export virtual machine from Instance<br>- Làm Lab14-05: Resource Cleanup on AWS Cloud | 19/05/2026 | 19/05/2026 | https://000014.awsstudygroup.com |
| 4 | - Làm Lab24-2.1: Create Storage Gateway<br>- Làm Lab24-2.2: Create File Shares<br>- Làm Lab24-2.3: Mount File shares on On-premises machine<br>- Làm Lab24-3: Clean up resources<br>- Làm Lab25-2.2: Create an SSD Multi-AZ file system<br>- Làm Lab25-2.3: Create an HDD Multi-AZ file system<br>- Làm Lab25-3: Create new file shares<br>- Làm Lab25-4: Test Performance<br>- Làm Lab25-5: Monitor Performance | 20/05/2026 | 20/05/2026 | https://000024.awsstudygroup.com<br>https://000025.awsstudygroup.com |
| 5 | - Làm Lab25-6: Enable data deduplication<br>- Làm Lab25-7: Enable shadow copies<br>- Làm Lab25-8: Manage user sessions and open files<br>- Làm Lab25-9: Enable user storage quotas<br>- Làm Lab25-11: Scale throughput capacity<br>- Làm Lab25-12: Scale storage capacity<br>- Làm Lab25-13: Delete environment<br>- Làm Lab57-2.1: Create S3 bucket<br>- Làm Lab57-2.2: Load data<br>- Làm Lab57-3: Enable static website feature<br>- Làm Lab57-4: Configuring public access block<br>- Làm Lab57-5: Configuring public objects<br>- Làm Lab57-6: Test website<br>- Làm Lab57-7.1: Block all public access<br>- Làm Lab57-7.2: Config Amazon CloudFront<br>- Làm Lab57-7.3: Test Amazon CloudFront<br>- Làm Lab57-8: Bucket Versioning<br>- Làm Lab57-9: Move objects<br>- Làm Lab57-10: Replication Object multi Region<br>- Làm Lab57-11: Clean up resources | 21/05/2026 | 21/05/2026 | https://000025.awsstudygroup.com<br>https://000057.awsstudygroup.com |

### Kết quả đạt được tuần 5:

- Hoàn thành nội dung học tập của Module 04 về dịch vụ lưu trữ trên AWS trong chương trình First Cloud AI Journey.
- Hiểu được vai trò của các dịch vụ lưu trữ trên AWS trong việc lưu trữ, bảo vệ, sao lưu, khôi phục và phân phối dữ liệu.
- Nắm được các dịch vụ lưu trữ chính trên AWS, bao gồm:
  - Amazon Simple Storage Service S3.
  - AWS Storage Gateway.
  - Snow Family.
  - Disaster Recovery on AWS.
  - AWS Backup.
- Hiểu được vai trò của Amazon S3 trong việc lưu trữ object với khả năng mở rộng cao, độ bền dữ liệu lớn và phù hợp cho nhiều loại dữ liệu khác nhau.
- Nắm được các khái niệm quan trọng trong Amazon S3, bao gồm:
  - S3 Bucket.
  - Object.
  - Object Key.
  - Access Point.
  - Storage Class.
  - Static Website Hosting.
  - CORS.
  - Control Access.
  - Performance.
  - Glacier.
- Hiểu được vai trò của S3 Storage Class trong việc tối ưu chi phí lưu trữ theo tần suất truy cập dữ liệu.
- Hiểu được Amazon S3 Glacier là lớp lưu trữ phù hợp cho dữ liệu ít truy cập, dữ liệu lưu trữ dài hạn hoặc dữ liệu cần archive.
- Thực hành các bài lab liên quan đến AWS Backup, bao gồm:
  - Lab13-02.1: Create S3 Bucket.
  - Lab13-02.2: Deploy Infrastructure.
  - Lab13-03: Create Backup plan.
  - Lab13-04: Set up notifications.
  - Lab13-05: Test Restore.
  - Lab13-06: Clean up resources.
- Biết cách tạo S3 Bucket để phục vụ cho bài lab backup và lưu trữ dữ liệu.
- Biết cách triển khai infrastructure phục vụ quá trình sao lưu và khôi phục dữ liệu trên AWS.
- Biết cách tạo Backup Plan để tự động hóa quá trình sao lưu theo lịch và theo chính sách được cấu hình.
- Hiểu được vai trò của notification trong việc theo dõi trạng thái backup, cảnh báo và ghi nhận kết quả sao lưu.
- Thực hành kiểm tra restore dữ liệu để xác nhận dữ liệu có thể được khôi phục khi xảy ra sự cố.
- Biết cách dọn dẹp tài nguyên sau khi hoàn thành bài lab nhằm tránh phát sinh chi phí không cần thiết.
- Thực hành các bài lab liên quan đến migration máy ảo từ môi trường on-premises lên AWS, bao gồm:
  - Lab14-01: VMware Workstation.
  - Lab14-02.1: Export Virtual Machine from On-premises.
  - Lab14-02.2: Upload virtual machine to AWS.
  - Lab14-02.3: Import virtual machine to AWS.
  - Lab14-02.4: Deploy Instance from AMI.
  - Lab14-03.1: Setting up S3 bucket ACL.
  - Lab14-03.2: Export virtual machine from Instance.
  - Lab14-05: Resource Cleanup on AWS Cloud.
- Hiểu được quy trình chuyển đổi và di chuyển máy ảo từ môi trường on-premises lên AWS.
- Biết cách export virtual machine từ môi trường on-premises, upload lên AWS, import thành AMI và triển khai EC2 Instance từ AMI.
- Hiểu được vai trò của S3 Bucket ACL trong việc kiểm soát quyền truy cập dữ liệu trong quá trình migration.
- Thực hành các bài lab liên quan đến AWS Storage Gateway, bao gồm:
  - Lab24-2.1: Create Storage Gateway.
  - Lab24-2.2: Create File Shares.
  - Lab24-2.3: Mount File shares on On-premises machine.
  - Lab24-3: Clean up resources.
- Hiểu được vai trò của AWS Storage Gateway trong việc kết nối hệ thống lưu trữ on-premises với dịch vụ lưu trữ trên AWS.
- Biết cách tạo File Shares và mount file shares trên máy on-premises để truy cập dữ liệu thông qua Storage Gateway.
- Thực hành các bài lab liên quan đến Amazon FSx, bao gồm:
  - Lab25-2.2: Create an SSD Multi-AZ file system.
  - Lab25-2.3: Create an HDD Multi-AZ file system.
  - Lab25-3: Create new file shares.
  - Lab25-4: Test Performance.
  - Lab25-5: Monitor Performance.
  - Lab25-6: Enable data deduplication.
  - Lab25-7: Enable shadow copies.
  - Lab25-8: Manage user sessions and open files.
  - Lab25-9: Enable user storage quotas.
  - Lab25-11: Scale throughput capacity.
  - Lab25-12: Scale storage capacity.
  - Lab25-13: Delete environment.
- Hiểu được vai trò của Amazon FSx trong việc cung cấp hệ thống file system được quản lý trên AWS.
- Phân biệt được SSD Multi-AZ file system và HDD Multi-AZ file system trong Amazon FSx theo nhu cầu hiệu năng và chi phí.
- Biết cách kiểm tra và giám sát hiệu năng file system thông qua các bước Test Performance và Monitor Performance.
- Hiểu được vai trò của data deduplication trong việc giảm dữ liệu trùng lặp và tối ưu dung lượng lưu trữ.
- Hiểu được vai trò của shadow copies trong việc hỗ trợ khôi phục phiên bản dữ liệu trước đó.
- Biết cách quản lý user sessions, open files và user storage quotas trong môi trường file sharing.
- Biết cách mở rộng throughput capacity và storage capacity để đáp ứng nhu cầu sử dụng tăng lên.
- Thực hành các bài lab liên quan đến website tĩnh trên Amazon S3 và CloudFront, bao gồm:
  - Lab57-2.1: Create S3 bucket.
  - Lab57-2.2: Load data.
  - Lab57-3: Enable static website feature.
  - Lab57-4: Configuring public access block.
  - Lab57-5: Configuring public objects.
  - Lab57-6: Test website.
  - Lab57-7.1: Block all public access.
  - Lab57-7.2: Config Amazon CloudFront.
  - Lab57-7.3: Test Amazon CloudFront.
  - Lab57-8: Bucket Versioning.
  - Lab57-9: Move objects.
  - Lab57-10: Replication Object multi Region.
  - Lab57-11: Clean up resources.
- Biết cách triển khai website tĩnh bằng Amazon S3.
- Hiểu được cách cấu hình public access block và public objects để kiểm soát quyền truy cập dữ liệu trong S3.
- Biết cách cấu hình Amazon CloudFront để phân phối nội dung website từ S3 với tốc độ truy cập tốt hơn và tăng tính bảo mật.
- Hiểu được vai trò của Bucket Versioning trong việc lưu giữ nhiều phiên bản object và hỗ trợ khôi phục khi dữ liệu bị ghi đè hoặc xóa nhầm.
- Thực hành move object trong S3 và hiểu cách quản lý object trong bucket.
- Hiểu được cơ chế Replication Object multi Region để sao chép dữ liệu giữa các region, hỗ trợ khả năng dự phòng và tăng độ bền dữ liệu.
- Rèn luyện kỹ năng thực hành AWS Storage thông qua các bài lab, bao gồm:
  - Đọc yêu cầu bài lab.
  - Thực hiện từng bước cấu hình trên AWS Console.
  - Quan sát kết quả sau khi cấu hình.
  - Kiểm tra kết quả sau khi triển khai.
  - Ghi nhận lỗi phát sinh nếu có.
  - Dọn dẹp tài nguyên sau khi hoàn thành lab.
- Có khả năng liên kết kiến thức lý thuyết về Amazon S3, AWS Backup, Storage Gateway, FSx, CloudFront và migration với các bài lab thực hành thực tế.
- Hoàn thành ghi chú, tổng hợp kết quả học tập và chuẩn bị nội dung báo cáo cho tuần 5.
