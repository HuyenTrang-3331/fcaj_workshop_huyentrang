---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

- Hoàn thành nội dung học tập của Module 05 về bảo mật và quản lý danh tính trên AWS.
- Hiểu mô hình Shared Responsibility Model và trách nhiệm bảo mật giữa AWS và người dùng.
- Tìm hiểu các dịch vụ bảo mật và quản lý danh tính như IAM, Amazon Cognito, AWS Organizations, AWS Identity Center, AWS KMS và AWS Security Hub.
- Thực hành bật AWS Security Hub, kiểm tra điểm đánh giá theo từng tiêu chí và dọn dẹp tài nguyên.
- Thực hành sử dụng tag để quản lý tài nguyên AWS, tạo Resource Group và thao tác với tag bằng AWS CLI.
- Thực hành tạo IAM User, IAM Policy, IAM Role, Switch Role và kiểm tra quyền truy cập theo điều kiện tag.
- Thực hành tạo restriction policy, IAM limited user và kiểm tra giới hạn quyền của IAM User.
- Thực hành mã hóa dữ liệu với AWS KMS, CloudTrail, Athena và kiểm tra chia sẻ dữ liệu đã mã hóa trên S3.
- Thực hành giới hạn switch role theo IP, thời gian và làm việc với access key, IAM role trong EC2.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Học Module 05-01: Shared Responsibility Model<br>- Học Module 05-02: Amazon Identity and Access Management<br>- Học Module 05-03: Amazon Cognito<br>- Học Module 05-04: AWS Organization<br>- Học Module 05-05: AWS Identity Center<br>- Học Module 05-06: Amazon Key Management Service<br>- Học Module 05-07: AWS Security Hub<br>- Học Module 05-08: Hands-on and Additional research<br>- Ghi chú các khái niệm quan trọng về bảo mật, IAM, quản lý danh tính, tổ chức tài khoản, mã hóa và giám sát bảo mật | 22/05/2026 | 22/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Làm Lab18-02: Enable Security Hub<br>- Làm Lab18-03: Score for each set of criteria<br>- Làm Lab18-04: Clean up resources<br>- Làm Lab22-2.1: Create VPC<br>- Làm Lab22-2.2: Create Security Group<br>- Làm Lab22-2.3: Create EC2 Instance<br>- Làm Lab22-2.4: Incoming Webhooks Slack<br>- Làm Lab22-3: Create Tag for Instance<br>- Làm Lab22-4: Create Role for Lambda<br>- Làm Lab22-5.1: Function stop instance<br>- Làm Lab22-5.2: Function start instance<br>- Làm Lab22-6: Check Result<br>- Làm Lab22-7: Clean up resources | 25/05/2026 | 25/05/2026 | https://000018.awsstudygroup.com<br>https://000022.awsstudygroup.com |
| 3 | - Làm Lab27-2.1.1: Create EC2 Instance with tag<br>- Làm Lab27-2.1.2: Managing Tags in AWS Resources<br>- Làm Lab27-2.1.3: Filter resources by tag<br>- Làm Lab27-2.2: Using tags with CLI<br>- Làm Lab27-3: Create a Resource Group<br>- Làm Lab27-4: Clean up resources<br>- Làm Lab28-2.1: Create IAM user<br>- Làm Lab28-3: Create IAM Policy<br>- Làm Lab28-4: Create IAM Role<br>- Làm Lab28-5.1: Switch Roles | 26/05/2026 | 26/05/2026 | https://000027.awsstudygroup.com<br>https://000028.awsstudygroup.com |
| 4 | - Làm Lab28-5.2.1: Initiating access to EC2 console in AWS Region - Tokyo<br>- Làm Lab28-5.2.2: Initiating access to EC2 console in AWS Region - North Virginia<br>- Làm Lab28-5.2.3: Proceed to create EC2 instance when there are no qualified Tags<br>- Làm Lab28-5.2.4: Edit Resource Tag on EC2 Instance<br>- Làm Lab28-5.2.5: Policy Check<br>- Làm Lab28-6: Clean up resources<br>- Làm Lab30-3: Create Restriction Policy<br>- Làm Lab30-4: Create IAM Limited User<br>- Làm Lab30-5: Test IAM User Limits<br>- Làm Lab30-6: Clean up resources | 27/05/2026 | 27/05/2026 | https://000028.awsstudygroup.com<br>https://000030.awsstudygroup.com |
| 5 | - Làm Lab33-2.1: Create Policy and Role<br>- Làm Lab33-2.2: Create Group and User<br>- Làm Lab33-3: Create Key Management Service<br>- Làm Lab33-4.1: Create Bucket<br>- Làm Lab33-4.2: Upload data to S3<br>- Làm Lab33-5.1: Create CloudTrail<br>- Làm Lab33-5.2: Logging to CloudTrail<br>- Làm Lab33-5.3: Create Amazon Athena<br>- Làm Lab33-5.4: Retrieve data with Athena<br>- Làm Lab33-6: Test and share encrypted data on S3<br>- Làm Lab33-7: Resource cleanup<br>- Làm Lab44-2: Create IAM Group<br>- Làm Lab44-3.1: Create IAM Users<br>- Làm Lab44-3.2: Check permissions<br>- Làm Lab44-4.1: Create Admin IAM Role<br>- Làm Lab44-4.2: Configure Switch Role<br>- Làm Lab44-4.3.1: Limit switch role by IP<br>- Làm Lab44-4.3.2: Limit switch role by Time<br>- Làm Lab44-5: Clean up resources<br>- Làm Lab48-1.1: Create EC2 Instance<br>- Làm Lab48-1.2: Create S3 Bucket<br>- Làm Lab48-2.1: Generate IAM user and access key<br>- Làm Lab48-2.2: Use access key<br>- Làm Lab48-3.1: Create IAM role<br>- Làm Lab48-3.2: Using IAM role<br>- Làm Lab48-4: Clean up resources | 28/05/2026 | 28/05/2026 | https://000033.awsstudygroup.com<br>https://000044.awsstudygroup.com<br>https://000048.awsstudygroup.com |

### Kết quả đạt được tuần 6:

- Hoàn thành nội dung học tập của Module 05 về bảo mật và quản lý danh tính trên AWS trong chương trình First Cloud AI Journey.
- Hiểu được Shared Responsibility Model và phân biệt trách nhiệm bảo mật giữa AWS và người dùng:
  - AWS chịu trách nhiệm bảo mật của cloud.
  - Người dùng chịu trách nhiệm bảo mật trong cloud.
  - Người dùng cần cấu hình đúng quyền truy cập, dữ liệu, tài nguyên, mạng và workload.
- Nắm được vai trò của AWS Identity and Access Management trong việc quản lý:
  - IAM User.
  - IAM Group.
  - IAM Role.
  - IAM Policy.
  - Permission.
  - Access Key.
  - Switch Role.
- Hiểu được vai trò của Amazon Cognito trong việc quản lý xác thực và phân quyền cho người dùng ứng dụng.
- Hiểu được vai trò của AWS Organizations trong việc quản lý nhiều AWS Account, phân nhóm tài khoản và áp dụng chính sách kiểm soát tập trung.
- Hiểu được vai trò của AWS Identity Center trong việc hỗ trợ đăng nhập tập trung, quản lý người dùng và phân quyền truy cập nhiều tài khoản AWS.
- Hiểu được vai trò của AWS Key Management Service trong việc tạo, quản lý và sử dụng khóa mã hóa để bảo vệ dữ liệu.
- Hiểu được vai trò của AWS Security Hub trong việc tổng hợp, đánh giá và theo dõi trạng thái bảo mật của tài khoản AWS.
- Thực hành các bài lab liên quan đến AWS Security Hub, bao gồm:
  - Lab18-02: Enable Security Hub.
  - Lab18-03: Score for each set of criteria.
  - Lab18-04: Clean up resources.
- Biết cách bật AWS Security Hub, xem điểm đánh giá theo từng nhóm tiêu chí và dọn dẹp tài nguyên sau khi hoàn thành lab.
- Thực hành tạo VPC, Security Group và EC2 Instance phục vụ cho bài lab tự động hóa quản lý instance.
- Thực hành tích hợp Incoming Webhooks Slack để nhận thông báo trong quá trình xử lý tự động.
- Biết cách tạo tag cho EC2 Instance và sử dụng tag để xác định tài nguyên cần quản lý.
- Thực hành tạo Role cho Lambda và xây dựng các function cơ bản:
  - Function stop instance.
  - Function start instance.
  - Check Result.
  - Clean up resources.
- Hiểu được cách Lambda có thể sử dụng IAM Role để thao tác với tài nguyên AWS theo quyền được cấp.
- Thực hành các bài lab liên quan đến quản lý tag, bao gồm:
  - Lab27-2.1.1: Create EC2 Instance with tag.
  - Lab27-2.1.2: Managing Tags in AWS Resources.
  - Lab27-2.1.3: Filter resources by tag.
  - Lab27-2.2: Using tags with CLI.
  - Lab27-3: Create a Resource Group.
  - Lab27-4: Clean up resources.
- Hiểu được vai trò của tag trong việc phân loại, tìm kiếm, lọc và quản lý tài nguyên AWS.
- Biết cách sử dụng AWS CLI để làm việc với tag và lọc tài nguyên theo tag.
- Biết cách tạo Resource Groups để gom nhóm tài nguyên theo điều kiện tag.
- Thực hành các bài lab liên quan đến IAM User, IAM Policy, IAM Role và Switch Role, bao gồm:
  - Lab28-2.1: Create IAM user.
  - Lab28-3: Create IAM Policy.
  - Lab28-4: Create IAM Role.
  - Lab28-5.1: Switch Roles.
  - Lab28-5.2.1: Initiating access to EC2 console in AWS Region - Tokyo.
  - Lab28-5.2.2: Initiating access to EC2 console in AWS Region - North Virginia.
  - Lab28-5.2.3: Proceed to create EC2 instance when there are no qualified Tags.
  - Lab28-5.2.4: Edit Resource Tag on EC2 Instance.
  - Lab28-5.2.5: Policy Check.
  - Lab28-6: Clean up resources.
- Hiểu được cách IAM Policy có thể kiểm soát hành động của người dùng dựa trên điều kiện như region hoặc resource tag.
- Biết cách kiểm tra quyền truy cập khi người dùng thao tác với EC2 Instance trong các region khác nhau.
- Hiểu được cách resource tag ảnh hưởng đến việc cho phép hoặc từ chối tạo EC2 Instance theo chính sách đã cấu hình.
- Thực hành tạo restriction policy, IAM limited user và kiểm tra giới hạn quyền của IAM User thông qua:
  - Lab30-3: Create Restriction Policy.
  - Lab30-4: Create IAM Limited User.
  - Lab30-5: Test IAM User Limits.
  - Lab30-6: Clean up resources.
- Hiểu được cách áp dụng policy để giới hạn quyền người dùng theo nguyên tắc least privilege.
- Thực hành các bài lab liên quan đến AWS KMS, S3, CloudTrail và Athena, bao gồm:
  - Lab33-2.1: Create Policy and Role.
  - Lab33-2.2: Create Group and User.
  - Lab33-3: Create Key Management Service.
  - Lab33-4.1: Create Bucket.
  - Lab33-4.2: Upload data to S3.
  - Lab33-5.1: Create CloudTrail.
  - Lab33-5.2: Logging to CloudTrail.
  - Lab33-5.3: Create Amazon Athena.
  - Lab33-5.4: Retrieve data with Athena.
  - Lab33-6: Test and share encrypted data on S3.
  - Lab33-7: Resource cleanup.
- Biết cách tạo KMS Key để mã hóa dữ liệu trên S3.
- Hiểu được vai trò của CloudTrail trong việc ghi nhận hoạt động API và hành vi truy cập tài nguyên AWS.
- Biết cách sử dụng Amazon Athena để truy vấn và phân tích log được lưu trữ trên S3.
- Hiểu được cách kiểm tra và chia sẻ dữ liệu đã mã hóa trên S3 thông qua KMS.
- Thực hành các bài lab liên quan đến IAM Group, IAM User, Admin Role và Switch Role, bao gồm:
  - Lab44-2: Create IAM Group.
  - Lab44-3.1: Create IAM Users.
  - Lab44-3.2: Check permissions.
  - Lab44-4.1: Create Admin IAM Role.
  - Lab44-4.2: Configure Switch Role.
  - Lab44-4.3.1: Limit switch role by IP.
  - Lab44-4.3.2: Limit switch role by Time.
  - Lab44-5: Clean up resources.
- Hiểu được cách giới hạn quyền switch role theo IP và theo thời gian để tăng cường kiểm soát truy cập.
- Thực hành các bài lab liên quan đến access key và IAM Role cho EC2, bao gồm:
  - Lab48-1.1: Create EC2 Instance.
  - Lab48-1.2: Create S3 Bucket.
  - Lab48-2.1: Generate IAM user and access key.
  - Lab48-2.2: Use access key.
  - Lab48-3.1: Create IAM role.
  - Lab48-3.2: Using IAM role.
  - Lab48-4: Clean up resources.
- Hiểu được sự khác biệt giữa sử dụng Access Key của IAM User và sử dụng IAM Role cho EC2 Instance.
- Nhận thức được rủi ro khi sử dụng access key dài hạn và vai trò của IAM Role trong việc cấp quyền tạm thời, an toàn hơn cho workload.
- Rèn luyện kỹ năng thực hành AWS Security thông qua các bài lab, bao gồm:
  - Đọc yêu cầu bài lab.
  - Cấu hình IAM User, Group, Role và Policy.
  - Kiểm tra quyền truy cập sau khi cấu hình.
  - Quan sát kết quả trên AWS Console.
  - Ghi nhận lỗi phát sinh nếu có.
  - Dọn dẹp tài nguyên sau khi hoàn thành lab để tránh phát sinh chi phí không cần thiết.
- Có khả năng liên kết kiến thức lý thuyết về bảo mật, IAM, KMS, CloudTrail, Athena, Security Hub và tag-based access control với các bài lab thực hành thực tế.
- Hoàn thành ghi chú, tổng hợp kết quả học tập và chuẩn bị nội dung báo cáo cho tuần 6.
