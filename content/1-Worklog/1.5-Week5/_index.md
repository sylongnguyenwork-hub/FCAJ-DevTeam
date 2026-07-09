---
title: "Worklog Week 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Objectives for Week 5:

- Handle advanced scenarios regarding cloud network scaling by building a central router, AWS Transit Gateway.
- Master the core characteristics of EC2 virtual servers, including Instance categorization, storage mechanisms, auto-scaling systems, and shared network files.
- Implement solutions for data security, automated backups, and Disaster Recovery using AWS Backup and Amazon SNS.

### Tasks to Implement This Week:

| Day | Tasks                                                                                                                                                                                                                            | Start Date | End Date   | Source Materials                          |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| Mon | - Deep dive into Module 03 on EC2: CPU chip classifications (Intel, AMD, ARM/Graviton) and cost optimization methods <br> - Differentiate the storage mechanisms between EBS Volume and Instance Store (ephemeral storage)       | 18/05/2026 | 18/05/2026 | First Cloud AI Journey Course             |
| Tue | - Learn about EC2 User Data & Metadata features, Auto Scaling & Load Balancing mechanisms <br> - Research shared network storage solutions (Amazon EFS, FSx) and the system migration service AWS MGN                            | 19/05/2026 | 19/05/2026 | First Cloud AI Journey Course             |
| Wed | - Use CloudFormation to quickly provision an infrastructure of 4 VPCs and 4 EC2 servers <br> - Initialize the central router Transit Gateway to solve the VPC Peering scaling issue       | 20/05/2026 | 20/05/2026 | First Cloud AI Journey Course             |
| Thu | - Create Transit Gateway Attachments to link 4 VPCs to the central network <br> - Configure the TGW route table (Associations, Propagations) and update the Route Table of each VPC to route traffic through the TGW             | 21/05/2026 | 21/05/2026 | First Cloud AI Journey Course             |
| Fri | - Build a Backup Plan defining backup rules and initialize a KMS-encrypted Backup Vault <br> - Configure Amazon SNS to create a Topic for sending backup alerts to the admin email                 | 22/05/2026 | 22/05/2026 | First Cloud AI Journey Course             |
| Sat | - Test the network via Reachability Analyzer and perform cross-SSH testing between VPCs. Execute a Restore Test to recover an EC2 server <br> - Execute the cleanup process for all resources (Backup, SNS, TGW, CloudFormation) | 23/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Achievements for Week 5:

| Day | Tasks                                                   | Achievements                                                                                                                                                                                                                                   |
| --- | ------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mon | Research EC2 virtual server architecture                | Deeply understood CPU selection strategies (especially the Graviton chip series which saves 40% in costs). Differentiated the 99.999% availability of EBS storage networks compared to the read/write speed of physical Instance Store drives. |
| Tue | Scaling mechanisms and network storage                  | Mastered how to automatically run scripts using User Data and fetch internal information via Metadata. Understood the NFSv4 standard file sharing mechanism (EFS) and data deduplication in SMB (FSx).                                         |
| Wed | Initialize centralized network infrastructure in Lab 20 | Successfully built the pre-configured CloudFormation Stack for 4 independent VPCs. Clearly understood the advantages of the Hub-and-Spoke model (Transit Gateway) over the Mesh connection of VPC Peering.                                     |
| Thu | Configure AWS Transit Gateway routing                   | Successfully linked virtual networks to the central gateway via TGW Attachments, performed automated route propagation, and ensured seamless routing from VPCs to the TGW.                                                                     |
| Fri | Deploy automated AWS Backup solution                    | Successfully set up a secure system backup plan into the Backup-LAB-VAULT, while successfully activating the automated incident alerting feature via Email using Amazon SNS.                                                                   |
| Sat | Test the system and optimize resources                  | Confirmed seamless Private network connections between VPC 1, VPC 2, VPC 3, and VPC 4. Successfully restored servers from a Recovery Point. Completely cleaned up all practice resources to avoid incurring costs.                             |

