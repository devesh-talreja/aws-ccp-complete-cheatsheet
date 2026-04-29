## EXAM STRATEGY TIPS

### 1. Question Keywords to Watch For:

**"MOST cost-effective"** → Look for:
- Spot Instances over On-Demand
- S3 Glacier over S3 Standard
- Reserved Instances for steady workloads
- Serverless options (Lambda, Fargate)

**"High availability"** → Look for:
- Multi-AZ deployments
- Auto Scaling
- Load Balancers
- Multiple regions

**"Disaster Recovery"** → Look for:
- Multi-region replication
- Automated backups
- Route 53 failover routing
- CloudFormation for infrastructure recreation

**"Real-time"** → Look for:
- Kinesis (not S3/Glacier)
- DynamoDB (not RDS)
- Lambda (not EC2 batch processing)

**"Serverless"** → Look for:
- Lambda, Fargate, Aurora Serverless
- DynamoDB, S3, Athena
- API Gateway, EventBridge

**"Hybrid cloud"** → Look for:
- Storage Gateway
- Direct Connect
- Outposts
- VPN

**"Compliance/Audit"** → Look for:
- CloudTrail (who did what)
- Config (configuration changes)
- AWS Artifact (compliance reports)

**"Secure"** → Look for:
- Encryption at rest (KMS)
- Encryption in transit (TLS/SSL)
- IAM roles (not access keys)
- VPC private subnets
- Security groups (not wide open)

### 2. Common Traps:

❌ **"We need to store logs"** → NOT CloudTrail (that's for API auditing), use CloudWatch Logs

❌ **"Fast database for web app"** → NOT Redshift (that's for analytics), use DynamoDB or RDS

❌ **"Share files between EC2 instances"** → NOT EBS (that's single-instance), use EFS or S3

❌ **"Cheapest storage for rarely accessed data"** → NOT S3 Standard, use S3 Glacier Deep Archive

❌ **"Need SQL database in AWS"** → NOT DynamoDB, use RDS

❌ **"Monitor who made changes to security groups"** → NOT CloudWatch, use CloudTrail

### 3. Process of Elimination Strategy:

1. **Eliminate obviously wrong answers** (e.g., DynamoDB for SQL queries)
2. **Look for keywords** (cost-effective, high availability, real-time)
3. **Consider AWS best practices** (multi-AZ, least privilege, encryption)
4. **Choose the most managed/AWS-native option** when in doubt

### 4. Scenario-Based Quick Reference:

**Scenario:** Website with unpredictable traffic
- **Solution:** Auto Scaling, ALB, Lambda, CloudFront, S3 for static content

**Scenario:** Migrate 200TB of data to AWS
- **Solution:** Snowball (not internet upload, too slow)

**Scenario:** Run code when file uploaded to S3
- **Solution:** Lambda with S3 event trigger

**Scenario:** Need to query logs stored in S3
- **Solution:** Athena (not Redshift unless large-scale analytics)

**Scenario:** Application needs temporary AWS credentials
- **Solution:** IAM Role (not IAM User with access keys)

**Scenario:** Protect web application from DDoS
- **Solution:** Shield, WAF, CloudFront

**Scenario:** Monitor EC2 CPU and create alarm
- **Solution:** CloudWatch (not CloudTrail)

**Scenario:** Store database passwords securely
- **Solution:** Secrets Manager or Systems Manager Parameter Store

**Scenario:** Connect on-premises to AWS securely
- **Solution:** VPN (quick/cheap) or Direct Connect (high bandwidth/consistent)

**Scenario:** Decouple application components
- **Solution:** SQS (queue) or SNS (pub/sub)

---

[< Categorized Summary](18-categorized-summary.md) | [Back to README](README.md) | [Pricing Quick Reference >](20-pricing-quick-reference.md)
