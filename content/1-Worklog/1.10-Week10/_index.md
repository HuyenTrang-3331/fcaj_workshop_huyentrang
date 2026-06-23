---
title: "Week 10 Worklog"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Learn and review AWS services supporting cloud application development.
* Reinforce knowledge of web application architecture on AWS.
* Understand the workflow between User, Route 53, CloudFront, WAF, ALB, EC2, S3, and RDS.
* Review network components like VPC, Subnet, Route Table, Internet Gateway, NAT Gateway, and Security Group.
* Practice AWS architecture diagram review, analysis, and editing skills.
* Explore internal system security options like IP Allowlist, HTTPS, Authentication, API Key, and HMAC.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 1 | - Review web application architecture on AWS <br> - Understand the access flow: User → Route 53 → CloudFront/WAF → ALB → EC2 <br> - Note the role of each component in the architecture | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/architecture/ |
| 2 | - Review VPC, Public Subnet, Private Subnet, Route Table, Internet Gateway, and NAT Gateway <br> - Differentiate resources located in Region, VPC, Subnet, and global resources <br> - Note how to place services correctly in architecture diagrams | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/vpc/ |
| 3 | - Understand the role of ALB, CloudFront, WAF, and S3 in web systems <br> - Differentiate the flow CloudFront → S3 and CloudFront/WAF → ALB <br> - Note common errors when drawing AWS architecture diagrams | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/ |
| 4 | - Explore internal dashboard security options <br> - Compare WAF, VPN, IP Allowlist, HTTPS, Authentication, API Key, and HMAC <br> - Note how to choose appropriate security options based on project cost and needs | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/waf/ |
| 5 | - Synthesize Week 10 AWS architecture knowledge <br> - Review and edit architecture diagrams logically <br> - Complete Week 10 report notes <br> - Clean up unused lab resources or materials | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/blogs/architecture/ |

### Week 10 Achievements:

* Better understand how to build basic web application architecture on AWS.
* Know how to determine the main access flow for users into the system.
* Master the common architecture flow:
  * User
  * Route 53
  * CloudFront
  * AWS WAF
  * Application Load Balancer
  * EC2 Backend
  * RDS Database
* Understand that CloudFront can be used to deliver static content from S3.
* Know that WAF should not be drawn as an independent intermediate network node, but is usually attached to CloudFront or ALB.
* Better understand the role of network components in AWS, including:
  * VPC
  * Public Subnet
  * Private Subnet
  * Route Table
  * Internet Gateway
  * NAT Gateway
  * Security Group
* Can differentiate resources located in VPC and resources not located in VPC.
* Understand that NAT Gateway is mainly used for outbound traffic from private subnet to the Internet.
* Know how to analyze architecture diagrams and detect some common errors, for example:
  * Drawing IAM as a data processing flow
  * Placing WAF in the wrong position
  * Confusing Internet Gateway and Application Load Balancer
  * Missing Security Group or Route Table
  * Not clearly showing public subnet and private subnet
* Understand internal dashboard security options.
* Know that if WAF is not used, the system still needs a replacement security layer.
* Master some suitable security options for internal systems, including:
  * VPN
  * IP Allowlist
  * HTTPS
  * Authentication
  * API Key
  * HMAC
* Know how to balance between security, cost, and complexity when designing architecture.
* Practice AWS architecture diagram review skills concisely and to the point.
