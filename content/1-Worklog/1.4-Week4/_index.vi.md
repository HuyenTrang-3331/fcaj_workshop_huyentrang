---

title: "Worklog Tuần 4"
date: 2026-05-07
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

- Hoàn thành nội dung học tập của Module 03 trong chương trình First Cloud AI Journey.
- Tìm hiểu về dịch vụ Compute VM trên AWS, đặc biệt là Amazon EC2 và các thành phần liên quan.
- Hiểu các khái niệm cơ bản của Amazon EC2 như instance type, AMI, backup, key pair, EBS, instance store, user data, metadata và EC2 Auto Scaling.
- Tìm hiểu các dịch vụ mở rộng liên quan như EFS, FSx, Lightsail và AWS Application Migration Service.
- Thực hành triển khai AWS Backup cho hệ thống, tạo backup plan, kiểm tra restore và dọn dẹp tài nguyên.
- Thực hành tạo S3 Bucket, Storage Gateway và File Shares để hiểu mô hình lưu trữ trên AWS.
- Thực hành triển khai website tĩnh trên Amazon S3, cấu hình public access, CloudFront, bucket versioning, move objects và replication object multi-region.
- Rèn luyện kỹ năng kiểm tra kết quả sau lab và dọn dẹp tài nguyên để tránh phát sinh chi phí.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Học Module 03-01: Compute VM on AWS<br>- Học Module 03-01-01: Amazon EC2 - Instance type<br>- Học Module 03-01-02: Amazon EC2 - AMI / Backup / Key Pair<br>- Học Module 03-01-03: Amazon EC2 - Elastic Block Store<br>- Học Module 03-01-04: Amazon EC2 - Instance Store<br>- Học Module 03-01-05: Amazon EC2 - User Data<br>- Học Module 03-01-06: Amazon EC2 - Metadata<br>- Học Module 03-01-07: Amazon EC2 - EC2 Auto Scaling<br>- Học Module 03-02: EC2 Autoscaling - EFS/FSx - Lightsail - MGN | 08/05/2026 | 08/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Làm Lab13-01: Deploy AWS Backup to the System - Introduction<br>- Làm Lab13-02.2: Deploy infrastructure<br>- Làm Lab13-03: Create Backup plan<br>- Làm Lab13-05: Test Restore<br>- Làm Lab13-06: Clean up resources<br>- Ghi chú quy trình triển khai backup, kiểm tra khôi phục dữ liệu và dọn dẹp tài nguyên | 11/05/2026 | 11/05/2026 | https://000013.awsstudygroup.com |
| 3 | - Làm Lab24-01.1: Create S3 Bucket<br>- Làm Lab24-01.2: Create EC2 for Storage Gateway<br>- Làm Lab24-02.1: Create Storage Gateway<br>- Làm Lab24-02.2: Create File Shares<br>- Tìm hiểu vai trò của Amazon S3, AWS Storage Gateway và File Shares | 12/05/2026 | 12/05/2026 | https://000024.awsstudygroup.com |
| 4 | - Làm Lab57-02.1: Create S3 bucket<br>- Làm Lab57-02.2: Load data<br>- Làm Lab57-03: Enable static website feature<br>- Làm Lab57-04: Configuring public access block<br>- Làm Lab57-05: Configuring public objects<br>- Làm Lab57-06: Test website | 13/05/2026 | 13/05/2026 | https://000057.awsstudygroup.com |
| 5 | - Làm Lab57-07.1: Block all public access<br>- Làm Lab57-07.2: Config Amazon CloudFront<br>- Làm Lab57-07.3: Test Amazon CloudFront<br>- Làm Lab57-08: Bucket Versioning<br>- Làm Lab57-09: Move objects<br>- Làm Lab57-10: Replication Object multi Region<br>- Làm Lab57-11: Clean up resources | 14/05/2026 | 14/05/2026 | https://000057.awsstudygroup.com |

### Kết quả đạt được tuần 4:

- Hoàn thành nội dung học tập của Module 03 trong chương trình First Cloud AI Journey.
- Hiểu được vai trò của dịch vụ Compute VM trên AWS trong việc cung cấp tài nguyên máy chủ ảo để triển khai ứng dụng và workload.
- Hiểu được vai trò của Amazon EC2 trong việc cung cấp máy chủ ảo linh hoạt trên AWS.
- Nắm được các khái niệm quan trọng của Amazon EC2, bao gồm:
  - Instance Type.
  - AMI.
  - Backup.
  - Key Pair.
  - Elastic Block Store.
  - Instance Store.
  - User Data.
  - Metadata.
  - EC2 Auto Scaling.
- Hiểu được vai trò của Instance Type trong việc lựa chọn cấu hình tài nguyên phù hợp cho workload, bao gồm CPU, RAM, network performance và storage performance.
- Hiểu được AMI là template dùng để khởi tạo EC2 Instance, đồng thời nắm được vai trò của backup và key pair trong việc triển khai, bảo vệ và truy cập instance.
- Phân biệt được Elastic Block Store và Instance Store:
  - EBS là block storage có thể gắn vào EC2 Instance và có khả năng tồn tại độc lập với vòng đời instance.
  - Instance Store là storage tạm thời gắn trực tiếp với phần cứng host và dữ liệu có thể mất khi instance bị stop hoặc terminate.
- Hiểu được vai trò của User Data trong việc tự động chạy script khi EC2 Instance được khởi tạo.
- Hiểu được vai trò của Metadata trong việc cung cấp thông tin về EC2 Instance như instance ID, private IP, public IP, security group và các thông tin cấu hình khác.
- Nắm được khái niệm EC2 Auto Scaling và vai trò của Auto Scaling trong việc:
  - Tự động tăng số lượng EC2 Instance khi hệ thống có tải cao.
  - Tự động giảm số lượng EC2 Instance khi nhu cầu sử dụng giảm.
  - Tăng tính sẵn sàng cho ứng dụng.
  - Tối ưu chi phí vận hành hệ thống.
- Tìm hiểu các dịch vụ mở rộng liên quan đến compute, storage và migration như:
  - Amazon EFS.
  - Amazon FSx.
  - Amazon Lightsail.
  - AWS Application Migration Service.
- Thực hành các bài lab liên quan đến AWS Backup, bao gồm:
  - Lab13-01: Deploy AWS Backup to the System - Introduction.
  - Lab13-02.2: Deploy infrastructure.
  - Lab13-03: Create Backup plan.
  - Lab13-05: Test Restore.
  - Lab13-06: Clean up resources.
- Hiểu được vai trò của AWS Backup trong việc quản lý tập trung các chính sách sao lưu và khôi phục dữ liệu cho tài nguyên trên AWS.
- Biết cách tạo Backup Plan để tự động hóa quá trình sao lưu dữ liệu theo lịch và theo chính sách được cấu hình.
- Thực hành kiểm tra khôi phục dữ liệu thông qua bước Test Restore, từ đó hiểu rõ hơn quy trình đảm bảo dữ liệu có thể được phục hồi khi xảy ra sự cố.
- Thực hành các bài lab liên quan đến Amazon S3 và AWS Storage Gateway, bao gồm:
  - Lab24-01.1: Create S3 Bucket.
  - Lab24-01.2: Create EC2 for Storage Gateway.
  - Lab24-02.1: Create Storage Gateway.
  - Lab24-02.2: Create File Shares.
- Hiểu được vai trò của Amazon S3 trong việc lưu trữ object với khả năng mở rộng cao, độ bền dữ liệu lớn và phù hợp cho nhiều loại dữ liệu khác nhau.
- Hiểu được vai trò của AWS Storage Gateway trong việc kết nối môi trường lưu trữ on-premises với dịch vụ lưu trữ trên AWS.
- Biết cách tạo File Shares để hỗ trợ truy cập và chia sẻ dữ liệu thông qua Storage Gateway.
- Thực hành các bài lab liên quan đến triển khai website tĩnh trên Amazon S3, bao gồm:
  - Lab57-02.1: Create S3 bucket.
  - Lab57-02.2: Load data.
  - Lab57-03: Enable static website feature.
  - Lab57-04: Configuring public access block.
  - Lab57-05: Configuring public objects.
  - Lab57-06: Test website.
- Biết cách cấu hình Amazon S3 để lưu trữ và triển khai một website tĩnh.
- Hiểu được cách cấu hình public access và public objects trong S3 để website có thể được truy cập từ Internet.
- Thực hành kiểm tra website sau khi triển khai để xác nhận dữ liệu được tải lên và website hoạt động đúng.
- Thực hành các bài lab liên quan đến Amazon CloudFront và quản lý object trong S3, bao gồm:
  - Lab57-07.1: Block all public access.
  - Lab57-07.2: Config Amazon CloudFront.
  - Lab57-07.3: Test Amazon CloudFront.
  - Lab57-08: Bucket Versioning.
  - Lab57-09: Move objects.
  - Lab57-10: Replication Object multi Region.
  - Lab57-11: Clean up resources.
- Hiểu được vai trò của Amazon CloudFront trong việc phân phối nội dung website thông qua CDN nhằm cải thiện tốc độ truy cập và tăng tính bảo mật.
- Biết cách cấu hình CloudFront để phân phối nội dung từ S3 Bucket thay vì truy cập trực tiếp vào bucket.
- Hiểu được vai trò của Bucket Versioning trong việc lưu giữ nhiều phiên bản của object, hỗ trợ khôi phục dữ liệu khi object bị ghi đè hoặc xóa nhầm.
- Thực hành di chuyển object trong S3 và hiểu cách quản lý dữ liệu object trong bucket.
- Hiểu được cơ chế Replication Object multi Region để sao chép dữ liệu giữa các region, hỗ trợ tăng độ bền dữ liệu và khả năng dự phòng.
- Biết cách dọn dẹp tài nguyên sau khi hoàn thành bài lab nhằm tránh phát sinh chi phí không cần thiết.
- Rèn luyện kỹ năng thực hành AWS thông qua các bài lab, bao gồm:
  - Đọc yêu cầu bài lab.
  - Thực hiện từng bước cấu hình trên AWS Console.
  - Quan sát kết quả sau khi cấu hình.
  - Ghi nhận lỗi phát sinh nếu có.
  - Kiểm tra kết quả sau khi triển khai.
  - Dọn dẹp tài nguyên sau khi hoàn thành lab.
- Có khả năng liên kết kiến thức lý thuyết về EC2, Auto Scaling, AWS Backup, S3, Storage Gateway và CloudFront với các bài lab thực hành thực tế.
- Hoàn thành ghi chú, tổng hợp kết quả học tập và chuẩn bị nội dung báo cáo cho tuần 4.
