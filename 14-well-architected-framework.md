## WELL-ARCHITECTED FRAMEWORK (EXAM FAVORITE!)

The AWS Well-Architected Framework helps cloud architects build secure, high-performing, resilient, and efficient infrastructure for their applications and workloads. It provides a consistent approach to evaluate architectures and implement designs that will scale over time.

### The Six Pillars Detailed Breakdown

| Pillar | Definition | Key Principles / Best Practices | AWS Services Used |
|---|---|---|---|
| **1. Operational Excellence** | The ability to run and monitor systems to deliver business value and continually improve supporting processes and procedures. | Perform operations as code, make frequent/small/reversible changes, refine operations procedures frequently, anticipate failure, learn from operational failures. | CloudFormation, Config, CloudTrail, CloudWatch, X-Ray |
| **2. Security** | The ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies. | Implement a strong identity foundation, enable traceability, apply security at all layers, automate security best practices, protect data in transit and at rest, keep people away from data. | IAM, Cognito, Shield, WAF, KMS, GuardDuty, Macie |
| **3. Reliability** | The ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions. | Automatically recover from failure, test recovery procedures, scale horizontally to increase aggregate workload availability, stop guessing capacity, manage change in automation. | Auto Scaling, Multi-AZ deployments, Route 53, S3 cross-region replication |
| **4. Performance Efficiency** | The ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve. | Democratize advanced technologies, go global in minutes, use serverless architectures, experiment more often, consider mechanical sympathy. | CloudFront, ElastiCache, Auto Scaling, Snowball |
| **5. Cost Optimization** | The ability to run systems to deliver business value at the lowest price point. | Implement cloud financial management, adopt a consumption model, measure overall efficiency, stop spending money on heavy lifting (data center ops), analyze and attribute expenditure. | Cost Explorer, Budgets, Compute Optimizer, Trusted Advisor |
| **6. Sustainability** | The ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload. | Understand your impact, establish sustainability goals, maximize utilization, anticipate and adopt new/more efficient hardware and software offerings, use managed services. | EC2 Auto Scaling, Serverless services (Lambda, Fargate), Cost Explorer |

**🧠 Memory Trick:** "OSRPCS" = "Oh So Really Pretty Cool Stuff"
- **O**perational Excellence
- **S**ecurity
- **R**eliability
- **P**erformance Efficiency
- **C**ost Optimization
- **S**ustainability

### Additional Framework Concepts

- **AWS Well-Architected Tool:** A free service in the AWS Console that helps you review the state of your workloads and compares them to the latest AWS architectural best practices.
- **Design Principles:** General design principles include stopping guessing your capacity needs, testing systems at production scale, automating to make architectural experimentation easier, allowing for evolutionary architectures, driving architectures using data, and improving through game days.

---

[< Key Comparisons](13-key-comparisons.md) | [Back to README](README.md) | [Cloud Concepts >](15-cloud-concepts.md)
