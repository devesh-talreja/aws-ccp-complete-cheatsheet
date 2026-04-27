## KEY COMPARISONS TO AVOID CONFUSION

### EC2 vs Lambda
- **EC2:** Full control, always running, you manage scaling
- **Lambda:** Serverless, runs on demand, auto-scales, 15-min limit
- **Use EC2 for:** Long-running applications, specific OS needs
- **Use Lambda for:** Event-driven, short tasks, unpredictable traffic

### S3 vs EBS vs EFS
- **S3:** Object storage, unlimited, accessed via internet, any file type
- **EBS:** Block storage, attached to ONE EC2 in ONE AZ, like a hard drive
- **EFS:** File storage, shared across MULTIPLE EC2s, Linux only, expensive
- **Memory:** S3 = Dropbox, EBS = Hard drive, EFS = Network share

### RDS vs DynamoDB
- **RDS:** SQL databases, structured data, complex queries, ACID transactions
- **DynamoDB:** NoSQL, key-value, flexible schema, millisecond latency
- **Use RDS for:** Traditional applications, complex relationships
- **Use DynamoDB for:** High-scale, simple queries, gaming leaderboards

### Security Groups vs NACLs
- **Security Groups:** Instance-level, STATEFUL (return traffic automatic), ALLOW rules only
- **NACLs:** Subnet-level, STATELESS (must explicitly allow return), ALLOW and DENY rules
- **Memory:** Security Group = Stateful guard at the door, NACL = Stateless border checkpoint

### CloudWatch vs CloudTrail vs Config
- **CloudWatch:** Performance monitoring (CPU, memory), alarms, logs
- **CloudTrail:** Who did what (API calls), audit trail
- **Config:** What changed (resource configuration history), compliance
- **Memory:** Watch = Monitor, Trail = Audit, Config = Configuration tracking

### SNS vs SQS
- **SNS:** Push notifications, one-to-many (pub/sub), immediate delivery
- **SQS:** Queue, one-to-one (producer/consumer), messages wait
- **Memory:** SNS = Notification broadcast, SQS = Queue/line

### VPN vs Direct Connect
- **VPN:** Over internet, encrypted, quick setup, lower cost
- **Direct Connect:** Dedicated physical connection, consistent performance, expensive, longer setup
- **Use VPN for:** Quick hybrid connection, backup
- **Use Direct Connect for:** High throughput, consistent latency

### CloudFront vs Global Accelerator
- **CloudFront:** CDN for content (videos, images, web pages), caching
- **Global Accelerator:** Improve global application performance, TCP/UDP, NO caching
- **Memory:** CloudFront = Content at edge, Global Accelerator = Fast routes (no caching)

### Route 53 Routing Policies
- **Simple:** Single resource, no health checks
- **Weighted:** Distribute traffic by percentage (A/B testing)
- **Latency:** Route to lowest latency region
- **Failover:** Primary/secondary for disaster recovery
- **Geolocation:** Route based on user location
- **Geoproximity:** Route based on resource location with bias

### Storage Classes Decision Tree
1. **Frequently accessed:** S3 Standard
2. **Don't know access pattern:** S3 Intelligent-Tiering
3. **Infrequent but need fast access:** S3 Standard-IA
4. **Archive, rare access:** S3 Glacier
5. **Almost never accessed:** S3 Glacier Deep Archive

---

[< Other Important Services](12-other-important-services.md) | [Back to README](README.md) | [Well-Architected Framework >](14-well-architected-framework.md)
