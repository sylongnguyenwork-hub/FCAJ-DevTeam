---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Week 9 Objectives:

- Hold a team meeting to allocate tasks and kick off the project.

### Tasks to be deployed this week:

| Day | Task | Start Date | Completion Date | Resource / Documentation |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| Mon | - Hold an online meeting to assign tasks and responsibilities for the FCAJ project. | June 15, 2026 | June 15, 2026   | |
| Tue | - Initialize the AWS Cloud environment and configure shared services in the Shared Services & Security Zone, including setting up AWS IAM policies, creating encryption keys with AWS KMS, and configuring cost alerts via AWS Budgets. | June 16, 2026 | June 16, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Create and configure two main Amazon S3 storage buckets: Amazon S3 Frontend to host the static user interface source code, and Amazon S3 Upload to act as the receiving repository for incoming documents. | June 17, 2026 | June 17, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Set up Amazon API Gateway to serve as the entry point for HTTPS requests, and configure the AWS WAF web application firewall in front of the API Gateway to prevent basic vulnerability exploitation attacks. | June 18, 2026 | June 18, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - Initialize the Amazon Cognito identity management service, configure the User Pool, and establish a JWT (Token Validation) authentication mechanism integrated directly into Amazon API Gateway routes to protect system resources. | June 19, 2026 | June 19, 2026   | <https://cloudjourney.awsstudygroup.com/> |

### Week 9 Key Results:

Successfully completed the baseline cloud infrastructure setup with foundational security, established the user authentication mechanism using Cognito, and smoothly operated the document upload workflow to the S3 Upload bucket via a secure Presigned URL mechanism.