---
title: "Worklog Week 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

- Build a Hybrid DNS solution using Route 53 Resolver to establish a synchronous and consistent name resolution mechanism between the AWS cloud environment and the traditional On-Premises infrastructure.

- Initialize and configure VPC Peering connections, enabling virtual networks to establish secure and highly isolated internal communication channels without routing through the public Internet.

- Apply Zero Trust security principles and strict resource governance to optimize infrastructure operational costs.

### Tasks to be Deployed This Week:

| Day | Task | Start Date | End Date | Resource / Documentation |
| --- | --- | --- | --- | --- |
| 2 | - Conduct foundational theoretical research on Hybrid DNS resolution mechanisms between cloud and physical infrastructures. Deeply analyze Route 53 Resolver service, clarifying its operating principles as well as methods for configuring Inbound and Outbound Endpoints. | 11/05/2026 | 11/05/2026 | First Cloud AI Journey Course |
| 3 | - Utilize CloudFormation to automate infrastructure provisioning and deploy AWS Managed Microsoft AD to simulate an On-Premises DNS Server environment. | 12/05/2026 | 12/05/2026 | First Cloud AI Journey Course |
| 4 | - Conduct assessments and design an IP address planning strategy for two distinct network partitions (My VPC and HG VPC), ensuring network ranges are isolated without any CIDR overlap. | 13/05/2026 | 13/05/2026 | First Cloud AI Journey Course |
| 5 | - Apply access control rules via Network ACLs to tighten security boundaries at the subnet layer. | 14/05/2026 | 14/05/2026 | First Cloud AI Journey Course |
| 6 | - Update and append routing records in Route Tables to accurately direct traffic through the established Peering Connection. | 15/05/2026 | 15/05/2026 | First Cloud AI Journey Course |
| 7 | - Configure detailed inbound rules within Security Groups and implement IAM Policies to enforce least privilege access control based on the Zero Trust security model. | 16/05/2026 | 16/05/2026 | First Cloud AI Journey Course |

### Week 4 Achievements:

| Day | Task | Key Achievements |
| --- | --- | --- |
| 2| Hybrid DNS Theoretical Research | Mastered the operational principles of the Route 53 Resolver service, fully grasping the mechanics of two-way DNS query forwarding between AWS and the internal On-Premises network. |
| 3 | Lab 10 Deployment & System Validation | Successfully initialized data exchange endpoints (Inbound/Outbound Endpoints) along with dedicated forwarding rules for the specific domain namespace. |
| 4 | VPC Peering Infrastructure Planning | Completed the establishment of stable network partitioning, ensuring clean and well-structured network ranges to facilitate dedicated internal routing. |
| 5 | Peer-to-Peer Connection Establishment | Successfully established and transitioned the Peering Connection status to Active. Enhanced perimeter defense by fine-tuning Network ACL rules to restrict access exclusively to designated IP ranges. |
| 6 | Inter-Network Routing & Cross-Peer DNS | Completed bi-directional route table configurations, enabling EC2 instances to communicate directly. Successfully enabled Cross-Peer DNS, significantly optimizing resolution speed and response times for private IP addresses across servers. |
| 7 | Security Governance & Budget Optimization | Enhanced troubleshooting mindset within complex networking environments. Strictly adhered to cost-optimization procedures by terminating all EC2 instances, releasing Peering Connections, removing Route 53 Endpoints, and tearing down deployed CloudFormation Stacks. |