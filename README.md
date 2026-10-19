# AWS Certification Roadmap

Knowmadics architecture and technical ownership | Revised October 19, 2026

**Objective:** Build the AWS architecture and operational skills needed to take broader technical ownership of the 360 Aware platform. **Starting point:** Some hands-on AWS experience and no AWS certifications.

Prioritize Solutions Architect Associate and CloudOps Engineer Associate, apply the learning to a representative 360 Aware environment, and build toward Solutions Architect Professional. Study networking and security throughout. The Advanced Networking exam is an optional, time-sensitive branch.

### First certification: Solutions Architect Associate

**Focus:** Secure, resilient, efficient, and cost-aware AWS designs; service selection; networking; storage; and recovery. This is the architectural foundation for understanding the platform as a whole. [AWS Solutions Architect Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/).

**Knowmadics application:** Map the web front end (WFE), data ingestion server (DIS), media server (MED), SQL Server, Redis, and authentication services. Explain their dependencies, traffic paths, failure modes, and hosting tradeoffs.

**Training:** Start with the AWS Solutions Architect learning plan and exam preparation. Use *Architecting on AWS* where access and budget permit. Include targeted VPC, DNS, load-balancing, Windows workload, and storage labs. [AWS course catalog](https://aws.amazon.com/training/classroom/).

**Planning allowance:** 10-14 weeks at 5 hours per week, including labs and practice assessments. **Exam fee:** $150 USD. **Deliverable:** An architecture diagram and a short review of resilience, security, and cost improvements.

### Second certification: CloudOps Engineer Associate

**Focus:** Deploying and operating AWS workloads, monitoring and troubleshooting, automation, backup and recovery, security controls, and cost/performance management. [AWS CloudOps Engineer Associate](https://aws.amazon.com/certification/certified-cloudops-engineer-associate/).

**Knowmadics application:** Diagnose problems across load balancers, Windows services, application logs, and database dependencies. Develop operating procedures that support dependable releases and recovery.

**Training:** Use the CloudOps exam preparation plan and relevant labs; consider *Cloud Operations on AWS*. Practice monitoring, controlled failure recovery, and repeatable environment configuration.

**Planning allowance:** 10-14 weeks at 5 hours per week. **Exam fee:** $150 USD. **Deliverable:** Monitoring and alerting, a troubleshooting runbook, and a demonstrated restore/recovery procedure.

The combined target is approximately six months. These are planning estimates, not AWS course durations or guarantees of exam readiness. Reassess after the initial diagnostic and before booking each exam. At 3 hours per week, the same 100-140 study hours would take roughly 8-11 months.

## Networking and later certifications

### Advanced Networking Specialty: learn early, assess the exam separately

The exam retires on **December 31, 2026**. A certification earned before retirement remains active for three years. Networking training continues on AWS Skill Builder; passing the exam is required to earn the credential. **Exam fee:** $300 USD. [AWS networking retirement notice](https://aws.amazon.com/certification/certified-advanced-networking-specialty/).

AWS has not provided a specific reason in its networking retirement notice or named a successor exam. Its earlier strategy of reducing specialty certifications provides context, but does not establish the reason for this retirement. [AWS retirement strategy in 2024](https://aws.amazon.com/blogs/training-and-certification/aws-certification-retirements-and-launches/).

Study DNS, routing, application/network load balancers, security groups, device ingestion, and media traffic early. These topics map directly to BUILD. The specialty exam extends into advanced cloud/hybrid networking; AWS recommends five years of networking experience, including two years in cloud/hybrid networking.

**Decision in the first study week:** Review the exam guide and take an official practice assessment. Accelerate the exam only if the remaining gaps are manageable and the credential supports a defined Knowmadics responsibility. Otherwise, keep the associate sequence and continue relevant networking labs.

**If pursuing it:** Target a first attempt in early December. AWS requires 14 calendar days after a failed attempt before a retake. Moving networking first will shift the associate schedule and add exam cost. [AWS retake policy](https://aws.amazon.com/certification/policies/after-testing/).

### Long-term destination: Solutions Architect Professional

Develop deeper skills in complex architecture, security, cost, performance, and modernization. Work toward this after the associates and substantial design responsibility. AWS recommends at least two years of AWS design and implementation experience. **Exam fee:** $300 USD. [AWS Solutions Architect Professional](https://aws.amazon.com/certification/certified-solutions-architect-professional/).

Deliver a reviewed architecture improvement proposal with tradeoffs, migration steps, recovery objectives, and operating costs. Set the exam date after assessing experience and readiness. AWS is transitioning this exam to SAP-C03; use preparation aligned to the version available when studying.

| Additional option | When it becomes useful | Exam fee |
| --- | --- | --- |
| DevOps Engineer Professional | Prioritize if release automation and infrastructure delivery become major responsibilities. Apply CI/CD, infrastructure as code, deployment validation, and rollback to the existing build/updater workflow. | $300 |
| Security Specialty | Move up if owning AWS security architecture or customer security reviews. Focus on IAM, network protection, secrets, encryption, logging, and incident response. | $300 |
| Cloud Practitioner | Use introductory modules to fill gaps. Skip the exam in this plan because the associates are the first credential targets. | $100 if taken |
| AI Practitioner | Defer until a defined AWS AI project makes the training relevant to delivery responsibilities. | $100 if taken |

Additional learning paths: [AWS DevOps Engineer Professional](https://aws.amazon.com/certification/certified-devops-engineer-professional/); [AWS Security Specialty](https://aws.amazon.com/certification/certified-security-specialty/). All exam fees are USD list prices before tax and discounts. [AWS exam pricing](https://aws.amazon.com/certification/policies/before-testing/).

## Study schedule, practical work, and budget

**Weekly commitment:** Request five protected study hours: approximately three hours of coursework/review and two hours of hands-on work. Use the proposed **devops.kmionaws.com** test environment for representative labs, with a defined spending limit and nonproduction data.

| Period | Learning and measurable result |
| --- | --- |
| Months 1-3 | Solutions Architect Associate preparation. Map WFE/DIS/MED dependencies and public/private traffic paths. Build a small representative deployment and document availability, storage, recovery, and cost tradeoffs. Take the exam when practice and lab results support readiness. |
| Months 4-6 | CloudOps Associate preparation. Add monitoring and alerting; investigate a controlled service or connectivity failure; demonstrate a backup restore and record recovery time. Complete a troubleshooting runbook and assess exam readiness. |
| After month 6 | Review the two practical deliverables with the technical lead. Take ownership of an agreed architecture improvement and assess the next certification against that responsibility. |

Use the outstanding DNS, public-listener, device-ingestion, and media-path questions in the LAB network inventory as investigation exercises. Evaluate AWS hosting and managed-service options against the existing SQL Server and Windows service requirements. Keep proposed designs distinct from verified deployed configuration.

### Initial six-month budget

| Item | Budget |
| --- | --- |
| Solutions Architect Associate exam | $150 |
| CloudOps Associate exam | $150 |
| Skill Builder monthly subscription (optional): 6 x $29 | $174 |
| Planned total before tax and lab usage | $474 ($300 with no subscription) |

AWS offers a 50% discount on the next certification exam after earning a certification. Passing Solutions Architect first and applying that benefit to CloudOps would reduce the planned total to **$399**. Confirm the benefit before booking. Retakes, optional exams, live classroom courses, taxes, and AWS lab infrastructure charges are excluded. [AWS Solutions Architect Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/); [AWS exam pricing](https://aws.amazon.com/certification/policies/before-testing/).

**Training access:** Free Skill Builder resources provide a starting point; they do not include every training experience. Monthly access is $29. Annual access is $449 and adds Digital Classroom content. A team subscription is $449 per seat per year, with a five-seat minimum. Use existing company access if available; otherwise begin monthly unless Digital Classroom content is specifically needed. [AWS Skill Builder](https://aws.amazon.com/training/digital/); [AWS training FAQs](https://aws.amazon.com/training/faqs/).

### BUILD references for the practical work

Paths below are relative to C:\V2\BUILD. These references connect the training to current platform work.

**Infrastructure:** DEV_OPS/AWSDevOps/OrchestrateVPC.ps1

**Network gaps:** lab-360awareqa-network-endpoints.md

**Build and deployment:** DEV_OPS/360AwareBuild/README.md; DEV_OPS/360AwareUpdater/docs/readme.md

**Application and identity:** V2.5_Backend/README.md; V2.5_Backend/docs/authentication-architecture.md

**Database operations:** V2_Database/docs/performance-tuning.md
