---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


### Week 10 Objectives:

- Build a database sufficient for storing project data.

### Tasks to be deployed this week:

| Day | Task | Start Date | Completion Date | Resource / Documentation |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| Mon | - Set up the Amazon DynamoDB NoSQL database and design the table structures (Tables, Partition Key, Sort Key) optimized for storing extracted invoice info, document categories, and payment data. | June 22, 2026 | June 22, 2026   | |
| Tue | - Configure the 'Event: ObjectCreated' feature on the Amazon S3 Upload bucket so that whenever a new document is uploaded, the system automatically generates an event and pushes this notification into the Amazon SQS message queue. | June 23, 2026 | June 23, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Initialize the AWS Lambda AI-Worker function responsible for core logic processing, and configure the Trigger mechanism to enable this Lambda function to automatically listen to and consume messages pushed from Amazon SQS. | June 24, 2026 | June 24, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Develop the source code for Lambda AI-Worker to integrate the Amazon Textract AI service, and configure the Analyze Queries feature to extract customized data fields based on predefined business queries from uploaded documents. | June 25, 2026 | June 25, 2026   | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - Add post-processing logic to the Lambda AI-Worker function to standardize all extracted text data into a JSON structure, then execute data writing operations (Store JSON Data) into Amazon DynamoDB. | June 26, 2026 | June 26, 2026   | <https://cloudjourney.awsstudygroup.com/> |

### Week 10 Key Results:

The intelligent IDP processing workflow is now fully automated and self-contained. The system is capable of automatically extracting highly accurate information from unstructured documents using Textract and synchronously storing it in DynamoDB.