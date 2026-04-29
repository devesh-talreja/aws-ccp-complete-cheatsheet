## REAL-WORLD USE CASE SCENARIOS

### E-Commerce Website
**Architecture:**
- CloudFront (CDN for fast loading)
- S3 (static content: images, CSS, JS)
- ALB (distribute traffic)
- EC2 with Auto Scaling (web servers)
- RDS Multi-AZ (product database)
- ElastiCache (session storage, frequently accessed products)
- SQS (order processing queue)
- SNS (order notifications)
- CloudWatch (monitoring)
- Route 53 (DNS)

### Mobile App Backend
**Architecture:**
- API Gateway (RESTful API)
- Lambda (serverless backend logic)
- DynamoDB (user data, fast NoSQL)
- Cognito (user authentication)
- S3 (user-uploaded photos/videos)
- CloudFront (content delivery)
- SNS (push notifications)

### Data Analytics Platform
**Architecture:**
- Kinesis (real-time data ingestion)
- S3 (data lake)
- Glue (ETL jobs)
- Athena (query S3 data)
- Redshift (data warehouse)
- QuickSight (visualization dashboards)
- EMR (big data processing)

### Disaster Recovery Setup
**Architecture:**
- Primary region: Full production
- Secondary region: AMIs, snapshots ready
- Route 53 failover routing
- CloudFormation templates (infrastructure as code)
- S3 cross-region replication
- RDS automated backups to secondary region

### Video Streaming Platform
**Architecture:**
- S3 (video storage)
- CloudFront (content delivery worldwide)
- Elastic Transcoder/MediaConvert (video format conversion)
- Lambda (trigger transcoding on upload)
- DynamoDB (user viewing history)
- ElastiCache (popular content caching)

### Corporate IT Infrastructure
**Architecture:**
- WorkSpaces (virtual desktops for employees)
- Directory Service (Active Directory)
- Direct Connect (secure connection to on-premises)
- VPN (remote employee access)
- Storage Gateway (hybrid storage)
- Organizations (manage multiple accounts)
- SSO (single sign-on)

### IoT Application
**Architecture:**
- IoT Core (connect devices)
- Kinesis (stream device data)
- Lambda (process data)
- DynamoDB (store device states)
- S3 (long-term storage)
- QuickSight (analytics dashboard)
- SNS (alerts for anomalies)

### Machine Learning Pipeline
**Architecture:**
- S3 (training data storage)
- SageMaker (train and deploy models)
- Lambda (inference endpoint)
- API Gateway (expose ML API)
- Kinesis (real-time predictions)
- CloudWatch (monitor model performance)

---

[< Acronym Master List](21-acronym-master-list.md) | [Back to README](README.md) | [Final Exam Day Tips >](23-final-exam-day-tips.md)
