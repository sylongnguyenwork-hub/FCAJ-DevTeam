---
title: "Worklog Week 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Strategic Objectives:

- **Deep Dive into Data Layer & Global Content Acceleration:** Explore comprehensive object storage management solutions combined with global content delivery network acceleration methodologies.
- **Design Backup and Disaster Recovery (DR) Architectures:** Architect and build system recovery models based on Service Level Agreements (SLAs) balanced with two core technical metrics: RTO (Recovery Time Objective) and RPO (Recovery Point Objective).
- **Implement Advanced Storage Features in Practice:** Execute configurations of specialized Amazon S3 features, integrate a Content Delivery Network (Amazon CloudFront), and enable Bucket Versioning to proactively safeguard data against ransomware.

### Weekly Deployment Plan:

| Day | Task Description | Start Date | End Date | Resource / Documentation |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------- | --------------------------------------------- |
| Mon | - Research Module 04 Theory: Architectural foundations of Object Storage and automating data tiering optimization via S3 Lifecycle Management.<br>- Explore Hybrid Storage solutions with AWS Storage Gateway and large-scale physical data migration methods using the AWS Snow Family. | 25/05/2026 | 25/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |
| Tue | - Configure Static Website Hosting on an S3 Bucket to host and deploy source code for a Single Page Application (SPA).<br>- Author an S3 Bucket Policy in JSON format to securely provision Public Read Permissions. | 26/05/2026 | 26/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |
| Wed | - Integrate Amazon CloudFront (CDN) to optimize page loading latency and enhance end-user experience.<br>- Configure S3 Bucket origin cloaking and enforce S3 Block Public Access at the bucket level to tighten infrastructure security boundaries. | 27/05/2026 | 27/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |
| Thu | - Enable Bucket Versioning to establish a security line of defense against ransomware attacks, accidental deletions, or object overwrites.<br>- Configure Cross-Region Replication (CRR) to set up automated, asynchronous data replication to another AWS Region for geographic redundancy. | 28/05/2026 | 28/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |
| Fri | - Deeply analyze 4 Disaster Recovery (DR) strategies on AWS: *Backup & Restore*, *Pilot Light*, *Warm Standby*, and *Multi-Site* to evaluate cost-to-recovery time trade-offs. | 29/05/2026 | 29/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |
| Sat | - Execute Cost Optimization through resource cleanup workflows: Disable and Delete active CloudFront Distributions; Empty and permanently Delete unutilized S3 Buckets to prevent unexpected AWS charges. | 30/05/2026 | 30/05/2026 | AWS First Cloud AI Journey (FCAJ) 2026 Course |

### Key Accomplishments & Deliverables:

| Day | Deployment Domain | Recorded Outcomes and Technical Value |
| --- | ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mon | Data Storage Technology Research | Mastered the structural nature of Amazon S3 as a flat, non-hierarchical peer object storage. Acquired comprehensive knowledge of AWS Storage Gateway deployment types (File, Volume, Tape) to establish hybrid sync between On-Premises environments and the Cloud. |
| Tue | Static Website Deployment | Successfully provisioned an S3 Bucket and enabled Single Page Application (SPA) hosting under a strictly governed public read permission policy. |
| Wed | CloudFront CDN Integration | Mastered the blueprint of high-performance static website architectures; successfully leveraged CloudFront CDN security mechanics to encapsulate and shield the underlying S3 origin from infrastructure exposures. |
| Thu | Advanced Storage Feature Delivery | Configured a multi-version object tracking system (Versioning) and engineered a robust Cross-Region Replication (CRR) workflow for seamless cross-region geographic failover backup. |
| Fri | Disaster Recovery Policy Formulation | Developed an architectural mindset for designing, analyzing, and deploying comprehensive cloud data recovery strategies compliant with cybersecurity baselines and enterprise uptime commitments. |
| Sat | Cost Optimization & Resource Cleanup | Enforced rigorous infrastructure hygiene practices; completely purged all objects, hidden versions inside S3 Buckets, and removed CloudFront Distributions, ensuring zero residual costs on the AWS account. |