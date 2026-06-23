---

title: "Week 4 Worklog"
date: 2026-05-07
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

- Complete all learning content of Module 03 in the First Cloud AI Journey program.
- Explore Compute VM services on AWS, especially Amazon EC2 and related components.
- Understand basic concepts of Amazon EC2 such as instance types, AMI, backup, key pairs, EBS, instance store, user data, metadata, and EC2 Auto Scaling.
- Learn about related extended services such as EFS, FSx, Lightsail, and AWS Application Migration Service.
- Practice deploying AWS Backup for the system, creating backup plans, testing restores, and cleaning up resources.
- Practice creating S3 Buckets, Storage Gateways, and File Shares to understand the AWS storage model.
- Practice deploying a static website on Amazon S3, configuring public access, CloudFront, bucket versioning, moving objects, and multi-region object replication.
- Develop skills in verifying lab results and cleaning up resources to avoid unnecessary costs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Study Module 03-01: Compute VM on AWS<br>- Study Module 03-01-01: Amazon EC2 - Instance type<br>- Study Module 03-01-02: Amazon EC2 - AMI / Backup / Key Pair<br>- Study Module 03-01-03: Amazon EC2 - Elastic Block Store<br>- Study Module 03-01-04: Amazon EC2 - Instance Store<br>- Study Module 03-01-05: Amazon EC2 - User Data<br>- Study Module 03-01-06: Amazon EC2 - Metadata<br>- Study Module 03-01-07: Amazon EC2 - EC2 Auto Scaling<br>- Study Module 03-02: EC2 Autoscaling - EFS/FSx - Lightsail - MGN | 08/05/2026 | 08/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Complete Lab13-01: Deploy AWS Backup to the System - Introduction<br>- Complete Lab13-02.2: Deploy infrastructure<br>- Complete Lab13-03: Create Backup plan<br>- Complete Lab13-05: Test Restore<br>- Complete Lab13-06: Clean up resources<br>- Note the process of deploying backups, testing data recovery, and cleaning up resources | 11/05/2026 | 11/05/2026 | https://000013.awsstudygroup.com |
| 3 | - Complete Lab24-01.1: Create S3 Bucket<br>- Complete Lab24-01.2: Create EC2 for Storage Gateway<br>- Complete Lab24-02.1: Create Storage Gateway<br>- Complete Lab24-02.2: Create File Shares<br>- Understand the roles of Amazon S3, AWS Storage Gateway, and File Shares | 12/05/2026 | 12/05/2026 | https://000024.awsstudygroup.com |
| 4 | - Complete Lab57-02.1: Create S3 bucket<br>- Complete Lab57-02.2: Load data<br>- Complete Lab57-03: Enable static website feature<br>- Complete Lab57-04: Configuring public access block<br>- Complete Lab57-05: Configuring public objects<br>- Complete Lab57-06: Test website | 13/05/2026 | 13/05/2026 | https://000057.awsstudygroup.com |
| 5 | - Complete Lab57-07.1: Block all public access<br>- Complete Lab57-07.2: Config Amazon CloudFront<br>- Complete Lab57-07.3: Test Amazon CloudFront<br>- Complete Lab57-08: Bucket Versioning<br>- Complete Lab57-09: Move objects<br>- Complete Lab57-10: Replication Object multi Region<br>- Complete Lab57-11: Clean up resources | 14/05/2026 | 14/05/2026 | https://000057.awsstudygroup.com |

### Week 4 Achievements:

- Completed all learning content of Module 03 in the First Cloud AI Journey program.
- Understood the role of Compute VM services on AWS in providing virtual server resources for deploying applications and workloads.
- Understood the role of Amazon EC2 in providing flexible virtual servers on AWS.
- Mastered key concepts of Amazon EC2, including:
  - Instance Type.
  - AMI.
  - Backup.
  - Key Pair.
  - Elastic Block Store.
  - Instance Store.
  - User Data.
  - Metadata.
  - EC2 Auto Scaling.
- Understood the role of Instance Type in selecting the appropriate resource configuration for workloads, including CPU, RAM, network performance, and storage performance.
- Understood that an AMI is a template used to launch EC2 instances, and learned the roles of backup and key pairs in deployment, protection, and access.
- Differentiated between Elastic Block Store and Instance Store:
  - EBS is block storage that can be attached to EC2 instances and can persist independently of the instance lifecycle.
  - Instance Store is temporary storage directly attached to the host hardware, and data may be lost when the instance is stopped or terminated.
- Understood the role of User Data in automatically running scripts when an EC2 instance is launched.
- Understood the role of Metadata in providing info about EC2 instances such as instance ID, private IP, public IP, security groups, and other configuration info.
- Mastered the concept of EC2 Auto Scaling and its role in:
  - Automatically increasing the number of EC2 instances during high system load.
  - Automatically decreasing the number of EC2 instances when demand drops.
  - Increasing application availability.
  - Optimizing system operation costs.
- Explored extended services related to compute, storage, and migration such as:
  - Amazon EFS.
  - Amazon FSx.
  - Amazon Lightsail.
  - AWS Application Migration Service.
- Practiced labs related to AWS Backup, including:
  - Lab13-01: Deploy AWS Backup to the System - Introduction.
  - Lab13-02.2: Deploy infrastructure.
  - Lab13-03: Create Backup plan.
  - Lab13-05: Test Restore.
  - Lab13-06: Clean up resources.
- Understood the role of AWS Backup in centrally managing backup and recovery policies for AWS resources.
- Learned how to create Backup Plans to automate data backups according to schedules and configured policies.
- Practiced testing data recovery through the Test Restore step, thereby understanding the process of ensuring data can be recovered during incidents.
- Practiced labs related to Amazon S3 and AWS Storage Gateway, including:
  - Lab24-01.1: Create S3 Bucket.
  - Lab24-01.2: Create EC2 for Storage Gateway.
  - Lab24-02.1: Create Storage Gateway.
  - Lab24-02.2: Create File Shares.
- Understood the role of Amazon S3 in object storage with high scalability, great data durability, and suitability for various data types.
- Understood the role of AWS Storage Gateway in connecting on-premises storage environments with AWS storage services.
- Learned how to create File Shares to support data access and sharing via Storage Gateway.
- Practiced labs related to static website deployment on Amazon S3, including:
  - Lab57-02.1: Create S3 bucket.
  - Lab57-02.2: Load data.
  - Lab57-03: Enable static website feature.
  - Lab57-04: Configuring public access block.
  - Lab57-05: Configuring public objects.
  - Lab57-06: Test website.
- Learned how to configure Amazon S3 to store and deploy a static website.
- Understood how to configure public access and public objects in S3 so the website can be accessed from the Internet.
- Practiced testing the website after deployment to confirm data upload and correct functionality.
- Practiced labs related to Amazon CloudFront and object management in S3, including:
  - Lab57-07.1: Block all public access.
  - Lab57-07.2: Config Amazon CloudFront.
  - Lab57-07.3: Test Amazon CloudFront.
  - Lab57-08: Bucket Versioning.
  - Lab57-09: Move objects.
  - Lab57-10: Replication Object multi Region.
  - Lab57-11: Clean up resources.
- Understood the role of Amazon CloudFront in distributing website content via CDN to improve access speed and increase security.
- Learned how to configure CloudFront to distribute content from an S3 bucket instead of direct bucket access.
- Understood the role of Bucket Versioning in keeping multiple versions of an object, supporting data recovery if an object is overwritten or accidentally deleted.
- Practiced moving objects in S3 and understood object data management in buckets.
- Understood the Multi-Region Object Replication mechanism for copying data between regions, supporting increased data durability and redundancy.
- Learned how to clean up resources after completing labs to avoid unnecessary costs.
- Developed AWS practice skills through labs, including:
  - Reading lab requirements.
  - Performing step-by-step configuration on AWS Console.
  - Observing results after configuration.
  - Documenting errors if any.
  - Testing results after deployment.
  - Cleaning up resources after completion.
- Acquired the ability to link theoretical knowledge of EC2, Auto Scaling, AWS Backup, S3, Storage Gateway, and CloudFront with practical labs.
- Completed notes, summarized learning outcomes, and prepared content for the Week 4 report.
