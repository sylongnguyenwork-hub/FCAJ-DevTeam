---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives:

- Design the frontend and dashboard to ensure stable and reliable operations.

### Tasks to be deployed this week:

| Day | Task | Start Date | Completion Date | Resource / Documentation |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| Mon | - Deploy the first two API functions in the Dashboard APIs Layer: 'AWS Lambda API-Get-Invoices' (to fetch the invoice list) and 'AWS Lambda API-Get-Stats' (to retrieve general statistical data) from the DynamoDB database. | June 29, 2026 | June 29, 2026   | |
| Tue | - Complete the remaining two API functions in the layer: 'AWS Lambda API-Get-Category' (to fetch document classification info) and 'AWS Lambda API-Get-Payment' (to query detailed payment data). | June 30, 2026 | June 30, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Map HTTP GET Requests on Amazon API Gateway to the cluster of 4 AWS Lambda functions within the Dashboard APIs Layer, configure data mapping templates, and enable CORS for the APIs. | July 1, 2026 | July 1, 2026    | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Review and reinforce system security, apply the Principle of Least Privilege to IAM Roles, and configure advanced blocking rules on AWS WAF to safeguard the Dashboard API layer. | July 2, 2026 | July 2, 2026    | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - Connect the Frontend source code to the API Gateway layer to dynamically display real-time data (invoice list, statistical charts, payment statuses) from the database onto the user interface. | July 3, 2026 | July 3, 2026    | <https://cloudjourney.awsstudygroup.com/> |

### Week 11 Key Results:

The Dashboard APIs system is operating stably, the Frontend interface visualizes real-time data intuitively, and the entire Serverless architecture is strictly secured and ready for deployment handover.