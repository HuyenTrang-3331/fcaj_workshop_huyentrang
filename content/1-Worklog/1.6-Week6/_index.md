---
title: "Week 6 Worklog"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:

- Complete all learning content of Module 05 on security and identity management on AWS.
- Understand the Shared Responsibility Model and security responsibilities between AWS and users.
- Explore security and identity management services like IAM, Amazon Cognito, AWS Organizations, AWS Identity Center, AWS KMS, and AWS Security Hub.
- Practice enabling AWS Security Hub, checking assessment scores by criteria, and cleaning up resources.
- Practice using tags to manage AWS resources, creating Resource Groups, and working with tags using AWS CLI.
- Practice creating IAM Users, IAM Policies, IAM Roles, Switch Roles, and checking access permissions based on tag conditions.
- Practice creating restriction policies, IAM limited users, and testing IAM User permission limits.
- Practice encrypting data with AWS KMS, CloudTrail, Athena, and testing sharing encrypted data on S3.
- Practice limiting switch roles by IP and time, and working with access keys and IAM Roles in EC2.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :------- | :----------- | :-------------- | :----------------- |
| 1 | - Study Module 05-01: Shared Responsibility Model<br>- Study Module 05-02: Amazon Identity and Access Management<br>- Study Module 05-03: Amazon Cognito<br>- Study Module 05-04: AWS Organization<br>- Study Module 05-05: AWS Identity Center<br>- Study Module 05-06: Amazon Key Management Service<br>- Study Module 05-07: AWS Security Hub<br>- Study Module 05-08: Hands-on and Additional research<br>- Note important concepts about security, IAM, identity management, account organization, encryption, and security monitoring | 22/05/2026 | 22/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2 | - Complete Lab18-02: Enable Security Hub<br>- Complete Lab18-03: Score for each set of criteria<br>- Complete Lab18-04: Clean up resources<br>- Complete Lab22-2.1: Create VPC<br>- Complete Lab22-2.2: Create Security Group<br>- Complete Lab22-2.3: Create EC2 Instance<br>- Complete Lab22-2.4: Incoming Webhooks Slack<br>- Complete Lab22-3: Create Tag for Instance<br>- Complete Lab22-4: Create Role for Lambda<br>- Complete Lab22-5.1: Function stop instance<br>- Complete Lab22-5.2: Function start instance<br>- Complete Lab22-6: Check Result<br>- Complete Lab22-7: Clean up resources | 25/05/2026 | 25/05/2026 | https://000018.awsstudygroup.com<br>https://000022.awsstudygroup.com |
| 3 | - Complete Lab27-2.1.1: Create EC2 Instance with tag<br>- Complete Lab27-2.1.2: Managing Tags in AWS Resources<br>- Complete Lab27-2.1.3: Filter resources by tag<br>- Complete Lab27-2.2: Using tags with CLI<br>- Complete Lab27-3: Create a Resource Group<br>- Complete Lab27-4: Clean up resources<br>- Complete Lab28-2.1: Create IAM user<br>- Complete Lab28-3: Create IAM Policy<br>- Complete Lab28-4: Create IAM Role<br>- Complete Lab28-5.1: Switch Roles | 26/05/2026 | 26/05/2026 | https://000027.awsstudygroup.com<br>https://000028.awsstudygroup.com |
| 4 | - Complete Lab28-5.2.1: Initiating access to EC2 console in AWS Region - Tokyo<br>- Complete Lab28-5.2.2: Initiating access to EC2 console in AWS Region - North Virginia<br>- Complete Lab28-5.2.3: Proceed to create EC2 instance when there are no qualified Tags<br>- Complete Lab28-5.2.4: Edit Resource Tag on EC2 Instance<br>- Complete Lab28-5.2.5: Policy Check<br>- Complete Lab28-6: Clean up resources<br>- Complete Lab30-3: Create Restriction Policy<br>- Complete Lab30-4: Create IAM Limited User<br>- Complete Lab30-5: Test IAM User Limits<br>- Complete Lab30-6: Clean up resources | 27/05/2026 | 27/05/2026 | https://000028.awsstudygroup.com<br>https://000030.awsstudygroup.com |
| 5 | - Complete Lab33-2.1: Create Policy and Role<br>- Complete Lab33-2.2: Create Group and User<br>- Complete Lab33-3: Create Key Management Service<br>- Complete Lab33-4.1: Create Bucket<br>- Complete Lab33-4.2: Upload data to S3<br>- Complete Lab33-5.1: Create CloudTrail<br>- Complete Lab33-5.2: Logging to CloudTrail<br>- Complete Lab33-5.3: Create Amazon Athena<br>- Complete Lab33-5.4: Retrieve data with Athena<br>- Complete Lab33-6: Test and share encrypted data on S3<br>- Complete Lab33-7: Resource cleanup<br>- Complete Lab44-2: Create IAM Group<br>- Complete Lab44-3.1: Create IAM Users<br>- Complete Lab44-3.2: Check permissions<br>- Complete Lab44-4.1: Create Admin IAM Role<br>- Complete Lab44-4.2: Configure Switch Role<br>- Complete Lab44-4.3.1: Limit switch role by IP<br>- Complete Lab44-4.3.2: Limit switch role by Time<br>- Complete Lab44-5: Clean up resources<br>- Complete Lab48-1.1: Create EC2 Instance<br>- Complete Lab48-1.2: Create S3 Bucket<br>- Complete Lab48-2.1: Generate IAM user and access key<br>- Complete Lab48-2.2: Use access key<br>- Complete Lab48-3.1: Create IAM role<br>- Complete Lab48-3.2: Using IAM role<br>- Complete Lab48-4: Clean up resources | 28/05/2026 | 28/05/2026 | https://000033.awsstudygroup.com<br>https://000044.awsstudygroup.com<br>https://000048.awsstudygroup.com |

### Week 6 Achievements:

- Completed all learning content of Module 05 on security and identity management on AWS in the First Cloud AI Journey program.
- Understood the Shared Responsibility Model and distinguished security responsibilities between AWS and users:
  - AWS is responsible for security of the cloud.
  - Users are responsible for security in the cloud.
  - Users need to correctly configure access permissions, data, resources, network, and workload.
- Mastered the role of AWS Identity and Access Management in managing:
  - IAM User.
  - IAM Group.
  - IAM Role.
  - IAM Policy.
  - Permission.
  - Access Key.
  - Switch Role.
- Understood the role of Amazon Cognito in managing authentication and authorization for application users.
- Understood the role of AWS Organizations in managing multiple AWS Accounts, grouping accounts, and applying centralized control policies.
- Understood the role of AWS Identity Center in supporting centralized login, user management, and access authorization across multiple AWS accounts.
- Understood the role of AWS Key Management Service in creating, managing, and using encryption keys to protect data.
- Understood the role of AWS Security Hub in aggregating, assessing, and monitoring the security posture of AWS accounts.
- Practiced labs related to AWS Security Hub, including:
  - Lab18-02: Enable Security Hub.
  - Lab18-03: Score for each set of criteria.
  - Lab18-04: Clean up resources.
- Learned how to enable AWS Security Hub, view assessment scores by criteria groups, and clean up resources after completing labs.
- Practiced creating VPC, Security Group, and EC2 Instance for instance automation management labs.
- Practiced integrating Incoming Webhooks Slack to receive notifications during automated processing.
- Learned how to create tags for EC2 Instance and use tags to identify resources to manage.
- Practiced creating Roles for Lambda and building basic functions:
  - Function stop instance.
  - Function start instance.
  - Check Result.
  - Clean up resources.
- Understood how Lambda can use IAM Roles to interact with AWS resources according to granted permissions.
- Practiced labs related to tag management, including:
  - Lab27-2.1.1: Create EC2 Instance with tag.
  - Lab27-2.1.2: Managing Tags in AWS Resources.
  - Lab27-2.1.3: Filter resources by tag.
  - Lab27-2.2: Using tags with CLI.
  - Lab27-3: Create a Resource Group.
  - Lab27-4: Clean up resources.
- Understood the role of tags in classifying, searching, filtering, and managing AWS resources.
- Learned how to use AWS CLI to work with tags and filter resources by tags.
- Learned how to create Resource Groups to group resources by tag conditions.
- Practiced labs related to IAM User, IAM Policy, IAM Role, and Switch Role, including:
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
- Understood how IAM Policies can control user actions based on conditions like region or resource tags.
- Learned how to check access permissions when users interact with EC2 Instances in different regions.
- Understood how resource tags affect allowing or denying EC2 Instance creation according to configured policies.
- Practiced creating restriction policies, IAM limited users, and testing IAM User permission limits through:
  - Lab30-3: Create Restriction Policy.
  - Lab30-4: Create IAM Limited User.
  - Lab30-5: Test IAM User Limits.
  - Lab30-6: Clean up resources.
- Understood how to apply policies to limit user permissions following the least privilege principle.
- Practiced labs related to AWS KMS, S3, CloudTrail, and Athena, including:
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
- Learned how to create KMS Keys to encrypt data on S3.
- Understood the role of CloudTrail in logging API activity and resource access behavior on AWS.
- Learned how to use Amazon Athena to query and analyze logs stored on S3.
- Understood how to test and share encrypted data on S3 through KMS.
- Practiced labs related to IAM Group, IAM User, Admin Role, and Switch Role, including:
  - Lab44-2: Create IAM Group.
  - Lab44-3.1: Create IAM Users.
  - Lab44-3.2: Check permissions.
  - Lab44-4.1: Create Admin IAM Role.
  - Lab44-4.2: Configure Switch Role.
  - Lab44-4.3.1: Limit switch role by IP.
  - Lab44-4.3.2: Limit switch role by Time.
  - Lab44-5: Clean up resources.
- Understood how to limit switch role permissions by IP and time to enhance access control.
- Practiced labs related to access keys and IAM Roles for EC2, including:
  - Lab48-1.1: Create EC2 Instance.
  - Lab48-1.2: Create S3 Bucket.
  - Lab48-2.1: Generate IAM user and access key.
  - Lab48-2.2: Use access key.
  - Lab48-3.1: Create IAM role.
  - Lab48-3.2: Using IAM role.
  - Lab48-4: Clean up resources.
- Understood the difference between using IAM User Access Keys and using IAM Roles for EC2 Instances.
- Recognized the risks of using long-term access keys and the role of IAM Roles in providing temporary, safer permissions for workloads.
- Developed hands-on skills in AWS Security through labs, including:
  - Reading lab requirements.
  - Configuring IAM User, Group, Role, and Policy.
  - Checking access permissions after configuration.
  - Observing results on AWS Console.
  - Documenting errors if any.
  - Cleaning up resources after completing labs to avoid unnecessary costs.
- Acquired the ability to link theoretical knowledge of security, IAM, KMS, CloudTrail, Athena, Security Hub, and tag-based access control with practical labs.
- Completed notes, summarized learning results, and prepared content for the Week 6 report.
