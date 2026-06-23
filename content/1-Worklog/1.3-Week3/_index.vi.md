--- 
title: "Worklog Tuần 3" 
date: 2026-05-01 
weight: 3 
chapter: false 
pre: " <b> 1.3. </b> " 
--- 

### Mục tiêu tuần 3: 

- Hoàn thành nội dung học tập của Module 02 về Amazon Virtual Private Cloud trong chương trình First Cloud AI Journey.
- Hiểu rõ các thành phần cốt lõi của mạng AWS và cách chúng phối hợp để tạo ra một môi trường an toàn.
- Thực hành xây dựng các mô hình mạng từ cơ bản đến nâng cao như VPC Peering, Transit Gateway và Hybrid DNS.
- Nắm vững cách kiểm soát lưu lượng mạng thông qua Security Groups và Network ACLs.

### Các nhiệm vụ sẽ được thực hiện trong tuần này: 
 
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo | 
| :--- | :------- | :----------- | :-------------- | :----------------- | 
| 1 | - Học Module 02-01: AWS Virtual Private Cloud <br>- Tìm hiểu khái niệm Amazon VPC và vai trò của VPC trong kiến trúc AWS <br>- Học Module 02-02: VPC Security and Multi-VPC features <br>- Tìm hiểu các cơ chế bảo mật trong VPC và các mô hình kết nối nhiều VPC <br>- Học Module 02-03: VPN, Direct Connect, Load Balancer và Extra Resources <br>- Ghi chú các khái niệm quan trọng liên quan đến kết nối mạng và cân bằng tải | 01/05/2026 | 01/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Làm Lab03-01: Start with Amazon VPC and AWS VPN Site-to-Site Introduction <br>- Làm Lab03-01.1: Subnets <br>- Làm Lab03-01.2: Route Table <br>- Làm Lab03-01.3: Internet Gateway IGW <br>- Làm Lab03-01.4: NAT Gateway <br>- Làm Lab03-02.1: Security Group <br>- Làm Lab03-02.2: Network ACLs <br>- Làm Lab03-02.3: VPC Resource Map | 04/05/2026 | 04/05/2026 | https://00003.awsstudygroup.com |  
| 3 | - Làm Lab03-03.1: Create VPC <br>- Làm Lab03-03.2: Create Subnet <br>- Làm Lab03-03.3: Create an Internet Gateway <br>- Làm Lab03-03.4: Create Route Table for Outbound Internet Routing via Internet Gateway <br>- Làm Lab03-03.5: Create Security Groups <br>- Làm Lab03-04.1: Create EC2 Instances in Subnets <br>- Làm Lab03-04.2: Test Connection <br>- Làm Lab03-04.3: Create NAT Gateway <br>- Làm Lab03-04.5: EC2 Instance Connect Endpoint | 05/05/2026 | 05/05/2026 | https://00003.awsstudygroup.com | 
| 4 | - Làm Lab10-01: Set up Hybrid DNS with Route 53 Resolver Introduction <br>- Làm Lab10-02.1: Generate Key Pair <br>- Làm Lab10-02.2: Initialize CloudFormation Template <br>- Làm Lab10-02.3: Configure Security Group <br>- Làm Lab10-03: Connect to RDGW <br>- Làm Lab10-05: Set up DNS <br>- Làm Lab10-05.1: Create Route 53 Outbound Endpoint <br>- Làm Lab10-05.2: Create Route 53 Resolver Rules <br>- Làm Lab10-05.3: Create Route 53 Inbound Endpoints <br>- Làm Lab10-05.4: Test Results <br>- Làm Lab10-06: Clean up Resources | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com | 
| 5 | - Làm Lab19-01: Set up VPC Peering Introduction <br>- Làm Lab19-02.1: Initialize CloudFormation Templates <br>- Làm Lab19-02.2: Create Security Group <br>- Làm Lab19-02.3: Create EC2 Instance <br>- Làm Lab19-03: Update Network ACLs <br>- Làm Lab19-04: Create a Peering Connection <br>- Làm Lab19-05: Configure Route Tables <br>- Làm Lab19-06: Enable Cross-Peer DNS <br>- Làm Lab19-07: Clean up Resources <br>- Làm Lab20-01: Set up AWS Transit Gateway Introduction <br>- Làm Lab20-02: Preparation Steps <br>- Làm Lab20-03: Create Transit Gateway <br>- Làm Lab20-04: Create Transit Gateway Attachments <br>- Làm Lab20-05: Create Transit Gateway Route Tables <br>- Làm Lab20-06: Add Transit Gateway Routes to VPC Route Tables <br>- Làm Lab20-07: Clean up Resources | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com <br> | https://000020.awsstudygroup.com | |  

### Kết quả đạt được tuần 3: 
 
- Hoàn thành nội dung học tập của Module 02 về Amazon Virtual Private Cloud trong chương trình First Cloud AI Journey. 
- Hiểu được vai trò của Amazon VPC trong việc xây dựng môi trường mạng riêng, cô lập và có khả năng kiểm soát truy cập trên AWS. 
- Nắm được các thành phần quan trọng trong kiến trúc mạng AWS, bao gồm: 
    - VPC. 
    - Subnet. 
    - Route Table. 
    - Internet Gateway. 
    - NAT Gateway. 
    - Security Group. 
    - Network ACLs. 
    - EC2 Instance Connect Endpoint. 
    - VPC Resource Map. 
- Hiểu được sự khác nhau giữa Security Group và Network ACLs: 
    - Security Group hoạt động ở cấp instance hoặc elastic network interface. 
    - Network ACLs hoạt động ở cấp subnet. 
    - Security Group có tính stateful. 
    - Network ACLs có tính stateless. 
- Thực hành các bài lab liên quan đến Amazon VPC, bao gồm: 
    - Lab03-01: Start with Amazon VPC and AWS VPN Site-to-Site Introduction. 
    - Lab03-01.1: Subnets. 
    - Lab03-01.2: Route Table. 
    - Lab03-01.3: Internet Gateway. 
    - Lab03-01.4: NAT Gateway. 
    - Lab03-02.1: Security Group. 
    - Lab03-02.2: Network ACLs. 
    - Lab03-02.3: VPC Resource Map. 
- Thực hành tạo và cấu hình các thành phần mạng cơ bản trong AWS, bao gồm: 
    - Create VPC. 
    - Create Subnet. 
    - Create an Internet Gateway. 
    - Create Route Table for Outbound Internet Routing via Internet Gateway. 
    - Create Security Groups. 
    - Create EC2 Instances in Subnets. 
    - Test Connection. 
    - Create NAT Gateway. 
    - EC2 Instance Connect Endpoint. 
- Hiểu được vai trò của Internet Gateway trong việc cho phép tài nguyên trong Public Subnet truy cập Internet. 
- Hiểu được vai trò của NAT Gateway trong việc cho phép tài nguyên trong Private Subnet truy cập Internet theo chiều outbound mà không cần public IP. 
- Nắm được cách sử dụng Route Table để điều hướng lưu lượng mạng giữa các subnet, Internet Gateway, NAT Gateway và các thành phần kết nối khác. 
- Tìm hiểu các mô hình kết nối mở rộng trong AWS như: 
    - VPN Site-to-Site. 
    - AWS Direct Connect. 
    - Load Balancer. 
    - VPC Peering. 
    - Transit Gateway. 
- Thực hành cấu hình Hybrid DNS với Route 53 Resolver, bao gồm: 
    - Lab10-01: Set up Hybrid DNS with Route 53 Resolver Introduction. 
    - Lab10-02.1: Generate Key Pair. 
    - Lab10-02.2: Initialize CloudFormation Template. 
    - Lab10-02.3: Configure Security Group. 
    - Lab10-03: Connect to RDGW. 
    - Lab10-05: Set up DNS. 
    - Lab10-05.1: Create Route 53 Outbound Endpoint. 
    - Lab10-05.2: Create Route 53 Resolver Rules. 
    - Lab10-05.3: Create Route 53 Inbound Endpoints. 
    - Lab10-05.4: Test Results. 
    - Lab10-06: Clean up Resources. 
- Hiểu được vai trò của Route 53 Resolver trong mô hình Hybrid DNS, hỗ trợ phân giải tên miền giữa môi trường AWS và môi trường on-premises. 
- Thực hành cấu hình VPC Peering, bao gồm: 
    - Lab19-01: Set up VPC Peering Introduction. 
    - Lab19-02.1: Initialize CloudFormation Templates. 
    - Lab19-02.2: Create Security Group. 
    - Lab19-02.3: Create EC2 Instance. 
    - Lab19-03: Update Network ACLs. 
    - Lab19-04: Create a Peering Connection. 
    - Lab19-05: Configure Route Tables. 
    - Lab19-06: Enable Cross-Peer DNS. 
    - Lab19-07: Clean up Resources. 
- Hiểu được VPC Peering là phương thức kết nối trực tiếp giữa hai VPC, giúp tài nguyên trong các VPC có thể giao tiếp với nhau thông qua private IP. 
- Thực hành cấu hình AWS Transit Gateway, bao gồm: 
    - Lab20-01: Set up AWS Transit Gateway Introduction. 
    - Lab20-02: Preparation Steps. 
    - Lab20-03: Create Transit Gateway. 
    - Lab20-04: Create Transit Gateway Attachments. 
    - Lab20-05: Create Transit Gateway Route Tables. 
    - Lab20-06: Add Transit Gateway Routes to VPC Route Tables. 
    - Lab20-07: Clean up Resources. 
- Hiểu được AWS Transit Gateway giúp đơn giản hóa việc kết nối nhiều VPC và hệ thống mạng khác nhau theo mô hình trung tâm, thay vì phải tạo nhiều kết nối VPC Peering phức tạp. 
- Biết cách kiểm tra kết quả sau khi cấu hình mạng, bao gồm: 
    - Kiểm tra kết nối giữa các instance. 
    - Kiểm tra route table. 
    - Kiểm tra security group. 
    - Kiểm tra Network ACLs. 
    - Kiểm tra DNS resolution. 
    - Kiểm tra kết nối qua VPC Peering hoặc Transit Gateway. 
- Rèn luyện kỹ năng thực hành AWS Networking thông qua các bài lab: 
    - Đọc yêu cầu bài lab. 
    - Thực hiện từng bước cấu hình trên AWS Console. 
    - Quan sát kết quả sau khi cấu hình. 
    - Ghi nhận lỗi phát sinh nếu có. 
    - Dọn dẹp tài nguyên sau khi hoàn thành lab để tránh phát sinh chi phí. 
- Có khả năng liên kết kiến thức lý thuyết về AWS Networking với bài lab thực hành thực tế. 
- Hoàn thành ghi chú, tổng hợp kết quả học tập và chuẩn bị nội dung báo cáo cho tuần 3. 
