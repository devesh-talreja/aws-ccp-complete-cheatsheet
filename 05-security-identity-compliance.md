## 5. SECURITY, IDENTITY & COMPLIANCE

### IAM (Identity and Access Management)
**What:** Manage access to AWS services
**Real-life:** Like a security badge system for your office
**Key Components:**
- **Users:** Individual people
- **Groups:** Collection of users
- **Roles:** Permissions for AWS services
- **Policies:** JSON documents defining permissions
**Key Points:**
- Global service (not region-specific)
- Principle of Least Privilege
- MFA (Multi-Factor Authentication) recommended
- **Memory Trick:** "IAM = I Am Me = Identity management"

### Organizations
**What:** Manage multiple AWS accounts
**Real-life:** Like a corporate structure with parent company and subsidiaries
**Key Points:**
- Consolidated billing
- Service Control Policies (SCPs)
- **Memory Trick:** "Organizations = Organize multiple accounts"

### Cognito
**What:** User authentication for applications
**Real-life:** Like a login system for your mobile app
**Key Points:**
- User pools and identity pools
- Social identity providers (Google, Facebook)
- **Memory Trick:** "Cognito = Recognize users = Authentication"

### Secrets Manager
**What:** Store and rotate secrets (passwords, API keys)
**Real-life:** Like a secure vault for sensitive information
**Key Points:**
- Automatic rotation
- Encrypted storage
**Memory Trick:** "Secrets Manager = Manages secrets securely"

### AWS Artifact
**What:** Access compliance reports and agreements
**Real-life:** Like a filing cabinet for compliance documents
**Key Points:**
- SOC reports, PCI reports
- AWS agreements
**Memory Trick:** "Artifact = Archive of facts = Compliance docs"

### GuardDuty
**What:** Threat detection service
**Real-life:** Like a security guard monitoring for suspicious activity
**Key Points:**
- Uses machine learning
- Monitors VPC Flow Logs, CloudTrail, DNS logs
**Memory Trick:** "GuardDuty = Guard on duty = Threat detection"

### Inspector
**What:** Automated security assessment for EC2 and ECR
**Real-life:** Like a building inspector checking for vulnerabilities
**Memory Trick:** "Inspector = Inspects for vulnerabilities"

### WAF (Web Application Firewall)
**What:** Protects web applications from common exploits
**Real-life:** Like a bouncer at a nightclub checking IDs
**Key Points:**
- Protects against SQL injection, XSS
- Works with CloudFront, ALB, API Gateway
**Memory Trick:** "WAF = Web Application Filter = Blocks bad requests"

### Shield
**What:** DDoS protection
**Two Tiers:**
- **Shield Standard:** Free, automatic
- **Shield Advanced:** Paid, 24/7 DDoS response team
**Memory Trick:** "Shield = Protects from DDoS attacks"

### KMS (Key Management Service)
**What:** Manage encryption keys
**Real-life:** Like a master key system for your building
**Key Points:**
- Create and control keys
- Integrated with many AWS services
**Memory Trick:** "KMS = Key Management = Encryption keys"

### CloudHSM
**What:** Hardware Security Module for cryptographic operations
**Real-life:** Like having a physical safe for your most sensitive keys
**Key Points:**
- Dedicated hardware
- Meet compliance requirements
**Memory Trick:** "HSM = Hardware Security = Physical device"

---
---

<p align="center">
  [< Networking & Content Delivery](04-networking-content-delivery.md) | [Back to README](README.md) | [Management & Governance >](06-management-governance.md)
</p>
