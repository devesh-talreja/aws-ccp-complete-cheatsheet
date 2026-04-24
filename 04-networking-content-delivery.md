## 4. NETWORKING & CONTENT DELIVERY

### VPC (Virtual Private Cloud)
**What:** Your own isolated network in AWS
**Real-life:** Like your private office building in a shared complex
**Components:**
- **Subnets:** Subdivisions of VPC (Public/Private)
- **Internet Gateway:** Allows internet access
- **NAT Gateway:** Allows private subnet to access internet
- **Route Tables:** Direct traffic
- **Security Groups:** Instance-level firewall (stateful)
- **NACLs:** Subnet-level firewall (stateless)
**Memory Trick:** "VPC = Your Private Castle in the cloud"

### CloudFront
**What:** Content Delivery Network (CDN)
**Real-life:** Like having copies of your store in every neighborhood
**Key Points:**
- Caches content at edge locations worldwide
- Reduces latency
- DDoS protection
- **Memory Trick:** "CloudFront = Content at the Front = Closer to users"

### Route 53
**What:** DNS service
**Real-life:** Like a phone book for the internet
**Key Points:**
- Domain registration
- Health checks and failover
- Various routing policies (Simple, Weighted, Latency, Failover, Geolocation)
- **Memory Trick:** "Route 53 = Routes on port 53 (DNS port)"

### Direct Connect
**What:** Dedicated private connection from on-premises to AWS
**Real-life:** Like having a private tunnel instead of using public roads
**Key Points:**
- Consistent network performance
- Reduced bandwidth costs
- **Memory Trick:** "Direct Connect = Direct private line = Bypass internet"

### VPN (Virtual Private Network)
**What:** Encrypted connection over the internet to AWS
**Real-life:** Like a secure encrypted tunnel through public streets
**Key Points:**
- Uses internet connection
- Site-to-Site VPN or Client VPN
- **Memory Trick:** "VPN = Virtual Private = Encrypted tunnel"

### API Gateway
**What:** Create, publish, and manage APIs
**Real-life:** Like a front desk that handles all visitor requests
**Key Points:**
- RESTful and WebSocket APIs
- Scales automatically
- **Memory Trick:** "API Gateway = Door to your services"

---

---

<p align="center">
  [← prev](03-database-services.md) | [README](README.md) | [next →](05-security-identity-compliance.md)
</p>
