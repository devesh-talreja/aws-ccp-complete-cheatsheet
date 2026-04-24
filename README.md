# ⚡ AWS Certified Cloud Practitioner (CLF-C02) Complete Cheat Sheet & Exam Guide

[![AWS](https://img.shields.io/badge/AWS-CCP--CLF--C02-orange?style=flat&logo=amazonaws)](https://aws.amazon.com/certification/certified-cloud-practitioner/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Sections](https://img.shields.io/badge/Sections-26-green)]()

> **By Devesh Talreja**

---

I built this comprehensive revision guide while preparing for my **AWS Certified Cloud Practitioner (CLF-C02)** exam with AI helping me articulate and consolidate concepts as I studied. These modular notes are designed to simplify cloud concepts and focus strictly on what you need to know to pass.

**Why use these notes?**
- **Foundational Focus:** Clear breakdowns of core services, billing, and the shared responsibility model.
- **Comparison Driven:** Side-by-side comparisons to help you distinguish similar services—a major exam favorite.
- **High Signal:** No fluff—just high-yield concepts, exam traps, and mnemonics for rapid recall.
- **Battle-Tested:** These are the exact notes I used to revise and pass my own exam.

Use these as your final revision companion to bridge the gap between courses and your exam!

---
all sections will be added before 30 april
| #  | Section                                                                         | What's Inside                                                                                     |
| -- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1  | [COMPUTE SERVICES](01-compute-services.md)                                | EC2, Lambda, Elastic Beanstalk, Lightsail, ECS, EKS                                               |
| 2  | [STORAGE SERVICES](02-storage-services.md)                                | S3 (tiers), EBS, EFS, Storage Gateway                                                             |
| 3  | [DATABASE SERVICES](03-database-services.md)                              | RDS, Aurora, DynamoDB, Redshift, ElastiCache                                                      |
| 4  | [NETWORKING &amp; CONTENT DELIVERY](04-networking-content-delivery.md)    | VPC, CloudFront, Route 53, Direct Connect, VPN, API Gateway                                       |
| 5  | [SECURITY, IDENTITY &amp; COMPLIANCE](05-security-identity-compliance.md) | IAM, Cognito, Artifact, GuardDuty, WAF, Shield, KMS                                               |
| 6  | [MANAGEMENT &amp; GOVERNANCE](06-management-governance.md)                | CloudWatch, CloudTrail, Config, Trusted Advisor, Control Tower                                    |
| 7  | [APPLICATION INTEGRATION](07-application-integration.md)                  | SQS, SNS, EventBridge, Step Functions                                                             |
| 8  | [ANALYTICS](08-analytics.md)                                              | Athena, EMR, Kinesis, Glue, QuickSight                                                            |
| 9  | [MACHINE LEARNING](09-machine-learning.md)                                | SageMaker, Rekognition, Comprehend, Lex, Polly, Personalize                                       |
| 10 | [MIGRATION &amp; TRANSFER](10-migration-transfer.md)                      | Snow Family, DMS, Migration Hub, DataSync                                                         |
| 11 | [COST MANAGEMENT](11-cost-management.md)                                  | Cost Explorer, Budgets, Pricing Calculator, Savings Plans                                         |
| 12 | [OTHER IMPORTANT SERVICES](12-other-important-services.md)                | CloudFormation, ELB, Auto Scaling, Outposts, WorkSpaces                                           |
| 13 | [KEY COMPARISONS TO AVOID CONFUSION](13-key-comparisons.md)               | EC2 vs Lambda, S3 vs EBS vs EFS, RDS vs DynamoDB, SNS vs SQS                                      |
| 14 | [WELL-ARCHITECTED FRAMEWORK](14-well-architected-framework.md)            | The 6 Pillars: Operational Excellence, Security, Reliability, Performance, Cost, Sustainability   |
| 15 | [CLOUD CONCEPTS (FUNDAMENTAL)](15-cloud-concepts.md)                      | Six advantages of cloud computing, deployment models, IaaS vs PaaS vs SaaS, Shared Responsibility |
| 16 | [SUPPORT PLANS](16-support-plans.md)                                      | Basic, Developer, Business, Enterprise On-Ramp, Enterprise differences                            |
| 17 | [REGIONAL SERVICES VS GLOBAL SERVICES](17-regional-vs-global.md)          | IAM, Route 53, CloudFront vs EC2, RDS, VPC                                                        |
| 18 | [CATEGORIZED SUMMARY](18-categorized-summary.md)                          | Quick list of services mapped to their core categories                                            |
| 19 | [EXAM STRATEGY TIPS](19-exam-strategy-tips.md)                            | Keywords to watch for ("cost-effective", "real-time"), common traps                               |
| 20 | [PRICING QUICK REFERENCE](20-pricing-quick-reference.md)                  | Free tier limits, Pay-As-You-Go models, Data Transfer IN vs OUT costs                             |
| 21 | [ACRONYM MASTER LIST](21-acronym-master-list.md)                          | Unlocking the alphabet soup: AMI, ARN, CIDR, IOPS, SG, etc.                                       |
| 22 | [REAL-WORLD USE CASE SCENARIOS](22-real-world-scenarios.md)               | Architecture mapping for E-Commerce, Mobile Backend, Data Analytics                               |
| 23 | [FINAL EXAM DAY TIPS](23-final-exam-day-tips.md)                          | What to do before the exam, during the exam, and green/red flags                                  |
| 24 | [QUICK MEMORIZATION TECHNIQUES](24-quick-memorization.md)                 | Memory Palaces, Rhymes, and Mnemonics (e.g. "My Poor Older Sister...")                            |
| 25 | [LAST-MINUTE POWER FACTS](25-last-minute-power-facts.md)                  | 20 rapid-fire facts that show up constantly on the CCP exam                                       |
| 26 | [CONFIDENCE BUILDER](26-confidence-builder.md)                            | Final checklist to verify you are ready for the test                                              |

---

### Suggested Preparation Strategy

Since the Cloud Practitioner exam is primarily theoretical and tests your foundational knowledge of cloud concepts, your study approach should be tailored differently than associate-level exams:

1. **Coursework & Concept Mastery:** Start with a video course (like Stephane Maarek's CCP course) to get a broad understanding of all AWS services. The focus here is to understand *what* each service does rather than *how* to build complex architectures with them. Hands-on labs are helpful but not strictly necessary for this exam.
2. **Revision & Active Memorization:** This is where you should spend the bulk of your time. Use this cheatsheet to drill down into the differences between similar services (Section 13) and memorize key acronyms and pricing concepts. Flashcards can be incredibly useful here.
3. **Knowledge Validation:** While not entirely non-negotiable, taking a few practice exams (like Tutorial Dojo) is highly recommended. They will help you get familiar with the wording of AWS questions and identify any weak spots in your theoretical knowledge before exam day.

### Navigation

Every section file has **← prev | README | next →** links at the bottom so you can move through sections without coming back to this page.

Feel free to **fork** or **⭐ star** this repo to keep it bookmarked so you can easily come back for your revision rounds!

---

## ⚠️ Disclaimer

These are personal study notes, not official AWS documentation. AWS services evolve constantly — always verify with the [official AWS docs](https://docs.aws.amazon.com/) for the latest details. Content is intentionally simplified in places to aid memorization and is optimized for exam preparation, not production architecture decisions.

---

## 🔗 Official AWS Resources

| Resource                       | Link                                                                                            |
| ------------------------------ | ----------------------------------------------------------------------------------------------- |
| CLF-C02 Exam Guide             | [Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) |
| AWS Official Documentation     | [docs.aws.amazon.com](https://docs.aws.amazon.com/)                                                |
| AWS Well-Architected Framework | [Well-Architected](https://aws.amazon.com/architecture/well-architected/)                          |
| AWS Architecture Center        | [Architecture Center](https://aws.amazon.com/architecture/)                                        |
| AWS Free Tier                  | [aws.amazon.com/free](https://aws.amazon.com/free/)                                                |
| AWS Skill Builder (free labs)  | [skillbuilder.aws](https://skillbuilder.aws/)                                                      |
| Stephane Maarek – CCP Course  | [Udemy Course](https://www.udemy.com/course/aws-certified-cloud-practitioner-new/)                 |

---

## 🤝 Contributing

This cheatsheet is a living document! If you spot a typo, find an outdated fact, or have a brilliant mnemonic to add, contributions are highly encouraged.

To suggest improvements and make learning easier for yourself and others:

1. Fork the repo and create your feature branch.
2. Commit your changes and submit a pull request.

You're also welcome to simply clone the repository to keep a local copy for your own offline study sessions.

## 📄 License

This repository is available under the [MIT License](LICENSE). Feel free to use and distribute these notes to help with your own AWS journey!

---

**Happy Learning and best of luck conquering the AWS CCP exam! 🚀 Gambare! ☁️**
*— Devesh Talreja*
